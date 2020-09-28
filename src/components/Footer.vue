<template>
	<div class="devide_position">
		<ul class="ivu-page">
			<li class="ivu-page-prev ivu-page-custom-text" title="首页">
				<a>首页</a>
			</li>
			<li class="ivu-page-prev ivu-page-custom-text" title="上一页">
				<a>上一页</a>
			</li>
			<li class="ivu-page-item" title="1">
				<a>1</a>
			</li>
			<li class="ivu-page-item" title="2">
				<a>2</a>
			</li>
			<li class="ivu-page-item" title="3">
				<a>3</a>
			</li>
			<li class="ivu-page-item ivu-page-item-active" title="4">
				<a>4</a>
			</li>
			<li class="ivu-page-item" title="5">
				<a>5</a>
			</li>
			<li class="ivu-page-item" title="6">
				<a>6</a>
			</li>
			<li class="ivu-page-item" title="7">
				<a>7</a>
			</li>
			<li class="ivu-page-next ivu-page-custom-text" title="下一页">
				<a>下一页</a>
			</li>
			<li class="ivu-page-next ivu-page-custom-text" title="尾页">
				<a>尾页</a>
			</li>
		</ul>
	</div>
</template>

<script>
</script>

<style>
	.devide_position{
		position: absolute;
		left: 829px;
		top: 839px;
		height: 30px;
		align-content: center;
	}
	.ivu-page-prev,.ivu-page-next{
		color: #4D4D4D !important;
		background-color: transparent !important;
		font-size: 14px !important;
		margin-left: 30px;
	}
	.ivu-page-item{
		color: #4D4D4D !important;
		background-color: transparent !important;
		font-size: 14px !important;
		border-radius: 50% !important;
		border: none !important;
		overflow: hidden !important;
		margin-left: 9px;
	}
	.ivu-page-item-active{
		background-color: #0BBA6E !important;
		color: #FFFFFF !important;
	}
	.ivu-page-item-active a, .ivu-page-item-active:hover a {
	    color: #FFFFFF !important;
	}
</style>
