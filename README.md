# Daily Time Block Planner

A one-sided, editable daily worksheet with hourly rows from **6:00 AM through 10:00 PM**, a narrow **Time** column, and wide **Routine** and **Adjusted** columns.

## Use
Open [the GitHub Pages planner](https://robert-z-lehr.github.io/Time-block-planner/). Enter a date and activities, then select **Print / Save PDF**. In the print dialog, choose **US Letter**, **Portrait**, **100%** scale, and disable browser headers/footers if they appear. The print stylesheet is designed to fit on one sheet.

Entries are saved automatically in the current browser using local storage. **Clear entries** clears only the schedule fields. No account, backend, or data sharing is required.

## Deploy
The repository contains a GitHub Actions Pages deployment workflow. To enable publishing if not already active, open **Settings → Pages**, choose **GitHub Actions** as the build and deployment source, then run or rerun **Deploy GitHub Pages** from the Actions tab.

The entire app is in `index.html`, with no build dependencies.

## Version
V1: single-sided daily schedule, date selector, editable Routine/Adjusted fields, and single-page printing.
