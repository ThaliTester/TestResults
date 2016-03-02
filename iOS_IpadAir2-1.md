#### Test 613623661dfc74c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623661dfc74c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/BC457165-DF6C-4E29-BFB3-E89B951CEBFD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BC457165-DF6C-4E29-BFB3-E89B951CEBFD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623661dfc74c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623661dfc74c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50423"
,(lldb)     command script import "/tmp/BC457165-DF6C-4E29-BFB3-E89B951CEBFD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 13:02:02.660 ThaliTest[474:502048] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CE342E5-0270-4A7D-A5BB-7F646EA8A150/Library/Cookies/Cookies.binarycookies
,2016-03-02 13:02:02.982 ThaliTest[474:502048] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 13:02:02.982 ThaliTest[474:502048] Multi-tasking -> Device: YES, App: YES
,2016-03-02 13:02:02.997 ThaliTest[474:502048] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 13:02:04.755 ThaliTest[474:502048] Using UIWebView
,2016-03-02 13:02:04.762 ThaliTest[474:502048] [CDVTimer][handleopenurl] 0.376999ms
,2016-03-02 13:02:04.769 ThaliTest[474:502048] [CDVTimer][intentandnavigationfilter] 7.358015ms
,2016-03-02 13:02:04.770 ThaliTest[474:502048] [CDVTimer][gesturehandler] 0.311017ms
,2016-03-02 13:02:04.770 ThaliTest[474:502048] [CDVTimer][TotalPluginStartup] 9.555042ms
,2016-03-02 13:02:12.070 ThaliTest[474:502048] Resetting plugins due to page load.
,2016-03-02 13:02:15.522 ThaliTest[474:502048] Finished load of: file:///var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/index.html
,2016-03-02 13:02:15.736 ThaliTest[474:502048] JXcore Cordova plugin initializing
,2016-03-02 13:02:15.737 ThaliTest[474:502295] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 13:02:27.452 ThaliTest[474:502295] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 13:02:27.452 ThaliTest[474:502295] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-02 13:02:27.453 ThaliTest[474:502295] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-02 13:02:27.454 ThaliTest[474:502295] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B0241D66-7163-4E61-BBD8-269A811DF1EB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
