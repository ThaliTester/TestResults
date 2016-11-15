#### Test 9376531715755df_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/53177AB6-484F-40F0-9EFB-9A4D113AB364/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/53177AB6-484F-40F0-9EFB-9A4D113AB364/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4493F5A3-5543-4355-ACDC-79E24CBA444C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63788"
,(lldb)     command script import "/tmp/53177AB6-484F-40F0-9EFB-9A4D113AB364/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 18:29:19.099 ThaliTest[3482:8906349] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/24C7FE13-CCA8-40F0-A8A1-77C2AE967A52/Library/Cookies/Cookies.binarycookies
,2016-11-15 18:29:19.136 ThaliTest[3482:8906349] Apache Cordova native platform version 4.2.1 is starting.
2016-11-15 18:29:19.137 ThaliTest[3482:8906349] Multi-tasking -> Device: YES, App: YES
,2016-11-15 18:29:19.149 ThaliTest[3482:8906349] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 18:29:19.443 ThaliTest[3482:8906349] Using UIWebView
,2016-11-15 18:29:19.448 ThaliTest[3482:8906349] [CDVTimer][handleopenurl] 0.150025ms
,2016-11-15 18:29:19.451 ThaliTest[3482:8906349] [CDVTimer][intentandnavigationfilter] 2.685964ms
2016-11-15 18:29:19.451 ThaliTest[3482:8906349] [CDVTimer][gesturehandler] 0.131965ms
2016-11-15 18:29:19.451 ThaliTest[3482:8906349] [CDVTimer][TotalPluginStartup] 3.639996ms
,2016-11-15 18:29:24.618 ThaliTest[3482:8906349] Resetting plugins due to page load.
,2016-11-15 18:29:24.981 ThaliTest[3482:8906349] Finished load of: file:///var/containers/Bundle/Application/4493F5A3-5543-4355-ACDC-79E24CBA444C/ThaliTest.app/www/index.html
,2016-11-15 18:29:25.313 ThaliTest[3482:8906349] JXcore Cordova plugin initializing
,2016-11-15 18:29:25.314 ThaliTest[3482:8906550] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 17:29:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 17:29:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 17:29:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 17:29:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 17:29:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 17:30:01 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.99300199747086
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
