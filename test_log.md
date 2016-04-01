#### Test 64941069b7d3db0 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T13:28:23.414Z - info: Require 3 ios devices

2016-04-01T13:28:23.433Z - info: Require 3 android devices

2016-04-01T13:28:23.493Z - info: listening on *:3000

2016-04-01T13:28:24.747Z - debug: Device presented: LGE-LG-H815 (1f3a3427-674c-400c-95ab-5c7ad4cc6133) - android 5.1

2016-04-01T13:28:25.571Z - debug: Device presented: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:25.628Z - debug: Device presented: LGE-LG-H815 (1f3a3427-674c-400c-95ab-5c7ad4cc6133) - android 5.1

2016-04-01T13:28:25.630Z - info: Updating existing device: LGE-LG-H815 (1f3a3427-674c-400c-95ab-5c7ad4cc6133)

2016-04-01T13:28:25.912Z - debug: Device presented: Apple-Iphone6-1 (00808060-5bbe-4b5b-bcc4-94f4c6c425a9) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:26.516Z - debug: Device presented: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:26.517Z - info: Updating existing device: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2)

2016-04-01T13:28:26.806Z - debug: Device presented: Apple-Iphone6-1 (00808060-5bbe-4b5b-bcc4-94f4c6c425a9) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:26.808Z - info: Updating existing device: Apple-Iphone6-1 (00808060-5bbe-4b5b-bcc4-94f4c6c425a9)

2016-04-01T13:28:27.087Z - debug: Device presented: LGE-Nexus 5 (47c2c59f-6700-458a-98e8-74b40d41b2c9) - android 5.1.1

2016-04-01T13:28:28.186Z - debug: Device presented: LGE-Nexus 5 (47c2c59f-6700-458a-98e8-74b40d41b2c9) - android 5.1.1

2016-04-01T13:28:28.187Z - info: Updating existing device: LGE-Nexus 5 (47c2c59f-6700-458a-98e8-74b40d41b2c9)

2016-04-01T13:28:28.521Z - debug: Device presented: Apple-IpadAir2-1 (9268d93e-6496-4daa-a1e8-946cc4e33b31) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:28.706Z - debug: Device presented: Apple-Iphone5s-1 (bd0104a2-12f2-49a9-9a5a-2c37d046ad3e) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:28.707Z - info: All 4 ios devices are present

2016-04-01T13:28:28.715Z - info: Starting unit test run on 4 ios devices

2016-04-01T13:28:29.407Z - debug: Device presented: Apple-IpadAir2-1 (9268d93e-6496-4daa-a1e8-946cc4e33b31) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:29.408Z - info: Updating existing device: Apple-IpadAir2-1 (9268d93e-6496-4daa-a1e8-946cc4e33b31)

2016-04-01T13:28:29.546Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-01T13:28:29.682Z - debug: Device presented: Apple-Iphone5s-1 (bd0104a2-12f2-49a9-9a5a-2c37d046ad3e) - ios Version 9.1 (Build 13B143)

2016-04-01T13:28:29.683Z - info: Updating existing device: Apple-Iphone5s-1 (bd0104a2-12f2-49a9-9a5a-2c37d046ad3e)

2016-04-01T13:28:30.163Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-01T13:28:30.597Z - debug: Device presented: samsung-SM-N910C (feca87d5-3c5d-4cf1-9e68-70c120b478b8) - android 5.1.1

2016-04-01T13:28:30.716Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-01T13:28:31.263Z - info: Running on ios test: 4. native server connections all up

2016-04-01T13:28:31.902Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T13:28:32.506Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T13:28:33.001Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T13:28:33.570Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-01T13:28:34.092Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T13:28:42.347Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T13:28:45.805Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T13:28:46.546Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-01T13:28:47.144Z - info: Running on ios test: 13. closeAll with promise

2016-04-01T13:28:47.642Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T13:28:48.174Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T13:28:48.763Z - info: Running on ios test: 16. enqueue and run in order

2016-04-01T13:28:49.544Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-01T13:28:49.688Z - debug: Device presented: motorola-Nexus 6 (f6c802f4-8436-4038-8ae8-70ae006f234c) - android 5.1.1

2016-04-01T13:28:49.689Z - info: All 4 android devices are present

2016-04-01T13:28:49.691Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T13:28:49.695Z - info: Starting unit test run on 3 android devices

2016-04-01T13:28:50.020Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-01T13:28:50.566Z - info: Running on ios test: 19. queues handled independently

2016-04-01T13:28:50.652Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T13:28:50.674Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-01T13:28:51.018Z - info: Running on ios test: 20. basic

2016-04-01T13:28:51.538Z - info: Running on ios test: 21. another

2016-04-01T13:28:52.297Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-01T13:28:53.541Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-01T13:28:54.081Z - info: Running on android test: 4. native server connections all up

2016-04-01T13:28:54.761Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-01T13:28:55.320Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-01T13:28:55.961Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-01T13:28:56.657Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-01T13:28:56.754Z - info: Running on ios test: 22. can pass data in setup

2016-04-01T13:28:57.359Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-01T13:28:58.456Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-01T13:28:58.892Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T13:28:59.035Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-01T13:28:59.455Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T13:28:59.560Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-01T13:28:59.891Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T13:29:00.165Z - info: Running on android test: 13. closeAll with promise

2016-04-01T13:29:00.456Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T13:29:01.652Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T13:29:02.955Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-01T13:29:46.400Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-01T13:29:50.000Z - info: Running on android test: 16. enqueue and run in order

2016-04-01T13:29:50.265Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T13:29:50.907Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-01T13:29:51.865Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-01T13:29:52.803Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-01T13:29:54.997Z - info: Running on android test: 19. queues handled independently

2016-04-01T13:30:09.121Z - info: Running on android test: 20. basic

2016-04-01T13:30:09.617Z - info: Running on android test: 21. another

2016-04-01T13:30:10.868Z - info: Running on android test: 22. can pass data in setup

2016-04-01T13:30:11.515Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-01T13:30:11.955Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-01T13:30:12.271Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-01T13:30:13.004Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-01T13:30:13.837Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-01T13:30:16.380Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-01T13:30:16.838Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-01T13:30:17.426Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T13:30:18.405Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-01T13:30:18.999Z - info: Running on android test: 32. can get the network status

2016-04-01T13:30:19.532Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T13:30:22.080Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T13:30:22.555Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T13:30:22.781Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-01T13:30:23.317Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-01T13:30:23.554Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-01T13:30:24.528Z - info: Running on ios test: 32. can get the network status

2016-04-01T13:30:25.211Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-01T13:30:27.177Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-01T13:30:30.161Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-01T13:30:58.605Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-01T13:31:02.522Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-01T13:31:10.521Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-01T13:31:12.060Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-01T13:31:12.199Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-01T13:31:32.920Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-01T13:32:36.304Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-01T13:32:45.361Z - warn: Failed on android test: 43. Get error when trying to double connect to a peer

2016-04-01T13:32:45.362Z - info: Running on android test: 44. Connect port dies if not connected to in in time

2016-04-01T13:33:45.927Z - debug: Too many emit retries to device: Apple-Iphone5-1

2016-04-01T13:34:01.597Z - info: Socket to device Apple-Iphone5-1 disconnected: ping timeout

2016-04-01T13:35:01.619Z - debug: Device presented: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2) - ios Version 9.1 (Build 13B143)

2016-04-01T13:35:01.620Z - info: Updating existing device: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2)

2016-04-01T13:35:02.506Z - debug: Device presented: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2) - ios Version 9.1 (Build 13B143)

2016-04-01T13:35:02.509Z - info: Updating existing device: Apple-Iphone5-1 (2be5ebec-a935-4f30-8b82-7039b8b8a0e2)

2016-04-01T13:48:11.640Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T13:48:11.672Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T13:48:11.682Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T13:48:11.800Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T13:49:48.018Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-01T13:51:59.244Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-01T13:52:01.253Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/64941069b7d3db0_Minor_fixes_vjrantal/thali08_motorola-Nexus 6.md)




