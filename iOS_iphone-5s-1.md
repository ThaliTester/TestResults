#### Test 10414824498b4517_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9FF11968-BB9A-4605-B03A-FD42B547EAEF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9FF11968-BB9A-4605-B03A-FD42B547EAEF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1718DC33-1EF9-45AC-851F-EE83F7208B50/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55934"
,(lldb)     command script import "/tmp/9FF11968-BB9A-4605-B03A-FD42B547EAEF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-02 17:44:47.934 ThaliTest[3221:8459781] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6DB43C14-6C65-4F37-8454-225FD52EE128/Library/Cookies/Cookies.binarycookies
,2017-02-02 17:44:48.056 ThaliTest[3221:8459781] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-02 17:44:48.059 ThaliTest[3221:8459781] Multi-tasking -> Device: YES, App: YES
,2017-02-02 17:44:48.081 ThaliTest[3221:8459781] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-02 17:44:49.622 ThaliTest[3221:8459781] Using UIWebView
,2017-02-02 17:44:49.631 ThaliTest[3221:8459781] [CDVTimer][handleopenurl] 0.477970ms
,2017-02-02 17:44:49.642 ThaliTest[3221:8459781] [CDVTimer][intentandnavigationfilter] 10.613024ms
2017-02-02 17:44:49.643 ThaliTest[3221:8459781] [CDVTimer][gesturehandler] 0.386000ms
2017-02-02 17:44:49.643 ThaliTest[3221:8459781] [CDVTimer][TotalPluginStartup] 13.657987ms
,2017-02-02 17:44:55.357 ThaliTest[3221:8459781] Resetting plugins due to page load.
,2017-02-02 17:44:58.730 ThaliTest[3221:8459781] Finished load of: file:///var/mobile/Containers/Bundle/Application/1718DC33-1EF9-45AC-851F-EE83F7208B50/ThaliTest.app/www/index.html
,2017-02-02 17:44:59.027 ThaliTest[3221:8459781] JXcore Cordova plugin initializing
,2017-02-02 17:44:59.029 ThaliTest[3221:8460001] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-02-02 16:45:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.47983402013779
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
