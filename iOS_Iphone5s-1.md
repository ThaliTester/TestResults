#### Test 50650278c5de1fe_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B0F73E09-0212-4F3E-A167-45633C5CD986/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B0F73E09-0212-4F3E-A167-45633C5CD986/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/85BEACD3-0798-40D1-B933-3FD4996A712D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60953"
,(lldb)     command script import "/tmp/B0F73E09-0212-4F3E-A167-45633C5CD986/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 19:24:46.020 ThaliTest[2533:2332762] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4839FE08-EBAB-4F8A-A539-CA5F38996393/Library/Cookies/Cookies.binarycookies
,2015-12-03 19:24:46.446 ThaliTest[2533:2332762] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 19:24:46.447 ThaliTest[2533:2332762] Multi-tasking -> Device: YES, App: YES
,2015-12-03 19:24:46.456 ThaliTest[2533:2332762] Unlimited access to network resources
,2015-12-03 19:24:46.464 ThaliTest[2533:2332762] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 19:24:50.269 ThaliTest[2533:2332762] Resetting plugins due to page load.
,2015-12-03 19:24:50.739 ThaliTest[2533:2332762] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/85BEACD3-0798-40D1-B933-3FD4996A712D/ThaliTest.app/www/index.html
,2015-12-03 19:24:50.898 ThaliTest[2533:2332762] JXcore Cordova plugin initializing
2015-12-03 19:24:50.899 ThaliTest[2533:2332876] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to ,bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter handles socket dis,connect correctly","ThaliReplicationManager can call start without error","ThaliReplicationManager receives identity","ThaliReplicationManager replicates database"]
,TAP version 13
,# setup
,# multiplex can send data
,CoordinatorConnector-debug: setup:multiplex can send data
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:multiplex can send data
,ok 1 String should be length:200
,# setup
,CoordinatorConnector-debug: teardown:multiplex can send data
,running teardown
,# basic
,CoordinatorConnector-debug: setup:basic
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:basic
,ok 2 sane
,# setup
,CoordinatorConnector-debug: teardown:basic
,running teardown
,# another
,CoordinatorConnector-debug: setup:another
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:another
,ok 3 sane
,# setup
,CoordinatorConnector-debug: teardown:another
,running teardown
,# successfully create a new pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully create a new pkcs12 file and return hash value
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:successfully create a new pkcs12 file and return hash value
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
running teardown
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:successfully read a previous pkcs12 file and return hash value
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
,CoordinatorConnector-debug: teardown:successfully read a previous pkcs12 file and return hash value
running teardown
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
,running teardown
,# failed to get mobile documents path
,CoordinatorConnector-debug: setup:failed to get mobile documents path
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
,running teardown
,# #init should register the peerAvailabilityChanged event
,CoordinatorConnector-debug: setup:#init should register the peerAvailabilityChanged event
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#init should register the peerAvailabilityChanged event
,ok 16 should be equal
,ok 17 should be equal
,ok 18 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the peerAvailabilityChanged event
running teardown
,# #init should register the networkChanged event
,CoordinatorConnector-debug: setup:#init should register the networkChanged event
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#init should register the networkChanged event
,ok 19 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the networkChanged event
,running teardown
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
,running teardown
,# #startBroadcasting should throw on empty string device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on empty string device name
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on empty string device name
,ok 21 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on empty string device name
running teardown
,# #startBroadcasting should throw on non-number port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on non-number port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on non-number port
,ok 22 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on non-number port
,running teardown
,# #startBroadcasting should throw on NaN port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on NaN port
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on NaN port
,ok 23 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on NaN port
running teardown
,# #startBroadcasting should throw on negative port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on negative port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on negative port
,ok 24 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on negative port
,running teardown
,# #startBroadcasting should throw on too large port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on too large port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on too large port
,ok 25 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on too large port
,running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,ok 26 should be equal
,ok 27 should be equal
,ok 28 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,running teardown
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,ok 32 should be equal
,ok 33 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,running teardown
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,ok 34 should be equal
,ok 35 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,running teardown
,# #connect should call Mobile("Connect") with a port and without an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") with a port and without an error
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") with a port and without an error
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") with a port and without an error
,running teardown
,# #connect should call Mobile("Connect") and handle an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") and handle an error
,ok 39 should be equal
,ok 40 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") and handle an error
,running teardown
,# should call Mobile("Disconnect") without an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") without an error
,ok 41 should be equal
,ok 42 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") without an error
,running teardown
,# should call Mobile("Disconnect") and handle an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") and handle an error
,ok 43 should be equal
,ok 44 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") and handle an error
,running teardown
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,CoordinatorConnector-debug: setup:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,2015-12-03 19:26:16.700 ThaliTest[2533:2332876] jxcore: startBroadcasting
,2015-12-03 19:26:16.886 ThaliTest[2533:2332876] server: starting 1449167176699.2533.yf8P3w==
,2015-12-03 19:26:16.887 ThaliTest[2533:2332876] multipeer session: start timer: 0x19f86900
,2015-12-03 19:26:16.896 ThaliTest[2533:2332876] THEMultipeerSession initialized peer 1449167176699.2533
2015-12-03 19:26:16.902 ThaliTest[2533:2332876] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-03 19:26:16.908 ThaliTest[2533:2332876] jxcore: stopBroadcasting
,2015-12-03 19:26:16.909 ThaliTest[2533:2332876] THEMultipeerSession stopping peer
,2015-12-03 19:26:16.910 ThaliTest[2533:2332876] multipeer session: stop timer
2015-12-03 19:26:16.916 ThaliTest[2533:2332876] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.922 ThaliTest[2533:2332876] jxcore: startBroadcasting
,2015-12-03 19:26:16.925 ThaliTest[2533:2332876] server: starting 1449167176921.2533.O2hi1g==
,2015-12-03 19:26:16.930 ThaliTest[2533:2332876] multipeer session: start timer: 0x1b85aca0
,2015-12-03 19:26:16.937 ThaliTest[2533:2332876] THEMultipeerSession initialized peer 1449167176921.2533
,2015-12-03 19:26:16.938 ThaliTest[2533:2332876] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2015-12-03 19:26:16.942 ThaliTest[2533:2332876] jxcore: stopBroadcasting
,2015-12-03 19:26:16.943 ThaliTest[2533:2332876] THEMultipeerSession stopping peer
,2015-12-03 19:26:16.944 ThaliTest[2533:2332876] multipeer session: stop timer
,2015-12-03 19:26:16.949 ThaliTest[2533:2332876] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.955 ThaliTest[2533:2332876] jxcore: startBroadcasting
,2015-12-03 19:26:16.957 ThaliTest[2533:2332876] server: starting 1449167176954.2533.DeLa/A==
,2015-12-03 19:26:16.961 ThaliTest[2533:2332876] multipeer session: start timer: 0x19f894a0
,2015-12-03 19:26:16.966 ThaliTest[2533:2332876] THEMultipeerSession initialized peer 1449167176954.2533
,2015-12-03 19:26:16.967 ThaliTest[2533:2332876] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-03 19:26:16.972 ThaliTest[2533:2332876] jxcore: stopBroadcasting
,2015-12-03 19:26:16.973 ThaliTest[2533:2332876] THEMultipeerSession stopping peer
,2015-12-03 19:26:16.974 ThaliTest[2533:2332876] multipeer session: stop timer
,2015-12-03 19:26:16.978 ThaliTest[2533:2332876] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.982 ThaliTest[2533:2332876] jxcore: startBroadcasting
,2015-12-03 19:26:16.985 ThaliTest[2533:2332876] server: starting 1449167176982.2533.271SaA==
,2015-12-03 19:26:16.987 ThaliTest[2533:2332876] multipeer session: start timer: 0x1b85bc10
,2015-12-03 19:26:16.991 ThaliTest[2533:2332876] THEMultipeerSession initialized peer 1449167176982.2533
,2015-12-03 19:26:16.992 ThaliTest[2533:2332876] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-03 19:26:16.994 ThaliTest[2533:2332876] jxcore: stopBroadcasting
,2015-12-03 19:26:16.995 ThaliTest[2533:2332876] THEMultipeerSession stopping peer
,2015-12-03 19:26:16.996 ThaliTest[2533:2332876] multipeer session: stop timer
,2015-12-03 19:26:16.998 ThaliTest[2533:2332876] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:17.001 ThaliTest[2533:2332876] jxcore: startBroadcasting
,2015-12-03 19:26:17.003 ThaliTest[2533:2332876] server: starting 1449167177001.2533.m1BgvQ==
,2015-12-03 19:26:17.007 ThaliTest[2533:2332876] multipeer session: start timer: 0x1b85cf30
,2015-12-03 19:26:17.011 ThaliTest[2533:2332876] THEMultipeerSession initialized peer 1449167177001.2533
,2015-12-03 19:26:17.012 ThaliTest[2533:2332876] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 19:26:17.024 ThaliTest[2533:2332876] jxcore: stopBroadcasting
,2015-12-03 19:26:17.025 ThaliTest[2533:2332876] THEMultipeerSession stopping peer
,2015-12-03 19:26:17.026 ThaliTest[2533:2332876] multipeer session: stop timer
,Process 2533 stopped
* thread #1: tid = 0x23985a, 0x38776f42 libobjc.A.dylib`objc_msgSend + 2, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x2)
    frame #0: 0x38776f42 libobjc.A.dylib`objc_msgSend + 2
libobjc.A.dylib`objc_msgSend:
->  0x38776f42 <+2>:  ldr.w  r9, [r0]
    0x38776f46 <+6>:  ldrh.w r12, [r9, #0xc]
    0x38776f4a <+10>: ldr.w  r9, [r9, #0x8]
    0x38776f4e <+14>: and.w  r12, r12, r1
,* thread #1: tid = 0x23985a, 0x38776f42 libobjc.A.dylib`objc_msgSend + 2, queue = 'com.apple.main-thread', stop reason = EXC_BAD_ACCESS (code=1, address=0x2)
  * frame #0: 0x38776f42 libobjc.A.dylib`objc_msgSend + 2
    frame #1: 0x2a3c4150 CFNetwork`<redacted> + 96
    frame #2: 0x2a3c3b10 CFNetwork`<redacted> + 36
    frame #3: 0x2a33d692 CFNetwork`<redacted> + 90
    frame #4: 0x2a86dfbe CoreFoundation`<redacted> + 14
    frame #5: 0x2a86d3ce CoreFoundation`<redacted> + 218
    frame #6: 0x2a86ba34 CoreFoundation`<redacted> + 772
    frame #7: 0x2a7b93b0 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #8: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #9: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #10: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #11: 0x0003d5e2 ThaliTest`main + 50

```
