# Bugs samples
----------------------------------------------------------------
Below are some Bug samples that I wrote from my experience.
--------------------------------------------------------------
## The translation of the text is not completed
------------------------------------------------------------
*Priority & Severity*

P2 Medium

*Description* 

When changing the language of the website, It will be noticed that not all text fields are translated.

*Steps to reproduce*

1. Go to “https://juice-shop.herokuapp.com/#/ ”.
2. Press “Choose language”
3. Press “Bahasa Indonesia”

*Expected results*

The webpage should translate all text
 
*Actual results*

The translation of the text is not completed.

![change ](https://user-images.githubusercontent.com/120104620/218248906-a47f9326-701f-48bd-b385-5512ad6e32c8.png)

--------------------------------------------------------------
**The text in the “About us” section, is not customized**
------------------------------------------------------------
*Priority & Severity*

P2 Medium

*Description*

The text in the “About us” section, is not customized.

*Steps to reproduce*

1. Go to “https://juice-shop.herokuapp.com/#/  ”.
2. Press the “Open side menu” button.
3. Press the “About us” button.
 
*Expected results*

The page should display information regarding the site (history, scop, team, etc.).

*Actual results*

There is a standard text area created “Lorem ipsum”, but the text is not customized.

![text](https://user-images.githubusercontent.com/120104620/218249070-536e97b0-001c-4e0b-80e9-eb439672f019.png)

--------------------------------------------------------------
**The account user email is not displayed after a long period of time**
------------------------------------------------------------
*Priority & Severity*

P2 Medium

*Description*

When the user reenters the webpage, after a long period of time, it will be noticed that the email with not be displayed in the “Account” section.

*Steps to reproduce*

1. Go to https://juice-shop.herokuapp.com/#/ . 
2. Press the “Account” button.
3. Press the “Login” button.
4. Login with a Gmail account.
5. Press the “Account” button.
6. Close the webpage and wait 1 day. 
7. Go to https://juice-shop.herokuapp.com/#/  . 
8. Press the “Account” button.

*Expected results*

The account email address is displayed in the “Account” button.

*Actual results*

The account user email is not displayed.

![account](https://user-images.githubusercontent.com/120104620/218249272-c0c16fe6-e1eb-427a-a766-d5d3173f4a5d.png)

![account missing](https://user-images.githubusercontent.com/120104620/218249275-627e247a-537d-4c0f-9cb3-40dbfa7705ad.png)

--------------------------------------------------------------
**Customer login page not displayed**
------------------------------------------------------------
*Priority & Severity*

P1 High

*Description*

When pressing the “Customer login” button, it will be noticed that the login page in not displayed.

*Steps to reproduce*

1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login.
2. Enter “Customer Login”

*Expected results*

The user should login and have access to his account.

https://user-images.githubusercontent.com/120104620/218248685-95bf4e68-43cd-4379-ade6-584c636d4dfa.mp4

--------------------------------------------------------------
**A customer can access information of other customers**
------------------------------------------------------------
*Priority & Severity*

P1 High

*Description*

When pressing the “Customer login” button, it will be noticed that the list of all clients is displayed and selecting any customer will allow the user to log in.
 
*Steps to reproduce*

1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login .
2. Enter “Customer Login”.
3. Press the “Your Name” field.
4. Scroll down to see the list of clients.
5. Press on one of the customer’s names listed.

*Expected results*

The user should have access to view his personal accounts only.
 
*Actual results*

The user can view several customer name lists and access them.

https://user-images.githubusercontent.com/120104620/218248791-98b4b532-3dbb-4c60-b6dc-c308771ca650.mp4

--------------------------------------------------------------
**The PDF for ”petitie_persoana_fizica.php” is missing**
------------------------------------------------------------
*Priority & Severity*

P1 Medium

*Description*

When verifying if there are console errors on the page, it will be noticed that one document link is missing.

*Steps to reproduce*

1. Go to the web page https://www.primariatechirghiol.ro/ 
2. Press F12.
3. Press “Console”.
4. Select the page mentioned in the error list.

*Expected results*

All site links and pdf should be accessible to the public.

*Actual results*

The PDF for ”petitie_persoana_fizica.php” is missing.

https://www.primariatechirghiol.ro/wp-content/themes/portal/petitie_persoana_fizica.php

![404](https://user-images.githubusercontent.com/120104620/218250261-1f112fe6-f9e3-4bab-9387-3680879dd222.png)

--------------------------------------------------------------
**The content is not displayed when opening pages from the "Hotararea" section on mobile devices**
------------------------------------------------------------
*Priority & Severity*

P3 High

*Description*

When trying to see if the site is responsive to devices, it will be noticed that the pages are blank.

*Steps to reproduce*

1. Go to https://www.primariatechirghiol.ro/ 
2. Press F12.
3. Press “Toggle device toolbar”.
4. Press any devices in the device list.
5. Press the ”Hotarari ale Comitetului local pentru Situatii de urgenta” button.
6.Select a document from the list.

*Expected results*

The content is displayed.  

*Actual results*

The content is not displayed.

https://user-images.githubusercontent.com/120104620/218250396-7c7744c6-5fb4-4ff5-b404-b5ae2def05ca.mp4

--------------------------------------------------------------
**There are incorrectly framed text while using devices**
------------------------------------------------------------
*Priority & Severity*

P1 High 

*Description*

When trying to enter the website, on different devices, it will be noticed that the padding is not adjusted properly for all the text.

*Steps to reproduce*

1. Go to https://fieni.ro/ .
2. Press F12.
3. Press the “Toggle device toolbar” button.
4. Press from the drop-down list “Galaxy Ford”.
5. Scroll down, the webpage.

*Expected results*

The text is framed correctly, and readable.

*Actual results*

There are some articles, with text that is incorrectly framed.

![text (1)](https://user-images.githubusercontent.com/120104620/218250616-b0def9d4-c7ff-445b-972e-974a58014a2b.png)

--------------------------------------------------------------
**The loading time of the web page is too long due to loading files multiple times**
------------------------------------------------------------
*Priority & Severity*
P3 Low

*Description*

When trying to enter the web application, it will be noticed that it take a long time for the page to load 

*Steps to reproduce*

1. Go to https://fieni.ro/.
2. Press F12.
3. Select Network.
4. Make sure that the ticks on the “Preserved log”, “Disable cache” and “All” are selected.
5. Press F5.
6. Filter by size.

 *Expected results*

The recommended loading time for web pages is ~3 seconds.

*Actual result*

The loading time of the web page is too long due to loading files multiple times.

![time](https://user-images.githubusercontent.com/120104620/218250719-54b5a274-68ad-459a-99aa-73ee6f103aa0.png)











