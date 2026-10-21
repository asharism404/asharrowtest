# AshArrow lecture page — enhanced build

## What's new
- Larger lecture tiles with smoother hover sheen and active-state animation.
- Searchable playlist plus All topics / To watch / Saved filters.
- Previous/Next lecture controls and left/right keyboard navigation (when not typing in a field).
- Current topic position, improved empty-search state, and animated progress updates.
- Marking a completed topic again now lets you undo completion.
- Existing dark mode, notes, saved topics, video-link handling, and localStorage persistence retained.

## Test locally
Open `lecture.html?subject=anatomy` through a local static server, or open `lecture-preview.html` as a single-file preview. Some browser security rules may restrict local video embeds; test hosted pages for final video behavior.

## Deploy to GitHub Pages
1. Unzip the project.
2. Upload/commit the contents of this folder into the root of your existing AshArrow/Asharchives repository, preserving the filenames.
3. In GitHub, open **Settings → Pages** and choose **Deploy from a branch**, select your default branch and `/ (root)`, then save.
4. Wait for GitHub Pages to finish the deployment. The exact live URL depends on your repository settings.

No account credentials or API keys are included in this package. Lecture progress, notes, and pasted links are stored in each learner's own browser.
