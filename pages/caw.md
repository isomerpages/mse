---
title: Climate Action Week 2021
permalink: /climate-action-week/
---

<style>

/* Red #EF3F22, Teal #02B499, Skydark blue #234F71 */

/* Start of offsetting margin to clear space */
.col.is-offset-2, .col.is-offset-2-tablet {
    margin-left: 0;
}

.col.is-8, .col.is-8-tablet {
    flex: 0%;
}
/* End of offsetting margin to clear space */



.grid {
  display: grid;
  gap: 10px;
  grid-template-columns: 2fr 4fr 1fr;
}

.grid h2 {
  /* color: black; */
}
.main {
  background: white;
}

.side {
  background: white;
}

.overflow-container {
  height: 40vh;
  overflow: auto;
  margin-bottom: 2em;
}

.main,
.side {
  padding: 20px;
  border-radius: 5px
  margin: 10px 10px;
}



/* Cards */

.card-news {
  overflow: hidden;
  /* height: 200px; */
  background: white;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  display: flex;
  flex-direction: column;
  border-radius: 5px;
  align-items: center;
  padding: 1em;
  max-width: auto;
  margin: 0em 0em 1em 0em;
}

.card-event {
  overflow: hidden;
  height: auto;
  background: white;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  display: flex;
  border-radius: 5px;
  align-items: center;
  margin: 0.2em 1em 1em 0.2em;
}

.card-event img {
  height: 100%;
  width: 60px;
  object-fit: cover;
  margin: 10px;
}

.card-event h2 {
  font-size: 16px;
  font-weight: bold;
  margin: 0px 0px 0px 5px;
  line-height: 1.5;
}

.card-event p {
  font-size: 12px;
  line-height: 1.5;
  opacity: .7;
  margin: 2px 0px 0px 5px;
}

.card-event a {
  text-decoration:none;
}

.card-event .card-event-infos {
  padding: 8px;
}


/* .card-event .card-event-infos a, h2:hover {
  text-decoration: none;
  background-color: #444;
} */



.card-banner {
  background-size: cover;
  background-position: center;
  height: auto;
  margin-left: 1em;
  display: flex;
  flex-flow: column;
  padding: 0em 7em 1em 6em;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 1.2em;
  /* font-weight: bold; */
  text-shadow: 1px 1px 3px rgba(0,0,0,0.8);
  border-radius: 5px;
  box-shadow: 0 0 5px rgba(0,0,0,0.2);
}

.card-banner > h3 {
  font-size: 2.8em;
  padding: 0.3em;
  justify-content: center;
  align-items: center;
  line-height: 0.8;
  color: white;
  text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
}

/* #org > a {
  text-decoration:none;
  a:hover {
  background: lightgrey;
  }
  } */

/* To hide title breadcrumb banner and right icons */
.bp-section.is-small.bp-section-pagetitle {
  display: none;
}

#main-content > section:nth-child(2) > div > div > div.col.is-1.has-float-btns.is-position-relative.is-hidden-touch {
  display: none;
}

/* Modal pop-ups for events */
.modal-window {
  position: fixed;
  background-color: rgba(200, 200, 200, 0.75);
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 999;
  opacity: 0;
  pointer-events: none;
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  transition: all 0.3s;
}

.modal-window:target {
  opacity: 1;
  pointer-events: auto;
}

.modal-window > div {
  width: auto;
  max-width: 80vw;
  position: relative;
  margin: 10% auto;
  padding: 2em;
  background: #fff;
  color: #444;
}

.modal-window header {
  font-weight: bold;
}

.modal-close {
  color: black;
  line-height: 50px;
  font-size: 1em;
  position: absolute;
  right: 0;
  text-align: center;
  top: 0;
  width: 70px;
  text-decoration: none;
  margin: 2em;
}

.modal-window h1 {
  font-size: 150%;
  margin: 0 0 15px;
}

#open-modal > div > a {
 color: black;
}

/* Media screening */
@media(max-width: 600px){
  .grid {
    grid-template-columns: 1fr;
  }
  .card-banner {
      padding: 0em 1em 1em 1em;
  }
}

</style>



<!-------------------------------------------- START OF HTML ------------------------------------------->



<div class="card-banner" style="background-image: linear-gradient(rgba(0,0,0,0), rgba(0,0,0,0)), url(../images/cawbanner.jpeg)">
  <h3>Climate Action Week 2021</h3> Climate Action Week rallies our people and communities to take collective climate action and secure a sustainable future for Singapore. In line with the Singapore Green Plan 2030, the theme this year is “City of Green Possibilities”.
  <!-- In 2020, more than 30 events were organised by our 3P partners during CAW.  This year, we once again welcome you to join us in organising climate initiatives to build an active green citizenry. -->
  <!-- Held from 12-18 July 2021, the objectives for Climate Action Week 2021 are to:
  - RAISE AWARENESS of climate adaptation and mitigation efforts by Public, Private and People sectors to support the Green Plan;
  - PARTNER communities and organisations to take concrete steps to realise net-zero emissions aspirations;
  - RALLY citizens to adopt a sustainable lifestyle, and be environmental stewards;
  - CO-CREATE solutions to achieve our climate pledge; and
  - EMPOWER stakeholders to enhance climate resilience. -->
</div>

<div class="grid">
<!-- NEWS -->
  <article class="main">
    <h4><strong><center>NEWS</center></strong></h4>
      <!-- <div class="card-news">
        <div class="card-event-infos">
          <h5><a href="url" class="external-link">Press Release on Climate Action Week </a></h5>
            <p>12 July</p>
        </div>
      </div>
      <div class="card-news">
        <div class="card-event-infos">
          <h5>Press Release on GreenGov.SG </h5>
            <p>12 July</p>
        </div>
      </div>
      <div class="card-news">
        <div class="card-event-infos">
        <h5><a href="" class="external-link">
        <img src="https://cdn.worldvectorlogo.com/logos/tiktok-icon-white-1-1.svg" alt="CAW Tiktok Challenge" style="width:3em;height:3em;margin-bottom:1em;margin-top:0.9em;">Join our Tiktok Face-off Challenge!</a></h5>
        </div>
      </div> -->
  </article>

<!-- EVENTS -->

  <section class="side">
    <h4><strong><center>ONE-DAY EVENTS</center></strong></h4>
        <!-- <div class="card-news" style="border:2px solid; border-radius:6px;">
            <div class="card-event-infos">
              <p><strong><a href="" class="external-link">120 activities with over 60 partners. Click for full details.</a></strong></p>
            </div>
        </div> -->
      <div class="overflow-container">
        <div class="card-event">
          <img src="../images/thumbnail.png" />
          <div class="card-event-infos">
              <h2><a href="https://form.gov.sg/#!/60d1572a67a33b0011b8f368" class="external-link">MSE - Partners for the Environment Forum 2021</a></h2>
              <p>12 July</p>
          </div>
        </div>
<!-- test modal -->
<!-- test modal -->
        <div class="card-event">
          <img src="https://www.thatballoons.com/wp-content/uploads/2018/02/MBS-Logo-1024x304.jpg" />
          <div class="card-event-infos">
            <h2>MBS - Climate Action Week Trainings</h2>
              <p>12 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://web.sgbc.online/assets/sgbc/sgbc-logo-medium.jpg" />
          <div class="card-event-infos">
            <h2>Singapore Green Building Council Webinar on Climate Change Adaptation & Sustainability Leadership</h2>
              <p>13 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://assets.grab.com/wp-content/uploads/sites/4/2020/04/01111035/Grab_Final_Master_Logo_2019_RGB_green.png" />
          <div class="card-event-infos">
            <!-- <a href="#open-modal"></a> -->
            <h2>Grab - Regional Green Programme & JustGrab Green</h2>
            <p>14 July</p>
          </div>
              <!-- <div id="open-modal" class="modal-window">
                <div>
                  <h1>Grab - Regional Green Programme & JustGrab Green</h1>
                      The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog. <br><br>
                      The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.The quick brown fox jumped over the lazy dog.
                      <br><br><a href="url"><h5>Click here to join the event</h5></a>
                  <a href="#modal-close" title="Close" class="modal-close">CLOSE &times;</a>
              </div>
          </div> -->
        </div>
        <div class="card-event">
          <img src="https://anchorgreenpri.moe.edu.sg/qql/slot/u530/About%20AGPS/School%20Info/Crest%20&%20Motto/AGPS%20SCHOOL%20CREST.jpg" />
          <div class="card-event-infos">
            <h2>Anchor Green Primary School - Climate Action Week school activity</h2>
              <p>13 July, 27 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://asi.sutd.edu.sg/wp-content/themes/asi-avada/assets/images/sutd-asi-logo-web-2021-fc.png" />
          <div class="card-event-infos">
            <h2>SUTD seminar series on Sustainability and Circular Economy: The Role of Design in Circular Economy</h2>
              <p>14 July (till 28 July)</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://www.regulationasia.com/wp-content/uploads/wwf.png" />
          <div class="card-event-infos">
            <h2>WWF Singapore - Schools for Climate Action</h2>
              <p>14 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a9/City_Developments_Limited_logo_-_text_bottom.svg/1200px-City_Developments_Limited_logo_-_text_bottom.svg.png" />
          <div class="card-event-infos">
            <h2>CDL - Launch of Climate Action Exhibition “Change the Present, Save the Future”</h2>
              <p>14 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Ricoh_logo_2012.svg/400px-Ricoh_logo_2012.svg.png" />
          <div class="card-event-infos">
            <h2>Ricoh Asia Pacific - Internal Outreach - "Facing Our Foodprint"</h2>
              <p>15 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://sustainableprocurement.sg/wp/wp-content/uploads/2020/03/NSPR-Logo.png" />
          <div class="card-event-infos">
            <h2>Forum for Sustainable Procurement - National Sustainable Procurement Roundtable (DBS, Mandai Park Holdings, Singtel and Starhub)</h2>
              <p>16 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://www.regulationasia.com/wp-content/uploads/wwf.png" />
          <div class="card-event-infos">
            <h2>WWF Singapore - Launch of Kosong Plan</h2>
              <p>15 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://web.sgbc.online/assets/sgbc/sgbc-logo-medium.jpg" />
          <div class="card-event-infos">
            <h2>Singapore Green Building Council - Joint Webinar with HDB-BRI on Smart & Sustainable Living</h2>
              <p>15 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://esi.nus.edu.sg/images/default-source/event_images/esi245fa6a9e17862769a03ff0000ab93db.png?sfvrsn=227c404_0" />
          <div class="card-event-infos">
            <h2>Energy Studies Institute, NUS - Singapore Green Plan 2030 Conversation</h2>
              <p>16 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://yt3.ggpht.com/ytc/AAUvwnh3VHRdrowiLggEd2nIYqfFzYNwnkBF7iSTznem=s900-c-k-c0x00ffffff-no-rj" />
          <div class="card-event-infos">
            <h2>NTU Earth Observatory of Singapore - ‘Ask a Scientist: Climate Change and Nature-Based Solutions</h2>
              <p>16 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://www.where2learn.com/wp-content/uploads/2020/02/fengshan-primary-school.jpg" />
          <div class="card-event-infos">
            <h2>Fengshan Primary School Environmental Committee - "Adopt an edible plant"</h2>
              <p>16 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://secondsguru.com/wp-content/uploads/2016/10/logo-2.png" />
          <div class="card-event-infos">
            <h2>Secondsguru - "Can I be a changemaker?" Real stories from current times</h2>
              <p>17 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://susscribe.com/issue-46/wp-content/uploads/2019/03/The-Eco-Statement.jpg" />
          <div class="card-event-infos">
            <h2>The Eco-Statement - Game of Recycling - A game-based workshop on recycling</h2>
              <p>17 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://eventnook.s3.amazonaws.com/u/63753/coverimage_1603284234074_tp_logo.png" />
          <div class="card-event-infos">
            <h2>Temasek Poly Green Interest Student Group & Rivervale Court Residents’ Network - Workshop on upcycling</h2>
              <p>17 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfqtDeUffwZnGYUJOugwNOx44rnx6PoeAmKlg-6BJpXU1vYKmtO--XFywc6Nq6us1XV8Q&usqp=CAU" />
          <div class="card-event-infos">
            <h2>Earth 300 - Earth 300 Initiative online conference</h2>
              <p>17 July</p>
          </div>
        </div>
        <div class="card-event">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBAP-XeAUJIxboNC6mq3s7974evWAhOILoVA&usqp=CAU" />
          <div class="card-event-infos">
            <h2>Singapore Youth for Climate Action - "A Voice for Mother Nature" online event</h2>
              <p>17 July</p>
          </div>
        </div>
        <div class="card-event">
            <img src="https://images.squarespace-cdn.com/content/v1/585fa90329687f7c77188418/1483953395999-ACW40ERP1C53986D5VHC/psa_logo.jpg" />
            <div class="card-event-infos">
              <h2>Port of Singapore Authority (PSA) - Green Port Conversation “Energy Resilience for Sustainable Growth – Strategies and Challenges for Singapore and the Industries” </h2>
                <p>13 July</p>
            </div>
          </div>
        </div>
        <!-- SECOND OVERFLOW FOR WEEK-LONG EVENTS -->
        <h4><strong><center>WEEK-LONG EVENTS</center></strong></h4>
          <div class="overflow-container">
          <div class="card-event">
            <img src="https://sagesch.files.wordpress.com/2017/05/logo-nygh2.png" />
            <div class="card-event-infos">
              <h2>Nanyang Girls High School - Plastic bottle collection competition, upcycling competition, sustainable lifestyle and zero-waste programmes</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://tampinesnorthpri.moe.edu.sg/qql/slot/u513/our%20school/school%20profile/School_Crest.png" />
            <div class="card-event-infos">
              <h2>Tampines North Primary School - Love Our Food</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.2020psec.sg/wp-content/uploads/2020/09/P10-360x360.png" />
            <div class="card-event-infos">
              <h2>Qihua Primary School - Green Wave & Virtual Eco-tour/sharing</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.where2learn.com/wp-content/uploads/cache/images/2021/01/punggol-primary-school/punggol-primary-school-506047199.jpg" />
            <div class="card-event-infos">
              <h2>Punggol Primary School - Clean Plate Challenge during mealtimes</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://thesmartlocal.com/reviews/wp-content/uploads/2013/02/wdg-1361792567.jpg" />
            <div class="card-event-infos">
              <h2>Woodgrove Primary School - Event on "Vampire Appliances"</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.moe.gov.sg/-/media/images/school-logos/secondary-schools/kuo-chuan-presbyterian-secondary-school.png" />
            <div class="card-event-infos">
              <h2>Kuo Chuan Presbyterian Primary School - Various events with hands-on activities</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://thesmartlocal.com/reviews/wp-content/uploads/2013/03/1-1364578315.gif" />
            <div class="card-event-infos">
              <h2>Sembawang Primary School - Sharing on sustainable practices and zero waste lifestyle habits </h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.where2learn.com/wp-content/uploads/2020/02/east-spring-primary-school.jpg" />
            <div class="card-event-infos">
              <h2>East Spring Primary School - Clean Plate Campaign and Earth Week</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.minds.org.sg/wp-content/uploads/2020/04/logo-minds@2x.png" />
            <div class="card-event-infos">
              <h2>Towner Gardens School (MINDS) - Edible Gardening</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.where2learn.com/wp-content/uploads/2020/02/fengshan-primary-school.jpg" />
            <div class="card-event-infos">
              <h2>Fengshan Primary School (FSPS) Environmental Committee - Urban Farming Programmes</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.where2learn.com/wp-content/uploads/cache/images/2021/01/ai-tong-school/ai-tong-school-2251316606.jpg" />
            <div class="card-event-infos">
              <h2>Ai Tong School - Climate Action Wall</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.rp.edu.sg/images/default-source/about-us/historical-milestones/milestones-02.jpg" />
            <div class="card-event-infos">
              <h2>Republic Polytechnic - Sustainable Living - Reduce waste and consumption, Reverse Vending Machine</h2>
                <p>April - September 2021</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://s3.ap-southeast-1.amazonaws.com/logos.form.gov.sg/1590560379953-SWCDC_Logo_FC_RGB_1080px.png" />
            <div class="card-event-infos">
              <h2>South-West Community Development Council (SWCDC) - Cooking Class for Community Gardeners, Green Schools Assembly Skit, Energy Conservation Posters by Junior Environment Ambassadors</h2>
                <p>12-16 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://static.wixstatic.com/media/c1b31b_f5f3ba5d40df483088ecc481cbc30515~mv2.png/v1/fill/w_400,h_130,al_c,q_85,usm_0.66_1.00_0.01/Sembwaste%20Logo.webp" />
            <div class="card-event-infos">
              <h2>PA (MacPherson) & SembWaste - Cash-for-Trash Station for residents to bring down their recyclables</h2>
                <p>3 July (1st Saturday of every month)</p>
            </div>
          </div>
          <div class="card-event">
            <img src="../images/taman.png" />
            <div class="card-event-infos">
              <h2>Taman Jurong Youth Network - Taman Jurong Eco Series </h2>
                <p>1-30 July</p>
            </div>
          </div>
          <div class="card-event">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBAP-XeAUJIxboNC6mq3s7974evWAhOILoVA&usqp=CAU" />
          <img src="https://eventnook.s3.amazonaws.com/u/63753/coverimage_1603284234074_tp_logo.png" />
            <div class="card-event-infos">
              <h2>Singapore Youth for Climate Action & Temasek Polytechnic student group campaigns - "Our Fight Against Dengue" & "Reducing Energy Consumption"</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://is3-ssl.mzstatic.com/image/thumb/Purple115/v4/e0/19/f9/e019f97e-d33f-8501-34f0-38aaf13cbc64/source/512x512bb.jpg" />
            <div class="card-event-infos">
              <h2>Just Dabao & SusGain - "Just Plant!" campaign on tree-planting and reforestation</h2>
                <p>From 12 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.logosurfer.com/wp-content/uploads/2018/03/Shimizu20Logo.jpg" />
            <div class="card-event-infos">
              <h2>Shimizu Corporation - Annual Tree Planting 2021 and "Bring Your Own" campaign</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
          <img src="https://web.sgbc.online/assets/sgbc/sgbc-logo-medium.jpg" />
            <div class="card-event-infos">
              <h2>Singapore Green Building Council - Digital Activation for SGBC Green Homes Public Engagement Campaign</h2>
                <p>12-16 July</p>
            </div>
          </div>
          <div class="card-event">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Ricoh_logo_2012.svg/400px-Ricoh_logo_2012.svg.png" />
            <div class="card-event-infos">
              <h2>Ricoh Asia Pacific - Facing our Footprint - Social Media Outreach</h2>
                <p>5-25 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://1000logos.net/wp-content/uploads/2020/05/Micron-Loog.png" />
            <div class="card-event-infos">
              <h2>Micron - Climate Action Week Campaign</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://s7d2.scene7.com/is/image/ritzcarlton/ritz-carlton-primary-black" />
            <div class="card-event-infos">
              <h2>The Ritz-Carlton, Millenia Singapore - Clean Plate Challenge</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://cdn.ek.aero/sg/english/images/Novotel_hsr_275_tcm289-3284955.png" />
            <div class="card-event-infos">
              <h2>Novotel Hotel - Promotional Menu & Green deals</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://www.swissotel.com/assets/0/92/2119/3454/3493/3495/5386/ff680b52-afc4-48a6-af51-76b4aa4f6f0c.png" />
            <div class="card-event-infos">
              <h2>Swissôtel Merchant Court - Herb Garden Showcase, staff outreach and Ellenborough Market Cafe outreach</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://global-uploads.webflow.com/5d930e99e2f2d3ed120f3956/5ddad401019b4b70ff25fa05_IMG_6566-p-500.png" />
            <div class="card-event-infos">
              <h2>Swapaholic - Publishing of Textile Sustainability Report</h2>
                <p>12-18 July</p>
            </div>
          </div>
          <div class="card-event">
            <img src="https://images.squarespace-cdn.com/content/v1/585fa90329687f7c77188418/1483953395999-ACW40ERP1C53986D5VHC/psa_logo.jpg" />
            <div class="card-event-infos">
              <h2>Port of Singapore Authority (PSA) - e-Waste Recycling Drive, Sustainability Champion Video Cascade, ENView Issue 9, and launch of Singapore Sustainability Narrative infographic </h2>
                <p>12-18 July</p>
            </div>
          </div>
      </div>
              <!-- END OF SECOND OVERFLOW -->
  </section>

<!-- RESOURCES -->

   <section class="side">
    <h4><strong><center>RESOURCES</center></strong></h4>
      <div class="card-news">
        <div class="card-event-infos">
          <h5><center style="margin:0;"><a href="../resources/caw-banners-posters.zip" class="external-link" >Help Publicise Climate Action Week </a></center></h5>
        </div>
      </div>
      <div class="card-news">
        <div class="card-event-infos">
          <h5><a href="https://www.mse.gov.sg/take-action/individuals" class="external-link">Take Action Today</a></h5>
        </div>
      </div>
      <div class="card-news">
        <div class="card-event-infos">
          <h5><a href="http://greenplan.gov.sg/" class="external-link">Join the Green Plan </a></h5>
        </div>
      </div>
      <div class="card-news">
        <div class="card-event-infos">
          <h5><a href="https://www.mse.gov.sg/resources/" class="external-link">View More Resources </a></h5>
        </div>
      </div>
  </section>
</div>


