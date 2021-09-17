+++
title = "What is RillRate?"
description = "RillRate - Real-time UI for bots and tools."
draft = false
weight = 20
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "What is the difference between <b>RillRate</b> and manual creating of UI?"
toc = true
top = false
+++

# How developers make UIs?

The software can be _interactive_ and _non-interactive_.

**Interactive** software has a user-interface (UI) to interact with it. Developers can
implement UI using different approaches:

- GUI - graphical user interface
- TUI - terminal user interface
- CLI - command line interface
- Web UI - web application

In all cases developer has to make and compose user-interface manually.
And also further maintenance requires a considerable amount of time.

**Non-interactive** software doesn't have a user-interface at all.
But this does not mean that such applications do not need an interface,
for example, it would be useful to have it for monitoring or changing
parameters without restarting the application.

But in both cases developing of user-interface is a long and not flexible process.
That is why many bots or tools supports command-line parameters only and prints any
data to files and `stdout`.
