#### Test 575312435db8e90_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/813A56B1-13E6-40B9-9D3C-C42E51D799CA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/813A56B1-13E6-40B9-9D3C-C42E51D799CA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312435db8e90/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63959"
,(lldb)     command script import "/tmp/813A56B1-13E6-40B9-9D3C-C42E51D799CA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:23:40.012 ThaliTest[417:669547] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC57ED91-5B01-4550-829D-BF665FA745BB/Library/Cookies/Cookies.binarycookies
,2016-02-02 12:23:40.379 ThaliTest[417:669547] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 12:23:40.380 ThaliTest[417:669547] Multi-tasking -> Device: YES, App: YES
,2016-02-02 12:23:40.389 ThaliTest[417:669547] Unlimited access to network resources
,2016-02-02 12:23:40.399 ThaliTest[417:669547] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 12:23:48.958 ThaliTest[417:669547] Resetting plugins due to page load.
,2016-02-02 12:23:52.578 ThaliTest[417:669547] Finished load of: file:///var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/index.html
,2016-02-02 12:23:52.744 ThaliTest[417:669547] JXcore Cordova plugin initializing
,2016-02-02 12:23:52.744 ThaliTest[417:669797] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42E235DF-0A05-46AC-ACC0-46FF989F785B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
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

,2016-02-02 12:28:17.356 ThaliTest[417:669797] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.357 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
,2016-02-02 12:28:17.358 ThaliTest[417:669797] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

2016-02-02 12:28:17.363 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:17.364 ThaliTest[417:669797] multipeer manager: stop client timer
,2016-02-02 12:28:17.365 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 12:28:17.391 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:17.391 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:17.394 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
,2016-02-02 12:28:17.394 ThaliTest[417:669797] THEMultipeerManager stopping peer
,2016-02-02 12:28:17.395 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 12:28:17.438 ThaliTest[417:669797] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.439 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
,2016-02-02 12:28:17.439 ThaliTest[417:669797] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 12:28:17.443 ThaliTest[417:669797] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:17.443 ThaliTest[417:669797] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error
,
,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 12:28:17.634 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:17.635 ThaliTest[417:669797] multipeer manager: stop client timer
,2016-02-02 12:28:17.635 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:17.638 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:17.639 ThaliTest[417:669797] THEMultipeerManager stopping peer
2016-02-02 12:28:17.639 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 12:28:17.684 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 12:28:17.685 ThaliTest[417:669797] server: starting 486A7E46-8E93-4E50-8992-47F882FEA360:1
,2016-02-02 12:28:17.687 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:17.687 ThaliTest[417:669797] THEMultipeerManager initialized peer 486A7E46-8E93-4E50-8992-47F882FEA360:1
2016-02-02 12:28:17.688 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 12:28:17.690 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
2016-02-02 12:28:17.690 ThaliTest[417:669797] THEMultipeerManager stopping peer
2016-02-02 12:28:17.691 ThaliTest[417:669797] multipeer manager: stop client timer
2016-02-02 12:28:17.691 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 12:28:17.732 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:17.732 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:17.735 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
,2016-02-02 12:28:17.735 ThaliTest[417:669797] THEMultipeerManager stopping peer
,2016-02-02 12:28:17.736 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 12:28:23.428 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 12:28:23.429 ThaliTest[417:669797] server: starting 486A7E46-8E93-4E50-8992-47F882FEA360:2
,2016-02-02 12:28:23.430 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:23.431 ThaliTest[417:669797] THEMultipeerManager initialized peer 486A7E46-8E93-4E50-8992-47F882FEA360:2
,2016-02-02 12:28:23.431 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening: success
,ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 12:28:23.441 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 12:28:23.442 ThaliTest[417:669797] THEMultipeerManager stopping peer
,2016-02-02 12:28:23.445 ThaliTest[417:669797] multipeer manager: stop client timer
,2016-02-02 12:28:23.446 ThaliTest[417:669797] server: starting 486A7E46-8E93-4E50-8992-47F882FEA360:3
,2016-02-02 12:28:23.447 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
,2016-02-02 12:28:23.451 ThaliTest[417:669797] THEMultipeerManager initialized peer 486A7E46-8E93-4E50-8992-47F882FEA360:3
,2016-02-02 12:28:23.453 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 12:28:24.304 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:24.305 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:24.307 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
,2016-02-02 12:28:24.307 ThaliTest[417:669797] THEMultipeerManager stopping peer
,2016-02-02 12:28:24.308 ThaliTest[417:669797] multipeer manager: stop client timer
2016-02-02 12:28:24.309 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 12:28:35.331 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 12:28:35.332 ThaliTest[417:669797] server: starting 486A7E46-8E93-4E50-8992-47F882FEA360:4
,2016-02-02 12:28:35.334 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:35.334 ThaliTest[417:669797] THEMultipeerManager initialized peer 486A7E46-8E93-4E50-8992-47F882FEA360:4
2016-02-02 12:28:35.335 Thal,iTest[417:669797] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-02 12:28:35.337 ThaliTest[417:669797] jxcore: startListeningForAdvertisements
,2016-02-02 12:28:35.338 ThaliTest[417:669797] multipeer manager: stop client timer
,2016-02-02 12:28:35.339 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:35.340 ThaliTest[417:669797] jxcore: startListeningForAdvertisements: success
,ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 12:28:40.895 ThaliTest[417:669547] client: found new peer: 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 12:28:41.319 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements
,2016-02-02 12:28:41.320 ThaliTest[417:669797] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 12:28:41.322 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening
,2016-02-02 12:28:41.323 ThaliTest[417:669797] THEMultipeerManager stopping peer
,2016-02-02 12:28:41.324 ThaliTest[417:669797] multipeer manager: stop client timer
2016-02-02 12:28:41.325 ThaliTest[417:669797] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 12:28:45.694 ThaliTest[417:669797] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 12:28:45.695 ThaliTest[417:669797] server: starting 486A7E46-8E93-4E50-8992-47F882FEA360:5
,2016-02-02 12:28:45.696 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:45.697 ThaliTest[417:669797] THEMultipeerManager initialized peer 486A7E46-8E93-4E50-8992-47F882FEA360:5
2016-02-02 12:28:45.697 Thal,iTest[417:669797] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 12:28:45.700 ThaliTest[417:669797] jxcore: startListeningForAdvertisements
2016-02-02 12:28:45.701 ThaliTest[417:669797] multipeer manager: stop client timer
,2016-02-02 12:28:45.705 ThaliTest[417:669797] multipeer manager: start client restart timer: 0x1667b9e0
2016-02-02 12:28:45.706 ThaliTest[417:669797] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:28:47.652 ThaliTest[417:669547] client: found new peer: 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:47.655 ThaliTest[417:669797] jxcore: connect 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
2016-02-02 12:28:47.655 ThaliTest[417:669797] client session: connect
2016-02-02 12:28:47.655 ThaliTest[417:669797] client session: stateChange:0->1 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:49.230 ThaliTest[417:670419] client session: not connected 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:49.231 ThaliTest[417:670419] client session: onLinkFailure: 23463C64-D12A-4472-B5F9-52B63D6A8BDA
,2016-02-02 12:28:49.232 ThaliTest[417:670419] client session: disconnect
2016-02-02 12:28:49.233 ThaliTest[417:670419] client session: stateChange:1->0 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:49.233 ThaliTest[417:670419] client session: fireConnectCallback: 23463C64-D12A-4472-B5F9-52B63D6A8BDA
2016-02-02 12:28:49.234 ThaliTest[417:670419] jxcore: connect: fail: Peer disconnected
,2016-02-02 12:28:49.360 ThaliTest[417:669547] multipeer session: reset timer
2016-02-02 12:28:49.361 ThaliTest[417:669547] server: rejecting invitation for lexical ordering 23463C64-D12A-4472-B5F9-52B63D6A8BDA
,2016-02-02 12:28:49.364 ThaliTest[417:669797] jxcore: connect 23463C64-D12A-4472-B5F9-52B63D6A8BDA:5
,2016-02-02 12:28:49.364 ThaliTest[417:669797] client session: connect
2016-02-02 12:28:49.365 ThaliTest[417:669797] client session: stateChange:0->1 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:52.439 ThaliTest[417:670417] client session: connected
2016-02-02 12:28:52.439 ThaliTest[417:670417] client session: stateChange:1->2 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
,2016-02-02 12:28:52.469 ThaliTest[417:670418] client session: fireConnectCallback: 23463C64-D12A-4472-B5F9-52B63D6A8BDA
,2016-02-02 12:28:52.469 ThaliTest[417:670418] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 50970 }

,ok 42 Connection must have listeningPort

,ok 43 listeningPort must be a number

,ok 44 Connection must have clientPort

,ok 45 clientPort must be null

,ok 46 Connection must have serverPort

,ok 47 serverPort must be null

,# setup

,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,2016-02-02 12:37:49.013 ThaliTest[417:671439] client session: not connected 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4
2016-02-02 12:37:49.014 ThaliTest[417:671439] client session: onLinkFailure: 23463C64-D12A-4472-B5F9-52B63D6A8BDA
2016-02-02 12:37:49.014 T,haliTest[417:671439] client session: disconnect
2016-02-02 12:37:49.014 ThaliTest[417:671439] client session: stateChange:2->0 23463C64-D12A-4472-B5F9-52B63D6A8BDA:4

```
