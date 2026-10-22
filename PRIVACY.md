# WYS — Privacy Policy

WYS is maintained by Alex / elzuzu. This policy applies to the Mac App Store edition. [Version française](PRIVACY.fr.md).

Last updated: 22 October 2026

## In short

WYS transcribes your audio and video files **on your Mac**. The app collects no data about you, does not track you, and sends neither your audio, your text nor any usage statistics to anyone.

- The app asks for no network access and has no account: there is nothing to create or sign in to.
- The speech models are inside the app: nothing is downloaded, ever.
- No analytics, advertising or measurement SDK.

## What WYS keeps on your Mac

Inside the app's **container**, a folder that macOS creates for the app at `~/Library/Containers/com.elzuzu.wys/`:

- your **transcripts** (original text, corrections, speakers, markers, alerts) and the **summaries and translations** you asked for;
- the **recordings** made with the voice recorder and by dictation, which belong to the app (a recording of a call or a meeting can contain other people's voices; it stays on this Mac, in the container);
- a **search index** (a copy of the text, rebuilt on demand);
- your **settings** (audio language, model, watched folders), the **amount of free transcription time used**, and **bookmarks** that let the app reopen the files and folders you chose.

WYS does not copy the audio or video files you import: it keeps a bookmark to the original (one exception: a file that the Shortcuts app hands over without a location is copied into the container while it is transcribed, then deleted). If you move or delete the original, playback is no longer possible; the text stays.

## What WYS asks of the system

- **Files**: access to the files and folders you choose yourself (open panel, drag and drop, watched folders).
- **Microphone**: only for the voice recorder and dictation (from the File menu or an optional shortcut), after the system prompt. Transcribing a file does not need the microphone.
- **System audio**: only when you choose System Audio or Both in the voice recorder, after the system prompt ("System Audio Recording"). WYS records the sound the Mac plays only while you record, and never the screen.
- No access to calendar, contacts, location, photos or the screen image.

## Processing

Transcription and speaker identification are done by models **bundled in the app** and run on your Mac. Summaries and translations, when you ask for them, are done by Apple's language model built into macOS 26 or later (Apple Intelligence), which Apple documents as running on your Mac: WYS does not send your text to any remote artificial intelligence service. A summary or a translation is produced by a language model and can be wrong: check names, numbers and negations against the recording.

## Purchases

WYS is free to download and includes 60 minutes of free transcription. A one-time in-app purchase unlocks unlimited transcription. Purchases are handled by the App Store: WYS receives neither your payment identity nor your billing details. "Restore Purchases" is in the WYS menu.

## Your rights and control

- **Delete a transcript** from the library at any time. If the transcript comes from a recording made with WYS, the recording is deleted with it (the app tells you before). Files you imported are never deleted by the app.
- **Delete a summary or a translation** from the Summaries and Translations window.
- **Stop watching a folder** by removing it in Settings. **Turn off the dictation shortcut** in Settings.
- **Withdraw microphone access** at any time in System Settings › Privacy & Security › Microphone, and **system audio access** in System Settings › Privacy & Security › Screen & System Audio Recording.
- **Delete everything**: delete your transcripts in the library, quit and delete the app, then delete its container folder (`~/Library/Containers/com.elzuzu.wys/`); macOS does not remove it automatically when an app is deleted.
- WYS holds no account and no data about you outside your Mac, so there is nothing to request from us; nothing is shared with anyone.

## Children

WYS collects no data, including from children.

## Changes

Any change to this policy is recorded in this public repository, with its date.

## Support

*Help › Contact Support…* opens the public support page (GitHub) in your browser: that is a system action, WYS sends nothing itself. If you open an issue there, what you write is public and processed by GitHub under its own privacy policy: do not post recordings, transcripts or personal information. WYS never attaches logs or files by itself.

## Contact

Questions or privacy requests: **wys@elzuzu.ch.eu.org**. Bug reports and suggestions: https://github.com/elzuzu/wys-feedback (issues are public: do not post recordings, transcripts or personal information).
