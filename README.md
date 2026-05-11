# ⚡ FlashStudio

A clean, dark-themed flashcard study app that runs entirely in your browser — no installs, no accounts, no data sent anywhere.

🔗 **[Open FlashStudio →](vulturu1.github.io/FlashStudio/)**

If FlashStudio has helped your studying, please consider **⭐ starring the repository** — it helps others find the project and takes just a second!

---

## Getting Started

1. Open the link above
2. Go to the **Build Deck** tab and enter a deck title
3. Add cards manually using the card editor, or use the **AI Generator** tab to build a deck from your study materials in seconds
4. Hit **Start Studying** when you're ready

---

## Building a Deck Manually

Fill in the **Front** (question) and **Back** (answer) fields for each card. Optionally add:
- **Category** — group cards by topic or chapter for filtered study sessions
- **Sub-note** — a small clarifying hint shown beneath the answer
- **List Answer** mode — enter one item per line and each becomes a pill/tag on the card

---

## Building a Deck with AI

1. Open the **AI Generator** tab and fill in your topic and preferences
2. Click **Generate Prompt**, then **Copy Prompt**
3. Open any AI chat (Claude, ChatGPT, Gemini, etc.) and upload your study materials — textbook pages, lecture slides, PDFs, notes
4. Paste the prompt and press Enter
5. Copy the AI's JSON response into a text file and save it as `deck.json`
6. Back in FlashStudio, go to **Build Deck → ⬆ Import .json** and load the file

---

## Studying

- **Click the card** (or press `Space` / `Enter`) to flip it and reveal the answer
- Mark cards as **✓ Got it** or **⚑ Review Later** after flipping — only flagged cards appear in the Review filter
- Use the **filter tabs** to study by category or focus only on flagged cards
- **⇌ Shuffle** randomizes the current deck at any time

**Keyboard shortcuts:**

| Key | Action |
|-----|--------|
| `Space` / `Enter` | Flip card |
| `→` | Next card |
| `←` | Previous card |
| `K` | Mark "Got it" (after flip) |
| `R` | Mark "Review Later" (after flip) |

---

## Import / Export

Since there is no local storage, use **⬇ Export .json** to save your deck as a file and **⬆ Import .json** to reload it in any future session. The exported file contains your full deck and is compatible with the AI Generator format.

---

## License

[MIT](LICENSE) — free to use, modify, and distribute.