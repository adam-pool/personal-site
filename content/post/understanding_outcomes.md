+++
title = "Tying It All Together"

date = 2018-06-01T00:00:00
lastmod = 2018-06-01T00:00:00
draft = false

tags = ["DevOps"]
summary = "How do you correlate your organizational changes to your outcomes?"

[header]
#image = "headers/getting-started.png"
#caption = "Image credit: [**Academic**](https://github.com/gcushen/hugo-academic/)"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-default.png"
caption = "Default"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-ocean.png"
caption = "Ocean"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-dark.png"
caption = "Dark"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-forest.png"
caption = "Default"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-coffee-playfair.png"
caption = "Coffee theme with Playfair font"

[[gallery_item]]
album = "1"
image = "https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/theme-1950s.png"
caption = "1950s"
+++

Anytime a group or an individual makes a change to the way things are done one of the first questions they are likely to be asked is "So what?". You reduced the time it takes to deploy from four days down to four hours. "So what?". I know what you're thinking. Any deployment time reduction sounds great on it's own. In reality though, everything we do as an organization really ties to business outcomes. How can we demonstrate that the things we are doing are having an impact on business outcomes?

![Screenshot](https://www.cloudtp.com/wp-content/uploads/2016/06/stop-focusing-devops.png)

First off, you need to understand how to measure all of the steps in the DevOps flow so that you can show correlation. You need to be able to tie your planning behaviors, execution behaviors, delivery results, and business outcomes together. If you do this successfully and an area breaks down you should be able to identify the root cause.

If you have read my other post on [how to measure your DevOps maturity]({{< ref "getting-started.md" >}})  you will see that your planning and execution behaviors can be measured through surveys. I would suggest that you include questions that include your feedback intake mechanisms, data analysis, Agile practices, and Continuous Delivery maturity.

Once you have measured those things, you will then need to take a look at your delivery praactices. Pace, Quality, and Throughput are good targets. When you measure your Pace it's literally as simple as how frequently you are delivering. This varies from company to company and industry to industry. If you are in a less regulated industry such as Netflix, you might be pushing thousands of software deliveries a day. If you are in a financial field, regulations may slow you down quite a bit.

Quality can be measured in a couple of different ways. I am a big fan of measuring the number of production incidents, as that is always a good mark of software quality. You may also want to measure application performance as well as availability. Those three indicators will give you the best idea of the quality that your customers are experiencing. If you don't have mechanisms in place to measure these things, I highly suggest you start.

Throughput is nothing more than measuring the business functionality that is moving through your pipeline. What I mean by this, is that if your team is busy working on production incidents and deploying fixes several times a day, their Pace measurements might look great. However if they aren't pushing out any business valued functionality then the pace of delivery really doesn't matter. They are essentially treading water and this is an indicator that Quality needs to be scrutinized.

Once you have measured all of those things it's time to measure your business outcomes. Your objective should be customer delight. If you have properly tied your feedback mechanisms to your planning behaviors then your desired business outcomes should be mostly known. You can measure whether or not your are achieving those goals in any way that you please. If those goals aren't being met, I would be willing to bet that you can trace back through the previously mentioned measurements and identify the root cause.
