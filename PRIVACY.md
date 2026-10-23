# WYS — Privacy Policy

WYS is published under the name **Otter Appworks**. Its legal operator is **Alexandre Wyer**, a sole proprietor in Switzerland, who is also the controller for information voluntarily provided to support. This policy covers the Mac App Store, iPhone and iPad editions. Platform-specific behavior is identified below. [Version française](https://github.com/elzuzu/wys-feedback/blob/main/PRIVACY.fr.md).

Last updated: 23 October 2026

## iPhone and iPad edition

WYS transcribes audio and video files locally with one Parakeet speech model bundled in the app. No recordings, transcripts, usage statistics or model-training data are sent to us. There is no account, advertising, analytics SDK, cloud transcription or downloaded speech model. This edition imports files; it does not record the microphone or system audio, identify speakers, or use Apple Intelligence.

When you select a file in Files, the system or its file provider may first download it from a location you chose, such as iCloud Drive. WYS copies that selected file into its private Application Support/Imports folder so playback does not depend on the original remaining available. It also stores transcripts and timestamps, audio-language preferences, minimal local file bookmarks, the locally used trial allowance and the versioned terms decision. It does not access other files or require Photos, Contacts, Calendar, location or microphone permissions. Imported originals remain yours and are not deleted by WYS.

These local user files remain eligible for system backups, including iCloud Backup if you enable it. Apple and your chosen file/backup provider handle those services under their own policies; WYS has no developer-operated cloud storage and does not initiate a separate upload. Keep independent copies. Deleting or reinstalling the app can remove its local library, imported copies, preferences, trial ledger and terms decision; a trial reset is not a synchronized cross-device allowance. Apple purchase entitlements are restored separately through StoreKit.

You can copy a transcript or explicitly share/export it. WYS writes an export copy into its temporary folder and attempts to remove it when sharing completes or is cancelled; the receiving app/provider controls the copy you sent. Do not share confidential material unintentionally. Deleting a transcript also removes its app-owned imported copy when available; the source you selected in Files is left alone. Settings offers the terms, this policy, notices and support. The same App Store non-consumable product unlocks transcription; Apple processes billing and transaction verification, and WYS receives no payment identity or card details. A restore is requested only when you tap Restore Purchases.

Support reports and contact details are handled as described in the support/contact sections below. Public GitHub issues are public: do not attach private recordings or transcripts. No attachment or diagnostic is sent automatically. The terms decision remains local and is never a blanket consent to processing.

## Mac edition

The following sections describe the Mac edition. Features such as voice recording, watched folders, Spotlight, contextual review and summaries are not offered by iPhone/iPad 1.0.

## In short

WYS transcribes your audio and video files **on your Mac**. The app collects no data about you, does not track you, and sends neither your audio, your text nor any usage statistics to anyone.

- The app asks for no network access and has no account: there is nothing to create or sign in to.
- The speech models are inside the app: nothing is downloaded, ever.
- No analytics, advertising or measurement SDK.

## What WYS keeps on your Mac

Inside the app's **container**, a folder that macOS creates for the app at `~/Library/Containers/com.elzuzu.wys/`:

- your **transcripts** (original text, corrections, speakers, markers, alerts) and the **summaries and translations** you asked for, with the **names, terms and description** you typed for the second pass with context;
- the **recordings** made with the voice recorder and by dictation, which belong to the app (a recording of a call or a meeting can contain other people's voices; it stays on this Mac, in the container);
- a **search index** (a copy of the text, rebuilt on demand);
- your **folders**, **favorite passages**, **text rules** and **summary prompts** (what you typed, kept as plain files), and the settings of **automatic export**, with a bookmark to the export folder you chose;
- your **settings** (audio language, model, watched folders), the **amount of free transcription time used**, and **bookmarks** that let the app reopen the files and folders you chose.

WYS does not copy the audio or video files you import: it keeps a bookmark to the original (one exception: a file that the Shortcuts app hands over without a location is copied into the container while it is transcribed, then deleted). If you move or delete the original, playback is no longer possible; the text stays. While a file is transcribed with speaker identification on, WYS writes a temporary decoded copy of its audio in the container (about 460 MB for two hours); it is deleted when the transcription ends, and any copy left by a crash is deleted at the next launch. The Shortcuts actions of WYS (get the text of a transcription, open it, search) hand the text of transcriptions you choose to the Shortcuts app on your Mac, which you control; WYS itself sends nothing anywhere.

## What WYS asks of the system

- **Files**: access to the files and folders you choose yourself (open panel, drag and drop, watched folders).
- **Microphone**: only for the voice recorder and dictation (from the File menu or an optional shortcut), after the system prompt. Transcribing a file does not need the microphone.
- **System audio**: only when you choose System Audio or Both in the voice recorder, after the system prompt ("System Audio Recording"). WYS records the sound the Mac plays only while you record, and never the screen.
- No access to calendar, contacts, location, photos or the screen image.

## Processing

Transcription and speaker identification are done by models **bundled in the app** and run on your Mac. Summaries, translations and the suggestions about wrong words of the second pass with context (*Transcript › Review with Context…*), when you ask for them, are done by Apple's language model built into macOS 26 or later (Apple Intelligence), which Apple documents as running on your Mac: WYS does not send your text to any remote artificial intelligence service. A summary or a translation is produced by a language model and can be wrong: check names, numbers and negations against the recording. For the second pass, WYS checks names, terms and spellings itself, on your Mac, without any model; the names and terms you type and your short description are saved with the transcription on your Mac and, when the on-device model is available, given to it together with the text of the transcript to suggest fixes for wrong words. The second pass applies on its own only the corrections it can back up (your names and terms, spellings used elsewhere in the text), as a new version that you can review, refuse or undo; the original transcription is never overwritten, and suggestions about wrong words are applied only when you accept them.

## Optional features that write outside the app

All of these are off until you turn them on or choose a folder. Nothing in this section sends anything over the network.

- **Spotlight** (*Settings › Spotlight*): the title and text of each finished transcript are given to the Spotlight index of your Mac (Apple's Core Spotlight, on this Mac only), so you can find a transcript from anywhere. Turning the option off removes all of them; deleting a transcript removes its entry.
- **Export All…** and **Automatic Export** (*Settings › Automatic Export…*): WYS writes files (TXT, SRT, DOCX and the other formats you choose) only into the folder you chose, with a bookmark that lets it write there again. Existing files are never overwritten.
- **Services** (*Services › Transcribe with WYS* in the Finder): the system hands WYS the audio or video files you selected, like a drop on the Dock icon.

## Purchases

WYS is free to download and includes 60 minutes of free transcription. A one-time in-app purchase unlocks unlimited transcription. Purchases are handled by the App Store: WYS receives neither your payment identity nor your billing details. "Restore Purchases" is in the WYS menu.

## Your rights and control

- **Delete a transcript** from the library at any time. If the transcript comes from a recording made with WYS, the recording is deleted with it (the app tells you before). Files you imported are never deleted by the app.
- **Delete a summary or a translation** from the Summaries and Translations window.
- **Stop watching a folder** by removing it in Settings. **Turn off the dictation shortcut**, **Spotlight** and **Automatic Export** in Settings.
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

## First-launch terms decision

Versions that display a first-launch terms screen keep the decision **on your Mac only**: agreement or continuation under the existing license, terms revision, fingerprints of the complete terms, language of the terms, date, app version/build and edition, and a copy of the text displayed. Merely opening or closing the screen does not record an agreement. Choosing the existing-license option is recorded separately and is never treated as acceptance. We do not receive this record or attach it to reports automatically. It contains no client account or hardware identifier, recording, filename or personal file path. Your own device backups may include it. Clearing the app’s preferences/container removes it and the screen will appear again. This record is not identity authentication or blanket consent to data processing.
