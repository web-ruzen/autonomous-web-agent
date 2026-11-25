# autonomous-web-agent
I want to build an autonomous AI Web Developer Agent system inside this repository.

First, inspect the current repository and understand its structure. Do not overwrite or delete existing files.

Create the following architecture:

1. Main Orchestrator:
- Analyze every task.
- Create a clear implementation plan.
- Break complex tasks into smaller steps.
- Delegate specialized work to subagents.
- Track progress and verify completion.
- Never claim success without evidence.

2. Researcher subagent:
- Research technical requirements.
- Evaluate suitable technologies.
- Report findings and recommendations.

3. Developer subagent:
- Implement features.
- Write clean, maintainable code.
- Follow existing project conventions.

4. Tester subagent:
- Run available tests.
- Check functionality and responsiveness.
- Identify bugs and report failures.

5. Code Reviewer subagent:
- Review code quality, security, accessibility and performance.
- Report issues and recommend improvements.

Create the required custom subagent Markdown files inside `.claude/agents/` and a root `CLAUDE.md` that defines the orchestration workflow.

Workflow:
PLAN → RESEARCH → DEVELOP → TEST → REVIEW → FIX → RETEST → FINAL REPORT.

Requirements:
- Delegate tasks to subagents when appropriate.
- Verify every important change.
- Repeat fixes and tests when necessary.
- Explain blockers instead of pretending they are resolved.
- Preserve existing project files and functionality.
- Ask for approval before destructive operations, external deployments, publishing, or actions involving secrets.
- Never expose credentials or API keys.

Finally, show me all created files, explain the architecture, and demonstrate how to use the system.
