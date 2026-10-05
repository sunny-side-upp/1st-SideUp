# 02 — MVP PRD

## Product

Commute Mode

## Objective

Reduce repeated booking effort for recurring riders while preserving transparency around live fare and ETA.

## User story

As a repeat commuter, I want to start my usual trip quickly so that I can book without repeating the same setup every day.

## Functional requirements

### P0 — Saved commute
- Save an origin/destination pair.
- Give it a label such as "Office" or "Home".
- Show a relevant saved commute on the home screen.

### P0 — Live trip confirmation
- Show current ETA.
- Show estimated fare range.
- Show selected ride type.
- Allow route editing before booking.

### P0 — Fast booking
- Move from commute card to confirmation with minimal steps.
- Keep booking confirmation explicit.

### P1 — Exceptions
- Change pickup.
- Change destination.
- Change ride type.

### P2 — Multiple routines
- Support multiple saved commute pairs.
- Rank them by recent usage/context after validation.

## Non-functional considerations

- Saved locations must be editable/deletable.
- Live ETA and fare should refresh before booking.
- No background booking.
- Clear error state when the preferred option is unavailable.

## Acceptance criteria

**Given** a saved commute exists  
**When** the rider opens the app  
**Then** a relevant commute shortcut is visible.

**Given** a commute shortcut is selected  
**When** live trip details load  
**Then** the rider sees current ETA and fare range before confirming.

**Given** the preferred ride type is unavailable  
**When** the rider reaches confirmation  
**Then** the UI offers an alternative instead of silently changing the ride.

## Out of scope for MVP

- subscription / commuter pass
- dynamic loyalty pricing
- predictive departure suggestions
- automatic booking without confirmation
- complex ML personalization
