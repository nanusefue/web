---
layout: project
title:  "Jan 25: Principles and practices, project management"
date:   2017-01-25 12:00:00
author: Marcel Newman
categories:
- project
img: portfolio_01.jpg
thumb: thumb02.jpg
carousel:
- single01.jpg
- single02.jpg
- single03.jpg
tagged: Flat, UI, Development
client: Wonder Corp.
website: http://blacktie.co
---
<h2>Create my own website (DRAFT) </h2>
<h3>Jekyll</h3>

<img src="{{ "/assets/img/project/week1/jekyll.png" | prepend: site.baseurl }}" alt='webpage jekyll'>
<p></p>
<p>To create my website I've chosen to use <a  target="_blank" href="https://jekyllrb.com">Jekyll</a>. That's because this system allows you to create a web in a easy and static way,  making modifications by simple changes in the configuration files (Markdown) </p>

<h4>Install Jekyll</h4>

<h4>Requirements</h4>

<p>Installing Jekyll should be straight-forward if all requirements are met. Before you start, make sure your system has the following:</p>
<ul>
<li>GNU/Linux, Unix, or macOS</li>
<li>Ruby version 2.0 or above, including all development headers</li>
<li>RubyGems</li>
<li>GCC and Make (in case your system doesn’t have them installed, which you can check by running gcc -v and make -v in your system’s command line interface)</li>
</ul>
<p>

<h4>Basic Usage</h4>

{% highlight bash linenos%}
# Install Jekyll and Bundler gems through RubyGems
~ $ gem install jekyll 

# Create a new Jekyll site at ./myblog
~ $ jekyll new myblog

# Change into your new directory
~ $ cd myblog

# Build the site on the preview server
~/myblog $ bundle exec jekyll serve

# Now browse to http://localhost:4000

{% endhighlight %}
</p>

<p>Jekyll also comes with a built-in development server that will allow you to preview what the generated site will look like in your browser locally</p>


{% highlight bash linenos %}
~ $ jekyll serve
# => A development server will run at http://localhost:4000/
# Auto-regeneration: enabled. Use `--no-watch` to disable.

~ $ jekyll serve --detach
# => Same as `jekyll serve` but will detach from the current terminal.
#    If you need to kill the server, you can `kill -9 1234` where "1234" is the PID.
#    If you cannot find the PID, then do, `ps aux | grep jekyll` and kill the instance.
{% endhighlight %}


<h4>Markdown</h4>

         
<p>Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, and then convert it to structurally valid XHTML (or HTML).</p>

<h4>Syntax</h4>
<p>Here, an example to show how easy is to create a link using Markdown:</p>
<p>This is [an example](http://example.com/ "Title") inline link.</p>

<p>[This link](http://example.net/) has no title attribute.</p>
<p> Will produce:</p>

<p>This is <a href="http://example.com/" title="Title">
            an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
            title attribute.</p>

<p><a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet" target="_blank">Markdown - Cheatsheet</a></p>              

<h3>How to generate static website</h3>
<p>
	Jekyll genearate your static site a partir your files, for this propus you need execute this command:
</p>

{% highlight bash linenos %}
~ $ jekyll build
# => The static site created in _site/ folder
{% endhighlight %}


<h2>Git (Version control system)  </h2>
<p>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.</p>

<h4>Branch</h4>
<p><img alt="Git Branch" class="img-responsive" src="{{ "/assets/img/project/git_branch.png" | prepend: site.baseurl }}"></p>
<p>TODO</p>

<h4>Basic Command</h4>


<h3>References</h3>
<p><a target="_blank" href="https://jekyllrb.com/">Jekyll</a></p>
<p><a target="_blank" href="https://en.wikipedia.org/wiki/Markdown">Markdown</a></p>
<p><a target="_blank" href="https://git-scm.com/">Git</a></p>



<h2>PROJECT IDEA: OPEN ECOTRONs</h2> 

<p>
An Ecotron is a device capable of generating a range of physical and chemical conditions applied to terrestrial or aquatic ecosystems.  Its principle is to confine a biological system (natural or artificial, complex or  simplified one) in a enclosure sealed in matter but not in energy, and simultaneously measure and control such flows of matter and energy.  For For this purpose, the enclosures are equipped with many sensors to obtain precise  real-time measurements and different actuators to control and modify the enclosure environmental conditions.</p> 
<p> REF: Lawton, J. H., Naeem, S., Woodfin, R. M., Brown, V. K., Gange, A., Godfray, H. J. C., Heads, P. A., Lawler, S., Magda, D., Thomas, C. D., Thompson, L. J. & Young, S. (1993) The Ecotron - a Controlled Environmental Facility for the Investigation of Population and Ecosystem Processes. Phil.Trans. R. Soc. B, 341, 181-194.</p>
<p>The idea is to end up with a generic  μCosm/bioreactor/fermentor  with a modular design that allows to be adapted by the user to match the specific farming/culturing/fermenting requirements of the chosen biological specie.  The device will include sensors and electronic systems to monitor control and automatize all the process, making it more resilient, productive and sustainable in a such easy way that it becomes accessible also for non-experts.</p>  

<h4>OpenGarden / Open μ-COSM</h4>
<p>OpenGarden is about to make a modular chamber with a very well controlled inner weather. That include the daily dynamic changes of the temperature, the humidity and light as basics, but also more sophisticated parameters as the flux of CO2  or the photosynthetic tax of the plants that could be growing inside.  OpenGraden will be a cheap DIY “classic” microcosm Ecotron, able to be adapted to the needs of each “user”: mushrooms, mycelium, lichens, moss, orchids, tomatoes, aloe, capsicum peppers, etc...</p>
<h4>OpenGrow / Open BioReactor</h4>
<p>
OpenGrow is about to make a modular bioreactor, following the diy-open-source philosophy and  keeping a low-price (a normal commercial one, can cost up to 4000 euros). A bioreactor is nothing else than a  enclosed space with controlled liquid environment to make the microorganism that grows inside the “happiest” possible. With this new generic apparatus we could cultivate our own yeast for making bread (or beer), your kefir fungi for yogurt, your bacteria to produce cellulose, glue, plastic, light... or even your favorite microalgae: spirulina, chlorella...etc. The modularity, of this micro-farm will be focused into allowing different configurations of sensors and actuators to control different parameters of the conditions of culturing (pH, temperature, density...) and also in allowing increasing culture volumes.   
Having that open source apparatus can make us envision the emergence of a world wide community of users. Thus, it could be interesting to create also a on-line website, where the community will share which specifications of the bioreactor makes which microorganism happier.  We could even invite the team of users to become a distributed repository of different interesting microorganisms.</p>

<h4>Open Brew / Open Fermentor</h4>
<p>OpenBrew is the follow-up of the OpenGrow.  But now, we are not interested in the microorganism that grows inside but in the liquid media and the fermentation process.  It is a project to explore the different ways to elaborate/prepare/ferment different beverages. Specially beer (from different cereals) but also drinks that are developed by similar fermentation process like wine, cider or any other fruit alcohol fermentation. But also Mate or kombucha tea as an non-alcoholic drink. 
Again, the idea is to end up with a general bioreactor/fermentor with a modular design that allows to be adapted to the special requirements of your beverage preparation. The fermentor, of course, will include some sensors and electronic systems to control and automatize the process, in order to make the fermentation easier, less laboured and accessible to everybody.</p>