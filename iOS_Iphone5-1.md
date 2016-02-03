#### Test 5813565532fb33b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D56FEB6B-B7DD-4835-9547-81B7CA7B7B78/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D56FEB6B-B7DD-4835-9547-81B7CA7B7B78/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49378"
,(lldb)     command script import "/tmp/D56FEB6B-B7DD-4835-9547-81B7CA7B7B78/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 20:27:17.631 ThaliTest[2469:7670413] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B72B98A2-1463-4E3E-B3AD-AD36C9E9DDC5/Library/Cookies/Cookies.binarycookies
,2016-02-03 20:27:18.173 ThaliTest[2469:7670413] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 20:27:18.174 ThaliTest[2469:7670413] Multi-tasking -> Device: YES, App: YES
,2016-02-03 20:27:18.179 ThaliTest[2469:7670413] Unlimited access to network resources
,2016-02-03 20:27:18.191 ThaliTest[2469:7670413] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 20:27:29.140 ThaliTest[2469:7670413] Resetting plugins due to page load.
,2016-02-03 20:27:32.753 ThaliTest[2469:7670413] Finished load of: file:///var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/index.html
,2016-02-03 20:27:32.959 ThaliTest[2469:7670413] JXcore Cordova plugin initializing
2016-02-03 20:27:32.960 ThaliTest[2469:7670738] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56400533-26D6-498C-A9BF-8B9B13D9B94A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
