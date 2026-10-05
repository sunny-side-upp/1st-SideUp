# 04 — Metrics & Experiments

## North Star metric

### Repeat commute booking completion rate

Completed bookings divided by Commute Mode booking intents.

This connects the feature to a meaningful product outcome rather than a vanity click metric.

## Funnel

Home screen view  
↓  
Commute card impression  
↓  
Commute card tap  
↓  
Commute confirmation loaded  
↓  
Booking confirmation  
↓  
Ride completed  
↓  
Next commute repeat

## Experiment 1 — Friction reduction

**Hypothesis:** Surfacing saved commute context reduces time-to-book for repeat riders.

**Control:** standard booking journey

**Treatment:** Commute Mode

Measure:
- booking completion
- median time-to-book
- abandonment
- cancellation

## Experiment 2 — Confidence

Test two confirmation treatments:

**A:** fare + ETA only

**B:** fare + ETA + simple context cue

Measure:
- confirmation rate
- edits before booking
- cancellations
- user feedback

## Instrumentation

Suggested events:
- `commute_card_viewed`
- `commute_card_tapped`
- `commute_confirmation_loaded`
- `commute_route_edited`
- `commute_booking_confirmed`
- `commute_booking_cancelled`
- `commute_ride_completed`

## Guardrails

A feature is not successful if faster booking creates:
- higher cancellation
- more failed bookings
- more support tickets
- lower rider trust

## Decision framework

Ship beyond MVP only if:
1. core adoption is meaningful,
2. booking friction falls,
3. guardrails remain healthy,
4. repeat behaviour improves.
