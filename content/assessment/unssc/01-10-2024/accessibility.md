---
title: Accessibility Report
weight: 1
draft: false
---

Accessibility report is a document containing the elements of the `xls` grid, but in linear form. It's a summary, so you don't have to navigate through the document tab by tab.


### Audit Context

**Web Site URL:** <https://playground.unssc.org/>

**Date :** 22/09/2024

**Method and Tools used in evaluation:**
 - Wave accessibility checker, 
 - Paul J. Adam Bookmarks, 
 - NVDA, 
 - Color Contrast Analyzer (CCA),
 - Manual Testing.

**Environment:** Windows 10, NVDA 2023.3, Firefox 127


**Note :** 
> When the header receives focus, it lands on the 'Dashboard' button. To access other header buttons, users have to press the left and right arrow keys.
> 
> Although this does not fail any guidelines, to improve navigation, ensure all header buttons can be accessed using tab navigation, or provide a message when the 'Dashboard' button receives focus: 'To access the other buttons, press the left and right arrow keys.'

### Critical accessibility issue.

##### Home Page 

**url:** <https://playground.unssc.org/](https://playground.unssc.org/>

###### Missing alt text


**WCAG test:** 1.1.1


The card behind The Blue line link, OCHA learn link and The Blue line link, Provide appropriate `alt` text for the images or mark them as decorative using `alt=""`.

###### Color contrast issue


**WCAG test:** 1.4.3


Choose your site heading does not meet the contrast ratio guideline of 4.5:1.

###### Unlabeled Form Fields


**WCAG test:** 1.3.5


It should be made more explanatory and prominent to ensure users understand its purpose clearly, such as labeling it "Close button."

##### Forgot Password Page 

**url:** <https://playground.unssc.org/login/forgot_password.php>

###### Color contrast issue

**WCAG test:** 1.4.3


Search button under Search by username and search by Email, both search buttons does not meet the contrast ratio guideline of 4.5:1.

##### Login Page 

**url:** <https://playground.unssc.org/login/index.php>

###### Color contrast issue


**WCAG test:** 1.4.3


The login button, "Forgot Password? Link", and 'cookie notice link' do not meet the contrast ratio guideline of 4.5:1.

###### Error Identification


**WCAG test:** 3.3.1


The error message is generic and does not provide specific details about the error. More descriptive error messages, such as 'Invalid username' or 'Invalid password,' would help users better understand the issue.

##### Dashboard 

**url:** <https://playground.unssc.org/my/>

###### Color contrast issue


**WCAG test:** 1.4.3


Search button, Grid view button, add course link, view all link, lesson 2, 3, and 4 and email address at the bottom of the page does not meet the contrast ratio guideline of 4.5:1.

###### Main Navigation (Tab index – 1 issue)


**WCAG test:** 2.4.1


The links are accessible using the right and left arrow keys. This suggestion was noted in both the Word report and the Excel report. For better navigation, all the main navigation items/tabs can be brought in tab order.

###### Element does not receive focus


**WCAG test:** 2.4.1


All elements should be focusable using the keyboard. The Bookmark button is not in tab order and the course progress info icon, such as 6% complete or 100% complete is not properly readable with screen reader.

###### Unlabeled Form Fields


**WCAG test:** 1.3.5


The combo box next to the Filters button doesn't have an accessible name.

##### Course Catalogue 

**url:** <https://playground.unssc.org/local/unssc\_coursecatalogue/?catalog\_category=0&page=1&perpage=9&lpfilters=>

###### Unlabeled Form Fields


**WCAG test:** 1.3.5

 
The combo box next to the grid view button and filter expand button are unlabeled.

###### Color contrast issue


**WCAG test:** 1.4.3

 
2 search buttons, All catalog button, Grid view button, Load more results button and page number button does not meet the contrast ratio guideline of 4.5:1.

##### My Learning 

**url:** <https://playground.unssc.org/my/courses.php#maincontent>

###### Color contrast issue


**WCAG test:** 1.4.3


The search button and the course name link text do not meet the guideline criterion of a 4.5:1 contrast ratio.

##### Best Value for Money

**url:** <https://playground.unssc.org/course/view.php?id=105>

###### Missing alt text


**WCAG test:** 1.1.1


The image under "We want to hear from you!" does not have alt text.

###### Color contrast issue


**WCAG test:** 1.4.3

 
Search button, Grid view button, Bookmark button, all link and text under "Course contacts" heading and all other link with light blue color as there link text does not meet the contrast ratio guideline of 4.5:1.

##### Ethics and Integrity in Procurement 

**url:** <https://playground.unssc.org/course/view.php?id=104>

###### Color contrast issue


**WCAG test:** 1.4.3


Search buttons and Procurement Training link does not meet the contrast ratio guideline of 4.5:1.

###### Focus order


**WCAG test:** 2.4.3


The focus is jumping from index to main content of the page and index is not accessible using tab navigation.

##### Profile Page

**url:** <https://playground.unssc.org/user/profile.php#sb-5>

###### Missing alt text


**WCAG test:** 1.1.1


Images under Community Updates heading do not have an alt text.

###### Color contrast issue


**WCAG test:** 1.4.3

 
Search button, View button under Upcoming events heading, Download the mobile app button, download button under My Certificates heading and view all links does not meet the contrast ratio guideline of 4.5:1.

### Less Critical Accessibility issue.

##### Home Page 

**url:** <https://playground.unssc.org/>

###### Heading Hierarchy


**WCAG test:** 1.3.1

 
The "Choose Your Site" heading is marked as `<h4>`, but since it is the only heading on the page, it should be marked as `<h1>`.

###### Bypass block


**WCAG test:** 2.4.1


There is a 'Skip to Main Content' link on the page, but the focus does not shift anywhere. The screen reader only announces 'content region,' and upon tabbing again, the focus returns to the 'Skip to Main Content' link

##### Dashboard 

**url:** <https://playground.unssc.org/my/>

###### Heading Hierarchy


**WCAG test:** 1.3.1

 
The heading hierarchy is broken, with an H5 appearing immediately after an `<h1>` on the page, Mark the headings in a hierarchical order from `<h1>` to `<h6>` without skipping levels, ensuring that `<h1>` is only used to convey the meaning or purpose of the page.

##### Course Catalogue 

**url:** <https://playground.unssc.org/local/unssc_coursecatalogue/?catalog_category=0&page=1&perpage=9&lpfilters=>

###### Reflow


**WCAG test:** 1.4.10

 
After zooming to 300%, the page starts to flow in two dimensions.

##### Best Value for Money

**url:** <https://playground.unssc.org/course/view.php?id=105>

###### Heading Hierarchy


**WCAG test:** 1.3.1

 
The heading hierarchy is broken, with an `<h3>` appearing immediately after an `<h1>` on the page.

##### Ethics and Integrity in Procurement 

**url:** <https://playground.unssc.org/course/view.php?id=104>

###### Heading Hierarchy


**WCAG test:** 1.3.1

 
The heading hierarchy is broken, with an `<h3>` appearing immediately after an `<h1>` on the page

##### Profile Page 

**url:** <https://playground.unssc.org/user/profile.php#sb-5>

###### Heading Hierarchy


**WCAG test:** 1.3.1

 
The heading hierarchy is broken; the first heading on the page is marked as `<h6>`, and `<h1>` to `<h4>` have not been used at all on the page.

### Minor Accessibility Issue.

##### Home Page

**url:** <https://playground.unssc.org/>

###### Policies panel - modal content


**WCAG test:** 1.3.1


The box appears as a pop-up window, and all the links are accessible using Tab navigation, as well as the up and down arrow keys. They can also be activated with the spacebar. The section/topic can be given a heading style, although not critical

##### Course Catalogue 

**url:** <https://playground.unssc.org/local/unssc_coursecatalogue/?catalog_category=0&page=1&perpage=9&lpfilters=>

###### Page Title


**WCAG test:** 2.4.2

 
The page does not have an appropriate title; it appears to be the same as the link of the page.
