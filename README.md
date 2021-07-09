# C-sharp-tip-trick

UTF8-WithBOM
```C#
Encoding encoding = new UTF8Encoding(true);
var writer = new StreamWriter(stream, encoding)
```
