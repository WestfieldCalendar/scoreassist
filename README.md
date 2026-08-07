# Game Show Scoring Console

Open `index.html` locally or publish these files to GitHub Pages.

## CSV export

The current episode CSV includes:

- Show number
- Round and question
- Result
- Score changes
- Both team names
- Running total score for each team after every logged result
- Edit Notes matched to the corresponding round and question

FIX entries that cannot be matched to a result are exported as separate `FIX note only` rows so they are not lost. Empty reasons are marked `[Reason not entered]`.

## GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to the repository root. Under **Settings > Pages**, deploy from the `main` branch and `/ (root)`.
