#### Test 6136236661fd38c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5BD5C5F6-2F06-4805-9682-89F3DAC5588C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5BD5C5F6-2F06-4805-9682-89F3DAC5588C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6136236661fd38c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51291"
,(lldb)     command script import "/tmp/5BD5C5F6-2F06-4805-9682-89F3DAC5588C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-03 14:57:14.382 ThaliTest[550:651107] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/511B3AF7-D29B-4413-948B-BC75488256D1/Library/Cookies/Cookies.binarycookies
,2016-03-03 14:57:14.762 ThaliTest[550:651107] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-03 14:57:14.763 ThaliTest[550:651107] Multi-tasking -> Device: YES, App: YES
,2016-03-03 14:57:14.782 ThaliTest[550:651107] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-03 14:57:16.689 ThaliTest[550:651107] Using UIWebView
,2016-03-03 14:57:16.696 ThaliTest[550:651107] [CDVTimer][handleopenurl] 0.425994ms
,2016-03-03 14:57:16.703 ThaliTest[550:651107] [CDVTimer][intentandnavigationfilter] 6.563008ms
,2016-03-03 14:57:16.704 ThaliTest[550:651107] [CDVTimer][gesturehandler] 0.301957ms
,2016-03-03 14:57:16.704 ThaliTest[550:651107] [CDVTimer][TotalPluginStartup] 8.862972ms
,2016-03-03 14:57:23.218 ThaliTest[550:651107] Resetting plugins due to page load.
,2016-03-03 14:57:26.584 ThaliTest[550:651107] Finished load of: file:///var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/index.html
,2016-03-03 14:57:26.766 ThaliTest[550:651107] JXcore Cordova plugin initializing
,2016-03-03 14:57:26.766 ThaliTest[550:651321] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-03 14:57:38.440 ThaliTest[550:651321] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-03 14:57:38.440 ThaliTest[550:651321] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-03 14:57:38.441 ThaliTest[550:651321] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-03 14:57:38.442 ThaliTest[550:651321] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8902A58-CFF2-40F5-BCD1-D3A3A2E02461/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# 2. enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# 3. enqueueAtTop and run backwards

,# teardown

,ok 11 thirdPromise - first to run

,ok 12 thirdPromise - in resolve

,ok 13 secondPromise - second to run

,ok 14 secondPromise - in catch

,ok 15 firstPromise - third to run

,ok 16 firstPromise - in then

,ok 17 testing promises

,# setup

,# 4. mix enqueue and enqueueAtTop

,# teardown

,ok 18 fourth

,ok 19 fourth

,ok 20 second

,ok 21 secondPromise - in then

,ok 22 first

,ok 23 firstPromise - in catch

,ok 24 third

,ok 25 thirdPromise - in then

,ok 26 testingPromises

,# setup

,# 5. queues handled independently

,# teardown

,ok 27 all short operations completed before the long resolves

,# setup

,# 6. basic

,# teardown

,ok 28 sane

,# setup

,# 7. another

,# teardown

,ok 29 sane

,# setup

,# 8. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 30 specific error should be returned

,# setup

,ok 31 error should be null

,ok 32 error should be null

,# 9. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 33 specific error should be returned

,# setup

,ok 34 error should be null

,ok 35 error should be null

,# 10. should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 36 error should be null

,ok 37 error should be null

,ok 38 error should be null

,ok 39 error should be null

,# setup

,ok 40 error should be null

,ok 41 error should be null

,# 11. should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 42 error should be null

,ok 43 error should be null

,ok 44 error should be null

,ok 45 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 46 error should be null

,ok 47 error should be null

,# 12. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 48 error should be null

,ok 49 error should be null

,ok 50 error should be null

,ok 51 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 52 error should be null

,ok 53 error should be null

,# 13. should be able to call #stopAdvertisingAndListening many times

,# teardown

,ok 54 error should be null

,ok 55 error should be null

,ok 56 error should be null

,ok 57 error should be null

,# setup

,ok 58 error should be null

,ok 59 error should be null

,# 14. #start should fail if called twice in a row

,# teardown

,ok 60 first call should succeed

,ok 61 first call should succeed

,ok 62 specific error should be returned

,# setup

,ok 63 error should be null

,ok 64 error should be null

,# 15. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 65 called only once

,ok 66 discovery state matches

,ok 67 advertising state matches

,# setup

,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 68 error should be null

,ok 69 error should be null

,# 16. does not send duplicate availability changes

,# teardown

,ok 70 should be called once

,ok 71 should not have been called more than once

,# setup

,ok 72 error should be null

,ok 73 error should be null

,# 17. can get the network status

,# teardown

,ok 74 network status should have certain non-empty properties

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 18. wifi peer is marked unavailable if announcements stop

,# teardown

,ok 77 host address should match

,ok 78 port should match

,ok 79 host address should be null

,ok 80 port should should be null
,
,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 81 error should be null

,ok 82 error should be null

,# 19. can get the network status before starting

,# teardown

,ok 83 network status should have certain non-empty properties

,# setup

,# 20. #generatePreambleAndBeacons bad args

,# teardown

,ok 84 publicKeysToNotify cannot be null

,ok 85 ecdh for local device cannot be null

,ok 86 milliseconds cannot be less than 0

,ok 87 milliseconds cannot be 0

,ok 88 milliseconds cannot be greater than one_day

,# setup

,# 21. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 89 should be equal

,# setup

,# 22. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 90 should be equal

ok 91 should be equal

,ok 92 (unnamed assert)

,ok 93 should be equal

,# setup

,# 23. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 94 should throw

,# setup

,# 24. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 95 Preamble expiration must be a 64 bit integer

,# setup

,# 25. #parseBeacons expiration out of range lower

,# teardown

,ok 96 Expiration out of range

,# setup

,# 26. #parseBeacons expiration out of range lower

,# teardown

,ok 97 Expiration out of range

,# setup

,# 27. #parseBeacons no beacons returns null

,# teardown

,ok 98 should be equal

,# setup

,# 28. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 99 Malformed encrypted beacon key ID

,# setup

,# 29. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 100 should be equal

,# setup

,# 30. #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 101 should be equal

ok 102 should be equal

,# setup

,# 31. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 103 should be equal

,ok 104 should be equal

,# setup

,# 32. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 105 should be equal

ok 106 (unnamed assert)

,# setup

,# 33. #parseBeacons with beacons both for and not for the user

,# teardown

,ok 107 should be equal

ok 108 (unnamed assert)

,# setup

,# 34. Start and stop ThaliNotificationServer

,# teardown

,ok 109 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

ok 110 ThaliMobile.StopAdvertisingAndListening should be called once

,# setup

,# 35. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 111 StartUpdateAdvertisingAndListening should not be called

,ok 112 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 113 no error

,ok 114 should be 204

,# setup

,# 36. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 115 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 37. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 116 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 38. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 117 no error

,ok 118 should be 200

ok 119 should be equal

ok 120 should be equal

,ok 121 (unnamed assert)

,ok 122 no error

ok 123 should be 204

,# setup

,# 39. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 124 error should be null

,ok 125 should be 204

,# setup

,# 40. Make an HTTP request to /NotificationBeacons before calling start

,# teardown

,ok 126 should be 404

,# setup

,# 41. #testThaliPeerAction - test getters

,# teardown

,ok 127 getPeerIdentifier

,ok 128 getConnectionType

,ok 129 getActionType

,ok 130 getActionState

,# setup

,# 42. #testThaliPeerAction - start and kill

,# teardown

,ok 131 initial state

,ok 132 after start

,ok 133 after kill

,# setup

,# 43. #testThaliPeerAction - double start

,# teardown

,ok 134 should be equal

,# setup

,# 44. #testThaliPeerAction - start after kill

,# teardown

,ok 135 clean kill

,ok 136 should be equal

,# setup

,# 45. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 137 should not be equal

,# setup

,# 46. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 138 null arg

,ok 139 wrong arg type

,ok 140 wrong state

,# setup

,# 47. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 141 good enqueue

,ok 142 should be equal

,# setup

,# 48. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 143 good enqueue

,ok 144 2nd good enqueue

,ok 145 we are in the pool

,ok 146 We are out of the pool

,ok 147 Action was killed

,ok 148 The original kill was called too

,ok 149 second item is still in queue

,# setup

,# 49. compareBufferArrays

,# teardown

,ok 150 should throw

,ok 151 should throw

,ok 152 (unnamed assert)

,ok 153 (unnamed assert)

,ok 154 (unnamed assert)

,ok 155 (unnamed assert)

,ok 156 (unnamed assert)

,# setup

,# 50. Call start twice and get error

,# teardown

,ok 157 should throw

,# setup

,# 51. Start and make sure it runs

,# teardown

,# setup

,# 52. Make sure getTimeWhenRun is right after start

,# teardown

,ok 158 (unnamed assert)

,# setup

,# 53. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 159 should be equal

,# setup

,# 54. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 160 should be equal

,ok 161 should be equal

,ok 162 should throw

,# setup

,# 55. Test TransientState

,# teardown

,ok 163 should throw

,ok 164 should throw

,ok 165 should be equal

,ok 166 should be equal

,ok 167 should be equal

,ok 168 should be equal

,ok 169 (unnamed assert)

,ok 170 (unnamed assert)

,# setup

,# 56. No peers and empty database

,# teardown

,ok 171 verify failed

ok 172 constructor called once

,ok 173 constructor called with right args

,ok 174 match start arg

,ok 175 start called once

,ok 176 stop called once

,ok 177 stop after start

,# setup

,# 57. One peer and empty DB

,# teardown

,ok 178 verify failed

ok 179 constructor called once

,ok 180 constructor called with right args

,ok 181 match start arg

,ok 182 start called once

,ok 183 stop called once

,ok 184 stop after start

,# setup

,# 58. One peer with _Local set behind current seq

,# teardown

,ok 185 verify failed

,ok 186 constructor called once

ok 187 constructor called with right args

,ok 188 match start arg

,ok 189 start called once

,ok 190 stop called once

,ok 191 stop after start

,# setup

,# 59. One peer with _Local set equal to current seq

,# teardown

,ok 192 verify failed

ok 193 constructor called once

,ok 194 constructor called with right args

,ok 195 match start arg

,ok 196 start called once

,ok 197 stop called once

,ok 198 stop after start

,# setup

,# 60. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 199 verify failed

ok 200 constructor called once

ok 201 constructor called with right args

,ok 202 match start arg

,ok 203 start called once

,ok 204 stop called once

,ok 205 stop after start

,# setup

,# 61. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 206 verify failed

,ok 207 constructor called once

,ok 208 constructor called with right args

,ok 209 match start arg

,ok 210 start called once

,ok 211 stop called once

,ok 212 stop after start

,# setup

,# 62. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 213 verify failed

,ok 214 constructor called once

ok 215 constructor called with right args

,ok 216 match start arg

,ok 217 start called once

,ok 218 stop called once

,ok 219 stop after start

,# setup

,# 63. two peers with empty DB, update the doc

,# teardown

,ok 220 verify failed

,ok 221 constructor called once

ok 222 constructor called with right args

,ok 223 last start before stop

ok 224 empty first start

,ok 225 full second start

,ok 226 only 2 timers

,# setup

,# 64. add doc and make sure tokens refresh when they expire

,# teardown

,ok 227 verify failed

,ok 228 constructor called once

,ok 229 constructor called with right args

,ok 230 start before stop

,ok 231 We got at least 3 calls to start

,ok 232 at least 3

,ok 233 default 1

,ok 234 1 run

,ok 235 default 2

,ok 236 2 run

,ok 237 default 3

,# setup

,# 65. start and stop and start and stop

,# teardown

,ok 238 start out null

,ok 239 back to null

,ok 240 still null

,ok 241 verify failed

,ok 242 constructor called once

,ok 243 constructor called with right args

,ok 244 first start before first stop

,ok 245 first stop before second start

,ok 246 second start before second stop

,# setup

,# 66. two identical starts in a row

,# teardown

,ok 247 verify failed

,ok 248 constructor called once

,ok 249 constructor called with right args

,ok 250 (unnamed assert)

,# setup

,# 67. two different starts in a row

,# teardown

,ok 251 verify failed

,ok 252 constructor called once

ok 253 constructor called with right args

,ok 254 (unnamed assert)

,ok 255 (unnamed assert)

,# setup

,# 68. two stops and a start and two stops

,# teardown

,ok 256 verify failed

ok 257 constructor called once

,ok 258 constructor called with right args

ok 259 start before stop

,# setup

,# 69. we properly enqueue requests so no then needed

,# teardown

,ok 260 verify failed

ok 261 constructor called once

,ok 262 constructor called with right args

ok 263 start before stop

,# setup

,# 70. test calculateSeqPointKeyId

,# teardown

,ok 264 should be equal

,ok 265 should be equal

,# setup

,# 71. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 266 should be in started state

,# teardown

,ok 267 peer identifier should match

,ok 268 host address should match

,ok 269 port should match

,ok 270 host address should be null

,ok 271 port should should be null

,# setup

,ok 272 should not be in started state

,# 72. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 273 should be in started state

,# teardown

,ok 274 USN should have changed from the first one

,ok 275 when receiving the second byebye, the first USN should be already set

,# setup

,ok 276 should not be in started state

,# 73. messages with invalid location or USN should be ignored

,ok 277 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 278 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 279 should not have emitted with invalid USN

,# setup

,ok 280 should not be in started state

,# 74. verify that Thali-specific messages are filtered correctly

,ok 281 should be in started state

,# teardown

,ok 282 irrelevant messages should be ignored

,ok 283 relevant messages should not be ignored

,ok 284 messages from this device should be ignored

,# setup

,ok 285 should not be in started state

,# 75. #startListeningForAdvertisements should fail if start not called

,ok 286 should be in started state

,# teardown

,ok 287 specific error should be returned

,# setup

,ok 288 should not be in started state

,# 76. #startUpdateAdvertisingAndListening should fail if start not called

,ok 289 should be in started state

,# teardown

,ok 290 specific error should be returned

,# setup

,ok 291 should not be in started state

,# 77. #start should fail if called twice in a row

,ok 292 should be in started state

,# teardown

,ok 293 specific error should be received

,# setup

,ok 294 should not be in started state

,# 78. should not be started after stop is called

,ok 295 should be in started state

,# teardown

,ok 296 should not be started

ok 297 should not be listening

,ok 298 should not target listening

,ok 299 should not be advertising

,ok 300 should not target advertising

,# setup

,ok 301 should not be in started state

,# 79. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 302 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 303 specific error should be received

,# setup

,ok 304 should not be in started state

,# 80. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 305 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 306 specific error expected

,# setup

,ok 307 should not be in started state

,# 81. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 308 should be in started state

,# teardown

,ok 309 server should respond with code 200

,# setup

,ok 310 should not be in started state

,# 82. #stop can be called multiple times in a row

,ok 311 should be in started state

,# teardown

,ok 312 should be in stopped state

,ok 313 should still be in stopped state

,# setup

,ok 314 should not be in started state

,# 83. #startListeningForAdvertisements can be called multiple times in a row

,ok 315 should be in started state

,# teardown

,ok 316 should be in listening state

,ok 317 should still be in listening state

,# setup

,ok 318 should not be in started state

,# 84. #stopListeningForAdvertisements can be called multiple times in a row

,ok 319 should be in started state

,# teardown

,ok 320 should not be in listening state

,ok 321 should still not be in listening state

,# setup

,ok 322 should not be in started state

,# 85. #stopAdvertisingAndListening can be called multiple times in a row

,ok 323 should be in started state

,# teardown

,ok 324 should not be in advertising state

,ok 325 should still not be in advertising state

,# setup

,ok 326 should not be in started state

,# 86. functions are run from a queue in the right order

,ok 327 should be in started state

,# teardown

,ok 328 call order must match

,Tests Complete

,ok 329 should not be in started state

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
