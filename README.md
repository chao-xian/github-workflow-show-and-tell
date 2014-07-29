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
This is how we've been using the Github Workflow model

### The steps
* Kelv makes a branch called `kelvs`
* Switches to that branch
```bash
git checkout kelvs
```
* And makes some changes
```markdown
  This is about to be an awesome change!
```
* Send a Pull Request!
  * this is a request for someone who looks after `master` to incorporate  changes from the `kelvs` branch
* Natt sees the Pull Request and checks for anything stupid
* He writes a comment: *TABS MUST DIE!* or similar
* Kelv replaces the tab for spaces then pushes back into the branch
* Natt approves and merges `kelvs` branch into `master`
* SHIP!🚢
* (Natt can now pull my changes in `master` into `natts`)

## Links
* [Github Workflow guide](https://guides.github.com/introduction/flow/index.html)
* [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) - similar but more sophisticated



