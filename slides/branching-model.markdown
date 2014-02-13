#Branching models

Note: Teams across various enterprises (including this one!) have solved the branching model problem in a multitude of ways. What model is right for a particular organization depends on many factors, including the type and size of the development organization, the type of software being produced, and the guidelines of the other software development methodologies the team has adopted. There is a link at the end of the presentation to a discussion of various models. None of them is necessarily "right" or "wrong", but our goal as an organization should be to find a model that is easy to comprehend and follow, while still meeting our development goals.



##Vincent Driessen
[@nvie][1] / [A Successful Git Branching Model][3]

[![git-flow blog post screenshot][2]][3]

[1]: https://twitter.com/nvie
[2]: nvie-gitflow-post.png
[3]: http://nvie.com/posts/a-successful-git-branching-model/

Note: Perhaps the most popular git branching model was introduced in a 2010 blog post by an independent software developer named Vincent Driessen. In it, he described a branching model his team had been using, with great results. The blog post doesn't actually coin the term, but we call this model ...



# git-flow



##Core Concept
Branch categories with clear purposes and workflows <!-- .element: class="fragment roll-in" -->

Note: The key to this branching model is to separate work into branches that are categorized for specific purposes. The logical, consistent relationship between the branch types reduces confusion by making clear what the state of the software is in a particular branch.