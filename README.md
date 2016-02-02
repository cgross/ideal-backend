# ideal-backend

- complete audit trail
  - for security purposes
  - potential use as a news feed or activity feed feature
  - underlying engine for other features:
    - websocket messages (below)
    - automated alerts when X happens or Y is updated
- websocket messsages for all updates
  - appreciating security
  - sent from audit trail so message can include new, old, and diff of updates
- webhooks?
- Some endpoints will need to transform/filter an entity before sending it back (for security purposes)
- Similarly some endpoints will need to accept a tranformed/filtered entity for PUTs
- PATCH for atomic modifications

