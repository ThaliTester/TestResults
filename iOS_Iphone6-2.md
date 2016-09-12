#### Test 830701775d60530_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A89048E4-BC06-489D-81E4-2B9534FC2D6E/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/A89048E4-BC06-489D-81E4-2B9534FC2D6E/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/830701775d60530/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0154B856-0E66-41F7-BADB-9E1C584A1445/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58226"
,(lldb)     command script import "/tmp/A89048E4-BC06-489D-81E4-2B9534FC2D6E/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 05:40:36.708 ThaliTest[514:526979] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D5E4CB7-C884-4781-8EC1-BDC037DBF1E9/Library/Cookies/Cookies.binarycookies
,2016-09-12 05:40:37.091 ThaliTest[514:526979] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 05:40:37.093 ThaliTest[514:526979] Multi-tasking -> Device: YES, App: YES
,2016-09-12 05:40:37.115 ThaliTest[514:526979] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 05:40:37.651 ThaliTest[514:526979] Using UIWebView
,2016-09-12 05:40:37.662 ThaliTest[514:526979] [CDVTimer][handleopenurl] 0.404000ms
,2016-09-12 05:40:37.670 ThaliTest[514:526979] [CDVTimer][intentandnavigationfilter] 7.371962ms
2016-09-12 05:40:37.670 ThaliTest[514:526979] [CDVTimer][gesturehandler] 0.340998ms
2016-09-12 05:40:37.671 ThaliTest[514:526979] [CDVTimer][TotalPluginStartup] 9.936988ms
,2016-09-12 05:40:43.989 ThaliTest[514:526979] Resetting plugins due to page load.
,2016-09-12 05:40:44.476 ThaliTest[514:526979] Finished load of: file:///var/containers/Bundle/Application/0154B856-0E66-41F7-BADB-9E1C584A1445/ThaliTest.app/www/index.html
,2016-09-12 05:40:44.949 ThaliTest[514:526979] JXcore Cordova plugin initializing
,2016-09-12 05:40:44.950 ThaliTest[514:527167] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  16
,Number of passed tests:  16
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.64224499464035
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
