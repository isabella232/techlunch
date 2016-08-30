# Tech Lunch

Every last Wednesday of the month, friends from tech companies of Paris gather
at Algolia to discuss tech-related subjects and share on challenges we
all face.

This repo holds the slides (Brunch + Reveal) that we use to present the meetup
every month.

## Ideas

Ideas for future events:

### Data Visualization

See with d3js meetup organisers.

### Support

How do you do support? Dedicated team, team effort, automated, manual? Do you
have a Q&A team, etc. Captain Train did a great talk about it.

### Buy or Build

Should you build something internally, or should you use an external service
that does it already? When is it better to do one or the other?

Stripe would be interested in presenting something.

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


