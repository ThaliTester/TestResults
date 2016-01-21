#### Test 56449660311ec66_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/333BE554-255A-4C57-9B0B-CF4C424EB75A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/333BE554-255A-4C57-9B0B-CF4C424EB75A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56449660311ec66/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59264"
,(lldb)     command script import "/tmp/333BE554-255A-4C57-9B0B-CF4C424EB75A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-21 10:16:07.715 ThaliTest[2466:5360225] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C23059E-3586-402C-9CEA-520AAD6B1781/Library/Cookies/Cookies.binarycookies
,2016-01-21 10:16:07.972 ThaliTest[2466:5360225] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-21 10:16:07.973 ThaliTest[2466:5360225] Multi-tasking -> Device: YES, App: YES
,2016-01-21 10:16:07.979 ThaliTest[2466:5360225] Unlimited access to network resources
,2016-01-21 10:16:07.985 ThaliTest[2466:5360225] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-21 10:16:12.133 ThaliTest[2466:5360225] Resetting plugins due to page load.
,2016-01-21 10:16:13.630 ThaliTest[2466:5360225] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/index.html
,2016-01-21 10:16:13.768 ThaliTest[2466:5360225] JXcore Cordova plugin initializing
,2016-01-21 10:16:13.769 ThaliTest[2466:5360414] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D19B236-987F-47CF-B98B-A1F8B7BFC0AD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded


```
