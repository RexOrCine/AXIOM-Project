# AXIOM-Project

Welcome to the world of apertus°

... and the home of FOSS, open hardware, community-driven, professional digital cinema and imaging tools.

Individual projects being worked on inside the community are quite complex and if you're unfamiliar then getting an initial overview can be difficult. Please accept these pointers to assist.  

<br />
<br />


<p align="center">
  <strong>Client</strong>

  <br />

  <a href="https://david-dm.org/Chocobozzz/PeerTube?path=client">
    <img src="https://david-dm.org/Chocobozzz/PeerTube.svg?path=client" alt="Dependency Status" />
  </a>

  <a href="https://david-dm.org/Chocobozzz/PeerTube?path=client&type=dev">
    <img src="https://david-dm.org/Chocobozzz/PeerTube/dev-status.svg?path=client" alt="devDependency Status" />
  </a>
  
  <a href="https://www.browserstack.com/automate/public-build/VXBPc0szNjUvRUNsREJQRFF6RkEvSjJBclZ4VUJBUm1hcS9RZGpUbitRST0tLWFWbjNEdVN6eEZpYTk4dGVpMkVlQWc9PQ==--644e755052bf7fe2346eb6e868be8e706718a17c%">
    <img src='https://www.browserstack.com/automate/badge.svg?badge_key=VXBPc0szNjUvRUNsREJQRFF6RkEvSjJBclZ4VUJBUm1hcS9RZGpUbitRST0tLWFWbjNEdVN6eEZpYTk4dGVpMkVlQWc9PQ==--644e755052bf7fe2346eb6e868be8e706718a17c%'/>
  </a>
</p>

<p align="center">
  <strong>Server</strong>

  <br />

  <a href="https://travis-ci.org/Chocobozzz/PeerTube">
    <img src="https://travis-ci.org/Chocobozzz/PeerTube.svg?branch=develop" alt="Build Status" />
  </a>

  <a href="https://david-dm.org/Chocobozzz/PeerTube">
    <img src="https://david-dm.org/Chocobozzz/PeerTube.svg" alt="Dependencies Status" />
  </a>

  <a href="https://david-dm.org/Chocobozzz/PeerTube?type=dev">
    <img src="https://david-dm.org/Chocobozzz/PeerTube/dev-status.svg" alt="devDependency Status" />
  </a>

  <a href="http://standardjs.com/">
    <img src="https://img.shields.io/badge/code%20style-standard-brightgreen.svg" alt="JavaScript Style Guide" />
  </a>

  <a href="https://kiwiirc.com/client/irc.freenode.net/#peertube">
    <img src="https://img.shields.io/badge/%23peertube-on%20freenode-brightgreen.svg" alt="PeerTube Freenode IRC" />
  </a>
</p>

<br />

Absolutely all documentation related to development is made publically available, e.g. design files, BOMs, software source code, etc (for everything... including FPGA), and the project's <a href="https://wiki.apertus.org/index.php/Main_Page" target="blank">Wiki</a> is deep and extensive.<br />
<br />
Most of the immediate communications between community members takes place via IRC, and technical issues are documented on apertus Labs. A page detailing channel names and links can be found <a href="https://wiki.apertus.org/index.php/Join_the_Team" target="blank">here</a>.<br />


* [How the project got started](#Project-Background)
* [Who are we?](#who-are-we?)
* [What do we need?](#what-do-we-need)
* [How can you get involved?](#get-involved)
* [Get in touch](#contact-us)
* [Find out more](#find-out-more)
* [Buy us a coffee?](#donations)
* [License Info](#license)


## Project Background

The AXIOM project has a rich history dating back to the late 2000's. The community prides itself on the FOSS principles it's built around. A full account of the project's history and how the camera got started can be read on the<a href="https://wiki.apertus.org/index.php/AXIOM_Project_Background">Wiki</a>.

<br />
<br />
<br />
<br />


# AXIOM Beta

<br />

<p align="center">
  <a href="https://www.apertus.org/axiom-beta">
    <img src="https://www.apertus.org/sites/default/files/images/AXIOM-Beta-Standard-wallpaper-01-Many-Tweaks.jpg" alt="AXIOM Beta Developer Kit" />
  </a>
</p>

... a professional digital cinema camera built around FOSS and open hardware licenses.

The first of its kind, and providing users with the ability to swap or upgrade sensors at any time, the community’s debut camera is the result of years of collaboration with the <a href="https://www.magiclantern.fm/">Magic Lantern</a> team. With powerful internal components, custom-built printed circuit boards and plugin modules, FPGAs and an onboard Linux operating system at your disposal, changing the entire operation of the camera to suit the needs of any project is now possible.

Introduction to the camera and its variations on <a href="https://www.apertus.org/axiom-beta">apertus.org</a>.

<br />

<p align="center">
  <a href="https://www.apertus.org/axiom-beta">
    <img src="https://www.apertus.org/sites/default/files/images/AXIOM-Beta-Developer-Kit-Reverse-on-f2f2f2.jpg" alt="AXIOM Beta Developer Kit" />
  </a>
</p>

The general approach for designing the AXIOM Beta PCB stack was to give every board a clear, core purpose and not just pack as many things as possible onto each one. This way individual PCBs can be replaced without affecting the rest of the stack - for example, as the interfaces between the boards are predefined, a new image sensor can be installed simply by changing the Sensor Board PCB. Likewise, as individual printed circuit boards ultimately become more complex and offer richer features, the user can upgrade any of the camera's boards as and when they're ready to do so. 

Unlike with existing manufacturers, who typically use the shelf-life of a camera's individual components as a way to ensure that a customer purchases a whole new camera, this approach also enables users to perform minor repairs in the event that, for example, one of the PCBs needs to be replaced.

Introduction to the camera's structure and components on <a href="https://www.apertus.org/axiom-beta-modularity">apertus.org</a>.

<br />
<p align="center">
  <a href="https://www.apertus.org/axiom-beta">
    <img src="https://www.apertus.org/sites/default/files/images/AXIOM-Beta-II-Overview-02.jpg" alt="AXIOM Beta Compact" />
  </a>
</p>


<strong>Repositories</strong><br />

<a href="https://github.com/apertus-open-source-cinema/beta-software">Software</a><br />
<a href="https://github.com/apertus-open-source-cinema/beta-hardware">Hardware</a><br />
<a href="https://github.com/apertus-open-source-cinema/axiom-beta-qemu">QEMU</a><br />

<br />
<br />
<br />
<br />
</h4>


# OpenCine

OpenCine is a free RAW processing suite in development.<br />


<strong>Feature Overview</strong><br />

There are several free and open raw-image processing tools for still images like: ufraw, darktable, RawTherapee, Rawstudio, digiKam and many more. While some of them offer batch processing capabilities none of these tools were designed for moving pictures. Processing DNG sequences is cumbersome and time consuming, CinemaDNG MXF files are not yet supported at all. This is where Open Cine should come in. It will be a raw processing tool designed from the ground up for moving images instead of still images.<br />

* Import Footage from Camera over network (FTP Transfer to backup location)
* Import Footage from local drive
* Preview Footage in real-time (GPU based raw debayering at full/reduced resolution [Reduced resolution equates to better playback performance])
* View(all) / Edit(some) Metadata
* Set IN/OUT points in footage
* Apply color relevant RAW transformations (Whitebalance, Exposure, Curves, etc.)
* Save/Load color transformation presets to/from File.
* Adjustments are preserved in a XMP file that stays with the original unaltered footage.
* Live Histogram/Vectorscope
* Batch Export RAW footage between IN/OUT to non destructive RAW conforming format (DNG, DPX, etc.)
* Batch Export RAW footage between IN/OUT to destructive digital intermediate format (Quicktime Prores444, AVI DNxHD, Image Sequence, etc.)
* Batch Export RAW footage between IN/OUT to destructive proxy format (Quicktime Prores422 (proxy), Quicktime/AVI MJPEG, etc.)

<br />
<br />
<strong>Typical usage</strong><br />
<br />
Reviewing and sorting footage<br />
<br />
* Import DNG sequence that was shot with a raw camera (Apertus or other) into Open Cine.<br />
* View footage in real-time.<br />
* Mark unneeded clips, rate good clips, write comments for each clip.<br />
* Later a filter can be used to hide all the bad/unneeded clips. Director could now review only the good ones and continue working with them.

<br />
<br />
<br />

Prepare footage for editing<br />
* Import DNG sequence that was shot with a raw camera (Apertus or other) into Open Cine
* Sort through footage and select best clips (rating, marking), shorten to relevant parts in the clips by setting IN/OUT points
* Apply color grading nodes to the raw footage (White-balance, Exposure correction, Tonal Curves, etc.)
* Export Intermediate Clips in FullHD as Avid DNxHD or Apple ProRes for editing in another software

<br />
<br />

Prepare footage for finishing<br />
* An EDL/XML file of a complete edit contains the list of clips we need for finishing, import EDL/XML and link the clips to the raw footage (big win if we find a way to do this automatically)
* Apply color grading nodes to the raw footage (White-balance, Exposure correction, Tonal Curves, etc.)
* Export required clips as *.DPX or *.EXR image sequence (with full bitdepth) for finishing suite.
    
    
<strong>Repositories</strong><br />

<a href="https://github.com/apertus-open-source-cinema/opencine">OpenCine</a><br />
<a href="https://wiki.apertus.org/index.php/OpenCine.Build_Instructions">Build Instructions</a><br />
<a href="https://lab.apertus.org/tag/open_cine/">Labs Workboard</a><br />   
    



<br />
<br />
<br />
<br />
</h4>

# AXIOM Remote

This device, and when released the associated software, is designed to be a comprehensive remote control unit for the AXIOM range of cameras.<br />
<br />
As with all software & hardware that is pre-production the information contained on this page is subject to changes.<br />
<br />
AXIOM Remote was funded as a stretch goal in the AXIOM Beta crowd funding campaign and is still in development. It features push-buttons and switches as well as 2 rotary encoders (also with push-button function) that can be used to control a wide range of camera parameters like shutter speed, gain, overlays, FPS, gamma curves etc. To keep everything as flexible as possible the buttons next to the LCD have dynamic functionality as their commands are displayed next to them on the LCD. Switches on the side allow locking of each individual dial wheel or all buttons on the AXIOM Remote.<br />
<br />
Force Feedback for the two dials with two small built-in micro-stepper motors would allow feeling the settings (like min, max reached) without looking at the display. This could also allow switching the dials between jog/shuttle mode.<br />
<br />
The AXIOM Remote is based on a small LCD screen (for showing status information, camera parameters and navigating through menus, no live video) and a PIC32 micro-controller. The connection between AXIOM Remote and an AXIOM camera will be a flexible (preferably spiral) cable with solid connectors. Expansion slots (with GPIO) will allow easy future addition of new buttons/knobs/wheels/controllers/interfaces. <br />

<strong>Repositories</strong><br />

<a href="https://github.com/apertus-open-source-cinema/AXIOM-Remote">AXIOM Remote</a><br />
<a href="https://lab.apertus.org/T939">AXIOM WebRemote: Detailed Specs, Requirements and Build</a><br />
<a href="https://wiki.apertus.org/index.php/AXIOM_Remote">Concepts on Wiki</a><br />   
    



<br />
<br />
<br />
<br />
</h4>

