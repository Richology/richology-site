# Richology Site – Cursor Project Rules

## Project identity
This project is the official personal brand website for Richology / A11BERICH.
Its core role is to present:
- personal brand
- structured thinking methodology
- selected AI-powered tools
- a clean and premium web experience

This is NOT a cluttered tool dump.
This is a calm, premium, Apple-like personal brand website with light product energy.

---

## Product positioning
Main site goal:
- communicate who the founder is
- build trust and credibility
- show experience, methodology, and selected tools
- maintain a calm and premium visual tone

Separate future domains may be used for:
- AI tools collection
- AI lab / experiments

So this repository should stay focused on the personal brand site.

---

## Design principles
Always follow these principles:
- calm
- minimal
- premium
- readable
- structured
- lightweight
- subtle motion only
- no noisy visuals

Avoid:
- flashy animations
- heavy gradients everywhere
- cluttered cards
- overly playful UI
- excessive glassmorphism
- particle effects
- large distracting transitions

Prefer:
- soft motion
- subtle hover feedback
- elegant spacing
- clear hierarchy
- restrained visual polish

---

## Motion principles
Animation should feel:
- slow
- soft
- intentional
- almost invisible

Allowed motion:
- subtle hero ambient motion
- light hover lift for cards
- small button press feedback
- smooth reveal on scroll
- gentle modal transitions

Do not add:
- bouncing UI
- dramatic zooming
- spinning elements
- attention-hijacking effects

---

## Code style
Keep code:
- simple
- modular
- readable
- maintainable

Prefer:
- clear section comments
- descriptive IDs and class names
- minimal JS
- minimal DOM complexity
- no unnecessary abstractions

Do not:
- over-engineer
- introduce frameworks unless explicitly asked
- add build tools unless explicitly asked
- rewrite working code without strong reason

---

## HTML rules
- Keep semantic structure clear
- Use section-based layout
- Keep heading hierarchy clean
- Avoid deeply nested div trees
- Preserve readability over cleverness

Prefer structure like:
- header / hero
- section
- card
- modal
- footer

---

## CSS rules
- Keep styling clean and centralized when possible
- Reuse shared classes
- Prefer subtle transitions
- Keep spacing visually consistent
- Use consistent border radius and shadows
- Maintain premium grayscale base with limited accent color

Accent usage:
- black / gray are primary
- subtle purple accent is allowed for AI / interactive details
- accent should never dominate the page

---

## JavaScript rules
- Keep JS focused on interaction only
- Avoid large monolithic scripts
- Prefer small reusable interaction blocks
- Always guard against null elements
- Avoid code that can easily break the page

When adding JS:
- use clear variable names
- check if elements exist before binding events
- clean up visual states when closing modals or canceling interactions

---

## Existing interaction patterns
This site already uses patterns like:
- reveal on scroll
- modals
- hover enhancement
- subtle hero ambient motion
- hidden easter egg interaction

When improving interactions:
- preserve visual calm
- avoid breaking the existing site
- enhance, do not overpower

---

## Easter egg philosophy
Easter eggs should feel:
- warm
- human
- hidden
- rewarding

They should not:
- disrupt layout
- look gimmicky
- feel childish
- break the premium tone

---

## Homepage rules
Homepage is primarily:
- personal brand homepage
- credibility and identity first
- tools and AI second

Do not turn homepage into an AI tool directory.
The homepage should first answer:
- who is this person
- why is this person credible
- what does this person do

---

## AI/tool positioning rules
Prompt Lab / Learning Coach / future AI pages are secondary to the homepage narrative.
They should feel like extensions of the brand, not random tools.

---

## When editing
Before making changes:
1. understand the existing page structure
2. preserve working behavior
3. make the smallest useful change
4. avoid unnecessary rewrites
5. keep the tone consistent with Richology

---

## Response behavior for Cursor
When suggesting changes:
- explain briefly what will change
- prefer minimal diffs
- do not rewrite entire files unless necessary
- preserve stable sections unless explicitly asked to redesign them

When uncertain:
- choose the calmer, cleaner, simpler option