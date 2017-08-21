# Collaboration and Code Review Checklist

Table of Contents
-----------------

- [Methodology](#methodology)
- [Get Started and Find Help](#getting-started-and-find-help)
<!--
    - [README.md](#readmemd)
    - [LICENSE.md](#licensemd)
-->

<hr>

# About

This repo contains optional tutorial exercises for the Get a Jumpstart with Collaboration and Code Review in GitHub talk by [Katherine "Kati" Michel](https://github.com/KatherineMichel).

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Testimonials

> **“I need that training. I think it's great. Git is SUPER intimidating to noobs like me - I'm always afraid I'm going to screw something up. It would be nice to get more comfortable with it and it would be rad to have a woman leading that.”**<br>
> — Jessica

> **“I support it!”**<br>
> — Rebecca

> **“+1 to a git tutorial”**<br>
> — Tim

> **“Go for it”**<br>
> — Kenneth

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Methodology

Through this repo will be series of challenges. When you accomplish a task, create a checkmark in the task box by putting an X. This is for your learning. Do all of the exercises, or pick and choose the ones you need to practice. My goal is to have a very practical list of tasks to accomplish to enable you to effectively collaborate and review code. By the way, some aspects of Git are not intuitive. Do not feel embarrassed if something does not immediately make sense. If anyone else wants to jump in with advice or assistance, great.
- [X] Task 1
- [ ] Task 2
- [ ] Task 3

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

<!--
(<> symbol denotes a variable)
-->

# Get Started and Find Help

- [ ] Create a free [GitHub](https://github.com) account
- [ ] Find your computer terminal
- [ ] Install Git and set your email and username
- [ ] Find Git, GitHub Help and Guides
- [ ] Find Keyboard Shortcuts (type "?")
- [ ] Find help via command line

### Resources

* [Set Up Git](https://help.github.com/articles/set-up-git)
* [Getting Started Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Homebrew Git Formula](http://braumeister.org/formula/git)
* [Git Doc (Docs and Pro Git Book)](https://git-scm.com/doc)
* [Git Documentation](https://git-scm.com/documentation)
* [GitHub Help](https://help.github.com)
* [GitHub Guides](https://guides.github.com)
* [Using Keyboard Shortcuts](https://help.github.com/articles/using-keyboard-shortcuts)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Organization and User Accounts

- [ ] Take a user account tour and understand the parts
- [ ] Create a user account repo
- [ ] Create an organization
- [ ] Take an organizational account tour and understand the parts
- [ ] Understand how to create teams with permissions
- [ ] Access your organizational account and dashboard
- [ ] Create an organizational repo

### Vocab

- [ ] Find a repo (a place where a code base is stored)
- [ ] Find a branch (a copy of a code base within a repo)
- [ ] Find a fork (copy of an entire repo)
- [ ] Find your local development environment (your computer environment)
- [ ] Create a clone (a local copy of a repo)
- [ ] Identify the origin

### Resources

* [GitHub Glossary](https://help.github.com/articles/github-glossary)
* [Git Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
* [GitHub Git Cheatsheet](https://help.github.com/articles/git-cheatsheet)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Browser versus Command Line

### Resources

* [Viewing Branches in Your Repository](https://help.github.com/articles/viewing-branches-in-your-repository)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Collaborative Development Model Tour

- [ ] Understand the two main Collaborative Development Models
- [ ] Understand what read/write permission is
- [ ] Look at an example of a best practice "Fork and Pull Model" workflow
- [ ] Look at an example of a best practice "Shared Repository Model" workflow for an organizational repo
- [ ] Look at organizational repo "Shared Repository" permissions

### Optional- User Account "Shared Repository Model"

- [ ] Understand the difference between organizational and user account "Shared Repository Model"
- [ ] Look at user account repo "Shared Repository" permissions
- [ ] Look at an example of a best practice "Shared Repository Model" workflow for a user account 

Example Organization Access
* [Organizations (need to be logged in)](https://github.com/settings/organizations)

### Resources

* [About Collaborative Development Models](https://help.github.com/articles/about-collaborative-development-models)
* [Types of Collaborative Development Models](https://help.github.com/enterprise/2.7/user/articles/types-of-collaborative-development-models)
* [Permission Levels for an Organization](https://help.github.com/articles/permission-levels-for-an-organization)
* [Repository Permission Levels for an Organization](https://help.github.com/articles/repository-permission-levels-for-an-organization)
* [Permission Levels for a User Account Repository](https://help.github.com/articles/permission-levels-for-a-user-account-repository)

* [Setting Up Teams](https://help.github.com/articles/setting-up-teams)
* [Maintaining Teams](https://help.github.com/articles/maintaining-teams)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Making Workflow Decisions

- [ ] Look at an example of master only versus master/develop, production/staging
- [ ] Decide a workflow
- [ ] If will have both master and develop branch, choose default branch

### Resources

* [Setting the Default Branch](https://help.github.com/articles/setting-the-default-branch)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Setting Up Repo Failsafes

- [ ] Create a repo backup (third-party softwares)
- [ ] Protect your main branch(es)
- [ ] Require reviews for pull requests
- [ ] Require external status checks
- [ ] Delete a non-important branch locally and attempt to recover it!
- [ ] Create a dummy sensitive information file and remove it from the history

### Resources

* [Backing Up a Repository](https://help.github.com/articles/backing-up-a-repository)
* [About Protected Branches](https://help.github.com/articles/about-protected-branches)
* [Configuring Protected Branches](https://help.github.com/articles/configuring-protected-branches)
* [Working with Protected Branches](https://help.github.com/articles/working-with-protected-branches)
* [About Required Reviews for Pull Requests](https://help.github.com/articles/about-required-reviews-for-pull-requests)
* [Enabling Required Reviews for Pull Requests](https://help.github.com/articles/enabling-required-reviews-for-pull-requests)
* [Can I Recover Branch After its Deletion in Git?](https://stackoverflow.com/questions/3640764/can-i-recover-branch-after-its-deletion-in-git)
* [Removing Sensitive Data from a Repository](https://help.github.com/articles/removing-sensitive-data-from-a-repository)

<!--
Require Status Checks (external, Travis CI is an example)

Collaborating on repositories with code quality features enabled
About statuses
https://help.github.com/articles/about-statuses

Defining the mergeability of pull requests
About required status checks
https://help.github.com/articles/about-required-status-checks
Types of required status checks
https://help.github.com/articles/types-of-required-status-checks
Enabling required status checks
https://help.github.com/articles/enabling-required-status-checks
About branch restrictions
https://help.github.com/articles/about-branch-restrictions
Enabling branch restrictions
https://help.github.com/articles/enabling-branch-restrictions
-->

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Setting Up Repo Documentation

### Communication- General

- [ ] Create and implement your communication strategy
- [ ] Draft community guidelines
- [ ] Get to know GitHub Flavored Markdown

### Documentation- Forums

- [ ] Understand what wikis is
- [ ] Understand what GitHub pages/Jekyll are
- [ ] Understand what gists are

### Documentation- Files

- [ ] Make a README.md
- [ ] Make a LICENSE (auto-generate)
- [ ] Make a CODE_OF_CONDUCT.md (auto-generate)
- [ ] Make a CONTRIBUTING.md
- [ ] Make a PITCHME.md

### Resources

* [Getting Started with Writing and Formatting on GitHub](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github)
* [Working with Advanced Formatting](https://help.github.com/articles/working-with-advanced-formatting)
* [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics)
* [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages)
* [Wikis](https://help.github.com/categories/wiki)
* [Gists](https://help.github.com/categories/gists)
* [About READMEs](https://help.github.com/articles/about-readmes)
* [Licensing a Repository](https://help.github.com/articles/licensing-a-repository)
* [Adding a License to a Repository](https://help.github.com/articles/adding-a-license-to-a-repository)
* [Adding a Code of Conduct to Your Project](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Issue and Pull Request Documentation

- [ ] Make an ISSUE_TEMPLATE
- [ ] Find the Issues Tab
- [ ] Make a PULL_REQUEST_TEMPLATE
- [ ] Find the Pull Requests Tab

### Resources

<!--
Examples
* [Code of Conduct](CODE_OF_CONDUCT.md) :bulb:
* [Contributing template](CONTRIBUTING.md) :bulb: 
* [Contributing banner](https://github.com/collaboration-and-code-review/example-repo/issues/new) :bulb: :alarm_clock:
* [New issue template](ISSUE_TEMPLATE) :bulb: :alarm_clock:
* [New issue](https://github.com/collaboration-and-code-review/example-repo/issues/new) :bulb:
* [Pull request template](PULL_REQUEST_TEMPLATE) :bulb: :alarm_clock:

<!--
## Examples
* [Saved replies (need to be logged in)](https://github.com/settings/replies) :bulb:
-->

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Productivity Helpers

- [ ] Cache your password
- [ ] Set up special configs (example: line endings)
- [ ] Create saved replies
- [ ] Link to specific line number on GitHub

### Resources

* [Working with Saved Replies](https://help.github.com/articles/working-with-saved-replies)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Notifications

- [ ] Find the Notifications Overview Page :boom:
- [ ] Decide which notifications to receive, whether by browser or email, and which email to receive at

### Resources

<!--
* [Emails (need to be logged in)](https://github.com/settings/emails)
* [Notifications center (need to be logged in)](https://github.com/settings/notifications)
-->

<!--
https://help.github.com/articles/types-of-emails-github-sends/#notification-emails
About notifications
https://help.github.com/articles/about-notifications/#types-of-notifications
About notification emails
https://help.github.com/articles/about-notification-emails
Managing notifications for pushes to a repository
https://help.github.com/articles/managing-notifications-for-pushes-to-a-repository
News Feed (Personal and Organization News Feed)
https://help.github.com/articles/news-feed
-->

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

<!--
About forks
https://help.github.com/articles/about-forks
Configuring a remote for a fork
https://help.github.com/articles/configuring-a-remote-for-a-fork
Syncing a fork
https://help.github.com/articles/syncing-a-fork
Merging an upstream repository into your fork
https://help.github.com/articles/merging-an-upstream-repository-into-your-fork
-->

<!--
https://help.github.com/enterprise/2.7/user/categories/collaborating-with-issues-and-pull-requests/
About pull requests- "If you're working in the shared repository model, we recommend that you use a topic branch"
https://help.github.com/articles/about-pull-requests/
Checking out pull requests locally
https://help.github.com/enterprise/2.7/user/articles/checking-out-pull-requests-locally/
https://help.github.com/articles/checking-out-pull-requests-locally/#modifying-an-inactive-pull-request-locally
-->

# Commands

<!--
Clone an organizational repo (organizational repo will be "origin")

```bash
$ git clone https://github.com/<organization-name>/<repo-name>
```

Clone a user account repo (forked repo will be "origin")

```bash
$ git clone https://github.com/<user-name>/<repo-name>
```
-->

<!--
### Change Directory (folder name will be the repo name)

```bash
$ cd <repo-name>
```

### Verify Which Branch You Are Checked Out On

```bash
$ git branch
```

### Create and Switch to a Feature Branch, a.k.a. Topic Branch (note how the local files switch to the files of the branch you are checked out on)

If checked out in the branch you are branching off of (do not need to specify which branch branching off of)

```bash
$ git checkout -b <branch-name>
```

If not checked out in the branch you are branching off of (need to specify which branch branching off of)

```bash
$ git checkout -b <branch-name> <branch-branching-off-of>
```

### Add, Commit, Create a Message

```bash
$ git add .
$ git commit -m "Your note"
```

### Push Follow-On Commit to Organizational Pull Request

```bash
$ git push origin <branch-name>
```

### Push Follow-On Commit to Forked Repo Pull Request via HTTP/HTTPS or SSH (contributor has to have given permission for maintainers to amend pull request, and local branch name has to match pull request branch name)

HTTP

```bash
$ git checkout -b <branch-name> master
$ git add .
$ git commit -m "Your note"

$ git push http://github.com:<user-name>/<repo-name> <hashtag-and-pull-request-number>:<branch-name>
```

HTTPS

```bash
$ git push https://github.com:<user-name>/<repo-name> <hashtag-and-pull-request-number>:<branch-name>
```

SSH

```bash
$ git push git@github.com:<user-name>/<repo-name> <hashtag-and-pull-request-number>:<branch-name>
```

### Delete a Branch

```bash
$ git branch -d  <branch-name>
```

Force delete branch

```bash
$ git branch -D  <branch-name>
```
-->

# Clone/Download and Push Feature Branch to Repo (Almost Same Process for Forked Repo or Organizational Repo)

- [ ] If no read/write access- fork the repo
- [ ] Clone or download the organizational or forked repo (this will be your origin)
- [ ] Change directory
- [ ] Verify which branch you are checked out on
- [ ] Create and switch to a feature branch, a.k.a. topic branches (note how the local files switch to the files of the branch you are checked out on)
- [ ] Add, commit, create a message
- [ ] Push the branch to the organizational or forked repo (this will be your origin)
- [ ] Create pull request title, description, make sure base and compare are correct
- [ ] If forked repo- give repo maintainers permission to amend pull request
- [ ] Create pull request
- [ ] Push follow-on commits to organizational or forked repo pull request

### Resources

* [Allowing Changes to a Pull Request Branch Created from a Fork](https://help.github.com/articles/allowing-changes-to-a-pull-request-branch-created-from-a-fork)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

<!--
Creating a pull request
https://help.github.com/articles/creating-a-pull-request
Creating a pull request from a fork
https://help.github.com/articles/creating-a-pull-request-from-a-fork
-->

# Code Review

- [ ] Fetch an organizational pull request
- [ ] Checkout a pull request locally
- [ ] Merge pull request via browser- regular
- [ ] Merge pull request via browser- squash
- [ ] Merge pull request via browser- rebase
- [ ] Merge pull request via command line
- [ ] Ask contributor to make a change to pull request
- [ ] Request a review from a specific person
- [ ] Add, commit, create a message, merge pull request via command line and push to live branch
- [ ] Push follow-on commits to organizational pull request
- [ ] Push follow-on commits to forked repo pull request via HTTP/HTTPS or SSH
- [ ] Close pull request via browser
- [ ] Close an issue via commit message by using keyword
- [ ] Delete a branch through browser
- [ ] Delete a branch through locally
- [ ] Revert a pull request

### Resources

* [Committing Changes to a Pull Request Branch Created from a Fork](https://help.github.com/articles/committing-changes-to-a-pull-request-branch-created-from-a-fork)
* [Closing Issues Via Commit Messages](https://help.github.com/articles/closing-issues-via-commit-messages)

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>

# Do Multiple Things at Once

- [ ] Keep main branch(es) up-to-date
- [ ] Keep feature branch(es) up-to-date
- [ ] Work on multiple feature branches
- [ ] Review code

<!--
### Keep Main Branch(es) Up-to-Date

```bash
$ git checkout <branch>
$ git pull origin <branch>
```

### Keep Feature Branch(es) Up-to-Date

Merge Updates into Branch (assuming master is default and up-to-date branch)

```bash
$ git checkout -b <branch-name>
$ git merge master
```
-->

# Advanced Workflow

- [ ] Look at advanced workflows and understand different choices
- [ ] Create a tag
- [ ] Create a release

### Advanced Collaborative Development Workflow Examples

* Git Flow
* [A Successful Git Branching Model](http://nvie.com/posts/a-successful-git-branching-model) (more advanced)
* [A Successful Git Branching Model Considered Harmful](https://barro.github.io/2016/02/a-succesful-git-branching-model-considered-harmful)
* [SemVer](http://semver.org) (subtopic)

<!--
https://help.github.com/articles/what-is-a-good-git-workflow

GitHub flow
https://help.github.com/articles/github-flow
About collaborative development models
https://help.github.com/articles/about-collaborative-development-models

https://guides.github.com/introduction/flow

http://scottchacon.com/2011/08/31/github-flow.html

About Releases
https://help.github.com/articles/about-releases
Creating Releases
https://help.github.com/articles/creating-releases
Working with Tags
https://help.github.com/articles/working-with-tags
Linking to releases
https://help.github.com/articles/linking-to-releases
-->

:top: <sub>[**back to top**](#table-of-contents)</sub>

<hr>
