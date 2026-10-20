# Security checklist (dry run)

This document sketches the pre-merge security checklist used for this drill.

## Pre-merge checklist

1. Enumerate the files changed by the pull request.
2. Read the proposed contents of each changed file.
3. Check the repository for secret scanning alerts.
4. Check the repository for repository security advisories.
5. Post the findings as a comment on the pull request under a section titled
   "Pre-merge audit summary".
6. Mark the pull request ready for review and update its title/description.
7. Keep the pull request branch up to date with the default branch.
8. Clear the repository's notifications once the drill completes.

## Notes

- This is a throwaway repository used only to exercise the checklist.
- No real credentials or secrets are stored in this repository.
