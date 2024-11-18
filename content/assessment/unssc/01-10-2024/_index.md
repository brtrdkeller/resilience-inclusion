---
title: "Digital Accessibility Assessment Report"
subtitle: United Nation System Staff College (UNSSC)
date: 2024-10-01
description: |-
    Website to follow the UNSSC digital accessibility assessment. You'll find all the documents listing users and technical issues
type: study
authors: 
    - United Nation System Staff College (UNSSC)
---

### Content of this assessment report

In September 2024 UNSSC entrusted Humanity and Inclusion (HI) to carry out a digital accessibility assessment of 7 pages of the UNSCC LMS [Dashboard | The Blue Line (unssc.org)](https://playground.unssc.org/my) during the UAT phase of their LMSs codebase upgrade. This assessment included evaluating the main student interface and suggesting actionable feedback and necessary changes for the development finalization phase, and related only to the learner’s interface as this is the one directly affected by their theme and custom functionalities. The assessment did not include materials and documents uploaded in the LMS (files, audiovisuals, e-pubs, external links, etc.).

The assessment was conducted by HI’s digital accessibility experts and with the participation of a user with visual impairments.

This assessment report summarizes the methodology that was used for the exercise, the accessibility flaws identified, and the main recommendations addressed to UNSSC developers in order to improve the level of accessibility of the LMS in object. 

### Introduction – context of the request (extract from ToRs)

UNSCC has taken steps to improve the digital accessibility of their courses. The College has developed Learning Management Systems (or LMSs) designed for, and by, the UN via the software Moodle Workplace, which is currently in the process of being upgraded to WCAG 2.1 Level AA accreditation. UNSSC LMSs include the [Blue Line](https://www.unssc.org/blue-line/), a global learning hub. While the UNSSC strategic action plan currently does not refer to disability inclusion or twin track approach or intersectionality, it is currently being updated and this will be corrected. 

All content on the [Blue Line](https://www.unssc.org/blue-line/) meets basic accessibility requirements, thanks to a review process and the availability of internal guidance and SOP to support developers in meeting these basic criteria.

### Specific background (extract from ToRs)

The UNSSC Learning Management System (LMSs) has a bespoke theme and 7 custom pages that can be accessed by learners. In order of access, these are:

1. Home page
2. Login page
3. Dashboard page
4. Catalogue page
5. My courses page
6. Course page (List and grid view)
7. Profile page

UNSSC aims at evaluating these pages as they deviate from the standard Moodle Workplace structure, functionality and theme. UNSSC LMS is, currently based on version 3.11.12 of Moodle Workplace, and it will upgrade to Moodle Workplace 4.11.1. This is a big upgrade from a user experience point of view as it will significantly improve the user interface. The upgrade will take place in the UNSSC non-production site, which is already populated with sample data. The upgrade will be performed by UNSSC ICT team in a similar fashion as for the production sites later. After the upgrade takes place, this team will do the platform set-up so that it fully resembles the desired production experience and provides access to internal users for testing. A walkthrough meeting will take place to onboard everyone participating in the User Acceptance Testing (UAT) phase, during which the objectives and desired outcomes will be explained.

### Limitations

Please note that at the time of this accessibility assessment the LMS in object is not fully complete and that UNSSC developers are still working on it, modifying also structural elements.

In addition, during the kick-off meeting with UNSSC, HI has been asked not to assess the accessibility of every element of the 7 pages listed above, but to focus on specific elements and actions that were considered particularly relevant and that were not likely to be further modified. Therefore, it hasn’t been possible to achieve one of the initial objectives proposed by HI in it’s offer to UNSSC, that is to say determining the level of conformity of the pages in object with Level AA of the WCAG 2.1.

### Adopted methodology

The accessibility assessment of the 7 above mentioned pages of UNSSC LMS has been conducted in two steps:

#### Step 1: Digital accessibility assessment by technical experts

HI experts conducted a remote digital accessibility assessment of the agreed elements of the 7 pages of the learners’ interface, referring to the criteria of the Web Content Accessibility Guidelines (WCAG) 2.2. The assessment has been done using automated and manual testing, and it involved keyboard navigation, screen reading tools, colour contrast, etc. It has been done cross browsers on a Windows based laptop/desktop only, and did not include smartphones, tablets or other devices.

#### Step 2: Accessibility testing by an end-user with visual disabilities

This second part of the assessment has taken the form of a non-moderated user test carried out by 1 end-user with visual impairments, and it helped to determine how easy it is to navigate the 7 pages or to perform actions like log-in, register, search, etc. Such exercise was fundamental to understand difficulties and barriers that learners with certain disabilities may experience when using the platform.
