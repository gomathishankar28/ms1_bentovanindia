# **Testing**

## Table of Contents
  - [Smoke Testing](#smoke-testing)
  - [Code Testing](#code-testing)
  - [User stories Testing](#user-stories-testing)
  - [Functional Testing](#functional-testing)
  - [Responsiveness Testing](#responsiveness-testing)
  - [Performance Testing](#performance-testing)
  - [Accessibility Testing](#accessibility-testing)
  - [Best Practices and SEO Results](#best-practices-and-seo-results)
  - [Issues found and fixed during Coding](#issues-found-and-fixed-during-coding)
  

## **Smoke Testing**
Following testcases were tested as part of smoke testing for which ***Test results were PASS***
1.	To  Check if the Website launches with a Home page when given the URL of the site. > Tested Pass
2.	To Check for broken links for all the navigation menus. –Tested Pass
3.	To Check if “Order Now” button on the Jumbotron invokes a modal ## Testing for Code. –Tested Pass
4.	To check if the click on “Know More About us” button opens a “About Page”. –Tested Pass
5.	To check if the website launches with a home page on all  different devices as per the wireframe. –Tested Pass

##  **Code Testing**
Html was validated with [W3C Validator](https://validator.w3.org/) by direct input. 
and CSS was validated with [W3C CSS](https://jigsaw.w3.org/css-validator/) by direct input. 
Results came out as follows

### **Results from HTML Validator**
> ![HTML validator Results](https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/HTMLvalidator.jpg?raw=true)

### *Results from  W3C CSS**
> ![CSS validator Results](https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/CSSValidator.jpg?raw=true)

##  **User Stories Testing**

1.  ***As a prospective customer to the website, I want to easily navigate the site, so that I can easily find about the differnt details about the offering.***
    >   As the Website is launched, On the Top left is the Navigation bar which is categorized to show different details about the website that the customer islooking for. 	
2.  ***As a prospective customer to the website, I want to precisely know what they offer so that I have enough infromation about the lunch deivery service.***
    >   In the Home page, "WHY BVI" section show all the features and specialities that gives customer enough information about their lunch delivery service.
3.	***As a new customer to the website, I want to take a look at the menu so that I know the contents of my lunch box.***
    >  "Menu" Page of the website shows in detail the number of items and the type of items based on nutritional composition of the Bento box being delivered.
4.	***As a customer to the website, I want to know the ordering process in detail so that I do not need to call them to know the same.***
    >  In the home page "Our Process" section details the 4 step process in detail in the form of text and images
5.	***As a customer to the website, I would like to know the price of the meal so that I know my lunch budget for the week.***
    > As soon as the customer clicks on the "Order Now button", the modal highlights the price of the meal(60Euros) per week.
6.	***As a prospective customer to the website,, I want an easy way to place my order so that I can place my repeat orders quickly.***
    > This is acheived by placing a "Order Now" button on the Jumbotron text which is the first section of the Home page for ease of access.

##  **Functional Testing**
Functional testing was done by testing induvidual features of the website to see if they meet their intended purpose.
1. **Brand-Title**
    > Checked to see if the Click on the Title takes you to the Home page.
2. **Navigation Bar**
    > Checked to see if the navigation links are highlighted according to the active page.At the launch, Home link of the nav bar has to be higlighted
3. **Home Page**
    > ***WHY BVI? Section***
    > * Checked to see if each feature zooms in with a box shadow on Hover.

    > ***Our Process Section***
    > * Checked to see if the images are displayed in order from step 1 to step 4.
4.  **About PAge**   
    > ***Contact us Section***
    > 1. checked to see if the google map link in contact details is working as expected.
    > 2. Checked to see if the form is verified for valid inputs before the submit button is clicked.
    > 3. Checked for "alert box" on click of the Submit button.
5. **Order Now**
    > ***Order Now Modal***  
        > Checked for "alert box" on click of the Submit button.

## **Responsiveness Testing**
***Devices Testing***

 Website was tested using Chrome Dev tools in the following devices to check if the pages are rendered well.The results are satisfying<br>
    1. Galaxy Fold.<br>
    2. Moto G4<br>
    3. Pixel 2<br>
    4. Pixel 2xl<br>
    5. iphone5<br>
    6. iphone 6/7/8<br>
    7. iphone 6/7/8 plus<br>
    8. iphone x<br>
    9. surface Duo<br>
    10. ipad<br>
    11. ipad pro.<br>

***BrowserTesting***

Website was tested in browsers listed below and results were satisfying.
1. Chrome<br>
2. Edge.<br>
3. Opera<br>
4. Safari<br>
5. Firefox<br>

***Operating System Testing***

Website was tested in different OS listed below and results were satisfying.

1. Windows 10<br>
2. Mac OS.<br>
3. iOS.<br>
4. Android<br>
    
    
## **Performance Testing**

Performance has been tested using the Lighthouse tool of Google Chrome. The results are shown below.

>  ![Perfomance Results](https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/perfomance.jpg?raw=true)

## **Accessibility Testing**

The website's accessibility was also tested using Lighthouse. The result are shown below.

>  ![Accessibility]https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/Accessibility.jpg?raw=true)

## **Best Practices and SEO Results**
>  ![BestPractices](https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/bestPractices.jpg?raw=true)
>  ![SEO](https://github.com/gomathishankar28/ms1_bentovanindia/blob/56afc577fd23264012de0ee9b2b1ce1382d7bf3b/assets/images/testing/SEO.jpg?raw=true)

Spelling was checked thoroughly using [W3C Spell Checker](https://www.w3.org/2002/01/spellchecker). The results are satisfying.

## **Issues found and fixed during Coding**
1. Nav bar was found to be cramped on ipad with all the nav-links expanded.
    > **Solution** - Fixed by replacing navbar-expand-md with navbar-expand-lg.Reference Bootstrap navbar documentation

2. CTA about button had anchor element inside it which was not allowed as per W3C rules.
    > **Solution** - Fixed by adding a onclick property to button.Reference stackoverflow.

3. Footer looked cramped on ipad.
    > **solution** - Fixed by changing the Bootstrap grid allocation from col-md-4 to col-md-12 col-lg-4.

4. Image Slider in "öur process" section were appearing in reverse order.
    >**solution** - Fixed by changing the order of the img:nth-child.

5.  Menu images were hugging in ipad pro.
    > **solution** - Fixed by changing the Bootstrap grid allocation from col-lg-3 to col-lg-6 col-xl-3.

6.  Navbrand shifts down when the toggler menu collapses.
    > **Solution** - Fixed by overiding align-items property to unset. Guidance given by Jo - Tutor support.

7. There were lot of small issues related to margin,padding,width,height of the image,font-size etc
    >**solution** - Fixed by adding media queries accordingly.

## **Enhancements**
Initially the menu page was designed to have only the menu items displayed. An improvement to the page was suggested by my mentor Nishant kumar to display the name of the menu item.

>**solution** - Added styles to display the name of the menu item on hover of the image.



