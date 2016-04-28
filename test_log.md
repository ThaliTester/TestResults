#### Test 68102130b92179b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-28T08:54:14.183Z - info: Require 3 ios devices

2016-04-28T08:54:14.201Z - info: Require 3 android devices

2016-04-28T08:54:14.262Z - info: listening on *:3000

2016-04-28T08:54:16.331Z - debug: Device presented: Apple-IpadAir2-1 (7584a5f3-2256-45a1-9c7d-be4cbf8153ae) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:16.497Z - debug: Device presented: Apple-Iphone5-1 (39dd3916-35f9-4a63-adf1-607e164f1c21) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:16.583Z - debug: Device presented: LGE-Nexus 5 (b3ba475f-78b4-4e29-99f3-31c87c9ba199) - android 5.1.1

2016-04-28T08:54:17.029Z - debug: Device presented: LGE-LG-H815 (4229f21b-ebd7-4926-8bf1-c807320e00d3) - android 5.1

2016-04-28T08:54:17.266Z - debug: Device presented: Apple-IpadAir2-1 (7584a5f3-2256-45a1-9c7d-be4cbf8153ae) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:17.269Z - info: Updating existing device: Apple-IpadAir2-1 (7584a5f3-2256-45a1-9c7d-be4cbf8153ae)

2016-04-28T08:54:17.417Z - debug: Device presented: Apple-Iphone5-1 (39dd3916-35f9-4a63-adf1-607e164f1c21) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:17.419Z - info: Updating existing device: Apple-Iphone5-1 (39dd3916-35f9-4a63-adf1-607e164f1c21)

2016-04-28T08:54:17.659Z - debug: Device presented: LGE-Nexus 5 (b3ba475f-78b4-4e29-99f3-31c87c9ba199) - android 5.1.1

2016-04-28T08:54:17.660Z - info: Updating existing device: LGE-Nexus 5 (b3ba475f-78b4-4e29-99f3-31c87c9ba199)

2016-04-28T08:54:17.684Z - debug: Device presented: Apple-Iphone5s-1 (602bb9c9-bfd6-48e7-bfb3-efdcc26cf1fa) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:18.002Z - debug: Device presented: LGE-LG-H815 (4229f21b-ebd7-4926-8bf1-c807320e00d3) - android 5.1

2016-04-28T08:54:18.003Z - info: Updating existing device: LGE-LG-H815 (4229f21b-ebd7-4926-8bf1-c807320e00d3)

2016-04-28T08:54:18.669Z - debug: Device presented: Apple-Iphone5s-1 (602bb9c9-bfd6-48e7-bfb3-efdcc26cf1fa) - ios Version 9.1 (Build 13B143)

2016-04-28T08:54:18.672Z - info: Updating existing device: Apple-Iphone5s-1 (602bb9c9-bfd6-48e7-bfb3-efdcc26cf1fa)

2016-04-28T08:54:25.240Z - debug: Device presented: samsung-SM-N910C (e296048a-fdb5-4bf2-aac5-59d20691743e) - android 5.1.1

2016-04-28T08:54:30.874Z - debug: Device presented: motorola-Nexus 6 (bef6c5b3-14d7-4bc1-a09a-55d1772aec06) - android 5.1.1

2016-04-28T08:54:30.876Z - info: All 4 android devices are present

2016-04-28T08:54:30.878Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-28T08:54:30.890Z - info: Starting unit test run on 3 android devices

2016-04-28T08:54:31.716Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-28T08:54:31.749Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-28T08:54:32.191Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-28T08:54:32.669Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-28T08:54:33.142Z - info: Running on android test: 4. native server connections all up

2016-04-28T08:54:33.606Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-28T08:54:33.933Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-28T08:54:34.294Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-28T08:54:34.636Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-28T08:54:35.011Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-28T08:54:35.803Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-28T08:54:36.138Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-28T08:54:36.528Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-28T08:54:36.897Z - info: Running on android test: 13. closeAll with promise

2016-04-28T08:54:37.267Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-28T08:54:37.646Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-28T08:54:38.051Z - info: Running on android test: 16. enqueue and run in order

2016-04-28T08:54:38.661Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-28T08:54:38.958Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-28T08:54:39.408Z - info: Running on android test: 19. queues handled independently

2016-04-28T08:54:39.754Z - info: Running on android test: 20. basic

2016-04-28T08:54:40.087Z - info: Running on android test: 21. another

2016-04-28T08:54:40.457Z - info: Running on android test: 22. can pass data in setup

2016-04-28T08:54:40.922Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-28T08:54:41.262Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-28T08:54:41.639Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-28T08:54:42.105Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-28T08:54:47.695Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-28T08:54:52.835Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-28T08:54:53.110Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-28T08:54:53.447Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-28T08:55:01.257Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-28T08:55:01.690Z - info: Running on android test: 32. can get the network status

2016-04-28T08:55:01.962Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-28T08:55:04.251Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-28T08:55:12.365Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-28T08:55:20.416Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-28T08:55:20.681Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-28T08:55:25.680Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-28T08:55:30.778Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-28T08:55:31.153Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-28T08:55:31.455Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-28T08:55:40.270Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-28T08:55:55.158Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-28T08:56:14.392Z - info: Running on android test: 44. Connect port dies if not connected to in time

2016-04-28T08:56:14.947Z - info: Running on android test: 45. Can shift large amounts of data

2016-04-28T08:56:31.788Z - info: Running on android test: 46. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-04-28T08:56:49.007Z - info: Running on android test: 47. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-04-28T08:57:10.845Z - info: Running on android test: 48. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-04-28T08:57:29.882Z - info: Running on android test: 49. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-04-28T08:57:52.235Z - info: Running on android test: 50. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-04-28T08:58:09.019Z - info: Running on android test: 51. Test updating advertising and parallel data transfer

2016-04-28T08:58:49.556Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T08:59:05.082Z - debug: Device presented: LGE-LG-H815 (7c7086ce-bf16-4b95-8582-ca806e3121a4) - android 5.1

2016-04-28T08:59:05.085Z - info: All 4 android devices are present

2016-04-28T08:59:05.086Z - info: Starting unit test run on 4 android devices

2016-04-28T08:59:05.870Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-04-28T09:13:36.440Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-28T09:13:36.491Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-28T09:13:36.522Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-28T09:15:09.561Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-28T09:17:43.934Z - info: Socket to device samsung-SM-N910C disconnected: transport close


 
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
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/68102130b92179b_Fixes_and_hardening_tompaana/thali08_motorola-Nexus 6.md)




