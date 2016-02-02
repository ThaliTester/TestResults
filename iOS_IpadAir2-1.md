#### Test 575312438097721_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D00C052A-D1BE-4657-86D3-D59ADB981EF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D00C052A-D1BE-4657-86D3-D59ADB981EF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312438097721/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64760"
,(lldb)     command script import "/tmp/D00C052A-D1BE-4657-86D3-D59ADB981EF9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 17:13:27.857 ThaliTest[496:706349] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/40404F43-5643-4EBD-886B-EF84AE3B5E0D/Library/Cookies/Cookies.binarycookies
,2016-02-02 17:13:28.130 ThaliTest[496:706349] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 17:13:28.131 ThaliTest[496:706349] Multi-tasking -> Device: YES, App: YES
,2016-02-02 17:13:28.138 ThaliTest[496:706349] Unlimited access to network resources
,2016-02-02 17:13:28.145 ThaliTest[496:706349] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 17:13:37.712 ThaliTest[496:706349] Resetting plugins due to page load.
,2016-02-02 17:13:41.647 ThaliTest[496:706349] Finished load of: file:///var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/index.html
,2016-02-02 17:13:41.810 ThaliTest[496:706349] JXcore Cordova plugin initializing
2016-02-02 17:13:41.810 ThaliTest[496:706600] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/73679D4D-911A-400F-80C3-7497172873E9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,2016-02-02 17:18:10.287 ThaliTest[496:706600] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:10.288 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:10.289 ThaliTest[496:706600] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-02 17:18:10.293 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:10.294 ThaliTest[496:706600] multipeer manager: stop client timer
2016-02-02 17:18:10.295 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 17:18:10.571 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
,2016-02-02 17:18:10.572 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:10.574 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:10.575 ThaliTest[496:706600] THEMultipeerManager stopping peer
,2016-02-02 17:18:10.575 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 17:18:10.732 ThaliTest[496:706600] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:10.733 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:10.733 ThaliTest[496:706600] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 17:18:10.736 ThaliTest[496:706600] jxcore: startListeningForAdvertisements
2016-02-02 17:18:10.736 ThaliTest[496:706600] jxcore: startListeningForAdvertisements: failure
,ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 17:18:10.783 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:10.783 ThaliTest[496:706600] multipeer manager: stop client timer
,2016-02-02 17:18:10.784 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:10.787 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
2016-02-02 17:18:10.787 ThaliTest[496:706600] THEMultipeerManager stopping peer
2016-02-02 17:18:10.787 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 17:18:11.680 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 17:18:11.681 ThaliTest[496:706600] server: starting 7548CBFA-E4A4-4015-A6EA-FADE5525928F:1
,2016-02-02 17:18:11.682 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:11.684 ThaliTest[496:706600] THEMultipeerManager initialized peer 7548CBFA-E4A4-4015-A6EA-FADE5525928F:1
2016-02-02 17:18:11.684 Thal,iTest[496:706600] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 17:18:11.687 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
2016-02-02 17:18:11.688 ThaliTest[496:706600] THEMultipeerManager stopping peer
2016-02-02 17:18:11.688 ThaliTest[496:706600] multipeer manager: stop client timer
2016-02-02 17:18:11.688 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 17:18:11.738 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
2016-02-02 17:18:11.738 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:11.740 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:11.741 ThaliTest[496:706600] THEMultipeerManager stopping peer
,2016-02-02 17:18:11.741 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 17:18:12.278 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 17:18:12.279 ThaliTest[496:706600] server: starting 7548CBFA-E4A4-4015-A6EA-FADE5525928F:2
,2016-02-02 17:18:12.280 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:12.280 ThaliTest[496:706600] THEMultipeerManager initialized peer 7548CBFA-E4A4-4015-A6EA-FADE5525928F:2
2016-02-02 17:18:12.281 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 17:18:12.284 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening
2016-02-02 17:18:12.284 ThaliTest[496:706600] THEMultipeerManager stopping peer
2016-02-02 17:18:12.284 ThaliTest[496:706600] multipeer manager: stop client timer
2016-02-02 17:18:12.285 ThaliTest[496:706600] server: starting 7548CBFA-E4A4-4015-A6EA-FADE5525928F:3
,2016-02-02 17:18:12.286 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:12.287 ThaliTest[496:706600] THEMultipeerManager initialized peer 7548CBFA-E4A4-4015-A6EA-FADE5525928F:3
2016-02-02 17:18:12.288 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 17:18:12.563 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
,2016-02-02 17:18:12.564 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:12.566 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:12.567 ThaliTest[496:706600] THEMultipeerManager stopping peer
,2016-02-02 17:18:12.567 ThaliTest[496:706600] multipeer manager: stop client timer
2016-02-02 17:18:12.568 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 17:18:12.686 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 17:18:12.687 ThaliTest[496:706600] server: starting 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
,2016-02-02 17:18:12.688 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:12.689 ThaliTest[496:706600] THEMultipeerManager initialized peer 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4
2016-02-02 17:18:12.689 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-02 17:18:12.691 ThaliTest[496:706600] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:12.691 ThaliTest[496:706600] multipeer manager: stop client timer
,2016-02-02 17:18:12.692 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:12.693 ThaliTest[496:706600] jxcore: startListeningForAdvertisements: success
ok 31 Can call startListeningForAdvertisements without ,error

,2016-02-02 17:18:14.009 ThaliTest[496:706349] client: found new peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 17:18:14.156 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements
,2016-02-02 17:18:14.157 ThaliTest[496:706600] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 17:18:14.160 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening
,2016-02-02 17:18:14.160 ThaliTest[496:706600] THEMultipeerManager stopping peer
,2016-02-02 17:18:14.161 ThaliTest[496:706600] multipeer manager: stop client timer
2016-02-02 17:18:14.162 ThaliTest[496:706600] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 17:18:15.183 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 17:18:15.183 ThaliTest[496:706600] server: starting 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:18:15.184 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
2016-02-02 17:18:15.185 ThaliTest[496:706600] THEMultipeerManager initialized peer 7548CBFA-E4A4-4015-A6EA-FADE5525928F:5
,2016-02-02 17:18:15.185 ThaliTest[496:706600] jxcore: startUpdateAdvertisingAndListening: success
,ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 17:18:15.198 ThaliTest[496:706600] jxcore: startListeningForAdvertisements
,2016-02-02 17:18:15.201 ThaliTest[496:706600] multipeer manager: stop client timer
,2016-02-02 17:18:15.203 ThaliTest[496:706600] multipeer manager: start client restart timer: 0x16daece0
,2016-02-02 17:18:15.205 ThaliTest[496:706600] jxcore: startListeningForAdvertisements: success
,ok 41 Can call startListeningForAdvertisements without error

,2016-02-02 17:18:16.047 ThaliTest[496:706349] client: found new peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:4
2016-02-02 17:18:16.052 ThaliTest[496:706600] jxcore: connect CC82672F-8CE5-4BAD-9985-B96C116558BE:4
,2016-02-02 17:18:16.052 ThaliTest[496:706600] client: server will connect
,2016-02-02 17:18:16.053 ThaliTest[496:706600] client session: reverseConnect
,2016-02-02 17:18:16.053 ThaliTest[496:706600] client session: stateChange:0->1 CC82672F-8CE5-4BAD-9985-B96C116558BE:4
,2016-02-02 17:18:16.232 ThaliTest[496:706349] multipeer session: reset timer
,2016-02-02 17:18:16.233 ThaliTest[496:706349] server: rejecting invitation from CC82672F-8CE5-4BAD-9985-B96C116558BE due to previous generation (7548CBFA-E4A4-4015-A6EA-FADE5525928F:5 != 7548CBFA-E4A4-4015-A6EA-FADE5525928F:4)
,2016-02-02 17:18:16.305 ThaliTest[496:707052] client session: not connected CC82672F-8CE5-4BAD-9985-B96C116558BE:4
,2016-02-02 17:18:16.307 ThaliTest[496:707052] client session: onLinkFailure: CC82672F-8CE5-4BAD-9985-B96C116558BE
2016-02-02 17:18:16.307 ThaliTest[496:707052] client session: disconnect
2016-02-02 17:18:16.307 ThaliTest[496:707052] client session: state,Change:1->0 CC82672F-8CE5-4BAD-9985-B96C116558BE:4
2016-02-02 17:18:16.308 ThaliTest[496:707052] client session: no connect callabck (server initiated)
,2016-02-02 17:18:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:18:35.222 ThaliTest[496:706349] client: found updated peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:18:35.224 ThaliTest[496:706600] jxcore: connect CC82672F-8CE5-4BAD-9985-B96C116558BE:5
2016-02-02 17:18:35.224 ThaliTest[496:706600] client: server will connect
2016-02-02 17:18:35.224 ThaliTest[496:706600] client session: reverseConnect
2,016-02-02 17:18:35.225 ThaliTest[496:706600] client session: stateChange:0->1 CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:18:36.342 ThaliTest[496:707147] client session: not connected CC82672F-8CE5-4BAD-9985-B96C116558BE:5
2016-02-02 17:18:36.343 ThaliTest[496:707147] client session: onLinkFailure: CC82672F-8CE5-4BAD-9985-B96C116558BE
2016-02-02 17:18:36.343 ThaliTest[496:707147] client session: disconnect
2016-02-02 17:18:36.343 ThaliTest[496:707147] client session: stateChange:1->0 CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:18:36.345 ThaliTest[496:707147] client session: no connect callabck (server initiated)
,2016-02-02 17:18:36.481 ThaliTest[496:706349] multipeer session: reset timer
,2016-02-02 17:18:36.482 ThaliTest[496:706349] server: disconnecting to refresh session (CC82672F-8CE5-4BAD-9985-B96C116558BE)
,2016-02-02 17:18:36.482 ThaliTest[496:706349] server session: connect
,2016-02-02 17:18:36.483 ThaliTest[496:706349] server session: stateChange:0->1 CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:18:36.489 ThaliTest[496:706349] server: accepting invitation CC82672F-8CE5-4BAD-9985-B96C116558BE
,2016-02-02 17:18:38.976 ThaliTest[496:707147] server session: connected
,2016-02-02 17:18:38.976 ThaliTest[496:707147] server session: stateChange:1->2 CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:18:38.993 ThaliTest[496:706349] server relay: socket disconnected
,2016-02-02 17:18:38.993 ThaliTest[496:706349] server relay: 0x19f5ab50 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 17:18:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:18:55.219 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:19:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:19:15.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:19:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:19:35.217 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:19:41.528 ThaliTest[496:707342] server session: not connected CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:19:55.205 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:19:55.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:20:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:20:15.219 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:20:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:20:35.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:20:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:20:55.218 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:21:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:21:15.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:21:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:21:35.221 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:21:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:21:55.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:22:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:22:15.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:22:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:22:35.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:22:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:22:55.219 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:23:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:23:15.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:23:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:23:35.221 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:23:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:23:55.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:24:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:24:15.221 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:24:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:24:35.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:24:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:24:55.221 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:25:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:25:15.218 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:25:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:25:35.219 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:25:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:25:55.218 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:26:15.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:26:15.218 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:26:35.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:26:35.220 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:26:55.206 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:26:55.221 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:27:15.205 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:27:15.218 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:27:35.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:27:35.205 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:27:55.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:27:55.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:28:15.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:28:15.205 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:28:35.192 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:28:35.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:28:55.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:28:55.203 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:29:15.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:29:15.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:29:35.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:29:35.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:29:55.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:29:55.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:30:15.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:30:15.205 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:30:35.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:30:35.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5
,2016-02-02 17:30:55.191 ThaliTest[496:706349] multipeer manager: restart client
,2016-02-02 17:30:55.206 ThaliTest[496:706349] client: found existing peer: CC82672F-8CE5-4BAD-9985-B96C116558BE:5

```
