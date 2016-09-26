#### Test 8652210239a4b7e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/03C78E12-381D-47B1-A445-E20BF4C7A4B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/03C78E12-381D-47B1-A445-E20BF4C7A4B8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/028F59F1-1F8F-4D7A-A0B8-41D90D2581D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57702"
,(lldb)     command script import "/tmp/03C78E12-381D-47B1-A445-E20BF4C7A4B8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 16:19:03.564 ThaliTest[1450:2264772] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB703613-826D-43DF-8687-64D2775B6016/Library/Cookies/Cookies.binarycookies
,2016-09-26 16:19:03.601 ThaliTest[1450:2264772] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 16:19:03.602 ThaliTest[1450:2264772] Multi-tasking -> Device: YES, App: YES
,2016-09-26 16:19:03.613 ThaliTest[1450:2264772] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 16:19:03.937 ThaliTest[1450:2264772] Using UIWebView
,2016-09-26 16:19:03.941 ThaliTest[1450:2264772] [CDVTimer][handleopenurl] 0.267029ms
,2016-09-26 16:19:03.945 ThaliTest[1450:2264772] [CDVTimer][intentandnavigationfilter] 3.467023ms
2016-09-26 16:19:03.945 ThaliTest[1450:2264772] [CDVTimer][gesturehandler] 0.135005ms
2016-09-26 16:19:03.945 ThaliTest[1450:2264772] [CDVTimer][TotalPluginStartup] 4.643023ms
,2016-09-26 16:19:09.099 ThaliTest[1450:2264772] Resetting plugins due to page load.
,2016-09-26 16:19:09.498 ThaliTest[1450:2264772] Finished load of: file:///var/containers/Bundle/Application/028F59F1-1F8F-4D7A-A0B8-41D90D2581D9/ThaliTest.app/www/index.html
,2016-09-26 16:19:09.876 ThaliTest[1450:2264772] JXcore Cordova plugin initializing
,2016-09-26 16:19:09.877 ThaliTest[1450:2264934] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14f513c50>
,Optional("B8C8AEAE-ACCA-439B-92A9-6FF36CC3F9BF")
nil
,nil
,Optional("DD1B0677-D835-4C2E-8E13-CCEA41AB8F89")
,Optional("3007CE82-97A0-4C0B-837A-3F5B9A15528B")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.35359901189804
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
