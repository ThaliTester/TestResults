#### Test 836273373ce2df7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6161F41A-5834-4B5F-AC25-46C2929BCD5E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6161F41A-5834-4B5F-AC25-46C2929BCD5E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273373ce2df7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3F7A4290-E106-46FB-8FC1-A0CAA0C3A8C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51016"
,(lldb)     command script import "/tmp/6161F41A-5834-4B5F-AC25-46C2929BCD5E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 12:08:26.356 ThaliTest[567:719297] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7CC7FEAF-2BB0-48AE-9EFB-B875C584D393/Library/Cookies/Cookies.binarycookies
,2016-09-14 12:08:26.690 ThaliTest[567:719297] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 12:08:26.692 ThaliTest[567:719297] Multi-tasking -> Device: YES, App: YES
,2016-09-14 12:08:26.715 ThaliTest[567:719297] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 12:08:27.092 ThaliTest[567:719297] Using UIWebView
,2016-09-14 12:08:27.099 ThaliTest[567:719297] [CDVTimer][handleopenurl] 0.585020ms
,2016-09-14 12:08:27.105 ThaliTest[567:719297] [CDVTimer][intentandnavigationfilter] 5.667984ms
2016-09-14 12:08:27.105 ThaliTest[567:719297] [CDVTimer][gesturehandler] 0.212014ms
2016-09-14 12:08:27.106 ThaliTest[567:719297] [CDVTimer][TotalPluginStartup] 7.772028ms
,2016-09-14 12:08:32.907 ThaliTest[567:719297] Resetting plugins due to page load.
,2016-09-14 12:08:33.229 ThaliTest[567:719297] Finished load of: file:///var/containers/Bundle/Application/3F7A4290-E106-46FB-8FC1-A0CAA0C3A8C9/ThaliTest.app/www/index.html
,2016-09-14 12:08:33.608 ThaliTest[567:719297] JXcore Cordova plugin initializing
,2016-09-14 12:08:33.609 ThaliTest[567:719510] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 12:08:40.334 ThaliTest[567:719510] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 12:08:40.335 ThaliTest[567:719510] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 12:08:40.335 ThaliTest[567:719510] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 12:08:40.337 ThaliTest[567:719510] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
