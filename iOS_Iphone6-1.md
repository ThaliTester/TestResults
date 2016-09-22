#### Test 8617437972ae596_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D1BF6529-F4DB-4DE2-B7EA-106D3864B429/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D1BF6529-F4DB-4DE2-B7EA-106D3864B429/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437972ae596/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B25AB932-C76A-4895-8424-5B2B0C30FDED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56435"
,(lldb)     command script import "/tmp/D1BF6529-F4DB-4DE2-B7EA-106D3864B429/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:15:56.047 ThaliTest[1139:1719955] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6BE8DF6E-6D7E-42AE-AF91-E02C06C11223/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:15:56.125 ThaliTest[1139:1719955] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:15:56.127 ThaliTest[1139:1719955] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:15:56.145 ThaliTest[1139:1719955] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:15:56.637 ThaliTest[1139:1719955] Using UIWebView
,2016-09-22 10:15:56.647 ThaliTest[1139:1719955] [CDVTimer][handleopenurl] 0.324965ms
,2016-09-22 10:15:56.654 ThaliTest[1139:1719955] [CDVTimer][intentandnavigationfilter] 7.041991ms
2016-09-22 10:15:56.655 ThaliTest[1139:1719955] [CDVTimer][gesturehandler] 0.328004ms
2016-09-22 10:15:56.655 ThaliTest[1139:1719955] [CDVTimer][TotalPluginS,tartup] 9.307981ms
,2016-09-22 10:16:02.103 ThaliTest[1139:1719955] Resetting plugins due to page load.
,2016-09-22 10:16:02.470 ThaliTest[1139:1719955] Finished load of: file:///var/containers/Bundle/Application/B25AB932-C76A-4895-8424-5B2B0C30FDED/ThaliTest.app/www/index.html
,2016-09-22 10:16:02.802 ThaliTest[1139:1719955] JXcore Cordova plugin initializing
,2016-09-22 10:16:02.802 ThaliTest[1139:1720129] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x146660a00>
,Optional("3893FCE2-0976-4B25-AB42-D17948CEF1CE")
nil
,nil
,Optional("A4F2E921-7335-4A81-94E6-AE4EA02FCAE3")
,Optional("29227E67-A8B0-4524-9188-E9335D395B88")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-22 10:16:26.005 ThaliTest[1139:1719955] BTM: attaching to BTServer
,2016-09-22 10:16:26.785 ThaliTest[1139:1719955] BTM: local device power state changed
2016-09-22 10:16:26.786 ThaliTest[1139:1719955] BTM: power is now on
,2016-09-22 10:16:31.516 ThaliTest[1139:1719955] BTM: local device power state changed
,2016-09-22 10:16:31.516 ThaliTest[1139:1719955] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  21.30446201562881
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
