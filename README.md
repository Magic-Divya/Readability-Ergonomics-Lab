# Readability Lab — HCI Experiment 7

A browser-based readability and ergonomic layout evaluator built with HTML, CSS and JavaScript.

## Features
- Live font-size, line-height, letter-spacing, text-width and paragraph-spacing controls
- Typeface and four reading themes (light, warm, dark, high contrast)
- Focus mode and optional reading ruler
- Three reading passages with comprehension questions
- Timed reading and words-per-minute (WPM) calculation
- Comprehension accuracy, heuristic layout indicators and performance chart
- Multiple trial history and CSV export
- Responsive layout for desktop and mobile
- No backend; trial data stays in the current browser session and is not uploaded

## Run in VS Code
1. Extract the folder `Readability-Ergonomics-Lab`.
2. Open that folder in VS Code.
3. Open `index.html` in your browser, or install the **Live Server** extension and choose **Open with Live Server**.
4. Internet access is needed to load Chart.js from its CDN and the optional Google Fonts. The core page still loads without Google Fonts; if Chart.js cannot load, the chart will not render, but the reading test and CSV export still work.

## How to run a trial
1. Select a passage and set the ergonomic factors.
2. Click **Start reading**, read naturally, then click **Finish & test**.
3. Answer all three comprehension questions and submit.
4. Review WPM, comprehension accuracy, time, chart and trial history.
5. Change one or two factors and repeat. Use **Export results (CSV)** to save the experiment data.

## Metrics and interpretation
- **Words per minute (WPM)** = passage word count ÷ reading time in minutes.
- **Comprehension accuracy** = correct answers ÷ total questions × 100.
- **Layout index / typography / width / spacing indicators** are heuristic estimates based on chosen settings. They are not clinical accessibility scores and should not be reported as measured reading speed.
- Reading speed and comprehension are measured from the user's trial. For a fair experiment, keep passage difficulty similar, use a consistent procedure, and change one or two variables per trial. Repeat trials to reduce random variation.

## Suggested lab analysis
Create a table with trial number, font size, line spacing, letter spacing, text width, theme, WPM and accuracy. Compare combinations using both WPM and comprehension: a faster trial with much lower accuracy should not automatically be treated as the best layout. Note limitations such as practice effects, passage difficulty, fatigue, and the small number of quiz questions.
