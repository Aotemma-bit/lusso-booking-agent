# 🏨 Lusso AI Booking Agent

An intelligent WhatsApp hotel booking assistant built with n8n that automates guest enquiries, room reservations, payment processing, and reservation management.

## Workflow

![Workflow](images/workflow.png)

---

## Features

- WhatsApp AI Chatbot
- Google Gemini AI Agent
- Guest Memory
- Room Availability Lookup
- Reservation Creation
- Reservation Updates
- Reservation Cancellation
- Guest Registration
- Stripe Payment Integration
- Google Sheets Database
- Automated WhatsApp Responses

---

## Tech Stack

- n8n
- Google Gemini
- WhatsApp Cloud API
- Google Sheets
- Stripe
- HTTP API

---

## Reservation Database

### Reservation Table

![Reservation Table](images/reservation-sheet.png)

### Payment & Reservation Status

![Reservation Status](images/reservation-status.png)

---

## Workflow Process

1. Customer sends a WhatsApp message.
2. AI Agent understands the request.
3. Retrieves available rooms.
4. Creates or updates reservations.
5. Registers guests.
6. Generates Stripe payment links.
7. Sends confirmations on WhatsApp.
8. Stores all reservation data in Google Sheets.

---

## Use Cases

- Hotel Reservation Automation
- Guest Support
- Payment Collection
- Reservation Management
- AI Concierge
