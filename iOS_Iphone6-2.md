#### Test 855258872e8b4bc_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8A1E8ACA-1B13-4B9C-873D-DF7C42A29473/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8A1E8ACA-1B13-4B9C-873D-DF7C42A29473/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/855258872e8b4bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/44F7CBCD-3B22-461F-AFB8-1C1FB9788758/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49654"
,(lldb)     command script import "/tmp/8A1E8ACA-1B13-4B9C-873D-DF7C42A29473/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 04:33:07.498 ThaliTest[1345:1663202] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EC36E506-250D-46CF-A62C-CB7E6A5B1BC3/Library/Cookies/Cookies.binarycookies
,2016-09-22 04:33:07.536 ThaliTest[1345:1663202] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 04:33:07.537 ThaliTest[1345:1663202] Multi-tasking -> Device: YES, App: YES
,2016-09-22 04:33:07.548 ThaliTest[1345:1663202] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 04:33:07.865 ThaliTest[1345:1663202] Using UIWebView
,2016-09-22 04:33:07.870 ThaliTest[1345:1663202] [CDVTimer][handleopenurl] 0.198960ms
,2016-09-22 04:33:07.874 ThaliTest[1345:1663202] [CDVTimer][intentandnavigationfilter] 3.449976ms
2016-09-22 04:33:07.874 ThaliTest[1345:1663202] [CDVTimer][gesturehandler] 0.136018ms
2016-09-22 04:33:07.874 ThaliTest[1345:1663202] [CDVTimer][TotalPluginS,tartup] 4.576981ms
,2016-09-22 04:33:13.454 ThaliTest[1345:1663202] Resetting plugins due to page load.
,2016-09-22 04:33:13.952 ThaliTest[1345:1663202] Finished load of: file:///var/containers/Bundle/Application/44F7CBCD-3B22-461F-AFB8-1C1FB9788758/ThaliTest.app/www/index.html
,2016-09-22 04:33:14.319 ThaliTest[1345:1663202] JXcore Cordova plugin initializing
,2016-09-22 04:33:14.320 ThaliTest[1345:1663390] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x151815b00>
,Optional("D353F97F-5AAC-4CB2-A1F4-9EF53CD963DD")
,nil
,nil
,Optional("CD2E7EF0-086B-45DB-98A1-4FA767E0AC88")
,Optional("B7BDDAE8-3975-4E43-A71E-D8901BB10EFC")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 04:33:35.324 ThaliTest[1345:1663202] BTM: attaching to BTServer
,2016-09-22 04:33:36.113 ThaliTest[1345:1663202] BTM: local device power state changed
2016-09-22 04:33:36.114 ThaliTest[1345:1663202] BTM: power is now on
,2016-09-22 04:33:40.824 ThaliTest[1345:1663202] BTM: local device power state changed
2016-09-22 04:33:40.824 ThaliTest[1345:1663202] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.21726304292679
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
