#### Test 79763830d186b13_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/98FFB1DD-CF1C-44D9-BF55-F5CA9C86CAE9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/98FFB1DD-CF1C-44D9-BF55-F5CA9C86CAE9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/166D0818-3488-400D-BD7D-92F99AAD4A96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59774"
,(lldb)     command script import "/tmp/98FFB1DD-CF1C-44D9-BF55-F5CA9C86CAE9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 21:09:16.302 ThaliTest[593:622129] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/03751B20-7218-45FF-97BB-FA6302933635/Library/Cookies/Cookies.binarycookies
,2016-08-26 21:09:16.686 ThaliTest[593:622129] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 21:09:16.688 ThaliTest[593:622129] Multi-tasking -> Device: YES, App: YES
,2016-08-26 21:09:16.710 ThaliTest[593:622129] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 21:09:18.536 ThaliTest[593:622129] Using UIWebView
,2016-08-26 21:09:18.543 ThaliTest[593:622129] [CDVTimer][handleopenurl] 0.562966ms
,2016-08-26 21:09:18.551 ThaliTest[593:622129] [CDVTimer][intentandnavigationfilter] 8.056998ms
2016-08-26 21:09:18.552 ThaliTest[593:622129] [CDVTimer][gesturehandler] 0.373006ms
2016-08-26 21:09:18.552 ThaliTest[593:622129] [CDVTimer][TotalPluginStartup,] 10.608971ms
,2016-08-26 21:09:24.959 ThaliTest[593:622129] Resetting plugins due to page load.
,2016-08-26 21:09:27.988 ThaliTest[593:622129] Finished load of: file:///var/mobile/Containers/Bundle/Application/166D0818-3488-400D-BD7D-92F99AAD4A96/ThaliTest.app/www/index.html
,2016-08-26 21:09:28.228 ThaliTest[593:622129] JXcore Cordova plugin initializing
,2016-08-26 21:09:28.229 ThaliTest[593:622365] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 21:09:35.194 ThaliTest[593:622365] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-26 21:09:35.194 ThaliTest[593:622365] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 21:09:35.195 ThaliTest[593:622365] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 21:09:35.196 ThaliTest[593:622365] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 21:09:35.521 ThaliTest[593:622365] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003753006458282471
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
