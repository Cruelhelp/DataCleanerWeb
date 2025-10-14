Data Cleaner (Web)

Data Cleaner (Web) is an offline HTML/JavaScript application for cleaning and standardising government V‑series Excel/CSV datasets. Drag and drop one or more files and let the app extract important metadata (folder names, file numbers, names, ministries/departments), normalise dates, and generate cleaned CSV output – all in your browser with no server required.

Features

Multi‑file upload: Add multiple Excel (.xlsx, .xlsm, .xls) or CSV files at once; they will be processed sequentially.

Path trimming options: Choose whether to trim all slashes from the file path or remove only the leading slash before cleaning.

Cleaning pipeline: Extract file numbers, names, and ministries/agencies, normalise dates to DD/MM/YYYY format, trim whitespace, and optionally remove banned words.

Customisable settings: Enable or disable whitespace trimming, date normalisation, and banned‑word removal from the Settings tab.

Excel‑style previews: Compare “Before” and “After” snapshots of the first 30 rows with row/column headers and gridlines. The preview pane auto‑fills when a file is added and updates automatically after cleaning.

Downloadable outputs: Save cleaned files individually or download all cleaned CSVs at once.

Themes: Switch between dark and light user interface themes; your preference is saved between sessions.

Change log & About: View a dated change log of new features and improvements, and see links to the web and desktop versions of the project.

Responsive design: The interface adapts to both desktop and mobile screens.

Usage

Open the datacleanerweb.html file in a modern web browser (Chrome, Edge, Firefox). No internet connection or server is required.

Click Add Files or drag and drop your Excel/CSV files into the sidebar.

In the Settings tab, choose your file path trimming strategy (trim all slashes or trim only the first) and configure optional cleaning steps.

Click Start Cleaning to process your files. Logs will appear in the Logs tab and cleaned files in the Output tab.

Use the Preview links to compare the original and cleaned data for each file, or use Download to save individual cleaned CSVs.

Click Download All to download all cleaned files at once.

Check the Change Log and About tabs for recent updates and project information.

Development

This project is built with plain HTML, CSS, and JavaScript. It relies on the following libraries:

Papa Parse
 – Fast CSV parser for the browser.

SheetJS (xlsx)
 – Reads Excel files in the browser.

Day.js
 – Lightweight date handling.

All functionality runs locally in your browser; no backend server is required. If you wish to turn this app into a desktop executable, you can wrap it with frameworks such as Electron or package a similar Python version using PyInstaller.

Contributing

Pull requests are welcome! Feel free to open issues or suggest enhancements. See the Change Log in the app for recent updates.

License

This project is licensed under the MIT License. See the LICENSE
 file for details.

© 2025 Ruel McNeil – All Rights Reserved.
