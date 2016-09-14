#### Test 82914073a6a0640_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9FB685D0-0DC3-4BC7-BC5C-7F0F68066C64/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9FB685D0-0DC3-4BC7-BC5C-7F0F68066C64/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a6a0640/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/403D306F-6927-43CC-A4AC-CAB28667056D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64948"
,(lldb)     command script import "/tmp/9FB685D0-0DC3-4BC7-BC5C-7F0F68066C64/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 20:06:55.712 ThaliTest[614:763970] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/141D0ECF-A952-47D7-8227-48288764FB73/Library/Cookies/Cookies.binarycookies
,2016-09-14 20:06:55.750 ThaliTest[614:763970] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 20:06:55.751 ThaliTest[614:763970] Multi-tasking -> Device: YES, App: YES
,2016-09-14 20:06:55.762 ThaliTest[614:763970] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 20:06:56.044 ThaliTest[614:763970] Using UIWebView
,2016-09-14 20:06:56.048 ThaliTest[614:763970] [CDVTimer][handleopenurl] 0.190973ms
,2016-09-14 20:06:56.051 ThaliTest[614:763970] [CDVTimer][intentandnavigationfilter] 3.427982ms
2016-09-14 20:06:56.052 ThaliTest[614:763970] [CDVTimer][gesturehandler] 0.146985ms
2016-09-14 20:06:56.052 ThaliTest[614:763970] [CDVTimer][TotalPluginStartup,] 4.579008ms
,2016-09-14 20:07:00.950 ThaliTest[614:763970] Resetting plugins due to page load.
,2016-09-14 20:07:01.277 ThaliTest[614:763970] Finished load of: file:///var/containers/Bundle/Application/403D306F-6927-43CC-A4AC-CAB28667056D/ThaliTest.app/www/index.html
,2016-09-14 20:07:01.656 ThaliTest[614:763970] JXcore Cordova plugin initializing
,2016-09-14 20:07:01.658 ThaliTest[614:764125] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x127a429c0>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 20:07:21.004 ThaliTest[614:763970] BTM: attaching to BTServer
,2016-09-14 20:07:22.142 ThaliTest[614:763970] BTM: local device power state changed
2016-09-14 20:07:22.148 ThaliTest[614:763970] BTM: power is now off
,2016-09-14 20:07:22.895 ThaliTest[614:763970] BTM: local device power state changed
2016-09-14 20:07:22.896 ThaliTest[614:763970] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  48
Number of passed tests:  48
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  13.9470009803772
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground
```
