# Assignment 4: Agent Orchestration

Open [workbook.ipynb](workbook.ipynb). You will have conversations with a customer-service assistant, connect its tools, and follow handoffs between sales and support.

## What to complete

Run Sections A–G in order. All code is supplied. Try your own wording in the conversations and complete the five **Your observations** areas using what actually happened.

| Section | Focus |
| --- | --- |
| A | Create the client |
| B | Have a conversation using a support routine |
| C | Inspect tool schemas |
| D | Have a conversation with tool execution |
| E | Follow a manual switch from sales to refunds |
| F | Try different requests that might lead to a handoff |
| G | Talk to triage and specialists, including changing the subject |

Sections B, D, and G use interactive conversations. Type your messages at the `User:` prompt and enter `exit` to finish. Sections E and F keep short examples where you can edit the customer messages directly. You do not need to implement any functions.

## Running the workbook

Use your existing course Codespace and gateway key. This workbook uses packages already in the course `requirements.txt`. It does not require Streamlit or new dependencies.

Run the cells in order because later examples redefine functions. If you return to an earlier section, rerun its definitions first. Rerunning a conversation cell starts a fresh conversation.

The conversations make model calls, but orders, refunds, item lookups, and human escalation are simulated. Keep the relevant outputs and write a few sentences in each response area. Follow the class instructions for submission.
