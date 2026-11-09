---
title: code is worthless. strategy is everything.
type: mini-conference talk
author: Oskar Holm
status: working draft
duration: 20 minutes
---

# Editorial intent
This is a revised talk draft. The central argument is:
> AI gives us speed. Strategy decides what that speed is worth.

The title is intentionally provocative. we do not claim that code has no value. It is a suggestion to redirect focus from producing code and solving tricky problems, and instead  upstream, toward choosing the right problems, and downstream, toward the outputs that create customer and business value.

The talk should leave the audience with three questions:

1. What outcome do we want AI to improve?
2. What will we do with the capacity AI creates?
3. What evidence will tell us that it worked?

# Delivery notes

- Slow down. pause after each major claim.
- State opinions directly. Use “my claim is” rather than “I think, perhaps”.
- Keep the audience involved: hands at the beginning, a short reflection in the middle, and a concrete question at the end.
- Treat disagreement as useful. The title is an invitation to think and discuss.
- aim for 3,000 spoken words, allowing time for pauses, hands, and audience reflection.

# Talk draft
## 1. Opening: confidence and evidence
Hello.

Let's talk about what is happening right now, in the field of software development.

By a quick show of hands, how many of you have an AI strategy that your board is satisfied with?

Keep your hands up if you are confident that this strategy is returning value on investment.

And keep your hands up if you have hard evidence that supports that confidence:
  metrics
  customer outcomes
  financial results

We have often seen a gap form between confidence and evidence. That gap is where many enterprise AI programmes get stuck.

The ambition is real. The investment is real. The urgency is real. But these do not add up to a strategy.

## 2. The thesis
So my claim is this:
> Code is abundant, strategy must catch up.

“Code is worthless. Strategy is everything.”

It is deliberately provocative and overstated. Code is obviously not worthless. Software still has to run. It still has to be secure, reliable, understandable and useful.

But the economics are changing. If producing a first version of a feature, a test, a script or a migration becomes dramatically easier, then the code itself becomes less scarce. And what is less scarce usually becomes less differentiating.

the scarce things become:
- knowing which problem is worth solving;
- knowing which problem is not worth solving;
- making trade-offs across customers, teams and time;
- creating the conditions in which generated code can be trusted;
- and turning technical capacity into an outcome that matters.

---
your AI strategy doesn’t exist in isolation. it must live between your vision and your execution

- a your vision drives its ai strategy and explains why the strategy is chosen.
- a your strategy implements the vision and explains how the vision is achieved.
- your ai strategy drives plans and processes and explains what plans and process are needed
- plans and processes implement the strategy and explain how the strategy is executed. 

together, these focus the ai adoption efforts, and they guide you where to start, how to track progress, measure successes.

that is strategy. i mean strategy in the practical sense: the layer between vision and plan.
vision tells us why we exist. A plan tells us what we will do next. strategy makes the choices that connect the two.
strategy is a thousand “no”s for every “yes”. it says: this is where we will focus, this is what we will stop doing, and this is how we will know whether the choice is achieving what we intended.

## 3. Speed is real—but speed is not the outcome
AI coding tools can create real speed and efficiency gains.

In a controlled GitHub Copilot experiment, developers completed a narrow JavaScript task 55.8% faster with access to Copilot. That is a meaningful result.

But the evidence is not a single number called “AI productivity”. In a 2025 randomized trial, METR gave experienced open-source developers real tasks in mature repositories. In that particular setting, developers took 19% longer when AI tools were allowed.

Those results are not  contradictory. A small, well-defined task is not the same as changing a mature system whose history and constraints you already understand. AI can reduce typing and searching while adding prompting, waiting, reviewing and correction.

And the tools keep changing. METR has since said its later data was difficult to interpret because the developers and tasks most likely to benefit from AI were increasingly selecting themselves out of the experiment.

So the conclusion is not “AI is fast” or “AI is slow”. It is: the effect depends on the task, the system, the people and the way the work is organized.

The capability is real. The business outcome is conditional.

DORA’s 2025 research makes a similar point at organizational scale. Almost 90% of respondents reported using AI at work, and more than 80% believed it had increased their productivity. At the same time, AI adoption was associated with higher delivery throughput and product performance—and with lower delivery stability.

That is a very useful finding. It says we can move faster and become less stable at the same time.

More code is moving through the system. That does not automatically mean more value is reaching customers.

This is why I want to separate three things we often collapse into one word:

1. **Activity:** how much usage your AI tooling gets.
2. **Output:** how much code, documentation, or change it produces.
3. **Outcome:** what improved for customers, for the business bottom line, or for the people doing the work.

Activity is easy to count. Output is trickier. Outcome is hard, not just to measure but also to attribute. 
Outcome is what the strategy is supposed to create.

## 4. Speed is a currency
my next point is this:

> Speed is a currency.

If AI gives a team time back, that time has value. We can spend it on doing the same work faster. That may be exactly the right choice. Faster feedback, shorter lead time and lower cost are valuable. But that is spinning the same wheel faster. 

We can also invest it in a larger opportunity set.

There are things in every software organization that are important but never urgent:

- modernizing a painful legacy area;
- paying down technical debt before it becomes a legacy liability;
- improving documentation while the knowledge is still available;
- testing the scenarios we currently leave to chance;
- making the product accessible to more people;
- exploring a new market or a new customer segment;
- or finally fixing the internal platform that slows everyone down.

These things are often not ignored because people are careless. They are deferred because the immediate work always wins. The cost is visible today; the benefit arrives later.

AI can change that calculation.

It can make previously uneconomic work possible. It can reduce the effort needed to understand an unfamiliar codebase. It can help create test cases, update documentation, explore an API, or build a prototype quickly enough to learn whether an idea deserves further investment.

But there is a crucial condition: someone has to choose to spend the capacity there.

If we use every efficiency gain to absorb more tickets, our organization may become more efficient at remaining exactly where it is.

We are spinning the same wheel faster.

The strategic opportunity is to expand the wheel.

## 5. From efficiency story to growth story

The focus on speed and efficiency naturally turns AI adoption into a cost-saving exercise.

Cost savings are attractive. They are relatively easy to explain. We know the baseline, we know the spend, and if the number goes down, the CFO is likely to be pleased.

But what is better than saving money?

Sometimes, making money.

By expanding what we can deliver, improving quality, serving more customers and testing more possibilities, AI adoption can become a growth story.

This is not an either/or choice. Every organization needs efficiency. We all have business-as-usual work, operational commitments and pressure to do more with what we have.

My point is to avoid treating efficiency as the finish line.

Efficiency is what AI can buy us. Strategy decides what we buy with it.

So ask yourself:

If AI gave my team one day back every week, where would I invest that day?

Would I use it to close the next ticket? To shorten the next sprint? Or to remove a bottleneck that has been limiting the business for three years?

That is not a tooling question. It is a strategic question.

## 6. The workforce question

There is one part of the cost conversation I want to challenge directly: the idea that AI adoption is mainly about swapping carbon-based programmers for silicon-based agents.

Consider two companies in the same sector. They have similar revenue, similar staff costs and similarly thin margins.

Company A adopts AI successfully and reduces its engineering team by half. Productivity stays roughly the same, costs fall and margins improve.

That can be a rational business decision. It is a success story if the strategy is to become leaner.

Company B keeps its people and equips them with AI agents. It uses the additional capacity to enter a new market, improve the product for underserved customers, retire dangerous legacy systems, increase reliability and run more experiments.

That can also be a rational business decision. It is a success story if the strategy is to expand.

Which company does your vision document describe?

I am not arguing that every organization should keep every role forever. I am arguing that “fewer people” is not the same as “more value”. It is one possible allocation of the capacity AI creates.

The other allocation is greater reach.

And there is a human dimension here. If AI removes repetitive toil, that can be a quality-of-life upgrade for developers. But only if the freed capacity is redirected toward meaningful work—not simply replaced by a higher volume of low-value output and a new demand to be constantly available.

The strategic choice is not only how many people we need to produce the same software. It is also what software becomes possible when those people have more leverage.

## 7. What strategic adoption looks like

So what does this mean in practice?

I would suggest four moves.

### First: choose the outcome before choosing the tool

Do not begin with “Where can we deploy an agent?” Begin with “What do we need to improve?”

Maybe the outcome is faster incident recovery. Maybe it is fewer escaped defects. Maybe it is reaching a new customer segment. Maybe it is reducing the cost of maintaining a product that has become too expensive to change.

The tool comes after the problem.

### Second: make the capacity decision explicit

When a team gets faster, decide in advance where the capacity goes.

If the entire benefit is left unallocated, the system will usually consume it. The backlog expands. Scope grows. Meetings multiply. The organization experiences activity, but not necessarily progress.

Say explicitly: a part of this capacity will go to reliability; a part will go to platform improvements; a part will go to customer discovery; a part will go to experiments.

That is strategy made visible.

### Third: strengthen the system around the code

AI can increase the volume of change. That makes small batches, automated tests, fast feedback, version control and good internal platforms even more important.

The question is not only, “Can the agent write this?”

It is also, “Can our organization safely review, test, deploy, observe and learn from what it writes?”

If the answer is no, we have not unlocked speed. We have moved the bottleneck downstream.

### Fourth: measure impact, not enthusiasm

Usage metrics can be useful for understanding adoption, but they are not proof of value.

Lines of code, number of commits, pull requests and agent sessions tell us that activity happened. They do not tell us whether customers are better served.

Choose measures that match the intended outcome:

- For reliability: change failure rate, recovery time and customer-visible incidents.
- For quality: escaped defects, support burden and user-reported problems.
- For flow: lead time, queue time and the size of changes moving through the system.
- For growth: adoption, retention, conversion or revenue in the target segment.
- For learning: time from idea to evidence, not just number of prototypes.
- For developers: time spent on meaningful work, cognitive load and sustainable satisfaction.

The exact metrics will vary. The principle does not:

> Measure whether the business changed—not merely whether the code changed.

## 8. Reflection and close

Let’s take a moment.

Think of one important task in your software delivery system that has been waiting for a long time. Not the loudest task. The one that is valuable, but never urgent enough.

Now ask yourself three questions:

What would become possible if AI reduced the effort required by half?

What would we choose to do with the capacity that creates?

And what evidence would tell us that the investment paid off?

Those three questions are the beginning of an AI strategy.

Not a list of tools. Not an adoption leaderboard. Not a target for lines of code.

An AI strategy is a set of choices about where to focus, what to stop, how to create value and how to learn whether we are succeeding.

The technology is moving quickly. The organizations that benefit will not necessarily be the ones that generate code fastest.

They will be the ones that know what their speed is for.

Code still matters. It is how our intentions become working software.

But when code becomes abundant, strategy becomes scarce.

And scarce things decide who gets ahead.

Thank you.

# Evidence and source notes

These are speaker notes, not necessarily slide text. Present the studies with their scope and limitations; do not use them as universal productivity claims.

- GitHub Copilot controlled experiment: [Microsoft Research — The Impact of AI on Developer Productivity](https://www.microsoft.com/en-us/research/publication/the-impact-of-ai-on-developer-productivity-evidence-from-github-copilot/). The 55.8% result came from a narrow, standardized JavaScript HTTP-server task.
- METR randomized trial: [Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity](https://metr.org/Early_2025_AI_Experienced_OS_Devs_Study-paper.pdf). The study covered 16 developers and 246 tasks in mature repositories and found a 19% increase in completion time in that setting.
- METR follow-up: [We are Changing our Developer Productivity Experiment Design](https://metr.org/blog/2026-02-24-uplift-update/). This is important context for a 2026 talk: METR says later data was affected by selection effects and is weak evidence for the size of current AI uplift.
- DORA 2025: [State of AI-assisted Software Development](https://dora.dev/research/2025/dora-report/) and [Google Cloud’s report summary](https://cloud.google.com/blog/products/ai-machine-learning/announcing-the-2025-dora-report). The report emphasizes that AI amplifies existing organizational strengths and weaknesses; its findings include near-universal adoption, perceived individual productivity gains, higher throughput/product performance, and a continuing stability trade-off.

# Optional slide spine

---

Gap: Confidence is ahead of evidence.
Thesis: Code is abundant, strategy is scarce.
Nuance: AI speed depends on the task and the system.
Trade: Speed is a currency, not the outcome.
Choice: spin the wheel faster or expand it?
workforce: fewer people, or more reach?
Practice: outcome, capacity, system, evidence.
Close: what strategy serves your vision?
