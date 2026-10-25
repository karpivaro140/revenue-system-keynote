# One Connected Revenue System: animated HTML presentation

Five slides, built as a single HTML file. All data is **illustrative**: none of it is company data.

## Present it
1. Open `revenue-system-keynote.html` in **Google Chrome**. Other current browsers should work but weren't tested.
2. Press **F** for fullscreen. Any 16:9 screen works; other shapes get black bars instead of a rearranged slide.
3. Navigate:
   - **→ / Space / Page Down**: next slide
   - **← / Page Up**: previous slide
   - **Home / End**: first / last slide
   - A trackpad scroll or a swipe also works.
4. Each slide builds itself in 3–5 seconds. Let it finish before you advance. Slide 1's orbit keeps a slow light pulse running while you speak.

You need an internet connection the first time so the fonts load from Google Fonts. Offline, the slides fall back to system fonts and the type spacing will look off.

## Edit the text
- Press **E**, or hover over the top-left corner and click **EDIT**. Headlines and descriptions become editable.
- Edits save automatically in this browser only.
- **Ctrl/Cmd + S** downloads an edited copy of the file.
- Press **E** again before presenting, so arrow keys don't move the text cursor.

## What's in the folder
| Path | What it is |
|---|---|
| `revenue-system-keynote.html` | The presentation. Self-contained; no other files needed |
| `revenue-system-keynote-stills.pdf` | Static 5-page handout (no motion) |
| `stills/` | Each slide in its final built state, as a 1920×1080 PNG |
| `previews/` | The three opening-slide directions explored (A was chosen) |
| `qa/` | Render checks and real-time playback frames used for review |

## Known limits
- The motion only exists in the HTML version. The PDF and PNGs are still images, and there is no video export, because ffmpeg isn't installed.
- The two camera zooms (into the system after slide 1, and back out to it on slide 5) measured about 45–50 fps in headless Chrome on this Mac under load. The other transitions run at about 55–60 fps. Do a quick rehearsal on the presenting laptop.
- This is not a PowerPoint file, so it can't be edited in PowerPoint.
