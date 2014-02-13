##release <small>branches</small>
* naming: <strong>release-[release number]</strong> <!-- .element: class="fragment roll-in" -->
* branches from: <strong>develop</strong> <!-- .element: class="fragment roll-in" -->
* merges to: <span><strong>develop</strong> <em>and</em> <strong>master</strong></span> <!-- .element: class="fragment roll-in" -->

Note: Release branches are created to prepare for a production release. They are based on the develop branch, and thus contain all features that have been merged to develop up to that point. Once the release branch has been created, no more features may be added to that release (although bugfixes may continue). Development on features not to be included on the release can continue, however. When a release is approved to move to production, the release branch is merged to develop and master, and master is tagged with the release number. Usually, the release branch is also destroyed at this point.



##lifecycle
>&ldquo;The key moment to branch off a new release branch from develop is when develop (almost) reflects the desired state of the new release.&rdquo;

<small>-Vincent Driessen, [A Successful Git Branching Model][nvie]</small>

[nvie]: http://nvie.com/posts/a-successful-git-branching-model/



##workflow
![Release branch workflow diagram][1] <!-- .element: class="noborder" -->

[1]: release-branch-workflow.png

