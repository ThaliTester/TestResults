#### Test 68102130f73255a Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-29T08:12:18.010Z - info: Require 3 ios devices

2016-04-29T08:12:18.028Z - info: Require 3 android devices

2016-04-29T08:12:18.088Z - info: listening on *:3000

2016-04-29T08:12:19.563Z - debug: Device presented: Apple-Iphone5s-1 (b7cd0fef-ad33-49c5-8781-858c9a5e3542) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:20.507Z - debug: Device presented: Apple-Iphone5s-1 (b7cd0fef-ad33-49c5-8781-858c9a5e3542) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:20.511Z - info: Updating existing device: Apple-Iphone5s-1 (b7cd0fef-ad33-49c5-8781-858c9a5e3542)

2016-04-29T08:12:20.595Z - debug: Device presented: Apple-Iphone6-1 (b7ccdf89-53fb-4b69-acec-42a4f66f335f) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:21.228Z - debug: Device presented: LGE-Nexus 5 (c84595dd-cff7-4506-93ef-a1dd06600ac5) - android 5.1.1

2016-04-29T08:12:21.528Z - debug: Device presented: Apple-Iphone6-1 (b7ccdf89-53fb-4b69-acec-42a4f66f335f) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:21.529Z - info: Updating existing device: Apple-Iphone6-1 (b7ccdf89-53fb-4b69-acec-42a4f66f335f)

2016-04-29T08:12:21.657Z - debug: Device presented: Apple-IpadAir2-1 (831652d1-f5dc-4370-9bb4-e736119d075f) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:22.039Z - debug: Device presented: Apple-Iphone5-1 (f94a4309-984a-4df8-a677-f820db7183f0) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:22.041Z - info: All 4 ios devices are present

2016-04-29T08:12:22.048Z - info: Starting unit test run on 4 ios devices

2016-04-29T08:12:22.240Z - debug: Device presented: LGE-Nexus 5 (c84595dd-cff7-4506-93ef-a1dd06600ac5) - android 5.1.1

2016-04-29T08:12:22.241Z - info: Updating existing device: LGE-Nexus 5 (c84595dd-cff7-4506-93ef-a1dd06600ac5)

2016-04-29T08:12:22.614Z - debug: Device presented: LGE-LG-H815 (4e020bad-02ee-4433-98e7-a542062bcaff) - android 5.1

2016-04-29T08:12:22.627Z - debug: Device presented: Apple-IpadAir2-1 (831652d1-f5dc-4370-9bb4-e736119d075f) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:22.628Z - info: Updating existing device: Apple-IpadAir2-1 (831652d1-f5dc-4370-9bb4-e736119d075f)

2016-04-29T08:12:22.904Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-04-29T08:12:23.035Z - debug: Device presented: motorola-Nexus 6 (377ec322-e2ed-4c30-96a3-e44f6a4e8dfa) - android 5.1.1

2016-04-29T08:12:23.043Z - debug: Device presented: Apple-Iphone5-1 (f94a4309-984a-4df8-a677-f820db7183f0) - ios Version 9.1 (Build 13B143)

2016-04-29T08:12:23.044Z - info: Updating existing device: Apple-Iphone5-1 (f94a4309-984a-4df8-a677-f820db7183f0)

2016-04-29T08:12:23.578Z - info: Running on ios test: 2. emits incomingConnectionState

2016-04-29T08:12:23.601Z - debug: Device presented: LGE-LG-H815 (4e020bad-02ee-4433-98e7-a542062bcaff) - android 5.1

2016-04-29T08:12:23.602Z - info: Updating existing device: LGE-LG-H815 (4e020bad-02ee-4433-98e7-a542062bcaff)

2016-04-29T08:12:24.076Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-04-29T08:12:24.582Z - info: Running on ios test: 4. native server connections all up

2016-04-29T08:12:24.890Z - debug: Device presented: samsung-SM-N910C (8ac3417a-a88a-4676-be99-31ce47e61222) - android 5.1.1

2016-04-29T08:12:24.891Z - info: All 4 android devices are present

2016-04-29T08:12:24.892Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-29T08:12:24.896Z - info: Starting unit test run on 3 android devices

2016-04-29T08:12:25.186Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-29T08:12:25.620Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-04-29T08:12:25.723Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-29T08:12:25.953Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-29T08:12:26.141Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-29T08:12:26.592Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-04-29T08:12:26.695Z - info: Running on android test: 2. emits incomingConnectionState

2016-04-29T08:12:27.074Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-29T08:12:28.119Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-04-29T08:12:28.927Z - info: Running on android test: 4. native server connections all up

2016-04-29T08:12:29.392Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-04-29T08:12:29.958Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-04-29T08:12:30.438Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-04-29T08:12:30.915Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-04-29T08:12:31.386Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-04-29T08:12:32.357Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-29T08:12:32.802Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-04-29T08:12:33.329Z - info: Running on android test: 12. closeAll can close even when connections open

2016-04-29T08:12:33.905Z - info: Running on android test: 13. closeAll with promise

2016-04-29T08:12:34.383Z - info: Running on android test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-29T08:12:34.958Z - info: Running on android test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-29T08:12:35.536Z - info: Running on android test: 16. enqueue and run in order

2016-04-29T08:12:35.698Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-04-29T08:12:36.320Z - info: Running on android test: 17. enqueueAtTop and run backwards

2016-04-29T08:12:36.717Z - info: Running on android test: 18. mix enqueue and enqueueAtTop

2016-04-29T08:12:37.248Z - info: Running on android test: 19. queues handled independently

2016-04-29T08:12:37.332Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-04-29T08:12:37.608Z - info: Running on android test: 20. basic

2016-04-29T08:12:37.840Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-04-29T08:12:37.973Z - info: Running on android test: 21. another

2016-04-29T08:12:38.368Z - info: Running on android test: 22. can pass data in setup

2016-04-29T08:12:38.397Z - info: Running on ios test: 13. closeAll with promise

2016-04-29T08:12:38.766Z - info: Running on android test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-29T08:12:38.929Z - info: Running on ios test: 14. closeAll properly throws when closing a non open server with eatNotRunning set to false

2016-04-29T08:12:39.314Z - info: Running on android test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-29T08:12:39.400Z - info: Running on ios test: 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true

2016-04-29T08:12:39.705Z - info: Running on android test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-29T08:12:39.874Z - info: Running on ios test: 16. enqueue and run in order

2016-04-29T08:12:40.231Z - info: Running on android test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-29T08:12:40.544Z - info: Running on ios test: 17. enqueueAtTop and run backwards

2016-04-29T08:12:40.930Z - info: Running on ios test: 18. mix enqueue and enqueueAtTop

2016-04-29T08:12:41.446Z - info: Running on ios test: 19. queues handled independently

2016-04-29T08:12:41.869Z - info: Running on ios test: 20. basic

2016-04-29T08:12:41.988Z - info: Running on android test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-29T08:12:42.240Z - info: Running on ios test: 21. another

2016-04-29T08:12:42.589Z - info: Running on ios test: 22. can pass data in setup

2016-04-29T08:12:42.926Z - info: Running on ios test: 23. #startListeningForAdvertisements should fail if start not called

2016-04-29T08:12:43.258Z - info: Running on android test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-29T08:12:43.263Z - info: Running on ios test: 24. #startUpdateAdvertisingAndListening should fail if start not called

2016-04-29T08:12:43.567Z - info: Running on android test: 29. #start should fail if called twice in a row

2016-04-29T08:12:43.698Z - info: Running on ios test: 25. should be able to call #stopListeningForAdvertisements many times

2016-04-29T08:12:43.954Z - info: Running on android test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-29T08:12:44.349Z - info: Running on ios test: 26. should be able to call #startListeningForAdvertisements many times

2016-04-29T08:12:44.970Z - info: Running on ios test: 27. should be able to call #startUpdateAdvertisingAndListening many times

2016-04-29T08:12:46.010Z - info: Running on android test: 31. does not send duplicate availability changes

2016-04-29T08:12:46.389Z - info: Running on android test: 32. can get the network status

2016-04-29T08:12:51.197Z - info: Running on ios test: 28. should be able to call #stopAdvertisingAndListening many times

2016-04-29T08:12:52.916Z - info: Running on android test: 33. wifi peer is marked unavailable if announcements stop

2016-04-29T08:13:03.880Z - info: Running on ios test: 29. #start should fail if called twice in a row

2016-04-29T08:13:04.293Z - info: Running on android test: 34. Can call start/stopListeningForAdvertisements

2016-04-29T08:13:04.356Z - info: Running on ios test: 30. does not emit duplicate discoveryAdvertisingStateUpdate

2016-04-29T08:13:04.819Z - info: Running on ios test: 31. does not send duplicate availability changes

2016-04-29T08:13:05.239Z - info: Running on ios test: 32. can get the network status

2016-04-29T08:13:06.319Z - info: Running on ios test: 33. wifi peer is marked unavailable if announcements stop

2016-04-29T08:13:09.498Z - info: Running on android test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-29T08:13:19.513Z - info: Running on android test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-29T08:13:24.466Z - info: Running on android test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-29T08:13:25.472Z - info: Running on android test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-29T08:13:26.516Z - info: Running on android test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-29T08:13:26.833Z - info: Running on android test: 40. cannot call connect when start listening for advertisements is not active

2016-04-29T08:13:27.207Z - info: Running on android test: 41. peerAvailabilityChange is called

2016-04-29T08:13:28.225Z - info: Running on ios test: 34. Can call start/stopListeningForAdvertisements

2016-04-29T08:13:28.920Z - info: Running on ios test: 35. Calling startListeningForAdvertisements twice is NOT an error

2016-04-29T08:13:29.819Z - info: Running on ios test: 36. Calling stopListeningForAdvertisements without calling start is NOT an error

2016-04-29T08:13:30.231Z - info: Running on android test: 42. Can connect to a remote peer

2016-04-29T08:13:40.754Z - info: Running on android test: 43. Get error when trying to double connect to a peer

2016-04-29T08:13:46.699Z - info: Running on ios test: 37. Can call start/stopUpdateAdvertisingAndListening

2016-04-29T08:13:47.367Z - info: Running on ios test: 38. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-04-29T08:13:48.012Z - info: Running on ios test: 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error

2016-04-29T08:14:01.165Z - info: Running on android test: 44. Connect port dies if not connected to in time

2016-04-29T08:14:02.546Z - info: Running on android test: 45. Can shift large amounts of data

2016-04-29T08:14:05.624Z - info: Running on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-29T08:14:08.663Z - warn: Failed on ios test: 40. cannot call connect when start listening for advertisements is not active

2016-04-29T08:14:08.665Z - info: Running on ios test: 41. peerAvailabilityChange is called

2016-04-29T08:14:12.980Z - info: Running on android test: 46. #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection

2016-04-29T08:14:17.472Z - info: Running on ios test: 42. Can connect to a remote peer

2016-04-29T08:15:17.060Z - info: Running on android test: 47. #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection

2016-04-29T08:15:28.620Z - info: Running on android test: 48. #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer

2016-04-29T08:16:13.821Z - info: Running on android test: 49. #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer

2016-04-29T08:16:42.098Z - warn: Failed on ios test: 42. Can connect to a remote peer

2016-04-29T08:16:42.100Z - info: Running on ios test: 43. Get error when trying to double connect to a peer

2016-04-29T08:17:00.677Z - info: Running on android test: 50. We do not emit peerAvailabilityChanged events until one of the start methods is called

2016-04-29T08:17:08.237Z - info: Running on android test: 51. Test updating advertising and parallel data transfer

2016-04-29T08:31:39.240Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-29T08:31:39.306Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-29T08:31:39.312Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-29T08:31:39.400Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-29T08:33:18.818Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-29T08:35:43.439Z - info: Socket to device samsung-SM-N910C disconnected: transport close

2016-04-29T08:35:45.490Z - info: Socket to device motorola-Nexus 6 disconnected: transport close


 
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
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/iOS_server.md)


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
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/thali07_LGE-LG-H815.md)

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
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/68102130f73255a_Fixes_and_hardening_tompaana/thali08_motorola-Nexus 6.md)




