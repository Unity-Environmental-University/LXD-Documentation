# Automated Profile Update Process

Note, you can also now use the [Chrome Extension](#chrome-extension) to publish and set profiles in sections. Documentation below.

## Python Script
### Installation
1. Install Python 3.7 or later : https://www.python.org/downloads/
1. Make sure to click “Add to PATH and/or Add to environment variables” checkbox when installing
1. Download Profile Update Script folder and all contents from Github
   * Go to “Repositories” “Add” “Clone”
   * Select 'publish script' from the result
   * Click “Fetch origin” button to update the publish script
1. Get "constants.json" from Hallie and place in the same folder  (Likely Documents/Github/publish-script)
   * Treat constants.json as a password. It’s important that we keep the constants.json as protected as possible as anyone with this file could make any changes to the canvas site that you could.
   * Open the constants.json file in notepad or another text editor, and make sure the “creator” and “term” values reflect your information and the term you’re currently working with, replacing names, role, and start as necessary.
1. Run "setup.py" from the same folder by double-clicking it

### Updating
1. Open GitHub
2. Select publish script from repositories
3. Click the "fetch origin" button if it is present. If not, you are up-to-date

### Running
1. Make sure the BP is created and associated with sections before starting.
1. Update to the latest version of "Publish Script"
1. The first time you are running the script for a new term, open your Profile Update Script folder and delete your copy of the “bios.json” 
1. Double-click on publish.py A dialog will pop up asking you for the blueprint code. Type the BP's course code into the box (e.g. BP_COMM100)
1. Press OK
1. The script will now present a checkbox with different options for the copying process. Select those that apply (typically all but “publish” on the copying day, the Wednesday a week and a half before the term start, and then only “publish” on publish day, the Monday the week before term start)
   1. First, select “Do you want to apply content fixes….”,
   1. “Do you want to remove lm annotation…” and
   1. “Do you want to lock blueprint module items” and click Run
   1. Press Run and wait for the program to finish.

1. Associate BP courses with sections and *wait for the sync process to finish*. Often, errors that occur are a result of the profile page not being ready to be updated.
1. Once all courses have been associated:
   1. If this is your first time running this term, or you have changed or added any profile pages in the Faculty Profile Pages course, select “Do you want to redownload…"
   1. Select “Do you want to update profiles….”
   1. Select Run and wait for the program to end. 
   2. A button to open the sections should appear. 
2. When finished, the script will show a message box detailing some errors that may have occurred, if any, and naming any profiles it was unable to update.
2. Click the “open courses” button to spot check the live sections and ensure the copying process was successful (the modules are locked, the correct instructors have been added to the homepages, etc.)
You may need to sync the BP to the live sections to push out any changes made by the script (such as locking the modules)
1. Check off on the course’s Trello card that the course has been copied, synced, and the instructor notified. Move the trello card to the correct list.
1. If there is a change needed in the Live section, make the change in the BP and DEV. Do not make a change in the live section.
1. Go to the BP.
1/ Make the change in the course.
1. Click on the blue tab to “Sync Changes”.


## Chrome Extension
BETA
1. Make sure the BP is created, set as a Blueprint, and DEV is imported
2. Remove learning material annotations from the BP (hopefully extension will be able to do this soon)
3. Go to the Modules page and click the "Lock All" button. This button will not appear if the course is not set as a BP.
<img alt="Lock All Button" src="lock-all.png" width="400"/>
4. Associate BP with sections 
5. Install or update the [Chrome Extension](LXD-Chrome-Extension.md) 
6. Wait for Sync with sections to finish if it hasn't already
7. Go to settings page and click on the "Publishing..." button. (This button will be disabled if this is not a blueprint)
<img alt="Picture of publishing button" src="publishing-dot-dot-dot.png" width="400"/>
8. You should see a dialog with all sections and buttons to Publish and Set Bios.
<img alt="Picture of publish dialog with Publish and Set Bios buttons and a list of sections" src="publish-dialog.png"/>
9. Clicking "Set Bios" will try to set bios for all courses. 
10. You should see the "Name on Front Page" populate with the display name from the section. 
   <img alt="A picture of the publish dialog showing a Name on Front page for Test Testersson" src="name-on-front-page.png"/>
   * If any names are not displayed, you may need to make a new page in [Faculty Bios](https://unity.instructure.com/courses/3716914/pages)
for that person by copying an existing page, renaming it to that person's full user name, and modifying the image, profile, and display name on that page.
   * If the person is incorrect, open the details view and scroll down (if necessary) to profile matches. If the matching profile is there, select "Use This Profile".
   <img src="profile-match.png"/>
If not, you may need to create a new faculty page for them. 
11. Check individual sections by clicking on the name of the section in sections list. You can also review section info with the "Details" view.
   <img src="profile-details-1.png"/>
