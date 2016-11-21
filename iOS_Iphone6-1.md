#### Test 94626375b5fe2b0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/590D071E-4C0A-4892-A045-43D3E491338B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/590D071E-4C0A-4892-A045-43D3E491338B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A628B6C2-DD5B-4B98-8D3A-CBC998CC6EA9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61075"
,(lldb)     command script import "/tmp/590D071E-4C0A-4892-A045-43D3E491338B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-21 17:38:16.345 ThaliTest[3843:9753883] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/987A6D8A-3F22-48BA-AAFF-DD06ACBEE98F/Library/Cookies/Cookies.binarycookies
,2016-11-21 17:38:16.392 ThaliTest[3843:9753883] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 17:38:16.393 ThaliTest[3843:9753883] Multi-tasking -> Device: YES, App: YES
,2016-11-21 17:38:16.412 ThaliTest[3843:9753883] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 17:38:16.716 ThaliTest[3843:9753883] Using UIWebView
,2016-11-21 17:38:16.721 ThaliTest[3843:9753883] [CDVTimer][handleopenurl] 0.213027ms
,2016-11-21 17:38:16.725 ThaliTest[3843:9753883] [CDVTimer][intentandnavigationfilter] 3.497005ms
2016-11-21 17:38:16.726 ThaliTest[3843:9753883] [CDVTimer][gesturehandler] 0.141025ms
2016-11-21 17:38:16.726 ThaliTest[3843:9753883] [CDVTimer][TotalPluginStartup] 4.669011ms
,2016-11-21 17:38:22.469 ThaliTest[3843:9753883] Resetting plugins due to page load.
,2016-11-21 17:38:22.794 ThaliTest[3843:9753883] Finished load of: file:///var/containers/Bundle/Application/A628B6C2-DD5B-4B98-8D3A-CBC998CC6EA9/ThaliTest.app/www/index.html
,2016-11-21 17:38:23.134 ThaliTest[3843:9753883] JXcore Cordova plugin initializing
,2016-11-21 17:38:23.136 ThaliTest[3843:9754079] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-11-21 16:38:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 16:38:59 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  24.95976901054382
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
