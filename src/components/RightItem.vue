<template>
	<div>
		<div>
			<p class="sum_text">累计收到赞赏</p>
			<p class="sum_number">{{number}}积分</p>
		</div>

		<div class="blog" style="top: 82px;">
			<div style="height: 36px;width: auto;">
				<div class="head_picture">
					<img src="../assets/headpic.jpg" style="max-width: 100%;max-height: 100%; align:absmiddle" />
				</div>
				<p class="author" style="top: 31px;">玉米粒</p>
				<p class="blog_title" style="top: 27px;">打赏了你的文章《{{blog1.essay}}》</p>
				<p class="league" style="top:28px;">{{blog1.league}}积分</p>
			</div>
			<div class="content">
				<p class="content_text">{{blog1.content}}</p>
			</div>
			<div style="margin-top: 13px;">
				<p class="time">{{blog1.time}}</p>
			</div>			
		</div>

		<div class="blog" style="top: 265px;">
			<div style="height: 36px;width: auto;">
				<div class="head_picture">
					<img src="../assets/headpic.jpg" style="max-width: 100%;max-height: 100%; align:absmiddle" />
				</div>
				<p class="author">玉米粒</p>
				<p class="blog_title">打赏了你的文章《{{blog2.essay}}》</p>
				<p class="league">{{blog2.league}}积分</p>
			</div>
			<div class="content">
				<p class="content_text">{{blog2.content}}</p>
			</div>
			<div style="margin-top: 13px;">
				<p class="time">{{blog2.time}}</p>
			</div>
		</div>

		<div class="blog" style="top: 448px;">
			<div style="height: 36px;width: auto;">
				<div class="head_picture">
					<img src="../assets/headpic.jpg" style="max-width: 100%;max-height: 100%; align:absmiddle" />
				</div>
				<p class="author">玉米粒</p>
				<p class="blog_title">打赏了你的文章《{{blog3.essay}}》</p>
				<p class="league">{{blog3.league}}积分</p>
			</div>
			<div class="content">
				<p class="content_text">{{blog3.content}}</p>
			</div>
			<div style="margin-top: 13px;">
				<p class="time">{{blog3.time}}</p>
			</div>
		</div>

		<div class="blog" style="top: 631px;">
			<div style="height: 36px;width: auto;">
				<div class="head_picture">
					<img src="../assets/headpic.jpg" style="max-width: 100%;max-height: 100%; align:absmiddle" />
				</div>
				<p class="author">玉米粒</p>
				<p class="blog_title">打赏了你的文章《{{blog4.essay}}》</p>
				<p class="league">{{blog4.league}}积分</p>
			</div>
			<div class="content">
				<p class="content_text">{{blog4.content}}</p>
			</div>
			<div style="margin-top: 13px;">
				<p class="time">{{blog4.time}}</p>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				number: "200",
				blog1: {
					essay: "代码质量管理工具：SonarQube常见的问题及正确解决方案",
					league: "30",
					content: "好文章，写的太好了，期待博主更新！",
					time: "2019-09-11 09:00"
				},
				blog2: {
					essay: "快速上手麒麟EasyDL专业版·物体检测模型（附代码）",
					league: "50",
					content: "好文章，写的太好了，期待博主更新！",
					time: "2019-09-11 09:00"
				},
				blog3: {
					essay: "图解kubernetes中etcd增删改查的工业实现",
					league: "20",
					content: "好文章，写的太好了，期待博主更新！",
					time: "2019-09-11 09:00"
				},
				blog4: {
					essay: "打赏了你的文章《PGET，一个简单、易用的并行调用框架",
					league: "20",
					content: "好文章，写的太好了，期待博主更新！",
					time: "2019-09-11 09:00"
				}
			}
		}
	}
</script>

<style scoped="scoped">
	.sum_text {
		width: 84px;
		height: 20px;
		font-size: 14px;
		font-family: PingFangSC-Regular, PingFang SC;
		font-weight: 400;
		color: #303030;
		line-height: 20px;
		position: absolute;
		left: 664px;
		top: 40px;
	}

	.sum_number {
		width: 54px;
		height: 20px;
		font-size: 14px;
		font-family: PingFangSC-Semibold, PingFang SC;
		font-weight: 600;
		color: #0BBA6E;
		line-height: 20px;
		position: absolute;
		left: 755px;
		top: 40px;
	}

	.blog {
		width: 906px;
		height: 173px;
		background: #FFFFFF;
		position: absolute;
		left: 654px;
		padding: 16px 20px;
	}

	.head_picture {
		display: inline-block;
		width: 36px;
		height: 36px;
		border-radius: 50%;
		overflow: hidden;
		align-items: auto;
	}

	.author {
		width: 44px;
		height: 14px;
		font-size: 14px;
		font-family: PingFangSC-Regular, PingFang SC;
		font-weight: 400;
		color: #7B8F9A;
		line-height: 14px;
		position: absolute;
		left: 66px;
		top: 31px;
	}

	.blog_title {
		width: 565px;
		height: 22px;
		font-size: 16px;
		font-family: PingFangSC-Semibold, PingFang SC;
		font-weight: 600;
		color: #303030;
		line-height: 22px;
		position: absolute;
		left: 120px;
		top: 27px;
	}

	.league {
		width: 45px;
		height: 20px;
		font-size: 14px;
		font-family: PingFangSC-Semibold, PingFang SC;
		font-weight: 600;
		color: #0BBA6E;
		line-height: 20px;
		position: absolute;
		left: 841px;
		top:28px;
	}

	.content {
		width: 866px;
		height: 58px;
		background: #F7F9FB;
		border-radius: 2px;
		margin-top: 14px;
		padding-top: 6px;
		padding-left: 15px;
	}
	.content_text{
		height: 20px;
		font-size: 14px;
		font-family: PingFangSC-Regular, PingFang SC;
		font-weight: 400;
		color: #4D4D4D;
		line-height: 20px;
	}
	.time{
		height: 16px;
		font-size: 12px;
		font-family: PingFangSC-Regular, PingFang SC;
		font-weight: 400;
		color: #7B8F9A;
		line-height: 16px;
		margin-top: 13px;
	}
</style>
