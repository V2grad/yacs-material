title: Yacs Wiki
disqus: 
<!--wip: if this is defined then an alert will rendered.-->

# Welcome to Yacs! [![GitHub watchers](https://img.shields.io/github/watchers/yacs-rcos/yacs.svg?style=social&label=Watch)](https://github.com/yacs-rcos/yacs) [![GitHub stars](https://img.shields.io/github/stars/yacs-rcos/yacs.svg?style=social&label=Stars)](https://github.com/yacs-rcos/yacs)

It's so good to see you!

<p align="center">
  <img src="./_static/media/logo.png"/>
</p>

## What is Yacs?

Yacs was created with the goal of making students' lives a little easier.
It allows users to avoid the clunky UIs of proprietary Catalog Management and Student Information Systems, replacing these unpleseant experiences with easy browsing and searching of courses, and adds the additional functionality of easy schedule generation, and much more.

But Yacs has grown to be much more than a simple schedule generator.
Our mission at Yacs is the following:

> 1. To alleviate the stress around academic and extracurrciluar planning for Students, Faculty and Staff by offering a Free, easy-to-use interface to supplement or replace traditional academic information and management systems.

> 2. To enable innovative, disruptive applications in the academic space by breaking down propreitary information silos and providing consistent, digestible, Open Data.

> 3. To empower students to take control of their academic experience and excel their careers through learning about and contributing to Open Source.

Further, Yacs aims to provide the best experience possible to as many people as possible by serving as many universities as we can.
Yacs is built from the ground up to be modular and flexible, and as such can use data from any source, and even combine data from many sources in an intelligent way.

We have made it as easy as possible to connect Yacs to your university, and have designed this process to be accessible to developers of nearly any skill level.
Please read through this documentation or contact us if you'd like to bring Yacs to your school, and help us make Yacs as great as it can be.

Yacs owes its creation and continued maintenance to [RCOS](https://rcos.io), the Rensselaer Center for Open Source, and is developed in collaboration with [BUGS](https://bugs-nyu.github.io/), NYU's Open Source Club.

## About this site
This site is the home of (nearly) all Yacs documetation.
Like all Yacs projects, this documentation is free and open source, and lives [in our Github](https://github.com/yacs-rcos/docs).

## How to Read These Docs
The Yacs documentation is divided into several sections.
Each section and its purpose is described here.

### Overview
Start Here!
This section contains the about page, which explains what Yacs is, why it exists, where we are, and where we plan to go.
This section also contains the [Code of Conduct](overview/code_of_conduct).
By participating in the Yacs community, you are agreeing to follow the Code of Conduct.
Understanding and following the Code of Conduct is extremely important for the health and success of the project, its contributors, and the Yacs community.

### Contributing
Look here if you want to contribute to Yacs, run the software on your machine, or just play around with the source.
Here you will find installation instructions, project management information, and tips on how and where to get started.

### Architecture
Here you will find the nitty-gritty details about how Yacs works.
This is a useful resource if you are looking to tackle a larger issue, or want to work towards bringing Yacs to your university.

### User Guides
This section contains user guides specific to each of the roles that use yacs.
This section is currenrly under construction.

### API Docs
Yacs has a public API! This API can be used to build all sorts of interesting, useful, or silly applications using the power of open data.
If you have an idea for something to build using the Yacs API, or are looking for inspiration, we'd love to hear from you!

### Afterword
Yacs is an open, safe community, and this site is a living document.
So please treat it as such!
If you find these docs to be insufficient, or you think you can do better, by all means let us know or open a pull request.
We encourage contributions from all, no matter how big or small.

> _When people help us to feel good about who we are, they are helping us love the meaning of what we create in this life_ - Mr. Rogers


## Material color palette

### Primary colors

> default `white`

Choose the color you want.

<div id="color-button">
<button data-md-color-primary="red">Red</button>
<button data-md-color-primary="pink">Pink</button>
<button data-md-color-primary="purple">Purple</button>
<button data-md-color-primary="deep-purple">Deep Purple</button>
<button data-md-color-primary="indigo">Indigo</button>
<button data-md-color-primary="blue">Blue</button>
<button data-md-color-primary="light-blue">Light Blue</button>
<button data-md-color-primary="cyan">Cyan</button>
<button data-md-color-primary="teal">Teal</button>
<button data-md-color-primary="green">Green</button>
<button data-md-color-primary="light-green">Light Green</button>
<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>
<button data-md-color-primary="amber">Amber</button>
<button data-md-color-primary="orange">Orange</button>
<button data-md-color-primary="deep-orange">Deep Orange</button>
<button data-md-color-primary="brown">Brown</button>
<button data-md-color-primary="grey">Grey</button>
<button data-md-color-primary="blue-grey">Blue Grey</button>
<button data-md-color-primary="white">White</button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);
    })
  })
</script>

### Accent colors

> default `red`

Choose the color you want.

<div id="color-button">
<button data-md-color-accent="red">Red</button>
<button data-md-color-accent="pink">Pink</button>
<button data-md-color-accent="purple">Purple</button>
<button data-md-color-accent="deep-purple">Deep Purple</button>
<button data-md-color-accent="indigo">Indigo</button>
<button data-md-color-accent="blue">Blue</button>
<button data-md-color-accent="light-blue">Light Blue</button>
<button data-md-color-accent="cyan">Cyan</button>
<button data-md-color-accent="teal">Teal</button>
<button data-md-color-accent="green">Green</button>
<button data-md-color-accent="light-green">Light Green</button>
<button data-md-color-accent="lime">Lime</button>
<button data-md-color-accent="yellow">Yellow</button>
<button data-md-color-accent="amber">Amber</button>
<button data-md-color-accent="orange">Orange</button>
<button data-md-color-accent="deep-orange">Deep Orange</button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-accent]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);
    })
  })
</script>