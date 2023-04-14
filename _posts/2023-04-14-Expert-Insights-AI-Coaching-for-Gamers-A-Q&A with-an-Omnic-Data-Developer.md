---
title: "Expert Insights: AI Coaching for Gamers - A Q&A with an Omnic Data Developer"
date: "2023-04-14 08:00:00 -0500"
categories: ["Omnic Data","Q&A"]
tags: ["Valorant","AI Coaching","Gaming Industry","Fortnite","Computer Vision","Game Analytics","Player Improvement","Artificial Intelligence","Developer Insights","Competitive Gaming","Esports"]
author:
---

![Developer](/2023-04-14-Expert-Insights-AI-Coaching-for-Gamers-A-Q&A with-an-Omnic-Data-Developer.png)

Welcome to our exclusive Q&A blog featuring insights from Nat Youngren a developer at [Omnic Data](https://www.omnic.ai/), who is part of the team behind the innovative AI coaching platform [Omnic Forge](https://forge.omnic.ai/) for [Fortnite](https://www.fortnite.com/) and [Valorant](https://playvalorant.com/en-us/). In this discussion, we explore the challenges, successes, and future of AI-driven coaching in gaming, as well as some light-hearted fun questions. Join us as we delve into the developer's perspective on revolutionizing player growth and strategy through cutting-edge AI technology.


**How do you adapt computer vision technology to recognize and analyze the unique gameplay elements of Fortnite and Valorant?** 

The field of computer vision has seen so many advances recently that the hardest part is often just keeping track of available technologies and applying them correctly to the tasks at hand.

The good news is that games across many genres share universal design elements, aimed at making these games easier for human players to pick up and learn at a glance. Game designers put a lot of thought into exposing information to a human player through visual cues, HUD elements, and consistent silhouette/color patterns.

Each game comes with unique considerations, but most problems can be generalized into a combination of detection, classification, and/or text analysis.


**What challenges have you faced in developing an AI model that can provide relevant and actionable feedback for players across two distinct games?**

There are a lot of tricky factors to consider, it can really feel like a balancing act. We actually have much more data available to us than we require to train AI analysis, and we work with both professional players and human coaches to inform our approach to each individual game. AI is capable of identifying an incredible range of patterns, but the ultimate goal is to train and frame that analysis in a way that can assist HUMAN players in the improvement process.


**How has the AI's analysis helped professional players to refine their strategies and boost their performance?**

With such dramatic TTK, the name of the game in Valorant is pre-aim, which requires map knowledge, disciplined control over your crosshair, and a keen sense of your opponents whereabouts. Through identifying and tracking onscreen player entities Forge is able to provide detail about a player’s ability to enter engagements with the best possible chance of winning.

Professional players can use this data to identify points of weakness, and with their feedback we will continue to present our data in new and informative ways.


**Can you discuss the process of creating training data for the AI from actual gameplay footage?**

A significant portion of my work has been spent crafting tools which optimize the development process. To this point, we now have an indispensable toolbox of training data utilities which allow us to easily convert video files into sampled frames, then further crop, sort, label, and organize that data to suit whatever detectors we are currently working on. Since the computer vision pipeline we have developed is largely a generalized framework, the process of implementing those detectors is almost drag-and-drop once the training is complete.


**How do you ensure that the data is diverse and representative?**

As with most AI technology, this is something we have to carefully approach. Games support accessibility options, HUD scaling, various languages, cosmetic customization, and a vast array of screen resolutions, to name only a few of the possible issues. Our goal is to maximize our coverage of these options whenever possible. A simple example, from Valorant, would be building our training data to include the range the possible enemy highlight colors. The good news is that modern computer vision is fully capable of handling variation. Our models typically become more attuned to the nuance of our detection targets when we expand the data to encompass these options, and we see improved accuracy across the board.

A reality of computer vision is that perfection will always be unattainable, but our models can only improve as we continue to identify edge cases and expand our coverage.


**What do you think the future holds for AI-driven coaching in the gaming industry, particularly for games like Fortnite and Valorant?**

Personally, I think AI is an inevitability for the gaming industry. We have all seen the conquest of reinforcement learning in so many genres of gaming, from chess to DOTA 2 (a personal favorite). AI is already incredible at optimization and self-improvement, but the next frontier is exploring how we can best apply AI to our own individual progress.


**If the AI could form a dream team with famous characters from Fortnite and Valorant, who would be on the roster and why?**

Out of innate robotic sympathy I would have to say Kitbash and Oppressor from Fortnite, and obviously KAY/O. But between you, me, and all the duelist spammers out there, I believe Reyna is in more of our training games than any other agent. Forge might appreciate the familiar face.


**Have you ever witnessed the AI getting "confused" by unusual in-game antics or strategies? Tell us about that amusing experience.**

I remember when I was working with our inventory and economy data, and I was just about to tear my hair out over some ridiculous results. I really thought I’d have to rebuild the detector again with more training data. Turns out the player was simply blowing his last-round credits and flinging guns back and forth with his teammates. Honestly, I was impressed after I found out, as the detectors captured everything just fine. Those sorts of behaviors can ultimately be confusing to an AI so I made sure to account for that in the backend.


**If the AI were to create a Fortnite skin or Valorant agent based on its own personality, what would it look like and what would its special abilities be?**

If the AI were to create a Fortnite skin? I consider Forge to be an everyman, he’d wear the default skin but downgraded to a grainy and consistent 720p. Nothing pretentious. As for Valorant, I think Forge would prefer zero bullet deviation and an ultimate that deletes Yoru from the game, that clone is not computer-vision friendly!

We hope this Q&A with Nat Youngren has sparked your curiosity about the potential of AI coaching in gaming. We invite you to try out [Omnic Forge](https://forge.omnic.ai/) and experience the benefits of AI-driven analysis firsthand. As the gaming industry continues to evolve, so does our approach to enhancing player performance. Stay tuned for more exciting installments in this series, as we keep exploring the cutting-edge intersection of AI and gaming. Happy gaming!