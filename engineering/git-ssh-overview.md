# Git and SSH Overview

## Git Overview
Many projects use Git. Here are some references to review if you are unfamiliar with it.

* Getting Git Right https://www.atlassian.com/git/
* Version Control with Git book http://www.amazon.com/Version-Control-Git-collaborative-development/dp/1449316387
* Learn "how git works" at a lower level, and some useful stuff like rebasing (workflow and interactive), reflog etc https://www.youtube.com/watch?v=MYP56QJpDr4
* if you want a non-video companion to the first half, http://git-scm.com/book/en/v2/Git-Internals-Git-Objects is a great place to start.

## ssh config
ssh'ing to `*.civicactions.net` requires port 940. You can add `-p 940` with every ssh command, or you can do this to make use port 940 every time:

* Create a `~/.ssh/config` file if you don't already have one.
* Then add these lines:

    `Host *.civicactions.net`

    `Port 940`

## Set up Git and ssh
See https://trello.com/c/WvvbYoqb/2-git-and-ssh-0-5 for setup steps.

## Sandbox
See our Coding Standards: https://civicactions.net/content/coding-standards
