# kernel_chat

## Why it matters

Cloud chats can reason over a rich conversation but normally do not own the
durable project workspace available to a local application or agentic coding
system. When a conversation ends, project state, source relationships, useful
competence and unfinished work can become expensive to reconstruct.

`kernel_chat` extends that project harness into cloud chats and small
conversational systems through a portable kernel, a host adapter and a
user-owned persistence surface.

## What exists

Version 0.4.0 is a public, installable first integrated release. It includes:

- present-first work and selective source-aware reentry;
- compact user-owned current state and source pointers;
- situated competence and metacompetence participation;
- FDLA self-observation when the acting interpretation narrows the field;
- optional unfinished-work continuity and recovery receipts;
- reversible evolution from observed reusable differences;
- a ChatGPT Custom Instructions adapter;
- a GitHub persistence adapter and dependency-free configurator/validator.

Repository: https://github.com/GrazianoGuiducci/kernel_chat

MAIOS product page: https://maios.it/conversation-kernel.html

## Architecture boundary

```text
current conversation
        ↓ when a durable relation is missing
portable kernel
        ↓
host adapter + user-owned state + persistence adapter
        ↓
relevant source / competence / unfinished work
        ↓
current result and reviewable delta
```

ChatGPT is the first implemented host adapter and GitHub the first persistence
adapter. Neither is the identity or future limit of the kernel.

`kernel_chat` remains distinct from:

- **Project Kernel**, the situated operating form owned by one project;
- **RepoKernel**, the generative metakernel that composes Project Kernel
  structures;
- the private ChatGPT host kernel from which some relations were learned.

The package does not simulate a daemon, scheduler or autonomous worker. It
does not manufacture connector access, host capability or authority over an
external effect.

## Evidence and maturity

| Dimension | Current evidence |
| --- | --- |
| Public source | repository and tagged release 0.4.0 |
| Package structure | validator, adapter, kernel, state and documentation |
| First host adapter | ChatGPT Custom Instructions |
| First persistence adapter | GitHub repository controlled by the user |
| Real-use assimilation | open; must emerge from continued use |
| Second-host portability | open; requires a host-native adapter and observed use |
| Autonomous background execution | not implemented and not claimed |

## Portfolio role

`kernel_chat` is the primary conversational-kernel surface in the current
portfolio. It makes the continuity and competence architecture available to a
chat host without pretending that the chat is a local agent runtime.
