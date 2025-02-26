---
layout: post
title: "Uniformity and Resources"
author: Ryan Fuller
excerpt: "Stylizing the website a little more."
---
This week, it was mostly more of trying to figure out why the resources are not saving to the database. Requests are working just fine and show up perfectly, so that's a relief. I took some of my time away from the stress of the Resources side of the website and focused on making all the pages uniform, so every title is the same color, size, etc.

Also, when we merged Elliot's changes, for some reason, there were two "Requests" links in the navbar, so I took care of making sure only one of those linked to the correct page. Then, it was changing the navbar link for the "Request Form" to be the Create page for Requests, and finally just making sure the tables for both Resources and Requests look the same and other smaller style changes.

We changed the Resource types to be an enum rather than just strings, so I tried a new approach by populating the dropdown menu with all the items in the enum, but it still would not save. So, instead, I switched them back to strings, but it still doesn't work. This signaled that there's a bigger, underlying issue, so it's just a matter of comparing earlier files and figuring out why this isn't working now. Easier said than done, but I know we're gonna get things rolling this week!