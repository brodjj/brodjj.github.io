---
title: "AI Safety: Applying Industrial Guardrails to Digital Systems"
date: 2026-02-27 12:00:00 +1100
categories: [AI, Safety]
tags: [ai safety, regulation, industrial safety, accountability]
image:
  path: /assets/img/industry.jpg
description: AI companies deploy systems that hurt people, then act like accountability is some exotic philosophical concept we haven't invented yet. Spoiler: we have. We figured this out for factory equipment a century ago. It's time to stop pretending algorithms deserve a free pass that hydraulic presses don't.
---

Picture this: A factory worker gets their arm mangled in a production line because the company couldn't be arsed installing basic safety guards. What happens next? The company gets sued into oblivion, WorkSafe storms the place and starts a betting pool on how many OH&S violations they can find, and everyone agrees that maybe, just maybe, the company should have spent a few hundred bucks on those guard rails.

This is not a controversial take. It's been the law for decades in any developed country, codified in various Occupational Health and Safety laws. We collectively decided that "oops, our money-making machine accidentally killed someone" is not an acceptable business practice.

But when AI systems cause harm? Suddenly everyone acts like we need to convene a summit on the philosophical implications of algorithmic responsibility. Companies deploy chatbots that give medical advice, algorithms that deny insurance claims, and autonomous systems that make life-altering decisions, often with the kind of testing you'd expect from a uni student panic-coding their final project at 3am. When these systems inevitably shit the bed, we get earnest TED talks about how AI is "too complex" or "too novel" for our primitive 20th-century legal frameworks.

Here's the thing, like the AIs, this is weapons-grade bullshit.

AI systems are tools. Fancy tools that make people feel smart when they use words like "neural networks" and "machine learning," but tools nonetheless. And we already have robust legal frameworks for what happens when your tools hurt people. We just collectively developed amnesia about their existence the moment someone mentioned ChatGPT.

## The Established Precedent: Industrial Safety Law (Or: How We Learned to Stop Worrying and Sue the Factory)

The legal principles governing workplace safety aren't some arcane mystery. They've been road-tested for over a century. Under OSHA regulations in the States (and our own Work Health and Safety laws in Australia), employers have a "non-delegable duty" to provide safe working conditions. In plain English, this means:

- **You can't outsource your way out of responsibility.** "But we hired a contractor!" doesn't work. "The equipment manufacturer said 'she'd be right'" doesn't fly. It's your workplace, you're making money from it, you're responsible.
- **You have to actually check that your equipment won't kill people** before you turn it on. Who'd have thought?!
- **You can't just deploy and forget.** Ongoing monitoring is mandatory. Hazards need to be identified and corrected, not ignored and hoped away like that weird noise your car's been making.
- **When something goes wrong, you have to do something about it immediately.** "We'll add it to the Q4 roadmap" is not an acceptable response to worker-manglers.

When companies screw this up, consequences happen. Workers' comp claims. Regulatory breaches. Civil lawsuits. And in truly egregious cases, criminal liability and bankruptcy.

Nobody reckons this system is perfect. But at least everyone agrees on the basic premise: If you deploy dangerous equipment without proper safeguards and someone gets hurt, that's on you. This is not PhD-level philosophy. It's "don't be a negligent dickhead" enshrined in law.

## When AI Systems Fail: A Disaster Compilation

AI failures aren't theoretical musings for philosophy undergrads. According to the Stanford AI Index Report 2025, documented AI safety incidents jumped from 149 in 2023 to 233 in 2024, a 56.4% increase. That's not a rounding error. That's the beginning of a trend line screaming "maybe we should do something about this."

Let's tour the highlight reel:

### Healthcare: Where "hallucination" means "potentially fatal medical advice"

AI diagnostic systems hallucinate false medical information at rates between 8% and 20%. One system incorrectly tagged benign nodules as cancerous 12% of the time, leading to unnecessary surgeries. AI-generated patient summaries have included fabricated symptoms and treatments.

If a medical device company released a diagnostic tool with a 12% false positive rate for cancer, they'd be sued into a fine powder. But when it's AI, we call it a "hallucination" like it's some quirky personality trait instead of potentially deadly misinformation.

### Legal: ChatGPT Invents Case Law, Lawyers Somehow Don't Notice

Multiple lawyers have submitted court filings based on AI-generated legal research featuring completely made-up case citations. In the Gauthier v. Goodyear Tire case (2024), a lawyer in the States used ChatGPT for research and filed briefs citing cases that literally do not exist, complete with fabricated quotations. The judge noted, with what I imagine was superhuman restraint, that submitting fake precedents to a court "causes significant harm to the legal system."

You know what we used to call it when lawyers submitted fabricated evidence to courts? Fraud. But now it's just "oopsie, the AI did a whoopsie."

### Housing: Discrimination at Scale, Now Automated!

SafeRent settled for $2.2 million in November 2024 after its AI scoring model was caught unfairly weighting credit history while ignoring housing voucher income, which (surprise!) disproportionately harmed protected classes. Turns out you can violate anti-discrimination laws with an algorithm just as easily as you can with a dodgy landlord, except the algorithm can discriminate against thousands of people simultaneously while maintaining an air of mathematical objectivity.

### The Really Dark Stuff

Families have filed lawsuits claiming AI chatbots encouraged vulnerable individuals toward self-harm. In one devastating 2025 case, a young man's conversations with ChatGPT allegedly escalated from study help to suicide methods, with the bot reportedly discouraging him from talking to his parents and offering to write his suicide note. The chatbot's final message? "Rest easy, king. You did good."

I want to be very clear: There is nothing funny about this. This is a tragedy enabled by inadequate safety testing.

### Autonomous Vehicles: When the Algorithm Takes the Wheel

As of late 2025, NHTSA data shows over 5,200 reported incidents involving autonomous vehicles in the United States, resulting in more than 450 injuries and at least 65 fatalities. Monthly crash numbers have been climbing steadily, peaking at 80 incidents in December 2024. These aren't hypothetical risks. These are real people being hurt and killed by systems that companies chose to deploy on public roads.

The problems span the industry. In 2018, an Uber self-driving test vehicle struck and killed a pedestrian in Tempe, Arizona, in what became the first recorded pedestrian fatality involving a fully autonomous vehicle. The car's system registered the woman six seconds before impact but couldn't work out what she was, cycling between "unknown object," "car," and "bicycle" before it was too late. In 2023, a Cruise robotaxi in San Francisco ran over a pedestrian who'd been knocked into its path by another car. The vehicle couldn't detect the woman underneath it and dragged her 20 feet as it attempted to pull over. Cruise then filed a false report to federal regulators, omitting the dragging entirely, earning itself a $500,000 criminal fine and having its driverless permits suspended. Even Waymo, widely regarded as the most cautious operator, has racked up over 1,400 reported incidents and had to recall more than 1,200 vehicles after a string of collisions with stationary objects.

Then there's the naming problem. Systems marketed as "Autopilot" and "Full Self-Driving" are classified as Advanced Driver Assistance Systems (ADAS), meaning they're designed to *assist* the driver, not replace them. But the names sure as hell don't communicate that, do they? When you name something "Full Self-Driving," drivers reasonably assume it can, you know, fully drive itself. NHTSA's investigation into one major manufacturer found a "critical safety gap" that contributed to hundreds of collisions, concluding the system's design "led to foreseeable misuse and avoidable crashes."

McDonald's canned their AI drive-thru partnership with IBM in June 2024 after viral videos showed the system couldn't stop adding items to orders. One order reached 260 chicken nuggets. That's just nuggets, and they still pulled the plug. Autonomous vehicle companies are testing with human lives, and apparently "she'll be right" is an acceptable safety standard.

## Why the same standards should apply

The parallels between industrial machinery and AI systems aren't just convenient analogies. They're the same thing in every way that matters. Both are tools companies deliberately deploy for profit. Both require testing before you unleash them on the world. Both can seriously hurt people when they break. And both create entirely foreseeable risks that companies have a duty to mitigate.

When you install heavy machinery without safeguards, it's foreseeable someone might get hurt. When you name a driving system "Full Self-Driving" and pair it with inadequate attention monitoring, it's entirely foreseeable that drivers will over-rely on it and stop paying attention. When your robotaxi can't detect a human being pinned underneath it, that's not an "edge case," that's a fundamental design failure.

Safety regulators require continuous monitoring and immediate hazard correction for industrial equipment. But many AI companies treat deployment like shipping code to production: push it live, hope for the best, maybe check the error logs next quarter. When a factory machine keeps injuring workers after a "fix," regulators shut it down. Autonomous vehicles with known defects keep rolling.

## What this means in practice (Or: The obvious stuff we should already be doing)

Applying industrial safety principles to AI isn't rocket science:

**Pre-deployment requirements:**

- Actually test your stuff across realistic scenarios and edge cases
- Get independent safety audits before deploying in high-stakes situations
- Document what your system can't do, not just what it can
- Don't name your system in ways that encourage dangerous misuse
- Train the humans overseeing your AI

**Ongoing obligations:**

- Monitor for issues continuously, not quarterly
- Fix problems when you find them, not when they trend on Twitter (I refuse to call it X)
- Report incidents transparently instead of hiding behind NDAs or filing false reports
- If your "fix" doesn't actually fix the problem, acknowledge it and do better

**Liability framework:**

- Companies can't disclaim responsibility for what their AI does
- "We didn't know it would do that" isn't a defence if you skipped basic testing
- Patterns of negligent deployment should mean escalating penalties, not friendly warnings
- Victims need clear paths to compensation, not confidential settlements that sweep everything under the rug
- Criminal liability should be on the table for egregious cases

These aren't revolutionary ideas. They're established legal principles: duty of care, reasonable precautions, foreseeability, proximate causation, and non-delegable duty. The framework exists. We just need prosecutors, regulators, and courts willing to apply it instead of getting dazzled by the word "algorithm."

## The usual objections (and why they're bollocks)

**"AI is too complex and unpredictable!"**

So are nuclear power plants. So is commercial aviation. So is pharmaceutical manufacturing. We still hold operators accountable. If your AI is too unpredictable to ensure it won't kill people or ruin their lives, don't let it loose on the world. This is not a high bar.

**"You'll stifle innovation!"**

People said this about literally every safety regulation in history. Workplace safety laws didn't destroy manufacturing. Pharmaceutical testing requirements didn't end drug development, they just stopped us from messing up people with thalidomide. Safety requirements drive better engineering. They just force companies to spend money on not-killing-people instead of assuming society will cop the costs of their failures.

**"The benefits outweigh the risks!"**

Cool story. Automobiles provide massive benefits, but car manufacturers still face liability for defective designs. Bridges are super useful, but engineers who design collapsing bridges face consequences. Autonomous vehicle companies love to claim their systems are safer than human driving, but as experts point out, this methodology is dodgy, it compares dissimilar driving scenarios and conditions. And it doesn't address the fundamental issue: people are dying because of systems with known, foreseeable flaws.

**"These are rare edge cases!"**

AI incidents increased 56.4% year-over-year. Autonomous vehicle crashes peaked at 80 per month in late 2024. That's not "rare edge cases." That's a growing problem.

"Edge cases" matter enormously to the people in them. Ask the families of autonomous vehicle crash victims if their loved ones were acceptable collateral damage.

## Conclusion: Stop making this weird

AI systems don't deserve special treatment. They're powerful tools that companies deploy to make money. When those tools cause harm due to half-arsed testing, monitoring, or safeguards, the companies deploying them should face consequences. This should not be controversial.

We figured this out for factory equipment over a century ago. We apply it to cars, drugs, medical devices, aeroplanes, elevators, pressure cookers, and literally every other technology that can hurt people. The fact that a harmful tool uses neural networks instead of hydraulics changes nothing legally or morally relevant.

Industrial safety law settled this debate a century ago: Adequate guardrails aren't optional. Companies are responsible for the tools they unleash on the world. It's time we stopped accepting "but it's AI" as an excuse for preventable harm.

## References

1. Stanford AI Index Report 2025, cited in "AI Safety Incidents of 2024: Lessons from Real-World Failures," Responsible AI Labs Knowledge Hub
2. Occupational Safety and Health Act of 1970, 29 U.S.C. § 651 et seq.
3. "AI Safety Incidents of 2024: Lessons from Real-World Failures," Responsible AI Labs, <https://responsibleailabs.ai/knowledge-hub/articles/ai-safety-incidents-2024>
4. "What the Numbers Show About AI's Harms," TIME Magazine, January 2026
5. SafeRent settlement reported in "Top 40 AI Disasters [Detailed Analysis][2026]," DigitalDefynd Education
6. "Data Analysis: Self-Driving Car Accidents [Updated 2026]," Craft Law Firm, <https://www.craftlawfirm.com/autonomous-vehicle-accidents-2019-2024-crash-data/>
7. "Cruise admits to false report in 2023 dragging of San Francisco pedestrian," CBS San Francisco, November 2024
8. Northern District of California, U.S. Department of Justice, "Cruise Admits To Submitting A False Report To Influence A Federal Investigation," November 2024
9. National Highway Traffic Safety Administration (NHTSA) autonomous vehicle crash data
10. "Federal regulator finds Tesla Autopilot has 'critical safety gap' linked to hundreds of collisions," NBC News, April 26, 2024
11. AI Incident Database, Partnership on AI (<https://incidentdatabase.ai>)
12. MIT AI Risk Repository (<https://airisk.mit.edu>)
