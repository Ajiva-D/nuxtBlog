<template>
  <div>
		<Header/>
    <nuxt />
		<Footer/>
  </div>
</template>

<script>
import Header from '../components/header'
import Footer from '../components/footer'
export default {
	components:{
		Header,
		Footer
	}
}
</script>
<style lang="scss">
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
body{
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
	background-color: rgba(239, 238, 235, 1);
}
.bg{
	background-color: rgba(239, 238, 235, 1);
	min-height: 100vh;
}
img{
	width:100%;
	object-fit: contain;
}
</style>
