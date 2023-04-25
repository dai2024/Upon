# Warinng -> Warn

<details>
<summary>W</summary>
PS

```PS
ls .\?indows.h
```

```
ls .\Windows.h	
```

```
ls .\windows.h
```
	
</details>

<details>
<summary></summary>
## swift
```bash
warning: 'swift run file.swift' command to interpret swift files is deprecated; use 'swift file.swift' instead

Annotations
1 warning
Swift: .github#L1
macOS-latest pipelines will use macOS-12 soon. For more details, see https://github.com/actions/runner-images/issues/6384
```

```
Run swift file.swift
  swift file.swift
  shell: /bin/bash -e {0}
```

```
Run swift file.swift
file.swift:9:13: error: cannot find type 'ObserableObject' in scope
class Data: ObserableObject {
            ^~~~~~~~~~~~~~~
Error: Process completed with exit code 1.
```

```
warning: 'swift run file.swift' command to interpret swift files is deprecated; use 'swift file.swift' instead
file.swift:16:18: error: cannot convert return expression of type 'Int64' to return type 'Int'
    return a < b ? b : a
           ~~~~~~^~~~~~~
           Int(         )
file.swift:20:18: error: cannot convert return expression of type 'Int32' to return type 'Int'
    return a < b ? b : a
           ~~~~~~^~~~~~~
           Int(         )
```
```
warning: 'swift run file.swift' command to interpret swift files is deprecated; use 'swift file.swift' instead
file.swift:16:18: error: cannot convert return expression of type 'Int' to return type 'Int64'
    return a < b ? b : a
           ~~~~~~^~~~~~~
           Int64(       )
file.swift:20:18: error: cannot convert return expression of type 'Int' to return type 'Int32'
    return a < b ? b : a
           ~~~~~~^~~~~~~
           Int32(       )
```

- Do you want results only for ObserableObject?
- The logs for this run have expired and are no longer available.

## go
```
./hello.go:8:8 invalid operation: i ^ j (mismatched types Int and Int64)
```
## c
```bash
Hello8.c: In function ‘main’:
Hello8.c:13:26: warning: conversion from ‘long unsigned int’ to ‘unsigned int’ changes value from ‘18446744073709551615’ to ‘4294967295’ [-Woverflow]
   13 |         unsigned int b = 0xffffffffffffffff;
      |                          ^~~~~~~~~~~~~~~~~~
```
```
hello8.c:2:13: warning: overflow in conversion from ‘long unsigned int’ to ‘int’ changes value from ‘18446744073709551615’ to ‘-1’ [-Woverflow]
    2 |     int a = (1 << 1) - sizeof(int) + 1;
```

```
template<typename _Tp>
constexpr
inline const _Tp&
max(const _Tp& __a, const _Tp& __b)
{
	if (__a < __b)
 		return __b;
      	return __a;
}
```

## PS
```PS
PS *:\***\***> Write-Output -InputObject Hello, world &!?
At line:1 char:40
+ Write-Output -InputObject Hello, world &!?
+                                        ~
The ampersand (&) character is not allowed. The & operator is reserved for future 
use; wrap an ampersand in double quotation marks ("&") to pass it as part of a 
string.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordExcepti 
   on
    + FullyQualifiedErrorId : AmpersandNotAllowed
```
</details>
