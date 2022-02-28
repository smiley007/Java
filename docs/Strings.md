# Strings

## Functions

### Length
String is an object and has a **length()** method to calculate the number of characters in string

------------------------------------------------------------------------------------

### Check if string is empty
Use **isEmpty()** to check if a string object has zero length
```
String str = "";
str.isEmpty();
```
------------------------------------------------------------------------------------

### Remove whitespace characters boundaries of string
Use **trim()** method to trim whitespace characters from start and end of string and returns trimmed string
Trimmed string preserves the middle whitespace characters
```
String str = "        Pravin asdflkj asdfklj      ";
String trimmedContent = str.trim(); // "Pravin asdflkj asdfklj"
```

------------------------------------------------------------------------------------
### Convert String to character array
To convert a string to character array, use *toCharArray()* method
```
String s = "abcd";
char[] c = s.toCharArray();
```
------------------------------------------------------------------------------------

### Convert a string to integer
Use **Integer.parseInt("61453")** method to get integer value in the string
```
int str = "3451"; 
int val = Integer.parseInt(str);
```

------------------------------------------------------------------------------------

### Convert a integer to String
Use **Integer.toString(intValue)** method to convert int to string
```
String str = Integer.toString(12354);
```

------------------------------------------------------------------------------------

### Substring of a string
Use **str.substring(startIndex)** method to get substring from specific start index. The returned string
has characters from start of the string to end of the string
```
String str = "My Name is Pravin";
String subStr = str.substring(3); // "Name is Pravin"
```

Use **str.substring(startIndex, endIndex)** to get substring
from startIndex inclusive upto endIndex exclusive
```
String str = "My Name is Pravin";
String subStr = str.substring(3, 7); // "Name"
```

------------------------------------------------------------------------------------

### String Hash
Use **str.hashCode()** to get the hash value of a string object. This hash can be used to put value in HashTable.
```
String str = "My Name is Pravin";
int hashId = str.hashCode();
```

------------------------------------------------------------------------------------

### Check if a character is a digit
Use **Character.isDigit(charValue)** to check if a character is a digit.
```
String str = "34543";
boolean isDigit = Character.isDigit(str.charAt(0));
```

------------------------------------------------------------------------------------

### Check if a character is a alphabet
Use **Character.isLetter(charValue)** checks whether character belongs to below category
```
boolean check = Character.isLetter('a');
UPPERCASE_LETTER
LOWERCASE_LETTER
TITLECASE_LETTER
MODIFIER_LETTER
OTHER_LETTER
```

------------------------------------------------------------------------------------

### Check if a character is alphabet or digit
Use **Character.isLetterOrDigit(charValue)** checks whether character belongs to letter or digit category
```
boolean check = Character.isLetterOrDigit('9');
```

------------------------------------------------------------------------------------

### Check if a character is lowercase character
Use **Character.isLowerCase(charValue)** to check if a character is a lowercase character
```
boolean check = Character.isLowerCase('a');
```

------------------------------------------------------------------------------------

### Check if a character is uppercase character
Use **Character.isUpperCase(charValue)** to check if a character is a uppercase character.
```
boolean check = Character.isUpperCase('A');
```
------------------------------------------------------------------------------------

### Split a string with a delimiter
Use **split(delimiterValue)** to split the string with the given delimiter.
```
String str = "My name is    pravin";
String[] strWords = str.split(" "); // ["My", "name", "", "", "", "pravin"] 
```
------------------------------------------------------------------------------------

### Delete a character at index of string
Use StringBuilder to make updates to string and make use of **deleteCharAt(Index)** to delete a character in string
```
StringBuilder sb = new StringBuilder("asdlfkj asdflkjadslkj ");
String str = sb.deleteCharAt(sb.length() - 1).toString(); // deleteCharAt() method returns StringBuilder instance
```

------------------------------------------------------------------------------------