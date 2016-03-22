#### Test 63680118f1433de_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/16B9F4A6-BB45-44BA-9DF0-9D5FB3EA19A9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/16B9F4A6-BB45-44BA-9DF0-9D5FB3EA19A9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118f1433de/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E1786485-144D-4F75-9F97-7603DD50C364/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54864"
,(lldb)     command script import "/tmp/16B9F4A6-BB45-44BA-9DF0-9D5FB3EA19A9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 15:38:07.463 ThaliTest[2042:3425547] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/92B99DF7-FDA8-4F49-9BB8-98FC2BEE9479/Library/Cookies/Cookies.binarycookies
,2016-03-22 15:38:07.900 ThaliTest[2042:3425547] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 15:38:07.901 ThaliTest[2042:3425547] Multi-tasking -> Device: YES, App: YES
,2016-03-22 15:38:07.919 ThaliTest[2042:3425547] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 15:38:10.014 ThaliTest[2042:3425547] Using UIWebView
,2016-03-22 15:38:10.022 ThaliTest[2042:3425547] [CDVTimer][handleopenurl] 0.514984ms
,2016-03-22 15:38:10.030 ThaliTest[2042:3425547] [CDVTimer][intentandnavigationfilter] 6.955981ms
,2016-03-22 15:38:10.030 ThaliTest[2042:3425547] [CDVTimer][gesturehandler] 0.324011ms
,2016-03-22 15:38:10.031 ThaliTest[2042:3425547] [CDVTimer][TotalPluginStartup] 10.805011ms
,2016-03-22 15:38:18.041 ThaliTest[2042:3425547] Resetting plugins due to page load.
,2016-03-22 15:38:21.862 ThaliTest[2042:3425547] Finished load of: file:///var/mobile/Containers/Bundle/Application/E1786485-144D-4F75-9F97-7603DD50C364/ThaliTest.app/www/index.html
,2016-03-22 15:38:21.874 ThaliTest[2042:3425547] JXcore Cordova plugin initializing
,2016-03-22 15:38:21.875 ThaliTest[2042:3425794] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Process 2042 stopped
* thread #7: tid = 0x3445a8, 0x28a90e94 JavaScriptCore`<redacted> + 116, name = 'WebThread', stop reason = EXC_BAD_ACCESS (code=1, address=0xbbadbeef)
    frame #0: 0x28a90e94 JavaScriptCore`<redacted> + 116
JavaScriptCore`<redacted>:
->  0x28a90e94 <+116>: str.w  r8, [r0]
    0x28a90e98 <+120>: ldr.w  r0, [r4, #0x160]
    0x28a90e9c <+124>: movw   r8, #0xfffe
    0x28a90ea0 <+128>: add.w  r3, r10, #0x300000
,* thread #7: tid = 0x3445a8, 0x28a90e94 JavaScriptCore`<redacted> + 116, name = 'WebThread', stop reason = EXC_BAD_ACCESS (code=1, address=0xbbadbeef)
  * frame #0: 0x28a90e94 JavaScriptCore`<redacted> + 116
    frame #1: 0x28a8f6b4 JavaScriptCore`<redacted> + 188
    frame #2: 0x28a8f53e JavaScriptCore`<redacted> + 18
    frame #3: 0x28a8e440 JavaScriptCore`<redacted> + 112
    frame #4: 0x28a8e5ba JavaScriptCore`<redacted> + 134
    frame #5: 0x36fb4348 WebCore`<redacted> + 88
    frame #6: 0x367803ae WebCore`WebCore::JSDOMWindow::setTimeout(JSC::ExecState*) + 54
    frame #7: 0x3678034a WebCore`<redacted> + 106
    frame #8: 0x289cf782 JavaScriptCore`<redacted> + 21394

```
