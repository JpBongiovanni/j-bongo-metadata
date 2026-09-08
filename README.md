# J. Bongo's Metadata Generator

YouTube metadata for long VODs — titles, a plain description, chapters, tags, Shorts cuts, thumbnail text, and a pinned comment. It learns how *you* edit so the next run takes less cleanup.

**Use the app:** sign in on the published grok.me site (the link you opened after Publish).  
This page is the public face of the product. The running app, accounts, and database live on grok.me — not here.

---

## What it does

Paste an **SBV/SRT** (the clock) and the **full transcript** (what was actually said). Generate. Then fix anything in the app and hit **Save edits for learning**.

You get:

- Five title options
- A short factual description (no hype)
- A chapter list (time + title) you can edit, add, delete, or reorder
- Tags, three Shorts cuts, thumbnail text, and a pinned-comment CTA

It is not locked to one game. Cut fluff figures out the topic of *this* video — plumbing, design talk, a Zelda dungeon, whatever you uploaded.

## How a normal run goes

1. Sign in.
2. Upload or paste captions (SBV or SRT).
3. Paste the full transcript. Caption snippets alone are too thin.
4. Optional: **Cut fluff** to drop hellos, IRL chat, and subscribe talk. You do not have to cut first for chapters to work.
5. **Generate metadata.**
6. Edit the chapter times and titles (and anything else) until you would actually publish it.
7. **Save edits for learning** — that is *your* account only.
8. **Clear** before the next VOD.

## How “it learns” works

This is not a privately trained model. After you save a few corrected runs, later drafts copy **your style**: how you title chapters, how many you keep, how spread-out they are, and the tone of your description and tags.

It will not paste this VOD’s times or dungeon names onto the next one. Clocks always come from **this file’s** captions.

## Voice, Prompt, Library, Billing

- **Voice** — how you sound (tone, phrases to use or avoid).
- **Prompt** — the recipe for the JSON metadata.
- **Library** — private search of your past VODs (“what did I say about Zant”).
- **Updates** — a short, plain-English log of what changed in the published app.
- **Billing** — trial credits, redeem codes, or your own xAI key (the secret that starts with `xai-`, not “Copy key ID”).

The app footer also links here. Everything is per signed-in user. Other people do not train on your VODs.

---

## Update log

Newest first. Same notes appear under **Updates** in the app.

### September 8, 2026 — Public GitHub page

- The footer now links to this public GitHub page: how the app works and the update log. Source stays private.

### September 8, 2026 — Chapters you can actually edit

- Chapters are a simple list again: one time and one title. You can edit either, add or delete a row, or move rows up and down.
- Generate still reads the whole timed VOD in slices, so later minutes should get chapters too — not just the first half hour.
- Stream start is always 00:00:00. A later chapter will not steal that slot.
- When you click Save edits for learning, the next run uses how you title chapters and how spread-out you like them. It will not copy this video’s times onto the next one.
- Cut fluff is optional. You do not have to shrink the transcript first for chapters to work.

### September 7, 2026 — Learning, billing, and a cleaner studio

- Save edits for learning stores your corrections on your account only.
- You can paste your own xAI key under Billing, or stay on trial credits and redeem codes.
- Voice and Prompt tabs are yours alone. Library lets you search past VODs.
- Help walks through a normal run: captions, full transcript, generate, edit, save, then Clear.

---

## Privacy

Each account has its own generations, voice pack, prompt, drop phrases, and credits. This GitHub page does not include the app’s source code.
