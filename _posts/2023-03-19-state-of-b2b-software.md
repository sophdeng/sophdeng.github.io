---
layout: post
title: "Mo' software, same problems"
---

For the last 10 years, we've been living in a golden age of B2B software. There's software that captures sales engineering workflows, streamlines the quote-to-cash process and attempts to solve evermore pointier-point problems. 

There's so much software available. But how come it doesn't feel like we're living in a corresponding golden age of company productivity? 

A telling sign is how prevalent spreadsheets remain in managing operational processes. You'd think that if so much software is out there making workflows less manual or resolving hyper-specific problems, then there should be fewer serious use cases for spinning up spreadsheets. The average startup purchases 103 SaaS applications [^1], so stitching some combination of the 103 applications and their data, should be able to cover a company's array of business logic...Right?

Here's a cynical take, one I think should be honestly put forth -- most recent B2B software hasn't been substantially better for users. Smart founders have been flooding the startup ecosystem for the last 5 years like hypebois to Supreme. But instead of searching for t-shirts, teams have been rabidly searching for any problem to solve and any opportunity to capture customer value. The result has been a flood of software vying to be part of the worker's day-to-day: _Pick ME to be where you perform your core activities_ or _Pick ME to be where you input in key data_. But it's unclear whether these products - made in a pressure cooker of hyper-speed and hyper-competition - have been designed with any real secret or differentiated insight into how to benefit users. 

B2B startups commonly look to Salesforce, which sits at ~$185 billion in market cap, as inspiration for how to become more valuable. Something I find totally underappreciated in Salesforce's story is their role in inventing B2B SaaS sales. To put it another way, Salesforce literally defined the method for selling a new category of software, B2B Software-as-a-Service applications, in the 2000s. The innovation was the sales methodology. Salesforce's next genius was creating software to proselytize the methodology at scale, wrapping the high-level stages of the sales process around a user interface. While Salesforce has done many things right in their 20 years, it started with a real point of view on a new way to work. 

Here's a different take about the disconnect between the availability of B2B tools and company productivity -- perhaps we're hitting a ceiling around how useful non-custom software is. Part of this is timing, part of this is the limit of what generic software can do.

A lot of B2B software is produced in a formulaic manner:  Understand the user's workflow and their function. Find a piece of it to improve and wedge into behavioural change. Expand to more pieces of the user's job, and ideally, expand into that persona's entire function. If the product sees decent usage, then comes the critical product tradeoff to make: Should the product provide higher usefulness for specific users or types of businesses, or remain less useful but more accessible to a wide base?   

Most founders I know cannot fathom shrinking their potential market size. Taking this side of the tradeoff is questionable today, but it was a no-brainer 10-20 years ago when any company using computers had hair-on-fire problems for how to work in a digital manner. Talk to anyone who experienced what it was like doing support before Zendesk came along in 2007, and you'll hear it was a shitshow: people were answering customer requests in their personal email accounts, and you had to talk to coworkers to confirm there wasn't cross-solving of tickets. Zendesk created a high-level scaffolding around the request handling process, with an interface for people to collaborate and understand how to handle tickets. 

Just like Salesforce for sales, the request handling scaffolding has up-leveled how support is done across all companies. Yes, Zendesk is brittle for reflecting custom business logic, but the core scaffolding - the steps from triaging to resolving a support ticket - is quite solid. This means that a new horizontal case management system wanting to service _every_ company has a far harder time introducing substantial value on the scaffolding level, which is where most value lies. It also means that unless a startup is radically re-imagining support, vying to just be a 2-5x better case management software for _everyone_ may be a hopeless battle when generic gain is devalued by users. It's a hard time now to be something for as many companies as possible, when the big problems for how to work with screens have gotten so much problem-solving love.  

Where does that leave us? Throwing out more B2B products without any point-of-view or depth will continue to have diminishing returns for users. One way forward for anyone looking to build B2B software is to take the other side of the product tradeoff. Especially in highly immersive and specialized verticals, there's still opportunity to increase how useful third-party software scaffolding is. The scaffolding will address a far narrower base of users, but it will be more useful to customers than a generic scaffolding tool. 

The other path forward could be extreme software customization. Internal software is around 50% of all software [^2]. I think that number will either stay the same or rise in future.  There seems to be a metabolism to how much third-party software can simply solve for companies, given that all companies are snowflakes and given the tradeoffs any product serving more than 1 customer has to make. 

Is this then a bull case for custom software? 

At the very least, some things will need to change with internal software development. On the terrible end, we've been required to use hoards of software-specific intermediaries - think Salesforce or Zendesk developers and UiPath consultants - to extend those applications. Ugh, that needs to go away.  On the positive end, there's been great developer tools like Retool that allow engineers to build internal software faster. While I'm a huge Retool stan, even there, I've experienced how co-developing and iterating on tooling can be bumpy between end users and engineers in growing companies.

I suspect large language models (LLMs) will be an interesting way to blow open the aperture of making custom software more comprehensive and easier to build. With software like Salesforce or UiPath, could we self-service extending these applications that use domain-specific language or require training to understand? It would be great to live in a world where [expensive back-and-forth development process with service providers]( https://www.reddit.com/r/salesforce/comments/i0hgiv/whats_your_experience_with_salesforce_consulting/) is nada. Or could we spin up internal applications with little to no engineering dependency if workflows are well-articulated? And how about custom software that holistically factours in a business's entire corpus of code, wiki, conversations, product/design strategy and goals?  

The ideas are taking on a dreamlike state, so I'll stop there. 

It's harder to find valuable problems to solve in B2B. But there's still exciting opportunities when we plunge deeper and fringier.  

 _Some essays I read while writing this include Kellan Elliott-McCrea's ["Software and its Discontents, Part 2](https://laughingmeme.org/2023/01/23/software-and-its-discontents-part-2-complexity.html) and Tristan Handy's ["The Modern Data Stack: Past, Present, and Future"](https://www.getdbt.com/blog/future-of-the-modern-data-stack/)._

 ---


[^1]: This is according to Bettercloud's 2020 State of SaaSOps Report: https://pages.bettercloud.com/rs/719-KZY-706/images/2020_StateofSaaSOpsReport.pdf

[^2]: This is the source: https://techcrunch.com/2022/07/28/retool-raises-45m-at-a-3-2b-valuation-to-make-building-custom-software-as-easy-as-buying-off-the-shelf/, but I'm not sure how the stat is calculated. 
