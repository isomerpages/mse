---
title: MSE50 Milestones
permalink: /mse50milestones
---

<style>

/*--------------------------------------------------------------
STYLING FOR INTRO
--------------------------------------------------------------*/
 
.img-icon {
 max-width: 60% !important;
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


<h1>Our Journey</h1>

<div class="container">
    <div class="timeline clearfix">
    <div class="vertical-line">
      <div id="post-1" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m1.jpg" alt="photo of ENV office at Princess House">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1972</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
                <h2>Formation of Ministry of Environment</h2>
            <p>On 16 September 1972, the Ministry of the Environment (ENV) was set up to tackle issues such as pollution control, sewerage, drainage and environmental health. The ENV office was located at Princess House. </p>
          </div>
          </div>
        </div>
      </div>
      <div id="post-2" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m2.jpg" alt="photo of water treatment plant">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1972</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Drafting of Singapore Water Master Plan</h2>
            <p>In the same year, Singapore's first Water Master Plan was drawn up. The plan outlined strategies for water resources to ensure a diversified and adequate supply that could meet future requirements.</p>
          </div>
        </div>
      </div>
      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m3.jpg" alt="photo of Jurong Industrial Waterworks">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1974</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of Singapore's Pilot Water Reclamation Plant</h2>
            <p>In October 1974, Singapore’s first pilot water reclamation plant, a joint project by the Public Utilities Board (PUB) and the ENV, was commissioned at the Jurong Industrial Waterworks.</p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m4.jpg" alt="photo of singapore river">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1977</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of the Singapore River Clean-Up</h2>
            <p>The clean-up of Singapore River and Kallang Basin commenced in 1977. Besides the physical cleaning of the heavily polluted rivers, the massive exercise also involved the removal of various sources of pollution, the provision of proper sewage infrastructure and new facilities for resettled residents and businesses, and the implementation of anti-pollution measures to minimise future pollution.</p>
          </div>
        </div>
      </div>
	          <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m5.jpg" alt="photo of pig farm">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1977</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Commencement of resettlement of farmlands</h2>
            <p>In the 1970s, rapid development brought about more employment opportunities and farmland was redirected to other uses. From 1977, pig farming was banned in water catchment areas such as Kranji, as well as Kallang and Singapore River basins. With intensive pig farming estates being developed at Punggol and Jalan Kayu, farmers who were more productive were given the option of relocation.</p>
          </div>
        </div>
      </div>
  <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m6.jpg" alt="photo of Ulu Pandan Incineration Plant">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1979</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Opening of Singapore's First Incineration Plant</h2>
            <p>Faced with a shortage of land for landfilling, Singapore took a bold step to build the first waste-to-energy (WTE) plant in Southeast Asia. On 30 July 1979, Singapore’s first WTE plant - Ulu Pandan Incineration Plant - was completed at a cost of $130 million, a hefty investment at the time.</p>
          </div>
        </div>
      </div>
	  <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="https://www.news-medical.net/image.axd?picture=2021%2F10%2Fshutterstock_1483138139-1.jpg" alt="photo of mosquito">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1982</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Singapore Declared 'Malaria-Free'</h2>
            <p>Singapore was declared malaria-free by the World Health Organization (WHO) on 22 November 1982.</p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m7.jpg" alt="photo of pig farm">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1984</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Phasing out of pig farming</h2>
            <p>Pig farming was gradually phased out from 1984, after it was concluded that pig farming caused massive pollution and required intensive use of land and water – scarce resources in Singapore. It was also expensive to treat pig wastes. The phasing out of pig farming was completed in 1989.</p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m8.jpg" alt="Eat Frozen Pork campaign poster">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1985</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Eat Frozen Pork’ Campaign</h2>
            <p>In the lead-up to the complete phasing-out of pig farming in Singapore, the “Eat Frozen Pork Campaign” debuted in 1985 to dispel common misconceptions on frozen pork and raise public awareness of the production, handling, quality and nutritional value of frozen pork. Technical seminars were conducted to give traders and consumers a better understanding of the production, handling, quality and nutritional value of frozen pork. </p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m9.jpg" alt="photo of old hawker street">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1986</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of Street Hawker Resettlement</h2>
            <p>From 1968 to 1986, the Government licensed and resettled street hawkers into purpose-built hawker centres and markets with proper sanitation and amenities. By February 1986, the resettlement work was completed and 18,000 street hawkers were resited into newly built hawker centres.</p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m10.jpg" alt="photo of environment building">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1986</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of 25-storey Environment Building</h2>
            <p>The Environment building is the first government building designed and drafted by the Public Works Department with the aid of a computer.
The $92.6 million building’s key was handed to ENV’s then Permanent Secretary, Mr Cheong Quee Wah, on 18 December 1986.</p>
          </div>
        </div>
      </div>
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m11.jpg" alt="photo of singapore river">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1987</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of the Singapore River Clean-Up</h2>
            <p>The decade-long clean-up of Singapore River was completed on 2 September 1987.</p>
          </div>
        </div>
      </div>
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m12.jpg" alt="photo of night soil bucket">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1987</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Phasing Out of the Nightsoil Bucket</h2>
            <p>On 24 January 1987, Singapore bid goodbye to the century-old night soil bucket system. That day, the last night soil collection centre, located at Lorong Halus, ceased operation for good, as Singapore entered a new era served by a modern sanitation system.</p>
          </div>
        </div>
      </div>	
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m13.jpg" alt="photo of clean and green week poster">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1990</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Singapore's First Annual Clean and Green Week</h2>
            <p>Launched on 4 November 1990, the Clean and Green Week was a campaign to create awareness among Singaporeans that everyone is responsible for the environment. It became a yearlong campaign in 2007 and was consequently renamed Clean and Green Singapore.</p>
          </div>
        </div>
      </div>	 
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m14.jpg" alt="photo of construction site">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1991</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Introduction of Policies on Pollution and Public Health</h2>
            <p>In 1991, ENV introduced the (i) Pollutant Standards Index (PSI) (ii) emissions standards for diesel vehicles and implemented (iii) the Environment Public Health (Control of Noise from Construction Sites) Regulation that capped noise levels at construction sites.</p>
          </div>
        </div>
      </div>	
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m15.jpg" alt="photo of bukit timah diversion canal">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1991</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Opening of the Bukit Timah Second Diversion Canal</h2>
            <p>The Bukit Timah Second Diversion Canal was constructed in 1991 to divert stormwater from the Bukit Timah Canal to the Kallang River. Subsidiary canals were also built to allow stormwater to flow more efficiently.</p>
          </div>
        </div>
      </div>
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m16.jpg" alt="photo of green plan book">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1992</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of Singapore's First Green Plan</h2>
            <p>The Singapore Green Plan (SGP) is Singapore's first environmental blueprint. Released in May 1992 by ENV, its objective is to ensure that Singapore could develop an economic growth model that does not compromise its environment.</p>
          </div>
        </div>
      </div>
	    
	    
	      <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m17.jpg" alt="photo of used water plant">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1997</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Singapore Fully Served by Modern Sanitation</h2>
            <p>By 1992, all of Singapore had access to modern sanitation. In comparison, just three decades ago when Singapore became independent in 1965, only 45% of the population had access to proper sanitation.</p>
          </div>
        </div>
      </div>
	      
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m18.jpg" alt="photo of semakau landfill">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1999</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Commencement of Semakau Landfill Operations (Phase 1)</h2>
            <p>With space running out at Singapore’s last inland dumping ground at Lorong Halus, and competition for land was getting increasingly intense with rapid urbanisation, Singapore’s first offshore landfill - Semakau Landfill - began its operations on 1 April 1999. Not only does this 3.5 square-kilometre island hold the trash generated by Singapore, it is also home to a thriving biodiversity and the waters around it support some of Singapore’s richest coral reefs.</p>
          </div>
        </div>
      </div>

	    <div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m19.jpg" alt="photo of recycling collection">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2001</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of Singapore's National Recycling Programme</h2>
            <p>Launched in April 2001, the National Recycling Programme (NRP) required the public waste collectors (PWCs) licensed by NEA to provide recycling bins and recycling collection services to all HDB estates, private landed properties and condominiums/private apartments opted into the public waste collection scheme. The NRP adopted a collection system in which paper, plastic, glass and metal recyclables were collected for recycling. Recycling bags were used for HDB and only bins/bags were used for landed properties.</p>
          </div>
        </div>
      </div>
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m20.jpg" alt="pub logo from 2001">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2001</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Reconstitution of PUB</h2>
            <p>Recognising that Singapore’s water catchment and supply systems, drainage systems, water reclamation plants, and sewerage systems are part of a comprehensive water cycle, PUB was reconstituted to become Singapore’s national water authority, overseeing the entire water loop. The drainage and sewerage departments from ENV were transferred to PUB, while PUB itself was transferred from the Ministry of Trade and Industry to ENV.</p>
          </div>
        </div>
      </div>
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m21.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2002</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Formation of National Environment Agency</h2>
            <p>On 1 July 2002, a new statutory board – the National Environment Agency (NEA) – was formed under ENV to focus on the implementation of environmental policies. It took on the operations of the Environmental Public Health Division, and the Environmental Policy and Management Division of ENV.</p>
          </div>
        </div>
      </div>
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/newater.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2002</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of NEWater</h2>
            <p>On 9 August 2002, 60,000 people toasted the nation’s birthday at the National Day Parade with bottles of NEWater. The following year, on 23 February 2003, then-Prime Minister Goh Chok Tong officially launched the NEWater Visitor Centre and the first NEWater Factory at Bedok. NEWater also became one of Singapore's Four National Taps.</p>
          </div>
        </div>
      </div>
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m22.jpg" alt="MEWR logo">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2004</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>ENV was renamed MEWR</h2>
            <p>In September 2004, ENV was renamed the Ministry of the Environment and Water Resources (MEWR) to better reflect the Ministry’s significantly expanded role in managing Singapore’s water resources.</p>
          </div>
        </div>
      </div>	    

<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m23.jpg" alt="photo of SingSpring Desalination Plant">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2005</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Opening of Singapore's First Desalination Plant</h2>
            <p>On 13 September 2005, the SingSpring Desalination Plant - Singapore's first desalination plant for water supply and the largest seawater reverse-osmosis plant in the world - opened in Tuas. The plant can produce 30 million gallons of potable water per day.</p>
          </div>
        </div>
      </div>	
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m24.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2006</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of Singapore's PSTLES Initiative</h2>
            <p>Introduced in 2006, the Public Sector Taking the Lead in Environmental Sustainability (PSTLES) initiative encouraged agencies to focus on sustainability outcomes and put in place organisational processes to drive resource efficiency.</p>
          </div>
        </div>
      </div>	
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m25.jpg" alt="President’s Award for the Environment">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2006</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of President’s Award for the Environment</h2>
            <p>The President’s Award for the Environment (PAE) was launched in 2006 as Singapore's highest environmental accolade for individuals, educational institutions and organisations that have made outstanding contributions towards environment and sustainability, as well as building a resilient future for Singapore.</p>
          </div>
        </div>
      </div>		    
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m26.jpg" alt="Singapore Packaging Agreement logo">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2007</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of the Singapore Packaging Agreement</h2>
            <p>The Singapore Packaging Agreement (SPA) was launched on 5 June 2007 as a joint initiative by government, industry, and non-governmental organisations to reduce packaging waste. The SPA was a voluntary initiative that offered signatories the flexibility to adopt cost-effective solutions to reduce packaging waste.</p>
          </div>
        </div>
      </div>
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m27.jpg" alt="photo of DTSS">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2008</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of Deep Tunnel Sewerage System Phase 1</h2>
            <p>Completed in 2008 at a cost of SGD$3.4 billion, Phase 1 of the DTSS comprises a 48 km-long deep sewer tunnel running from Kranji to Changi, a centralised water reclamation plant at Changi, two 5 km-long deep sea outfall pipes and 60km of link sewers.</p>
          </div>
        </div>
      </div>	    

<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m28.jpg" alt="Kolam Ayer ABC Waterfront">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2008</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Launch of Singapore's First ABC Waters Project</h2>
            <p>Kolam Ayer ABC Waterfront, the first project launched under the Active, Beautiful, Clean (ABC) Waters Programme, was officially opened to the public on 5 April 2008. The aim of the ABC Waters Programme was to transform waterways and reservoirs in Singapore beyond their basic drainage and water storage functions, to allow these spaces to be used for community bonding and recreation.</p>
          </div>
        </div>
      </div>	    
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m29.jpg" alt="photo of MELS">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2008</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Introduction of the Mandatory Energy Labelling Scheme</h2>
            <p>The Mandatory Energy Labelling Scheme (MELS) was introduced on 1 January 2008 for regulated goods to help consumers compare the energy efficiency and make more informed purchasing decisions. The objective of setting Minimum Energy Performance Standards (MEPS) is to raise the average energy efficiency of regulated goods in the market.</p>
          </div>
        </div>
      </div>	
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="https://www.news-medical.net/image.axd?picture=2021%2F10%2Fshutterstock_1483138139-1.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1982</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Singapore Declared 'Malaria-Free'</h2>
            <p>Singapore was declared malaria-free by the World Health Organization (WHO) on 22 November 1982.</p>
          </div>
        </div>
      </div>		    
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m30.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2008</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Opening of Marina Barrage</h2>
            <p>Officially opened on 31 October 2008, Marina Barrage (MB) was Singapore’s 15th reservoir, and the first in the heart of the city. With a catchment area of 10,000 hectares, Marina catchment is the island’s largest and most urbanised catchment. Together with two other reservoirs, Marina Reservoir has increased Singapore’s water catchment from half to two-thirds of the country’s land area.</p>
          </div>
        </div>
      </div>		    
	    
<div id="post-3" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="../images/mse50/m30.jpg" alt="">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">2008</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Singapore Declared 'Malaria-Free'</h2>
            <p>Singapore was declared malaria-free by the World Health Organization (WHO) on 22 November 1982.</p>
          </div>
        </div>
      </div>	
	    
      <div id="post-4" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="https://www.nas.gov.sg/archivesonline/watermark/picas_data/tn_pcd/19990007092-0004-3012-0348/img047.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1987</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Completion of the Singapore River Clean-Up</h2>
            <p>The clean-up was officially declared complete on 2 September 1987. As part of the Clean Rivers Commemoration Celebration, a five-day carnival was held at Marina Bay.</p>
          </div>
        </div>
      </div>
    </div>
  </div>







	
<!-- container end dic -->


