# EnchantedBlueprintString

---

### **GetstringLength**

**Return Type:** `int`

**Parameters:**
- `FString string`

**Description:**


---

---

### **IsValidStringIndex**

**Return Type:** `bool`

**Parameters:**
- `FString string, int index`

**Description:**
Check if the index of the string is valid

---

---

### **ContainsSubStringInString**

**Return Type:** `bool`

**Parameters:**
- `FString string, FString subString`

**Description:**


---

---

### **CountSubStringInString**

**Return Type:** `int`

**Parameters:**
- `FString subString, FString string`

**Description:**


---

---

### **GenerateRandomString**

**Return Type:** `FString`

**Parameters:**
- `int minLenth = 1, int maxLenth = 1`

**Description:**
generate a string that contains a-z, A-Z, 0-1, and all specific characters

---

---

### **GenerateCustomRandomString**

**Return Type:** `FString`

**Parameters:**
- `FString randomCharacters, int minLenth = 1, int maxLenth = 1`

**Description:**
generate a random string with your custom characters in it

---

---

### **GenerateIPv4**

**Return Type:** `FString`

**Parameters:**
- `EIPv4Classes ipClass`

**Description:**
Generate an IPv4 (does not include 0.0.0.0 and 127.0.0.1)

---

---

### **GenerateIPv6**

**Return Type:** `FString`

**Parameters:**
- ``

**Description:**
Generate an IPv6  (does not include ::0 and ::1)

---

---

### **RandomizeString**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
generate a string that contains a-z, A-Z, 0-1, and all specials characters

---

---

### **MoveLeft**

**Return Type:** `FString`

**Parameters:**
- `FString string, int iteration`

**Description:**
Move all characters to the left starting at index with number of iteration

---

---

### **MoveRight**

**Return Type:** `FString`

**Parameters:**
- `FString string, int iteration`

**Description:**
Move all characters to the right starting at index with number of iteration

---

---

### **FindLastCharIndex**

**Return Type:** `int32`

**Parameters:**
- `FString string, FString character`

**Description:**
find the last index of a char in a string. function will always use the first character of the 'character' variable

---

---

### **FindFirstCharIndex**

**Return Type:** `int32`

**Parameters:**
- `FString string, FString character`

**Description:**
find the first index of a char in a string. function will always use the first character of the 'character' variable

---

---

### **InsertStringAt**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString insertString, int index`

**Description:**
insert a string in a string at index

---

---

### **GetStringAfterChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character, int count`

**Description:**
return a string part after the n (count) given char. If count is bigger than char number, it will use the last found char of the string

---

---

### **GetStringBeforeChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character, int count`

**Description:**
return a string part before the n (count) given char. If count is bigger than char number, it will use the last found char of the string

---

---

### **GetStringAfterFirstChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character`

**Description:**
return a string part after the first given char

---

---

### **GetStringBeforeFirstChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character`

**Description:**
return a string part before the first given char

---

---

### **GetStringAfterLastChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character`

**Description:**
return a string part after the last given char

---

---

### **GetStringBeforeLastChar**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString character`

**Description:**
return a string part before the last given char

---

---

### **GetUrlSubDomain**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Return the subdomain part of a URL

---

---

### **GetUrlTLD**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Return the top-level domain (TLD) of a URL

---

---

### **GetUrlDomain**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Return the domain part of a URL

---

---

### **GetDateTimeDateAsString**

**Return Type:** `FString`

**Parameters:**
- `FDateTime dateTime`

**Description:**
Return the date portion of a dateTime as a string

---

---

### **GetDateTimeTimeAsString**

**Return Type:** `FString`

**Parameters:**
- `FDateTime dateTime`

**Description:**
Return the time portion of a dateTime as a string

---

---

### **RemoveAt**

**Return Type:** `FString`

**Parameters:**
- `FString string, int index`

**Description:**
remove character in a string at index

---

---

### **RemoveSpaces**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all spaces in a string

---

---

### **RemoveNumerics**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all numerics in a string

---

---

### **RemoveAlphas**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all Alphas in a string

---

---

### **RemoveSpecials**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all specials characters in a string

---

---

### **RemoveUpper**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all upper characters in a string

---

---

### **RemoveLower**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all lower characters in a string

---

---

### **RemoveMultipleSpaces**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove multiple spaces in a string. ('this    is a   string' --> 'this is a string')

---

---

### **RemoveChars**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString characters`

**Description:**
remove any given characters in a string. Each char of the given characters will be removed from the given string

---

---

### **TrimStart**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all spaces at the start of the string

---

---

### **TrimEnd**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all spaces at the end of the string

---

---

### **TrimStartEnd**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
remove all spaces at the start and at the end of the string

---

---

### **TrimQuotes**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Remove first and last characters if they are quotes

---

---

### **RemoveFromStart**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString inPrefix`

**Description:**
Removes the text from the start of the string if it exists.

---

---

### **RemoveFromEnd**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString inPrefix`

**Description:**
Removes the text from the end of the string if it exists.

---

---

### **RemoveFromStartAndEnd**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString inPrefix`

**Description:**
Removes the text from the start end the end of the string if it exists.

---

---

### **RemoveString**

**Return Type:** `FString`

**Parameters:**
- `FString string, FString subString`

**Description:**
Return a string with the specified substring removed

---

---

### **RemoveStrings**

**Return Type:** `FString`

**Parameters:**
- `FString string, TArray<FString> subStrings`

**Description:**
Return a string with the specified substrings removed

---

---

### **ToLower**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
return a string with only lowercase characters

---

---

### **ToUpper**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
return a string with only uppercase characters

---

---

### **InvertString**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
return a string with invert characters order

---

---

### **ToCamelCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Came Case string format \n First character of each words are in lower case exept the first one, spaces are deleted

---

---

### **ToPascalCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Pascal Case string format \n First character of each words are in lower case, spaces are deleted

---

---

### **ToSnakeCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Snake Case string format \n spaces between words are replaced with underscores ( _ ). All characters are in lower case

---

---

### **ToKebabCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Kebab Case string format \n spaces between words are replaced with dashes ( - ). All characters are in lower case

---

---

### **ToTitleCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Title Case string format \n First character is in lower case and other ones are in lower case

---

---

### **InvertCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Invert Case string format \n Upper characters will become lower characters and low characters will become upper characters

---

---

### **AlternateCase**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Convert string into a Alternate Case string format \n Characters will be alterned between upper and lower ( depending on the first character cases )

---

---

### **ConvertStringIntoBool**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
if the string does not contains a value that can be convert into a boolean value the fonction will be return false. \n acceptable value ({1 | 0}, {true | false}) 

---

---

### **ConvertStringToColor**

**Return Type:** `FColor`

**Parameters:**
- `FString string, FString separator`

**Description:**
Convert string to string

---

---

### **ConvertColorToString**

**Return Type:** `FString`

**Parameters:**
- `FColor color`

**Description:**
Convert color to string

---

---

### **ConvertStringToLinearColor**

**Return Type:** `FLinearColor`

**Parameters:**
- `FString string, FString separator`

**Description:**
convert string linear color

---

---

### **ConvertStringToDatetime**

**Return Type:** `FDateTime`

**Parameters:**
- `FString string, FString separator`

**Description:**
return a datetime based on string

---

---

### **ConvertStringToRotator**

**Return Type:** `FRotator`

**Parameters:**
- `FString string, FString separator`

**Description:**
return a rotator based on string sapces and given separator will be removed automaticly. If no separator was given, space will be chose automaticly

---

---

### **ConvertStringTo3dVector**

**Return Type:** `FVector`

**Parameters:**
- `FString string, FString separator`

**Description:**
return a 3d vector based on string, sapces and given separator will be removed automaticly. If no separator was given, space will be chose automaticly

---

---

### **ConvertStringTo2dVector**

**Return Type:** `FVector2D`

**Parameters:**
- `FString string, FString separator`

**Description:**
return a 2d vector based on string, sapces and given separator will be removed automaticly. If no separator was given, space will be chose automaticly

---

---

### **ConvertBinaryStringToInt**

**Return Type:** `int64`

**Parameters:**
- `FString string`

**Description:**
Convert a binary string to int ( return 0 if the conversion failed)

---

---

### **ConvertIntToBinaryString**

**Return Type:** `FString`

**Parameters:**
- `int32 value`

**Description:**
Convert an int to a binary string

---

---

### **ConvertCustomBaseStringToInt**

**Return Type:** `int64`

**Parameters:**
- `FString string, int32 base`

**Description:**
Convert a number string with a custom base to int ( return 0 if conversion failed )

---

---

### **ConvertHexadecimalStringToInt**

**Return Type:** `int64`

**Parameters:**
- `FString string`

**Description:**
Convert a hexadecimal string to int (return 0 if conversion failed )

---

---

### **ConvertOctalStringToInt**

**Return Type:** `int64`

**Parameters:**
- `FString string`

**Description:**
Convert an octal string to int (return 0 if conversion failed )

---

---

### **ConvertIntToHexadecimalString**

**Return Type:** `FString`

**Parameters:**
- `int32 value`

**Description:**
Convert an int to a hexadecimal string

---

---

### **ConvertIntToOctalString**

**Return Type:** `FString`

**Parameters:**
- `int32 value`

**Description:**
Convert an int to an octal string

---

---

### **ConvertIntToCustomBaseString**

**Return Type:** `FString`

**Parameters:**
- `int32 value, int32 base`

**Description:**
Convert an int to a number string with a custom base

---

---

### **ConvertDateTimeToString**

**Return Type:** `FString`

**Parameters:**
- `FDateTime datetime`

**Description:**
Convert a dateTime to a string

---

---

### **IsStringInStringArray**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> stringArray`

**Description:**
Return true if the string is found in the array of strings

---

---

### **AreNumerics**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if all elements of the string are numerics 

---

---

### **AreAlphas**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if all elements of the string are Alphas 

---

---

### **AreSpecials**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if all elements of the string are specials characters 

---

---

### **AreUppers**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if all elements of the string are upper characters 

---

---

### **AreLowers**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if all elements of the string are lower characters 

---

---

### **ContainsNumeric**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if there is a numeric character in the given string

---

---

### **ContainsAlpha**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if there is a Alpha in the given string

---

---

### **ContainsSpecial**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if there is a special character in the given string

---

---

### **ContainsUpper**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if there is an upper character in the given string

---

---

### **ContainsLower**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
return true if there is an lower character in the given string

---

---

### **ContainsChars**

**Return Type:** `bool`

**Parameters:**
- `FString string, FString characters`

**Description:**
return true if any given characters was found 

---

---

### **IsEmailFormat**

**Return Type:** `int32`

**Parameters:**
- `FString string`

**Description:**
Check if the string is in the correct email format \n error code \n 0 no error \n 1 contains space \n 2 not allowed character \n 3 less or more than 1 '.' \n 4 less or more than 1 '@' \n 5 wrong '@' location \n 6 wrong '.' location

---

---

### **IsEmailDomainFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> domains`

**Description:**
check if the string is in the correct email format and contains given domains

---

---

### **IsUrlFormat**

**Return Type:** `int32`

**Parameters:**
- `FString string`

**Description:**
Check if a string is in the correct URL format \n error code \n 0 no error \n 1 no 'http://' or 'https://' \n 2 less than 3 sections ( separate by '.')

---

---

### **IsUrlTLDFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> TLD`

**Description:**
Return true if the url has the TLD listed in the given array

---

---

### **IsUrlDomainFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> domains`

**Description:**
Return true if the url has the TLD listed in the given array

---

---

### **IsUrlSubdomainFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> subDomains`

**Description:**
Return true if the url has the subdomain listed in the given array

---

---

### **IsUrlDomainAndSubdomainFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> domains, TArray<FString> subDomains`

**Description:**
Return true if the url has the domain and subdomain listed in the given arrays

---

---

### **GetUrlPathAsString**

**Return Type:** `FString`

**Parameters:**
- `FString string`

**Description:**
Get url path as string

---

---

### **IsIPv4Format**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the given string is an IPv4

---

---

### **IsIPv6Format**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the given string is an IPv6

---

---

### **IsHexadecimalFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the given string is a hexadecimal number

---

---

### **IsBinaryFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the given string is a binary number

---

---

### **IsOctalFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the given string is an octal number

---

---

### **IsFileFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string, TArray<FString> extensions`

**Description:**
Return true if the file has a given extension

---

---

### **IsImageFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the file has an image extension

---

---

### **IsVideoFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the file has a video extension

---

---

### **IsAudioFormat**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the file has an audio extension

---

---

### **IsUrlHttp**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the string represents an HTTP URL

---

---

### **IsUrlHttps**

**Return Type:** `bool`

**Parameters:**
- `FString string`

**Description:**
Return true if the string represents an HTTPS URL

---

---

### **SetDateTimeDay**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int day = 1`

**Description:**
Set the day of a dateTime

---

---

### **SetDateTimeYear**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int year = 1`

**Description:**
Set the year of a dateTime

---

---

### **SetDateTimeMonth**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int month = 1`

**Description:**
Set the month of a dateTime

---

---

### **SetDateTimeDate**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int year = 1, int month = 1, int day = 1`

**Description:**
Set the date (day, month and year) of a dateTime

---

---

### **SetDateTimeHour**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int hour = 0`

**Description:**
Set the hour of a dateTime

---

---

### **SetDateTimeMinute**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int minute = 0`

**Description:**
Set the minute of a dateTime

---

---

### **SetDateTimeSecond**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int second = 0`

**Description:**
Set the second of a dateTime

---

---

### **SetDateTimeMillisecond**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int millisecond = 0`

**Description:**
Set the millisecond of a dateTime

---

---

### **SetDateTimeTime**

**Return Type:** `FDateTime`

**Parameters:**
- `FDateTime dateTime, int hour = 0, int minute = 0, int second = 0, int millisecond = 0`

**Description:**
Set the time (hour, minute, second and millisecond) of a dateTime

---

