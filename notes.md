## Python revamping

### Data types:

#### Strings:

| # |Method | Description | Example |
|1 |.capitalize() | Returns a copy of the string with the first character capitalized. | na |
|2 |.casefold() | Stronger version of .lower() method for case-insensitive comparisons. | na |
|3 |.center(width, fillchar) |	Centers the string in a field of a given width, using the specified fill character. |
|4 |.count(substring, start, end) |	Returns the number of non-overlapping occurrences of a substring in the string. |
|5 |.encode(encoding, errors) |	Encodes the string to bytes, using the specified encoding. |
|6 |.endswith(suffix, start, end) |	Checks if the string ends with the specified suffix. |
|7 |.find(substring, start, end) |	Returns the lowest index of the substring if found in the string, otherwise returns -1. |
|8 |.format(*args, kwargs) |	Formats the string by replacing placeholders with specified values. |
index(substring, start, end)	Similar to find(), but raises a ValueError if the substring is not found. |
isalnum()	Returns True if all characters in the string are alphanumeric. |
isalpha()	Returns True if all characters in the string are alphabetic. |
isdecimal()	Returns True if all characters in the string are decimal characters. |
isdigit()	Returns True if all characters in the string are digits. |
isidentifier()	Returns True if the string is a valid identifier. |
islower()	Returns True if all cased characters in the string are lowercase. |
isnumeric()	Returns True if all characters in the string are numeric. |
isspace()	Returns True if there are only whitespace characters in the string. |
istitle()	Returns True if the string is in title case (first letter of each word capitalized). |
isupper()	Returns True if all cased characters in the string are uppercase. |
join(iterable)	Joins elements of an iterable into a single string, using the string as a separator. |
ljust(width, fillchar)	Left-aligns the string in a field of a given width, using the specified fill character.
lower()	Returns a copy of the string with all characters converted to lowercase.
lstrip(chars)	Removes leading whitespace or specified characters from the string.
replace(old, new, count)	Returns a copy of the string with all occurrences of a substring replaced by another substring.
rfind(substring, start, end)	Returns the highest index of the substring if found, otherwise returns -1.
rindex(substring, start, end)	Similar to rfind(), but raises a ValueError if the substring is not found.
rjust(width, fillchar)	Right-aligns the string in a field of a given width, using the specified fill character.
rstrip(chars)	Removes trailing whitespace or specified characters from the string.
split(sep, maxsplit)	Splits the string into a list using the specified separator.
splitlines(keepends)	Splits the string at line breaks and returns a list of lines.
strip(chars)	Removes leading and trailing whitespace or specified characters from the string.
title()	Converts the string to title case.
upper()	Returns a copy of the string with all characters converted to uppercase.
zfill(width)	Pads the string on the left with zeros to fill a specified width.
