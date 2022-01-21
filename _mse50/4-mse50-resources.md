---
title: Additional Resources
permalink: /mse50/resources
---

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

<div id="resources-container">
<h1 style="text-align:center"><b>Resources</b></h1>
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
	<div class="card">
        <a href="https://www.roots.gov.sg/places/places-landing/trails/singapore-river-walk" target="_blank">  
            <div class="card-content">
            <h5>Singapore River Walk</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>
		<div class="card">
        <a href="https://www.roots.gov.sg/places/places-landing/trails/Tampines-Heritage-Trail-Green-Spaces-Trail
" target="_blank">  
            <div class="card-content">
            <h5>Green Spaces Trail</h5>
            </div>
          <img src="https://d33wubrfki0l68.cloudfront.net/a9154e74e9c95139dc8f60630dd4ee06387861a2/5f7f9/images/take-action-3.svg" alt="" style="width:300px;">
        </a>
    </div>	
</div>
<!-- container end dic -->
</div>
