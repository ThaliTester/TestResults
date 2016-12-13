#### Test 9781689977f4746_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/0D5D200D-082C-4404-83D3-23879AFC9B87/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/0D5D200D-082C-4404-83D3-23879AFC9B87/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/87543869-90D6-496C-B7D5-E23E723900A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57056"
,(lldb)     command script import "/tmp/0D5D200D-082C-4404-83D3-23879AFC9B87/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 20:45:40.304 ThaliTest[698:831909] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AAAB54FD-DB9C-40E3-BEFE-319C7EA9CC9F/Library/Cookies/Cookies.binarycookies
,2016-12-13 20:45:40.346 ThaliTest[698:831909] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 20:45:40.347 ThaliTest[698:831909] Multi-tasking -> Device: YES, App: YES
,2016-12-13 20:45:40.367 ThaliTest[698:831909] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 20:45:40.704 ThaliTest[698:831909] Using UIWebView
,2016-12-13 20:45:40.709 ThaliTest[698:831909] [CDVTimer][handleopenurl] 0.295043ms
,2016-12-13 20:45:40.715 ThaliTest[698:831909] [CDVTimer][intentandnavigationfilter] 5.872011ms
2016-12-13 20:45:40.716 ThaliTest[698:831909] [CDVTimer][gesturehandler] 0.199020ms
2016-12-13 20:45:40.716 ThaliTest[698:831909] [CDVTimer][TotalPluginStartup,] 7.473052ms
,2016-12-13 20:45:46.236 ThaliTest[698:831909] Resetting plugins due to page load.
,2016-12-13 20:45:46.589 ThaliTest[698:831909] Finished load of: file:///var/containers/Bundle/Application/87543869-90D6-496C-B7D5-E23E723900A0/ThaliTest.app/www/index.html
,2016-12-13 20:45:46.925 ThaliTest[698:831909] JXcore Cordova plugin initializing
,2016-12-13 20:45:46.926 ThaliTest[698:832107] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 19:45:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 19:45:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 19:45:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 19:45:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 19:45:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-13 19:46:22 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.88658398389816
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
