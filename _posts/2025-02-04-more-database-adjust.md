---
layout: post
title: "Database Reworking and Navbar Work"
author: Ryan Fuller
excerpt: "Database Stuff is NOT Impossible!"
---
The first week back with Disco Tray was a little more eventful than I thought it was gonna be. There were (inevitably) more issues with the database, but the biggest one was that we were constructing it in the complete wrong way. By we, I mainly mean me. Instead of storing only the resources available and sending the requests to the SOS department's email, the requests will be stored on the website. This ensures the email will essentially be obsolete, as they use it for everything right now and it's a big pain. So, resources *and* requests will be stored in the database, and a resource can be a textbook and store more information such as the serial number, edition, etc.

I also wanted to update the site's navbar to have white text instead of black. It fits the theme a lot better, but it feels a bit weird because it's been black for a while. It was a little more complicated than I thought: I had to overpower some specific parameters within bootstraps' CSS files, which I didn't know you could do, but now I do!

This week was a big fat learning experience. I learned a lot about how CSS and HTML files interact with each other, specifically where to change certain styles and parameters. I also learned more about how to simplify the connection between the database and the website. What we were doing was much more complicated than what we needed to do--a situation that will absolutely stick with me and influence how I program later projects (and even this one!).