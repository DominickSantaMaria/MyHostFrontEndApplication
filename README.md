# MyHost-FrontEnd
Front End code for MyHost application project

30 Oct 2021
Started login screen. The webpage still looks good when resized and appears to be compatible with mobile.

01-02 Nov 2021
Added User home screen, basic table layout, and jquery functionality
Added tableTemplate.html for table selection, passing selected table to tableTemplate functionality, converted jquery back to javascript functionality

03 Nov 2021 (at 1 am...)
Added functionality to tableTemplate.html using sessionStorage to pass table selection information to change template to selected table. So far, only the table displayed, table name,
and how many seats the selection has changed. Need to create a dyanmic change for the placeholder time and adjust table sizing. Plan to code confirm table selection next.

Added nav bar that we can add more buttons if necessarily and css to go along. No functionality for the logout or account buttons yet.
Added pop up tests for table reservation page.

07 Nov 2021
1. Added CSS grid to Table Template file to make customization easier. Also added a form for entering information for table and separate stylesheet for table template.
2. Added login styles css file / updated login input css
3. Added sign up styles css file / updated sign up input css
4. Adjusted table template so max attribute of input for partySize to match max seats for table type selected
5. Added error handling on booking details for phone number, and option to opt in or out of automatic table swapping
6. Updated table template size display from scale(1) --> scale(1.5)

08 Nov 2021
1. Added admin view home page and some basic information. Added buttons to navigation bar to switch between admin view and user view for placeholder purposes.
2. Updated links for buttons on navigation bar to inherit color so text isn't blue anymore + MyHost now is a button to home page.
3. Added admin view table layout page, adjusted some formatting. Will plan to add customizable...grid. Work in progress and patience.

12 Nov 2021
1. Adding adminLayout html and style sheet for html page. Adding an incomplete layout html and plan to add more. Wanted to go ahead and add to project.

Next Steps:
1. Organize and develop created home screen (In Progress)
2. Figure out how to make interactive pages for the table configurations / choose table in restaurant.
3. Create booking screen for restaurant. (DONE)
4. Create web notification that a different table is available (need connection to backend to be able to test)
 . More user stuff
x. Create admin view for managing tables
y . create admin view for moving tables in or out of the restaurant. 
z. ? 

Later Steps:
[ ] 1. Add javascript for login and registration in the login.html and signup.html pages. 
[ ] 2. Connect the front end to the backend via sockets. JavaScript -> Java



Notes for Website <---> Server (backend) communication
1. Do we use sockets for communication? 
   This would involve the frequent communication of persistent sockets.

2. Create temporary sockets sending json objects back and forth for details? 






