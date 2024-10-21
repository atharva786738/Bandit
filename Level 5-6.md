# Level 5->6 

Objective: The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

**human-readable, 1033 bytes in size & not executable**

1. ls -alps  to see  available files.

2. multiple directories pop up from "maybehere00" to "maybehere19"

3. search for the file with 1033 bytes size

4. use find . -type f -readable -size 1033c ! -executable

_find ._----> find for a file in **this** directory

_-type f_----> search for a file type 

_-readable_-----> is a readable file

_-size 1033c_----> is 1033 bytes in size

_! -executable_-----> denotes not executable

5. response given is file location. open this file to get the password.

Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG