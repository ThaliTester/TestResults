#### Test 5133502893bec48_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/562EC78E-CFBA-4F50-8B92-97ADFA0BE600/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/562EC78E-CFBA-4F50-8B92-97ADFA0BE600/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502893bec48/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AD38E62B-24C0-4EA0-8998-15CAEE872754/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50742"
,(lldb)     command script import "/tmp/562EC78E-CFBA-4F50-8B92-97ADFA0BE600/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-20 10:49:09.988 ThaliTest[808:933498] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/245C5BFF-A897-4124-A085-689658A34127/Library/Cookies/Cookies.binarycookies
,2015-11-20 10:49:10.273 ThaliTest[808:933498] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-20 10:49:10.274 ThaliTest[808:933498] Multi-tasking -> Device: YES, App: YES
,2015-11-20 10:49:10.280 ThaliTest[808:933498] Unlimited access to network resources
,2015-11-20 10:49:10.286 ThaliTest[808:933498] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-20 10:49:14.315 ThaliTest[808:933498] Resetting plugins due to page load.
,2015-11-20 10:49:15.587 ThaliTest[808:933498] Finished load of: file:///var/mobile/Containers/Bundle/Application/AD38E62B-24C0-4EA0-8998-15CAEE872754/ThaliTest.app/www/index.html
,2015-11-20 10:49:15.732 ThaliTest[808:933498] JXcore Cordova plugin initializing
2015-11-20 10:49:15.733 ThaliTest[808:933687] JXcore instance initializing
,Process 808 stopped
* thread #15: tid = 0xe3f37, 0x2517d6ba CoreFoundation`<redacted> + 294, stop reason = EXC_BAD_ACCESS (code=1, address=0x0)
    frame #0: 0x2517d6ba CoreFoundation`<redacted> + 294
CoreFoundation`<redacted>:
->  0x2517d6ba <+294>: ldr.w  r0, [r6, r11, lsl #2]
    0x2517d6be <+298>: cmp    r0, #0x0
    0x2517d6c0 <+300>: beq    0x2517d710                ; <+380>
    0x2517d6c2 <+302>: movw   r1, #0xd232
,* thread #15: tid = 0xe3f37, 0x2517d6ba CoreFoundation`<redacted> + 294, stop reason = EXC_BAD_ACCESS (code=1, address=0x0)
  * frame #0: 0x2517d6ba CoreFoundation`<redacted> + 294
    frame #1: 0x000163b0 ThaliTest`+[JXcore addNativeMethod:withName:] + 204
    frame #2: 0x0001390a ThaliTest`+[JXcore initialize:withCallback:namedAs:] + 262
    frame #3: 0x00013786 ThaliTest`__43+[JXcore startEngine:withCallback:namedAs:]_block_invoke + 86
    frame #4: 0x00014564 ThaliTest`+[JXcore threadMain] + 716
    frame #5: 0x260377fc Foundation`<redacted> + 1144
    frame #6: 0x373cbc92 libsystem_pthread.dylib`<redacted> + 138
    frame #7: 0x373cbc06 libsystem_pthread.dylib`_pthread_start + 110
    frame #8: 0x373c9a24 libsystem_pthread.dylib`thread_start + 8

```
