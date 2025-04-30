---
layout: post
title: "Request Page Working!"
author: Ryan Fuller
excerpt: "Just took a little while..."
---
I got a lot done this past week. Firstly, the way I was approaching the problem was pretty flawed in and of itself. Having every other resource *besides* textbooks in a potentially infinite dropdown menu was just not a good idea. So, instead, the dropdown was changed to just be all of the different types of resources someone could request, and the table would not hold just the textbooks, but everything. Furthermore, it is now filterable and paginated, so it won't be just one huge list and students can easily find what they are looking for.

The filtering was particularly tricky to get working. I am not a big fan of how JavaScript is written, so getting everything to match up correctly was more difficult than I expected. The row type was not matching with the type of each item, as one was fetching the display name and the other was fetching the enum type name itself. So, it was a matter of figuring out how to get the two to match, which, again, took a lot more code than I expected. But, everything works, and the requests will be saved to the database!

There is an issue with the pagination that needs to be fixed: if the "Next" option is pressed, it will reset whatever the filter was before, which is not helpful whatsoever. So this week will be focused on ironing out that kink and whatever else needs to be done to ensure the application is where it needs to be. A great, productive week overall!