---
title: Capturing VM Screenshots in Google Cloud
description: In this tutorial we can find the ways for capturing VM screenshots in Google Cloud
author: rohna619
tags: VM Screenshots
date_published: 2021-08-18
---

Rohan Madan | Community Editor | Google

Contributed by the Google Cloud community. Not official Google documentation.

This tutorial shows you how to capture the VM screenshots in Google Cloud. Capturing a screenshot from a VM can help you troubleshoot a VM that is not otherwise accessible. For example, a VM might not be accessible if it is booting or has a disk image that is corrupted. VM screenshots can help us to troubleshoot the failed RDP connections to Windows VM, by identifying if the instance has started successfully.

There are some limitations by google for capturing screenshot.

1.Instance must be in running state
2.Maximum rate for capturing screenshots is 20 per second.
3.You can't initiate a screenshot while one is in progress.
4.You can capture one screenshot at a time.

This tutorial assumes that you're familiar with Compute Engine.

### Costs
This tutorial uses billable components of Google Cloud, including the following:
Compute Engine VM instances

You can use small instance size for reducing the costs.

### Before You Begin

For this tutorial, you need a Google Cloud project. You can create a new project or select an existing project.

Select or create a Google Cloud project.
Enable billing for your project.
When you finish this tutorial, you can avoid continued billing by deleting the resources that you created.









