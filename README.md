# AryaBot - AI Tutor Workflow (n8n)

AryaBot is an interactive AI tutoring workflow built in n8n. It guides students through complex concepts using a structured 4-part pedagogical response format while keeping track of conversation history.

## 🛠️ Workflow Architecture
* Trigger: Chat Trigger (When chat message received)
* Core Agent: AI Agent Node
* Language Model: OpenAI Chat Model
* Memory: Simple Memory (session-tracked)

## 🎯 Response Format
AryaBot follows a strict output template for effective teaching:
1. Core Concept: High-level 1–2 sentence definition.
2. Real-World Analogy: Everyday comparison for easy understanding.
3. Key Details: 3 concise bullet points.
4. Check-In Question: A quick question to test student retention.
