# PoliSci U — Spring 2027 Courses & Enrollment (demo)

**Demo site:** https://rahnumasiddika.github.io/polisciu-illinois/

This is a **demo for review**, not an official University of Illinois web page. The official page will be published on the Department of Political Science website at Illinois, using the content drafted here.

The page lists the graduate political methodology courses offered through **PoliSci U**, the consortium of Illinois, Minnesota, Ohio State and Wisconsin–Madison. It also explains how students at each member university enroll.

## What's on the page

- **Key Dates:** start dates and last days to add
- **Courses:** one card per course, with instructor, time, dates, location, course number, credit hours and description
- **How to Enroll:** one tab per member university, each with three cases (a course at the student's own university, a course at another member university, and visiting students). Each tab also lists that university's PoliSci U contact and an "Information last updated" date.
- **FAQ** and **Contact**
- **About PoliSci U** and **Past Courses**, which link to past schedules (1999–Spring 2024) and papers on the program
- **History** (always the last section), copied from the Ohio State PoliSci U page with a link to the source

## Updating the page

Everything is in one file, `index.html`. To edit it, open the file on GitHub, click the pencil icon, make the change, and click **Commit changes**. The site updates in a minute or two.

- **Courses:** each course is one `<article class="course">` block. Copy a block to add a course, or delete one to remove it.
- **Enrollment steps:** each university's tab is a `<div class="uni-panel">` block. Replace "Details from … coming soon" with the steps, add the contact, and update "Information last updated".
- **Each enrollment period:** update the Key Dates, the courses, each university's "Information last updated" date, and the "Last updated" date in the footer.

## Acknowledgement

The History section is copied from, and the links to past schedules and papers come from, the PoliSci U – Advanced Methodology page maintained by the Department of Political Science at The Ohio State University: https://polisci.osu.edu/graduate/current-students/PoliSciU-advanced-methodology
