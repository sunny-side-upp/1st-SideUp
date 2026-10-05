# 03 — User Stories & Acceptance Criteria

| Story | Acceptance criteria | Priority |
|---|---|---|
| Save a recurring trip | Rider can save origin + destination with a label | P0 |
| Rebook from home | Relevant saved commute appears on home | P0 |
| Verify live conditions | ETA + fare range refresh before confirmation | P0 |
| Edit exception | Rider can change pickup/destination | P1 |
| Handle availability | Unavailable option shows alternatives | P1 |
| Manage saved commutes | Rider can edit/delete saved routes | P1 |
| Add another routine | Rider can create a second commute | P2 |

## Edge cases

### Fare changed
Show the updated estimate clearly before confirmation.

### Pickup changed
Allow the rider to edit pickup without rebuilding the whole journey.

### Saved location is stale
Prompt the rider to review or update it.

### Preferred ride is unavailable
Offer alternatives and preserve user agency.

### User is occasional
Do not clutter the home screen with a feature that does not match behaviour.
