---
author:
  name: Sam Foo
  email: docs@linode.com
description: Learn how to find a running process and terminate it from the command line in Linux and Mac OS.
keywords: ["kill", "terminate", "PID", "command line"]
license: '[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0)'
modified: 2018-02-20
modified_by:
  name: Sam Foo
published: 2018-02-20
title: Find and Terminate Processes from the Linux or Mac OS Command Line
---

This Quick Answer explores some ways to locate and terminate a process from the command line. While there are graphical utilities such as Activity Monitor on Mac OS or Task Manager on Windows, such programs compromise control over processes in exchange for convenience. The command line offers many options for closing a process.

## Find Process ID (PID)

A common pattern for ending a process is though its Process ID (PID). There are a variety of ways to find the PID.

If the process name is known, `pgrep` will search currently running processes for the name:

    pgrep firefox

{{< note >}}
