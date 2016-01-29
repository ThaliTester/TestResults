#### Test 57531243c766d4e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0F3FA130-D12D-407B-A238-B473FA20AE4A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0F3FA130-D12D-407B-A238-B473FA20AE4A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63101"
,(lldb)     command script import "/tmp/0F3FA130-D12D-407B-A238-B473FA20AE4A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 18:54:47.564 ThaliTest[2163:6820781] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DF08221B-5192-409B-BEF9-D33B98632E5E/Library/Cookies/Cookies.binarycookies
,2016-01-29 18:54:47.673 ThaliTest[2163:6820781] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 18:54:47.675 ThaliTest[2163:6820781] Multi-tasking -> Device: YES, App: YES
,2016-01-29 18:54:47.679 ThaliTest[2163:6820781] Unlimited access to network resources
,2016-01-29 18:54:47.691 ThaliTest[2163:6820781] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 18:54:53.984 ThaliTest[2163:6820781] Resetting plugins due to page load.
,2016-01-29 18:54:56.488 ThaliTest[2163:6820781] Finished load of: file:///var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/index.html
,2016-01-29 18:54:56.676 ThaliTest[2163:6820781] JXcore Cordova plugin initializing
,2016-01-29 18:54:56.806 ThaliTest[2163:6820932] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/994369F7-D5CD-485B-BCAE-D8FEBB9F4464/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```
