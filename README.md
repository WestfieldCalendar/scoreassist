# Game Show Scoring Console

Dependency-free HTML/CSS/JavaScript app for GitHub Pages and offline use.

## Thirty independent shows

The Show selector stores 30 separate episode records. Every show has its own:

- Team names and scores
- Active round and question counters
- Notes
- Capitalization Round setup and used tiles
- Question and result log
- Undo history

Switching shows automatically saves the current episode and restores the selected episode. The autosave status names the show being saved.

## Capitalization Round setup

Open **Season Setup**, select a show, and configure 1 to 5 category questions plus each question's point value for every board tile. Configurations are unique to each show.

## Backups

- **Save Session** exports all 30 show records and the complete season setup.
- **Load Session** restores the complete season file.
- **Export Season** exports only the 30 Capitalization Round configurations.
- **Export CSV** exports the question log of the currently selected show.

## GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to the repository root. In **Settings > Pages**, deploy from the `main` branch and `/ (root)`.
