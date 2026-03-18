## Python revamping

### Data types:

#### Strings - Methods:

| # |Method | Description |Important|
|---|-------|-------------|---------|
|1 |.capitalize() | Returns a copy of the string with the first character capitalized. | yes|
|2 |.casefold() | Stronger version of .lower() method for case-insensitive comparisons.| yes|
|3 |.center(width, fillchar) |	Centers the string in a field of a given width, using the specified fill character. |
|4 |.count(substring, start, end) |	Returns the number of non-overlapping occurrences of a substring in the string. |
|5 |.encode(encoding, errors) |	Encodes the string to bytes, using the specified encoding. |
|6 |.endswith(suffix, start, end) |	Checks if the string ends with the specified suffix. |
|7 |.find(substring, start, end) |	Returns the lowest index of the substring if found in the string, otherwise returns -1. |yes|
|8 |.format(*args, kwargs) |	Formats the string by replacing placeholders with specified values. |
|9 |.index(substring, start, end) |	Similar to find(), but raises a ValueError if the substring is not found. | yes|
|10|.isalnum()|	Returns True if all characters in the string are alphanumeric. |
|11|.isalpha()|	Returns True if all characters in the string are alphabetic. |
|12|.isdecimal()|	Returns True if all characters in the string are decimal characters. |
|13|.isdigit()|	Returns True if all characters in the string are digits. |
|14|.isidentifier()|	Returns True if the string is a valid identifier. |
|15|.islower()|	Returns True if all cased characters in the string are lowercase. |
|16|.isnumeric()|	Returns True if all characters in the string are numeric. |
|17|.isspace()|	Returns True if there are only whitespace characters in the string. |
|18|.istitle()|	Returns True if the string is in title case (first letter of each word capitalized). |
|19|.isupper()|	Returns True if all cased characters in the string are uppercase. |
|20|.join(iterable)|	Joins elements of an iterable into a single string, using the string as a separator. | yes |
|21|.ljust(width, fillchar)|	Left-aligns the string in a field of a given width, using the specified fill character.|
|22|.lower()|	Returns a copy of the string with all characters converted to lowercase.|
|23|.lstrip(chars)|	Removes leading whitespace or specified characters from the string.|
|24|.replace(old, new, count)|	Returns a copy of the string with all occurrences of a substring replaced by another substring.| yes |
|25|.rfind(substring, start, end)|	Returns the highest index of the substring if found, otherwise returns -1.|
|26|.rindex(substring, start, end)|	Similar to rfind(), but raises a ValueError if the substring is not found.|
|27|.rjust(width, fillchar)|	Right-aligns the string in a field of a given width, using the specified fill character.|
|28|.rstrip(chars)|	Removes trailing whitespace or specified characters from the string.|
|29|.split(sep, maxsplit)|	Splits the string into a list using the specified separator.| yes |
|30|.splitlines(keepends)|	Splits the string at line breaks and returns a list of lines.|
|31|.strip(chars)|	Removes leading and trailing whitespace or specified characters from the string.| yes |
|32|.title()|	Converts the string to title case.|
|33|.upper()|	Returns a copy of the string with all characters converted to uppercase.|
|34|.zfill(width)|	Pads the string on the left with zeros to fill a specified width.|

#### Strings - Functions:

| # |Function | Description |Important|
|---|-------|-------------|---------|
|1| str() | Converts an object to its string representation. |
|2| len() | Returns the length (number of characters) of the string. |
|3| min/max() | Returns the smallest/largest character in the string based on Unicode code point. |
|4| sorted() | Returns a new sorted (via order or letters in word) list of characters in the string. |

