# eightqueensproblem
I created a game application ,using javascript,html and css code.First of all there is a table in my code and it represents a chessboard.
There are eight div objects in my code and they represent eight queens.
Eight queens shapes are circle and coloured yellow.
Chessboard is coloured red and its shape is square.
There are 64 td tags in the table and they have a common class called b and they have id's.
The purpose of this game is eight queens must be inserted in squares but there is a restriction in the game.
Forexample if the first queen places A1 square ,the second queen can not place at the same row or column or diagonal.
If two queens share the same row or column or diagonal you will be alerted.
If you solve the puzzle ,you will get congrutulations message.
Div elements have draggable attributes.
When drag starts application goes to method1(event) javascript method.
The data transfer setData method sets the drag's operation's drag data to the specified data and type.
Event.target.getAttribute('id') calls id attributes value(for div object).
There is a global variable called array.And all its values are assigned to false at the beginning.
Every td has ondrop attribute and this method calls method2() javascript method.
Queens can place in the chessboard by method2.
Convert method returns a boolean value, if the value is false then table appends a div child element.
When a queen is inserted in the table,method3 javascript method reacts so it specifies unavailable squares for next queen object.
