#### Test 62509094cfda267_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C91C0B55-BC95-40AD-BF1C-3D1A08CEAFDA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C91C0B55-BC95-40AD-BF1C-3D1A08CEAFDA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094cfda267/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50291"
,(lldb)     command script import "/tmp/C91C0B55-BC95-40AD-BF1C-3D1A08CEAFDA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 09:51:07.587 ThaliTest[1350:2172271] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/066F4A59-1808-488B-97DE-4BA8F7FA61A7/Library/Cookies/Cookies.binarycookies
,2016-03-14 09:51:07.930 ThaliTest[1350:2172271] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 09:51:07.931 ThaliTest[1350:2172271] Multi-tasking -> Device: YES, App: YES
,2016-03-14 09:51:07.947 ThaliTest[1350:2172271] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 09:51:09.764 ThaliTest[1350:2172271] Using UIWebView
,2016-03-14 09:51:09.770 ThaliTest[1350:2172271] [CDVTimer][handleopenurl] 0.408053ms
,2016-03-14 09:51:09.777 ThaliTest[1350:2172271] [CDVTimer][intentandnavigationfilter] 6.690979ms
,2016-03-14 09:51:09.778 ThaliTest[1350:2172271] [CDVTimer][gesturehandler] 0.322998ms
,2016-03-14 09:51:09.778 ThaliTest[1350:2172271] [CDVTimer][TotalPluginStartup] 9.112000ms
,2016-03-14 09:51:16.610 ThaliTest[1350:2172271] Resetting plugins due to page load.
,2016-03-14 09:51:20.288 ThaliTest[1350:2172271] Finished load of: file:///var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/index.html
,2016-03-14 09:51:20.497 ThaliTest[1350:2172271] JXcore Cordova plugin initializing
,2016-03-14 09:51:20.498 ThaliTest[1350:2172497] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 09:51:32.184 ThaliTest[1350:2172497] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 09:51:32.184 ThaliTest[1350:2172497] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 09:51:32.185 ThaliTest[1350:2172497] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 09:51:32.185 ThaliTest[1350:2172497] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EAC1F276-2F36-4CDE-873A-2A16CB64E4E1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,ok 51 error should be null

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

,ok 82 port should should be null

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 83 error should be null

,ok 84 error should be null

,# 21. can get the network status before starting

,# teardown

,ok 85 network status should have certain non-empty properties

,# setup

,# 22. #generatePreambleAndBeacons bad args

,# teardown

,ok 86 publicKeysToNotify cannot be null

,ok 87 ecdh for local device cannot be null

,ok 88 milliseconds cannot be less than 0

,ok 89 milliseconds cannot be 0

,ok 90 milliseconds cannot be greater than one_day

,# setup

,# 23. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 91 should be equal

,# setup

,# 24. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 92 should be equal

ok 93 should be equal

,ok 94 (unnamed assert)

,ok 95 should be equal

,# setup

,# 25. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 96 should throw

,# setup

,# 26. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 97 Preamble expiration must be a 64 bit integer

,# setup

,# 27. #parseBeacons expiration out of range lower

,# teardown

,ok 98 Expiration out of range

,# setup

,# 28. #parseBeacons expiration out of range lower

,# teardown

,ok 99 Expiration out of range

,# setup

,# 29. #parseBeacons no beacons returns null

,# teardown

,ok 100 should be equal

,# setup

,# 30. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 101 Malformed encrypted beacon key ID

,# setup

,# 31. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 102 should be equal

,# setup

,# 32. #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 103 should be equal

ok 104 should be equal

,# setup

,# 33. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 105 should be equal

,ok 106 should be equal

,# setup

,# 34. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 107 should be equal

ok 108 (unnamed assert)

,# setup

,# 35. #parseBeacons with beacons both for and not for the user

,# teardown

,ok 109 should be equal

ok 110 (unnamed assert)

,# setup

,# 36. Start and stop ThaliNotificationServer

,# teardown

,ok 111 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

,ok 112 ThaliMobile.StopAdvertisingAndListening should be called once

,# setup

,# 37. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 113 StartUpdateAdvertisingAndListening should not be called

,ok 114 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 115 no error

ok 116 should be 204

,# setup

,# 38. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 117 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 39. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 118 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 40. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 119 no error

,ok 120 should be 200

,ok 121 should be equal

ok 122 should be equal

,ok 123 (unnamed assert)

,ok 124 no error

ok 125 should be 204

,# setup

,# 41. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 126 error should be null

ok 127 should be 204

,# setup

,# 42. Make an HTTP request to /NotificationBeacons before calling start

,# teardown

,ok 128 should be 404

,# setup

,# 43. #testThaliPeerAction - test getters

,# teardown

,ok 129 getPeerIdentifier

,ok 130 getConnectionType

,ok 131 getActionType

,ok 132 getActionState

,# setup

,# 44. #testThaliPeerAction - start and kill

,# teardown

,ok 133 initial state

,ok 134 after start

,ok 135 after kill

,# setup

,# 45. #testThaliPeerAction - double start

,# teardown

,ok 136 should be equal

,# setup

,# 46. #testThaliPeerAction - start after kill

,# teardown

,ok 137 clean kill

,ok 138 should be equal

,# setup

,# 47. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 139 should not be equal

,# setup

,# 48. Test PeerConnectionInformation basics

,# teardown

,ok 140 getHostAddress works

,ok 141 getPortNumber works

,ok 142 getSuggestedTCPTimeout works

,# setup

,# 49. Test PeerDictionary basic functionality

,# teardown

,ok 143 Entry counter must be 1

,ok 144 Size must be 1

,ok 145 Entry counter must be 2

,ok 146 Size must be 2

,ok 147 Entry2 should not be found

,ok 148 Size must be 1

,ok 149 Size must be 0

,ok 150 entry not found must be thrown

,# setup

,# 50. Test PeerDictionary with multiple entries.

,# teardown

,ok 151 Size must be100

,ok 152 Entries between 20 and MAXSIZE + 20 should exist

,ok 153 WAITING state entry should not be removed

,# setup

,# 51. RESOLVED entries are removed before WAITING state entry.

,# teardown

,ok 154 Entries between 6 and MAXSIZE + 4 should exist

ok 155 Size should be MAXSIZE

,ok 156 Size should be MAXSIZE+6

,# setup

,# 52. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

,# teardown

,ok 157 WAITING state entry should not be removed

,ok 158 Waiting entries between 6 and MAXSIZE + 4 should exist

,ok 159 Size should be MAXSIZE

,ok 160 entryCounter should be MAXSIZE+6

,# setup

,# 53. When CONTROLLED_BY_POOL entry is removed and kill is called.

,# teardown

,ok 161 Kill should be called once

,ok 162 Size should be 100

,# setup

,# 54. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 163 null arg

,ok 164 wrong arg type

,ok 165 wrong state

,# setup

,# 55. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 166 good enqueue

,ok 167 should be equal

,# setup

,# 56. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 168 good enqueue

,ok 169 2nd good enqueue

,ok 170 we are in the pool

,ok 171 We are out of the pool

,ok 172 Action was killed

,ok 173 The original kill was called too

,ok 174 second item is still in queue

,# setup

,# 57. compareBufferArrays

,# teardown

,ok 175 should throw

,ok 176 should throw

,ok 177 (unnamed assert)

,ok 178 (unnamed assert)

,ok 179 (unnamed assert)

,ok 180 (unnamed assert)

,ok 181 (unnamed assert)

,# setup

,# 58. Call start twice and get error

,# teardown

,ok 182 should throw

,# setup

,# 59. Start and make sure it runs

,# teardown

,# setup

,# 60. Make sure getTimeWhenRun is right after start

,# teardown

,ok 183 (unnamed assert)

,# setup

,# 61. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 184 should be equal

,# setup

,# 62. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 185 should be equal

,ok 186 should be equal

,ok 187 should throw

,# setup

,# 63. Test TransientState

,# teardown

,ok 188 should throw

,ok 189 should throw

,ok 190 should be equal

,ok 191 should be equal

,ok 192 should be equal

,ok 193 should be equal

,ok 194 (unnamed assert)

,ok 195 (unnamed assert)

,# setup

,# 64. No peers and empty database

,# teardown

,ok 196 verify failed

ok 197 constructor called once

,ok 198 constructor called with right args

,ok 199 match start arg

,ok 200 start called once

,ok 201 stop called once

,ok 202 stop after start

,# setup

,# 65. One peer and empty DB

,# teardown

,ok 203 verify failed

ok 204 constructor called once

,ok 205 constructor called with right args

,ok 206 match start arg

,ok 207 start called once

,ok 208 stop called once

,ok 209 stop after start

,# setup

,# 66. One peer with _Local set behind current seq

,# teardown

,ok 210 verify failed

,ok 211 constructor called once

,ok 212 constructor called with right args

ok 213 match start arg

,ok 214 start called once

,ok 215 stop called once
,
,ok 216 stop after start

,# setup

,# 67. One peer with _Local set equal to current seq

,# teardown

,ok 217 verify failed

ok 218 constructor called once

,ok 219 constructor called with right args

,ok 220 match start arg

ok 221 start called once

,ok 222 stop called once

,ok 223 stop after start

,# setup

,# 68. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 224 verify failed

ok 225 constructor called once

,ok 226 constructor called with right args

,ok 227 match start arg

,ok 228 start called once

,ok 229 stop called once

,ok 230 stop after start

,# setup

,# 69. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 231 verify failed

ok 232 constructor called once

ok 233 constructor called with right args

,ok 234 match start arg

,ok 235 start called once

,ok 236 stop called once

,ok 237 stop after start

,# setup

,# 70. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 238 verify failed

ok 239 constructor called once

ok 240 constructor called with right args

,ok 241 match start arg

,ok 242 start called once

,ok 243 stop called once

,ok 244 stop after start

,# setup

,# 71. two peers with empty DB, update the doc

,# teardown

,ok 245 verify failed

,ok 246 constructor called once

ok 247 constructor called with right args

,ok 248 last start before stop

,ok 249 empty first start

,ok 250 full second start

,ok 251 only 2 timers

,# setup

,# 72. add doc and make sure tokens refresh when they expire

,# teardown

,ok 252 verify failed

,ok 253 constructor called once

,ok 254 constructor called with right args

,ok 255 start before stop

,ok 256 We got at least 3 calls to start

,ok 257 at least 3

,ok 258 default 1

,ok 259 1 run

,ok 260 default 2

,ok 261 2 run

,ok 262 default 3

,# setup

,# 73. start and stop and start and stop

,# teardown

,ok 263 start out null

,ok 264 back to null

,ok 265 still null

,ok 266 verify failed

ok 267 constructor called once

,ok 268 constructor called with right args

,ok 269 first start before first stop

,ok 270 first stop before second start

,ok 271 second start before second stop

,# setup

,# 74. two identical starts in a row

,# teardown

,ok 272 verify failed

ok 273 constructor called once

,ok 274 constructor called with right args

ok 275 (unnamed assert)

,# setup

,# 75. two different starts in a row

,# teardown

,ok 276 verify failed

,ok 277 constructor called once

,ok 278 constructor called with right args

,ok 279 (unnamed assert)

,ok 280 (unnamed assert)

,# setup

,# 76. two stops and a start and two stops

,# teardown

,ok 281 verify failed

ok 282 constructor called once

,ok 283 constructor called with right args

,ok 284 start before stop

,# setup

,# 77. we properly enqueue requests so no then needed

,# teardown

,ok 285 verify failed

,ok 286 constructor called once

ok 287 constructor called with right args

,ok 288 start before stop

,# setup

,# 78. test calculateSeqPointKeyId

,# teardown

,ok 289 should be equal

,ok 290 should be equal

,# setup

,# 79. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 291 should be in started state

,# teardown

,ok 292 peer identifier should match

ok 293 host address should match

,ok 294 port should match

,ok 295 host address should be null

,ok 296 port should should be null

,# setup

,ok 297 should not be in started state

,# 80. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 298 should be in started state

,# teardown

,ok 299 USN should have changed from the first one

,ok 300 when receiving the second byebye, the first USN should be already set

,# setup

,ok 301 should not be in started state

# 81. messages with invalid location or USN should be ignored

,ok 302 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 303 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 304 should not have emitted with invalid USN

,# setup

,ok 305 should not be in started state

,# 82. verify that Thali-specific messages are filtered correctly

,ok 306 should be in started state

,# teardown

,ok 307 irrelevant messages should be ignored

,ok 308 relevant messages should not be ignored

,ok 309 messages from this device should be ignored

,# setup

,ok 310 should not be in started state

,# 83. #startListeningForAdvertisements should fail if start not called

,ok 311 should be in started state

,# teardown

,ok 312 specific error should be returned

,# setup

,ok 313 should not be in started state

,# 84. #startUpdateAdvertisingAndListening should fail if start not called

,ok 314 should be in started state

,# teardown

,ok 315 specific error should be returned

,# setup

,ok 316 should not be in started state

,# 85. #start should fail if called twice in a row

,ok 317 should be in started state

,# teardown

,ok 318 specific error should be received

,# setup

,ok 319 should not be in started state

,# 86. should not be started after stop is called

,ok 320 should be in started state

,# teardown

,ok 321 should not be started

,ok 322 should not be listening

,ok 323 should not target listening

,ok 324 should not be advertising

,ok 325 should not target advertising

,# setup

,ok 326 should not be in started state

,# 87. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 327 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 328 specific error should be received

,# setup

,ok 329 should not be in started state

,# 88. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 330 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 331 specific error expected

,# setup

,ok 332 should not be in started state

,# 89. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 333 should be in started state

,# teardown

,ok 334 server should respond with code 200

,# setup

,ok 335 should not be in started state

,# 90. #stop can be called multiple times in a row

,ok 336 should be in started state

,# teardown

,ok 337 should be in stopped state

,ok 338 should still be in stopped state

,# setup

,ok 339 should not be in started state

,# 91. #startListeningForAdvertisements can be called multiple times in a row

,ok 340 should be in started state

,# teardown

,ok 341 should be in listening state

,ok 342 should still be in listening state

,# setup

,ok 343 should not be in started state

# 92. #stopListeningForAdvertisements can be called multiple times in a row

,ok 344 should be in started state

,# teardown

,ok 345 should not be in listening state

,ok 346 should still not be in listening state

,# setup

,ok 347 should not be in started state

,# 93. #stopAdvertisingAndListening can be called multiple times in a row

,ok 348 should be in started state

,# teardown

,ok 349 should not be in advertising state

,ok 350 should still not be in advertising state

,# setup

,ok 351 should not be in started state

,# 94. functions are run from a queue in the right order

,ok 352 should be in started state

,# teardown

,ok 353 call order must match

,# setup

,ok 354 should not be in started state

,# 95. #ThaliPeerPoolDefault - single action

,# teardown

,ok 355 is an agent

,ok 356 enqueue is fine

,ok 357 Everything should be off the queue

,# setup

,# 96. #ThaliPeerPoolDefault - multiple actions

,# teardown

,ok 358 is an agent

,ok 359 first enqueue is fine

,ok 360 is an agent

,ok 361 second enqueue is fine

,ok 362 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.

,ok 363 Queue is empty

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
