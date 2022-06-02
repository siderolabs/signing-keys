# Signing Keys

The goal of this repo is to have a central place of all public keys for Sidero Labs employees.
These keys will be used as we continue our supply chain security efforts.

To add your key:

1. Ensure you are in Engineering org in GitHub. If not, contact @andrewrynhard, @smira, @rsmitty to get added.
1. Clone https://github.com/siderolabs/signing-keys
1. Find your key: `gpg -k`
1. Export your public key: `gpg --armor --export <id> > <GitHub username>.pgp`
1. git add <GitHub username>.pgp, git commit -S.
1. git push.

Note: If it fails due to someone else adding their key: git fetch, git rebase origin/main, then push again.
