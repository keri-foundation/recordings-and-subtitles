# SEDI Summit 2025 — speaker cut inventory

Starter guide for splitting the three session MP4s into individual speaker (or panel) presentations.

**Event:** State-Endorsed Digital Identity (SEDI) Summit  
**Date:** Friday, 17 October 2025  
**Venue:** Vallejo Auditorium, Scott C. Keller Building, Utah Valley University  
**Official agenda:** [UVU Herbert Institute — 2025 SEDI Summit](https://www.uvu.edu/herbertinstitute/data_governance/state_endorsed_digital_identity_summit.html)

Times below are **video timestamps** from the matching `.srt` files, not wall-clock. They are good first cuts, not frame-accurate. Verify on the picture: the auto-captions miss some openings, swallow applause as `Wild` / `Thank you` loops, and sometimes start mid-sentence.

**How to use**

- Prefer one file per *presentation* (solo talk or named panel), not per microphone turn.
- Add ~0.5–2 s of pad at in/out after watching; do not cut on the first caption if the speaker is already on stage.
- Rolling-caption leftovers (`Thank you.` every ~30 s, `Wild Wild Wild…`) are **not speech**. Treat those ranges as silence, walk-up, or video playback until real words return.
- Names in *italics* are ASR spellings that were corrected against the published agenda.

---

## Source files

| Session | Subtitle / video basename | Caption span | Useful speech |
| --- | --- | --- | --- |
| Morning | `State-Endorsed-Digital-Identity-Summit-Morning-Session` | `00:00:00` → `02:34:17` | ~`00:03:34` → `02:34:17` |
| Lunch | `State-Endorsed-Digital-Identity-Summit-Lunch-Panel` | `00:00:01` → `00:59:50` | ~`00:38:43` → `00:59:11` (large ASR gap before that) |
| Afternoon | `State-Endorsed-Digital-Identity-Summit-Afternoon-Session` | `00:00:00` → `02:32:34` | ~`00:16:06` → `02:32:06` (Alan Fuller likely in the ASR gap) |

Suggested output names: `Speaker Name ｜ Talk title ｜ SEDI Summit 2025.mp4`

---

## 1. Morning session

Published block: 9:00–11:00 AM, then Rep. Cutler at 11:10 AM before breakouts.

### 1.1 Chris Bramwell — Utah’s Vision for State-Endorsed Digital Identity

| | |
| --- | --- |
| **Speaker** | Christopher Bramwell, Utah Chief Privacy Officer |
| **In** | `00:03:34` |
| **Out** | `00:18:20` |
| **Cut notes** | `00:00:00`–`00:03:34` is pre-roll / rolling captions. Opening thanks (Herbert Institute, GovOps, Legislature, UVU) then vision for SEDI and the day’s run of show. Hands off: “So with that, Ryan, I’ll invite you to come up.” |

### 1.2 Ryan Hurst — What Is Digital Identity?

| | |
| --- | --- |
| **Speaker** | Ryan Hurst, CEO, Peculiar Ventures |
| **In** | `00:19:09` |
| **Out** | `00:29:15` |
| **Cut notes** | ~50 s gap after Bramwell. Caption opens mid-thought (“I’m going to turn / to you. working for companies like Google…”). Ends: “Ladies and gentlemen, I appreciate your time today.” |

### 1.3 Cindy George — The Human Cost — Why SEDI Matters

| | |
| --- | --- |
| **Speaker** | Cindy George (Utah parent; Jake Curtis story) |
| **In** | `00:31:40` |
| **Out** | `00:55:41` |
| **Cut notes** | `00:29:15`–`00:31:40` is likely applause / KUTV clip / walk-up (captions are only `Thank you.`). Talk starts “Hi. Thank you. Oh, those dimples…” Ends “it can happen to the best of kids. Thank you.” Long applause after; do not extend the cut through `00:59:44`. |

### 1.4 Legislative panel — The Urgency of Advancing State-Endorsed Digital Identity

Keep as **one** file (overlapping Q&A). Do not split by speaker unless you re-edit with isolated mics.

| | |
| --- | --- |
| **Participants** | Sen. Kirk Cullimore (Senate Majority Leader); Rep. Paul Cutler (HD 18); Rep. Kristen Chevrier (HD 54); Rep. Lisa Shepherd (HD 61); Chris Bramwell moderating |
| **In** | `00:59:44` |
| **Out** | `01:29:30` |
| **Cut notes** | First voice ~`00:59:44` (“Do I have it on?”) is a legislator (Utah County; “even before I took office”). Moderator cue to Cullimore ~`01:01:08`; Cullimore “I’ll start” `01:01:29`. Chevrier/Shepherd invited `01:11:36`; first of those two ~`01:12:11`. **Floor:** Sarah Thunberg, Colorado Digital Service `01:16:32`; Shanna Durant, Utah DPS `01:20:23`. Lisa Shepherd “Go ahead Lisa” `01:25:59`. Close: “Let’s give them a round of applause” `01:29:19`. |

### 1.5 Daniel Hardman — Current Lay of the Land: Verifiable Credentials & Digital Identity

| | |
| --- | --- |
| **Speaker** | Daniel Hardman, CTO/CISO, Provenant |
| **In** | `01:30:34` |
| **Out** | `01:41:59` |
| **Cut notes** | Self-intro. Ends “Thank you. That’s all I’m going to do.” |

### 1.6 Phil Windley — Centralized vs Decentralized Identity

| | |
| --- | --- |
| **Speaker** | Phil Windley, Executive Director, IIW Foundation |
| **In** | `01:43:00` (first *clear* words ~`01:43:30`) |
| **Out** | `01:50:14` |
| **Cut notes** | Opening is lost in applause-ASR (`Wild…` then “Amazon. They own it”). First person / endorsement argument. Ends “Let’s not squander that opportunity.” |

### 1.7 Joe Jackson — Backward Compatibility & Continuous Improvement

| | |
| --- | --- |
| **Speaker** | Joe Jackson, Utah Chief Technology Officer |
| **In** | `01:50:35` |
| **Out** | `01:58:24` |
| **Cut notes** | Opens “All right. We’re going to see if I get to keep my geek card here.” Backward compatibility talk, then introduces SpruceID, GET Group North America, Cardano Foundation / Veridian. Hands off `01:58:23`. |

### 1.8 Proof-of-concept demos (morning)

Keep as **one** file unless you later split on picture.

| | |
| --- | --- |
| **Participants** | Wayne Chang, SpruceID; GET Group North America (*Derek* on caption); Cardano Foundation / Veridian (Thomas Mayfield and others; KERI/ACDC) |
| **In** | `01:58:29` |
| **Out** | `02:20:59` |
| **Cut notes** | Wayne: “Thanks so much, Joe…” `01:58:29`. Age / mDL / wallet flows; GET Group pick-up ~`02:12:37`; further KERI/ACDC demo. Ends “that’s the end of my demo and my time.” |

### 1.9 Rep. Paul Cutler — Endorsement and Protection of Individual Digital Identity Is a State Role

| | |
| --- | --- |
| **Speaker** | Rep. Paul Cutler |
| **In** | `02:21:20` |
| **Out** | `02:32:35` |
| **Cut notes** | Caption: “Presentation by Representative Cutler on the role of the state…” Video clip / AV trouble ~`02:22:19`–`02:23:53`. Ends “Thank you for coming… And I think we’re moving to the breakouts. Chris?” |

### 1.10 Logistics only (skip for speaker videos)

| | |
| --- | --- |
| **Speaker** | Chris Bramwell |
| **In** | `02:32:45` |
| **Out** | `02:34:17` |
| **Cut notes** | Recordings/slides will be online; two breakouts (KB 405 state vs federal; upstairs tourism/housing). Not a presentation. |

Morning breakouts and lunch upstairs were **not** in this recording.

---

## 2. Lunch presentations

Published block: 12:30–1:00 PM. Video is ~60 minutes; **almost all captions before `00:38:43` are rolling `Thank you.`** Jay Stanley (ACLU) is on the agenda at 12:30 and is **not recoverable from this SRT**. Watch the picture from the start of the file (and any `Thank you,` clusters around `00:13:00`–`00:38:00`) to find him.

### 2.1 Jay Stanley — Civil Liberties Perspective on Digital Identity & SEDI

| | |
| --- | --- |
| **Speaker** | Jay Stanley, Senior Policy Analyst, ACLU |
| **In / Out** | **Unknown — visual search required** |
| **Cut notes** | No usable transcript. Likely in `00:00:00`–`00:38:43`. If he is on this tape, cut from first on-stage appearance to Chipman’s start. |

### 2.2 Jason Chipman — Public Interest Perspective (Libertas)

| | |
| --- | --- |
| **Speaker** | Jason Chipman, Director of Public Policy, Libertas |
| **In** | `00:38:43` (**mid-talk**) |
| **Out** | `00:41:34` |
| **Cut notes** | Caption starts mid-sentence (“through the legislature for this is so important…”). Five kids, former legislator, “this is good until it’s not.” **Rewind on video** to find his walk-up / intro (Bramwell or Stanley). Ends “Thank you very much.” |

### 2.3 Jeremy Grant — Additional comments (Better Identity Coalition)

| | |
| --- | --- |
| **Speaker** | Jeremy Grant, Better Identity Coalition (Venable) |
| **Host intro** | `00:41:41` → `00:42:27` (Bramwell) |
| **Talk in** | `00:42:27` |
| **Talk out** | `00:48:06` |
| **Cut notes** | Optional: include Bramwell intro in this file. Ends “appreciate the invite again and look forward to talking to you. Thank you.” |

### 2.4 Christian Reza — Additional comments (Stand With Crypto)

| | |
| --- | --- |
| **Speaker** | *Christian Riza* in captions → **Christian Reza**, Utah chapter president, Stand With Crypto |
| **Host intro** | `00:48:12` → `00:48:40` |
| **Talk in** | `00:48:48` |
| **Talk out** | `00:52:35` |
| **Cut notes** | Community / crypto-voter support for SEDI. Ends “And we hope that you will. So thank you.” |

### 2.5 Scott Stornetta — Additional comments

| | |
| --- | --- |
| **Speaker** | Scott Stornetta, co-inventor of blockchain |
| **Host** | Bramwell comment + intro `00:52:44` → `00:53:50` (includes economic aside about a company reincorporating in Utah) |
| **Talk in** | `00:53:50` |
| **Talk out** | `00:58:51` |
| **Cut notes** | Haber–Stornetta, decentralization, endorsement of SEDI. Ends “value to many, many people across the world. Thank you.” |

### 2.6 Lunch close (skip)

Bramwell `00:59:01`–`00:59:11`: move downstairs to the atrium. Then caption garbage to `00:59:50`.

---

## 3. Afternoon session

Published block: 1:15–2:40 PM talks, then 2:55–4:00 PM discussion. Video ~2h 32m.

### 3.1 Alan Fuller — SEDI Is Critical Public Infrastructure

| | |
| --- | --- |
| **Speaker** | Alan Fuller, Utah CIO |
| **In / Out** | **Uncertain — visual search `00:00:00`–`00:16:06`** |
| **Cut notes** | Agenda: 1:15 PM, before Scott Perry. Captions in this window are almost only `Thank you.` One real line: **“Thank you, Chris. Thank you.” `00:10:33`–`00:10:40`** — possible end of Fuller’s talk. Leftover at `00:00:00` (“I will never edit it…”) is not a start. If he is on tape, he is the missing first speaker. He **is** on the closing panel later (`01:33:31`). |

### 3.2 Scott Perry — Open Standards and Open Protocols

| | |
| --- | --- |
| **Speaker** | Scott Perry, Founder/CEO, Digital Governance Institute |
| **In** | `00:16:06` |
| **Out** | `00:26:12` |
| **Cut notes** | “There we go. Yay. All right. So my name is Scott Perry.” Trust over IP, open standards. Ends “access this at your leisure. Thank you very much for your time.” |

### 3.3 Timothy Ruff — Individual Control, Autonomy & Guardianship

| | |
| --- | --- |
| **Speaker** | Timothy Ruff, Chief Strategy Officer, Digital Trust Venture Partners |
| **In** | `00:26:28` |
| **Out** | `00:44:25` |
| **Cut notes** | Opens by looking for Stornetta and Samuel Smith, then guardianship vs delegation, “Legos not a toolbox.” Ends “designed for the coming agentic AI era. Thank you.” |

### 3.4 Demo — Minor guardianship & age assurance (Cardano / Veridian)

| | |
| --- | --- |
| **Participants** | Cardano Foundation / Veridian — Thomas Mayfield (narration); Fergal O’Connor (on-stage demo). Jeremy Firster is in the later Q&A. |
| **In** | `00:47:49` (first clear words after applause-ASR) |
| **Out** | `01:02:47` |
| **Cut notes** | Child-safety stats then live birth-certificate / guardianship / chat demo. Ends “what choice would you make? Thank you very much for your time.” `00:45:26` “SEDI actualized… Good afternoon” may be the true walk-up; check picture. |

### 3.5 Demo — Senior adult guardianship (Clear Foundation / Utah Life)

| | |
| --- | --- |
| **Participants** | Agenda: Clear Foundation on Utah Life (senior guardianship / multisig). Speaker name not in captions. |
| **In** | `01:06:53` |
| **Out** | `01:10:02` |
| **Cut notes** | ASR is poor. Content: grandparent app, utility bill, grandchild, thanks to Sam Smith / Phil Windley / Tim. Ends “thank you for being here and understanding some of these concepts.” Then more caption garbage until McCown. |

### 3.6 Steve McCown — Zero Surveillance, Zero Tracking

| | |
| --- | --- |
| **Speaker** | Steve McCown, Utah Privacy Commission; Chief Architect, Anonyome Labs |
| **In** | `01:11:15` |
| **Out** | `01:21:17` |
| **Cut notes** | “Thank you. All right. My name is Steve McCown…” Agenda lists him as CIO in one place; he self-IDs as commissioner / Anonyome. Ends “So thank you very much. Thank you.” |

### 3.7 Simon Wood — Economic Impact and Opportunity of SEDI

| | |
| --- | --- |
| **Speaker** | Simon Wood, Senior Advisor to Refute; former CEO, Ubisecure |
| **In** | `01:22:14` |
| **Out** | `01:31:45` |
| **Cut notes** | Remote from the UK. Finnish tax-office case (org + individual identity). Ends “I can provide more information if that’s useful. Thank you very much.” |

### 3.8 Closing discussion and Q&A — Getting Started on Your SEDI Journey

Keep as **one** file.

| | |
| --- | --- |
| **On stage / host** | Chris Bramwell; Rep. Paul Cutler; Alan Fuller |
| **In** | `01:32:08` |
| **Out** | `02:32:06` |
| **Cut notes** | Bramwell: “This is the final discussion.” Cutler invited `01:33:31`; speaking `01:35:31`. Audience / other voices (not separate videos unless you want clips): Steve McCown `01:45:27`; Eric Torgensen `01:46:48`; Amelia Powers Gardner (Utah County Commissioner) `01:49:46`; Mariano Green (Mexico City) `02:07:42`; Jeremy Firster (*Furster* in captions), Cardano/Veridian `02:22:13`; Mark Allen, Citizen Portal `02:25:27`. Close “let’s get SEDI rolling. So thank you everyone.” `02:32:01`, then “Thanks Brian.” |

---

## Suggested first-pass cut list (ffmpeg-friendly)

Times as `HH:MM:SS`. Confirm on picture before batch-encoding.

| Output (working title) | Source | In | Out |
| --- | --- | --- | --- |
| Chris Bramwell \| Utah’s Vision for SEDI | Morning | 00:03:34 | 00:18:20 |
| Ryan Hurst \| What Is Digital Identity | Morning | 00:19:09 | 00:29:15 |
| Cindy George \| The Human Cost | Morning | 00:31:40 | 00:55:41 |
| Legislative Panel \| Urgency of Advancing SEDI | Morning | 00:59:44 | 01:29:30 |
| Daniel Hardman \| Lay of the Land | Morning | 01:30:34 | 01:41:59 |
| Phil Windley \| Centralized vs Decentralized | Morning | 01:43:00 | 01:50:14 |
| Joe Jackson \| Backward Compatibility | Morning | 01:50:35 | 01:58:24 |
| Morning PoC Demos \| SpruceID, GET Group, Veridian | Morning | 01:58:29 | 02:20:59 |
| Paul Cutler \| Identity Endorsement Is a State Role | Morning | 02:21:20 | 02:32:35 |
| Jay Stanley \| Civil Liberties *(find on tape)* | Lunch | TBD | TBD |
| Jason Chipman \| Libertas / Public Interest | Lunch | 00:38:43* | 00:41:34 |
| Jeremy Grant \| Better Identity Coalition | Lunch | 00:41:41 | 00:48:06 |
| Christian Reza \| Stand With Crypto | Lunch | 00:48:12 | 00:52:35 |
| Scott Stornetta \| Comments | Lunch | 00:52:44 | 00:58:51 |
| Alan Fuller \| Critical Public Infrastructure *(find on tape)* | Afternoon | TBD | TBD |
| Scott Perry \| Open Standards and Open Protocols | Afternoon | 00:16:06 | 00:26:12 |
| Timothy Ruff \| Control, Autonomy & Guardianship | Afternoon | 00:26:28 | 00:44:25 |
| Veridian demo \| Minor guardianship & age assurance | Afternoon | 00:47:49 | 01:02:47 |
| Clear Foundation demo \| Senior guardianship | Afternoon | 01:06:53 | 01:10:02 |
| Steve McCown \| Zero Surveillance, Zero Tracking | Afternoon | 01:11:15 | 01:21:17 |
| Simon Wood \| Economic Impact of SEDI | Afternoon | 01:22:14 | 01:31:45 |
| Closing Q&A \| Getting Started on Your SEDI Journey | Afternoon | 01:32:08 | 02:32:06 |

\*Chipman in-point is mid-sentence; rewind.

---

## Visual-search checklist (ASR failed)

1. **Lunch `00:00:00`–`00:38:43`** — Jay Stanley; start of Jason Chipman; any Bramwell lunch intro.
2. **Afternoon `00:00:00`–`00:16:06`** — Alan Fuller (likely).
3. **Phil Windley** — confirm whether he is already talking during the `Wild` block at `01:43:00`.
4. **Morning `00:29:15`–`00:31:40`** — Cindy George KUTV package vs empty stage.
5. **Afternoon `00:44:25`–`00:47:49`** — walk-up vs start of Veridian demo.
6. **GET Group vs Spruce** in the morning demo (`~02:11`–`02:13`) if you want two files instead of one.

---

## Name corrections (captions → use these)

| ASR | Use |
| --- | --- |
| Kullimore / Collin Moore / Colomore | Kirk Cullimore |
| Shepard | Lisa Shepherd |
| Winley | Phil Windley |
| Christian Riza | Christian Reza |
| Jeremy Furster | Jeremy Firster |
| Sarah Thunberg | Sarah Thunberg (keep; director, Colorado Digital Service) |
| Shanna Durant | Shanna Durant (Utah DPS) |
