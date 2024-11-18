---
title: User Test Report
weight: 2
draft: false
---

**User Test Report** is a document that summarizes the difficulties encountered by people with disabilities. 

Its testimony will help confirm errors identified during an audit, as well as pointing out problems that do not correspond to WCAG tests.

### Tests Context

**Test completion date:** 27-Sep-2024  
**User technology proficiency:** Intermediate

### Actions

#### Home                                        

##### Action 1

**Result  :**
Home Page This page is accessible. I am able to navigate with a keyboard. It has minimal information.

#### Login

##### Action 1


**Description:**  
Access Login page and test Login Form

**Result :**      
I was able to input the username and password without difficulty. Once I logged in, I got a message asking me to save the username and password  but this message disappeared before I could act on it.

##### Action 2


**Description:**    
Test Password forgotten (Form)

**Result :**    
> I entered the username and pressed lost password, I got an option to get password on my mail id, but it did not get processed.

**Note :**  
Could be a behaviour of the development website.

#### Courses                                             

##### Action 1


**Description:**    
Access Dashboard or My Learning (Both are present only on this test platform)

**Result :**    
> Able to navigate to Dashboard and My Learning tabs.

##### Action 2


**Description:**    
Access Course Catalogue (Landing page of a search) and Check different views/grid, list and carousel.

**Result :**    
> Able to view and navigate course catalogue and different views. Grid, list, carousel.

##### Action 3


**Description:**    
Access a Course Unit (Called “Best Value Unit”)

**Result :**    
> Found course called "Best Value for money".

#### Dashboard                                           

##### Action 1


**Description:**    
Add/Remove courses

**Result :**    
> Add Course is available from the Courses page.
>
> I was able to add a course though there is no audio confirmation when a course is added.
>
> Remove Course does not work consistently.
>
> Tabbing through the course information does not go to the Remove course from plan link, though this can be accessed via a mouse and there is a visual bookmark indicator.
>
> There is no audio confirmation that Course has been deleted
>
> The bookmark icon changes visually, but there is no audio feedback.
>
> We need to go back to Course page to remove Course and check if Course has been removed Inconsistent availability of Remove option.
>
> On repeated use, sometimes the remove option doesn’t appear either as a button or link and does not work on the dashboard and I had to go to the add courses page and remove the files, another day it appears as a link and works. 

#### My Account                                          

##### Action 1


**Description:**    
Access My profile

**Result :**    
> Tabbing on Dashboard page reaches My account tab.After the search button, the next tab is read out as ‘toggle messaging drawer graphic link’Account has Profile, Calendar, Private Files, Reports, Preferences, Log Out.

##### Action 2


**Description:**    
Access Preferences page (Only for users test)

**Result :**    
> Edit preferences- Added description easily

##### Action 3


**Description:**    
Access Notification Preference / Notifications are disturbing me. I would like to stop them.

**Result :**    
> Notification preferences- only check box to disable notifications is functional, which I can navigate with the tab key. The options under that can be accessed with the arrow keys, although they are not functional. 

##### Action 4


**Description:**    
Change Password 

**Result :**    
> Able to change password successfully. Changed to learnerhi123 and back to original one.

### Scenarios

#### “My learning page” - I want to filter my course 

**Description:**    
I would like to find the list of completed courses.

**Result :**    
> I was able to view the list of completed courses.

#### I’m looking for a course with “Money” in the title  

**Description:**    
Someone told me about a course I have to follow, with the word “Money” in title.

**Result :**    
> I was able to find a course with Money in the title

#### I’m looking for a course with a specific theme

**Description:**    
I’m not a UN employee, I’m looking for a Free course.

**Result :**    
> When navigating to the Filters section, I can navigate through the themes using the Tab key, but after the last option on the Themes section (Singing and playing), pressing tab goes directly to ‘Clear all filters’ instead of Type as I would expect.
>
> When someone told me that ‘Type’ occurs after Singing and Playing, then I was able to get to Type by pressing the Down arrow key but I would have missed this if I had not been told there was a category to expand. Even after navigating to type, there is no audio confirmation that category has been expanded, which could result in my missing this entirely.
>
> There are no audio cues of any operation being carried out at this point.

#### I want to bookmark a course

**Description:**    
I should have time next month, my manager told me to take advantage of this time for following some courses. I would like to bookmark some of them.                            

**Result :**    
> It is not clear if course bookmarking is different from adding a course to the learning plan.
> If it is different, I have not been able to figure out how to do it. I am able to bookmark activities and remove bookmarks from activities without any issue.                                   

#### I want to check my calendar 

**Description:**    
I subscribe some courses, I have to plan my week.

**Result :**    
> It is not clear if subscribing to courses is different from enrolling in them. Able to select a course and schedule an event for a specific date and time.

#### I want to continue the course I left

**Description:**    
I think, I left a course in the middle. Can I continue it, exactly where I stopped.

**Result :**    
> Yes, I am able to navigate to the course and continue from where I left off.

#### I want to contact the site support 

**Description:**    
I’m blocked in the website. I have to contact the support team.

**Result :**    
> The contact site support link is very difficult to find using a screen reader. 
> 
> It currently pops up when tabbing to the ‘Show footer’ link and clicking on. This needs to be changed to have a separate link saying ‘Contact Site Support’. When I tried to send an email to site support, the email could not be sent.

**Note :**  
See site support screenshot               

#### Create and Amend learning plan

**Description:**    
Create and amend my learning plan with courses starting in different dates in October and one which is half done.Reach out for help to solve issues.

**Result :**    
> Not clear how to create a learning plan – was not able to do this. When viewing learning plan from the dashboard, am not able to consistently remove courses.Under my learning plan- one day I get remove course from learning plan as a link which works, and one day 
>
> I just get the message remove from plan, but it is neither a link, nor a button and doesn’t work for a screen reader.
>
> Remove from plan is not intuitive as the user needs to hover over the bookmark icon to realise that it is the icon for remove from plan, which only works when the mouse is clicked.                            

#### Receiving a certificate:

**Description:**    
Access a certificate. 

**Result :**  
> I was able to receive a certificate successfully.

#### Activity bookmarks/stars

**Description:**    
Bookmarking an activity.

**Result :**    
> I was able to bookmark an activity successfully.

### Overall comments


> Menu and submenu items could have clearer descriptions e.g. ‘Clickable user menu’ to get to the profile, ‘Toggle drawer options’, ‘Show Footer’ all did not indicate underlying content.

> Make the placement and functionality of content predictable and consistent – for example Adding and Removing a course from a plan should be similar in the way the functionality is accessed.

> Buttons and Links should all be accessible via keyboard.

> The homepage could benefit from providing an option to select user accessibility preferences such as high contrast, screen reader view etc., description of images such as web page logo and a clearer separation of foreground from background.

> The learning plan is very confusing. When clicking on Learning plans from the Profile page I get shown the learning plans list page which saus no learning plans have been created yet. It is not clear how or where to create one or what happens to all the courses I have enrolled in, as they don’t appear to get added to the learning plan.
