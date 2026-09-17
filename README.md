# Chat Story Formatter, Reader & Extractor

A complete toolkit designed to extract, format, and transform raw chat transcripts from **Shapes.inc** into a beautiful, customizable, distraction-free reading and storytelling experience.

> ❗**NOTE:** You require a pc for this so that you can use the browser inspect/dev tools on your pages. 

Created to make life easier by **Kaihime (@Shorai)** to help archive and relive cherished chat memories! 

## Launch the Tools Online
* **[📖 Read the Extraction Guide](How%20to%20Extract%20Chat%20History.html)**
* **[👉 Open the Chat Story Formatter & Reader](Chat%20Story%20Formatter%20and%20Reader.html)**

---

## The Complete Workflow

To turn your chat room memories into a clean story book, the process uses two parts:

### Part 1: Extracting the Chat (.txt)
Before formatting, you need to pull your conversation history out of your chat room:
1. Launch from here: * **[📖 Read the Extraction Guide](How%20to%20Extract%20Chat%20History.html)**
2. Once this step is completed, it will generate a raw `.txt` transcript file containing your messages, timestamps, and model/engine metadata.

### Part 2: Formatting & Reading
1. * Launch the page from here: **[👉 Open the Chat Story Formatter & Reader](Chat%20Story%20Formatter%20and%20Reader.html)**
2. (Optional) Enter a **Story Title** and **Description/Author name** on the control panel.
3. Adjust your display preferences:
   - Toggle timestamps on/off.
   - Toggle AI model/engine tags on/off.
   - Choose your command handling (`!wack`, `!sleep`, `!reset`) to keep them, replace them with story text, or strip them out entirely.
4. Customize your theme colors or use the **Light/Dark Mode toggle**.
5. Upload your raw chat transcript `.txt` file and click **Open Styled Reader**.

---

## Key Reader Features

- **Immersive Layout:** Formats flat transcripts into clean dialogue blocks with word counts, message counters, and estimated reading time.
- **Custom Theming:** Personalize text colors, bold text, and italicized elements.
- **Command Cleanup:** Manage raw bot-interaction commands seamlessly without cluttering narrative pacing.
- **Export & Print:** Export your cleaned transcript back out as a `.txt` file or print/save it directly to PDF using your browser's print utility. 
> NOTE: PLEASE ALWAYS SAVE YOUR ORIGINAL FILE THAT WAS EXPORTED AS WELL even if exporting from here. I don't take responsibility if this accidently removes or missed a message. 

---

## Important Notes & Limitations

- **AI Engine Tag Limitation:** The platform only embeds model names into individual message data if an active manual model override or switch was used. Messages running on standard default backend slots will not display an engine tag.

- **Command Response Behavior:** Choosing to "Strip out entirely" removes standalone command messages (like `!wack`). However, custom text responses sent by your shape in reply to those commands can be manually fine-tuned in the final exported text file if needed.

---

### Frequently Asked Questions (FAQ)

#### Is this safe to run? Will I get banned?

* **Yes, it is 100% safe.** These scripts do not automate clicking, bypass platform logic, or interact with the server in any unauthorized way.

* **You will not get banned.** The script simply reads text that is already fully visible on your own screen and packages it into a local download.

#### Can the platform developers see that I ran this? Do they track it?

* **No.** The code does not make any network requests (`fetch`, `XMLHttpRequest`, or API calls). It doesn't talk to an external server or send data anywhere.

* Because everything happens entirely offline inside your browser’s local memory, platform developers have zero visibility or logs indicating that you exported your data.

#### Where does my data go? Does it leave my computer?

* **No data ever leaves your network.** When you trigger the script, your browser generates a local data file (`data:text/json...`) and forces your browser to download it straight to your computer's local hard drive (`Downloads` folder). Your content stays completely private to you.

#### What if I am worried or suspicious of the code?

* **Verify it yourself!** If you want absolute peace of mind, you can copy any of these JavaScript scripts and paste them into an AI assistant (like ChatGPT or Gemini) and ask: *"Can you review this code and confirm it doesn't contain any malicious code, external trackers, or network requests?"* You'll see that it's just basic DOM reading and file-saving logic.


#### Will these scripts break if the platform updates its UI?

* Because the scripts use flexible, adaptive selectors rather than rigid hardcoded maps, they are built to be resilient. However, if the platform completely redesigns its underlying class names in a major layout update, a script might need a minor selector tweak. If something stops working, check the console or let me know on shapes.inc!

---

## Credits & Sharing

- **Creator:** Designed and conceptualized by **Kaihime**.
- **License / Usage:** Please give proper credit if you share or fork this tool, and do not claim it as your own original work. 

Need help, want to suggest improvements, or just hang out? Find me in my [Shapes.inc room](https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390)!(https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390)!
