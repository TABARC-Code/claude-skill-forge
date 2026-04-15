# Crossfire Foundry v4 — Professional Release

Crossfire Foundry v4 is a production-grade Claude skill system for designing, pressure-testing, documenting, and iterating tabletop games.

It is built for four jobs that usually break when handled as separate disciplines:

- **wargame design** — mechanics, friction, activation, balance, scenario structure
- **campaign design** — persistence, logistics, operational movement, linked battle consequence
- **eurogame usability** — teachability, social durability, pacing, and reduction of needless friction
- **technical writing** — rulebooks, procedures, troubleshooting, warnings, and production-ready clarity

This release is stricter than the earlier versions. It does not rely on casual “see also” links. It encodes **structured reciprocal contracts** between modules. If one file routes into another, the receiving file states how that route is accepted, what it returns, what it may invoke next, and how reverse routes work where they exist.

## Package guarantees

This package is built to the following constraints:

- exactly one top-level folder
- exactly one master `SKILL.md`
- all supporting logic moved into `subskills/`
- supporting documentation in `docs/`
- no empty shell sections
- no unfinished marker text

## What is inside

- `SKILL.md` — master router, execution order, mode selection, and hard rules
- `subskills/` — the working system
- `docs/` — install, architecture, audit, release notes, changelog
- `examples/` — activation prompts and worked usage patterns

## Version identity

- **v1** — exploratory framework
- **v2** — broad agent expansion
- **v3** — enforced execution engine
- **v4** — professional release with reciprocal routing contracts, chain propagation rules, arbitration gates, validation checks, and release audit

## Best use cases

Use this system when you need one or more of the following:

- a new skirmish, operational, or campaign ruleset
- a hostile review of an existing design, playtest packet, or rulebook
- a campaign layer that persists consequences across games
- a rulebook that reads cleanly under stress
- a design board that can disagree without collapsing into mush

## Recommended activation prompt

> Run Crossfire Foundry v4 in Build Mode.  
> Design a skirmish ruleset with alternating activation, morale, and campaign persistence.  
> Force adversarial review, arbitration, validation, and final editorial release.

## Final note

This system is designed to behave like a disciplined studio, not a mood board. If it feels slightly severe, that is intentional.
