#### Test 575312430087a60_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/93C9A76C-F0DA-4C71-972C-9B52614DFFC6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/93C9A76C-F0DA-4C71-972C-9B52614DFFC6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63271"
,(lldb)     command script import "/tmp/93C9A76C-F0DA-4C71-972C-9B52614DFFC6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 19:24:35.295 ThaliTest[790:1316338] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78ED7357-C4AD-4BC5-BE53-899B0F97E983/Library/Cookies/Cookies.binarycookies
,2016-01-29 19:24:35.665 ThaliTest[790:1316338] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 19:24:35.667 ThaliTest[790:1316338] Multi-tasking -> Device: YES, App: YES
,2016-01-29 19:24:35.676 ThaliTest[790:1316338] Unlimited access to network resources
,2016-01-29 19:24:35.686 ThaliTest[790:1316338] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 19:24:45.032 ThaliTest[790:1316338] Resetting plugins due to page load.
,2016-01-29 19:24:48.363 ThaliTest[790:1316338] Finished load of: file:///var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/index.html
,2016-01-29 19:24:48.548 ThaliTest[790:1316338] JXcore Cordova plugin initializing
,2016-01-29 19:24:48.650 ThaliTest[790:1316640] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/107519B1-7134-4551-88F6-9563DEF1E1D3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-01-29 19:29:07.132 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements
,2016-01-29 19:29:07.135 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:07.137 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:07.138 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-01-29 19:29:07.190 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:07.191 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:29:07.193 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:07.193 ThaliTest[790:1316640] THEMultipeerManager stopping peer
2016-01-29 19:29:07.194 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: succes,s
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-01-29 19:29:07.464 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements
2016-01-29 19:29:07.465 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:07.467 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements
2016-01-29 19:29:07.468 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-01-29 19:29:08.744 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:08.745 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown
,
,2016-01-29 19:29:08.746 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
,2016-01-29 19:29:08.750 ThaliTest[790:1316640] THEMultipeerManager stopping peer
2016-01-29 19:29:08.751 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-01-29 19:29:09.565 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:09.566 ThaliTest[790:1316640] server: starting 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:1
2016-01-29 19:29:09.566 ThaliTest[790:1316640] THEMultipeerMa,nager initialized peer 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:1
2016-01-29 19:29:09.567 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:29:09.570 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:09.570 ThaliTest[790:1316640] THEMultipeerManager stopping peer
2016-01-29 19:29:09.571 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-01-29 19:29:09.646 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:09.647 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:29:09.648 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:09.649 ThaliTest[790:1316640] THEMultipeerManager stopping peer
2016-01-29 19:29:09.649 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-01-29 19:29:15.409 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:15.409 ThaliTest[790:1316640] server: starting 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:2
2016-01-29 19:29:15.410 ThaliTest[790:1316640] THEMultipeerMa,nager initialized peer 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:2
2016-01-29 19:29:15.410 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:29:15.412 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening
,2016-01-29 19:29:15.413 ThaliTest[790:1316640] THEMultipeerManager stopping peer
,2016-01-29 19:29:15.414 ThaliTest[790:1316640] server: starting 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:3
2016-01-29 19:29:15.415 ThaliTest[790:1316640] THEMultipeerManager initialized peer 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:3
2016-01-29 19:29:15.420 Thal,iTest[790:1316640] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-01-29 19:29:15.856 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:15.857 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown
,
,2016-01-29 19:29:15.859 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:15.859 ThaliTest[790:1316640] THEMultipeerManager stopping peer
2016-01-29 19:29:15.860 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-01-29 19:29:16.229 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:16.229 ThaliTest[790:1316640] server: starting 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:4
2016-01-29 19:29:16.230 ThaliTest[790:1316640] THEMultipeerMa,nager initialized peer 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:4
2016-01-29 19:29:16.230 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-01-29 19:29:16.234 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements
2016-01-29 19:29:16.235 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:20.649 ThaliTest[790:1316338] client: found peer: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-01-29 19:29:20.868 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:20.869 ThaliTest[790:1316640] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown
,
,2016-01-29 19:29:20.871 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening
,2016-01-29 19:29:20.871 ThaliTest[790:1316640] THEMultipeerManager stopping peer
,2016-01-29 19:29:20.873 ThaliTest[790:1316640] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-01-29 19:29:23.529 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:23.530 ThaliTest[790:1316640] server: starting 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:29:23.531 ThaliTest[790:1316640] THEMultipeerMa,nager initialized peer 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:29:23.532 ThaliTest[790:1316640] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

2016-01-29 19:29:23.533 Th,aliTest[790:1316640] jxcore: startListeningForAdvertisements
2016-01-29 19:29:23.534 ThaliTest[790:1316640] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:25.868 ThaliTest[790:1316338] client: found peer: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:29:25.870 ThaliTest[790:1316640] jxcore: connect 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
,2016-01-29 19:29:25.871 ThaliTest[790:1316640] client: server will connect
2016-01-29 19:29:25.872 ThaliTest[790:1316640] client session: reverseConnect
2016-01-29 19:29:25.872 ThaliTest[790:1316640] client session: stateChange:0->1 4AD9B88D-FF95-42F6-B2,A5-BCD6B24CE242:5
,2016-01-29 19:29:26.022 ThaliTest[790:1316338] server session: connect
2016-01-29 19:29:26.023 ThaliTest[790:1316338] server session: stateChange:0->1 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
,2016-01-29 19:29:26.033 ThaliTest[790:1316338] server: accepting invitation 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
,2016-01-29 19:29:26.079 ThaliTest[790:1317061] client session: not connected 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:29:26.079 ThaliTest[790:1317061] client session: onLinkFailure: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:29:26.085, ThaliTest[790:1317061] client session: disconnect
2016-01-29 19:29:26.086 ThaliTest[790:1317061] client session: stateChange:1->0 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:29:26.087 ThaliTest[790:1317061] client session: no connect callabck (server initiated)
,2016-01-29 19:29:28.648 ThaliTest[790:1317061] server session: connected
2016-01-29 19:29:28.649 ThaliTest[790:1317061] server session: stateChange:1->2 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
,2016-01-29 19:29:28.655 ThaliTest[790:1316338] server relay: socket disconnected
2016-01-29 19:29:28.656 ThaliTest[790:1316338] server relay: 0x187506e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-01-29 19:33:24.494 ThaliTest[790:1317337] server session: not connected 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
,appEnteredForeground wasn't registered

,2016-01-29 19:33:32.657 ThaliTest[790:1316338] client: lost peer: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:33:32.658 ThaliTest[790:1316338] client session: onPeerLost: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
,appEnteringBackground wasn't registered

,2016-01-29 19:33:54.274 ThaliTest[790:1316640] jxcore: connect 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:33:54.274 ThaliTest[790:1316640] client: connect: unreachable 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:33:54.274 ThaliTest[790:1,316640] jxcore: connect: fail: Peer unreachable
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,2016-01-29 19:40:55.957 ThaliTest[790:1316338] client: lost peer: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:40:55.957 ThaliTest[790:1316338] client session: onPeerLost: 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
,2016-01-29 19:41:16.576 ThaliTest[790:1316640] jxcore: connect 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:41:16.577 ThaliTest[790:1316640] client: connect: unreachable 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242
2016-01-29 19:41:16.577 ThaliTest[790:1,316640] jxcore: connect: fail: Peer unreachable

```
