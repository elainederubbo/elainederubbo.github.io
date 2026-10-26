# Elaine's portfolio site

This folder is the whole website. Each page is one file. GitHub turns these files into the live site at **https://elainederubbo.github.io**.

## What's where

| File | What it is |
|---|---|
| `index.html` | Home page |
| `about.html` | About page |
| `portfolio.html` | Portfolio page with the case study cards |
| `case-studies/internal-alerts.html` | Internal Alerts (WMATA) case study |
| `case-studies/sus-benchmarking.html` | SUS Benchmarking (Higher Logic) case study |
| `styles.css` | Colors, fonts, and spacing for every page. You rarely need to touch this. |
| `images/` | Your photo |
| `cmt-tracker/` | Forwards old Spoon Tracker links to the new address. Leave it alone. |
| `404.html` | The page people see if a link is broken |

The Spoon Tracker app and its case study live in a different repository, **github.com/elainederubbo/spoon-tracker**. The portfolio card links out to it.

The diagrams in the case studies (like the Internal Alerts lifecycle map and the SUS benchmark chart) are built from text right on the page, not pictures, so you can edit their words the same way as any other words.

## How to change words on a page

1. Go to **github.com/elainederubbo/elainederubbo.github.io**.
2. Click the file you want, like `about.html`.
3. Click the **pencil icon** near the top right of the file. (Its label says "Edit this file.")
4. Find the words you want to change. Tip: press **Command + F** to search. Every spot waiting for your words starts with `[Elaine:`.
5. Change only the words **between** the tags. Tags are the bits in angle brackets, like `<p>` and `</p>`. Leave those alone.
   - Before: `<p>[Elaine: a paragraph or two.]</p>`
   - After: `<p>Your own words go here.</p>`
6. Click the green **Commit changes...** button at the top right. "Commit" just means "save this change, with a note about what you did."
7. In the box that pops up, type a short note, like "Fix typo on About page." Leave "Commit directly to the main branch" selected. Click **Commit changes**.

## How long until it shows up

Usually **1 to 2 minutes**. To watch it happen, click the **Actions** tab at the top of the repository. A yellow dot means it's still publishing. A green check means it's live.

If the live page still looks old after that, your browser may be showing a saved copy. Hold **Shift** and click the reload button.

## How to swap in a new picture

1. Name your picture exactly like the one it replaces. Your home page photo is `elaine-photo.jpg`.
2. Open the `images` folder on github.com.
3. Click **Add file**, then **Upload files**, and drag your picture in.
4. Click **Commit changes**. The new picture replaces the old one.

Then open the page and update the **alt text**. That's the `alt="..."` description screen readers say out loud.

## How to upload files into a folder

Dragging a whole folder onto GitHub's upload page puts every file at the top level instead of inside the folder. Instead, go straight to the folder's upload page and drag in just the files:

- Top level (like `index.html`, `portfolio.html`, `styles.css`): **github.com/elainederubbo/elainederubbo.github.io/upload/main**
- Case studies: **github.com/elainederubbo/elainederubbo.github.io/upload/main/case-studies**
- Pictures: **github.com/elainederubbo/elainederubbo.github.io/upload/main/images**

If a new page and `styles.css` both changed, upload `styles.css` first so the page never shows up unstyled.

## If something breaks

Every change is saved in the history. Open the file, click **History**, and you can see every earlier version and copy back from it. Nothing you do here is permanent.
