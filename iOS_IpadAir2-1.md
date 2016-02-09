#### Test 58380500306a2c5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D53D5802-2D0B-401F-B9B3-F7FFC5D23BD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D53D5802-2D0B-401F-B9B3-F7FFC5D23BD6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58380500306a2c5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54011"
,(lldb)     command script import "/tmp/D53D5802-2D0B-401F-B9B3-F7FFC5D23BD6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-09 23:48:54.125 ThaliTest[1230:1838756] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/54783C90-29D9-4238-B7FA-AAD389DA8CE9/Library/Cookies/Cookies.binarycookies
,2016-02-09 23:48:54.464 ThaliTest[1230:1838756] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-09 23:48:54.464 ThaliTest[1230:1838756] Multi-tasking -> Device: YES, App: YES
,2016-02-09 23:48:54.473 ThaliTest[1230:1838756] Unlimited access to network resources
,2016-02-09 23:48:54.480 ThaliTest[1230:1838756] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-09 23:49:04.334 ThaliTest[1230:1838756] Resetting plugins due to page load.
,2016-02-09 23:49:08.340 ThaliTest[1230:1838756] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/index.html
,2016-02-09 23:49:08.523 ThaliTest[1230:1838756] JXcore Cordova plugin initializing
,2016-02-09 23:49:08.524 ThaliTest[1230:1839008] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

ok 16 should be equal

,ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

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

,2016-02-09 23:53:54.819 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.836 ThaliTest[1230:1839008] server: starting 1455058434819.1230.0UuqLg==
,2016-02-09 23:53:54.837 ThaliTest[1230:1839008] multipeer session: start timer: 0x178682b0
,2016-02-09 23:53:54.837 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434819.1230
,2016-02-09 23:53:54.840 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.844 ThaliTest[1230:1839008] jxcore: stopBroadcasting
2016-02-09 23:53:54.845 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
2016-02-09 23:53:54.845 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.846 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.850 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.855 ThaliTest[1230:1839008] server: starting 1455058434850.1230.HmGvyg==
2016-02-09 23:53:54.856 ThaliTest[1230:1839008] multipeer session: start timer: 0x14edcc40
2016-02-09 23:53:54.856 ThaliTest[1230:1839008] THEMultipeerSession in,itialized peer 1455058434850.1230
2016-02-09 23:53:54.857 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error

2016-02-09 23:53:54.859 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.859 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.860 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.861 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
ok 66 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.865 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.873 ThaliTest[1230:1839008] server: starting 1455058434864.1230.Rilvfw==
,2016-02-09 23:53:54.875 ThaliTest[1230:1839008] multipeer session: start timer: 0x14edd8e0
,2016-02-09 23:53:54.882 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434864.1230
,2016-02-09 23:53:54.883 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 67 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.885 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.886 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.887 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.891 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 68 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.894 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.898 ThaliTest[1230:1839008] server: starting 1455058434893.1230./5M2Zg==
,2016-02-09 23:53:54.901 ThaliTest[1230:1839008] multipeer session: start timer: 0x179ee770
,2016-02-09 23:53:54.904 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434893.1230
,2016-02-09 23:53:54.907 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 69 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.910 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.911 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.912 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.914 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.917 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.920 ThaliTest[1230:1839008] server: starting 1455058434917.1230.aD6ekA==
,2016-02-09 23:53:54.922 ThaliTest[1230:1839008] multipeer session: start timer: 0x179ee750
,2016-02-09 23:53:54.924 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434917.1230
,2016-02-09 23:53:54.926 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 71 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.928 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.929 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.930 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.932 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 72 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.934 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.937 ThaliTest[1230:1839008] server: starting 1455058434934.1230.biV1/Q==
,2016-02-09 23:53:54.938 ThaliTest[1230:1839008] multipeer session: start timer: 0x179efc40
,2016-02-09 23:53:54.941 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434934.1230
,2016-02-09 23:53:54.942 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 73 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.944 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.945 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.945 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.946 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 74 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.950 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.953 ThaliTest[1230:1839008] server: starting 1455058434950.1230.IJ9RQA==
,2016-02-09 23:53:54.957 ThaliTest[1230:1839008] multipeer session: start timer: 0x179f0290
,2016-02-09 23:53:54.961 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434950.1230
,2016-02-09 23:53:54.962 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 75 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.964 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.964 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.965 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.966 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:54.970 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.972 ThaliTest[1230:1839008] server: starting 1455058434969.1230.EX3ovA==
,2016-02-09 23:53:54.973 ThaliTest[1230:1839008] multipeer session: start timer: 0x179f05f0
,2016-02-09 23:53:54.976 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434969.1230
,2016-02-09 23:53:54.977 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 77 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.979 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.980 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.981 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.984 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 78 Should be able to call stopBroadcasting without error
,
,2016-02-09 23:53:54.986 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:54.988 ThaliTest[1230:1839008] server: starting 1455058434985.1230.JK+xYw==
,2016-02-09 23:53:54.989 ThaliTest[1230:1839008] multipeer session: start timer: 0x179f0760
,2016-02-09 23:53:54.990 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434985.1230
,2016-02-09 23:53:54.993 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 79 Should be able to call startBroadcasting without error

,2016-02-09 23:53:54.995 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:54.995 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:54.996 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:54.998 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 80 Should be able to call stopBroadcasting without error

,2016-02-09 23:53:55.000 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:55.002 ThaliTest[1230:1839008] server: starting 1455058434999.1230.TERJRw==
,2016-02-09 23:53:55.003 ThaliTest[1230:1839008] multipeer session: start timer: 0x16cef040
,2016-02-09 23:53:55.005 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058434999.1230
,2016-02-09 23:53:55.006 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 81 Should be able to call startBroadcasting without error

,2016-02-09 23:53:55.008 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:53:55.008 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:55.008 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:55.009 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-09 23:53:55.319 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:55.322 ThaliTest[1230:1839008] server: starting 1455058435318.1230.wcrO0w==
,2016-02-09 23:53:55.323 ThaliTest[1230:1839008] multipeer session: start timer: 0x178ecc20
2016-02-09 23:53:55.324 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058435318.1230
2016-02-09 23:53:55.324 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-09 23:53:55.327 ThaliTest[1230:1839008] jxcore: startBroadcasting
2016-02-09 23:53:55.328 ThaliTest[1230:1839008] jxcore: startBroadcasting: failure
ok 84 Cannot call startBroadcasting twice

2016-02-09 23:53:55.331 ThaliTest[1230:1839008] jxco,re: stopBroadcasting
2016-02-09 23:53:55.331 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:55.331 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:55.333 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 85 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-09 23:53:56.721 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:53:56.724 ThaliTest[1230:1839008] server: starting 1455058436721.1230.24uj4w==
,2016-02-09 23:53:56.725 ThaliTest[1230:1839008] multipeer session: start timer: 0x14edbc70
,2016-02-09 23:53:56.726 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058436721.1230
2016-02-09 23:53:56.726 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
ok 86 Should be able to call startBroadcasting without error

,2016-02-09 23:53:56.729 ThaliTest[1230:1839008] jxcore: connect foobar
,2016-02-09 23:53:56.730 ThaliTest[1230:1839008] client: unknown peer foobar
2016-02-09 23:53:56.730 ThaliTest[1230:1839008] jxcore: connect: fail: Unknown peer
,ok 87 Should not connect to a bad peer

2016-02-09 23:53:56.734 ThaliTest[1230:1839008] jxcore: stopBroadcasting
2016-02-09 23:53:56.734 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:53:56.734 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:53:56.735 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 88 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-09 23:54:01.126 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:01.129 ThaliTest[1230:1839008] server: starting 1455058441126.1230.VjTN9Q==
,2016-02-09 23:54:01.130 ThaliTest[1230:1839008] multipeer session: start timer: 0x16a93640
,2016-02-09 23:54:01.131 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058441126.1230
,2016-02-09 23:54:01.131 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 89 Should be able to call startBroadcasting without error

2016-02-09 23:54:01.134 ThaliTest[1230:1839008] jxcore: disconnect
2016-02-09 23:54:01.134 ThaliTest[1230:1839008] jxcore: disconnect: fail
,ok 90 Disconnect should fail to a non-existant peer 

2016-02-09 23:54:01.139 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:01.141 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
2016-02-09 23:54:01.142 ThaliTest[1230:1839008] multipeer session: stop timer
2016-02-09 23:54:01.142 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,ok 91 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-09 23:54:06.871 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:06.875 ThaliTest[1230:1839008] server: starting 1455058446871.1230.Aoz4Cg==
,2016-02-09 23:54:06.875 ThaliTest[1230:1839008] multipeer session: start timer: 0x16c53f40
,2016-02-09 23:54:06.876 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058446871.1230
2016-02-09 23:54:06.877 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-09 23:54:08.103 ThaliTest[1230:1838756] client: found peer: 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:08.106 ThaliTest[1230:1839008] jxcore: connect 1455058444752.1727.XtjAGw==
2016-02-09 23:54:08.106 ThaliTest[1230:1839008] client session: connect
,2016-02-09 23:54:08.107 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:08.529 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:08.529 ThaliTest[1230:1838756] multipeer session: stop timer
2016-02-09 23:54:08.529 ThaliTest[1230:1838756] multipeer session: start timer: 0x16c53f40
2016-02-09 23:54:08.530 ThaliTest[1230:1838756] server session: connect
2016-02-09 23:54:08.530 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058444752.1727
,2016-02-09 23:54:08.536 ThaliTest[1230:1838756] server: accepting invitation 1455058444752.1727
,2016-02-09 23:54:11.053 ThaliTest[1230:1839486] server session: connected
2016-02-09 23:54:11.054 ThaliTest[1230:1839486] server session: stateChange:1->2 1455058444752.1727
,2016-02-09 23:54:11.060 ThaliTest[1230:1838756] server relay: socket disconnected
,2016-02-09 23:54:11.061 ThaliTest[1230:1838756] server relay: 0x16dbc470 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 23:54:11.131 ThaliTest[1230:1839484] server session: not connected 1455058444752.1727
,2016-02-09 23:54:11.193 ThaliTest[1230:1839539] client session: connected
,2016-02-09 23:54:11.194 ThaliTest[1230:1839539] client session: stateChange:1->2 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:11.199 ThaliTest[1230:1839539] client session: fireConnectCallback: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:11.199 ThaliTest[1230:1839539] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-09 23:54:11.204 ThaliTest[1230:1839008] jxcore: disconnect
,2016-02-09 23:54:11.204 ThaliTest[1230:1839008] client session: disconnectFromPeer: 1455058444752.1727.XtjAGw==
2016-02-09 23:54:11.205 ThaliTest[1230:1839008] client session: disconnect
2016-02-09 23:54:11.205 ThaliTest[1230:1839008] client session: stateChange:2->0 1455058444752.1727.XtjAGw==
,2016-02-09 23:54:11.275 ThaliTest[1230:1839008] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 23:54:11.461 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:11.461 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:54:11.462 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:11.463 ThaliTest[1230:1839008] server session: disconnect
,2016-02-09 23:54:11.463 ThaliTest[1230:1839008] server session: stateChange:2->0 1455058444752.1727
,2016-02-09 23:54:11.466 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-09 23:54:12.278 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:12.282 ThaliTest[1230:1839008] server: starting 1455058452278.1230.xZ+qZQ==
,2016-02-09 23:54:12.283 ThaliTest[1230:1839008] multipeer session: start timer: 0x16e26be0
2016-02-09 23:54:12.284 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058452278.1230
2016-02-09 23:54:12.285 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 96 Should be able to call startBroadcasting without error

,2016-02-09 23:54:12.775 ThaliTest[1230:1838756] client: found peer: 1455058449482.1727.JXtk8g==
2016-02-09 23:54:12.777 ThaliTest[1230:1839008] jxcore: connect 1455058449482.1727.JXtk8g==
2016-02-09 23:54:12.777 ThaliTest[1230:1839008] client session: co,nnect
2016-02-09 23:54:12.777 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:13.451 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:13.451 ThaliTest[1230:1838756] multipeer session: stop timer
2016-02-09 23:54:13.452 ThaliTest[1230:1838756] multipeer session: start timer: 0x16e26be0
2016-02-09 23:54:13.452 ThaliTest[1230:1838756] server session: connect
2016-02-09 23:54:13.452 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058449482.1727
,2016-02-09 23:54:13.457 ThaliTest[1230:1838756] server: accepting invitation 1455058449482.1727
,2016-02-09 23:54:15.678 ThaliTest[1230:1839484] client session: connected
2016-02-09 23:54:15.678 ThaliTest[1230:1839484] client session: stateChange:1->2 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:15.683 ThaliTest[1230:1839526] client session: fireConnectCallback: 1455058449482.1727.JXtk8g==
2016-02-09 23:54:15.683 ThaliTest[1230:1839526] jxcore: connect: success
,ok 97 Should be able to connect without error

,ok 98 Port should be within range

,2016-02-09 23:54:15.687 ThaliTest[1230:1839008] jxcore: connect 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:15.688 ThaliTest[1230:1839008] client: already connect(ing/ed) to 1455058449482.1727.JXtk8g==
2016-02-09 23:54:15.688 ThaliTest[1230:1839008] jxcore: connect: fail: Aleady connecting
,ok 99 Should fail on double connect

,2016-02-09 23:54:15.692 ThaliTest[1230:1839008] jxcore: disconnect
,2016-02-09 23:54:15.693 ThaliTest[1230:1839008] client session: disconnectFromPeer: 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:15.693 ThaliTest[1230:1839008] client session: disconnect
,2016-02-09 23:54:15.694 ThaliTest[1230:1839008] client session: stateChange:2->0 1455058449482.1727.JXtk8g==
,2016-02-09 23:54:15.703 ThaliTest[1230:1839008] jxcore: disconnect: success
,ok 100 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 23:54:15.872 ThaliTest[1230:1839486] server session: connected
2016-02-09 23:54:15.872 ThaliTest[1230:1839486] server session: stateChange:1->2 1455058449482.1727
,2016-02-09 23:54:15.877 ThaliTest[1230:1838756] server relay: socket disconnected
2016-02-09 23:54:15.878 ThaliTest[1230:1838756] server relay: 0x14eedff0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ,refused} 
,2016-02-09 23:54:15.920 ThaliTest[1230:1839547] server session: not connected 1455058449482.1727
,calling stopBroadcasting

,2016-02-09 23:54:16.167 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:16.168 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:54:16.168 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:16.170 ThaliTest[1230:1839008] server session: disconnect
2016-02-09 23:54:16.171 ThaliTest[1230:1839008] server session: stateChange:2->0 1455058449482.1727
,2016-02-09 23:54:16.175 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-09 23:54:16.496 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:16.499 ThaliTest[1230:1839008] server: starting 1455058456496.1230.EiakUw==
,2016-02-09 23:54:16.500 ThaliTest[1230:1839008] multipeer session: start timer: 0x14e032b0
2016-02-09 23:54:16.501 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058456496.1230
2016-02-09 23:54:16.501 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
ok 101 Should be able to call startBroadcasting without error

,2016-02-09 23:54:17.935 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:17.936 ThaliTest[1230:1838756] multipeer session: stop timer
,2016-02-09 23:54:17.936 ThaliTest[1230:1838756] multipeer session: start timer: 0x14e032b0
2016-02-09 23:54:17.936 ThaliTest[1230:1838756] server session: connect
,2016-02-09 23:54:17.937 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058454617.1727
,2016-02-09 23:54:17.943 ThaliTest[1230:1838756] server: accepting invitation 1455058454617.1727
,2016-02-09 23:54:18.097 ThaliTest[1230:1838756] client: found peer: 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:18.098 ThaliTest[1230:1839008] jxcore: connect 1455058454617.1727.2diA4Q==
2016-02-09 23:54:18.098 ThaliTest[1230:1839008] client session: connect
2016-02-09 23:54:18.099 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:20.497 ThaliTest[1230:1839484] server session: connected
2016-02-09 23:54:20.498 ThaliTest[1230:1839484] server session: stateChange:1->2 1455058454617.1727
,2016-02-09 23:54:20.501 ThaliTest[1230:1838756] server relay: socket disconnected
,2016-02-09 23:54:20.501 ThaliTest[1230:1838756] server relay: 0x179f9b10 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-09 23:54:20.584 ThaliTest[1230:1839486] server session: not connected 1455058454617.1727
,2016-02-09 23:54:20.655 ThaliTest[1230:1839486] client session: connected
,2016-02-09 23:54:20.655 ThaliTest[1230:1839486] client session: stateChange:1->2 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:20.661 ThaliTest[1230:1839486] client session: fireConnectCallback: 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:20.661 ThaliTest[1230:1839486] jxcore: connect: success
,ok 102 Should be able to connect without error

,ok 103 Port should be within range

,2016-02-09 23:54:20.665 ThaliTest[1230:1839008] jxcore: disconnect
,2016-02-09 23:54:20.666 ThaliTest[1230:1839008] client session: disconnectFromPeer: 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:20.666 ThaliTest[1230:1839008] client session: disconnect
,2016-02-09 23:54:20.667 ThaliTest[1230:1839008] client session: stateChange:2->0 1455058454617.1727.2diA4Q==
,2016-02-09 23:54:20.676 ThaliTest[1230:1839008] jxcore: disconnect: success
,ok 104 Should be able to disconnect without error

,2016-02-09 23:54:20.679 ThaliTest[1230:1839008] jxcore: disconnect
,2016-02-09 23:54:20.679 ThaliTest[1230:1839008] jxcore: disconnect: fail
,ok 105 Disconnect should fail 

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-09 23:54:20.890 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:20.890 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:54:20.891 ThaliTest[1230:1839008] multipeer session: stop timer
2016-02-09 23:54:20.892 ThaliTest[1230:1839008] server session: disconnect
2016-02-09 23:54:20.892 ThaliTest[1230:1839008] server session: stateChange:2->0 1455058454617.1727
,2016-02-09 23:54:21.097 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 56999

,2016-02-09 23:54:22.031 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:22.032 ThaliTest[1230:1839008] server: starting 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:22.032 ThaliTest[1230:1839008] multipeer session: start timer: 0x16a17300
2016-02-09 23:54:22.033 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058462031.1230
2016-02-09 23:54:22.033 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 106 Should be able to call startBroadcasting without error

,2016-02-09 23:54:23.229 ThaliTest[1230:1838756] client: found peer: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:23.230 ThaliTest[1230:1839008] jxcore: connect 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:23.231 ThaliTest[1230:1839008] client session: connect
,2016-02-09 23:54:23.232 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:23.559 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:23.559 ThaliTest[1230:1838756] multipeer session: stop timer
,2016-02-09 23:54:23.560 ThaliTest[1230:1838756] multipeer session: start timer: 0x16a17300
,2016-02-09 23:54:23.560 ThaliTest[1230:1838756] server session: connect
,2016-02-09 23:54:23.560 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058460000.1727
,2016-02-09 23:54:23.567 ThaliTest[1230:1838756] server: accepting invitation 1455058460000.1727
,2016-02-09 23:54:25.947 ThaliTest[1230:1839486] server session: connected
2016-02-09 23:54:25.948 ThaliTest[1230:1839486] server session: stateChange:1->2 1455058460000.1727
,2016-02-09 23:54:25.956 ThaliTest[1230:1838756] server relay: connected (to port: 56999)
,2016-02-09 23:54:25.966 ThaliTest[1230:1839526] client session: connected
,2016-02-09 23:54:25.966 ThaliTest[1230:1839526] client session: stateChange:1->2 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:25.975 ThaliTest[1230:1839526] client session: fireConnectCallback: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:25.975 ThaliTest[1230:1839526] jxcore: connect: success
,ok 107 Should be able to connect without error

,ok 108 Port should be within range

,2016-02-09 23:54:25.980 ThaliTest[1230:1838756] client: relay established
,2016-02-09 23:54:25.980 ThaliTest[1230:1838756] client: new accepted socket: 0x16eefcd0
,data in 2190

,data in 6570

,data in 15330

,data in 24090

,data in 26280

,data in 28470
,
,data in 35040
,
,data in 42705

,data in 61320

,data in 73365

,data in 87914

,data in 124830
,
,data in 131072

,ok 109 the test messages should be equal

,2016-02-09 23:54:26.274 ThaliTest[1230:1839008] jxcore: disconnect
,2016-02-09 23:54:26.275 ThaliTest[1230:1839008] client session: disconnectFromPeer: 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:26.275 ThaliTest[1230:1839008] client session: disconnect
,2016-02-09 23:54:26.275 ThaliTest[1230:1839008] client session: stateChange:2->0 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:26.281 ThaliTest[1230:1839008] jxcore: disconnect: success
,ok 110 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-09 23:54:26.291 ThaliTest[1230:1839513] server session: not connected 1455058460000.1727
,calling stopBroadcasting

,2016-02-09 23:54:26.657 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:26.658 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
2016-02-09 23:54:26.659 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:26.660 ThaliTest[1230:1839008] server session: disconnect
2016-02-09 23:54:26.660 ThaliTest[1230:1839008] server session: stateChange:2->0 1455058460000.1727
,2016-02-09 23:54:26.667 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 57005

,2016-02-09 23:54:26.748 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:26.751 ThaliTest[1230:1839008] server: starting 1455058466747.1230.UMClSA==
,2016-02-09 23:54:26.752 ThaliTest[1230:1839008] multipeer session: start timer: 0x16a17300
2016-02-09 23:54:26.752 ThaliTest[1230:1839008] THEMultipeerSession initialized peer 1455058466747.1230
2016-02-09 23:54:26.753 ThaliTest[1230:1839008] jxcore: sta,rtBroadcasting: success
,ok 111 Should be able to call startBroadcasting without error

,2016-02-09 23:54:26.764 ThaliTest[1230:1838756] client: found peer: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:26.765 ThaliTest[1230:1838756] client: found peer: 1455058460000.1727.HGrj8A==
,[{"peerIdentifier":"1455058462031.1230.GLlCGQ==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 23:54:26.768 ThaliTest[1230:1839008] jxcore: connect 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:26.769 ThaliTest[1230:1839008] client session: connect
,2016-02-09 23:54:26.769 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058462031.1230.GLlCGQ==
,[{"peerIdentifier":"1455058460000.1727.HGrj8A==","peerName":"(null)","peerAvailable":true}]

,2016-02-09 23:54:27.770 ThaliTest[1230:1839008] jxcore: connect 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:27.771 ThaliTest[1230:1839008] client session: connect
2016-02-09 23:54:27.771 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:27.879 ThaliTest[1230:1838756] client: lost peer: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:27.879 ThaliTest[1230:1838756] client session: onPeerLost: 1455058462031.1230.GLlCGQ==
2016-02-09 23:54:27.879 ThaliTest[1230:1838756] client session: onLinkFailure: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:27.880 ThaliTest[1230:1838756] client session: disconnect
2016-02-09 23:54:27.880 ThaliTest[1230:1838756] client session: stateChange:1->0 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:27.881 ThaliTest[1230:1838756] client session: fireConnectCallback: 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:27.881 ThaliTest[1230:1838756] jxcore: connect: fail: Peer disconnected
,[{"peerIdentifier":"1455058462031.1230.GLlCGQ==","peerName":"(null)","peerAvailable":false}]

,2016-02-09 23:54:27.892 ThaliTest[1230:1838756] multipeer session: reset timer
,2016-02-09 23:54:27.892 ThaliTest[1230:1838756] multipeer session: stop timer
,2016-02-09 23:54:27.892 ThaliTest[1230:1838756] multipeer session: start timer: 0x16a17300
,2016-02-09 23:54:27.893 ThaliTest[1230:1838756] server session: connect
2016-02-09 23:54:27.893 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058464677.1727
,2016-02-09 23:54:27.900 ThaliTest[1230:1838756] server: accepting invitation 1455058464677.1727
,2016-02-09 23:54:27.904 ThaliTest[1230:1838756] client: lost peer: 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:27.904 ThaliTest[1230:1838756] client session: onPeerLost: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:27.905 ThaliTest[1230:1838756] client session: onLinkFailure: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:27.905 ThaliTest[1230:1838756] client session: disconnect
2016-02-09 23:54:27.905 ThaliTest[1230:1838756] client session: stateChange:1->0 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:27.906 ThaliTest[1230:1838756] client session: fireConnectCallback: 1455058460000.1727.HGrj8A==
2016-02-09 23:54:27.907 ThaliTest[1230:1838756] jxcore: connect: fail: Peer disconnected
2016-02-09 23:54:27.907 ThaliTest[1230:1838756] clie,nt: found peer: 1455058464677.1727.ccpfIA==
[{"peerIdentifier":"1455058460000.1727.HGrj8A==","peerName":"(null)","peerAvailable":false}]

[{"peerIdentifier":"1455058464677.1727.ccpfIA==","peerName":"(null)","peerAvailable":true}]

2016-02-09 23:54:27.,910 ThaliTest[1230:1839008] jxcore: connect 1455058464677.1727.ccpfIA==
2016-02-09 23:54:27.911 ThaliTest[1230:1839008] client session: connect
2016-02-09 23:54:27.911 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:28.890 ThaliTest[1230:1839008] jxcore: connect 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:28.891 ThaliTest[1230:1839008] client: connect: unreachable 1455058462031.1230.GLlCGQ==
,2016-02-09 23:54:28.891 ThaliTest[1230:1839008] jxcore: connect: fail: Peer unreachable
,2016-02-09 23:54:28.920 ThaliTest[1230:1839008] jxcore: connect 1455058460000.1727.HGrj8A==
2016-02-09 23:54:28.921 ThaliTest[1230:1839008] client: connect: unreachable 1455058460000.1727.HGrj8A==
,2016-02-09 23:54:28.921 ThaliTest[1230:1839008] jxcore: connect: fail: Peer unreachable
,2016-02-09 23:54:30.493 ThaliTest[1230:1839547] server session: connected
2016-02-09 23:54:30.493 ThaliTest[1230:1839547] server session: stateChange:1->2 1455058464677.1727
,2016-02-09 23:54:30.511 ThaliTest[1230:1838756] server relay: connected (to port: 57005)
,2016-02-09 23:54:30.632 ThaliTest[1230:1839513] client session: connected
2016-02-09 23:54:30.633 ThaliTest[1230:1839513] client session: stateChange:1->2 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:30.665 ThaliTest[1230:1839513] client session: fireConnectCallback: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:30.665 ThaliTest[1230:1839513] jxcore: connect: success
,ok 112 Should be able to connect without error

,ok 113 Port should be within range

,ok 114 First connect should succeed

,2016-02-09 23:54:30.699 ThaliTest[1230:1839513] server session: not connected 1455058464677.1727
,2016-02-09 23:54:30.734 ThaliTest[1230:1838756] client: relay established
,2016-02-09 23:54:30.734 ThaliTest[1230:1838756] client: new accepted socket: 0x14ed8970
,2016-02-09 23:54:30.757 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:30.757 ThaliTest[1230:1838756] multipeer session: stop timer
,2016-02-09 23:54:30.758 ThaliTest[1230:1838756] multipeer session: start timer: 0x16a17300
,2016-02-09 23:54:30.758 ThaliTest[1230:1838756] server: disconnecting to refresh session (1455058464677.1727)
,2016-02-09 23:54:30.759 ThaliTest[1230:1838756] server session: disconnect
,2016-02-09 23:54:30.759 ThaliTest[1230:1838756] server session: stateChange:2->0 1455058464677.1727
,2016-02-09 23:54:30.763 ThaliTest[1230:1838756] server session: connect
2016-02-09 23:54:30.763 ThaliTest[1230:1838756] server session: stateChange:0->1 1455058464677.1727
,2016-02-09 23:54:30.773 ThaliTest[1230:1838756] server: accepting invitation 1455058464677.1727
,ok 115 the test messages should be equal

,ok 116 First send should succeed

,2016-02-09 23:54:30.802 ThaliTest[1230:1838756] client: socket closed
2016-02-09 23:54:30.802 ThaliTest[1230:1838756] client relay: socket disconnected
,2016-02-09 23:54:30.803 ThaliTest[1230:1838756] client relay: 0x14ed8970 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 23:54:,30.803 ThaliTest[1230:1838756] client session: socket closed: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:30.803 ThaliTest[1230:1838756] client session: onLinkFailure: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:30.803 ThaliTest[1230:1838756] client session: disconnect
,2016-02-09 23:54:30.803 ThaliTest[1230:1838756] client session: stateChange:2->0 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:30.932 ThaliTest[1230:1838756] client session: fireConnectionErrorEvent: 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:30.936 ThaliTest[1230:1839008] jxcore: connect 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:30.936 ThaliTest[1230:1839008] client session: connect
,2016-02-09 23:54:30.937 ThaliTest[1230:1839008] client session: stateChange:0->1 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:33.454 ThaliTest[1230:1839547] server session: connected
2016-02-09 23:54:33.454 ThaliTest[1230:1839547] server session: stateChange:1->2 1455058464677.1727
,2016-02-09 23:54:33.485 ThaliTest[1230:1838756] server relay: connected (to port: 57005)
,2016-02-09 23:54:33.592 ThaliTest[1230:1839602] client session: connected
2016-02-09 23:54:33.593 ThaliTest[1230:1839602] client session: stateChange:1->2 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:33.660 ThaliTest[1230:1839547] client session: fireConnectCallback: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:33.660 ThaliTest[1230:1839547] jxcore: connect: success
ok 117 Should be able to connect without error

,ok 118 Port should be within range

,ok 119 Second connect should succeed

,2016-02-09 23:54:33.670 ThaliTest[1230:1839547] server session: not connected 1455058464677.1727
,2016-02-09 23:54:33.694 ThaliTest[1230:1838756] client: relay established
2016-02-09 23:54:33.695 ThaliTest[1230:1838756] client: new accepted socket: 0x178d3740
,ok 120 the test messages should be equal

,ok 121 Second send should succeed

,# setup

,2016-02-09 23:54:33.795 ThaliTest[1230:1838756] client: socket closed
2016-02-09 23:54:33.796 ThaliTest[1230:1838756] client relay: socket disconnected
2016-02-09 23:54:33.796 ThaliTest[1230:1838756] client relay: 0x178d3740 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-09 23:54:,33.797 ThaliTest[1230:1838756] client session: socket closed: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:33.797 ThaliTest[1230:1838756] client session: onLinkFailure: 1455058464677.1727.ccpfIA==
2016-02-09 23:54:33.797 ThaliTest[1230:1838756] client se,ssion: disconnect
2016-02-09 23:54:33.797 ThaliTest[1230:1838756] client session: stateChange:2->0 1455058464677.1727.ccpfIA==
,2016-02-09 23:54:33.807 ThaliTest[1230:1838756] client session: fireConnectionErrorEvent: 1455058464677.1727.ccpfIA==
,calling stopBroadcasting

,2016-02-09 23:54:34.013 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:34.013 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:54:34.014 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:34.015 ThaliTest[1230:1839008] server session: disconnect
2016-02-09 23:54:34.015 ThaliTest[1230:1839008] server session: stateChange:2->0 1455058464677.1727
,2016-02-09 23:54:34.021 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# #generatePreambleAndBeacons null ECDH for local device

,# teardown

,ok 122 ecdhForLocalDevice cannot be null

,# setup

,# #generatePreambleAndBeacons expiration out of range lower

,# teardown

,ok 123 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons expiration out of range upper

,# teardown

,ok 124 secondsUntilExpiration out of range.

,# setup

,# #generatePreambleAndBeacons empty keys to notify

,# teardown

,ok 125 should be equal

,# setup

,# #generatePreambleAndBeacons multiple keys to notify

,# teardown

,ok 126 should be equal

,ok 127 should be equal

,ok 128 should be equal

,ok 129 should be equal

,# setup

,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble

,# teardown

,ok 130 should throw

,# setup

,# #parseBeacons invalid expiration in beaconStreamWithPreAmble

,# teardown

,ok 131 Preamble expiration must be a 64 bit integer

,# setup

,# #parseBeacons expiration out of range lower

,# teardown

,ok 132 Expiration out of range

,# setup

,# #parseBeacons no beacons returns null

,# teardown

,ok 133 should be equal

,# setup

,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble

,# teardown

,ok 134 Malformed encrypted beacon key ID

,# setup

,# #parseBeacons addressBookCallback fails decrypt

,# teardown

,ok 135 should be equal

,# setup

,# #parseBeacons addressBookCallback returns no matches

,# teardown

,ok 136 should be equal

ok 137 should be equal

,# setup

,# #parseBeacons addressBookCallback returns public key

,# teardown

,ok 138 should be equal

,ok 139 (unnamed assert)

,# setup

,# #parseBeacons with beacons both for and not for the user

,# teardown

,ok 140 (unnamed assert)

,# setup

,# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/54783C90-29D9-4238-B7FA-AAD389DA8CE9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 141 starting event should occur in right order

,2016-02-09 23:54:46.637 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:46.638 ThaliTest[1230:1839008] server: starting p_29iHlSdwuZDWS9L3mN8Q.9s3wxg==
,2016-02-09 23:54:46.639 ThaliTest[1230:1839008] multipeer session: start timer: 0x14f00410
2016-02-09 23:54:46.639 ThaliTest[1230:1839008] THEMultipeerSession initialized peer p_29iHlSdwuZDWS9L3mN8Q
2016-02-09 23:54:46.639 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
,ok 142 started event should occur in right order

,Now in TRM stop

State of this._isStarted: true

ok 143 stopping event should occur in right order

About to call stopBroadcasting

2016-02-09 23:54:46.641 ThaliTest[1230:1839008] jxcore: stopBroadcasting
,2016-02-09 23:54:46.641 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
,2016-02-09 23:54:46.641 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:46.642 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 144 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/54783C90-29D9-4238-B7FA-AAD389DA8CE9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 23:54:46.927 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:46.930 ThaliTest[1230:1839008] server: starting p_29iHlSdwuZDWS9L3mN8Q.ffKbkg==
,2016-02-09 23:54:46.931 ThaliTest[1230:1839008] multipeer session: start timer: 0x17d1dd70
2016-02-09 23:54:46.932 ThaliTest[1230:1839008] THEMultipeerSession initialized peer p_29iHlSdwuZDWS9L3mN8Q
2016-02-09 23:54:46.932 ThaliTest[1230:1839008] jxcore: startBroadcasting: success
ok 145 getDeviceIdentity should not return an error

,ok 146 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true
,
,About to call stopBroadcasting

2016-02-09 23:54:46.936 ThaliTest[1230:1839008] jxcore: stopBroadcasting
2016-02-09 23:54:46.936 ThaliTest[1230:1839008] THEMultipeerSession stopping peer
2016-02-09 23:54:46.936 ThaliTest[1230:1839008] multipeer session: stop timer
,2016-02-09 23:54:46.937 ThaliTest[1230:1839008] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/54783C90-29D9-4238-B7FA-AAD389DA8CE9/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-09 23:54:48.834 ThaliTest[1230:1839008] jxcore: startBroadcasting
,2016-02-09 23:54:48.835 ThaliTest[1230:1839008] server: starting p_29iHlSdwuZDWS9L3mN8Q.dPIBxA==
,2016-02-09 23:54:48.835 ThaliTest[1230:1839008] multipeer session: start timer: 0x14f7b730
2016-02-09 23:54:48.835 ThaliTest[1230:1839008] THEMultipeerSession initialized peer p_29iHlSdwuZDWS9L3mN8Q
2016-02-09 23:54:48.836 ThaliTest[1230:1839008] jxcore:, startBroadcasting: success
,ok 147 getDeviceIdentity should not return an error

ok 148 deviceName should not be null

,2016-02-09 23:54:49.882 ThaliTest[1230:1838756] client: found peer: GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
,2016-02-09 23:54:52.834 ThaliTest[1230:1839008] jxcore: connect GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
2016-02-09 23:54:52.834 ThaliTest[1230:1839008] client session: connect
,2016-02-09 23:54:52.834 ThaliTest[1230:1839008] client session: stateChange:0->1 GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
,ok 149 Should be able to put doc without error

,ok 150 1st change of local doc should contain local id

,2016-02-09 23:54:53.502 ThaliTest[1230:1838756] multipeer session: reset timer
2016-02-09 23:54:53.503 ThaliTest[1230:1838756] multipeer session: stop timer
2016-02-09 23:54:53.503 ThaliTest[1230:1838756] multipeer session: start timer: 0x14f7b730
2016-02-09 23:54:53.503 ThaliTest[1230:1838756] server session: connect
,2016-02-09 23:54:53.504 ThaliTest[1230:1838756] server session: stateChange:0->1 GsV0h1_bzr1cf6gcdw0n9g
,2016-02-09 23:54:53.510 ThaliTest[1230:1838756] server: accepting invitation GsV0h1_bzr1cf6gcdw0n9g
,2016-02-09 23:54:56.208 ThaliTest[1230:1839688] client session: connected
2016-02-09 23:54:56.208 ThaliTest[1230:1839688] client session: stateChange:1->2 GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
2016-02-09 23:54:56.208 ThaliTest[1230:1839513] server session: con,nected
2016-02-09 23:54:56.208 ThaliTest[1230:1839513] server session: stateChange:1->2 GsV0h1_bzr1cf6gcdw0n9g
,2016-02-09 23:54:56.394 ThaliTest[1230:1839687] client session: fireConnectCallback: GsV0h1_bzr1cf6gcdw0n9g.uKAEAg==
2016-02-09 23:54:56.395 ThaliTest[1230:1838756] server relay: connected (to port: 57024)
2016-02-09 23:54:56.395 ThaliTest[1230:1839687] ,jxcore: connect: success
,server bridge: new client socket

,2016-02-09 23:54:56.416 ThaliTest[1230:1838756] client: relay established
2016-02-09 23:54:56.416 ThaliTest[1230:1838756] client: new accepted socket: 0x16f585b0
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,Uncaught Promise Rejection: {"status":400}

,Trace: { [Error: ETIMEDOUT] status: 400 }
    at $3.prototype.trace@console.js:139:8
    at @/private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/lib/thali-tape.js:39:3
    at emit@events.js:98:,1
    at handlers.reject/<@/private/var/mobile/Containers/Bundle/Application/EB9CD54A-8466-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/node_modules/lie/lib/index.js:128:11
    at nextTick@/private/var/mobile/Containers/Bundle/Application/EB9CD54A-846,6-44D6-B6BA-9BBC11ABEF15/ThaliTest.app/www/jxcore/node_modules/lie/node_modules/immediate/lib/index.js:61:7
    at $0a@node.js:917:1

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
