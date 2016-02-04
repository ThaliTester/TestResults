#### Test 575312431745da8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/ECCDAD8B-2D69-4957-95CE-4EE71F0C24D5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ECCDAD8B-2D69-4957-95CE-4EE71F0C24D5/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50203"
,(lldb)     command script import "/tmp/ECCDAD8B-2D69-4957-95CE-4EE71F0C24D5/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 14:36:06.025 ThaliTest[1234:2196589] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/91CC2615-3A89-45C7-A305-A7FEB3EC80F0/Library/Cookies/Cookies.binarycookies
,2016-02-04 14:36:06.463 ThaliTest[1234:2196589] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 14:36:06.464 ThaliTest[1234:2196589] Multi-tasking -> Device: YES, App: YES
,2016-02-04 14:36:06.474 ThaliTest[1234:2196589] Unlimited access to network resources
,2016-02-04 14:36:06.489 ThaliTest[1234:2196589] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 14:36:16.385 ThaliTest[1234:2196589] Resetting plugins due to page load.
,2016-02-04 14:36:20.155 ThaliTest[1234:2196589] Finished load of: file:///var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/index.html
,2016-02-04 14:36:20.338 ThaliTest[1234:2196589] JXcore Cordova plugin initializing
2016-02-04 14:36:20.339 ThaliTest[1234:2196820] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7EC4544D-50CC-459F-B503-3AD1497B5E88/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-04 14:40:41.300 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements
,2016-02-04 14:40:41.303 ThaliTest[1234:2196820] multipeer manager: start client restart timer: 0x165e9740
,2016-02-04 14:40:41.304 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements: success
ok 13 Can call startListeningForAdvertisements without error

,2016-02-04 14:40:41.308 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:41.308 ThaliTest[1234:2196820] multipeer manager: stop client timer
2016-02-04 14:40:41.309 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-04 14:40:41.385 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:41.386 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
ok 15 Should be able to call stopListeningForAdvertisments in teardown,

,2016-02-04 14:40:41.388 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:41.388 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
2016-02-04 14:40:41.389 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: suc,cess
ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-04 14:40:41.657 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements
2016-02-04 14:40:41.657 ThaliTest[1234:2196820] multipeer manager: start client restart timer: 0x165e9740
2016-02-04 14:40:41.658 ThaliTest[1234:2196820] jxcore: star,tListeningForAdvertisements: success
ok 17 Can call startListeningForAdvertisements without error

2016-02-04 14:40:41.660 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements
2016-02-04 14:40:41.660 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-04 14:40:41.716 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:41.718 ThaliTest[1234:2196820] multipeer manager: stop client timer
,2016-02-04 14:40:41.722 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:41.725 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:41.727 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
,2016-02-04 14:40:41.728 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-04 14:40:42.084 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:40:42.085 ThaliTest[1234:2196820] server: starting 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:1
2016-02-04 14:40:42.086 ThaliTest[1234:2196820] multipeer m,anager: start client restart timer: 0x165e9740
2016-02-04 14:40:42.086 ThaliTest[1234:2196820] THEMultipeerManager initialized peer 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:1
2016-02-04 14:40:42.087 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-04 14:40:42.088 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:42.089 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
201,6-02-04 14:40:42.090 ThaliTest[1234:2196820] multipeer manager: stop client timer
2016-02-04 14:40:42.090 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-04 14:40:42.150 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:42.151 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:42.153 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:42.153 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
,2016-02-04 14:40:42.154 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-04 14:40:42.259 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:40:42.260 ThaliTest[1234:2196820] server: starting 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:2
2016-02-04 14:40:42.261 ThaliTest[1234:2196820] multipeer m,anager: start client restart timer: 0x165e9740
2016-02-04 14:40:42.261 ThaliTest[1234:2196820] THEMultipeerManager initialized peer 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:2
2016-02-04 14:40:42.262 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-04 14:40:42.264 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:40:42.264 ThaliTest[1234:2196820] THEMultipeerManager stopping pe,er
2016-02-04 14:40:42.264 ThaliTest[1234:2196820] multipeer manager: stop client timer
2016-02-04 14:40:42.265 ThaliTest[1234:2196820] server: starting 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:3
2016-02-04 14:40:42.266 ThaliTest[1234:2196820] multipeer man,ager: start client restart timer: 0x165e9740
2016-02-04 14:40:42.269 ThaliTest[1234:2196820] THEMultipeerManager initialized peer 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:3
2016-02-04 14:40:42.269 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndList,ening: success
ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-04 14:40:42.329 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:42.329 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:42.332 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:42.333 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
2016-02-04 14:40:42.333 ThaliTest[1234:2196820] multipeer manager: stop client timer
20,16-02-04 14:40:42.333 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-04 14:40:42.664 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:40:42.664 ThaliTest[1234:2196820] server: starting 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:4
2016-02-04 14:40:42.665 ThaliTest[1234:2196820] multipeer m,anager: start client restart timer: 0x165e9740
2016-02-04 14:40:42.666 ThaliTest[1234:2196820] THEMultipeerManager initialized peer 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:4
2016-02-04 14:40:42.666 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

2016-02-04 14:40:42.668 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements
2016-02-04 14:40:42.668 ThaliTest[1234:2196820] multipeer manager: stop client time,r
2016-02-04 14:40:42.669 ThaliTest[1234:2196820] multipeer manager: start client restart timer: 0x165e9740
2016-02-04 14:40:42.669 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements w,ithout error

,2016-02-04 14:40:43.931 ThaliTest[1234:2196589] client: found new peer: A177B611-71F7-4D84-9C24-28925D8696EB:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

ok 34 peer must have peerIdentifier

ok 35 peerIdentifier must be a string

ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-04 14:40:44.209 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:44.209 ThaliTest[1234:2196820] jxcore: stopListeningForAdvertisements: success
ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:44.211 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:44.212 ThaliTest[1234:2196820] THEMultipeerManager stopping peer
2016-02-04 14:40:44.212 ThaliTest[1234:2196820] multipeer manager: stop client timer
20,16-02-04 14:40:44.213 ThaliTest[1234:2196820] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-04 14:41:03.542 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:41:03.542 ThaliTest[1234:2196820] server: starting 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
2016-02-04 14:41:03.543 ThaliTest[1234:2196820] multipeer m,anager: start client restart timer: 0x165e9740
2016-02-04 14:41:03.544 ThaliTest[1234:2196820] THEMultipeerManager initialized peer 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
2016-02-04 14:41:03.544 ThaliTest[1234:2196820] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

2016-02-04 14:41:03.546 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements
2016-02-04 14:41:03.546 ThaliTest[1234:2196820] multipeer manager: stop client tim,er
2016-02-04 14:41:03.547 ThaliTest[1234:2196820] multipeer manager: start client restart timer: 0x165e9740
2016-02-04 14:41:03.547 ThaliTest[1234:2196820] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-02-04 14:41:05.579 ThaliTest[1234:2196589] client: found new peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:05.582 ThaliTest[1234:2196820] jxcore: connect A177B611-71F7-4D84-9C24-28925D8696EB:5
2016-02-04 14:41:05.582 ThaliTest[1234:2196820] client: server will connect
2016-02-04 14:41:05.582 ThaliTest[1234:2196820] client session: reverseConn,ect
2016-02-04 14:41:05.583 ThaliTest[1234:2196820] client session: stateChange:0->1 A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:06.189 ThaliTest[1234:2196589] multipeer session: reset timer
2016-02-04 14:41:06.190 ThaliTest[1234:2196589] server session: connect
2016-02-04 14:41:06.190 ThaliTest[1234:2196589] server session: stateChange:0->1 A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:06.200 ThaliTest[1234:2196589] server: accepting invitation A177B611-71F7-4D84-9C24-28925D8696EB
,2016-02-04 14:41:06.442 ThaliTest[1234:2197349] client session: not connected A177B611-71F7-4D84-9C24-28925D8696EB:5
2016-02-04 14:41:06.443 ThaliTest[1234:2197349] client session: onLinkFailure: A177B611-71F7-4D84-9C24-28925D8696EB
2016-02-04 14:41:06.4,44 ThaliTest[1234:2197349] client session: disconnect
,2016-02-04 14:41:06.444 ThaliTest[1234:2197349] client session: stateChange:1->0 A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:06.449 ThaliTest[1234:2197349] client session: no connect callabck (server initiated)
,2016-02-04 14:41:09.591 ThaliTest[1234:2197349] server session: connected
2016-02-04 14:41:09.591 ThaliTest[1234:2197349] server session: stateChange:1->2 A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:09.609 ThaliTest[1234:2196589] server relay: socket disconnected
2016-02-04 14:41:09.610 ThaliTest[1234:2196589] server relay: 0x17e28c60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:41:23.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:41:23.566 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:43.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:42:03.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:42:03.559 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:42:23.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:42:23.559 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:42:28.718 ThaliTest[1234:2197350] server session: not connected A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:42:43.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:42:43.560 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:43:03.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:43:03.560 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:43:23.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:43:23.559 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:43:43.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:43:43.561 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:44:03.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:44:03.562 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:44:23.548 ThaliTest[1234:2196589] multipeer manager: restart client
,2016-02-04 14:44:23.561 ThaliTest[1234:2196589] client: found existing peer: A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:44:42.407 ThaliTest[1234:2196589] multipeer session: reset timer
2016-02-04 14:44:42.407 ThaliTest[1234:2196589] server: disconnecting to refresh session (A177B611-71F7-4D84-9C24-28925D8696EB)
2016-02-04 14:44:42.407 ThaliTest[1234:2196589], server session: disconnect
2016-02-04 14:44:42.408 ThaliTest[1234:2196589] server session: stateChange:2->0 A177B611-71F7-4D84-9C24-28925D8696EB:5
Assertion failed: (_connectCallback == nil), function -[THEMultipeerServerSession connectWithConnectCallba,ck:], file /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/THEMultipeerServerSession.m, line 63.
,* thread #1: tid = 0x21846d, 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38fc7c84 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x39067b46 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38f5ff40 libsystem_c.dylib`abort + 108
    frame #3: 0x38f3f6ce libsystem_c.dylib`__assert_rtn + 302
    frame #4: 0x000b73e6 ThaliTest`-[THEMultipeerServerSession connectWithConnectCallback:] + 254
    frame #5: 0x000b41e4 ThaliTest`-[THEMultipeerServer advertiser:didReceiveInvitationFromPeer:withContext:invitationHandler:] + 1396
    frame #6: 0x292c0acc MultipeerConnectivity`<redacted> + 152
    frame #7: 0x38ecfe2e libdispatch.dylib`<redacted> + 10
    frame #8: 0x38ecfe1a libdispatch.dylib`<redacted> + 22
    frame #9: 0x38ed46c8 libdispatch.dylib`_dispatch_main_queue_callback_4CF + 1532
    frame #10: 0x26d3f534 CoreFoundation`<redacted> + 8
    frame #11: 0x26d3da2e CoreFoundation`<redacted> + 1590
    frame #12: 0x26c900d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #13: 0x26c8fecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #14: 0x2ffc5af8 GraphicsServices`GSEventRunModal + 160
    frame #15: 0x2af192dc UIKit`UIApplicationMain + 144
    frame #16: 0x000a0cf2 ThaliTest`main + 50

```
