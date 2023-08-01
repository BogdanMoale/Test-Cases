# Test-Cases
Test Case samples

# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects.

----------------

**Description:** 
Check if the login works when a person uses a correct user/pass.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Add a correct user / pass
3. Press Login button

**Expected result:**
User should be able to login and is taken to his profile page.

**Test Data:**
User: bogdan  &  Pass: 147741


------------------------

**Description:**
Check if the login works when a person uses an incorrect user/pass.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Add an incorrect user/pass
3. Press Login button

**Expected result:**
User should not be able to login and be taken to his profile page.

**Test data:**
* User: Bogdan & Pass:123455 - With wrong user and correct password

------------------------

**Description:** 
Check if forgot password functionality works as expedted and an email with reset password link is sent.

**Steps to Reproduce:**
1. Go to www.website.com/login
2. Press "Forgot Password" button
3. Add an email address
4. Press "Recover" button

**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.

**Test Data:**
User: bogdan@email.com

**Note**
Please check the login again after running this test case.

------------------------

**Description:**
Use the search bar from the www.emag.ro website to search for random products.

**Steps to reproduce:**
1. Go to https://www.emag.ro/#opensearch
2. Write the product name
3. Press Search button

**Expected result:**
User should be able to find the product searched on the site.

**Test data:**
For searches: Lapotp, Smartphone, placa video, sursa calculator, mouse, tastatura, huse telfoane,samsung z fold

------------------------

As a user I want to delete a picture from my Facebook profile

**Preconditions:**

* The user must have an account
* The user must be logged in
* The user must have a picture on his account

**Given** the user is in Pictures section/My Pictures on his profile

**When** the user accesses a picture and click on 3 points and the Delete button

**Then** he will be able to confirm and delete the picture

**Expected results:**

**G:** The user successfully sees his picture

**w:** The user successfully accesses the picture, 3 points section and presses the Delete button

**T:** The user successfully confirms and delete the picture 

* The picture will disappear 


----------------

**Description:**
Check if a user profile appear when a person uses a different URL without being connected to the site.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Change the URL address from www.website.com/login to www.website.com/Myaccount
3. Press Enter

**Expected result:**
Person should not be able to see a user profile.


-----------------
**Description:**
As a user I want to access a News on the home page

**Preconditions:**

- The user must be on https://ziare.com/

**Given** the user accesses the website and he is on the home page

**When** the user clicks on a news 

**Then** the user will be able to read the news

**Expected results:**

**G:** The user successfully acces the website and he is on the homepage

**W:** The user successfully click on a news

**T:** The user is successfully able to read the news



-----------------

**Description:**
Search for a product and after that use the x function in the search bar to delete the produc from the bar.

**Steps to reproduce:**
1. Go to https://www.emag.ro/#opensearch
2. Write the product name
3. Press the Search button
4. Click on the search bar
5. Use the x button to delete the product name

**Expected result:**
User should be able to find the product searched on the site and the x function will delete the product name from the bar for him.

**Test data:**
For search: Unt President


**Description:**
Verify if the user can successfully pay the products using a valid credit card.

**Steps to reproduce:**
1. Go to https://www.emag.ro
2. Log in to the site
3. Add the products to the cart
4. Press the Cart button
5. Select credit card option for payment
6. Provide the valid credit card details
7. Pay for products

**Expected result:**
User should be able to purchase successfully the products using the credit card without any error.

**Test data:**
* User: bogdan & Pass:147741
* Cart products: Husa pentru OnePlus 7T, Ultra subtire, Rezistenta la socuri, Rosu
* Payment Type: Visa



