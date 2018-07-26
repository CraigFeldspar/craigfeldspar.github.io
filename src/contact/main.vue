<template>
    <b-row class="content">
    	<b-col class="contact-content">
	    	<b-row style="height: 100%">
				<b-col md=6 class="contact-container-title">
					<div class="contact-title">
						<h1>Contact</h1>
					</div>
				</b-col>
				<b-col md=6 class="contact-container-info">
					<div class="contact-info">
						<h3>Anna Jeziorska</h3>
						50 al. Wojska Polskiego<br>
						Gdansk, POL<br>
						NOT SOPOT YET<br>
						<strong>Phone :</strong> +48 XXX XXX XXX<br>
						<strong>Email :</strong> anna.jeziorska@benek.com
					</div>
				</b-col>
			</b-row>
		</b-col>
	</b-row>
</template>

<script>

export default {
  data () {
    return {	
    }
  },
  methods: {
  	
  }
}
</script>

<style>
.contact-content {
	background-color: rgba(255, 255, 255, 0.8);
	margin: 15px;
    min-height: calc(100vh - 190px);
}
.contact-container-info {
	text-align: right;
	background-color: rgba(210, 210 ,255, 0.8);
	height: 100%;
}
.contact-info {
	line-height: 2em;
	margin: 15px;
	margin-top: 50px;
}
.contact-title h1 {
	padding-left: 30px;
	padding-top: 30px;
	font-size: 3em;
}
</style>