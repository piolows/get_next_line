# get_next_line - 42
Get_next_line project from the 42 cursus.

This project involves creating a function which reads a line from a specified file descriptor and returns the line. This project introduces new concepts such as the read() function and static variables. Using a static variable with a specified buffer size, we're able to read from a file and return a line (up to a "\n" character or the end of the file) no matter what the buffer size is. Every subsequent call of the function will return the next line, as the read() function retains its place in the file being read. By using a static array of strings, we are able to read from multiple FDs at the same time while retaining our place in all of them.

Project completed on November 28 2023 with bonus (125/100).
