# J. Bongo Studio

Livemark for live chapters. Metadata Generator for titles, description, and tags. One Google or X account. Adding another tool later is a card on the home grid, not a new login.

**App:** [j-bongo-metadata.grok.me](https://j-bongo-metadata.grok.me)  
Sign in with Google or X. Home opens on a **J. Bongo Studio** banner and preview cards for Livemark and Metadata. This GitHub page is the public face of the product. The running app, accounts, and database live on grok.me — not here. Source is not in this repo.

## The two tools

**Livemark** — drop chapter marks in OBS while you stream. Go Live does **not** start the clock: bind **Livemark: Start clock** and hit it when the stream actually begins, then **Livemark: Mark chapter** at each chapter. Each clock-start writes a dated `.jsonl` (for example `livemark-marks-2026-09-21-144532.jsonl`). The OBS script pack is **$3 once** per account (a Metadata generation pack also unlocks it). After YouTube has the replay, click a connected VOD (or paste the URL), import that file, Align (**Mark is here**), copy a chapter block that starts at `0:00`. Align, copy, and download spend **no** generation credits. If YouTube is connected, **Send to Metadata** also brings that VOD’s captions. OBS does not listen to you — `title` in the file is a placeholder until you rename chapters in Livemark.

**Metadata Generator** — titles, a plain description, chapters, and tags from captions. It learns how *you* edit so the next run takes less cleanup. **Generate metadata** spends one credit, same as before.

If you just streamed: Livemark first, then **Send to Metadata**. You do not have to wait for YouTube captions.

---

## Metadata Generator — what it does

Upload an **SBV/SRT** (the clock) and the **full transcript** (what was actually said). Generate. Fix anything in the app, then **Save edits for learning**.

You get:

- Five title options
- A short factual description (no hype)
- A chapter list (time + title) you can edit, add, delete, or reorder
- A **YouTube description** preview (write-up + chapters) with **Copy for Studio**
- Tags
- Optional extras under Additional information: Shorts cuts, thumbnail text, pinned comment, themes

It is not locked to one game or niche. A basketball VOD and a design-talk VOD both work. Fill **Voice**, or Connect YouTube so the first run can copy how your last titles were built.

## How a normal run goes

1. Sign in. Home is an app grid — pick Metadata Generator (or open Livemark if you just streamed).
2. In YouTube Studio, download the `.sbv` (or `.srt`) and the transcript `.txt`.
   **Or** Connect YouTube and click a recent long video (Shorts are hidden) to fill the title and captions.
3. On Generate, add a title and upload both files if you did not use a card.
4. Click **Generate metadata**.
5. Check the YouTube description preview. Edit titles, description, chapters, and tags until you would actually publish them.
6. Click **Save edits for learning** — that is *your* account only.
7. Click **Clear for next VOD** before you load a different video.

If YouTube has no captions, open **No YouTube captions?** and upload audio you stripped in VLC (MP3, 48 kbps, mono). That fills both boxes. Then Generate as usual.

You do **not** have to shorten the transcript first. Chapter times always come from the caption file.

## How “it learns” works

This is not a privately trained model. After you save a few corrected runs, later drafts copy **your style**: how you title chapters, how many you keep, how spread-out they are, and the tone of your description and tags.

If you Connect YouTube, Voice also shows titles from your last 10 long videos. Generate copies title *shape* and tag density from those — not old episode names. Saved edits still win once you have a few.

It will not paste this VOD’s times or dungeon names onto the next one. Clocks always come from **this file’s** captions.

## Apps and tabs

Home is **Apps**. Livemark and Metadata are the first two cards.

- **Livemark** — replay URL, OBS import, Align, copy chapters. Help and OBS pack live in that header.
- **Generate** — load a VOD and get metadata. Optional YouTube cards after Connect.
- **Library** — private search of your past runs (“what did I say about Zant”).
- **Voice** — a short form: channel type, tone, title style, audience, phrases, extra rules. Also shows channel memory if you connected YouTube.
- **Prompt** — the recipe for titles, description, and chapters.
- **Billing** — 3 trial generations, then $12 for 20 more, or a redeem code. Some people use their own xAI key (the secret that starts with `xai-`, not “Copy key ID”).
- **Help** — the same walkthrough as this page, inside the app.
- **Update Log** — what changed, in plain English.

The orange chip in the header shows how many generations you have left (or Unlimited). Livemark Align never decrements it.

The app footer also links here. Everything is per signed-in user. Other people do not train on your VODs.

---

## Update log

Newest first. Same notes appear under **Update Log** in the app.

### September 21, 2026 — Start clock is its own OBS hotkey

- Go Live no longer starts the chapter clock. Bind Livemark: Start clock and hit it when the stream actually begins, then Livemark: Mark chapter for each chapter. Times count from Start clock. Download the OBS script again to get this.

### September 21, 2026 — Each live gets its own dated OBS marks file

- Start clock writes a new file named with the date and time, like livemark-marks-2026-09-21-144532.jsonl. The next stream does not append onto the last one.

### September 21, 2026 — OBS script download works on the published site

- The Livemark OBS pack is bundled with the app, so Download no longer says the pack is missing after publish.

### September 21, 2026 — Share card and banner say J. Bongo Studio

- The app cover, in-app banner, and X share banner now read J. Bongo Studio instead of Metadata Generator.

### September 21, 2026 — OBS pack is a one-time $3 unlock

- The OBS chapter-mark scripts now cost $3 once per account. Buying any Metadata generation pack unlocks them too, so you do not pay both. Admins can grant or revoke OBS on the account list, and that list now shows how many times someone has Aligned in Livemark.

### September 21, 2026 — Livemark can use your YouTube connection

- If you already Connected YouTube in Metadata, Livemark now shows the same recent long videos. Click one to load the replay instead of hunting the URL. Send to Metadata pulls that VOD’s captions when they exist. Align and copy still spend no credits. Connect stays inside the apps, not on the home grid.

### September 21, 2026 — Studio banner and app preview cards

- A J. Bongo Studio banner now runs across the top of every page, in the same blue-and-orange look as the share preview. Livemark and Metadata each have their own preview still on the Apps home cards.

### September 21, 2026 — Apps home. Livemark for live chapters. Metadata is unchanged.

- Signed-in home is now an app grid. Livemark imports OBS chapter marks, Aligns them to the YouTube replay, and copies chapters without spending a generation. Send to Metadata prefills Generate; the credit still only drops when you click Generate metadata.

### September 18, 2026 — Channel memory from your last videos

- After Connect YouTube, Voice shows titles from your last 10 long videos. The next Generate copies title shape and tag density from those, not old episode names. You can turn that off on Voice.

### September 18, 2026 — Results page is cleaner

- Shorts cuts, thumbnail text, pinned comment, and themes now sit under Additional information so the main results stay titles, description, chapters, the YouTube preview, and tags.

### September 18, 2026 — YouTube description preview

- After Generate, you can see the Description field the way YouTube will: a short write-up, then chapter times. Copy for Studio pastes that whole block. It also warns if chapters would not unlock on YouTube (need 0:00, at least 3, 10 seconds apart).

### September 18, 2026 — YouTube cards hide Shorts

- Connect YouTube now lists regular videos only. Clips under 3 minutes and #Shorts posts are left out.

### September 17, 2026 — Optional YouTube video cards

- Connect the Google account that owns your channel, then click a recent upload to fill the title and captions. Generate is unchanged. File upload still works if YouTube has no captions or the daily YouTube shortcut limit is full.

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
