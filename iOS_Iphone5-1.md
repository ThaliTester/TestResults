#### Test 63036995fb62ea7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/46ED13A2-55F3-4294-BA21-BEE8260B5193/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/46ED13A2-55F3-4294-BA21-BEE8260B5193/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63036995fb62ea7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51048"
,(lldb)     command script import "/tmp/46ED13A2-55F3-4294-BA21-BEE8260B5193/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 07:09:26.601 ThaliTest[1231:2759421] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3FBDAA68-A081-4803-A856-3097C21CDFAE/Library/Cookies/Cookies.binarycookies
,2016-03-17 07:09:26.724 ThaliTest[1231:2759421] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 07:09:26.726 ThaliTest[1231:2759421] Multi-tasking -> Device: YES, App: YES
,2016-03-17 07:09:26.748 ThaliTest[1231:2759421] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 07:09:28.806 ThaliTest[1231:2759421] Using UIWebView
,2016-03-17 07:09:28.811 ThaliTest[1231:2759421] [CDVTimer][handleopenurl] 0.317991ms
,2016-03-17 07:09:28.817 ThaliTest[1231:2759421] [CDVTimer][intentandnavigationfilter] 5.137980ms
2016-03-17 07:09:28.818 ThaliTest[1231:2759421] [CDVTimer][gesturehandler] 0.259042ms
2016-03-17 07:09:28.818 ThaliTest[1231:2759421] [CDVTimer][TotalPluginS,tartup] 6.748021ms
,2016-03-17 07:09:37.372 ThaliTest[1231:2759421] Resetting plugins due to page load.
,2016-03-17 07:09:41.427 ThaliTest[1231:2759421] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/index.html
,2016-03-17 07:09:41.633 ThaliTest[1231:2759421] JXcore Cordova plugin initializing
,2016-03-17 07:09:41.635 ThaliTest[1231:2759612] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-17 07:10:06.696 ThaliTest[1231:2759612] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 07:10:06.697 ThaliTest[1231:2759612] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 07:10:06.698 ThaliTest[1231:2759612] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 07:10:06.700 ThaliTest[1231:2759612] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D54B8D7-FD68-4980-B09A-D185ED9647C3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
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
,ok 93 error should be null
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
ok 101 error should be null
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
,# 33. #generatePreambleAndBeacons bad args
,# teardown
,ok 130 publicKeysToNotify cannot be null
,ok 131 ecdh for local device cannot be null
,ok 132 milliseconds cannot be less than 0
,ok 133 milliseconds cannot be 0
,ok 134 milliseconds cannot be greater than one_day
,# setup
,# 34. #generatePreambleAndBeacons empty keys to notify
,# teardown
,ok 135 should be equal
,# setup
,# 35. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 136 should be equal
,ok 137 should be equal
,ok 138 (unnamed assert)
,ok 139 should be equal
,# setup
,# 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 140 should throw
,# setup
,# 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 141 Preamble expiration must be a 64 bit integer
,# setup
,# 38. #parseBeacons expiration out of range lower
,# teardown
,ok 142 Expiration out of range
,# setup
,# 39. #parseBeacons expiration out of range lower
,# teardown
,ok 143 Expiration out of range
,# setup
,# 40. #parseBeacons no beacons returns null
,# teardown
,ok 144 should be equal
,# setup
,# 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 145 Malformed encrypted beacon key ID
,# setup
,# 42. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 146 should be equal
,# setup
,# 43. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 147 should be equal
,ok 148 should be equal
,# setup
,# 44. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 149 should be equal
,ok 150 should be equal
,# setup
,# 45. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 151 should be equal
,ok 152 (unnamed assert)
,# setup
,# 46. #parseBeacons with beacons both for and not for the user
,# teardown
,ok 153 should be equal
,ok 154 (unnamed assert)
,# setup
,# 47. Start and stop ThaliNotificationServer
,# teardown
,ok 155 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 156 ThaliMobile.StopAdvertisingAndListening should be called once
,# setup
,# 48. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 157 StartUpdateAdvertisingAndListening should not be called
,ok 158 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 159 no error
,ok 160 should be 204
,# setup
,# 49. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 161 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 50. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 162 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 51. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 163 no error
,ok 164 should be 200
,ok 165 should be equal
,ok 166 should be equal
,ok 167 (unnamed assert)
,ok 168 no error
,ok 169 should be 204
,# setup
,# 52. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 170 error should be null
,ok 171 should be 204
,# setup
,# 53. Make an HTTP request to /NotificationBeacons before calling start
,# teardown
,ok 172 should be 404
,# setup
,# 54. #testThaliPeerAction - test getters
,# teardown
,ok 173 getPeerIdentifier
,ok 174 getConnectionType
,ok 175 getActionType
,ok 176 getActionState
,# setup
,# 55. #testThaliPeerAction - start and kill
,# teardown
,ok 177 initial state
,ok 178 after start
,ok 179 after kill
,# setup
,# 56. #testThaliPeerAction - double start
,# teardown
,ok 180 should be equal
,# setup
,# 57. #testThaliPeerAction - start after kill
,# teardown
,ok 181 clean kill
,ok 182 should be equal
,# setup
,# 58. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 183 should not be equal
,# setup
,# 59. Test PeerConnectionInformation basics
,# teardown
,ok 184 getHostAddress works
,ok 185 getPortNumber works
,ok 186 getSuggestedTCPTimeout works
,# setup
,# 60. Test PeerDictionary basic functionality
,# teardown
,ok 187 Entry counter must be 1
,ok 188 Size must be 1
,ok 189 Entry counter must be 2
,ok 190 Size must be 2
,ok 191 Entry2 should not be found
,ok 192 Size must be 1
,ok 193 Size must be 0
,ok 194 entry not found must be thrown
,# setup
,# 61. Test PeerDictionary with multiple entries.
,# teardown
,ok 195 Size must be100
,ok 196 Entries between 20 and MAXSIZE + 20 should exist
,ok 197 WAITING state entry should not be removed
,# setup
,# 62. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 198 Entries between 6 and MAXSIZE + 4 should exist
,ok 199 Size should be MAXSIZE
,ok 200 Size should be MAXSIZE+6
,# setup
,# 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 201 WAITING state entry should not be removed
,ok 202 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 203 Size should be MAXSIZE
,ok 204 entryCounter should be MAXSIZE+6
,# setup
,# 64. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 205 Kill should be called once
,ok 206 Size should be 100
,# setup
,# 65. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 207 null arg
,ok 208 wrong arg type
,ok 209 wrong state
,# setup
,# 66. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 210 good enqueue
,ok 211 should be equal
,# setup
,# 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 212 good enqueue
,ok 213 2nd good enqueue
,ok 214 we are in the pool
,ok 215 We are out of the pool
,ok 216 Action was killed
,ok 217 The original kill was called too
,ok 218 second item is still in queue
,# setup
,# 68. compareBufferArrays
,# teardown
,ok 219 should throw
,ok 220 should throw
,ok 221 (unnamed assert)
,ok 222 (unnamed assert)
,ok 223 (unnamed assert)
,ok 224 (unnamed assert)
,ok 225 (unnamed assert)
,# setup
,# 69. Call start twice and get error
,# teardown
,ok 226 should throw
,# setup
,# 70. Start and make sure it runs
,# teardown
,# setup
,# 71. Make sure getTimeWhenRun is right after start
,# teardown
,ok 227 (unnamed assert)
,# setup
,# 72. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 228 should be equal
,# setup
,# 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 229 should be equal
,ok 230 should be equal
,ok 231 should throw
,# setup
,# 74. Test TransientState
,# teardown
,ok 232 should throw
,ok 233 should throw
,ok 234 should be equal
,ok 235 should be equal
,ok 236 should be equal
,ok 237 should be equal
,ok 238 (unnamed assert)
,ok 239 (unnamed assert)
,# setup
,# 75. No peers and empty database
,# teardown
,ok 240 verify failed
,ok 241 constructor called once
,ok 242 constructor called with right args
,ok 243 match start arg
,ok 244 start called once
,ok 245 stop called once
,ok 246 stop after start
,# setup
,# 76. One peer and empty DB
,# teardown
,ok 247 verify failed
,ok 248 constructor called once
,ok 249 constructor called with right args
,ok 250 match start arg
,ok 251 start called once
,ok 252 stop called once
,ok 253 stop after start
,# setup
,# 77. One peer with _Local set behind current seq
,# teardown
,ok 254 verify failed
,ok 255 constructor called once
,ok 256 constructor called with right args
,ok 257 match start arg
,ok 258 start called once
,ok 259 stop called once
,ok 260 stop after start
,# setup
,# 78. One peer with _Local set equal to current seq
,# teardown
,ok 261 verify failed
,ok 262 constructor called once
,ok 263 constructor called with right args
,ok 264 match start arg
,ok 265 start called once
,ok 266 stop called once
,ok 267 stop after start
,# setup
,# 79. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,ok 268 verify failed
,ok 269 constructor called once
,ok 270 constructor called with right args
,ok 271 match start arg
,ok 272 start called once
,ok 273 stop called once
,ok 274 stop after start
,# setup
,# 80. Three peers, one not in DB, one behind and one ahead
,# teardown
,ok 275 verify failed
,ok 276 constructor called once
,ok 277 constructor called with right args
,ok 278 match start arg
,ok 279 start called once
,ok 280 stop called once
,ok 281 stop after start
,# setup
,# 81. More than maximum peers, make sure we only send maximum allowed
,# teardown
,ok 282 verify failed
,ok 283 constructor called once
,ok 284 constructor called with right args
,ok 285 match start arg
,ok 286 start called once
,ok 287 stop called once
,ok 288 stop after start
,# setup
,# 82. two peers with empty DB, update the doc
,# teardown
,ok 289 verify failed
,ok 290 constructor called once
,ok 291 constructor called with right args
,ok 292 last start before stop
,ok 293 empty first start
,ok 294 full second start
,ok 295 only 2 timers
,# setup
,# 83. add doc and make sure tokens refresh when they expire
,# teardown
,ok 296 verify failed
,ok 297 constructor called once
,ok 298 constructor called with right args
,ok 299 start before stop
,ok 300 We got at least 3 calls to start
,ok 301 at least 3
,ok 302 default 1
,ok 303 1 run
,ok 304 default 2
,ok 305 2 run
,ok 306 default 3
,# setup
,# 84. start and stop and start and stop
,# teardown
,ok 307 start out null
,ok 308 back to null
,ok 309 still null
,ok 310 verify failed
,ok 311 constructor called once
,ok 312 constructor called with right args
,ok 313 first start before first stop
,ok 314 first stop before second start
,ok 315 second start before second stop
,# setup
,# 85. two identical starts in a row
,# teardown
,ok 316 verify failed
,ok 317 constructor called once
,ok 318 constructor called with right args
,ok 319 (unnamed assert)
,# setup
,# 86. two different starts in a row
,# teardown
,ok 320 verify failed
,ok 321 constructor called once
,ok 322 constructor called with right args
,ok 323 (unnamed assert)
,ok 324 (unnamed assert)
,# setup
,# 87. two stops and a start and two stops
,# teardown
,ok 325 verify failed
,ok 326 constructor called once
,ok 327 constructor called with right args
,ok 328 start before stop
,# setup
,# 88. we properly enqueue requests so no then needed
,# teardown
,ok 329 verify failed
,ok 330 constructor called once
,ok 331 constructor called with right args
,ok 332 start before stop
,# setup
,# 89. test calculateSeqPointKeyId
,# teardown
,ok 333 should be equal
,ok 334 should be equal
,# setup
,# 90. can create servers manager
,# teardown
,ok 335 serversManager must not be null
,ok 336 serversManager must be an object
,# setup
,# 91. calling stop without start causes error
,# teardown
,ok 337 We need to call start first
,# setup
,# 92. can start/stop servers manager
,# teardown
,ok 338 port must be in range
,# setup
,# 93. starting twice resolves with listening port
,# teardown
,ok 339 second start should return same port
,# setup
,# 94. terminateIncomingConnection will terminate a connection
,# teardown
,ok 340 we should be connected
,ok 341 now we are disconnected
,# setup
,# 95. terminate an Outgoing connection will terminate the server
,# teardown
,# setup
,# 96. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,# setup
,# 97. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 342 should be in started state
,# teardown
,ok 343 peer identifier should match
,ok 344 host address should match
,ok 345 port should match
,ok 346 host address should be null
,ok 347 port should should be null
,# setup
,ok 348 should not be in started state
,# 98. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 349 should be in started state
,# teardown
,ok 350 USN should have changed from the first one
,ok 351 when receiving the second byebye, the first USN should be already set
,# setup
,ok 352 should not be in started state
,# 99. messages with invalid location or USN should be ignored
,ok 353 should be in started state
,# teardown
,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
,ok 354 should not have emitted with invalid port
,WARN thaliWifiInfrastructure Received an invalid USN value: 
,ok 355 should not have emitted with invalid USN
,# setup
,ok 356 should not be in started state
,# 100. verify that Thali-specific messages are filtered correctly
,ok 357 should be in started state
,# teardown
,ok 358 irrelevant messages should be ignored
,ok 359 relevant messages should not be ignored
,ok 360 messages from this device should be ignored
,# setup
,ok 361 should not be in started state
,# 101. #startListeningForAdvertisements should fail if start not called
,ok 362 should be in started state
,# teardown
,ok 363 specific error should be returned
,# setup
,ok 364 should not be in started state
,# 102. #startUpdateAdvertisingAndListening should fail if start not called
,ok 365 should be in started state
,# teardown
,ok 366 specific error should be returned
,# setup
,ok 367 should not be in started state
,# 103. #start should fail if called twice in a row
,ok 368 should be in started state
,# teardown
,ok 369 specific error should be received
,# setup
,ok 370 should not be in started state
,# 104. should not be started after stop is called
,ok 371 should be in started state
,# teardown
,ok 372 should not be started
,ok 373 should not be listening
,ok 374 should not target listening
,ok 375 should not be advertising
,ok 376 should not target advertising
,# setup
,ok 377 should not be in started state
,# 105. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 378 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 379 specific error should be received
,# setup
,ok 380 should not be in started state
,# 106. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 381 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
,ok 382 specific error expected
,# setup
,ok 383 should not be in started state
,# 107. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 384 should be in started state
,# teardown
,ok 385 server should respond with code 200
,# setup
,ok 386 should not be in started state
,# 108. #stop can be called multiple times in a row
,ok 387 should be in started state
,# teardown
,ok 388 should be in stopped state
,ok 389 should still be in stopped state
,# setup
,ok 390 should not be in started state
,# 109. #startListeningForAdvertisements can be called multiple times in a row
,ok 391 should be in started state
,# teardown
,ok 392 should be in listening state
,ok 393 should still be in listening state
,# setup
,ok 394 should not be in started state
,# 110. #stopListeningForAdvertisements can be called multiple times in a row
,ok 395 should be in started state
,# teardown
,ok 396 should not be in listening state
,ok 397 should still not be in listening state
,# setup
,ok 398 should not be in started state
,# 111. #stopAdvertisingAndListening can be called multiple times in a row
,ok 399 should be in started state
,# teardown
,ok 400 should not be in advertising state
,ok 401 should still not be in advertising state
,# setup
,ok 402 should not be in started state
,# 112. functions are run from a queue in the right order
,ok 403 should be in started state
,# teardown
,ok 404 call order must match
,# setup
,ok 405 should not be in started state
,# 113. #ThaliPeerPoolDefault - single action
,# teardown
,ok 406 is an agent
,ok 407 enqueue is fine
,ok 408 Everything should be off the queue
,# setup
,# 114. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 409 is an agent
,ok 410 first enqueue is fine
,ok 411 is an agent
,ok 412 second enqueue is fine
,ok 413 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 414 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
