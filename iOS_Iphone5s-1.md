#### Test 57617811ecc172f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57617811ecc172f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E92F8B14-88BE-4C8E-830F-E3896EDDDB9B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E92F8B14-88BE-4C8E-830F-E3896EDDDB9B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57617811ecc172f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57617811ecc172f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62695"
,(lldb)     command script import "/tmp/E92F8B14-88BE-4C8E-830F-E3896EDDDB9B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 11:28:30.865 ThaliTest[2871:8196105] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/01CEF725-F484-45D9-BB78-1F5436A0F807/Library/Cookies/Cookies.binarycookies
,2016-01-29 11:28:31.166 ThaliTest[2871:8196105] Apache Cordova native platform version 3.9.2 is starting.
2016-01-29 11:28:31.167 ThaliTest[2871:8196105] Multi-tasking -> Device: YES, App: YES
,2016-01-29 11:28:31.174 ThaliTest[2871:8196105] Unlimited access to network resources
,2016-01-29 11:28:31.184 ThaliTest[2871:8196105] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 11:28:35.793 ThaliTest[2871:8196105] Resetting plugins due to page load.
,2016-01-29 11:28:37.510 ThaliTest[2871:8196105] Finished load of: file:///var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/index.html
,2016-01-29 11:28:37.725 ThaliTest[2871:8196105] JXcore Cordova plugin initializing
,2016-01-29 11:28:37.727 ThaliTest[2871:8196367] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B8C8B576-6D92-4F88-967F-F5C5BE2E9A75/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown
,

```
