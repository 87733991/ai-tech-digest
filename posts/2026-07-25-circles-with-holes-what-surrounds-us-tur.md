# Circles With Holes: What Surrounds Us Turns Ecology Into a Systems Puzzle

*Published on 2026-07-25*

---

# Circles With Holes: What Surrounds Us Turns Ecology Into a Systems Puzzle

## Context & Core Event Analysis

*What Surrounds Us*, a short PC adventure now on Steam and covered by The Verge, takes its title with almost pedantic seriousness. You are not a hero with inventory slots. You are a circle with a hole in the middle—a moving ring that looks, as the review notes, like a donut with frosting. The map is built from the same geometric grammar: circles, openings, meetings, and the spaces that form between them. Other rings are not NPCs in the cutscene sense; they are sentient moving bodies with their own trajectories. Sometimes the work is joyful—helping two shapes find each other. Sometimes it is infrastructural—reading the environment well enough that a fragile habitat does not collapse under your “help.”

That framing is the news, not a cute art style. The game sells ecology as interaction design: species with unique behaviors, environmental challenges, and an abstract colorful world that still insists on consequence. You explore at your own pace, but the systems underneath are not free-form fantasy. They are rules about adjacency, enclosure, and what a surrounding body can enable or destroy. In an industry still full of open-world checklists and combat-as-progress, a title that makes “surrounding” the primary verb is a deliberate constraint. The Verge’s coverage lands on the right pressure point: the game will make you think a lot about circles—not as decorative UI, but as a model of how things hold, pass through, and depend on one another.

The commercial context is familiar for short indie systems games: Steam discovery, a compact runtime, and a thesis strong enough to travel without multiplayer live-ops. The interesting part for builders is not the score. It is that the fiction and the mechanics share one data model. If the world is made of rings, every player action is a topology edit. That is closer to network ops than to power fantasy.

## Domain Knowledge & Technical Extension

Games that reduce the world to a small set of primitives are doing architecture work under another name. Circles with holes are a clean abstraction for containers, boundaries, and channels. A ring can enclose; a hole can admit; two rings meeting can form a temporary joint. That is not far from how engineers reason about interfaces: what is inside the trust boundary, what is allowed to cross, and what happens when two services “joyfully meet” without a contract.

In systems terms, *What Surrounds Us* is closer to a constraint solver than to a story engine. Unique species behaviors read like agents with local policies. Environmental challenges read like capacity and degradation models. The player is not conquering a map so much as becoming part of a feedback loop—exactly the difference between a dashboard that only reports metrics and an operator who can change routing. Abstract ecology games often fail when the metaphor is paint and the simulation is fake. They work when the metaphor is load-bearing: when “protect the habitat” is enforced by rules the player can feel, not by a lecture after a cutscene.

There is also a quiet lesson for AI-era product design. Synthetic perfection and high-fidelity assets are now cheap. What remains expensive is operable meaning: a small ruleset that still produces legible consequence. A donut avatar is almost anti-spectacle. It forces attention onto adjacency and intent. That is the same bet good infrastructure UIs make when they stop decorating every panel and start making dependency graphs honest. If your model of the world is “entities with hit points,” you design combat. If your model is “bodies that surround and are surrounded,” you design coupling.

## Trade-off & TCO Breakdown

The engineering trade-off is classic. A tight geometric language lowers art and animation TCO: fewer skeletons, fewer combat trees, less content surface area to maintain across patches. It also raises design and QA cost, because every interaction must be readable inside the same circle grammar. Players will not forgive a broken meeting mechanic the way they forgive a bland side quest. Maintenance cost shifts from asset pipelines to systems balance—tuning behaviors, failure modes, and the pacing of discovery so a short game does not feel thin.

Ecosystem impact is double-edged. Constraint-led indies can ship faster and teach harder ideas than sprawling open worlds, but they also live or die on first-hour clarity. If players cannot internalize the ring logic, no amount of ecological messaging recovers the session. Total cost of ownership for the studio is not just build hours; it is the support surface of a metaphor that must stay consistent from trailer to end credits. For players, the TCO is attention: a short systems game is cheap in dollars and expensive in interpretive load. That is a fair exchange only if the rules pay rent every minute.

Comment: This is not proof that circles beat open worlds; it is proof that when ecology is encoded as topology instead of slideshow, markets reprice a short Steam title as systems literacy—and your real question is whether your own product’s “surroundings” are modeled as operable dependencies or as decorative background. (Personal view)
