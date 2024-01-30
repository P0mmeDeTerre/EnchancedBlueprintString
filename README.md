# EnchantedBlueprintString

### **GetstringLength**

**Type de retour :** `Entier`

**Paramètres :**
- `string` (Type : `Chaîne de caractères`): La chaîne dont vous souhaitez obtenir la longueur.

**Description :**
Cette fonction retourne la longueur de la cha



User
NON LAISSE TOUT EN ANGMA
ChatGPT
Certainly, my apologies for the misunderstanding. Here's the documentation in English:

markdown
Copy code
# Unreal Engine 5 Plugin Documentation

## String Utility Functions

### **GetstringLength**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The string for which you want to get the length.

**Description:**
This function returns the length of the specified string.

---

### **IsValidStringIndex**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string for which you want to check the index.
- `index` (Type: `Integer`): The index you want to check.

**Description:**
Checks if the given index is valid for the specified string.

---

### **ContainsSubStringInString**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The main string.
- `subString` (Type: `String`): The substring you are looking for.

**Description:**
Checks if the specified string contains the given substring.

---

### **CountSubStringInString**

**Return Type:** `Integer`

**Parameters:**
- `subString` (Type: `String`): The substring you are counting.
- `string` (Type: `String`): The main string.

**Description:**
Counts the number of occurrences of the given substring in the specified string.

---

### **GenerateRandomString**

**Return Type:** `String`

**Parameters:**
- `minLenth` (Type: `Integer`, default: `1`): The minimum length of the generated string.
- `maxLenth` (Type: `Integer`, default: `1`): The maximum length of the generated string.

**Description:**
Generates a random string of characters with a length between `minLenth` and `maxLenth`.

---

### **GenerateCustomRandomString**

**Return Type:** `String`

**Parameters:**
- `randomCharacters` (Type: `String`): The characters to use for generating the string.
- `minLenth` (Type: `Integer`, default: `1`): The minimum length of the generated string.
- `maxLenth` (Type: `Integer`, default: `1`): The maximum length of the generated string.

**Description:**
Generates a random string using the specified characters, with a length between `minLenth` and `maxLenth`.

...

## String Manipulation Functions

### **RandomizeString**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The string you want to randomize.

**Description:**
Randomly shuffles the characters in the specified string.

---

### **MoveLeft**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The string you want to move.
- `iteration` (Type: `Integer`): The number of iterations to move left.

**Description:**
Moves the characters to the left in the specified string.

---

## String Manipulation Functions (Continued)

### **MoveRight**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The string you want to move.
- `iteration` (Type: `Integer`): The number of iterations to move right.

**Description:**
Moves the characters to the right in the specified string.

---

### **FindLastCharIndex**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The string to search in.
- `character` (Type: `String`): The character to find.

**Description:**
Finds the last index of the specified character in the string.

---

### **FindFirstCharIndex**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The string to search in.
- `character` (Type: `String`): The character to find.

**Description:**
Finds the first index of the specified character in the string.

---

### **InsertStringAt**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `insertString` (Type: `String`): The string to insert.
- `index` (Type: `Integer`): The index at which to insert the string.

**Description:**
Inserts the specified string at the given index in the original string.

---

### **GetStringAfterChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The character after which to extract the substring.
- `count` (Type: `Integer`): The number of occurrences of the character to skip.

**Description:**
Gets the substring in the original string that occurs after the specified character.

---

### **GetStringBeforeChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The character before which to extract the substring.
- `count` (Type: `Integer`): The number of occurrences of the character to consider.

**Description:**
Gets the substring in the original string that occurs before the specified character.

---

### **GetStringAfterFirstChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The first occurrence of the character after which to extract the substring.

**Description:**
Gets the substring in the original string that occurs after the first occurrence of the specified character.

---

### **GetStringBeforeFirstChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The first occurrence of the character before which to extract the substring.

**Description:**
Gets the substring in the original string that occurs before the first occurrence of the specified character.

---

### **GetStringAfterLastChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The last occurrence of the character after which to extract the substring.

**Description:**
Gets the substring in the original string that occurs after the last occurrence of the specified character.

---

### **GetStringBeforeLastChar**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `character` (Type: `String`): The last occurrence of the character before which to extract the substring.

**Description:**
Gets the substring in the original string that occurs before the last occurrence of the specified character.

...

### **GetUrlSubDomain**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The URL string.

**Description:**
Extracts the subdomain from the specified URL string.

---

### **GetUrlTLD**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The URL string.

**Description:**
Extracts the top-level domain (TLD) from the specified URL string.

---

### **GetUrlDomain**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The URL string.

**Description:**
Extracts the domain from the specified URL string.

...

### **GetDateTimeDateAsString**

**Return Type:** `String`

**Parameters:**
- `dateTime` (Type: `DateTime`): The DateTime object.

**Description:**
Converts the date part of the specified DateTime object to a string.

---

### **GetDateTimeTimeAsString**

**Return Type:** `String`

**Parameters:**
- `dateTime` (Type: `DateTime`): The DateTime object.

**Description:**
Converts the time part of the specified DateTime object to a string.

---

### **RemoveAt**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `index` (Type: `Integer`): The index at which to remove a character.

**Description:**
Removes the character at the specified index in the original string.

---

### **RemoveSpaces**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes all spaces from the specified string.

---

### **RemoveNumerics**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes all numeric characters from the specified string.

...

### **RemoveUpper**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes all uppercase characters from the specified string.

---

### **RemoveLower**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes all lowercase characters from the specified string.

...

### **RemoveChars**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `characters` (Type: `String`): The characters to remove from the original string.

**Description:**
Removes the specified characters from the original string.

---

### **TrimStart**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes leading whitespaces from the specified string.

...

### **TrimQuotes**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Removes single and double quotes from both ends of the specified string.

...

### **RemoveString**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.
- `subString` (Type: `String`): The substring to remove.

**Description:**
Removes the specified substring from the original string.

...

### **ToLower**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Converts all characters in the specified string to lowercase.

...

### **ToCamelCase**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The original string.

**Description:**
Converts the specified string to camel case.

...

### **ConvertStringIntoBool**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to convert.

**Description:**
Converts the specified string into a boolean value.

...

### **ConvertStringToColor**

**Return Type:** `Color`

**Parameters:**
- `string` (Type: `String`): The string representation of color.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a color using the provided separator.

---

### **ConvertColorToString**

**Return Type:** `String`

**Parameters:**
- `color` (Type: `Color`): The color to convert.

**Description:**
Converts the specified color into a string representation.

---

### **ConvertStringToLinearColor**

**Return Type:** `LinearColor`

**Parameters:**
- `string` (Type: `String`): The string representation of linear color.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a linear color using the provided separator.

---

### **ConvertStringToDatetime**

**Return Type:** `DateTime`

**Parameters:**
- `string` (Type: `String`): The string representation of datetime.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a datetime object using the provided separator.

...

### **ConvertStringToRotator**

**Return Type:** `Rotator`

**Parameters:**
- `string` (Type: `String`): The string representation of rotator.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a rotator using the provided separator.

---

### **ConvertStringTo3dVector**

**Return Type:** `Vector`

**Parameters:**
- `string` (Type: `String`): The string representation of 3D vector.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a 3D vector using the provided separator.

---

### **ConvertStringTo2dVector**

**Return Type:** `Vector2D`

**Parameters:**
- `string` (Type: `String`): The string representation of 2D vector.
- `separator` (Type: `String`): The separator used in the string.

**Description:**
Converts the specified string into a 2D vector using the provided separator.

...

### **ConvertBinaryStringToInt**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The binary string to convert.

**Description:**
Converts the specified binary string into an integer.

...

### **ConvertIntToBinaryString**

**Return Type:** `String`

**Parameters:**
- `value` (Type: `Integer`): The integer value to convert.

**Description:**
Converts the specified integer into a binary string.

...

### **ConvertCustomBaseStringToInt**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The custom base string to convert.
- `base` (Type: `Integer`): The base of the number system used in the string.

**Description:**
Converts the specified custom base string into an integer.

...

### **ConvertHexadecimalStringToInt**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The hexadecimal string to convert.

**Description:**
Converts the specified hexadecimal string into an integer.

...

### **ConvertOctalStringToInt**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The octal string to convert.

**Description:**
Converts the specified octal string into an integer.

...

### **ConvertIntToHexadecimalString**

**Return Type:** `String`

**Parameters:**
- `value` (Type: `Integer`): The integer value to convert.

**Description:**
Converts the specified integer into a hexadecimal string.

...

### **ConvertIntToOctalString**

**Return Type:** `String`

**Parameters:**
- `value` (Type: `Integer`): The integer value to convert.

**Description:**
Converts the specified integer into an octal string.

...

### **ConvertIntToCustomBaseString**

**Return Type:** `String`

**Parameters:**
- `value` (Type: `Integer`): The integer value to convert.
- `base` (Type: `Integer`): The base of the number system for the resulting string.

**Description:**
Converts the specified integer into a custom base string.

...

### **ConvertDateTimeToString**

**Return Type:** `String`

**Parameters:**
- `datetime` (Type: `DateTime`): The datetime object to convert.

**Description:**
Converts the specified datetime object into a string.

...

### **IsStringInStringArray**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.
- `stringArray` (Type: `Array of Strings`): The array of strings to check against.

**Description:**
Checks if the specified string is present in the given array of strings.

...

### **AreNumerics**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if all characters in the specified string are numeric.

...

### **AreAlphas**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if all characters in the specified string are alphabetic.

...

### **AreSpecials**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains special characters.

...

### **AreUppers**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if all characters in the specified string are uppercase.

...

### **AreLowers**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if all characters in the specified string are lowercase.

...

### **ContainsNumeric**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains numeric characters.

...

### **ContainsAlpha**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains alphabetic characters.

...

### **ContainsSpecial**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains special characters.

...

### **ContainsUpper**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains uppercase characters.

...

### **ContainsLower**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string contains lowercase characters.

---

### **ContainsChars**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.
- `characters` (Type: `String`): The characters to check for in the string.

**Description:**
Checks if the specified string contains any of the characters provided.

---

### **IsEmailFormat**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string is in email format and returns an integer code indicating the result.

---

### **IsEmailDomainFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The email domain to check.
- `domains` (Type: `Array of Strings`): The allowed email domains.

**Description:**
Checks if the specified email domain is in the correct format and is present in the list of allowed domains.

...

### **IsUrlFormat**

**Return Type:** `Integer`

**Parameters:**
- `string` (Type: `String`): The URL to check.

**Description:**
Checks if the specified string is in URL format and returns an integer code indicating the result.

...

### **IsUrlTLDFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The TLD to check.
- `TLD` (Type: `Array of Strings`): The allowed TLDs.

**Description:**
Checks if the specified TLD is in the correct format and is present in the list of allowed TLDs.

...

### **IsUrlDomainFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The domain to check.
- `domains` (Type: `Array of Strings`): The allowed domains.

**Description:**
Checks if the specified domain is in the correct format and is present in the list of allowed domains.

...

### **IsUrlSubdomainFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The subdomain to check.
- `subDomains` (Type: `Array of Strings`): The allowed subdomains.

**Description:**
Checks if the specified subdomain is in the correct format and is present in the list of allowed subdomains.

...

### **IsUrlDomainAndSubdomainFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The full domain with subdomain to check.
- `domains` (Type: `Array of Strings`): The allowed domains.
- `subDomains` (Type: `Array of Strings`): The allowed subdomains.

**Description:**
Checks if the specified full domain with subdomain is in the correct format and both are present in the respective lists of allowed domains and subdomains.

...

### **GetUrlPathAsString**

**Return Type:** `String`

**Parameters:**
- `string` (Type: `String`): The URL to extract the path from.

**Description:**
Extracts the path component from the specified URL.

...

### **IsIPv4Format**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The IPv4 address to check.

**Description:**
Checks if the specified string is in IPv4 format.

...

### **IsIPv6Format**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The IPv6 address to check.

**Description:**
Checks if the specified string is in IPv6 format.

...

### **IsHexadecimalFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string is in hexadecimal format.

...

### **IsBinaryFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string is in binary format.

...

### **IsOctalFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The string to check.

**Description:**
Checks if the specified string is in octal format.

...

### **IsFileFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The file name to check.
- `extensions` (Type: `Array of Strings`): The allowed file extensions.

**Description:**
Checks if the specified file name has a valid format and has an allowed file extension.

...

### **IsImageFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The image file name to check.

**Description:**
Checks if the specified image file name has a valid format.

...

### **IsVideoFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The video file name to check.

**Description:**
Checks if the specified video file name has a valid format.

...

### **IsAudioFormat**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The audio file name to check.

**Description:**
Checks if the specified audio file name has a valid format.

...

### **IsUrlHttp**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The URL to check.

**Description:**
Checks if the specified URL uses the HTTP protocol.

...

### **IsUrlHttps**

**Return Type:** `Boolean`

**Parameters:**
- `string` (Type: `String`): The URL to check.

**Description:**
Checks if the specified URL uses the HTTPS protocol.

...

### **SetDateTimeDay**

**Return Type:** `DateTime`

**Parameters:**
- `dateTime` (Type: `DateTime`): The original DateTime object.
- `day` (Type: `Integer`, default: `1`): The day value to set.

**Description:**
Sets the day component of the specified DateTime object.

...

### **SetDateTimeYear**

**Return Type:** `DateTime`

**Parameters:**
- `dateTime` (Type: `DateTime`): The original DateTime object.
- `year` (Type: `Integer`, default: `1`): The year value to set.

**Description:**
Sets the year component of the specified DateTime object.

...

### **SetDateTimeMonth**

**Return Type:** `DateTime`

**Parameters:**
- `dateTime` (Type: `DateTime`): The original DateTime object.
- `month` (Type: `Integer`, default: `1`): The month value to set.

**Description:**
Sets the month component of the specified DateTime object.

---

