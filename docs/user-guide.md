# Lext — User Guide

Lext is a clean, distraction-free ebook reader for Android. It supports EPUB, MOBI, and plain text files, with tools for vocabulary learning built in.

---

## Opening a Book

1. Tap anywhere at the very bottom of the screen to show the menu bar.
2. Tap **Open**.
3. Choose a file from your device. Supported formats:
   - `.epub` — most ebooks
   - `.mobi` / `.azw` — older Kindle files
   - `.txt` — plain text

The app remembers the last book you opened and reopens it automatically next time.

> **Note:** Newer Kindle formats (KF8/AZW3) are not supported. If a MOBI file fails to open, it may be in the newer format.

---

## Reading

- **Turn pages:** swipe left (next page) or swipe right (previous page).
- **Page number:** shown at the bottom of every page — for example `12 / 340`.
- The status bar and any navigation buttons are hidden while reading for a clean, full-screen experience.

---

## Menu Bar

Tap near the **bottom of the page** (the page number area) to show the menu bar. The bar has two rows:

**Top row — reading settings:**
| Button | What it does |
|---|---|
| **Font** | Choose the typeface |
| **S / M / L / XL** | Change the font size |
| **☀ / ◑ / ☾ / ◈** | Cycle through reading themes |

**Bottom row — actions:**
| Button | What it does |
|---|---|
| **Open** | Open a new book |
| **Chapters** | Jump to a chapter |
| **My Words** | Manage vocabulary highlighting |
| **Dict** | Toggle word lookup on/off |

**Hiding the bar:** swipe to turn a page, or tap anywhere above the bar.

---

## Themes

Tap the theme button (top-right of the menu bar) to cycle through four themes:

| Icon | Name | Best for |
|---|---|---|
| ☀ | Day | Bright environments |
| ◑ | Warm | Comfortable warm tint, easier on the eyes |
| ☾ | Night | Dark mode for reading in the dark |
| ◈ | Eye Care | Green-tinted background, reduces eye strain |

Your theme choice is saved automatically.

---

## Font & Size

**Font:** tap **Font** in the menu bar to choose from six typefaces:
- Literata, Crimson Pro, Noto Serif, Lora, Source Serif 4, EB Garamond

**Size:** tap **S**, **M**, **L**, or **XL** in the middle of the top row. The selected size is shown with a highlighted chip.

Both settings are saved and apply immediately.

---

## Chapters

Tap **Chapters** in the menu bar to see the table of contents. Tap any chapter to jump straight to it.

> Chapters are only available for EPUB files that include a table of contents.

---

## Vocabulary Highlighting

Lext can colour-highlight words from vocabulary lists as you read, making it easy to spot words you are learning.

### Turning on highlighting

1. Open the menu bar and tap **My Words**.
2. A list of available word lists appears. Tick the ones you want and tap **Apply**.

Available lists:
| Name | Contents |
|---|---|
| IELTS | Common IELTS exam vocabulary |
| TOEFL | Common TOEFL exam vocabulary |
| GRE | Advanced GRE vocabulary |
| Phrases | Common English phrases and prepositions |
| My Words | Words you have saved yourself |

Each list uses a different colour that adapts to the current theme.

When any list is active, the button label changes to **My Words ✓**.

### Saving a word to My Words

Long-press any word in the text. A small dialog appears:
- **Add to My Words** — saves the word and highlights it immediately
- **Remove from My Words** — removes it if it was already saved
- **Cancel** — do nothing

### Managing My Words

1. Tap **My Words** in the menu bar.
2. Tap **Edit My Words**.
3. Tick the words you want to delete and tap **Remove selected**.

---

## Word Lookup (Dictionary)

Lext can look up the definition of any word — useful for words you do not know.

### Enabling lookup

Tap **Dict** in the menu bar to toggle it on. The button shows **Dict ✓** when active.

### Looking up a word

**Double-tap** any word in the text. A definition card appears showing:
- The word and its part of speech
- The definition
- An example sentence (when available)

Tap anywhere else to dismiss the card.

If the word is not found in its current form (e.g. "running"), Lext automatically tries the base form ("run") before giving up.

### Offline dictionary

By default, lookup uses the internet (Free Dictionary API). You can also download an offline dictionary so lookups work without a connection and respond instantly.

**To download:**
1. Open the menu bar.
2. **Long-press** the **Dict** button.
3. Tap **Download** (~10 MB).
4. A progress bar shows the download. Once complete, all lookups use the offline dictionary first, with the online API as a fallback.

**To delete the offline dictionary:**
Long-press **Dict** → tap **Delete**.

---

## Tips

- **EPUB loading is progressive** — the first chapter appears almost immediately while the rest loads in the background. You can start reading straight away.
- **Fast reload** — once a book has been opened once, it reloads from a local cache the next time, so it opens much faster.
- **Position is saved automatically** — closing the app and reopening it returns you to the exact page you were on.
- The app works best with serif fonts and the Warm or Eye Care themes for long reading sessions.
