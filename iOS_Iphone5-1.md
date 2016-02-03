#### Test 57924002a578a80_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FF2D1D08-9919-4058-97A0-6064152E62AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FF2D1D08-9919-4058-97A0-6064152E62AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57924002a578a80/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65220"
,(lldb)     command script import "/tmp/FF2D1D08-9919-4058-97A0-6064152E62AD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 01:39:28.100 ThaliTest[2411:7538446] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D854DE3A-58E7-4FD4-9BF3-F4A1B8F3F9EB/Library/Cookies/Cookies.binarycookies
,2016-02-03 01:39:28.211 ThaliTest[2411:7538446] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 01:39:28.212 ThaliTest[2411:7538446] Multi-tasking -> Device: YES, App: YES
,2016-02-03 01:39:28.216 ThaliTest[2411:7538446] Unlimited access to network resources
,2016-02-03 01:39:28.228 ThaliTest[2411:7538446] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 01:39:34.743 ThaliTest[2411:7538446] Resetting plugins due to page load.
,2016-02-03 01:39:37.266 ThaliTest[2411:7538446] Finished load of: file:///var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/index.html
,2016-02-03 01:39:37.456 ThaliTest[2411:7538446] JXcore Cordova plugin initializing
,2016-02-03 01:39:37.583 ThaliTest[2411:7538665] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7170F4B2-2C41-4329-A1B7-4D1F8431E1FD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
