#### Test 10414824498b4517_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/580F48B5-A57D-4C84-B774-1067FF0BCA80/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/580F48B5-A57D-4C84-B774-1067FF0BCA80/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9ABE3744-B75F-4903-92FE-CB6D0F85A4D6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55933"
,(lldb)     command script import "/tmp/580F48B5-A57D-4C84-B774-1067FF0BCA80/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-02 17:44:50.734 ThaliTest[3174:8592513] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A7D07D9D-DF7B-461A-A256-32986ECF1D36/Library/Cookies/Cookies.binarycookies
,2017-02-02 17:44:51.107 ThaliTest[3174:8592513] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-02 17:44:51.109 ThaliTest[3174:8592513] Multi-tasking -> Device: YES, App: YES
,2017-02-02 17:44:51.128 ThaliTest[3174:8592513] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-02 17:44:53.006 ThaliTest[3174:8592513] Using UIWebView
,2017-02-02 17:44:53.013 ThaliTest[3174:8592513] [CDVTimer][handleopenurl] 0.427008ms
,2017-02-02 17:44:53.020 ThaliTest[3174:8592513] [CDVTimer][intentandnavigationfilter] 6.711960ms
,2017-02-02 17:44:53.021 ThaliTest[3174:8592513] [CDVTimer][gesturehandler] 0.304043ms
,2017-02-02 17:44:53.022 ThaliTest[3174:8592513] [CDVTimer][TotalPluginStartup] 9.068966ms
,2017-02-02 17:44:59.408 ThaliTest[3174:8592513] Resetting plugins due to page load.
,2017-02-02 17:45:02.711 ThaliTest[3174:8592513] Finished load of: file:///var/mobile/Containers/Bundle/Application/9ABE3744-B75F-4903-92FE-CB6D0F85A4D6/ThaliTest.app/www/index.html
,2017-02-02 17:45:02.857 ThaliTest[3174:8592513] JXcore Cordova plugin initializing
,2017-02-02 17:45:02.858 ThaliTest[3174:8592754] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-02 16:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-02 16:45:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  29.11889004707336
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
