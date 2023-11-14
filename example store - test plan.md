# Example store - test plan #


## General informations ##

The goal of the test plan is to practice and gain experience in writing test plans, constructing test cases, and reporting bugs. 

## Tested objects ##

The online store (https://mystore-testlab.coderslab.pl/index.php) will be tested. It has features such as user login and an interactive homepage. The objective of this test plan is to verify the display of the homepage, the functioning of placed links, and to test the email and password fields in the login form of the myStore online shop.

## Scope of testing ##

**Homepage**

* loading time of Home Page
* display of following elements 
    * header (“Contact us” tab, “Sign in” tab,  “Clother” tab, “Accesories” tab, “Art” tab)
    * scrollable '’Sample’' section
    * popular products
    * “All products” tab
    * “20% OFF” banner
    
Out of scope: 

* Search field
* Subscribe field
* Footer section 

**Login form**

* Email field
* Password field

Out of scope: 

* Password reminder option
* Link "No account? Create one"

## Tools and technologies #

* MSOffice Excel - creating test cases and defect reports.
* MSOffice Word - creating test plan. 
* DevTools - verification of page loading time and locating elements on the page.
* Git and GitHub 

## Test pass criteria ##

**Home Page**

* Loading time below 3 seconds
* display of elements 
    * the "Contact Us" tab is visible and clickable, and it redirects to a contact form.
    * the "Sign In" tab is visible and clickable, and it redirects to a login form.
    * the "Clothes" tab is visible and clickable, and it redirects to a page with clothes.
    * the "Accessories" tab is visible and clickable, and it redirects to a page with accessories.
    * the “Art” tab tab is visible and clickable, and it redirects to a page with decorative items such as picture frames and wall stickers.
    * the "Sample" section with sliding elements is visible, displayed correctly, and the arrow allowing users to navigate between slides is working. The slides are changing accordingly as the user clicks on the arrow.
    * the products in the "Popular Products" section are displaying correctly.
    * clicking on the "All Products" tab leads to the "Home" page with the available product categories.
    * The "20% Off" banner is displaying correctly, and clicking on it redirects the user to the section with clothes.

**Login form**

* The Email and Password fields are active, allowing users to enter their information.
* Successful user login with correct credentials

## Test fail criteria ##

**Home Page**

* Incorrect or missing display of tested elements
* Slow page loading time
* Inability to access active website elements
* Incorrect redirect of the user after clicking on a clickable element.

**Login form**

* Login failure even after providing the correct login credentials.
* Successful login despite entering incorrect login credentials.
* Successful login after entering incomplete login information.

## Test cases ##

[Home Page](https://docs.google.com/spreadsheets/d/1ZqnrTbNqqxGSWXPh7NN7_nuQITN_Oinh/edit?usp=sharing&ouid=118428523364148890041&rtpof=true&sd=true)

[Login form](https://docs.google.com/spreadsheets/d/12L6hlD95KCWFK0KUjAgAa6BKAtqBeDfc/edit?usp=sharing&ouid=118428523364148890041&rtpof=true&sd=true)

## Bug raports ##

[Home Page](https://docs.google.com/spreadsheets/d/1XtUVMRk_ddhO7VH4sXKbBiX0byrvuER1bG4MPgK6Vjg/edit?usp=sharing)

[Login form](https://docs.google.com/spreadsheets/d/1lNCfs_d7F_T9hSrQqWHIlPIJHSWPVI67ijKBxvJDC70/edit?usp=sharing)

## Entry criteria ##

* Internet access
* A functioning website 
* Working hardware

## Exit criteria ##

* Missing internet access
* Non-functioning hardware
* Inability to access the tested website

## Testing enviroment ##

macOS Ventura 13.0.2 
Browser: Chrome version 110.0.5481.179 (arm64)
Access to the internet 

## Error management ##

Errors will be logged and reported in the Bug Report.

## Roles and Responsibilities ##

Ilona is responsible for planning and conducting the tests.

## Risk management ##

The risks that may occur in the project are:

* Lack or poor internet connection
* Inability to access the online store
* Hardware failures

*Risk management involves minimizing the potential for system failures and lack of internet connectivity by using a stable internet connection and new hardware.*













