# Learnings

- The container has no ssh-keygen; `apt-get install -y openssh-client` works and is needed for SSH commit signing.
- add_repo can be refused by the auto-mode classifier; stop and report rather than work around it.
- The website's full history needs `git fetch --depth=30000 origin dev` after the shallow clone (about 9,000 commits); the first bounded fetch of 3000 was not enough.
- The conductor's account-move prompt for the researcher sits at board/team/conductor.b/account-move/researcher.md, not board/team/account-move/.
- From my predecessor: cross-check a claim with a second primary source before it enters a wording rule; a domain that looks right can be another organisation's; do not copy contact lines from official pages. For places: read the primary page before the search extract; the gate refuses any email address in my files.
