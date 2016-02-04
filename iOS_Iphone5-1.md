#### Test 58259810381ca4f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/CD4BF3D7-7A14-42DC-AF89-5DEA1142D0C2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CD4BF3D7-7A14-42DC-AF89-5DEA1142D0C2/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58259810381ca4f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49860"
,(lldb)     command script import "/tmp/CD4BF3D7-7A14-42DC-AF89-5DEA1142D0C2/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 10:39:39.527 ThaliTest[2519:7778143] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/98E3CAFC-65C3-4645-8D86-EE50DFEA3B6A/Library/Cookies/Cookies.binarycookies
,2016-02-04 10:39:39.670 ThaliTest[2519:7778143] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 10:39:39.673 ThaliTest[2519:7778143] Multi-tasking -> Device: YES, App: YES
,2016-02-04 10:39:39.678 ThaliTest[2519:7778143] Unlimited access to network resources
,2016-02-04 10:39:39.692 ThaliTest[2519:7778143] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 10:39:50.391 ThaliTest[2519:7778143] Resetting plugins due to page load.
,2016-02-04 10:39:54.791 ThaliTest[2519:7778143] Finished load of: file:///var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/index.html
,2016-02-04 10:39:55.006 ThaliTest[2519:7778143] JXcore Cordova plugin initializing
2016-02-04 10:39:55.007 ThaliTest[2519:7778417] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CA8B62A2-6563-4290-A20E-DE7ACF5D6D14/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

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

ok 26 should be equal

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

ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-04 10:48:35.354 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.363 ThaliTest[2519:7778417] server: starting 1454579315354.2519.sRd3/Q==
,2016-02-04 10:48:35.364 ThaliTest[2519:7778417] multipeer session: start timer: 0x1dad0e60
,2016-02-04 10:48:35.364 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315354.2519
,2016-02-04 10:48:35.365 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.367 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:48:35.367 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.367 ThaliTest[2,519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.368 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-04 10:48:35.369 ThaliTest[2519:7778417] jxcore: startBroad,casting
,2016-02-04 10:48:35.375 ThaliTest[2519:7778417] server: starting 1454579315369.2519.Q/b9oA==
2016-02-04 10:48:35.376 ThaliTest[2519:7778417] multipeer session: start timer: 0x1dae0330
2016-02-04 10:48:35.376 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579315369.2519
2016-02-04 10:48:35.377 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.378 ThaliTest[2519:7778417] jxcore: stopBroadcasting,
2016-02-04 10:48:35.378 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.378 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.378 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 57 Shou,ld be able to call stopBroadcasting without error

2016-02-04 10:48:35.380 ThaliTest[2519:7778417] jxcore: startBroadcasting
2016-02-04 10:48:35.383 ThaliTest[2519:7778417] server: starting 1454579315379.2519.A/Dedg==
,2016-02-04 10:48:35.386 ThaliTest[2519:7778417] multipeer session: start timer: 0x1dadfc10
2016-02-04 10:48:35.390 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315379.2519
2016-02-04 10:48:35.390 ThaliTest[2519:7778417] jxcore: sta,rtBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.393 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:48:35.393 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04, 10:48:35.393 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.393 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-04 10:48:35.395 ThaliTest[2519:77,78417] jxcore: startBroadcasting
2016-02-04 10:48:35.399 ThaliTest[2519:7778417] server: starting 1454579315395.2519.xXFXTA==
2016-02-04 10:48:35.399 ThaliTest[2519:7778417] multipeer session: start timer: 0x1daef8d0
2016-02-04 10:48:35.400 ThaliTest[25,19:7778417] THEMultipeerSession initialized peer 1454579315395.2519
2016-02-04 10:48:35.412 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.414 ThaliTest[2519:,7778417] jxcore: stopBroadcasting
2016-02-04 10:48:35.415 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.415 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.415 ThaliTest[2519:7778417] jxcore: sto,pBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

2016-02-04 10:48:35.417 ThaliTest[2519:7778417] jxcore: startBroadcasting
2016-02-04 10:48:35.422 ThaliTest[2519:7778417] server: starting 1454579315416.2519.ND+AjQ==
,2016-02-04 10:48:35.423 ThaliTest[2519:7778417] multipeer session: start timer: 0x1daeee00
2016-02-04 10:48:35.424 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315416.2519
2016-02-04 10:48:35.424 ThaliTest[2519:7778417] jxcore: sta,rtBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-04 10:48:35.435 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:48:35.438 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.439 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.,440 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-02-04 10:48:35.442 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.449 ThaliTest[2519:7778417] server: starting 1454579315441.2519.22Vzpw==
2016-02-04 10:48:35.450 ThaliTest[2519:7778417] multipeer session: start timer: 0x1daf0c00
2016-02-04 10:48:35.450 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579315441.2519
2016-02-04 10:48:35.450 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.452 ThaliTest[2519:7778417] jxcore: stopBroadcasting,
2016-02-04 10:48:35.452 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.453 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:35.453 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 65 Shou,ld be able to call stopBroadcasting without error

2016-02-04 10:48:35.455 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.459 ThaliTest[2519:7778417] server: starting 1454579315454.2519.TLm6gA==
2016-02-04 10:48:35.460 ThaliTest[2519:7778417] multipeer session: start timer: 0x1daee580
2016-02-04 10:48:35.461 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579315454.2519
2016-02-04 10:48:35.461 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

2016-02-04 10:48:35.464 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:48:35.464 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:48:35.464 ThaliTest[2519:7778417] multipeer session: stop timer
,2016-02-04 10:48:35.467 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error

2016-02-04 10:48:35.468 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.480 ThaliTest[2519:7778417] server: starting 1454579315468.2519.cXSasA==
,2016-02-04 10:48:35.494 ThaliTest[2519:7778417] multipeer session: start timer: 0x1cc99d10
,2016-02-04 10:48:35.496 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315468.2519
,2016-02-04 10:48:35.501 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,
,2016-02-04 10:48:35.505 ThaliTest[2519:7778417] jxcore: stopBroadcasting
,2016-02-04 10:48:35.507 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
,2016-02-04 10:48:35.507 ThaliTest[2519:7778417] multipeer session: stop timer
,2016-02-04 10:48:35.508 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error
,
,2016-02-04 10:48:35.514 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.516 ThaliTest[2519:7778417] server: starting 1454579315513.2519.pY3ksA==
,2016-02-04 10:48:35.519 ThaliTest[2519:7778417] multipeer session: start timer: 0x1dae5ee0
,2016-02-04 10:48:35.522 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315513.2519
,2016-02-04 10:48:35.526 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error
,
,2016-02-04 10:48:35.530 ThaliTest[2519:7778417] jxcore: stopBroadcasting
,2016-02-04 10:48:35.530 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
,2016-02-04 10:48:35.531 ThaliTest[2519:7778417] multipeer session: stop timer
,2016-02-04 10:48:35.532 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error
,
,2016-02-04 10:48:35.537 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:35.540 ThaliTest[2519:7778417] server: starting 1454579315537.2519.yVPFng==
,2016-02-04 10:48:35.546 ThaliTest[2519:7778417] multipeer session: start timer: 0x1ce9d910
,2016-02-04 10:48:35.548 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579315537.2519
,2016-02-04 10:48:35.550 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-04 10:48:35.553 ThaliTest[2519:7778417] jxcore: stopBroadcasting
,2016-02-04 10:48:35.553 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
,2016-02-04 10:48:35.554 ThaliTest[2519:7778417] multipeer session: stop timer
,2016-02-04 10:48:35.556 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-04 10:48:53.981 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:48:53.983 ThaliTest[2519:7778417] server: starting 1454579333980.2519.MyoXIg==
2016-02-04 10:48:53.984 ThaliTest[2519:7778417] multipeer session: start timer: 0x1ce199d0
2016-02-04 10:48:53.984 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579333980.2519
2016-02-04 10:48:53.984 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-04 10:48:53.986 ThaliTest[2519:7778417] jxcore: startBroadcasting,
2016-02-04 10:48:53.986 ThaliTest[2519:7778417] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

2016-02-04 10:48:53.988 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:48:53.988 ThaliTest[2519:7778417] THE,MultipeerSession stopping peer
2016-02-04 10:48:53.988 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:48:53.988 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-04 10:49:07.848 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:49:07.851 ThaliTest[2519:7778417] server: starting 1454579347848.2519.zIJjdw==
2016-02-04 10:49:07.851 ThaliTest[2519:7778417] multipeer session: start timer: 0x1daf79d0
2016-02-04 10:49:07.851 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579347848.2519
2016-02-04 10:49:07.851 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-04 10:49:07.853 ThaliTest[2519:7778417] jxcore: connect foobar
2,016-02-04 10:49:07.853 ThaliTest[2519:7778417] client: unknown peer foobar
2016-02-04 10:49:07.853 ThaliTest[2519:7778417] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-02-04 10:49:07.855 ThaliTest[2519:7778417] jxcor,e: stopBroadcasting
2016-02-04 10:49:07.855 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:49:07.856 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:49:07.856 ThaliTest[2519:7778417] jxcore: stopBroadcasting:, success
,ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-04 10:49:21.558 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:49:21.560 ThaliTest[2519:7778417] server: starting 1454579361557.2519.S0Dezw==
2016-02-04 10:49:21.560 ThaliTest[2519:7778417] multipeer session: start timer: 0x16d27450
2016-02-04 10:49:21.561 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579361557.2519
2016-02-04 10:49:21.561 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-04 10:49:21.562 ThaliTest[2519:7778417] jxcore: disconnect
2016-,02-04 10:49:21.562 ThaliTest[2519:7778417] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

2016-02-04 10:49:21.564 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:49:21.564 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
,2016-02-04 10:49:21.565 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:49:21.565 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-04 10:49:21.869 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:49:21.872 ThaliTest[2519:7778417] server: starting 1454579361869.2519.Nr3MYw==
2016-02-04 10:49:21.872 ThaliTest[2519:7778417] multipeer session: start timer: 0x1ca9e060
2016-02-04 10:49:21.872 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579361869.2519
2016-02-04 10:49:21.872 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-04 10:49:22.689 ThaliTest[2519:7778143] client: found peer: 1454579364296.626.kKhhAw==
2016-02-04 10:49:22.691 ThaliTest[2519:7778417] jxcore: connect 1454579364296.626.kKhhAw==
2016-02-04 10:49:22.691 ThaliTest[2519:7778417] client session: connect
,2016-02-04 10:49:22.691 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579364296.626.kKhhAw==
,2016-02-04 10:49:23.735 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:49:23.736 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:49:23.736 ThaliTest[2519:7778143] multipeer session: start timer: 0x1ca9e060
,2016-02-04 10:49:23.736 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:49:23.736 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579364296.626
,2016-02-04 10:49:23.742 ThaliTest[2519:7778143] server: accepting invitation 1454579364296.626
,2016-02-04 10:49:27.915 ThaliTest[2519:7780773] server session: connected
2016-02-04 10:49:27.915 ThaliTest[2519:7780773] server session: stateChange:1->2 1454579364296.626
,2016-02-04 10:49:27.938 ThaliTest[2519:7778143] server relay: socket disconnected
2016-02-04 10:49:27.938 ThaliTest[2519:7778143] server relay: 0x1d9b6de0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:27.976 ThaliTest[2519:7780773] server session: not connected 1454579364296.626
,2016-02-04 10:49:28.778 ThaliTest[2519:7780773] client session: connected
2016-02-04 10:49:28.780 ThaliTest[2519:7780773] client session: stateChange:1->2 1454579364296.626.kKhhAw==
,2016-02-04 10:49:28.843 ThaliTest[2519:7780811] client session: fireConnectCallback: 1454579364296.626.kKhhAw==
2016-02-04 10:49:28.844 ThaliTest[2519:7780811] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be, within range

,2016-02-04 10:49:28.847 ThaliTest[2519:7778417] jxcore: disconnect
,2016-02-04 10:49:28.847 ThaliTest[2519:7778417] client session: disconnectFromPeer: 1454579364296.626.kKhhAw==
2016-02-04 10:49:28.848 ThaliTest[2519:7778417] client session: disconnect
2016-02-04 10:49:28.848 ThaliTest[2519:7778417] client session: stateChange:2->0 1454579364296.626.kKhhAw==
,2016-02-04 10:49:28.855 ThaliTest[2519:7778417] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 10:49:29.239 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:49:29.240 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:49:29.240 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:49:29.,241 ThaliTest[2519:7778417] server session: disconnect
2016-02-04 10:49:29.241 ThaliTest[2519:7778417] server session: stateChange:2->0 1454579364296.626
,2016-02-04 10:49:29.245 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-04 10:49:33.710 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:49:33.712 ThaliTest[2519:7778417] server: starting 1454579373709.2519.veA/ug==
2016-02-04 10:49:33.713 ThaliTest[2519:7778417] multipeer session: start timer: 0x1d93f470
2016-02-04 10:49:33.713 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579373709.2519
2016-02-04 10:49:33.713 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-04 10:49:33.725 ThaliTest[2519:7778143] client: found peer: 1454579373191.626.+mjFYQ==
2016-02-04 10:49:33.726 ThaliTest[2519:7778417] jxcore: connect 1454579373191.626.+mjFYQ==
,2016-02-04 10:49:33.727 ThaliTest[2519:7778417] client session: connect
2016-02-04 10:49:33.727 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579373191.626.+mjFYQ==
,2016-02-04 10:49:35.271 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:49:35.272 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:49:35.272 ThaliTest[2519:7778143] multipeer session: start timer: 0x1d93f470
2016-02-04 10:49:35.272 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:49:35.272 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579373191.626
,2016-02-04 10:49:35.278 ThaliTest[2519:7778143] server: accepting invitation 1454579373191.626
,2016-02-04 10:49:37.288 ThaliTest[2519:7780811] client session: connected
2016-02-04 10:49:37.288 ThaliTest[2519:7780811] client session: stateChange:1->2 1454579373191.626.+mjFYQ==
,2016-02-04 10:49:37.293 ThaliTest[2519:7780775] client session: fireConnectCallback: 1454579373191.626.+mjFYQ==
2016-02-04 10:49:37.293 ThaliTest[2519:7780775] jxcore: connect: success
ok 88 Should be able to connect without error

ok 89 Port should be, within range

2016-02-04 10:49:37.295 ThaliTest[2519:7778417] jxcore: connect 1454579373191.626.+mjFYQ==
2016-02-04 10:49:37.295 ThaliTest[2519:7778417] client: already connect(ing/ed) to 1454579373191.626.+mjFYQ==
2016-02-04 10:49:37.295 ThaliTest[25,19:7778417] jxcore: connect: fail: Aleady connecting
ok 90 Should fail on double connect

2016-02-04 10:49:37.298 ThaliTest[2519:7778417] jxcore: disconnect
2016-02-04 10:49:37.298 ThaliTest[2519:7778417] client session: disconnectFromPeer: 14545793731,91.626.+mjFYQ==
2016-02-04 10:49:37.299 ThaliTest[2519:7778417] client session: disconnect
2016-02-04 10:49:37.299 ThaliTest[2519:7778417] client session: stateChange:2->0 1454579373191.626.+mjFYQ==
,2016-02-04 10:49:37.312 ThaliTest[2519:7778417] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 10:49:38.423 ThaliTest[2519:7780775] server session: connected
2016-02-04 10:49:38.424 ThaliTest[2519:7780775] server session: stateChange:1->2 1454579373191.626
,2016-02-04 10:49:38.485 ThaliTest[2519:7778143] server relay: socket disconnected
2016-02-04 10:49:38.485 ThaliTest[2519:7778143] server relay: 0x1ca397b0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:38.548 ThaliTest[2519:7780775] server session: not connected 1454579373191.626
,calling stopBroadcasting

,2016-02-04 10:49:38.624 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:49:38.625 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:49:38.625 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:49:38.,625 ThaliTest[2519:7778417] server session: disconnect
2016-02-04 10:49:38.625 ThaliTest[2519:7778417] server session: stateChange:2->0 1454579373191.626
2016-02-04 10:49:38.626 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-04 10:49:42.114 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:49:42.116 ThaliTest[2519:7778417] server: starting 1454579382114.2519.RfvuPg==
2016-02-04 10:49:42.117 ThaliTest[2519:7778417] multipeer session: start timer: 0x1cff8520
2016-02-04 10:49:42.117 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579382114.2519
2016-02-04 10:49:42.117 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-04 10:49:43.453 ThaliTest[2519:7778143] client: found peer: 1454579384548.626.aIV07A==
2016-02-04 10:49:43.454 ThaliTest[2519:7778417] jxcore: connect 1454579384548.626.aIV07A==
2016-02-04 10:49:43.455 ThaliTest[2519:7778417] client session: connect
2016-02-04 10:49:43.455 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579384548.626.aIV07A==
,2016-02-04 10:49:43.981 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:49:43.981 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:49:43.981 ThaliTest[2519:7778143] multipeer session: start timer: 0x1cff8520
2016-02-04 10:49:43.982 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:49:43.982 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579384548.626
,2016-02-04 10:49:43.988 ThaliTest[2519:7778143] server: accepting invitation 1454579384548.626
,2016-02-04 10:49:46.812 ThaliTest[2519:7780811] server session: connected
2016-02-04 10:49:46.812 ThaliTest[2519:7780811] server session: stateChange:1->2 1454579384548.626
,2016-02-04 10:49:46.816 ThaliTest[2519:7778143] server relay: socket disconnected
2016-02-04 10:49:46.816 ThaliTest[2519:7778143] server relay: 0x1cdebf30 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 10:49:46.935 ThaliTest[2519:7780773] server session: not connected 1454579384548.626
,2016-02-04 10:49:47.197 ThaliTest[2519:7780773] client session: connected
2016-02-04 10:49:47.198 ThaliTest[2519:7780773] client session: stateChange:1->2 1454579384548.626.aIV07A==
,2016-02-04 10:49:47.201 ThaliTest[2519:7780773] client session: fireConnectCallback: 1454579384548.626.aIV07A==
2016-02-04 10:49:47.202 ThaliTest[2519:7780773] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be, within range

2016-02-04 10:49:47.204 ThaliTest[2519:7778417] jxcore: disconnect
2016-02-04 10:49:47.204 ThaliTest[2519:7778417] client session: disconnectFromPeer: 1454579384548.626.aIV07A==
2016-02-04 10:49:47.204 ThaliTest[2519:7778417] client sess,ion: disconnect
2016-02-04 10:49:47.204 ThaliTest[2519:7778417] client session: stateChange:2->0 1454579384548.626.aIV07A==
,2016-02-04 10:49:47.279 ThaliTest[2519:7778417] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-04 10:49:47.282 ThaliTest[2519:7778417] jxcore: disconnect
,2016-02-04 10:49:47.282 ThaliTest[2519:7778417] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 10:49:47.587 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:49:47.588 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:49:47.588 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:49:47.,588 ThaliTest[2519:7778417] server session: disconnect
2016-02-04 10:49:47.588 ThaliTest[2519:7778417] server session: stateChange:2->0 1454579384548.626
,2016-02-04 10:49:48.537 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 63601

,2016-02-04 10:50:31.741 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:50:31.743 ThaliTest[2519:7778417] server: starting 1454579431741.2519.AkU5fw==
2016-02-04 10:50:31.744 ThaliTest[2519:7778417] multipeer session: start timer: 0x1cfa1a10
2016-02-04 10:50:31.744 ThaliTest[2519:7778417] THEMultipeerSession initialized peer 1454579431741.2519
2016-02-04 10:50:31.744 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-04 10:50:33.404 ThaliTest[2519:7778143] client: found peer: 1454579393536.626.4X3Rxg==
2016-02-04 10:50:33.405 ThaliTest[2519:7778417] jxcore: connect 1454579393536.626.4X3Rxg==
2016-02-04 10:50:33.406 ThaliTest[2519:7778417] client session: connect
2016-02-04 10:50:33.406 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579393536.626.4X3Rxg==
,2016-02-04 10:50:34.572 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:50:34.572 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:50:34.572 ThaliTest[2519:7778143] multipeer session: start timer: 0x1cfa1a10
2016-,02-04 10:50:34.573 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:50:34.573 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579393536.626
,2016-02-04 10:50:34.579 ThaliTest[2519:7778143] server: accepting invitation 1454579393536.626
,2016-02-04 10:50:37.444 ThaliTest[2519:7780953] server session: connected
2016-02-04 10:50:37.445 ThaliTest[2519:7780953] server session: stateChange:1->2 1454579393536.626
,2016-02-04 10:50:37.477 ThaliTest[2519:7778143] server relay: connected (to port: 63601)
,2016-02-04 10:50:37.530 ThaliTest[2519:7780937] client session: connected
2016-02-04 10:50:37.530 ThaliTest[2519:7780937] client session: stateChange:1->2 1454579393536.626.4X3Rxg==
,2016-02-04 10:50:37.549 ThaliTest[2519:7780937] client session: fireConnectCallback: 1454579393536.626.4X3Rxg==
2016-02-04 10:50:37.549 ThaliTest[2519:7780937] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-02-04 10:50:37.556 ThaliTest[2519:7778143] client: relay established
2016-02-04 10:50:37.556 ThaliTest[2519:7778143] client: new accepted socket: 0x1c92b590
,data in 3285
,
,data in 10950

,data in 17520

,data in 22995

,data in 28470

,data in 41610

,data in 45990

,data in 50299

,data in 57964

,data in 65700

,data in 66724

,data in 68985

,data in 70080

,data in 72270

,data in 76650

,data in 101835

,2016-02-04 10:50:38.793 ThaliTest[2519:7780937] server session: not connected 1454579393536.626
,data in 108334

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 10:50:39.762 ThaliTest[2519:7778417] jxcore: disconnect
2016-02-04 10:50:39.763 ThaliTest[2519:7778417] client session: disconnectFromPeer: 1454579393536.626.4X3Rxg==
2016-02-04 10:50:39.763 ThaliTest[2519:7778417] client session: disconnect
2016-02-04 10:50:39.763 ThaliTest[2519:7778417] client session: stateChange:2->0 1454579393536.626.4X3Rxg==
,2016-02-04 10:50:39.771 ThaliTest[2519:7778417] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,calling stopBroadcasting

,2016-02-04 10:50:55.997 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:50:55.997 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:50:55.997 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:50:55.998 ThaliTest[2519:7778417] server session: disconnect
2016-02-04 10:50:55.998 ThaliTest[2519:7778417] server session: stateChange:2->0 1454579393536.626
,2016-02-04 10:50:56.063 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 63607

,2016-02-04 10:51:06.515 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:51:06.517 ThaliTest[2519:7778417] server: starting 1454579466514.2519.fpP7ow==
2016-02-04 10:51:06.517 ThaliTest[2519:7778417] multipeer session: start timer: 0x1dbc77e0
2016-02-04 10:51:06.518 ThaliTest[2519:7778417] THEMultipeerSession in,itialized peer 1454579466514.2519
2016-02-04 10:51:06.518 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-04 10:51:06.529 ThaliTest[2519:7778143] client: found peer: 1454579458964.626.q01zJg==
[{"peerIdentifier":"1454579458964.626.q01zJg==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 10:51:06.530 ThaliTest[2519:7778417] jxcore: connect 1454579458964.626.q01zJg==
2016-02-04 10:51:06.531 ThaliTest[2519:7778417] client session: connect
2016-02-04 10:51:06.531 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579458964.626.q01zJg==
,2016-02-04 10:51:08.418 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:51:08.418 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:51:08.418 ThaliTest[2519:7778143] multipeer session: start timer: 0x1dbc77e0
2016-,02-04 10:51:08.418 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:51:08.419 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579458964.626
,2016-02-04 10:51:08.427 ThaliTest[2519:7778143] server: accepting invitation 1454579458964.626
,2016-02-04 10:51:10.797 ThaliTest[2519:7781085] client session: connected
2016-02-04 10:51:10.797 ThaliTest[2519:7781085] client session: stateChange:1->2 1454579458964.626.q01zJg==
,2016-02-04 10:51:10.863 ThaliTest[2519:7781041] client session: fireConnectCallback: 1454579458964.626.q01zJg==
2016-02-04 10:51:10.864 ThaliTest[2519:7781041] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-02-04 10:51:10.897 ThaliTest[2519:7778143] client: relay established
2016-02-04 10:51:10.899 ThaliTest[2519:7778143] client: new accepted socket: 0x1dbf23f0
,2016-02-04 10:51:11.499 ThaliTest[2519:7781041] server session: connected
,2016-02-04 10:51:11.499 ThaliTest[2519:7781041] server session: stateChange:1->2 1454579458964.626
,2016-02-04 10:51:11.503 ThaliTest[2519:7778143] server relay: connected (to port: 63607)
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-02-04 10:51:12.056 ThaliTest[2519:7778143] client: socket closed
2016-02-04 10:51:12.057 ThaliTest[2519:7778143] client relay: socket disconnected
2016-02-04 10:51:12.057 ThaliTest[2519:7778143] client relay: 0x1dbf23f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 10:51:12.057 ThaliTest[2519:7778143] client session: socket closed: 1454579458964.626.q01zJg==
2016-02-04 1,0:51:12.057 ThaliTest[2519:7778143] client session: onLinkFailure: 1454579458964.626.q01zJg==
2016-02-04 10:51:12.057 ThaliTest[2519:7778143] client session: disconnect
2016-02-04 10:51:12.058 ThaliTest[2519:7778143] client session: stateChange:2->0 1454579458964.626.q01zJg==
,2016-02-04 10:51:12.079 ThaliTest[2519:7778143] client session: fireConnectionErrorEvent: 1454579458964.626.q01zJg==
,2016-02-04 10:51:12.084 ThaliTest[2519:7778417] jxcore: connect 1454579458964.626.q01zJg==
,2016-02-04 10:51:12.096 ThaliTest[2519:7778417] client session: connect
2016-02-04 10:51:12.097 ThaliTest[2519:7778417] client session: stateChange:0->1 1454579458964.626.q01zJg==
,2016-02-04 10:51:12.472 ThaliTest[2519:7778143] multipeer session: reset timer
2016-02-04 10:51:12.472 ThaliTest[2519:7778143] multipeer session: stop timer
2016-02-04 10:51:12.472 ThaliTest[2519:7778143] multipeer session: start timer: 0x1dbc77e0
2016-,02-04 10:51:12.472 ThaliTest[2519:7778143] server: disconnecting to refresh session (1454579458964.626)
2016-02-04 10:51:12.472 ThaliTest[2519:7778143] server session: disconnect
2016-02-04 10:51:12.472 ThaliTest[2519:7778143] server session: stateChange,:2->0 1454579458964.626
,2016-02-04 10:51:12.484 ThaliTest[2519:7778143] server session: connect
2016-02-04 10:51:12.484 ThaliTest[2519:7778143] server session: stateChange:0->1 1454579458964.626
,2016-02-04 10:51:12.496 ThaliTest[2519:7778143] server: accepting invitation 1454579458964.626
,2016-02-04 10:51:14.599 ThaliTest[2519:7781073] client session: connected
2016-02-04 10:51:14.599 ThaliTest[2519:7781073] client session: stateChange:1->2 1454579458964.626.q01zJg==
,2016-02-04 10:51:14.617 ThaliTest[2519:7781042] client session: fireConnectCallback: 1454579458964.626.q01zJg==
2016-02-04 10:51:14.618 ThaliTest[2519:7781042] jxcore: connect: success
,ok 108 Should be able to connect without error

ok 109 Port should be within range

ok 110 Second connect should succeed

,2016-02-04 10:51:14.649 ThaliTest[2519:7778143] client: relay established
2016-02-04 10:51:14.650 ThaliTest[2519:7778143] client: new accepted socket: 0x1dbcc590
,ok 111 the test messages should be equal

ok 112 Second send should succeed

,# setup

,2016-02-04 10:51:15.319 ThaliTest[2519:7778143] client: socket closed
2016-02-04 10:51:15.319 ThaliTest[2519:7778143] client relay: socket disconnected
2016-02-04 10:51:15.319 ThaliTest[2519:7778143] client relay: 0x1dbcc590 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 10:51:15.319 ThaliTest[2519:7778143] client session: socket closed: 1454579458964.626.q01zJg==
2016-02-04 1,0:51:15.319 ThaliTest[2519:7778143] client session: onLinkFailure: 1454579458964.626.q01zJg==
2016-02-04 10:51:15.320 ThaliTest[2519:7778143] client session: disconnect
,2016-02-04 10:51:15.320 ThaliTest[2519:7778143] client session: stateChange:2->0 1454579458964.626.q01zJg==
,2016-02-04 10:51:15.330 ThaliTest[2519:7778143] client session: fireConnectionErrorEvent: 1454579458964.626.q01zJg==
,2016-02-04 10:51:15.567 ThaliTest[2519:7781067] server session: connected
2016-02-04 10:51:15.567 ThaliTest[2519:7781067] server session: stateChange:1->2 1454579458964.626
,2016-02-04 10:51:15.572 ThaliTest[2519:7778143] server relay: connected (to port: 63607)
,calling stopBroadcasting

,2016-02-04 10:51:16.178 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:51:16.179 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:51:16.179 ThaliTest[2519:7778417] multipeer session: stop timer
2016-02-04 10:51:16.179 ThaliTest[2519:7778417] server session: disconnect
2016-02-04 10:51:16.179 ThaliTest[2519:7778417] server session: stateChange:2->0 1454579458964.626
,2016-02-04 10:51:16.191 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/98E3CAFC-65C3-4645-8D86-EE50DFEA3B6A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}
,
,ok 113 starting event should occur in right order

,2016-02-04 10:51:17.279 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:51:17.281 ThaliTest[2519:7778417] server: starting qaeyI3FvKZQqwhcyA3Btow.145UUw==
2016-02-04 10:51:17.282 ThaliTest[2519:7778417] multipeer session: start timer: 0x1cbd9670
2016-02-04 10:51:17.282 ThaliTest[2519:7778417] THEMultipeerSessio,n initialized peer qaeyI3FvKZQqwhcyA3Btow
2016-02-04 10:51:17.283 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-04 10:51:17.285 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:51:17.286 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
,2016-02-04 10:51:17.286 ThaliTest[2519:7778417] multipeer session: stop timer
,2016-02-04 10:51:17.287 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/98E3CAFC-65C3-4645-8D86-EE50DFEA3B6A/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 10:51:21.763 ThaliTest[2519:7778417] jxcore: startBroadcasting
,2016-02-04 10:51:21.765 ThaliTest[2519:7778417] server: starting qaeyI3FvKZQqwhcyA3Btow.Au+dqA==
2016-02-04 10:51:21.765 ThaliTest[2519:7778417] multipeer session: start timer: 0x1cbfaa50
2016-02-04 10:51:21.765 ThaliTest[2519:7778417] THEMultipeerSessio,n initialized peer qaeyI3FvKZQqwhcyA3Btow
2016-02-04 10:51:21.765 ThaliTest[2519:7778417] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-04 10:51:21.768 ThaliTest[2519:7778417] jxcore: stopBroadcasting
2016-02-04 10:51:21.768 ThaliTest[2519:7778417] THEMultipeerSession stopping peer
2016-02-04 10:51:21.768 ThaliTest[2519:7778417,] multipeer session: stop timer
2016-02-04 10:51:21.769 ThaliTest[2519:7778417] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup
,
,* thread #1: tid = 0x76af5f, 0x3979d2c6 libsystem_platform.dylib`<redacted> + 34, queue = 'com.apple.main-thread'
  * frame #0: 0x3979d2c6 libsystem_platform.dylib`<redacted> + 34
    frame #1: 0x3972d350 libsystem_malloc.dylib`<redacted> + 548
    frame #2: 0x397b435e libsystem_trace.dylib`_os_log_internal + 542
    frame #3: 0x29d72b64 MultipeerConnectivity`<redacted> + 60
    frame #4: 0x27113984 CFNetwork`<redacted> + 120
    frame #5: 0x2711332c CFNetwork`<redacted> + 36
    frame #6: 0x27071062 CFNetwork`<redacted> + 90
    frame #7: 0x277e87c6 CoreFoundation`<redacted> + 14
    frame #8: 0x277e8348 CoreFoundation`<redacted> + 344
    frame #9: 0x277e671e CoreFoundation`<redacted> + 806
    frame #10: 0x277390d8 CoreFoundation`CFRunLoopRunSpecific + 516
    frame #11: 0x27738ecc CoreFoundation`CFRunLoopRunInMode + 108
    frame #12: 0x30aaeaf8 GraphicsServices`GSEventRunModal + 160
    frame #13: 0x2b9c22dc UIKit`UIApplicationMain + 144
    frame #14: 0x000bc1f2 ThaliTest`main + 50

```
