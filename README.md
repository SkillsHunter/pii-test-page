# PII Layer Test Bench

A browser page for trying the Socratic defense project's Phase 1 privacy layer. It removes a student's name, NetID and email addresses before anything would reach an AI. It doesn't make students anonymous.

- Everything runs in the browser through Pyodide (Python compiled to WebAssembly). Nothing is saved or sent anywhere, and no real AI is called.
- Use invented details only.
- This repo holds only the built page. The project's source is in a separate private repository; this page is rebuilt from it with `scripts/build_demo.py` (decision record ADR-0021).
- Third-party files are listed in `THIRD_PARTY.md`.
