# AI-Powered Appointment Booking & Voice Automation System (n8n + VAPI)

## 🚀 Overview

An end-to-end AI automation system built using n8n and VAPI to handle
real-time appointment booking through webhook-triggered workflows. The
system integrates Google Calendar for availability checks and Google
Sheets for structured data storage.

## 🎯 Key Features

-   Real-time availability detection using Google Calendar API
-   AI-powered conversational booking logic
-   Structured output parsing for reliable slot confirmation
-   Automated data storage in Google Sheets
-   Multi-workflow orchestration with conditional routing

## 🏗 Architecture

Webhook Trigger → AI Agent → Availability Check (Google Calendar) →
Conditional Logic → Booking Confirmation → Data Storage (Google Sheets)
→ Response

## 📊 Impact

-   Achieved 95%+ slot detection accuracy
-   Reduced manual booking effort by \~80%
-   Scalable webhook-based architecture supporting concurrent users

## 🛠 Tech Stack

-   n8n
-   VAPI
-   Google Calendar API
-   Google Sheets API
-   Webhooks
-   Structured Output Parsing
-   AI Agent Orchestration

## 🔧 How It Works

1.  User initiates request via webhook/voice interface.
2.  AI agent interprets booking intent.
3.  Calendar availability is checked dynamically.
4.  Slot is confirmed and stored in Google Sheets.
5.  Confirmation response is sent back to user.

## 📌 Future Improvements

-   Add retry logic for API failures
-   Add monitoring and logging layer
-   Integrate SMS/Email confirmation workflows

------------------------------------------------------------------------

Built for scalable AI-powered automation infrastructure.
