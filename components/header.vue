<template>
	<nav>
		<ul class="px-4 py-2">
			<li>
				<a href="https://david-aji.com/">
					Home
				</a>
			</li>
			<li>
				<nuxt-link to="/">
					Blog
				</nuxt-link>
			</li>
			<li>
				<a href="http://github.com/Ajiva-D" target="_blank" rel="noopener noreferrer">Github</a>
			</li>
		</ul>
	</nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
nav{
	ul{
		list-style: none;
		display: flex;
		justify-content:flex-end;
		li{
			font-size:30px;
			margin:0 10px;
			a{
				color:rgba(141, 20, 14, 1);
				&:hover{
					color:rgba(19, 18, 13, 1);
				}
			}
		}
	}
}
</style>