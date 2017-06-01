---
title: "Bird's Eye View"
excerpt: "Using ROS, tum_ardone, ar_track_alvar and hand-written code, a TurtleBot 2 and an AR.Drone Bebop 2 team up to explore and map the surrounding environment."
author_profile: false
header:
  image: birds-eye-view-2.jpg
  teaser: birds-eye-view-1.jpg
sidebar:
  - title: "Role"
    image: usc-logo.png
    image_alt: "USC Logo"
    text: "Research Assistant"
  - title: "Responsibilities"
    text: "Redesigned the system from the network up to allow for more robust communication, tag tracking, and effective navigation. Implemented cooperative localization and scaled ORB-SLAM 2 to provide pose estimates of the UAV."
gallery:
  - url: birds-eye-slides-2.png
    image_path:  birds-eye-slides-2-th.png
    alt: "ORB-SLAM 2 camera view"
  - url: birds-eye-slides-3.jpg
    image_path:  birds-eye-slides-3-th.jpg
    alt: "Action photo"
  - url: birds-eye-slides-1.png
    image_path:  birds-eye-slides-1-th.png
    alt: "View from the TurtleBot's camera"
  - url: birds-eye-slides-4.jpg
    image_path:  birds-eye-slides-4-th.jpg
    alt: "Bebop with tag placed on the bottom"  
  - url: birds-eye-slides-5.jpg
    image_path:  birds-eye-slides-5-th.jpg
    alt: "TurtleBot setup"
  - url: birds-eye-slides-6.png
    image_path:  birds-eye-slides-6-th.png
    alt: "Swearingen results w/o ORB-SLAM"
---

{% include gallery caption="Photos of results and of the robots in action." %}

<h2>Summary</h2>
<p>This paper proposes a solution to the problem of cooperative exploration using an Unmanned Ground Vehicle (UGV) and an Unmanned Aerial Vehicle (UAV). More specifically, the UGV navigates through the free space, and the UAV provides enhanced situational awareness via its higher vantage point. The motivating application is search and rescue in a damaged building. A camera atop the UGV is used to track a fiducial tag on the underside of the UAV, allowing the UAV to maintain a fixed pose relative to the UGV. Furthermore, the UAV uses its front facing camera to provide a birds-eye-view to the remote operator, allowing for observation beyond obstacles that obscure the UGV's sensors. The proposed approach has been tested using a TurtleBot 2 equipped with a Hokuyo laser ranger finder and a Parrot Bebop 2. Experimental results demonstrate the feasibility of this approach. This work is based on several open source packages and the generated code is available on-line <a href="http://github.com/hoodsr/birds-eye-view">here</a>.</p>

<!--<h2>Additional Information</h2>-->


<h2>Participants</h2>

Shannon Hood, Kelly Benson, Patrick Hamod, Daniel Madison, and Ioannis Rekleitis.