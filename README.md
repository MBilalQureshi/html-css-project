# Hot Bowl Cuisine
This website is about cooking desi foods. One can learn cooking by watching the videos. It is based on a youtube cooking channel [Hot Bowl Cuisine](https://www.youtube.com/@hotbowlcuisine/featured).

On home page website user can get the information related kitchen visiting hours, contact and address. There is also one video to tell the users how the food is prepared and made.
On Our kitchen page user can see top 3 recipies, other user reviews and a text area to add own review.
There is also a sign up page for users to get signed up.

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