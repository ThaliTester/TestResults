#### Test 878597992c267bc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8FE430AC-4DB3-4511-96FD-7EB40D29D2B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8FE430AC-4DB3-4511-96FD-7EB40D29D2B7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/878597992c267bc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CDCCBC36-489A-44A0-B41E-FFC2DA9010C1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55069"
,(lldb)     command script import "/tmp/8FE430AC-4DB3-4511-96FD-7EB40D29D2B7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-10-04 11:46:37.438 ThaliTest[3779:6940319] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CBF39979-B45F-4121-A436-338088F109CC/Library/Cookies/Cookies.binarycookies
,2016-10-04 11:46:37.799 ThaliTest[3779:6940319] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-04 11:46:37.800 ThaliTest[3779:6940319] Multi-tasking -> Device: YES, App: YES
,2016-10-04 11:46:37.820 ThaliTest[3779:6940319] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-04 11:46:39.781 ThaliTest[3779:6940319] Using UIWebView
,2016-10-04 11:46:39.788 ThaliTest[3779:6940319] [CDVTimer][handleopenurl] 0.346959ms
,2016-10-04 11:46:39.794 ThaliTest[3779:6940319] [CDVTimer][intentandnavigationfilter] 6.352961ms
,2016-10-04 11:46:39.795 ThaliTest[3779:6940319] [CDVTimer][gesturehandler] 0.293970ms
,2016-10-04 11:46:39.795 ThaliTest[3779:6940319] [CDVTimer][TotalPluginStartup] 8.592010ms
,2016-10-04 11:46:46.113 ThaliTest[3779:6940319] Resetting plugins due to page load.
,2016-10-04 11:46:49.044 ThaliTest[3779:6940319] Finished load of: file:///var/mobile/Containers/Bundle/Application/CDCCBC36-489A-44A0-B41E-FFC2DA9010C1/ThaliTest.app/www/index.html
,2016-10-04 11:46:49.258 ThaliTest[3779:6940319] JXcore Cordova plugin initializing
,2016-10-04 11:46:49.258 ThaliTest[3779:6940632] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-04 09:46:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-04 09:46:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-04 09:46:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-04 09:46:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-04 09:46:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x1481e8fa0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("B551003B-3FCB-4F4C-8C08-23C19378AB41")
,nil
,nil
,Optional("B68C3E73-F460-4939-AB15-09691C132B58")
,Optional("4E421252-7B84-4D4C-B9F4-D56E35C4754D")
,Process 3779 stopped
* thread #17: tid = 0x69e80a, 0x000000019b3f2864 libdispatch.dylib`_os_object_release_internal + 84, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BREAKPOINT (code=1, subcode=0x19b3f2864)
    frame #0: 0x000000019b3f2864 libdispatch.dylib`_os_object_release_internal + 84
libdispatch.dylib`_os_object_release_internal:
->  0x19b3f2864 <+84>: brk    #0x1

libdispatch.dylib`dispatch_once:
    0x19b3f2868 <+0>:  ldr    x2, [x1, #16]
    0x19b3f286c <+4>:  b      0x19b3f249c               ; dispatch_once_f

libdispatch.dylib`dispatch_get_current_queue:
    0x19b3f2870 <+0>:  mrs    x8, TPIDRRO_EL0
,* thread #17: tid = 0x69e80a, 0x000000019b3f2864 libdispatch.dylib`_os_object_release_internal + 84, queue = 'com.apple.root.background-qos', activity = 'Breadcrumb initiated activity', stop reason = EXC_BREAKPOINT (code=1, subcode=0x19b3f2864)
  * frame #0: 0x000000019b3f2864 libdispatch.dylib`_os_object_release_internal + 84
    frame #1: 0x000000019b642774 libxpc.dylib`<redacted> + 56
    frame #2: 0x000000019b6428e4 libxpc.dylib`<redacted> + 72
    frame #3: 0x000000019b6427f0 libxpc.dylib`<redacted> + 44
    frame #4: 0x000000019b6427a8 libxpc.dylib`<redacted> + 28
    frame #5: 0x000000019b642774 libxpc.dylib`<redacted> + 56
    frame #6: 0x0000000185be8784 CoreBluetooth`<redacted> + 240
    frame #7: 0x0000000185be8130 CoreBluetooth`<redacted> + 44
    frame #8: 0x0000000185bdaa4c CoreBluetooth`<redacted> + 68
    frame #9: 0x0000000185be8ee0 CoreBluetooth`<redacted> + 60
    frame #10: 0x000000019b3f16e8 libdispatch.dylib`<redacted> + 24
    frame #11: 0x000000019b3f16a8 libdispatch.dylib`<redacted> + 16
    frame #12: 0x000000019b3fd6ec libdispatch.dylib`<redacted> + 864
    frame #13: 0x000000019b3f51ac libdispatch.dylib`<redacted> + 464
    frame #14: 0x000000019b3ff5bc libdispatch.dylib`<redacted> + 728
    frame #15: 0x000000019b3ff2dc libdispatch.dylib`<redacted> + 112
    frame #16: 0x000000019b611470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #17: 0x000000019b611020 libsystem_pthread.dylib`start_wqthread + 4

```
