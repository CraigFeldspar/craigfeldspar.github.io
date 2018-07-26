<template>
    <b-row class="content" align-v="center">
    	<b-col lg="6" class="slideshow-container">
    		<div class="slideshow">
    			<div class="slideshow-title">Why I'm the greatest architect <br>in da world
    			</div>
    			<div class="slideshow-text">
    				...Because I build all kind of stairs<br>
    				...Because my roofs have never collapsed before<br>
    				...Because I eat concrete for dessert<br>
    				...Because 1/4 = 1/5<br>
    			</div>
    		</div>
    	</b-col>
    	<b-col lg=6 class="projects-container">
    		<b-row>
    			<project-image :imagePath="image1" :shortText='"Wow !! Amazing project !!"'></project-image>
    			<project-image :imagePath="image2" :shortText='"Benek is really da beast"'></project-image>
    			<project-image :imagePath="image3" :shortText='"I cant believe this is a building"'></project-image>
    			<project-image :imagePath="image4" :shortText='"Look at this shit"'></project-image>
    		</b-row>
    	</b-col>
    </b-row>
</template>

<script>
import image1 from "./1.jpg";
import image2 from "./2.jpg";
import image3 from "./3.jpg";
import image4 from "./4.jpg";
import ProjectImage from "../hd-image/main.vue";

export default {
  data () {
    return {
        image1: image1,
        image2: image2,
        image3: image3,
        image4: image4,
    }
  },
  components: {
    "project-image" : ProjectImage,
  }
}
</script>
<style>
.slideshow {
    min-height: calc(100vh - 190px);
    background: rgba(255,255,255,0.8);
    padding: 25px;
    padding-left: 50px;
}
.slideshow-title {
    margin-top: 30px;
    margin-bottom: 30px;
    font-size: 2em;
    font-weight: bold;
}
.slideshow-text {
    font-size: 1.5em;
    line-height: 2.5em;
    font-family: 'Poppins', sans-serif;
}
</style>
