# Test Case Samples
This repository contains Test Case samples written by myself for different real webpages, in order to verify their functionalities. These Test Cases aim Positive Flow, Negative Flow and Other Flows of the websites.

------

### :one: Test Cases for Login function on https://login.wordpress.org/ :arrow_down:


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
