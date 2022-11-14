
# BookCave
The Book store app is an Android application. It allows the user to select and buy or rent the book from this book app store. 

# About the project
This whole project has only one concept, which is to provide a wide range of book products to their customers. You can select any type of book you want to buy or borrow. Also, you can schedule your shipping details. You have to provide the proper shipping details.

# Problem Statement - “Create a Book App Platform” with the following specifications -
1. Take a sample JSON for a list of Books
2. The book shall have most basic identifying fields
3. Create a few users who will perform the following activities 
4. Track the readers progress in renting the books
5. Users make a Draft Booking, where the user tries to rent/buy a book but don't complete the process
6. Users rent or buy a book i.e. Create a completed booking
7. Display the activities on the book page (Visits, Draft Bookings, Completed Booking)
8. Display recommendations of other books based on the activities done by the user.
9. Implement a basic UI with minimal functionality required.
 
 # Technology Stack Used : 
Android (AndroidX)
XML and Java
Libraries -> GSON , JackSon Faster XML , Adapters , 
XML Components -> Recycler Views , Card Views , Collapsing Toolbars.

 
# Application Flow
1. User Login (Dummy Users Created)
2. Views a List of Books (Dummy books with basic Information)
3. Can View Detailed Information of each book.
4. Scrol down to view Recommended books.
5. Rent or buy a book.
6. Draft book (Save for later).
7. View a book from the recommendations.

# Recommendations logic
If the user has no bookings then books are recommended on the basis of the **location** of the user is currently viewing.
Or else based on the **similarity of features** of the previously read books.

User and book information stored in assets folder as a Users.json and Book.json files respectively .
Bookings and Draft Booking details are stored in SharedPreferences as a json string.
