#### Test 84265062d118465_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/684398D5-17B0-4EBF-9670-130F7BC4B092/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/684398D5-17B0-4EBF-9670-130F7BC4B092/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/84265062d118465/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9702A804-C0B8-4A54-A650-97D24D2A9952/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50589"
,(lldb)     command script import "/tmp/684398D5-17B0-4EBF-9670-130F7BC4B092/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 09:12:22.448 ThaliTest[523:543518] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/720119D8-1450-4C27-B9A3-56FFDF35E5B7/Library/Cookies/Cookies.binarycookies
,2016-09-12 09:12:22.535 ThaliTest[523:543518] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 09:12:22.537 ThaliTest[523:543518] Multi-tasking -> Device: YES, App: YES
,2016-09-12 09:12:22.559 ThaliTest[523:543518] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 09:12:23.024 ThaliTest[523:543518] Using UIWebView
,2016-09-12 09:12:23.032 ThaliTest[523:543518] [CDVTimer][handleopenurl] 0.373006ms
,2016-09-12 09:12:23.040 ThaliTest[523:543518] [CDVTimer][intentandnavigationfilter] 6.860018ms
2016-09-12 09:12:23.040 ThaliTest[523:543518] [CDVTimer][gesturehandler] 0.295997ms
2016-09-12 09:12:23.041 ThaliTest[523:543518] [CDVTimer][TotalPluginStartup,] 9.154975ms
,2016-09-12 09:12:28.845 ThaliTest[523:543518] Resetting plugins due to page load.
,2016-09-12 09:12:29.415 ThaliTest[523:543518] Finished load of: file:///var/containers/Bundle/Application/9702A804-C0B8-4A54-A650-97D24D2A9952/ThaliTest.app/www/index.html
,2016-09-12 09:12:29.866 ThaliTest[523:543518] JXcore Cordova plugin initializing
,2016-09-12 09:12:29.867 ThaliTest[523:543692] JXcore instance initializing
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
,2016-09-12 09:13:15.759 ThaliTest[523:543518] BTM: attaching to BTServer
,2016-09-12 09:13:16.953 ThaliTest[523:543518] BTM: local device power state changed
2016-09-12 09:13:16.954 ThaliTest[523:543518] BTM: power is now off
,2016-09-12 09:13:17.737 ThaliTest[523:543518] BTM: local device power state changed
2016-09-12 09:13:17.737 ThaliTest[523:543518] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  40.61342304944992
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
