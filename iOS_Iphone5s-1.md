#### Test 5065027881383b1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/600A3C23-0AC5-4778-995F-F0C876C10214/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/600A3C23-0AC5-4778-995F-F0C876C10214/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027881383b1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1A7370F0-E0DC-44AE-A7AA-D09249AB74F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53348"
,(lldb)     command script import "/tmp/600A3C23-0AC5-4778-995F-F0C876C10214/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-10 14:06:58.415 ThaliTest[695:572763] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6C9D9ED1-199E-4FBA-B17C-AEE9321787B6/Library/Cookies/Cookies.binarycookies
,2015-12-10 14:06:58.851 ThaliTest[695:572763] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 14:06:58.853 ThaliTest[695:572763] Multi-tasking -> Device: YES, App: YES
,2015-12-10 14:06:58.864 ThaliTest[695:572763] Unlimited access to network resources
,2015-12-10 14:06:58.880 ThaliTest[695:572763] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 14:07:07.971 ThaliTest[695:572763] Resetting plugins due to page load.
,2015-12-10 14:07:12.017 ThaliTest[695:572763] Finished load of: file:///var/mobile/Containers/Bundle/Application/1A7370F0-E0DC-44AE-A7AA-D09249AB74F0/ThaliTest.app/www/index.html
,2015-12-10 14:07:12.224 ThaliTest[695:572763] JXcore Cordova plugin initializing
,2015-12-10 14:07:12.226 ThaliTest[695:572979] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-10 14:07:13.533 ThaliTest[695:572763] THREAD WARNING: ['JXcore'] took '89.645996' ms. Plugin should use a background thread.

```
