# Offline Microtools

Two **single-file, offline-first** browser tools. Double-click the `.html` and
go — no build step, no server, no network, no dependencies, no tracking.

| Tool | File | What it does |
|------|------|--------------|
| **NeverLose v0.2** | `neverlose.html` | A loss-proof note collector. Every keystroke is saved to `localStorage` immediately; automatic versioned snapshots let you roll back; export to JSON / CSV / Markdown. Search, tags, sorting. |
| **Recall v0.1** | `recall.html` | A spaced-repetition flashcard app (SM-2). Decks, cards, tags, due-today queue, grading, JSON/CSV import/export. |

Both tools keep **all data on your machine** (browser `localStorage`). Nothing
is ever sent anywhere.

## Run

1. Download the file you want (or grab the packaged release assets below).
2. Double-click it in a modern desktop browser.
3. Start typing. NeverLose saves as you type; Recall schedules reviews.

Prefer a packaged copy? The `dist/` folder (and the release assets) contain
ready-to-run zips that are byte-for-byte identical to the single files.

## Integrity

Every frozen artifact is pinned by SHA-256:

```
c03aa1f19f04d3b581274640100182d34fdcdbc1b7efd4d56f9c6a23e3869c17  neverlose.html
2ab75d389529ade31657b14e915a811cdb2d561f1ca02f77b68c72991e2386de  recall.html
0afc0ae0d5b2f8f8d274144cd617e8e797d4ec245bc1ca50e60e33a344a1eea3  dist/neverlose-v0.2.zip
3c0b1b528b6a2979a6b696e450f3ecb2a2dd5cd909ee67b31e338204b2574732  dist/recall-v0.1.zip
56f5df35c0fe760069bfc371667e12edb80518e4d3852a70cccbc6e96560b772  covers/neverlose-cover.png
ac164e8eac2d43e2912568945ee14a1adb5f6d86eca8d8a02ac0165c38e0296a  covers/neverlose-cover@1x.png
172552fa63f4a9e06cfbcc1a60cdaf765137cd80482ca715f1854b2c95e06ceb  covers/recall-cover.png
e4033bbc0d418d2240c96108f8d9a091fa8b4ccfbb7066d2bd81296980332aa8  covers/recall-cover@1x.png
d4e99c5815923ac0ac7f03ddb6e6d86da1caa96ec84a7a1d6c52d3dd7d85bb5f  covers/bundle-cover.png
c59955ccabf253a7e7eb97eecc443e7248ba6229b0d2d1b7ca263a64db9d18b6  covers/bundle-cover@1x.png

```

## License

MIT — see `LICENSE`.
