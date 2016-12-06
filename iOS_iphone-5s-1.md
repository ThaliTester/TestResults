#### Test 965242983906281_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/3FF9C9AC-00CC-44B4-A6C9-3A2B08628C27/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3FF9C9AC-00CC-44B4-A6C9-3A2B08628C27/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.1/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/965242983906281/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/136367E3-4A1E-45E0-A364-9437E2C9934B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52512"
,(lldb)     command script import "/tmp/3FF9C9AC-00CC-44B4-A6C9-3A2B08628C27/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-06 16:04:19.812 ThaliTest[302:146004] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DEFC38A-E7FA-43BA-9D65-544FE90E8176/Library/Cookies/Cookies.binarycookies
(lldb) ,2016-12-06 16:04:19.927 ThaliTest[302:146004] Apache Cordova native platform version 4.3.1 is starting.
2016-12-06 16:04:19.928 ThaliTest[302:146004] Multi-tasking -> Device: YES, App: YES
(lldb) ,2016-12-06 16:04:19.944 ThaliTest[302:146004] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

(lldb) ,2016-12-06 16:04:22.007 ThaliTest[302:146004] Using UIWebView
,2016-12-06 16:04:22.019 ThaliTest[302:146004] [CDVTimer][handleopenurl] 0.429988ms
(lldb) ,2016-12-06 16:04:22.030 ThaliTest[302:146004] [CDVTimer][intentandnavigationfilter] 10.290980ms
2016-12-06 16:04:22.030 ThaliTest[302:146004] [CDVTimer][gesturehandler] 0.394046ms
2016-12-06 16:04:22.031 ThaliTest[302:146004] [CDVTimer][TotalPluginStartup] 13.112009ms
,2016-12-06 16:04:28.822 ThaliTest[302:146004] Resetting plugins due to page load.
(lldb) ,2016-12-06 16:04:32.611 ThaliTest[302:146004] Finished load of: file:///var/mobile/Containers/Bundle/Application/136367E3-4A1E-45E0-A364-9437E2C9934B/ThaliTest.app/www/index.html
(lldb) ,2016-12-06 16:04:32.938 ThaliTest[302:146004] JXcore Cordova plugin initializing
,2016-12-06 16:04:32.939 ThaliTest[302:146253] JXcore instance initializing
(lldb) ,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
,Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2016-12-06 15:04:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2016-12-06 15:04:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-06 15:04:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
(lldb) ,2016-12-06 15:04:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-06 15:04:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,Optional(true)
Optional(false)
Optional(false)
Optional(true)
(lldb) ,2016-12-06 15:05:11 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
,Total number of executed tests:  116
(lldb) ,Number of passed tests:  116
,Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
,Total duration:  25.09381800889969
(lldb) ,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
