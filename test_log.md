#### Test 924347213a23a0d Logs

#### Test Server Logs
```
Error: Command failed: IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":1}}
2016-11-14 20:27:59 - INFO HttpServer: 'listening on *:3000'

2016-11-14 20:32:59 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_924347213a23a0d/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: CopyLog Failed (thali05): ssh: connect to host 192.168.1.54 port 22: Operation timed out

Error: Command failed: packet_write_wait: Connection to 192.168.1.54: Broken pipe
packet_write_wait: Connection to 192.168.1.54: Broken pipe


TIMEOUT REACHED!CopyLog Failed (thali05): ssh: connect to host 192.168.1.54 port 22: Operation timed out


```
###Android Logs
####Node name: thali05



