#### Test 992481310a19089_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/725FF46B-B3ED-4F33-BA29-E2A4D3765C75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/725FF46B-B3ED-4F33-BA29-E2A4D3765C75/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2783FE25-5664-47FA-A60F-50E5773CE110/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55561"
,(lldb)     command script import "/tmp/725FF46B-B3ED-4F33-BA29-E2A4D3765C75/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-23 16:23:26.154 ThaliTest[1272:2604429] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A4E571B-0D0D-4E67-B69C-BF0C253F64C9/Library/Cookies/Cookies.binarycookies
,2016-12-23 16:23:26.277 ThaliTest[1272:2604429] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-23 16:23:26.279 ThaliTest[1272:2604429] Multi-tasking -> Device: YES, App: YES
,2016-12-23 16:23:26.302 ThaliTest[1272:2604429] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-23 16:23:27.802 ThaliTest[1272:2604429] Using UIWebView
,2016-12-23 16:23:27.813 ThaliTest[1272:2604429] [CDVTimer][handleopenurl] 0.432014ms
,2016-12-23 16:23:27.823 ThaliTest[1272:2604429] [CDVTimer][intentandnavigationfilter] 9.337008ms
2016-12-23 16:23:27.824 ThaliTest[1272:2604429] [CDVTimer][gesturehandler] 0.416994ms
2016-12-23 16:23:27.825 ThaliTest[1272:2604429] [CDVTimer][TotalPluginS,tartup] 12.184024ms
,2016-12-23 16:23:34.822 ThaliTest[1272:2604429] Resetting plugins due to page load.
,2016-12-23 16:23:39.458 ThaliTest[1272:2604429] Finished load of: file:///var/mobile/Containers/Bundle/Application/2783FE25-5664-47FA-A60F-50E5773CE110/ThaliTest.app/www/index.html
,2016-12-23 16:23:39.777 ThaliTest[1272:2604429] JXcore Cordova plugin initializing
,2016-12-23 16:23:39.778 ThaliTest[1272:2604648] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-23 15:23:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-23 15:23:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-23 15:23:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-23 15:23:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-23 15:23:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-23 15:24:18 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.03144598007202
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
