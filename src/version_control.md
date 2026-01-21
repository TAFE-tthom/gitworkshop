# Version Control

The idea of version control is that you have artifacts that persists and continues to be developed. It takes on changes either addition, removals or modifications directly. These are different versions of an artifact and software that is responsible for controlling this needs to keep a log of their changes.

*Why is it important in software?*

Software changes from its first stage, as with anything in this world.

However, within software, we may want to know when:

* What particular version had a bug
* What version has the new fixes
* What version is considered stable
* What has new features but may be unstable
...

The list is non-exhaustive. If you can think of why a version could exist, version control relates to this.

## Is version control just for software?*

Definitely not! For most of my own work, I typically keep a lot of documentation within a version control system. You have probably used a less robust but friendlier system like Google Drive, M365, Overleaf or Dropbox to name a few.

## What is `git` and why?

`git` is common software and the industry standard for software. This software enables version control but is a little more feature-full.

* It is a distributed version control system, not limited to just one service, can use many different services and remotes
* Enables non-linear workflows and branching
* Compresses data very well, tracks changes through commits
* Protocol can be used with other protocols like HTTPS and SSH
* Leverages a merkle-tree data structure (Common in p2p applications)
