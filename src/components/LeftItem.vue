<template>
	<div>
		<div>
			<div class="resume">
				<h6>个人简介</h6>
				<Icon type="ios-create-outline" size="17" class="edit" color="#7A8F9A"/>
			</div>
			<div class="intrudction">
				<p>
					杨文昔：毕业于北京大学，具有13年的写作经验，2009年出版文学作品作品作品《春》，2009年出版文学作品作品作品文学作品作品 作品文学作品作品作品文学作品…
				</p>
				<img src="../assets/Shape.png" style="margin-left: 3px;cursor: pointer;"/>
			</div>
		</div>
		<div class="options">
			<Menu active-name="7" width="auto">
				<MenuItem name="1" style="padding: 12px 60px;">
				    浏览记录
				</MenuItem>
				<MenuItem name="2" style="padding: 12px 60px;">
				    我的收藏
				</MenuItem>
				<MenuItem name="3" style="padding: 12px 60px;">
				    我的问答
				</MenuItem>
				<MenuItem name="4" style="padding: 12px 60px;">
				    我的圈子
				</MenuItem>
				<MenuItem name="5" style="padding: 12px 60px;">
				    我的小册
				</MenuItem>
				<MenuItem name="6" style="padding: 12px 60px;">
				    我的博客
				</MenuItem>
				<MenuItem name="7" style="padding: 12px 60px;">
				    我收到的赞赏
				</MenuItem>
			</Menu>
		</div>
	</div>
</template>

<script>
</script>

<style>
	.resume{
		background: url(../assets/personal_back.png);
		position: absolute;
		left: 360px;
		top: 23px;
		width: 274px;
		height: 66px;
	}
	
	h6{
		position: absolute;
		top: 24px;
		left: 27px;
		width: 56px;
		height: 20px;
		font-size: 14px;
		font-family: PingFangSC-Medium, PingFang SC;
		font-weight: 500;
		color: #4D4D4D;
		line-height: 20px;
	}
	
	.edit{
		position: absolute;
		left: 95px;
		top: 26px;
	}
	
	.intrudction{
		position: absolute;
		left: 360px;
		top: 88px;
		background-color: #ffffff;
		width: 274px;
		height: 136px;
		padding: 20px 1px 20px 20px;
	}
	p{
		display: inline;
		width: 253px;
		height: 96px;
		font-size: 12px;
		font-family: PingFangSC-Regular, PingFang SC;
		font-weight: 400;
		color: #4D4D4D;
		line-height: 24px;
	}
	
	.options{
		position: absolute;
		left: 360px;
		top: 242px;
		width: 274px;
		height: 560px;
		background: #FFFFFF;
	}
	
	.ivu-menu-light.ivu-menu-vertical .ivu-menu-item-active:not(.ivu-menu-submenu) {
	    color: #FFFFFF !important;
		background: #0BBA6E !important;
	    z-index: 2;
	}	
</style>
