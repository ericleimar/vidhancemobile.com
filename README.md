# Source files for vidhance.com

Original files for the Vidhance webpage.

## Working on Windows

### Local Editing
1. Open Atom
  1. Start Hugo from taskbar
  2. Open folder: `File > Open Folder...`
2. Start Hugo
  1. Press Windows button on keyboard
  2. Type `cmd` and press enter
  3. Type `cd ` and paste path to source file folder
  4. Type `hugo server -w` and press enter
3. View in browser
  1. Open http://127.0.0.1:1313 in your browser
4. Edit md-files in content folder. Save to preview.

### Publish Content
1. Commit and push changes to source files.
1. Empty `public` folder.
2. Run `hugo` in source folder ().
3. Commit in `public` folder and push.
5. Verify by opening [vidhance.com](vidhance.com) from your browser and press reload.
