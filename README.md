# Print F

<img alt="coding" width="784" height="350" src="https://github.com/Karlie-crypto/alx-system_engineering-devops/blob/master/new.png" />

| PR.NO | PROJECT                                                                           | DESCRIPTION |
| ----- | --------------------------------------------------------------------------------- | ----------- |
|  1  | [Printf ](./1-printf.c/)                                            | The code implements a custom `_printf` function that mimics the standard `printf`. It processes format specifiers, accumulates characters in a buffer, and prints them when necessary. The `print_buffer` function outputs the buffer contents to the standard output. It also handles flags, width, precision, and size using helper functions. |
| 10 | [Utils](./10-utils.c/)                                         | The code includes functions to check if a character is printable (is_printable), convert ASCII to hexadecimal (append_hexa_code), verify if a character is a digit (is_digit), and cast numbers to specified sizes (convert_size_number and convert_size_unsgnd).           |
| 11  | [Write Hand](./11-write_hand.c/)                                         | The code contains functions to handle printing various types of data in a custom `_printf` implementation, including characters, numbers, unsigned numbers, and memory addresses. It manages padding, width, flags, and precision for each type, ensuring correct formatting. Functions like `handle_write_char`, `write_number`, `write_unsgnd`, and `write_pointer` handle specific data types and apply the necessary formatting before printing to the output.           |
| 2  | [PrintF](./2-printf.c/)                                                 | The code defines functions to print characters, strings, percent signs, integers, and binary numbers, handling formatting options like width, precision, and sign.  |
| 3  | [Specif](./3-specif.c/)                                             | The code defines functions to print unsigned numbers in decimal, octal, and hexadecimal (both lowercase and uppercase) formats, with support for flags like hash and width/precision adjustments.           |
| 4  | [Printf](./4-printf.c/)                                              | The code defines functions to print pointer values, non-printable characters as hex codes, reverse strings, and strings encoded in ROT13 format.            |
| 5  | [Flag](./5-flag.c/)                                    |  The function get_flags calculates and returns the active flags based on a formatted string, updating the index i accordingly.           |
| 6 | [Precision](./6-precision.c/)                                         | The get_precision function calculates the precision for printing based on a formatted string and a list of arguments, updating the index i accordingly.             |
| 7 | [Size](7-size.c)                                                      | The get_size function calculates the size to cast the argument based on the formatted string, updating the index i accordingly.                         |
| 8 |  [Width](./8-width.c/)                                                                             | The get_width function calculates the width for printing based on the formatted string and the list of arguments, updating the index i accordingly.  |

The files collectively define functions for handling various types of formatted output in a custom printf-like implementation. They include functions to print different data types (e.g., characters, strings, integers, unsigned numbers, binary, hexadecimal), handle flags, precision, width, and size formatting, and perform special formatting operations like printing pointers, non-printable characters, and strings in reverse or ROT13. The utility functions like get_flags, get_precision, get_size, and get_width process the format string and arguments to determine the appropriate formatting options for each print operation. These functions utilize buffers and flags to format and print the results accordingly.
# Write your own printf function.

### Authorized functions and macros
- write (man 2 write)
- malloc (man 3 malloc)
- free (man 3 free)
- va_start (man 3 va_start)
- va_end (man 3 va_end)
- va_copy (man 3 va_copy)
- va_arg (man 3 va_argv)

### AUTHOR:
<details>
    <summary>KARLIE MOYO</summary>
    <ul>
        <li>
            <a href="https://github.com/karlie-moyo">Github</a>
        </li>
        <li>
            <a href="https://twitter.com/karlieemoyo">Twitter</a>
        </li>
        <li>
            <a href="https://karlieemoyo@gmail.com">e-mail</a>
        </li>
    </ul>
</details>

---

### Acknowledgements  :pray:
___
All of the work in this project was conducted as part of the UoS-SE program's curriculum.
