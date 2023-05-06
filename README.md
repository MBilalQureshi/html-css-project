# Hot Bowl Cuisine
This website is about cooking desi foods. It is based on a youtube cooking channel [Hot Bowl Cuisine](https://www.youtube.com/@hotbowlcuisine/featured). One can learn cooking by watching the videos that are linked with website.

Food lovers are more than welcome to come and socialise even take part in upcoming cooking sessions or have a cup of coffee with chef. This website provides the information related kitchen visiting hours for those who wants to meet. contact and address information so that users can get in touch before visiting.

There is weekly top 3 recipies for the website users. Users can submit their reviews based on their experince and obviously sign up.

![Screenshot of Hot Bowl Cuisine website mockup](/assets/images/html-css-project1-mockup.png)

## Features
- Navigation Bar
    - The navigation bar is available on all three pages. It has fully responsive design that changes as per screen size.
    - The logo of Hot Bowl Cuisine is available on top left of the screens. On click user will be able to retuen back to home page.
    - Remaining three navigation links are available on the top right side which are Home, Our Food and Sign up.
    - Website user can easily navigate through website using these links.
    - Keeping kitchen and cooking theme in mind navigation bar background color, font color and font is carefully selected for best user experience.

![Screenshot of Hot Bowl Cuisine website navigation bar](/assets/images/nav-bar.png)

- The landing page image
    - There is a background image which has bread, vegtables and fruits in it which defines own its on what the page is about.
    - On the right side of background image there is a label on which a  very popular quotation of Wolfgang Puck is written for user attraction.
    - The label background color, font and font color itself is very beautiful to grab the attention of this website users.

![Screenshot of Hot Bowl Cuisine home page landing image and label](/assets/images/landing-image.png)

- Search Bar
    - The search bar is used to search for the recipies you like.
    - User can directly search for the required recipie instead of navigating the whole website.

![Screenshot of Hot Bowl Cuisine home page landing image and label](/assets/images/search-bar.png)

- Featuring Video
    - On the back side of the featuring video, there is a greyscale image to beautify the look of the video.
    - The featuring video is basically to tell the website users how the food is prepared along with the list of required recipies.

![Screenshot of Hot Bowl Cuisine featuring video](/assets/images/featuring-video.png)

- About us
    - About us section tells the users how they can make international dishes at home.
    - What different varieties of dishes users can try.
    - There is also an option to open the main youtube channel in new tab by clicking the link available in about us section.

![Screenshot of about us at home page](/assets/images/about-us.png)

- Visit Our kitchen
    - The time table shows the user when they can come to visit, share their thoughts, give suggestions or have a cup of coffee with chef.
- Address
    - This section tells the user where to come for visit.
- Our Contact
    - User can contact the chef and get appointment before visiting.
    - User can either contact via phone or email.

![Screenshot of details related visiting hours, address and our contact](/assets/images/details.png)

- Footer
    - Using the social media links in footer user can easily stay connected with Hot Bowl Cuisine and know what's new, are there any new recipies to try or which are top three weekly recipies.
    - All the social media links will open in new tab for users feasibility.

![Screenshot of social media links in footer](/assets/images/footer.png)

- Our top 3 recipies
    - On our food page, user can see what weekly top 3 recipies are trending.
    - On clicking the image of any of the top three trending recipies, user can switch to youtube channel where he/she can see the whole video and try making the same recipie at home.
    - In top 3 recipies section user is also able to see the Ingredients list to prepare the food.

![Screenshot of our food page's top three recipies](/assets/images/top3-recipies.png)

- User Reviews
    - Users can see the what others think about the services provided by Hot Bowl Cuisine.
    - User can also decide if they want to become a proper visitor based on the reviews provided by other users.

![Screenshot of our User reviews on our food page](/assets/images/user-reviews.png)

- How are we doing?
    - Users can give their feedback which will be added to user reviews.
    - Feedback can be positive or negative but based on that it will help future users to better undestand the website.

![Screenshot of our User reviews on our food page](/assets/images/how-are-we-doing.png)
## Fixes
1. Hot bowl Cuisine logo link is not working and there is still a line under it.
    Fix: Add text-decoration: none; on .home a and changed its color to black.
2. Header background pink color gets overflowed from right on small screens.
    Fix: width set to auto instead of 100%
3. Issue 3a and 3b are same, Alot of white space is left on small screens on background image areas
    Fix: Add overflow:hidden in bcakground image styling
4. Hot Bowl cuisine logo moves to right on middle size screen sizes
    fix: Use float: left to fix the logo on left
5. On Tablets nav option moves below the logo
    Fix:Set max width to 750px in media query and move the nav styling from first media query to there.
6. On mobile screens smaller than 450px search bar overflows its self to right side.
    Fix:Set width of search bar to 70% and add media query of max width of 450px
7. On tablets search bar moves below its label
    fix: Move code from first media query to the second one.
8. On tablets video on home page has false width height as per tablet screens
    fix:Move code from first media query to the second one.
9. The tabel overflows from bottom to to next content on small screens
    fix:Add margin on top
9.1. The issue number 9 still persist on small screens
    fix: Fix the width for small screen using media query fix the issue.
10. The ingredients list was overflowing over the next available content, Used multiple methods to fix it using, inline, inline block, float right changing div to span, nothing worked
    Fix:Using Tutuor support fixed the issue using col-count and set it to 2.
11. Fixing the issue of changing ordered list values to bold 
Fix:Used stack overflow to see how to change ordered list marker to bold.
12. At some point the issue number 10 works but still ingredients content is overflowing to the next availaible contetnt
    Fix: At the next available content use clear right to avoid this issue.
13. The last ingredient list also overflows to below available content
    Fix: Use clear right on below avaialble content (#main-panel) to fix this.
14. As per discussion change second background image on home page to greyscale.
    fix: Change background color to white and use background property of background-blend-mode to luminosity.
15. Padding of about us is invalid
    fix: Remove previous padding and change it to 24px
16. Visit our kitchen time table at home page visibilty is not correct.
    Fix: Change background color to white
17. Visit our kitchen time table at home page margin which was already taken care off at fix number 9 still had margin issues
    Fix: Change margin to auto and after that give margin top of 14px
18. In footer for margin percentage was used which is not a good practice
    Fix: Change percentage to px for margin in footer 
19. Change the font size of search bar at home page
    Fix: Change the font size from xx-large to x-large
20. Remove top 3 background color as it might be too much color for some users
    Fix: Just remove the code for the background color
21. Stretched images in our food page in some dimensions
    Fix: Remove height from the images in our food page
22. Aside was used in our food page which is not required
    fix:remove aside from the our food html file and also removed the style that was applied on it
23. Details element in ingredients is used which is causing lot of space
    Fix: Removed details element from our food page
24. User review comments are on the right move them to middle
    Fix: Use margin auto to fix the issue
25. There is no margin on top and bottom of the user comments section
    Fix: Added margin on top and bottom of user comments section
26. Remove the pink background color from user comments section as there are already other color and this will be too much
    Fix: Removed the pink background color
27. Give us a review form was on right, as per user point of view it should be in middle
    Fix: User text align center to center the content of form
28. When user writes in the text are in our food page review form, it is too much attached with the border.
    Fix: Add padding of 12px in the text area.
29. Change the Sign up for interface as it dosen't look good as per user point of view
    Fix: Change background of sign up form to white, border radius to 20px and a shdow box effect.
30. The sign up label is not giving equal space from left and right on differnt screen sizes
    Fix: Use the code provided by mentor: top: 50%; transform: translate(-50%, -50%); left: 50%;
31. On some tablet screens the images on our food page size is less than its ingredients list leaveing alot of space below image. In this case image and ingredients list is parallel to each other.
    Fix: Use media query for tablet screen sizes less than 1224px and than set the img width to 70% and moving the ingredients content below it.
32. The buttons there should be a point cursor instead of normal mouse pointer
    Fix: Add cursor pointer at buttons in stylesheet.
33. A lot of white space was at the bottom of sign up page on many screen sizes.
    Fix: Remove absolute and relative positiong, add background image in section use siplay flex.
34. Second background image size is too large which is cauusing performace issue.
    Fix: Used and online resize tool to reduce size of image and replace it with the current image.
35. Move navigation to middle of screen instead remaining on left on small screens.
    Fix: Used flex to fix this.
36. The featuring video on home page width and height might not be good enough for small screen users.
    Fix: Change the width and height of the featuring video.