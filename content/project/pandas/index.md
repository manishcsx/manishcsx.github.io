---
title: Python Web Scrapper
date: 2025-05-05
external_link: https://github.com/pandas-dev/pandas
tags:
  - Python
  - Bot
  - Cyber
---

I developed a Python-based web scraper designed to interact with a test domain (http://manishsas.t1cloudwaf.com/), 
which simulates an e-commerce site. The scraper operates for a duration of three minutes, continuously scanning the 
test domain. If a specific condition (denoted as "Size M") becomes available during this time, the scraper captures 
a screenshot before resuming its activity until the three-minute window concludes.

The primary goal of this project was to assess the effectiveness of Imperva’s Anti-Bot Protection (ABP). Unlike 
traditional bots that typically operate through command-line interfaces without emulating human behavior, this scraper 
was intentionally crafted to simulate human-like interactions by integrating a local browser. This approach allowed 
for more realistic testing of the ABP system’s ability to detect and mitigate bot activity.

<!--more-->
