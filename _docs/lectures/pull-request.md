---
title: Submitting a pull-request
permalink: /docs/pull-request/
---

The website is hosted on a [github repository](https://github.com/transparency-lecture/transparency-lecture.github.io).
To submit a change you'll have to make a so-called "pull-request". This page is
a step-by-step explanation on how to do that.

#### Step 1: create a github account

Create an account [here](https://github.com/join).
You can choose to remain anonymous, but I personally
recommend to use github under your real name.

#### Step 2: create a fork

If you haven't done it yet, create a fork of the website's
[repository](https://github.com/transparency-lecture/transparency-lecture.github.io)
by clicking on the fork button:

[![image unavailable](/img/docs/pull-request/fork.png)](/img/docs/pull-request/fork.png)

The newly created fork should now be available under your own personal profile,
under the address: ``https://github.com/USERNAME/transparency-lecture.github.io``
where ``USERNAME`` is your github account name.

#### Step 3: make sure that your fork is up-to-date

**If you just forked the repository for the first time, you can skip this step.**

If not, you should check that your ``master`` branch is up-to-date:

- go to your forked repository website (see above): you can check that you
  you are on the right page by checking the header (green box in the image below).
- make sure that you are looking at the master branch (orange box in the
  image below).
- check the current status. If the message says that you are behind (red box in
  the image below), continue reading. If it says that you are up-to-date,
  go to step #4.

[![image unavailable](/img/docs/pull-request/update.png)](/img/docs/pull-request/update.png)

**If you are behind**, a tiny bit of command line manipulation is necessary:

- [install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  on your computer. On linux, this is as simple as ``$ sudo apt-get install git``.
- update your git name and email: ``git config --global user.name "Mona Lisa"``
  and ``git config --global user.email "email@example.com"``. The name is not
  very important, but the email must match the one you provided to github.
- in any directory, type: ``$ git clone https://github.com/fmaussion/transparency-lecture.github.io.git``
  This will create a new directory called ``transparency-lecture.github.io``.
  Navigate to this repository (``$ cd transparency-lecture.github.io``)
- add the main repository as upstream (in order to get the updates from it):
  ``$ git remote add upstream https://github.com/transparency-lecture/transparency-lecture.github.io.git``
- get the updates from github: ``$ git fetch upstream``
- merge them in your master branch : ``$ git checkout master`` and
  ``$ git merge upstream/master``
- upload them to your online fork: ``$ git push origin master``. You might have
  to enter your github credentials at this step.

**You're all set!** If everything went fine, your online master branch should
indicate that you are up-to-date with the original repository.

#### Step 4: create a new branch

On your fork's website (see above), click on
