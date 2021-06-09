# Keep Mining

This simple bat script can help you wont stop mining!

- Miner close automatically troubleshoot
- Miner stop automatically troubleshoot
- Instable connection mining troubleshoot
- Lost connection mining troubleshoot

## How-To
- Save the script bellow in the same folder that your bat is running, like keep-mining.bat.
Remember to change [YOUR_BAT_NAME.bat] for your bat name!
Execute and it ll keep mining!

```
@echo off

:loop
 call [YOUR_BAT_NAME.bat]
GOTO :loop
```

## Alternative
If you prefer to simplify as one bat you can do something like this:

```
@echo off

:loop
 ethminer.exe -P stratum1+tcp://0x0000000000000000000000000000000000000000.NaoDivulgue@us1.ethermine.org:4444
GOTO :loop
```