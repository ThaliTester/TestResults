#### Test 7976383092ab77f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F6123DB0-20DB-4774-B0AB-57469C7CE20A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F6123DB0-20DB-4774-B0AB-57469C7CE20A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4DB5B94F-C446-47C0-B91A-D267241AE15E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54914"
,(lldb)     command script import "/tmp/F6123DB0-20DB-4774-B0AB-57469C7CE20A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/4DB5B94F-C446-47C0-B91A-D267241AE15E/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/C,ontainers/Bundle/Application/4DB5B94F-C446-47C0-B91A-D267241AE15E/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/4DB5B94F-C446-47C0-B91A-D267241AE15E/ThaliTest,Process 236 stopped
* thread #1: tid = 0xb53c, 0x1fe6908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x1fe6908c dyld`dyld_fatal_error
dyld`dyld_fatal_error:
->  0x1fe6908c <+0>: trap   
    0x1fe69090 <+4>: nop    

dyld`gdb_image_notifier:
    0x1fe69094 <+0>: bx     lr

dyld`dyldbootstrap::start:
    0x1fe69098 <+0>: push   {r4, r5, r6, r7, lr}
,* thread #1: tid = 0xb53c, 0x1fe6908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fe6908c dyld`dyld_fatal_error
    frame #1: 0x1fe6b99a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fe6deaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fe691ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fe69040 dyld`_dyld_start + 64

```
