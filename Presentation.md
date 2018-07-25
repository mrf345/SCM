<style>
* {
    color: cornsilk !important;
}
h1 {
    color: lightblue !important;
    text-align: center;
    font-stretch: ultra-condensed;
    font-family: 'Times New Roman', Times, serif !important;
    font-weight: 600 !important;
    text-transform: capitalize !important;
    text-shadow: -4px 4px 20px darkblue !important;
    margin-bottom: 0% !important;
}
p {
    color: cornsilk !important;
    text-align: left;
    font-stretch: ultra-expanded;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif !important;
}
body {
    background-color: brown;
    box-shadow: inset 0 0 20px black;
}
img {
    cursor: zoom-in;
    height: 400px;
}
img:hover {
    height: 650px;
}
img.qr {
    height: 300px;
    width: 400px;
}
a {
    font-stretch: ultra-expanded;
    font-weight: bold;
}
li {
    list-style-type: square;
}
code {
    color: green;
}
pre:hover {
    cursor: zoom-in;
    font-size: 70%;
}

@keyframes beat {
  0%   { color: lightblue; }
  50% { color: white; font-size: 150%; }
  100%   { color: lightblue; }
}

.theEnd {
    animation: beat 3s infinite;
}

.typeWriter {
    color: #000;
    font-family: monospace;
    overflow: hidden;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: .15em;
    margin-top: 0% !important;
    padding-top: 0% !important;
}

.typeIt1 {
    animation: typing1 10s steps(30, end) infinite;
}

.typeIt2 {
    animation: typing2 10s steps(30, end) infinite;
}

.typeIt3 {
    animation: typing3 10s steps(30, end) infinite;
}


@keyframes typing1 {
  0% { width: 0 }
  10% { width: 100% }
}

@keyframes typing2 {
    0% { width: 0 }
    10% { width: 0 }
    20% { width: 100% }
}

@keyframes typing3 {
    0% { width: 0 }
    20% { width: 0 }
    30% { width: 100% }
}
</style>

<!-- slide id="1" -->
# software configuration management (SCM) <br /> <br />
- What's it? _deploy, configure, maintain_ <br /><br /> <!-- .element: class="fragment" data-fragment-index="1" -->
- How it started ? _(Tasks -> automated tasks -> concurrent task) Endless bash scripting in SA !_ <br /><br /> <!-- .element: class="fragment" data-fragment-index="2" -->


<!-- slide id="2" -->
# SCM tools and frameworks <br /> <br />
- What's SCM tools ? _tools to achieve the same goals of SCM without thousands of scripts_  <br /> <br /> <!-- .element: class="fragment" data-fragment-index="1" -->
- Why a framework ? _configuring and deploying code with bash scripting to * is hell itself_ <!-- .element: class="fragment" data-fragment-index="2" -->

<!-- slide id="3" -->
- How about deploying your web application into different a 100 server and configuring it concurrently ? <br /> <br />  <!-- .element: class="fragment" data-fragment-index="1" -->
<p class="typeWriter typeIt1">
Why the hell would you need all
</p>
<p class="typeWriter typeIt3">
that useless configuration ?!"
</p><br />


<!-- slide -->
# DevOps and System Administration <br /> <br />
- What's DevOps ? SA + Software development <br /> <br />  <!-- .element: class="fragment" data-fragment-index="1" -->
- DevOps SCM tools ? Chief, Puppet, Ansible <br /> <br /> <!-- .element: class="fragment" data-fragment-index="2" -->
- Why ansible ? Python, SSH, no guest requirements <br /> <br /> <!-- .element: class="fragment" data-fragment-index="3" -->

<!-- slide id="5" -->
<h1 class="theEnd">Let's be practical</h1>

<!-- slide -->
<h1 class="theEnd">The end</h1>
