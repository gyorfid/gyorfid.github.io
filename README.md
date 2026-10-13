# Dávid Győrfi: personal website

The website is live at **https://gyorfid.github.io**. It updates by itself 1–2 minutes after you save a change here.

## Where everything is

| What you want to change | File to edit |
|---|---|
| Home page text | `_pages/about.md` |
| Publications | `_pages/publications.md` |
| Talks | `_pages/talks.md` |
| Teaching | `_pages/teaching.md` |
| CV (the PDF behind the "CV" menu item) | `files/Gyorfi_CV.pdf` |
| Photo | `images/profile.jpg` |
| Sidebar: name, job title, email, links (ORCID, Google Scholar…) | `_config.yml` (the `author:` section near the top) |
| Top menu | `_data/navigation.yml` |

## Editing text (publications, talks, teaching, home page)

1. Click the file name above (or browse to it), then click the **pencil icon** (top right of the file).
2. Make your change. The top of each page file has a short note showing the pattern for a new entry. Copy an existing entry and edit it.
3. Click **Commit changes…**, then **Commit changes** again.
4. Wait 1–2 minutes and refresh the website. If you still see the old version, force a refresh: Ctrl+F5 on Windows or Cmd+Shift+R on a Mac.

Formatting:

- `*italic*` gives *italic*, and `**bold**` gives **bold**.
- `[link text](https://example.com)` makes a link.
- `## Heading` is a section heading (e.g. a year on the Talks page), and `### Title` is one entry.
- To start a new line inside an entry, end the previous line with two spaces.

## Replacing your CV

1. In Word, save your CV as a PDF named exactly **`Gyorfi_CV.pdf`**.
2. Open the `files` folder here, then click **Add file → Upload files**.
3. Drag the PDF in, then click **Commit changes**. The new file replaces the old one.

## Adding a PDF (a paper or slides)

Upload it to the `files` folder in the same way, ideally with a simple name without accents or spaces (e.g. `Gyorfi_2026_zhat.pdf`). Then link to it from a page as `/files/Gyorfi_2026_zhat.pdf`.

## Changing the photo

Upload a square photo named **`profile.jpg`** into the `images` folder.

## Changing the sidebar

In `_config.yml`, under `author:`, fill in a line to make a link appear, or empty it to hide it. For example:

```yaml
  orcid            : "https://orcid.org/0000-0000-0000-0000"
  googlescholar    : "https://scholar.google.com/citations?user=XXXXXXX"
```

Keep the quotation marks and the spaces at the start of the line exactly as they are. This file is the one place where a typo can stop the site from updating.

## If something goes wrong

- If a change doesn't appear after a few minutes, open the **Actions** tab. A red ✗ means the update failed. Your website stays as it was before, so nothing breaks for visitors.
- Every change is saved in the file's **History**, so you can always go back to an earlier version.
- When in doubt, ask Claude.
