#### Test 113351851556e64f Logs

#### Test Server Logs
```
Error: Command failed: index.js failed [ 1 ]
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3}}
2017-05-24 08:26:02 - INFO HttpServer: 'listening on *:3000'

2017-05-24 08:29:03 - DEBUG HttpServer: 'device presented, name: 'Apple-ipad-air-2-1', uuid: '68b6562e-4d26-4bb0-8a7c-8a3ea2cc7ad3', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-24 08:29:03 - DEBUG TestFramework: 'device added, name: 'Apple-ipad-air-2-1''

2017-05-24 08:29:15 - DEBUG HttpServer: 'device presented, name: 'Apple-iphone-5s-1', uuid: '5663d3a1-cf5d-46a1-a53b-b166d6cf5a35', platformName: 'ios', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2017-05-24 08:29:15 - DEBUG TestFramework: 'device added, name: 'Apple-iphone-5s-1''

2017-05-24 08:31:02 - ERROR TestServerProcess: 'uncaught exception, error: 'Error: timeout exceed', stack: 'Error: timeout exceed
    at null._onTimeout (/home/pi/Test/server_113351851556e64f/test/TestServer/index.js:45:9)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2017-05-24 08:31:02 - INFO HttpServer: 'Socket to device name: 'Apple-ipad-air-2-1' disconnected, reason: 'undefined''

2017-05-24 08:31:02 - INFO HttpServer: 'Socket to device name: 'Apple-iphone-5s-1' disconnected, reason: 'undefined''

[0;31merror: command 'sudo jx ______.js ios' failed with code 1, file 'bash' on line 30[0m
One or more Android tests are failed.
 [0m
index.js failed [ 1 ]

```


Logs for system : 
```

ios : Error: Command failed: true
24/5/2017@10:24:12 Getting the list of iOS devices 
24/5/2017@10:24:13 ios: device name: iphone-5s-mfts , device identifier:  bffa901fefdea07f59339a6737776943349f5077
24/5/2017@10:24:13 ios: device name: iphone-5s-1 , device identifier:  00b2e2c1b30013159b62125fe7f097bdcc055c10
24/5/2017@10:24:13 ios: device name: ipad-air-2-1 , device identifier:  605a17dff1a0ba7f312ea7b076f5923e29d8b1fe
24/5/2017@10:24:13 Deploying iOS test app 
24/5/2017@10:24:13 uninstalling the application 
24/5/2017@10:24:14 installing the application 
24/5/2017@10:47:32 ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
24/5/2017@10:47:32 ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[iphone-5s-mfts](https://github.com/ThaliTester/TestResults/blob/113351851556e64f_CI_sanity_check_jareksl/iOS_iphone-5s-mfts.md)

[iphone-5s-1](https://github.com/ThaliTester/TestResults/blob/113351851556e64f_CI_sanity_check_jareksl/iOS_iphone-5s-1.md)

[ipad-air-2-1](https://github.com/ThaliTester/TestResults/blob/113351851556e64f_CI_sanity_check_jareksl/iOS_ipad-air-2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/113351851556e64f_CI_sanity_check_jareksl/iOS_server.md)




