---
draft: false


date: 2025-10-11


categories:
  - introspection
  - motives
---

# 12 years of 'machine learning' engineering in a blink

  ![clock](/img/clock_time_pass.jpg){ width="100%", loading=lazy}

!!! note
    This article is non technical and personal.
    The reader may not get much out of it as it intends
    to help myself shape the next decade of objectives to pursue.
    Making it public is a desired constraint to flesh it out more plainly.

## Intro

I am a father since 3 weeks and the priority of my life just changed forever.
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
Their humanity and 'warping' optimism along side a good dose of 'deliver fast' and 'push to prod' made wonders.
They gave me a chance while they were looking for a seasoned machine learning engineer: a job that was very
uncommon on the market and I had little to no experience back then.
Here, I learned a lot here on how to build data pipelines, create models, scale workloads, in service of various business goals, with what most would
call today traditional (trad) ML.

2y after, I was too comfortable. They switched toward more classical business with less need for data science. I felt it was time
for me to say good bye and try something new I had dreamed to do since university:
Starting my own company in speech understanding for call-centers. The core idea was that we need to stop punish 'operator' and instead cherish the customer
relationship by a deeper conversational/emotional analysis of customer call. This can be measured and aggregated on global dashboards linked back to all those detailed conversations. It was a drastic change.
A far broader skill-set became needed and to be clear I was (and still is) a clueless beginner in most areas: sales,
pricing, marketing, front-end, product development ... I never worked so much BUT damn, I enjoyed testing those new hats !!
This period of my pro-life was extremely exciting. It was incredible to finally set objectives based on my convictions
to solve big real world problems.
So many people I shared a demo of the product were impressed of what was achieved in such short amount of time,
but after almost 2 year in, things were not yet good enough, and I started to feel drained.
A key failure in this adventure, was likely to have spent too much time in features creep, on things I was good at realising.
Not enough time was allocated to build the hard core 'value' proposition of the company that was: a good adaptive 'tailored speech recognition system' for the clients.
At the beginning I took too much time to recognize that external speech recognition API providers weren't good enough and charged too much to build a viable business.
Later I spent too little time training speech models, by lack of focus and too few data gathered for the 'locale'.
A cardinal sin, that I will try too never forget again.
Secondly, Loneliness took a profound toll on me. That's probably my biggest regret, I failed to gather a proper team around the project:
In retrospect there were opportunities.
I was probably too young too introvert and despite my own first clients proposing me to become partners,
or being approached by a fundraiser to perform a proper 'seed' fund, I declined.
Postponed forever by thinking wrongly that the kind of project I was working on could be bootstrapped by the first clients subscriptions.

In 2018, I was out of money and started to look at some freelancing to buy some time. After a market search
I landed a permanent job at Parisian startup. It was not the original goal, but I thought I would just quit after some time.
They also focused on speech recognition, their end product being a private by design 'voice smart assistant' that could be tailored to client needs and ran fully on a mere Raspi 3.
It was an opportunity I could not refuse, first because this was the occasion to strengthen my knowledge in deep-learning and speech
recognition, but also because after so long it was the occasion to meet with people that shared the same passion
I have: building ML systems and experimenting with cutting edge technologies. Funnily, this company was at the opposite spectrum of what I was trying to build before: 50ish peoples gathered from around the world, a product pivot every year, money raised again and again without much paying clients. Different also in that, I met some really smart people full of energy which allowed me to grow again, some became friends and time passed one crazy event at a time. In 2020 the startup was acquired by a big company. I felt I still had to learn so much, I could not leave.

Like all acquisitions, big companies attract different talents than startups. People started to slowly leave the boat, one at a time, few hiccups in management and product release accelerated the process. Among the numerous things I learnt in this new era, one is maybe apart: the process to conduct experimental research with successive written logbook reports followed by a global advancement report (something I very much intend to do in this blog from time to time). This is probably the thing that was most alien to me and my 'startup' mindset. The first time I did it I felt so illegitimate. The 2nd, that so much time was spent for something ad-hoc. Then it became an habit and today I can not even think do do serious ML research or advanced engineering without this process. Having written material for discussion or looking back at projects from 2020 and being able to recover the work realised back then, is simply invaluable.

During these last years, beyond working on large language model finetuning and quantization,
I also got opportunity to share some of that joy back to the community:
by [an article on 'small footprint voice identification' accepted to ICASSP in 2021](https://scholar.google.com/citations?user=tV8RVtcAAAAJ&hl=en&oi=sra),
a published an open source library [torch-to-nnef](https://github.com/sonos/torch-to-nnef) this year aimed as a strong bridge between PyTorch and the Neural Network Exchange Format 'NNEF' ([introduction article here](https://tech-blog.sonos.com/posts/torch-2-nnef-open-sourcing/)), or regular
contributions to [tract](github.com/sonos/tract) an open source neural network Rust inference engine
maintained by Sonos.
I never thought, it would be possible for a simple 'applied' research engineer like me,
to attend conferences like ICASSP 2021, 2022 & Neurips 2023, living these incredible events
from the inside, seeing and discussing with the authors behind latest advances in
deep learning, ASR, Large Language models, reinforcement learning ...
Meeting people of such diverse background and experiences continually
willing to share and improve technologies openly to the world,
made a positive imprint in me and helped me shape who I am.

The journey was good, still I would be lying saying it's have been a perfect honeymoon:

So many projects, so many urgent features that where of core importance back then.
Most, merely useful at some point in time and so few withstanding the test of time.
Sometime it feels our industry is just an house of card slowly but continually churning.
Dinosauria we.

This background set, I think it's time to think of the future by a reflection of what kind work attract me most.
In a Gist: the public projects and the research experiments.

## 1. The public projects

The public projects that stands still.
Here seems to lie the biggest impact for our societies in programming:
the foundation of most technological project I know of.
From  programming languages, to operating systems, to the libraries used within each software private or not.
We build on top of each others one brick at a time.
Public projects are strange living human construct,
fed by the attention of the open crowd, they become so hard to compete
against those once a big community gather around them.

At their core there is always at least few stubborn peoples that will
maintain and make those evolves beyond reason, mostly because they enjoy playing
around the problems they framed for themselves. Which is funny to think of, we are
driven by passion to build one of the most 'logical' technology existing today.

### torch-to-nnef

In that respect `torch-to-nnef` is probably my main attempt to contribute.

Why I take the burden to start and maintain such project ? The defensive
answer could state the value proposition: This is a solution to better exchange our PyTorch models to the [tract](https://github.com/sonos/tract) neural inference engine since 2022.
Still that does not explain my motives.
If I am being realistic, [ONNX](https://onnx.ai/) could fit the bill, modulo few limitations here and there (and likely some will shrink with time).
The project is too big for a single person: bridging 2 libraries that evolve that fast without control on 1 side, is so time consuming:
 We will likely never reach the final goal to be a complete general purpose exchange.
More importantly, this 'exchange format' project is rather far from my usual beloved ML formulation and optimization experimentations.

So, what's the deeper 'reason' ?
It may be in part that it help me understand in-depth the linear algebra primitives that compose our deep-learning models.
How they compose together ? Putting myself in that position allow me to better understand latest neural network architectures.
It's also an enabler when it come to my 'unusual' quantization attempts, performance squeezing, or more recently to export model that does not fit in RAM in full precision.
Still this project will probably always be 'niche' and the attracted community is tightly tied to tract, which is not very significant to begin with.
Don't get me wrong `torch-to-nnef` open sourcing is a milestone I am happy with, and I plan to continue to maintain it. This is just not enough to fulfill
my thirst to help our field move forward with more innovative public projects.

## 2. The experiments that challenges the status-quo

The second technical area I enjoy most is likely *experimentation*. Optimising predictive models toward the final end product goal is so fun.
From building solid datasets with classical data-science, to challenging our evaluations and metrics, to designing the neural network itself. I
did all those steps so many time for so many projects.

Selecting latest convincing techniques published, reformulating it to our goal, improving it,
by validating/discarding hypothesis one at a time, is probably the most thrilling part for me. The critical thinking, the knowledge shared and created around the discussions
that come after the experimental reports, are wonderful and so fruitful. From my experience, this is what a lot of 'start-up' and short timed project miss,
this time to explore bring unforeseen opportunities. Without it we are just good copist, greasing an engine and doomed for incremental small improvements.

Yet, it's impressive how subtle our work can be. Optimization is such a slippery beast.
Do not assume prior work reported is always perfectly handled, final model working is **not** a proof of correctness.
As a friend of mine would state a good scientist is at first a good engineer: Basics should be reassessed regularly with low ego.
I recall vividly a deep learning model that was core to our stack, it had a very simple framing, with years of works in: Talented peoples had completely missed to (re-)set a proper learning rate decay and training time. They did probably not revisit the parameters after some data ingestion. Impact was crazy: this meant all subsequent experiments were non-conclusive (that was couple years of work). Fixing that, in the 2 month after few reassessments, we had increased by 70% the quality of the model relative to our baseline.

In the recent years few core principles stood-out in that area for me: Fast iteration cycles with proper reproducibility and plain reporting are of core importance.
If validating an hypothesis take more than 2 weeks of training the iteration loop is broken and launching experiments asynchronously is not a solution. Indeed managing in parallel experiments is exponentially hard, as their number grow. Large model training do not escape this rule, each trick allowing faster training is a blessing.
By example let's imagine you tweak the hyper-parameters A from a baseline then the parameter B and C from same baseline. If A is reactive and C too
is B+C still leading to improvements ? Guess what, sometime it's can be worse.

Navigating this meta-optimisation process led by the practitioner is never the same. Damn it's hard to avoid hitting local minima.
Even if with time come intuition of what work, determining the infamous limiting factor of a good baseline is an hide and seek,
where we are forced to play guesses backed with partial data clues in a hugely complex [POMDP](https://en.wikipedia.org/wiki/Partially_observable_Markov_decision_process). More often than not we only are limited to observe correlation with impossible to confirms causalities, building degrees of trust more than certainty.

This leave us with the question of what I would like to experiment with, next. Reinforcement-learning is certainly a key area
on my radar since I read the [Sutton & Barto](http://incompleteideas.net/book/the-book-2nd.html) book. I also very much like my recent work focusing
on compression techniques like quantization and efficiency. On the long term, every piece of technology that allow
a trained system to be more autonomous and adaptive, feels interesting and intriguing.

## Conclusion

Opportunities will come. As time pass we will see how this article age. The experienced ML practitioner I am, can already tell you: it's certainty not a good predictor of the future ;) .
Still, turning a page, maybe I will be able to refer to it as a good compass of my past self.
In the meantime let's be assured next articles will be far more technical: doh !
