#### Test 896247960fcbde9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D0875D09-F0A0-4DEA-BD45-9BFA358E7DDA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D0875D09-F0A0-4DEA-BD45-9BFA358E7DDA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/995DC277-10A2-4777-8C94-6399AEA89EDF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64592"
,(lldb)     command script import "/tmp/D0875D09-F0A0-4DEA-BD45-9BFA358E7DDA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 11:17:11.502 ThaliTest[5329:13472374] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB5EBB2B-33C3-4666-97F9-24FA8133C99C/Library/Cookies/Cookies.binarycookies
,2016-11-08 11:17:11.629 ThaliTest[5329:13472374] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 11:17:11.630 ThaliTest[5329:13472374] Multi-tasking -> Device: YES, App: YES
,2016-11-08 11:17:11.654 ThaliTest[5329:13472374] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 11:17:13.170 ThaliTest[5329:13472374] Using UIWebView
,2016-11-08 11:17:13.181 ThaliTest[5329:13472374] [CDVTimer][handleopenurl] 0.510991ms
,2016-11-08 11:17:13.190 ThaliTest[5329:13472374] [CDVTimer][intentandnavigationfilter] 8.337021ms
2016-11-08 11:17:13.191 ThaliTest[5329:13472374] [CDVTimer][gesturehandler] 0.387013ms
2016-11-08 11:17:13.191 ThaliTest[5329:13472374] [CDVTimer][TotalPlug,inStartup] 11.121988ms
,2016-11-08 11:17:18.890 ThaliTest[5329:13472374] Resetting plugins due to page load.
,2016-11-08 11:17:22.007 ThaliTest[5329:13472374] Finished load of: file:///var/mobile/Containers/Bundle/Application/995DC277-10A2-4777-8C94-6399AEA89EDF/ThaliTest.app/www/index.html
,2016-11-08 11:17:22.319 ThaliTest[5329:13472374] JXcore Cordova plugin initializing
,2016-11-08 11:17:22.320 ThaliTest[5329:13472603] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:17:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:17:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:17:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:17:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:17:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 10:18:01 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.08580094575882
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
