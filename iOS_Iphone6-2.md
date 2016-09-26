#### Test 86482582e70b00a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3A99732D-DD8E-443B-923F-35C7EA5118FA/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/3A99732D-DD8E-443B-923F-35C7EA5118FA/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86482582e70b00a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/059B925F-4163-4EA8-8A44-9FB3AF699A81/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64638"
,(lldb)     command script import "/tmp/3A99732D-DD8E-443B-923F-35C7EA5118FA/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 03:32:28.459 ThaliTest[1615:2110665] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DDA3750D-06D5-4A61-A6E2-28B0956693E3/Library/Cookies/Cookies.binarycookies
,2016-09-26 03:32:28.495 ThaliTest[1615:2110665] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 03:32:28.496 ThaliTest[1615:2110665] Multi-tasking -> Device: YES, App: YES
,2016-09-26 03:32:28.512 ThaliTest[1615:2110665] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 03:32:28.840 ThaliTest[1615:2110665] Using UIWebView
,2016-09-26 03:32:28.845 ThaliTest[1615:2110665] [CDVTimer][handleopenurl] 0.188053ms
,2016-09-26 03:32:28.849 ThaliTest[1615:2110665] [CDVTimer][intentandnavigationfilter] 3.502965ms
2016-09-26 03:32:28.850 ThaliTest[1615:2110665] [CDVTimer][gesturehandler] 0.136971ms
2016-09-26 03:32:28.850 ThaliTest[1615:2110665] [CDVTimer][TotalPluginS,tartup] 4.633009ms
,2016-09-26 03:32:34.572 ThaliTest[1615:2110665] Resetting plugins due to page load.
,2016-09-26 03:32:34.954 ThaliTest[1615:2110665] Finished load of: file:///var/containers/Bundle/Application/059B925F-4163-4EA8-8A44-9FB3AF699A81/ThaliTest.app/www/index.html
,2016-09-26 03:32:35.277 ThaliTest[1615:2110665] JXcore Cordova plugin initializing
,2016-09-26 03:32:35.278 ThaliTest[1615:2110849] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x14f0c0000>
,Optional("164F963C-1911-48E3-8215-754291AFDA91")
nil
,nil
Optional("9B5B2C76-5609-4790-9ED8-02DB416FE2E4")
,Optional("C52F54B8-B53B-45C2-9579-F7C00F252661")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.59225302934647
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
