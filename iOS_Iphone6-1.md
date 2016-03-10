#### Test 60124347e678b8e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FE7AF4E9-09B2-454B-A3FB-0280875EEEA2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FE7AF4E9-09B2-454B-A3FB-0280875EEEA2/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51118"
,(lldb)     command script import "/tmp/FE7AF4E9-09B2-454B-A3FB-0280875EEEA2/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 19:27:00.310 ThaliTest[1067:1642206] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2273E6D7-730C-453A-9F30-D4B6298EB9A5/Library/Cookies/Cookies.binarycookies
,2016-03-10 19:27:00.608 ThaliTest[1067:1642206] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 19:27:00.609 ThaliTest[1067:1642206] Multi-tasking -> Device: YES, App: YES
,2016-03-10 19:27:00.626 ThaliTest[1067:1642206] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 19:27:02.385 ThaliTest[1067:1642206] Using UIWebView
,2016-03-10 19:27:02.392 ThaliTest[1067:1642206] [CDVTimer][handleopenurl] 0.555038ms
,2016-03-10 19:27:02.400 ThaliTest[1067:1642206] [CDVTimer][intentandnavigationfilter] 7.389963ms
2016-03-10 19:27:02.401 ThaliTest[1067:1642206] [CDVTimer][gesturehandler] 0.388980ms
2016-03-10 19:27:02.401 ThaliTest[1067:1642206] [CDVTimer][TotalPluginS,tartup] 10.000050ms
,2016-03-10 19:27:09.382 ThaliTest[1067:1642206] Resetting plugins due to page load.
,2016-03-10 19:27:12.842 ThaliTest[1067:1642206] Finished load of: file:///var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/index.html
,2016-03-10 19:27:13.073 ThaliTest[1067:1642206] JXcore Cordova plugin initializing
,2016-03-10 19:27:13.075 ThaliTest[1067:1642444] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 19:27:20.429 ThaliTest[1067:1642444] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-10 19:27:20.429 ThaliTest[1067:1642444] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 19:27:20.429 ThaliTest[1067:1642444] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 19:27:20.432 ThaliTest[1067:1642444] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F65F7D82-62E7-4272-AE69-9BED3D145F51/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded

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

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 44 error should be null

,  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 45 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 46 error should be null

,  ---

    operator: equal
,
,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 47 error should be null

,# setup

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 50 error should be null

,  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 51 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 52 error should be null

  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

  ...

,ok 53 error should be null

,# setup

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

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,ok 67 called only once

,ok 68 discovery state matches

,ok 69 advertising state matches

,# setup

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

,not ok 76 network status should have certain non-empty properties

,  ---

    operator: throws

,    expected: |-

,      undefined

,    actual: |-

,      [TypeError: undefined must be a string]

,  ...

,# setup

,ok 77 error should be null

,ok 78 error should be null

,# 20. wifi peer is marked unavailable if announcements stop

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true


```
