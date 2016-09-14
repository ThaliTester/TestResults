#### Test 82914073fb4f932_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E9490E40-3CE0-41BC-BCAB-C74B0BC94EA3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/E9490E40-3CE0-41BC-BCAB-C74B0BC94EA3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073fb4f932/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FE191D04-B9FF-4AC9-A14D-F69D3473C1ED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61832"
,(lldb)     command script import "/tmp/E9490E40-3CE0-41BC-BCAB-C74B0BC94EA3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 10:24:25.686 ThaliTest[720:781003] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/523AD75F-D071-4842-8A05-4CFCFF675186/Library/Cookies/Cookies.binarycookies
,2016-09-14 10:24:25.778 ThaliTest[720:781003] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 10:24:25.781 ThaliTest[720:781003] Multi-tasking -> Device: YES, App: YES
,2016-09-14 10:24:25.808 ThaliTest[720:781003] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 10:24:26.268 ThaliTest[720:781003] Using UIWebView
,2016-09-14 10:24:26.277 ThaliTest[720:781003] [CDVTimer][handleopenurl] 0.398993ms
,2016-09-14 10:24:26.285 ThaliTest[720:781003] [CDVTimer][intentandnavigationfilter] 7.054985ms
2016-09-14 10:24:26.286 ThaliTest[720:781003] [CDVTimer][gesturehandler] 0.294983ms
2016-09-14 10:24:26.286 ThaliTest[720:781003] [CDVTimer][TotalPluginStartup] 9.400010ms
,2016-09-14 10:24:32.124 ThaliTest[720:781003] Resetting plugins due to page load.
,2016-09-14 10:24:32.528 ThaliTest[720:781003] Finished load of: file:///var/containers/Bundle/Application/FE191D04-B9FF-4AC9-A14D-F69D3473C1ED/ThaliTest.app/www/index.html
,2016-09-14 10:24:32.894 ThaliTest[720:781003] JXcore Cordova plugin initializing
,2016-09-14 10:24:32.894 ThaliTest[720:781182] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x142821330>
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-14 10:24:51.949 ThaliTest[720:781003] BTM: attaching to BTServer
,2016-09-14 10:24:53.098 ThaliTest[720:781003] BTM: local device power state changed
2016-09-14 10:24:53.102 ThaliTest[720:781003] BTM: power is now off
,2016-09-14 10:24:53.871 ThaliTest[720:781003] BTM: local device power state changed
2016-09-14 10:24:53.872 ThaliTest[720:781003] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  13.75812602043152
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
