JS-Revision-II

Upon cloning this repository, create an index.js file for your solution.

Objective
The objective of this exercise is to revise the topics or concepts which appear in this exercise.

Instructions
Please read and solve the following challenges below:

You have been given an array of objects representing a list of books. Each book object contains the title, author, and number of pages for the book. Your task is to create a function that performs the following tasks:

That takes in the array of book objects as a parameter.

Uses a loop to iterate through each book object in the array.

Checks if the number of pages in the book is greater than or equal to 200 pages. If it is, add the title of the book to a new array called longBooks.

For each book object in the array, add a new property called summary that concatenates the title and author of the book. For example, if the book object has a title of "The Great Gatsby" and an author of "F. Scott Fitzgerald", the summary property should be "The Great Gatsby by F. Scott Fitzgerald".

Returns an object with the following properties:
longBooks: an array of book titles that have more than or equal to 200 pages.
allBooks: an array of all book objects with the summary property added.

const books = [
  { title: 'To Kill a Mockingbird', author: 'Harper Lee', pages: 281 },
  { title: 'The Great Gatsby', author: 'F. Scott Fitzgerald', pages: 180 },
  {
    title: 'One Hundred Years of Solitude',
    author: 'Gabriel Garcia Marquez',
    pages: 417,
  },
  { title: 'The Catcher in the Rye', author: 'J.D. Salinger', pages: 234 },
  { title: 'Pride and Prejudice', author: 'Jane Austen', pages: 432 },
  { title: 'The Hobbit', author: 'J.R.R. Tolkien', pages: 310 },
  { title: '1984', author: 'George Orwell', pages: 328 },
  {
    title: 'The Lord of the Rings',
    author: 'J.R.R. Tolkien',
    pages: 1178,
  },
];
Write a function called filterEvenNumbers that takes an array of numbers as input, and returns a new array that contains only the even numbers from the original array.

Write a function called countChars that takes a string as input, and returns an object containing the count of each character in the string. For example, if the input is "hello", the output should be { h: 1, e: 1, l: 2, o: 1 }.

Write a function called addAndSquare that takes two numbers as input, adds them together, and returns the square of the result. You should use destructuring to extract the two input numbers from an object.

Write a function called getLongestWord that takes an array of words as input, and returns the longest word in the array. If there are multiple words with the same length, return the first one in the array.

Write a function called findMax that takes an array of numbers as input and returns the largest number in the array. You should use a loop to iterate through the array and compare each number to the current maximum.

Write a function called calculate that takes an object as input, with properties for numOne, numTwo, and operation. The numOne and num2 properties should be numbers, and the operation property should be a string representing a math operation ("add","subtract", "multiply", or "divide"). The function should perform the requested operation on the two numbers and return the result. Use the SWITCH statement for this exercise.

Write a function called findNumthat takes an array of numbers and a target number as inputs. The function should return"Found number"if the target number is present in the array, and"Number not found"otherwise. Use anIF...ELSE statement to check if the target number is present in the array.