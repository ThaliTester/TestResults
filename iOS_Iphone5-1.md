#### Test 579720943a29850_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6D4C34E1-DDB2-4614-A87C-BB43AEB53CC1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6D4C34E1-DDB2-4614-A87C-BB43AEB53CC1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/579720943a29850/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64086"
,(lldb)     command script import "/tmp/6D4C34E1-DDB2-4614-A87C-BB43AEB53CC1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 13:04:37.887 ThaliTest[2313:7445076] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/61362FC7-6451-48A7-8C7F-0EFA089DA664/Library/Cookies/Cookies.binarycookies
,2016-02-02 13:04:38.009 ThaliTest[2313:7445076] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 13:04:38.011 ThaliTest[2313:7445076] Multi-tasking -> Device: YES, App: YES
,2016-02-02 13:04:38.016 ThaliTest[2313:7445076] Unlimited access to network resources
,2016-02-02 13:04:38.028 ThaliTest[2313:7445076] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 13:04:44.555 ThaliTest[2313:7445076] Resetting plugins due to page load.
,2016-02-02 13:04:47.122 ThaliTest[2313:7445076] Finished load of: file:///var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/index.html
,2016-02-02 13:04:47.307 ThaliTest[2313:7445076] JXcore Cordova plugin initializing
2016-02-02 13:04:47.309 ThaliTest[2313:7445278] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/38A0C43F-6D97-4EF6-AA48-FC7B324F774A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

ok 6 secondPromise result

ok 7 secondPromise testValue

ok 8 thirdPromise in promise

ok 9 thirdPromise result

ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

# setup

,# another

,# teardown

,ok 12 sane

# setup

,# successfully create a new pkcs12 file and return hash value

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

ok 17 should not throw

# setup

,# successfully read a previous pkcs12 file and return hash value

,# teardown

,ok 18 (unnamed assert)
,
,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal
,
ok 22 should be equal

# setup

,# failed to extract public key because of corrupt pkcs12 file

,# teardown

,ok 23 should be equal

# setup

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

# setup

,# #startBroadcasting should throw on null device name

,# teardown

,ok 29 should throw

# setup

,# #startBroadcasting should throw on empty string device name

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,# teardown

,ok 31 should throw

# setup

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

ok 36 should be equal

ok 37 should be equal

# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,# teardown

,ok 38 should be equal

ok 39 should be equal

ok 40 should be equal

# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,# teardown

,ok 41 should be equal

ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,# teardown

,ok 43 should be equal

,ok 44 should be equal

# setup

,# #connect should call Mobile("Connect") with a port and without an error

,# teardown

,ok 45 should be equal

ok 46 should be equal

ok 47 should be equal

# setup

,# #connect should call Mobile("Connect") and handle an error

,# teardown

,ok 48 should be equal

ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,# teardown

,ok 50 should be equal

ok 51 should be equal

# setup

,# should call Mobile("Disconnect") and handle an error

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,# teardown

,2016-02-02 13:10:17.601 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.611 ThaliTest[2313:7445278] server: starting 1454415017601.2313.d9/zuA==
2016-02-02 13:10:17.612 ThaliTest[2313:7445278] multipeer session: start timer: 0x16e0bac0
2016-02-02 13:10:17.612 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415017601.2313
2016-02-02 13:10:17.613 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-02-02 13:10:17.615 ThaliTest[2313:7445278] jxcore: stopBroadcasting,
,2016-02-02 13:10:17.615 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:17.620 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:17.621 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-02 13:10:17.622 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.627 ThaliTest[2313:7445278] server: starting 1454415017622.2313.RT84Xw==
2016-02-02 13:10:17.632 ThaliTest[2313:7445278] multipeer session: start timer: 0x1ce7c480
2016-02-02 13:10:17.633 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415017622.2313
2016-02-02 13:10:17.633 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.635 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:17.641 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:17.641 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.648 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-02-02 13:10:17.650 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.657 ThaliTest[2313:7445278] server: starting 1454415017650.2313.cBu+gQ==
2016-02-02 13:10:17.658 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d2a63f0
2016-02-02 13:10:17.658 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415017650.2313
2016-02-02 13:10:17.658 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-02 13:10:17.660 ThaliTest[2313:7445278] jxcore: stopBroadcasting,
2016-02-02 13:10:17.660 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.660 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:17.666 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-02 13:10:17.668 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.679 ThaliTest[2313:7445278] server: starting 1454415017668.2313.4vrorw==
,2016-02-02 13:10:17.682 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d347660
,2016-02-02 13:10:17.694 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017668.2313
,2016-02-02 13:10:17.696 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.699 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.699 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.700 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.703 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.707 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.710 ThaliTest[2313:7445278] server: starting 1454415017706.2313.VocUoA==
,2016-02-02 13:10:17.713 ThaliTest[2313:7445278] multipeer session: start timer: 0x1cd233b0
,2016-02-02 13:10:17.716 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017706.2313
,2016-02-02 13:10:17.719 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.721 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.722 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.722 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.724 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.728 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.732 ThaliTest[2313:7445278] server: starting 1454415017728.2313.TcMF9w==
,2016-02-02 13:10:17.735 ThaliTest[2313:7445278] multipeer session: start timer: 0x1cb438e0
,2016-02-02 13:10:17.739 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017728.2313
,2016-02-02 13:10:17.740 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.743 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.744 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.745 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.748 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error
,
,2016-02-02 13:10:17.751 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.754 ThaliTest[2313:7445278] server: starting 1454415017751.2313.8b4drQ==
,2016-02-02 13:10:17.757 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d044b40
,2016-02-02 13:10:17.762 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017751.2313
,2016-02-02 13:10:17.764 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.766 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.766 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.768 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.771 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.774 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.777 ThaliTest[2313:7445278] server: starting 1454415017774.2313.uVMDog==
,2016-02-02 13:10:17.780 ThaliTest[2313:7445278] multipeer session: start timer: 0x16d0e7c0
,2016-02-02 13:10:17.782 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017774.2313
,2016-02-02 13:10:17.785 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.788 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.788 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.790 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.792 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.796 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.800 ThaliTest[2313:7445278] server: starting 1454415017796.2313.GLzPzQ==
,2016-02-02 13:10:17.803 ThaliTest[2313:7445278] multipeer session: start timer: 0x16d0ec60
,2016-02-02 13:10:17.806 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017796.2313
,2016-02-02 13:10:17.811 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error
,
,2016-02-02 13:10:17.816 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.817 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.818 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.819 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-02 13:10:17.825 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.828 ThaliTest[2313:7445278] server: starting 1454415017825.2313.MYxISQ==
,2016-02-02 13:10:17.830 ThaliTest[2313:7445278] multipeer session: start timer: 0x16d0ee90
,2016-02-02 13:10:17.833 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415017825.2313
,2016-02-02 13:10:17.834 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-02 13:10:17.842 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:17.843 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:17.844 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:17.845 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error
,
,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,# teardown

,2016-02-02 13:10:17.993 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:17.996 ThaliTest[2313:7445278] server: starting 1454415017993.2313.V3uOSg==
2016-02-02 13:10:17.996 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d2a7080
2016-02-02 13:10:17.997 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415017993.2313
2016-02-02 13:10:17.997 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 74 Should be able to call startBroadcasting without error

2016-02-02 13:10:17.998 ThaliTest[2313:7445278] jxcore: startBroadcasting,
2016-02-02 13:10:17.998 ThaliTest[2313:7445278] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-02-02 13:10:18.001 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:18.004 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:18.004 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:18.,004 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on connection to bad peer

,# teardown

,2016-02-02 13:10:19.016 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:19.019 ThaliTest[2313:7445278] server: starting 1454415019016.2313.hAOe4Q==
2016-02-02 13:10:19.019 ThaliTest[2313:7445278] multipeer session: start timer: 0x1ce55320
2016-02-02 13:10:19.020 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415019016.2313
2016-02-02 13:10:19.020 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-02 13:10:19.021 ThaliTest[2313:7445278] jxcore: connect foobar
2016-02-02 13:10:19.021 ThaliTest[2313:7445278] client: unknown peer foobar
,2016-02-02 13:10:19.022 ThaliTest[2313:7445278] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-02-02 13:10:19.028 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:19.028 ThaliTest[2313:7445278] THEMult,ipeerSession stopping peer
2016-02-02 13:10:19.028 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:19.029 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,# teardown

,2016-02-02 13:10:19.977 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:19.979 ThaliTest[2313:7445278] server: starting 1454415019976.2313.hDDtLA==
2016-02-02 13:10:19.979 ThaliTest[2313:7445278] multipeer session: start timer: 0x1ca77360
2016-02-02 13:10:19.980 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415019976.2313
2016-02-02 13:10:19.980 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-02 13:10:19.981 ThaliTest[2313:7445278] jxcore: disconnect
2016-02-02 13:10:19.981 ThaliTest[2313:7445278] jxcore: disconnect: fail
ok 81 Disconnect should fail to a non-existant peer 

,2016-02-02 13:10:19.984 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:19.989 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:19.990 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:19.,990 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter can discover and connect to peers

,# teardown

,2016-02-02 13:10:20.523 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:20.526 ThaliTest[2313:7445278] server: starting 1454415020523.2313.MLQeWw==
2016-02-02 13:10:20.526 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d331ad0
2016-02-02 13:10:20.526 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415020523.2313
2016-02-02 13:10:20.527 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-02 13:10:21.902 ThaliTest[2313:7445076] client: found peer: 1454415020611.428.QLjBuw==
2016-02-02 13:10:21.903 ThaliTest[2313:7445278] jxcore: connect 1454415020611.428.QLjBuw==
2016-02-02 13:10:21.904 ThaliTest[2313:7445278] client session: connect
2016-02-02 13:10:21.904 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415020611.428.QLjBuw==
,2016-02-02 13:10:22.147 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:10:22.148 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:10:22.148 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d331ad0
2016-,02-02 13:10:22.148 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:22.148 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415020611.428
,2016-02-02 13:10:22.157 ThaliTest[2313:7445076] server: accepting invitation 1454415020611.428
,2016-02-02 13:10:25.155 ThaliTest[2313:7445897] server session: connected
2016-02-02 13:10:25.155 ThaliTest[2313:7445897] server session: stateChange:1->2 1454415020611.428
,2016-02-02 13:10:25.221 ThaliTest[2313:7445865] server session: not connected 1454415020611.428
,2016-02-02 13:10:25.347 ThaliTest[2313:7445897] client session: connected
,2016-02-02 13:10:25.347 ThaliTest[2313:7445897] client session: stateChange:1->2 1454415020611.428.QLjBuw==
,2016-02-02 13:10:25.362 ThaliTest[2313:7445865] client session: fireConnectCallback: 1454415020611.428.QLjBuw==
2016-02-02 13:10:25.362 ThaliTest[2313:7445865] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-02 13:10:25.364 ThaliTest[2313:7445278] jxcore: disconnect
,2016-02-02 13:10:25.365 ThaliTest[2313:7445278] client session: disconnectFromPeer: 1454415020611.428.QLjBuw==
,2016-02-02 13:10:25.366 ThaliTest[2313:7445278] client session: disconnect
,2016-02-02 13:10:25.367 ThaliTest[2313:7445278] client session: stateChange:2->0 1454415020611.428.QLjBuw==
,2016-02-02 13:10:25.379 ThaliTest[2313:7445278] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-02 13:10:25.424 ThaliTest[2313:7445278] jxcore: stopBroadcasting
,2016-02-02 13:10:25.424 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:10:25.424 ThaliTest[2313:7445278] multipeer session: stop timer
,2016-02-02 13:10:25.425 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:10:25.425 ThaliTest[2313:7445278] server session: stateChange:2->0 1454415020611.428
,2016-02-02 13:10:25.607 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,# teardown

,2016-02-02 13:10:25.934 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:25.938 ThaliTest[2313:7445278] server: starting 1454415025934.2313.8C1EhA==
2016-02-02 13:10:25.938 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d32cfc0
2016-02-02 13:10:25.938 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415025934.2313
2016-02-02 13:10:25.939 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-02 13:10:27.184 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:10:27.184 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:10:27.185 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d32cfc0
2016-02-02 13:10:27.185 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:27.185 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415026027.428
2016-02-02 13:10:27.191 ThaliTest[2313:7445076] server: accepting invitation 1454415026027.428
,2016-02-02 13:10:27.472 ThaliTest[2313:7445076] client: found peer: 1454415026027.428.a3OVsg==
2016-02-02 13:10:27.473 ThaliTest[2313:7445278] jxcore: connect 1454415026027.428.a3OVsg==
2016-02-02 13:10:27.473 ThaliTest[2313:7445278] client session: connect
2016-02-02 13:10:27.473 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.007 ThaliTest[2313:7445684] server session: connected
2016-02-02 13:10:30.007 ThaliTest[2313:7445684] server session: stateChange:1->2 1454415026027.428
,2016-02-02 13:10:30.013 ThaliTest[2313:7445076] server relay: socket disconnected
2016-02-02 13:10:30.013 ThaliTest[2313:7445076] server relay: 0x1ca438f0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:10:30.070 ThaliTest[2313:7445684] server session: not connected 1454415026027.428
,2016-02-02 13:10:30.268 ThaliTest[2313:7445684] client session: connected
,2016-02-02 13:10:30.268 ThaliTest[2313:7445684] client session: stateChange:1->2 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.274 ThaliTest[2313:7445684] client session: fireConnectCallback: 1454415026027.428.a3OVsg==
2016-02-02 13:10:30.274 ThaliTest[2313:7445684] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-02 13:10:30.278 ThaliTest[2313:7445278] jxcore: connect 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.278 ThaliTest[2313:7445278] client: already connect(ing/ed) to 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.278 ThaliTest[2313:7445278] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-02 13:10:30.281 ThaliTest[2313:7445278] jxcore: disconnect
,2016-02-02 13:10:30.281 ThaliTest[2313:7445278] client session: disconnectFromPeer: 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.282 ThaliTest[2313:7445278] client session: disconnect
,2016-02-02 13:10:30.282 ThaliTest[2313:7445278] client session: stateChange:2->0 1454415026027.428.a3OVsg==
,2016-02-02 13:10:30.357 ThaliTest[2313:7445278] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-02 13:10:30.627 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:30.627 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:30.627 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:30.628 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:10:30.628 ThaliTest[2313:7445278] server session: stateChange:2->0 1454415026027.428
,2016-02-02 13:10:30.629 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,# teardown

,2016-02-02 13:10:32.539 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:32.542 ThaliTest[2313:7445278] server: starting 1454415032539.2313.++UI8g==
2016-02-02 13:10:32.542 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d321950
2016-02-02 13:10:32.542 ThaliTest[2313:7445278] THEMultipeerSession in,itialized peer 1454415032539.2313
2016-02-02 13:10:32.543 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-02 13:10:33.440 ThaliTest[2313:7445076] client: found peer: 1454415032635.428.uRxb8A==
2016-02-02 13:10:33.441 ThaliTest[2313:7445278] jxcore: connect 1454415032635.428.uRxb8A==
2016-02-02 13:10:33.441 ThaliTest[2313:7445278] client session: connect
2016-02-02 13:10:33.441 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415032635.428.uRxb8A==
,2016-02-02 13:10:34.199 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:10:34.199 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:10:34.199 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d321950
2016-,02-02 13:10:34.199 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:34.200 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415032635.428
,2016-02-02 13:10:34.205 ThaliTest[2313:7445076] server: accepting invitation 1454415032635.428
,2016-02-02 13:10:36.962 ThaliTest[2313:7445897] server session: connected
,2016-02-02 13:10:36.962 ThaliTest[2313:7445897] server session: stateChange:1->2 1454415032635.428
,2016-02-02 13:10:36.966 ThaliTest[2313:7445897] client session: connected
,2016-02-02 13:10:36.966 ThaliTest[2313:7445897] client session: stateChange:1->2 1454415032635.428.uRxb8A==
,2016-02-02 13:10:37.032 ThaliTest[2313:7445076] server relay: socket disconnected
,2016-02-02 13:10:37.035 ThaliTest[2313:7445076] server relay: 0x1d30bd40 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-02 13:10:37.040 ThaliTest[2313:7445866] client session: fireConnectCallback: 1454415032635.428.uRxb8A==
,2016-02-02 13:10:37.041 ThaliTest[2313:7445866] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-02 13:10:37.044 ThaliTest[2313:7445278] jxcore: disconnect
,2016-02-02 13:10:37.045 ThaliTest[2313:7445278] client session: disconnectFromPeer: 1454415032635.428.uRxb8A==
,2016-02-02 13:10:37.045 ThaliTest[2313:7445278] client session: disconnect
,2016-02-02 13:10:37.046 ThaliTest[2313:7445278] client session: stateChange:2->0 1454415032635.428.uRxb8A==
,2016-02-02 13:10:37.053 ThaliTest[2313:7445897] server session: not connected 1454415032635.428
,2016-02-02 13:10:37.068 ThaliTest[2313:7445278] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-02 13:10:37.069 ThaliTest[2313:7445278] jxcore: disconnect
,2016-02-02 13:10:37.071 ThaliTest[2313:7445278] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

2016-02-02 13:10:37.480 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:37.481 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:37.481 ThaliTest[2313:7445278] multipeer session: stop, timer
2016-02-02 13:10:37.481 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:10:37.481 ThaliTest[2313:7445278] server session: stateChange:2->0 1454415032635.428
,2016-02-02 13:10:37.485 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,# teardown

,echo server started on port: 61037

,2016-02-02 13:10:40.155 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:40.158 ThaliTest[2313:7445278] server: starting 1454415040155.2313.JIJ5wg==
2016-02-02 13:10:40.159 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d30a8f0
,2016-02-02 13:10:40.159 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415040155.2313
2016-02-02 13:10:40.163 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-02 13:10:42.790 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:10:42.790 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:10:42.790 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d30a8f0
,2016-02-02 13:10:42.791 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:42.794 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415042533.428
2016-02-02 13:10:42.802 ThaliTest[2313:7445076] server: accepting invitation 1454415042533.428
,2016-02-02 13:10:43.306 ThaliTest[2313:7445076] client: found peer: 1454415042533.428.NkSsuA==
2016-02-02 13:10:43.307 ThaliTest[2313:7445278] jxcore: connect 1454415042533.428.NkSsuA==
2016-02-02 13:10:43.307 ThaliTest[2313:7445278] client session: connect
2016-02-02 13:10:43.307 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415042533.428.NkSsuA==
,2016-02-02 13:10:45.535 ThaliTest[2313:7445897] server session: connected
2016-02-02 13:10:45.535 ThaliTest[2313:7445897] server session: stateChange:1->2 1454415042533.428
,2016-02-02 13:10:45.565 ThaliTest[2313:7445076] server relay: connected (to port: 61037)
,2016-02-02 13:10:46.074 ThaliTest[2313:7445684] server session: not connected 1454415042533.428
,2016-02-02 13:10:46.252 ThaliTest[2313:7445684] client session: connected
,2016-02-02 13:10:46.252 ThaliTest[2313:7445684] client session: stateChange:1->2 1454415042533.428.NkSsuA==
,2016-02-02 13:10:46.280 ThaliTest[2313:7445684] client session: fireConnectCallback: 1454415042533.428.NkSsuA==
2016-02-02 13:10:46.280 ThaliTest[2313:7445684] jxcore: connect: success
,ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-02-02 13:10:46.285 ThaliTest[2313:7445076] client: relay established
2016-02-02 13:10:46.285 ThaliTest[2313:7445076] client: new accepted socket: 0x1d3084e0
,data in 5475

,data in 20805

,data in 24090

,data in 26280

,data in 28470

,data in 29565

,data in 38325

,data in 61320
,
,data in 64605

,data in 68985

,data in 76650

,data in 83220

,data in 99645

,data in 102930

,data in 113880

,data in 131072

,ok 100 the test messages should be equal

2016-02-02 13:10:47.515 ThaliTest[2313:7445278] jxcore: disconnect
2016-02-02 13:10:47.515 ThaliTest[2313:7445278] client session: disconnectFromPeer: 1454415042533.428.NkSsuA==
2016-02-02 13:10:47.515 ThaliTes,t[2313:7445278] client session: disconnect
2016-02-02 13:10:47.515 ThaliTest[2313:7445278] client session: stateChange:2->0 1454415042533.428.NkSsuA==
,2016-02-02 13:10:47.534 ThaliTest[2313:7445278] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

# setup

,calling stopBroadcasting

,2016-02-02 13:10:47.973 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:47.974 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:47.974 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:10:47.,974 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:10:47.974 ThaliTest[2313:7445278] server session: stateChange:2->0 1454415042533.428
2016-02-02 13:10:47.980 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly

,# teardown

,echo server started on port: 61043

2016-02-02 13:10:50.043 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:10:50.047 ThaliTest[2313:7445278] server: starting 1454415050043.2313.0cmmaw==
2016-02-02 13:10:50.047 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d3005b0
2016-02-02 13:10:50.048 ThaliTest[2313:7445278] THEMultipeerSession initialized peer 1454415050043.2313
2016-02-02 13:10:50.048 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-02 13:10:50.765 ThaliTest[2313:7445076] client: found peer: 1454415049669.428.6nTPEw==
[{"peerIdentifier":"1454415049669.428.6nTPEw==","peerName":"(null)","peerAvailable":true}]

2016-02-02 13:10:50.766 ThaliTest[2313:7445278] jxcore: connect 1454415049669.428.6nTPEw==
2016-02-02 13:10:50.766 ThaliTest[2313:7445278] client session: connect
2016-02-02 13:10:50.767 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415049669.428.6nTPEw==
,2016-02-02 13:10:51.295 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:10:51.295 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:10:51.296 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d3005b0
2016-,02-02 13:10:51.296 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:51.296 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415049669.428
2016-02-02 13:10:51.303 ThaliTest[2313:7445076] server: accepting invitation 1454415049669.428
,2016-02-02 13:10:54.056 ThaliTest[2313:7445902] server session: connected
2016-02-02 13:10:54.056 ThaliTest[2313:7445902] server session: stateChange:1->2 1454415049669.428
,2016-02-02 13:10:54.317 ThaliTest[2313:7445076] server relay: connected (to port: 61043)
,2016-02-02 13:10:54.335 ThaliTest[2313:7445902] client session: connected
2016-02-02 13:10:54.336 ThaliTest[2313:7445902] client session: stateChange:1->2 1454415049669.428.6nTPEw==
,2016-02-02 13:10:54.383 ThaliTest[2313:7445684] client session: fireConnectCallback: 1454415049669.428.6nTPEw==
2016-02-02 13:10:54.383 ThaliTest[2313:7445684] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

ok 105 First connect should succeed

,2016-02-02 13:10:54.408 ThaliTest[2313:7445076] client: relay established
2016-02-02 13:10:54.408 ThaliTest[2313:7445076] client: new accepted socket: 0x1cdfa400
,2016-02-02 13:10:54.452 ThaliTest[2313:7445902] server session: not connected 1454415049669.428
ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-02-02 13:10:54.473 ThaliTest[2313:7445076] client: socket closed
2016-02-02 13:10:54.474 ThaliTest[2313:7445076] client relay: socket disconnected
2016-02-02 13:10:54.474 ThaliTest[2313:7445076] client relay: 0x1cdfa400 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-02 13:10:54.474 ThaliTest[2313:7445076] client session: socket closed: 1454415049669.428.6nTPEw==
2016-02-02 1,3:10:54.474 ThaliTest[2313:7445076] client session: onLinkFailure: 1454415049669.428.6nTPEw==
2016-02-02 13:10:54.474 ThaliTest[2313:7445076] client session: disconnect
2016-02-02 13:10:54.474 ThaliTest[2313:7445076] client session: stateChange:2->0 1454415049669.428.6nTPEw==
,2016-02-02 13:10:54.492 ThaliTest[2313:7445076] client session: fireConnectionErrorEvent: 1454415049669.428.6nTPEw==
,2016-02-02 13:10:54.493 ThaliTest[2313:7445278] jxcore: connect 1454415049669.428.6nTPEw==
,2016-02-02 13:10:54.497 ThaliTest[2313:7445278] client session: connect
,2016-02-02 13:10:54.497 ThaliTest[2313:7445278] client session: stateChange:0->1 1454415049669.428.6nTPEw==
,2016-02-02 13:10:54.515 ThaliTest[2313:7445076] multipeer session: reset timer
,2016-02-02 13:10:54.516 ThaliTest[2313:7445076] multipeer session: stop timer
,2016-02-02 13:10:54.516 ThaliTest[2313:7445076] multipeer session: start timer: 0x1d3005b0
,2016-02-02 13:10:54.517 ThaliTest[2313:7445076] server: disconnecting to refresh session (1454415049669.428)
,2016-02-02 13:10:54.517 ThaliTest[2313:7445076] server session: disconnect
,2016-02-02 13:10:54.517 ThaliTest[2313:7445076] server session: stateChange:2->0 1454415049669.428
,2016-02-02 13:10:54.522 ThaliTest[2313:7445076] server session: connect
2016-02-02 13:10:54.522 ThaliTest[2313:7445076] server session: stateChange:0->1 1454415049669.428
,2016-02-02 13:10:54.532 ThaliTest[2313:7445076] server: accepting invitation 1454415049669.428
,2016-02-02 13:10:57.595 ThaliTest[2313:7445897] server session: connected
2016-02-02 13:10:57.595 ThaliTest[2313:7445897] server session: stateChange:1->2 1454415049669.428
,2016-02-02 13:10:57.652 ThaliTest[2313:7445076] server relay: connected (to port: 61043)
,2016-02-02 13:10:57.998 ThaliTest[2313:7445897] client session: connected
2016-02-02 13:10:57.998 ThaliTest[2313:7445897] client session: stateChange:1->2 1454415049669.428.6nTPEw==
,2016-02-02 13:10:58.009 ThaliTest[2313:7445897] server session: not connected 1454415049669.428
,2016-02-02 13:10:58.053 ThaliTest[2313:7445897] client session: fireConnectCallback: 1454415049669.428.6nTPEw==
2016-02-02 13:10:58.053 ThaliTest[2313:7445897] jxcore: connect: success
ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-02 13:10:58.075 ThaliTest[2313:7445076] client: relay established
2016-02-02 13:10:58.075 ThaliTest[2313:7445076] client: new accepted socket: 0x1d638270
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-02 13:10:58.146 ThaliTest[2313:7445076] client: socket closed
2016-02-02 13:10:58.146 ThaliTest[2313:7445076] client relay: socket disconnected
2016-02-02 13:10:58.146 ThaliTest[2313:7445076] client relay: 0x1d638270 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-02 13:10:58.147 ThaliTest[2313:7445076] client session: socket closed: 1454415049669.428.6nTPEw==
2016-02-02 13:10:58.147 ThaliTest[2313:7445076] client session: onLinkFailure: 1454415049669.428.6nTPEw==
2016-02-02 13:10:58.147 ThaliTest[2313:744,5076] client session: disconnect
,2016-02-02 13:10:58.148 ThaliTest[2313:7445076] client session: stateChange:2->0 1454415049669.428.6nTPEw==
,2016-02-02 13:10:58.157 ThaliTest[2313:7445076] client session: fireConnectionErrorEvent: 1454415049669.428.6nTPEw==
,calling stopBroadcasting

2016-02-02 13:10:59.519 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:10:59.519 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 13:10:59.519 ThaliTest[2313:7445278] multipeer session: stop, timer
2016-02-02 13:10:59.519 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:10:59.520 ThaliTest[2313:7445278] server session: stateChange:2->0 1454415049669.428
,2016-02-02 13:10:59.524 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/61362FC7-6451-48A7-8C7F-0EFA089DA664/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order
,
,2016-02-02 13:11:00.691 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:11:00.693 ThaliTest[2313:7445278] server: starting JQ6i2aeI0mdeePtIc-qbjA.LgrvsA==
2016-02-02 13:11:00.693 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d66e000
2016-02-02 13:11:00.694 ThaliTest[2313:7445278] THEMultipeerSessio,n initialized peer JQ6i2aeI0mdeePtIc-qbjA
2016-02-02 13:11:00.694 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event sh,ould occur in right order

About to call stopBroadcasting

2016-02-02 13:11:00.696 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:11:00.696 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:11:00.697 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:11:00.702 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/61362FC7-6451-48A7-8C7F-0EFA089DA664/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:11:01.082 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:11:01.085 ThaliTest[2313:7445278] server: starting JQ6i2aeI0mdeePtIc-qbjA.Fp3Wjg==
2016-02-02 13:11:01.085 ThaliTest[2313:7445278] multipeer session: start timer: 0x1d6a7400
2016-02-02 13:11:01.086 ThaliTest[2313:7445278] THEMultipeerSessio,n initialized peer JQ6i2aeI0mdeePtIc-qbjA
2016-02-02 13:11:01.086 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-02 13:11:01.088 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:11:01.088 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
,2016-02-02 13:11:01.088 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:11:01.095 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/61362FC7-6451-48A7-8C7F-0EFA089DA664/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-02 13:11:06.025 ThaliTest[2313:7445278] jxcore: startBroadcasting
,2016-02-02 13:11:06.029 ThaliTest[2313:7445278] server: starting JQ6i2aeI0mdeePtIc-qbjA.UblVHA==
2016-02-02 13:11:06.029 ThaliTest[2313:7445278] multipeer session: start timer: 0x1cf85620
2016-02-02 13:11:06.030 ThaliTest[2313:7445278] THEMultipeerSessio,n initialized peer JQ6i2aeI0mdeePtIc-qbjA
2016-02-02 13:11:06.030 ThaliTest[2313:7445278] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-02 13:11:06.098 ThaliTest[2313:7445076] client: found peer: DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:15.939 ThaliTest[2313:7445278] jxcore: connect DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:15.941 ThaliTest[2313:7445278] client session: connect
,2016-02-02 13:11:15.942 ThaliTest[2313:7445278] client session: stateChange:0->1 DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:16.062 ThaliTest[2313:7445076] multipeer session: reset timer
2016-02-02 13:11:16.062 ThaliTest[2313:7445076] multipeer session: stop timer
2016-02-02 13:11:16.062 ThaliTest[2313:7445076] multipeer session: start timer: 0x1cf85620
2016-02-02 13:11:16.063 ThaliTest[2313:7445076] server session: connect
,2016-02-02 13:11:16.063 ThaliTest[2313:7445076] server session: stateChange:0->1 DtRsu22HVgBakRtUz9QTCw
,2016-02-02 13:11:16.069 ThaliTest[2313:7445076] server: accepting invitation DtRsu22HVgBakRtUz9QTCw
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-02 13:11:18.958 ThaliTest[2313:7445897] server session: connected
2016-02-02 13:11:18.958 ThaliTest[2313:7445897] server session: stateChange:1->2 DtRsu22HVgBakRtUz9QTCw
,2016-02-02 13:11:18.964 ThaliTest[2313:7445076] server relay: connected (to port: 61058)
,server bridge: new client socket

,2016-02-02 13:11:19.158 ThaliTest[2313:7445865] client session: connected
2016-02-02 13:11:19.158 ThaliTest[2313:7445865] client session: stateChange:1->2 DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:19.172 ThaliTest[2313:7445902] client session: fireConnectCallback: DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
2016-02-02 13:11:19.172 ThaliTest[2313:7445902] jxcore: connect: success
,2016-02-02 13:11:19.179 ThaliTest[2313:7445076] client: relay established
2016-02-02 13:11:19.181 ThaliTest[2313:7445076] client: new accepted socket: 0x16dca730
,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed
,
,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket

,client bridge: socket closed

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: 'cfbb9e67-a228-4c37-aaef-d6a9e5c4ac10',
  rev: '2-4c7957b34c6f3252cb8dcaef8d20f153' }

,client bridge: new client socket
,
,client bridge: new client socket
,
,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 126 Local changes occur in strict order
,
,ok 127 2nd change of local doc should contain remote id
,
,# setup

,client bridge: new client socket
,
,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-02 13:11:36.656 ThaliTest[2313:7445278] jxcore: stopBroadcasting
2016-02-02 13:11:36.656 ThaliTest[2313:7445278] THEMultipeerSession stopping peer
2016-02-02 1,3:11:36.656 ThaliTest[2313:7445278] multipeer session: stop timer
2016-02-02 13:11:36.657 ThaliTest[2313:7445278] client session: disconnect
2016-02-02 13:11:36.657 ThaliTest[2313:7445278] client session: stateChange:2->0 DtRsu22HVgBakRtUz9QTCw.gDbjyQ==
,2016-02-02 13:11:36.681 ThaliTest[2313:7445278] server session: disconnect
2016-02-02 13:11:36.681 ThaliTest[2313:7445278] server session: stateChange:2->0 DtRsu22HVgBakRtUz9QTCw
,2016-02-02 13:11:36.769 ThaliTest[2313:7445278] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,mux server bridge listener closed

,client bridge: socket closed

,server bridge: socket closed

,client bridge: socket closed

,client bridge: socket closed


```
