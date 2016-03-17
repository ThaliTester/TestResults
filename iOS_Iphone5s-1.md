#### Test 62754403d2f0346_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/88BC9B31-1503-4EF3-B8DD-99B9D50ACB80/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/88BC9B31-1503-4EF3-B8DD-99B9D50ACB80/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62754403d2f0346/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52193"
,(lldb)     command script import "/tmp/88BC9B31-1503-4EF3-B8DD-99B9D50ACB80/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 13:25:32.303 ThaliTest[1681:2671629] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/08C00BF0-9EFB-49E1-8270-6F7A80129AA0/Library/Cookies/Cookies.binarycookies
,2016-03-17 13:25:32.737 ThaliTest[1681:2671629] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 13:25:32.739 ThaliTest[1681:2671629] Multi-tasking -> Device: YES, App: YES
,2016-03-17 13:25:32.766 ThaliTest[1681:2671629] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 13:25:34.848 ThaliTest[1681:2671629] Using UIWebView
,2016-03-17 13:25:34.856 ThaliTest[1681:2671629] [CDVTimer][handleopenurl] 0.419974ms
,2016-03-17 13:25:34.865 ThaliTest[1681:2671629] [CDVTimer][intentandnavigationfilter] 7.847011ms
2016-03-17 13:25:34.865 ThaliTest[1681:2671629] [CDVTimer][gesturehandler] 0.365019ms
2016-03-17 13:25:34.866 ThaliTest[1681:2671629] [CDVTimer][TotalPluginStartup] 10.469019ms
,2016-03-17 13:25:42.044 ThaliTest[1681:2671629] Resetting plugins due to page load.
,2016-03-17 13:25:46.019 ThaliTest[1681:2671629] Finished load of: file:///var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/index.html
,2016-03-17 13:25:46.247 ThaliTest[1681:2671629] JXcore Cordova plugin initializing
,2016-03-17 13:25:46.248 ThaliTest[1681:2671821] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-17 13:26:01.960 ThaliTest[1681:2671821] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 13:26:01.960 ThaliTest[1681:2671821] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 13:26:01.960 ThaliTest[1681:2,671821] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 13:26:01.962 ThaliTest[1681:2671821] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B98F5747-F804-4598-9EEB-DAFB9B802D3C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
