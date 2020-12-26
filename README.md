# 42_get_next_line
Calling your function get_next_line in a loop reads the text available on a file descriptor one line at a time until the EOF.
Bonus : succeed get_next_line with a single static variable, and be able to manage multiple file descriptor.

__int get_next_line(int fd, char **line);__

**Parameters**
#1. file descriptor for reading
#2. The value of what has been read

**Return value**
1 : A line has been read
0 : EOF has been reached
-1 : An error happened

-> Compile with gcc -Wall -Wextra -Werror -D BUFFER_SIZE=32 get_next_line*.c (or whatever BUFFER_SIZE you prefer. Go nuts!)

Written in november 2019.

