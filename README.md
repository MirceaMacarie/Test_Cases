# Test Case Samples
This repository contains Test Case samples written by myself for different real webpages, in order to verify their functionalities. These Test Cases aim Happy Flow, Negative Flow and Other Flows of the websites.

------

### :one: Test Cases for Login function on https://login.wordpress.org/ :arrow_down:
![login-wp](https://user-images.githubusercontent.com/115346533/205150712-3dd8e65e-d957-4fc5-8e8f-57e4207e12aa.png)



**Test ID:** 1

**Test Title:** Test login with correct credentials

**Description:** Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to site https://login.wordpress.org/ 
2. Add correct username and password
3. Press the login button
4. Observe if user can login

**Expected result:** User should be able to login.

**Test Data:** Username: test & Password: 1234

#


**Test ID:** 2

**Test Title:** Test login with incorrect credentials

**Description:** Test the login by using incorrect credentials.

**Steps to reproduce:** 
1. Go to site https://login.wordpress.org/ 
2. Add incorrect username / password
3. Press the login button
4. Observe if user can't login

**Expected result:** User should not be able to login with incorrect username / password and it gets a window alert with the message "Username/ Password incorrect!".

**Test Data:** Username: test & Password: 1234 

#


**Test ID:** 3

**Test Title:** Test login without credentials

**Description:** Test the login without using any credentials.

**Steps to reproduce:** 
1. Go to site https://login.wordpress.org/ 
2. Click the login button without using any credentials
3. Observe if user can't login

**Expected result:** User should not be able to login without using credentials.

**Test Data:** /

#


**Test ID:** 4

**Test Title:** Test the "Remember Me" checkbox

**Description:** Test the "Remember Me" checkbox by using correct credentials and checking it.

**Steps to reproduce:** 
1. Go to site https://login.wordpress.org/ 
2. Add the correct username / password
3. Click the "Remember Me" checkbox
4. Observe if user remains logged in after closing the webpage

**Expected result:** User should remain logged in after checking "Remember Me" checkbox and closing the webpage.

**Test Data:** Username: test & Password: 1234

#


**Test ID:** 5

**Test Title:** Test "Lost your password?" link

**Description:** Test the functionality to change / recover the password by using "Lost your password?" link.

**Steps to reproduce:**
1. Go to site https://login.wordpress.org/  
2. Add correct username
3. Press "Forgot your passowrd?" link
4. Observe if user receives an email to change the password

**Expected result:** User should receive an email to change / recover the password after pressing the "Forgot your passowrd?" link.

**Test Data:** Username: test & Password: /

------


### :two: Test Cases for search bar function on https://www.emag.ro/ :arrow_down:
![emag-search](https://user-images.githubusercontent.com/115346533/205151237-5cd31123-8e7b-4053-b71a-902af540fde2.png)



**Test ID:** 6

**Test Title:** Test the search bar with a specific item

**Description:** Test the search bar by searching a specific item from the site https://www.emag.ro/.

**Steps to reproduce:** 
1. Go to site https://www.emag.ro/ 
2. Search a specific item in the search bar
3. Press the enter button
4. Observe if user receives the correct results of the searching

**Expected result:** User should receive correct and valid results of searching a specific item by using the search bar.

**Test Data:** "camere"

#


**Test ID:** 7

**Test Title:** Test the autofill functionality of the search bar

**Description:** Test the autofill functionality by searching a specific item.

**Steps to reproduce:**
1. Go to site https://www.emag.ro/ 
2. Type the first 3 letters of a specific item in the search bar
3. Observe if user receives the entire name of the item by autofill functionality

**Expected result:** User should receive the complete name of the searched item by autofill functionality.

**Test Data:** "cam" (from "camere" or other items)

#


**Test ID:** 8

**Test Title:** Test the search bar with a non-existent item

**Description:** Test the search bar by searching an item that does not exist.

**Steps to reproduce:**
1. Go to site https://www.emag.ro/ 
2. Search a non-existent item in the search bar
3. Press the enter button
4. Observe if user receives no valid results and / or suggestions to improve searching

**Expected result:** User should receive no valid results of searching a non-existent item and / or suggestions to improve the searching.

**Test Data:** "dolpetrimente"

#


**Test ID:** 9

**Test Title:** Test the search history of the search bar

**Description:** Test if the search history results are displayed on a new search.

**Steps to reproduce:** 
1. Go to site https://www.emag.ro/ 
2. Type the name of a specific item in the search bar
3. Observe if user receives the results of its search history under the search bar

**Expected result:** User should see its search history results after typing the name of an item.

**Test Data:** "camere"

#


**Test ID:** 10

**Test Title:** Test the cross-site scripting security vulnerability in the search bar

**Description:** Test the security of the search bar by using a cross-site scripting script in the search field.

**Steps to reproduce:** 
1. Go to site https://www.emag.ro/ 
2. Introduce in the search bar the security test.
3. Press the Enter button
4. Observe if it is opening a pop-up / window alert

**Expected result:** It should not open any pop-up / window alert on the webpage unless it is a cross-site scripting security problem.

**Test Data:** Security test: <script>alert(1)</script>

------


### :three: Test Cases for wishlist function on www.udemy.com :arrow_down:
![udemy_wishlist](https://user-images.githubusercontent.com/115346533/205152028-7bbb2b46-799f-4a69-9a28-b4f3d4cbc7b1.jpg)



**Test ID:** 11

**Test Title:** Test the wishlist by adding a new product on www.udemy.com

**Description:** Test the functionality of wishlist from www.udemy.com by adding a new product here from the main page.

**Steps to reproduce:** 
1. Go to site https://www.udemy.com/ and log in
2. Select one product from the main page of the site
3. Click on the heart icon from the product interface
4. Click on the wishlist button near the account name
5. Observe if the selected product was saved in wishlist

**Expected result:** User should see the selected product added in the wishlist of the account. 

**Test Data:** Username: test & Password: 1234

#


**Test ID:** 12

**Test Title:** Test the option of the wishlist to delete a product from it

**Description:** Test the wishlist trying to delete a specific product which was added before here.

**Steps to reproduce:** 
1. Go to site https://www.udemy.com/ and log in
2. Click on the wishlist button near the account name
3. Click on the Heart icon of one product, from its upper-right corner
4. Observe if that product was deleted from the wishlist

**Expected result:** The deleted product should not appear in the user wishlist anymore.

**Test Data:** Username: test & Password: 1234

#


**Test ID:** 13

**Test Title:** Test the wishlist by adding to cart a product from it

**Description:** Test the wishlist trying to add to cart a specific product.

**Steps to reproduce:**
1. Go to site https://www.udemy.com/ and log in
2. Click on the wishlist button near the account name
3. Select one product from wishlist by clicking on it
4. Press "Add to cart" button
5. Observe if it open a notification / window with "Added to cart"

**Expected result:** It should appear a notification / a distinct window which show to user the product which was added to cart, in order to buy it.

**Test Data:** Username: test & Password: 1234

#


**Test ID:** 14

**Test Title:** Test the search bar of the wishlist

**Description:** Test the search bar functionality from wishlist by searching a specific word.

**Steps to reproduce:**
1. Go to site https://www.udemy.com/ and log in
2. Click on the wishlist button near the account name
3. Search a specific word in the search bar of the wishlist
4. Observe if user receives the relevant results of the searching

**Expected result:** User should receive correct and relevant results of searching a specific product by using the search bar in wishlist.

**Test Data:** Username: test & Password: 1234 & "sql" (into search bar)

#


**Test ID:** 15

**Test Title:** Test the purchasing of a specific product from wishlist

**Description:** Test the function of buying a specific product from user wishlist.

**Steps to reproduce:**
1. Go to site https://www.udemy.com/ and log in
2. Click on the wishlist button near the account name
3. Select one product from wishlist by clicking on it
4. Press "Buy now" button
5. Observe if it opens the new page where user can buy the product

**Expected result:** User should see the new page where the selected product can be purchased online.

**Test Data:** Username: test & Password: 1234

------


### :four: Test Cases for website https://eventbook.ro/ :arrow_down:



**Test ID:** 16

**Test Title:** The existence of a custom 404 error page

**Description:** It is verified if this website has a custom 404 error page which help the people to navigate on it.

**Steps to reproduce:**
1. Go on https://eventbook.ro/
2. Write in the URL something that does not exist on the website

**Expected result:** An error page should appear directing the users to what they are looking for.

**Test Data:** "https://eventbook.ro/BlackJack21"

#


**Test ID:** 17

**Test Title:** There are different versions of the website in foreign languges (EN, FR, HU)

**Description:** The website should have proper versions in different foreign languges, in English, French and Hungarian.

**Steps to reproduce:**
1. Go on https://eventbook.ro/
2. Select one at a time different languages of the website from the option at the top right of the page

**Expected result:** The language of the website should change completely to the new language related to our option (Romanian, English, French, Hungarian).

**Test Data:** /

#


**Test ID:** 18

**Test Title:** Search the name of a film or cinema in the search bar

**Description:** The search bar should help the user to find what hei s looking for (a movie title, a cinema, films by actor name etc.).

**Steps to reproduce:**
1. Go on https://eventbook.ro/
2. Write in the search bar the name of a movie/ cinema from Romania

**Expected result:** The user should get a complet list of relevant results of what he is looking for, movies, cinema, events etc.

**Test Data:** Into the search bar: "Florin Piersic"

#


**Test ID:** 19

**Test Title:** The account creation without all required elements

**Description:** The "Create account" form should not let user to create a new account without all mandatory elements. 

**Steps to reproduce:**
1. Go on https://eventbook.ro/
2. Click on Login button
3. Click on Create account button
4. Complete the firstname and secondname in the form, and let the other inputs blank
5. Click on the Create account button, under the form

**Expected result:** The website should show an error message for the user, because he did not complete all mandatory inputs of the form. 

**Test Data:** "Nume" input: "Ionescu" & "Prenume" input: "Mihai"

#


**Test ID:** 20

**Test Title:** The existence of tutorial pages on buying tickets for users

**Description:** The website should have a special section with information about buying tickets operation for users who do not know it.

**Steps to reproduce:**
1. Go on https://eventbook.ro/
2. Scroll down to the footer of the page
3. Click on the button "How to buy tickets" from "Information" section

**Expected result:** The user should be redirected to a separate page with page with information on how to buy movie tickets.

**Test Data:** /


------



