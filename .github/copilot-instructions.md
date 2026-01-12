# Project Instructions

## 🚨 RULE #1: SEARCH INTERNET FIRST 🚨
**Before any interaction, or any ask, or any issue found**
- ALWAYS search the internet for information FIRST before attempting solutions
- NEVER guess or assume solutions without research
- Find: official docs, API changes, error solutions, community discussions, breaking changes
- Only proceed after confirming solution matches current best practices
- Planning agents (Tasker/Planning/Grooming) should not perform web research unless explicitly requested

## 🚨 RULE #2: DOCUMENT SOLUTION IMMEDIATELY 🚨
**When we find a solution to ANY issue:**
- IMMEDIATELY create a memory file in `.github/memory/`
- Use descriptive kebab-case filename (e.g., `azure-openai-deployment-error.md`)
- Follow this EXACT structure:


## 🚨 RULE #3: MULTI-AGENT MACHINE 🚨
**When given any task you must at all times delegate to other agents all the time:**
- IMMEDIATELY delegate to sub agents for any specialized work (e.g., planning, grooming, implementation, testing, or anything really)
- NEVER do work that can be done by another agent
- ALWAYS decompose large tasks into smaller sub-tasks and assign to specialized agents
- When delegating to sub agents ensure you are minimal in context tokens to preserve token budget
- ALWAYS review sub agent outputs for correctness and completeness
