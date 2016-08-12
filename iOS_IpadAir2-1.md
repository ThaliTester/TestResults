#### Test 7976383092ab77f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/202B3703-04D7-41D3-8240-B28CFBC6E199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/202B3703-04D7-41D3-8240-B28CFBC6E199/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/7976383092ab77f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54911"
,(lldb)     command script import "/tmp/202B3703-04D7-41D3-8240-B28CFBC6E199/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/C,ontainers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliT,est.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/BBC0FCAD-90B2-4FC8-B867-0C8FAB239E3D/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,Process 247 stopped
* thread #1: tid = 0xb0cc, 0x1fe0908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x1fe0908c dyld`dyld_fatal_error
dyld`dyld_fatal_error:
->  0x1fe0908c <+0>: trap   
    0x1fe09090 <+4>: nop    

dyld`gdb_image_notifier:
    0x1fe09094 <+0>: bx     lr

dyld`dyldbootstrap::start:
    0x1fe09098 <+0>: push   {r4, r5, r6, r7, lr}
,* thread #1: tid = 0xb0cc, 0x1fe0908c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fe0908c dyld`dyld_fatal_error
    frame #1: 0x1fe0b99a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fe0deaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fe091ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fe09040 dyld`_dyld_start + 64

```
