# 01 — Problem Discovery

## Observation

Recurring mobility trips have unusually predictable intent.

A commuter who travels between the same locations repeatedly should not have to reconstruct the same booking context from scratch every time.

## Problem statement

> Repeat riders may spend unnecessary interactions recreating known commute context before they can book.

This is deliberately framed as a hypothesis rather than a proven fact.

## Why this problem is worth testing

It sits close to a meaningful product event: completed rides.

Potential upside:
- lower friction
- faster booking
- stronger repeat behaviour
- better utility for high-frequency customers

Potential downside:
- users may value control over speed
- saved routes can become stale
- fare/ETA variability can create expectation mismatch

Therefore, the shortcut should preserve live decision information and user control.

## Target segment

Start with riders who:
- have completed multiple trips
- show recurring origin/destination patterns
- frequently book during commute windows

Avoid forcing the feature onto occasional riders.

## User journey

Open app → choose route → enter/check trip details → book → ride → repeat

Opportunity:

Open app → Commute Mode → verify live details → book

## Key discovery questions

1. How many users actually have recurring routes?
2. Do they repeat routes at predictable times?
3. What causes the most friction: route entry, fare uncertainty, ETA uncertainty, or choice overload?
4. Would users trust a saved route?
5. What exceptions require editing before booking?

## Validation plan

Before engineering:
- 8–12 qualitative commuter interviews
- click-tracking on the existing booking flow
- cohort analysis for repeat-route behaviour
- fake-door test on the home screen
- usability testing of the prototype

**Decision gate:** build only if recurring users show meaningful adoption intent and the current journey demonstrates measurable avoidable friction.
