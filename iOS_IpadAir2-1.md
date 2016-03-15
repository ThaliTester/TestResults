#### Test 6275440391a6bae_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B4454699-C7B0-4112-9E0C-BC55762DF779/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B4454699-C7B0-4112-9E0C-BC55762DF779/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49942"
,(lldb)     command script import "/tmp/B4454699-C7B0-4112-9E0C-BC55762DF779/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 20:34:53.623 ThaliTest[1526:2401081] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7A868721-A79F-4F0E-9D4C-3671B396D8FB/Library/Cookies/Cookies.binarycookies
,2016-03-15 20:34:54.005 ThaliTest[1526:2401081] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 20:34:54.007 ThaliTest[1526:2401081] Multi-tasking -> Device: YES, App: YES
,2016-03-15 20:34:54.029 ThaliTest[1526:2401081] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 20:34:56.010 ThaliTest[1526:2401081] Using UIWebView
,2016-03-15 20:34:56.016 ThaliTest[1526:2401081] [CDVTimer][handleopenurl] 0.405014ms
,2016-03-15 20:34:56.024 ThaliTest[1526:2401081] [CDVTimer][intentandnavigationfilter] 7.165015ms
,2016-03-15 20:34:56.025 ThaliTest[1526:2401081] [CDVTimer][gesturehandler] 0.343025ms
,2016-03-15 20:34:56.026 ThaliTest[1526:2401081] [CDVTimer][TotalPluginStartup] 9.795010ms
,2016-03-15 20:35:02.841 ThaliTest[1526:2401081] Resetting plugins due to page load.
,2016-03-15 20:35:06.279 ThaliTest[1526:2401081] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/index.html
,2016-03-15 20:35:06.497 ThaliTest[1526:2401081] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2016-03-15 20:35:06.498 ThaliTest[1526:2401289] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 20:35:18.305 ThaliTest[1526:2401289] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 20:35:18.305 ThaliTest[1526:2401289] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 20:35:18.306 ThaliTest[1526:2401289] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 20:35:18.307 ThaliTest[1526:2401289] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E579BAE-B8EC-47AC-9640-920318024E24/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,# 33. Test BEACONS_RETRIEVED_AND_PARSED locally

,# teardown

,ok 128 Response should be BEACONS_RETRIEVED_AND_PARSED

ok 129 good beacon

,ok 130 good preAmble

,ok 131 public keys match!

,ok 132 must return null after successful call

,# setup

,# 34. Test HTTP_BAD_RESPONSE locally

,# teardown

,ok 133 Response should be HTTP_BAD_RESPONSE

,ok 134 must return null after successful call

,# setup

,# 35. Test NETWORK_PROBLEM locally

,# teardown

,ok 135 Response should be NETWORK_PROBLEM

,ok 136 reject reason should be: Could not establish TCP connection

,# setup

,# 36. Test timeout locally

,# teardown

,ok 137 Should be NETWORK_PROBLEM caused by timeout

,ok 138 reject reason should be Could not establish TCP connection

,# setup

,# 37. Call the start two times

,# teardown

,ok 139 Call start once

,ok 140 Response should be BEACONS_RETRIEVED_AND_PARSED

,ok 141 must return null after successful call.

,# setup

,# 38. Call the kill before calling the start

,# teardown

,ok 142 Should be Killed

,ok 143 Start after killed

,# setup

,# 39. Call the kill immediately after the start

,# teardown

,ok 144 Should be KILLED

,ok 145 must return null after successful kill

,# setup

,# 40. Call the kill while waiting a response from the server

,# teardown

,ok 146 Should be KILLED

,ok 147 must return null after successful kill

,# setup

,# 41. Test to exceed the max content size locally

,# teardown

,ok 148 HTTP_BAD_RESPONSE should be response when content size is exceeded

,ok 149 must return null after successful call

,# setup

,# 42. Close the server socket while the client is waiting a responsefrom the server. Local test.

,# teardown

,ok 150 Should be NETWORK_PROBLEM caused closing server socket

,ok 151 Should be Could not establish TCP connection

,# setup

,# 43. #generatePreambleAndBeacons bad args

,# teardown

,ok 152 publicKeysToNotify cannot be null

,ok 153 ecdh for local device cannot be null

,ok 154 milliseconds cannot be less than 0

,ok 155 milliseconds cannot be 0

,ok 156 milliseconds cannot be greater than one_day

,# setup

,# 44. #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 157 should be equal

,# setup

,# 45. #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 158 should be equal

ok 159 should be equal

ok 160 (unnamed assert)

,ok 161 should be equal

,# setup

,# 46. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 162 should throw

,# setup

,# 47. #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 163 Preamble expiration must be a 64 bit integer

,# setup

,# 48. #parseBeacons expiration out of range lower

,# teardown

,ok 164 Expiration out of range

,# setup

,# 49. #parseBeacons expiration out of range lower

,# teardown

,ok 165 Expiration out of range

,# setup

,# 50. #parseBeacons no beacons returns null

,# teardown

,ok 166 should be equal

,# setup

,# 51. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 167 Malformed encrypted beacon key ID

,# setup

,# 52. #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 168 should be equal

,# setup

,# 53. #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 169 should be equal

ok 170 should be equal

,# setup

,# 54. #parseBeacons addressBookCallback returns spurious match

,# teardown

,ok 171 should be equal

,ok 172 should be equal

,# setup

,# 55. #parseBeacons addressBookCallback returns public key

,# teardown

,ok 173 right number of calls to address book

,ok 174 good preAmble

ok 175 good unencryptedKeyId

,ok 176 good beacon

,# setup

,# 56. validate generatePskIdentityField

,# teardown

,ok 177 decoded buffers match

,# setup

,# 57. validate generatePskSecret

,# teardown

,ok 178 secrets match

,# setup

,# 58. Start and stop ThaliNotificationServer

,# teardown

,ok 179 ThaliMobile.StartUpdateAdvertisingAndListening should be called once

ok 180 ThaliMobile.StopAdvertisingAndListeningshould be called once

,# setup

,# 59. Pass an empty array to ThaliNotificationServer.start

,# teardown

,ok 181 StartUpdateAdvertisingAndListening should not be called

,ok 182 ThaliMobile.StopAdvertisingAndListening should be called once

,ok 183 no error

,ok 184 should be 204

,# setup

,# 60. Pass a string to ThaliNotificationServer.start

,# teardown

,ok 185 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 61. Pass an empty parameter to ThaliNotificationServer.start

,# teardown

,ok 186 StartUpdateAdvertisingAndListening should not be called

,# setup

,# 62. Make an HTTP request to /NotificationBeacons

,# teardown

,ok 187 no error

ok 188 should be 200

ok 189 should be equal

,ok 190 should be equal

,ok 191 (unnamed assert)

,ok 192 no error

ok 193 should be 204

,# setup

,# 63. Make an HTTP request to /NotificationBeacons (no keys)

,# teardown

,ok 194 error should be null

ok 195 should be 204

,# setup

,# 64. Make an HTTP request to /NotificationBeaconsbefore calling start

,# teardown

,ok 196 should be 404

,# setup

,# 65. #testThaliPeerAction - test getters

,# teardown

,ok 197 getPeerIdentifier

,ok 198 getConnectionType

,ok 199 getActionType

,ok 200 getActionState

,# setup

,# 66. #testThaliPeerAction - start and kill

,# teardown

,ok 201 initial state

,ok 202 after start

,ok 203 after kill

,# setup

,# 67. #testThaliPeerAction - double start

,# teardown

,ok 204 should be equal

,# setup

,# 68. #testThaliPeerAction - start after kill

,# teardown

,ok 205 clean kill

,ok 206 should be equal

,# setup

,# 69. #testThaliPeerAction - make sure ids are unique

,# teardown

,ok 207 should not be equal

,# setup

,# 70. Test PeerConnectionInformation basics

,# teardown

,ok 208 getHostAddress works

,ok 209 getPortNumber works

,ok 210 getSuggestedTCPTimeout works

,# setup

,# 71. Test PeerDictionary basic functionality

,# teardown

,ok 211 Entry counter must be 1

,ok 212 Size must be 1

,ok 213 Entry counter must be 2

,ok 214 Size must be 2

,ok 215 Entry2 should not be found

,ok 216 Size must be 1

,ok 217 Size must be 0

,ok 218 entry not found must be thrown

,# setup

,# 72. Test PeerDictionary with multiple entries.

,# teardown

,ok 219 Size must be100

,ok 220 Entries between 20 and MAXSIZE + 20 should exist

,ok 221 WAITING state entry should not be removed

,# setup

,# 73. RESOLVED entries are removed before WAITING state entry.

,# teardown

,ok 222 Entries between 6 and MAXSIZE + 4 should exist

ok 223 Size should be MAXSIZE

ok 224 Size should be MAXSIZE+6

,# setup

,# 74. WAITING entries are removed before CONTROLLED_BY_POOL state entry.

,# teardown

,ok 225 WAITING state entry should not be removed

,ok 226 Waiting entries between 6 and MAXSIZE + 4 should exist

,ok 227 Size should be MAXSIZE

,ok 228 entryCounter should be MAXSIZE+6

,# setup

,# 75. When CONTROLLED_BY_POOL entry is removed and kill is called.

,# teardown

,ok 229 Kill should be called once

ok 230 Size should be 100

,# setup

,# 76. #ThaliPeerPoolInterface - bad enqueues

,# teardown

,ok 231 null arg

,ok 232 wrong arg type

,ok 233 wrong state

,# setup

,# 77. #ThaliPeerPoolInterface - do not allow same object type

,# teardown

,ok 234 good enqueue

,ok 235 should be equal

,# setup

,# 78. #ThaliPeerPoolInterface - make sure we catch kill and dequeue

,# teardown

,ok 236 good enqueue

,ok 237 2nd good enqueue

,ok 238 we are in the pool

,ok 239 We are out of the pool

,ok 240 Action was killed

,ok 241 The original kill was called too

,ok 242 second item is still in queue

,# setup

,# 79. compareBufferArrays

,# teardown

,ok 243 should throw

,ok 244 should throw

,ok 245 (unnamed assert)

,ok 246 (unnamed assert)

,ok 247 (unnamed assert)

,ok 248 (unnamed assert)

,ok 249 (unnamed assert)

,# setup

,# 80. Call start twice and get error

,# teardown

,ok 250 should throw

,# setup

,# 81. Start and make sure it runs

,# teardown

,# setup

,# 82. Make sure getTimeWhenRun is right after start

,# teardown

,ok 251 (unnamed assert)

,# setup

,# 83. Make sure getTimeWhenRun is -1 after function is called

,# teardown

,ok 252 should be equal

,# setup

,# 84. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running

,# teardown

,ok 253 should be equal

,ok 254 should be equal

,ok 255 should throw

,# setup

,# 85. Test TransientState

,# teardown

,ok 256 should throw

,ok 257 should throw

,ok 258 should be equal

,ok 259 should be equal

,ok 260 should be equal

,ok 261 should be equal

,ok 262 (unnamed assert)

,ok 263 (unnamed assert)

,# setup

,# 86. No peers and empty database

,# teardown

,ok 264 verify failed

ok 265 constructor called once

,ok 266 constructor called with right args

,ok 267 match start arg

,ok 268 start called once

,ok 269 stop called once

,ok 270 stop after start

,# setup

,# 87. One peer and empty DB

,# teardown

,ok 271 verify failed

ok 272 constructor called once

,ok 273 constructor called with right args

ok 274 match start arg

,ok 275 start called once

,ok 276 stop called once

,ok 277 stop after start

,# setup

,# 88. One peer with _Local set behind current seq

,# teardown

,ok 278 verify failed

,ok 279 constructor called once

ok 280 constructor called with right args

ok 281 match start arg

,ok 282 start called once

,ok 283 stop called once

,ok 284 stop after start

,# setup

,# 89. One peer with _Local set equal to current seq

,# teardown

,ok 285 verify failed

,ok 286 constructor called once

ok 287 constructor called with right args

,ok 288 match start arg

,ok 289 start called once

,ok 290 stop called once

,ok 291 stop after start

,# setup

,# 90. One peer with _Local set ahead of current seq (and no this should not happen)

,# teardown

,ok 292 verify failed

ok 293 constructor called once

ok 294 constructor called with right args

,ok 295 match start arg

,ok 296 start called once

,ok 297 stop called once

,ok 298 stop after start

,# setup

,# 91. Three peers, one not in DB, one behind and one ahead

,# teardown

,ok 299 verify failed

ok 300 constructor called once

,ok 301 constructor called with right args

,ok 302 match start arg

,ok 303 start called once

,ok 304 stop called once

,ok 305 stop after start

,# setup

,# 92. More than maximum peers, make sure we only send maximum allowed

,# teardown

,ok 306 verify failed

ok 307 constructor called once

ok 308 constructor called with right args

,ok 309 match start arg

,ok 310 start called once

,ok 311 stop called once

,ok 312 stop after start

,# setup

,# 93. two peers with empty DB, update the doc

,# teardown

,ok 313 verify failed

,ok 314 constructor called once

ok 315 constructor called with right args

,ok 316 last start before stop

,ok 317 empty first start

,ok 318 full second start

,ok 319 only 2 timers

,# setup

,# 94. add doc and make sure tokens refresh when they expire

,# teardown

,ok 320 verify failed

,ok 321 constructor called once

,ok 322 constructor called with right args

,ok 323 start before stop

,ok 324 We got at least 3 calls to start

,ok 325 at least 3

,ok 326 default 1

,ok 327 1 run

,ok 328 default 2

,ok 329 2 run

,ok 330 default 3

,# setup

,# 95. start and stop and start and stop

,# teardown

,ok 331 start out null

,ok 332 back to null

,ok 333 still null

,ok 334 verify failed

,ok 335 constructor called once

,ok 336 constructor called with right args

,ok 337 first start before first stop

,ok 338 first stop before second start

,ok 339 second start before second stop

,# setup

,# 96. two identical starts in a row

,# teardown

,ok 340 verify failed

,ok 341 constructor called once

,ok 342 constructor called with right args

ok 343 (unnamed assert)

,# setup

,# 97. two different starts in a row

,# teardown

,ok 344 verify failed

ok 345 constructor called once

,ok 346 constructor called with right args

,ok 347 (unnamed assert)

,ok 348 (unnamed assert)

,# setup

,# 98. two stops and a start and two stops

,# teardown

,ok 349 verify failed

ok 350 constructor called once

,ok 351 constructor called with right args

,ok 352 start before stop

,# setup

,# 99. we properly enqueue requests so no then needed

,# teardown

,ok 353 verify failed

,ok 354 constructor called once

,ok 355 constructor called with right args

,ok 356 start before stop

,# setup

,# 100. test calculateSeqPointKeyId

,# teardown

,ok 357 should be equal

ok 358 should be equal

,# setup

,# 101. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ok 359 should be in started state

,# teardown

,ok 360 peer identifier should match

ok 361 host address should match

,ok 362 port should match

,ok 363 host address should be null

,ok 364 port should should be null

,# setup

,ok 365 should not be in started state

,# 102. #startUpdateAdvertisingAndListening should use different USN after every invocation

,ok 366 should be in started state

,# teardown

,ok 367 USN should have changed from the first one

,ok 368 when receiving the second byebye, the first USN should be already set

,# setup

,ok 369 should not be in started state

,# 103. messages with invalid location or USN should be ignored

,ok 370 should be in started state

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 371 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 372 should not have emitted with invalid USN

,# setup

,ok 373 should not be in started state

,# 104. verify that Thali-specific messages are filtered correctly

,ok 374 should be in started state

,# teardown

,ok 375 irrelevant messages should be ignored

,ok 376 relevant messages should not be ignored

,ok 377 messages from this device should be ignored

,# setup

,ok 378 should not be in started state

,# 105. #startListeningForAdvertisements should fail if start not called

,ok 379 should be in started state

,# teardown

,ok 380 specific error should be returned

,# setup

,ok 381 should not be in started state

,# 106. #startUpdateAdvertisingAndListening should fail if start not called

,ok 382 should be in started state

,# teardown

,ok 383 specific error should be returned

,# setup

,ok 384 should not be in started state

,# 107. #start should fail if called twice in a row

,ok 385 should be in started state

,# teardown

,ok 386 specific error should be received

,# setup

,ok 387 should not be in started state

,# 108. should not be started after stop is called

,ok 388 should be in started state

,# teardown

,ok 389 should not be started

,ok 390 should not be listening

,ok 391 should not target listening

,ok 392 should not be advertising

,ok 393 should not target advertising

,# setup

,ok 394 should not be in started state

,# 109. #startUpdateAdvertisingAndListening should fail invalid router has been passed

,ok 395 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 396 specific error should be received

,# setup

,ok 397 should not be in started state

,# 110. #startUpdateAdvertisingAndListening should fail if router server starting fails

,ok 398 should be in started state

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 399 specific error expected

,# setup

,ok 400 should not be in started state

,# 111. #startUpdateAdvertisingAndListening should start hosting given router object

,ok 401 should be in started state

,# teardown

,ok 402 server should respond with code 200

,# setup

,ok 403 should not be in started state

,# 112. #stop can be called multiple times in a row

,ok 404 should be in started state

,# teardown

,ok 405 should be in stopped state

,ok 406 should still be in stopped state

,# setup

,ok 407 should not be in started state

,# 113. #startListeningForAdvertisements can be called multiple times in a row

,ok 408 should be in started state

,# teardown

,ok 409 should be in listening state

,ok 410 should still be in listening state

,# setup

,ok 411 should not be in started state

,# 114. #stopListeningForAdvertisements can be called multiple times in a row

,ok 412 should be in started state

,# teardown

,ok 413 should not be in listening state

,ok 414 should still not be in listening state

,# setup

,ok 415 should not be in started state

,# 115. #stopAdvertisingAndListening can be called multiple times in a row

,ok 416 should be in started state

,# teardown

,ok 417 should not be in advertising state

,ok 418 should still not be in advertising state

,# setup

,ok 419 should not be in started state

,# 116. functions are run from a queue in the right order

,ok 420 should be in started state

,# teardown

,ok 421 call order must match

,# setup

,ok 422 should not be in started state

,# 117. #ThaliPeerPoolDefault - single action

,# teardown

,ok 423 is an agent

,ok 424 enqueue is fine

,ok 425 Everything should be off the queue

,# setup

,# 118. #ThaliPeerPoolDefault - multiple actions

,# teardown

,ok 426 is an agent

,ok 427 first enqueue is fine

,ok 428 is an agent

,ok 429 second enqueue is fine

,ok 430 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.

,ok 431 Queue is empty

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
