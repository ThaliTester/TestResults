#### Test 85519194329c724_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B2EE890E-9A28-4E28-BE64-9C3936BAAFE7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B2EE890E-9A28-4E28-BE64-9C3936BAAFE7/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85519194329c724/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A7618BC8-F371-4763-AB1C-1F96F3A7CB74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50221"
,(lldb)     command script import "/tmp/B2EE890E-9A28-4E28-BE64-9C3936BAAFE7/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 22:22:02.624 ThaliTest[888:959704] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4C92BA47-038F-4433-9CA8-F67E863C647A/Library/Cookies/Cookies.binarycookies
,2016-09-15 22:22:02.736 ThaliTest[888:959704] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 22:22:02.738 ThaliTest[888:959704] Multi-tasking -> Device: YES, App: YES
,2016-09-15 22:22:02.760 ThaliTest[888:959704] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 22:22:03.273 ThaliTest[888:959704] Using UIWebView
,2016-09-15 22:22:03.280 ThaliTest[888:959704] [CDVTimer][handleopenurl] 0.348032ms
,2016-09-15 22:22:03.288 ThaliTest[888:959704] [CDVTimer][intentandnavigationfilter] 6.982982ms
2016-09-15 22:22:03.288 ThaliTest[888:959704] [CDVTimer][gesturehandler] 0.301003ms
2016-09-15 22:22:03.289 ThaliTest[888:959704] [CDVTimer][TotalPluginStartup] 9.432018ms
,2016-09-15 22:22:09.080 ThaliTest[888:959704] Resetting plugins due to page load.
,2016-09-15 22:22:09.752 ThaliTest[888:959704] Finished load of: file:///var/containers/Bundle/Application/A7618BC8-F371-4763-AB1C-1F96F3A7CB74/ThaliTest.app/www/index.html
,2016-09-15 22:22:10.156 ThaliTest[888:959704] JXcore Cordova plugin initializing
,2016-09-15 22:22:10.157 ThaliTest[888:959868] JXcore instance initializing
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
,Unit Test app is loaded

```
