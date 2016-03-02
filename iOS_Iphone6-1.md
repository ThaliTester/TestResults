#### Test 61432979123161a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/73342FE7-D680-4B7D-9BCD-3E35D0F26328/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/73342FE7-D680-4B7D-9BCD-3E35D0F26328/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50872"
,(lldb)     command script import "/tmp/73342FE7-D680-4B7D-9BCD-3E35D0F26328/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 18:35:41.713 ThaliTest[505:544251] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B1CF0CA-7037-4689-91AA-DFE6D6DDDFE9/Library/Cookies/Cookies.binarycookies
,2016-03-02 18:35:42.065 ThaliTest[505:544251] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 18:35:42.066 ThaliTest[505:544251] Multi-tasking -> Device: YES, App: YES
,2016-03-02 18:35:42.088 ThaliTest[505:544251] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 18:35:43.945 ThaliTest[505:544251] Using UIWebView
,2016-03-02 18:35:43.952 ThaliTest[505:544251] [CDVTimer][handleopenurl] 0.423968ms
,2016-03-02 18:35:43.961 ThaliTest[505:544251] [CDVTimer][intentandnavigationfilter] 8.432984ms
2016-03-02 18:35:43.961 ThaliTest[505:544251] [CDVTimer][gesturehandler] 0.366986ms
2016-03-02 18:35:43.962 ThaliTest[505:544251] [CDVTimer][TotalPluginStartup,] 10.854006ms
,2016-03-02 18:35:50.713 ThaliTest[505:544251] Resetting plugins due to page load.
,2016-03-02 18:35:54.158 ThaliTest[505:544251] Finished load of: file:///var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/index.html
,2016-03-02 18:35:54.382 ThaliTest[505:544251] JXcore Cordova plugin initializing
,2016-03-02 18:35:54.383 ThaliTest[505:544480] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 18:36:01.897 ThaliTest[505:544480] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 18:36:01.897 ThaliTest[505:544480] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-02 18:36:01.897 ThaliTest[505:544480,] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-02 18:36:01.901 ThaliTest[505:544480] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/316BF4D7-0E60-4BBA-85EE-F79A9FC22D45/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

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

,  ---

    operator: equal

,    expected: |-

,      null

,    actual: |-

,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 43 error should be null

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

,# setup

,ok 46 error should be null

,ok 47 error should be null

,# 12. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 48 error should be null

,  ---

    operator: equal

,    expected: |-
,
,      null

,    actual: |-
,
,      [Error: Unspecified Error with Radio infrastructure]

,  ...

,ok 49 error should be null

,WARN thaliWifiInfrastructure Got unexpected Wifi state: true

,not ok 50 error should be null

,  ---

    operator: equal
,
,    expected: |-

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

,  ---

    operator: throws

,    expected: |-

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
