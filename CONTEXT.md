# KUNA PATISSERIE — AI PROJECT CONTEXT

## Purpose

This file records the current implementation state for AI coding agents.

It is NOT a source of business requirements. PRD.md remains authoritative.

## Current project state

- Laravel project has been initialized and is running successfully.
- PHP CLI version: 8.5.4.
- PHPUnit is working.
- Baseline test result: 2 tests passed, 2 assertions.
- Git branch: main.
- Working tree is clean.
- Repository is synchronized with origin/main.
- The project is currently at the Foundation stage.
- Financial domain functionality has not yet been implemented.
- Only the default Laravel example tests currently exist.
- Phase 1 — Foundation is the current implementation phase.

## Current implementation status:

- Authentication: Not implemented
- Accounts: Not implemented
- Menu Items: Not implemented
- Income: Not implemented
- Expenses: Not implemented
- Payment Confirmation: Not implemented
- Cancellation: Not implemented
- Editing: Not implemented
- Transfers: Not implemented
- Receivables: Not implemented
- Payables: Not implemented
- Loans: Not implemented
- Assets: Not implemented
- Dashboard: Not implemented
- Reports: Not implemented
- CSV Export: Not implemented
- Audit Trail: Not implemented
- Financial Tests: Not implemented

## Completed phases

- [ ] Phase 1 — Foundation
- [ ] Phase 2 — Accounts
- [ ] Phase 3 — Menu
- [ ] Phase 4 — Income and Expense
- [ ] Phase 5 — Payment Logic
- [ ] Phase 6 — Cancellation and Editing
- [ ] Phase 7 — Transfers
- [ ] Phase 8 — Loans, Receivables, Payables, Assets
- [ ] Phase 9 — Dashboard
- [ ] Phase 10 — Reports and CSV
- [ ] Phase 11 — Audit Trail
- [ ] Phase 12 — Stabilization

## Database:
- PRD specifies MySQL.
- .env.example uses DB_CONNECTION=mysql.
- Development database is provided by XAMPP.
- Database server reports MariaDB 10.4.32.
- WSL can connect to the database through 127.0.0.1:3306.
- Laravel successfully executed the initial migrations.

## Active task

None.

## Last verified tests

None yet.

## Known issues

- PRD.md specifies MySQL as the database.
- .env.example currently specifies SQLite.
- The active database configuration has not yet been verified.

## Important:

The current 2 passing tests are only Laravel default/example tests.
They do NOT provide financial correctness coverage.

No financial feature should be considered implemented until it is supported by the PRD, implementation, and appropriate tests.

## Decisions made during implementation

Record only implementation decisions that are consistent with PRD.md. If a decision changes a business requirement, update PRD.md explicitly instead of recording an override here.

## AI handoff notes

When finishing a task, update:
- current phase;
- completed task;
- files changed;
- tests run;
- invariant verification;
- known issues;
- next task.

Keep this file factual and concise.
