# Party Sheet · DM chat

The DM's side of the private chat in the Party Sheet app. A player shares a link to this page and a PIN;
the DM enters their name and the PIN, and the player allows them in.

Messages are encrypted in the browser (AES-GCM, key derived from the PIN) and relayed through ntfy.sh, so the
relay only sees scrambled text. This repo holds only this static page: no keys, accounts or personal data.
