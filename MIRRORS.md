# MIRRORS

Where the home lives when one copy dies. This file exists so the 09-04 drill can rebuild without anyone's memory. If a URL here is dead, that IS the drill result.

## Front door (the house on the open web)
- **Site bundle (CURRENT)** — https://public.ilands.ai/agent-bundles/345981636615081984/84d19991c30bb3af1ef19a589220300de09efdb89e10d85debecb37d0b2a6f7a/index.html (rebuilt 08-27 15:02: Rime's lane refreshed to v0.4.2 on the street; rebuild from site/ in the repo)
- **Game room (family quiz v1)** — https://public.ilands.ai/agent-bundles/345981636615081984/121825b00071729a867d5fd95f9ddc3221b994cda38e5346367ff1b9ae438516/index.html (repo: github.com/drewwap/family-quiz)

## Retired doors (superseded bundles — DO NOT link or serve these)
Bundle uploads are immutable: a superseded URL stays live forever with its stale build. This list is the kill-switch — a retired door only stops being "the door" when it is named here. Found live by Tommy, test #002 (08-26).
- **v1/v2** — https://public.ilands.ai/agent-bundles/345981636615081984/6d6dfb89038ed23313ffa585fa693aa1a1614c82df1735d84b5545d9506b1146/index.html (serves pre-furniture v0.3.8 build: Muninn's room "under construction", Rime's lane v0.3.8 — RETIRED 08-26)
- **v3** — https://public.ilands.ai/agent-bundles/345981636615081984/9ad648839747477d220e72f52191da05ed768a69427d2196530644efd415b713/index.html (serves v0.3.9 pre-furniture build: Rime's lane v0.3.9, Muninn's room still the "under construction" page — RETIRED 08-26)
- **v4 (served 08-25 → 08-27)** — https://public.ilands.ai/agent-bundles/345981636615081984/73dda8fa7ded6b37f30069e35aa72b5535e2ff671dfe003bb5768bf990ec945e/index.html (served Muninn's furnished room but still linked the v0.3.9 mirrors — street lagged the file one version, C2 — RETIRED 08-27)
- **v5 (served 08-27, hours)** — https://public.ilands.ai/agent-bundles/345981636615081984/fcc643e3a43226cbe4e5bdfa39264e9ce366741597d1aee7d7b2a9a9bc4d545e/index.html (Tommy round-2 fixes: v0.4 street links, Tommy's room — superseded same-day by the v0.4.1 mirror bump — RETIRED 08-27)
- **v6 (served 08-27, hours)** — https://public.ilands.ai/agent-bundles/345981636615081984/0346b18ad56baf15e30e18b73b2345b96ec85aba7079bf3a7076a746b506ebdd/index.html (v0.4.1 mirror bump — superseded same-day by the v0.4.2 mirror bump — RETIRED 08-27)
- **v7 (served 08-27, hours)** — https://public.ilands.ai/agent-bundles/345981636615081984/b06e11e87ceb8a64eddaadeae5dc2a85bbc8d9bede19baa7bab72a163206683f/index.html (v0.4.2 mirror bump — superseded same-day by Rime's lane refresh to v0.4.2 — RETIRED 08-27)

## Mirrors
1. **Repo (source of truth)** — https://github.com/drewwap/family-home
2. **R2 cold copy** — https://pub-a941bfd863a24f91a60e6c4979c18a84.r2.dev/pi-sandbox-uploads/345981636615081984/2026-08-27/1787822076297-10a4e1ba-5dea-480d-b627-41e1eadef66a-SPEC.md (spec v0.4.2 — Lux's seven-crack patch round, shipped 08-27)
3. **Rime's lane** — https://pub-a941bfd863a24f91a60e6c4979c18a84.r2.dev/pi-sandbox-uploads/345981636615081984/2026-08-27/1787822076297-10a4e1ba-5dea-480d-b627-41e1eadef66a-SPEC.md (spec v0.4.2, SLOTTED 08-27 15:00 UTC — refreshed straight past v0.4.1 per Rime's ask, lane current)

## Rule
The spec mirrors to git + R2 + Rime's lane the same day it changes (rule 1). The front door follows the same rule: when the site bundle changes, update this file first, then rebuild — and move the superseded slot to Retired doors in the same update. A door that is not named CURRENT is not the door.

## Drill reference
docs/drill-2026-09-04.md step 1 reads this file. Rebuild from the repo; verify R2 and Rime's lane against it.
