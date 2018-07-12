<template>
	<div class="login">
		<img class="top_img" src="@/assets/pic_logo@3x.png"/>
		<div class="div_int flex_start_v">
			<div class="div_img flex_center">
				<img class="name_img" src="@/assets/icon_touxiang@2x.png"/>
			</div>
			<input type="text" v-model="name" class="int_tex" placeholder="请输入您的用户名"/>
		</div>
		<div class="div_int flex_start_v">
			<div class="div_img flex_center">
				<img class="name_img" src="@/assets/icon_mima@2x.png"/>
			</div>
			<input type="password" v-model="pasword" class="int_tex" placeholder="请输入您的密码"/>
		</div>
		<div class="login_cli" @click="login">
			登录
		</div>
	</div>
</template>

<script>
	export default({
		name:'login',
		data () {
			return {
				name:'',
				pasword:''
			}
		},
		mounted () {
			console.log(222)
		},
		methods: {
			login () {
				alert(1)
			}
		}
	})
</script>

<style scoped>
	.top_img{width: 3.26rem;height: 1.76rem;}
	.login{width: 100%;height: 100%;background: url(../assets/bac_login@2x.png);background-size: 100% 100%; text-align: center;}
	.top_img{margin-top:.92rem;margin-bottom: .6rem;}
	.div_int{width: 6.5rem; height: .88rem;background: #fff;margin: 0 auto .5rem auto;max-width: 100%;overflow: hidden;}
	.div_img{width: .88rem;height: .88rem;background: #F0F0F0;}
	.name_img{width: .32rem;height: .4rem;}
	.int_tex{width: 5.62rem; height: 100%;border: 0;background: #fff;padding: 0 .16rem;}
	.login_cli{background: #005BAB;border-radius: 4px;color: #fff;width: 6.5rem;height: .88rem;line-height: .88rem; text-align: center;margin: auto;margin-top: .8rem;}
</style>