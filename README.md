# Prompt Planner: A Proof of Concept for Automated Prompt Generation

The Prompt Planner is a proof of concept designed to demonstrate how large language models (LLMs) can be used to automatically generate effective prompts.

# It operates through a two-step process:

### Step 1) Information Collection:
The system begins by acting as an information collector, using LLMs to engage with users and gather necessary details based on a brief task description. This interaction is designed to build a comprehensive understanding of the task at hand.

### Step 2) Prompt Planning:
Once the detailed task description is established from the user’s inputs, this information is fed into the prompt planner. The planner then constructs a tailored prompt, optimized to instruct another LLM to produce outputs in specific formats like JSON or markdown, based on the detailed task description.


This agentic approach leverages multiple LLMs that pass information to one another, refining the process of prompt engineering to meet user expectations efficiently. The dynamically changing inputs and the ability to optimize output formats make the Prompt Planner a decent starting point for people how doesnt know how to create an effective prompts based on given inputs and desired output requirements.
