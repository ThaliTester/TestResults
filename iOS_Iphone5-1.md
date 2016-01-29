#### Test 575312430087a60_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0984414B-DAB8-42D9-BC8B-289FEBAD0F94/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0984414B-DAB8-42D9-BC8B-289FEBAD0F94/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312430087a60/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63238"
,(lldb)     command script import "/tmp/0984414B-DAB8-42D9-BC8B-289FEBAD0F94/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 19:23:48.609 ThaliTest[2168:6824929] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EF600241-4AE6-458C-9BB2-6894FA46A9D6/Library/Cookies/Cookies.binarycookies
,2016-01-29 19:23:48.732 ThaliTest[2168:6824929] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 19:23:48.734 ThaliTest[2168:6824929] Multi-tasking -> Device: YES, App: YES
,2016-01-29 19:23:48.738 ThaliTest[2168:6824929] Unlimited access to network resources
,2016-01-29 19:23:48.751 ThaliTest[2168:6824929] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 19:23:55.114 ThaliTest[2168:6824929] Resetting plugins due to page load.
,2016-01-29 19:23:57.624 ThaliTest[2168:6824929] Finished load of: file:///var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/index.html
,2016-01-29 19:23:57.812 ThaliTest[2168:6824929] JXcore Cordova plugin initializing
,2016-01-29 19:23:57.921 ThaliTest[2168:6825125] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/634C98E4-9FBE-420D-B26E-B834A28533EA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-01-29 19:29:07.172 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements
,2016-01-29 19:29:07.175 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements without error

2016-01-29 19:29:07.176 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:07.177 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

# setup

,2016-01-29 19:29:07.207 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:07.207 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown,

2016-01-29 19:29:07.209 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:07.209 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:07.209 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: ,success
ok 16 Should be able to call stopAdvertisingAndListening in teardown

# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-01-29 19:29:07.487 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements
2016-01-29 19:29:07.487 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:07.489 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements
2016-01-29 19:29:07.489 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call St,op!"

# setup

,2016-01-29 19:29:08.086 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:08.086 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 20 Should be able to call stopListeningForAdvertisments in teardown,

2016-01-29 19:29:08.087 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:08.087 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:08.088 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: ,success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-01-29 19:29:09.513 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:09.513 ThaliTest[2168:6825125] server: starting 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:1
2016-01-29 19:29:09.514 ThaliTest[2168:6825125] THEMultipee,rManager initialized peer 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:1
2016-01-29 19:29:09.514 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:29:09.515 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:09.515 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:09.516 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-01-29 19:29:13.385 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:13.385 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown,

2016-01-29 19:29:13.386 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:13.386 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:13.386 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: ,success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-01-29 19:29:15.845 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:15.845 ThaliTest[2168:6825125] server: starting 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:2
2016-01-29 19:29:15.845 ThaliTest[2168:6825125] THEMultipee,rManager initialized peer 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:2
2016-01-29 19:29:15.846 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:29:15.847 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:15.847 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:15.847 ThaliTest[2168:6825125] server: starting 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:3
,2016-01-29 19:29:15.848 ThaliTest[2168:6825125] THEMultipeerManager initialized peer 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:3
2016-01-29 19:29:15.848 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-01-29 19:29:15.866 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:15.867 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:29:15.868 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:15.868 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:15.868 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: suc,cess
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-01-29 19:29:18.683 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:18.683 ThaliTest[2168:6825125] server: starting 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:4
2016-01-29 19:29:18.683 ThaliTest[2168:6825125] THEMultipee,rManager initialized peer 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:4
2016-01-29 19:29:18.684 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-01-29 19:29:18.685, ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements
2016-01-29 19:29:18.685 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:19.631 ThaliTest[2168:6824929] client: found peer: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-01-29 19:29:21.836 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements
2016-01-29 19:29:21.836 ThaliTest[2168:6825125] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown,

2016-01-29 19:29:21.837 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening
2016-01-29 19:29:21.837 ThaliTest[2168:6825125] THEMultipeerManager stopping peer
2016-01-29 19:29:21.838 ThaliTest[2168:6825125] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,# teardown

,2016-01-29 19:29:23.488 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:29:23.488 ThaliTest[2168:6825125] server: starting 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:29:23.488 ThaliTest[2168:6825125] THEMultipee,rManager initialized peer 4AD9B88D-FF95-42F6-B2A5-BCD6B24CE242:5
2016-01-29 19:29:23.488 ThaliTest[2168:6825125] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

2016-01-29 19:29:23.48,9 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements
2016-01-29 19:29:23.490 ThaliTest[2168:6825125] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-01-29 19:29:25.854 ThaliTest[2168:6824929] client: found peer: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:29:25.855 ThaliTest[2168:6825125] jxcore: connect 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:29:25.856 ThaliTest[2168:6825125,] client session: connect
2016-01-29 19:29:25.856 ThaliTest[2168:6825125] client session: stateChange:0->1 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
,2016-01-29 19:29:26.044 ThaliTest[2168:6824929] server: rejecting invitation for lexical ordering 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:29:26.045 ThaliTest[2168:6825125] jxcore: connect 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:29,:26.046 ThaliTest[2168:6825125] client: already connect(ing/ed) to 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:29:26.046 ThaliTest[2168:6825125] jxcore: connect: fail: Aleady connecting
,2016-01-29 19:29:28.661 ThaliTest[2168:6825972] client session: connected
2016-01-29 19:29:28.661 ThaliTest[2168:6825972] client session: stateChange:1->2 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
,2016-01-29 19:29:28.725 ThaliTest[2168:6826007] client session: fireConnectCallback: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:29:28.725 ThaliTest[2168:6826007] jxcore: connect: success
{ clientPort: 0, serverPort: 0, listeningPort: 59900 }

ok 42 Connection must have listeningPort

ok 43 listeningPort must be a number

ok 44 Connection must have clientPort

ok 45 clientPort must be null

ok 46 Connection must have serverPort

ok 47 serverPort must be null

,# setup

,2016-01-29 19:33:25.255 ThaliTest[2168:6826391] client session: not connected 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:33:25.256 ThaliTest[2168:6826391] client session: onLinkFailure: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:33:25.256 ThaliTest[2168:6826391] client session: disconnect
2016-01-29 19:33:25.256 ThaliTest[2168:6826391] client session: stateChange:2->0 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
,2016-01-29 19:33:31.834 ThaliTest[2168:6824929] client: lost peer: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:33:31.835 ThaliTest[2168:6824929] client session: onPeerLost: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
,2016-01-29 19:33:52.739 ThaliTest[2168:6825125] jxcore: connect 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:33:52.739 ThaliTest[2168:6825125] client: connect: unreachable 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:33:52.739 ThaliTest[216,8:6825125] jxcore: connect: fail: Peer unreachable
,2016-01-29 19:40:56.316 ThaliTest[2168:6824929] client: lost peer: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:40:56.317 ThaliTest[2168:6824929] client session: onPeerLost: 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
,2016-01-29 19:41:16.126 ThaliTest[2168:6825125] jxcore: connect 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407:5
2016-01-29 19:41:16.127 ThaliTest[2168:6825125] client: connect: unreachable 03A0BFE6-63BD-4CA4-ABC6-C41FC11C9407
2016-01-29 19:41:16.127 ThaliTest[2168:6825125] jxcore: connect: fail: Peer unreachable

```
