<template>
    <div class="projects-wrapper">
        <b-row class="projects-section" no-gutters>
        	<b-col lg="6" class="projects-section-image">
                <img :src="image1" />
        	</b-col>
        	<b-col lg="6" class="projects-section-description">
                <h1>Amazing Project</h1>
                <figcaption>In order to make this shit, I had to do several stuff. First i grabbed a pen, then, i fucking put it on the fucking paper. Then, once it was on the paper, i started moving it. I did this for several hours, and then it turned out it was pure shit. So i started again until it was amazing. Now it's fucking amazing, i mean look at this shit. You could have this in all museums. Call the fucking Louvre</figcaption><br>
                <div class="project-postcaption"><cite>made in 2016</cite></div>
            </b-col>
            <b-col lg="6" class="projects-section-description">
                <h1>Shit Project</h1>
                <figcaption>This project is pure shit but it's not mine, so it's fine. Just don"t bother look at it, instead, here is a quote to sound more intelligent :<br />
                <em>Let us sacrifice our today so that our children can have a better tomorrow.</em></figcaption><br>
                <div class="project-postcaption"><cite>made in 2015 by some random dude</cite></div>
            </b-col>
            <b-col lg="6" class="projects-section-image">
                <img :src="image2" />
            </b-col>
            <b-col lg="6" class="projects-section-image">
                <img :src="image3" />
            </b-col>
            <b-col lg="6" class="projects-section-description">
                <h1>Benek</h1>
                <figcaption>BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK BENEK </figcaption><br>
                <div class="project-postcaption"><cite>made in 1989 by Brigitte & JP</cite></div>
            </b-col>
        </b-row>
    </div>
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
.projects-section-image img {
    width: 100%;
}

.projects-section-description {
    text-align: justify;
}

.projects-section-description h1 {
    margin: 30px;
    margin-top: 45px;
}

.projects-section-description figcaption {
    margin: 60px;
    margin-top: 30px;
    margin-bottom: 15px;
}
.project-postcaption {
    text-align: right;
}

.project-postcaption cite {
    margin-right: 30px;
}

.projects-wrapper {
    background-color: rgba(255, 255, 255, 0.8);
    height: 1000px;
    margin-top: 15px;
    font-size: 1.2em;
}
</style>
