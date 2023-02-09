+++
fragment = "content"
#disabled = true
date = "2017-10-05"
weight = 100
#background = ""

#title = "HPC in the city"
#subtitle = ""
+++
<!DOCTYPE html>
<html>
<head>
 <script src="//cdn.wordart.com/wordart.min.js" async defer></script>
 <style>
.modal {
        position: fixed;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
        opacity: 0;
        visibility: hidden;
        transform: scale(1.1);
        transition: visibility 0s linear 0.25s, opacity 0.25s 0s, transform 0.25s;
    }
    .modal-content {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: white;
        padding: 1rem 1.5rem;
        width: 24rem;
        border-radius: 0.5rem;
    }
    .close-button {
        float: right;
        width: 1.5rem;
        line-height: 1.5rem;
        text-align: center;
        cursor: pointer;
        border-radius: 0.25rem;
        background-color: lightgray;
    }
    .close-button:hover {
        background-color: darkgray;
    }
    .show-modal {
        opacity: 1;
        visibility: visible;
        transform: scale(1.0);
        transition: visibility 0s linear 0s, opacity 0.25s 0s, transform 0.25s;
    }
</style>
<script>
   const modal = document.querySelector(".modal");
    const trigger = document.querySelector(".trigger");
    const closeButton = document.querySelector(".close-button");

    function toggleModal() {
        modal.classList.toggle("show-modal");
    }

    function windowOnClick(event) {
        if (event.target === modal) {
            toggleModal();
        }
    }

    trigger.addEventListener("click", toggleModal);
    closeButton.addEventListener("click", toggleModal);
    window.addEventListener("click", windowOnClick);
</script>
</head>
<body>
   <button class="trigger">Click here to trigger the modal!</button>
    <div class="modal">
        <div class="modal-content">
            <span class="close-button">&times;</span>
            <h1>Hello, I am a modal!</h1>
        </div>
    </div>

<center><img src="/images/HPCinthecity.png" alt="HPCinthecity Banner"></center>
<center><h2><b><u>November 5th - 9th, 2020</u></b></h2></center>
<center><h3><b>CONGRATS TO ALL OF OUR HACKERS, MENTORS, AND SUPPORT STAFF FOR A GREAT HPC IN THE CITY 2020</b></h3></center>
<center><h3>Thank you to the judges and speakers that helped HPC in the City be such a great success:</h3></center>
<center><h5><b>Judges:</b> <a href="https://www.uvm.edu/president/chief-information-officer">Simeon Ananou (University of Vermont)</a>, <a href="https://www.linkedin.com/in/kelly-gaither-5b39301/">Kelly Gaither (TACC)</a>, <a href="https://www.linkedin.com/in/rosalia-gomez-368035198/">Rosalia Gomez (TACC)</a>, <a href="https://www.linkedin.com/in/itsharveytime/">Christine Harvey (Sandie National Labs)</a>, <a href="https://www.linkedin.com/in/linda-hayden-5a8b424/">Linda Hayden (ECSU)</a>, <a href="https://www.linkedin.com/in/sarajeanes/">Sara Jeanes (Internet2)</a>, <a href="https://www.linkedin.com/in/gina-lamotte-790680a/">Gina LaMotte (EcoRise)</a>, <a href="https://www.linkedin.com/in/jay-lofstead-89674463/">Jay Lofstead (Sania National Labs)</a>, <a href="https://www.linkedin.com/in/lynn-vance-1978b26a">Lynn Vance (Ascension Healthcare)</a></h5></center>
<center><h5><b>Speakers: </b><a href="https://www.linkedin.com/in/jay-alameda-35b97a7/">Jay Alameda (XSEDE)</a>, <a href="https://www.linkedin.com/in/garybrantley/">Gary Brantleyt (City of Atlanta)</a>, <a href="https://www.linkedin.com/in/rqcai/">Runqiu Rachel Cai (Google)</a>, <a href="https://www.linkedin.com/mwlite/in/amy-cannon-46230b31">Amy Cannon (Omnibond)</a>, <a href="https://www.linkedin.com/in/ajdabrowski/">Anna Dabrowski (TACC)</a>, <a href="https://www.linkedin.com/in/itsharveytime/">Christine Harvey (Students@SC20)</a>, <a href="https://www.linkedin.com/in/tomkrueger1/">Tom Krueger (Intel)</a>, <a href="https://www.linkedin.com/in/nash-palaniswamy-045501/">Nash Palaniswamy (Intel)</a>, <a href="https://www.linkedin.com/in/vasiliadis/">Vas Vasiliadis (Globus)</a></h5></center>
<center><h3>Special thanks to our <a href="/sponsors">SPONSORS</a> and to the <a href="https://sc20.supercomputing.org/">SC20</a> conference</h3></center>
<!-- <center><h5>HackHPC in the news:</a></h5>
<dd><a href="https://sc20.supercomputing.org/2020/09/04/hpc-in-the-virtual-city/">HPC in the Virtual City</a></dd> 
<dd><a href="https://sciencegateways.org/community/blog/-/asset_publisher/p52xrlMcuiZb/blog/hack-pearc20-participants-solved-real-challeng-1">PEARC20 Solve Real Challenges</a></dd> -->
</center>

---

<div class="row" style="padding-top: 20px;">
  <div class="col-sm-5" align="center">
    <p style="padding-top: 50px"><b>Click for Photos</b></p>
    <a href="/hpc_photos"><img src="/images/HPCintheCityScreenCap.png" style="width: 100%; padding-top: 0px;"></a>

  </div>
  <div class="col-sm-7" align="left">
  <center><h3 style="padding-top: 0px"><a href="/pasthacks">Final Results:</a></h3></center>
  <center>
    <dt>Participants: 63</dt>
    <dt>Hackers: 31</dt>
    <dt>Mentors: 7</dt>
    <dt>Support Staff: 8</dt>
    <dt>Speakers: 9</dt>
    <dt>Teams: 9</dt>
    <dt>Student-Mentors: 3</dt>
    <dt>Hours: 96+</dt>
    <dt>HPC in the City Impact Award Winner:</dt>
    <dd><a href="/images/HotSpotHero6Final.pdf">Hotspot Hero 6</a> - <a href="https://github.com/mventparram/HotspotHero6">GITHUB</a></dd>
    <dt>HPC in the City Judges Choice Award Winner:</dt>
    <dd><a href="/images/FraudFindersPresentation.pdf">Fraud Finders</a> - <a href="https://github.com/frederick-morris/election-analytics">GITHUB</a></dd>
    <dt>HPC in the City Viewers Choice Award Winner:</dt>
    <dd><a href="/images/STSP_final.pdf">Silent Titanic Space Pythons</a> - <a href="https://github.com/abdulmohammed3/Covid-19_Disease_Transmission_and_Economic_Impact">GITHUB</a></dd>
    <dt>Final Presentations:</dt>
    <dd><a href="https://www.youtube.com/watch?v=NWPjygAVZ4c&list=PLTkmCX5R7siMgyw8seTHPY1P0qbL00GbD&index=10">Link to Video</a></dd>
    <dt>Visit <a href="/pasthacks">Past Hacks</a> for a full list of teams and projects</dt>
  </center>
  <br>
  </div>

</div>

---
<div class="row" style="padding-top: 00px;">
  <div class="col-sm-5" align="center">
    <h4>Word Cloud of Mentor Projects</h4>
    <div style="width: 400px; height: 400px; text-align: center;" data-wordart-src="//cdn.wordart.com/json/39rsyqlu1nx0" data-wordart-show-attribution></div>
  </div>
  <div class="col-sm-7" align="center">
    <h4>Map of Participants and Mentors</h4>
    <img src="/images/map.png" style="width: 100%; padding-top: 20px;">
</div>
  </div>

<!-- <div class="row">
    <div class="col-sm-5" style="padding-top: 0px; padding-bottom: 60px; text-align: center; display: block;">
    <img src="/images/SC2020Logoblack1.png" alt="SC2020logoblack" style="padding-top: 30px; width: 60%;">
  </div>
  <div class="col-sm-7" style="padding-top: 0px;"> -->
<!--     <center><h5 style="padding-top: 45px;">Registration for HPC in the City Hackaton is closed.</h5></center>
    <center><h5>Check back here or follow us on Twitter for updates during the hackaton</h5></center -->
<!--     <center>
      <h5 style="padding-top: 40px"><a href="https://docs.google.com/forms/d/1vyRObYtbs8L-HIoIYcISlMgf8gAfpoSFOAqXuK7zaU0/viewform?edit_requested=true">HACKER (Student) REGISTRATION</a> for HPC in the City Hackathon <b>CLOSES 10/19@MIDNIGHT</b><br> <a href="/images/Student_Flyer.pdf">Student Flyer</a></h5>
    </center> -->
<!--     <center>
      <h5 style="padding-top: 45px;"><a href="https://docs.google.com/forms/d/e/1FAIpQLSdmUAk6ZH-cM-LYjTrFmWSjX-gACGW3_BMEyYWGLSuPxFS4Zw/viewform">MENTOR/SUPPORT STAFF REGISTRATION</a> for HPC in the City Hackathon <br><a href="/images/Mentor_Flyer.pdf">Mentor Flyer</a>
      </h5></center>
    </div>
</div> -->

---
<center><h4>Hackathon Schedule and Trainings:</h4></center>
<center><h5><a href="https://jeaimehp.github.io/HackHPC-HPCintheCity20/#-schedule-of-events---november-5th---9th">HackHPC Schedule on Github</a></h5></center>
<div class="row" style="padding-top: 10px;">
  <div class="col-sm-7" align="center">
  <dl style="list-style: inside;">
    <center><h5>Trainings:</h5></center>
    <dt><b>Self Paced Training</b></dt>
    <dd><a href="/qwiklabs">Qwiklabs</a></dd>
    <dt><b>September 24th@10:00am ET - Mentor Training</b></dt>
    <dd><a href="/images/Mentor_Training.pdf">Slides</a> - <a href="https://www.youtube.com/watch?v=gtgzil_G5bA&feature=youtu.be">Video</a> - <a href="/images/A_Team_Challenge.pdf">Mentor MiniHack Challenge</a></dd>
    <dt><b>October 1st@10:00am ET - Github/Slack Training</b></dt>
    <dd><a href="/images/Slack_and_GitHub_Training.pdf">Slides</a> - <a href="https://youtu.be/WkAHAlApRDY">Video</a> - <a href="https://github.com/jeaimehp/HPC-inthe-City-ExcellentCode">Github Link</a></dd>
    <dt><b>October 8th@10:00am ET - Python Development Environment Training</b></dt>
    <dd><a href="/images/Python_Training.pdf">Slides</a> - <a href="https://youtu.be/cWHQ1BmxaUk">Video</a> - <a href="https://github.com/jeaimehp/HPC-in-the-City-Python-IDE-Demo">Sample Code</a></dd>
    <dt><b>October 15th@10:00am ET - Google Cloud Training</b></dt>
    <dd><a href="/images/Google_Cloud_Training.pdf">Slides</a> - <a href="https://youtu.be/ZWl8nd0F0rk">Video</a></dd>
    <dt><b>October 22nd@10:00am ET - CloudyCluster Training</b></dt>
    <dd><a href="/images/CloudyCluster_Training.pdf">Slides</a> - <a href="https://youtu.be/PN3s5kgQ8o0">Video</a> - <a href="http://gcp.cloudycluster.com/videos/index.html">CloudyCluster Tutorial</a></dd>
    <dt><b>October 29th@10:00am ET - Mentor Determined Pretraining</b></dt>
    <dd><a href="/images/Overview.pdf">Overview</a> - <a href="/images/Bringing_it_all_Together.pdf">Bringing it all Together</a> - <a href="/images/Data_Science.pdf">Data Science</a> <br> <a href="https://github.com/jeaimehp/HackHPC-HPCintheCity20/tree/gh-pages/DataScience">Data Science Github Repo</a> - <a href="/images/DataScience_Example.zip">Data Science Example Files</a> - <a href="https://youtu.be/3nac-2Et--Y">Video</a></dd>
    <dt><b>November 5th - HPC in the City HACKATHON begins!</b></dt>
    <dt><b>November 9th - Final Presentations</b></dt>
  </div>
  <div class="col-sm-5" align="center"><img src="/images/SC2020group.jpg" style="width: 90%; padding-top: 75px;"></div>
</div>

---

<div class="row" style="padding-top: 20px;">
  <div class="col-sm-5" align="center">
    <img src="/images/sc19image3.jpg" style="width: 90%; padding-top: 0px;">

  </div>
  <div class="col-sm-7" align="left">
  <center><h5 style="padding-top: 10px">GOALS:</h5></center>
  <center><p>The primary goal of the first HPC in the City is to host a hackathon focused on issues that directly impact the Atlanta Metro Area. These issues can range from societal to scientific utilizing available subject area specialists. The hackathon aims to harness the resources, skills, and knowledge found in the HPC community in an effort to provide applied exposure towards the conference host city local students of 2-4 year post-secondary educational institutions. In short, the hackathon will provide HPC skills and training while targeting problems that directly affect the participants. The hackathon is being planned from the outset as a virtual event.

Prior hackathon example projects:<a href="/pasthacks"> Past Hacks</a></p></center>
  <br>
  </div>

</div>

---

<div class="row" style="padding-top: 10px;">
  <div class="col-sm-7" align="left">
  <center><h5 style="padding-top: 10px">FAQ:</h5></center>

  <dl style="text-align: center; list-style: inside;">
    <dt>Do I need to know how to code to participate?</dt>
    <dd>No! All projects need a variety of skills, coding is just one of the many.</dd>
    <dt>Do I have to stay up the entire hackathon?</dt>
    <dd>No! You and your team decide on goals and mini-goals. Outside of some defined checkpoints, your time is your own.</dd>
    <dt>Is it a contest?</dt>
    <dd>Sometimes, but if it is we clearly define the judging criteria. We do often enjoy a little healthy competition from small tasks to the overall judging of the final product with sponsor-provided prizes.</dd>
    <dt>Will this interfere with me attending the conference or participating in a student program?</dt>
    <dd>Though we can not speak for your schedule or associate responsibilities, we do work closely with conference organizers to not conflict with other events. Commonly this is why the hackathons take place during night hours or in the case of HPC in the City, the week prior to the conference.</dd>
  </dl>
 
  <br>
  </div>
  <div class="col-sm-5" align="center"><img src="/images/sc19image2.jpg" style="width: 100%; padding-top: 60px;"></div>
</div>

</body>
</html>