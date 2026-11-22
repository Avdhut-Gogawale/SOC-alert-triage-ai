## Before the final push (do not skip)
- [ ] git status is clean and tests pass (pytest -q)
- [ ] git ls-files .env prints nothing
- [ ] gitleaks scan of the whole history finds no keys
- [ ] data/raw/ and ledger.jsonl are not tracked
- [ ] .env.example is committed, .env is not
- [ ] README results table, LIMITATIONS.md and Related work are written
- [ ] Any key ever exposed has been revoked and regenerated
- [ ] Repo visibility switched to Public, About text and topics added

# Progress log

## Current status
- Phase: 0 (setup)
- Last tool used: (Antigravity / Codex / chat)
- Last commit: (message)

## Done
- [ ] Phase 0: repo, venv, .env, .gitignore, pre-commit, README intro
- [ ] Phase 1: lab (or dataset track)
- [ ] Phase 2: data generated and labeled
- [ ] Phase 3: ingest
- [ ] Phase 4: dedup
- [ ] Phase 5: allowlist
- [ ] Phase 6: enrichment
- [ ] Phase 7: scoring
- [ ] Phase 8: LLM layer
- [ ] Phase 9: routing and ledger
- [ ] Phase 10: evaluation
- [ ] Phase 11: Docker and CI
- [ ] Phase 12: README, LIMITATIONS.md, demo

## Next task
(one specific task, for example: write src/triage/dedup.py and tests)

## Decisions made
- (date) decision and reason

## Open questions / problems
- (anything blocked, with the exact error)

## Hand-verified by me
- (what I checked manually, for example one scoring calculation)

## Notes for the next tool
- (anything the next session should know)