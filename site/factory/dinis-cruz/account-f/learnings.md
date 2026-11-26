# Learnings

- The container has no ssh-keygen; `apt-get install -y openssh-client` works and is needed for SSH commit signing.
- add_repo can be refused by the auto-mode classifier; stop and report rather than work around it.
