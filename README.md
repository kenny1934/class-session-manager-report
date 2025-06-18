# Class Management System - Technical Report

This repository hosts the source code for a technical report web page detailing the features, workflow, and architecture of a custom Class Management System built with Google Sheets, Google Apps Script, and Google AppSheet.

The live version of this report can be viewed at:  
[**https://your-username.github.io/your-repository-name/**](https://your-username.github.io/your-repository-name/) *(You will need to replace this with your actual GitHub Pages URL after setting it up).*

---

## About This Report

This `index.html` file is a self-contained web page designed to professionally present the class management system to stakeholders, such as management. It uses Tailwind CSS for styling and is fully responsive for viewing on desktop and mobile devices.

The report details the three main components of the system:

1.  **The Google Sheets Database:** The backend data structure.
2.  **The Google Apps Script Automation Engine:** The scripts that handle data processing and generation.
3.  **The AppSheet User Interface:** The user-facing application for tutors and admins.

It also outlines key features, system workflows, current limitations, and plans for future improvements.

---

## How to Use and Update This Report

This repository is set up to be hosted using GitHub Pages. Follow these steps to add your screenshots and deploy the page.

### 1. File Structure

The repository should have the following structure:

* `/` (Root Folder)
    * `index.html` (The main report file I provided)
    * `README.md` (This file)
    * `images/` (A folder to hold your screenshots)
        * `app-menu.jpg`
        * `my-schedule-calendar-view.jpg`
        * `today-attendance-view.jpg`
        * `reschedule-action-buttons.jpg`
        * `pending-make-up-view.jpg`
        * `cw-hw-logging-buttons.jpg`
        * `lesson-record-form-with-suggestions.jpg`
        * `lesson-records.jpg`
        * `tutor-schedule-sheet.jpg`
        * `msa-logo.png`
        * `...` (and any other screenshots)

### 2. Adding Your Screenshots

1.  **Upload Images:** In your GitHub repository, navigate into the `images` folder (or create it if it doesn't exist). Click "Add file" -> "Upload files" and upload all your PNG or JPG screenshot files.

2.  **Update Image Paths in `index.html`:**
    - Open the `index.html` file in the GitHub editor (or on your local computer).
    - Find the `<img>` tags. Each one has a placeholder `src` path like `src="./images/my-schedule-calendar-view.jpg"`.
    - **Replace** the placeholder filename with the **exact filename** of the corresponding screenshot you uploaded. Ensure the path starts with `./images/`.
    - Update the `alt="..."` text for each image to accurately describe the screenshot.
    - Commit the changes to `index.html`.

### 3. Publishing with GitHub Pages

1.  In your repository on GitHub, go to the **"Settings"** tab.
2.  In the left sidebar, click on **"Pages"**.
3.  Under the "Build and deployment" section, for "Source", select **"Deploy from a branch"**.
4.  Under "Branch", ensure `main` (or `master`) is selected and the folder is `/(root)`.
5.  Click **"Save"**.
6.  GitHub will generate a public URL for your site. It can take a few minutes to become active. You will see the URL at the top of the "Pages" settings screen once it's ready.

---
