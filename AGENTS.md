# AGENTS.md

This repository publishes release notes for ChemTrack & WasteTrack.

## File layout

- Save each release note as `docs/release-note-v<version>.md`.
- Put its screenshots and other supporting assets in `docs/v<version>/`. Use descriptive filenames and relative links from the release note.
- Keep the notes in plain Markdown so they render in GitHub and Markdown previews. Use headings, lists, and Markdown image syntax.

## Writing release notes

- Compare the target release with the previous release tag in the application repository. Use commit messages to find candidate changes, then verify the final behavior against the code or running app. Check the tagged contents for changes that were already released under a different commit.
- Group major changes by workflow. Put smaller user-visible changes in one **Other user-facing changes** list and avoid repeating the highlights.
- Use the labels people see in the app. Explain what changed, who is affected, and any material conditions or limitations. Include administrative changes when they affect how someone manages the system.
- Keep internal refactoring and test-only changes out of the release note. Describe deployment status only when it has been verified.

## Screenshots and verification

- Capture major UI changes in the relevant build. Show the control, result, or panel discussed in the note, and use alt text that describes it.
- Use sample data or crop out personal information and internal identifiers before publishing. Keep enough surrounding UI for readers to recognize the screen.
- Use one representative screenshot when multiple reports show the same footnote. Recapture it when the wording changes.
- Check that every image link resolves and that the screenshots show the behavior described. Keep each release's supporting assets with its note.
