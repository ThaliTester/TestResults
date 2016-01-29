#### Test 57531243c766d4e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A33DCC4B-8BF6-4FFE-9153-908C6430D3C0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A33DCC4B-8BF6-4FFE-9153-908C6430D3C0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63138"
,(lldb)     command script import "/tmp/A33DCC4B-8BF6-4FFE-9153-908C6430D3C0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 18:56:11.295 ThaliTest[2967:8287263] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4471B90-C3A8-4DDB-94B1-60410CD70CB2/Library/Cookies/Cookies.binarycookies
,2016-01-29 18:56:11.600 ThaliTest[2967:8287263] Apache Cordova native platform version 3.9.2 is starting.
2016-01-29 18:56:11.601 ThaliTest[2967:8287263] Multi-tasking -> Device: YES, App: YES
,2016-01-29 18:56:11.608 ThaliTest[2967:8287263] Unlimited access to network resources
,2016-01-29 18:56:11.619 ThaliTest[2967:8287263] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 18:56:15.993 ThaliTest[2967:8287263] Resetting plugins due to page load.
,2016-01-29 18:56:17.706 ThaliTest[2967:8287263] Finished load of: file:///var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/index.html
,2016-01-29 18:56:17.932 ThaliTest[2967:8287263] JXcore Cordova plugin initializing
,2016-01-29 18:56:18.022 ThaliTest[2967:8287548] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/25E5CC25-54F3-43D9-8572-D6EB672B9535/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
