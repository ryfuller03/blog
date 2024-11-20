---
layout: post
title: "Database Visuals and Functionality"
author: Ryan Fuller
excerpt: "Editing the database"
---
This week's focus was on all the different aspects of the resource database's page. First, it was just making sure the page correctly popped up with the right URL and everything. Then, I moved on to changing the edit and create screens to match how the resource types are listed in the Miscellaneous Resource Request Form page. Then I spent a while researching different classes and ways to visually change how the table looks with bootstrap to make it look like more than just a Razor Pages Database page.

After that, I wanted to add a hyperlink to the nav bar to make sure that you could get to the resources database page easily while we edit and make changes to it. This caused me a bit of issues, but overall wasn't too bad. The problem was that instead of redirecting the user to the index page of the Resources directory, I was redirecting them just to some generic "Resources" page that didn't exist. So, I had to specify in the nav-bar that instead of just "Resources", it needed to go to "Resources/Index", and there was the page that I had been building.

Overall a very productive week that ended in some great progress on the database end! Next up is editing the edit/create pages to include the textbook fields if the "Textbook" option in the Type field is selected, just like how it responds on the Miscellaneous Request Form page.