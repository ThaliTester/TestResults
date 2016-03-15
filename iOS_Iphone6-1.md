#### Test 62947189e430ee9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9A982B25-F2C0-4D44-9DB9-BC799C2C4F40/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9A982B25-F2C0-4D44-9DB9-BC799C2C4F40/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49841"
,(lldb)     command script import "/tmp/9A982B25-F2C0-4D44-9DB9-BC799C2C4F40/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 19:11:21.544 ThaliTest[1453:2333239] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/79BC81D4-8F50-4DB4-ACE4-A88E4DE277DF/Library/Cookies/Cookies.binarycookies
,2016-03-15 19:11:21.911 ThaliTest[1453:2333239] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 19:11:21.913 ThaliTest[1453:2333239] Multi-tasking -> Device: YES, App: YES
,2016-03-15 19:11:21.937 ThaliTest[1453:2333239] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 19:11:23.913 ThaliTest[1453:2333239] Using UIWebView
,2016-03-15 19:11:23.920 ThaliTest[1453:2333239] [CDVTimer][handleopenurl] 0.537038ms
,2016-03-15 19:11:23.928 ThaliTest[1453:2333239] [CDVTimer][intentandnavigationfilter] 7.299006ms
2016-03-15 19:11:23.929 ThaliTest[1453:2333239] [CDVTimer][gesturehandler] 0.373006ms
2016-03-15 19:11:23.929 ThaliTest[1453:2333239] [CDVTimer][TotalPluginStartup] 9.958029ms
,2016-03-15 19:11:30.892 ThaliTest[1453:2333239] Resetting plugins due to page load.
,2016-03-15 19:11:34.290 ThaliTest[1453:2333239] Finished load of: file:///var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/index.html
,2016-03-15 19:11:34.516 ThaliTest[1453:2333239] JXcore Cordova plugin initializing
2016-03-15 19:11:34.516 ThaliTest[1453:2333451] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 19:11:47.149 ThaliTest[1453:2333451] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 19:11:47.149 ThaliTest[1453:2333451] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 19:11:47.150 ThaliTest[1453:2333451] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 19:11:47.150 ThaliTest[1453:2333451] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CEADE91F-9C2F-419E-A341-DF3C3C966A0C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. calling createNativeListener directly rejects

,# teardown

,ok 1 Should throw

,# setup

,# 2. emits incomingConnectionState

,# teardown

,ok 2 initial connection state should be CONNECTED

,ok 3 final connection state should be DISCONNECTED

,# setup

,# 3. emits routerPortConnectionFailed

,# teardown

,ok 4 routerPortConnectionFailed is emitted

,# setup

,# 4. native server connections all up

,# teardown

,ok 5 Send/recvd #1 should be equal length

,ok 6 Send/recvd #1 should be same

,ok 7 Send/recvd #2 should be equal length

,ok 8 Send/recvd #2 should be same

,ok 9 Should be exactly 2 client sockets

,# setup

,# 5. native server - closing incoming stream cleans outgoing socket

,# teardown

,ok 10 socket shouldn't close until after stream

,ok 11 incoming remains open

,# setup

,# 6. native server - closing incoming connection cleans outgoing socket

,# teardown

,ok 12 we should not have gotten an error

,ok 13 socket shouldn't close until after incoming

,ok 14 incoming is cleaned up

,# setup

,# 7. native server - closing outgoing socket cleans associated mux stream

,# teardown

,ok 15 stream was closed

,ok 16 incoming should survive

,ok 17 mux should have no streams

,# setup

,# 8. native server - closing the whole server cleans everything up

,# teardown

,ok 18 we should not have gotten an error

,ok 19 Buffers are identical

,ok 20 native server is nulled out

,ok 21 native server should be closed

,ok 22 incoming has been removed

,ok 23 Incoming should be done

,ok 24 The mux object should be closed

,ok 25 The mux stream should be closed

,# setup

,# 9. native server - we can get a ton of connections and data through and still clean up the server completely

,# teardown

,ok 26 native server is nulled out

ok 27 native server should be closed

,ok 28 incoming has been removed

,# setup

,# 10. native server - simulate mux failure, make sure everything is cleaned up

,# teardown

,ok 29 we should not have gotten an error

,ok 30 Buffers are identical

,ok 31 server should be fine

,ok 32 server should be open

,ok 33 incoming has been removed

,ok 34 The mux object should be closed

,ok 35 The mux stream should be closed

,# setup

,# 11. native server - timing out the incoming connection cleans everything up

,# teardown

,ok 36 we should not have gotten an error

,ok 37 Buffers are identical

,ok 38 server should be fine

,ok 39 server should be open

,ok 40 incoming has been removed

,ok 41 The mux object should be closed

,ok 42 The mux stream should be closed

,# setup

,# 12. closeAll can close even when connections open

,# teardown

,ok 43 not possible to connect to the server anymore

,# setup

,# 13. closeAll with promise

,# teardown

,ok 44 not possible to connect to the server anymore

,# setup

,# 14. multiplex can send data

,# teardown

,ok 45 String should be length:200

,# setup

,# 15. enqueue and run in order

,# teardown

,ok 46 firstPromise setTimeout

,ok 47 firstPromise result

,ok 48 firstPromise testValue

,ok 49 secondPromise setTimeout

,ok 50 secondPromise result

,ok 51 secondPromise testValue

,ok 52 thirdPromise in promise

,ok 53 thirdPromise result

,ok 54 thirdPromise testValue

,# setup

,# 16. enqueueAtTop and run backwards

,# teardown

,ok 55 thirdPromise - first to run

,ok 56 thirdPromise - in resolve

,ok 57 secondPromise - second to run

,ok 58 secondPromise - in catch

,ok 59 firstPromise - third to run

,ok 60 firstPromise - in then

,ok 61 testing promises

,# setup

,# 17. mix enqueue and enqueueAtTop

,# teardown

,ok 62 fourth

,ok 63 fourth

,ok 64 second

,ok 65 secondPromise - in then

,ok 66 first

,ok 67 firstPromise - in catch

,ok 68 third

,ok 69 thirdPromise - in then

,ok 70 testingPromises

,# setup

,# 18. queues handled independently

,# teardown

,ok 71 all short operations completed before the long resolves

,# setup

,# 19. basic

,# teardown

,ok 72 sane

,# setup

,# 20. another

,# teardown

,ok 73 sane

,# setup

,# 21. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 74 specific error should be returned

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 22. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 77 specific error should be returned

,# setup

,ok 78 error should be null

,ok 79 error should be null

,# 23. should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 80 error should be null

,ok 81 error should be null

,ok 82 error should be null

,ok 83 error should be null

,# setup

,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 86 error should be null

,ok 87 error should be null

,ok 88 error should be null

,ok 89 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 92 error should be null

,ok 93 error should be null

,ok 94 error should be null

,ok 95 error should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,ok 98 error should be null

,ok 99 error should be null

,ok 100 error should be null

,ok 101 error should be null

,# setup

,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,ok 109 called only once

,ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 112 error should be null

,ok 113 error should be null

,# 29. does not send duplicate availability changes

,# teardown

,ok 114 should be called once

,ok 115 should not have been called more than once

,# setup

,ok 116 error should be null

,ok 117 error should be null

,# 30. can get the network status

,# teardown

,ok 118 network status should have certain non-empty properties

,# setup

,ok 119 error should be null

,ok 120 error should be null

,# 31. wifi peer is marked unavailable if announcements stop

,# teardown

,ok 121 host address should match

,ok 122 port should match

,ok 123 host address should be null

,ok 124 port should should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 125 error should be null

,ok 126 error should be null

,# 32. can get the network status before starting

,# teardown

,ok 127 network status should have certain non-empty properties

,# setup

,# 33. #generatePreambleAndBeacons bad args

,# teardown

,ok 128 publicKeysToNotify cannot be null

,ok 129 ecdh for local device cannot be null

,ok 130 milliseconds cannot be less than 0

,ok 131 milliseconds cannot be 0

,ok 132 milliseconds cannot be greater than one_day

,# setup

,# 34. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 133 should be equal

,# setup

,# 35. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 134 should be equal

ok 135 should be equal

,ok 136 (unnamed assert)

,ok 137 should be equal

,# setup

,# 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 138 should throw

,# setup

,# 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 139 Preamble expiration must be a 64 bit integer

,# setup

,# 38. #parseBeacons expiration out of range lower

,# teardown

,ok 140 Expiration out of range

,# setup

,# 39. #parseBeacons expiration out of range lower

,# teardown

,ok 141 Expiration out of range

,# setup

,# 40. #parseBeacons no beacons returns null

,# teardown

,ok 142 should be equal

,# setup

,# 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 143 Malformed encrypted beacon key ID

,# setup

,# 42. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 144 should be equal

,# setup

,# 43. #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 145 should be equal

ok 146 should be equal
,
,# setup

,# 44. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 147 should be equal

ok 148 should be equal

,# setup

,# 45. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 149 should be equal

ok 150 (unnamed assert)

,# setup

,# 46. #parseBeacons with beacons both for and not for the user

,# teardown

,ok 151 should be equal

ok 152 (unnamed assert)

,# setup

,# 47. Start and stop ThaliNotificationServer

,# teardown

,ok 153 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

ok 154 ThaliMobile.StopAdvertisingAndListening should be called once

,# setup

,# 48. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 155 StartUpdateAdvertisingAndListening should not be called

,ok 156 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 157 no error

,ok 158 should be 204

,# setup

,# 49. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 159 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 50. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 160 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 51. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 161 no error

ok 162 should be 200

,ok 163 should be equal

,ok 164 should be equal

,ok 165 (unnamed assert)

,ok 166 no error

,ok 167 should be 204

,# setup

,# 52. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 168 error should be null

,ok 169 should be 204

,# setup

,# 53. Make an HTTP request to /NotificationBeacons before calling start

,# teardown

,ok 170 should be 404

,# setup

,# 54. #testThaliPeerAction - test getters

,# teardown

,ok 171 getPeerIdentifier

,ok 172 getConnectionType

,ok 173 getActionType

,ok 174 getActionState

,# setup

,# 55. #testThaliPeerAction - start and kill

,# teardown

,ok 175 initial state

,ok 176 after start

,ok 177 after kill

,# setup

,# 56. #testThaliPeerAction - double start

,# teardown

,ok 178 should be equal

,# setup

,# 57. #testThaliPeerAction - start after kill

,# teardown

,ok 179 clean kill

,ok 180 should be equal

,# setup

,# 58. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 181 should not be equal

,# setup

,# 59. Test PeerConnectionInformation basics

,# teardown

,ok 182 getHostAddress works

,ok 183 getPortNumber works

,ok 184 getSuggestedTCPTimeout works

,# setup

,# 60. Test PeerDictionary basic functionality

,# teardown

,ok 185 Entry counter must be 1

,ok 186 Size must be 1

,ok 187 Entry counter must be 2

,ok 188 Size must be 2

,ok 189 Entry2 should not be found

,ok 190 Size must be 1

,ok 191 Size must be 0

,ok 192 entry not found must be thrown

,# setup

,# 61. Test PeerDictionary with multiple entries.

,# teardown

,ok 193 Size must be100

,ok 194 Entries between 20 and MAXSIZE + 20 should exist

,ok 195 WAITING state entry should not be removed

,# setup

,# 62. RESOLVED entries are removed before WAITING state entry.

,# teardown

,ok 196 Entries between 6 and MAXSIZE + 4 should exist

,ok 197 Size should be MAXSIZE

ok 198 Size should be MAXSIZE+6

,# setup

,# 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

,# teardown

,ok 199 WAITING state entry should not be removed

,ok 200 Waiting entries between 6 and MAXSIZE + 4 should exist

,ok 201 Size should be MAXSIZE

,ok 202 entryCounter should be MAXSIZE+6

,# setup

,# 64. When CONTROLLED_BY_POOL entry is removed and kill is called.

,# teardown

,ok 203 Kill should be called once

ok 204 Size should be 100

,# setup

,# 65. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 205 null arg

,ok 206 wrong arg type

,ok 207 wrong state

,# setup

,# 66. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 208 good enqueue

,ok 209 should be equal

,# setup

,# 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 210 good enqueue

,ok 211 2nd good enqueue

,ok 212 we are in the pool

,ok 213 We are out of the pool

,ok 214 Action was killed

,ok 215 The original kill was called too

,ok 216 second item is still in queue

,# setup

,# 68. compareBufferArrays

,# teardown

,ok 217 should throw

,ok 218 should throw

,ok 219 (unnamed assert)

,ok 220 (unnamed assert)

,ok 221 (unnamed assert)

,ok 222 (unnamed assert)

,ok 223 (unnamed assert)

,# setup

,# 69. Call start twice and get error

,# teardown

,ok 224 should throw

,# setup

,# 70. Start and make sure it runs

,# teardown

,# setup

,# 71. Make sure getTimeWhenRun is right after start

,# teardown

,ok 225 (unnamed assert)

,# setup

,# 72. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 226 should be equal

,# setup

,# 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 227 should be equal

,ok 228 should be equal

,ok 229 should throw

,# setup

,# 74. Test TransientState

,# teardown

,ok 230 should throw

,ok 231 should throw

,ok 232 should be equal

,ok 233 should be equal

,ok 234 should be equal

,ok 235 should be equal

,ok 236 (unnamed assert)

,ok 237 (unnamed assert)

,# setup

,# 75. No peers and empty database

,# teardown

,ok 238 verify failed

,ok 239 constructor called once

,ok 240 constructor called with right args

,ok 241 match start arg

,ok 242 start called once

,ok 243 stop called once

,ok 244 stop after start

,# setup

,# 76. One peer and empty DB

,# teardown

,ok 245 verify failed

ok 246 constructor called once

,ok 247 constructor called with right args

,ok 248 match start arg

,ok 249 start called once

,ok 250 stop called once

,ok 251 stop after start

,# setup

,# 77. One peer with _Local set behind current seq

,# teardown

,ok 252 verify failed

ok 253 constructor called once

,ok 254 constructor called with right args

,ok 255 match start arg

,ok 256 start called once

,ok 257 stop called once

,ok 258 stop after start

,# setup

,# 78. One peer with _Local set equal to current seq

,# teardown

,ok 259 verify failed

,ok 260 constructor called once

,ok 261 constructor called with right args

,ok 262 match start arg

,ok 263 start called once

,ok 264 stop called once

,ok 265 stop after start

,# setup

,# 79. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 266 verify failed

ok 267 constructor called once

,ok 268 constructor called with right args

,ok 269 match start arg

,ok 270 start called once

,ok 271 stop called once

,ok 272 stop after start

,# setup

,# 80. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 273 verify failed

ok 274 constructor called once

,ok 275 constructor called with right args

,ok 276 match start arg

,ok 277 start called once

,ok 278 stop called once

,ok 279 stop after start

,# setup

,# 81. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 280 verify failed

ok 281 constructor called once
,
,ok 282 constructor called with right args

,ok 283 match start arg

,ok 284 start called once

,ok 285 stop called once

,ok 286 stop after start

,# setup

,# 82. two peers with empty DB, update the doc

,# teardown

,ok 287 verify failed

ok 288 constructor called once

,ok 289 constructor called with right args

,ok 290 last start before stop

,ok 291 empty first start

,ok 292 full second start

,ok 293 only 2 timers

,# setup

,# 83. add doc and make sure tokens refresh when they expire

,# teardown

,ok 294 verify failed

,ok 295 constructor called once

,ok 296 constructor called with right args

,ok 297 start before stop

,ok 298 We got at least 3 calls to start

,ok 299 at least 3

,ok 300 default 1

,ok 301 1 run

,ok 302 default 2

,ok 303 2 run

,ok 304 default 3

,# setup

,# 84. start and stop and start and stop

,# teardown

,ok 305 start out null

,ok 306 back to null

,ok 307 still null

,ok 308 verify failed

,ok 309 constructor called once

,ok 310 constructor called with right args

,ok 311 first start before first stop

,ok 312 first stop before second start

,ok 313 second start before second stop

,# setup

,# 85. two identical starts in a row

,# teardown

,ok 314 verify failed

ok 315 constructor called once

,ok 316 constructor called with right args

ok 317 (unnamed assert)

,# setup

,# 86. two different starts in a row

,# teardown

,
ok 318 verify failed

ok 319 constructor called once
,ok 320 constructor called with right args

,ok 321 (unnamed assert)

,ok 322 (unnamed assert)

,# setup

,# 87. two stops and a start and two stops

,# teardown

,ok 323 verify failed

ok 324 constructor called once

,ok 325 constructor called with right args

,ok 326 start before stop

,# setup

,# 88. we properly enqueue requests so no then needed

,# teardown

,ok 327 verify failed

ok 328 constructor called once

,ok 329 constructor called with right args

,ok 330 start before stop

,# setup

,# 89. test calculateSeqPointKeyId

,# teardown

,ok 331 should be equal

,ok 332 should be equal

,# setup

,# 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 333 should be in started state

,# teardown

,ok 334 peer identifier should match

,ok 335 host address should match

,ok 336 port should match

,ok 337 host address should be null

,ok 338 port should should be null

,# setup

,ok 339 should not be in started state

,# 91. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 340 should be in started state

,# teardown

,ok 341 USN should have changed from the first one

,ok 342 when receiving the second byebye, the first USN should be already set

,# setup

,ok 343 should not be in started state

,# 92. messages with invalid location or USN should be ignored

,ok 344 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 345 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 346 should not have emitted with invalid USN

,# setup

,ok 347 should not be in started state

,# 93. verify that Thali-specific messages are filtered correctly

,ok 348 should be in started state

,# teardown

,ok 349 irrelevant messages should be ignored

,ok 350 relevant messages should not be ignored

,ok 351 messages from this device should be ignored

,# setup

,ok 352 should not be in started state

,# 94. #startListeningForAdvertisements should fail if start not called

,ok 353 should be in started state

,# teardown

,ok 354 specific error should be returned

,# setup

,ok 355 should not be in started state

,# 95. #startUpdateAdvertisingAndListening should fail if start not called

,ok 356 should be in started state

,# teardown

,ok 357 specific error should be returned

,# setup

,ok 358 should not be in started state

,# 96. #start should fail if called twice in a row

,ok 359 should be in started state

,# teardown

,ok 360 specific error should be received

,# setup

,ok 361 should not be in started state

,# 97. should not be started after stop is called

,ok 362 should be in started state

,# teardown

,ok 363 should not be started

,ok 364 should not be listening

,ok 365 should not target listening

,ok 366 should not be advertising

,ok 367 should not target advertising

,# setup

,ok 368 should not be in started state

,# 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 369 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 370 specific error should be received

,# setup

,ok 371 should not be in started state

,# 99. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 372 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 373 specific error expected

,# setup

,ok 374 should not be in started state

,# 100. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 375 should be in started state

,# teardown

,ok 376 server should respond with code 200

,# setup

,ok 377 should not be in started state

,# 101. #stop can be called multiple times in a row

,ok 378 should be in started state

,# teardown

,ok 379 should be in stopped state

,ok 380 should still be in stopped state

,# setup

,ok 381 should not be in started state

,# 102. #startListeningForAdvertisements can be called multiple times in a row

,ok 382 should be in started state

,# teardown

,ok 383 should be in listening state

,ok 384 should still be in listening state

,# setup

,ok 385 should not be in started state

,# 103. #stopListeningForAdvertisements can be called multiple times in a row

,ok 386 should be in started state

,# teardown

,ok 387 should not be in listening state

,ok 388 should still not be in listening state

,# setup

,ok 389 should not be in started state

,# 104. #stopAdvertisingAndListening can be called multiple times in a row

,ok 390 should be in started state

,# teardown

,ok 391 should not be in advertising state

,ok 392 should still not be in advertising state

,# setup

,ok 393 should not be in started state

,# 105. functions are run from a queue in the right order

,ok 394 should be in started state

,# teardown

,ok 395 call order must match

,# setup

,ok 396 should not be in started state

,# 106. #ThaliPeerPoolDefault - single action

,# teardown

,ok 397 is an agent

,ok 398 enqueue is fine

,ok 399 Everything should be off the queue

,# setup

,# 107. #ThaliPeerPoolDefault - multiple actions

,# teardown

,ok 400 is an agent

,ok 401 first enqueue is fine

,ok 402 is an agent

,ok 403 second enqueue is fine

,ok 404 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.

,ok 405 Queue is empty

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
