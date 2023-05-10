# Testing
- I confirmed that in sign up page all inputs from user is required and can't be left empty.
- I confirmed that text area in our food page can't be left empty during submission.
- I confirmed that submit button on our food and sign up page works.
- I confirmed all the links in footer, about us and top 3 recipes opens in new tab.

## Browser Compatibility
- I confirmed that this website works on following browsers.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](/documentation/readme_img/chrome-preview.png) | Works as expected |
| Firefox | ![screenshot](/documentation/readme_img/firefox-preview.png) | Works as expected |
| Edge | ![screenshot](/documentation/readme_img/edge-preview.png) | Works as expected |

## Responsiveness

I confirmed that website is completely responsive on different screen sizes.

| Device | Home | Contact us | Top 3 recipes | Sign up | Notes |
| --- | --- | --- | --- | --- | --- |
| XS Mobile (DevTools - Galaxy S9+ - 320 x 658) | ![screenshot](/documentation/readme_img/xs-mobile-home.png) | ![screenshot](/documentation/readme_img/xs-mobile-contactus.png) | ![screenshot](/documentation/readme_img/xs-mobile-top3.png) | ![screenshot](/documentation/readme_img/xs-mobile-signup.png) | Works as expected |
| Small Mobile (DevTools - iphoneX - 375 x 812) | ![screenshot](/documentation/readme_img/ss-mobile-home.png) | ![screenshot](/documentation/readme_img/ss-contact-us.png) | ![screenshot](/documentation/readme_img/ss-top3-recipies.png) | ![screenshot](/documentation/readme_img/ss-signup.png) | Works as expected |
| Medium Mobile (DevTools - Pixel 3 - 393 x 786) | ![screenshot](/documentation/readme_img/m-mobile-home.png) | ![screenshot](/documentation/readme_img/m-contact-us.png) | ![screenshot](/documentation/readme_img/m-top3-recipies.png) | ![screenshot](/documentation/readme_img/m-signup.png) | Works as expected |
| Large Mobile (DevTools - S20 Ultra - 412 x 915) | ![screenshot](/documentation/readme_img/l-mobile-home.png) | ![screenshot](/documentation/readme_img/l-mobile-contactus.png) | ![screenshot](/documentation/readme_img/l-mobile-top3.png) | ![screenshot](/documentation/readme_img/l-mobile-signup.png) | Works as expected |
| Small Tablet (DevTools iPad Mini - 786 x 1024) | ![screenshot](/documentation/readme_img/s-tablet-home.png) | ![screenshot](/documentation/readme_img/st-contact-us.png) | ![screenshot](/documentation/readme_img/st-top3-recipies.png) | ![screenshot](/documentation/readme_img/st-signup.png) | Works as expected |
| Tablet (DevTools iPad Pro - 1024 x 1366) | ![screenshot](/documentation/readme_img/lt-home.png) | ![screenshot](/documentation/readme_img/lt-contactus.png) | ![screenshot](/documentation/readme_img/lt-top3.png) | ![screenshot](/documentation/readme_img/lt-signup.png) | Works as expected |
| Laptop (HP Omen - 1536 x 864) | ![screenshot](/documentation/readme_img/laptop-home.png) | ![screenshot](/documentation/readme_img/laptop-contact-us.png) | ![screenshot](/documentation/readme_img/laptop-top3.png) | ![screenshot](/documentation/readme_img/laptop-signup.png) | Works as expected |
| Desktop (Dell - 1920 x 1080)| ![screenshot](/documentation/readme_img/desktop-home.png) | ![screenshot](/documentation/readme_img/desktop-contactus.png) | ![screenshot](/documentation/readme_img/desktop-top3.png) | ![screenshot](/documentation/readme_img/desktop-signup.png) | Works as expected |

## Validator Testing

### HTML validator

I used the recommended [W3C validator](https://validator.w3.org/) to validate my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmbilalqureshi.github.io%2Fhtml-css-project%2Findex.html) | ![screenshot](/documentation/readme_img/w3c-validator-home-page.png) | Pass: No Errors |
| Our Food | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmbilalqureshi.github.io%2Fhtml-css-project%2Four-food.html) | ![screenshot](/documentation/readme_img/w3c-validator-our-food.png) | Pass: No Errors |
| Sign up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmbilalqureshi.github.io%2Fhtml-css-project%2Fsign-up.html) | ![screenshot](/documentation/readme_img/w3c-validator-sign-up.png) | Pass: No Errors |

### CSS validator
- I confirmed that no errors were returned when CSS code was passed through [jigsaw validator](https://jigsaw.w3.org/css-validator/).

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmbilalqureshi.github.io%2Fhtml-css-project%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](/documentation/readme_img/jigsaw-validator-css.png) | Pass: No Errors |

## Accessibility

### Fonts and colors

I confirmed that fonts and colors that are chosen are easy to read and enhances user experince.

### Lighthouse Audit
- I have used lighthouse devtool after deployment to fix major issues. Issues found by Lighthouse is mentioned below.
    - Reduce background image sizes.
    - Change format of background images to webp format.
    - In html tags use role = img along with aria labels when background images are declared in CSS files.
    - Add meta keywords tag in head element of each page.

Following are the results of Lighthouse audit of every page for mobile and desktop. Accessibility is 100 in every case.

| Page | Size | Screenshot |
| --- | --- | --- |
| Home | Mobile | ![screenshot](/documentation/readme_img/mobile-audit-home.png) |
| Home | Desktop | ![screenshot](/documentation/readme_img/desktop-audit-homepage.png) |
| Our Food | Mobile | ![screenshot](/documentation/readme_img/mobile-audit-our-food.png) |
| Our Food | Desktop | ![screenshot](/documentation/readme_img/desktop-audit-ourfood.png) |
| Sign up | Mobile | ![screenshot](/documentation/readme_img/mobile-audit-signup.png) |
| Sign up | Desktop | ![screenshot](/documentation/readme_img/desktop-audit-signup.png) |

## List of bugs and issues
1. Hot bowl Cuisine logo link was not working and there was still hyperlink line under it after styling.
    #### Fix:
    - Set text-decoration: none; for valid header tags after that add color: black; and fix the broken link in html.

2. Header background pink color gets overflowed from right on small screens.

    #### Fix:
    - Set width: auto; instead of 100%.

3. Both background images on home page were causing lot of white space from left side on small screens.

    #### Fix:
    - Add overflow: hidden; for both background images.

4. Hot Bowl cuisine logo moves to right on middle size screens.

    #### Fix:
    - Use float: left; to fix the logo.

5. On mobile screens smaller than 450px search bar extends its self to right edge of screen.

    #### Fix:
    - Make media query of max width of 450px.
    - Set width: 70%; for search bar.

6. On tablets search bar moves below its label
    #### Fix:
    - Make media query of max width of 750px and write navigation code in it instead of inside 950px screens.

7. The time table overflows from bottom to next content on small screens
    #### Fix:
    - Add margin-top: 15px; inside media query of max width of 950px.
    - Add width: fit-content; inside media query of max width of 450px.

8. The ingredients list was overflowing over the next available content below it on medium screen sizes.
    #### Fix:
    - Using Tutor support fixed the issue by adding column-count: 2;

9. Ingredients Ordered list numeric values marker was not turning to bold.
    #### Fix:
    - Learned from stack overflow that I just needed to add ::marker with class name and give font-weight: bold;

10. At some point the issue number **8** works but still ingredients content is overflowing to the next available content.
    #### Fix:
    - At the next available content use clear: right; to avoid this.

11. The last ingredient list also overflows to below available content
    #### Fix:
    - Use clear: right; on user reviews div to fix this.

12. Form in our food was submitting values without any entry.
    #### Fix:
    - Add required to the text area tags.

 **Fixes after discussion with mentor**

13. Change second background image on home page to greyscale but not the content on top of it.
    #### Fix: 
    - Learned from stack overflow that I need to change background color to white and use background property of background-blend-mode: luminosity;

14. Padding of about us paragraph was invalid
    #### Fix:
    - Remove previous padding and change it to 24px

15. Visit our kitchen time table at home page visibility was really low and it was hard to see the time table.
    #### Fix: 
    - Change table background color to white.

16. Visit our kitchen time table at home page margin which was already taken care off at fix number **7** still had margin issues
    #### Fix:
    - Change margin to auto and after that give margin top of 14px but not inside media query.

17. In footer for margin percentage was used better practice is to use px as per discussion with mentor.
    #### Fix: 
    - Change percentage to px for margin in footer 

18. Change the font size of search bar at home page just a little bit.
    #### Fix:
    - Change the font size from xx-large to x-large

19. Remove background color from our food page where ingredients were mentioned as it might be too much colors for some users
    #### Fix: 
    - Simply remove the code for the background color

20. Stretched images in our food page in some screen sizes
    #### Fix: 
    - Remove height from the images in our food page.

21. Aside was used in our food page which is not required.
    #### Fix: 
    - Simply remove aside from our food html file and also removed the style that was applied on it.

22. Details tag in ingredients was causing lot of white space unless user clicks on it. Remove it for better user interface.
    #### Fix: 
    - Simply removed details tag from our food page.

23. User comments on our food page are on the right move them to middle for better UI.
    #### Fix: 
    - Use margin: auto; on the outer most div for user comments.

24. There is no margin on top and bottom of the user comments section
    #### Fix: 
    - Added margin on top and bottom of user comments section
       
25. Remove the pink background color from user comments section as there are already other color and this will be too much from user point of view.
    #### Fix: 
    - Simply remove the pink background color.

26. Give us a review form was on right, as per user point of view it should be in middle on large screens.
    #### Fix: 
    - Use text-align: center; to move the text area and submit button to middle.

27. When user writes in the text are in our food page review form, it is too much attached with the border.
    #### Fix: 
    - Add padding: 12px; in the text area.

28. Change the Sign up for interface as it doesn’t look good as per user point of view
    #### Fix: 
    - Change background of sign up form to white, border radius to 20px and a shadow box effect.

29. On some tablet screens the images on our food page size is less than its ingredients list leaving a lot of space below image. In this case image and ingredients list is parallel to each other.
    #### Fix:
    - Use media query for tablet screen sizes less than 1224px and then set the image width to 70% and moving the ingredients content below it.

30. On hovering over buttons mouse cursor should change to pointer.
    #### Fix:
    - Add cursor: pointer; at buttons.

31. A lot of white space was at the bottom of sign up page on many screen sizes.
    #### Fix: 
    - Use min-height: calc(100vh - 150px); as told by mentor.

32. The sign up label is not giving equal space from left and right on different screen sizes.
    #### Fix 1:
    - Remove absolute positioning from sign up page, move background image in section tag which has id of sign-up-sec and finally use flex. The code is shared by mentor.
    ```css
    background: url("../images/Sign-up-background.webp") center center no-repeat;
    background-size: cover;
    position: relative;
    min-height: calc(100vh - 150px);
    display: flex;
    align-items: center;
    justify-content: center;
    ```
    
    #### Fix 2:   
    - There was another solution which is mentioned below
    ```css
    top: 50%; 
    transform: translate(-50%, -50%); 
    left: 50%;
    ```

    I have tried both solutions but used the first one.

33. Second background image size is too large which is causing performance issue.
    #### Fix: 
    - Use online resize tool to reduce size of image and replace it with the current image also change it to webp format.

34. Move navigation to middle of screen instead keeping it on left side of small screens.
    #### Fix: 
    - Use flex to fix this inside media query of max width of 750px. See the solution below.
        ```css
        display: flex;
        flex-wrap: wrap;
        align-content: center;
        justify-content: center;
        flex-direction: column;
        ```

35. The featuring video on home page width and height might not be good enough for small screen users.
    #### Fix:
    - Change width: 90%; and height: 300px; of the featuring video inside media query of max width of 750px.

## Unfixed bugs
- No unfixed bugs.

Return back to the [README.md](/README.md) file.