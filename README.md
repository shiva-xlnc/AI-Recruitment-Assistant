# AI Recruitment Assistant using LangGraph & Groq

## Overview

This project automates candidate screening using a multi-agent workflow built with LangGraph and Llama 3.3 (Groq API).

The system evaluates job applications based on:

* Experience Level
* Skill Match
* Recruitment Decision

and routes candidates through different hiring stages.

## Workflow

1. Experience Classification Agent
2. Skill Assessment Agent
3. HR Interview Scheduling Agent
4. Recruiter Escalation Agent
5. Application Rejection Agent

## Tech Stack

* Python
* LangGraph
* LangChain
* Groq API
* Llama 3.3 70B
* Google Colab

## Workflow Diagram

START → Experience Agent → Skill Agent → Decision Router

Decision Router:

* Match → HR Interview
* Senior + No Match → Recruiter Review
* No Match → Reject

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

## Sample Output

Candidate:
10 years experience in Java

Output:

Experience Level: Senior-level
Skill Match: No Match
Decision: Escalate to Recruiter

```
```
