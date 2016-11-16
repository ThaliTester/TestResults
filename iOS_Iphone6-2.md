#### Test 93986313a169e88_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7FDFC649-589D-4451-B826-02E9C46284FD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7FDFC649-589D-4451-B826-02E9C46284FD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E8E2F820-C9E5-4720-A5DD-5A559375207A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59897"
,(lldb)     command script import "/tmp/7FDFC649-589D-4451-B826-02E9C46284FD/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 08:09:31.661 ThaliTest[3547:8072984] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D038454-AEFB-4C7C-883F-E25954902F3B/Library/Cookies/Cookies.binarycookies
,2016-11-16 08:09:31.732 ThaliTest[3547:8072984] Apache Cordova native platform version 4.2.1 is starting.
2016-11-16 08:09:31.734 ThaliTest[3547:8072984] Multi-tasking -> Device: YES, App: YES
,2016-11-16 08:09:31.752 ThaliTest[3547:8072984] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 08:09:32.305 ThaliTest[3547:8072984] Using UIWebView
,2016-11-16 08:09:32.313 ThaliTest[3547:8072984] [CDVTimer][handleopenurl] 0.375032ms
,2016-11-16 08:09:32.321 ThaliTest[3547:8072984] [CDVTimer][intentandnavigationfilter] 7.110000ms
2016-11-16 08:09:32.321 ThaliTest[3547:8072984] [CDVTimer][gesturehandler] 0.307024ms
2016-11-16 08:09:32.322 ThaliTest[3547:8072984] [CDVTimer][TotalPluginStartup] 9.581029ms
,2016-11-16 08:09:39.288 ThaliTest[3547:8072984] Resetting plugins due to page load.
,2016-11-16 08:09:39.936 ThaliTest[3547:8072984] Finished load of: file:///var/containers/Bundle/Application/E8E2F820-C9E5-4720-A5DD-5A559375207A/ThaliTest.app/www/index.html
,2016-11-16 08:09:40.347 ThaliTest[3547:8072984] JXcore Cordova plugin initializing
,2016-11-16 08:09:40.348 ThaliTest[3547:8073158] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 16:09:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 16:09:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 16:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 16:09:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 16:09:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-16 16:10:14 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.08152604103088
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
