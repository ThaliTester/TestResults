#### Test 625481246a7d362 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-03-21T14:50:49.949Z - info: listening on *:3000

2016-03-21T14:50:51.806Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-21T14:50:52.130Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:1

2016-03-21T14:50:52.431Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:2

2016-03-21T14:50:52.433Z - info: Required number of ios devices presented (2)

2016-03-21T14:50:52.437Z - info: Starting unit test run for platform: ios

2016-03-21T14:50:53.067Z - info: Running on ios test: 1. calling createNativeListener directly rejects

2016-03-21T14:50:53.359Z - info: Running on ios test: 2. emits incomingConnectionState

2016-03-21T14:50:53.782Z - info: Running on ios test: 3. emits routerPortConnectionFailed

2016-03-21T14:50:53.995Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-03-21T14:50:53.996Z - info: Discarding surplus device: Apple-Iphone6-1

2016-03-21T14:50:54.089Z - info: Running on ios test: 4. native server connections all up

2016-03-21T14:50:54.484Z - info: Running on ios test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T14:50:54.964Z - info: Running on ios test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T14:50:55.516Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:3

2016-03-21T14:50:55.517Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-21T14:50:55.525Z - info: Running on ios test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T14:50:56.059Z - info: Running on ios test: 8. native server - closing the whole server cleans everything up

2016-03-21T14:50:56.691Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-03-21T14:50:56.744Z - info: Running on ios test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T14:50:56.977Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:5

2016-03-21T14:50:56.978Z - info: Required number of android devices presented (2)

2016-03-21T14:50:56.979Z - info: Starting unit test run for platform: android

2016-03-21T14:50:57.522Z - info: Running on android test: 1. calling createNativeListener directly rejects

2016-03-21T14:50:57.998Z - info: Running on android test: 2. emits incomingConnectionState

2016-03-21T14:50:58.098Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5s-1)

2016-03-21T14:50:58.610Z - info: Running on android test: 3. emits routerPortConnectionFailed

2016-03-21T14:50:59.166Z - info: Running on android test: 4. native server connections all up

2016-03-21T14:50:59.880Z - info: Running on android test: 5. native server - closing incoming stream cleans outgoing socket

2016-03-21T14:51:00.539Z - info: Running on android test: 6. native server - closing incoming connection cleans outgoing socket

2016-03-21T14:51:00.995Z - info: Running on android test: 7. native server - closing outgoing socket cleans associated mux stream

2016-03-21T14:51:01.308Z - info: Running on android test: 8. native server - closing the whole server cleans everything up

2016-03-21T14:51:01.784Z - info: Running on android test: 9. native server - we can get a ton of connections and data through and still clean up the server completely

2016-03-21T14:51:02.696Z - info: Running on android test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T14:51:03.143Z - info: Running on android test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T14:51:03.532Z - info: Running on android test: 12. closeAll can close even when connections open

2016-03-21T14:51:03.943Z - info: Running on android test: 13. closeAll with promise

2016-03-21T14:51:04.215Z - info: Running on android test: 14. multiplex can send data

2016-03-21T14:51:04.595Z - info: Running on android test: 15. enqueue and run in order

2016-03-21T14:51:05.219Z - info: Running on android test: 16. enqueueAtTop and run backwards

2016-03-21T14:51:05.477Z - info: Running on ios test: 10. native server - simulate mux failure, make sure everything is cleaned up

2016-03-21T14:51:05.598Z - info: Running on android test: 17. mix enqueue and enqueueAtTop

2016-03-21T14:51:06.107Z - info: Running on android test: 18. queues handled independently

2016-03-21T14:51:06.208Z - info: Running on ios test: 11. native server - timing out the incoming connection cleans everything up

2016-03-21T14:51:06.512Z - info: Running on android test: 19. basic

2016-03-21T14:51:06.613Z - info: Running on ios test: 12. closeAll can close even when connections open

2016-03-21T14:51:06.779Z - info: Running on android test: 20. another

2016-03-21T14:51:06.898Z - info: Running on ios test: 13. closeAll with promise

2016-03-21T14:51:07.182Z - info: Running on android test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T14:51:07.333Z - info: Running on ios test: 14. multiplex can send data

2016-03-21T14:51:07.581Z - info: Running on android test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T14:51:07.686Z - info: Running on ios test: 15. enqueue and run in order

2016-03-21T14:51:07.786Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:6

2016-03-21T14:51:07.787Z - info: Discarding surplus device: motorola-Nexus 6

2016-03-21T14:51:07.832Z - info: Running on android test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T14:51:08.203Z - info: Running on ios test: 16. enqueueAtTop and run backwards

2016-03-21T14:51:08.249Z - info: Running on android test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T14:51:08.419Z - debug: Socket disconnected: transport close 6 (motorola-Nexus 6)

2016-03-21T14:51:08.503Z - info: Running on ios test: 17. mix enqueue and enqueueAtTop

2016-03-21T14:51:08.867Z - info: Running on ios test: 18. queues handled independently

2016-03-21T14:51:08.953Z - info: Running on android test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T14:51:09.182Z - info: Running on ios test: 19. basic

2016-03-21T14:51:09.486Z - info: Running on ios test: 20. another

2016-03-21T14:51:09.745Z - info: Running on android test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T14:51:09.798Z - info: Running on ios test: 21. #startListeningForAdvertisements should fail if start not called

2016-03-21T14:51:10.175Z - info: Running on ios test: 22. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T14:51:10.211Z - info: Running on android test: 27. #start should fail if called twice in a row

2016-03-21T14:51:10.732Z - info: Running on android test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T14:51:11.996Z - info: Running on android test: 29. does not send duplicate availability changes

2016-03-21T14:51:12.474Z - info: Running on android test: 30. can get the network status

2016-03-21T14:51:12.969Z - info: Running on android test: 31. wifi peer is marked unavailable if announcements stop

2016-03-21T14:51:14.319Z - info: Running on android test: 32. Can call start/stopListeningForAdvertisements

2016-03-21T14:51:14.747Z - info: Running on ios test: 23. should be able to call #stopListeningForAdvertisements many times

2016-03-21T14:51:14.926Z - info: Running on android test: 33. Calling startListeningForAdvertisements twice is NOT an error

2016-03-21T14:51:15.389Z - info: Running on ios test: 24. should be able to call #startListeningForAdvertisements many times

2016-03-21T14:51:15.910Z - info: Running on android test: 34. Can call start/stopUpdateAdvertisingAndListening

2016-03-21T14:51:16.017Z - info: Running on ios test: 25. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T14:51:16.629Z - info: Running on android test: 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-21T14:51:17.621Z - info: Running on android test: 36. peerAvailabilityChange is called

2016-03-21T14:51:17.679Z - info: Running on ios test: 26. should be able to call #stopAdvertisingAndListening many times

2016-03-21T14:51:19.713Z - info: Running on android test: 37. Can connect to a remote peer

2016-03-21T14:51:19.724Z - info: Running on ios test: 27. #start should fail if called twice in a row

2016-03-21T14:51:20.553Z - info: Running on ios test: 28. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-21T14:51:28.868Z - info: Running on android test: 38. Can shift large amounts of data

2016-03-21T14:51:34.515Z - info: Running on android test: 39. #startListeningForAdvertisements should fail if start not called

2016-03-21T14:51:35.013Z - info: Running on android test: 40. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-21T14:51:35.398Z - info: Running on android test: 41. should be able to call #stopListeningForAdvertisements many times

2016-03-21T14:51:35.827Z - info: Running on android test: 42. should be able to call #startListeningForAdvertisements many times

2016-03-21T14:51:36.531Z - info: Running on android test: 43. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-21T14:51:37.485Z - info: Running on android test: 44. should be able to call #stopAdvertisingAndListening many times

2016-03-21T14:51:38.269Z - info: Running on android test: 45. can get the network status before starting

2016-03-21T14:51:40.642Z - info: Running on android test: 46. error returned with bad router

2016-03-21T14:51:42.357Z - info: Running on android test: 47. all services are stopped when we call stop

2016-03-21T14:51:44.913Z - info: Running on android test: 48. make sure terminateConnection is properly hooked up

2016-03-21T14:51:45.891Z - info: Running on android test: 49. make sure terminateListener is properly hooked up

2016-03-21T14:51:46.540Z - info: Running on android test: 50. make sure we actually call kill connections properly

2016-03-21T14:51:47.029Z - info: Running on android test: 51. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received

2016-03-21T14:51:48.274Z - debug: Socket disconnected: transport close 1 (LGE-LG-H815)

2016-03-21T14:51:48.371Z - debug: Socket disconnected: transport close 5 (samsung-SM-N910C)

2016-03-21T14:52:45.825Z - debug: Socket disconnected: ping timeout 0 (Apple-IpadAir2-1)

2016-03-21T15:10:21.636Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5-1)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true

```
###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  FAILED
Device test finished on LGH8153b36be34 
Android task is completed. [FAILED]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
STOP log received from  41006f95c8139173 Test has  FAILED
Device test finished on 41006f95c8139173 
Android task is completed. [FAILED]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/thali08_motorola-Nexus 6.md)


###iOS Logs
[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/625481246a7d362_More_thaliMobileNativeWrapper_vjrantal/iOS_server.md)




