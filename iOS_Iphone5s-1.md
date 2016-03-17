#### Test 627544039ea0a99_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/627544039ea0a99/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D59F85AC-4A3E-4B53-B629-1E576B29BEA9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D59F85AC-4A3E-4B53-B629-1E576B29BEA9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/627544039ea0a99/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/627544039ea0a99/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52097"
,(lldb)     command script import "/tmp/D59F85AC-4A3E-4B53-B629-1E576B29BEA9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 12:55:08.692 ThaliTest[1673:2667860] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9CAE8B2A-8B30-4FE8-A3B8-AC70A8AE0865/Library/Cookies/Cookies.binarycookies
,2016-03-17 12:55:09.056 ThaliTest[1673:2667860] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 12:55:09.057 ThaliTest[1673:2667860] Multi-tasking -> Device: YES, App: YES
,2016-03-17 12:55:09.082 ThaliTest[1673:2667860] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 12:55:10.984 ThaliTest[1673:2667860] Using UIWebView
,2016-03-17 12:55:10.992 ThaliTest[1673:2667860] [CDVTimer][handleopenurl] 0.431001ms
,2016-03-17 12:55:11.001 ThaliTest[1673:2667860] [CDVTimer][intentandnavigationfilter] 8.526027ms
2016-03-17 12:55:11.002 ThaliTest[1673:2667860] [CDVTimer][gesturehandler] 0.418007ms
2016-03-17 12:55:11.003 ThaliTest[1673:2667860] [CDVTimer][TotalPluginStartup] 11.295021ms
,2016-03-17 12:55:18.296 ThaliTest[1673:2667860] Resetting plugins due to page load.
,2016-03-17 12:55:21.791 ThaliTest[1673:2667860] Finished load of: file:///var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/index.html
,2016-03-17 12:55:22.053 ThaliTest[1673:2667860] JXcore Cordova plugin initializing
,2016-03-17 12:55:22.055 ThaliTest[1673:2668068] JXcore instance initializing
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
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-17 12:55:37.664 ThaliTest[1673:2668068] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 12:55:37.664 ThaliTest[1673:2668068] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 12:55:37.664 ThaliTest[1673:2668068] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 12:55:37.667 ThaliTest[1673:2668068] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/78F5B11D-27F1-46AE-8799-22C4F4B1DE12/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
