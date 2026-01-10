# Memory System Update

**Objective:** Introduce long-term and short-term memory systems to enhance the AI's conversational context and personalized interactions.

---

## New Features (v2.5.2)

### Long-Term Memory
- Stores user-specific facts and relationships persistently across sessions
- Allows adding and retrieving facts per user
- Maintains a “friends” list and metadata (creator information)
- Memory is saved in a JSON file for durability and future retrieval
- Enables the AI to recall previous interactions, making conversations feel continuous

### Short-Term Memory
- Maintains context for recent interactions during a session
- Stores the last few user-bot exchanges (configurable number of turns)
- Builds dynamic context summaries to inform AI responses
- Automatically discards oldest entries to keep memory buffer concise

---

## Version 2.5 Update — 2.5.2

### Added: Memory System
This update introduces a dual-memory system that allows the AI to:
- Remember user-specific information over multiple sessions (long-term memory)
- Keep track of ongoing conversation context (short-term memory)
- Provide more natural, personalized, and coherent responses

---

## Patch Notes

### v2.5.2.1 — Memory System

#### Features
- **Long-Term Memory:** JSON-based persistent storage of facts, friends, and metadata
- **Short-Term Memory:** Session-level buffer of recent conversation turns
- Context-aware responses leverage both memory systems
- Adds foundation for future enhancements such as adaptive behavior and personalized interactions

**This update significantly improves conversation continuity, personalization, and user experience.**

# Patch Notes

### v2.5.2.2 - Conversation Topic Memory

#### Features
- **Persistent Topic Tracking:** Stores the current main conversation topic per user with timestamp
- **Easy Access & Management:** Functions to set, retrieve, and clear the active topic
- **Session-spanning Context:** Topic persists across messages, mode switches, and application restarts
- Provides foundation for more coherent, context-aware replies (e.g. "Continuing our discussion about your [x,y,z]...")
**This update adds lightweight but powerful short-term conversational continuity, helping Lilly stay on-topic and feel more connected to ongoing discussions.**
