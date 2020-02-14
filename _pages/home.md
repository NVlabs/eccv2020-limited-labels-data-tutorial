---
layout: project
urltitle:  "New Frontiers for Learning with Limited Labels or Data"
title: "New Frontiers for Learning with Limited Labels or Data"
categories: eccv, tutorial, computer vision, robotics, machine learning, few-shot, unsupervised, semi-supervised
permalink: /
favicon: /static/img/eccv-final.png
bibtex: true
paper: true
acknowledgements: ""
---

<br>
<div class="row">
  <div class="col-xs-12">
    <center><h1>New Frontiers for Learning with Limited Labels or Data</h1></center>
    <center><h2>ECCV 2020 Tutorial, Glasgow, Scotland, UK</h2></center>
    <center>23-28 August 2020</center>
    <center>Location: <b>TDB</b></center>
  </div>
</div>


<div class="row" id="intro">
  <div class="col-md-12">
    <img src="{{ "/static/img/Glasgow.jpg" | prepend:site.baseurl }}">
    <p align="right"> Photo: Pixabay</p>
  </div>
</div>

<br>

<div class="row">
  <div class="col-xs-12">
    <h2>Introduction</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
Learning from limited data or supervision has garnered much research interest and many ideas to solve it are now well-established. Among them, learning from 1) partial or imperfect labels and 2) data from other related domains (synthetic data), modalities (text/audio/3D) or tasks have been extensively addressed in past tutorials/workshops. To improve network generalization when learning with limited data, the ideas of zero-, few-shot, meta- and task-transfer learning are ubiquitous. So, what's next? Are there new sub-problems that we have not yet investigated? Are there recent breakthroughs in other areas of vision and learning that can help us to better tackle this problem? Can we enable new applications?

<br>
<br>

To foster discussion and inspire new ideas along these lines, in this tutorial we will focus on new frontiers of learning with limited labels or data. We will explore emerging sub-problems, such as 1) omni-supervision, which is creating unified frameworks for learning from the entire spectrum of supervision -- with completely unsupervised, semi/weakly-supervised, to full-supervised data and 2) deep dreaming, which involves effectively inverting networks to generate training data. We will present some recent breakthroughs in other vision problems including, but not limited to, neural rendering; biologically-inspired self-learning and self-supervised image representation learning by exploiting video correspondences and 3D mesh reconstruction that can help to solve this problem. Finally, we will present some new applications including self-supervisedly learned discovery of visual object attributes.
      
<br id="schedule">
<br>
<br>

<div class="row">
  <div class="col-xs-12">
     <h2>Schedule</h2>
     <table class="table schedule" style="border:none !important;">
      <thead class="thead-light">
        <tr>
	  <th>#</th>
		  <th>Time</th>
          <th>Item</th>
        </tr>
      </thead>
      <tbody>

        <tr>
	  <td> </td>
		  <td>8:15am - 8:20am</td>
          <td>Welcome and Opening Remarks, <a href="#shalini">Shalini De Mello</a> (NVIDIA)</td>
        </tr>

	<tr>
	  <td>1</td>
		  <td>8:20am - 9:00am</td>
          <td><b>Biologically Inspired Self-Learning</b>, <a href="#anima">Animashree Anandkumar</a> (NVIDIA, Caltech)</td>
        </tr>

	<tr>
	  <td>2</td>
		  <td>9:00am - 9:45am</td>
          <td><b>Inverting Neural Networks for Data-free Knowledge Transfer</b>, <a href="#pavlo">Pavlo Molchanov</a> (NVIDIA)</td>
        </tr>

        <tr>
	  <td> </td>
		  <td>9:45am - 10:00am</td>
          <td>Coffee Break</td>
        </tr>

        <tr>
	  <td>3</td>
		  <td>10:00am - 10:45am</td>
          <td><b>Self-supervised Learning for Video Correspondences and 3D Mesh Reconstruction</b>, <a href="#sifei">Sifei Liu</a> (NVIDIA)</td>
        </tr>

	<tr>
	  <td>4</td>
		  <td>10:45am - 11:30am</td>
          <td><b>Object Attribute Discovery from Image Collections</b>, <a href="#varun">Varun Jampani</a> (Google Research)</td>
        </tr>

	<tr>
	  <td>5</td>
		  <td>11:30am - 12:15pm</td>
          <td><b>Omni-supervised Learning: Unifying Levels of Supervision</b>, <a href="#zhiding">Zhiding Yu</a> (NVIDIA)</td>
        </tr>


        <tr id="organizers">
	  <td> </td>
		  <td>12:15pm - 12:20pm</td>
          <td> Closing Remarks, <a href="#shalini">Shalini De Mello</a> (NVIDIA)</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>


<br>


<div class="row">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>

<div class="row speaker" id="shalini">
  <div class="col-sm-3 speaker-pic">
    <a href="https://research.nvidia.com/person/shalini-gupta">
      <img class="people-pic" src="{{ "/static/img/people/sdm.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://research.nvidia.com/person/shalini-gupta">Shalini De Mello</a>
      <h6>Nvidia</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Shalini De Mello is a Principal Research Scientist at NVIDIA. Her research interests are in computer vision and machine learning for human-computer interaction and smart interfaces. At NVIDIA, she has invented technologies for gaze estimation, and 2D and 3D head pose estimation, hand gesture recognition, face detection, video stabilization and GPU-optimized libraries for mobile computer vision. Her research over that past several years has pushed the envelope of HCI in cars and has led to the development of NVIDIA’s innovative <a href="https://www.nvidia.com/en-us/self-driving-cars/drive-ix/" target="_blank">DriveIX</a> product for smart <a href="https://www.youtube.com/watch?v=EVymqG9mdJg" target="_blank">AI-based automotive interfaces</a> for future generations of cars. She received doctoral and master’s degrees in Electrical and Computer Engineering from the University of Texas at Austin in 2008 and 2004, respectively.
    </p>
  </div>
</div>

<br>
<div class="row speaker" id="sifei">
  <div class="col-sm-3 speaker-pic">
    <a href="https://www.sifeiliu.net/">
      <img class="people-pic" src="{{ "/static/img/people/sl.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://www.sifeiliu.net/">Sifei Liu</a>
      <h6>Nvidia</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Sifei Liu obtained her PhD at the University of California, Merced in EECS, advised by <a href="https://faculty.ucmerced.edu/mhyang"> Prof. Ming-Hsuan Yang</a>. Her research interests lie in computer vision, deep learning, and the combination of both. She has worked on self-supervised co-segmentation, video correspondence and 3D mesh reconstruction. She has co-organized the <a href="https://xiaolonw.github.io/graphnn/"> Learning Representations via Graph-structured Networks</a> tutorial in conjunction with CVPR 2019.
    </p>
  </div>
</div>

<br>
<div class="row speaker" id="zhiding">
  <div class="col-sm-3 speaker-pic">
    <a href="https://www.sifeiliu.net/">
      <img class="people-pic" src="{{ "/static/img/people/zy.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://chrisding.github.io/index.htm">Zhiding Yu</a>
      <h6>Nvidia</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Zhiding Yu obtained his PhD in ECE from Carnegie Mellon University in 2017. His research interests include deep representation learning, weakly/semi-supervised learning, transfer learning and deep structured prediction, with their applications to vision problems. He has worked on noisy-label learning, self-training/semi-supervised learning for domain adaptation, uncertainty estimation, learning via data synthesis and weakly supervised learning. He is the winner of the Domain Adaptation for Semantic Segmentation Track, WAD Challenge at CVPR 2018.
    </p>
  </div>
</div>
<br>

<div class="row speaker" id="pavlo">
  <div class="col-sm-3 speaker-pic">
    <a href="https://research.nvidia.com/person/pavlo-molchanov">
      <img class="people-pic" src="{{ "/static/img/people/pm.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://research.nvidia.com/person/pavlo-molchanov">Pavlo Molchanov</a>
      <h6>Nvidia</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Pavlo Molchanov obtained PhD from Tampere University of Technology, Finland in the area of signal processing in 2014. His dissertation was focused on designing automatic target recognition systems for radars. Since 2015 he is with the Learning and Perception Research team at NVIDIA, currently holding a senior research scientist position. His research is focused on methods for neural network acceleration, and designing novel systems for human-computer interaction and human understanding. For network acceleration, he is interested in neural network pruning methods and conditional inference. For human understanding, he is working on landmark estimation, gesture recognition, hand pose estimation. He received the EuRAD best paper award in 2011 and EuRAD young engineer award in 2013.
    </p>
  </div>
</div>
<br>

<div class="row speaker" id="varun">
  <div class="col-sm-3 speaker-pic">
    <a href="https://varunjampani.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/vj.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://varunjampani.github.io/">Varun Jampani</a>
      <h6>Google Research</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Varun Jampani is a research scientist at Google Research, US. Prior to that, he was a research scientist at NVIDIA. His main research interests include content-adaptive neural networks, self-supervised visual discovery and deep structured prediction. His work on `SplatNet' received the `Best Paper Honorable Mention' award at CVPR 2018. In relevance to this tutorial, has worked on self-, unsupervised and semi-supervised learning, and on domain adaptation. He has co-organized a tutorial on <a href="https://xiaolonw.github.io/graphnn/">Learning Representations via Graph-structured Networks</a> in conjunction with CVPR 2019.
    </p>
  </div>
</div>
<br>

<div class="row speaker" id="anima">
  <div class="col-sm-3 speaker-pic">
    <a href="http://tensorlab.cms.caltech.edu/users/anima/">
      <img class="people-pic" src="{{ "/static/img/people/aa.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://tensorlab.cms.caltech.edu/users/anima/">Animashree Anandkumar</a>
      <h6>NVIDIA and California Institute of Technology</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
	TBD
    </p>
  </div>
</div>
<br>

<div class="row speaker" id="jan">
  <div class="col-sm-3 speaker-pic">
    <a href="http://jankautz.com/">
      <img class="people-pic" src="{{ "/static/img/people/jk.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://jankautz.com/">Jan Kautz</a>
      <h6>NVIDIA</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
	TBD
    </p>
  </div>
</div>
<br>