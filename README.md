Github Workflow Show and Tell
=============================

![Branch all the things](/images/branch-allthethings.jpg)

## Intro

Files in a repository.

In the `master` branch.

`master` = ready to ship.

Let's hack!

Rule Number One: DON'T BREAK `master` branch!

NEW BRANCH!

## How?
This is how we've been using the Github Workflow :octocat: model

### The steps
* Kelv makes a branch called `kelvs`
  * Click `branch` button
  * type in `kelvs`
* Switches to that branch
```bash
git checkout kelvs
```
* And makes some changes
```markdown
This is about to be an awesome change but with typo!
```
* Send a [Pull Request](https://github.bath.ac.uk/mnskchg/github-workflow-show-and-tell/pulls)!
  * this is a request for someone who looks after `master` to incorporate  changes from the `kelvs` branch
* Natt sees the Pull Request and checks for anything stupid
* He writes a comment: *TYPO! FIX IT!* or similar
* Kelv fixes then pushes back into the branch
* Natt approves and merges `kelvs` branch into `master`
* SHIP IT! [:shipit:](http://qr.ae/ogWaA)
* (Natt can now pull my changes in `master` into `natts`)

## Links
* [Github Workflow guide](https://guides.github.com/introduction/flow/index.html)
* [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) - similar but more sophisticated
* [Shipit Squirrel](https://www.quora.com/GitHub/What-is-the-significance-of-the-Ship-It-squirrel)



