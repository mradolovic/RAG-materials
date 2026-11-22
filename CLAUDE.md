# CLAUDE.md: link list workflow

This repo is a curated link collection. **`linkovi.txt` is the user's raw inbox** of links and is kept in the repo, where the user adds new links over time. **`README.md` is the polished list** made from it.

## How to update

1. Read `linkovi.txt` and compare every URL against the **Processed links** list below.
2. For each new URL:
   - Get its real title (YouTube: `https://www.youtube.com/oembed?url=<url>&format=json` gives `title` and `author_name`; websites: the page `<title>`).
   - Add it to the matching section/table in `README.md`, or create a new section if none fits. Use the user's headings and notes in `linkovi.txt` as hints, but group by actual topic.
   - Skip duplicates. Keep timestamps such as `&t=92s`.
   - Table columns: Video | Channel | Description | Added | My comments (sites: Site | Description | Added | My comments).
   - Description: one short sentence about the video. Added: the date it was processed.
   - Put new rows at the **top** of their table (newest first). A new section for new links goes first within its group.
   - Leave **My comments** empty for new rows, and never change or drop the user's existing comments.
3. Add each new URL to **Processed links** below, along with the README section it went into.
4. Never edit or delete `linkovi.txt`.

## README sections

- 🔭 Radio Astronomy — Videos → *Talks & Lectures*, *Fundamentals*, *Hydrogen Line (1420 MHz) & DIY Telescopes*
- 🔌 Electronics & Circuit Design — Videos
- 🌐 Useful Sites

## Processed links

Last updated: 2026-11-22

| URL | README section |
|-----|----------------|
| https://www.youtube.com/watch?v=QUq971c_zOs | Electronics & Circuit Design |
| https://www.youtube.com/watch?v=_2EBCzyrqTA | Radio Astronomy / Fundamentals |
| https://www.youtube.com/watch?v=0TwnZhiEc3A | Radio Astronomy / Fundamentals |
| https://www.youtube.com/watch?v=z_tF4JZFgLo | Radio Astronomy / Fundamentals |
| https://www.youtube.com/watch?v=AOgvjRXnins | Radio Astronomy / Fundamentals |
| https://www.youtube.com/watch?v=C6NCefVxNL8 | Radio Astronomy / Hydrogen Line & DIY |
| https://www.youtube.com/watch?v=HeOkW17gJ_w&t=92s | Radio Astronomy / Hydrogen Line & DIY |
| https://www.youtube.com/watch?v=wylZjuO-gEc | Radio Astronomy / Hydrogen Line & DIY (listed twice in linkovi.txt) |
| https://lambda.gsfc.nasa.gov/product/foreground/f_images.html | Useful Sites |
| https://www.haystack.mit.edu/haystack-memo-series/vsrt-and-mosaic-memos/ | Useful Sites |
| https://www.youtube.com/watch?v=W-9w_EDOKKA | Electronics & Circuit Design (listed under USEFUL SITES in linkovi.txt) |
| https://www.youtube.com/watch?v=mhR4F4OB5hI | Radio Astronomy / Talks & Lectures |
| https://www.youtube.com/watch?v=sIZ4u0-T_9w | Radio Astronomy / Talks & Lectures |
| https://www.youtube.com/watch?v=d7QSjevNQ30 | Radio Astronomy / Talks & Lectures |
