## File 

```cat test.txt``` --> Read content of file on terminal

```touch test.txt``` --> Create a empty txt file

```rm test.txt``` --> Delete/Remove file

```head test.txt``` --> Display first 10 line of file on terminal

```head -5 test.txt``` --> Specifying the number of lines (This will output the first 5 lines.)

```tail test.txt``` --> Display last 10 line of file on terminal

```tail -5 test.txt``` --> Specifying the number of lines (This will output the last 5 lines.)

```tail -f test.txt``` ---> It will keep the file open and display new lines as they are added.


```less test.txt``` --> open the file on terminal & can be read line by line (use arrows to scroll up & down)

```more test.txt``` --> writes the content of file on terminal page by page ( to move to next page need to hit space bar on keyboard )

## Copy and Move

```cp A.txt B.txt``` ---> Makes a copy of A.txt names it to B.txt in current directory

```cp -r testdir/ newdir/``` --> makes a copy of testdir & names it to newdir in current dirctory(for directory only)

```mv A.txt /tmp``` ---> moves to A.txt to /tmp

```mv testdir newdir``` --> renames testdir to newdir in crrent path

