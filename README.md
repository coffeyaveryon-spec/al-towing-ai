[README_ALTowing.md](https://github.com/user-attachments/files/27855385/README_ALTowing.md)
# A&L Towing — AI Lead Capture & Call Automation Platform

> AI-driven inbound call automation system replacing manual lead intake workflows. Deployed conversational AI to capture, qualify, and route inbound calls — enabling 24/7 lead coverage without additional staffing costs.

---

## What It Does

A&L Towing was losing inbound leads every time a call went unanswered — after hours, during busy periods, or when staff were already on calls. This system replaced manual call handling with an AI agent that answers every call, captures lead information, qualifies the request, and routes it appropriately — 24/7.

No missed calls. No missed leads.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Voice AI | Vapi.ai |
| LLM | Claude API (Anthropic) |
| Telephony | Twilio |
| Automation | Make.com |
| Lead Routing | Webhook-based CRM integration |
| Backend | REST APIs |

---

## Architecture Overview

```
Inbound Call Received
        ↓
  Vapi Voice Agent Answers (instant pickup)
        ↓
  Conversational Lead Capture
  ┌──────────────────────────────────┐
  │  Caller name & contact info      │
  │  Service type needed             │
  │  Vehicle & location details      │
  │  Urgency assessment              │
  └──────────────────────────────────┘
        ↓
  Lead Qualification Logic
        ↓
  ┌─────────────────────────────────────┐
  │  High priority → immediate alert    │
  │  Standard → CRM entry + follow-up   │
  │  Out of service area → redirect     │
  └─────────────────────────────────────┘
        ↓
  Lead Data pushed to CRM via Webhook
        ↓
  Staff Notified (SMS / Email alert)
```

---

## Key Features

- **Instant Answer Rate** — every inbound call answered immediately, regardless of time or staff availability
- **Structured Lead Capture** — extracts name, number, location, vehicle info, and service type in natural conversation
- **Lead Qualification** — prioritizes urgent roadside calls vs. standard scheduling requests
- **Automated CRM Entry** — lead data written to CRM automatically with zero manual data entry
- **Staff Alerts** — real-time notifications sent to the right team member based on lead type
- **After-Hours Coverage** — fully autonomous operation outside business hours

---

## Results / Impact

- Reduced missed inbound calls by **40%+**
- Captured **100+ qualified leads** through automated intake
- Eliminated manual lead logging — zero data entry required from staff
- Extended effective business hours to 24/7 without hiring additional staff

---

## Project Status

Production-deployed for towing & roadside services client. Actively handling inbound calls.

---

## Contact

Built by **Averyon Coffey** — [acaidev.org](https://acaidev.org) · [coffeyaveryon@gmail.com](mailto:coffeyaveryon@gmail.com)
