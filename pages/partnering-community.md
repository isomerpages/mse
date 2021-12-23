---
title: Partnering the Community
permalink: /partnering-community/
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
    padding: 0px;
    border-radius: 0px;
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
	line-height: 150%;
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
<h1 style="text-align:center"><b>Partnership Reports</b></h1>
<div class="cards">
  <div class="card">
        <a href="/resources/good_samaritan_law_report_090321.pdf" target="_blank">  
            <div class="card-content">
            <h5>MSE-NYC Youth Circle Report<br>(2021)</h5>
            </div>
          <img src="/images/youth-circle-report-cover.jpg" alt="" style="width:80%; border:1px solid black;">
		<p style="text-align: center; font-size: 0.8em;">This is a report by a group of youth leaders who worked with the Ministry of Sustainability and the Environment and the Singapore Food Agency to study the issue of food waste, and how a Good Samaritan Law Food Donation Act might encourage donation of surplus or unsold food to the needy.</p>
        </a>
    </div>
    <div class="card">
        <a href="/resources/CW_Report_MEWR.pdf" target="_blank">  
            <div class="card-content">
            <h5>Response to Citizens’ Workgroup Report (2019)</h5>
            </div>
        <img src="/images/CW_Report_MEWR_Cover.jpg" alt="" style="width:80%;">
		<p style="text-align: center; font-size: 0.8em;">In 2019, the Ministry of Sustainability and the Environment convened a #RecycleRight Citizens’ Workgroup to study how household recycling could be improved. This is the Ministry’s response to the recommendations of the Workgroup.</p>
        </a>
    </div>
    <div class="card">
        <a href="/resources/CW_Report_Participants.pdf" target="_blank">  
            <div class="card-content">
            <h5>#RecycleRight Citizens’ Workgroup Report (2019)</h5>
            </div>
        <img src="/images/CW_Report_Participants_Cover.png" alt="" style="width:80%;">
		<p style="text-align: center; font-size: 0.8em;">This is a report of the recommendations of a diverse group of citizens brought together by the Ministry of Sustainability and the Environment to co-create solutions to improve the way households recycle in Singapore.</p>
        </a>
    </div>
</div>
<!-- container end dic -->
</div>
