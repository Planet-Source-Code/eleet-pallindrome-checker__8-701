<div align="center">

## Pallindrome Checker


</div>

### Description

Check to see if a string is a palindrome in only 5 lines of code!
 
### More Info
 
1 string which would be your string. Great to be the form andler for a form.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[eleet](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/eleet.md)
**Level**          |Beginner
**User Rating**    |3.3 (13 globes from 4 users)
**Compatibility**  |PHP 4\.0
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__8-26.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/eleet-pallindrome-checker__8-701/archive/master.zip)

### API Declarations

Please put my name eleet-2k2 in your code if you use it.


### Source Code

```
<html>
<head>
<title>Palindrome Checker</title>
</head>
<body>
<?php
$str_reversed = strrev($str);
if ($str == $str_reversed) {
	print("\'$str\' is a palindrome.<br>\n");
} else {
	print("\'$str\' is <b>not</b> a palindrome.<br>\n");
}
?>
</body>
</html>
```

