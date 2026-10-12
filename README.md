# Daily Time Block Planner

A one-sided, editable daily worksheet with hourly intervals from **6:00 AM through 10:00 PM** and columns in the order **Priority | Tasks | Events | Time**. Hour labels are positioned at the horizontal interval boundaries.

## Use
Open [the GitHub Pages planner](https://robert-z-lehr.github.io/Time-block-planner/). Enter a date and activities, then select **Print / Save PDF**. In the print dialog, choose **US Letter**, **Portrait**, **100%** scale, and disable browser headers/footers if they appear. The print stylesheet is designed to fit on one sheet.

Entries are saved automatically in the current browser using local storage. **Clear entries** clears the Priority, Tasks, and Events fields. No account, backend, or data sharing is required.

## Deploy
The repository contains a GitHub Actions Pages deployment workflow. To enable publishing if not already active, open **Settings → Pages**, choose **GitHub Actions** as the build and deployment source, then run or rerun **Deploy GitHub Pages** from the Actions tab.

The entire app is in `index.html`, with no build dependencies.

## Version
V2: Priority | Tasks | Time | Events layout, narrow Priority/Time columns, 6 AM–10 PM hour boundary markers. Existing Routine/Adjusted browser entries are carried forward as Events/Tasks.

## Column controls and clock
Click the right arrow in a column header to swap that column with its right neighbor. The last column wraps to the first. Column order is saved in your browser. The clock defaults to 24-hour numerals (6 through 22); the toolbar toggles 12-hour labels (6 AM through 10 PM). Toolbar and arrow controls are hidden when printing. Priority is narrower than the other fields.
