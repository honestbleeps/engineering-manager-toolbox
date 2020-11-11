# Engineering Manager Toolbox
The Engineering Manager toolbox is meant to be a collaborative compendium of the things that Engineering Managers should remember to pay attention to over the course of a given time period. This is a living document, starting out and being shared earlier than I'd normally share something like this - so expect it to be a bit brainstormy, a bit unrefined at the start.

For the time being, it is *not* meant to be a reading list or a repository of links to tools, because several of those already exist. Instead, this is meant to primarily be prose and bulleted lists - a reference that Engineering Managers can go back to in order to ensure they're asking the right questions and keeping a pulse on all aspects of their teams' work.

I'd eventually like to link some of the lines/questions here to relevant articles or guides (either within this repo, or external) that elaborate on the "what to do about answers to question X", right now it's mostly just a list of questions to ask oneself


### Table of Contents
- [Introduction](#introduction)
- [Team Performance Tracking / Pulse Checking](#team-performance-tracking)
- [Individual Performance Tracking / Pulse Checking](#individual-performance-tracking)
- [Organizational Performance Tracking / Pulse Checking](#organizational-performance-tracking)

# Introduction
The job of an Engineering Manager varies a great deal due to a number of factors from team structure to industry to simple decisionmaking by the hiring manager (e.g. "should an engineering manager be writing code or not?").

This list is meant to cover the general topics that hopefully most or all engineering managers are keeping track of.  The idea here isn't to track these things in the literal sense, with metrics, but rather "things to keep your finger on the pulse of."

While this list *may* offer some prescribed solutions to specific challenges, please do consider that every team and team member is different! What solves a problem for one team may create problems for others. Take any advice here with the understanding that it was given with its own set of contextual factors.

Some of the things you'll find listed here (e.g. Velocity) may be obvious, and others may be things you don't personally think your team ought to track - that's fine! The idea here is more about being complete than about applying perfectly to every manager who makes use of this documentation.

# Team Performance Tracking

It's important to look not only at the performance, happiness, successes and frustrations of each of your individual teammates, but to also zoom out and see what the team looks like as a whole.  The following are some things you'll want to check in on, perhaps monthly or quarterly:

- Velocity - has it changed from prior months/quarters?
- Dev environment and setup
  - Do you have a README in each repo for setting up a local environment to start developing?
    - Is there a consistent format to that README across repos that includes common details you want (e.g. setup insructions, deployment pipeline details, integration testing details, etc)
  - Are you hearing / noticing mentions of issues with the dev environment in meetups? Does it justify carving out some time for the team to clean things up?
  - Even if you haven't onboarded a new engineer recently, can you get a fresh laptop from IT and run through the instructions on getting a local environment up?
    - Are the instructions still valid?
    - Are there bugs? 
    - Does the database seed reflect your current structure?
- Deployments - if you're not on a CI/CD pipeline, it's worth looking at a few things:
  - How much time are deploys typically taking?
  - How often are deploys being rolled back?
  - How often are repeat issues coming up during deploys (e.g. environment variable changes slipping through the cracks, migrations not run, etc)?
- Are team standups still useful and accomplishing the intended goal?
  - Are updates succinct and to the point?
  - Are team members providing useful information, or just rattling off ticket numbers?
  - Are team members remembering to ask for help / make the team aware of blockers when appropriate?
- Are team retros useful?
  - Is the team doing a good job of raising difficult issues, mistakes, etc but in a blameless manner?
  - Is the team comfortable with the manager in the room, or do they prefer the space to talk without them there?
  - Are the takeaways from retros actually being put into action / followed?
- Are the team's more senior engineers doing all of the things expected of them besides writing good code?
  - Are they as autonomous as expected?
  - Are they actively mentoring / helping other engineers?
  - Are they noticing problems with code on their own, or only in response to bugs?
- Is the team modeling inclusive behavior?
  - Are team members amplifying the voices of others?
  - Is there equity in both contribution and acceptance of ideas on the team?
  - Are team members soliciting the opinions and voices of others?
  - When there is disagreement in a team meeting, is the team respectfully self-moderating?
  - For managers with remote employees: Are considerations being made to ensure remote voices are heard regularly?
  
  

# Individual Performance Tracking

Of course keeping a pulse on individual employees is also important. Below is a list of things to monitor regularly:

- How is morale for this employee?
- How do they feel the team is performing?
- How do they feel the company is performing?
- What parts of the codebase are they most impressed with?
- What parts of the codebase do they think could use some work?
- What is their opinion on current processes
  - Are tickets well-refined / described from the start?
  - Is QA adequately up to speed on the tools?
  - Are QA and the relevant engineer(s) collaborating appropriately on testing strategy?
  - Are deployments smooth, or frustrating?
- How do they feel they're progressing in their career
  - What's their next career step?
  - Are they looking to progress, or more interested in simply having stability?
  - Do they feel the career ladder / expectations of their current/next role are clear?
  - Do they feel supported in being able to learn/do those things?
- Do they feel amply supported by their teammates?
- Do they feel amply supported by their manager?
- Do they model inclusive behavior?
  - Feedback:
    - Are people delivering feedback to each other, even when it's difficult?
    - Are people receiving feedback gracefully?
    - When was the last time your team delivered feedback to you *about* you? (If it has been a while, solicit some)
  - Communication:
    - Do they interrupt others? If so, do they notice and return the floor to those they interrupted?
    - Do they notice when others interrupt, and return the floor to the original speaker?
    - Do they acknowledge and amplify the contributions of others?
    - Are they about their use of pronouns in examples, documentation, requests, etc? e.g. using "they" rather than "he" or "she"?


# Organizational Performance Tracking

- How many team members in your org are trained to conduct interviews?
- Are you satisfied that your interview process is effectively vetting/evaluating candidates on the skills your org is looking for?
- Do you know who the organization's stars are, even if they're on other teams?
  - What are you doing to support them and propel them forward?
  - Are they/you leveraging their great performance to make the team around them better?
- Do you know who's struggling, even if they're on other teams?
  - What's your plan to help them out of the rut, and have you communicated it?
  - What's their plan to get out of the rut?
- What upcoming promotions might your organization have in the next few months?
  - If you have some, have you calibrated and looked to ensure they're being promoted on a comparable timeline to similarly performing peers?
  - If you have none, what can/should you be doing to help folks in the organization level up?
