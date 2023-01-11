# cu-schedule-extension-support
Carleton University Inline Professor-Ratings Support Page

## This is the home of all support and issue tracking
- If you have na **issue** with your extension please log it within the issues tab with the issue tag
- Suggestions can be logged under issues with the suggestion tag
- Comments can be logged under issues with the suggestion tag
- For security issues please contact developers directly at the contact info below

---

## Info on the Extension Structure

### Program file structure
```
src -|
     |-background.js (get all data from my own website hosting live data, if it failed local data will be served)
     |-content.js (insert ratings into the carelton schedule page based on indexing through an xpath)
     |-popup.js/html/css (code for the extension's popup)
```
     
### Program structure
When a user visits the specified website the extension activates and calls backgound.js to get data. The data is either served live with a failsafe of local data to prevent issues. The data is returned to a file that can index through the scheduling page and insert each professor's rating beside their name.

### Contact
Developer/Admin - Colin - contact.developer.colin@gmail.com

