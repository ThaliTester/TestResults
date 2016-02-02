#### Test 575312431be71d2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5DF5943D-E795-4805-A843-236590074980/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5DF5943D-E795-4805-A843-236590074980/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64350"
,(lldb)     command script import "/tmp/5DF5943D-E795-4805-A843-236590074980/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 14:15:19.125 ThaliTest[2336:7455622] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75855F69-D77F-4926-810E-DF56F170C451/Library/Cookies/Cookies.binarycookies
,2016-02-02 14:15:19.244 ThaliTest[2336:7455622] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 14:15:19.246 ThaliTest[2336:7455622] Multi-tasking -> Device: YES, App: YES
,2016-02-02 14:15:19.251 ThaliTest[2336:7455622] Unlimited access to network resources
,2016-02-02 14:15:19.264 ThaliTest[2336:7455622] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 14:15:25.797 ThaliTest[2336:7455622] Resetting plugins due to page load.
,2016-02-02 14:15:28.054 ThaliTest[2336:7455622] Finished load of: file:///var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/index.html
,2016-02-02 14:15:28.249 ThaliTest[2336:7455622] JXcore Cordova plugin initializing
,2016-02-02 14:15:28.376 ThaliTest[2336:7455854] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/507F077E-9851-4D86-A61E-3B20D0EEC0F5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 3 firstPromise result

ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

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

,2016-02-02 14:21:13.370 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements
,2016-02-02 14:21:13.372 ThaliTest[2336:7455854] multipeer manager: start client restart timer: 0x15dbc110
,2016-02-02 14:21:13.372 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:13.379 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
,2016-02-02 14:21:13.382 ThaliTest[2336:7455854] multipeer manager: stop client timer
,2016-02-02 14:21:13.382 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 14:21:13.403 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
,2016-02-02 14:21:13.404 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:13.407 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:13.408 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
,2016-02-02 14:21:13.409 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 14:21:14.193 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements
2016-02-02 14:21:14.193 ThaliTest[2336:7455854] multipeer manager: start client restart timer: 0x15dbc110
2016-02-02 14:21:14.193 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

2016-02-02 14:21:14.194 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements
2016-02-02 14:21:14.194 ThaliTest[2336:7455854] jxcore: startList,eningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

# setup

,2016-02-02 14:21:14.234 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:14.235 ThaliTest[2336:7455854] multipeer manager: stop client timer
2016-02-02 14:21:14.235 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisem,ents: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-02 14:21:14.236 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:14.236 ThaliTest[2336:7455854] THEMultipeerManager stopping peer,
2016-02-02 14:21:14.236 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 14:21:14.358 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:14.358 ThaliTest[2336:7455854] server: starting AC42391D-3B67-44B2-83EF-6199949E75E1:1
2016-02-02 14:21:14.358 ThaliTest[2336:7455854] multipeer m,anager: start client restart timer: 0x15dbc110
2016-02-02 14:21:14.359 ThaliTest[2336:7455854] THEMultipeerManager initialized peer AC42391D-3B67-44B2-83EF-6199949E75E1:1
2016-02-02 14:21:14.359 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 14:21:14.360 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:14.360 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
,2016-02-02 14:21:14.360 ThaliTest[2336:7455854] multipeer manager: stop client timer
2016-02-02 14:21:14.367 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

# setup

,2016-02-02 14:21:17.508 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:17.508 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 14:21:17.509 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:17.509 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
2016-02-02 14:21:17.510 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 14:21:20.845 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:20.845 ThaliTest[2336:7455854] server: starting AC42391D-3B67-44B2-83EF-6199949E75E1:2
2016-02-02 14:21:20.845 ThaliTest[2336:7455854] multipeer m,anager: start client restart timer: 0x15dbc110
2016-02-02 14:21:20.846 ThaliTest[2336:7455854] THEMultipeerManager initialized peer AC42391D-3B67-44B2-83EF-6199949E75E1:2
2016-02-02 14:21:20.846 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-02 14:21:20.847 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:20.847 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
,2016-02-02 14:21:20.847 ThaliTest[2336:7455854] multipeer manager: stop client timer
2016-02-02 14:21:20.854 ThaliTest[2336:7455854] server: starting AC42391D-3B67-44B2-83EF-6199949E75E1:3
2016-02-02 14:21:20.854 ThaliTest[2336:7455854] multipeer manager: start client restart timer: 0x15dbc110
2016-02-02 14:21:20.855 ThaliTest[2336:7455854] THEMultipeerManager initialized peer AC42391D-3B67-44B2-83EF-6199949E75E1:3
,2016-02-02 14:21:20.855 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-02-02 14:21:20.928 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:20.929 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 14:21:20.929 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:20.930 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
2016-02-02 14:21:20.930 ThaliTest[2336:7455854] multipeer manager: stop client timer,
2016-02-02 14:21:20.930 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

# peerAvailabilityChange is called

,# teardown

,2016-02-02 14:21:21.104 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:21.105 ThaliTest[2336:7455854] server: starting AC42391D-3B67-44B2-83EF-6199949E75E1:4
2016-02-02 14:21:21.105 ThaliTest[2336:7455854] multipeer m,anager: start client restart timer: 0x15dbc110
2016-02-02 14:21:21.106 ThaliTest[2336:7455854] THEMultipeerManager initialized peer AC42391D-3B67-44B2-83EF-6199949E75E1:4
2016-02-02 14:21:21.106 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-02 14:21:21.107 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements
2016-02-02 14:21:21.107 ThaliTest[2336:7455854] multipeer manager: stop client time,r
2016-02-02 14:21:21.107 ThaliTest[2336:7455854] multipeer manager: start client restart timer: 0x15dbc110
2016-02-02 14:21:21.108 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:28.092 ThaliTest[2336:7455622] client: found new peer: B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
ok 32 peers must be an array

ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a str,ing

ok 36 peer must have peerAvailable

ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 14:21:29.427 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:29.427 ThaliTest[2336:7455854] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

2016-02-02 14:21:29.428 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:29.428 ThaliTest[2336:7455854] THEMultipeerManager stopping peer
2016-02-02 14:21:29.428 ThaliTest[2336:7455854] multipeer manager: stop client timer,
2016-02-02 14:21:29.428 ThaliTest[2336:7455854] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,# teardown

,2016-02-02 14:21:30.775 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:30.775 ThaliTest[2336:7455854] server: starting AC42391D-3B67-44B2-83EF-6199949E75E1:5
2016-02-02 14:21:30.776 ThaliTest[2336:7455854] multipeer m,anager: start client restart timer: 0x15dbc110
2016-02-02 14:21:30.776 ThaliTest[2336:7455854] THEMultipeerManager initialized peer AC42391D-3B67-44B2-83EF-6199949E75E1:5
2016-02-02 14:21:30.776 ThaliTest[2336:7455854] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

2016-02-02 14:21:30.777 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements
2016-02-02 14:21:30.777 ThaliTest[2336:7455854] multipeer manager: stop client timer
,2016-02-02 14:21:30.777 ThaliTest[2336:7455854] multipeer manager: start client restart timer: 0x15dbc110
2016-02-02 14:21:30.784 ThaliTest[2336:7455854] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:30.796 ThaliTest[2336:7455622] client: found new peer: B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
2016-02-02 14:21:30.797 ThaliTest[2336:7455854] jxcore: connect B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
2016-02-02 14:21:30.797 ThaliTest[2336:7,455854] client: server will connect
2016-02-02 14:21:30.798 ThaliTest[2336:7455854] client session: reverseConnect
2016-02-02 14:21:30.798 ThaliTest[2336:7455854] client session: stateChange:0->1 B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
,2016-02-02 14:21:31.830 ThaliTest[2336:7455622] multipeer session: reset timer
2016-02-02 14:21:31.830 ThaliTest[2336:7455622] server: rejecting invitation from B0673E8C-23B0-4E2C-B7F0-E2565174D20F due to previous generation (AC42391D-3B67-44B2-83EF-61999,49E75E1:5 != AC42391D-3B67-44B2-83EF-6199949E75E1:4)
,2016-02-02 14:21:31.893 ThaliTest[2336:7456467] client session: not connected B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
2016-02-02 14:21:31.893 ThaliTest[2336:7456467] client session: onLinkFailure: B0673E8C-23B0-4E2C-B7F0-E2565174D20F
2016-02-02 14:21:31.893 ThaliTest[2336:7456467] client session: disconnect
2016-02-02 14:21:31.893 ThaliTest[2336:7456467] client session: stateChange:1->0 B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
,2016-02-02 14:21:31.895 ThaliTest[2336:7456467] client session: no connect callabck (server initiated)
,2016-02-02 14:26:24.036 ThaliTest[2336:7455622] client: lost peer: B0673E8C-23B0-4E2C-B7F0-E2565174D20F
2016-02-02 14:26:24.036 ThaliTest[2336:7455622] client session: onPeerLost: B0673E8C-23B0-4E2C-B7F0-E2565174D20F
,2016-02-02 14:26:45.503 ThaliTest[2336:7455622] client: found updated peer: B0673E8C-23B0-4E2C-B7F0-E2565174D20F:5
2016-02-02 14:26:45.504 ThaliTest[2336:7455854] jxcore: connect B0673E8C-23B0-4E2C-B7F0-E2565174D20F:5
2016-02-02 14:26:45.505 ThaliTest[2336:7455854] client: connect: unreachable B0673E8C-23B0-4E2C-B7F0-E2565174D20F
2016-02-02 14:26:45.505 ThaliTest[2336:7455854] jxcore: connect: fail: Peer unreachable
,2016-02-02 14:33:53.311 ThaliTest[2336:7455622] client: lost peer: B0673E8C-23B0-4E2C-B7F0-E2565174D20F
2016-02-02 14:33:53.312 ThaliTest[2336:7455622] client session: onPeerLost: B0673E8C-23B0-4E2C-B7F0-E2565174D20F

```
