---
layout: page
title: About
permalink: /about/
---

This is intended to be a play ground.

If you want to see your edits in the proper way, you must install and use [jekyll](https://jekyllrb.com/docs/home/).

Installing git:

* On windows: [git for windows](https://git-for-windows.github.io/)
* On linux `apt-get install git git-gui` or something similar on redhat, centos and such


Part I: How to contribute to this/any github project
------------------------------

1. Go to [the project](https://github.com/{{site.github_username}}/git-demo)

2. click fork project

3. `git clone git@github.com/<your user>/git-demo`

4. edit project (e.g. add an .md file)

5. `git add` changes

6. `git commit` and give a proper description

7. Repeat 4-6

8. `git push` to send the changes to github.

9. Go to https://github.com/<your user>/git-demo

10. Click create pull request

11. Write some nice description

12. Wait for {{site.github_username}} to approve and merge the update

 
Part II: Synchronizing with *upstream*
------------------------------

Updates to upstream will not automatically get into the fork.

1. create a new *remote* repository reference (following [this](https://help.github.com/articles/configuring-a-remote-for-a-fork/) quide)

   `git remote add upstream https://github.com/{{site.github_username}}/git-demo.git`
  
2. Sync with upstream (see [this](https://help.github.com/articles/syncing-a-fork/) for details)
   
   `git pull upstream master`

3. resolve any issues

4. `git push` to send it to your own repository


Part III: more...
-----------------

We have not talked about [branches](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) even though they are very fundamental.
