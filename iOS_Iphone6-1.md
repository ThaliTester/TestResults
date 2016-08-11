#### Test 797638305bc0289_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FF443713-4698-4DD0-8395-FCE76583B7A1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FF443713-4698-4DD0-8395-FCE76583B7A1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638305bc0289/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58864"
,(lldb)     command script import "/tmp/FF443713-4698-4DD0-8395-FCE76583B7A1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,dyld: Library not loaded: @rpath/ThaliCore.framework/ThaliCore
  Referenced from: /var/mobile/Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliTest.app/ThaliTest
  Reason: no suitable image found.  Did find:
	/private/var/mobile/Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliT,est.app/Frameworks/ThaliCore.framework/ThaliCore'
	/private/var/mobile/Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore: mmap() errno=1 validating first page of '/private/var/mobile/,Containers/Bundle/Application/05DCBB2F-64E7-498F-BC04-535C4404A0AD/ThaliTest.app/Frameworks/ThaliCore.framework/ThaliCore'
,Process 1545 stopped
* thread #1: tid = 0x3fa5e7, 0x1fedd08c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
    frame #0: 0x1fedd08c dyld`dyld_fatal_error
dyld`dyld_fatal_error:
->  0x1fedd08c <+0>: trap   
    0x1fedd090 <+4>: nop    

dyld`gdb_image_notifier:
    0x1fedd094 <+0>: bx     lr

dyld`dyldbootstrap::start:
    0x1fedd098 <+0>: push   {r4, r5, r6, r7, lr}
,* thread #1: tid = 0x3fa5e7, 0x1fedd08c dyld`dyld_fatal_error, stop reason = EXC_BREAKPOINT (code=EXC_ARM_BREAKPOINT, subcode=0xe7ffdefe)
  * frame #0: 0x1fedd08c dyld`dyld_fatal_error
    frame #1: 0x1fedf99a dyld`dyld::halt(char const*) + 74
    frame #2: 0x1fee1eaa dyld`dyld::_main(macho_header const*, unsigned long, int, char const**, char const**, char const**, unsigned long*) + 4298
    frame #3: 0x1fedd1ee dyld`dyldbootstrap::start(macho_header const*, int, char const**, long, macho_header const*, unsigned long*) + 342
    frame #4: 0x1fedd040 dyld`_dyld_start + 64

```
