#### Test 85046911c0a96fd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4FCE1B44-FF0A-49C1-931D-D3026B541E42/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4FCE1B44-FF0A-49C1-931D-D3026B541E42/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9230266B-CDC9-4CDC-8BDD-9FE924C2E959/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56553"
,(lldb)     command script import "/tmp/4FCE1B44-FF0A-49C1-931D-D3026B541E42/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 13:05:16.156 ThaliTest[3365:6787526] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F37B34B5-197B-4861-AD7A-A1C2DDE18741/Library/Cookies/Cookies.binarycookies
,2016-09-27 13:05:16.280 ThaliTest[3365:6787526] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 13:05:16.282 ThaliTest[3365:6787526] Multi-tasking -> Device: YES, App: YES
,2016-09-27 13:05:16.303 ThaliTest[3365:6787526] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 13:05:17.775 ThaliTest[3365:6787526] Using UIWebView
,2016-09-27 13:05:17.786 ThaliTest[3365:6787526] [CDVTimer][handleopenurl] 0.579000ms
,2016-09-27 13:05:17.795 ThaliTest[3365:6787526] [CDVTimer][intentandnavigationfilter] 8.370996ms
2016-09-27 13:05:17.796 ThaliTest[3365:6787526] [CDVTimer][gesturehandler] 0.394046ms
2016-09-27 13:05:17.796 ThaliTest[3365:6787526] [CDVTimer][TotalPluginS,tartup] 11.218011ms
,2016-09-27 13:05:23.838 ThaliTest[3365:6787526] Resetting plugins due to page load.
,2016-09-27 13:05:27.366 ThaliTest[3365:6787526] Finished load of: file:///var/mobile/Containers/Bundle/Application/9230266B-CDC9-4CDC-8BDD-9FE924C2E959/ThaliTest.app/www/index.html
,2016-09-27 13:05:27.948 ThaliTest[3365:6787526] JXcore Cordova plugin initializing
,2016-09-27 13:05:27.950 ThaliTest[3365:6787749] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x10aaafbf0>
,Optional("C2F5A871-D9F6-4F7C-98C9-292E0F975969")
,nil
,nil
,Optional("415C16BF-97F5-4939-B356-A74719E91FD4")
,Optional("CF79BA32-04E6-43A7-A590-018136FAFF4D")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.47762602567673
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
