#### Test 506502784dae475_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/2D0B3799-2F8E-4DF5-BFEB-ECB5E37562DF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2D0B3799-2F8E-4DF5-BFEB-ECB5E37562DF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502784dae475/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/848A0431-4206-4ADA-8D59-798FCD6FF6FA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53242"
,(lldb)     command script import "/tmp/2D0B3799-2F8E-4DF5-BFEB-ECB5E37562DF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 13:35:29.965 ThaliTest[715:561498] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BEB36389-4BCB-497C-A754-D273BCF188FB/Library/Cookies/Cookies.binarycookies
,2015-12-10 13:35:29.977 ThaliTest[715:561498] <CATransformLayer: 0x14712060> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 13:35:29.979 ThaliTest[715:561498] <CATransformLayer: 0x1463bcf0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 13:35:29.980 ThaliTest[715:561498] <CATransformLayer: 0x1452d170> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-10 13:35:30.271 ThaliTest[715:561498] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 13:35:30.272 ThaliTest[715:561498] Multi-tasking -> Device: YES, App: YES
,2015-12-10 13:35:30.280 ThaliTest[715:561498] Unlimited access to network resources
,2015-12-10 13:35:30.286 ThaliTest[715:561498] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 13:35:39.178 ThaliTest[715:561498] Resetting plugins due to page load.
,2015-12-10 13:35:42.544 ThaliTest[715:561498] Finished load of: file:///var/mobile/Containers/Bundle/Application/848A0431-4206-4ADA-8D59-798FCD6FF6FA/ThaliTest.app/www/index.html
,2015-12-10 13:35:42.686 ThaliTest[715:561498] JXcore Cordova plugin initializing
,2015-12-10 13:35:42.687 ThaliTest[715:561754] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded

```
