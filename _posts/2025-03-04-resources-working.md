---
layout: post
title: "Resources and Requests"
author: Ryan Fuller
excerpt: "It's all connected..."
---
Finally, it's all working! I was debugging and trying to figure out exactly what was going wrong by just changing a bunch of things, dropping the database (not necessary) and a TON of Stack Overflow searching, when I realized that the console has been right there all along. Who knew that the thing that runs our programs could be so powerful in helping run programs?

So, I decided to start placing some Console.WriteLine() functions in functions, and finally saw that the issue was in the model's validation. It could not be validated for some mystery reason, therefore the Resource object would never be added to the database. After writing out a loop that checks what each error message is, it was obvious that the problem was the Requests ICollection in the Resource model. With the addition of the Requests DBSet, this is a completely useless parameter that isn't even being used when initially seeding the database, so I got rid of it, modified some files that needed adjustments, and everything works perfectly now!

I am so glad that it all works and that this entire kerfuffle is over. This was pretty challenging, but like almost every problem I run into, it just takes looking at it from a different angle and taking advantage of all possible resources to get it solved.