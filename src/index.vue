<template>
<b-container fluid> 
    <b-row class="nav">
        <b-col cols="12" offset-lg="1" lg="6" md="6" class="main-title">Anna Jeziorska</b-col>
        <b-col sm class="custom-button">Contact</b-col>
        <b-col sm class="custom-button">Projects</b-col>
        <b-col sm class="custom-button">Blog</b-col>
    </b-row>
</b-container>
</template>

<script>

export default {
  data () {
    return {
    }
  }
}
</script>

<style>
.main-title {
	font-size: 3em;
	padding-left: 50px;
}
.nav {
	height: 90px;
	background: linear-gradient(to right, rgba(255,255,255,1) 0%,rgba(255,255,255,0) 100%);
}
.custom-button {
	font-size: 2em;
	line-height: 90px;
	width: 150px;
	text-align: center;
	color: white;
}
body {
	background-image: url(./background.jpg);
	background-repeat: no-repeat;
	background-size: 100%;
}
</style>