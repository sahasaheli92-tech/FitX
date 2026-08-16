# MOVE — 5-Day Weekly Gym Plan

An interactive fitness site: warm-up library, a 5-day weekly plan with rep
logging, cooldown stretches, a full-body mobility flow, and a shared friends
leaderboard.

## Folder contents
- `index.html` — the whole site (lightweight now, ~34 KB)
- `images/` — every exercise demo image, as `images/<Exercise_Name>/0.jpg` and `1.jpg`
- `README.md` — this file

`index.html` loads the images from the `images/` folder using relative paths,
so **keep the folder structure intact** when you upload.

## Put it online (free) with GitHub Pages
1. Create a new **public** repository on GitHub.
2. Upload **everything in this folder**, keeping the `images/` folder as-is
   (drag the whole folder into GitHub's uploader).
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
5. Wait 1–2 minutes and your live link appears:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Notes
- Images are from the open-source **free-exercise-db** (public domain).
- The mobility-flow poses are instruction cards (the image set is
  weightlifting-focused and doesn't include yoga poses). Add your own pose
  images to `images/` later if you like.
- **Rep-saving and the friends leaderboard** run on Claude's storage, so those
  are fully live inside Claude. On GitHub Pages the plan and demos work; the
  save/leaderboard features need Claude.
