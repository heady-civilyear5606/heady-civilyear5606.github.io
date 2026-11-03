# Rules for Claude Code in this project

## Always
- Read SPEC.md and PLAN.md before starting any work.
- Work on ONE milestone at a time (the first unchecked one in PLAN.md, or the one I name).
- Plan first: explain what you will do and which files you will create or change, then WAIT for my approval before editing any file.
- Explain each change in simple Arabic (I am a beginner). Code, file contents and commit messages stay in English.
- Never delete files or folders without asking me first.
- After finishing a milestone: test what can be tested, tell me exactly how to test it myself, update the checkboxes in PLAN.md, then make a git commit with a clear English message.
- If something fails twice, stop and explain the problem in simple Arabic instead of trying more fixes.

## Project rules
- Plain HTML + CSS only (tiny JavaScript only if really needed). No frameworks, no npm packages in the website, no build step.
- Website text is in English. Content must match SPEC.md exactly; do not invent extra text, numbers or claims about the company.
- Mobile-first. Test layouts at 320px and 375px widths.
- This project has no secrets. If a secret is ever needed, it goes only in a .env file listed in .gitignore and is never printed.
- Keep files small and well organized: index.html, styles.css, saeed-garfan.vcf, assets/, qr/.
