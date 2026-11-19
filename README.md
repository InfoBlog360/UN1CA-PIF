# UN1CA PIF configuration

This public repository hosts a JSON configuration consumed by the Play Integrity Fix settings in the private `InfoBlog360/UN1CA-fourteen` firmware project.

- Public endpoint: `https://raw.githubusercontent.com/InfoBlog360/UN1CA-PIF/main/pif/pif.json`
- `pif/pif.json` is an independently maintained **snapshot**, initially copied from the publicly accessible `salvogiangri/UN1CA` `main` branch on 2026-11-19, original `VERSION` `20250618`.
- **No automatic synchronization or runtime dependency** on the original developer. To change the served configuration, explicitly update this repository.
- Do not store tokens, private keys, or other secrets here: the JSON is publicly accessible.
- The original snapshot may be obsolete and does not guarantee a successful Play Integrity verdict. Check compatibility before relying on it.
- Attribution for original upstream: https://github.com/salvogiangri/UN1CA (original code and credits retained in the main firmware project).

The firmware source remains private; only this non-secret configuration is public.
