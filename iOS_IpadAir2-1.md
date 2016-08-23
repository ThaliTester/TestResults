#### Test 81095569cb9dee4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/72E1B5C6-B40D-47B8-A154-1B4F0DA8FB75/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/72E1B5C6-B40D-47B8-A154-1B4F0DA8FB75/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A21048CC-CFA2-4858-834F-11C723A38A07/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60388"
,(lldb)     command script import "/tmp/72E1B5C6-B40D-47B8-A154-1B4F0DA8FB75/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-23 18:33:45.550 ThaliTest[834:1564047] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96BB74C2-DEF0-4C02-8415-255F9EE8D9DC/Library/Cookies/Cookies.binarycookies
,2016-08-23 18:33:45.962 ThaliTest[834:1564047] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-23 18:33:45.964 ThaliTest[834:1564047] Multi-tasking -> Device: YES, App: YES
,2016-08-23 18:33:45.983 ThaliTest[834:1564047] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-23 18:33:48.020 ThaliTest[834:1564047] Using UIWebView
,2016-08-23 18:33:48.026 ThaliTest[834:1564047] [CDVTimer][handleopenurl] 0.452995ms
,2016-08-23 18:33:48.034 ThaliTest[834:1564047] [CDVTimer][intentandnavigationfilter] 6.613970ms
,2016-08-23 18:33:48.034 ThaliTest[834:1564047] [CDVTimer][gesturehandler] 0.302970ms
,2016-08-23 18:33:48.035 ThaliTest[834:1564047] [CDVTimer][TotalPluginStartup] 9.001970ms
,2016-08-23 18:33:55.366 ThaliTest[834:1564047] Resetting plugins due to page load.
,2016-08-23 18:33:59.343 ThaliTest[834:1564047] Finished load of: file:///var/mobile/Containers/Bundle/Application/A21048CC-CFA2-4858-834F-11C723A38A07/ThaliTest.app/www/index.html
,2016-08-23 18:33:59.574 ThaliTest[834:1564047] JXcore Cordova plugin initializing
,2016-08-23 18:33:59.575 ThaliTest[834:1564297] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-23 18:34:05.781 ThaliTest[834:1564297] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-23 18:34:05.782 ThaliTest[834:1564297] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-23 18:34:05.782 ThaliTest[834:1564297] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-23 18:34:05.784 ThaliTest[834:1564297] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-23 18:34:06.033 ThaliTest[834:1564297] Native method ExecuteNativeTests not found.
,Is Android:  false
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
