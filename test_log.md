#### Test 648099366fd8e87 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T08:28:40.689Z - info: Require 3 ios devices

2016-04-01T08:28:40.708Z - info: Require 3 android devices

2016-04-01T08:28:40.767Z - info: listening on *:3000

2016-04-01T08:28:42.475Z - debug: Device presented: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:43.073Z - debug: Device presented: LGE-LG-H815 (b38e8f9b-8235-4d84-a3d0-b5cba0e4851b) - android 5.1

2016-04-01T08:28:43.364Z - debug: Device presented: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:43.366Z - info: Updating existing device: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394)

2016-04-01T08:28:43.470Z - debug: Device presented: Apple-IpadAir2-1 (674acf2f-26d0-4b75-8664-1b61e32c9c92) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:43.966Z - debug: Device presented: LGE-LG-H815 (b38e8f9b-8235-4d84-a3d0-b5cba0e4851b) - android 5.1

2016-04-01T08:28:43.967Z - info: Updating existing device: LGE-LG-H815 (b38e8f9b-8235-4d84-a3d0-b5cba0e4851b)

2016-04-01T08:28:44.542Z - debug: Device presented: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:44.550Z - debug: Device presented: Apple-IpadAir2-1 (674acf2f-26d0-4b75-8664-1b61e32c9c92) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:44.551Z - info: Updating existing device: Apple-IpadAir2-1 (674acf2f-26d0-4b75-8664-1b61e32c9c92)

2016-04-01T08:28:44.835Z - debug: Device presented: LGE-Nexus 5 (b246f6be-19d7-4484-8aff-f9299ae2d614) - android 5.1.1

2016-04-01T08:28:45.513Z - debug: Device presented: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:45.515Z - info: Updating existing device: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd)

2016-04-01T08:28:45.577Z - debug: Device presented: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:45.579Z - info: All 4 ios devices are present

2016-04-01T08:28:45.587Z - info: Starting unit test run on 4 ios devices

2016-04-01T08:28:45.895Z - debug: Device presented: LGE-Nexus 5 (b246f6be-19d7-4484-8aff-f9299ae2d614) - android 5.1.1

2016-04-01T08:28:45.896Z - info: Updating existing device: LGE-Nexus 5 (b246f6be-19d7-4484-8aff-f9299ae2d614)

2016-04-01T08:28:46.590Z - debug: Device presented: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744) - ios Version 9.1 (Build 13B143)

2016-04-01T08:28:46.591Z - info: Updating existing device: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744)

2016-04-01T08:28:48.189Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-01T08:28:48.984Z - debug: Device presented: samsung-SM-N910C (1a13810e-2cca-4140-bd70-dc162456a5a5) - android 5.1.1

2016-04-01T08:28:51.228Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-01T08:28:51.686Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-01T08:28:52.169Z - info: Running on ios test: 4. native server connections all up

2016-04-01T08:28:52.751Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T08:28:53.246Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T08:28:53.916Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T08:28:54.358Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-01T08:28:54.814Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T08:29:03.606Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T08:29:05.313Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T08:29:05.780Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-01T08:29:06.201Z - info: Running on ios test: 13. closeAll with promise

2016-04-01T08:29:06.391Z - debug: Device presented: motorola-Nexus 6 (0f88aeab-e112-4711-854c-6ee96409d4c0) - android 5.1.1

2016-04-01T08:29:06.393Z - info: All 4 android devices are present

2016-04-01T08:29:06.394Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T08:29:06.398Z - info: Starting unit test run on 3 android devices

2016-04-01T08:29:06.676Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T08:29:07.053Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T08:29:07.156Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T08:29:07.405Z - info: Running on ios test: 16. enqueue and run in order

2016-04-01T08:29:07.559Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-01T08:29:07.976Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-01T08:29:08.329Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-01T08:29:08.678Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-01T08:29:08.733Z - info: Running on ios test: 19. queues handled independently

2016-04-01T08:29:09.125Z - info: Running on ios test: 20. basic

2016-04-01T08:29:09.504Z - info: Running on ios test: 21. another

2016-04-01T08:29:09.927Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-01T08:29:09.966Z - info: Running on ios test: 22. can pass data in setup

2016-04-01T08:29:10.407Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T08:29:10.652Z - info: Running on android test: 4. native server connections all up

2016-04-01T08:29:10.757Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T08:29:11.086Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T08:29:11.161Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T08:29:11.523Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T08:29:11.651Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T08:29:12.171Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T08:29:12.646Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T08:29:12.704Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-01T08:29:14.451Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T08:29:22.292Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T08:29:30.449Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T08:30:36.600Z - info: Socket to device Apple-Iphone5-1 disconnected: transport error

2016-04-01T08:31:07.346Z - info: Socket to device Apple-Iphone5s-1 disconnected: ping timeout

2016-04-01T08:31:25.689Z - debug: Too many emit retries to device: Apple-Iphone5s-1

2016-04-01T08:31:25.691Z - debug: Too many emit retries to device: Apple-Iphone5-1

2016-04-01T08:31:58.936Z - info: Socket to device samsung-SM-N910C disconnected: ping timeout

2016-04-01T08:32:04.597Z - info: Socket to device Apple-Iphone6-1 disconnected: ping timeout

2016-04-01T08:32:18.107Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: ping timeout

2016-04-01T08:32:33.235Z - debug: Too many emit retries to device: samsung-SM-N910C

2016-04-01T08:32:56.343Z - debug: Device presented: samsung-SM-N910C (1a13810e-2cca-4140-bd70-dc162456a5a5) - android 5.1.1

2016-04-01T08:32:56.345Z - info: Updating existing device: samsung-SM-N910C (1a13810e-2cca-4140-bd70-dc162456a5a5)

2016-04-01T08:32:57.439Z - debug: Device presented: samsung-SM-N910C (1a13810e-2cca-4140-bd70-dc162456a5a5) - android 5.1.1

2016-04-01T08:32:57.440Z - info: Updating existing device: samsung-SM-N910C (1a13810e-2cca-4140-bd70-dc162456a5a5)

2016-04-01T08:34:37.627Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:34:47.465Z - debug: Device presented: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394) - ios Version 9.1 (Build 13B143)

2016-04-01T08:34:47.468Z - info: Updating existing device: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394)

2016-04-01T08:34:48.674Z - debug: Device presented: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394) - ios Version 9.1 (Build 13B143)

2016-04-01T08:34:48.677Z - info: Updating existing device: Apple-Iphone6-1 (a43a42fb-60cd-429b-9482-f47c6b29e394)

2016-04-01T08:35:37.203Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:35:37.381Z - info: Socket to device motorola-Nexus 6 disconnected: ping timeout

2016-04-01T08:35:40.928Z - debug: Device presented: motorola-Nexus 6 (0f88aeab-e112-4711-854c-6ee96409d4c0) - android 5.1.1

2016-04-01T08:35:40.928Z - info: Updating existing device: motorola-Nexus 6 (0f88aeab-e112-4711-854c-6ee96409d4c0)

2016-04-01T08:35:41.899Z - debug: Device presented: motorola-Nexus 6 (0f88aeab-e112-4711-854c-6ee96409d4c0) - android 5.1.1

2016-04-01T08:35:41.900Z - info: Updating existing device: motorola-Nexus 6 (0f88aeab-e112-4711-854c-6ee96409d4c0)

2016-04-01T08:36:13.740Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:36:14.728Z - debug: Device presented: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744) - ios Version 9.1 (Build 13B143)

2016-04-01T08:36:14.729Z - info: Updating existing device: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744)

2016-04-01T08:36:15.678Z - debug: Device presented: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744) - ios Version 9.1 (Build 13B143)

2016-04-01T08:36:15.679Z - info: Updating existing device: Apple-Iphone5-1 (4f3079db-5318-489d-b5a2-5da219f54744)

2016-04-01T08:36:51.966Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:36:55.734Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:37:02.474Z - info: Socket to device DEVICE THAT HAS NOT PRESENTED YET disconnected: transport close

2016-04-01T08:37:02.759Z - debug: Device presented: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd) - ios Version 9.1 (Build 13B143)

2016-04-01T08:37:02.760Z - info: Updating existing device: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd)

2016-04-01T08:37:03.797Z - debug: Device presented: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd) - ios Version 9.1 (Build 13B143)

2016-04-01T08:37:03.798Z - info: Updating existing device: Apple-Iphone5s-1 (ccbe122f-8216-4649-a64f-eb913b58c9dd)

2016-04-01T08:46:30.580Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T08:48:28.931Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T08:48:28.938Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T08:48:31.002Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T08:50:04.970Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-01T08:52:16.219Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-01T08:52:18.062Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/iOS_server.md)


###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/648099366fd8e87_416_Notification_final_juhanak/thali08_motorola-Nexus 6.md)




