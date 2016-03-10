#### Test 61362366b225741 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":2}}
2016-03-10T10:14:33.891Z - info: listening on *:3000

2016-03-10T10:14:36.151Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:0

2016-03-10T10:14:36.611Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-03-10T10:14:36.614Z - info: Required number of ios devices presented (2)

2016-03-10T10:14:36.618Z - info: Starting unit test run for platform: ios

2016-03-10T10:14:37.159Z - info: Running on ios test: 1. multiplex can send data

2016-03-10T10:14:37.505Z - info: Running on ios test: 2. enqueue and run in order

2016-03-10T10:14:37.590Z - debug: Device presented: Apple-Iphone5s-1 (ios) unittest socket:2

2016-03-10T10:14:37.592Z - info: Discarding surplus device: Apple-Iphone5s-1

2016-03-10T10:14:38.060Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:3

2016-03-10T10:14:38.062Z - info: Discarding surplus device: Apple-Iphone5-1

2016-03-10T10:14:38.125Z - info: Running on ios test: 3. enqueueAtTop and run backwards

2016-03-10T10:14:38.464Z - info: Running on ios test: 4. mix enqueue and enqueueAtTop

2016-03-10T10:14:39.339Z - info: Running on ios test: 5. queues handled independently

2016-03-10T10:14:39.830Z - info: Running on ios test: 6. basic

2016-03-10T10:14:40.118Z - info: Running on ios test: 7. another

2016-03-10T10:14:40.132Z - debug: Socket disconnected: transport close 2 (Apple-Iphone5s-1)

2016-03-10T10:14:40.443Z - info: Running on ios test: 8. #startListeningForAdvertisements should fail if start not called

2016-03-10T10:14:40.769Z - info: Running on ios test: 9. #startUpdateAdvertisingAndListening should fail if start not called

2016-03-10T10:14:41.030Z - info: Running on ios test: 10. should be able to call #stopListeningForAdvertisements many times

2016-03-10T10:14:41.160Z - debug: Socket disconnected: transport close 3 (Apple-Iphone5-1)

2016-03-10T10:14:41.332Z - info: Running on ios test: 11. should be able to call #startListeningForAdvertisements many times

2016-03-10T10:14:41.624Z - info: Running on ios test: 12. should be able to call #startUpdateAdvertisingAndListening many times

2016-03-10T10:14:42.109Z - info: Running on ios test: 13. should be able to call #stopAdvertisingAndListening many times

2016-03-10T10:14:42.449Z - info: Running on ios test: 14. #start should fail if called twice in a row

2016-03-10T10:14:42.716Z - info: Running on ios test: 15. does not emit duplicate discoveryAdvertisingStateUpdate

2016-03-10T10:14:43.070Z - info: Running on ios test: 16. does not send duplicate availability changes

2016-03-10T10:14:43.341Z - info: Running on ios test: 17. can get the network status

2016-03-10T10:14:43.710Z - info: Running on ios test: 18. wifi peer is marked unavailable if announcements stop

2016-03-10T10:14:45.222Z - info: Running on ios test: 19. Can call start/stopListeningForAdvertisements

2016-03-10T10:14:45.803Z - info: Running on ios test: 20. Calling startListeningForAdvertisements twice is NOT an error

2016-03-10T10:14:47.299Z - info: Running on ios test: 21. Can call start/stopUpdateAdvertisingAndListening

2016-03-10T10:14:49.369Z - info: Running on ios test: 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

2016-03-10T10:14:52.167Z - info: Running on ios test: 23. peerAvailabilityChange is called

2016-03-10T10:14:52.980Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:4

2016-03-10T10:14:56.153Z - info: Running on ios test: 24. Can connect to a remote peer

2016-03-10T10:33:35.217Z - debug: Socket disconnected: transport close 0 (Apple-IpadAir2-1)

2016-03-10T10:33:35.254Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-03-10T10:38:09.345Z - debug: Socket disconnected: transport close 4 (samsung-SM-N910C)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_Iphone6-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/61362366b225741_Make_CI_build_and_unit_tests_pass_vjrantal/thali04_samsung-SM-N910C.md)




