#### Test 58752353dc32d9f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/07446EC5-50A4-4EF1-8C8C-93B3024BBDD8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/07446EC5-50A4-4EF1-8C8C-93B3024BBDD8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58752353dc32d9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54338"
,(lldb)     command script import "/tmp/07446EC5-50A4-4EF1-8C8C-93B3024BBDD8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-10 15:10:27.153 ThaliTest[1459:1970177] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/10FE2398-3268-4E35-A2AE-FF4DF1676CC5/Library/Cookies/Cookies.binarycookies
,2016-02-10 15:10:27.481 ThaliTest[1459:1970177] Apache Cordova native platform version 4.0.1 is starting.
,2016-02-10 15:10:27.482 ThaliTest[1459:1970177] Multi-tasking -> Device: YES, App: YES
,2016-02-10 15:10:27.496 ThaliTest[1459:1970177] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-10 15:10:29.433 ThaliTest[1459:1970177] Using UIWebView
,2016-02-10 15:10:29.439 ThaliTest[1459:1970177] [CDVTimer][handleopenurl] 0.391006ms
,2016-02-10 15:10:29.446 ThaliTest[1459:1970177] [CDVTimer][intentandnavigationfilter] 6.652951ms
2016-02-10 15:10:29.447 ThaliTest[1459:1970177] [CDVTimer][gesturehandler] 0.313997ms
,2016-02-10 15:10:29.447 ThaliTest[1459:1970177] [CDVTimer][TotalPluginStartup] 8.889019ms
,2016-02-10 15:10:37.095 ThaliTest[1459:1970177] Resetting plugins due to page load.
,2016-02-10 15:10:40.835 ThaliTest[1459:1970177] Finished load of: file:///var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/index.html
,2016-02-10 15:10:41.063 ThaliTest[1459:1970177] JXcore Cordova plugin initializing
2016-02-10 15:10:41.064 ThaliTest[1459:1970601] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/42A1B6AB-190F-4844-9DAE-6252E55A5CAC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded
,
,appEnteringBackground wasn't registered

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

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# #start should fail if called twice in a row

,# teardown

,ok 54 specific error should be received

,# setup

,# #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 55 specific error should be returned

,# setup

,# should be able to call #stopListeningForAdvertisements many times

,# teardown

,ok 56 error should be null

,ok 57 error should be null

,# setup

,# should be able to call #startListeningForAdvertisements many times

,# teardown

,ok 58 error should be null

,ok 59 error should be null

,# setup

,# should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,ok 60 error should be null

,ok 61 error should be null

,# setup

,# #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 62 specific error should be returned

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-10 15:15:47.378 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.393 ThaliTest[1459:1970601] server: starting 1455113747378.1459.sY3e4A==
,2016-02-10 15:15:47.395 ThaliTest[1459:1970601] multipeer session: start timer: 0x1903c1d0
2016-02-10 15:15:47.396 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747378.1459
2016-02-10 15:15:47.396 ThaliTest[1459:1970601] jxcore: sta,rtBroadcasting: success
ok 63 Should be able to call startBroadcasting without error

2016-02-10 15:15:47.399 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.399 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:47.399 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.400 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

2016-02-10 15:15:47.403 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.409 ThaliTest[1459:1970601] server: starting 1455113747403.1459.lpy8DQ==
,2016-02-10 15:15:47.410 ThaliTest[1459:1970601] multipeer session: start timer: 0x18334d30
2016-02-10 15:15:47.411 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747403.1459
2016-02-10 15:15:47.412 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error

2016-02-10 15:15:47.415 ThaliTest[1459:1970601] jxcore: stopBroadcasting
2016-02-10 15:15:47.415 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:47.416 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.416 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 66 Should be able to call stopBroadcasting without error

2016-02-10 15:15:47.419 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.424 ThaliTest[1459:1970601] server: starting 1455113747419.1459.+1Mnmg==
2016-02-10 15:15:47.425 ThaliTest[1459:1970601] multipeer session: start timer: 0x194e8030
2016-02-10 15:15:47.425 ThaliTest[1459:1970601] THEMultipeerSession in,itialized peer 1455113747419.1459
2016-02-10 15:15:47.426 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

2016-02-10 15:15:47.428 ThaliTest[1459:1970601] jxcore: stopBroadcasting
2016-02-10 15:15:47.429 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:47.429 ThaliTest[1,459:1970601] multipeer session: stop timer
2016-02-10 15:15:47.429 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.433 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.438 ThaliTest[1459:1970601] server: starting 1455113747431.1459.78ObLA==
2016-02-10 15:15:47.439 ThaliTest[1459:1970601] multipeer session: start timer: 0x194e8120
2016-02-10 15:15:47.439 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747431.1459
,2016-02-10 15:15:47.439 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
ok 69 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.443 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.444 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:47.445 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.445 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

2016-02-10 15:15:47.450 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.455 ThaliTest[1459:1970601] server: starting 1455113747449.1459.NA5cGQ==
,2016-02-10 15:15:47.456 ThaliTest[1459:1970601] multipeer session: start timer: 0x18334180
,2016-02-10 15:15:47.460 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747449.1459
2016-02-10 15:15:47.460 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.463 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.464 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.465 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.468 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.470 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.472 ThaliTest[1459:1970601] server: starting 1455113747469.1459.B91org==
,2016-02-10 15:15:47.474 ThaliTest[1459:1970601] multipeer session: start timer: 0x194e7ce0
,2016-02-10 15:15:47.475 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747469.1459
,2016-02-10 15:15:47.477 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.480 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.480 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.481 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.482 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.486 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.488 ThaliTest[1459:1970601] server: starting 1455113747485.1459.I2iTtQ==
,2016-02-10 15:15:47.490 ThaliTest[1459:1970601] multipeer session: start timer: 0x190e24d0
,2016-02-10 15:15:47.492 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747485.1459
,2016-02-10 15:15:47.494 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.496 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.496 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.497 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.499 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.501 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.503 ThaliTest[1459:1970601] server: starting 1455113747501.1459.bloH0Q==
,2016-02-10 15:15:47.505 ThaliTest[1459:1970601] multipeer session: start timer: 0x194e9d30
,2016-02-10 15:15:47.506 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747501.1459
,2016-02-10 15:15:47.507 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.510 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.511 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.512 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.514 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.516 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.518 ThaliTest[1459:1970601] server: starting 1455113747516.1459.amqzbQ==
,2016-02-10 15:15:47.520 ThaliTest[1459:1970601] multipeer session: start timer: 0x190e2220
,2016-02-10 15:15:47.522 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747516.1459
,2016-02-10 15:15:47.522 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.526 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.527 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.527 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.529 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-10 15:15:47.532 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.534 ThaliTest[1459:1970601] server: starting 1455113747531.1459.mQr5PA==
,2016-02-10 15:15:47.535 ThaliTest[1459:1970601] multipeer session: start timer: 0x190e1c90
,2016-02-10 15:15:47.537 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747531.1459
,2016-02-10 15:15:47.538 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-10 15:15:47.541 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.542 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.542 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.544 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-10 15:15:47.864 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:47.868 ThaliTest[1459:1970601] server: starting 1455113747864.1459.Jueq3Q==
,2016-02-10 15:15:47.868 ThaliTest[1459:1970601] multipeer session: start timer: 0x194eb8e0
,2016-02-10 15:15:47.869 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113747864.1459
,2016-02-10 15:15:47.871 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

2016-02-10 15:15:47.874 ThaliTest[1459:1970601] jxcore: startBroadcasting
2016-02-10 15:15:47.875 ThaliTest[1459:1970601] jxcore: startBroadcasting: failure
,ok 84 Cannot call startBroadcasting twice

,2016-02-10 15:15:47.879 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:47.880 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:47.880 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:47.882 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-10 15:15:49.941 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:49.945 ThaliTest[1459:1970601] server: starting 1455113749941.1459.5ES6Yw==
,2016-02-10 15:15:49.945 ThaliTest[1459:1970601] multipeer session: start timer: 0x194eef40
,2016-02-10 15:15:49.946 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113749941.1459
2016-02-10 15:15:49.946 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 86 Should be able to call startBroadcasting without error

2016-02-10 15:15:49.949 ThaliTest[1459:1970601] jxcore: connect foobar
2016-02-10 15:15:49.950 ThaliTest[1459:1970601] client: unknown peer foobar
2016-02-10 15:15:49.950 ThaliTest[1459:1970601] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-10 15:15:49.954 ThaliTest[1459:1970601] jxcore: stopBroadcasting
2016-02-10 15:15:49.954 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:49.954 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:49.955 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-10 15:15:50.919 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:50.922 ThaliTest[1459:1970601] server: starting 1455113750918.1459.ziRj1A==
,2016-02-10 15:15:50.923 ThaliTest[1459:1970601] multipeer session: start timer: 0x194f1ec0
,2016-02-10 15:15:50.923 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113750918.1459
2016-02-10 15:15:50.924 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

,2016-02-10 15:15:50.927 ThaliTest[1459:1970601] jxcore: disconnect
2016-02-10 15:15:50.927 ThaliTest[1459:1970601] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-10 15:15:50.933 ThaliTest[1459:1970601] jxcore: stopBroadcasting
2016-02-10 15:15:50.933 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:15:50.933 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:50.934 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-10 15:15:51.421 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:51.424 ThaliTest[1459:1970601] server: starting 1455113751420.1459.34QzYA==
,2016-02-10 15:15:51.427 ThaliTest[1459:1970601] multipeer session: start timer: 0x194f45e0
,2016-02-10 15:15:51.432 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113751420.1459
,2016-02-10 15:15:51.434 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-10 15:15:52.618 ThaliTest[1459:1970177] client: found peer: 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:52.621 ThaliTest[1459:1970601] jxcore: connect 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:52.622 ThaliTest[1459:1970601] client session: connect
,2016-02-10 15:15:52.622 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:53.138 ThaliTest[1459:1970177] multipeer session: reset timer
,2016-02-10 15:15:53.139 ThaliTest[1459:1970177] multipeer session: stop timer
2016-02-10 15:15:53.139 ThaliTest[1459:1970177] multipeer session: start timer: 0x194f45e0
,2016-02-10 15:15:53.140 ThaliTest[1459:1970177] server session: connect
2016-02-10 15:15:53.140 ThaliTest[1459:1970177] server session: stateChange:0->1 1455113748407.1768
,2016-02-10 15:15:53.147 ThaliTest[1459:1970177] server: accepting invitation 1455113748407.1768
,2016-02-10 15:15:55.813 ThaliTest[1459:1971299] server session: connected
,2016-02-10 15:15:55.814 ThaliTest[1459:1971299] server session: stateChange:1->2 1455113748407.1768
,2016-02-10 15:15:55.820 ThaliTest[1459:1970177] server relay: socket disconnected
,2016-02-10 15:15:55.821 ThaliTest[1459:1970177] server relay: 0x190eb1c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-10 15:15:55.873 ThaliTest[1459:1971299] server session: not connected 1455113748407.1768
,2016-02-10 15:15:56.101 ThaliTest[1459:1971299] client session: connected
2016-02-10 15:15:56.101 ThaliTest[1459:1971299] client session: stateChange:1->2 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:56.119 ThaliTest[1459:1971294] client session: fireConnectCallback: 1455113748407.1768.ybCI6g==
2016-02-10 15:15:56.119 ThaliTest[1459:1971294] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-10 15:15:56.124 ThaliTest[1459:1970601] jxcore: disconnect
,2016-02-10 15:15:56.125 ThaliTest[1459:1970601] client session: disconnectFromPeer: 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:56.125 ThaliTest[1459:1970601] client session: disconnect
,2016-02-10 15:15:56.126 ThaliTest[1459:1970601] client session: stateChange:2->0 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:56.199 ThaliTest[1459:1970601] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-10 15:15:56.685 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:15:56.686 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
2016-02-10 15:15:56.686 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:15:56.687 ThaliTest[1459:1970601] server session: disconnect
2016-02-10 15:15:56.687 ThaliTest[1459:1970601] server session: stateChange:2->0 1455113748407.1768
,2016-02-10 15:15:56.690 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-10 15:15:57.829 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:15:57.832 ThaliTest[1459:1970601] server: starting 1455113757828.1459.fF+coQ==
,2016-02-10 15:15:57.833 ThaliTest[1459:1970601] multipeer session: start timer: 0x1943ac70
2016-02-10 15:15:57.834 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113757828.1459
2016-02-10 15:15:57.834 ThaliTest[1459:1970601] jxcore: sta,rtBroadcasting: success
ok 96 Should be able to call startBroadcasting without error

,2016-02-10 15:15:58.415 ThaliTest[1459:1970177] client: found peer: 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:58.417 ThaliTest[1459:1970601] jxcore: connect 1455113748407.1768.ybCI6g==
2016-02-10 15:15:58.418 ThaliTest[1459:1970601] client session: connect
2016-02-10 15:15:58.418 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113748407.1768.ybCI6g==
,2016-02-10 15:15:58.545 ThaliTest[1459:1970177] client: found peer: 1455113754486.1768.FWj1Sg==
,2016-02-10 15:15:58.546 ThaliTest[1459:1970601] jxcore: connect 1455113754486.1768.FWj1Sg==
2016-02-10 15:15:58.547 ThaliTest[1459:1970601] client session: connect
2016-02-10 15:15:58.547 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113754486.1768.FWj1Sg==
,2016-02-10 15:15:59.962 ThaliTest[1459:1970177] multipeer session: reset timer
2016-02-10 15:15:59.962 ThaliTest[1459:1970177] multipeer session: stop timer
2016-02-10 15:15:59.962 ThaliTest[1459:1970177] multipeer session: start timer: 0x1943ac70
2016-02-10 15:15:59.963 ThaliTest[1459:1970177] server session: connect
,2016-02-10 15:15:59.963 ThaliTest[1459:1970177] server session: stateChange:0->1 1455113754486.1768
,2016-02-10 15:15:59.970 ThaliTest[1459:1970177] server: accepting invitation 1455113754486.1768
,2016-02-10 15:16:02.322 ThaliTest[1459:1971294] client session: connected
2016-02-10 15:16:02.322 ThaliTest[1459:1971294] client session: stateChange:1->2 1455113754486.1768.FWj1Sg==
,2016-02-10 15:16:02.327 ThaliTest[1459:1971294] client session: fireConnectCallback: 1455113754486.1768.FWj1Sg==
2016-02-10 15:16:02.327 ThaliTest[1459:1971294] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-10 15:16:02.333 ThaliTest[1459:1970601] jxcore: connect 1455113754486.1768.FWj1Sg==
,2016-02-10 15:16:02.333 ThaliTest[1459:1970601] client: already connect(ing/ed) to 1455113754486.1768.FWj1Sg==
,2016-02-10 15:16:02.334 ThaliTest[1459:1970601] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-10 15:16:02.337 ThaliTest[1459:1970601] jxcore: disconnect
,2016-02-10 15:16:02.338 ThaliTest[1459:1970601] client session: disconnectFromPeer: 1455113754486.1768.FWj1Sg==
,2016-02-10 15:16:02.338 ThaliTest[1459:1970601] client session: disconnect
,2016-02-10 15:16:02.339 ThaliTest[1459:1970601] client session: stateChange:2->0 1455113754486.1768.FWj1Sg==
,2016-02-10 15:16:02.413 ThaliTest[1459:1970601] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-10 15:16:02.579 ThaliTest[1459:1971299] server session: connected
2016-02-10 15:16:02.580 ThaliTest[1459:1971299] server session: stateChange:1->2 1455113754486.1768
,2016-02-10 15:16:02.585 ThaliTest[1459:1970177] server relay: socket disconnected
,2016-02-10 15:16:02.586 ThaliTest[1459:1970177] server relay: 0x18530e10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-10 15:16:02.641 ThaliTest[1459:1971301] server session: not connected 1455113754486.1768
,calling stopBroadcasting

,2016-02-10 15:16:02.985 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:16:02.985 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:16:02.985 ThaliTest[1459:1970601] multipeer session: stop timer
2016-02-10 15:16:02.986 ThaliTest[1459:1970601] client session: disconnect
2016-02-10 15:16:02.987 ThaliTest[1459:1970601] client session: stateChange:1->0 1455113748407.1768.ybCI6g==
,2016-02-10 15:16:02.987 ThaliTest[1459:1970601] server session: disconnect
2016-02-10 15:16:02.988 ThaliTest[1459:1970601] server session: stateChange:2->0 1455113754486.1768
,2016-02-10 15:16:02.992 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-10 15:16:03.602 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:16:03.606 ThaliTest[1459:1970601] server: starting 1455113763602.1459.TGadlQ==
,2016-02-10 15:16:03.607 ThaliTest[1459:1970601] multipeer session: start timer: 0x18530ff0
2016-02-10 15:16:03.607 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113763602.1459
2016-02-10 15:16:03.608 ThaliTest[1459:1970601] jxcore: sta,rtBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-10 15:16:04.783 ThaliTest[1459:1970177] client: found peer: 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:04.785 ThaliTest[1459:1970601] jxcore: connect 1455113760477.1768.tuq5kg==
2016-02-10 15:16:04.785 ThaliTest[1459:1970601] client session: connect
2016-02-10 15:16:04.785 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:04.915 ThaliTest[1459:1970177] multipeer session: reset timer
2016-02-10 15:16:04.916 ThaliTest[1459:1970177] multipeer session: stop timer
,2016-02-10 15:16:04.916 ThaliTest[1459:1970177] multipeer session: start timer: 0x18530ff0
,2016-02-10 15:16:04.917 ThaliTest[1459:1970177] server session: connect
2016-02-10 15:16:04.917 ThaliTest[1459:1970177] server session: stateChange:0->1 1455113760477.1768
,2016-02-10 15:16:04.923 ThaliTest[1459:1970177] server: accepting invitation 1455113760477.1768
,2016-02-10 15:16:07.432 ThaliTest[1459:1971298] server session: connected
,2016-02-10 15:16:07.432 ThaliTest[1459:1971298] server session: stateChange:1->2 1455113760477.1768
,2016-02-10 15:16:07.459 ThaliTest[1459:1970177] server relay: socket disconnected
,2016-02-10 15:16:07.460 ThaliTest[1459:1970177] server relay: 0x190f1080 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-10 15:16:07.484 ThaliTest[1459:1971298] client session: connected
2016-02-10 15:16:07.484 ThaliTest[1459:1971298] client session: stateChange:1->2 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:07.502 ThaliTest[1459:1971294] server session: not connected 1455113760477.1768
,2016-02-10 15:16:07.504 ThaliTest[1459:1971299] client session: fireConnectCallback: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:07.504 ThaliTest[1459:1971299] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-10 15:16:07.508 ThaliTest[1459:1970601] jxcore: disconnect
2016-02-10 15:16:07.508 ThaliTest[1459:1970601] client session: disconnectFromPeer: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:07.508 ThaliTest[1459:1970601] client session: disconnect
2016-02-10 15:16:07.508 ThaliTest[1459:1970601] client session: stateChange:2->0 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:07.515 ThaliTest[1459:1970601] jxcore: disconnect: success
ok 104 Should be able to disconnect without error

2016-02-10 15:16:07.517 ThaliTest[1459:1970601] jxcore: disconnect
,2016-02-10 15:16:07.518 ThaliTest[1459:1970601] jxcore: disconnect: fail
ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-10 15:16:08.763 ThaliTest[1459:1970601] jxcore: stopBroadcasting
,2016-02-10 15:16:08.764 ThaliTest[1459:1970601] THEMultipeerSession stopping peer
,2016-02-10 15:16:08.765 ThaliTest[1459:1970601] multipeer session: stop timer
,2016-02-10 15:16:08.766 ThaliTest[1459:1970601] server session: disconnect
2016-02-10 15:16:08.766 ThaliTest[1459:1970601] server session: stateChange:2->0 1455113760477.1768
2016-02-10 15:16:08.767 ThaliTest[1459:1970601] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 57523

,2016-02-10 15:16:11.327 ThaliTest[1459:1970601] jxcore: startBroadcasting
,2016-02-10 15:16:11.328 ThaliTest[1459:1970601] server: starting 1455113771326.1459.gBubyg==
,2016-02-10 15:16:11.328 ThaliTest[1459:1970601] multipeer session: start timer: 0x1949de30
2016-02-10 15:16:11.328 ThaliTest[1459:1970601] THEMultipeerSession initialized peer 1455113771326.1459
2016-02-10 15:16:11.328 ThaliTest[1459:1970601] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-10 15:16:11.333 ThaliTest[1459:1970177] client: found peer: 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:11.333 ThaliTest[1459:1970601] jxcore: connect 1455113760477.1768.tuq5kg==
2016-02-10 15:16:11.334 ThaliTest[1459:1970601] client session: connect
2016-02-10 15:16:11.334 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:12.613 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:12.614 ThaliTest[1459:1970601] jxcore: connect 1455113768332.1768.7T5mUA==
2016-02-10 15:16:12.614 ThaliTest[1459:1970601] client session: connect
2016-02-10 15:16:12.615 ThaliTest[1459:1970601] client session: stateChange:0->1 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:13.816 ThaliTest[1459:1970177] multipeer session: reset timer
,2016-02-10 15:16:13.816 ThaliTest[1459:1970177] multipeer session: stop timer
,2016-02-10 15:16:13.817 ThaliTest[1459:1970177] multipeer session: start timer: 0x1949de30
2016-02-10 15:16:13.817 ThaliTest[1459:1970177] server session: connect
2016-02-10 15:16:13.817 ThaliTest[1459:1970177] server session: stateChange:0->1 1455113768,332.1768
,2016-02-10 15:16:13.826 ThaliTest[1459:1970177] server: accepting invitation 1455113768332.1768
,2016-02-10 15:16:18.088 ThaliTest[1459:1971294] client session: connected
2016-02-10 15:16:18.088 ThaliTest[1459:1971294] client session: stateChange:1->2 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:18.114 ThaliTest[1459:1971294] client session: fireConnectCallback: 1455113768332.1768.7T5mUA==
2016-02-10 15:16:18.114 ThaliTest[1459:1971294] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-10 15:16:18.120 ThaliTest[1459:1970177] client: relay established
2016-02-10 15:16:18.121 ThaliTest[1459:1970177] client: new accepted socket: 0x1918bca0
,2016-02-10 15:16:18.194 ThaliTest[1459:1971344] server session: connected
2016-02-10 15:16:18.195 ThaliTest[1459:1971344] server session: stateChange:1->2 1455113768332.1768
,2016-02-10 15:16:18.513 ThaliTest[1459:1970177] server relay: connected (to port: 57523)
,2016-02-10 15:16:26.612 ThaliTest[1459:1970177] client: lost peer: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:26.613 ThaliTest[1459:1970177] client session: onPeerLost: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:26.613 ThaliTest[1459:1970177] client ,session: onLinkFailure: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:26.613 ThaliTest[1459:1970177] client session: disconnect
2016-02-10 15:16:26.613 ThaliTest[1459:1970177] client session: stateChange:1->0 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:26.614 ThaliTest[1459:1970177] client session: fireConnectCallback: 1455113760477.1768.tuq5kg==
2016-02-10 15:16:26.614 ThaliTest[1459:1970177] jxcore: connect: fail: Peer disconnected
,2016-02-10 15:16:27.630 ThaliTest[1459:1970601] jxcore: connect 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:27.630 ThaliTest[1459:1970601] client: connect: unreachable 1455113760477.1768.tuq5kg==
,2016-02-10 15:16:27.631 ThaliTest[1459:1970601] jxcore: connect: fail: Peer unreachable
,data in 1095

,data in 2190

,data in 3285

,2016-02-10 15:16:29.805 ThaliTest[1459:1971298] client session: not connected 1455113768332.1768.7T5mUA==
2016-02-10 15:16:29.806 ThaliTest[1459:1971298] client session: onLinkFailure: 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:29.806 ThaliTest[1459:1971298] client session: disconnect
2016-02-10 15:16:29.806 ThaliTest[1459:1971298] client session: stateChange:2->0 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:29.809 ThaliTest[1459:1971298] client session: fireConnectionErrorEvent: 1455113768332.1768.7T5mUA==
,2016-02-10 15:16:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:16:43.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:17:05.835 ThaliTest[1459:1971526] server session: not connected 1455113768332.1768
,2016-02-10 15:17:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:17:13.844 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:17:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:18:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:18:13.840 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:18:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:18:43.844 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:19:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:19:13.845 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:19:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:19:43.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:20:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:20:13.842 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:20:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:21:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:21:13.841 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:21:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:21:43.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:22:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:22:13.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:22:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:22:43.840 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:23:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:23:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:23:43.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:24:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:24:13.842 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:24:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:24:43.843 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:25:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:25:13.842 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:25:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:25:43.841 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:26:13.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:26:13.844 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:26:43.818 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:26:43.844 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:27:13.816 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:27:13.842 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:27:43.804 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:27:43.829 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==
,2016-02-10 15:28:13.804 ThaliTest[1459:1970177] multipeer session: restart
,2016-02-10 15:28:13.826 ThaliTest[1459:1970177] client: found peer: 1455113768332.1768.7T5mUA==

```
