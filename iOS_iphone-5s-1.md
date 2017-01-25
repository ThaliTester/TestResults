#### Test 10307209017d2aad_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/81AE50D3-0871-49BD-8BB3-F100E6A552D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/81AE50D3-0871-49BD-8BB3-F100E6A552D0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BE06D62D-DBF1-4DB0-A573-197604477DC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50027"
,(lldb)     command script import "/tmp/81AE50D3-0871-49BD-8BB3-F100E6A552D0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,success
,(lldb)     autoexit
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 09:43:14.782 ThaliTest[2840:7092487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3675299-D403-454A-AF34-7DBAE7C92306/Library/Cookies/Cookies.binarycookies
,2017-01-25 09:43:14.848 ThaliTest[2840:7092487] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-25 09:43:14.849 ThaliTest[2840:7092487] Multi-tasking -> Device: YES, App: YES
,2017-01-25 09:43:14.869 ThaliTest[2840:7092487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-25 09:43:15.704 ThaliTest[2840:7092487] Using UIWebView
,2017-01-25 09:43:15.709 ThaliTest[2840:7092487] [CDVTimer][handleopenurl] 0.198007ms
,2017-01-25 09:43:15.714 ThaliTest[2840:7092487] [CDVTimer][intentandnavigationfilter] 4.640996ms
2017-01-25 09:43:15.714 ThaliTest[2840:7092487] [CDVTimer][gesturehandler] 0.184000ms
2017-01-25 09:43:15.714 ThaliTest[2840:7092487] [CDVTimer][TotalPluginS,tartup] 5.823016ms
,2017-01-25 09:43:18.888 ThaliTest[2840:7092487] Resetting plugins due to page load.
,2017-01-25 09:43:20.510 ThaliTest[2840:7092487] Finished load of: file:///var/mobile/Containers/Bundle/Application/BE06D62D-DBF1-4DB0-A573-197604477DC4/ThaliTest.app/www/index.html
,2017-01-25 09:43:20.725 ThaliTest[2840:7092487] JXcore Cordova plugin initializing
,2017-01-25 09:43:20.726 ThaliTest[2840:7092672] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 08:43:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-25 08:43:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-25 08:43:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-25 08:43:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-25 08:43:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 08:44:01 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.03352802991867
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
