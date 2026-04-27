# 🧠 MindFlow  
### An Agentic Layer for Task Management

MindFlow is an AI-powered system that transforms unstructured inputs into structured, actionable workflows. It acts as an agentic layer on top of existing productivity tools, enabling users to capture thoughts naturally and have them automatically converted into tasks, follow-ups, and insights.

---

## 🚨 Problem

Modern workflows are fragmented across notes, emails, chat, and memory. As a result:

- To-dos are scattered across multiple platforms  
- Action items are often forgotten or lost  
- Delegation and follow-up lack visibility  
- Users spend more time organizing work than doing it  

---

## 💡 Solution

MindFlow bridges this gap by introducing an **agentic AI layer** that:

1. **Ingests unstructured input**  
   - Voice notes  
   - Text, email, calendar events  

2. **Extracts structured information**  
   - Tasks  
   - Deadlines  
   - Owners  
   - Context  

3. **Executes actions automatically**  
   - Creates tasks  
   - Schedules follow-ups  
   - Delegates work  
   - Syncs across platforms  

4. **Generates insights**  
   - Completion trends  
   - Focus summaries  
   - Behavioral patterns  

---

## 🏗️ System Architecture

### 🔹 Pipeline Overview
   Input → Speech-to-Text → Information Extraction → Organization → Actions & Insights


### 🔹 Core Components

#### 1. Input Ingestion
- Captures multimodal input (voice, text, email, calendar)

#### 2. Speech-to-Text
- Whisper-based transcription (privacy-aware)

#### 3. Information Extraction (SLM)
- Identifies:
  - Action items  
  - Deadlines  
  - Participants  
  - Context  

#### 4. Organization Layer
- Clusters tasks by:
  - Work vs personal  
  - Priority  
  - Platform  

#### 5. Agentic Action Layer
- Uses tool-calling agents to:
  - Create tasks  
  - Trigger workflows  
  - Schedule follow-ups  

#### 6. Insights Engine
- Generates summaries and behavioral analytics

---

## ⚙️ Tech Stack

- **Models:** TinyLlama (lightweight inference), LLM APIs  
- **Speech:** Whisper  
- **Backend:** AWS Lambda, API Gateway  
- **Storage:** DynamoDB (text + metadata)  
- **Agents:** Tool-calling agents (CrewAI-style architecture)  
- **Frontend:** React (Web MVP), React Native (planned)  
- **Integrations (planned):** Notion, Slack, Calendar  

---

## ⚠️ Challenges

- **Noisy Input → Structured Output**  
  Extracting reliable tasks from ambiguous, unstructured data  

- **Error Propagation**  
  Small extraction errors can lead to incorrect downstream actions  

- **Agent Decision-Making**  
  Determining when and how to trigger tools safely  

---

## 🚀 Future Work

- Replace mock APIs with production integrations  
- Expand agent capabilities with more tool integrations  
- Add personalization and user behavior modeling  
- Scale to pilot users and measure extraction accuracy  
- Transition fully to mobile-first experience  

---

## 🎯 Impact

MindFlow shifts task management from:
> manual organization → intelligent execution  

By introducing an agentic layer, it reduces cognitive overhead and ensures that important actions are captured, tracked, and completed reliably.


---

## 🔗 Links

- Slide Deck: [https://docs.google.com/presentation/d/1Cfi9O6H0a8_PBr30Xu4u9pQ_U1-kWCdWIpWyOCkQkm0/edit?usp=sharing]   

