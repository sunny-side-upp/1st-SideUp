# Commute Mode — A Product Case Study

> Self-initiated mobility product concept.

## The problem

For many urban commuters, the hardest part of a familiar ride is not discovering the service — it is repeating the same intent every day.

A rider may repeatedly:
- enter the same pickup and destination
- review the same trip context
- decide whether today's ETA/fare feels acceptable
- complete the same booking flow

This creates avoidable friction at a moment of high intent: "I need my usual ride now."

## Product question

How might we turn a recurring commute into a one-tap, confidence-building experience without taking control away from the rider?

## The solution

### Commute Mode

A personalized shortcut for recurring trips.

One tap → confirm the saved route → see current ETA/fare → book.

The experience surfaces:
- current ETA
- estimated fare range
- preferred ride type
- quick edit controls
- a clear alternative path when the preferred option is unavailable

The goal is not to add more features. It is to remove repeated work from an already-known journey.

## Product thinking

**Primary user:** an urban commuter with one or more recurring routes.

**Core job-to-be-done:** Help me get my usual ride with minimal effort while still letting me verify today's price and pickup time.

**Key hypothesis:** If repeat riders can launch a saved commute directly from the home screen and verify live trip conditions before booking, booking completion time should fall and repeat-trip conversion should improve.

## MVP scope

| Priority | Feature | Why |
|---|---|---|
| P0 | Saved commute card | Removes repeated route entry |
| P0 | Live ETA + fare range | Preserves decision confidence |
| P0 | One-tap booking flow | Reduces interaction cost |
| P1 | Edit route/time | Handles exceptions |
| P1 | Multiple commute presets | Supports more than one routine |
| P2 | Proactive commute reminder | Useful only after core usage is validated |

## Success metrics

**North Star:** Repeat commute booking completion rate

Supporting metrics:
- median time from home-screen view to booking
- saved-commute adoption
- repeat booking frequency
- booking cancellation rate
- ETA/fare edit rate
- 7-day retention of Commute Mode users

**Guardrails**
- cancellation rate
- failed booking rate
- support contacts related to fare/ETA expectations
- reminder opt-out rate

## Experiment design

**Control:** existing home-screen booking flow

**Treatment:** Commute Mode card for eligible repeat riders

Measure:
- booking completion
- time-to-book
- repeat booking frequency
- cancellation

The first experiment should validate friction reduction, not the whole roadmap.

## What I built

This project contains:
1. Problem framing
2. User journey and opportunity analysis
3. MVP PRD
4. User stories and acceptance criteria
5. Metrics and experiment plan
6. Product roadmap
7. A simple clickable HTML prototype
8. Four mobile UI mockups as SVGs

### Prototype

Open `prototype/index.html` locally to explore the flow.

Screens are available in `screens/`:
- Home
- Commute confirmation
- Trip tracking
- Post-ride

## What I'd do differently today

The first version of this case focused mainly on reducing interaction friction.

Today I would push discovery further before committing to the feature:
- interview repeat riders across different commute patterns
- distinguish "repeated route" from "repeated time" behaviour
- validate whether fare volatility or pickup uncertainty is the bigger source of anxiety
- test a fake-door concept before building the full experience
- instrument the existing booking journey to quantify where repeat users spend time
- evaluate operational constraints before promising one-tap booking

The biggest lesson: **a good PM does not start with the feature. The feature is the output of validated user behaviour.**

## Disclaimer

This is a self-initiated product concept, not an official product or internal project of any mobility company. Assumptions in the case are hypotheses for product exploration rather than claims about proprietary user data.
