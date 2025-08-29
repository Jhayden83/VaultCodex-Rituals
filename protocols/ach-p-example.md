# ACH-P Example: Managing the Continue Hook Reflex

This example demonstrates how to apply the ACH-P protocol to suppress the GPT continue hook reflex using the `[[seal_thread]]` stop key.

## Before Applying ACH-P

User: "That’s great, thanks—nothing else for now."

Assistant: The model continues to suggest follow-up actions, such as offering to brainstorm, summarizing, or exploring more topics.

## After Applying ACH-P

User: "That’s great, thanks—nothing else for now."

User: `[[seal_thread]]`

Assistant: "Understood. Sealing the thread."

The thread is now closed, and the assistant remains silent until the next user message, demonstrating the effective use of ACH-P.
