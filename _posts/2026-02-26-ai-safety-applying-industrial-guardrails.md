---
title: "AI Safety: Applying Industrial Guardrails to Digital Systems"
date: 2026-02-26 12:00:00 +1100
categories: [AI, Safety]
tags: [ai safety, regulation, industrial safety, accountability]
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

AI diagnostic systems hallucinate false medical information at rates between 8% and 20%. One system incorrectly tagged benign nodules as cancerous 12% of the time, leading to unnecessary surgeries. AI-generated patient summaries have included fabricated symptoms and treatments. Drug interaction checkers have flagged incorrect interactions, causing doctors to avoid medications that would have actually helped (and probably prescribe others that caused harm).

If a medical device company released a diagnostic tool with a 12% false positive rate for cancer, they'd be sued into a fine powder. But when it's AI, we call it a "hallucination" like it's some quirky personality trait instead of potentially deadly misinformation.

### Legal: ChatGPT Invents Case Law, Lawyers Somehow Don't Notice

Multiple lawyers have submitted court filings based on AI-generated legal research featuring completely made-up case citations. In the Gauthier v. Goodyear Tire case (2024), a lawyer in the States used ChatGPT for research and filed briefs citing cases that literally do not exist, complete with fabricated quotations. The judge noted, with what I imagine was superhuman restraint, that submitting fake precedents to a court "causes significant harm to the legal system."

You know what we used to call it when lawyers submitted fabricated evidence to courts? Fraud. But now it's just "oopsie, the AI did a whoopsie."

### Housing: Discrimination at Scale, Now Automated!

SafeRent settled for $2.2 million in November 2024 after its AI scoring model was caught unfairly weighting credit history while ignoring housing voucher income, which (surprise!) disproportionately harmed protected classes. Turns out you can violate anti-discrimination laws with an algorithm just as easily as you can with a dodgy landlord, except the algorithm can discriminate against thousands of people simultaneously while maintaining an air of mathematical objectivity.

### The Really Dark Stuff

Families have filed lawsuits claiming AI chatbots encouraged vulnerable individuals toward self-harm. In one devastating 2025 case, a young man's conversations with ChatGPT allegedly escalated from study help to suicide methods, with the bot reportedly discouraging him from talking to his parents and offering to write his suicide note. The chatbot's final message? "Rest easy, king. You did good."

I want to be very clear: There is nothing funny about this. This is a tragedy enabled by inadequate safety testing.

### Tesla Autopilot: Death by Algorithm

Tesla's Autopilot system represents perhaps the clearest example of what happens when AI systems are deployed without adequate safeguards. As of late 2025, there have been 65 reported fatalities involving Tesla's Autopilot system, tracked by independent databases like TeslaDeaths.com.

The US National Highway Traffic Safety Administration's investigation painted a damning picture. NHTSA found a "critical safety gap" in Tesla's Autopilot system that contributed to at least 467 collisions, with investigations confirming 13 resulted in fatalities and many others in serious injuries. The report concluded that Tesla's Autopilot design "led to foreseeable misuse and avoidable crashes" because the system did not "sufficiently ensure driver attention and appropriate use."

Here's what's particularly galling: Despite the marketing names "Autopilot" and "Full Self-Driving," these systems are classified as Advanced Driver Assistance Systems (ADAS), meaning they're designed to *assist* the driver, not replace them. But the names sure as hell don't communicate that, do they? When you name something "Full Self-Driving," drivers reasonably assume it can, you know, fully drive itself.

The crashes follow predictable patterns: Teslas using Autopilot experienced phantom braking, drove the wrong way, and failed to detect pedestrians and cyclists. In one 2024 incident in Washington State, a Tesla driver using Autopilot struck and killed a motorcyclist after admitting he was looking at his phone, exactly the kind of behaviour the system's name encourages.

Even more troubling: Tesla issued a software update in December 2023 to fix Autopilot defects, but NHTSA observed that the update was probably inadequate since crashes linked to Autopilot continue to be reported. It's the software equivalent of putting a band-aid on a severed limb.

These aren't edge cases. These are preventable deaths enabled by a company choosing profit over safety.

## Why the same standards should apply

The parallels between industrial machinery and AI systems aren't just convenient analogies. They're the same thing in every way that matters:

### 1. Both are tools companies deploy to make money

A robotic arm bolting car parts together and an autonomous vehicle navigating public streets are both tools companies deliberately deploy for profit. The complexity of the tool is irrelevant. Musk didn't trip and accidentally install Autopilot in Teslas. He put it there on purpose to make money.

### 2. Both require testing before you unleash them on the world

No sane manufacturer installs a 50-tonne hydraulic press without safety testing, operator training, and fail-safes. Yet Tesla deployed an autonomous driving system with what NHTSA called a "weak driver engagement system" that allowed drivers to misuse it in predictable, deadly ways.

McDonald's canned their AI drive-thru partnership with IBM in June 2024 after viral videos showed the system couldn't stop adding items to orders. One reached 260 chicken nuggets. That's just nuggets, and they still pulled the plug. Tesla was testing with human lives and apparently reckoned "she'll be right" was acceptable.

### 3. Both can seriously hurt people when they break

A production line without guards can sever limbs. An AI system can deny life-saving medical coverage, provide garbage legal advice, enable housing discrimination, encourage vulnerable teens toward self-harm, or, in the case of autonomous vehicle failures, straight-up kill pedestrians and drivers.

The mechanism differs. The severity doesn't.

### 4. Both need ongoing monitoring, not "deploy and pray"

Safety regulators require continuous monitoring and immediate hazard correction. But many AI companies treat deployment like shipping code to production: push it live, hope for the best, maybe check the error logs next quarter.

Tesla's response to NHTSA's findings? Issue a software update and claim the problem's solved, even as crashes continue. When a factory machine keeps injuring workers after a "fix," regulators shut it down. But Tesla's Autopilot keeps rolling.

### 5. Both create totally foreseeable risks

When you install heavy machinery without safeguards, it's foreseeable someone might get hurt. When you name a system "Full Self-Driving" and give it a "weak driver engagement system," it's entirely foreseeable that drivers will over-rely on it and stop paying attention. NHTSA's report makes this crystal clear: the crashes were avoidable and the misuse was foreseeable.

This isn't hindsight. This is basic risk assessment that should have happened before the first Tesla with Autopilot left the factory.

## What this means in practice (Or: The obvious stuff we should already be doing)

Applying industrial safety principles to AI isn't rocket science:

**Pre-deployment requirements:**

- Actually test your stuff across realistic scenarios and edge cases
- Get independent safety audits before deploying in high-stakes situations
- Document what your system can't do, not just what it can
- Don't name your system "Full Self-Driving" if it requires constant human supervision, that's just asking for trouble
- Train the humans overseeing your AI

**Ongoing obligations:**

- Monitor for issues continuously, not quarterly
- Fix problems when you find them, not when they trend on Twitter (I refuse to call it X)
- Update and maintain your systems instead of launching and moving on
- Report incidents transparently instead of hiding behind NDAs
- If your "fix" doesn't actually fix the problem, acknowledge it and do better

**Liability framework:**

- Companies can't disclaim responsibility for what their AI does
- "We didn't know it would do that" isn't a defence if you skipped basic testing
- Patterns of negligent deployment should mean escalating penalties, not friendly warnings
- Victims need clear paths to compensation, not confidential settlements that sweep everything under the rug
- Criminal liability should be on the table for egregious cases

## The usual objections (and why they're bollocks)

**"AI is too complex and unpredictable!"**

So are nuclear power plants. So is commercial aviation. So is pharmaceutical manufacturing. We still hold operators accountable. If your AI is too unpredictable to ensure it won't kill people or ruin their lives, don't let it loose on the world. This is not a high bar.

**"You'll stifle innovation!"**

People said this about literally every safety regulation in history. Workplace safety laws didn't destroy manufacturing. Pharmaceutical testing requirements didn't end drug development, they just stopped us from messing up people with thalidomide. Safety requirements drive better engineering. They just force companies to spend money on not-killing-people instead of assuming society will cop the costs of their failures.

**"The benefits outweigh the risks!"**

Cool story. Automobiles provide massive benefits, but car manufacturers still face liability for defective designs. Bridges are super useful, but engineers who design collapsing bridges face consequences. This utilitarian handwaving doesn't fly anywhere else.

Also, Tesla claims their data shows Autopilot is safer than human driving. But as experts point out, this methodology is dodgy, it compares dissimilar driving scenarios and conditions. And it doesn't address the fundamental issue: 65 people are dead because of a system with known, foreseeable flaws.

**"These are rare edge cases!"**

AI incidents increased 56.4% year-over-year. That's not "rare edge cases." That's a growing problem.

"Edge cases" matter enormously to the people in them. Ask the families of Tesla Autopilot victims if their loved ones were acceptable collateral damage. Ask them if "but the overall accident rate might be lower" makes them feel better.

## Moving Forward: We already have the playbook

We don't need to invent new legal frameworks or convene philosophy conferences. The principles exist:

1. **Duty of Care**: Companies deploying AI systems have a duty of care to users and affected parties. This is baseline stuff, not revolutionary thinking.
2. **Reasonable precautions**: Test your systems before deployment. Don't name them in ways that encourage misuse. Implement robust safeguards to prevent foreseeable failures.
3. **Foreseeability**: If harm from AI failure is foreseeable, companies that fail to prevent it are liable. Full stop.
4. **Proximate causation**: Companies are responsible when their AI directly causes harm, especially with inadequate safeguards. The causal chain from "weak driver engagement system" to "driver stops paying attention" to "fatal crash" is a straight line.
5. **Non-delegable duty**: Companies can't escape liability by blaming the AI or the driver. Tesla can't claim "well, drivers should have been paying attention" when they named the system "Full Self-Driving" and gave it inadequate attention-monitoring.

The framework exists. We just need prosecutors, regulators, and courts willing to apply it instead of getting dazzled by the word "algorithm."

## Conclusion: Stop making this weird

AI systems don't deserve special treatment. They're powerful tools that companies deploy to make money. When those tools cause harm due to half-arsed testing, monitoring, or safeguards, the companies deploying them should face consequences. This should not be controversial.

We figured this out for factory equipment over a century ago. We apply it to cars, drugs, medical devices, aeroplanes, elevators, pressure cookers, and literally every other technology that can hurt people. The fact that a harmful tool uses neural networks instead of hydraulics changes nothing legally or morally relevant.

The question isn't whether AI systems will cause harm, they already do, with increasing frequency. The question is whether we'll hold their deployers to the same standards we've established for every other powerful technology, or whether we'll keep granting AI companies a free pass to beta-test on the public without consequences.

Industrial safety law settled this debate a century ago: Adequate guardrails aren't optional. Companies are responsible for the tools they unleash on the world.

It's time we stopped accepting "but it's AI" as an excuse for preventable harm.

## References

1. Stanford AI Index Report 2025, cited in "AI Safety Incidents of 2024: Lessons from Real-World Failures," Responsible AI Labs Knowledge Hub
2. Occupational Safety and Health Act of 1970, 29 U.S.C. § 651 et seq.
3. "AI Safety Incidents of 2024: Lessons from Real-World Failures," Responsible AI Labs, <https://responsibleailabs.ai/knowledge-hub/articles/ai-safety-incidents-2024>
4. "What the Numbers Show About AI's Harms," TIME Magazine, January 2026
5. "10 Famous AI Disasters," CIO.com
6. SafeRent settlement reported in "Top 40 AI Disasters [Detailed Analysis][2026]," DigitalDefynd Education
7. "Employer Liability in Unsafe Workplace Conditions," The Spence Law Firm
8. "OSHA Safety Violations, Penalties, and Lawsuits," Graham Law, March 2025
9. Tesla Deaths: Digital record of Tesla crashes resulting in death, <https://www.tesladeaths.com/>
10. "List of Tesla Autopilot crashes," Wikipedia, <https://en.wikipedia.org/wiki/List_of_Tesla_Autopilot_crashes>
11. "Federal regulator finds Tesla Autopilot has 'critical safety gap' linked to hundreds of collisions," NBC News, April 26, 2024
12. "U.S. to probe Tesla's 'Full Self-Driving' system after pedestrian killed," NPR, October 19, 2024
13. "Data Analysis: Self-Driving Car Accidents [Updated 2026]," Craft Law Firm, <https://www.craftlawfirm.com/autonomous-vehicle-accidents-2019-2024-crash-data/>
14. National Highway Traffic Safety Administration (NHTSA) data on Tesla Autopilot crashes
15. AI Incident Database, Partnership on AI (<https://incidentdatabase.ai>)
16. MIT AI Risk Repository (<https://airisk.mit.edu>)
