---
layout: post
title: NBA
description: Alexa
img: /img/nba_cover.png
---

# NBA 

# Alexa Skill

## Customer Need
*"I want to keep up with my favorite teams, but I’m busy."*

**Business Need**
Stake a claim in the world of voice interfaces.

**Solution**
An Alexa Skill that checks scores, gives the schedule and plays live game audio.

<div class="img_row">
<img class="col three" src="/img/nba_cover.png"/>
</div>

Turner Broadcasting, the official digital partner of the NBA, approached my team looking to create an Alexa Skill. Their primary goal was to stake a claim in the world of voice interfaces.

During kickoff, I briefed the client on Alexa capabilities and made the recommendation that we start small. Best practices for voice dictate that interactions are brief, but valuable. Voice interfaces are in their infancy, and I felt keeping the scope small would set ourselves and users up for success. 

We concluded that broadcasting live game audio would be what our Skill would do. The client mentioned adding complete score and schedule functionality, which for the MVP, I recommended against since Alexa natively does that. I recommended we only do live schedule information, so users could know what games were available to listen to.

I began mapping those features to Intents. Intents are the individual pieces of functionality that a Skill has. Our intents would be: "Play A Game" and  “List Upcoming and Live Games.” Each of these intents required variations based on the depth and type of information the user gave us. For example: The “Play A Game” flow will prompt the user for a team name if they only say “Play A Game.”

This was the first time I had worked on an Alexa Skill. I whiteboarded rough flows with our developer for days. We researched the technical feasibility of our ideas. Then I presented my initial flow diagrams to the client.

The coming weeks mirrored that process with more detail being added each iteration. I worked out a long list of Utterances which would map to the intents. For example, to play a game one person says "Play the Hawks game" but another says “Turn on the Hawks game.”

During development of our Skill, a different NBA product team had developed their own Skill with score and schedule information. Stakeholders at NBA decided they wanted only one Skill. It was agreed that since the League Pass Audio Skill was executed so well, that our team would take over the task of merging both Skills. We needed to make sure our scores and schedule feature was better than the native functionality. Alexa native focused on individual teams and games. I decided that our Skill would also list scores and schedules for the entire league.

Merging the Skills presented its own set of challenges. When a Skill is named "NBA League Pass Audio" it gives the user a clear mental model of what they can ask it. This new Skill would be named “NBA,” which would require more hand holding to guide the user.

We brought in a 2nd designer. I staked her with doing flows for our new Intents. In the first iteration, I had been fleshing out a notation system for Voice interfaces. I taught it to the junior designer and had her put the flows in Invision as a way to contextually discuss the Intents. I worked closely with her to add and reduce complexity where needed. I edited dialog ensuring it was concise and easy to understand. I made suggestions on how we adhere to Amazon’s guidelines.

I couldn’t be happier about how the skill turned out. Our team solved some complicated problems to get to where we are today. The skill handles log in validation, multiple days of scores and schedule information and playing live audio. It does a great job of leading the user to the information they request without being long-winded and it’s one of the highest rated major sports league skills on Amazon.


