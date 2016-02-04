#### Test 575312431745da8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/AA7992CD-9FC1-43BA-923C-5CFC79387437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AA7992CD-9FC1-43BA-923C-5CFC79387437/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431745da8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50201"
,(lldb)     command script import "/tmp/AA7992CD-9FC1-43BA-923C-5CFC79387437/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 14:36:07.993 ThaliTest[661:980530] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88AF5E95-FB3B-4C69-B9AB-FB464EA0793E/Library/Cookies/Cookies.binarycookies
,2016-02-04 14:36:08.318 ThaliTest[661:980530] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 14:36:08.319 ThaliTest[661:980530] Multi-tasking -> Device: YES, App: YES
,2016-02-04 14:36:08.327 ThaliTest[661:980530] Unlimited access to network resources
,2016-02-04 14:36:08.335 ThaliTest[661:980530] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 14:36:17.795 ThaliTest[661:980530] Resetting plugins due to page load.
,2016-02-04 14:36:21.690 ThaliTest[661:980530] Finished load of: file:///var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/index.html
,2016-02-04 14:36:21.853 ThaliTest[661:980530] JXcore Cordova plugin initializing
2016-02-04 14:36:21.853 ThaliTest[661:980772] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/998BBE78-043A-4D2E-AB5E-1F954CBA3EC0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-04 14:40:44.432 ThaliTest[661:980772] jxcore: startListeningForAdvertisements
,2016-02-04 14:40:44.434 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:40:44.434 ThaliTest[661:980772] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-04 14:40:44.438 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
2016-02-04 14:40:44.439 ThaliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:44.441 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-04 14:40:44.681 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:44.682 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:44.684 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:44.685 ThaliTest[661:980772] THEMultipeerManager stopping peer
,2016-02-04 14:40:44.686 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-04 14:40:44.791 ThaliTest[661:980772] jxcore: startListeningForAdvertisements
,2016-02-04 14:40:44.792 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
,2016-02-04 14:40:44.792 ThaliTest[661:980772] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-04 14:40:44.796 ThaliTest[661:980772] jxcore: startListeningForAdvertisements
,2016-02-04 14:40:44.796 ThaliTest[661:980772] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-04 14:40:44.834 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:44.835 ThaliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:44.836 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

2016-02-04 14:40:44.839 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:44.839 ThaliTest[661:980772] THEMultipeerManager stopping peer
2016-02-04 14:40:4,4.840 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-04 14:40:45.221 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening
,2016-02-04 14:40:45.222 ThaliTest[661:980772] server: starting A177B611-71F7-4D84-9C24-28925D8696EB:1
,2016-02-04 14:40:45.224 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:40:45.225 ThaliTest[661:980772] THEMultipeerManager initialized peer A177B611-71F7-4D84-9C24-28925D8696EB:1
2016-02-04 14:40:45.226 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-04 14:40:45.228 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
2016-02-04 14:40:45.228 ThaliTest[661:980772] THEMultipeerManager stopping peer
2016-02-04 14:40:45.229 T,haliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:45.229 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-04 14:40:45.265 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:45.266 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:45.268 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:45.268 ThaliTest[661:980772] THEMultipeerManager stopping peer
,2016-02-04 14:40:45.269 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-04 14:40:45.363 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening
,2016-02-04 14:40:45.363 ThaliTest[661:980772] server: starting A177B611-71F7-4D84-9C24-28925D8696EB:2
,2016-02-04 14:40:45.365 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:40:45.365 ThaliTest[661:980772] THEMultipeerManager initialized peer A177B611-71F7-4D84-9C24-28925D8696EB:2
2016-02-04 14:40:45.365 Thal,iTest[661:980772] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-04 14:40:45.367 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening
2016-02-04 14:40:45.368 ThaliTest[661:980772] THEMultipeerManager stopping peer
,2016-02-04 14:40:45.369 ThaliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:45.369 ThaliTest[661:980772] server: starting A177B611-71F7-4D84-9C24-28925D8696EB:3
2016-02-04 14:40:45.370 ThaliTest[661:980772] multipeer manager: star,t client restart timer: 0x14f7dea0
2016-02-04 14:40:45.370 ThaliTest[661:980772] THEMultipeerManager initialized peer A177B611-71F7-4D84-9C24-28925D8696EB:3
2016-02-04 14:40:45.370 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-04 14:40:45.451 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:45.452 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:45.454 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:45.455 ThaliTest[661:980772] THEMultipeerManager stopping peer
,2016-02-04 14:40:45.456 ThaliTest[661:980772] multipeer manager: stop client timer
,2016-02-04 14:40:45.456 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-04 14:40:45.796 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening
,2016-02-04 14:40:45.797 ThaliTest[661:980772] server: starting A177B611-71F7-4D84-9C24-28925D8696EB:4
,2016-02-04 14:40:45.798 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:40:45.798 ThaliTest[661:980772] THEMultipeerManager initialized peer A177B611-71F7-4D84-9C24-28925D8696EB:4
2016-02-04 14:40:45.799 Thal,iTest[661:980772] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-04 14:40:45.801 ThaliTest[661:980772] jxcore: startListeningForAdvertisements
,2016-02-04 14:40:45.802 ThaliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:45.803 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:40:45.803 ThaliTest[661:980772] jxcore: startListenin,gForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without error
,
,2016-02-04 14:40:47.076 ThaliTest[661:980530] client: found new peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-04 14:40:47.343 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements
,2016-02-04 14:40:47.343 ThaliTest[661:980772] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-04 14:40:47.346 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening
,2016-02-04 14:40:47.346 ThaliTest[661:980772] THEMultipeerManager stopping peer
,2016-02-04 14:40:47.347 ThaliTest[661:980772] multipeer manager: stop client timer
2016-02-04 14:40:47.348 ThaliTest[661:980772] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-04 14:41:06.663 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening
,2016-02-04 14:41:06.663 ThaliTest[661:980772] server: starting A177B611-71F7-4D84-9C24-28925D8696EB:5
,2016-02-04 14:41:06.665 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:41:06.665 ThaliTest[661:980772] THEMultipeerManager initialized peer A177B611-71F7-4D84-9C24-28925D8696EB:5
2016-02-04 14:41:06.666 ThaliTest[661:980772] jxcore: startUpdateAdvertisingAndListening: success
,ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-04 14:41:06.669 ThaliTest[661:980772] jxcore: startListeningForAdvertisements
,2016-02-04 14:41:06.669 ThaliTest[661:980772] multipeer manager: stop client timer
,2016-02-04 14:41:06.670 ThaliTest[661:980772] multipeer manager: start client restart timer: 0x14f7dea0
2016-02-04 14:41:06.671 ThaliTest[661:980772] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,2016-02-04 14:41:08.059 ThaliTest[661:980530] client: found new peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:41:08.061 ThaliTest[661:980772] jxcore: connect 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
2016-02-04 14:41:08.062 ThaliTest[661:980772] client session: connect
2016-02-04 14:41:08.062 ThaliTest[661:980772] client session: stateChange:0->1 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:41:09.320 ThaliTest[661:980530] multipeer session: reset timer
,2016-02-04 14:41:09.320 ThaliTest[661:980530] server: rejecting invitation for lexical ordering 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:41:09.323 ThaliTest[661:980772] jxcore: connect 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:41:09.323 ThaliTest[661:980772] client: already connect(ing/ed) to 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
2016-02-04 14:41:09.324 ThaliTest[661:980772] jxcore: connect: fail: Aleady connecting
,2016-02-04 14:41:12.722 ThaliTest[661:981251] client session: connected
,2016-02-04 14:41:12.722 ThaliTest[661:981251] client session: stateChange:1->2 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:41:12.729 ThaliTest[661:981252] client session: fireConnectCallback: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:41:12.730 ThaliTest[661:981252] jxcore: connect: success
,{ clientPort: 0, serverPort: 0, listeningPort: 53266 }

,ok 42 Connection must have listeningPort

,ok 43 listeningPort must be a number

,ok 44 Connection must have clientPort

,ok 45 clientPort must be null

,ok 46 Connection must have serverPort

,ok 47 serverPort must be null

,# setup

,2016-02-04 14:41:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:41:26.685 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:41:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:41:46.687 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:42:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:42:06.686 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:42:21.430 ThaliTest[661:981398] client session: not connected 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
2016-02-04 14:42:21.431 ThaliTest[661:981398] client session: onLinkFailure: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
2016-02-04 14:42:21.431 T,haliTest[661:981398] client session: disconnect
2016-02-04 14:42:21.431 ThaliTest[661:981398] client session: stateChange:2->0 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:42:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:42:26.686 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:42:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:42:46.686 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:43:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:43:06.684 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:43:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:43:26.687 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:43:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:43:46.685 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:44:06.686 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:44:26.685 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:42.632 ThaliTest[661:980530] client: lost peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:44:42.632 ThaliTest[661:980530] client session: onPeerLost: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:44:44.279 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:44.281 ThaliTest[661:980772] jxcore: connect 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:44.282 ThaliTest[661:980772] client session: connect
,2016-02-04 14:44:44.282 ThaliTest[661:980772] client session: stateChange:0->1 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:44:46.687 ThaliTest[661:980530] client: found existing peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:49.312 ThaliTest[661:980530] client: lost peer: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:44:49.312 ThaliTest[661:980530] client session: onPeerLost: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
2016-02-04 14:44:49.313 ThaliTest[661:980530] client session: onLinkFailure: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:44:49.313 ThaliTest[661:980530] client session: disconnect
2016-02-04 14:44:49.313 ThaliTest[661:980530] client session: stateChange:1->0 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C:5
,2016-02-04 14:44:49.314 ThaliTest[661:980530] client session: fireConnectCallback: 1632E4F6-D8EF-4B76-AC05-F83B2F14AA0C
,2016-02-04 14:44:49.314 ThaliTest[661:980530] jxcore: connect: fail: Peer disconnected
,2016-02-04 14:45:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:45:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:45:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:46:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:46:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:46:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:47:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:47:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:47:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:48:06.672 ThaliTest[661:980530] multipeer manager: restart client
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,2016-02-04 14:48:26.672 ThaliTest[661:980530] multipeer manager: restart client
,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,2016-02-04 14:48:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:49:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:49:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:49:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:50:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:50:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:50:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:51:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:51:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:51:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:52:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:52:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:52:46.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:53:06.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:53:26.672 ThaliTest[661:980530] multipeer manager: restart client
,2016-02-04 14:53:46.672 ThaliTest[661:980530] multipeer manager: restart client

```
