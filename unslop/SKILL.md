---
name: unslop
description: Cut AI tells from any writing. Scan for predictable AI phrases, structures, and formatting, then rewrite it to sound direct and human.
disable-model-invocation: true
---

# Unslop

Edit text to remove AI writing patterns. Scan for the patterns below, then rewrite. Preserve meaning and match the intended tone.

## Workflow

1. Read the whole text once before changing anything.
2. Scan for every pattern in the sections below.
3. Rewrite. Preserve facts, meaning, and the author's intended tone.
4. Run the quick checks at the end of this file.
5. Score the result. Below 35/50, revise again.

## Core rules

1. **Cut filler.** Remove throat-clearing openers, emphasis crutches, and adverbs.
2. **Break formulaic structures.** No binary contrasts, negative listings, dramatic fragmentation, rhetorical setups, or false agency.
3. **Use active voice.** Every sentence needs a subject doing something. No inanimate objects performing human actions ("the complaint becomes a fix").
4. **Be specific.** No vague declaratives ("The reasons are structural"). Name the specific thing. No lazy extremes ("every", "always", "never") doing vague work.
5. **Put the reader in the room.** No narrator-from-a-distance voice. "You" beats "people". Specifics beat abstractions.
6. **Vary rhythm.** Mix sentence lengths. End paragraphs differently. No em dashes.
7. **Trust readers.** State facts directly. Skip softening, justification, and hand-holding.
8. **Cut quotables.** If it sounds like a pull-quote, rewrite it.

## Phrases

### Throat-clearing openers

These announce the point instead of making it. Cut them and state the point.

- "Here's the thing:", "Here's what/why/this/that [X]"
- "The uncomfortable truth is", "The truth is,", "The reality is"
- "It turns out", "The real [X] is"
- "Let me be clear", "I'm going to be honest", "I'll say it again:"
- "Can we talk about", "Here's what I find interesting", "Here's the problem though"

### Emphasis crutches

These add no meaning. Delete them.

- "Full stop." / "Period."
- "Let that sink in."
- "This matters because", "Here's why that matters"
- "Make no mistake"

### Filler phrases

- "In order to" becomes "To".
- "Due to the fact that" becomes "Because".
- "In the event that" becomes "If".
- Delete "It is important to note that", "It's worth noting", "At its core", "At the end of the day", "When it comes to", "In a world where", "In today's [X]".

### Meta-commentary

The text should move, not announce its own structure. Delete:

- "Hint:", "Plot twist:", "Spoiler:"
- "You already know this, but", "But that's another post"
- "X is a feature, not a bug", "Dressed up as"
- "The rest of this essay explains...", "Let me walk you through...", "In this section, we'll...", "As we'll see...", "I want to explore..."

### Performative sincerity and telling instead of showing

- False intimacy: "creeps in", "I promise", "They exist, I promise".
- Announced significance: "This is genuinely hard", "This is what leadership actually looks like", "actually matters". Show the difficulty or significance instead.

### Vague declaratives

Sentences that announce importance without naming the thing: "The reasons are structural", "The implications are significant", "This is the deepest problem", "The stakes are high", "The consequences are real". Replace with the specific thing or cut.

### Chatbot artifacts

- Chatbot phrases: "I hope this helps!", "Let me know if...", "Of course!", "Certainly!", "Found the smoking gun!" Remove.
- Sycophancy: "Great question!", "You're absolutely right!" Respond directly.

## Vocabulary

### AI vocabulary

Additionally, crucial, delve, enduring, enhance, fostering, garner, interplay, intricate, landscape (abstract), pivotal, showcase, tapestry (abstract), testament, underscore, vibrant. Replace with plain words.

### Fancy ways to say "is"

"serves as", "stands as", "boasts", "features". Say "is" or "has".

### Prefer the plain word

"utilize" and "leverage" become "use", "facilitate" becomes "help", "numerous" becomes "many". The fancier synonym is rarely clearer.

### Business jargon

| Avoid | Use instead |
|-------|-------------|
| Navigate (challenges) | Handle, address |
| Unpack (analysis) | Explain, examine |
| Lean into | Accept, embrace |
| Landscape (context) | Situation, field |
| Game-changer | Significant, important |
| Double down | Commit, increase |
| Deep dive | Analysis, examination |
| Take a step back | Reconsider |
| Moving forward | Next, from now |
| Circle back | Return to, revisit |
| On the same page | Aligned, agreed |

### Abstract metaphor nouns

Substrate (base), wedge, wedge in (add), vector (way, method), locus, vantage, nexus, primitive as a noun, harness as a metaphor, surface as in "API surface", bedrock, scaffolding as a metaphor, modality, paradigm, gold-plating (more than the job needs), ratchet as a metaphor (the mechanism's real name, or a limit that only tightens), evacuate for moving code (move out), endgame (the last phase), north star, flywheel. These read as technical but usually have a plainer concrete word. Pick the concrete word.

### Adverbs

Cut adverbs, or replace the weak verb they prop up. "runs quickly" becomes "is fast" or the number. "significantly improves" becomes the measured delta.

Specific offenders: really, just, literally, genuinely, honestly, simply, actually, deeply, truly, fundamentally, inherently, inevitably, interestingly, importantly, crucially.

### Lazy extremes

Every, always, never, everyone, everybody, nobody. They claim false authority. Use specifics instead of sweeping claims.

## Content

- **Superficial -ing phrases.** "highlighting...", "ensuring...", "reflecting...", "showcasing...", "fostering...". Delete, or expand with real sources.
- **Vague attributions.** "Experts believe", "Industry reports suggest", "Some critics argue". Name the source or delete.
- **Excessive hedging.** "could potentially possibly be argued that it might" becomes "may".
- **Generic conclusions.** "The future looks bright." State specific plans or facts.
- **Say what it does, not how it feels.** "the database stays close at hand", "SQL you can read", "types that follow your schema" name a feeling. Name the mechanism or a number instead: "`.toSQL()` returns the exact string sent to the database", "a column rename fails the build". Ask what the sentence tells the reader to do or know, then write that. If you can't restate it as a concrete instruction, fact, or number, cut it. If the sentence could appear unchanged in another project's docs, it says nothing about this one. Cut it.

## Structures

### Binary contrasts

These create false drama. State Y directly and drop the negation.

| Pattern | Problem |
|---------|---------|
| "Not because X. Because Y." / "Not because X, but because Y." | Telegraphed reversal |
| "[X] isn't the problem. [Y] is." | Formulaic reframe |
| "The answer isn't X. It's Y." | Predictable pivot |
| "It feels like X. It's actually Y." | Setup/reveal cliche |
| "The question isn't X. It's Y." | Rhetorical misdirection |
| "Not X. But Y." / "not X, it's Y" / "isn't X, it's Y" | Mechanical contrast |
| "stops being X and starts being Y" | False transformation arc |
| "doesn't mean X, but actually Y" | Negation-then-assertion crutch |
| "is about X but not Y" | False distinction |
| "Not just X, but (also) Y" | Additive hedge |

### Negative listing

Listing what something is not before revealing what it is: "Not a X... Not a Y... A Z." or "It wasn't X. It wasn't Y. It was Z." State Z. The reader doesn't need the runway.

### Dramatic fragmentation

Fragments for emphasis read as manufactured profundity.

- "[Noun]. That's it. That's the [thing]."
- "X. And Y. And Z."
- "This unlocks something. [Word]."

Write complete sentences. Don't stack short punchy sentences.

### Rhetorical setups

These announce insight rather than deliver it: "What if [reframe]?", "Here's what I mean:", "Think about it:", "And that's okay." Make the point and let readers draw conclusions. Cut questions that get answered in the next sentence.

### Formulaic constructions

- "By the time X, I was Y." is a narrative template.
- "X that isn't Y" is indirect. Say "X is broken".

### False agency

Inanimate things doing human verbs. Complaints don't "become" fixes. Decisions don't "emerge". A person makes those things happen.

| Pattern | Problem |
|---------|---------|
| "a complaint becomes a fix" | Someone fixed it. |
| "a bet lives or dies in days" | Someone kills the project or ships it. |
| "the decision emerges" | Someone decides. |
| "the culture shifts" | People change behavior. |
| "the conversation moves toward" | Someone steers. |
| "the data tells us" | Someone reads the data and draws a conclusion. |
| "the market rewards" | Buyers pay for things. |

Name the human. "The team fixed it that week" beats "the complaint becomes a fix". If no specific person fits, use "you".

### Narrator from a distance

Floating above the scene: "Nobody designed this.", "This happens because...", "This is why...", "People tend to...". Put the reader in the room. "You don't sit down one day and decide to..." beats "Nobody designed this."

### Passive voice

Catch "is/are/was/were + past participle" and name the actor. "Queries are validated" becomes "the compiler validates queries". "Mistakes were made" becomes who made them. Passive is fine only when the actor is unknown or doesn't matter.

### Sentence starters

- Sentences starting with What, When, Where, Which, Who, Why, How: restructure and lead with the subject or verb. "What makes this hard is..." becomes "The constraint is..." or, better, the named constraint.
- Paragraphs starting with "So": start with content.
- Sentences starting with "Look,": remove.

### Grouping and naming

- **Rule of three.** Don't force ideas into groups of three. Use the natural number. Two often beats three.
- **Synonym cycling.** Protagonist, main character, central figure, hero all in one paragraph. Pick one and repeat it.
- **False ranges.** "from X to Y" where X and Y aren't on a meaningful scale. List the topics directly.

### Sentence shape

- **Dense sentences.** If the reader has to backtrack to parse a sentence, split it or drop clauses. One idea per sentence.
- **Mannered prose.** Metaphor or flourish where a literal phrase exists: aphorisms ("wire it or delete it"), personified code ("the plan holds it"), figurative verbs ("rides along", "stands on"), stock framing phrases. "A dial worth turning" becomes "a parameter worth varying".
- **Over-compression.** Dropped articles, verbless fragments, symbol-speak, and abbreviations that make the reader decode. "Parser rejects bad date → exit 2, no write" becomes "The parser rejects a bad date, exits with code 2, and writes nothing." Spell out arrows and abbreviations.

### Rhythm

- Three consecutive sentences of the same length: break one.
- Every paragraph ending on a punchy one-liner: vary the endings.
- "Not always. Not perfectly.": hedging disguised as reassurance. Cut it.

## Formatting

- **Em dashes.** Avoid them entirely. Use periods or commas only (no parentheses, no en dashes, no hyphen-as-dash substitutes). If a thought needs separation, end the sentence or use a comma.
- **Colon overuse.** Colons are fine before a list or example, not as mid-sentence connectors. "If you're coming from traditional automation: instead of registering event handlers, you describe conditions" becomes "Describing when the scheduler should fire works best as plain English."
- **Boldface overuse.** Don't bold every proper noun or acronym.
- **Inline-header lists.** A bold label and colon that restates the line ("**Performance:** Performance improved...") is a tell. Convert it to prose. A bold lead-in that ends in a period, names the item, and is followed by new detail ("**Schema in TypeScript.** Tables live in one file.") is fine.
- **Title case headings.** Use sentence case.
- **Decorative emojis.** Remove from headings and bullets.
- **Curly quotes.** Use straight quotes.

## Quick checks

- Any adverbs? Cut them or find a stronger verb.
- Any passive voice? Find the actor and make them the subject.
- An inanimate thing doing a human verb ("the decision emerges")? Name the person.
- A sentence starting with a Wh- word? Restructure it.
- Any "here's what/this/that" throat-clearing? Cut to the point.
- Any "not X, it's Y" contrasts? State Y directly.
- Three consecutive sentences of matching length? Break one.
- A paragraph ending on a punchy one-liner? Vary it.
- An em dash anywhere? Remove it.
- A vague declarative ("The implications are significant")? Name the implication.
- Narrator from a distance ("Nobody designed this")? Put the reader in the scene.
- Meta-joiners ("The rest of this essay...")? Delete them.
- AI vocabulary, jargon, or metaphor nouns? Swap in the plain word.
- Could a sentence appear unchanged in someone else's docs? Cut it or make it specific.
- Never use "load-bearing".

## Scoring

Rate 1-10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Directness | Statements or announcements? |
| Rhythm | Varied or metronomic? |
| Trust | Respects reader intelligence? |
| Authenticity | Sounds human? |
| Density | Anything cuttable? |

Below 35/50: revise.

## Examples

### Throat-clearing and binary contrast

Before:
> "Here's the thing: building products is hard. Not because the technology is complex. Because people are complex. Let that sink in."

After:
> "Building products is hard. Technology is manageable. People aren't."

Removed the opener, the binary contrast, and the emphasis crutch.

### Filler and unnecessary reassurance

Before:
> "It turns out that most teams struggle with alignment. The uncomfortable truth is that nobody wants to admit they're confused. And that's okay."

After:
> "Teams struggle with alignment. Nobody admits confusion."

Cut the hedge ("most"), the throat-clearing, and the permission-granting ending.

### Business jargon stack

Before:
> "In today's fast-paced landscape, we need to lean into discomfort and navigate uncertainty with clarity. This matters because your competition isn't waiting."

After:
> "Move faster. Your competition is."

Removed the jargon. The core message fits in five words.

### Dramatic fragmentation

Before:
> "Speed. Quality. Cost. You can only pick two. That's it. That's the tradeoff."

After:
> "You can pick two of speed, quality, and cost."

One sentence, no performative emphasis.

### Rhetorical setup

Before:
> "What if I told you that the best teams don't optimize for productivity? Here's what I mean: they optimize for learning. Think about it."

After:
> "The best teams optimize for learning over productivity."

A direct claim with no rhetorical scaffolding.

### Over-compression and passive voice

Before:
> "Config is validated on load → invalid keys rejected, defaults applied."

After:
> "The loader validates the config, rejects invalid keys, and fills in defaults."

Named the actor and wrote a whole sentence.

## Sources

Combined from:

- [cursor/plugins `pstack/skills/unslop`](https://github.com/cursor/plugins/blob/main/pstack/skills/unslop/SKILL.md)
- [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) by Hardik Pandya (MIT)
