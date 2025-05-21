# TOEIC Resources Web Page User Guide

This guide provides a step-by-step walkthrough for setting up a simple web page that lets you quickly access your audio and PDF materials. You will download three archive folders from Moodle and use the provided `index.html` file.

---

## 1. Logging into Moodle and Downloading Files

1. Log in to your Moodle account.
2. On the course page, find the **“Archives”** or **“Resources”** section and download the following three folders:

   * `Audio Files-20250516` (audio files)
   * `Listening Exercises-20250516` (listening exercise PDFs)
   * `🔑 Answer - Keys-20250516` (answer key PDFs)
3. Extract all ZIP archives into a single directory. You should end up with:

   ```
   Audio Files-20250516/
   Listening Exercises-20250516/
   🔑 Answer - Keys-20250516/
   ```

## 2. Placing the `index.html` File

1. Download or copy the `index.html` file from this GitHub repository.
2. Move or copy `index.html` into the same directory where you extracted the three folders:

   ```
   YourFolder/
   ├── index.html
   ├── Audio Files-20250516/
   ├── Listening Exercises-20250516/
   └── 🔑 Answer - Keys-20250516/
   ```

## 3. Opening the Page Locally or in a Browser

### Option A: Open Directly

1. Double-click on `index.html`.
2. It will open in your default web browser.
3. **Note:** Some browsers may restrict local PDF previews or audio playback. You may need to adjust browser settings or enable relevant extensions.

### Option B: Use a Simple Local Server (Recommended)

This method ensures smoother PDF preview and audio playback:

1. Open your terminal or command prompt.
2. Navigate to your folder:

   ```bash
   cd path/to/YourFolder
   ```
3. Start a local server:

   * For Python 3:

     ```bash
     python3 -m http.server 8000
     ```
   * For Python 2:

     ```bash
     python -m SimpleHTTPServer 8000
     ```
4. In your browser, go to `http://localhost:8000`.

## 4. Using the Web Page

* **Search**: Type a unit, file name, or page number into the search box at the top left to filter audio files.
* **PDF Preview**: Click any PDF title in the left menu to view it instantly in the right-hand preview pane.
* **Audio Controls**: Click an audio file in the left menu to open the floating audio panel at the bottom right. Use the play/pause, previous, and next buttons to control playback without closing the PDF preview.

---

If you encounter any issues or have suggestions, please open an issue on GitHub. Happy studying!
