#### Test 61362366b225741_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EDCD406B-6521-4658-A5AE-F24F01ACC017/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EDCD406B-6521-4658-A5AE-F24F01ACC017/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366b225741/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50609"
,(lldb)     command script import "/tmp/EDCD406B-6521-4658-A5AE-F24F01ACC017/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 11:12:23.336 ThaliTest[1026:1586961] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BC08206A-0998-4C01-9306-63D634A98A38/Library/Cookies/Cookies.binarycookies
,2016-03-10 11:12:23.648 ThaliTest[1026:1586961] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 11:12:23.649 ThaliTest[1026:1586961] Multi-tasking -> Device: YES, App: YES
,2016-03-10 11:12:23.669 ThaliTest[1026:1586961] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 11:12:25.226 ThaliTest[1026:1586961] Using UIWebView
,2016-03-10 11:12:25.233 ThaliTest[1026:1586961] [CDVTimer][handleopenurl] 0.428021ms
,2016-03-10 11:12:25.241 ThaliTest[1026:1586961] [CDVTimer][intentandnavigationfilter] 7.296979ms
2016-03-10 11:12:25.242 ThaliTest[1026:1586961] [CDVTimer][gesturehandler] 0.374019ms
2016-03-10 11:12:25.242 ThaliTest[1026:1586961] [CDVTimer][TotalPluginS,tartup] 9.980977ms
,2016-03-10 11:12:31.230 ThaliTest[1026:1586961] Resetting plugins due to page load.
,2016-03-10 11:12:34.280 ThaliTest[1026:1586961] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/index.html
,2016-03-10 11:12:34.491 ThaliTest[1026:1586961] JXcore Cordova plugin initializing
,2016-03-10 11:12:34.494 ThaliTest[1026:1587172] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 11:12:46.823 ThaliTest[1026:1587172] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 11:12:46.824 ThaliTest[1026:1587172] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 11:12:46.824 ThaliTest[1026:1,587172] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-10 11:12:46.825 ThaliTest[1026:1587172] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/AD0953C4-2683-43B7-A20B-4904FF3CC05B/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,# setup

,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 81 error should be null

,ok 82 error should be null

,# 19. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-10 11:14:45.428 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements
,2016-03-10 11:14:45.430 ThaliTest[1026:1587172] multipeer manager: start client restart timer: 0x17dc6c00
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-10 11:14:45.433 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements: success
,ok 83 Can call startListeningForAdvertisements without error

,2016-03-10 11:14:45.445 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
,2016-03-10 11:14:45.448 ThaliTest[1026:1587172] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:45.451 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 84 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-10 11:14:45.781 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:45.783 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 85 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:45.786 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:45.786 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:45.787 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: success
,ok 86 Should be able to call stopAdvertisingAndListening in teardown

,# 20. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-10 11:14:46.305 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements
2016-03-10 11:14:46.306 ThaliTest[1026:1587172] multipeer manager: start client restart timer: 0x17dc6c00
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 11:14:46.308 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements: success
,ok 87 Can call startListeningForAdvertisements without error

2016-03-10 11:14:46.312 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-10 11:14:46.313 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-10 11:14:46.415 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
2016-03-10 11:14:46.416 ThaliTest[1026:1587172] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:46.417 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 89 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:46.421 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
2016-03-10 11:14:46.422 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:46.423 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: suc,cess
ok 90 Should be able to call stopAdvertisingAndListening in teardown

,# 21. Can call start/stopUpdateAdvertisingAndListening
,
,# teardown

,2016-03-10 11:14:49.059 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:49.060 ThaliTest[1026:1587172] server: starting 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:1
2016-03-10 11:14:49.061 ThaliTest[1026:1587172] multipeer m,anager: start client restart timer: 0x17dc6c00
2016-03-10 11:14:49.061 ThaliTest[1026:1587172] THEMultipeerManager initialized peer 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:1
2016-03-10 11:14:49.062 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening: success
ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:49.066 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
2016-03-10 11:14:49.066 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:49.067 ThaliTest[1026:1587172] multipeer manager: stop client timer
20,16-03-10 11:14:49.068 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: success
ok 92 Can call stopAdvertisingAndListening without error

# setup

,2016-03-10 11:14:49.360 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-10 11:14:49.362 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 93 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:49.365 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:49.365 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:49.366 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: success
ok 94 Should be able to call stopAdvertisingAndListening in teardown

,# 22. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-10 11:14:52.006 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:52.007 ThaliTest[1026:1587172] server: starting 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:2
2016-03-10 11:14:52.008 ThaliTest[1026:1587172] multipeer m,anager: start client restart timer: 0x17dc6c00
2016-03-10 11:14:52.008 ThaliTest[1026:1587172] THEMultipeerManager initialized peer 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:2
2016-03-10 11:14:52.009 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 95 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:52.013 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:52.014 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:52.014 ThaliTest[1026:1587172] multipeer manager: stop client ti,mer
2016-03-10 11:14:52.015 ThaliTest[1026:1587172] server: starting 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:3
2016-03-10 11:14:52.015 ThaliTest[1026:1587172] multipeer manager: start client restart timer: 0x17dc6c00
2016-03-10 11:14:52.016 ThaliTest[1026:,1587172] THEMultipeerManager initialized peer 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:3
2016-03-10 11:14:52.016 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening: success
ok 96 Can call startUpdateAdvertisingAndListening twice without error,

# setup

,2016-03-10 11:14:52.144 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 11:14:52.146 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 97 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:52.148 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
2016-03-10 11:14:52.149 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
,2016-03-10 11:14:52.150 ThaliTest[1026:1587172] multipeer manager: stop client timer
,2016-03-10 11:14:52.151 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: success
ok 98 Should be able to call stopAdvertisingAndListening in teardown

,# 23. peerAvailabilityChange is called

,# teardown

,2016-03-10 11:14:52.631 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:52.632 ThaliTest[1026:1587172] server: starting 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
2016-03-10 11:14:52.632 ThaliTest[1026:1587172] multipeer m,anager: start client restart timer: 0x17dc6c00
2016-03-10 11:14:52.633 ThaliTest[1026:1587172] THEMultipeerManager initialized peer 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4
2016-03-10 11:14:52.633 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 99 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-10 11:14:52.635 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 11:14:52.638 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements: success
ok 100 Can call startListeningForAdvertisements without error

,2016-03-10 11:14:54.846 ThaliTest[1026:1586961] client: found new peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
,ok 101 peers must be an array

ok 102 peers must not be zero-length

ok 103 peer must have peerIdentifier

ok 104 peerIdentifier must be a string

,ok 105 peer must have peerAvailable

,ok 106 peer must have pleaseConnect

,# setup

,2016-03-10 11:14:56.109 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}

,2016-03-10 11:14:56.111 ThaliTest[1026:1587172] jxcore: stopListeningForAdvertisements: success
,ok 107 Should be able to call stopListeningForAdvertisments in teardown

,2016-03-10 11:14:56.114 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening
,2016-03-10 11:14:56.115 ThaliTest[1026:1587172] THEMultipeerManager stopping peer
2016-03-10 11:14:56.115 ThaliTest[1026:1587172] multipeer manager: stop client timer
2016-03-10 11:14:56.116 ThaliTest[1026:1587172] jxcore: stopAdvertisingAndListening: success
ok 108 Should be able to call stopAdvertisingAndListening in teardown

,# 24. Can connect to a remote peer

,# teardown

,2016-03-10 11:14:56.364 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening
2016-03-10 11:14:56.364 ThaliTest[1026:1587172] server: starting 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
2016-03-10 11:14:56.365 ThaliTest[1026:1587172] multipeer m,anager: start client restart timer: 0x17dc6c00
2016-03-10 11:14:56.366 ThaliTest[1026:1587172] THEMultipeerManager initialized peer 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5
2016-03-10 11:14:56.366 ThaliTest[1026:1587172] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 Can call startUpdateAdvertisingAndListening without error

,2016-03-10 11:14:56.369 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-10 11:14:56.371 ThaliTest[1026:1587172] jxcore: startListeningForAdvertisements: success
ok 110 Can call startListeningForAdv,ertisements without error

,2016-03-10 11:14:57.251 ThaliTest[1026:1586961] client: found new peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
2016-03-10 11:14:57.253 ThaliTest[1026:1587172] jxcore: connect 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
2016-03-10 11:14:57.253 ThaliTest[1026:1587172] client: server will connect
,2016-03-10 11:14:57.254 ThaliTest[1026:1587172] client session: reverseConnect
2016-03-10 11:14:57.254 ThaliTest[1026:1587172] client session: stateChange:0->1 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
,2016-03-10 11:14:57.468 ThaliTest[1026:1586961] multipeer session: reset timer
2016-03-10 11:14:57.469 ThaliTest[1026:1586961] server: rejecting invitation from 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2 due to previous generation (3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:5 != 3B096B8E-DEC6-4495-9FE6-71F5C2A3A315:4)
,2016-03-10 11:14:57.933 ThaliTest[1026:1587447] client session: not connected 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
2016-03-10 11:14:57.933 ThaliTest[1026:1587447] client session: onLinkFailure: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2
2016-03-10 11:14:57.9,34 ThaliTest[1026:1587447] client session: disconnect
2016-03-10 11:14:57.934 ThaliTest[1026:1587447] client session: stateChange:1->0 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:4
2016-03-10 11:14:57.935 ThaliTest[1026:1587447] client session: no connect callb,ack (server initiated)
,2016-03-10 11:15:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:15:16.385 ThaliTest[1026:1586961] client: found updated peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:15:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:15:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:15:56.366 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:15:56.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:16:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:16:16.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:16:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:16:36.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:16:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:16:56.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:17:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:17:16.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:17:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:17:36.389 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:17:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:17:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:18:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:18:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:18:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:18:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:18:56.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:19:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:19:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:19:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:19:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:19:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:19:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:20:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:20:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:20:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:20:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:20:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:20:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:21:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:21:16.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:21:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:21:36.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:21:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:21:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:22:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:22:16.386 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:22:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:22:36.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:22:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:22:56.382 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:23:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:23:16.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:23:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:23:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:23:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:23:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:24:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:24:16.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:24:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:24:36.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:24:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:24:56.386 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:25:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:25:16.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:25:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:25:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:25:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:25:56.386 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:26:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:26:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:26:36.366 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:26:36.382 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:26:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:26:56.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:27:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:27:16.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:27:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:27:36.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:27:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:27:56.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:28:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:28:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:28:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:28:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:28:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:29:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:29:16.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:29:36.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:29:36.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:29:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:29:56.385 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:30:16.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:30:16.383 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:30:36.366 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:30:36.382 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:30:56.367 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:30:56.384 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:31:16.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:31:16.333 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:31:36.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:31:36.334 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:31:56.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:31:56.332 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:32:16.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:32:16.331 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:32:36.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:32:36.335 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:32:56.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:32:56.333 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5
,2016-03-10 11:33:16.315 ThaliTest[1026:1586961] multipeer manager: restart client
,2016-03-10 11:33:16.334 ThaliTest[1026:1586961] client: found existing peer: 9422AEAE-6CC5-4D20-97AE-1094E9AF1BD2:5

```
