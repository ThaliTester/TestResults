#### Test 5753124374916c2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D0AD488C-E8B5-4E4F-84F0-5E4A2D31A7A9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D0AD488C-E8B5-4E4F-84F0-5E4A2D31A7A9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50647"
,(lldb)     command script import "/tmp/D0AD488C-E8B5-4E4F-84F0-5E4A2D31A7A9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 15:12:12.437 ThaliTest[2597:7977615] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB044F0F-BA72-4ACA-8FF5-D90D932974EE/Library/Cookies/Cookies.binarycookies
,2016-02-05 15:12:13.043 ThaliTest[2597:7977615] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 15:12:13.045 ThaliTest[2597:7977615] Multi-tasking -> Device: YES, App: YES
,2016-02-05 15:12:13.049 ThaliTest[2597:7977615] Unlimited access to network resources
,2016-02-05 15:12:13.062 ThaliTest[2597:7977615] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 15:12:24.099 ThaliTest[2597:7977615] Resetting plugins due to page load.
,2016-02-05 15:12:27.747 ThaliTest[2597:7977615] Finished load of: file:///var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/index.html
,2016-02-05 15:12:27.957 ThaliTest[2597:7977615] JXcore Cordova plugin initializing
,2016-02-05 15:12:28.170 ThaliTest[2597:7977948] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A49CFFAD-76B9-4094-BA14-808D01FFA2AC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
