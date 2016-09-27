#### Test 8689130568a1443_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/20FC3EC8-75ED-48C6-B8F3-2CF1DA06CACD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/20FC3EC8-75ED-48C6-B8F3-2CF1DA06CACD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/203AF464-5F86-4068-9CE2-EF0F58EBE158/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56346"
,(lldb)     command script import "/tmp/20FC3EC8-75ED-48C6-B8F3-2CF1DA06CACD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:51:53.285 ThaliTest[3350:6782888] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3AAF6934-3350-415B-9D04-2624C6CD63F9/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:51:53.409 ThaliTest[3350:6782888] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:51:53.411 ThaliTest[3350:6782888] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:51:53.432 ThaliTest[3350:6782888] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:51:55.037 ThaliTest[3350:6782888] Using UIWebView
,2016-09-27 12:51:55.049 ThaliTest[3350:6782888] [CDVTimer][handleopenurl] 0.494003ms
,2016-09-27 12:51:55.058 ThaliTest[3350:6782888] [CDVTimer][intentandnavigationfilter] 8.340001ms
2016-09-27 12:51:55.059 ThaliTest[3350:6782888] [CDVTimer][gesturehandler] 0.358999ms
2016-09-27 12:51:55.059 ThaliTest[3350:6782888] [CDVTimer][TotalPluginS,tartup] 11.090040ms
,2016-09-27 12:52:00.764 ThaliTest[3350:6782888] Resetting plugins due to page load.
,2016-09-27 12:52:04.209 ThaliTest[3350:6782888] Finished load of: file:///var/mobile/Containers/Bundle/Application/203AF464-5F86-4068-9CE2-EF0F58EBE158/ThaliTest.app/www/index.html
,2016-09-27 12:52:04.523 ThaliTest[3350:6782888] JXcore Cordova plugin initializing
,2016-09-27 12:52:04.524 ThaliTest[3350:6783109] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x16061d820>
,Optional("AA83F4A4-4CFB-48DC-8E0F-07A902262352")
,nil
,nil
,Optional("64A8D6F6-0E8C-40B7-B7C5-5DFE5579D3FC")
,Optional("566B9426-D79D-40EF-A2A0-04387407C7BF")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  15.52473300695419
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
