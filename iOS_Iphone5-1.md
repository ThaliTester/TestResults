#### Test 62754403b276699_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F846F762-E685-41FF-9448-346643C57E69/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F846F762-E685-41FF-9448-346643C57E69/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50873"
,(lldb)     command script import "/tmp/F846F762-E685-41FF-9448-346643C57E69/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 18:15:02.089 ThaliTest[1062:2358914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/59701FEE-E820-43AA-B4B3-16DB3586CA59/Library/Cookies/Cookies.binarycookies
,2016-03-14 18:15:02.616 ThaliTest[1062:2358914] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 18:15:02.617 ThaliTest[1062:2358914] Multi-tasking -> Device: YES, App: YES
,2016-03-14 18:15:02.637 ThaliTest[1062:2358914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 18:15:04.592 ThaliTest[1062:2358914] Using UIWebView
,2016-03-14 18:15:04.597 ThaliTest[1062:2358914] [CDVTimer][handleopenurl] 0.301003ms
,2016-03-14 18:15:04.602 ThaliTest[1062:2358914] [CDVTimer][intentandnavigationfilter] 5.160034ms
2016-03-14 18:15:04.603 ThaliTest[1062:2358914] [CDVTimer][gesturehandler] 0.254989ms
2016-03-14 18:15:04.603 ThaliTest[1062:2358914] [CDVTimer][TotalPluginStartup] 6.782949ms
,2016-03-14 18:15:13.251 ThaliTest[1062:2358914] Resetting plugins due to page load.
,2016-03-14 18:15:16.894 ThaliTest[1062:2358914] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/index.html
,2016-03-14 18:15:17.096 ThaliTest[1062:2358914] JXcore Cordova plugin initializing
,2016-03-14 18:15:17.099 ThaliTest[1062:2359088] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 18:15:39.045 ThaliTest[1062:2359088] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-14 18:15:39.047 ThaliTest[1062:2359088] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 18:15:39.047 ThaliTest[1062:2359088] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 18:15:39.049 ThaliTest[1062:2359088] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5BB6B662-AB61-41B0-9E1D-E5F076B16D50/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. closeAll can close even when connections open

,# teardown

,ok 1 not possible to connect to the server anymore

,# setup

,# 2. closeAll with promise

,# teardown

,ok 2 not possible to connect to the server anymore

,# setup

,# 3. multiplex can send data

,# teardown

,ok 3 String should be length:200

,# setup

,# 4. enqueue and run in order

,# teardown

,ok 4 firstPromise setTimeout

,ok 5 firstPromise result

,ok 6 firstPromise testValue

,ok 7 secondPromise setTimeout

,ok 8 secondPromise result

,ok 9 secondPromise testValue

,ok 10 thirdPromise in promise

,ok 11 thirdPromise result

,ok 12 thirdPromise testValue

,# setup

,# 5. enqueueAtTop and run backwards

,# teardown

,ok 13 thirdPromise - first to run

,ok 14 thirdPromise - in resolve

,ok 15 secondPromise - second to run

,ok 16 secondPromise - in catch

,ok 17 firstPromise - third to run

,ok 18 firstPromise - in then

,ok 19 testing promises

,# setup

,# 6. mix enqueue and enqueueAtTop

,# teardown

,ok 20 fourth

,ok 21 fourth

,ok 22 second

,ok 23 secondPromise - in then

,ok 24 first

,ok 25 firstPromise - in catch

,ok 26 third

,ok 27 thirdPromise - in then

,ok 28 testingPromises

,# setup

,# 7. queues handled independently

,# teardown

,ok 29 all short operations completed before the long resolves

,# setup

,# 8. basic

,# teardown

,ok 30 sane

,# setup

,# 9. another

,# teardown

,ok 31 sane

,# setup

,# 10. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 32 specific error should be returned

,# setup

,ok 33 error should be null

,ok 34 error should be null

,# 11. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 35 specific error should be returned

,# setup

,ok 36 error should be null

,ok 37 error should be null

,# 12. should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 38 error should be null

,ok 39 error should be null

,ok 40 error should be null

,ok 41 error should be null

,# setup

,ok 42 error should be null

,ok 43 error should be null

,# 13. should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 44 error should be null

,ok 45 error should be null

,ok 46 error should be null

,ok 47 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 50 error should be null

ok 51 error should be null
,
,ok 52 error should be null

,ok 53 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 54 error should be null

,ok 55 error should be null

,# 15. should be able to call #stopAdvertisingAndListening many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,ok 58 error should be null

,ok 59 error should be null

,# setup

,ok 60 error should be null

,ok 61 error should be null

,# 16. #start should fail if called twice in a row

,# teardown

,ok 62 first call should succeed

,ok 63 first call should succeed

,ok 64 specific error should be returned

,# setup

,ok 65 error should be null

,ok 66 error should be null

,# 17. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 67 called only once

,ok 68 discovery state matches

ok 69 advertising state matches

,# setup

,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 70 error should be null

,ok 71 error should be null

,# 18. does not send duplicate availability changes

,# teardown

,ok 72 should be called once

,ok 73 should not have been called more than once

,# setup

,ok 74 error should be null

,ok 75 error should be null

,# 19. can get the network status

,# teardown

,ok 76 network status should have certain non-empty properties

,# setup

,ok 77 error should be null

,ok 78 error should be null

,# 20. wifi peer is marked unavailable if announcements stop

,# teardown

,ok 79 host address should match

,ok 80 port should match

,ok 81 host address should be null

ok 82 port should should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 83 error should be null

,ok 84 error should be null

,# 21. can get the network status before starting

,# teardown

,ok 85 network status should have certain non-empty properties

,# setup

,# 22. Test BEACONS_RETRIEVED_AND_PARSED locally

,# teardown

,ok 86 Response should be BEACONS_RETRIEVED_AND_PARSED

,ok 87 must return null after successful call

,# setup

,# 23. Test HTTP_BAD_RESPONSE locally

,# teardown

,ok 88 Response should be HTTP_BAD_RESPONSE

,ok 89 must return null after successful call

,# setup

,# 24. Test NETWORK_PROBLEM locally

,# teardown

,ok 90 Response should be NETWORK_PROBLEM

,ok 91 reject reason should be: Could not establish TCP connection

,# setup

,# 25. Test timeout locally

,# teardown

,ok 92 Should be NETWORK_PROBLEM caused by timeout

,ok 93 reject reason should be Could not establish TCP connection

,# setup

,# 26. Call the start two times

,# teardown

,ok 94 Call start once

,ok 95 Response should be BEACONS_RETRIEVED_AND_PARSED

,ok 96 must return null after successful call.

,# setup

,# 27. Call the kill before calling the start

,# teardown

,ok 97 Should be Killed

,ok 98 Start after killed

,# setup

,# 28. Call the kill immediately after the start

,# teardown

,ok 99 Should be KILLED

,ok 100 must return null after successful kill

,# setup

,# 29. Call the kill while waiting a response from the server

,# teardown

,ok 101 Should be KILLED

,ok 102 must return null after successful kill

,# setup

,# 30. Test to exceed the max content size locally

,# teardown

,ok 103 HTTP_BAD_RESPONSE should be response when content size is exceeded

,ok 104 must return null after successful call

,# setup

,# 31. #generatePreambleAndBeacons bad args

,# teardown

,ok 105 publicKeysToNotify cannot be null

,ok 106 ecdh for local device cannot be null

,ok 107 milliseconds cannot be less than 0

,ok 108 milliseconds cannot be 0

,ok 109 milliseconds cannot be greater than one_day

,# setup

,# 32. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 110 should be equal

,# setup

,# 33. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 111 should be equal

,ok 112 should be equal

,ok 113 (unnamed assert)

,ok 114 should be equal

,# setup

,# 34. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 115 should throw

,# setup

,# 35. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 116 Preamble expiration must be a 64 bit integer

,# setup

,# 36. #parseBeacons expiration out of range lower

,# teardown

,ok 117 Expiration out of range

,# setup

,# 37. #parseBeacons expiration out of range lower

,# teardown

,ok 118 Expiration out of range

,# setup

,# 38. #parseBeacons no beacons returns null

,# teardown

,ok 119 should be equal

,# setup

,# 39. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 120 Malformed encrypted beacon key ID

,# setup

,# 40. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 121 should be equal

,# setup

,# 41. #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 122 should be equal

,ok 123 should be equal

,# setup

,# 42. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 124 should be equal

,ok 125 should be equal

,# setup

,# 43. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 126 should be equal

,ok 127 (unnamed assert)

,# setup

,# 44. #parseBeacons with beacons both for and not for the user

,# teardown

,ok 128 should be equal

,ok 129 (unnamed assert)

,# setup

,# 45. Start and stop ThaliNotificationServer

,# teardown

,ok 130 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

,ok 131 ThaliMobile.StopAdvertisingAndListening should be called once

,# setup

,# 46. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 132 StartUpdateAdvertisingAndListening should not be called

,ok 133 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 134 no error

,ok 135 should be 204

,# setup

,# 47. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 136 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 48. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 137 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 49. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 138 no error

ok 139 should be 200

,ok 140 should be equal

,ok 141 should be equal

,ok 142 (unnamed assert)

,ok 143 no error

,ok 144 should be 204

,# setup

,# 50. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 145 error should be null

,ok 146 should be 204

,# setup

,# 51. Make an HTTP request to /NotificationBeacons before calling start

,# teardown

,ok 147 should be 404

,# setup

,# 52. #testThaliPeerAction - test getters

,# teardown

,ok 148 getPeerIdentifier

,ok 149 getConnectionType

,ok 150 getActionType

,ok 151 getActionState

,# setup

,# 53. #testThaliPeerAction - start and kill

,# teardown

,ok 152 initial state

,ok 153 after start

,ok 154 after kill

,# setup

,# 54. #testThaliPeerAction - double start

,# teardown

,ok 155 should be equal

,# setup

,# 55. #testThaliPeerAction - start after kill

,# teardown

,ok 156 clean kill

,ok 157 should be equal

,# setup

,# 56. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 158 should not be equal

,# setup

,# 57. Test PeerConnectionInformation basics

,# teardown

,ok 159 getHostAddress works

,ok 160 getPortNumber works

,ok 161 getSuggestedTCPTimeout works

,# setup

,# 58. Test PeerDictionary basic functionality

,# teardown

,ok 162 Entry counter must be 1

,ok 163 Size must be 1

,ok 164 Entry counter must be 2

,ok 165 Size must be 2

,ok 166 Entry2 should not be found

,ok 167 Size must be 1

,ok 168 Size must be 0

,ok 169 entry not found must be thrown

,# setup

,# 59. Test PeerDictionary with multiple entries.

,# teardown

,ok 170 Size must be100

,ok 171 Entries between 20 and MAXSIZE + 20 should exist

,ok 172 WAITING state entry should not be removed

,# setup

,# 60. RESOLVED entries are removed before WAITING state entry.

,# teardown

,ok 173 Entries between 6 and MAXSIZE + 4 should exist

ok 174 Size should be MAXSIZE

,ok 175 Size should be MAXSIZE+6

,# setup

,# 61. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

,# teardown

,ok 176 WAITING state entry should not be removed

,ok 177 Waiting entries between 6 and MAXSIZE + 4 should exist

,ok 178 Size should be MAXSIZE

,ok 179 entryCounter should be MAXSIZE+6

,# setup

,# 62. When CONTROLLED_BY_POOL entry is removed and kill is called.

,# teardown

,ok 180 Kill should be called once

,ok 181 Size should be 100

,# setup

,# 63. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 182 null arg

,ok 183 wrong arg type

,ok 184 wrong state

,# setup

,# 64. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 185 good enqueue

,ok 186 should be equal

,# setup

,# 65. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 187 good enqueue

,ok 188 2nd good enqueue

,ok 189 we are in the pool

,ok 190 We are out of the pool

,ok 191 Action was killed

,ok 192 The original kill was called too

,ok 193 second item is still in queue

,# setup

,# 66. compareBufferArrays

,# teardown

,ok 194 should throw

,ok 195 should throw

,ok 196 (unnamed assert)

,ok 197 (unnamed assert)

,ok 198 (unnamed assert)

,ok 199 (unnamed assert)

,ok 200 (unnamed assert)

,# setup

,# 67. Call start twice and get error

,# teardown

,ok 201 should throw

,# setup

,# 68. Start and make sure it runs

,# teardown

,# setup

,# 69. Make sure getTimeWhenRun is right after start

,# teardown

,ok 202 (unnamed assert)

,# setup

,# 70. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 203 should be equal

,# setup

,# 71. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 204 should be equal

,ok 205 should be equal

,ok 206 should throw

,# setup

,# 72. Test TransientState

,# teardown

,ok 207 should throw

,ok 208 should throw

,ok 209 should be equal

,ok 210 should be equal

,ok 211 should be equal

,ok 212 should be equal

,ok 213 (unnamed assert)

,ok 214 (unnamed assert)

,# setup

,# 73. No peers and empty database

,# teardown

,ok 215 verify failed

,ok 216 constructor called once

,ok 217 constructor called with right args

,ok 218 match start arg

,ok 219 start called once

,ok 220 stop called once

,ok 221 stop after start

,# setup

,# 74. One peer and empty DB

,# teardown

,ok 222 verify failed

,ok 223 constructor called once

,ok 224 constructor called with right args

,ok 225 match start arg

,ok 226 start called once

,ok 227 stop called once

,ok 228 stop after start

,# setup

,# 75. One peer with _Local set behind current seq

,# teardown

,ok 229 verify failed

,ok 230 constructor called once

,ok 231 constructor called with right args

,ok 232 match start arg

,ok 233 start called once

,ok 234 stop called once

,ok 235 stop after start

,# setup

,# 76. One peer with _Local set equal to current seq

,# teardown

,ok 236 verify failed

,ok 237 constructor called once

,ok 238 constructor called with right args

,ok 239 match start arg

,ok 240 start called once

,ok 241 stop called once

,ok 242 stop after start

,# setup

,# 77. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 243 verify failed

,ok 244 constructor called once

,ok 245 constructor called with right args

,ok 246 match start arg

,ok 247 start called once

,ok 248 stop called once

,ok 249 stop after start

,# setup

,# 78. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 250 verify failed

,ok 251 constructor called once

,ok 252 constructor called with right args

,ok 253 match start arg

,ok 254 start called once

,ok 255 stop called once

,ok 256 stop after start

,# setup

,# 79. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 257 verify failed

,ok 258 constructor called once

,ok 259 constructor called with right args

,ok 260 match start arg

,ok 261 start called once

,ok 262 stop called once

,ok 263 stop after start

,# setup

,# 80. two peers with empty DB, update the doc

,# teardown

,ok 264 verify failed

,ok 265 constructor called once

,ok 266 constructor called with right args

,ok 267 last start before stop

,ok 268 empty first start

,ok 269 full second start

,ok 270 only 2 timers

,# setup

,# 81. add doc and make sure tokens refresh when they expire

,# teardown

,ok 271 verify failed

,ok 272 constructor called once

,ok 273 constructor called with right args

,ok 274 start before stop

,ok 275 We got at least 3 calls to start

,ok 276 at least 3

,ok 277 default 1

,ok 278 1 run

,ok 279 default 2

,ok 280 2 run

,ok 281 default 3

,# setup

,# 82. start and stop and start and stop

,# teardown

,ok 282 start out null

,ok 283 back to null

,ok 284 still null

,ok 285 verify failed

,ok 286 constructor called once

,ok 287 constructor called with right args

,ok 288 first start before first stop

,ok 289 first stop before second start

,ok 290 second start before second stop

,# setup

,# 83. two identical starts in a row

,# teardown

,ok 291 verify failed

,ok 292 constructor called once

,ok 293 constructor called with right args

,ok 294 (unnamed assert)

,# setup

,# 84. two different starts in a row

,# teardown

,ok 295 verify failed

,ok 296 constructor called once

,ok 297 constructor called with right args

,ok 298 (unnamed assert)

,ok 299 (unnamed assert)

,# setup

,# 85. two stops and a start and two stops

,# teardown

,ok 300 verify failed

,ok 301 constructor called once

,ok 302 constructor called with right args

,ok 303 start before stop

,# setup

,# 86. we properly enqueue requests so no then needed

,# teardown

,ok 304 verify failed

,ok 305 constructor called once

,ok 306 constructor called with right args

,ok 307 start before stop

,# setup

,# 87. test calculateSeqPointKeyId

,# teardown

,ok 308 should be equal

,ok 309 should be equal

,# setup

,# 88. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 310 should be in started state

,# teardown

,ok 311 peer identifier should match

,ok 312 host address should match

,ok 313 port should match

,ok 314 host address should be null

,ok 315 port should should be null

,# setup

,ok 316 should not be in started state

,# 89. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 317 should be in started state

,# teardown

,ok 318 USN should have changed from the first one

,ok 319 when receiving the second byebye, the first USN should be already set

,# setup

,ok 320 should not be in started state

,# 90. messages with invalid location or USN should be ignored

,ok 321 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

ok 322 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 323 should not have emitted with invalid USN

,# setup

,ok 324 should not be in started state

,# 91. verify that Thali-specific messages are filtered correctly

,ok 325 should be in started state

,# teardown

,ok 326 irrelevant messages should be ignored

,ok 327 relevant messages should not be ignored

,ok 328 messages from this device should be ignored

,# setup

,ok 329 should not be in started state

,# 92. #startListeningForAdvertisements should fail if start not called

,ok 330 should be in started state

,# teardown

,ok 331 specific error should be returned

,# setup

,ok 332 should not be in started state

,# 93. #startUpdateAdvertisingAndListening should fail if start not called

,ok 333 should be in started state

,# teardown

,ok 334 specific error should be returned

,# setup

,ok 335 should not be in started state

,# 94. #start should fail if called twice in a row

,ok 336 should be in started state

,# teardown

,ok 337 specific error should be received

,# setup

,ok 338 should not be in started state

,# 95. should not be started after stop is called

,ok 339 should be in started state

,# teardown

,ok 340 should not be started

,ok 341 should not be listening

,ok 342 should not target listening

,ok 343 should not be advertising

,ok 344 should not target advertising

,# setup

,ok 345 should not be in started state

,# 96. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 346 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 347 specific error should be received

,# setup

,ok 348 should not be in started state

,# 97. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 349 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 350 specific error expected

,# setup

,ok 351 should not be in started state

,# 98. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 352 should be in started state

,# teardown

,ok 353 server should respond with code 200

,# setup

,ok 354 should not be in started state

,# 99. #stop can be called multiple times in a row

,ok 355 should be in started state

,# teardown

,ok 356 should be in stopped state

,ok 357 should still be in stopped state

,# setup

,ok 358 should not be in started state

,# 100. #startListeningForAdvertisements can be called multiple times in a row

,ok 359 should be in started state

,# teardown

,ok 360 should be in listening state

,ok 361 should still be in listening state

,# setup

,ok 362 should not be in started state

,# 101. #stopListeningForAdvertisements can be called multiple times in a row

,ok 363 should be in started state

,# teardown

,ok 364 should not be in listening state

,ok 365 should still not be in listening state

,# setup

,ok 366 should not be in started state

,# 102. #stopAdvertisingAndListening can be called multiple times in a row

,ok 367 should be in started state

,# teardown

,ok 368 should not be in advertising state

,ok 369 should still not be in advertising state

,# setup

,ok 370 should not be in started state

,# 103. functions are run from a queue in the right order

,ok 371 should be in started state

,# teardown

,ok 372 call order must match

,# setup

,ok 373 should not be in started state

,# 104. #ThaliPeerPoolDefault - single action

,# teardown

,ok 374 is an agent

,ok 375 enqueue is fine

,ok 376 Everything should be off the queue

,# setup

,# 105. #ThaliPeerPoolDefault - multiple actions

,# teardown

,ok 377 is an agent

,ok 378 first enqueue is fine

,ok 379 is an agent

,ok 380 second enqueue is fine

,ok 381 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.

ok 382 Queue is empty
,
,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****
,
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
