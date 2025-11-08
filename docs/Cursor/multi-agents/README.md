# # Step-by-step guide

1. Open Cursor and your project: Launch Cursor and open the project you want to work on.

2. Create your first agent: Click the "New agent" button in the main interface and enter a clear, single task for it to perform. For example, "Generate a backend API endpoint for projects".
   Create your first agent: Click the "New agent" button in the main interface and enter a clear, single task for it to perform. For example, "Generate a backend API endpoint for projects".

3. Create additional agents: Create more agents for different tasks to run in parallel.
   Example 1: Create a second agent with the task, "Create unit tests for the new endpoint".
   Example 2: Create a third agent to handle a different part of the application, like "Change the project's color scheme to green and black".

4. Review results: Wait for the agents to complete their tasks. You will see their progress, and once finished, you can review their proposed changes.

5. Iterate: You can provide feedback to a specific agent by pasting errors or asking for improvements within that agent's thread, maintaining continuity for a specific task

## Key concepts

- Parallel execution: Cursor runs multiple agents simultaneously, each in its own isolated copy of your codebase using techniques like git worktrees, to prevent conflicts.

- Role-based prompting: Think of each agent as an employee with a specific role, like a "backend developer," "tester," or "documenter." You define the role by giving the agent a clear task.

- Focus on outcomes: The interface is designed to focus on project outcomes rather than individual files. You direct what needs to be done, and the agents handle the implementation details.
