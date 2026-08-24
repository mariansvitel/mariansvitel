# Working Principles

These principles describe the standard I am practicing. They are expected to evolve
when evidence shows a better approach.

## 1. Evidence before claims

A technology badge is not evidence of competence. Prefer a reviewed commit, passing
test, resolved issue, documented decision, or reproducible demonstration.

## 2. Private by default, public by decision

Early experiments may contain weak assumptions, unclear licenses, unsafe data, or
unfinished security controls. Public visibility is a separate decision, not the
automatic result of finishing code.

## 3. Small, reversible changes

Use focused branches and pull requests. Keep unrelated work separate. A reviewer
should be able to understand the purpose, risk, and validation of a change.

## 4. Human accountability for AI

AI may summarize, classify, ask questions, or propose a next action. It must expose
uncertainty and safety signals. A human owns consequential decisions and external
changes.

## 5. Secrets stay outside Git

API keys, tokens, passwords, and private configuration belong in ignored local
environment files or an approved secret store. If a secret is exposed, revoke or
rotate it; deleting the visible line is not sufficient.

## 6. Test the failure modes

Include incomplete inputs, duplicates, adversarial instructions, sensitive-data
patterns, and boundary values. A polished happy path does not establish reliability.

## 7. Documentation is part of the system

Record why a choice was made, what was deliberately excluded, how it was verified,
and what would cause the decision to change.

## 8. Maintenance is a feature

Archive stale public work or clearly label its status. A small maintained catalog is
more useful than a large collection of abandoned repositories.
