<template>
	<div class="backPic">
		<img src="../assets/CEC-greatwall.png" class="logo" />
		<p class="first_text logo_name">PK生态服务平台</p>
		<a class="first_text" style="width: 28px;left: 676px;">首页</a>
		<a class="first_text" style="width: 42px;left: 744px;">云计算</a>
		<a class="first_text" style="width: 28px;left: 826px;">方案</a>
		<a class="first_text" style="width: 28px;left: 894px;">学院</a>
		<a class="first_text" style="width: 56px;left: 962px;">兼容中心</a>
		<a class="first_text" style="width: 56px;left: 1058px;">企业联盟</a>
		<a class="first_text" style="width: 56px;left: 1154px;">关于我们</a>
		<div class="small_picture">
			<img src="../assets/head_picture.png" style="max-width: 100%;max-height: 100;"/>
		</div>
		<Dropdown placement="bottom-start" class="arrow_down">
			<a href="javascript:void(0)">
				聂芳华
				<Icon type="ios-arrow-down"></Icon>
			</a>
		</Dropdown>
		<Dropdown placement="bottom-start" class="arrow_down" style="left: 1517px;">
			<a href="javascript:void(0)">
				费用
				<Icon type="ios-arrow-down"></Icon>
			</a>
		</Dropdown>
		<img src="../assets/head_picture.png" class="big_picture"/>
		<p class="name">{{name}}</p>
		<div class="sex_icon">
			<img src="../assets/female.png" />
		</div>
		<p class="first_text person">{{job}} | {{city}}</p>
		<p class="number" style="left: 835px;width: 44px;">326</p>
		<p class="number" style="left: 949px;width: 29px;">46</p>
		<p class="number" style="left: 1048px;width: 29px;">58</p>
		<p class="first_text" style="left: 843px;top: 293px;">星币</p>
		<p class="first_text" style="left: 950px;top: 293px;">关注</p>
		<p class="first_text" style="left: 1049px;top: 293px;">粉丝</p>
	</div>
</template>

<script>
	export default{
		data(){
			return{
				name:"杨文昔",
				job:"著名作家、摄影师、茶艺师 ",
				city:" 长沙"
			}
		}
	}
</script>

<style scoped>
	.backPic {
		width: 1920px;
		height: 330px;
		background: url(../assets/top-back.png);
		position: absolute;
		left: 0px;
		top: 0px;
	}

	.logo {
		position: absolute;
		left: 360px;
		top: 16px;
		width: 137.72px;
		height: 29.08px;
	}

	p,a{
		font-family: PingFangSC-Medium, PingFang SC;
		color: #FFFFFF;
	}
	a:hover{
		font-weight: bold;
		color: #FFFFFF;
	}
	
	.first_text {
		position: absolute;
		top: 20px;
		height: 20px;
		font-size: 14px;
		line-height: 20px;
		font-weight: 400;
	}

	.logo_name {
		left: 510px;
		width: 104px;		
		font-weight: 500;
	}
	
	.arrow_down {
		left: 1439px;
		top: 22px;
		position: absolute;
		font-size: 12px;
	}
	
	.small_picture{
		position: absolute;
		left: 1389.73px;
		top: 12.73px;
		width: 34.55px;
		height: 34.55px;
		border-radius: 50%;
		overflow: hidden;
	}
	
	.big_picture{
		position: absolute;
		left: 921.42px;
		top: 85.42px;
	}
	
	.name{
		position: absolute;
		left: 922px;
		top: 173px;
		width: 72px;
		height: 33px;
		font-size: 24px;
		font-weight: 400;
		line-height: 33px;
	}
	
	.sex_icon{
		position: absolute;
		left: 1000px;
		top: 176px;
		width: 27px;
		height: 27px;
		border-radius: 50%;
		overflow: hidden;
		background-color: #FFB9C6;
		/* 设置div内的图片居中 */
		display: flex;
		justify-content: center;
		align-items: center;
	}
	
	.person{
		width: 223px;
		left: 848px;
		top: 216px;
	}
	
	.number{
		position: absolute;
		top: 253px;
		height: 33px;
		font-size: 24px;
		font-weight: 500;
		line-height: 33px;

	}
</style>
