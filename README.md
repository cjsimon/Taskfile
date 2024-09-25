# Taskfile

My branch of [AdrianCooney's Taskfile](https://github.com/adriancooney/Taskfile)

## Overview

I've always used Make as a flexible project task-runner more than a build system. Build tools like Make, CMake, and even npm's script runner are rightly domain specific, too much so to be a general build orchestrator—I simply want to automate kicking off project tasks from my command line. What better way to do that than using the command line itself? No new magic under the hood other than bash functions; No new syntax; it's already turing complete, easy to read and relatively portable, and it's already on everyone's systems. In the past, something very much like Adrian's elegant Taskfile is what I had been attempting to create.

## Prerequisites

I wrote this for modern bash on Linux to prioritize readability for me, as I'm more familiar with that than sh—I'm not too interested in running this on lesser or older systems at the moment, sorry. This could likely be ported to work on sh without too much effort though; maybe that's something worth exploring in the future.

It should go without saying—this tool is still in alpha, and is currently not intended for production use.

This has yet to be tested under Mac and Git for Windows' GitBash; I'm not sure how nice the `compgen` calls will play under those systems. I wonder if `grep` under Mac is, or can be setup to be, roughly GNU/`POSIXLY_CORRECT`.
