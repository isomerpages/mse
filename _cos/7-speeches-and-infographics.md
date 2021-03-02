---
title: Speeches & Infographics
permalink: /cos/speeches-and-infographics
---
<style>

body {
  background-color: #F4F0E5;
}

#main-content > section:nth-child(3) > div > div > div.col.is-1.has-float-btns.is-position-relative.is-hidden-touch {
      visibility: hidden;
}


<style>
/*--------------------------------------------------------------
DAVID: START OF ISSUES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
/* refrain from using pure img selector as it changes the MSE logo size */

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
    background: #EBD3B2;
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
.card-content h4 {
    padding: 1em;
    margin-top: 1em;
    margin-bottom: 0.5em;
    /* font-weight: bold; */
    /* font-family: "Roboto Condensed", "Lato", sans-serif;
    font-style: italic;
    color: white; */
    text-decoration: none;
}

.card:hover {
    transition: all 0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    top: -4px;
    border: 2px solid #cccccc;
    background-color: inherit;
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

@media screen and (min-width: 52em) {
  .img {
    max-width: 52em;
  }
}

@media screen and (max-width : 480px) {
	.card { 
    max-width: 100%; }
}

/*--------------------------------------------------------------
DAVID: END OF ISSUES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>

<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital@1&display=swap" rel="stylesheet">

<div id="resources-container">
  <div class="cards">
    <div class="card">
        <a href="/cos/resources/COS_infographic_full.pdf" target="_blank">  
            <div class="card-content">
            <h4>INFOGRAPHICS</h4>
            </div>
          <!-- <img src="/images/key-environmental-statistics.png" style="width:300px;"> -->
        </a>
    </div>
    <div class="card">
        <a href="/news/committee-of-supply" target="_blank">  
            <div class="card-content">
            <h4>COS SPEECHES</h4>
            </div>
        <!-- <img src="/images/zero-waste-masterplan.png" style="width:max-content;"> -->
        </a>
    </div>
      <div class="card">
      <a href="/" target="_blank">  
          <div class="card-content">
          <h4>VIDEOS</h4>
          </div>
      <!-- <img src="/images/zero-waste-masterplan.png" style="width:max-content;"> -->
      </a>
  </div>
  </div>
</div>

<div>
<center><a class="button_cos" href="/cos/">Back to Overview</a></center>
</div>
