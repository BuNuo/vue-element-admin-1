<template>
    <div class="wq-foot  h30 lh30 pl10  bdc bgf0">
      Copyright &copy; {{getYear}} <a target="_blank" href="http://www.cnblogs.com/weiqinl">weiqinl</a>. All rights reserved. 
      <span class="r pr10">
      <a target="_blank" href="https://github.com/weiqinl/vue-element-admin/issues">反馈建议</a>V0.2.0
    </span>
  </div>
</template>
<script type="text/javascript">
	export default {
		computed: {
			getYear() {
				let y = new Date().getFullYear();
				let showY = y;
				if (y > 2017) {
					showY = "2017-" + y;
				}
				return showY;
			}
		}
	}
</script>
