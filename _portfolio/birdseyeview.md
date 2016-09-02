---
title: "Bird's Eye View"
excerpt: "Using ROS, tum_ardone, ar_track_alvar and hand-written code, a TurtleBot 2 and an AR.Drone Parrot 2.0 team up to explore and map the surrounding environment."
author_profile: false
header:
  image: birds-eye-view-2.jpg
  teaser: birds-eye-view-1.jpg
sidebar:
  - title: "Role"
    image: usc-logo.png
    image_alt: "logo"
    text: "Research Assistant"
  - title: "Responsibilities"
    text: "I worked primarily with the AR.Drone and was in charge of state estimation. I also configured the network on which the robots communicate."
gallery:
  - url: unsplash-gallery-image-1.jpg
    image_path: unsplash-gallery-image-1-th.jpg
    alt: "PTAM camera view"
  - url: unsplash-gallery-image-2.jpg
    image_path: unsplash-gallery-image-2-th.jpg
    alt: "Photo of the TurtleBot tag"
  - url: unsplash-gallery-image-3.jpg
    image_path: unsplash-gallery-image-3-th.jpg
    alt: "Action photo"
---

{% include gallery caption="Photos of the robots in action." %}

<h2>Summary</h2>
This project addresses the problem of cooperative exploration using an Unmanned Ground Vehicle (UGV) and an Unmanned Aerial Vehicle (UAV). More specifically, the UGV navigates through the free space, and the UAV provides enhanced situational awareness via its higher vantage point. The motivating application is search and rescue in a damaged building, where the UGV navigates on the ground utilizing the generalized Voronoi graph (GVG) while the UAV uses its bottom facing camera to maintain a fixed pose above the UGV by tracking a fiducial marker. Furthermore, the UAV uses its front facing camera to provide a bird's-eye-view to the remote operator and even observe beyond obstacles that obscure the sensors of the UGV. The proposed approach was tested using a TurtleBot 2 equipped with a Hokyuo laser ranger finder and a Parrot AR.Drone 2.0. Experimental results demonstrate the feasibility of our approach. This work was based on several open source packages and the generated code will be available online.

<!--<h2>Additional Information</h2>-->


<h2>Participants</h2>

Shannon Hood, Kelly Benson, Patrick Hamod, Daniel Madison, and Ioannis Rekleitis.