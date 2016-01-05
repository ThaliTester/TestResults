#### Test 54970261fc259e9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AC879CCF-EDAE-4A39-B572-A02ED32BF22A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC879CCF-EDAE-4A39-B572-A02ED32BF22A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54970261fc259e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/486EE245-0ED2-4437-81B6-AE40CA39B793/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65180"
,(lldb)     command script import "/tmp/AC879CCF-EDAE-4A39-B572-A02ED32BF22A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 17:24:40.353 ThaliTest[1307:2790789] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/680BBD36-9D93-48BB-8A74-B3ECCE96EF38/Library/Cookies/Cookies.binarycookies
,2016-01-05 17:24:40.801 ThaliTest[1307:2790789] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 17:24:40.803 ThaliTest[1307:2790789] Multi-tasking -> Device: YES, App: YES
,2016-01-05 17:24:40.813 ThaliTest[1307:2790789] Unlimited access to network resources
,2016-01-05 17:24:40.829 ThaliTest[1307:2790789] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 17:24:50.371 ThaliTest[1307:2790789] Resetting plugins due to page load.
,2016-01-05 17:24:54.093 ThaliTest[1307:2790789] Finished load of: file:///var/mobile/Containers/Bundle/Application/486EE245-0ED2-4437-81B6-AE40CA39B793/ThaliTest.app/www/index.html
,2016-01-05 17:24:54.371 ThaliTest[1307:2790789] JXcore Cordova plugin initializing
,2016-01-05 17:24:54.372 ThaliTest[1307:2791015] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,TAP version 13
,# setup
,# multiplex can send data
,# teardown
,ok 1 String should be length:200
,# setup
,# basic
,# teardown
,ok 2 sane
,# setup
,# another
,# teardown
,ok 3 sane
,# setup
,# successfully create a new pkcs12 file and return hash value
,# teardown
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
,# setup
,# successfully read a previous pkcs12 file and return hash value
,# teardown
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
,# failed to extract public key because of corrupt pkcs12 file
,# teardown
,ok 14 should be equal
,# setup
,# failed to get mobile documents path
,# teardown
,ok 15 should be equal
,# setup
,# #init should register the peerAvailabilityChanged event
,# teardown
,ok 16 should be equal
,ok 17 should be equal
,ok 18 should be equal
,# setup
,# #init should register the networkChanged event
,# teardown
,ok 19 should be equal
,# setup
,# #startBroadcasting should throw on null device name
,# teardown
,ok 20 should throw
,# setup
,# #startBroadcasting should throw on empty string device name
,# teardown
,ok 21 should throw
,# setup
,# #startBroadcasting should throw on non-number port
,# teardown
,ok 22 should throw
# setup
,# #startBroadcasting should throw on NaN port
,# teardown
,ok 23 should throw
,# setup
,# #startBroadcasting should throw on negative port
,# teardown
,ok 24 should throw
,# setup
,# #startBroadcasting should throw on too large port
,# teardown
,ok 25 should throw
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,ok 26 should be equal
,ok 27 should be equal
,ok 28 should be equal
,# setup
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,ok 32 should be equal
,ok 33 should be equal
,# setup
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,ok 34 should be equal
,ok 35 should be equal
,# setup
,# #connect should call Mobile("Connect") with a port and without an error
,# teardown
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,# #connect should call Mobile("Connect") and handle an error
,# teardown
,ok 39 should be equal
,ok 40 should be equal
,# setup
,# should call Mobile("Disconnect") without an error
,# teardown
,ok 41 should be equal
,ok 42 should be equal
,# setup
,# should call Mobile("Disconnect") and handle an error
,# teardown
,ok 43 should be equal
,ok 44 should be equal
,# setup
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,2016-01-05 17:30:11.523 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.541 ThaliTest[1307:2791015] server: starting 1452011411523.1307.0dnjqA==
,2016-01-05 17:30:11.542 ThaliTest[1307:2791015] multipeer session: start timer: 0x180f6b20
,2016-01-05 17:30:11.544 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411523.1307
2016-01-05 17:30:11.546 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2016-,01-05 17:30:11.549 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.549 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.549 ThaliTest[1307:2791015] multipeer session: stop timer
2016-01-05 17:30:11.550 T,haliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.552 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.580 ThaliTest[1307:2791015] server: starting 1452011411552.1307.oE5EtQ==
,2016-01-05 17:30:11.584 ThaliTest[1307:2791015] multipeer session: start timer: 0x180faf00
,2016-01-05 17:30:11.591 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411552.1307
,2016-01-05 17:30:11.594 ThaliTest[1307:2790789] client: found peer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 17:30:11.594 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.597 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.598 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.598 ThaliTest[1307:2791015] multipeer session: stop timer
2016-01-05 17:30:11.,599 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.602 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.606 ThaliTest[1307:2791015] server: starting 1452011411601.1307.T87vLQ==
2016-01-05 17:30:11.607 ThaliTest[1307:2791015] multipeer session: start timer: 0x181b4270
2016-01-05 17:30:11.607 ThaliTest[1307:2791015] THEMultipeerSession in,itialized peer 1452011411601.1307
2016-01-05 17:30:11.608 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.610 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.611 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.612 ThaliTest[1307:2791015] multipeer session: stop timer
,2016-01-05 17:30:11.613 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.615 ThaliTest[1307:2791015] jxcore: startBroadcasting
2016-01-05 17:30:11.619 ThaliTest[1307:2791015] server: starting 1452011411615.1307.F0Isbw==
2016-01-05 17:30:11.619 Th,aliTest[1307:2791015] multipeer session: start timer: 0x181b5850
2016-01-05 17:30:11.620 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411615.1307
2016-01-05 17:30:11.620 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.623 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.623 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.624 ThaliTest[130,7:2791015] multipeer session: stop timer
2016-01-05 17:30:11.624 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.626 ThaliTest[1307:2791015] jxcore: startBroadcast,ing
,2016-01-05 17:30:11.630 ThaliTest[1307:2791015] server: starting 1452011411626.1307.vBpDiQ==
2016-01-05 17:30:11.630 ThaliTest[1307:2791015] multipeer session: start timer: 0x181b6330
,2016-01-05 17:30:11.632 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411626.1307
,2016-01-05 17:30:11.633 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.635 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.635 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.636 ThaliTest[130,7:2791015] multipeer session: stop timer
2016-01-05 17:30:11.636 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.637 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.641 ThaliTest[1307:2791015] server: starting 1452011411637.1307.rYY3vA==
2016-01-05 17:30:11.641 ThaliTest[1307:2791015] multipeer session: start timer: 0x181b8590
2016-01-05 17:30:11.642 ThaliTest[1307:2791015] THEMultipeerSession in,itialized peer 1452011411637.1307
2016-01-05 17:30:11.642 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.643 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2,016-01-05 17:30:11.644 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.644 ThaliTest[1307:2791015] multipeer session: stop timer
2016-01-05 17:30:11.644 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.646 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.654 ThaliTest[1307:2791015] server: starting 1452011411645.1307.zAwFfw==
2016-01-05 17:30:11.655 ThaliTest[1307:2791015] multipeer session: start timer: 0x180f88d0
2016-01-05 17:30:11.655 ThaliTest[1307:2791015] THEMultipeerSession in,itialized peer 1452011411645.1307
2016-01-05 17:30:11.655 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.657 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.657 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:11.657 ThaliTest[1307:2791015] multipeer session: stop timer
,2016-01-05 17:30:11.658 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.660 ThaliTest[1307:2791015] jxcore: startBroadcasting
2016-01-05 17:30:11.664 ThaliTest[1307:2791015] server: starting 1452011411659.1307.y6dw6w==
,2016-01-05 17:30:11.666 ThaliTest[1307:2791015] multipeer session: start timer: 0x180761b0
2016-01-05 17:30:11.666 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411659.1307
2016-01-05 17:30:11.666 ThaliTest[1307:2791015] jxcore: sta,rtBroadcasting: success
ok 59 Should be able to call startBroadcasting without error
2016-01-05 17:30:11.668 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.668 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.670 ThaliTest[1307:2791015] multipeer session: stop timer
,2016-01-05 17:30:11.671 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2016-01-05 17:30:11.673 ThaliTest[1307:2791015] jxcore: startBroadcasting
2016-01-05 17:30:11.676 ThaliTest[130,7:2791015] server: starting 1452011411672.1307.daOKaw==
2016-01-05 17:30:11.676 ThaliTest[1307:2791015] multipeer session: start timer: 0x18075220
,2016-01-05 17:30:11.678 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411672.1307
2016-01-05 17:30:11.681 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2016-,01-05 17:30:11.684 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:11.684 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.685 ThaliTest[1307:2791015] multipeer session: stop timer
,2016-01-05 17:30:11.690 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2016-01-05 17:30:11.694 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:11.703 ThaliTest[1307:2791015] server: starting 1452011411693.1307.03ehPg==
,2016-01-05 17:30:11.705 ThaliTest[1307:2791015] multipeer session: start timer: 0x181ba8b0
,2016-01-05 17:30:11.705 ThaliTest[1307:2791015] THEMultipeerSession initialized peer 1452011411693.1307
,2016-01-05 17:30:11.710 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2016-01-05 17:30:11.735 ThaliTest[1307:2791015] jxcore: stopBroadcasting
,2016-01-05 17:30:11.737 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
,2016-01-05 17:30:11.738 ThaliTest[1307:2791015] multipeer session: stop timer
,2016-01-05 17:30:11.740 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter calls startBroadcasting twice with error
,# teardown
,2016-01-05 17:30:12.472 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:12.476 ThaliTest[1307:2791015] server: starting 1452011412471.1307.QglTFw==
2016-01-05 17:30:12.476 ThaliTest[1307:2791015] multipeer session: start timer: 0x181b8840
2016-01-05 17:30:12.477 ThaliTest[1307:2791015] THEMultipeerSession in,itialized peer 1452011412471.1307
2016-01-05 17:30:12.477 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2016-01-05 17:30:12.480 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:12.481 ThaliTest[1307:2791015] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2016-01-05 17:30:12.484 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:12.484 ThaliTest[1307:2791015] THEMult,ipeerSession stopping peer
2016-01-05 17:30:12.484 ThaliTest[1307:2791015] multipeer session: stop timer
2016-01-05 17:30:12.485 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,# ThaliEmitter throws on connection to bad peer
,# teardown
,2016-01-05 17:30:13.507 ThaliTest[1307:2791015] jxcore: startBroadcasting
,2016-01-05 17:30:13.511 ThaliTest[1307:2791015] server: starting 1452011413507.1307.1S8xfg==
2016-01-05 17:30:13.512 ThaliTest[1307:2791015] multipeer session: start timer: 0x181be700
2016-01-05 17:30:13.512 ThaliTest[1307:2791015] THEMultipeerSession in,itialized peer 1452011413507.1307
2016-01-05 17:30:13.513 ThaliTest[1307:2791015] jxcore: startBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
2016-01-05 17:30:13.516 ThaliTest[1307:2791015] jxcore: connect foobar
201,6-01-05 17:30:13.516 ThaliTest[1307:2791015] client: unknown peer foobar
2016-01-05 17:30:13.517 ThaliTest[1307:2791015] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2016-01-05 17:30:13.521 ThaliTest[1307:2791015] jxcore: stopBroadcasting
2016-01-05 17:30:13.521 ThaliTest[1307:2791015] THEMultipeerSession stopping peer
2016-01-05 17:30:13.521 ThaliTest[1307:2791015] multipeer s,ession: stop timer
2016-01-05 17:30:13.522 ThaliTest[1307:2791015] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,Process 1307 stopped
* thread #20: tid = 0x2a985a, 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x5000000c)
    frame #0: 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6
libobjc.A.dylib`objc_msgSend:
->  0x33e93ae6 <+6>:  ldrh.w r12, [r9, #0xc]
    0x33e93aea <+10>: ldr.w  r9, [r9, #0x8]
    0x33e93aee <+14>: and.w  r12, r12, r1
    0x33e93af2 <+18>: add.w  r9, r9, r12, lsl #3
,* thread #20: tid = 0x2a985a, 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6, queue = 'com.apple.MCNearbyServiceBrowser.syncQueue', stop reason = EXC_BAD_ACCESS (code=1, address=0x5000000c)
  * frame #0: 0x33e93ae6 libobjc.A.dylib`objc_msgSend + 6
    frame #1: 0x24a76538 MultipeerConnectivity`<redacted> + 52
    frame #2: 0x345abe2e libdispatch.dylib`<redacted> + 10
    frame #3: 0x345b5fee libdispatch.dylib`<redacted> + 1762
    frame #4: 0x345aef86 libdispatch.dylib`<redacted> + 282
    frame #5: 0x345b737c libdispatch.dylib`<redacted> + 400
    frame #6: 0x345b71ea libdispatch.dylib`<redacted> + 94
    frame #7: 0x34740e0c libsystem_pthread.dylib`_pthread_wqthread + 1024
    frame #8: 0x347409fc libsystem_pthread.dylib`start_wqthread + 8

```
