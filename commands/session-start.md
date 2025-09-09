# Start Coding Session

I'll begin a documented coding session using Claude Code CLI's memory system.

Let me first check the content of the CLAUDE.md file for project information.

I'll integrate with the native memory system by updating CLAUDE.md:


Let me check for existing memory files and update them appropriately:
- Project memory (./CLAUDE_PROGRESS.md) for documenting the project progress
    - Session timestamp and context
    - Current git state and branch
    - Session goals and objectives
    - Progress tracking throughout our work
- Bugfix memory (./CLAUDE_FIX.md) for documenting bugfixes

Please tell me:
1. What are we working on today?
2. What specific goals do you want to accomplish?
3. Any context I should know about?

I'll add this session context to your memory system using the `/memory` command functionality, ensuring our progress is tracked and can be resumed later. This integrates seamlessly with Claude Code CLI's native memory management rather than creating a separate system.

**Important**: I will NEVER:
- Add "Co-authored-by" or any Claude signatures
- Include "Generated with Claude Code" or similar messages
- Update the CLAUDE.md file
- Modify git config or user credentials
- Add any AI/assistant attribution to the commit

The session context will be preserved in the appropriate CLAUDE.md file for future reference and continuation.