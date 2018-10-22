# [Start Bootstrap - Creative](https://startbootstrap.com/template-overviews/creative/)

Ref:
Challenge Overview
App environment:
- HTML, CSS, Javascript, Bootstrap (UI Prototype)

Basic requirements for this challenge:
- Build Responsive Web UI Prototype based on storyboard design
- Need load and create data from embedded JSON files.

Project Background
The Vendor Management Team at TopcoderMobile is launching Topcoder’s crowdsourcing solution across its technology organization. In an effort to promote and inform TopcoderMobile's teams about the program they would like to create a microsite.

This responsive website would provide a one-stop solution for view information about the program, with the ability to navigate to different sections and areas to learn more.

Technology Stack
- HTML
- CSS
- Javascript
- Bootstrap
- JSON

Deployment environment requirements
- localhost
- heroku

Challenge Assets:
Gdrive: https://drive.google.com/open?id=1OISipccEksURN55GHDKM9L4k2amzAJPw

MarvelApp:
Desktop: https://marvelapp.com/44058jj
Tablet: https://marvelapp.com/9g0cfee
Mobile: https://marvelapp.com/7709d43

General Requirements
- Build provided storyboard into best practice Responsive UI Prototype across required browser on responsive Desktop/Tablet/Mobile screen size
- Use Bootstrap to build base layout of this submission
- As possible we need most elements using Bootstrap styling
- Data for each pages as possible need loaded from JSON files.
- Responsive size requirements:

Desktop layout
- Provided storyboard using 1400px.
- All sections background need covered browser screen, while the main content area centered.

Tablet layout
- Provided storyboard using 786px.
- All sections background and content need use fluid width as device screen
- Make sure your prototype look good on Portrait and Landscape view

Mobile layout
- Provided storyboard using 375px.
- All sections background and content need use fluid width as device screen
- Make sure your prototype look good on Portrait and Landscape view

Individual Requirements
1). Homepage
DESKTOP VERSION:
Screenshot: D_01_Landing-Onepage.png
- This is homepage look and feel
- You may use parallax effect when scrolling for the background image. Apply consistently to another pages
- Logo placeholder need easily swapped for TopcoderMobile logo
- Create animation effect for the menu navigation, something like lava menu. Any other ideas?
- Match active state styling
- Current Status Report and Start Project placed on the right side
- Video player need placed centered
- Click play button need load the video
- Display statistic below the video player
- How it works need able to show up the tooltip when hover
- Completed Projects need take to separate page. We need support this to auto set active tab of Completed Project based on selected division
- Click the arrow on Project menu navigation need load dropdown option (Screenshot: D_01_2_Landing-Onepage Copy.png)

TABLET VERSION:
Screenshot: T_01_Landing-Onepage.png
- For tablet screen size, main navigation will be placed under hamburger menu
- Click Hamburger menu need display floating sidebar like this (Screenshot: T_04_Navigation.png)
- Click Project need expand the sub-menu (Screenshot: T_04_2_Navigation.png)
- Use animation effect when hide and show the sidebar
- Start a Project button and Current Status Report need placed on top.
- Set active state for menu based on related page.  
- No need display the Privacy Policy, Terms & Condition links
- All elements need resized as browser screen
- On tablet, instead hover, need able to click/tap How it works section to show up the tooltips
- Completed projects card need auto shift down
- All footer content need to be centered

MOBILE VERSION:
Screenshot: M_01_Landing-Onepage.png
- For mobile screen size, main navigation will be placed under hamburger menu
- Click Hamburger menu need display floating sidebar like this (Screenshot: M_04_Navigation.png)
- Click Project need expand the sub-menu (Screenshot: M_04_2_Navigation.png)
- Use animation effect when hide and show the sidebar
- Start a Project button and Current Status Report need placed on top.
- Set active state for menu based on related page.  
- No need display the Privacy Policy, Terms & Condition links
- All elements need resized as browser screen
- All elements need resized as browser screen
- Project stats need to be swipeable
- How it works move to different row instead of single line like on Tablet/Desktop
- On mobile, instead hover, need able to click/tap How it works section to show up the tooltips
- Completed projects cards need shift down in separate line
- All footer content need to be centered

2). Projects
DESKTOP VERSION
Screenshot: D_02_1_Preload-Projects.png
- This is when user navigate to Completed Projects page
- Need quick animation for all charts on page load
- You may use d3js or coming with your own suggestion
- All challenges tabs need load by default if user click menu from top navigation
- If user click Completed Project Cards from homepage need auto set active tab to related Design, Development or Data Science Division
- By default we need your display this preloader effect on table row
- This is table look after data loaded (Screenshot: D_02_2_Projects.png)
- Match different border color based based on Design, Development and Data Science
- Click each row for Design, Development and Data Science will take to separated details page with different icons. See details below.
- Click filter need load this flyout (Screenshot: D_02_3_Projects-Filter.png)
- Make sure datepicker using same styling like overall application
- Click load more button need load more rows

TABLET VERSION
Screenshot: T_02_1_Preload-Projects.png
- This is tablet look for Completed Projects page
- Stats on top need auto move down
- Tabs need remain centered, you need display all tabs
- Input and filter need adapt fluid width
- Make sure the preloader graphics look good in tablet size
- This is page look after data loaded, you need adjust content placement based on storyboard look (Screenshot: T_02_2_Projects.png)
- This is when filter flyout show up (Screenshot: T_02_3_Projects-Filter.png)
- Filter flyout need use same width like the row.
- Click load more button need load more rows

MOBILE VERSION
Screenshot: M_02_1_Preload-Projects.png
- This is mobile version look for completed projects
- Stats need move in separated line
- Completed Projects tab need swipeable
- Input and filter need use fluid width
- Make sure preloader adjusted for mobile screen size
- This is table row look after data loaded (Screenshot: M_02_2_Projects.png)
- Adjust the content placement to follow storyboard
- This is when filter flyout show up (Screenshot: M_02_3_Projects-Filter.png)
- Filter flyout need use same width like the row. Adjust input placement to follow storyboard look
- Click load more button need load more rows

3). Project Detail
DESKTOP VERSION
Screenshot: D_03_1_Project-Detail.png
- This is Project Detail look
- You need create separate project details for Development (Screenshot: D_03_2_Project-Detail.png) and Data Science (Screenshot: D_03_3_Project-Detail.png)
- Capture the icon differences
- Click back arrow button need take user to Completed Projects page
- Display stats on top of page
- Match content and styling based storyboard
- Testimonials are need scrollable

TABLET VERSION
Screenshot: T_03_1_Project-Detail.png
- You need create separate project details for Development (Screenshot: T_03_2_Project-Detail.png) and Data Science (Screenshot: T_03_3_Project-Detail.png)
- For tablet version, need make the page support fluid width
- Content on the right side on desktop, need move down and swipeable on tablet view
- Testimonials need remain swipeable

MOBILE VERSION
Screenshot: M_03_1_Project-Detail.png, Screenshot: M_03_2_Project-Detail.png
- This is mobile screen look
- You need create separate project details for Development (Screenshot: M_03_2_Project-Detail.png) and Data Science (Screenshot: M_03_3_Project-Detail.png)
- Stats information need swipeable
- Content need use fluid width
- Content on the right side on desktop, need move down and swipeable on tablet view
- Testimonials need remain swipeable

4). How it Works
DESKTOP VERSION
Screenshot: D_04_How-it-Works.png
- This is How it works page
- Important: remove the video player and move the content up
- This will be contains of static content

TABLET VERSION
Screenshot: T_05_How-it-Works.png
- Adjust content for tablet screen size

MOBILE VERSION
Screenshot: M_05_How-it-Works.png
- Adjust content for mobile screen size

5). Status Reports
DESKTOP VERSION
Screenshot: D_05_1_Program-Documents.png
- Current Status Report need load by default
- Match active/inactive state on the left sidebar
- This is the Archived Status Report look (Screenshot: D_05_2_Program-Documents.png)
- This is Walking Deck (Screenshot: D_05_3_Program-Documents.png)
- This is Reference Material (Screenshot: D_05_4_Program-Documents.png)
- This is Survey Result (Screenshot: D_05_5_Program-Documents.png)
- You need linke the content area in the right with embedded PPT file, make sure file displayed in page.
- Match active state for the left sidebar

TABLET VERSION
Screenshot: T_06_1_Status-Reports.png
- On mobile, we need move the tab to top.
- Tab need to be swipeable
- Need use same height for all menu navigation
- Table row need use fluid width
- This is Survey Result (Screenshot: T_06_2_Status-Reports.png)
- This is the Program Documents tab (Screenshot: T_06_3_Status-Reports.png)
- This is Reference Material (Screenshot: T_06_4_Status-Reports.png)

MOBILE VERSION
Screenshot: M_06_1_Status-Reports.png
- On mobile, we need move the tab to top.
- Tab need to be swipeable
- Need use same height of the menu
- Table row need use fluid width
- This is Survey Result (Screenshot: M_06_2_Status-Reports.png)
- This is the Program Documents tab (Screenshot: M_06_3_Status-Reports.png)
- This is Reference Material (Screenshot: M_06_4_Status-Reports.png)

6). Contact Us
DESKTOP VERSION
Screenshot: D_06_4_Contact-Us-ALT.png
- Click email link need use mailto tag
- Match the styling like storyboard

TABLET VERSION
Screenshot: M_07_4_Contact-Us-ALT.png
- Click email link need use mailto tag
- Match the styling like storyboard

MOBILE VERSION
Screenshot: T_07_4_Contact-Us-ALT.png
- Click email link need use mailto tag
- Match the styling like storyboard

6). FAQs
DESKTOP VERSION
Screenshot: D_07_1_FAQs.png
- FAQs page need display search on top
- Search input need support auto suggest (Screenshot: D_07_2_FAQs.png)
- Highlight the typed keyword on the search result
- You need display preloader when load the data
- Need able to expand each row to see the answer

TABLET VERSION
Screenshot: T_08_1_FAQs.png
- On tablet, need use fluid width for FAQs page
- This is how auto suggest look for tablet (Screenshot: T_08_2_FAQs.png)

MOBILE VERSION
Screenshot: M_08_1_FAQs.png
- On mobile, need use fluid width for FAQs page
- This is how auto suggest look for tablet (Screenshot: M_08_2_FAQs.png)

Client Priorities (The items that are considered highest prototype priorities)
- Creating quality and efficient UI Prototype that works in all the requested browsers.
- All elements should be consistent pay attention to padding, margin, line-height, etc.
- Matching the storyboards (as close as possible) across the required browsers.
- Responsive Web Design solution!

CODE REQUIREMENTS:
HTML/HTML5
- Provide comments on the page elements to give clear explanation of the code usage. The goal is to help future developers understand the code.
- Please use clean INDENTATION for all HTML code so future developers can follow the code.
- All HTML code naming should not have any conflicts or errors.
Element and Attribute names should be in lowercase and use a "-" or camel naming to separate multiple-word classes (i.e.. "main-content", or "mainContent)
- Use semantically correct tags- use H tags for headers, etc. Use strong and em tags instead of bold and italic tags.
- No inline CSS styles- all styles must be placed in an external stylesheet.
- Validate your code- reviewers may accept minor validation errors, but please comment your reason for any validation errors. Use the validators listed in the scorecard.

CSS3
- Provide comments on the CSS code. We need CSS comments to give a clear explanation of the code usage. The goal is to help future developers understand the code.
- Please use clean INDENTATION for all CSS so developers can follow the code.
- All CSS naming should not have any conflicts.
- As possible use CSS3 style when create all styling.
- Use CSS to space out objects, not clear/transparent images (GIFs or PNGs) and use proper structural CSS to lay out your page. Only use table tags for tables of data/information and not for page layout.

Javascript
- All JavaScript must not have a copyright by a third party.
- It is fine to use GPL/MIT/Open Source code.
- You are encouraged to use your own scripts, or scripts that are free, publicly available and do not have copyright statements or author recognition requirements anywhere in the code.

Images
- Images should be properly compressed while still having good visual quality.
- Please use best practice repetition usage of background based image.
- Please use sprites when using icons for your submission.
- Make sure your submission look sharp for Retina and Standard devices
- Wherever it makes sense, you can use icon fonts instead of images.

Web Browsers Requirements
Your submission must look and work consistently across these following browsers on the latest versions:  
- IE11,  
- Edge,
- Chrome,
- Safari,
- Firefox
Final Submission Guidelines
What To Submit?
- Create clear documentation about how to set up your submission locally and on Heroku.
- Create CI/CD to support auto deployment from Gitlab to Heroku
- Upload your submission to Heroku for client review, Include the link on your README.md