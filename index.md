---
layout: home
classes: wide
author_profile: true
header:
  image: "/assets/images/eth_banner.jpg"
---
<h1 id="about" class="small-title" style="padding-top: 40px; margin-top: -50px;">Grüezi!</h1>

<div class="justified-paragraph small-text">
    My name is Gokul Raju and I recently graduated with a Master's degree in <a href="https://ethz.ch/en/studies/master/degree-programmes/engineering-sciences/robotics-systems-and-control.html" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Robotics, Systems & Control</a> from <a href="https://ethz.ch/en.html" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">ETH, Zurich</a>. My research interests focus on Machine Learning, Computer Vision, Reinforcement Learning, Event-based Vision and Sequence Modelling (State-Space Models).
</div>

<div class="justified-paragraph small-text">
    Over the course of my Master's degree, I have had the opportunity to implement learning algorithms for complex computer vision tasks in both pixel-based and event-based domains and for dynamic real world tasks such as autonomous drone racing at the <a href="https://rpg.ifi.uzh.ch/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Robotics and Percpetion Group</a> in <a href="https://www.uzh.ch/en.html" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">University of Zurich</a> under <a href="https://rpg.ifi.uzh.ch/people_scaramuzza.html" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Prof. Davide Scaramuzza</a>.
</div>

<div class="justified-paragraph small-text">
    Prior to my Masters, I completed my <a href="https://www.hw.ac.uk/dubai/study/undergraduate/mechanical-engineering" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">BEng (Hons) in Mechanical Engineering</a> at <a href="https://www.hw.ac.uk/dubai/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Heriot-Watt University, Dubai</a>; I was awarded with the <a href="https://www.hw.ac.uk/alumni/watt-club/medals-prizes.htm" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Watt Club Medal</a> and <a href="https://www.hw.ac.uk/alumni/watt-club/medals-prizes.htm" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">The James Anderson Memorial Prize</a>.
</div>

<br>

<h2 id="projects" class="small-title" style="padding-top: 40px; margin-top: -50px;">Projects</h2>

<div class="image-text-container">
    <div class="text-content">
        <p class="project-title"><strong>State Space Models for Efficient Reinforcement Learning in Quadrotors</strong></p>
        <p class="project-desc justified-paragraph">Proposed the first SSM-based RL framework for Autonomous Drone Racing for both state-based and vision-based domains. Developed a custom PPO JAX-Implementation to train the drone racing policies for the <a href="https://uzh-rpg.github.io/flightmare/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Flightmare Simulator</a>. Achieved SOTA performance – 8-10% faster lap-times in comparison to existing drone racing policies on the Flightmare Simulator by effectively capturing and utilizing the rich temporal information embedded in the drone racing environment.
        <br>
        <a href="https://github.com/BjfpgZOC/ETH-Master-Thesis" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[Report]</a>
        </p>
    </div>
        <div class="grid-container-two-right-column">
        <img src="assets/images/thesis_flight.png" alt="Flightmare Environment" class="grid-item-temp1">
        <img src="assets/images/thesis_track.png" alt="Racetrack Trajectory" class="grid-item-temp1">
    </div>
</div>

<div class="image-text-container">
        <div class="grid-container-four-left">
        <img src="assets/images/sempro_cam.gif" alt="Camera" class="grid-item-temp1">
        <img src="assets/images/sempro_event.gif" alt="Events" class="grid-item-temp1">
        <img src="assets/images/sempro_gt.gif" alt="GT Optical Flow" class="grid-item-temp1">
        <img src="assets/images/sempro_flow.gif" alt="Predicted Optical Flow" class="grid-item-temp1">
    </div>
    <div class="text-content">
        <p class="project-title"><strong>Pushing the limits of Optical Flow Estimation in Event Cameras</strong></p>
        <p class="project-desc justified-paragraph">Proposed the first multi-event learning based optical flow framework for event-based vision. Achieved SOTA performance on event-based optical flow benchmarks such as <a href="https://dsec.ifi.uzh.ch/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">DSEC-Flow</a> and <a href="https://daniilidis-group.github.io/mvsec/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">MVSEC</a>.
        <br>
        <a href="https://github.com/BjfpgZOC/ETH-Semester-Thesis" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[Report]</a>
        <br>
        <br>
        An extension of this work was published as a Workshop Paper.
        <br>
        <strong>Perturbed State Space Feature Encoders for Optical Flow with Event Cameras</strong>
        <br>
        <em>Gokul Raju Govinda Raju, Nikola Zubi´c, Marco Cannici, Davide Scaramuzza</em>
        <br>
        <em>IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), Nashville, 2025</em>
        <br>
        <a href="https://arxiv.org/abs/2504.10669" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[arXiv]</a><a href="https://dsec.ifi.uzh.ch/uzh/dsec-flow-optical-flow-benchmark/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[Benchmark]</a>
        </p>
    </div>
</div>

<div class="image-text-container">
    <div class="text-content">
        <p class="project-title"><strong>Spaceship Obstacle Avoidance and Trajectory Planning</strong></p>
        <p class="project-desc justified-paragraph">Implemented a <a href="https://arxiv.org/abs/2106.09125" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">SCvx (Successive Convexification)</a> planning and control algorithm for a 2-D spaceship to effectively avoid static obstacles (planets) & dynamic obstacles (satellites) and to dock with the docking station.
        <br>
        <a href="https://github.com/BjfpgZOC/ETH-PDM4AR-Spaceship-Project" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[Code]</a>
        </p>
    </div>
        <div class="grid-container-two-right-column">
        <img src="assets/images/dock.gif" alt="Docking" class="grid-item-temp1">
        <img src="assets/images/sat_dock.gif" alt="Docking with satellites" class="grid-item-temp1">
    </div>
</div>

<div class="image-text-container">
        <div class="grid-container-four-left">
        <img src="assets/images/fifa.gif" alt="FIFA test video" class="grid-item-temp1">
        <img src="assets/images/detection.gif" alt="Soccer ball detection" class="grid-item-temp1">
        <img src="assets/images/track_2d.gif" alt="2-D Trajectory" class="grid-item-temp1">
        <img src="assets/images/track_3d.gif" alt="3-D Trajectory" class="grid-item-temp1">
    </div>
    <div class="text-content">
        <p class="project-title"><strong>Robust Soccer Ball Detection and Tracking (FIFA) </strong></p>
        <p class="project-desc justified-paragraph">Developed an end-to-end pipeline to effectively detect & track soccer balls in both sharp and blurred broadcast frames. Generated a synthetic dataset with <a href="https://research.google/blog/introducing-google-research-football-a-novel-reinforcement-learning-environment/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">Google Research Football Simulator</a> and implemented transfer learning on the <a href="https://docs.ultralytics.com/models/yolov8/" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">YOLOv8n</a> object detection model to achieve a 216% increase in precision (0.31 to 0.98) and 717% increase in recall (0.12 to 0.98) compared to the base model. Integrated the fine-tuned detection model with a state-of-the art approach <a href="https://arxiv.org/abs/2111.14465" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">MfB (Motion from Blur)</a> to hadnle high-speed blurry motion. Combined multi-view detections with camera pose information to triangulate the position of the soccer ball (95.78% tracking accuracy at 0.75 IoU) and visualized the tracking results by generating 3D trajectories for coaching analytics.
        <br>
        <a href="https://github.com/BjfpgZOC/ETH-3DVision-Project" style="color:rgb(33, 140, 227); text-decoration: none;" target="_blank">[Report]</a>
        </p>
    </div>
</div>
