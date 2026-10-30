# Tool Use: Letting an Agent Act

Chatting is useful. Acting is more useful. Tool use is what lets an agent do things in the world — look up information, run calculations, write drafts, move files — instead of only talking about them.

## What a tool is

A tool is a small, specific capability with a clear name and purpose. Examples:

- **Web search** — find current information online
- **Calculator** — do math reliably
- **Draft email** — write an email (but not send it without you)
- **Read file** — open a document on your computer
- **Write file** — save a document on your computer

## How an agent uses tools

The flow looks like this:

1. The agent sees a task ("Find flights under $300").
2. It picks a tool ("web search") and decides what to ask it.
3. The tool runs and returns a result.
4. The agent reads the result and decides the next step (search again, or move on).

The agent never touches your computer directly. The tool is the only thing that acts, and each tool does one narrow job.

## Human in the loop

Some actions should never happen automatically:

- Sending email or messages
- Spending money
- Deleting or changing records
- Posting publicly

For these, the agent drafts the action and asks you to approve it. You stay in control. The agent suggests; you decide.

## Start without code

You can practice tool use today with no computer at all. On your worksheet, list three tools your agent might need and write one sentence about what each one does and when you'd want to approve its use.

---

Published by **Asdale Dynamics, LLC**.
