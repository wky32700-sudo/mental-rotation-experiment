# Mental Rotation Letter Experiment

A static, GitHub Pages-ready experiment testing the angular-disparity effect with normal and mirror-reversed letter R stimuli.

## Features
- Consent gate and anonymous participant ID
- Random counterbalancing of F/J response mapping
- 4 practice trials and 40 randomized experimental trials
- Rotation conditions: 0°, 60°, 120°, 180°
- Trial-level reaction time, accuracy, response method, and timestamp
- In-browser summary chart
- CSV download; no server or database required
- Responsive buttons for keyboard, mouse, and touch

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, `.nojekyll`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.

## Data and analysis
The CSV preserves all trials. For the RT analysis, use main-task trials that are correct and between 200 and 10,000 ms. Aggregate mean correct RT and mean accuracy within participant and angle before inferential analysis.

## Ethics
This demonstration stores data only in the current browser until the participant downloads the CSV. Researchers remain responsible for consent wording, ethics approval, secure transfer/storage, debriefing, accessibility, and institutional requirements.
