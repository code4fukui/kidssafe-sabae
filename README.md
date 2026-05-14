# KidsSafe for Sabae

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A customizable community mapping tool for Sabae City. This project allows residents to easily create and share interactive maps using simple CSV files. It is built upon the [KidsSafe by Code for FUKUI](https://github.com/code4fukui/kidssafe/) framework.

**Live Demo:** [https://code4fukui.github.io/kidssafe-sabae/](https://code4fukui.github.io/kidssafe-sabae/)

## Features

-   **CSV-Powered:** Create and update map layers by simply editing and uploading CSV files.
-   **Customizable:** Easily add new data types (e.g., AEDs, playgrounds, restaurants) and custom map icons.
-   **Mobile-Friendly:** Includes instructions for adding the map to a smartphone home screen for quick access.
-   **Multi-Language Support:** The interface can be switched to other languages.

## How to Use the Map

Simple instructions are available for getting the most out of the map on your smartphone.

-   **Add to Home Screen (Android):** [Instructions (PPTX)](https://github.com/code4fukui/kidssafe-okamoto/files/14518682/android.pptx)
-   **Add to Home Screen (iPhone):** [Instructions (PPTX)](https://github.com/code4fukui/kidssafe-okamoto/files/14518806/iphone.pptx)
-   **Change Display Language (iPhone):** [Instructions (PPTX)](https://github.com/code4fukui/kidssafe-okamoto/files/14518975/iphone.pptx)

## How to Update Map Data

You can update the map directly from the GitHub interface. Changes are typically reflected within a minute.

*Note: If you don't see your changes, try refreshing the page in a private/incognito browser window to bypass the cache.*

### 1. Update an Existing Data Set

1.  Navigate to the file you want to change (e.g., [`aed.csv`](aed.csv)).
2.  Click the "Download raw file" button.
3.  Open the file in a spreadsheet editor like Excel or Numbers and make your changes.
    -   To get location data, use the [Latitude and Longitude Map](https://fukuno.jig.jp/app/map/latlng/#%E8%B6%8A%E5%89%8D%E5%B8%82) and copy the `Geo3x3` code.
4.  Save your changes.
5.  Return to the repository's main page, and drag-and-drop your updated file into the file list to upload it.

### 2. Add a New Data Type (Map Layer)

1.  Download the [`template.csv`](template.csv) file.
2.  Open it and add your new data, starting from the second row. You can add as many columns as you need.
3.  Save the file as "CSV UTF-8 (comma-separated)" with a descriptive, alphanumeric filename (e.g., `playgrounds.csv`).
4.  Download and open [`index.csv`](index.csv).
5.  Add a new row containing your new file's name, a display name for the map layer, and the icon filename to use.
6.  Upload both your new data CSV and the updated `index.csv` to the root of the repository.

### 3. Add a New Icon

1.  Create a PNG image (around 100x100 pixels is best) with a simple, alphanumeric filename.
2.  Navigate to the [`icon`](icon) folder.
3.  Drag-and-drop your new icon image into the folder to upload it.
4.  Update the `icon` column in [`index.csv`](index.csv) or your specific data file to reference the new icon's filename.

## Feedback

-   For inquiries about the Sabae map data, please [open an issue in this repository](../../issues).
-   For feedback on the core KidsSafe application, please use the [main KidsSafe issue tracker](https://github.com/code4fukui/kidssafe/issues).

---

MIT License — see [LICENSE](LICENSE).