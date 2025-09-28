# Libft: Your very first own library <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Card%20File%20Box.png" alt="Card File Box" width="40" height="40" />
<img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/c.png" title="C"/><img width="50" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/1012px-Tux.svg.png" title="linux"/>

---
## Overview
**This project** is about coding a C library. It will contain a lot of general purpose functions your programs will rely upon.

| Program name | libft.a |
| :--- | :--- |
| **Turn in files** | `Makefile`, `libft.h`, `ft_*.c` |
| **Makefile** | `NAME`, `all`, `clean`, `fclean`, `re` |
| **External functs** | Detailed below |
| **Libft authorized** | n/a |
| **Description** | Write your own library: a collection of functions<br> that will be a useful tool for your cursus |

---
## Libc functions
<table>
  <tr>
    <td rowspan="7">
      <b>ctype.h</b> :
      <br>ctype.h : <br>
      the C Standard Library<br>
      for <b>testing and mapping characters</b>.
    </td>
    <td>ft_isalpha</td>
    <td>isalpha</td>
    <td>Checks if a character is alphabetic.</td>
  </tr>
  <tr>
    <td>ft_isdigit</td>
    <td>isdigit</td>
    <td>Checks if a character is a digit.</td>
    </tr>
  <tr>
    <td>ft_isalnum</td>
    <td>isalnum</td>
    <td>Checks if a character is alphanumeric.</td>
  </tr>
  <tr>
    <td>ft_isascii</td>
    <td>isascii</td>
    <td>Checks if a character is ASCII.</td>
  </tr>
  <tr>
    <td>ft_isprint</td>
    <td>isprint</td>
    <td>Checks if a character is printable.</td>
  </tr>
  <tr>
    <td>ft_toupper</td>
    <td>toupper</td>
    <td>Converts lowercase to uppercase.</td>
  </tr>
  <tr>
    <td>ft_tolower</td>
    <td>tolower</td>
    <td>Converts uppercase to lowercase.</td>
  </tr>
  <tr>
    <td rowspan="14">
      <b>string.h</b> :
      <br>The header defines various functions <br>for <b>manipulating arrays of characters</b>.
    </td>
    <td>ft_strlen</td>
    <td>strlen</td>
    <td>Computes the length of a string.</td>
  </tr>
  <tr>
    <td>ft_memset</td>
    <td>memset</td>
    <td>Fills memory with a constant byte.</td>
  </tr>
  <tr>
    <td>ft_bzero</td>
    <td>bzero</td>
    <td>Sets memory to zero.</td>
  </tr>
  <tr>
    <td>ft_memcpy</td>
    <td>memcpy</td>
    <td>Copies memory area.</td>
  </tr>
  <tr>
    <td>ft_memmove</td>
    <td>memmove</td>
    <td>Copies memory area (handles overlap).</td>
  </tr>
  <tr>
    <td>ft_strlcpy</td>
    <td>strlcpy</td>
    <td>Copies string with size bound.</td>
  </tr>
  <tr>
    <td>ft_strlcat</td>
    <td>strlcat</td>
    <td>Concatenates string with size bound.</td>
  </tr>
  <tr>
    <td>ft_strchr</td>
    <td>strchr</td>
    <td>Locates character in string.</td>
  </tr>
  <tr>
    <td>ft_strrchr</td>
    <td>strrchr</td>
    <td>Locates last occurrence of character in string.</td>
  </tr>
  <tr>
    <td>ft_strncmp</td>
    <td>strncmp</td>
    <td>Compares two strings up to n characters.</td>
  </tr>
  <tr>
    <td>ft_memchr</td>
    <td>memchr</td>
    <td>Locates byte in memory area.</td>
  </tr>
  <tr>
    <td>ft_memcmp</td>
    <td>memcmp</td>
    <td>Compares memory areas.</td>
  </tr>
  <tr>
    <td>ft_strnstr</td>
    <td>strnstr</td>
    <td>Locates substring in string (with length).</td>
  </tr>
  <tr>
    <td>ft_strdup</td>
    <td>strdup</td>
    <td>Duplicates string (uses malloc).</td>
  </tr>
  <tr>
    <td rowspan="2">
      <b>stdlib.h</b> :
      <br>The header defines various <br><b>general purpose functions</b>,<br> including dynamic memory allocation <br>and integer arithmetics.
    </td>
    <td>ft_atoi</td>
    <td>atoi</td>
    <td>Converts string to integer.</td>
  </tr>
  <tr>
    <td>ft_calloc</td>
    <td>calloc</td>
    <td>Allocates memory and sets to zero (uses malloc).</td>
  </tr>
</table>



---

## Installation and Usage

To compile the library, clone this repository and use the provided `Makefile`.

```bash
# Clone the repository
git clone [your-repository-url] Libft
cd Libft

# To compile the mandatory part:
make

# To compile both mandatory and bonus parts:
make bonus
