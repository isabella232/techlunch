# Tech Lunch

Every last Wednesday of the month, friends from tech companies of Paris gather
at Algolia to discuss tech-related subjects and share on challenges we
all face.

This repo holds the slides (Brunch + Reveal) that we use to present the meetup
every month.

## Ideas

Ideas for future events:

### Data Visualization

See with d3js meetup organisers / ToucanToco

### Machine Learning

Fabien Vauchelles did a very nice explanatory talk at the TakeOffConf 2016.
Might be nice to explain the basics, and then who is doing what with it.

### (Chat)bots

Amazon Echo or Slackbots, a lot of API calls are going to come from bots. What
should be changed in an API to make it more bot-compliant? What can be built
with it? How does this change the way we interact with API?

Nicolas Grenié talked about it at TakeOffConf 2016. Dustin did build an Echo
/ Algolia integration. CommitStrip used Wit.ai and Algolia.

### Internet of Things

More and more devices are connected. Connected home, connected car, connected
whatever. We also saw a massive DNS DDoS attack from an IoT botnet. How does
this change our business? Is that new ways of consuming APIs? Is that new
devices to build for? Is that new tools we can use ourselves?

### CI

How to do your CI. Travis is nice for open-source but the 5 concurrent jobs slow
us down. Pro version is expensive for only 10 jobs.
Gitlab CI seems nice, but too coupled with Gitlab.
CircleCI? I was not hearing good feedbacks from it.
Manual Jenkins?

Would be nice to have talks from people each using a different solution.

## Local testing

```
npm install
npm run serve
```

Slides will be available on [http://localhost:5013/](http://localhost:5013/)

## Pushing

Use `npm run deploy` to deploy on
[https://community.algolia.com/techlunch-slides/](https://community.algolia.com/techlunch-slides/)

## List

To get the list of attendees for an event, run `npm run list {meetup.com url of
the event}`


