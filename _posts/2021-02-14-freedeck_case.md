---
layout: post
title:  "Freedeck Case and 3D PCB-Model"
date:   2021-02-14
excerpt: "I designed a 3D model for the Freedeck PCB and a Case for it"
#excerpt_separator: <!--more-->
project: true
tag: [freedeck, freedeck case, freedeck model]

comments: true
---
I recently came across the <a href="https://github.com/FreeYourStream"> Freedeck project</a>, which allows people to build their own customizable control pad. It's a small keyboard with keys that can be programmed to execute different marcros and functions. As a special feature, each key has an own small display, which can show icons to explain the functionality underneath.

While taking a first glance into the project, I noticed that some dimensions had changed in the last PCB revision and there was no longer a suitable case for it. At the same time, there was a GitHub request for a 3D model of the PCB to help with the creation of cases. After a quick look at the PCB files provided, I decided to tackle this task and create a 3D PCB model and provide it as a .step file, to make it compatible with most design software.

At the moment, I have not been able to verify the correct dimensions, as the electrical parts are still in shipping due to the Chinese New Year festival. But other users on Discord have confirmed the Dimensions as:" Your model looks pretty accurate including the SD Card reader protrusion, USB connection and holes. I have a slightly larger gap between the 2 rows on the OLEDs, but that's probably due to the different manufacturers." 


<a href="/assets/img/posts/2021-02-14/freedeck_pcb_through_1_1.step">DOWNLOAD</a> - .step Freedeck PCB v1.1 throug-hole
<figure class="full">
    <a href="/assets/img/posts/2021-02-14/freedeck_pcb_through_1_1.PNG"><img src="/assets/img/posts/2021-02-14/freedeck_pcb_through_1_1.PNG"></a>
    <figcaption>3D Model of the Freedeck v1.1 throug-hole PCB.</figcaption>
</figure>

After creating the PCB, I decided to design a case as well.
<figure class="full">
    <a href="/assets/img/posts/2021-02-14/first_render.PNG"><img src="/assets/img/posts/2021-02-14/first_render.PNG"></a>
    <figcaption>First rendering of the Freedeck Case</figcaption>
</figure>
Here you can see a first rendering. I have already 3D printed it and will publish the files after I have made minor adjustments and could check the correct fitment. For that, I also need to wait for the electrical parts.

---
Update May 2021:

In the meantime the parts arrived and the final tests are completed.
<figure class="third">
    <a href="/assets/img/posts/2021-02-14/2021_0504_16394400_3.jpg"><img src="/assets/img/posts/2021-02-14/2021_0504_16394400_3.jpg"></a>
    <a href="/assets/img/posts/2021-02-14/2021_0504_16401700_2.jpg"><img src="/assets/img/posts/2021-02-14/2021_0504_16401700_2.jpg"></a>
    <a href="/assets/img/posts/2021-02-14/2021_0504_16414400.jpg"><img src="/assets/img/posts/2021-02-14/2021_0504_16414400.jpg"></a>    
    <figcaption>Pictures of the case for the pcb v1.1</figcaption>
</figure>
I also created an updated version of case to fit the v1.2 PCB.
- PCB v1.2 moved the SD-Card reader further inwards, and allowed to remove the SD-Card slot.
- PCB v1.2 fixed the alignment of the screw holes (they are now symmetrical).


You can find the .stl files (v1.1 and v1.2) and an assembly + print instruction at <a href="https://www.thingiverse.com/thing:4849163"> Thingiverse</a>.



---
Response/Achievements:
- My Freedeck Case created positive feedback from the Freedeck-Team and it got included in the official Freedeck-Wiki.
- Multiple requests to produce cases for people without a 3D Printer. If the request came from people inside of Europe, I was able provided this service on a "pay what you think it's worth to you" base.
- Provided in depth support and guidance for people trying to print the case or got general questions via <a href="https://discord.com/invite/sEt2Rrd"> Discord</a>.

