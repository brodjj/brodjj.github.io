---
title: "LLM Spatial Experiments: Why Launchpad McQuack is still inside a 1992 Fisher-Price toy cash register"
date: 2026-02-27 18:00:00 +1100
categories: [AI, LLM Experiments]
tags: [llm, gemini, spatial reasoning, 90s nostalgia, experiments]
math: true
description: "What do a DuckTales figurine, a 30-year-old toy cash register, and someone else's ruined childhood collectibles have to do with AI? More than you'd think. A real-world spatial reasoning problem reveals what LLMs can and can't actually do, and why the difference matters more than you'd expect."
image:
  path: /assets/img/ducktales.jpg
---

Yes, that's a real title, not an AI hallucination. This is based on a real-world problem that I presented to Gemini in an attempt to reveal the weak spatial reasoning capabilities of LLMs. Its response was surprising (and hilarious given the backstory).

## My childhood idiocy as an AI case study

When I was a kid in the early 90s, I recall a stupid and amusing incident that stuck with me.

I was having a playdate with a kid across town that I didn't really know. I think it was just an excuse for our mums to hang out on the back porch to day-drink chardonnay, eat cheese crackers, and smoke menthol cigarettes.

Anyway, this kid had an insane playroom with multiple toy chests, a slot car track (unfortunately out of commission), and various big play sets, including the much-coveted Castle Grayskull and a bunch of He-Man figures. Annoyingly, this kid was a bit of a douchebag and made it very clear that I wasn't to touch the Castle or any of the figures he'd stashed inside. I was relegated to a chest of second-rate toys (mostly McDonald's giveaways) and a bunch of toddler stuff he'd abandoned.

Bored, I started messing around with this toy cash register where you'd place giant plastic coins inside spring-loaded caddies. When you press the button below the caddy, it retracts down into the cash register and the coin is able to roll to one side and exit the register via a small ramp. Once the coin has left the caddy, you can press on the top of it and it will spring back into the upright position, ready for another coin. This was fun for about five seconds, so I started looking for other stuff to jam in there, preferably a figurine so I could send it down into the register like a man in a little elevator.

The first toys I found didn't fit. The Duplo men were too thick to get in the narrow caddy, and the off-brand GI Joe knockoffs were way too big. I eventually hit the jackpot: a 2-inch-tall Launchpad McQuack figurine from a McDonald's Happy Meal. Nervously, I put him in the first caddy, chuckled to myself, mimicked the voiceover from the McDonald's ad ("It's Launchpad!") then slammed my hand down on the button.

The oblivious Launchpad stood there motionless for a second, staring at me with his stupid dead-eyed grin, then abruptly sprang down into the cash register with a frightening clunk followed by a lingering metallic ring.

I paused for a moment then picked up the register and tried to tip Launchpad down the ramp. Nothing moved. I shook the register and tapped at the side and buttons. Again, no movement. I peered apprehensively into the ramp opening and saw the doomed Launchpad, trapped in the dark depths of the plastic cash register at an awkward angle, his dead-eyed stare boring accusingly into my soul.

![The face of doom](/assets/img/launchpad.jpg)
_The face of doom_

I started to panic. The other kid was still occupied with his He-Man toys, but it was only a matter of time before he figured out what I'd done and had a whole meltdown about it (he seemed like the type). I set the register down behind the toy chest and looked for something to pry Launchpad loose. I found a pencil, but no amount of poking around would make the figure budge.

As a last-ditch effort, I put coins into the two remaining slots, foolishly hoping they'd somehow push Launchpad towards the ramp. Of course, this only made things worse. The remaining caddies dropped down into the register, but with the path to the exit obstructed, the coins were now also jammed inside (and the caddies wouldn't spring back up).

My final act was to shove the cash register into the bottom of the nearest toy chest, then hastily bury it under the rubble of assorted plushies, like an amateur mobster trying to hide a body in a dumpster. I promptly declared that I wasn't feeling well and made my bewildered mum take me home. As we left the house, I could hear the final echo of my crimes as the kid called out to his mum from the playroom: "Have you seen my Launchpad?"

**Naturally, this seems like a perfectly reasonable spatial problem to present to an LLM.**

## The Experiment: Can Gemini free Launchpad?

**My prompt:** Let's try a spatial problem. I have a toy cash register where you can place large plastic coins inside spring-loaded caddies. When you press the button below the caddy, it retracts down into the cash register and the coin is able to roll to one side and exit the register via a small ramp. Once the coin has left the caddy, you can press on the top of it and it will spring back into the upright position, ready for another coin. I once made the mistake of putting a plastic figurine of Launchpad McQuack into the caddy and pressing the button to blast him down into the cash register. As he's not round like a coin, he couldn't roll sideways down the ramp and was jammed inside the register. Pushing on the top of the caddy wouldn't allow it to spring back up either, as he was leaning to one side and jamming the mechanism from sliding back up (similar to how a loose wooden spoon can jam a cutlery drawer from opening). How might I get Launchpad back out of the cash register?

*[Editor's note: For some reason, I was initially embarrassed to give Gemini the full story, that I didn't actually own the cash register and this was me messing around at another kid's house and being reckless with his toys. I gave it the sanitised version where this hypothetically happened to my own toy. The guilt runs deep, apparently.]*

> **Gemini:** This is a classic mechanical interference problem. Launchpad McQuack has effectively become a "toggle bolt" or a "cam lock", his irregular geometry (beak, goggles, or flight jacket) has wedged between the moving part (the caddy) and the static part (the register housing).
>
> To get him out, we have to address the Normal Force that is keeping him jammed. Here is the breakdown of the situation and the solution.
>
> **The Mechanical Map**
>
> **The Jam:** The spring is trying to push the caddy up, but Launchpad is tilted, creating a diagonal bridge between the caddy and the internal ceiling of the register.
>
> **The Friction Lock:** The more the spring pushes up, the tighter Launchpad wedges. This is exactly like your "wooden spoon in the drawer" analogy.
>
> **Solution 1: The "Reverse Gravity" (Easiest)**
>
> Since Launchpad is held in place by the spring pressure and his own tilted weight, we need to neutralise the spring.
>
> 1. Turn the cash register upside down.
> 2. Press the button that originally retracted the caddy and hold it down. This pulls the caddy away from Launchpad, removing the "squeeze."
> 3. Give the register a firm shake. With the caddy retracted and gravity on your side, Launchpad should drop away from the internal wall and hopefully slide out the coin ramp or fall back into the caddy's "pocket."
>
> **Solution 2: The "Thin Shim" (The Surgical Approach)**
>
> If shaking doesn't work, Launchpad is likely snagged on a specific internal lip.
>
> 1. Take a thin, flexible plastic card (like a library card) or a stiff piece of cardstock.
> 2. Slide it into the gap at the top of the caddy where the coin usually goes.
> 3. Use the card to try and "straighten" Launchpad. You are looking to move him from a diagonal position to a vertical one. If he is vertical, he no longer bridges the gap, and the jam clears.
>
> **Solution 3: The "Centrifugal Flick"**
>
> If he's stuck deep inside the ramp area:
>
> 1. Hold the register firmly.
> 2. Perform a wide, fast arc motion (like a hammer swing) ending abruptly toward the exit ramp.
> 3. The centrifugal force can sometimes "walk" an irregular object along a smooth plastic track, even if it can't roll.
>
> **My Internal "Scratchpad" Dialogue for this Problem:**
>
> - **Identify Mechanism:** Spring-loaded linear actuator (caddy) + gravity-fed exit (ramp).
> - **Identify Failure:** Non-cylindrical object (Launchpad) introduced into a system designed for disks (coins).
> - **Vector Analysis:** The spring exerts a force ($F_{spring}$) upward. Launchpad's height ($H$) is greater than the clearance ($C$) when tilted.
> - **Logic Check:** Pushing the caddy "up" is impossible because the "bridge" (Launchpad) is already under compression.
> - **Solution Goal:** Create "Slack." To create slack, I must move the caddy down (away from the jam) or change the register's orientation (Gravity reversal).
>
> **Next Step:** If you try to shake him out and he still won't budge, tell me: Is there any rattling sound when you shake it, or is he "dead-locked" and silent? This tells me if we're dealing with a friction jam or a physical hook.

*[This just about had me in tears with laughter. I vaguely recall 7-year-old me panicking, peering into the ramp opening and seeing Launchpad's beak hooked on the edge of the register housing. The fact that Gemini correctly identified "beak, goggles, or flight jacket" as the likely culprits is both impressive and deeply unsettling. It's like the AI witnessed my childhood crime.]*

**My prompt:** He was dead-locked from memory.

*[I'm dying at this point. I remember violently tapping and shaking the register, but Launchpad was dead-locked. Not a rattle to be heard. I futilely poked at him with a pencil, but he was well and truly jammed in place. Gemini asking for this specific diagnostic detail (rattle vs. silence) felt uncomfortably like being interrogated by someone who knows exactly what I did.]*

> **Gemini:** If he was dead-locked, it means Launchpad wasn't just "stuck", he had created a mechanical over-center toggle. This happens when an object is wedged so tightly that the force of the spring actually increases the "bite" of the jam.
>
> Since you can't push the caddy up, and pushing the button down probably felt stiff or impossible, you have to break the "lock" by attacking the object's orientation directly.
>
> **1. The "Percussion" Method (Breaking the Friction)**
>
> A dead-lock is held together by friction. You need to vibrate the housing to "un-seat" the beak or goggles.
>
> **The Action:** Hold the register upside down. Use the heel of your hand to give a sharp, firm thump to the side of the register furthest from the coin ramp.
>
> **The Goal:** You're trying to use inertia to make Launchpad "jump" slightly. Even a millimetre of movement can break the friction lock, allowing the spring to finally push him out or gravity to drop him into the ramp.
>
> **2. The "Point-Load" Lever**
>
> If you can see even a tiny bit of Launchpad through the top of the caddy:
>
> **The Tool:** A long, thin object like a knitting needle, a straightened paperclip, or even a thin skewer.
>
> **The Technique:** Instead of pushing the caddy, you need to push one specific side of Launchpad. If you push his left side down while the spring tries to push his right side up, you might rotate him enough to break the "bridge" he's formed.
>
> **3. The "Caddy Compression"**
>
> If the button is stuck, the caddy is being pinched by Launchpad against the internal walls.
>
> **The Action:** Squeeze the sides of the cash register (if the plastic is flexible) while holding the release button.
>
> **The Goal:** By slightly deforming the outer shell, you might increase the internal clearance ($C$) just enough that Launchpad is no longer taller than the space he is occupying.
>
> **My "LLM Scratchpad" Logic for "Dead-Locked"**
>
> - **State Change:** The scenario has shifted from "interference" to "mechanical binding."
> - **Vector Analysis:** The jam is likely a Three-Point Bend. Point A: The caddy floor. Point B: Launchpad's head against the internal ceiling. Point C: Launchpad's back against the side wall.
> - **Internal Dialogue:** If he is silent when shaken, the Normal Force ($N$) is extremely high. Shaking won't work because $Static\ Friction > Inertia$.
> - **New Strategy:** Must introduce a force that is perpendicular to the jam. If the jam is vertical, I must suggest horizontal force (side-thumping) or rotational force (poking a corner).
>
> **Hypothetical Outcome:**
>
> Usually, in these plastic toys, the "ceiling" of the register has a bit of give. If you had turned it upside down and poked a thin wire through the coin exit ramp to "tickle" Launchpad's feet, he likely would have tumbled out.
>
> Since this was a memory, do you remember if he ever made it out, or is Launchpad McQuack still entombed in plastic to this day?

**Me:** This happened at another kid's house in about 1992 (you can help me verify the year based on when McDonald's or Hungry Jacks gave away DuckTales toys). As far as I know, Launchpad's still in there.

*[Editor's note: Time to come clean. I decided to confess that not only did this happen to someone else's toy, but it happened over three decades ago and the evidence has never been recovered. I half-expected Gemini to tell me off. Instead, it got weirdly forensic.]*

> **Gemini:** Your memory is remarkably sharp. Based on my "internal library" of fast-food history and mechanical toy designs, we can actually narrow this down to a very specific moment in 1990s Australia.
>
> **The Year: 1992**
>
> Your estimate of 1992 is spot on. While McDonald's had a DuckTales run in 1988, the specific Launchpad McQuack PVC figurine you're likely remembering (the one with the brown flight jacket and aviator goggles) was widely distributed in Australia around 1991–1992.
>
> **The Victim: The Fisher-Price Cash Register (Model #926 / #2044)**
>
> The toy you described is a design icon: the Fisher-Price Cash Register.
>
> - **The Caddies:** Those spring-loaded "slots" were designed for specific, thick plastic coins (red, yellow, and blue).
> - **The Flaw:** When you pressed the lever, the floor of the caddy dropped, and the coin (being a perfect circle) would roll sideways into the ramp.
> - **The Jam:** Launchpad is essentially a rectangular prism with appendages. When he dropped into that internal chamber, he didn't roll. Instead, he likely tilted at a 45-degree angle.
>
> **The "Dead-Lock" Geometry**
>
> From a mapping perspective, here is why Launchpad is likely still in that register:
>
> **Vertical Compression:** The caddy floor is spring-loaded to push up. When Launchpad tilted, his height ($H$) became greater than the vertical clearance ($C$) of the internal chamber. He became a structural pillar.
>
> **The Beak Factor:** Launchpad has a prominent beak and a scarf. These act as "hooks." Once they snagged on the internal plastic lip of the coin ramp, no amount of shaking would move him because the spring was constantly pushing those hooks into the snag.
>
> **The "One-Way" Gate:** Those registers have an internal plastic flap to prevent coins from falling back into the mechanism. Launchpad likely pushed past that flap, which then snapped shut behind him, acting like a barb on a fishhook.
>
> **My Internal "Scratchpad" Verdict:**
>
> - **Probability of Survival:** High. Those registers were built like tanks (high-density polyethylene).
> - **Status:** Launchpad McQuack is currently in a state of permanent mechanical stasis.
> - **The Only Way Out:** To retrieve him today, you would have to unscrew the base of the register (usually 6–8 recessed Phillips head screws). Once the "clamshell" housing is opened, the tension on the caddy spring would release, and Launchpad would simply fall out, probably looking as good as the day he was entombed.
>
> It's poetic in a way, the world's greatest pilot ended his career stuck in a coin slot because he couldn't roll.
>
> Would you like me to look up what that specific 1992 Launchpad figurine is worth on the collector's market today, just to see the "bounty" on his head?

**Me:** What's the value of the figurine (and the ruined cash register)?

*[Editor's note: This is the question of someone who's spent 30+ years wondering if they owe someone a beer, or a formal apology, or possibly financial restitution. Gemini's about to give me the invoice for my childhood crimes.]*

> **Gemini:** In a stroke of irony that Launchpad would appreciate, the "ruined" cash register is actually worth significantly more than the pilot himself.
>
> Here is the 2026 market breakdown for your childhood accident:
>
> **1. The Entombing Force: Fisher-Price Cash Register (Model #926)**
>
> **Condition:** Jammed/Broken (Non-functional caddy)
> **Value:** $10 – $20 AUD
>
> **Market Analysis:** In mint condition with all seven original coins, this toy fetches between $30 and $60 AUD on the vintage market. However, because yours is effectively a "parts-only" unit with a dead-locked mechanism, its value drops to "project" status. It is essentially a $15 paperweight unless someone wants to perform the surgery we discussed.
>
> **2. The Entombee: 1991/92 Launchpad McQuack Figurine**
>
> **Condition:** "Near Mint" (Preserved in a plastic vacuum for 30+ years)
> **Value:** $7 – $15 AUD
>
> **Market Analysis:** These PVC figurines were produced in the millions. Even though yours is likely in pristine condition (having been shielded from UV light and oxygen inside the register), the market is flooded with them. You can pick up a "loose" Launchpad on eBay today for about the price of a fancy sandwich.
>
> **The Combined "Time Capsule" Value**
>
> If you were to sell the register with Launchpad still visible inside, you might actually find a niche collector of "Object Lessons" or "Toy Fails" willing to pay a premium.
>
> **The "Story" Premium:** $50+ AUD
>
> There is a specific charm to a toy that has been "frozen in time" by a specific childhood mistake. In the world of weird collectibles, a 1992 mistake is worth more than a 1992 toy.
>
> **Final Verdict:** Launchpad McQuack is currently a low-value asset trapped inside a depreciated piece of heavy machinery. It is the most on-brand ending possible for Disney's most crash-prone pilot.
>
> Would you like me to draft a mock "eBay Listing" for this disaster to see how we'd market a jammed 90s cash register to collectors?

*[The figurine would have indeed been shielded from UV light, but certainly not oxygen. I don't recall telling Gemini that the inside of the cash register was a vacuum. That would be extremely unlikely for a children's toy.]*

## What Did We Learn?

Gemini's response was genuinely impressive. It indicated at least a conceptual understanding of the mechanism, suggested possible types of jams, provided different solutions that might actually work, identified likely toy models, verified the year, and even calculated the depreciated value of my childhood crime scene.

But here's what it *didn't* do, and this is the crucial part for understanding LLM spatial reasoning:

**It didn't visualise the problem.** Gemini processed my text description and matched it against patterns in its training data about mechanical systems, toy designs, and physics principles. It's doing sophisticated pattern matching and reasoning *about* spatial relationships through language, not actually building a 3D model of a cash register with a duck jammed inside. Having Gemini attempt to generate an image of the problem further illustrates this (and the general disconnect LLMs and the separate LDMs that generate the images for them).

**AI's attempt at illustrating the problem**

![Gemini's AI-generated image of the problem](/assets/img/geminicashregister.jpg)
_Gemini + Nano Banana madness. The image seems impressive, until you look at it for more than two seconds and realise that it's completely nonsensical._

**Here's how it really looked (with bonus "x-ray" vision)**

![Real photo of the cash register alongside an x-ray illustration](/assets/img/xray.jpg)
_Left: A real photo of the same model cash register. Right: My artist's impression of where Launchpad was trapped (made in Krita in a couple of minutes)_

**Expanding on the matter of visual problem solving**

When you read my little story, you probably formed a mental image of the cash register, visualised the mechanism, and imagined Launchpad stuck inside at an angle. LLMs don't do that. They recognise linguistic patterns: "spring-loaded" + "jammed" + "tilted object" triggers associations with "toggle bolt" and "cam lock" from its training data. "Dead-locked" + "no rattle" triggers "friction jam" rather than "loose object."

The solutions Gemini provided? They're not derived from imagining the spatial problem and mentally rotating objects or simulating forces. They're high-probability patterns based on similar problems in its training data. "When object X is jammed in mechanism Y, humans typically try approach Z."

This is why Gemini could be seemingly accurate in its descriptions of a 90s Launchpad figurine and a toddler's cash register, not because it can "see" the toys, but because there are likely thousands of forum posts, repair guides, and nostalgic blog posts about these exact toys in its training data. It's matching my description against a massive library of human obsession and problem-solving.

![Google search results for jammed cash register](/assets/img/screenshot.jpg)
_A quick Google search reveals that I'm not the first idiot to ask the internet how to extract a jammed object from a toy cash register._

The impressive part? For many practical purposes, this distinction doesn't matter. Gemini's suggestions would probably work. The important part? We humans need to understand that this isn't actually spatial reasoning, it's linguistic reasoning *about* spatial concepts. And that distinction becomes crucial when you move beyond well-documented problems into novel spatial scenarios that don't have obvious matches in the training data.

![Michael Scott drives into a lake](/assets/img/mscott.jpg)
_20 years ago, Michael Scott learned the hard way that you shouldn't blindly follow directions from a robot._

Launchpad McQuack is still in that cash register somewhere in suburban Melbourne, entombed since 1992. And while Gemini can tell me how to get him out, it's doing so through the accumulated chatter of humans solving similar problems, not through any actual understanding of what it's like to peer into a toy cash register and see a dead-eyed duck staring back at you.

That image, unfortunately, is mine alone.
