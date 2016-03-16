#### Test 63012666d6bb2e8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B1740CB2-CB6D-4DA4-BDA5-55DA135DDB18/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B1740CB2-CB6D-4DA4-BDA5-55DA135DDB18/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63012666d6bb2e8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50725"
,(lldb)     command script import "/tmp/B1740CB2-CB6D-4DA4-BDA5-55DA135DDB18/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 14:30:33.641 ThaliTest[1579:2523496] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8AD613BD-B27E-4598-AA22-6703DB44CE3B/Library/Cookies/Cookies.binarycookies
,2016-03-16 14:30:34.093 ThaliTest[1579:2523496] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 14:30:34.095 ThaliTest[1579:2523496] Multi-tasking -> Device: YES, App: YES
,2016-03-16 14:30:34.126 ThaliTest[1579:2523496] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 14:30:36.061 ThaliTest[1579:2523496] Using UIWebView
,2016-03-16 14:30:36.069 ThaliTest[1579:2523496] [CDVTimer][handleopenurl] 0.444055ms
,2016-03-16 14:30:36.078 ThaliTest[1579:2523496] [CDVTimer][intentandnavigationfilter] 8.001029ms
2016-03-16 14:30:36.079 ThaliTest[1579:2523496] [CDVTimer][gesturehandler] 0.366986ms
2016-03-16 14:30:36.079 ThaliTest[1579:2523496] [CDVTimer][TotalPluginStartup] 10.685027ms
,2016-03-16 14:30:43.163 ThaliTest[1579:2523496] Resetting plugins due to page load.
,2016-03-16 14:30:46.602 ThaliTest[1579:2523496] Finished load of: file:///var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/index.html
,2016-03-16 14:30:46.846 ThaliTest[1579:2523496] JXcore Cordova plugin initializing
,2016-03-16 14:30:46.848 ThaliTest[1579:2523719] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,2016-03-16 14:30:51.876 ThaliTest[1579:2523719] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 14:30:51.877 ThaliTest[1579:2523719] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 14:30:51.877 ThaliTest[1579:2,523719] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-16 14:30:51.880 ThaliTest[1579:2523719] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/5E97236D-9D19-463F-8F40-8CC511D52262/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-16 14:31:02.226 ThaliTest[1579:2523496] THREAD WARNING: ['JXcore'] took '7420.401123' ms. Plugin should use a background thread.

```
