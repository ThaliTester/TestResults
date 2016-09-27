#### Test 8689130568a1443_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C25F92B5-D31B-444C-8E0E-46952EDF4DA5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/C25F92B5-D31B-444C-8E0E-46952EDF4DA5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5F23CBF9-B765-4738-B41A-B145BC6AF817/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56342"
,(lldb)     command script import "/tmp/C25F92B5-D31B-444C-8E0E-46952EDF4DA5/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 03:51:49.523 ThaliTest[1711:2228529] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A02B6C08-3AF2-440C-92E6-25A868D30BE4/Library/Cookies/Cookies.binarycookies
,2016-09-27 03:51:49.559 ThaliTest[1711:2228529] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 03:51:49.560 ThaliTest[1711:2228529] Multi-tasking -> Device: YES, App: YES
,2016-09-27 03:51:49.572 ThaliTest[1711:2228529] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 03:51:49.927 ThaliTest[1711:2228529] Using UIWebView
2016-09-27 03:51:49.931 ThaliTest[1711:2228529] [CDVTimer][handleopenurl] 0.253022ms
,2016-09-27 03:51:49.937 ThaliTest[1711:2228529] [CDVTimer][intentandnavigationfilter] 5.568027ms
2016-09-27 03:51:49.937 ThaliTest[1711:2228529] [CDVTimer][gesturehandler] 0.184000ms
2016-09-27 03:51:49.938 ThaliTest[1711:2228529] [CDVTimer][TotalPluginStartup] 7.126987ms
,2016-09-27 03:51:55.735 ThaliTest[1711:2228529] Resetting plugins due to page load.
,2016-09-27 03:51:56.197 ThaliTest[1711:2228529] Finished load of: file:///var/containers/Bundle/Application/5F23CBF9-B765-4738-B41A-B145BC6AF817/ThaliTest.app/www/index.html
,2016-09-27 03:51:56.548 ThaliTest[1711:2228529] JXcore Cordova plugin initializing
,2016-09-27 03:51:56.549 ThaliTest[1711:2228688] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1385e4470>
,Optional("E0B2E946-E2BA-4043-925D-6CFB14E5B596")
nil
,nil
,Optional("073F4DCA-AD59-42A9-9BD0-B3619CAD6158")
,Optional("31DF7EDD-BC3E-4981-BEDF-B212FA793BF8")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.49756598472595
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
