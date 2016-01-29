#### Test 57531243c766d4e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A39798FF-F13A-442C-A763-1315BD5FCEA1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A39798FF-F13A-442C-A763-1315BD5FCEA1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/57531243c766d4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63134"
,(lldb)     command script import "/tmp/A39798FF-F13A-442C-A763-1315BD5FCEA1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-29 18:55:37.754 ThaliTest[276:176326] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D37CE208-EB2F-4959-B106-257C55E7041F/Library/Cookies/Cookies.binarycookies
,2016-01-29 18:55:38.161 ThaliTest[276:176326] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-29 18:55:38.162 ThaliTest[276:176326] Multi-tasking -> Device: YES, App: YES
,2016-01-29 18:55:38.171 ThaliTest[276:176326] Unlimited access to network resources
,2016-01-29 18:55:38.180 ThaliTest[276:176326] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-29 18:55:47.506 ThaliTest[276:176326] Resetting plugins due to page load.
,2016-01-29 18:55:51.132 ThaliTest[276:176326] Finished load of: file:///var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/index.html
,2016-01-29 18:55:51.295 ThaliTest[276:176326] JXcore Cordova plugin initializing
,2016-01-29 18:55:51.296 ThaliTest[276:176570] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/593EE093-FB00-46F5-A65D-63CA2569631C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-01-29 19:00:25.291 ThaliTest[276:176570] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:25.293 ThaliTest[276:176570] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:25.296 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
2016-01-29 19:00:25.297 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-01-29 19:00:25.340 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:25.340 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:25.343 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
,2016-01-29 19:00:25.344 ThaliTest[276:176570] THEMultipeerManager stopping peer
,2016-01-29 19:00:25.344 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-01-29 19:00:25.690 ThaliTest[276:176570] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:25.691 ThaliTest[276:176570] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:25.693 ThaliTest[276:176570] jxcore: startListeningForAdvertisements
2016-01-29 19:00:25.694 ThaliTest[276:176570] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

ok 19 Error must be "Call Stop!"

,# setup

,2016-01-29 19:00:25.779 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:25.780 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:25.783 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
,2016-01-29 19:00:25.783 ThaliTest[276:176570] THEMultipeerManager stopping peer
2016-01-29 19:00:25.784 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening: success
ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-01-29 19:00:26.167 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening
,2016-01-29 19:00:26.168 ThaliTest[276:176570] server: starting 770D1EEC-042B-4953-9292-E9415F928032:1
,2016-01-29 19:00:26.170 ThaliTest[276:176570] THEMultipeerManager initialized peer 770D1EEC-042B-4953-9292-E9415F928032:1
,2016-01-29 19:00:26.171 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

2016-01-29 19:00:26.174 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
2016-01-29 19:00:26.174 ThaliTest[276:176570] THEMultipeerManager stopping peer
2016-01-29 19:00:26.175 T,haliTest[276:176570] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-01-29 19:00:26.641 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:26.642 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:26.644 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
,2016-01-29 19:00:26.645 ThaliTest[276:176570] THEMultipeerManager stopping peer
,2016-01-29 19:00:26.645 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-01-29 19:00:28.637 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:28.637 ThaliTest[276:176570] server: starting 770D1EEC-042B-4953-9292-E9415F928032:2
,2016-01-29 19:00:28.639 ThaliTest[276:176570] THEMultipeerManager initialized peer 770D1EEC-042B-4953-9292-E9415F928032:2
2016-01-29 19:00:28.639 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:00:28.641 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:28.641 ThaliTest[276:176570] THEMultipeerManager stopping peer
,2016-01-29 19:00:28.643 ThaliTest[276:176570] server: starting 770D1EEC-042B-4953-9292-E9415F928032:3
2016-01-29 19:00:28.643 ThaliTest[276:176570] THEMultipeerManager initialized peer 770D1EEC-042B-4953-9292-E9415F928032:3
2016-01-29 19:00:28.644 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-01-29 19:00:28.773 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:28.773 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:28.777 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
,2016-01-29 19:00:28.777 ThaliTest[276:176570] THEMultipeerManager stopping peer
2016-01-29 19:00:28.778 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-01-29 19:00:29.207 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening
2016-01-29 19:00:29.208 ThaliTest[276:176570] server: starting 770D1EEC-042B-4953-9292-E9415F928032:4
,2016-01-29 19:00:29.209 ThaliTest[276:176570] THEMultipeerManager initialized peer 770D1EEC-042B-4953-9292-E9415F928032:4
2016-01-29 19:00:29.209 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-01-29 19:00:29.211 ThaliTest[276:176570] jxcore: startListeningForAdvertisements
2016-01-29 19:00:29.213 ThaliTest[276:176570] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:31.101 ThaliTest[276:176326] client: found peer: 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-01-29 19:00:31.314 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements
,2016-01-29 19:00:31.314 ThaliTest[276:176570] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-01-29 19:00:31.317 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening
,2016-01-29 19:00:31.317 ThaliTest[276:176570] THEMultipeerManager stopping peer
,2016-01-29 19:00:31.318 ThaliTest[276:176570] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-01-29 19:00:31.409 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening
,2016-01-29 19:00:31.409 ThaliTest[276:176570] server: starting 770D1EEC-042B-4953-9292-E9415F928032:5
,2016-01-29 19:00:31.411 ThaliTest[276:176570] THEMultipeerManager initialized peer 770D1EEC-042B-4953-9292-E9415F928032:5
2016-01-29 19:00:31.411 ThaliTest[276:176570] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-01-29 19:00:31.413 ThaliTest[276:176570] jxcore: startListeningForAdvertisements
,2016-01-29 19:00:31.414 ThaliTest[276:176570] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-01-29 19:00:31.425 ThaliTest[276:176326] client: found peer: 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1
,2016-01-29 19:00:31.428 ThaliTest[276:176570] jxcore: connect 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
2016-01-29 19:00:31.429 ThaliTest[276:176570] client: server will connect
2016-01-29 19:00:31.429 ThaliTest[276:176570] client session: reverseConnect
,2016-01-29 19:00:31.430 ThaliTest[276:176570] client session: stateChange:0->1 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
,2016-01-29 19:00:32.358 ThaliTest[276:176326] server: rejecting invitation from 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1 due to previous generation (770D1EEC-042B-4953-9292-E9415F928032:5 != 770D1EEC-042B-4953-9292-E9415F928032:4)
,2016-01-29 19:00:32.608 ThaliTest[276:177114] client session: not connected 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
,2016-01-29 19:00:32.609 ThaliTest[276:177114] client session: onLinkFailure: 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1
2016-01-29 19:00:32.610 ThaliTest[276:177114] client session: disconnect
,2016-01-29 19:00:32.610 ThaliTest[276:177114] client session: stateChange:1->0 95973D89-2F1E-4F25-8ADD-12CD6B75FDD1:4
,2016-01-29 19:00:32.611 ThaliTest[276:177114] client session: no connect callabck (server initiated)
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
