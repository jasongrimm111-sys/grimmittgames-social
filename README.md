# social.grimmittgames.com

The sign-in page for Grimmitt Games' social posting. It holds no secrets: `vault.json` (created on first sign-in) is the
GitHub key locked with AES-GCM under a key derived from the owner's email and password (PBKDF2-SHA256, 600,000 rounds).
Everything else (videos, schedule, captions, posting) lives in the private `monkey-vine-rush-social` project.

`index.html` is a copy of `settings.html` from that project: edit it there and copy it here.
