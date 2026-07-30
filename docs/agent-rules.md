# Agent Rules

## Required task record
Every task must state SIPOC, owner, deadline, estimated cost, expected value, acceptance criteria, evidence location, approval level, and one next action.

## Startup
Read `agent_state.json` and the active `task_board.json` item before any change.

## Scope
Do not modify files outside the active task scope. Record assumptions; when a required input is missing, mark the task `blocked` instead of guessing.

## Approval
Require owner approval before external communication, purchases, price commitments, sensitive-data disclosure, destructive actions, or new runtime dependencies.

## Definition of done
A task is complete only when its acceptance criteria pass, output and evidence are stored, and the handoff packet is complete.
