# Agent ER — Agentic Recovery for Failing AI Agents

Agent ER is an AI-powered system designed to detect, diagnose, and recover from failures
in AI agents through autonomous investigation and controlled recovery.

## System Architecture
The system consists of three components:
- **Patient Agent:** A customer-support agent for a simulated online store.
- **Monitor:** Tracks four vital signs: task completion, tool efficiency, reliability, and security.
- **Doctor Agent:** Investigates failures using a six-step workflow:
  Observe → Hypothesize → Test → Fix → Verify → Decide.

The Doctor can apply configuration patches, verify recovery through conversation replay,
or escalate unresolved incidents to a human.

## Supported Failure Scenarios
- Tool Loop
- Schema Drift
- Prompt Injection
- Backend Outage

## Technologies
Python · OpenAI API · Google Colab · Gradio

## How to Run
1. Open the project notebook in Google Colab.
2. Add your OpenAI API key as a Colab Secret named `OpenAI_Key`.
3. Allow Google Drive access when prompted (results are saved to `MyDrive/agent_er/`).
4. Run the notebook cells to initialize the system.
5. Launch the Gradio interface.
6. Select a failure scenario and run the simulation.
7. Review the Monitor's vital signs, the Doctor's actions, and the final incident report.

**Note:** An OpenAI API key is required. 
