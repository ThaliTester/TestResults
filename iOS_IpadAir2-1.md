#### Test 60124347e678b8e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/755DF606-3CFD-49AB-8000-2BA402FC67D7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/755DF606-3CFD-49AB-8000-2BA402FC67D7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/60124347e678b8e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51116"
,(lldb)     command script import "/tmp/755DF606-3CFD-49AB-8000-2BA402FC67D7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-10 19:27:00.341 ThaliTest[1104:1680674] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C552A30C-C528-4041-8086-EEC1C30B12AC/Library/Cookies/Cookies.binarycookies
,2016-03-10 19:27:00.623 ThaliTest[1104:1680674] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-10 19:27:00.624 ThaliTest[1104:1680674] Multi-tasking -> Device: YES, App: YES
,2016-03-10 19:27:00.640 ThaliTest[1104:1680674] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-10 19:27:02.437 ThaliTest[1104:1680674] Using UIWebView
,2016-03-10 19:27:02.443 ThaliTest[1104:1680674] [CDVTimer][handleopenurl] 0.346005ms
,2016-03-10 19:27:02.450 ThaliTest[1104:1680674] [CDVTimer][intentandnavigationfilter] 6.972015ms
,2016-03-10 19:27:02.451 ThaliTest[1104:1680674] [CDVTimer][gesturehandler] 0.349998ms
,2016-03-10 19:27:02.451 ThaliTest[1104:1680674] [CDVTimer][TotalPluginStartup] 9.213984ms
,2016-03-10 19:27:09.441 ThaliTest[1104:1680674] Resetting plugins due to page load.
,2016-03-10 19:27:13.138 ThaliTest[1104:1680674] Finished load of: file:///var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/index.html
,2016-03-10 19:27:13.347 ThaliTest[1104:1680674] JXcore Cordova plugin initializing
,2016-03-10 19:27:13.348 ThaliTest[1104:1680939] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-10 19:27:19.987 ThaliTest[1104:1680939] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-10 19:27:19.988 ThaliTest[1104:1680939] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-10 19:27:19.988 ThaliTest[1104:1680939] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-10 19:27:19.990 ThaliTest[1104:1680939] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/59860238-38EA-4AC5-9D44-F2E28AF2D535/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 45 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 46 error should be null

  ---

,    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

  ...

,ok 47 error should be null

,# setup

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 50 error should be null

  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 51 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 52 error should be null

,  ---

    operator: equal

,    expected: |-

,      null
,
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

  ---

,    operator: throws

    expected: |-

,      undefined

,    actual: |-
,
,      [TypeError: undefined must be a string]

,  ...

,# setup

,ok 77 error should be null

,ok 78 error should be null

,# 20. wifi peer is marked unavailable if announcements stop

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true


```
