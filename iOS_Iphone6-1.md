#### Test 62754403d2f0346_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AFCF5CFA-DE1D-4C9B-ABBB-27521F1E7FFB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AFCF5CFA-DE1D-4C9B-ABBB-27521F1E7FFB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52190"
,(lldb)     command script import "/tmp/AFCF5CFA-DE1D-4C9B-ABBB-27521F1E7FFB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 13:25:29.909 ThaliTest[1639:2599760] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB350B3F-17B7-4B09-A4A9-758AE8C0D3E4/Library/Cookies/Cookies.binarycookies
,2016-03-17 13:25:30.244 ThaliTest[1639:2599760] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 13:25:30.245 ThaliTest[1639:2599760] Multi-tasking -> Device: YES, App: YES
,2016-03-17 13:25:30.269 ThaliTest[1639:2599760] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 13:25:32.182 ThaliTest[1639:2599760] Using UIWebView
,2016-03-17 13:25:32.189 ThaliTest[1639:2599760] [CDVTimer][handleopenurl] 0.391960ms
,2016-03-17 13:25:32.196 ThaliTest[1639:2599760] [CDVTimer][intentandnavigationfilter] 7.206976ms
2016-03-17 13:25:32.197 ThaliTest[1639:2599760] [CDVTimer][gesturehandler] 0.399947ms
2016-03-17 13:25:32.198 ThaliTest[1639:2599760] [CDVTimer][TotalPluginS,tartup] 9.575009ms
,2016-03-17 13:25:39.224 ThaliTest[1639:2599760] Resetting plugins due to page load.
,2016-03-17 13:25:42.818 ThaliTest[1639:2599760] Finished load of: file:///var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/index.html
,2016-03-17 13:25:43.049 ThaliTest[1639:2599760] JXcore Cordova plugin initializing
,2016-03-17 13:25:43.051 ThaliTest[1639:2599968] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-17 13:25:56.877 ThaliTest[1639:2599968] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 13:25:56.877 ThaliTest[1639:2599968] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 13:25:56.877 ThaliTest[1639:2599968] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 13:25:56.879 ThaliTest[1639:2599968] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/679470FA-C4B5-4399-8E90-3CE4975F1848/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
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
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,# 4. native server connections all up
,# teardown
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# setup
,# 5. native server - closing incoming stream cleans outgoing socket
,# teardown
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,# 6. native server - closing incoming connection cleans outgoing socket
,# teardown
,ok 14 we should not have gotten an error
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,# 8. native server - closing the whole server cleans everything up
,# teardown
,ok 20 we should not have gotten an error
,ok 21 Buffers are identical
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,ok 31 we should not have gotten an error
,ok 32 Buffers are identical
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,ok 38 we should not have gotten an error
,ok 39 Buffers are identical
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 45 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 46 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 47 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 73 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 74 sane
,# setup
,# 20. another
,# teardown
,ok 75 sane
,# setup
,# 21. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 76 specific error should be returned
,# setup
,ok 77 error should be null
,ok 78 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 79 specific error should be returned
,# setup
,ok 80 error should be null
,ok 81 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,ok 82 error should be null
,ok 83 error should be null
,ok 84 error should be null
,ok 85 error should be null
,# setup
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 88 error should be null
,ok 89 error should be null
,ok 90 error should be null
,ok 91 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 94 error should be null
,ok 95 error should be null
,ok 96 error should be null
,ok 97 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 100 error should be null
,ok 101 error should be null
,ok 102 error should be null
,ok 103 error should be null
,# setup
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 114 error should be null
,ok 115 error should be null
,# 29. does not send duplicate availability changes
,# teardown
,ok 116 should be called once
,ok 117 should not have been called more than once
,# setup
,ok 118 error should be null
,ok 119 error should be null
,# 30. can get the network status
,# teardown
,ok 120 network status should have certain non-empty properties
,# setup
,ok 121 error should be null
,ok 122 error should be null
,# 31. wifi peer is marked unavailable if announcements stop
,# teardown
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. can get the network status before starting
,# teardown
,ok 129 network status should have certain non-empty properties
,# setup
,# 33. Test BEACONS_RETRIEVED_AND_PARSED locally
,# teardown
,ok 130 peerIdentifier should be hello
,ok 131 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 132 good beacon
,ok 133 good preAmble
,ok 134 public keys match!
,ok 135 must return null after successful call
,# setup
,# 34. Test HTTP_BAD_RESPONSE locally
,# teardown
,ok 136 Response should be HTTP_BAD_RESPONSE
,ok 137 must return null after successful call
,# setup
,# 35. Test NETWORK_PROBLEM locally
,# teardown
,ok 138 Response should be NETWORK_PROBLEM
,ok 139 reject reason should be: Could not establish TCP connection
,# setup
,# 36. Test timeout locally
,# teardown
,ok 140 Should be NETWORK_PROBLEM caused by timeout
,ok 141 reject reason should be Could not establish TCP connection
,# setup
,# 37. Call the start two times
,# teardown
,ok 142 Call start once
,ok 143 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 144 must return null after successful call.
,# setup
,# 38. Call the kill before calling the start
,# teardown
,ok 145 Should be Killed
,ok 146 Start after killed
,# setup
,# 39. Call the kill immediately after the start
,# teardown
,ok 147 Should be KILLED
,ok 148 must return null after successful kill
,# setup
,# 40. Call the kill while waiting a response from the server
,# teardown
,ok 149 Should be KILLED
,ok 150 must return null after successful kill
,# setup
,# 41. Test to exceed the max content size locally
,# teardown
,ok 151 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 152 must return null after successful call
,# setup
,# 42. Close the server socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 153 Should be NETWORK_PROBLEM caused closing server socket
,ok 154 Should be Could not establish TCP connection
,# setup
,# 43. Close the client socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 155 Should be NETWORK_PROBLEM caused closing client socket
,ok 156 Should be Could not establish TCP connection
,# setup
,# 44. #generatePreambleAndBeacons bad args
,# teardown
,ok 157 publicKeysToNotify cannot be null
,ok 158 ecdh for local device cannot be null
,ok 159 milliseconds cannot be less than 0
,ok 160 milliseconds cannot be 0
,ok 161 milliseconds cannot be greater than one_day
,# setup
,# 45. #generatePreambleAndBeacons empty keys to notify
,# teardown
,ok 162 should be equal
,# setup
,# 46. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 163 should be equal
ok 164 should be equal
,ok 165 (unnamed assert)
,ok 166 should be equal
,# setup
,# 47. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 167 should throw
,# setup
,# 48. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 168 Preamble expiration must be a 64 bit integer
,# setup
,# 49. #parseBeacons expiration out of range lower
,# teardown
,ok 169 Expiration out of range
,# setup
,# 50. #parseBeacons expiration out of range lower
,# teardown
,ok 170 Expiration out of range
,# setup
,# 51. #parseBeacons no beacons returns null
,# teardown
,ok 171 should be equal
,# setup
,# 52. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 172 Malformed encrypted beacon key ID
,# setup
,# 53. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 173 should be equal
,# setup
,# 54. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 174 should be equal
ok 175 should be equal
,# setup
,# 55. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 176 should be equal
ok 177 should be equal
,# setup
,# 56. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 178 right number of calls to address book
,ok 179 good preAmble
,ok 180 good unencryptedKeyId
,ok 181 good beacon
,# setup
,# 57. validate generatePskIdentityField
,# teardown
,ok 182 decoded buffers match
,# setup
,# 58. validate generatePskSecret
,# teardown
,ok 183 secrets match
,# setup
,# 59. Start and stop ThaliNotificationServer
,# teardown
,ok 184 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 185 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# setup
,# 60. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 186 StartUpdateAdvertisingAndListening should not be called
,ok 187 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 188 no error
,ok 189 should be 204
,# setup
,# 61. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 190 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 62. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 191 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 63. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 192 no error
,ok 193 should be 200
ok 194 should be equal
,ok 195 should be equal
,ok 196 (unnamed assert)
,ok 197 no error
ok 198 should be 204
,# setup
,# 64. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 199 error should be null
,ok 200 should be 204
,# setup
,# 65. Make an HTTP request to /NotificationBeaconsbefore calling start
,# teardown
,ok 201 should be 404
,# setup
,# 66. #testThaliPeerAction - test getters
,# teardown
,ok 202 getPeerIdentifier
,ok 203 getConnectionType
,ok 204 getActionType
,ok 205 getActionState
,# setup
,# 67. #testThaliPeerAction - start and kill
,# teardown
,ok 206 initial state
,ok 207 after start
,ok 208 after kill
,# setup
,# 68. #testThaliPeerAction - double start
,# teardown
,ok 209 should be equal
,# setup
,# 69. #testThaliPeerAction - start after kill
,# teardown
,ok 210 clean kill
,ok 211 should be equal
,# setup
,# 70. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 212 should not be equal
,# setup
,# 71. Test PeerConnectionInformation basics
,# teardown
,ok 213 getHostAddress works
,ok 214 getPortNumber works
,ok 215 getSuggestedTCPTimeout works
,# setup
,# 72. Test PeerDictionary basic functionality
,# teardown
,ok 216 Entry counter must be 1
,ok 217 Size must be 1
,ok 218 Entry counter must be 2
,ok 219 Size must be 2
,ok 220 Entry2 should not be found
,ok 221 Size must be 1
,ok 222 Size must be 0
,ok 223 entry not found must be thrown
,# setup
,# 73. Test PeerDictionary with multiple entries.
,# teardown
,ok 224 Size must be100
,ok 225 Entries between 20 and MAXSIZE + 20 should exist
,ok 226 WAITING state entry should not be removed
,# setup
,# 74. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 227 Entries between 6 and MAXSIZE + 4 should exist
,ok 228 Size should be MAXSIZE
,ok 229 Size should be MAXSIZE+6
,# setup
,# 75. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 230 WAITING state entry should not be removed
,ok 231 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 232 Size should be MAXSIZE
,ok 233 entryCounter should be MAXSIZE+6
,# setup
,# 76. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 234 Kill should be called once
ok 235 Size should be 100
,# setup
,# 77. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 236 null arg
,ok 237 wrong arg type
,ok 238 wrong state
,# setup
,# 78. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 239 good enqueue
,ok 240 should be equal
,# setup
,# 79. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 241 good enqueue
,ok 242 2nd good enqueue
,ok 243 we are in the pool
,ok 244 We are out of the pool
,ok 245 Action was killed
,ok 246 The original kill was called too
,ok 247 second item is still in queue
,# setup
,# 80. compareBufferArrays
,# teardown
,ok 248 should throw
,ok 249 should throw
,ok 250 (unnamed assert)
,ok 251 (unnamed assert)
,ok 252 (unnamed assert)
,ok 253 (unnamed assert)
,ok 254 (unnamed assert)
,# setup
,# 81. Call start twice and get error
,# teardown
,ok 255 should throw
,# setup
,# 82. Start and make sure it runs
,# teardown
,# setup
,# 83. Make sure getTimeWhenRun is right after start
,# teardown
,ok 256 (unnamed assert)
,# setup
,# 84. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 257 should be equal
,# setup
,# 85. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 258 should be equal
,ok 259 should be equal
,ok 260 should throw
,# setup
,# 86. Test TransientState
,# teardown
,ok 261 should throw
,ok 262 should throw
,ok 263 should be equal
,ok 264 should be equal
,ok 265 should be equal
,ok 266 should be equal
,ok 267 (unnamed assert)
,ok 268 (unnamed assert)
,# setup
,# 87. No peers and empty database
,# teardown
,ok 269 verify failed
ok 270 constructor called once
,ok 271 constructor called with right args
,ok 272 match start arg
,ok 273 start called once
,ok 274 stop called once
,ok 275 stop after start
,# setup
,# 88. One peer and empty DB
,# teardown
,ok 276 verify failed
ok 277 constructor called once
,ok 278 constructor called with right args
,ok 279 match start arg
,ok 280 start called once
,ok 281 stop called once
,ok 282 stop after start
,# setup
,# 89. One peer with _Local set behind current seq
,# teardown
,ok 283 verify failed
ok 284 constructor called once
,ok 285 constructor called with right args
,ok 286 match start arg
,ok 287 start called once
,ok 288 stop called once
,ok 289 stop after start
,# setup
,# 90. One peer with _Local set equal to current seq
,# teardown
,ok 290 verify failed
ok 291 constructor called once
,ok 292 constructor called with right args
,ok 293 match start arg
,ok 294 start called once
,ok 295 stop called once
,ok 296 stop after start
,# setup
,# 91. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,ok 297 verify failed
ok 298 constructor called once
,ok 299 constructor called with right args
,ok 300 match start arg
,ok 301 start called once
,ok 302 stop called once
,ok 303 stop after start
,# setup
,# 92. Three peers, one not in DB, one behind and one ahead
,# teardown
,ok 304 verify failed
ok 305 constructor called once
,ok 306 constructor called with right args
,ok 307 match start arg
,ok 308 start called once
,ok 309 stop called once
,ok 310 stop after start
,# setup
,# 93. More than maximum peers, make sure we only send maximum allowed
,# teardown
,ok 311 verify failed
,ok 312 constructor called once
,ok 313 constructor called with right args
,ok 314 match start arg
,ok 315 start called once
,ok 316 stop called once
,ok 317 stop after start
,# setup
,# 94. two peers with empty DB, update the doc
,# teardown
,ok 318 verify failed
ok 319 constructor called once
,ok 320 constructor called with right args
,ok 321 last start before stop
,ok 322 empty first start
,ok 323 full second start
,ok 324 only 2 timers
,# setup
,# 95. add doc and make sure tokens refresh when they expire
,# teardown
,ok 325 verify failed
,ok 326 constructor called once
,ok 327 constructor called with right args
,ok 328 start before stop
,ok 329 We got at least 3 calls to start
,ok 330 at least 3
,ok 331 default 1
,ok 332 1 run
,ok 333 default 2
,ok 334 2 run
,ok 335 default 3
,# setup
,# 96. start and stop and start and stop
,# teardown
,ok 336 start out null
,ok 337 back to null
,ok 338 still null
,ok 339 verify failed
,ok 340 constructor called once
,ok 341 constructor called with right args
,ok 342 first start before first stop
,ok 343 first stop before second start
,ok 344 second start before second stop
,# setup
,# 97. two identical starts in a row
,# teardown
,ok 345 verify failed
ok 346 constructor called once
,ok 347 constructor called with right args
,ok 348 (unnamed assert)
,# setup
,# 98. two different starts in a row
,# teardown
,ok 349 verify failed
,ok 350 constructor called once
,ok 351 constructor called with right args
,ok 352 (unnamed assert)
,ok 353 (unnamed assert)
,# setup
,# 99. two stops and a start and two stops
,# teardown
,ok 354 verify failed
ok 355 constructor called once
,ok 356 constructor called with right args
,ok 357 start before stop
,# setup
,# 100. we properly enqueue requests so no then needed
,# teardown
,ok 358 verify failed
ok 359 constructor called once
,ok 360 constructor called with right args
,ok 361 start before stop
,# setup
,# 101. test calculateSeqPointKeyId
,# teardown
,ok 362 should be equal
,ok 363 should be equal
,# setup
,# 102. can create servers manager
,# teardown
,ok 364 serversManager must not be null
ok 365 serversManager must be an object
,# setup
,# 103. calling stop without start causes error
,# teardown
,ok 366 We need to call start first
,# setup
,# 104. can start/stop servers manager
,# teardown
,ok 367 port must be in range
,# setup
,# 105. starting twice resolves with listening port
,# teardown
,ok 368 second start should return same port
,# setup
,# 106. terminateIncomingConnection will terminate a connection
,# teardown
,ok 369 we should be connected
,ok 370 now we are disconnected
,# setup
,# 107. terminate an Outgoing connection will terminate the server
,# teardown
,# setup
,# 108. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,# setup
,# 109. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 371 should be in started state
,# teardown
,ok 372 peer identifier should match
,ok 373 host address should match
,ok 374 port should match
,ok 375 host address should be null
,ok 376 port should should be null
,# setup
,ok 377 should not be in started state
,# 110. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 378 should be in started state
,# teardown
,ok 379 USN should have changed from the first one
,ok 380 when receiving the second byebye, the first USN should be already set
,# setup
,ok 381 should not be in started state
,# 111. messages with invalid location or USN should be ignored
,ok 382 should be in started state
,# teardown
,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
,ok 383 should not have emitted with invalid port
,WARN thaliWifiInfrastructure Received an invalid USN value: 
,ok 384 should not have emitted with invalid USN
,# setup
,ok 385 should not be in started state
,# 112. verify that Thali-specific messages are filtered correctly
,ok 386 should be in started state
,# teardown
,ok 387 irrelevant messages should be ignored
,ok 388 relevant messages should not be ignored
,ok 389 messages from this device should be ignored
,# setup
,ok 390 should not be in started state
,# 113. #startListeningForAdvertisements should fail if start not called
,ok 391 should be in started state
,# teardown
,ok 392 specific error should be returned
,# setup
,ok 393 should not be in started state
,# 114. #startUpdateAdvertisingAndListening should fail if start not called
,ok 394 should be in started state
,# teardown
,ok 395 specific error should be returned
,# setup
,ok 396 should not be in started state
,# 115. #start should fail if called twice in a row
,ok 397 should be in started state
,# teardown
,ok 398 specific error should be received
,# setup
,ok 399 should not be in started state
,# 116. should not be started after stop is called
,ok 400 should be in started state
,# teardown
,ok 401 should not be started
,ok 402 should not be listening
,ok 403 should not target listening
,ok 404 should not be advertising
,ok 405 should not target advertising
,# setup
,ok 406 should not be in started state
,# 117. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 407 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 408 specific error should be received
,# setup
,ok 409 should not be in started state
,# 118. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 410 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
,ok 411 specific error expected
,# setup
,ok 412 should not be in started state
,# 119. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 413 should be in started state
,# teardown
,ok 414 server should respond with code 200
,# setup
,ok 415 should not be in started state
,# 120. #stop can be called multiple times in a row
,ok 416 should be in started state
,# teardown
,ok 417 should be in stopped state
,ok 418 should still be in stopped state
,# setup
,ok 419 should not be in started state
,# 121. #startListeningForAdvertisements can be called multiple times in a row
,ok 420 should be in started state
,# teardown
,ok 421 should be in listening state
,ok 422 should still be in listening state
,# setup
,ok 423 should not be in started state
,# 122. #stopListeningForAdvertisements can be called multiple times in a row
,ok 424 should be in started state
,# teardown
,ok 425 should not be in listening state
,ok 426 should still not be in listening state
,# setup
,ok 427 should not be in started state
,# 123. #stopAdvertisingAndListening can be called multiple times in a row
,ok 428 should be in started state
,# teardown
,ok 429 should not be in advertising state
,ok 430 should still not be in advertising state
,# setup
,ok 431 should not be in started state
,# 124. functions are run from a queue in the right order
,ok 432 should be in started state
,# teardown
,ok 433 call order must match
,# setup
,ok 434 should not be in started state
,# 125. #ThaliPeerPoolDefault - single action
,# teardown
,ok 435 is an agent
,ok 436 enqueue is fine
,ok 437 Everything should be off the queue
,# setup
,# 126. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 438 is an agent
,ok 439 first enqueue is fine
,ok 440 is an agent
,ok 441 second enqueue is fine
,ok 442 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 443 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
