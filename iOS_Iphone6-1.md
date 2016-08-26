#### Test 79763830cfa9ed9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/99DCDD86-24D0-4A77-90C0-A515B43E046F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/99DCDD86-24D0-4A77-90C0-A515B43E046F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cfa9ed9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1584F25F-CD8B-4727-BAF0-FFA8D9DD1770/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60380"
,(lldb)     command script import "/tmp/99DCDD86-24D0-4A77-90C0-A515B43E046F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-26 15:41:13.746 ThaliTest[542:585454] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EFECE2A3-2DEA-40DE-86ED-E1F15903C7BF/Library/Cookies/Cookies.binarycookies
,2016-08-26 15:41:14.137 ThaliTest[542:585454] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 15:41:14.139 ThaliTest[542:585454] Multi-tasking -> Device: YES, App: YES
,2016-08-26 15:41:14.166 ThaliTest[542:585454] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 15:41:16.047 ThaliTest[542:585454] Using UIWebView
,2016-08-26 15:41:16.054 ThaliTest[542:585454] [CDVTimer][handleopenurl] 0.386000ms
,2016-08-26 15:41:16.062 ThaliTest[542:585454] [CDVTimer][intentandnavigationfilter] 7.358015ms
2016-08-26 15:41:16.063 ThaliTest[542:585454] [CDVTimer][gesturehandler] 0.361979ms
2016-08-26 15:41:16.063 ThaliTest[542:585454] [CDVTimer][TotalPluginStartup] 9.880006ms
,2016-08-26 15:41:22.332 ThaliTest[542:585454] Resetting plugins due to page load.
,2016-08-26 15:41:25.590 ThaliTest[542:585454] Finished load of: file:///var/mobile/Containers/Bundle/Application/1584F25F-CD8B-4727-BAF0-FFA8D9DD1770/ThaliTest.app/www/index.html
,2016-08-26 15:41:25.816 ThaliTest[542:585454] JXcore Cordova plugin initializing
,2016-08-26 15:41:25.817 ThaliTest[542:585693] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 15:41:32.691 ThaliTest[542:585693] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 15:41:32.692 ThaliTest[542:585693] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 15:41:32.692 ThaliTest[542:585693,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 15:41:32.694 ThaliTest[542:585693] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 15:41:33.019 ThaliTest[542:585693] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01093399524688721
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
