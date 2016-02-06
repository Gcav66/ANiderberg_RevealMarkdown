# Fuck Powerpoint
### Use Reveal.js, Markdown, and Github Pages to easily create badass presentations

This is a practical guide to creating presentations using Reveal Markdown. If you read this guide and follow the examples (don't be lazy - actually try them), you will have the requisite skills to create badass Reveal.js presentations with Markdown that you host on Github Pages like a boss.

### PowerPoint is awful.
As much as we love to blame the decline in Western culture on social media and reality television, those of who work desk jobs know that PowerPoint has done more to retard cognitive development and crush the human spirit than anything else. While it is true that the PowerPoint authors are truly to blame, and they will be held accountable (read that in a V for Vendetta voice), PowerPoint both as a tool and medium of expression allows for easily generated vapid nonsense.It encourages is us to trade complex ideas for not-more-than-three bullets and to create hideous, static graphics when a real example is what is needed.

No more. This has to stop.

### Enter Reveal.js
Reveal.js is a framework for easily creating beautiful presentations using HTML. Check out this [presentation](http://vizzuality.github.io/rollingstonesmap/#/). Ready to drop, PowerPoint? Thought so...

The power of reveal.js comes from the fact that it is code. This give us tremendous flexibility but in return asks a little more of us.

Each reveal.js slide is HTML. Even for programmers, writing HTML isn't much fun.
```
<section class="landing">
	<div class="introText">
		<h1 class="hugeNumber">50</h1>
		<h1>Years of concerts of <strong>The Rolling Stones</strong></h1>
		<h2>An interactive map of their live-show story.</h2>
	</div>
	<div class="nextButton"><a href="#" actual-slide="0"> </a></div>
</section>
```
Luckily, there is a better way: Markdown. 
[Markdown](https://daringfireball.net/projects/markdown/) is a syntax, i.e., a style of arranging words and phrases, that converts to HTML. It is much easier to write than HTML without sacrificing any power. Below is the glob of HTML we just saw as written in Markdown.
```
# Years of concerts of **The Rolling Stones**
## An interactive map of their live-show story
```
Interested? Let's dive in and get started.

