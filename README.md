
# Campus Insights Agent — Kaggle Capstone

This zip contains:
- agents.py
- sample_data.csv
- notebook.ipynb
- README.md
- ## 🎥 Demo Video
Watch the demo here: <https://youtu.be/Zohg8gvjBxc>
## 📸 Screenshots
![Demo](project.png)
## 📝 Project Description
(### Problem Statement

Students in colleges and universities often struggle with managing academics, deadlines, campus processes, and emotional well-being. They need quick and reliable answers about study plans, exams, fees, certificates, hostel rules, and sometimes motivation when overwhelmed. However, real-time help is limited—faculty are busy, administrative offices have fixed hours, and students hesitate to ask for help repeatedly.

The problem becomes even more important because poor academic planning, stress, and lack of clarity directly lead to lower performance and burnout. Existing chatbots are usually rule-based, rigid, and cannot handle personalized multi-step tasks.

The challenge is to build a system that can act as a 24/7 personal assistant for students—guiding them academically, emotionally, and administratively.

### Why Agents?

Traditional single-model chatbots fail when tasks require:

Multiple domain-specific skills

Routing queries to correct specialists

Long, contextual conversations

Personalized planning

Combining multiple types of answers into one result

Agents solve this because:

✔ Specialized Roles

Different agents handle academics, well-being, and campus admin—each optimized for its task.

✔ Autonomous Routing

A Query Understanding Agent classifies the user’s intent and forwards the request to the right expert.

✔ Collaboration

A central Orchestrator merges responses when a student needs multi-domain help (e.g., study + routine + motivational support).

✔ Scalable

New agents can be added anytime (Placement Agent, Finance Agent, etc.).

✔ Reliable

Each agent uses structured reasoning, tools, and memory, which makes the system consistent.

In short, agents allow us to replicate a real “Student Help Desk” using coordinated AI specialists, not one overloaded model.

### What You Created (Architecture Overview)

I built the Campus Insights Agent, a multi-agent system designed to assist students across three major domains:

1. Query Understanding Agent

Detects intent

Routes query correctly

Handles ambiguous messages

2. Academic Support Agent

Generates exam study plans

Explains concepts

Creates notes

Breaks tasks into manageable chunks

3. Well-being & Motivation Agent

Provides stress management tips

Motivation guidance

Balanced routines

Safe emotional support

4. Campus Information Agent

Fees

Documents (bonafide, ID card, etc.)

Hostel rules

Event information

5. Multi-Agent Orchestrator

Receives student input

Calls the correct agent(s)

Merges, formats, and refines final output

Ensures tone + clarity + accuracy

System Architecture (Simplified)
Student Input
     |
     v
+---------------------------+
| Query Understanding Agent |
+---------------------------+
     |
     v
---------------------------------------------
| Academic Agent | Well-being Agent | Campus Agent |
---------------------------------------------
     |
     v
+---------------------------+
| Multi-Agent Orchestrator |
+---------------------------+
     |
     v
Final Student Response

### Demo (How It Works for the Student)

Here are real examples demonstrating the system:

Student Query 1:

"Make a 5-day study plan for DBMS and OS."
✔ Query routed to Academic Agent
✔ Agent generates day-wise plan
✔ Orchestrator formats clean output

Student Query 2:

"I am stressed about my assignments."
✔ Routed to Well-being Agent
✔ Supportive, safe, motivational response
✔ Time-management strategies added

Student Query 3:

"How do I apply for a bonafide certificate?"
✔ Routed to Campus Info Agent
✔ Step-by-step process shared

Student Query 4:

"Plan my full week with studies, gym, and hostel tasks."
✔ Multiple agents collaborate
✔ Orchestrator merges into one weekly routine

This demo flow shows how students receive instant, personalized, structured, and helpful guidance in real time.

### The Build (Tools & Technologies Used)
Languages & APIs

Python

Google Gemini Agents API

Gemini 1.5 Flash & Pro

Python agent framework + orchestration engine

Key Techniques

Intent detection

Tool-enabled agents

Multi-agent routing

Structured output generation

Memory-based conversation chaining

Centralized orchestration

Development Workflow

Defined roles and capabilities for each agent

Implemented intent classifier in Query Agent

Built Academic, Wellness, and Campus agents with structured outputs

Implemented the Orchestrator for combining responses

Tested with real student scenarios

Packaged into both:

a Python backend

a Kaggle demo notebook

GitHub repository

This project demonstrates real-world application of multi-agent architecture beyond simple chat responses—showing autonomy, reasoning, and collaboration.

### If I Had More Time, This Is What I’d Do
1. Add More Agents

Placement Agent (resume review + job matching)

Financial Aid Agent

Fitness & Habit Agent

2. Add Voice Interface

Speech-to-text

Text-to-speech

Hands-free interaction

3. Real Campus Database Integration

To answer:

Real-time fees

Class schedules

Available staff office hours

4. Add a Student Dashboard

Daily tasks

Analytics

Personalized learning patterns

5. Deploy as a Web App / Mobile App

With authentication + saved profiles.)




Upload these to Kaggle Notebook to run your agent.
