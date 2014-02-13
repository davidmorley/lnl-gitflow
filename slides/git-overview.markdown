#git overview

Note: Git is an SCM tool, in the same class as CVS, Subversion, Mercurial, and ClearCase.



##what makes git so great?
<span>distributed</span> <!-- .element: class="fragment roll-in" -->
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span>fast branching and merging</span> <!-- .element: class="fragment roll-in" -->

Note: Two of the biggest selling points of git are its distributed model and its ability to do fast and easy branching.



##Distributed
no defined central repository (unless you want one) <!-- .element: class="fragment roll-in" -->

developers clone the entire repository (including history) <!-- .element: class="fragment roll-in" -->

Note: Git was designed by Linus Torvalds, the father of Linux, in order to support distributed development of the Linux kernel.



###Advantages of Distributed SCM
<span>operations are _FAST_</span> <!-- .element: class="fragment roll-in" -->

<span>development can be done offline</span> <!-- .element: class="fragment roll-in" -->

<span>many others&hellip;</span> <!-- .element: class="fragment roll-in" -->

Note: Since developers work on local copies of the repository, most operations are very fast, including branching and merging. Only pushing to and pulling from the origin repository require internet access. Development can even go on while on a plane!



##Fast Branching &amp; Merging
<span>branches are created locally</span> <!-- .element: class="fragment roll-in" -->

<span>starts as a snapshot of code at a given moment</span> <!-- .element: class="fragment roll-in" -->

<span>development on the new branch separate from the original</span> <!-- .element: class="fragment roll-in" -->

<span>branches can be merged together</span> <!-- .element: class="fragment roll-in" -->



###Fast Branching &amp; Merging Advantages
<span>quick prototyping</span> <!-- .element: class="fragment roll-in" -->

<span>feature development</span> <!-- .element: class="fragment roll-in" -->

<span>many others&hellip;</span> <!-- .element: class="fragment roll-in" -->

Note: The nature of git branching means that developers can easily create throwaway branches to test out ideas without needing to share them with other developers, all the while protecting the code in case the experiment doesn't work out. It also allows developers to work on features separately more easily.



##consequences
* no central source of "truth" <!-- .element: class="fragment roll-in" -->
* no defined branching strategy <!-- .element: class="fragment roll-in" -->

Note: Due to its openness and un-opinionated position, git itself has no central repository, and does not impose a particular branching strategy. These are key to its power, but as we all know, "With great power comes great responsibility." It is incumbent upon the developers to come up with a strategy to manage git repositories, especially in a collaborative software development environment such as the enterprise.



##simple branching
#+
##unclear model
#=

Note: What happens when branches are cheap and easy to create, and developers don't have a clear idea of how they should be managing those branches?



#Confusion
![Tangled wires](stock-vector-seamless-tangled-wires-vector-eps-110064839.jpg)

Note: Developers bring their own assumptions and internal mental models to each project. When those assumptions conflict with the reality of a branching model, things can go downhill quickly. Developers don't know what branches have what features, and worst of all, it is difficult or impossible to know what is the "truth" any more. Git is just a tool; it is not a process.