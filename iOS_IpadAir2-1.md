#### Test 58380500c26a9ef_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A9182DF5-D83A-49B0-927B-F439C646B78E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A9182DF5-D83A-49B0-927B-F439C646B78E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500c26a9ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52461"
,(lldb)     command script import "/tmp/A9182DF5-D83A-49B0-927B-F439C646B78E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 03:05:27.186 ThaliTest[993:1673070] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D03F474C-E4D5-41A0-8C26-465570570750/Library/Cookies/Cookies.binarycookies
,2016-02-09 03:05:27.535 ThaliTest[993:1673070] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 03:05:27.536 ThaliTest[993:1673070] Multi-tasking -> Device: YES, App: YES
,2016-02-09 03:05:27.544 ThaliTest[993:1673070] Unlimited access to network resources
,2016-02-09 03:05:27.552 ThaliTest[993:1673070] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 03:05:37.896 ThaliTest[993:1673070] Resetting plugins due to page load.
,2016-02-09 03:05:41.569 ThaliTest[993:1673070] Finished load of: file:///var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/index.html
,2016-02-09 03:05:41.723 ThaliTest[993:1673070] JXcore Cordova plugin initializing
,2016-02-09 03:05:41.724 ThaliTest[993:1673316] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 20 should not throw

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

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-09 03:15:27.876 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.891 ThaliTest[993:1673316] server: starting 1454984127876.993.sQHKTA==
,2016-02-09 03:15:27.893 ThaliTest[993:1673316] multipeer session: start timer: 0x16e51790
,2016-02-09 03:15:27.894 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127876.993
,2016-02-09 03:15:27.896 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 54 Should be able to call startBroadcasting without error

,2016-02-09 03:15:27.900 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:15:27.900 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:15:27.900 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:15:27.901 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-09 03:15:27.903 ThaliTest[993:1673316] jxcore: startBroadcasting
2016-02-09 03:15:27.907 ThaliTest[993:1673316] server: start,ing 1454984127902.993.5dycYA==
2016-02-09 03:15:27.908 ThaliTest[993:1673316] multipeer session: start timer: 0x14f10b00
2016-02-09 03:15:27.908 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127902.993
2016-02-09 03:15:27.909 ThaliT,est[993:1673316] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

2016-02-09 03:15:27.912 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:27.913 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:27.913 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:15:27.915 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:27.918 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.925 ThaliTest[993:1673316] server: starting 1454984127917.993.oKm8pg==
2016-02-09 03:15:27.926 ThaliTest[993:1673316] multipeer session: start timer: 0x14ef8bb0
2016-02-09 03:15:27.926 ThaliTest[993:1673316] THEMultipeerSession initia,lized peer 1454984127917.993
2016-02-09 03:15:27.927 ThaliTest[993:1673316] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-09 03:15:27.928 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:15:27.929 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:27.929 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:15:27.934 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:27.938 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.945 ThaliTest[993:1673316] server: starting 1454984127938.993.F29Kew==
,2016-02-09 03:15:27.946 ThaliTest[993:1673316] multipeer session: start timer: 0x16fc9c40
2016-02-09 03:15:27.946 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127938.993
2016-02-09 03:15:27.947 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-09 03:15:27.954 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:27.954 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:27.955 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:27.959 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:27.962 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.965 ThaliTest[993:1673316] server: starting 1454984127962.993.5iDFNQ==
,2016-02-09 03:15:27.966 ThaliTest[993:1673316] multipeer session: start timer: 0x14fc70f0
,2016-02-09 03:15:27.970 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127962.993
,2016-02-09 03:15:27.971 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-09 03:15:27.973 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:27.974 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:27.975 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:27.976 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:27.980 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.982 ThaliTest[993:1673316] server: starting 1454984127979.993.RH7NPQ==
,2016-02-09 03:15:27.984 ThaliTest[993:1673316] multipeer session: start timer: 0x14f1d350
,2016-02-09 03:15:27.987 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127979.993
,2016-02-09 03:15:27.988 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-09 03:15:27.990 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:27.990 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:27.991 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:27.993 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:27.995 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:27.997 ThaliTest[993:1673316] server: starting 1454984127995.993.cNXS3w==
,2016-02-09 03:15:27.998 ThaliTest[993:1673316] multipeer session: start timer: 0x16d342c0
,2016-02-09 03:15:28.000 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984127995.993
,2016-02-09 03:15:28.001 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-09 03:15:28.004 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:28.005 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:28.006 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:28.007 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:28.010 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:28.012 ThaliTest[993:1673316] server: starting 1454984128010.993.iA1wQg==
,2016-02-09 03:15:28.014 ThaliTest[993:1673316] multipeer session: start timer: 0x16fcf990
,2016-02-09 03:15:28.017 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984128010.993
,2016-02-09 03:15:28.018 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-09 03:15:28.021 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:28.021 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:28.022 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:28.024 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:28.027 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:28.030 ThaliTest[993:1673316] server: starting 1454984128026.993.0KQM+w==
,2016-02-09 03:15:28.031 ThaliTest[993:1673316] multipeer session: start timer: 0x16f2da40
2016-02-09 03:15:28.034 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984128026.993
,2016-02-09 03:15:28.035 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-09 03:15:28.038 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:28.038 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:28.039 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:28.042 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-09 03:15:28.044 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:28.046 ThaliTest[993:1673316] server: starting 1454984128043.993.PxLiAA==
,2016-02-09 03:15:28.047 ThaliTest[993:1673316] multipeer session: start timer: 0x17ca18f0
,2016-02-09 03:15:28.050 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984128043.993
,2016-02-09 03:15:28.050 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-09 03:15:28.052 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:15:28.052 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:15:28.053 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:28.055 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 03:15:38.037 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:38.040 ThaliTest[993:1673316] server: starting 1454984138037.993.NK0AeQ==
,2016-02-09 03:15:38.041 ThaliTest[993:1673316] multipeer session: start timer: 0x14e70120
2016-02-09 03:15:38.042 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984138037.993
2016-02-09 03:15:38.042 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-09 03:15:38.045 ThaliTest[993:1673316] jxcore: startBroadcasting
2016-02-09 03:15:38.046 ThaliTest[993:1673316] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-02-09 03:15:38.051 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:15:38.051 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:15:38.052 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:15:38.052, ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 03:15:38.532 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:38.536 ThaliTest[993:1673316] server: starting 1454984138532.993.Eif/GA==
,2016-02-09 03:15:38.537 ThaliTest[993:1673316] multipeer session: start timer: 0x14e4d220
,2016-02-09 03:15:38.537 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984138532.993
,2016-02-09 03:15:38.538 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

2016-02-09 03:15:38.540 ThaliTest[993:1673316] jxcore: connect foobar
2016-02-09 03:15:38.541 ThaliTest[993:1673316] client: unknown peer foobar
2016-02-09 03:15:38.541 ThaliTest[993:1673316] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

2016-02-09 03:15:38.545 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:15:38.546 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:15:38.546 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:38.547 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 03:15:49.258 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:49.261 ThaliTest[993:1673316] server: starting 1454984149258.993.xQUxfA==
,2016-02-09 03:15:49.262 ThaliTest[993:1673316] multipeer session: start timer: 0x17a8f9d0
2016-02-09 03:15:49.263 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984149258.993
2016-02-09 03:15:49.263 ThaliTest[993:1673316] jxcore: startBr,oadcasting: success
ok 80 Should be able to call startBroadcasting without error

,2016-02-09 03:15:49.266 ThaliTest[993:1673316] jxcore: disconnect
2016-02-09 03:15:49.266 ThaliTest[993:1673316] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-09 03:15:49.270 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:15:49.272 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:15:49.272 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:15:49.272 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 03:15:58.811 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:15:58.814 ThaliTest[993:1673316] server: starting 1454984158810.993.0Qovaw==
,2016-02-09 03:15:58.815 ThaliTest[993:1673316] multipeer session: start timer: 0x178f85c0
2016-02-09 03:15:58.816 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984158810.993
2016-02-09 03:15:58.817 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 03:16:01.146 ThaliTest[993:1673070] multipeer session: reset timer
2016-02-09 03:16:01.147 ThaliTest[993:1673070] multipeer session: stop timer
2016-02-09 03:16:01.147 ThaliTest[993:1673070] multipeer session: start timer: 0x178f85c0
,2016-02-09 03:16:01.148 ThaliTest[993:1673070] server session: connect
2016-02-09 03:16:01.148 ThaliTest[993:1673070] server session: stateChange:0->1 1454984157964.2780
,2016-02-09 03:16:01.154 ThaliTest[993:1673070] server: accepting invitation 1454984157964.2780
,2016-02-09 03:16:01.490 ThaliTest[993:1673070] client: found peer: 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:01.493 ThaliTest[993:1673316] jxcore: connect 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:01.493 ThaliTest[993:1673316] client session: connect
,2016-02-09 03:16:01.494 ThaliTest[993:1673316] client session: stateChange:0->1 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:04.094 ThaliTest[993:1674424] server session: connected
,2016-02-09 03:16:04.094 ThaliTest[993:1674424] server session: stateChange:1->2 1454984157964.2780
,2016-02-09 03:16:04.112 ThaliTest[993:1673070] server relay: socket disconnected
,2016-02-09 03:16:04.112 ThaliTest[993:1673070] server relay: 0x14feda10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection r,efused} 
,2016-02-09 03:16:04.147 ThaliTest[993:1674447] server session: not connected 1454984157964.2780
,2016-02-09 03:16:04.295 ThaliTest[993:1674476] client session: connected
2016-02-09 03:16:04.295 ThaliTest[993:1674476] client session: stateChange:1->2 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:04.328 ThaliTest[993:1674447] client session: fireConnectCallback: 1454984157964.2780.GTHaNg==
2016-02-09 03:16:04.328 ThaliTest[993:1674447] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-09 03:16:04.335 ThaliTest[993:1673316] jxcore: disconnect
,2016-02-09 03:16:04.335 ThaliTest[993:1673316] client session: disconnectFromPeer: 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:04.336 ThaliTest[993:1673316] client session: disconnect
,2016-02-09 03:16:04.337 ThaliTest[993:1673316] client session: stateChange:2->0 1454984157964.2780.GTHaNg==
,2016-02-09 03:16:04.410 ThaliTest[993:1673316] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 03:16:05.406 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:16:05.407 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:16:05.408 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:16:05.409 ThaliTest[993:1673316] server session: disconnect
,2016-02-09 03:16:05.409 ThaliTest[993:1673316] server session: stateChange:2->0 1454984157964.2780
,2016-02-09 03:16:05.412 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 03:16:11.169 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:16:11.172 ThaliTest[993:1673316] server: starting 1454984171169.993.I1lJBA==
,2016-02-09 03:16:11.173 ThaliTest[993:1673316] multipeer session: start timer: 0x1785a330
2016-02-09 03:16:11.174 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984171169.993
2016-02-09 03:16:11.174 ThaliTest[993:1673316] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-09 03:16:12.020 ThaliTest[993:1673070] client: found peer: 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:12.022 ThaliTest[993:1673316] jxcore: connect 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:12.023 ThaliTest[993:1673316] client session: connect
2016-02-09 03:16:12.024 ThaliTest[993:1673316] client session: stateChange:0->1 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:12.614 ThaliTest[993:1673070] multipeer session: reset timer
2016-02-09 03:16:12.615 ThaliTest[993:1673070] multipeer session: stop timer
2016-02-09 03:16:12.615 ThaliTest[993:1673070] multipeer session: start timer: 0x1785a330
2016-02-09 03:16:12.615 ThaliTest[993:1673070] server session: connect
2016-02-09 03:16:12.616 ThaliTest[993:1673070] server session: stateChange:0->1 1454984169717.2780
,2016-02-09 03:16:12.622 ThaliTest[993:1673070] server: accepting invitation 1454984169717.2780
,2016-02-09 03:16:15.491 ThaliTest[993:1674423] client session: connected
2016-02-09 03:16:15.491 ThaliTest[993:1674423] client session: stateChange:1->2 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:15.497 ThaliTest[993:1674423] client session: fireConnectCallback: 1454984169717.2780.fHQHxA==
2016-02-09 03:16:15.497 ThaliTest[993:1674423] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-09 03:16:15.502 ThaliTest[993:1673316] jxcore: connect 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:15.503 ThaliTest[993:1673316] client: already connect(ing/ed) to 1454984169717.2780.fHQHxA==
2016-02-09 03:16:15.504 ThaliTest[993:1673316] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-09 03:16:15.508 ThaliTest[993:1673316] jxcore: disconnect
,2016-02-09 03:16:15.508 ThaliTest[993:1673316] client session: disconnectFromPeer: 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:15.508 ThaliTest[993:1673316] client session: disconnect
,2016-02-09 03:16:15.509 ThaliTest[993:1673316] client session: stateChange:2->0 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:15.518 ThaliTest[993:1673316] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-09 03:16:15.618 ThaliTest[993:1674485] server session: connected
,2016-02-09 03:16:15.619 ThaliTest[993:1674485] server session: stateChange:1->2 1454984169717.2780
,2016-02-09 03:16:15.623 ThaliTest[993:1673070] server relay: socket disconnected
,2016-02-09 03:16:15.624 ThaliTest[993:1673070] server relay: 0x17b94680 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 03:16:15.665 ThaliTest[993:1674485] server session: not connected 1454984169717.2780
,calling stopBroadcasting

,2016-02-09 03:16:16.479 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:16:16.479 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:16:16.480 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:16:16.481 ThaliTest[993:1673316] server session: disconnect
2016-02-09 03:16:16.482 ThaliTest[993:1673316] server session: stateChange:2->0 1454984169717.2780
2016-02-09 03:16:16.483 ThaliTest[993:1673316] jxcore: stopBroadcasting: success,
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 03:16:20.185 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:16:20.189 ThaliTest[993:1673316] server: starting 1454984180185.993.dEZ3qg==
2016-02-09 03:16:20.190 ThaliTest[993:1673316] multipeer session: start timer: 0x179deb10
,2016-02-09 03:16:20.191 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984180185.993
2016-02-09 03:16:20.191 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 03:16:20.204 ThaliTest[993:1673070] client: found peer: 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:20.206 ThaliTest[993:1673316] jxcore: connect 1454984169717.2780.fHQHxA==
2016-02-09 03:16:20.206 ThaliTest[993:1673316] client session: connect
,2016-02-09 03:16:20.207 ThaliTest[993:1673316] client session: stateChange:0->1 1454984169717.2780.fHQHxA==
,2016-02-09 03:16:21.456 ThaliTest[993:1673070] multipeer session: reset timer
2016-02-09 03:16:21.457 ThaliTest[993:1673070] multipeer session: stop timer
2016-02-09 03:16:21.457 ThaliTest[993:1673070] multipeer session: start timer: 0x179deb10
2016-02-09 03:16:21.457 ThaliTest[993:1673070] server session: connect
2016-02-09 03:16:21.458 ThaliTest[993:1673070] server session: stateChange:0->1 1454984179661.2780
,2016-02-09 03:16:21.466 ThaliTest[993:1673070] server: accepting invitation 1454984179661.2780
,2016-02-09 03:16:21.949 ThaliTest[993:1673070] client: found peer: 1454984179661.2780.DfruYA==
,2016-02-09 03:16:21.950 ThaliTest[993:1673316] jxcore: connect 1454984179661.2780.DfruYA==
2016-02-09 03:16:21.951 ThaliTest[993:1673316] client session: connect
2016-02-09 03:16:21.951 ThaliTest[993:1673316] client session: stateChange:0->1 1454984179661.2780.DfruYA==
,2016-02-09 03:16:24.217 ThaliTest[993:1674526] server session: connected
,2016-02-09 03:16:24.219 ThaliTest[993:1674526] server session: stateChange:1->2 1454984179661.2780
,2016-02-09 03:16:24.222 ThaliTest[993:1673070] server relay: socket disconnected
,2016-02-09 03:16:24.223 ThaliTest[993:1673070] server relay: 0x17b94d60 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 03:16:24.345 ThaliTest[993:1674526] server session: not connected 1454984179661.2780
,2016-02-09 03:16:25.200 ThaliTest[993:1674526] client session: connected
2016-02-09 03:16:25.201 ThaliTest[993:1674526] client session: stateChange:1->2 1454984179661.2780.DfruYA==
,2016-02-09 03:16:25.205 ThaliTest[993:1674526] client session: fireConnectCallback: 1454984179661.2780.DfruYA==
2016-02-09 03:16:25.206 ThaliTest[993:1674526] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 03:16:25.209 ThaliTest[993:1673316] jxcore: disconnect
,2016-02-09 03:16:25.209 ThaliTest[993:1673316] client session: disconnectFromPeer: 1454984179661.2780.DfruYA==
,2016-02-09 03:16:25.209 ThaliTest[993:1673316] client session: disconnect
,2016-02-09 03:16:25.210 ThaliTest[993:1673316] client session: stateChange:2->0 1454984179661.2780.DfruYA==
,2016-02-09 03:16:25.219 ThaliTest[993:1673316] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-09 03:16:25.222 ThaliTest[993:1673316] jxcore: disconnect
,2016-02-09 03:16:25.222 ThaliTest[993:1673316] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 03:16:25.448 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:16:25.449 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:16:25.449 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:16:25.450 ThaliTest[993:1673316] client session: disconnect
2016-02-09 03:16:25.450 ThaliTest[993:1673316] client session: stateChange:1->0 1454984169717.2780.fHQHxA==
2016-02-09 03:16:25.451 ThaliTest[993:1673316] server session: disconnec,t
2016-02-09 03:16:25.451 ThaliTest[993:1673316] server session: stateChange:2->0 1454984179661.2780
,2016-02-09 03:16:25.921 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 55256

,2016-02-09 03:16:27.458 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:16:27.460 ThaliTest[993:1673316] server: starting 1454984187458.993.aoLPtw==
,2016-02-09 03:16:27.460 ThaliTest[993:1673316] multipeer session: start timer: 0x179dfab0
2016-02-09 03:16:27.460 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984187458.993
2016-02-09 03:16:27.460 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-09 03:16:29.816 ThaliTest[993:1673070] client: found peer: 1454984187348.2780.zlzeIw==
,2016-02-09 03:16:29.818 ThaliTest[993:1673316] jxcore: connect 1454984187348.2780.zlzeIw==
2016-02-09 03:16:29.818 ThaliTest[993:1673316] client session: connect
2016-02-09 03:16:29.819 ThaliTest[993:1673316] client session: stateChange:0->1 1454984187348.2780.zlzeIw==
,2016-02-09 03:16:31.678 ThaliTest[993:1673070] multipeer session: reset timer
,2016-02-09 03:16:31.679 ThaliTest[993:1673070] multipeer session: stop timer
,2016-02-09 03:16:31.679 ThaliTest[993:1673070] multipeer session: start timer: 0x179dfab0
2016-02-09 03:16:31.679 ThaliTest[993:1673070] server session: connect
,2016-02-09 03:16:31.680 ThaliTest[993:1673070] server session: stateChange:0->1 1454984187348.2780
,2016-02-09 03:16:31.686 ThaliTest[993:1673070] server: accepting invitation 1454984187348.2780
,2016-02-09 03:16:32.644 ThaliTest[993:1674526] client session: connected
,2016-02-09 03:16:32.645 ThaliTest[993:1674526] client session: stateChange:1->2 1454984187348.2780.zlzeIw==
,2016-02-09 03:16:32.660 ThaliTest[993:1674519] client session: fireConnectCallback: 1454984187348.2780.zlzeIw==
2016-02-09 03:16:32.661 ThaliTest[993:1674519] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-09 03:16:32.667 ThaliTest[993:1673070] client: relay established
2016-02-09 03:16:32.668 ThaliTest[993:1673070] client: new accepted socket: 0x17b36930
,data in 3285

,data in 6570

,data in 30660

,data in 32850

,data in 42705

,2016-02-09 03:16:34.339 ThaliTest[993:1674485] server session: connected
2016-02-09 03:16:34.339 ThaliTest[993:1674485] server session: stateChange:1->2 1454984187348.2780
,2016-02-09 03:16:34.358 ThaliTest[993:1673070] server relay: connected (to port: 55256)
,data in 73425

,data in 112785

,2016-02-09 03:16:36.002 ThaliTest[993:1674519] server session: not connected 1454984187348.2780
,data in 116070

,data in 131072

,ok 100 the test messages should be equal

,2016-02-09 03:16:55.931 ThaliTest[993:1673316] jxcore: disconnect
,2016-02-09 03:16:55.932 ThaliTest[993:1673316] client session: disconnectFromPeer: 1454984187348.2780.zlzeIw==
2016-02-09 03:16:55.932 ThaliTest[993:1673316] client session: disconnect
2016-02-09 03:16:55.933 ThaliTest[993:1673316] client session: stateChange:2->0 1454984187348.2780.zlzeIw==
,2016-02-09 03:16:55.939 ThaliTest[993:1673316] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 03:16:56.323 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:16:56.324 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:16:56.324 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:16:56.325 ThaliTest[993:1673316] server session: disconnect
2016-02-09 03:16:56.326 ThaliTest[993:1673316] server session: stateChange:2->0 1454984187348.2780
,2016-02-09 03:16:56.331 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 55262

,2016-02-09 03:16:57.856 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:16:57.859 ThaliTest[993:1673316] server: starting 1454984217855.993.Tw9Hdw==
,2016-02-09 03:16:57.860 ThaliTest[993:1673316] multipeer session: start timer: 0x14fc7470
,2016-02-09 03:16:57.861 ThaliTest[993:1673316] THEMultipeerSession initialized peer 1454984217855.993
,2016-02-09 03:16:57.862 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-09 03:16:58.619 ThaliTest[993:1673070] client: found peer: 1454984187348.2780.zlzeIw==
,[{"peerIdentifier":"1454984187348.2780.zlzeIw==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 03:16:58.622 ThaliTest[993:1673316] jxcore: connect 1454984187348.2780.zlzeIw==
,2016-02-09 03:16:58.623 ThaliTest[993:1673316] client session: connect
,2016-02-09 03:16:58.623 ThaliTest[993:1673316] client session: stateChange:0->1 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:00.697 ThaliTest[993:1673070] multipeer session: reset timer
2016-02-09 03:17:00.697 ThaliTest[993:1673070] multipeer session: stop timer
2016-02-09 03:17:00.697 ThaliTest[993:1673070] multipeer session: start timer: 0x14fc7470
2016-02-09 03:17:00.698 ThaliTest[993:1673070] server session: connect
,2016-02-09 03:17:00.698 ThaliTest[993:1673070] server session: stateChange:0->1 1454984218180.2780
,2016-02-09 03:17:00.705 ThaliTest[993:1673070] server: accepting invitation 1454984218180.2780
,2016-02-09 03:17:00.737 ThaliTest[993:1673070] client: found peer: 1454984218180.2780.KE6AwQ==
[{"peerIdentifier":"1454984218180.2780.KE6AwQ==","peerName":"(null)","peerAvailable":true}]

2016-02-09 03:17:00.739 ThaliTest[993:1673316] jxcore: connect 14,54984218180.2780.KE6AwQ==
2016-02-09 03:17:00.739 ThaliTest[993:1673316] client session: connect
2016-02-09 03:17:00.740 ThaliTest[993:1673316] client session: stateChange:0->1 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:02.185 ThaliTest[993:1674661] server session: connected
2016-02-09 03:17:02.185 ThaliTest[993:1674661] server session: stateChange:1->2 1454984218180.2780
,2016-02-09 03:17:02.201 ThaliTest[993:1674519] client session: connected
2016-02-09 03:17:02.201 ThaliTest[993:1674519] client session: stateChange:1->2 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:02.486 ThaliTest[993:1673070] server relay: connected (to port: 55262)
,2016-02-09 03:17:02.504 ThaliTest[993:1674661] client session: fireConnectCallback: 1454984218180.2780.KE6AwQ==
2016-02-09 03:17:02.504 ThaliTest[993:1674661] jxcore: connect: success
,ok 103 Should be able to connect without error

,ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-09 03:17:02.571 ThaliTest[993:1673070] client: relay established
2016-02-09 03:17:02.571 ThaliTest[993:1673070] client: new accepted socket: 0x17869840
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-09 03:17:03.174 ThaliTest[993:1674663] server session: not connected 1454984218180.2780
,2016-02-09 03:17:03.179 ThaliTest[993:1673070] client: socket closed
2016-02-09 03:17:03.180 ThaliTest[993:1673070] client relay: socket disconnected
,2016-02-09 03:17:03.180 ThaliTest[993:1673070] client relay: 0x17869840 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-09 03:17:03.180 ThaliTest[993:1673070] client session: socket closed: 1454984218180.2780.KE6AwQ==
2016-02-09 03:17:03.181 ThaliTest[993:1673070] client session: onLinkFailure: 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:03.181 ThaliTest[993:1673070] client session: disconnect
,2016-02-09 03:17:03.181 ThaliTest[993:1673070] client session: stateChange:2->0 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:03.192 ThaliTest[993:1673070] client session: fireConnectionErrorEvent: 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:03.195 ThaliTest[993:1673316] jxcore: connect 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:03.196 ThaliTest[993:1673316] client session: connect
,2016-02-09 03:17:03.197 ThaliTest[993:1673316] client session: stateChange:0->1 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:03.259 ThaliTest[993:1673070] multipeer session: reset timer
,2016-02-09 03:17:03.259 ThaliTest[993:1673070] multipeer session: stop timer
,2016-02-09 03:17:03.260 ThaliTest[993:1673070] multipeer session: start timer: 0x14fc7470
,2016-02-09 03:17:03.260 ThaliTest[993:1673070] server: disconnecting to refresh session (1454984218180.2780)
,2016-02-09 03:17:03.261 ThaliTest[993:1673070] server session: disconnect
,2016-02-09 03:17:03.261 ThaliTest[993:1673070] server session: stateChange:2->0 1454984218180.2780
,2016-02-09 03:17:03.267 ThaliTest[993:1673070] server session: connect
,2016-02-09 03:17:03.267 ThaliTest[993:1673070] server session: stateChange:0->1 1454984218180.2780
,2016-02-09 03:17:03.279 ThaliTest[993:1673070] server: accepting invitation 1454984218180.2780
,2016-02-09 03:17:03.562 ThaliTest[993:1673070] client: lost peer: 1454984187348.2780.zlzeIw==
2016-02-09 03:17:03.562 ThaliTest[993:1673070] client session: onPeerLost: 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:03.562 ThaliTest[993:1673070] client session: onLinkFailure: 1454984187348.2780.zlzeIw==
2016-02-09 03:17:03.562 ThaliTest[993:1673070] client session: disconnect
2016-02-09 03:17:03.563 ThaliTest[993:1673070] client session: stateChange:1->0 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:03.563 ThaliTest[993:1673070] client session: fireConnectCallback: 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:03.563 ThaliTest[993:1673070] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1454984187348.2780.zlzeIw==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 03:17:04.577 ThaliTest[993:1673316] jxcore: connect 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:04.577 ThaliTest[993:1673316] client: connect: unreachable 1454984187348.2780.zlzeIw==
,2016-02-09 03:17:04.578 ThaliTest[993:1673316] jxcore: connect: fail: Peer unreachable
,2016-02-09 03:17:05.043 ThaliTest[993:1674661] client session: connected
,2016-02-09 03:17:05.044 ThaliTest[993:1674661] client session: stateChange:1->2 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:06.141 ThaliTest[993:1674661] server session: connected
,2016-02-09 03:17:06.141 ThaliTest[993:1674661] server session: stateChange:1->2 1454984218180.2780
,2016-02-09 03:17:06.209 ThaliTest[993:1673070] server relay: connected (to port: 55262)
,2016-02-09 03:17:06.422 ThaliTest[993:1674663] client session: fireConnectCallback: 1454984218180.2780.KE6AwQ==
2016-02-09 03:17:06.423 ThaliTest[993:1674663] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-09 03:17:06.458 ThaliTest[993:1673070] client: relay established
2016-02-09 03:17:06.459 ThaliTest[993:1673070] client: new accepted socket: 0x14e4ef40
,2016-02-09 03:17:06.471 ThaliTest[993:1674519] server session: not connected 1454984218180.2780
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-09 03:17:06.919 ThaliTest[993:1673070] client: socket closed
,2016-02-09 03:17:06.920 ThaliTest[993:1673070] client relay: socket disconnected
,2016-02-09 03:17:06.920 ThaliTest[993:1673070] client relay: 0x14e4ef40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 03:17:0,6.920 ThaliTest[993:1673070] client session: socket closed: 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:06.921 ThaliTest[993:1673070] client session: onLinkFailure: 1454984218180.2780.KE6AwQ==
2016-02-09 03:17:06.921 ThaliTest[993:1673070] client session: disconnect
2016-02-09 03:17:06.921 ThaliTest[993:1673070] client session: stateChange,:2->0 1454984218180.2780.KE6AwQ==
,2016-02-09 03:17:06.931 ThaliTest[993:1673070] client session: fireConnectionErrorEvent: 1454984218180.2780.KE6AwQ==
,calling stopBroadcasting

,2016-02-09 03:17:08.463 ThaliTest[993:1673316] jxcore: stopBroadcasting
,2016-02-09 03:17:08.464 ThaliTest[993:1673316] THEMultipeerSession stopping peer
,2016-02-09 03:17:08.464 ThaliTest[993:1673316] multipeer session: stop timer
,2016-02-09 03:17:08.465 ThaliTest[993:1673316] server session: disconnect
,2016-02-09 03:17:08.466 ThaliTest[993:1673316] server session: stateChange:2->0 1454984218180.2780
,2016-02-09 03:17:08.475 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 113 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range

,# teardown

,ok 114 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 115 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 116 should be equal

,ok 117 should be equal

,ok 118 should be equal

,ok 119 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 120 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 121 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range

,# teardown

,ok 122 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 123 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 124 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 125 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 126 should be equal

ok 127 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 128 should be equal

ok 129 (unnamed assert)

,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 130 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D03F474C-E4D5-41A0-8C26-465570570750/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 131 starting event should occur in right order

,2016-02-09 03:21:00.184 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:21:00.186 ThaliTest[993:1673316] server: starting Hr93NoKxPbQgmEH4U3bolg.nch1dA==
,2016-02-09 03:21:00.186 ThaliTest[993:1673316] multipeer session: start timer: 0x17cad750
2016-02-09 03:21:00.186 ThaliTest[993:1673316] THEMultipeerSession initialized peer Hr93NoKxPbQgmEH4U3bolg
,2016-02-09 03:21:00.187 ThaliTest[993:1673316] jxcore: startBroadcasting: success
,ok 132 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

,ok 133 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 03:21:00.189 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:21:00.190 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:21:00.190 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:21:00.190 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 134 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D03F474C-E4D5-41A0-8C26-465570570750/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 03:21:10.844 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:21:10.847 ThaliTest[993:1673316] server: starting Hr93NoKxPbQgmEH4U3bolg.w0jTJg==
,2016-02-09 03:21:10.848 ThaliTest[993:1673316] multipeer session: start timer: 0x14e174e0
,2016-02-09 03:21:10.850 ThaliTest[993:1673316] THEMultipeerSession initialized peer Hr93NoKxPbQgmEH4U3bolg
2016-02-09 03:21:10.851 ThaliTest[993:1673316] jxcore: startBroadcasting: success
ok 135 getDeviceIdentity should not return an error

ok 136 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-02-09 03:21:10.854 ThaliTest[993:1673316] jxcore: stopBroadcasting
2016-02-09 03:21:10.855 ThaliTest[993:1673316] THEMultipeerSession stopping peer
2016-02-09 03:21:10.855 ThaliTest[993:1673316] multipeer session: stop timer
2016-02-09 03:21:10.856 ThaliTest[993:1673316] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/D03F474C-E4D5-41A0-8C26-465570570750/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 03:21:19.509 ThaliTest[993:1673316] jxcore: startBroadcasting
,2016-02-09 03:21:19.511 ThaliTest[993:1673316] server: starting Hr93NoKxPbQgmEH4U3bolg.sayvsg==
,2016-02-09 03:21:19.511 ThaliTest[993:1673316] multipeer session: start timer: 0x14fca440
2016-02-09 03:21:19.511 ThaliTest[993:1673316] THEMultipeerSession initialized peer Hr93NoKxPbQgmEH4U3bolg
2016-02-09 03:21:19.511 ThaliTest[993:1673316] jxcore: st,artBroadcasting: success
ok 137 getDeviceIdentity should not return an error

,ok 138 deviceName should not be null

,2016-02-09 03:21:22.792 ThaliTest[993:1673070] client: found peer: bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
,2016-02-09 03:21:23.539 ThaliTest[993:1673316] jxcore: connect bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
2016-02-09 03:21:23.539 ThaliTest[993:1673316] client session: connect
2016-02-09 03:21:23.539 ThaliTest[993:1673316] client session: stateChange:0->1 bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
,ok 139 Should be able to put doc without error

,ok 140 1st change of local doc should contain local id

,2016-02-09 03:21:32.160 ThaliTest[993:1673070] multipeer session: reset timer
2016-02-09 03:21:32.160 ThaliTest[993:1673070] multipeer session: stop timer
2016-02-09 03:21:32.160 ThaliTest[993:1673070] multipeer session: start timer: 0x14fca440
2016-02-,09 03:21:32.161 ThaliTest[993:1673070] server session: connect
2016-02-09 03:21:32.161 ThaliTest[993:1673070] server session: stateChange:0->1 bIBi0lXqqRYjUr0x3GWJLQ
,2016-02-09 03:21:32.170 ThaliTest[993:1673070] server: accepting invitation bIBi0lXqqRYjUr0x3GWJLQ
,2016-02-09 03:21:34.572 ThaliTest[993:1675262] client session: connected
,2016-02-09 03:21:34.572 ThaliTest[993:1675262] client session: stateChange:1->2 bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
,2016-02-09 03:21:34.576 ThaliTest[993:1675262] client session: fireConnectCallback: bIBi0lXqqRYjUr0x3GWJLQ.I7NLfQ==
2016-02-09 03:21:34.576 ThaliTest[993:1675262] jxcore: connect: success
,2016-02-09 03:21:34.588 ThaliTest[993:1673070] client: relay established
2016-02-09 03:21:34.588 ThaliTest[993:1673070] client: new accepted socket: 0x179c53e0
,client bridge: new client socket

,client bridge: new client socket

,2016-02-09 03:21:35.046 ThaliTest[993:1675263] server session: connected
,2016-02-09 03:21:35.046 ThaliTest[993:1675263] server session: stateChange:1->2 bIBi0lXqqRYjUr0x3GWJLQ
,2016-02-09 03:21:35.053 ThaliTest[993:1673070] server relay: connected (to port: 55281)
,server bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/lib/thali-tape.js:37:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/4CAD21BA-0A2,A-46EB-A91F-C20C19F624B6/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
