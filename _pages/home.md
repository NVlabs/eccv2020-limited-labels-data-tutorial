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
    <center>Sunday, August 23rd, 2020</center>
    <center>Location: <b>Room M1 </b></center>
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
		  <td>8:00am - 8:15am</td>
          <td>Welcome and Opening Remarks, <a href="#shalini">Shalini De Mello</a> (NVIDIA)</td>
        </tr>

	<tr>
	  <td>1</td>
		  <td>8:15am - 8:50am</td>
          <td><b>Biologically Inspired Self-Learning</b>, <a href="#anima">Animashree Anandkumar</a> (NVIDIA, Caltech)</td>
        </tr>

	<tr>
	  <td>2</td>
		  <td>8:50am - 9:25am</td>
          <td><b>Inverting Neural Networks for Data-free Knowledge Transfer</b>, <a href="#pavlo">Pavlo Molchanov</a> (NVIDIA)</td>
        </tr>
        
        <tr>
        <td>2</td>
            <td>9:25am - 10:00am</td>
            <td><b>Limitless Labels in a Labelless World: Weak Supervision with Noisy Labels</b>, <a href="#arash">Arash Vahdat</a> (NVIDIA)</td>
          </tr>

        <tr>
	  <td> </td>
		  <td>10:00am - 10:10am</td>
          <td>Coffee Break</td>
        </tr>
        
        <tr>
          <td>3</td>
              <td>10:10am - 10:45am</td>
              <td><b>Object Attribute Discovery from Image Collections</b>, <a href="#varun">Varun Jampani</a> (Google Research)</td>
            </tr>

        <tr>

        <tr>
	  <td>4</td>
		  <td>10:45am - 11:20am</td>
          <td><b>Self-supervised Learning for Video Correspondences and 3D Mesh Reconstruction</b>, <a href="#sifei">Sifei Liu</a> (NVIDIA)</td>
        </tr>

	
	  <td>5</td>
		  <td>11:20am - 11:55pm</td>
          <td><b>Omni-supervised Learning: Unifying Levels of Supervision</b>, <a href="#zhiding">Zhiding Yu</a> (NVIDIA)</td>
        </tr>


        <tr id="organizers">
	  <td> </td>
		  <td>11:55pm - 12:00pm</td>
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
      <a href="https://research.nvidia.com/person/shalini-gupta">Shalini De Mello</a> <a href="https://twitter.com/shalinidemello"><img src="{{ "/static/img/Twitter_Social_Icon_Rounded_Square_Color.png" | prepend:site.baseurl }}"></a>
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
Sifei Liu is a senior research scientist at Learning and Perception Research (LPR) at NVIDIA. She obtained her Ph.D. at the University of California Merced, department of EECS, advised by Professor Ming-Hsuan Yang. Her research interests are in computer vision (low-level vision, semantic segmentation and 3D scene understanding), deep learning (graph-structured modules, self-supervised learning), and the combination of both. She worked as an intern student in Baidu IDL from 2013 to 2014, multimedia lab in CUHK in 2015, and NVIDIA research in 2017. She is also the recipient of the Baidu Graduate Fellowship in 2013 and the Rising Star EECS in 2019. She has co-organized the <a href="https://xiaolonw.github.io/graphnn/"> Learning Representations via Graph-structured Networks</a> tutorial in conjunction with CVPR 2019.
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
Zhiding Yu is a Research Scientist with ML Research at NVIDIA. He obtained Ph.D. in ECE from Carnegie Mellon University in 2017, and M.Phil. in ECE from The Hong Kong University of Science and Technology in 2012. His research interests mainly focus on deep representation learning, weakly/semi-supervised learning, transfer learning and deep structured prediction, with their applications to vision and robotics problems. His research goal is to leverage the abundant domain knowledge, priors and structured information to eliminate uncertainties with minimum human supervision and uncover the secret towards true visual intelligence. He has conducted research internships at Adobe, Microsoft Research and Mitsubishi Electric Research Laboratories. He is the winner of the Domain Adaptation for Semantic Segmentation Track, WAD Challenge at CVPR 2018.
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
      <a href="https://research.nvidia.com/person/pavlo-molchanov">Pavlo Molchanov</a> <a href="https://twitter.com/PavloMolchanov"><img src="{{ "/static/img/Twitter_Social_Icon_Rounded_Square_Color.png" | prepend:site.baseurl }}"></a>
      <h6>Nvidia</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
Pavlo Molchanov obtained his PhD from the Tampere University of Technology, Finland in the area of signal processing in 2014. His dissertation was focused on designing automatic target recognition systems for radars. Since 2015 he is with the Learning and Perception Research team at NVIDIA, currently holding a senior research scientist position. His research is focused on methods for neural network acceleration, and designing novel systems for human-computer interaction and human understanding. For network acceleration, he is interested in neural network pruning methods and conditional inference. For human understanding, he is working on landmark estimation, gesture recognition, hand pose estimation. He received the EuRAD best paper award in 2011 and EuRAD young engineer award in 2013.
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
Varun Jampani is a Research Scientist at Google Research in Cambridge, US. Prior to that, he was a Research Scientist at NVIDIA Research. He works in the areas of machine learning and computer vision and his main research interests include content-adaptive neural networks, self-supervised visual discovery, motion understanding and novel view synthesis. He obtained his Ph.D. with highest honors at Max Planck Institute for Intelligent Systems (MPI) in 2017. He obtained his BTech and MS from International Institute of Information Technology, Hyderabad (IIIT-H), India, where he was a gold medalist. His work on <a href="http://openaccess.thecvf.com/content_cvpr_2018/papers/Su_SPLATNet_Sparse_Lattice_CVPR_2018_paper.pdf">“SplatNet”</a> received the Best Paper Honorable Mention award at CVPR 2018.
    </p>
  </div>
</div>
<br>

<div class="row speaker" id="arash">
  <div class="col-sm-3 speaker-pic">
    <a href="http://latentspace.cc/arash_vahdat/">
      <img class="people-pic" src="{{ "/static/img/people/av.jpg" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="http://latentspace.cc/arash_vahdat/">Arash Vahdat</a> <a href="https://twitter.com/ArashVahdat"><img src="{{ "/static/img/Twitter_Social_Icon_Rounded_Square_Color.png" | prepend:site.baseurl }}"></a>
      <h6>NVIDIA</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
    Arash Vahdat is a senior research scientist at NVIDIA research specializing in machine learning and computer vision. Before joining NVIDIA, he was a research scientist at D-Wave Systems where he worked on weakly supervised learning from noisy labeled data and deep generative learning with discrete latent variable models. Prior to D-Wave, Arash was a PhD student under Greg Mori’s supervision working on latent variable frameworks for visual analysis, then a research faculty member at Simon Fraser University, where he led several research projects at the intersection of deep learning and video analysis. Arash completed his undergrad in computer engineering at the Sharif University of Technology. His area of research includes weakly-supervised learning, neural architecture search, probabilistic deep learning, and generative learning. More information regarding Arash's background can be found on his personal <a href="http://latentspace.cc/arash_vahdat/">website</a>.
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
      <a href="http://tensorlab.cms.caltech.edu/users/anima/">Animashree Anandkumar</a> <a href="https://twitter.com/AnimaAnandkumar"><img src="{{ "/static/img/Twitter_Social_Icon_Rounded_Square_Color.png" | prepend:site.baseurl }}"></a>
      <h6>NVIDIA and California Institute of Technology</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
	Anima Anandkumar is the Director of ML Research at NVIDIA and Bren Professor at Caltech. She was previously a Principal Scientist at Amazon Web Services. She has received several honors such as Alfred. P. Sloan Fellowship, NSF Career Award, Young investigator awards from DoD, and Faculty Fellowships from Microsoft, Google and Adobe. She is part of the World Economic Forum's Expert Network. She is passionate about designing principled AI algorithms and applying them in interdisciplinary applications.  Her research interests include tensor methods, optimization, and large-scale learning.
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
      <a href="http://jankautz.com/">Jan Kautz</a> <a href="https://twitter.com/jankautz"><img src="{{ "/static/img/Twitter_Social_Icon_Rounded_Square_Color.png" | prepend:site.baseurl }}"></a>
      <h6>NVIDIA</h6>
    </div>
  </div>
  <div class="col-md-9">
    <b>Biography</b>
    <p class="speaker-bio">
	Jan Kautz is VP of Learning and Perception Research at NVIDIA. Jan and his team pursue fundamental research in the areas of computer vision and deep learning, including visual perception, geometric vision, generative models, and efficient deep learning. Before joining NVIDIA in 2013, Jan was a tenured faculty member at University College London. He holds a BSc in Computer Science from the University of Erlangen-Nürnberg (1999), an MMath from the University of Waterloo (1999), received his PhD from the Max-Planck-Institut für Informatik (2003), and worked as a post-doctoral researcher at the Massachusetts Institute of Technology (2003-2006).
    </p>
  </div>
</div>
<br>
