# Multi-agent App with ADK, Agent Engine and AlloyDB

### Overview
An agent is an autonomous program that talks to an AI model to perform a goal-based operation using the tools and context it has and is capable of autonomous decision making grounded in truth!

When your application has multiple agents working together autonomously and together as required to cater to its larger purpose with each of its agents being independently knowledgeable and responsible for a specific focus area, then your application becomes a multi-agent system.

**The Agent Development Kit (ADK)**

Agent Development Kit (ADK) is a flexible and modular framework for developing and deploying AI agents. ADK supports building sophisticated applications by composing multiple, distinct agent instances into a Multi-Agent System (MAS).

In ADK, a multi-agent system is an application where different agents, often forming a hierarchy, collaborate or coordinate to achieve a larger goal. Structuring your application this way offers significant advantages, including enhanced modularity, specialization, reusability, maintainability, and the ability to define structured control flows using dedicated workflow agents.

### Things to keep in mind for a multi-agent system
**First**, It's important to have a proper understanding and reasoning of the specialization for each agent. — "do you know why you need a specific sub-agent for something", work that out first.

**Second**, How to bring them together with a root agent to route and make sense of each of the responses.

**Third**, There are multiple types of agent routing that you can find here in this documentation. Make sure which one suits your application's flow. Also what are the various contexts and states that you need for your multi-agent system's flow control.

### What you'll build
Let's build a multi-agent system to handle kitchen renovations. That's what we'll do. We'll build a system with 3 agents.

1. Renovation Proposal Agent
2. Permits and Compliance Check Agent
3. Order Status Check Agent

Renovation Proposal Agent, to generate the kitchen renovation proposal document.

Permits and Compliance Agent, to take care of permits and compliance related tasks.

Order Status Check Agent, to check order status of materials by working on the order management database that we have set up in AlloyDB.

We'll have a root agent that orchestrates these agents based on the requirement.

### Requirements
* A browser, such as Chrome or Firefox
* A Google Cloud project with billing enabled.
