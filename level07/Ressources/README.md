```shell
$> ls -la
[...]
-rwsr-s---+ 1 level08 users   11744 Sep 10  2016 level07
[...]

$> ./level07
----------------------------------------------------
  Welcome to wil's crappy number storage service!   
----------------------------------------------------
 Commands:                                          
    store - store a number into the data storage    
    read  - read a number from the data storage     
    quit  - exit the program                        
----------------------------------------------------
   wil has reserved some storage :>                 
----------------------------------------------------

Input command: store
 Number: 42
 Index: 42
 *** ERROR! ***
   This index is reserved for wil!
 *** ERROR! ***
 Failed to do store command
Input command: read
 Index: 42
 Number at data[42] is 0
 Completed read command successfully
Input command: quit
```

Analyze with ghidra and disassembler the code in GDB

```c
```

```shell
```