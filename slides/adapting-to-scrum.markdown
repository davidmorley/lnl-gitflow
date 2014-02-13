##Adapting git-flow for
#Agile Scrum Teams



<em>Problem #1</em>
##Large, long-lived features (epics)
<span>Solution: <strong>use git-flow (AVH edition)</strong></span> <!-- .element: class="fragment roll-in" -->



##git-flow (AVH edition)
* features can have sub-features <!-- .element: class="fragment roll-in" -->
* sub-features branch from and merge to parent features <!-- .element: class="fragment roll-in" -->



##sub-feature workflow
![Sub-feature branch workflow][1] <!-- .element: class="noborder" -->

[1]: subfeature-branch-workflow.png



<em>Problem #2</em>
##Intra-sprint feature testing
<span>Solution: <strong>continue using sprint branches</strong></span> <!-- .element: class="fragment roll-in" -->



##Sprint branches
<span>created from `develop` at sprint start</span> <!-- .element: class="fragment roll-in" -->

<span>features to be tested are manually merged</span> <!-- .element: class="fragment roll-in" -->

<span>*destroyed* at the end of the sprint</span> <!-- .element: class="fragment roll-in" -->



##sprint branch workflow
![Sprint branch workflow][sprint-branch-workflow] <!-- .element: class="noborder" -->

[sprint-branch-workflow]: sprint-branch-workflow.png

