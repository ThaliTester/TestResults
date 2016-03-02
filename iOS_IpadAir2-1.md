#### Test 613623660556c10_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/CE6975E0-B6E7-4695-AA7D-D3D3F5F24BB9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CE6975E0-B6E7-4695-AA7D-D3D3F5F24BB9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623660556c10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50266"
,(lldb)     command script import "/tmp/CE6975E0-B6E7-4695-AA7D-D3D3F5F24BB9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 09:53:21.263 ThaliTest[463:483129] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A38C17C-97C9-44F6-B096-1F89F89E2E1B/Library/Cookies/Cookies.binarycookies
,2016-03-02 09:53:21.647 ThaliTest[463:483129] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 09:53:21.649 ThaliTest[463:483129] Multi-tasking -> Device: YES, App: YES
,2016-03-02 09:53:21.668 ThaliTest[463:483129] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 09:53:23.693 ThaliTest[463:483129] Using UIWebView
,2016-03-02 09:53:23.699 ThaliTest[463:483129] [CDVTimer][handleopenurl] 0.395000ms
,2016-03-02 09:53:23.707 ThaliTest[463:483129] [CDVTimer][intentandnavigationfilter] 6.901026ms
,2016-03-02 09:53:23.708 ThaliTest[463:483129] [CDVTimer][gesturehandler] 0.357985ms
,2016-03-02 09:53:23.708 ThaliTest[463:483129] [CDVTimer][TotalPluginStartup] 9.320974ms
,2016-03-02 09:53:31.168 ThaliTest[463:483129] Resetting plugins due to page load.
,2016-03-02 09:53:34.424 ThaliTest[463:483129] Finished load of: file:///var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/index.html
,2016-03-02 09:53:34.658 ThaliTest[463:483129] JXcore Cordova plugin initializing
,2016-03-02 09:53:34.659 ThaliTest[463:483361] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 09:53:46.395 ThaliTest[463:483361] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 09:53:46.396 ThaliTest[463:483361] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-02 09:53:46.396 ThaliTest[463:483361] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":true,"bluetoothLowEnergy":false,"bssidName":null,"cellular":true,"bluetooth":true}

,2016-03-02 09:53:46.397 ThaliTest[463:483361] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B603E572-89AD-46E2-9BDB-CF4DBEB7545C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 42 error should be null

  ---

,    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 43 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 44 error should be null

  ---

,    operator: equal

,    expected: |-

,      null
,
    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 45 error should be null

,# setup

,ok 46 error should be null

,ok 47 error should be null

,# 12. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 48 error should be null

,  ---

,    operator: equal

    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

  ...

,ok 49 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 50 error should be null

  ---

,    operator: equal

    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 51 error should be null

,# setup

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

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,ok 65 called only once

,ok 66 discovery state matches

,ok 67 advertising state matches

,# setup

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

,not ok 74 network status should have certain non-empty properties

  ---

,    operator: throws

,    expected: |-
,
,      undefined

,    actual: |-

,      [TypeError: undefined must be a string]

,  ...

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 18. wifi peer is marked unavailable if announcements stop

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true


```
