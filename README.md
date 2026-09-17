# 📖 Chat Story Formatter & Reader

A sleek, standalone HTML tool designed to transform raw chat transcripts exported from **Shapes.inc** into a beautiful, customizable, distraction-free reading and storytelling experience.

Created to make life easier by **[Kaihime](https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390)** to help archive and relive cherished chat memories! 

---

## Key Features

- **Immersive Reader View:** Turns flat text transcripts into a formatted story layout with styled dialogue blocks, word counts, message counters, and estimated reading time.

- **Custom Theming:** Personalize text colors, bold text, and italicized elements, complete with a quick **Light/Dark Mode preset toggle**.

- **Command Cleanup (!wack, !sleep, !reset):** 
  - Keep raw commands as-is.
  - **Strip them out entirely** to remove clutter.
  - **Replace them with story text** (e.g., *[User sent a wack command]*) to maintain narrative pacing.

- **Timestamp & Model Filtering:** Choose whether to include timestamps and toggle AI model/engine tags on or off.

- **Export & Print:** Export your cleaned transcript back out as a `.txt` file or print/save it directly to PDF using your browser's print utility.

---

## How to Use

1. Download or clone this repository.

2. Open **`Chat Story Formatter and Reader.html`** (or whatever you named your HTML file) directly in any modern web browser (Chrome, Firefox, Edge, Safari)—no installation, servers, or coding knowledge required!

3. (Optional) Enter a **Story Title** and **Description/Author name** on the control panel.

4. Adjust your display preferences (timestamps, engine tags, command handling, and theme colors).
5. Upload your raw chat transcript `.txt` file and click **Open Styled Reader**.

---

## Important Notes & Limitations

- **AI Engine Tag Limitation:** The platform only embeds model names into individual message data if an active manual model override or switch was used. Messages running on standard default backend slots will not display an engine tag.

- **Command Response Behavior:** Choosing to "Strip out entirely" removes standalone command messages (like `!wack`). However, text or media responses sent by the shape in reply to those commands should be reviewed; media-only link lines are automatically filtered, but custom text replies from your shape can be manually fine-tuned in the final exported text file.

---

## Credits & Sharing

- **Creator:** Designed and conceptualized by **Kaihime**.

- **License / Usage:** Please give proper credit if you share or fork this tool, and do not claim it as your own original work. 

Need help, want to suggest improvements, or just hang out? Find me in my [Shapes.inc room](https://talk.shapes.inc/chat/2df43177-b5e0-43af-a10b-4c39bf155390)!
