# J. Bongo's Metadata Generator

YouTube metadata for long VODs — titles, a plain description, chapters, tags, Shorts cuts, thumbnail text, and a pinned comment. It learns how *you* edit so the next run takes less cleanup.

**App:** [j-bongo-metadata.grok.me](https://j-bongo-metadata.grok.me)  
Sign in with Google or X. This GitHub page is the public face of the product. The running app, accounts, and database live on grok.me — not here. Source is not in this repo.

---

## What it does

Upload an **SBV/SRT** (the clock) and the **full transcript** (what was actually said). Generate. Fix anything in the app, then **Save edits for learning**.

You get:

- Five title options
- A short factual description (no hype)
- A chapter list (time + title) you can edit, add, delete, or reorder
- Tags, three Shorts cuts, thumbnail text, and a pinned-comment CTA
- Themes pulled from the talk

It is not locked to one game or niche. A basketball VOD and a design-talk VOD both work. Fill **Voice** so the writing sounds like your channel.

## How a normal run goes

1. Sign in.
2. In YouTube Studio, download the `.sbv` (or `.srt`) and the transcript `.txt`.
3. On Generate, add a title and upload both files (or paste them).
4. Click **Generate metadata**.
5. Edit the results until you would actually publish them.
6. Click **Save edits for learning** — that is *your* account only.
7. Click **Clear for next VOD** before you load a different video.

If YouTube has no captions, open **No YouTube captions?** and upload audio you stripped in VLC (MP3, 48 kbps, mono). That fills both boxes. Then Generate as usual.

You do **not** have to shorten the transcript first. Chapter times always come from the caption file.

## How “it learns” works

This is not a privately trained model. After you save a few corrected runs, later drafts copy **your style**: how you title chapters, how many you keep, how spread-out they are, and the tone of your description and tags.

It will not paste this VOD’s times or dungeon names onto the next one. Clocks always come from **this file’s** captions.

## Tabs

- **Generate** — load a VOD and get metadata.
- **Library** — private search of your past runs (“what did I say about Zant”).
- **Voice** — a short form: channel type, tone, title style, audience, phrases, extra rules.
- **Prompt** — the recipe for titles, description, and chapters.
- **Billing** — 3 trial generations, then $12 for 20 more, or a redeem code. Some people use their own xAI key (the secret that starts with `xai-`, not “Copy key ID”).
- **Help** — the same walkthrough as this page, inside the app.
- **Update Log** — what changed, in plain English.

The orange chip in the header shows how many generations you have left (or Unlimited).

The app footer also links here. Everything is per signed-in user. Other people do not train on your VODs.

---

## Update log

Newest first. Same notes appear under **Update Log** in the app.

### September 16, 2026 — Help and Update Log tabs

- The header has Help (how the app works) and Update Log. Generate no longer shows a changelog blurb.

### September 16, 2026 — Credits in the header

- The orange chip shows how many generations you have left. After you pay, Billing confirms the pack even if the webhook is slow.

### September 16, 2026 — Buy more runs

- When the trial is used up, Billing can take a card for 20 generations at $12. Redeem codes still work if you were sent one.

### September 16, 2026 — Audio when YouTube has no captions

- Strip audio in VLC (MP3, 48 kbps, mono) and upload it on Generate. The app transcribes it and fills captions and transcript.

### September 16, 2026 — Voice is a form

- Channel type, tone, title style, audience, phrase chips, and a write-in box. A basketball channel and a gaming channel fill out the same form.

### September 16, 2026 — Long VODs

- Paste the whole transcript. The app samples start, middle, and end. Longer streams still get chapters in the last hour.

### September 15, 2026 — Cut fluff is optional

- You do not need to cut fluff before Generate. Chapter times always come from the caption file.

### September 8, 2026 — Chapters you can edit

- One time and one title per row. Edit, add, delete, or reorder. Stream start is always 00:00:00.
- Save edits for learning uses how you title chapters — not this video’s times on the next one.

### September 7, 2026 — Learning and billing

- Save edits for learning stores your corrections on your account only.
- Trial credits, redeem codes, or your own xAI key under Billing.
- Voice, Prompt, and Library are yours alone.

---

## Privacy

Each account has its own generations, voice pack, prompt, and credits. This GitHub page does not include the app’s source code.
