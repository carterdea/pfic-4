# Research Packet Maintenance

- Always create both Markdown and HTML files for each PFIC4 research packet document, including disease summaries and per-drug pages.
- Store Markdown files in `markdown/` and HTML files in `html/`.
- Use matching basenames for companion files, for example `markdown/livmarli-maralixibat.md` and `html/livmarli-maralixibat.html`.
- Treat Markdown as the agent-facing source to read first.
- Treat HTML as the human-facing version.
- Whenever Markdown content changes, update the matching HTML in the same change.
- Whenever HTML content changes, update the matching Markdown in the same change.
- Keep medical claims sourced and preserve the reviewed date when updating either format.
- Link related HTML pages together so human readers can navigate between the layperson guide, clinician brief, combined packet, and drug pages.
- Link each HTML page back to its Markdown companion in `../markdown/`.
- Link each Markdown page to its HTML companion in `../html/`.
- Keep patient/family-specific details out of repo-ready packet files.
- If private context is needed, put it only in `markdown/personal.md` and `html/personal.html`; those exact files are ignored by git.
