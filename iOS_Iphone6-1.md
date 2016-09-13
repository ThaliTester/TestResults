#### Test 846487404bc066c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CD8DAC8B-8ACB-460F-B9C9-1C16529D4757/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CD8DAC8B-8ACB-460F-B9C9-1C16529D4757/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F0345061-8261-4796-A9B8-7F5592A7ED14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49387"
,(lldb)     command script import "/tmp/CD8DAC8B-8ACB-460F-B9C9-1C16529D4757/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 11:55:30.664 ThaliTest[473:589855] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C2D9492-A37D-492D-AB4B-B1F4A40A696B/Library/Cookies/Cookies.binarycookies
,2016-09-13 11:55:30.856 ThaliTest[473:589855] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 11:55:30.857 ThaliTest[473:589855] Multi-tasking -> Device: YES, App: YES
,2016-09-13 11:55:30.875 ThaliTest[473:589855] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 11:55:31.239 ThaliTest[473:589855] Using UIWebView
,2016-09-13 11:55:31.244 ThaliTest[473:589855] [CDVTimer][handleopenurl] 0.238001ms
,2016-09-13 11:55:31.249 ThaliTest[473:589855] [CDVTimer][intentandnavigationfilter] 4.706025ms
2016-09-13 11:55:31.249 ThaliTest[473:589855] [CDVTimer][gesturehandler] 0.220954ms
2016-09-13 11:55:31.249 ThaliTest[473:589855] [CDVTimer][TotalPluginStartup,] 6.301999ms
,2016-09-13 11:55:36.665 ThaliTest[473:589855] Resetting plugins due to page load.
,2016-09-13 11:55:37.140 ThaliTest[473:589855] Finished load of: file:///var/containers/Bundle/Application/F0345061-8261-4796-A9B8-7F5592A7ED14/ThaliTest.app/www/index.html
,2016-09-13 11:55:37.542 ThaliTest[473:589855] JXcore Cordova plugin initializing
,2016-09-13 11:55:37.543 ThaliTest[473:590039] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 11:55:44.324 ThaliTest[473:590039] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 11:55:44.324 ThaliTest[473:590039] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 11:55:44.324 ThaliTest[473:590039] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 11:55:44.326 ThaliTest[473:590039] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-13 11:55:44.723 ThaliTest[473:590039] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003675997257232666
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
