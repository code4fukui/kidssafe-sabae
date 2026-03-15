# KidsSafe for Sabae

This is a regional safety map tool that allows residents of the Sabae city area to create and share an interactive map on smartphones and PCs.

## Features

- Create and update a regional safety map using Excel or Numbers to edit and upload CSV data
- Built using the [KidsSafe by Code for FUKUI](https://github.com/code4fukui/kidssafe/) project

## Usage

### Adding the site to your home screen

For users who are not familiar with smartphone operations, clear instructions are provided on how to quickly access KidsSafe.

- [Home screen registration (Android)](https://github.com/code4fukui/kidssafe-okamoto/files/14518682/android.pptx)
- [Home screen registration (iPhone)](https://github.com/code4fukui/kidssafe-okamoto/files/14518806/iphone.pptx)

### Changing the site language

Instructions are provided on how to switch the site display to a foreign language.

- [Foreign language conversion method (iPhone)](https://github.com/code4fukui/kidssafe-okamoto/files/14518975/iphone.pptx)

### Updating the data

1. Identify the data you want to change (e.g., [aed.csv](aed.csv))
2. Click the download button and download the file
3. Edit the file in Excel
4. For location information, use the [Latitude and Longitude Map](https://fukuno.jig.jp/app/map/latlng/#%E8%B6%8A%E5%89%8D%E5%B8%82) to find the corresponding Geo3x3 code
5. Save the Excel file
6. Drop the edited file into the [./](./) folder and upload it

The changes will be reflected in about 1 minute (refresh in private mode if the cache is still being used).

### Adding new data types

1. Download the [template.csv](template.csv) file and open it in Excel
2. Add the information you want to map in the rows starting from the 2nd row (you can freely add new columns)
3. Save the file in "CSV UTF-8 (comma separated)(.csv)" format with a file name that indicates the data type
4. Download the [index.csv](index.csv) file and open it in Excel
5. Add the file name, data type name, and icon file name
6. Upload the index.csv file and the file you saved in step 3 to the [./](./) folder

The changes will be reflected in about 1 minute (refresh in private mode if the cache is still being used).

### Adding new icons

1. Prepare a PNG image approximately 100x100 pixels in size with a half-width alphanumeric file name
2. Display the [icon](icon) folder and upload the image by dragging and dropping it
3. Download the [index.csv](index.csv) or the data files, open them in Excel, and update the icon item to the file name
4. Upload the edited files to the [./](./) folder

The changes will be reflected in about 1 minute (refresh in private mode if the cache is still being used).

## Feedback

- For inquiries about the KidsSafe in this area, please use the [Issues](../../issues)
- For feedback on the KidsSafe application, please use the [KidsSafe Issues](https://github.com/code4fukui/kidssafe/issues)