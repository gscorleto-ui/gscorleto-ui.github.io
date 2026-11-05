# VinoTrust link pages

Public link pages only (no app code, no data):
- `/b/?u=<seal UID>` – opens a tapped NFC seal in the VinoTrust app
- `/p/?t=<token>` – bottle passport shared for sale (D-034); reads only `get_shared_passport` with the public Supabase key
- `/.well-known/apple-app-site-association` – Universal Links for the app (Team M6PLPF4WT8)

Source of truth: `VinoTrust/web/seal-links/` on the founder's Mac.
