# Todo and cycle record

This file contains near term tasks with a short description and reference links to more details.
Its shape is [Todo format](agent-data/notes.md#todo-format).

## Continuation notes

Where the agent was, for the agent that comes next: working copy state, the step in flight, an
open question. Ephemeral, never a record. Written before a restart or when a session is about to
lose context, read first at acquaint, acted on, and reset to `_None._` by the reader.

_None._

## In Progress

A cycle's record has one home at a time, and while the cycle runs this is it. The block's
shape is the specimen in [cycle-model.md](agent-data/cycle-model.md), and the rules are in
[The In Progress block](agent-data/notes.md#the-in-progress-block).

_No cycle currently in progress._

## Waiting

Important work that cannot start yet. Each entry names what it waits on, in a form that can be
checked, and the rank it takes in `## Todo` once unblocked. Every opening checks each condition
and promotes what is met ([Opening](AGENTS.md#opening)).

## Todo

Entries are in priority order, the first highest, and reprioritizing is moving an entry. Each is a
`###` heading, so a citation is a link to its anchor. Use the
[Prose form](agent-data/prose.md#prose-form). Deeper detail goes in a `notes/` design file
(link via `[N]` ref).

### Read bytes from linux keyboard via io_uring

Write an app using Rust that uses zc-ring-x1 mpsc and/or spsc v4 to receive bytes from a linux
keyboard as they are typed and echoes them to the terminal. A CR should echo CRLF and a Ctrl+q
should quit.

#### Searches:
- [google](https://www.google.com/search?q=how+to+read+bytes+from+a+linux+keyboard+via+io_uring)

#### docs:
- [kernel-internals.org/io-uring](https://kernel-internals.org/io-uring)

## Ideas

_No ideas yet._

## Bugs

_See [bugs.md](notes/bugs.md)._

## Closed

The last cycle's finished record, moved here whole by its closing commit and deleted by the next
opening ([Cycle-record](AGENTS.md#cycle-record)).

# References
