# Software Quality Project - A Library Assistant App
Repo: https://github.com/sqrlmn/LA583
## Team members:
### Nghia Minh Luong nghia.luong@wsu.edu 11693938 (contact person)
### Namgyu Han namgyu.han@wsu.edu 11647029
### Travis Cripe travis.cripe@wsu.edu 11519554
### Chris Minh Nguyen chris.m.nguyen@wsu.edu 11595663
## Download "LibrarianAssistant.zip", then extract it and run "setup.exe" to install and run our software.
This system is a library assistant program that can be used on the online web. Members 
can search the books by title, author, subject, add to cart and check out books, reserve 
books, get book recommendations, and receive notifications to return. Librarians can 
search the book and add, update, and remove the book. This project is written in C# and designed using Winforms. 
The project is structured in 3 layers with the with the class files call BL with the updates that will be made to the database and calls the DAL file being the connection between to the database and with queries to update the values. 

# Roles and Functionality 
 
## User

Registration- A user can register to become a member.

Login-Users can login with their password and username.

## Member

Search book -Search a book based on certain criteria.

Book details- A user can check a book's detail.

Checkout-Check out a book and removes the book from the users cart.

Check book details-Look at book details such as author, genre, decrsiption, amount 
of pages, copies available, title, and the rating.

Get alert-recieves an alert when a book that is the cart is available. 

Edit account information-edit users account. 

Add to cart-add a book to the user's cart.

Rate book-rate the book, giving a book a 1 out of 5 star.

## Librarian 

Search book-Search a book based on certain criteria.

Book details-A librarian can check a book details.

Add/update/remove book- A librarian can add, update or remove a book from the database.

Return book-When a user return a book, the librarian marks the book as avialable so it can be borrowed again.

Edit account-A librarian can edit their account.

