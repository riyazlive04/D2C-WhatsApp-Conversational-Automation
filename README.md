# D2C WhatsApp Conversational Automation

This n8n workflow powers an AI-driven WhatsApp assistant for D2C brands using Evolution API.

It listens to incoming WhatsApp messages, maintains conversation memory, understands customer intent, and replies with human-like responses for product queries, pricing, usage guidance, and ordering support.

All conversations are logged in Google Sheets for tracking and follow-ups.

## Requirements
- n8n (self-hosted or cloud)
- Evolution API
- Google Sheets (conversation history)
- AI model (Gemini / OpenAI)
- WhatsApp device linked to Evolution API

## WhatsApp Device Setup (Required)
Link your WhatsApp device before activating the workflow:
https://message.sirahagents.com/manager/

## Features
- Real-time WhatsApp message handling
- Conversation memory (last messages)
- AI-powered natural replies
- Product discovery & order guidance
- WhatsApp response delivery via Evolution API
- Full conversation logging

## Usage
1. Import the JSON into n8n
2. Configure Evolution API credentials
3. Link your WhatsApp device
4. Connect Google Sheets & AI credentials
5. Activate the workflow

This workflow is ideal for D2C brands, WhatsApp commerce, and automated customer support.
