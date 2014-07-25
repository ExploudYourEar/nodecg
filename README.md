# NodeCG
NodeCG is a live graphics system, designed to be used during live stream events.  
It is based on the overlay system used during the [Tip of the Hats 2014](https://www.youtube.com/playlist?list=PLJUPqfTTJdNnxdK5YlAo3y2jQj188jl0_) event.  
  
NodeCG provides a basic package system for graphics, and an admin dashboard for controlling the packages.  
  
A package contains HTML, Javascript, CSS, and any other resources required to produce a certain graphic animation, and also contains an admin panel for controlling the animation.  
A nodecg-samples repository will be created soon to demonstrate how this works in practice.

### Installation
Install [node.js & npm](http://nodejs.org/), then install [bower](http://bower.io/), then run the following:
```
git clone https://github.com/nodecg/nodecg.git  
cd nodecg  
npm install  
bower install  
node server.js
```

### Usage
- Open `http://localhost:9090/dashboard` to see the admin dashboard  
- For each package you install, you can see it's graphic at `http://localhost:9090/view/{package-name}/`  
- You can configure NodeCG by editing config.js

### License
NodeCG is provided under the MIT license, which is available to read in the LICENSE file

### Credits
[Alex "Lange" Van Camp](http://alexvancamp.com), lead programmer & designer of [toth-overlay](https://github.com/Langeh/toth-overlay), contributor to NodeCG  
[Atmo](https://github.com/atmosfar), original dashboard concept and code
