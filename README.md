# Shapes.inc Backup Tools

A growing toolkit of scripts and pages that let you pull your own data out of **Shapes.inc** — chat history, Knowledge Base entries, and (soon) more — and turn it into something you can keep, read, and revisit on your own terms.

> ❗**NOTE:** You require a pc for this so that you can use the browser inspect/dev tools on your pages.

Created to make life easier by **Kaihime (@Shorai)** to help archive and relive cherished chat memories!

---

# 🖋️ Chat Story Formatter, Reader & Extractor
Pulls a raw chat transcript out of your chat room and turns it into a clean, distraction-free story reader — with theming, timestamp/command toggles, and export back out to `.txt` or PDF.

**How to use:**
1. **[Open the Extraction Guide](How%20to%20Extract%20Chat%20History.html)** and follow it to generate a raw `.txt` transcript of your messages, timestamps, and model/engine metadata.
2. **[Open the Chat Story Formatter & Reader](Chat%20Story%20Formatter%20and%20Reader.html)** and upload that `.txt` file.
3. (Optional) Add a **Story Title** and **Description/Author name**.
4. Set your display preferences — timestamps on/off, model tags on/off, and how to handle commands like `!wack`, `!sleep`, `!reset` (keep, replace with story text, or strip entirely).
5. Pick a theme or use the **Light/Dark Mode toggle**, then click **Open Styled Reader**.

**Features:**
- **Immersive Layout** — flat transcripts become clean dialogue blocks with word counts, message counters, and estimated reading time.
- **Custom Theming** — personalize text colors, bold text, and italicized elements.
- **Command Cleanup** — manage raw bot-interaction commands without cluttering narrative pacing.
- **Export & Print** — save the cleaned version back out as `.txt`, or print/save to PDF via your browser.

> NOTE: PLEASE ALWAYS SAVE YOUR ORIGINAL EXPORTED FILE AS WELL, even if exporting from here. I don't take responsibility if this accidentally removes or misses a message.

---

# 📚 Knowledge Base Exporter (COMING SOON)
Backs up everything on your Shape's Knowledge page — General, Commands, Relationships, and any custom tabs — into one JSON file. Run it alongside the chat extraction above for a full backup of both your conversations *and* your Shape's memory/persona data.

**How to use:**
1. OPEN HERE and follow the guide.
2. On your Shape's Knowledge page, open your browser console and paste in the script.
3. Capture each tab one at a time, then click download to save the combined file.

**Features:**
- **Multi-Tab Capture** — walk through General, Commands, Relationships, and custom tabs one at a time via a floating on-page panel.
- **Single Combined File** — everything bundles into one JSON file, tagged with the Shape name and export timestamp.
- **Fully Local** — same guarantee as the chat tools above: nothing is uploaded, and the file goes straight to your Downloads folder.

---

# 🔜 Coming Soon
More of your Shape's data, made backup-able:
- **Shape Profile Exporter** — pull your Shape's core profile info into a keepable file.
- **Personality Exporter** — back up personality settings and traits.
- **AI Engine Page Exporter** — export the engine/model configuration pages.

Watch this space, or check in on my [Shapes.inc room](https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390) for updates.

---

# Important Notes & Limitations

- **AI Engine Tag Limitation:** The platform only embeds model names into individual message data if an active manual model override or switch was used. Messages running on standard default backend slots will not display an engine tag.
- **Command Response Behavior:** Choosing "Strip out entirely" removes standalone command messages (like `!wack`). Custom text responses your shape sent in reply to those commands can still be manually fine-tuned in the final exported text file if needed.

---

# FAQ

**Is this safe to run? Will I get banned?**
Yes. These scripts don't automate clicking, bypass platform logic, or interact with the server in any unauthorized way. They just read text already visible on your own screen and package it into a local download.

**Can the platform developers see that I ran this? Do they track it?**
No. The code makes no network requests (`fetch`, `XMLHttpRequest`, or API calls) — it doesn't talk to an external server or send data anywhere. Everything happens entirely offline in your browser's local memory, so there's nothing for platform developers to see or log.

**Where does my data go? Does it leave my computer?**
No data leaves your network. The script generates a local file (`data:text/json...`) and downloads it straight to your `Downloads` folder. Your content stays completely private to you.

**What if I'm worried or suspicious of the code?**
Verify it yourself — copy any of these scripts, paste them into an AI assistant (ChatGPT, Gemini, etc.), and ask it to confirm there's no malicious code, external trackers, or network requests. You'll find it's just basic DOM reading and file-saving logic.

**Will these scripts break if the platform updates its UI?**
The scripts use flexible, adaptive selectors rather than rigid hardcoded maps, so they're built to be resilient. A major redesign of the platform's underlying class names might need a minor selector tweak — if something stops working, check the console or let me know on shapes.inc!

---

# Credits & Sharing

- **Creator:** Designed and conceptualized by **Kaihime**.
- **License / Usage:** Please give proper credit if you share or fork this tool, and do not claim it as your own original work.

Need help, want to suggest improvements, or just hang out? Find me in my [Shapes.inc room](https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390)!
