# Basic Knowledge Graph Extraction

This isn't great, and there are likely better solutions (e.g., [see this thread](http://gptprompts.wikidot.com/chaining:using-the-fringe)) but worth noting GPT-3's ability to extract relationships.

```
Ironscales, a Ramat Gan, Israel-based self-learning email security solutions, closed an $8m Series B extension funding round.
-- Ironscales <--located--> Ramat, israel
-- Ironscales <--do--> self-learning email security solution
-- Ironscales <--raise--> $8M

With a renewed focus on creative skills, online learning company Skillshare raises $66M
-- Skillshare <--raise--> $66M
-- Skillshare <--do--> creative skills

CakeResume, which wants to become Asia’s largest tech talent pool, raises $900,000 seed round
```

In my case, the output for the above was...
```
-- CakeResume <--located--> Beijing
-- CakeResume <--do--> tech talent pool
-- CakeResume <--raise--> $900,000
```
