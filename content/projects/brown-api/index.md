---
title: "Brown API"
description: "Reopening the landscape of application development for Brown University with a new API"
tags: ["API DEVELOPMENT"]
category: "Personal Project"
tech: ["Python (Flask)"]
team: "1 Full Stack Engineer (Me)"
date_string: "March 2020 (2 Weeks)"
---
<section>

### The Problem

Brown University previously had a student-maintained API to give quick access to real-time laundry and dining data.
However, the developers graduated and the repository sunk into deprecation as the websites they sourced their data from
changed.

</section>

<section>

### The Goal

To reboot the Brown API, fixing it and making it more efficient, modular, and readable

</section>

<section>

### The Execution

I began with a fork of the original Brown API repository and found that there were several problems. First, the data was
stored non-relationally and nested in messy, hard to reach objects. Moreover, I found that the dining API was slow and
scraped directly from the HTML of the Brown University dining site instead of using public, though hard to find,
endpoints provided by our catering company. Similarly, the laundry endpoint was structured to scrape from the website
rather than the public API.

To fix these issues, I first restructured to a Postgres database. I then rebuilt the scraping and data collection
systems to pull from the faster and more consistent aforementioned public endpoints. Finally, I slapped a new frontend
on the site to give documentation, and I was finished.

</section>

<section>

### Takeaways

This project was an interesting foray into building a public API and learning to manage public user credentials. If you
feel compelled, [check out the API here](http://api.cs.brown.edu/)!

</section>
