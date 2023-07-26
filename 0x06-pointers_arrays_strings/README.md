# Pointers, arrays and strings (II)
# 0. strcat
A function that concatenates two strings.

Prototype: char *_strcat(char *dest, char *src);
This function appends the src string to the dest string, overwriting the terminating null byte (\0) at the end of dest, and then adds a terminating null byte
Returns a pointer to the resulting string dest
FYI: The standard library provides a similar function: strcat. Run man strcat to learn more.

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 0-strcat.c
  
# 1. strncat
A function that concatenates two strings.

Prototype: char *_strncat(char *dest, char *src, int n);
The _strncat function is similar to the _strcat function, except that
it will use at most n bytes from src; and
src does not need to be null-terminated if it contains n or more bytes
Return a pointer to the resulting string dest
FYI: The standard library provides a similar function: strncat. Run man strncat to learn more.

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 1-strncat.c
  
# 2. strncpy
A function that copies a string.

Prototype: char *_strncpy(char *dest, char *src, int n);
Your function should work exactly like strncpy
FYI: The standard library provides a similar function: strncpy. Run man strncpy to learn more.

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 2-strncpy.c
  
# 3. strcmp
A function that compares two strings.

Prototype: int _strcmp(char *s1, char *s2);
Your function should work exactly like strcmp
FYI: The standard library provides a similar function: strcmp. Run man strcmp to learn more.

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 3-strcmp.c
  
# 4. I am a kind of paranoid in reverse. I suspect people of plotting to make me happy
A function that reverses the content of an array of integers.

Prototype: void reverse_array(int *a, int n);
Where n is the number of elements of the array

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 4-rev_array.c
  
# 5. Always look up
A function that changes all lowercase letters of a string to uppercase.

Prototype: char *string_toupper(char *);

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 5-string_toupper.c
  
# 6. Expect the best. Prepare for the worst. Capitalize on what comes
A function that capitalizes all words of a string.

Prototype: char *cap_string(char *);
Separators of words: space, tabulation, new line, ,, ;, ., !, ?, ", (, ), {, and }

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 6-cap_string.c
  
# 7. Mozart composed his music not for the elite, but for everybody
A function that encodes a string into 1337.

Letters a and A should be replaced by 4
Letters e and E should be replaced by 3
Letters o and O should be replaced by 0
Letters t and T should be replaced by 7
Letters l and L should be replaced by 1
Prototype: char *leet(char *);
You can only use one if in your code
You can only use two loops in your code
You are not allowed to use switch
You are not allowed to use any ternary operation

GitHub repository: alx-low_level_programming
Directory: 0x06-pointers_arrays_strings
File: 7-leet.c

Copyright © 2023 ALX, All rights reserved.