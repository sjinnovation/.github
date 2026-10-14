## What changed
<!-- One or two lines in plain words. Paste the AI delivery summary if you have it. -->


**Ticket:** <!-- ActiveCollab / Dev Control Tower task link -->
**AI-assisted:** <!-- Yes (Cursor / Claude / Lovable) or No -->

## How I tested it
<!-- Steps you ran and what you checked: happy path, empty input, wrong input, no permission. -->


## Screenshots / Loom
<!-- Required for UI changes. Mobile: TestFlight / build link. -->


## Standards checklist
<!-- Tick every box ([x]). The merge stays blocked until all are ticked. -->
- [ ] I can explain every line in this PR, including AI-generated code
- [ ] Follows the architecture pattern in ARCHITECTURE.md (no logic in the wrong layer)
- [ ] No secrets, keys or personal data in code, logs or prompts (.env.example only)
- [ ] New Supabase tables have RLS and policies; schema changes are new migration files
- [ ] LLM calls run server-side (Edge Function) with a timeout and token limit
- [ ] Unit tests added or updated for new logic and passing
- [ ] PR is small and focused (aim for under ~400 changed lines)
- [ ] Branch is up to date with `develop` and conflicts are resolved
