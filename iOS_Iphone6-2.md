#### Test 85046911e91e24b_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6AC15EC1-C6D9-45C2-8451-F35F62C891D5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/6AC15EC1-C6D9-45C2-8451-F35F62C891D5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911e91e24b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/88F24F08-5325-4E23-A3DA-BDD1D9F4113B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51924"
,(lldb)     command script import "/tmp/6AC15EC1-C6D9-45C2-8451-F35F62C891D5/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 08:16:40.758 ThaliTest[704:769669] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/42B7137E-8F99-4D91-8642-EC061894FEFB/Library/Cookies/Cookies.binarycookies
,2016-09-14 08:16:41.091 ThaliTest[704:769669] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 08:16:41.092 ThaliTest[704:769669] Multi-tasking -> Device: YES, App: YES
,2016-09-14 08:16:41.115 ThaliTest[704:769669] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 08:16:41.546 ThaliTest[704:769669] Using UIWebView
,2016-09-14 08:16:41.552 ThaliTest[704:769669] [CDVTimer][handleopenurl] 0.349998ms
,2016-09-14 08:16:41.561 ThaliTest[704:769669] [CDVTimer][intentandnavigationfilter] 7.716000ms
2016-09-14 08:16:41.561 ThaliTest[704:769669] [CDVTimer][gesturehandler] 0.362992ms
2016-09-14 08:16:41.562 ThaliTest[704:769669] [CDVTimer][TotalPluginStartup] 10.132015ms
,2016-09-14 08:16:47.390 ThaliTest[704:769669] Resetting plugins due to page load.
,2016-09-14 08:16:47.658 ThaliTest[704:769669] Finished load of: file:///var/containers/Bundle/Application/88F24F08-5325-4E23-A3DA-BDD1D9F4113B/ThaliTest.app/www/index.html
,2016-09-14 08:16:48.001 ThaliTest[704:769669] JXcore Cordova plugin initializing
,2016-09-14 08:16:48.002 ThaliTest[704:769875] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 08:16:54.656 ThaliTest[704:769875] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 08:16:54.657 ThaliTest[704:769875] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-14 08:16:54.657 ThaliTest[704:769875] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 08:16:54.659 ThaliTest[704:769875] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-14 08:16:55.050 ThaliTest[704:769875] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004150986671447754
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
