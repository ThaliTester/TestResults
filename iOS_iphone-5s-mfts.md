#### Test 9835488260af434_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9697ECD1-E905-4E37-AF40-7ADB0C86984C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/9697ECD1-E905-4E37-AF40-7ADB0C86984C/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9835488260af434/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/08D2C260-CE79-4CBD-9304-5E19A4D14167/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55136"
,(lldb)     command script import "/tmp/9697ECD1-E905-4E37-AF40-7ADB0C86984C/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-12-19 12:53:05.406 ThaliTest[881:1509112] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EC0D7756-E4FE-4AB2-BBC4-748CA6842C12/Library/Cookies/Cookies.binarycookies
,2016-12-19 12:53:05.464 ThaliTest[881:1509112] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 12:53:05.465 ThaliTest[881:1509112] Multi-tasking -> Device: YES, App: YES
,2016-12-19 12:53:05.482 ThaliTest[881:1509112] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 12:53:05.808 ThaliTest[881:1509112] Using UIWebView
,2016-12-19 12:53:05.813 ThaliTest[881:1509112] [CDVTimer][handleopenurl] 0.338018ms
,2016-12-19 12:53:05.818 ThaliTest[881:1509112] [CDVTimer][intentandnavigationfilter] 4.648983ms
2016-12-19 12:53:05.818 ThaliTest[881:1509112] [CDVTimer][gesturehandler] 0.186980ms
2016-12-19 12:53:05.818 ThaliTest[881:1509112] [CDVTimer][TotalPluginStar,tup] 6.161988ms
,2016-12-19 12:53:11.822 ThaliTest[881:1509112] Resetting plugins due to page load.
,2016-12-19 12:53:12.203 ThaliTest[881:1509112] Finished load of: file:///var/containers/Bundle/Application/08D2C260-CE79-4CBD-9304-5E19A4D14167/ThaliTest.app/www/index.html
,2016-12-19 12:53:12.622 ThaliTest[881:1509112] JXcore Cordova plugin initializing
,2016-12-19 12:53:12.623 ThaliTest[881:1509314] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 11:53:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 11:53:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 11:53:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-19 11:53:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 11:53:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 11:53:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.95267200469971
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
