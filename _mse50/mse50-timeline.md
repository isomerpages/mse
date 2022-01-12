---
title: Timeline of MSE History
permalink: /mse50/timeline
---

<style>

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

img {
  max-width: 100%;
}

a {
  text-decoration: none;
}

.clearfix:after {
  content: " ";
  display: table;
  clear: both;
} 

@media (min-width: 760px) {
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
  margin-bottom: 0;
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

/*izmedju - remove later */

.timeline-post:nth-child(2n+3) {
  clear: both;
}

.timeline-post:nth-child(odd) .vesti-date-wrapper .vesti-date {
  float: right;
}

.timeline-post:nth-child(even) {
  /*float: right;*/
  margin-bottom: 0;
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
  font-size: 1em;
  font-weight: 800;
  margin-top: 35px;
  margin-bottom: 15px;
  transition-delay: 0s;
  transition-duration: 0.2s;
  transition-property: all;
  transition-timing-function: ease-out
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
    margin-bottom: 0;
    margin-top: 50px;
  }
  .vesti-desc h2 {
    margin-bottom: 15px;
    margin-top: 20px;
    font-size: 30px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -77px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -77px;
    bottom: 15px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 77px;
  }
}

@media (min-width: 850px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -85px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -85px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 85px;
  }
}

@media (min-width: 1000px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -95px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -95px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 95px;
  }
}

@media (min-width: 1100px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -100px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -100px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 100px;
  }
}
  
@media (min-width: 1200px) {
/*  .timeline {
    margin-top: 40px;
  }*/
  .timeline-post:nth-child(even) {
    margin-top: 100px;
  }
  .vesti-date-wrapper .vesti-date {
    width: 100px;
    height: 100px;
    padding: 23px;
  }
/*   .vesti-date-wrapper .vesti-date .date {
    font-size: 1em;
    line-height: 10px;
  } */
  .vesti-date-wrapper .vesti-date .year {
    font-size: 1.5em;
    line-height: 50px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -132px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -132px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 132px;
  }
  .owl-item .vesti-desc h2 {
    margin-top: 75px;
  }
}

@media (min-width: 1300px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -140px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -140px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 140px;
  }
}

@media (min-width: 1400px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -146px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -146px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 146px;
  }
}

@media (min-width: 1500px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -155px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -155px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 155px;
  }
}

@media (min-width: 1600px) {
  .timeline-post:nth-child(odd) .vesti-date-wrapper {
    right: -160px;
    top: 55px;
  }
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    left: -160px;
  }
  .timeline-post:nth-child(odd) .vesti-date-wrapper,
  .timeline-post:nth-child(even) .vesti-date-wrapper {
    width: 160px;
  }
}
</style>

<div class="container">
    <div class="timeline clearfix">
    <div class="vertical-line">
      <div id="post-1" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="https://www.nas.gov.sg/archivesonline/watermark/picas_data/tn_pcd/19980005056-8073-3222-4844/img0114.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1972</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
                <h2>Formation of Ministry of Environment</h2>
            </a>
            <p>On 16 September 1972, the Ministry of the Environment (ENV), to tackle issues such as pollution control, sewerage, drainage and environmental health.</p>
                <h2>Drafting of Singapore Water Master Plan</h2>
            </a>
            <p>In the same year, Singapore's first Water Master Plan was drawn up. The plan outlined strategies for water resources to ensure a diversified and adequate supply that could meet future requirements.</p>
          </div>
          </div>
        </div>
      </div>
      <div id="post-2" class="vesti-col timeline-post">
        <div class="vesti-content-wrapper">
          <div class="photo">
            <img src="https://d33wubrfki0l68.cloudfront.net/6eb7e39110590bf5fb8204ecccec7b7014025679/a98b6/images/ch1_ulu_pandan_ip.jpg">
            <div class="vesti-date-wrapper">
              <div class="vesti-date">
                <span class="year">1979</span>
              </div>
            </div>
          </div>
          <div class="vesti-desc">
              <h2>Opening of Singapore's First Incineration Plant</h2>
            <p>On 30 July 1979, Singapore's and Southeast Asia's first incinerator plant, Ulu Pandan Incineration Plant, started operations.</p>
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
            <p>Singapore was declared malaria-free by the World Health Organization (WHO) on November 22 1982.</p>
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
  </div>
