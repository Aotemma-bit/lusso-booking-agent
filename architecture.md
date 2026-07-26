# System Architecture

```
WhatsApp
      │
      ▼
WhatsApp Trigger
      │
      ▼
Google Gemini AI Agent
      │
 ┌────┼───────────────────────────┐
 │    │        │        │         │
 ▼    ▼        ▼        ▼         ▼
Rooms Guests Reservations Payments Memory
 │      │        │         │
 ▼      ▼        ▼         ▼
Google Sheets  Stripe  HTTP API

             │
             ▼
     WhatsApp Response
```

## Components

- WhatsApp Trigger
- Google Gemini Chat Model
- AI Agent
- Simple Memory
- Google Sheets Database
- HTTP Requests
- Stripe Payments
- Reservation Management
