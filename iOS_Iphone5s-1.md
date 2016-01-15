#### Test 561517803567b2a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F1B9AE9C-3138-48FC-8264-1D41F3F6167A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F1B9AE9C-3138-48FC-8264-1D41F3F6167A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/561517803567b2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/557277D8-D6FA-4BF2-A5B7-41A7FACC427E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56071"
,(lldb)     command script import "/tmp/F1B9AE9C-3138-48FC-8264-1D41F3F6167A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 11:58:55.389 ThaliTest[1967:4646588] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14044874-7C2E-48EB-A694-F5D0C04878CF/Library/Cookies/Cookies.binarycookies
,2016-01-15 11:58:55.651 ThaliTest[1967:4646588] Apache Cordova native platform version 3.9.2 is starting.
2016-01-15 11:58:55.651 ThaliTest[1967:4646588] Multi-tasking -> Device: YES, App: YES
,2016-01-15 11:58:55.658 ThaliTest[1967:4646588] Unlimited access to network resources
,2016-01-15 11:58:55.667 ThaliTest[1967:4646588] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 11:58:59.598 ThaliTest[1967:4646588] Resetting plugins due to page load.
,2016-01-15 11:59:01.048 ThaliTest[1967:4646588] Finished load of: file:///var/mobile/Containers/Bundle/Application/557277D8-D6FA-4BF2-A5B7-41A7FACC427E/ThaliTest.app/www/index.html
,2016-01-15 11:59:01.230 ThaliTest[1967:4646588] JXcore Cordova plugin initializing
2016-01-15 11:59:01.231 ThaliTest[1967:4646735] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
