# regular-expressions-csharp
Hopefully this will become a nice doc with some usefull regular expressions.



**remove html tags from string**
```csharp
Regex.Replace(inputString, "<.*?>", String.Empty);
```
