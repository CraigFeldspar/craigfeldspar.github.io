<template>
	<b-row class="nav" align-v="end">
	    <b-col offset-lg="1" lg="6" md="6" class="main-title">
	    	<div id="anna">Anna</div>
	    	<div id="jeziorska">Jeziorska</div>
	 	</b-col>
	    <b-col md class="custom-button"><span class="align-bottom" v-on:click="$emit('change-view', 'landing')">About me</span></b-col>
	    <b-col md class="custom-button"><span class="align-bottom" v-on:click="$emit('change-view', 'projects')">Projects</span></b-col>
	    <b-col md class="custom-button"><span class="align-bottom" v-on:click="$emit('change-view', 'contact')">Contact</span></b-col>
	</b-row>
</template>

<style>
	#anna {
		height: 1em;
	}
	#jeziorska {
		color: orange;
	}
	.main-title {
		font-size: 4em;
		padding-left: 50px;
	}
	.nav {
		background: linear-gradient(to right, rgba(255,255,255,1) 0%,rgba(255,255,255,0.7) 100%);
		/*height: 150px;*/
	}
	.custom-button {
		font-size: 1.5em;
		/*line-height: 150px;*/
		width: 150px;
		text-align: center;
		vertical-align: text-bottom;
		color: black;
		padding-bottom: 10px;
		font-family: 'Poppins', sans-serif;
		cursor: pointer;
		transition: all 0.3s;
	}

	.custom-button:hover {
		color: rgb(56, 56, 56);
		background-color: rgba(0, 0, 0, 0.2);
	}
</style>