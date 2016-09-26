#### Test 8652210239a4b7e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4FC0F4B2-5B2F-4BB7-A238-750DEF5040C2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4FC0F4B2-5B2F-4BB7-A238-750DEF5040C2/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8652210239a4b7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8236C69E-6EAA-47BE-A951-1FB9E0B1E96D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57705"
,(lldb)     command script import "/tmp/4FC0F4B2-5B2F-4BB7-A238-750DEF5040C2/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 07:19:07.201 ThaliTest[1628:2129360] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AD614316-8727-47A8-A120-19673F52C213/Library/Cookies/Cookies.binarycookies
,2016-09-26 07:19:07.285 ThaliTest[1628:2129360] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-26 07:19:07.287 ThaliTest[1628:2129360] Multi-tasking -> Device: YES, App: YES
,2016-09-26 07:19:07.309 ThaliTest[1628:2129360] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 07:19:07.811 ThaliTest[1628:2129360] Using UIWebView
,2016-09-26 07:19:07.818 ThaliTest[1628:2129360] [CDVTimer][handleopenurl] 0.531971ms
,2016-09-26 07:19:07.826 ThaliTest[1628:2129360] [CDVTimer][intentandnavigationfilter] 6.889999ms
2016-09-26 07:19:07.827 ThaliTest[1628:2129360] [CDVTimer][gesturehandler] 0.329971ms
2016-09-26 07:19:07.827 ThaliTest[1628:2129360] [CDVTimer][TotalPluginS,tartup] 9.477973ms
,2016-09-26 07:19:13.830 ThaliTest[1628:2129360] Resetting plugins due to page load.
,2016-09-26 07:19:14.277 ThaliTest[1628:2129360] Finished load of: file:///var/containers/Bundle/Application/8236C69E-6EAA-47BE-A951-1FB9E0B1E96D/ThaliTest.app/www/index.html
,2016-09-26 07:19:14.617 ThaliTest[1628:2129360] JXcore Cordova plugin initializing
,2016-09-26 07:19:14.618 ThaliTest[1628:2129543] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x12f3ac060>
,Optional("1B49726D-781B-48B7-B08F-72EA692939C0")
,nil
,nil
,Optional("D6F083C5-CFFE-496E-A6E8-73AD74E5DC36")
,Optional("55D8760A-C47B-4D10-9769-CCB95D80110D")
,*Native tests were executed*
,Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.24201101064682
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
