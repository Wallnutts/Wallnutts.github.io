---
title: Pressly - The Leather Fork Punch Press
excerpt: "Silent Leather Stitch Hole Puncher"
header:
  teaser: /assets/images/postphotos/pressly/teaser.jpg
  #overlay_color: "#333"
  overlay_image: /assets/images/postphotos/pressly/header.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #overlay_filter: rgba(255, 0, 0, 0.5)
  #overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  #caption: "Finished Product"
  actions:
    - label: "3D Files"
      url: "https://www.printables.com/social/278875-wallnutts/models"
teaser_image_path: /assets/images/postphotos/pressly/2.jpg #use .jpg files
#sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
#  - title: "Another Title"
#    text: "More text here."
date: 2024-01-06
#last_modified_at: 2021-07-07
---
# Introduction

![](/assets/images/postphotos/pressly/punching.gif "Punching")

A major part of the stitching process during leather working is punching stitch holes into leather. Usually done with a fork punch and mallet, it can be really loud especially for my neighbours as I lives in an apartment building. Hence I always found this part of the process a hassle as I would have to bring my whole setup downstairs when hammering so that I would not disturb them. 

This project is a solution for that. I felt that it could be possible to combine a arbor press with a leather fork punch to allow for easy, precise and quieter holepunching in a nice and cheap DIY 3D printed package. Given the strength of such plastic components, I thought at first that it would be more realistic to modify an existing arbor press to fit a fork punch but the size (>$100!) and cost of a regular metal one was a huge turn off. So I thought that it would make for a fun and good challenge as well as an experiment in pushing the strength of 3D printed plastic. 

Pressly is very durable and versatile, being able to punch >4 layers of leather with relative ease. Different leather forks can be swapped out easily by undoing a retaining M4 screw. Operation is similar to a drill press and allows for precise application of force such that you can pre-mark dents in the leather before committing to a hole punch.

![](/assets/images/postphotos/pressly/front.jpg "Front")

# Mechanism

![](/assets/images/postphotos/pressly/herringbone.png "gears")

Pressly's mechanism is very simple, consisting of a rack and pinion assembly using a herringbone gear profile. This is to maximise the contact area and shear strength of the print as they are the most critical parts in ensuring smooth operation. The rack holding the punching fork is also kept as close as possible to the main body for strength. 

# Print Settings + Assembly

- Rack, Pinion, Gear and Arm Attachment to be printed at >4 Walls >50% Infill with preferably PETG
- Axle to be printed at >4 Walls 100% infill with preferably PETG vertically up on the bed 
- Everything else ( Main body A & B , baseplate ) can be printed with more conservative settings 3 Walls, 20% Infill
- For the Arm Im using a long Phillips screwdriver with 6mm diameter cause it has a nice handle but you could just use a steel rod/3D printed rod.

Additional parts needed:
- 15x M3 Heat Set Inserts
- 1x M4 Heat Set Inserts
- 10x M3x10mm screws
- 5x  M3x20mm screws
- 6x  M3x30mm screws
- 1x  M4x10mm screw

![](/assets/images/postphotos/pressly/heatset3.jpg "heatsetinserts")

Heat Set every screw hole in the assembly. 

![](/assets/images/postphotos/pressly/gears.jpg "gears")

I did test if only plastic for these parts were sufficient but they seemed to start cracking on repeated hole punches at 3 or more layers of leather. For additional strength, you can drive the 6x M3x30mm screws straight into the gears to reinforce it.

I also added some cloth tape where the rack meets the mainbody while sliding up and down for a tighter friction fit but thats up to user preference. Surprisingly, the axle holds up despite the large forces applied as most of the force is transfered through the Arm attachment into the Main body.

There are 4 holes around the baseplate if you ever want to fix it to a table or swap in baseplate surfaces. Full .f3d and .3mf files are provided in the Printables link at the top.









