#### Test 864825826cfc86f_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AA915934-BE50-4DBB-B8EF-83E271FCEA77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/AA915934-BE50-4DBB-B8EF-83E271FCEA77/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825826cfc86f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/60047E3A-70FB-44FF-A6DE-4F9517F11C98/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62090"
,(lldb)     command script import "/tmp/AA915934-BE50-4DBB-B8EF-83E271FCEA77/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 07:58:39.745 ThaliTest[1642:2133870] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1D9B6DD-82A1-40FE-BC76-8EF945201271/Library/Cookies/Cookies.binarycookies
,2016-09-26 07:58:39.826 ThaliTest[1642:2133870] Apache Cordova native platform version 4.2.1 is starting.
2016-09-26 07:58:39.828 ThaliTest[1642:2133870] Multi-tasking -> Device: YES, App: YES
,2016-09-26 07:58:39.851 ThaliTest[1642:2133870] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 07:58:40.341 ThaliTest[1642:2133870] Using UIWebView
,2016-09-26 07:58:40.351 ThaliTest[1642:2133870] [CDVTimer][handleopenurl] 0.436008ms
,2016-09-26 07:58:40.358 ThaliTest[1642:2133870] [CDVTimer][intentandnavigationfilter] 7.007003ms
2016-09-26 07:58:40.359 ThaliTest[1642:2133870] [CDVTimer][gesturehandler] 0.286996ms
2016-09-26 07:58:40.360 ThaliTest[1642:2133870] [CDVTimer][TotalPluginStartup] 9.386003ms
,2016-09-26 07:58:46.217 ThaliTest[1642:2133870] Resetting plugins due to page load.
,2016-09-26 07:58:46.684 ThaliTest[1642:2133870] Finished load of: file:///var/containers/Bundle/Application/60047E3A-70FB-44FF-A6DE-4F9517F11C98/ThaliTest.app/www/index.html
,2016-09-26 07:58:47.040 ThaliTest[1642:2133870] JXcore Cordova plugin initializing
,2016-09-26 07:58:47.041 ThaliTest[1642:2134050] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x127f0d8e0>
,Optional("0FF96CB4-564B-4266-9A3B-B440539FD33D")
nil
,nil
,Optional("962944B7-7E9E-4583-BBED-75286E89F0C6")
,Optional("6E06ABF7-9B3F-4278-9AA2-1F7ADFD83D16")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.52661603689194
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
