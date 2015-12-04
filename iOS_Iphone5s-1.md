#### Test 52539314a265f91_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/447480C2-249E-468F-9EEB-0D3D6C9037D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/447480C2-249E-468F-9EEB-0D3D6C9037D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A999815F-B23F-40DF-9760-8252AD97C472/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61309"
,(lldb)     command script import "/tmp/447480C2-249E-468F-9EEB-0D3D6C9037D4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:02:58.656 ThaliTest[2592:2396267] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1F6B9919-4B8B-4452-BDA5-2AE1DC2E2332/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:02:59.021 ThaliTest[2592:2396267] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:02:59.022 ThaliTest[2592:2396267] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:02:59.031 ThaliTest[2592:2396267] Unlimited access to network resources
,2015-12-04 09:02:59.037 ThaliTest[2592:2396267] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:03:01.872 ThaliTest[2592:2396267] Resetting plugins due to page load.
,2015-12-04 09:03:02.167 ThaliTest[2592:2396267] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/A999815F-B23F-40DF-9760-8252AD97C472/ThaliTest.app/www/index.html
,2015-12-04 09:03:02.347 ThaliTest[2592:2396267] JXcore Cordova plugin initializing
,2015-12-04 09:03:02.347 ThaliTest[2592:2396483] JXcore instance initializing
,ThaliTest(2592,0x3b5449dc) malloc: *** error for object 0x156eb164: incorrect checksum for freed object - object was probably modified after being freed.
*** set a breakpoint in malloc_error_break to debug
,* thread #1: tid = 0x24906b, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x38df13ae libsystem_malloc.dylib`<redacted> + 334
    frame #4: 0x38df1658 libsystem_malloc.dylib`<redacted> + 28
    frame #5: 0x38de9402 libsystem_malloc.dylib`<redacted> + 1026
    frame #6: 0x38de7eba libsystem_malloc.dylib`<redacted> + 222
    frame #7: 0x38de7da8 libsystem_malloc.dylib`malloc_zone_malloc + 88
    frame #8: 0x3877441e libobjc.A.dylib`<redacted> + 86
    frame #9: 0x3876e090 libobjc.A.dylib`<redacted> + 1084
    frame #10: 0x3876c4b8 libobjc.A.dylib`<redacted> + 176
    frame #11: 0x3877105a libobjc.A.dylib`<redacted> + 250
    frame #12: 0x38770f56 libobjc.A.dylib`<redacted> + 34
    frame #13: 0x387771d8 libobjc.A.dylib`<redacted> + 24
    frame #14: 0x0003a53c ThaliTest`-[CDVJXcore onResume:] + 148
    frame #15: 0x000842e2 ThaliTest`-[CDVCommandQueue execute:] + 906
    frame #16: 0x00083bde ThaliTest`-[CDVCommandQueue executePending] + 726
    frame #17: 0x0007cb98 ThaliTest`-[CDVViewController webView:shouldStartLoadWithRequest:navigationType:] + 328
    frame #18: 0x00088882 ThaliTest`-[CDVWebViewDelegate webView:shouldStartLoadWithRequest:navigationType:] + 230
    frame #19: 0x2dfcc60e UIKit`<redacted> + 290
    frame #20: 0x2a8abad4 CoreFoundation`<redacted> + 68
    frame #21: 0x2a7d8644 CoreFoundation`<redacted> + 300
    frame #22: 0x2a7dc0c6 CoreFoundation`<redacted> + 50
    frame #23: 0x36cd7260 WebKitLegacy`<redacted> + 224
    frame #24: 0x2a8aa62e CoreFoundation`<redacted> + 354
    frame #25: 0x2a7dc008 CoreFoundation`<redacted> + 24
    frame #26: 0x2a8abad4 CoreFoundation`<redacted> + 68
    frame #27: 0x2a7d8644 CoreFoundation`<redacted> + 300
    frame #28: 0x36200728 WebCore`<redacted> + 100
    frame #29: 0x2a86dfbe CoreFoundation`<redacted> + 14
    frame #30: 0x2a86d3ce CoreFoundation`<redacted> + 218
    frame #31: 0x2a86ba34 CoreFoundation`<redacted> + 772
    frame #32: 0x2a7b93b0 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #33: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #34: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #35: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #36: 0x000385e2 ThaliTest`main + 50

```
