<div align="center">

# TajiCast

### The verse, on screen, the moment it's spoken.

**TajiCast** is a Windows app that listens to your preacher and detects the Bible verses being
read or referenced — live — then puts them on screen. Show the verse full-screen on your
projector or displays, and, when you're livestreaming, send clean lower-thirds over NDI to your
switcher. No typist frantically searching for references. No dead air. Just the right verse, on
screen, at the right moment.

### ⬇️ [**Download for Windows**](https://github.com/stefanwallach/TajiCast-releases/releases/latest/download/TajiCast-Setup.exe)

Free · Windows 10 & 11 (64-bit) · [All versions & release notes](https://github.com/stefanwallach/TajiCast-releases/releases)

</div>

---

## What TajiCast does

During a live service, TajiCast runs quietly in the background and:

1. **Listens** to the sermon through your microphone or audio input.
2. **Transcribes** the speech in real time.
3. **Detects** the Bible verse being spoken — whether the preacher says a reference out loud
   ("turn to John 3:16") or simply reads or paraphrases the passage.
4. **Displays** that verse on screen — full-screen on your projector or displays for the
   congregation, and, when livestreaming, as a lower-third sent over NDI to your switcher.

The person running the booth just watches it happen — and can approve, pin, or change what's on
screen at any time. And because TajiCast is transcribing the whole message as it listens, every
service also leaves you with a full transcript and, on demand, a set of sermon notes to reuse.

## Key features

- **Real-time verse detection** — finds the passage as it's spoken, by spoken reference or by the
  words themselves.
- **Smart search** — type a reference like `Mark 3:5` *or* a phrase like `Jesus walks on water`
  and TajiCast lands on the same verse. Search by idea, not just by chapter number.
- **Full-screen display output** — the main way to show verses: send a full verse display to a
  projector or second screen for your congregation.
- **NDI output for live streaming** — when you're streaming, send broadcast-ready lower-thirds
  straight into **vMix, OBS**, or any NDI-capable switcher.
- **Beautiful, ready-made themes** — a range of built-in designs for both full-screen displays
  and NDI lower-thirds, including full-width styles and options tuned for different pulpit color
  schemes. Customize colors, fonts, and layout to match your church's look.
- **Multiple Bible translations** — switch between translations, and import additional ones.
- **Works completely offline** — the Bible database and the AI detection model are bundled inside
  the app. Once installed, it needs no internet to detect and display verses.
- **Manual control when you want it** — pin a verse, search and push one yourself, or let the
  detection run hands-free.
- **Cross-references and reading mode** — follow along through a passage and surface related
  verses.
- **Live sermon transcripts** — every service is transcribed and saved automatically, ready to
  search, edit and export.
- **Automatic sermon notes** — turn any transcript into structured notes (key points, scripture
  references, quotes and applications) with your own AI provider or a local model, all organized in
  a built-in Content Studio.
- **Remote control** — trigger and control output from other tools over OSC or HTTP.

## Speech recognition options

TajiCast can transcribe using a cloud speech provider for the highest live accuracy, or run
locally when you'd rather not depend on the internet:

- **Cloud providers** — Deepgram, ElevenLabs, OpenAI, Groq, Google Gemini, and Anthropic Claude
  (bring your own API key).
- **Local / offline** — on-device Whisper and Ollama, no account required.

You can also see your usage per model and, for supported providers, check your account balance
right inside Settings.

## Transcripts, sermon notes & Content Studio

TajiCast does more than put verses on screen — because it's already transcribing the sermon, it
turns each service into reusable content:

- **Every service is saved** — each transcription session is stored automatically with its date,
  length and word count, so you build up a searchable archive of your preaching without lifting a
  finger.
- **One-click sermon notes** — from any transcript, generate a structured set of notes: a title,
  the key points, the scripture references, memorable quotes and practical applications. It follows
  strict rules to use *only* what was actually said — no invented references or quotes.
- **Your AI, your choice** — generate notes with OpenAI, Claude, Gemini or Groq using your own
  key, or run a **local model with Ollama** so nothing leaves your computer.
- **Content Studio** — a built-in library to organize, edit, search and **export** your transcripts
  and notes (as Markdown or text). You can even combine several sessions into one unified set of
  notes.

The result: one service gives you the on-screen verses, a full transcript, and ready-made notes for
your podcast show notes, a blog post, a study handout, or a week of social content.

## Who it's for

- **Churches and ministries** running live services with a projector or a live stream.
- **Production volunteers** who want the right verse on screen without hunting for it mid-sermon.
- **Multi-campus and broadcast teams** using vMix or OBS who need clean NDI graphics.

## Download & install

1. Click **[Download for Windows](https://github.com/stefanwallach/TajiCast-releases/releases/latest/download/TajiCast-Setup.exe)** and run **TajiCast-Setup.exe**.
2. Windows may show a blue **"Windows protected your PC"** screen. This appears because the
   installer isn't code-signed yet — it's expected and safe. Click **More info → Run anyway**.
3. Follow the installer prompts, then launch TajiCast.
4. Pick your audio input, choose a theme, select your output display, and you're ready.

## System requirements

- Windows 10 or 11 (64-bit)
- ~2 GB free disk space (the Bible database and AI model are bundled for offline use)
- A microphone or audio input for live transcription
- A second monitor (for projector output) and/or an NDI-capable switcher such as vMix or OBS,
  if you want to broadcast

## Frequently asked questions

**Does it need the internet?**
No — verse detection and display work fully offline. An internet connection is only needed if you
choose a cloud speech-recognition provider; local transcription works without one.

**Why does Windows warn me when I install it?**
The installer isn't code-signed yet, so Windows SmartScreen labels it "unknown publisher." Click
**More info → Run anyway** to install. Code signing is planned for a future release.

**Which live-streaming software does it work with?**
Anything that accepts NDI — including vMix and OBS (with the NDI plugin).

**Can I use my own Bible translation?**
Yes. TajiCast ships with translations built in and lets you import additional ones.

**Does it do more than display verses?**
Yes. As it runs, TajiCast transcribes the whole sermon and saves every service automatically. From
that transcript it can generate structured sermon notes — key points, references, quotes and
applications — which you can edit and export from its built-in Content Studio. Transcription and
notes can run fully on-device, or use an AI provider of your choice.

## Support

Have a question, found a bug, or want to request a feature?
[**Open an issue**](https://github.com/stefanwallach/TajiCast-releases/issues) and we'll take a look.

---

<div align="center">
<sub>TajiCast · Real-time Bible verse detection &amp; broadcast for live sermons</sub>
</div>
