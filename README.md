# firstjava
var students;
 while(student < 10){
     console.log("class continues");
     students--;
 }
for(i=0; i<10; i++){
    document.write("add another student");
}
7:34
/*
The Reading List
Keep track of which books you read and which books you want to read!
- Iterate through the array of books. For each book, log the book title
  and book author like so: "The Hobbit by J.R.R. Tolkien".
- If you read it, log a string like
  'You already read "The Hobbit" by J.R.R. Tolkien', 
  else, log a string
  like 'You still need to read "The Lord of the Rings" by J.R.R. Tolkien.'
*/
// write your solution here...
var books = [
    {title: "Think and Grow Rich", author: "Napoleon Hill", alreadyRead: true },
    {title: "The Personal MBA", author: "Josh Kaufman", alreadyRead: false},
    {title: "The Peter Plan", author: "Dr. Laurence J. Peter", alreadyRead: false}
  ];
  for (var i = 0; i < books.length; i++ ) {
      if(books[i].alreadyRead == true){
          console.log("You already read "+books[i].title+" by "+books[i].author);
      }
      else {
          console.log("You still need to read "+books[i].title+" by "+books[i].author)
      }
  }
