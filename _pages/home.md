---
layout: single
read_time: false
comments: false
share: false
permalink: /
---

<style>
#projects {
    margin: 0;
    padding: 0;
    background-color: white;
    font-family: sans-serif;
    font-size: 16px;
    line-height: 1.4;
    color: #333;
    padding-bottom: 20px;
}
#pubs {
    margin: 0;
    padding: 0;
    background-color: white;
    font-family: sans-serif;
    font-size: 16px;
    line-height: 1.4;
    color: #333;
    /* margin-bottom: 50px;  */
}
#about {
    margin-bottom: 50px; 
}


.container {
    margin-left: auto;
    margin-right: auto;
    padding-left: 15px;
    padding-right: 15px;
}

.row {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
}

.timespan {
    grid-column: span 1;
    font-size: 14px;
    text-align: right;
    padding-right: 5px;
    color: #bbb;
}

.entry-dot {
    position: absolute;
    top: 0px;
    left: -8px;
    width: 10px;
    height: 10px;
    border-radius: 7px;
    background-color: #cfcfcf;
    border: 2px solid white;
}

.ico {
    grid-column: span 1;
    vertical-align: top;
    border-left: 2px solid #cfcfcf;
    position: relative;
}

.ico img {
    border-radius: 5px;
    width: 100%;
    max-width: 80px;
    margin-left: 10px;
}

img {
    overflow-clip-margin: content-box;
    overflow: clip;
}

.desc {
    grid-column: span 10;
    vertical-align: top;
    font-size: 17px;
    padding-left: 20px;
    padding-bottom: 20px;
}

.project {
    margin-bottom: 10px;
    padding-bottom: 10px;
    border-bottom: 1px solid #eee;
}

.pico {
    float: left;
    margin-right: 10px;
}

.pico img {
    height: 80px;
    border-radius: 5px;
    border: 1px solid #999;
}

.half {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 120%;
}
figcaption {
    margin-bottom: 0.5em;
    color: #777a7d;
    font-family: sans-serif;
    font-size: .75em;
}

.fluid-width-video-wrapper {
    width: 100%;
    position: relative;
    padding: 0;
}
.fluid-width-video-wrapper iframe{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
</style>

<div id="about">

<div id="history" class="container">

<div class="entry row">
<div class="timespan">
    2024 - 
</div>
<div class="ico">
    <div class="entry-dot"></div>
    <img src="assets/images/hs-logo.png">
</div>
<div class="desc">
    Currently building <a href="https://heartspacehealth.co.nz/">Heartspace</a>...
</div>
</div>

<div class="entry row">
<div class="timespan">
    2019 - 2023
</div>
<div class="ico">
    <div class="entry-dot"></div>
    <img src="assets/images/halter-logo.png">
</div>
<div class="desc">
    I was Director of Data at <a href="https://www.halterhq.com/">Halter</a> where I led the data science team for models on pasture growth forecasting and on-edge position tracking.
    This included data collection, incorporating the relevant pasture and animal science, and considering the appropriate model architectures.
    <figure>
        <img src="/assets/images/halter-3.jpg">
        <figcaption>Developing pasture growth models on the Halter Research & Development farm.</figcaption>
    </figure>
    In the senior leadership team we managed a number of tough business decisions across logistics, customer needs, and R&D risk management in the face of demanding growth expectations and tight market conditions. We also set up research relationships with universities who are world leaders in agriculture research.
    <figure>
        <img src="/assets/images/halter-4.jpg">
        <figcaption>Kicking off the collaboration with Tasmania Institute of Agriculture for research on dairy farm productivity.</figcaption>
    </figure>
    Early on at Halter I was the leader of various systems engineering projects. In this role I developed a system for efficiently calibrating the IMU sensor on thousands of devices, and led the effort to efficiently manage power across the fleet of devices, enabling Halter to deploy into a new market. I was with Halter through the Series B & C funding rounds (USD $74M raised), over which time the company grew from 30 to 150 employees.
</div>
</div>

<div class="entry row">
<div class="timespan">
    2015 - 2019
</div>
<div class="ico">
    <div class="entry-dot"></div>
    <img src="assets/images/uoa-logo.jpeg">
</div>
<div class="desc">
    My PhD in biomedical engineering explored how <a href="https://www.auckland.ac.nz/en/abi/our-research/research-groups-themes/bioinstrumentation-laboratory/needle-free-jet-injection.html">needle free drug delivery</a> could be controlled more accurately using laser imaging. I showed the depth of the injection could be calculated by measuring the scattered light pattern produced from light in the water jet. I built a laser-jet injection device, simulated the optics of skin tissue, and solved the inverse problem to calculate injection depth from scattered laser-light patterns.
    <figure>
        <img src="/assets/images/phd-2.jpeg">
        <figcaption>My colleagues and I with the jet injector system, which delivers vaccines in a fraction of a second without a needle.</figcaption>
    </figure>
    In 2016 I was a visiting researcher at Massachusetts Institute of Technology, on a 3-month exchange. During my PhD I published 3 journal papers, presented at international conferences and my work was nominated for thesis of the year. 
    <figure>
        <img src="/assets/images/phd-1.jpeg">
        <figcaption>A presentation on my thesis for the UoA 3-minute thesis competition.</figcaption>
    </figure>
    My PhD brought my background in mathematical modelling together with my passion for applied engineering in the biomedical domain. I developed a greater appreciation for hardware and electronics and honed my skills in experimentation and iterative development.
</div>
</div>

<div class="entry row">
<div class="timespan">
    2014 - 2018
</div>
<div class="ico">
    <div class="entry-dot"></div>
    <img src="assets/images/sm-logo.jpeg">
</div>
<div class="desc">
    As a Research Engineer at <a href="https://www.soulmachines.com/">Soul Machines</a> under <a href="https://nzawards.org.nz/winners/mark-sagar-phd-frsnz/">Dr. Mark Sagar</a>, I developed a neural network for motor control of a virtual human avatar. The avatar could be trained to draw and play pong, built on a simple network called a self-organising map.
    <figure class="half">
        <a><div class="fluid-width-video-wrapper" style="padding-top: 50%;"><iframe src="https://www.youtube.com/embed/fNWjKtVWToc?si=IMOpwUs-0DZHRM5e" frameborder="0" allowfullscreen="" id="fitvid0"></iframe></div></a>
        <figcaption>Demonstrating the avatar, BabyX, which is controlled by neural networks and can interact in real-time.</figcaption>
    </figure>
    I learnt to build models in a streaming, 3D graphics environment, and continued to work for Soul Machines during my PhD. When I began at Soul Machines in 2014 we were a team of six. By the time I left the company was over 70 employees and had raised USD $7.5m. As of 2024, Soul Machines has raised USD$135m in funding.
</div>
</div>

<div class="entry row">
<div class="timespan">
    2012 - 2014
</div>
<div class="ico">
    <div class="entry-dot"></div>
    <img src="assets/images/uoa-logo.jpeg">
</div>
<div class="desc">
    BE at The University of Auckland, top of class in Engineering Science. This is where I developed a passion for applied mathematical modelling. My honours project was in the research lab which would later become Soul Machines. Optimisation problems were a theme throughout the degree, a notable project involving the simulation of power generation of a wind turbine, which we validated by building and testing it at the university's wind tunnel.
    <figure>
        <a href="/assets/images/uoa-2.jpeg" class="image-popup"><img src="/assets/images/uoa-2.jpeg"></a>
    <figcaption>Testing the wind turbine design at the wind tunnel</figcaption>
    </figure>
    Community involvement has played an important role in shaping how I like to lead teams. Through my undergraduate degree I tutored Physics and Biology in low socio-economic high schools, and was a supervisor in a hostel for first-year and international students.
    <figure>
        <a href="/assets/images/uoa-3.jpeg" class="image-popup"><img src="/assets/images/uoa-3.jpeg"></a>
    <figcaption>Finishing up the year with the students at International House, UoA and the resident advisor team.</figcaption>
    </figure>
</div>
</div>

</div>
</div>


## Featured projects
<div id="projects">

<div class="project">
<div class="pico"><img src="assets/images/ebyt.png"></div>
<div class="pdesc">I built <a href="https://github.com/kieranabrennan/every-breath-you-take">Every-Breath-You-Take</a> to be able to train heart rate variability with a Polar H10 heart rate monitor. The project received some attention after being on the front page of <a href="https://news.ycombinator.com/item?id=37538028">Hacker News</a> for a week.</div>
<div class="pend"></div>
</div>

<div class="project">
<div class="pico"><img src="assets/images/ecg.png"></div>
<div class="pdesc"><a href="https://github.com/kieranabrennan/to-beat-or-not-to-beat">To-Beat-Or-Not-To-Beat</a> is a CNN model for detecting Atrial Fibrillation, a common type of heart arrhythmia. It is an implementation of a <a href="https://pubmed.ncbi.nlm.nih.gov/30106699/">recent paper on the topic</a> adapted to make detections from a Polar H10 heart rate monitor.</div>

<div class="pend"></div>
</div>

<div class="project">
<div class="pico"><img src="assets/images/trp-logo.jpeg"></div>
<div class="pdesc">In 2018 me and a friend started <a href="https://www.instagram.com/therestproject/">The Rest Project</a> to bring the science of flotation therapy (sensory deprivation) to more people. Hundreds of people around NZ used our programs to manage stress. </div>
<div class="pend"></div>
</div>

</div>



## Publications
<div id="pubs">
<p>Also on <a href="https://scholar.google.com/citations?user=wtPJVG0AAAA">Google Scholar</a></p>

<ul>
  <li>
    <a href="https://iopscience.iop.org/article/10.1088/2040-8986/aaf4db/meta">High-speed light source depth estimation using spatially-resolved diffuse imaging.</a>
    <span style="color: green;">Journal of Optics, 21 (1), 015604.</span> Kieran Brennan, Dan Kulasingham, Poul Nielsen, Andrew Taberner, Bryan Ruddy.
  </li>
  <li>
    <a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10493/104931S/High-speed-spatially-resolved-diffuse-imaging-for-jet-injection-depth/10.1117/12.2288874.short#_=_">High speed spatially resolved diffuse imaging for jet injection depth estimation.</a>
    <span style="color: green;">Dynamics and Fluctuations in Biomedical Photonics XV (Vol. 10493, pp. 202-208). SPIE.</span> Kieran Brennan, Bryan Ruddy, Poul Nielsen, Andrew Taberner
  </li>
  <li>
    <a href="https://ieeexplore.ieee.org/abstract/document/7592075">Light source depth estimation in porcine skin using spatially resolved diffuse imaging.</a>
    <span style="color: green;">In 2016 38th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC) (pp. 5917-5920). IEEE.</span> Kieran Brennan, Bryan Ruddy, Poul Nielsen, Andrew Taberner
  </li>
</ul>
</div>

