# **LibrarySystem**
## **21st MAR'23**
## **Overview**
Library class which has attributes book_list(Available books for lending) and library name. Library class has methods of available_books to display available books for 
lending , adding_books to add books to out booklist, lending_book to have the names of the lended books and the name of one who borrowed the books (in dictionary)and remove this books from booklist and returning_book 
to add returned books to available booklist once again and remove it from book : user dictionary.
## **File used**
Banksystem.ipynb
# **How the program works:**
* Creation Library class which has attributes book_list(Available books for lending) and library name.
* Library class has 4 methods
  * available_books : Display available books for lending.
  * adding_books : Adding books to out booklist.
  * lending_book : have the names of the lended books and the name of one who borrowed the books (in dictionary) and remove this books from booklist
  * returning_book to add returned books to available booklist once again and remove it from book : user dictionary.
* Ask user to enter names of the books that are in the libray and the name of the library
* Ask user to choose between 1, 2, 3, 4
  * 1.Display available books.
  * 2.lending books. 
  * 3.Add book to library.
  * 4.Return book.
 * if the user chooses 1 that means he wants to display available books.
 * if the user chooses 2 that means he wants to add new books to library.
 * if user chooses 3 that means he wans to lend a books to someone the program will ask him to enter the name of the user and the name of the book(check if this book exists in the available bboklist). the program will 
 have a dictionary that have the name of the book as a key and name of the one who borrowed the book as a value.
 * if the user chooses 4 that means he wants to return a book from lending the program will ask the user about the name book (check if this book in bbok:user dictionary keys) 
 and the program will add this book once again to the available boooklist and remove it from book:user dictionary.
