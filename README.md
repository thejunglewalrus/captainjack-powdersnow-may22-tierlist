# Captain Jack &amp; Powdersnow — May 22, 2026 Joint Tier List (English)

English translation of the joint KR Lost Ark class tier list by **Captain Jack** (Thaemine The First &middot; Kazeros The Second) and **Powdersnow** (Kazeros The Third), posted to Inven on 2026-05-22.

- **Inven source:** https://www.inven.co.kr/board/lostark/6271/3682420 (post by 마러, 60,572 views, 47 recommends)
- **Agam recap:** https://youtu.be/j6JIShzNsHU?t=562 (English summary in his "May 3rd week hot topics" video — useful but has two errors: adds a phantom "Guardian Knight (spec)" in S, and skips the entire 몰라요 / "don't know" tier)

## Live site

https://thejunglewalrus.github.io/captainjack-powdersnow-may22-tierlist/

## What's in here

- `index.html` — embeds the source image and renders a clean translated tier table + decoder + translation notes
- `images/source-tierlist.png` — the original Inven image (1608×1638)

## Translation method

Every chip label in the source image is a class abbreviation + build slang (e.g., `소올 만월` = Souleater + Full Moon Harvester). The decoder table on the page lists every chip, the official KR build name from Loawa, and the official NA localization. Class / build names were verified against:

- Loawa rank taxonomy (https://loawa.com/rank), the gold-standard for KR build names
- The LPK-extracted Lost Ark game files (`~lostark_extracted/lostark_data.db`) for NA localization

One slang on this list — **강무** (Deadeye, S tier) — needed extra research. It's a carry-over slang from the pre-Ark-Passive engraving "강화된 무기" (Enhanced Weapon) → 강+무. After the Ark Passive launch, the build was renamed 전술 탄환 (Tactical Bullet) but the 강무 slang persists in active KR community use as of March 2026. Same Tactical Bullet build as 전탄 — not a separate variant.

## Local preview

```bash
python -m http.server 8000
# then visit http://localhost:8000
```
