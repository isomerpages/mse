---
title: COS Testing Page
description: add a description here
permalink: /costest
image: /images/cos2023/COS2023-thumbnail.png
---
<style>
/*--------------------------------------------------------------
STYLING FOR INTRO
--------------------------------------------------------------*/

.img-icon {
 max-width: 90% !important;
margin-top: 10px !important;
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
STYLING FOR ACCORDIAN
--------------------------------------------------------------*/
 input {
	display: none;
}
label {
	display: block;
	padding: 8px 22px;
	margin: 0 0 5px 0;
	cursor: pointor;
	background: #F0F4F6;
	border-radius: 3px;
	color: #484848;
	transition: ease .5s;
	font-size: 1.5em;
}

label:hover {
	background: #4a96b0;
	color: #FFF;
}

.accordion-content {
	/* background: #E2E5F6; */
	padding: 10px 0px 30px 30px;
	/* border: 1px solid #484848; */
	margin: 0 0 1px 0;
	border-radius: 3px;
}

input + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: none;
}

input:checked + label + .accordion-content {
	display: block;
}
</style>
<img src="/images/cos2023/COS2023-Thumbnail.png" class="mse50-logo"><br>

<p>Insert first two paras of media factsheet</p>
<p>Insert first two paras of media factsheet</p>

<div>
<center>
	  <a class="button" href="xxx" target="_blank">Press Release</a>&nbsp; 
	  <a class="button" href="/news/committee-of-supply/" target="_blank">Speeches</a>&nbsp;
	  <a class="button" href="xxxx/" target="_blank">Infographics</a>&nbsp;
</center>
</div>

<hr> 

<h3 id="carbon-emissions">2023 Announcements</h3>
<div>
  	<input type="checkbox" id="cctitle1"  /><label for="cctitle1">A Green & Climate-Friendly Singapore</label>
	<div class="accordion-content">
      <p><b>Public Sector leading the way in environmental sustainability</b></p>
      <ul>
	 <li>Annual GreenGov.SG report on Government's efforts, progress and plans (from 2023)</li>
         <li> Statutory Boards to publish annual environmental sustainability disclosures on their efforts, progress and plans (from 2024)</li>
         <li>Up to 5% of evaluation points to be set aside for environmental sustainability for large Government construction and ICT tenders (starting in 2024)</li>
        <li>PUB has committed to achieving net zero emissions around 2045 through 3Rs strategy - Replace, Reduce, Remove</li>
</ul>

	<p><b>Supporting our Households & Companies to be more energy efficient</b></p>
  <p><li>Helping households make more informed decisions</li>
    - Energy labels will be introduced for more appliances<br>
    - Energy standards for appliances will be raised over the next two years</p>
  <li>Extension and expansion of the Climate Friendly Households Programme. More details will be released later this year.</li>
  <li>Enhancement of Energy Efficiency Fund (E2F) to provide manufacturing SMEs more certainty when investing in energy efficient technologies and simpler grant application process</li></p>
	</div>
	
  	<input type="checkbox" id="cctitle2"  /><label for="cctitle2">Ensuring Water Sustainability</label>
	<div class="accordion-content">
		<li>Tunneling works for Deep Tunnel Sewerage System (DTSS) Phase 2 Project expected to be completed (by 2H2023)</li>
      <li>Redevelopment of Kranji Water Reclamation Plant and Kranji NEWater Factory to increase treatment capacities and NEWater production</li>
      <li>Introduction of mandatory water recycling requirements on new projects in wafer fabrication, electronics and biomedical industries (from 1 January 2024)</li>
	</div>
  	<input type="checkbox" id="cctitle3"  /><label for="cctitle3">Towards a Zero Waste Nation</label>
	<div class="accordion-content">
      <p><b>Reducing packaging waste, increasing recycling & building zero waste habits</b></p>
<li>Larger supermarket operators to charge at least 5 cents per disposable carrier bag to encourage consumers to bring their own bags (from 3 July 2023)</li>
      <li>New beverage container return scheme to boost recycling of used plastic bottles and metal cans</li>
      <li>Bloobox distribution to encourage households to recycle right</li>
	</div>
		
</div>	
		<input type="checkbox" id="cctitle4"  /><label for="cctitle4">Safeguarding Our Hawker Culture</label>
	<div class="accordion-content">
		<p>
          <b>New & upgraded hawker centres</b>
      </p>
      <li>Two new hawker centres (Buangkok and Woodleigh Village), and a refreshed hawker centre (Jurong West) will be operational in 2023</li></p>
      <p>
        <b>Sustaining the hawker trade</b> 
        <li>Ongoing programmes such as Hawkers' Development Programme will be enhanced</li></p>
        <p>
          <b>Raising hawkers' productivity</b></p>
          <li>Expansion of hawkers' Productivity Grant from $5,000 to $7,000 to cover stall-level digital solutions (extended to FY2025)</li>
          <li>Enhancement of Productive Hawker Centres Programme to cover co-funding for Cleaning Process Automation solutions (extended to FY2028)</li>
	</div>
	
</div>	
	<input type="checkbox" id="cctitle5"  /><label for="cctitle5">Enhancing Coastal & Flood Resilience</label>
	<div class="accordion-content">
		<li>New Coastal Protection and Flood Management Research Programme to support development of innovative coastal protection and flood management solutions</li>
      <li>Ongoing site-specific studies will cover half of Singapore's coastline when new study at North-west coast (Lim Chu Kang) and Sungei Kadut area) commences in second half of 2023</li>
      <li>Ongoing drainage improvement works at 25 locations to enhance flood resilience</li>
          
	</div>
	
</div>	
	<input type="checkbox" id="cctitle6"  /><label for="cctitle6">Securing a Safe Supply of Food</label>
	<div class="accordion-content">
      <p><b>Diversifying our food import sources</b>
      <li>Increased our food supply sources from 172 countries and regions in 2019 to 183 in 2022</li></p>
      <p>
        <b>Growing local</b>
      
      <li>Launch first land tender for wider range of food types (e.g. fruited vegetables and mushrooms) in 2H2023</li>
      <li>Continue efforts to transform the Lim Chu Kang region through masterplanning</li></p>
      <p>
        <b>Developing a skilled agri-food workforce</b>
     
      <li>New ITE Work-Study Diploma in Agriculture and Aquaculture Technology (from April 2023) </li> </p>
      <p>
        <b>New Alliance for Action (AfA)</b>
        <li>Explore solutions to raise demand for local produce</li>
      </p>
      <p>
        <b>A more productive & sustainable aquaculture sector</b>
        <li>SFA's Marine Aquaculture Centre as key research campus of Aquapolis for aquaculture research and innovation</li>
        <li>Pre-planning study on integrating future research facilities with aquaculture infrastructure</li>
      </p>
      <p><b>Leveraging Science, Data & Technology to enhance food safety</b>
        <li>Development of Whole Genome Sequencing analytics to better identify causes of foodborne diseases</li>
        <li>$23 million set aside under the Singapore Food Story R&D Programme 2.0 to build new food safety capabilities</li>
      </p>
	</div>
	
</div>	
	<input type="checkbox" id="cctitle7"  /><label for="cctitle7">Partnering the Community</label>
	<div class="accordion-content">
		<p>
          <b>Green Action for Communities (GAC)</b>
          <li>Galvanise community participation to develop action plans for sustainability initiatives</li>
          <li>700 GAC group members engaged through workshops and deep dives</li>
          <li>More deep dives to be rolled out over the next few months</li>
      </p>
      <p><b>SG Eco Fund</b>
        <li>Supported over 180 ground-up community projects on sustainability</li>
        <li>Individuals and groups are invited to apply for funding to implement projects with the community</li>
      </p>
	</div>
	
</div>	
<hr>

<h1>Header</h1>

* ABC
* ABC
* ABC



<hr>

<h1>COS Videos</h1>
<p><strong>I Remember - an MSE50 Short Film</strong></p>
<p>Take a trip down memory lane in this short film as we re-live the days of street hawkers in 1970s, where a chance encounter between a young lady and a strange boy triggers off reflections about our sustainable habits and how they have carried on till today.</p>

<iframe src="https://www.youtube.com/embed/STUnLrfK0as" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe src="https://www.youtube.com/embed/STUnLrfK0as" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe src="https://www.youtube.com/embed/STUnLrfK0as" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe src="https://www.youtube.com/embed/STUnLrfK0as" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p></p>

<p><strong>#50YearsOfSustainability - Crowdsourcing for your environment stories</strong></p>
<p>Got a story or memory of what Singapore’s environment used to be like when you were growing up? Share your stories and experiences with us and stand to win limited edition prizes! </p>

<a href="/mse50contest"><img src="images/mse50/UGCWebBanner.png" class="img-icon" alt="web banner"></a>
 

  
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



	
<!-- container end dic -->

