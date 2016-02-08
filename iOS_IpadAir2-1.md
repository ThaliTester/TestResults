#### Test 586024278176cca_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/586024278176cca/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/2008D1D7-AC41-4D65-9567-8C53A54FD3B1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2008D1D7-AC41-4D65-9567-8C53A54FD3B1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/586024278176cca/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/586024278176cca/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BB37AF92-55F9-4E6C-90DD-6A7D75C608FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51670"
,(lldb)     command script import "/tmp/2008D1D7-AC41-4D65-9567-8C53A54FD3B1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 13:35:50.496 ThaliTest[879:1571182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6C53E2E7-674A-4B5A-A06E-60E14FB5D449/Library/Cookies/Cookies.binarycookies
,2016-02-08 13:35:50.829 ThaliTest[879:1571182] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 13:35:50.830 ThaliTest[879:1571182] Multi-tasking -> Device: YES, App: YES
,2016-02-08 13:35:50.838 ThaliTest[879:1571182] Unlimited access to network resources
,2016-02-08 13:35:50.844 ThaliTest[879:1571182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 13:35:54.461 ThaliTest[879:1571182] Resetting plugins due to page load.
,2016-02-08 13:35:58.178 ThaliTest[879:1571182] Finished load of: file:///var/mobile/Containers/Bundle/Application/BB37AF92-55F9-4E6C-90DD-6A7D75C608FF/ThaliTest.app/www/index.html
,2016-02-08 13:35:58.360 ThaliTest[879:1571182] JXcore Cordova plugin initializing
,2016-02-08 13:35:58.360 ThaliTest[879:1571826] JXcore instance initializing
,Process 879 stopped
* thread #17: tid = 0x17fbf2, 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6, stop reason = EXC_BAD_ACCESS (code=1, address=0x8c7ae00c)
    frame #0: 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x362c3ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x362c3aea <+10>: ldr.w  r9, [r9, #0x8]
    0x362c3aee <+14>: and.w  r12, r12, r1
    0x362c3af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #17: tid = 0x17fbf2, 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6, stop reason = EXC_BAD_ACCESS (code=1, address=0x8c7ae00c)
  * frame #0: 0x362c3ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x246d45ce CoreFoundation`<redacted> + 330
    frame #2: 0x00034f10 ThaliTest`+[JXcore addNativeMethod:withName:] + 204
    frame #3: 0x0003246a ThaliTest`+[JXcore initialize:withCallback:namedAs:] + 262
    frame #4: 0x000322e6 ThaliTest`__43+[JXcore startEngine:withCallback:namedAs:]_block_invoke + 86
    frame #5: 0x000330c4 ThaliTest`+[JXcore threadMain] + 716
    frame #6: 0x2559036c Foundation`<redacted> + 1144
    frame #7: 0x36b72c7e libsystem_pthread.dylib`<redacted> + 138
    frame #8: 0x36b72bf2 libsystem_pthread.dylib`_pthread_start + 110
    frame #9: 0x36b70a08 libsystem_pthread.dylib`thread_start + 8

```
