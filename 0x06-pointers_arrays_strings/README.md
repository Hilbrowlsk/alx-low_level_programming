0x06. C - More pointers, arrays and strings



Tasks 0. strcat mandatory Write a function that concatenates two strings.



Prototype: char *_strcat(char *dest, char *src); This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte Returns a pointer to the resulting string dest FYI: The standard library provides a similar function: strcat. Run man strcat to learn more.



GitHub repository: alx-low_level_programming Directory: 0x06-pointers_arrays_strings File: 0-strcat.c