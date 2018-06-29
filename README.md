# SimpleLengthScanner

This is a pretty straight forward tool. I got sick of fighting with dirb and wfuzz on sites that return 200 but a custom error page. So I built this tool.

You just need a bash shell and curl
```
Simple Length Scanner v1.0
Author: Anthony Russell
Twitter: @DotNetRussell

How to use:
./lengthScanner <full path to target> <ignore content length #> <full path to wordlist>

Example:
./lengthScanner http://10.10.10.10/target/path/ 12345 /usr/share/wordlists/dirb/big.txt
```
