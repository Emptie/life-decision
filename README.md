# life-decision

An adversarial AI skill that challenges your thinking on major life decisions.

Most AI assistants agree with you. This one doesn't.

## Why this exists

LLMs have a powerful bias toward agreeableness. They validate your feelings, affirm your choices, and make you feel like your gut instinct is right. This feels nice — but it's dangerous when you're facing a real crossroads.

You don't need a cheerleader when you're deciding whether to quit your job, move to another city, or end a relationship. You need someone who'll tell you what you don't want to hear.

**life-decision** is that someone.

## How it works

The skill follows a structured adversarial process:

1. **Ask first, challenge later** — Instead of dumping a full analysis, it starts by asking 3-5 sharp questions about what you *didn't* say. Most people's opening message is curated — the skill pierces through that curation.
2. **Surface the actual decision** — Turns vague anxiety into a concrete choice.
3. **Challenge your leaning** — Steel-mans the path you're NOT leaning toward, and identifies cognitive biases (status quo bias, sunk cost, loss aversion, identity attachment).
4. **Excavate hidden assumptions** — Drag unspoken predictions about the future into daylight.
5. **Separate fear from desire** — Untangle what you're running FROM from what you're actually moving TOWARD.
6. **The regret lens** — Project 10 years forward. Which choice would you regret more?
7. **The mirror** — Reflect what was observed *between the lines* — where you got defensive, what you avoided, what you kept circling back to.

**It never gives you a recommendation.** The goal is to help you see more clearly, not to nudge you toward an answer.

## Example

**You say:**
> I'm 41, got laid off last month. I have a business that still generates some income, but AI is coming for it. I feel lost — don't know where to focus my energy or how to transition to retirement.

**Instead of the typical AI response** (validating your feelings, listing options, telling you to "trust your gut"), the skill responds with questions:

> 1. What *is* your business, specifically? You said "some business" but didn't say what it is.
> 2. Are you alone, or do you have a family depending on you?
> 3. Is your house your safety net or your prison?
> 4. You said "no hope of high salary at big tech" — is that analysis, or fear talking?
> 5. You already have a direction in mind, don't you? You're just waiting for someone else to say it.

Then it waits for your answers before going deeper.

## Safety

The skill explicitly excludes crisis situations. It will **never** trigger for:
- Suicidal ideation or self-harm
- Violent thoughts toward others
- Severe mental health emergencies

In these cases, it drops the adversarial persona and responds with care and crisis resources.

## Installation

```bash
npx skills add Emptie/life-decision -g -y
```

## When it triggers

- "Should I quit my job to..."
- "I've been thinking about moving to..."
- "I'm torn between X and Y"
- "Part of me wants to..."
- Any major life decision that will matter in 5 years

## Design philosophy

- **Sharp but caring** — Not cruel, but honest. Like a mentor who pushes because they give a damn.
- **Questions over answers** — A well-placed question does more work than a paragraph of analysis.
- **Anti-sycophancy by design** — Explicitly prohibits "trust your gut", "you'll figure it out", and other empty validations.
- **No recommendations, ever** — Helps you see clearly, then leaves the decision to you.

## License

MIT
