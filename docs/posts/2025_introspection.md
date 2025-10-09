---
draft: true


date: 2025-10-01


categories:
  - introspection
  - motive
---

# 12 years of 'machine learning' engineering in a blink

  ![clock](/img/clock_time_pass.jpg){ width="100%", loading=lazy}

!!! note
    This article is non technical and personal.
    The reader may not get much out of it as it intends
    to help myself shape the next decade of objectives to pursue.
    Making it public is a desired constraint to flesh it out more plainly.

## Intro

I am a father since two weeks and the priority of my life just changed forever.
It's time to take a step back and think of what I achieved in this first part of
my professional career.

I am amazed by how fast time have passed.
It has been 12 years already forging machine learning applications as a living.

From start-ups of my early days to entrepreneurship, then freelancing and big company,
it's always thrilling to apply cutting edge research from dozen to millions of customer devices.

What a lucky man I am, paid to read scientific articles, implements and improve
over ideas at the frontier of what is known possible, in one of
the hottest field of our time that is deep learning.

## Retrospective

The journey have been good to me until now.

The first startup I worked with was more of a 2nd family, that helped us to grow.
I am forever thankful to Jerry & Nico the 2 veterans founders for that.
Their humanity and 'warping' optimism along side a good dose of 'deliver fast' and 'push to prod' make wonders.
They gave me a chance while they were looking for a seasoned machine learning engineer: a job that was very
uncommon on the market and I had little to no experience back then.
I learned a lot here on how to build data pipelines, create models that eventually solve business goals with them.

2y after, I was too confortable. As they switched toward more classical business with less need for data science I felt it was time
for me to say good bye, and try something new I had dreamed to do since university:
Starting my own company in speech understanding for call-centers. It was a drastic change.
A far broader skill-set became needed and to be clear I was (and still is) a clueless beginner in most areas: sales,
pricing, marketing, front-end, product development ... BUT I enjoyed so much testing those new hats !!
This period of my pro-life was extremely exciting, it was incredible to finally set objectives based on my convictions
to solve big real world problems.
So many people I shared demo of the product were impressed of what was achieved in such short amount of time,
but after almost 2 year of work, loneliness took a profound toll on me.
That's probably my biggest regret, I failed to gather a proper team around the project:
In retrospect there were opportunities.
I was probably too young too introvert and despite my own first clients proposing me to become partner,
or being approached by a fundraiser to perform a proper 'seed' fund, I declined.
Postponed forever by thinking wrongly that the kind of project I was working on could be bootstrapped by the first clients revenue.
Another key failure in this adventure, was likely to have spent too much time in features creep,
those I was good at realising.
Not enough time was allocated to build the core 'value' proposition of the company that was a good 'tailored speech recognition system' for the specific business
cases I was targeting.
At first by taking too much time to recognize that external providers speech recognition API weren't good enough and charged too much to build a viable business.
Later spending too little time training speech models, by lack of focus and too few data gathered for the 'locale'.
A cardinal sin, that I will try too never forget again.

In 2018, I was out of money and started to look at some freelancing to buy some time. After a market search
I landed a permanent job at Parisian startup. It was not the original goal, but I thought I would just quit after some time.
They also focused on speech recognition, their end product being a private by design 'voice smart assistant' that could be tailored to client needs and ran fully on a mere Raspi 3.
It was an opportunity I could not refuse, first because this was the occasion to strengthen my knowledge in deep-learning and speech
recognition, but also because after so long it was the occasion to meet with people that shared the same passion
I have: building ML systems and experimenting with cutting edge technologies. This company was at the opposite spectrum of what I was trying to build before: 50ish peoples gathered from around the world, a product pivot every year, money raised again and again without much paying clients. Here, I met some really smart people full of energy, some became friends and time passed one crazy event at a time. In 2020 the startup was acquired by a big company. I felt I still had to learn so much I could not leave.

Like all acquisitions, big companies attract different talent than startups. People started to slowly leave the boat, one at a time, few hiccups in management and product release accelerated the process. Among the numerous things I learnt in this new era, one is maybe apart: the process to conduct experimental research with successive written logbook reports followed by a global advancement report (something I very much intend to do in this blog from time to time). Is probably the thing that was most alien to me and my 'startup' mindset. The first time I did it I felt so illegitimate. Today I can not even think do do serious ML research without this process. Looking back at projects from 2020 and being able to recover the work realised back then is simply invaluable.

During this last years, I also got opportunity to share some of that joy back to the community,
by [an article on 'small footprint voice identification' accepted to ICASSP in 2021](https://scholar.google.com/citations?user=tV8RVtcAAAAJ&hl=en&oi=sra),
a published an open source library [torch-to-nnef](https://github.com/sonos/torch-to-nnef) this year aimed as a strong bridge between PyTorch and the Neural Network Exchange Format 'NNEF' ([introduction article here](https://tech-blog.sonos.com/posts/torch-2-nnef-open-sourcing/)), or regular
contributions to [tract](github.com/sonos/tract) an open source neural network Rust inference engine
maintained by Sonos.
I never thought, it would be possible for a simple 'applied' research engineer like me,
to attend conferences like ICASSP 2021, 2022 & Neurips 2023, living these incredible events
from the inside, seeing and discussing with the authors behind latest advances in
deep learning, ASR, Large Language models, reinforcement learning ...
But also the FOSDEM and EuroPython with people of such diverse background and experiences continually
willing to share and improve technology openly.
Those people fuelled with passion, eager to share their discoveries to the world,
made a positive imprint in me and helped shape who I am.

Still I would be lying saying it's have been a perfect honeymoon:

So many projects, so many urgent features that where of core importance back then.
Most, merely useful at some point in time and so few withstanding the test of time.
Sometime it feels our industry is just an house of card slowly but continually churning.
Dinosauria we.

As I grow old I am more and more attracted 2 kind work.

## 1. The public projects

The public projects that stands still.
Here seems to lie the biggest impact for our societies in programming:
the foundation of most technological project I know of.
From operating systems, to programming languages, to the library used within a project private or not.
We build on top of each others one brick at a time.
Those projects are strange living human construct,
fed by the attention of the open crowd, it becomes so hard to compete
against those once a big community gather around them.

At their core there is always at least few stubborn peoples that will
maintain and make those evolves beyond reason, mostly because they enjoy playing
around the problems they framed for themselves. Which is funny to think of, we are
driven by passion to build one of the most 'logical' technology existing today.

## 2. The experiments that challenges status-quo
