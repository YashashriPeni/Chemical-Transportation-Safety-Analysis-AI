# Chemical Transportation Safety Analysis AI

## Overview

An AI-powered chemical transportation safety analysis system built using n8n and OpenAI.

The workflow receives transportation details through a webhook, validates the input, analyzes transportation risks using AI, and generates safety recommendations.

---

## Features

- Webhook-based API endpoint
- Input validation using conditional logic
- AI-powered risk assessment
- Safety recommendation generation
- Regulatory compliance guidance
- Emergency precaution suggestions

---

## Workflow Architecture

1. Webhook receives transportation data
2. Input validation checks chemical type
3. Prompt preparation for AI analysis
4. OpenAI performs risk assessment
5. Results returned through API response

---

## Technology Stack

- n8n
- OpenAI GPT
- Webhooks
- JSON API

---

## Sample Input

```json
{
  "type": "chemical",
  "name": "Sulfuric Acid",
  "hazard": "High",
  "temperature": 45,
  "transport": "Truck"
}
