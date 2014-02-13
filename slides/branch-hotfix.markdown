##hotfix <small>branches</small>
* naming: <strong>hotfix-[fix number]</strong> <!-- .element: class="fragment roll-in" -->
* branches from: <strong>master</strong> <!-- .element: class="fragment roll-in" -->
* merges to: <span><strong>develop</strong> <em>and</em> <strong>master</strong></span> <!-- .element: class="fragment roll-in" -->

Note: Hotfix branches are intended to fix critical issues found in the production system that cannot wait for the next production release. Because they will not include other features, hotfix branches are created from the master branch and, when complete, are merged back to master (and develop).



##lifecycle
>&ldquo;The essence [of the hotfix branch] is that work of team members (on the develop branch) can continue, while another person is preparing a quick production fix.&rdquo;

<small>-Vincent Driessen, [A Successful Git Branching Model][nvie]</small>

[nvie]: http://nvie.com/posts/a-successful-git-branching-model/



##workflow
![Hotfix branch workflow diagram][1] <!-- .element: class="noborder" -->

[1]: hotfix-branch-workflow.png

