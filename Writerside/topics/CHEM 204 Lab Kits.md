# CHEM 204 Lab Kits (DEPRECATING)

In order to give students rigorous, engaging laboratory experiences, courses will require Lab Kits as part of the learning materials. This enables at home experiments to move beyond "kitchen chemistry" experiments.

## CHEM204 & Science Interactive Custom Lab Kits

### Introduction

[Science Interactive](https://www.scienceinteractive.com/) (SI) customized lab kits provide students the opportunity to participate in authentic science labs from their homes in a safe manner. Science Interactive (SI) has a library of experiments and accompanying laboratory materials that can be curated to create custom laboratory kits specific for a Unity DE laboratory course. Students are required to purchase a kit that includes laboratory materials (ex: beakers, burners, chemicals, gloves,etc.) for them to conduct four experiments at home. Students will be responsible for supplying additional materials to accompany the kits (ex: oven mitts, distilled water, tinfoil, pie plate, etc.) The purchase of the kit includes access to the lessons from the SI Cloud online through the course in Canvas. These lessons typically cover getting started, laboratory safety, and the assignments that accompany the experiments. 

### Ordering Kits
#### How will students be provided lab kit purchasing information?
- Advisors: Advisors will be presenting students with the purchasing information that includes a purchase link.
  - (link this later) CHEM 204 Example:Materials for CHEM 204-Information & Purchasing Directions for Students 
  - In the case of CHEM 204, (our first course designed w/ SI kits) Advisors have also been provided with the document that includes sign up information with more context: (link this later) Chem 204 Lab Kit Information for Advising Team
- Stratus: the Director of Learning Experience Design will add a note to StratusCAMS upon request of LXD (already done for CHEM 204):  "This course requires student supplied materials and the ordering of a custom lab kit. Please contact your advisor for the purchasing information and directions as soon as you are enrolled in the course."
- Reminder to students in Canvas-Overview of Science Interactive Lab Kits Page

#### When and how do students order Lab Kits?
- It is highly recommended that students purchase lab kits as soon as they sign up for a laboratory course. They use the purchase link to order, which will be provided by advisors. However, if course enrollment is low enough to make it uncertain that a section will run, we will advise the students who are enrolled to not purchase their lab kits until 3 weeks prior to term start, at which point it will become clearer whether the course is running or not.
- Expect that processing and shipping can take up to 10 days with the standard UPS Ground Shipping Option. Students should order the lab kits at least 2 weeks before the start of the term. 

#### What do students do with the kit when it arrives?
- Students should inspect the outside of the box for damages and store it in a safe place until the start of the course.
  Some customized kits might have items that need to be refrigerated. Please let advisors know if this is the case for the customized kit.
- Once the course starts, students will access the SI Cloud through the Canvas modules
- Click on the assignment, Science Interactive- Getting Started in the Week 1 Module
- Students must follow the directions on the SI guide: [How do I Register my Kit in My LMS?](https://studenthelp.scienceinteractive.com/a/1237536-how-do-i-register-my-kit-in-my-lms)
  - This guide will explain how to use the code that is on the box of the kit to register your kit through the Getting Started module in Canvas.
  - IMPORTANT NOTE: The code that grants access to the online Science Interactive assignments is on the physical box. Students should not recycle the box before registering the kit.
- Students should be able to access the first initial lessons before being required to enter the kit code, although it is encouraged that students enter the code as soon as they are prompted with the option to do so.
- [tentative] Week 1 also contains the “Inventory” lesson where students can confirm they have the proper materials and also receive information on how to order replacements if anything was damaged in transit.

#### What if there is low enrollment in the laboratory course and it is possible that the course might not run?
- If we suspect that a course will not run, we should do our best to notify the student(s) as soon as possible, preferably more than two weeks before the start of the term (before they purchase the kit).
  - Please stay in communication with the Dean, Associate Dean, and the Associate Dean of Advising in the weeks leading up to course launch.
- Returning Kits: There is a return policy, and 20% restocking fee to return kits. We would like to avoid students having to return kits.
  - [Science Interactive Returns & Refunds](https://studenthelp.scienceinteractive.com/a/1203266-returns-refunds)

#### How long will the lab kits last?
- Each custom lab kit has a different shelf life because each custom kit has a different materials list. When designing a custom kit, it is wise to ask the Science Interactive Team the shelf life of the kit and if any materials need to be refrigerated. Generally speaking, the biology kits are likely to have a shorter shelf life than other science kits. Many of the kits will last 6 months-1 year.
- CHEM 204 Kit Shelf Life: Approximately 1 year
  - “In terms of this kit in particular (CHEM 204 kit), I don't see anything that would change that 1 year timeline. The biggest concern would be the volatile materials in the synthesis of esters chembag. We have changed our manufacturing protocols for this chembag to decrease the likelihood of evaporation of the chemicals, but over time it is still possible to see a reduction in the amount of chemical present. To reduce the chances of evaporation, the kit should be maintained in a temperature-controlled environment.” -SI Team
  - Reach out to SI if students have issues w/ this chemical if the kits are stored long term to see if they can replace the defective item.

### Accounts and ID Access
Cloud Sign-in Page: [MyHOL.HOLScience.com](http://myhol.holscience.com/)

{style="note"}
  - Optional SI Training: The SI Rep, Joe Schubert has offered to do a 20-30 min training session with instructors if they want to. Most of the information in the training is already covered in the SI New Instructor Tutorial. Please reach out to him if an instructor expresses interest.
  - [General Instructor Help Page](https://instructorhelp.scienceinteractive.com/)
  - If an instructor needs to be changed after the live section is created: An ID can click on the course SKU, remove an instructor, and add a new instructor (as long as the new instructor has an account set up by SI)
### Setting Up Canvas & SI Integration 
#### Creating the hooks in the DEV template
Please view the [Canvas Instructor Quick-Start Guide (LTI)](https://instructorhelp.scienceinteractive.com/a/1397553-canvas-instructor-quick-start-guide-lti) to set up the Dev_CHEM204 in Canvas. This will walk you through the process of creating the course master hook and creating the individual assignments for the experiments in Canvas.
Notes: 
- You will be using the option of creating a master hook
- In Canvas, please label the assignments as Science Interactive- followed by the name of the assignment (Ex:Science Interactive- Laboratory Safety)
- If you have issues or questions setting up the DEV template with the course hooks, please reach out to both SI rep/ Account Executive
#### Copying Process & Hook Set Up
- During the course hook set up, you might be asked to sign into HOL/SI. Please use your individual Instructor Admin Account. If you do not have one please ask Science Interactive to make you one that has the same permissions as the other ID Team member.
- Reset BP
- Import Dev into BP
  - You do not need to make any connections in the BP (do not not click on any of the hooks.) This only needs to be done in the Live sections.
- Associate the BP with the live course
- Go to Live Modules
- Click on the unpublished master hook in Canvas
- Click Load Science Interactive Course Hook in a new window.
- You will be prompted to set up the live section in Science Interactive. See below:
![](SI_Course_Setup.png)
- Course Name: Name the Course as it reads in Canvas.
  - Ex: DE-24-Aug_CHEM204-01: Organic Chemistry 2 Laboratory
- Course Session: Session name should be the month and year.
  - Ex: August 2022
- Instructor
  - IDs can assign instructors that have existing accounts.Search for the instructor teaching the course. The ID must communicate with SI ahead of time and let them know who the new instructor is so the instructor’s name can show up here.
    - SI will need the instructor’s name and email address
  - Before copying, instructors can easily be changed.
  - Science Interactive can add usernames of a pool of instructors
- Checkboxes:
  - Select: Enable LTI Grade Sync
  - Select: Enable Student Final Report Download
  - Do NOT select: Maintain Instructor Notes
  - Select: Maintain Gradebook weights
  - Section open dates
    - Set the course to open on the official start date of the term and end a week after the term start
- Choose an SI assignment module in the live section in Canvas and confirm that it opens without error messages
  - Class start date should also be set to the first day of the term
- Note: If you would like the final grade report turned off for students then you need to email SI to turn it off.
- Leave the inventory unchecked
### Instructor Grading and Responsibilities
- Instructor Access to the SI Cloud is needed for grading
  - When students complete the Science Interactive assignments in the HOL Cloud, some of the questions will be automatically answered. Questions with more complex formats will require instructor grading (see below for how to download Answer Guides).
- Instructors will access the assignments for grading by visiting the SI Cloud directly (Cloud Sign-in Page: [MyHOL.HOLScience.com](http://myhol.holscience.com/)), not through Canvas.
- Once an assignment is graded, the grades should sync automatically to Canvas within 15 minutes. If this does not appear to have worked correctly, the sync button can be pressed manually on the instructor side.
- [How To Grade in the SI Cloud Gradebook](https://instructorhelp.scienceinteractive.com/m/113006)
  - Note: there are also grading support videos available in the instructor view of the SI cloud.
- [How to Download Answer Guides](https://instructorhelp.scienceinteractive.com/a/1257763-how-to-download-answer-guides)
- [General Instructor Help Page](https://instructorhelp.scienceinteractive.com/)
- Note about upcoming Gradebook: There is a new version of gradebook coming out in September, instructors still have access to both. When the new gradebook is released, the ID Team might want to consider asking SI to only turn on the new version.
### Student & Instructor Experience: Troubleshooting and Common Issues
- Answers to Commonly Asked Student Questions: [Science Interactive Student Help Guides](https://studenthelp.scienceinteractive.com/)
- Chrome/Firefox are preferred browsers w/ SI
  - Site doesn’t work very well with internet explorer products
- File uploads
  - If the SI Cloud asks students to upload a photo for a lesson, they cannot use AirDrop at all during the process of uploading the photo.
      - AirDrop picture to self, won’t accept that file format → HEIC format, even if they change it over to .jpeg.
- Student is “locked out” of the SI Cloud
  - It is likely that the student did not enter their kit code. Please prompt the student to do so and reach out to SI if they are still locked out or if the student no longer has their kit code.
### SI Contact/ Support
LXD/LTSS Support
Jonathan Santos, Account Manager
jsantos@scienceinteractive.com
Office Phone: 720.253.1806
Cell Phone: 858.449.4226

Student Support
[Get in Touch Student Form](https://www.scienceinteractive.com/student-contact/)
Email: info@scienceinteractive.com
Call: 866.206.0773
[Science Interactive Student Help Guides](https://studenthelp.scienceinteractive.com/)
### Incorporating SI in a New Build
Currently, CHEM 204 is the only Unity DE course that requires SI custom lab kits. If you are considering the lab kits for a specific course, please reach out to the Science Interactive representative and ask that you and the ID can have permission to browse the lab kit library. Once you have an idea of which experiments you would like to include in the lab kit, you can request a sample lab kit and pricing information. You can also email the Course Outcomes and Description to the SI Rep and they can have the SI team propose a good fit of experiments.

#### Appropriate Amount of Experiments
Each experiment comes with a tailored lesson plan and step by step directions on the SI Cloud. A five week undergraduate lab course should expect to have one experiment per week for weeks 2-5. Week 1 should include the Getting Started, Inventory, and Lab Safety lessons, which are automatically included as part of the SI kit and necessary to unlock the lessons for the experiments.
#### Pricing
Due to the range of materials needed for each kit, the individual experiments have varying prices, thus each custom lab kit has its own unique cost. It is important to consider the following:
- Price of custom kit (this includes price of each experiment and access to the SI cloud)
- Shipping (currently $22.95 for UPS Ground Shipping)
- The expected cost for student supplied materials

Example price quote: The lab kits for CHEM 204 cost $142.95 + tax with shipping. The overall prices have increased since this custom kit was quoted

Pricing note: Please consider the overall student costs for a laboratory course, as we try to limit the costs for undergraduate courses to $100 for support materials and textbooks. Although this might not be achieved in a laboratory course, it is important to limit the cost as much as possible. This can be done by limiting the number of experiments in a custom kit, or by choosing experiments that utilize some of the same materials. Each experiment will have a list of student supply materials that will need to be purchased in addition to a lab kit. You should have a general idea of the cost of the student supplied items. You should also consider an open source textbook or the same textbook as the content course, to help reduce overall cost.
#### Price Agreement
Once the SME, ID, and Dean have decided on the customization of the kits, then the ID should notify the SI representative. The SI rep will then present a price agreement that must be signed before SI can create the custom lab kit at their warehouse. As the ID, you can send the price agreement to the dean who can then present it to the Vice President of Distance Education for a signature.
