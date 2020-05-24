<template>
  <div class="bg py-4">
    <b-container>
      <h1>{{ blog.title }}</h1>
      <nuxt-content :document="blog" />
    </b-container>
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const blog = await $content('articles/index').fetch()

    return {
      blog
    }
  }
}
</script>

<style scoped lang="scss">
.nuxt-content {
	color:rgba(19, 18, 13, 1);
  em {
    font-size: 14px;
  }
  p {
    font-size: 20px;
  }
  img {
    max-width: 900px;
    height: 500px;
    object-fit: cover;
    border-radius: 6px;
  }
	li{
		font-size:13px;
	}
	.code-img{
		width:100%;
		height:100%;
		object-fit: contain;
	}
	a{
		color:rgba(141, 20, 14, 1);
	}
}
</style>
