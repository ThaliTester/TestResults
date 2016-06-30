#### Test 757892682551a10_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/1C320BB7-8D36-4D64-AC03-E8B41A0BA93D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1C320BB7-8D36-4D64-AC03-E8B41A0BA93D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892682551a10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65025"
,(lldb)     command script import "/tmp/1C320BB7-8D36-4D64-AC03-E8B41A0BA93D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 13:50:08.868 ThaliTest[6147:18569379] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B0C9939-8662-4A6D-86EF-E1859500D653/Library/Cookies/Cookies.binarycookies
,2016-06-30 13:50:09.274 ThaliTest[6147:18569379] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 13:50:09.276 ThaliTest[6147:18569379] Multi-tasking -> Device: YES, App: YES
,2016-06-30 13:50:09.300 ThaliTest[6147:18569379] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 13:50:11.471 ThaliTest[6147:18569379] Using UIWebView
,2016-06-30 13:50:11.479 ThaliTest[6147:18569379] [CDVTimer][handleopenurl] 0.512958ms
,2016-06-30 13:50:11.488 ThaliTest[6147:18569379] [CDVTimer][intentandnavigationfilter] 7.951975ms
2016-06-30 13:50:11.489 ThaliTest[6147:18569379] [CDVTimer][gesturehandler] 0.449955ms
2016-06-30 13:50:11.489 ThaliTest[6147:18569379] [CDVTimer][TotalPlug,inStartup] 10.800004ms
,2016-06-30 13:50:18.887 ThaliTest[6147:18569379] Resetting plugins due to page load.
,2016-06-30 13:50:22.548 ThaliTest[6147:18569379] Finished load of: file:///var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/index.html
,2016-06-30 13:50:22.797 ThaliTest[6147:18569379] JXcore Cordova plugin initializing
,2016-06-30 13:50:22.798 ThaliTest[6147:18569619] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 13:50:31.711 ThaliTest[6147:18569619] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-06-30 13:50:31.711 ThaliTest[6147:18569619] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 13:50:31.712 ThaliTest[6147:18569619] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 13:50:31.714 ThaliTest[6147:18569619] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4DE4D1B6-5BAE-4CD7-AB6D-79F3AC0CBBD7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 13:50:38.965 ThaliTest[6147:18569379] THREAD WARNING: ['JXcore'] took '6884.491943' ms. Plugin should use a background thread.
2016-06-30 13:50:38.965 ThaliTest[6147:18569379] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-06-30 13:50:38.965 ThaliTest[6147:18569379] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore316123203","JXcore","Test",[]]

```
