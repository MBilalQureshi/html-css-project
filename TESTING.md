# List of bugs and fixes during development
1. Hot bowl Cuisine logo link was not working and there was still hyperlink line under it.

    **Fix:** Add text-decoration to none, change its color to black and fix the broken link.
    
2. Header background pink color gets overflowed from right on small screens.

    **Fix:** Set width to auto instead of 100%.

3. Both background images were causing lot of white space from left side on small screens.

    **Fix:** Add overflow to hidden for both backgroud images.

4. Hot Bowl cuisine logo moves to right on middle size screens.

    **Fix:** Use float left to fix the logo.

<!-- 5. On Tablets nav option moves below the logo
    **Fix:**Set max width to 750px in media query and move the nav styling from first media query to there. -->
6. On mobile screens smaller than 450px search bar overflows its self to right edge of screen.

    **Fix:** Set width of search bar to 70% and add media query of max width of 450px.

7. On tablets search bar moves below its label
    **Fix:** Move code from first media query to the second one.
8. On tablets video on home page has false width height as per tablet screens
    **Fix:**Move code from first media query to the second one.
9. The tabel overflows from bottom to to next content on small screens
    **Fix:**Add margin on top
9.1. The issue number 9 still persist on small screens
    **Fix:** Fix the width for small screen using media query fix the issue.
10. The ingredients list was overflowing over the next available content, Used multiple methods to fix it using, inline, inline block, float right changing div to span, nothing worked
    **Fix:**Using Tutuor support fixed the issue using col-count and set it to 2.
11. Fixing the issue of changing ordered list values to bold 
**Fix:**Used stack overflow to see how to change ordered list marker to bold.
12. At some point the issue number 10 works but still ingredients content is overflowing to the next availaible contetnt
    **Fix:** At the next available content use clear right to avoid this issue.
13. The last ingredient list also overflows to below available content
    **Fix:** Use clear right on below avaialble content (#main-panel) to fix this.
14. As per discussion change second background image on home page to greyscale.
    **Fix:** Change background color to white and use background property of background-blend-mode to luminosity.
15. Padding of about us is invalid
    **Fix:** Remove previous padding and change it to 24px
16. Visit our kitchen time table at home page visibilty is not correct.
    **Fix:** Change background color to white
17. Visit our kitchen time table at home page margin which was already taken care off at fix number 9 still had margin issues
    **Fix:** Change margin to auto and after that give margin top of 14px
18. In footer for margin percentage was used which is not a good practice
    **Fix:** Change percentage to px for margin in footer 
19. Change the font size of search bar at home page
    **Fix:** Change the font size from xx-large to x-large
20. Remove top 3 background color as it might be too much color for some users
    **Fix:** Just remove the code for the background color
21. Stretched images in our food page in some dimensions
    **Fix:** Remove height from the images in our food page
22. Aside was used in our food page which is not required
    **Fix:**remove aside from the our food html file and also removed the style that was applied on it
23. Details element in ingredients is used which is causing lot of space
    **Fix:** Removed details element from our food page
24. User review comments are on the right move them to middle
    **Fix:** Use margin auto to fix the issue
25. There is no margin on top and bottom of the user comments section
    **Fix:** Added margin on top and bottom of user comments section
26. Remove the pink background color from user comments section as there are already other color and this will be too much
    **Fix:** Removed the pink background color
27. Give us a review form was on right, as per user point of view it should be in middle
    **Fix:** User text align center to center the content of form
28. When user writes in the text are in our food page review form, it is too much attached with the border.
    **Fix:** Add padding of 12px in the text area.
29. Change the Sign up for interface as it dosen't look good as per user point of view
    **Fix:** Change background of sign up form to white, border radius to 20px and a shdow box effect.
30. The sign up label is not giving equal space from left and right on differnt screen sizes
    **Fix:** Use the code provided by mentor: top: 50%; transform: translate(-50%, -50%); left: 50%;
31. On some tablet screens the images on our food page size is less than its ingredients list leaveing alot of space below image. In this case image and ingredients list is parallel to each other.
    **Fix:** Use media query for tablet screen sizes less than 1224px and than set the img width to 70% and moving the ingredients content below it.
32. The buttons there should be a point cursor instead of normal mouse pointer
    **Fix:** Add cursor pointer at buttons in stylesheet.
33. A lot of white space was at the bottom of sign up page on many screen sizes.
    **Fix:** Remove absolute and relative positiong, add background image in section use siplay flex.
34. Second background image size is too large which is cauusing performace issue.
    **Fix:** Used and online resize tool to reduce size of image and replace it with the current image.
35. Move navigation to middle of screen instead remaining on left on small screens.
    **Fix:** Used flex to fix this.
36. The featuring video on home page width and height might not be good enough for small screen users.
    **Fix:** Change the width and height of the featuring video.
37. Form in our food was submitting values without any entry.
    **Fix:** Add required to the text area element.