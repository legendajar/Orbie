<p align="center">
  <img src="orbie.png" width="128" height="128" alt="Orbie: a violet orb with two dark eyes">
</p>

<h1 align="center">Orbie</h1>

<p align="center"><b>A living orb at the top of your Windows screen: a personal assistant that keeps your private life on your PC.</b></p>

<p align="center">
  <a href="https://github.com/legendajar/Orbie/releases/latest"><b>Download the latest version</b></a> · Windows 10 and 11 (64-bit) · Free
</p>

---

Orbie is a small violet orb with eyes that sits at the top-centre of your screen. It breathes, blinks, follows your pointer with its eyes, and dozes off when nothing is going on. Click it, press a shortcut, or hold it and talk, and a panel unfolds with everything it can do for you:

- **Chat** with your own AI model running on your PC, or, for harder general questions, with Claude Code on your own login.
- **Tasks, reminders and notes**, said in plain words: "remind me at 5 to call the bank".
- **Google Calendar and Gmail**: what's on today, summaries of your email, drafted replies. Nothing is sent or changed without your click.
- **A morning brief**, meeting heads-ups and nudges, quiet at night.
- **Voice**: hold a key and talk, hear answers in Orbie's voice, or talk hands-free with a wake word. Your voice never leaves the PC.
- **Your PC**: open apps, folders and websites, find and tidy up files (with undo), work with what you copied, and ask about what's on the screen.
- **Claude Code**: see your coding sessions on the orb, answer their permission requests there, and hand Claude Code a coding task.
- **Memory**: it remembers what you tell it about yourself, and you can read and edit all of it.

**Privacy is the rule it's built around.** Your email, calendar, notes, tasks, memories and files are only ever handled on your PC, by a model you run yourself. Only general questions, with nothing about you in them, may go to the cloud.

Orbie is designed and built by Harsh Solanki. **This repository holds Orbie's releases**: the installers, the files Orbie uses to update itself, and the release notes. Orbie's source code isn't public.

## Contents

- [What you see on screen](#what-you-see-on-screen)
- [What Orbie can do](#what-orbie-can-do)
- [Privacy](#privacy)
- [What you need](#what-you-need)
- [Install](#install)
- [First-run setup](#first-run-setup)
- [Shortcuts](#shortcuts)
- [Updates](#updates)
- [Uninstall and your data](#uninstall-and-your-data)
- [Troubleshooting](#troubleshooting)
- [Resource use](#resource-use)
- [Versions](#versions)
- [Built with](#built-with)

## What you see on screen

### The orb

The orb lives at the top-centre of your main screen, above every window. Everywhere around it, clicks go straight through to the app underneath, so it never gets in the way. **Settings → Orbie's position** slides it left or right.

Its look tells you what's going on:

| What it looks like | What it means |
|---|---|
| A violet orb, gently breathing, blinking, its eyes following your pointer | Awake, nothing going on |
| A warm glow, with two rings pulsing outwards | Something waits for you in the Inbox: a reminder, the morning brief, a nudge, or a step that needs your OK |
| Cool teal, with a ring that swells as you speak | Listening while you hold the talk key (or the orb) |
| A still teal ring | Listening for the wake word, ready for live talk |
| Eyes looking up, with a slow glow | Working out what you said, or thinking of an answer in live talk |
| Soft violet rings drifting outwards | Reading an answer aloud (click it to stop) |
| Faded and grey, eyes closed | Asleep after five quiet minutes. Anything happening wakes it, and so does a click |

It has a little personality too. As it starts it pops in, hops, and shows "Good morning!" under itself for a few seconds ("Good afternoon!", "Good evening!", or "Hello, night owl!" later on). Then it reacts to what happens:

- a **happy bounce** when a task is done,
- a **proud nod** when something you allowed finishes,
- a **sad droop** when something goes wrong, or your local model goes offline,
- a **surprised hop** when a reminder fires or Claude Code asks for something,
- and a **giggle** if you poke it a few times in a row.

### Claude Code's island

If you use Claude Code (Anthropic's coding assistant) and connect it to Orbie, your running sessions show around the orb while the panel is closed, like a phone's live activity. A pill around the orb shows the session that most needs you and what it's doing. When a session asks for your permission, wants you to answer a question, or finishes a long turn, a card drops down below the orb. You can **Allow**, **Allow for this session** or **Deny** right there, without switching windows. Clicks on the island hand focus straight back to the app you were in.

### The panel

Click the orb (or press **Ctrl+Shift+A**) and the panel unfolds below it. **Esc**, or a click anywhere else, folds it away. It has seven tabs:

| Tab | What it shows |
|---|---|
| **Chat** | Your conversation with Orbie. Each answer is marked with the brain that gave it: 🔒 your local model, or ☁ Claude Code. Beside the message box: the **mic** (talk instead of typing), the **camera** (ask about a screenshot), and the **clipboard** (explain, summarise or translate what you copied). A **Live** view holds your hands-free live talk conversation. Steps that change something wait here as a card for your OK. |
| **Today** | Today's and the coming days' events from Google Calendar, your tasks due and overdue, the reminders still to come, and the morning brief at the top. |
| **Tasks & Notes** | Your tasks (with due days), reminders (once, daily, on weekdays or weekly) and notes: add, edit, tick off or delete them. |
| **Inbox** | What's waiting for you: reminders that fired, the morning brief, nudges, steps waiting for your OK, and your important unread email with the latest in your Gmail inbox. Its count shows on the tab. |
| **Code** | Your Claude Code sessions, the requests they're waiting on, and the coding tasks you handed to Claude Code, with their steps and the files they changed. |
| **Memory** | Everything Orbie remembers about you ("prefers short answers", "works from home on Fridays"), each one editable or deletable. |
| **Settings** | Everything below, from start-up to your voice. |

**Settings** has these sections:

| Section | What's there |
|---|---|
| (top) | **Start with Windows**, **Orbie's position**, and a preview of the attention glow |
| **Shortcuts** | Change Orbie's three global shortcuts |
| **Brains** | Your local model (LM Studio) and Claude Code: which models, whether they're online, Claude Code's usage, and which models LM Studio has in your graphics memory, with Unload |
| **Reaching out** | The morning brief, meeting heads-ups, overdue nudges and quiet hours, each with its time |
| **Voice** | Push-to-talk, the speech model, spoken replies and Orbie's voice, live talk and the wake word |
| **Google** | Connect your Google account for Calendar and Gmail |
| **Claude Code** | Connect your Claude Code sessions to the orb, the island, and its notifications |
| **Hands** | The folders Orbie may search and tidy up, and undo for the last tidy-up |
| **About** | Orbie's version, updates, where your data is, and the log folder |

### Notifications and the tray

Windows notifications carry reminders, the morning brief, meeting heads-ups, overdue nudges and Claude Code's requests, all named "Orbie". Click one to open the panel where it belongs.

Orbie's icon sits in the tray (by the clock). Its menu has **Open**, **Settings…**, **Pause** (hides the orb and closes the microphone until **Resume**), **Free graphics memory** (unloads LM Studio's models for a game or another app), **Restart to update** while an update is ready, and **Quit Orbie**.

## What Orbie can do

### Chat with two brains

Orbie has two brains, and decides for each message which one answers:

- **Your local model** (🔒) runs on your PC in [LM Studio](https://lmstudio.ai). It answers anything about you and does everything that uses your data: tasks, notes, calendar, email, files, the screen.
- **Claude Code** (☁) answers harder general questions ("explain how HTTPS works", "compare these two laptops") on your own Claude Code login, with web search and nothing else: no files, no tools on your PC, and none of your personal Claude Code setup.

Start a message with `/local` or `/cloud` to choose yourself. Anything private stays local even with `/cloud`, and once a chat has used your data, all of it stays local until **New chat**.

### Tasks, reminders and notes

Just say it: "remind me in 10 minutes to stretch", "remind me every Monday at 9 to send the report", "add a task to renew my passport by Friday", "note: the router password is on the fridge". Reminders fire as notifications at their time, even with the panel closed, and ones missed while the PC was off fire when Orbie starts. Ask "what's on my list?" or "what did I note about the router?" anytime.

### Today and the morning brief

Each morning (08:00 unless you change it) Orbie writes you a brief: today's events, tasks due and overdue, the reminders still to come and your important unread email, with a short overview in plain words. It lands in the Inbox and at the top of **Today**. If your PC was asleep at brief time, it comes when the PC wakes. It also gives you a heads-up 10 minutes before each meeting and a nudge when a task becomes overdue. During quiet hours (22:00–07:00 unless you change them) these wait silently in the Inbox; reminders you set yourself still notify.

### Google Calendar and Gmail

Once connected, ask "what's on tomorrow?", "am I free Friday afternoon?", "book lunch with Sam on Friday at 1pm", "summarise my unread email" or "reply to Sam's email saying Friday works". Before an event is created, moved or deleted, or an email is sent, archived or saved as a draft, a card shows you exactly what will happen, and you can edit it before you confirm. New email is never read in the background, and never makes the orb glow.

### Voice

- **Push-to-talk:** hold **Ctrl+Alt+V** anywhere (or press and hold the orb), speak, and let go. Your words appear marked 🎙, and Orbie answers them like a typed message.
- **Spoken replies:** answers to what you said are read aloud in Orbie's voice. Choose from 28 English voices, American or British. Hindi answers are read in a Hindi voice.
- **Live talk:** press **Ctrl+Alt+W**, or say the wake word, and just talk. Orbie listens, answers out loud and listens again, hands-free, until you say "Thanks Orbie", press the shortcut again, or say nothing for two minutes. It's one conversation that carries on across days. As it grows, your local model summarises the earlier part.
- **Wake word:** "Hey Jarvis" out of the box (a ready-made model, for personal use). You can also choose your own wake word model file in **Settings → Voice**.

Speech is recognised on your PC by [Whisper](https://github.com/openai/whisper), and Orbie's voice is made on your PC by [Kokoro](https://huggingface.co/hexgrad/Kokoro-82M). Your voice is never saved or sent anywhere. The models download once, the first time you talk; after that voice works offline. Live talk always uses your local model, never the cloud.

### On your PC

- **Open things:** "open Spotify", "open my Downloads folder", "open the calculator".
- **Find files:** "find the invoice PDF from March", by name or by what's inside.
- **Tidy up:** "organise my Downloads" sorts files into Images, Documents, Archives and so on. A card lists every move first, and "undo that organise" puts everything back.
- **What you copied:** the clipboard button offers Explain, Summarise and Translate, or ask "summarise the text I copied".
- **The screen:** the camera button takes a screenshot (without Orbie in it) for your next question, answered by a local vision model. Screenshots stay in memory only and are gone after 10 minutes.

Orbie searches and tidies only in Documents, Desktop and Downloads, unless you add folders in **Settings → Hands**. Programs and scripts ask before they run, and Orbie never deletes anything.

### Claude Code

If you use [Claude Code](https://claude.com/claude-code), **Settings → Claude Code → Install…** connects it to Orbie. It shows the exact change it will make to Claude Code's settings and backs the file up first. Then:

- Every Claude Code session you run shows on the island and in the **Code** tab.
- Permission requests come to the orb: **Allow**, **Allow for this session** or **Deny**. Claude's questions get a little form, and a plan can be approved or sent back. Orbie holds a request for a minute at most; after that Claude Code asks in its terminal as usual. If Orbie isn't running, Claude Code never waits for it.
- **Coding tasks:** say "ask Claude Code to fix the failing test in C:\dev\my-app" (or **Code → New task**). Orbie shows the folder and your exact words with a **Start** button. Claude Code then works there in the background, its steps stream into the Code tab, **Stop** ends it, and the end shows its summary and the files it changed.

### Memory

Tell Orbie about yourself ("I prefer short answers", "my sister's name is Priya") and it remembers, on your PC. Everything it remembers is listed in the **Memory** tab, where you can edit or delete each one.

## Privacy

Orbie is built around one rule: **your private data never leaves your PC.** Email, calendar, memories, notes, tasks, files, the clipboard and the screen are only ever handled by your local model in LM Studio.

- Only questions with nothing about you in them may go to Claude Code. Once a chat has used any of your data, nothing in it goes to the cloud, even with `/cloud`.
- Text other people wrote (an email, a calendar invite, a file, something you copied) is something to read, never to obey. After reading some, saving a memory or opening a website asks you first, showing exactly what would be saved or opened.
- Sending email, changing events, archiving email, tidying files and running programs always ask first. Nothing is ever deleted without a click.
- A link in a private answer shows its whole address before it opens.
- **No telemetry and no crash reporting.** What goes wrong is written to a log on your PC and sent nowhere. The update check asks GitHub only for the newest version: GitHub sees your PC's address and nothing else, and every Orbie sends the same anonymous ID.
- Your Google sign-in and other secrets are kept encrypted by Windows, readable only by your Windows account.

## What you need

| | |
|---|---|
| **Windows** | Windows 10 or 11, 64-bit |
| **Disk** | About 500 MB for Orbie, plus up to about 950 MB if you use voice (downloaded the first time you talk) |
| **For chat and everything private** | [LM Studio](https://lmstudio.ai) (free) with the **gpt-oss-20b** model, about 12 GB. A graphics card makes answers much faster. For screenshot questions, also **gemma-4-12b-qat** |
| **Optional, for harder general questions and coding** | [Claude Code](https://claude.com/claude-code), signed in to your Claude account. Orbie uses your existing login, with no API key |
| **Optional, for calendar and email** | A Google account, and a free Google Cloud client you make once (about 10 minutes, steps below) |

Everything Orbie uses is free: Orbie itself, LM Studio, the speech models and Google's APIs. Claude Code uses your existing Claude plan.

## Install

1. **Download** `Orbie-Setup-<version>.exe` from the [latest release](https://github.com/legendajar/Orbie/releases/latest) and run it.
2. **SmartScreen:** Windows may say "Windows protected your PC", because it hasn't seen this download often. Click **More info → Run anyway**.
3. **That's it.** Orbie installs for your Windows account only (no admin prompt), adds Start menu and desktop shortcuts, and starts: the orb pops in at the top of your screen and says hello.

Running the installer of a version you already have, or an older one, tells you so and changes nothing. Running a newer one updates Orbie in place, keeping your data, settings and shortcuts.

### Trust Orbie's certificate (recommended, once per PC)

Orbie is signed by **Harsh Solanki** with a free self-signed certificate, which Windows doesn't know about on its own. Trusting it once makes Windows name Orbie's publisher instead of "Unknown publisher". It also lets Orbie check that its updates really come from Harsh Solanki: without it, Orbie refuses to install its own updates, and you update by running a newer installer.

1. Download `Orbie-publisher.cer` from the [latest release](https://github.com/legendajar/Orbie/releases/latest) and double-click it.
2. On **Details**, check that **Thumbprint** is `014734FA47DDCD2D06FCCE60BF9952C18D3F00F0`. If it isn't, stop: it isn't Orbie's.
3. On **General**, choose **Install Certificate… → Current User → Place all certificates in the following store → Browse… → Trusted Root Certification Authorities → OK → Next → Finish**, and **Yes** when Windows asks.

The certificate can only sign code, and its private key never leaves the PC Orbie is built on.

## First-run setup

Orbie works in stages: each of these adds to it, and none needs the others.

### 1. LM Studio (chat, voice answers, your data, the brief)

1. Install [LM Studio](https://lmstudio.ai) and download **gpt-oss-20b**. For questions about screenshots, also download **gemma-4-12b-qat**.
2. Start its server on `127.0.0.1:1234`: in LM Studio's **Developer** tab, or with **Settings → Brains → Start LM Studio** in Orbie.
3. **Settings → Brains** now shows your local model online. Try "remind me in 10 minutes to stretch".

### 2. Claude Code (optional)

Install [Claude Code](https://claude.com/claude-code) and sign in once in a terminal by running `claude`. Orbie finds it by itself. To see your sessions on the orb, use **Settings → Claude Code → Install…**.

### 3. Google Calendar and Gmail (optional)

Orbie signs in to Google with your own Google Cloud client. It's free (no billing account) and takes about 10 minutes, once.

**Create the client.** Sign in to the [Google Cloud Console](https://console.cloud.google.com) with the account Orbie should use.

1. **Create a project**, for example "Orbie".
2. **APIs & Services → Library:** enable the **Gmail API**, the **Google Calendar API** and the **People API**.
3. **Google Auth Platform → Get started** (called "OAuth consent screen" in older consoles): app name "Orbie", your address as the support and contact email, Audience **External**.
4. **Data Access → Add or remove scopes:** add these five.

   | Scope | What Orbie does with it |
   |---|---|
   | `https://www.googleapis.com/auth/gmail.modify` | Read email, mark it read or archive it, save drafts and send (only after you click Send) |
   | `https://www.googleapis.com/auth/calendar.events` | See your events, and create, move or delete them (only after you confirm) |
   | `https://www.googleapis.com/auth/calendar.calendarlist.readonly` | See which calendars you show in Google Calendar |
   | `https://www.googleapis.com/auth/contacts.readonly` | Find a guest's address in your contacts |
   | `https://www.googleapis.com/auth/contacts.other.readonly` | Find a guest's address among people you've emailed |

5. **Audience → Publish app**, so it's **In production**. Don't submit it for verification: an app only you use doesn't need it. (In "Testing", Google ends the sign-in every 7 days. If Google won't let you sign in to the unverified app, set it back to Testing and add your own address under **Test users**; you'll then reconnect weekly.)
6. **Clients → Create client:** application type **Desktop app**, name "Orbie desktop". Copy the **Client ID** and **Client secret**, and keep them to yourself.

**Connect Orbie.**

1. In Orbie, open **Settings → Google**, paste the Client ID and Client secret, and click **Save client**.
2. Click **Connect Google account**. Your browser opens Google's sign-in.
3. Google warns "Google hasn't verified this app", because it's your own app. Click **Advanced → Go to Orbie (unsafe)**.
4. Tick **every** box and click **Continue**. A box left unticked turns that feature off; Settings lists what's missing, and **Reconnect** asks again.
5. The browser says "Orbie is connected to Google". Close the tab. **Today** now shows your events, and the **Inbox** your email.

**Disconnect** in Settings signs Orbie out at Google and forgets the sign-in on your PC.

### 4. Voice (optional)

Nothing to set up: hold **Ctrl+Alt+V** and talk. The speech model (Whisper Small, 589 MB, or the quicker but less accurate Whisper Base, 209 MB) and Orbie's voice (341 MB) download the first time, with their progress in the chat. If Windows blocks desktop apps from the microphone, Orbie says so and offers to open the right Windows settings.

## Shortcuts

| Shortcut | Does |
|---|---|
| **Ctrl+Shift+A** | Open or close the panel |
| **Ctrl+Alt+V** (hold) | Push-to-talk: speak, then let go |
| **Ctrl+Alt+W** | Start or end live talk |
| **Esc** | Stop what's going on: talking, live talk, an answer read aloud, then the open panel |

Change any of the three in **Settings → Shortcuts → Change**, then press the new keys. Each needs a key and at least two of Ctrl, Alt, Shift and Win, so Orbie never takes a shortcut other apps rely on (like Ctrl+C). If another app already holds one, Orbie tells you and keeps the old one.

## Updates

From version 1.2.0, Orbie keeps itself up to date:

1. It looks for a newer version a minute after it starts and every 6 hours, or right away with **Settings → About → Check for updates**.
2. A newer version downloads in the background. **Settings → About** shows its progress.
3. When it's ready, **Settings → About** and the tray offer **Restart to update**. Orbie never installs by itself, so pick a moment that suits you. Restarting stops an answer or a coding task still running.
4. Orbie closes, the installer shows its progress for a few seconds, and the new Orbie opens with your data, settings and shortcuts.

Orbie installs only an update signed by Harsh Solanki, on a PC that trusts Orbie's certificate (see [Install](#install)). Anything else is refused and deleted, and Settings says so. **What's new** in Settings → About opens the release notes here.

Versions 1.0.0 and 1.1.0 can't update themselves: download the newest installer and run it once.

## Uninstall and your data

Everything Orbie keeps is on your PC, in `%APPDATA%\orb-assistant`:

| What | Where |
|---|---|
| Settings | `settings.json` |
| Tasks, notes, reminders, memories, the Inbox, briefs and the live talk conversation | `orb.db` |
| Your Google sign-in | `secrets.json`, encrypted by Windows for your account only |
| Speech models and Orbie's voice | `voice-models` |
| The log | `logs\orbie.log` (**Settings → About → Open log folder**) |

To uninstall, use **Windows Settings → Apps → Installed apps → Orbie → Uninstall**. It removes Orbie and its Start with Windows entry, and keeps your data, so reinstalling picks up where you left off. To remove your data too, delete `%APPDATA%\orb-assistant`.

If you connected Claude Code, use **Settings → Claude Code → Uninstall…** first: Orbie's hooks do nothing while Orbie is gone, but they'd stay in Claude Code's settings.

## Troubleshooting

| You see | What to do |
|---|---|
| "Local brain offline" | LM Studio's server isn't running: **Settings → Brains → Start LM Studio** |
| A shortcut does nothing | Another app holds it. **Settings → Shortcuts** says which; choose another |
| "Claude Code wasn't found" | Check that `claude --version` works in a terminal, then reopen the panel |
| Calendar or email asks you to **Reconnect** | Google ended the sign-in (a new password, or Orbie's access removed). Click **Reconnect** |
| "The new version isn't signed by Harsh Solanki" | Your PC doesn't trust Orbie's certificate. Trust it (see [Install](#install)), or download the newest installer and run it |
| "Couldn't reach GitHub" in Settings → About | You're offline. Orbie looks again later |
| Nothing happens when you start Orbie again | Only one Orbie runs at a time: starting it again opens the running one's panel |

When something goes wrong, the log has the details: **Settings → About → Open log folder**. It stays on your PC, and it never grows past 3 MB. Next to it, `cloud-prompts.log` lists every message sent to Claude Code, so you can see for yourself that nothing private left your PC.

## Resource use

Measured on the installed app (a 16-thread PC on Windows 11), with nothing waiting in the Inbox:

| Orbie is | CPU in Task Manager |
|---|---|
| Awake and breathing | about 0.3% |
| Asleep (after 5 quiet minutes) | about 0% |
| Glowing for your attention | about 1% |

It uses about 175 MB of memory across its processes. Speech recognition, Orbie's voice and the wake word listener add to that only while they're in use, and close when idle.

## Versions

| Version | What changed |
|---|---|
| [1.2.2](https://github.com/legendajar/Orbie/releases/tag/v1.2.2) | Orbie's home is now this repository, renamed from `orbie-releases`: Orbie looks for updates here, and **What's new** opens these release notes. 1.2.0 and 1.2.1 still find their updates, since GitHub forwards the old name. |
| [1.2.1](https://github.com/legendajar/Orbie/releases/tag/v1.2.1) | Claude Code answers again. Since Claude Code 2.1.296, every question for Claude Code was refused with "Orbie stopped Claude Code because it loaded plugins", because that version lists the plugins built into Claude Code itself. Orbie now accepts those, and still stops Claude Code if any other plugin would apply. |
| [1.2.0](https://github.com/legendajar/Orbie/releases/tag/v1.2.0) | Orbie updates itself: it checks by itself and on request, downloads in the background, and installs on **Restart to update**, only if the update is signed by Harsh Solanki. |
| 1.1.0 | Signed as Harsh Solanki, so Windows names the publisher on a PC that trusts Orbie's certificate. The installer says when Orbie is already installed instead of reinstalling it. |
| 1.0.0 | The first release: chat with two brains, tasks, notes, reminders and memory, Google Calendar and Gmail, the morning brief, voice and live talk, Claude Code on the orb, and hands on your PC. |

## Built with

Orbie is built with [Electron](https://www.electronjs.org), [React](https://react.dev) and [Ant Design](https://ant.design). Its local models run in [LM Studio](https://lmstudio.ai), and on your PC it uses [Whisper](https://github.com/openai/whisper) (through [Transformers.js](https://github.com/huggingface/transformers.js)) to hear you, [Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) to speak, and [openWakeWord](https://github.com/dscripka/openWakeWord) with [Silero VAD](https://github.com/snakers4/silero-vad) for the wake word and live talk. Harder general questions and coding go to [Claude Code](https://claude.com/claude-code), if you use it.

Copyright © 2026 Harsh Solanki.
