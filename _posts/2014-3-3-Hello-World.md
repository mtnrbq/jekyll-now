---
layout: post
title: Step 1 - running code on a serv RISCV core on TinyFPGA Bx
published: true
---

## This is part of my 'Grossly over-engineered distance display' (goedd) project
### fusesoc, serv, oh-my

I finally managed to get by franken-toolchain operational - split between WSL with Ubuntu 20, and Windows 10, with about an 80% overlap.

Following the doco at [fusesoc](https://github.com/olofk/fusesoc) and [serv core](https://github.com/olofk/serv), and dusting off an old discontinued Salae Logic USB capture device I was finally able to get step 1 of my goedd project sorted, specifically:

1. Build the serv RISCV core (WSL)
2. Deploy to a physical FPGA (Win10)
3. Capture and decode the output to validate the results

![shell console showing output of building serv]({{site.baseurl}}/_posts/build.png)
![shell console showing use of tinyprog to deploy a binary file to a tinyFPGA Bx board]({{site.baseurl}}/_posts/prog_LI.jpg)
![screen showing a logic level decode of 'Hello World']({{site.baseurl}}/_posts/pulseviewdecode.png)

