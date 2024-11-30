## Assignment

### Brief

Write your answers for each question:

Question 1:
Imagine you are hired by a startup company for a school to implement their IT infrastructure as their IT consultant. n your own words (300 words or less), describe how could implementing Scrum help their IT team improve their productivity.

```
Implementing scrum can help team working on setting up the IT infrastructure develop in smaller chunks of work. This helps with on time delivery as there are clear deliverables for the end of each sprint, set at the beginning of the sprint. As scrum is an agile methodolgy, it also allows and welcome changes to be introduced while development is ongoing. This results in a product that the customer is satisfied with and is also delivered on time. 

```

Question 2:
Write ten (10) user stories for a book-borrowing website for a library. Write it in the format: `As a ____, I want to ____, so that _____`.

```
1) As an exisiting user, I want to be able to login to the library website, so that I can borrow books.
2) As an exisiting user, I want to be able to have an overview of the books that I currently have on loan with due dates, so that I know when to return the books.
3) As an exisiting user, I want to have a payment page, so that I can pay for any outstanding fees without having to physically make payment at the library.
4) As an exisiting user, I want to be able to catalog of all the books the library has, so that I can browse the list of all the books even if the book is already on loan.
5) As a user, I want to have the physical location of the books in the library listed/tagged in the book catalog, so that I can physically locate a book in the library.
6) As a system administrator, I want to have an administrative view, so that I can easily search for all the books that are currently on loan.
7) As a user, I want to have catagories, so that I can search for books according to topics.
8) As a new user, I want to be able to sign up on the library website, so that I can create an account with the library.
9) as an exisiting user, I want to be able to have a history page, so that I can look through a list of books I have previously borrowed.
10) As a system administrator, I want to be able to have an administrative view, so that I have rights to grant/prevent certain users from borrowing books.
11) As a user, I want to have a Scan function, so that I can perform a self-checkout of the books that I want to borrow.

```

Question 3: 
Define [Acceptance Criteria](https://resources.scrumalliance.org/Article/need-know-acceptance-criteria) for 3 to 5 user stories out of the 10 user stories you have defined.

```
As an exisiting user, I want to be able to login to the library website, so that I can borrow books.

 -Given user enters the login page 
  When they enter a valid email username and password
  Then the user is successfully logged in and redirected to the Home Page.

 -Given user enters the login page
  When they enter an invalid email username
  And/Or
  When they enter an invalid password  
  Then an error message "Wrong username or password" is presented to the user

 -Given user enters the login page
  When they click on Google SSO
  Or 
  When they click on Microsoft SSO
  Or
  When they click on AppleID SSO 
  Then user is redirected to the respective SSO login page to perform SSO login
 
 -Given user has the respective SSO already signed in
  When the respective SSO login is clicked
  Then login is performed automatically using the SSO credentials

 -Given user enters the login page and forgets their password
  When they click on the "Forget password" button hyperlink text
  Then user is redirected to the password recovery page
  And
  Then uses their account's registered email to perform the password recovery
 
  
As a system administrator, I want to be able to have an administrative view, so that I have rights to grant/prevent certain users from borrowing books.

 -Given system administrator enters the administrative page 
  When they search for a user by username or email address
  Then the user's email address
  And 
  Then the user's First and Last Name
  And 
  Then the user's Borrwing Status 
  And 
  Then the list of books currently on loan by the user
  And
  Then the list of books previously borrowed by the user is presented to the systme administrator

 -Given User A's details returned to the system administrator after searching
  When they click on the "Ban" button at the end of the row of the user's details
  Then User A's Borrowing Status changes from "Allowed" to "Banned"
  And
  Then the text of the "Ban" button changes to "Unban"

 -Given User B's details returned to the system administrator after searching
  When they click on the "Unban" button at the end of the row of the user's details
  Then User B's Borrowing Status changes from "Banned" to "Allowed"
  And
  Then the text of the "Unban" button changes to "Ban" 
  
As a user, I want to have a Scan function, so that I can perform a self-checkout of the books that I want to borrow.
 
 -Given Scan function 
  When scanning barcodes 
  Or
  When scanning QR codes
  Then the barcode or QR code can be read correctly
 
 -Given user is logging in from a local computer within the library
  When user uses the Scan function
  Then the system's connected camera/scanner is initialied and ready to scan 
  
 -Given user is logging in from their mobile device
  When the user uses the Scan function
  Then Camera permissions are checked and requested if not present




```


### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 


### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.
```js
    function printMe(){
        console.log("I am a reference example");
    }
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github

