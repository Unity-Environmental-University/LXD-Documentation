# Copying, Syncing and Publishing Courses

## Creating a DEV Shell
To copy a course from Google to Canvas you will need to build a DEV shell.
- Go to the Distance Education account in Canvas.
- Click “+ Course”.
- Enter course name with code (DEV_MATH215: CALCULUS) in all caps in both the Course Name and Reference Code.
  - Subaccount: Distance Education. 
  - Enrollment Term: Course Development.
  - Search for the course you just created and click on it.
- Import Course Development Template.
  - Settings -> “Import Course Content”.
  - Content Type: “Copy a Canvas Course”.
  - Search for DEV_template.
  - Click “Import All Content”.
- Clean up:
  - Delete extra modules and items. (The template is 8 weeks so that it can be used for graduate and undergraduate courses. One template allows for one set of modifications if changes need to be made to the template and is easier for upkeep)
    - Unpublish and delete in modules and then in assignments (click on the left menu button to access the assignments page).
    - Pages: delete unpublished pages for weeks 6-8 (if it’s an ungrad course).
  - Don’t populate homework (built in quizzes) or quizzes. This will be added later.
## Creating a Blueprint (BP)
If you are working with a new build or a very old course, you will need to create a Blueprint. BPs have a box icon after the title and begin with BP_.
- Always check DE Live to make sure there isn’t a Blueprint.
- Go to the DEV to copy the full course name.
- Open Live Distance Education and click “+Course” to add a course.
- Paste the title of the course into the Course Name box and the Reference Code box, but change DEV_ to BP_ at the beginning of the title. 
- NOTE: Make sure there is not a space between the course title’s 4 letters and the course number (see blue arrows)
  - Subaccount: Distance Education
  - Enrollment Term: Blueprints

![creating a blueprint 1.png](creating_a_blueprint_1.png)
![creating a blueprint 2.png](creating_a_blueprint_2.png)

## Copying from DEV to BP
Once a course has been built/updated/refreshed/retrofitted/converted in the Development (DEV) course and is ready to  be copied to its Blueprint (BP). 
- Check the DEV to make sure the dates, syllabus, etc. are updated.
- If the course exists as a BP, search for it in the Distance Education account of Canvas.
- Disable the BP: Disabling the BP unlinks it from any Live sections. 
  - Go to “Settings” within the BP. 
  - Uncheck the “Enable course as a Blueprint Course” box.
  - Scroll down and click “Update Course Details”.
    - To check your work you can look for 3 things:
      1. “Reset Course Content” will pop up on the right hand side. 
      2. The blue tab/border will disappear on the right hand side.
      3. The “Enable course as a Blueprint Course” box will be unchecked.
    - Workflow is protected and there are contingencies.
- Once you’ve ensured that the course is no longer serving as a BP and that you are in fact working within the BP, click “Reset Course Content” on the right hand side. Warning: resetting course content CANNOT be undone.
  - A warning message will pop up. If you’ve ensured the BP is no longer linked, you can click “Reset Course Content”.
  - Removing the link to the BP does not change the Live sections previously linked to the BP. This is why it is ok to edit a blueprint for the new semester while current courses are still running. Previous runs of the courses can also be accessed, so the content typically lives on in another location in case of emergency.
- Once the course has been reset, you can import the content from DEV. Click on “Import Course Content”.
  - Select “Copy a Canvas Course”.
  - Search for the course you are importing, DEV_COURSENAME
  - Import Content: “All Content”.
  - Do NOT check “Adjust events and due dates”
- After importing, error messages may pop up. You must fix the errors in the BP and DEV shells. If only noting a fix in the future, making the change in the DEV section is enough. Although, sometimes the issue is a big enough problem that it needs to be fixed in DEV and BP, such as a contextual problem.
  - Go to the course Syllabus to check that the dates imported correctly.
  - Check the Intros: make sure Introductions aren’t available until the 1st day of class. 
    - If set properly, the Academic Integrity Agreement will be set to open the rest of the course.
- Next, go back to “Settings” and “Enable course as a Blueprint Course”.
  - Click all of the boxes under the “General Locked Objects” section (content, points, due dates, availability dates).Click “Update Course Details”
- Click in the top right corner in the blue area to look for Associations. Click the Associations link to search for the sections.
  - Search for the term and course you wish to associate with the BP.
  - Check the term, instructor, sections, and course title to make sure you are associating the BP with the correct course. You can find this information on the Faculty Schedule Google Sheet *Warning: be sure to select the correct sections.*
    - Make sure to check what is in the Faculty Schedule Google SheetTrello card to what is appearing in Canvas; good opportunity to reach out to Dean if there is a problem.
  - Check the boxes next to the sections.
    - Do not click “Adjust Events and Due Dates”
    - Do not click “Publish Upon Association”.
  - Click save and then done.
- The next steps have been automated, so see the [Publish Script](https://docs.google.com/document/d/1CKTxrChEGYn6NrwsZ8k7uGcWsburOdcWXELCaHfSndc/edit?pli=1#bookmark=id.7p1vxobv2fya) page.