---
layout: post
title: Instrumenting a Rails application
date: 2019-07-22 09:00:01 -0000
description: How to use Prometheus to instrument a running Rails application
tags: tutorial talks rails prometheus
---

In the 18th of July 2019 I gave a talk at [Le Wagon Lisbon](https://www.lewagon.com/lisbon) about how to instrument a Rails application, using Prometheus.

Since [my last talk](/2019-06-28/email-me-maybe/) I grew fond of simple live coding demonstrations to convey practical knowledge as well as awareness that things are often easier than they seem. This time I went about gathering some system and custom metrics from an already existing application into an existing Prometheus server.

[The application with the end setup is available here](https://github.com/punnie/rails-prom) as a docker compose bundle that can easily be run to inspect results and do further experimentation. The instructions in the README should be clear enough to get you a working example, but if they are not then feel free to open an issue in the repository.

Happy hacking!
