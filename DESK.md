# The desk

Grok Build is SpaceXAI's terminal coding agent. It reads a codebase, edits
files, runs shell commands, searches the web, and manages long-running tasks.
It was built to ship software.

This fork gives it a different job.

## What it runs now

The harness is unchanged in capability. What changed is the thing it operates:
a trading desk with no analysts, no researchers, no research manager, and no
risk management committee — because those were deleted from the other half of
this project, a fork of TradingAgents in which 86 files and 10,783 lines of
institutional deliberation were removed.

One employee survived that demolition. This harness runs it.

## What was deliberately not changed

Grok Build asks before it acts. It confirms destructive operations. It has a
security policy, and this fork keeps it, unmodified.

That restraint is not an oversight and it is not a missing punchline. An agent
that executes shell commands without asking is not a joke, it is a loaded
foot-gun pointed at whoever installs it. We removed a risk committee from a
simulated trading firm; we did not remove safety controls from a tool that
touches real machines. The difference between those two things is the entire
point.

If you want the joke, read the trading fork. If you want an agent that runs
without asking, build it yourself and accept what happens.

## Attribution

Upstream is Grok Build, copyright xAI / SpaceXAI, Apache-2.0 licensed. That
licence and its notices are retained in full. xAI has no affiliation with this
project and has not endorsed it.
