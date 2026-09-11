AI Usage Log
Interaction 1
User

What is a .h file, and what does it do in C?

Assistant Summary

Explained that a .h file is a C header file used to contain declarations such as function prototypes, types, and constants that can be shared between .c files. Explained how #include makes the header's contents available to the source file and distinguished declarations in .h files from implementations in .c files.

Interaction 2
User

What does #ifndef MATH_H and #define MATH_H mean?

Assistant Summary

Explained that these statements form a header guard. #ifndef MATH_H checks whether MATH_H has not already been defined, while #define MATH_H defines it so the header's contents are not processed multiple times. Also explained the role of #endif and why header guards prevent duplicate declarations.