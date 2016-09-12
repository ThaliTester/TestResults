#### Test 82894682da71698_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/94359A29-47D9-4D50-8D0D-836E3F35F287/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/94359A29-47D9-4D50-8D0D-836E3F35F287/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82894682da71698/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0C443673-8204-4B46-B3C2-1C9CD96C5F4D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53410"
,(lldb)     command script import "/tmp/94359A29-47D9-4D50-8D0D-836E3F35F287/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-12 15:04:07.612 ThaliTest[534:569881] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31A22F63-3A4F-4300-8693-71178B2C8685/Library/Cookies/Cookies.binarycookies
,2016-09-12 15:04:07.688 ThaliTest[534:569881] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 15:04:07.690 ThaliTest[534:569881] Multi-tasking -> Device: YES, App: YES
,2016-09-12 15:04:07.709 ThaliTest[534:569881] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 15:04:08.174 ThaliTest[534:569881] Using UIWebView
,2016-09-12 15:04:08.180 ThaliTest[534:569881] [CDVTimer][handleopenurl] 0.325024ms
,2016-09-12 15:04:08.188 ThaliTest[534:569881] [CDVTimer][intentandnavigationfilter] 6.821990ms
2016-09-12 15:04:08.188 ThaliTest[534:569881] [CDVTimer][gesturehandler] 0.263989ms
2016-09-12 15:04:08.189 ThaliTest[534:569881] [CDVTimer][TotalPluginStartup] 8.993030ms
,2016-09-12 15:04:13.653 ThaliTest[534:569881] Resetting plugins due to page load.
,2016-09-12 15:04:14.282 ThaliTest[534:569881] Finished load of: file:///var/containers/Bundle/Application/0C443673-8204-4B46-B3C2-1C9CD96C5F4D/ThaliTest.app/www/index.html
,2016-09-12 15:04:14.685 ThaliTest[534:569881] JXcore Cordova plugin initializing
,2016-09-12 15:04:14.686 ThaliTest[534:570037] JXcore instance initializing
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
,2016-09-12 15:04:22.039 ThaliTest[534:569881] BTM: attaching to BTServer
,2016-09-12 15:04:22.091 ThaliTest[534:569881] BTM: local device power state changed
2016-09-12 15:04:22.091 ThaliTest[534:569881] BTM: power is now off
,2016-09-12 15:04:22.857 ThaliTest[534:569881] BTM: local device power state changed
2016-09-12 15:04:22.866 ThaliTest[534:569881] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  39.38590002059937
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
