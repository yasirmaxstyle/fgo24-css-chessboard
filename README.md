# MAKE CHESSBOARD USING HTML TABLE

This demonstrate the implementation of html table to make chessboard. Here you can make it as well
***First***, wrap your table inside \<table> tag and you can add the rest using emmet shortcut

```c
table>tbody>(tr>(td*8)*8)
// it means you make 8 rows table and 8 columns table respectively

//now give the <table> tag attributes
<table border="1" width="500px" height="500px">

//now give the children attribute bgcolor black and white
<td bgcolor="white"></td>
<td bgcolor="black"></td>

// do it until the end respectively

```

Now, run it using **live-server** package by npm