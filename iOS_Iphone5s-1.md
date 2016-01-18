#### Test 5635717154d1b6f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EB7DCF75-3173-41CE-A01E-8D38075C0542/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EB7DCF75-3173-41CE-A01E-8D38075C0542/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5635717154d1b6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58062"
,(lldb)     command script import "/tmp/EB7DCF75-3173-41CE-A01E-8D38075C0542/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-18 16:56:00.209 ThaliTest[2198:5411917] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EFB2CE8D-29C2-4C42-B881-FF452FC7C410/Library/Cookies/Cookies.binarycookies
,2016-01-18 16:56:00.475 ThaliTest[2198:5411917] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-18 16:56:00.476 ThaliTest[2198:5411917] Multi-tasking -> Device: YES, App: YES
,2016-01-18 16:56:00.484 ThaliTest[2198:5411917] Unlimited access to network resources
,2016-01-18 16:56:00.496 ThaliTest[2198:5411917] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-18 16:56:04.499 ThaliTest[2198:5411917] Resetting plugins due to page load.
,2016-01-18 16:56:05.979 ThaliTest[2198:5411917] Finished load of: file:///var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/index.html
,2016-01-18 16:56:06.189 ThaliTest[2198:5411917] JXcore Cordova plugin initializing
,2016-01-18 16:56:06.191 ThaliTest[2198:5412088] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A7D93EDF-447D-4A51-8DB6-FE66AF428D18/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test app app.js loaded
,--= Surplus to requirements =--
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
