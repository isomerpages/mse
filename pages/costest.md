---
title: COS Test Page
permalink: /costest
---

<style>

/*--------------------------------------------------------------
STYLING FOR INTRO
--------------------------------------------------------------*/
 
.img-icon {
 max-width: 90% !important;
margin-top: 10px !important;
}

.mse50-logo {
 max-width: 75% !important;
 }
 
.column {
  float: left;
  width: 33%;
  margin: 5px;
}

.icon-desc {
 line-height: 1.5rem !important;
 margin: 10px 0px !important;
 }
 
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
 
@media screen and (max-width: 600px) {
  .column {
    width: 75%;
    margin-left: 12.5%;
  }
}

/*--------------------------------------------------------------
STYLING FOR TIMELINE
--------------------------------------------------------------*/
 
 *,
*:after, 
*:before {
-webkit-box-sizing: border-box; 
-moz-box-sizing: border-box; 
box-sizing: border-box;}

.container {
  margin: 50px auto;
  max-width: 1600px;
  padding: 30px 20px;

  position: relative;
}

.content img {
  max-width: 100%;
  margin-bottom: 10px
}
  
a {
  text-decoration: none;
}
  
.clearfix:after {
  content: " ";
  display: table;
  clear: both;
} 

@media (min-width: 768px) {
  .vertical-line::after {
    top: -10px;
    right: 50%;
    background-color: #a6a6a6;
    overflow: hidden;
    position: absolute;
    content: "";
    display: block;
    height: 10px;
    width: 10px;
    border-radius: 50%;
    margin-right: -5px;
  }
  .vertical-line::before {
    top: -10px;
    right: 50%;
    background-color: #a6a6a6;
    overflow: hidden;
    position: absolute;
    content: "";
    display: block;
    height: 100%;
    width: 2px;
    margin-right: -2px;
  }
  .vesti-date-wrapper::before {
    top: 50%;
    background-color: #a6a6a6;
    overflow: hidden;
    position: absolute;
    content: "";
    display: block;
    height: 2px;
    width: 100%;
    margin-top: -2px;
    z-index: -10;
  }
}
.vesti-col {
  width: 100%;
}

.timeline-post {
  position: relative;
}

.timeline-post:nth-child(odd) {
  margin-top: 20px;
}

.timeline-post:nth-child(even) {
  margin-bottom: 15px;
  margin-top: 100px;
}

.photo {
  position: relative;
}
/*Vesti date*/

.vesti-date-wrapper {
  position: absolute;
  right: 50%;
  margin-right: -25px;
  bottom: -25px;
}

.vesti-date-wrapper .vesti-date {
  width: 50px;
  height: 50px;
  text-align: center;
  background: #fff;
  padding-top: 14px;
  margin-bottom: 5px;
  border-width: 2px;
  border-style: solid;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  border-color: #a6a6a6;
}

/* .vesti-date-wrapper .vesti-date .date {
  font-size: 1em;
  text-align: center;
  color: #2d3e4f;
  line-height: 0px;
  display: block;
} */

.vesti-date-wrapper .vesti-date .year {
  font-size: 1em;
  text-align: center;
  color: #2d3e4f;
  line-height: 15px;
  display: block;
  text-transform: uppercase;
}

.timeline-post:nth-child(2n+3) {
  clear: both;
}

.timeline-post:nth-child(odd) .vesti-date-wrapper .vesti-date {
  float: right;
}

.timeline-post:nth-child(even) {
  /*float: right;*/
  margin-bottom: 15px;
  margin-top: 20px;
}

.timeline-post:nth-child(even) .vesti-date-wrapper {
  bottom: -25px;
  right: 50%;
  margin-right: -25px;
}

/*Vesti typography*/

.vesti-desc {
  text-align: center;
}

.vesti-desc h2 {
  color: #2d3e4f;
  text-transform: uppercase;
  font-size: 1.2em;
  font-weight: 800;
  margin-top: 28px !important;
  margin-bottom: 15px;
  transition-delay: 0s;
  transition-duration: 0.2s;
  transition-property: all;
  transition-timing-function: ease-out;
  line-height: 1.5rem;
}

.owl-item .vesti-desc h2 {
  margin-top: 50px;
}

.vesti-desc h2:hover {
  color: #00b388 !important;
}

.vesti-desc p {
  color: #2d3e4f;
  font-size: 16px !important;
  font-weight: 400;
  line-height: 1.2rem;
  margin-top: 10px;
  margin-bottom: 12px !important;
}

@media (min-width: 768px) {
  #section_2 .owl-item {
    padding: 0 20px;
  }
  .post-type-archive-vesti .container {
    max-width: 1600px;
  }
  .archive .site-content {
    margin-top: 100px;
  }
  .vesti-col {
    width: 43%;
  }
  .timeline {
    margin-top: 20px;
    margin-bottom: 50px;
    padding-top: 20px;
  }
  .vesti-date-wrapper {
    position: absolute;
    right: 150px;
    margin-right: 0px;
    bottom: auto;
  }
  .timeline-post:nth-child(odd) {
    float: left;
    margin-top: 0;
  }
  .timeline-post:nth-child(even) {
    float: right;
    margin-bottom: 15px;
    margin-top: 50px;
  }
  .vesti-desc h2 {
    margin-bottom: 15px;
    margin-top: 20px;
    font-size: 20px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -75px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -75px;
    bottom: 15px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 77px;
  }
}

@media (min-width: 850px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -80px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -80px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 85px;
  }
}
  
  @media (min-width: 920px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -87px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -87px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 85px;
  }
}

@media (min-width: 1023px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -65px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -65px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 95px;
  }
}

@media (min-width: 1100px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -65px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -65px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 100px;
  }
}
  
@media (min-width: 1200px) {

  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -70px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -70px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 132px;
  }
  .owl-item .vesti-desc h2 {
    margin-top: 75px;
  }
}

  @media (min-width: 1280px) {
  
  /*  .timeline {
    margin-top: 40px;
  }*/
  .timeline-post:nth-child(even) {
    margin-top: 100px;
  }
  .vesti-date-wrapper .vesti-date {
    width: 88px;
    height: 88px;
    padding: 18px;
  }

  .vesti-date-wrapper .vesti-date .year {
    font-size: 1em;
    line-height: 50px;
  }
  
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -102px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -102px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 140px;
  }
}

@media (min-width: 1400px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -102px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -102px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 146px;
  }
}

@media (min-width: 1500px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -100px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -100px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 155px;
  }
}

@media (min-width: 1600px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -100px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -100px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 160px;
  }
}
/*--------------------------------------------------------------
STYLING FOR BUTTONS
--------------------------------------------------------------*/
 
.button {
  cursor: pointer;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  font: inherit;
  border: none;
  position: relative;
  transition: 300ms ease;
  color: #484848 !important;
  text-transform: uppercase;
  background: #ffffff;
  padding: 15px 20px;
  border: 2px solid #484848;
  display: inline-block;
  transition: all 0.4s ease 0s;
  border-radius: 15px;
  font-weight: bold;
  text-decoration: none !important;
  font-size:0.9em;
}
.button:before {
  transition: 300ms ease;
  position: absolute;
  display: block;
  content: "";
  transform: translateZ(-40px);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  height: calc(100% - 20px);
  width: calc(100% - 20px);
  border-radius: 100px;
  left: 10px;
  top: 16px;
}
.button:hover {
  transform: translateZ(55px);
  color: #ffffff !important;
  background: #4a96b0;
  border-color: #4a96b0 !important;
  transition: all 0.4s ease 0s;
  text-decoration: none;
}
.button:hover:before {
  transform: translateZ(-45px);
}
.button:active {
  transform: translateZ(20px);
}
.button:active:before {
  transform: translateZ(-20px);
  top: 10px;
}
	
/*--------------------------------------------------------------
STYLING FOR CARDS - ADDITIONAL RESOURCES
--------------------------------------------------------------*/
	
#resources-container > div > div > a > img {
    display: block;
    border: 0;
    max-width: 180px;
    max-height: auto;
    padding: 1em;
    border-radius: 15px 15px 0px 0px;
}

.card {
    flex: 1 0 500px;
    box-sizing: border-box;
    margin: 1em 0.5em;
    background: white;
    margin-bottom: 1em;
    border: 0.13em solid rgba(0,0,0,.1);
    border-radius: 15px;
    /* box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3); */
}

.card a {
    color: inherit;
    text-decoration: none; /* no underline */
}

.card p,
.card-content h5 {
    padding: 1em;
    margin-top: 0.5em;
    margin-bottom: .5em;
    /* font-weight: bold; */
    color: inherit;
    text-decoration: none;
}

.card:hover {
    transition: all 0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    top: -4px;
    border: 2px solid #cccccc;
    background-color: white;
}

.card a:hover {
    color: black;
    text-decoration: none; /* no underline */
}

/* Flexbox stuff */

.cards {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
    /* padding: 0 1em; */
    text-align: center;
 }

@media screen and (min-width: 40em) {
  .card {
    max-width: calc(50% -  1em);
  }
}

@media screen and (min-width: 60em) {
  .card {
    max-width: calc(33% - 1em);
  }
}

@media screen and (max-width : 480px) {
	.card { 
    max-width: 100%; }
}
 
</style>

<img src="images/mse50/MSE50_Hori_Dark_RGB.png" alt="MSE50" class="mse50-logo"><br>
<p><b>2022 marks the Ministry of Sustainability and the Environment's 50th Anniversary (MSE50).</b></p>

<p>Singapore has come a long way since the inception of the ministry in 1972. We were one of the first countries in the world to form a ministry of the environment to tackle issues such as pollution control, sewerage, drainage and environmental health.</p>

<p>Even before sustainable development became a global concern, Singapore sought to balance environmental protection with economic growth and social inclusion.</p>

<p>The Ministry of Sustainability and the Environment will be commemorating this Golden Jubilee with a series of meaningful activities to celebrate Singapore’s environmental milestones  and renew our commitment to build a green and resilient Singapore.</p>

<p>We look forward to celebrating not only with past and present staff but also with our partners from the people, private and public sectors, and the generations of Singaporeans who have been part of our sustainable development journey over the last five decades.</p>

	
<div>
<center>
	  <a class="button" href="/resource-room/category/2022-09-15-media-release-on-tree-planting-ceremony" target="_blank">Press Release</a>&nbsp; <a class="button" href="/resource-room/category/2022-09-15-speech-by-minister-grace-fu-at-mse50-tree-planting/" target="_blank">MSE 50th Anniversary Tree Planting Event</a>&nbsp;
</center>
</div>
   <img src="images/mse50/treeplanting.jpg" class="img-icon" alt="MSE50">
  <center> Check out photos of the <a href="https://www.facebook.com/MSEsingapore/posts/pfbid015pc4aFT5mrxaXvhBNwJpRoyXhBQby7hNpPy5krHYK4JaUAMufDfWX2GQ8xDdSAml">MSE50 Tree Planting Event</a>!</center>
  
  <hr> 
  

<h1>Our milestones</h1>

<p>Take a look back in time as we trace our environmental milestones over the past five decades.</p>
<div class="row">
 <div class="column">
 <img src="images/mse50/m4.jpg" class="img-icon" alt="MSE50"><br>
  <p class="icon-desc">Singapore River Clean Up<br></p>
 </div>
 <div class="column">
 <img src="images/mse50/m9.jpg" class="img-icon" alt="MSE50"><br>
  <p class="icon-desc">Street Hawkers Resettlement<br></p>
 </div>
 <div class="column">
 <img src="images/mse50/m12.jpg" class="img-icon" alt="MSE50"><br>
  <p class="icon-desc">Phasing out of night-soil bucket<br></p>
 </div>
</div>


<div>
<center>
	  <a class="button" href="/mse50milestones">Full list of milestones</a>&nbsp; <a class="button" href="https://www.facebook.com/hashtag/mse50" target="_blank">Social Media Highlights</a>&nbsp;  <a class="button" href="https://www.straitstimes.com/singapore/environment/mse-from-newater-to-vertical-farming-key-milestones-singapore-50-year-journey-towards-sustainability" target="_blank">Digital Advertorial</a>&nbsp;
</center>
</div>  
  
 
 <hr>



<h1>Our stories</h1>

<p><strong>I Remember - an MSE50 Short Film</strong></p>
<p>Take a trip down memory lane in this short film as we re-live the days of street hawkers in 1970s, where a chance encounter between a young lady and a strange boy triggers off reflections about our sustainable habits and how they have carried on till today.</p>

<iframe src="https://www.youtube.com/embed/ksnmTNMwvhM" width="620" height="380" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<p></p>

<p><strong>#50YearsOfSustainability - Crowdsourcing for your environment stories</strong></p>
<p>Got a story or memory of what Singapore’s environment used to be like when you were growing up? Share your stories and experiences with us and stand to win limited edition prizes! </p>

<a href="/mse50contest"><img src="images/mse50/UGCWebBanner.png" class="img-icon" alt="web banner"></a>
 
<div>
<center>
	  <a class="button" href="/mse50contest">Join Now!</a>&nbsp; </center>
</div>   
  


<h1>Our People</h1>
	
<p>Our achievements over the last 50 years would not be possible without the many unsung heroes working behind the scenes in the MSE family. This brand new series celebrate the officers in the MSE family as the Ministry commemorates its 50th anniversary this year. </p>

<iframe src="https://www.youtube.com/embed/lb9QPUAdCBo" width="620" height="380" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<hr> 



<!--

<h1>Our People</h1>

<i>Coming Soon: Video Series of MSE Officers</i>

<h1>Additional Resources</h1>
<br>
<div id="resources-container">
<h4>Learning Journeys</h4>
<div class="cards">
<div class="card">
        <a href="https://www.roots.gov.sg/places/places-landing/trails/singapore-river-walk" target="_blank">  
            <div class="card-content">
            <h5>Singapore River Walk</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>
<div class="card">
        <a href="https://www.roots.gov.sg/places/places-landing/trails/Tampines-Heritage-Trail-Green-Spaces-Trail" target="_blank">  
            <div class="card-content">
            <h5>Green Spaces Trail</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>	
</div>
	
<h4>Publications</h4>
<div class="cards">
  <div class="card">
        <a href="#" target="_blank">  
            <div class="card-content">
            <h5>NEA Hawker Book</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>  
	<div class="card">
        <a href="#" target="_blank">  
            <div class="card-content">
            <h5>+65 Publication</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>
</div>

-->	
	
<!-- container end dic -->


