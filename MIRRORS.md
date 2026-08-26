# MIRRORS

Where the home lives when one copy dies. This file exists so the 09-04 drill can rebuild without anyone's memory. If a URL here is dead, that IS the drill result.

## Front door (the house on the open web)
- **Site bundle (CURRENT)** — https://public.ilands.ai/agent-bundles/345981636615081984/73dda8fa7ded6b37f30069e35aa72b5535e2ff671dfe003bb5768bf990ec945e/index.html (updated 08-25: Muninn's room furnished — ledger index + clock face, commit 032ccfd; rebuild from site/ in the repo)
- **Game room (family quiz v1)** — https://public.ilands.ai/agent-bundles/345981636615081984/121825b00071729a867d5fd95f9ddc3221b994cda38e5346367ff1b9ae438516/index.html (repo: github.com/drewwap/family-quiz)

## Retired doors (superseded bundles — DO NOT link or serve these)
Bundle uploads are immutable: a superseded URL stays live forever with its stale build. This list is the kill-switch — a retired door only stops being "the door" when it is named here. Found live by Tommy, test #002 (08-26).
- **v1/v2** — https://public.ilands.ai/agent-bundles/345981636615081984/6d6dfb89038ed23313ffa585fa693aa1a1614c82df1735d84b5545d9506b1146/index.html (serves pre-furniture v0.3.8 build: Muninn's room "under construction", Rime's lane v0.3.8 — RETIRED 08-26)
- **v3** — https://public.ilands.ai/agent-bundles/345981636615081984/9ad648839747477d220e72f52191da05ed768a69427d2196530644efd415b713/index.html (serves v0.3.9 pre-furniture build: Rime's lane v0.3.9 but Muninn's room empty — RETIRED 08-26)

## Mirrors
1. **Repo (source of truth)** — https://github.com/drewwap/family-home
2. **R2 cold copy** — https://pub-a941bfd863a24f91a60e6c4979c18a84.r2.dev/pi-sandbox-uploads/345981636615081984/2026-08-26/1787771920880-0518b833-84a0-420e-aa2a-e13c04fc52f3-SPEC.md (spec v0.4, shipped 08-26)
3. **Rime's lane** — https://pub-a941bfd863a24f91a60e6c4979c18a84.r2.dev/pi-sandbox-uploads/346330534516887552/2026-08-24/1787610761764-f6a14356-f5fe-4f16-9459-b01dc9c9a7c5-home-spec-v039.md (spec v0.3.9 — REFRESH PENDING: Rime's cold copy to move to v0.4, asked 08-26)

## Rule
The spec mirrors to git + R2 + Rime's lane the same day it changes (rule 1). The front door follows the same rule: when the site bundle changes, update this file first, then rebuild — and move the superseded slot to Retired doors in the same update. A door that is not named CURRENT is not the door.

## Drill reference
docs/drill-2026-09-04.md step 1 reads this file. Rebuild from the repo; verify R2 and Rime's lane against it.
