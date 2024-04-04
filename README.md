# coursera-andrew-milliken-1
Coursera Repo for Johns Hopkins Web Development Cert on Coursera

Assignment #1 Notes: (Link to assignment: https://github.com/jhu-ep-coursera/fullstack-course4/blob/master/assignments/assignment2/Assignment-2.md)

6. You are NOT allowed to use any CSS (or Javascript) framework for this assignment, including Twitter Bootstrap CSS Framework. No framework CSS files should even be referenced in your index.html, even if you are not using them. However, you MAY use the simple responsive framework we developed in Lecture 24 as a starting point for this assignment.
7. You must implement the following breakpoints that will be considered desktop, tablet, and mobile.
   a. display a desktop version of the site when the width of the browser window is 992px and above.
   b. Tablet view should appear only if the width of the browser window is between >=768px and <=991px, inclusively.
   c. Mobile view should appear only if the width of the browser is equal to or less than <=767px.
   
9. Your site is very simple. It consists of
   a. 1 page heading -- 75% larger than dummy lorem ipsum text
   b. 3 sections(cards) (all in one row in the desktop view) -- 25% larger than dummy lorem ipsum text
   c. Each section(card) contains some lorem ipsum text How the sections(cards) are laid out on the screen depends on the width of the browser window. (Hint: use media queries discussed in Lecture 23.)

10. Layout:
    a.Desktop View (992px and above): each of the 3 sections(cards) should take up equal amount of space on the screen. As you make the browser window wider or narrower, each section(card) should become wider or narrower. (Hint: use percentages to define width and use the 'float' property. See Lecture 24).

11. Layout: Tablet View (between 768px and 991px, inclusively): the first 2 sections(cards) should be in the first row and be of equal size. The 3rd section(card) should be in the second row and take up the entire row by itself. 

12. Layout: Mobile View (equal to or less than 767px): each section(card) should take up the entire row(STACKED, width: 100%).

13. Section Title Region: Each section(card) should have a section(card) title region that is always positioned at the top right corner of the section(card) no matter the view (desktop, tablet or mobile). Copy the titles from the mockup illustration (i.e., Chicken, Beef, Sushi) or come up with your own. (Hint: use relative and absolute positioning and offsets as discussed in Lecture 22.)

14. Spacing: Pay attention to the spacing shown in the mockup illustrations. Note the spacing between sections(cards) (both x and y). Note the horizontal spacing between the edges of the section(card) and the edges of the browser window. Also, note the spacing between the dummy text in each section(card) and the edges of the section(card). Lastly, make sure the dummy text is "pushed down" enough so it doesn't overlap the section(card) title region. (Hint: use margins and padding and use border-box as your box-sizing as discussed in Lecture 19.)

15. Borders and Colors:
    a. Each section(card) should have a background color set to some color (of your choosing).
    b. Set the background color of each section title region to some unique color (of your choosing).
    c. Make sure that the background color still allows the user to view the text in the section and section title regions.
    d. Set a black border on both the section(card) and section(card) title region that is 1px thick.
        Warning: While not specifying borders and colors according to the requirements does not hurt your grade so much, not doing so will make it much harder for your classmates to peer grade the rest of your assignment, possibly resulting in a much lower grade.

Set Font-family from Google APIs
(OPTIONAL) You will NOT be graded on this, but you may want to explicitly set a font-family for the text in your page, so you are not stuck with the default browser font-family. 
Also, set the font size of the heading and section title to be 75% larger and 25% larger (respectively) than the font size of the dummy text.
