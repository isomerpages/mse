---
title: Go Green Singapore
permalink: /gogreensg
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
 max-width: 35% !important;
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

<img src="images/gogreensg_logo.png" alt="GoGreenSG" class="mse50-logo"><br>
Led by the Ministry of Sustainability and the Environment, Go Green SG (formerly known as Climate Action Week) is a whole-of-nation movement to rally the community to take collective action towards a sustainable future for Singapore. It comprises a series of sustainability-related events and activities in July organised by our People, Public and Private (3P) partners.

This year, in collaboration with the Singapore Tourism Board, we are also showcasing various sustainable experiences that Singapore has to offer as a sustainable urban destination.

You can curate your own Go Green experiences, based on individual lifestyles, personal interests and goals. With many exciting activities (e.g. behind-the-scenes sustainability tours, exclusive learning journeys, events, workshops, school and youth activities, promotions and green challenges) organised by 3P partners to choose from, everyone can go green in your own way.


<!--
<p><b>Climate Action Week is now Go Green SG!</b></p>

<p>Organised by the Ministry of Sustainability and the Environment (MSE), Climate Action Week is an annual national initiative that brings together sustainability-related events to galvanise Singaporeans to take collective climate action.</p>

<p>Last year’s edition saw over 140 activities organised by 80 partners – the highest number since its launch in 2019! The activities included community events, workshops, talks, learning journeys, school and youth activities, clean-ups, promotions and green challenges.</p>

<p><b>This year, Climate Action Week will be rebranded as Go Green SG</b> to better reflect the wide range of sustainability initiatives and programmes it encompasses. </p>

We invite you to join in this community movement and organise sustainability-related activities in the month of July to rally even more Singaporeans towards a sustainable lifestyle. Download our [partner's package](/files/GGSG-partners-package.pdf) to find out how to be part of the Go Green SG movement this year!

<p>Find out what happened during last year’s event <a href="https://www.mse.gov.sg/climate-action-week/">here!</a></p>
-->

	
<!-- container end dic -->


