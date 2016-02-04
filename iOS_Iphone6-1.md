#### Test 58135655a685cd3_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/50572A84-773E-490C-A54D-1366D5526C5F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/50572A84-773E-490C-A54D-1366D5526C5F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50062"
,(lldb)     command script import "/tmp/50572A84-773E-490C-A54D-1366D5526C5F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-04 14:03:21.777 ThaliTest[1219:2191830] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/30F27E2F-A32B-4F31-BAD8-288AB878D9AF/Library/Cookies/Cookies.binarycookies
,2016-02-04 14:03:22.170 ThaliTest[1219:2191830] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 14:03:22.172 ThaliTest[1219:2191830] Multi-tasking -> Device: YES, App: YES
,2016-02-04 14:03:22.181 ThaliTest[1219:2191830] Unlimited access to network resources
,2016-02-04 14:03:22.192 ThaliTest[1219:2191830] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 14:03:31.844 ThaliTest[1219:2191830] Resetting plugins due to page load.
,2016-02-04 14:03:35.549 ThaliTest[1219:2191830] Finished load of: file:///var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/index.html
,2016-02-04 14:03:35.753 ThaliTest[1219:2191830] JXcore Cordova plugin initializing
,2016-02-04 14:03:35.756 ThaliTest[1219:2192187] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4BCE8D37-1892-4B0D-92C0-C516E82F06D5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,appEnteringBackground wasn't registered

,TAP version 13

,# setup

,got: setup_multiplex can send data

,ack: setup_multiplex can send data_ok

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,got: setup_enqueue and run in order

ack: setup_enqueue and run in order_ok

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

,got: setup_basic

,ack: setup_basic_ok

,# teardown

,ok 11 sane

,# setup

,# another

,got: setup_another

,ack: setup_another_ok

,# teardown

,ok 12 sane

,# setup

,# successfully create a new pkcs12 file and return hash value

,got: setup_successfully create a new pkcs12 file and return hash value

,ack: setup_successfully create a new pkcs12 file and return hash value_ok

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

,ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,got: setup_successfully read a previous pkcs12 file and return hash value

ack: setup_successfully read a previous pkcs12 file and return hash value_ok

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

ok 20 should not throw

,ok 21 should be equal

ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,got: setup_failed to extract public key because of corrupt pkcs12 file

ack: setup_failed to extract public key because of corrupt pkcs12 file_ok

,# teardown

,ok 23 should be equal

,# setup

,# failed to get mobile documents path

,got: setup_failed to get mobile documents path

ack: setup_failed to get mobile documents path_ok

,# teardown

,ok 24 should be equal

,# setup

,# #init should register the peerAvailabilityChanged event

,got: setup_#init should register the peerAvailabilityChanged event

ack: setup_#init should register the peerAvailabilityChanged event_ok

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,got: setup_#init should register the networkChanged event

ack: setup_#init should register the networkChanged event_ok

,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,got: setup_#startBroadcasting should throw on null device name

ack: setup_#startBroadcasting should throw on null device name_ok

,# teardown

,ok 29 should throw

,# setup

,# #startBroadcasting should throw on empty string device name

,got: setup_#startBroadcasting should throw on empty string device name

,ack: setup_#startBroadcasting should throw on empty string device name_ok

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,got: setup_#startBroadcasting should throw on non-number port

,ack: setup_#startBroadcasting should throw on non-number port_ok

,# teardown

,ok 31 should throw

,# setup

,# #startBroadcasting should throw on NaN port

,got: setup_#startBroadcasting should throw on NaN port

,ack: setup_#startBroadcasting should throw on NaN port_ok

,# teardown

,ok 32 should throw

,# setup

,# #startBroadcasting should throw on negative port

,got: setup_#startBroadcasting should throw on negative port

,ack: setup_#startBroadcasting should throw on negative port_ok

,# teardown

,ok 33 should throw

,# setup

,# #startBroadcasting should throw on too large port

,got: setup_#startBroadcasting should throw on too large port

ack: setup_#startBroadcasting should throw on too large port_ok

,# teardown

,ok 34 should throw

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,got: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok

,# teardown

,ok 35 should be equal

,ok 36 should be equal

,ok 37 should be equal

,# setup

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,got: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error_ok

,# teardown

,ok 38 should be equal

,ok 39 should be equal

,ok 40 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

,ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok

,# teardown

,ok 43 should be equal

,ok 44 should be equal

,# setup

,# #connect should call Mobile("Connect") with a port and without an error

,got: setup_#connect should call Mobile("Connect") with a port and without an error

,ack: setup_#connect should call Mobile("Connect") with a port and without an error_ok

,# teardown

,ok 45 should be equal

,ok 46 should be equal

,ok 47 should be equal

,# setup

,# #connect should call Mobile("Connect") and handle an error

,got: setup_#connect should call Mobile("Connect") and handle an error

ack: setup_#connect should call Mobile("Connect") and handle an error_ok

,# teardown

,ok 48 should be equal

,ok 49 should be equal

,# setup

,# should call Mobile("Disconnect") without an error

,got: setup_should call Mobile("Disconnect") without an error

ack: setup_should call Mobile("Disconnect") without an error_ok

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,got: setup_should call Mobile("Disconnect") and handle an error

,ack: setup_should call Mobile("Disconnect") and handle an error_ok

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok

,# teardown

,2016-02-04 14:08:36.633 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.650 ThaliTest[1219:2192187] server: starting 1454591316633.1219.4DT/aQ==
,2016-02-04 14:08:36.651 ThaliTest[1219:2192187] multipeer session: start timer: 0x18626e60
2016-02-04 14:08:36.652 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316633.1219
2016-02-04 14:08:36.652 ThaliTest[1219:2192187] jxcore: sta,rtBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

2016-02-04 14:08:36.655 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:08:36.656 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04, 14:08:36.656 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:08:36.656 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-04 14:08:36.658 ThaliTest[1219:21,92187] jxcore: startBroadcasting
,2016-02-04 14:08:36.666 ThaliTest[1219:2192187] server: starting 1454591316658.1219.Sg1wZg==
2016-02-04 14:08:36.666 ThaliTest[1219:2192187] multipeer session: start timer: 0x1857bc20
2016-02-04 14:08:36.667 ThaliTest[1219:2192187] THEMultipeerSession in,itialized peer 1454591316658.1219
2016-02-04 14:08:36.667 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-04 14:08:36.669 ThaliTest[1219:2192187] jxcore: stopBroadcasting,
2016-02-04 14:08:36.670 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:08:36.671 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.679 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
ok 57 Should be able to call stopBroadcasting without error

2016-02-04 14:08:36.683 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.696 ThaliTest[1219:2192187] server: starting 1454591316682.1219.sJ6rPw==
,2016-02-04 14:08:36.706 ThaliTest[1219:2192187] multipeer session: start timer: 0x194dfbc0
,2016-02-04 14:08:36.713 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316682.1219
,2016-02-04 14:08:36.715 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 58 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.718 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.719 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.721 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.726 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.730 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.734 ThaliTest[1219:2192187] server: starting 1454591316729.1219.EGQlfg==
,2016-02-04 14:08:36.740 ThaliTest[1219:2192187] multipeer session: start timer: 0x194dc590
,2016-02-04 14:08:36.744 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316729.1219
,2016-02-04 14:08:36.747 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.750 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.751 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.752 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.755 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.758 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.761 ThaliTest[1219:2192187] server: starting 1454591316758.1219.K7QuUw==
,2016-02-04 14:08:36.763 ThaliTest[1219:2192187] multipeer session: start timer: 0x1828b690
,2016-02-04 14:08:36.768 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316758.1219
,2016-02-04 14:08:36.769 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 62 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.771 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.772 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.773 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.776 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.779 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.782 ThaliTest[1219:2192187] server: starting 1454591316778.1219.DdLklA==
,2016-02-04 14:08:36.785 ThaliTest[1219:2192187] multipeer session: start timer: 0x1938e910
,2016-02-04 14:08:36.788 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316778.1219
,2016-02-04 14:08:36.790 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.793 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.795 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.795 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.798 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.802 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.805 ThaliTest[1219:2192187] server: starting 1454591316801.1219.JG/TzA==
,2016-02-04 14:08:36.807 ThaliTest[1219:2192187] multipeer session: start timer: 0x184ad660
,2016-02-04 14:08:36.812 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316801.1219
,2016-02-04 14:08:36.813 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.815 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.816 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.817 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.818 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,
,2016-02-04 14:08:36.823 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.826 ThaliTest[1219:2192187] server: starting 1454591316822.1219.Kg54Hw==
,2016-02-04 14:08:36.827 ThaliTest[1219:2192187] multipeer session: start timer: 0x194dfe40
,2016-02-04 14:08:36.829 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316822.1219
,2016-02-04 14:08:36.829 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.837 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.837 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.839 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.840 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.845 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.848 ThaliTest[1219:2192187] server: starting 1454591316845.1219.6jQmRQ==
,2016-02-04 14:08:36.849 ThaliTest[1219:2192187] multipeer session: start timer: 0x194e06b0
,2016-02-04 14:08:36.854 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316845.1219
,2016-02-04 14:08:36.855 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-04 14:08:36.857 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.857 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.858 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.861 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:36.863 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:36.865 ThaliTest[1219:2192187] server: starting 1454591316863.1219.Dkd/zQ==
,2016-02-04 14:08:36.867 ThaliTest[1219:2192187] multipeer session: start timer: 0x184ad200
,2016-02-04 14:08:36.868 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591316863.1219
,2016-02-04 14:08:36.869 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-02-04 14:08:36.873 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:36.873 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:36.874 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:36.876 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

,ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok
,
,# teardown

,2016-02-04 14:08:37.159 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:37.164 ThaliTest[1219:2192187] server: starting 1454591317158.1219.hRUfFw==
,2016-02-04 14:08:37.168 ThaliTest[1219:2192187] multipeer session: start timer: 0x194456d0
,2016-02-04 14:08:37.173 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591317158.1219
,2016-02-04 14:08:37.176 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-04 14:08:37.180 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:37.181 ThaliTest[1219:2192187] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-04 14:08:37.189 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:08:37.190 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:08:37.191 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:08:37.194 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-04 14:08:37.619 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:37.623 ThaliTest[1219:2192187] server: starting 1454591317619.1219.aULMbQ==
2016-02-04 14:08:37.624 ThaliTest[1219:2192187] multipeer session: start timer: 0x18698730
2016-02-04 14:08:37.624 ThaliTest[1219:2192187] THEMultipeerSession in,itialized peer 1454591317619.1219
2016-02-04 14:08:37.624 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-04 14:08:37.627 ThaliTest[1219:2192187] jxcore: connect foobar
2,016-02-04 14:08:37.627 ThaliTest[1219:2192187] client: unknown peer foobar
2016-02-04 14:08:37.627 ThaliTest[1219:2192187] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-04 14:08:37.633 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:08:37.633 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:08:37.634 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:08:37.634 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

,ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-04 14:08:39.603 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:39.606 ThaliTest[1219:2192187] server: starting 1454591319602.1219.0IKuTg==
2016-02-04 14:08:39.607 ThaliTest[1219:2192187] multipeer session: start timer: 0x1959f830
2016-02-04 14:08:39.607 ThaliTest[1219:2192187] THEMultipeerSession in,itialized peer 1454591319602.1219
2016-02-04 14:08:39.608 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-04 14:08:39.610 ThaliTest[1219:2192187] jxcore: disconnect
2016-02-04 14:08:39.610 ThaliTest[1219:2192187] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-04 14:08:39.616 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:08:39.617 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:08:39.617 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:08:39.,617 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

,ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-04 14:08:40.545 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:40.549 ThaliTest[1219:2192187] server: starting 1454591320545.1219.6wynUQ==
2016-02-04 14:08:40.550 ThaliTest[1219:2192187] multipeer session: start timer: 0x190106b0
2016-02-04 14:08:40.550 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591320545.1219
2016-02-04 14:08:40.550 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-04 14:08:42.089 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:08:42.090 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:08:42.090 ThaliTest[1219:2191830] multipeer session: start timer: 0x190106b0
,2016-02-04 14:08:42.091 ThaliTest[1219:2191830] server session: connect
,2016-02-04 14:08:42.091 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591323801.641
,2016-02-04 14:08:42.102 ThaliTest[1219:2191830] server: accepting invitation 1454591323801.641
2016-02-04 14:08:42.104 ThaliTest[1219:2191830] client: found peer: 1454591323801.641.noJRcg==
2016-02-04 14:08:42.106 ThaliTest[1219:2192187] jxcore: connect ,1454591323801.641.noJRcg==
2016-02-04 14:08:42.107 ThaliTest[1219:2192187] client session: connect
2016-02-04 14:08:42.107 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591323801.641.noJRcg==
,2016-02-04 14:08:45.020 ThaliTest[1219:2192756] server session: connected
2016-02-04 14:08:45.021 ThaliTest[1219:2192756] server session: stateChange:1->2 1454591323801.641
,2016-02-04 14:08:45.035 ThaliTest[1219:2191830] server relay: socket disconnected
,2016-02-04 14:08:45.036 ThaliTest[1219:2191830] server relay: 0x16ddf1a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:08:45.104 ThaliTest[1219:2192756] server session: not connected 1454591323801.641
,2016-02-04 14:08:45.310 ThaliTest[1219:2192756] client session: connected
,2016-02-04 14:08:45.311 ThaliTest[1219:2192756] client session: stateChange:1->2 1454591323801.641.noJRcg==
,2016-02-04 14:08:45.363 ThaliTest[1219:2192753] client session: fireConnectCallback: 1454591323801.641.noJRcg==
2016-02-04 14:08:45.363 ThaliTest[1219:2192753] jxcore: connect: success
ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-04 14:08:45.369 ThaliTest[1219:2192187] jxcore: disconnect
2016-02-04 14:08:45.369 ThaliTest[1219:2192187] client session: disconnectFromPeer: 1454591323801.641.noJRcg==
2016-02-04 14:08:45.370 ThaliTest[1219:2192187] client session: disconnect
,2016-02-04 14:08:45.370 ThaliTest[1219:2192187] client session: stateChange:2->0 1454591323801.641.noJRcg==
,2016-02-04 14:08:45.381 ThaliTest[1219:2192187] jxcore: disconnect: success
ok 86 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 14:08:45.444 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:08:45.445 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:08:45.445 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:08:45.,446 ThaliTest[1219:2192187] server session: disconnect
2016-02-04 14:08:45.446 ThaliTest[1219:2192187] server session: stateChange:2->0 1454591323801.641
2016-02-04 14:08:45.447 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

# ThaliEmitter can discover and connect to peers and then fail on double connect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-04 14:08:59.089 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:08:59.092 ThaliTest[1219:2192187] server: starting 1454591339088.1219.inLX2Q==
2016-02-04 14:08:59.093 ThaliTest[1219:2192187] multipeer session: start timer: 0x16db9e30
2016-02-04 14:08:59.093 ThaliTest[1219:2192187] THEMultipeerSession in,itialized peer 1454591339088.1219
2016-02-04 14:08:59.094 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-04 14:08:59.111 ThaliTest[1219:2191830] client: found peer: 1454591340670.641.ch05nQ==
,2016-02-04 14:08:59.120 ThaliTest[1219:2192187] jxcore: connect 1454591340670.641.ch05nQ==
,2016-02-04 14:08:59.121 ThaliTest[1219:2192187] client session: connect
,2016-02-04 14:08:59.123 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591340670.641.ch05nQ==
,2016-02-04 14:09:00.092 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:00.092 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:09:00.093 ThaliTest[1219:2191830] multipeer session: start timer: 0x16db9e30
2016-,02-04 14:09:00.093 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:00.093 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591340670.641
,2016-02-04 14:09:00.100 ThaliTest[1219:2191830] server: accepting invitation 1454591340670.641
,2016-02-04 14:09:02.147 ThaliTest[1219:2192837] client session: connected
2016-02-04 14:09:02.148 ThaliTest[1219:2192837] client session: stateChange:1->2 1454591340670.641.ch05nQ==
,2016-02-04 14:09:02.190 ThaliTest[1219:2192798] client session: fireConnectCallback: 1454591340670.641.ch05nQ==
2016-02-04 14:09:02.190 ThaliTest[1219:2192798] jxcore: connect: success
,ok 88 Should be able to connect without error

ok 89 Port should be within range

,2016-02-04 14:09:02.195 ThaliTest[1219:2192187] jxcore: connect 1454591340670.641.ch05nQ==
2016-02-04 14:09:02.195 ThaliTest[1219:2192187] client: already connect(ing/ed) to 1454591340670.641.ch05nQ==
2016-02-04 14:09:02.195 ThaliTest[1219:2192187] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect
,
,2016-02-04 14:09:02.205 ThaliTest[1219:2192187] jxcore: disconnect
,2016-02-04 14:09:02.207 ThaliTest[1219:2192187] client session: disconnectFromPeer: 1454591340670.641.ch05nQ==
,2016-02-04 14:09:02.208 ThaliTest[1219:2192187] client session: disconnect
,2016-02-04 14:09:02.209 ThaliTest[1219:2192187] client session: stateChange:2->0 1454591340670.641.ch05nQ==
,2016-02-04 14:09:02.287 ThaliTest[1219:2192187] jxcore: disconnect: success
ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 14:09:02.768 ThaliTest[1219:2192798] server session: connected
2016-02-04 14:09:02.768 ThaliTest[1219:2192798] server session: stateChange:1->2 1454591340670.641
,2016-02-04 14:09:02.798 ThaliTest[1219:2191830] server relay: socket disconnected
2016-02-04 14:09:02.798 ThaliTest[1219:2191830] server relay: 0x192b83e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:09:02.837 ThaliTest[1219:2192837] server session: not connected 1454591340670.641
,calling stopBroadcasting

,2016-02-04 14:09:02.860 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:09:02.861 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:09:02.862 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:09:02.863 ThaliTest[1219:2192187] server session: disconnect
2016-02-04 14:09:02.864 ThaliTest[1219:2192187] server session: stateChange:2->0 1454591340670.641
,2016-02-04 14:09:02.865 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-04 14:09:05.275 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:05.279 ThaliTest[1219:2192187] server: starting 1454591345275.1219.8JsXAQ==
2016-02-04 14:09:05.280 ThaliTest[1219:2192187] multipeer session: start timer: 0x1979ed80
2016-02-04 14:09:05.280 ThaliTest[1219:2192187] THEMultipeerSession in,itialized peer 1454591345275.1219
2016-02-04 14:09:05.281 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-04 14:09:06.161 ThaliTest[1219:2191830] client: found peer: 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:06.163 ThaliTest[1219:2192187] jxcore: connect 1454591348406.641.sA/FUQ==
2016-02-04 14:09:06.164 ThaliTest[1219:2192187] client session: connect
2016-02-04 14:09:06.164 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:06.995 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:06.995 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:09:06.995 ThaliTest[1219:2191830] multipeer session: start timer: 0x1979ed80
2016-,02-04 14:09:06.996 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:06.996 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591348406.641
,2016-02-04 14:09:07.006 ThaliTest[1219:2191830] server: accepting invitation 1454591348406.641
,2016-02-04 14:09:09.472 ThaliTest[1219:2192798] client session: connected
2016-02-04 14:09:09.472 ThaliTest[1219:2192798] client session: stateChange:1->2 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:09.477 ThaliTest[1219:2192798] client session: fireConnectCallback: 1454591348406.641.sA/FUQ==
2016-02-04 14:09:09.477 ThaliTest[1219:2192798] jxcore: connect: success
ok 93 Should be able to connect without error

,ok 94 Port should be within range

2016-02-04 14:09:09.482 ThaliTest[1219:2192187] jxcore: disconnect
2016-02-04 14:09:09.482 ThaliTest[1219:2192187] client session: disconnectFromPeer: 1454591348406.641.sA/FUQ==
2016-02-04 14:09:09.483 ThaliTest[1219:,2192187] client session: disconnect
2016-02-04 14:09:09.483 ThaliTest[1219:2192187] client session: stateChange:2->0 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:09.495 ThaliTest[1219:2192187] jxcore: disconnect: success
ok 95 Should be able to disconnect without error

2016-02-04 14:09:09.498 ThaliTest[1219:2192187] jxcore: disconnect
2016-02-04 14:09:09.498 ThaliTest[1219:2192187] jxcore: dis,connect: fail
ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 14:09:09.857 ThaliTest[1219:2192837] server session: connected
2016-02-04 14:09:09.857 ThaliTest[1219:2192837] server session: stateChange:1->2 1454591348406.641
,2016-02-04 14:09:09.863 ThaliTest[1219:2191830] server relay: socket disconnected
2016-02-04 14:09:09.864 ThaliTest[1219:2191830] server relay: 0x16e2c030 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:09:09.934 ThaliTest[1219:2192818] server session: not connected 1454591348406.641
,calling stopBroadcasting

,2016-02-04 14:09:10.082 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:09:10.082 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:09:10.083 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:09:10.,083 ThaliTest[1219:2192187] server session: disconnect
2016-02-04 14:09:10.083 ThaliTest[1219:2192187] server session: stateChange:2->0 1454591348406.641
,2016-02-04 14:09:10.089 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

,ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 56706

,2016-02-04 14:09:10.731 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:10.732 ThaliTest[1219:2192187] server: starting 1454591350730.1219.09eirA==
,2016-02-04 14:09:10.733 ThaliTest[1219:2192187] multipeer session: start timer: 0x1972be70
,2016-02-04 14:09:10.736 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591350730.1219
,2016-02-04 14:09:10.736 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-04 14:09:11.863 ThaliTest[1219:2191830] client: found peer: 1454591354054.641.NC190g==
2016-02-04 14:09:11.864 ThaliTest[1219:2192187] jxcore: connect 1454591354054.641.NC190g==
2016-02-04 14:09:11.865 ThaliTest[1219:2192187] client session: conn,ect
2016-02-04 14:09:11.865 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591354054.641.NC190g==
,2016-02-04 14:09:12.105 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:12.106 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:09:12.106 ThaliTest[1219:2191830] multipeer session: start timer: 0x1972be70
2016-02-04 14:09:12.106 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:12.107 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591354054.641
,2016-02-04 14:09:12.116 ThaliTest[1219:2191830] server: accepting invitation 1454591354054.641
,2016-02-04 14:09:12.191 ThaliTest[1219:2191830] client: found peer: 1454591348406.641.sA/FUQ==
2016-02-04 14:09:12.192 ThaliTest[1219:2192187] jxcore: connect 1454591348406.641.sA/FUQ==
2016-02-04 14:09:12.192 ThaliTest[1219:2192187] client session: connect
2016-02-04 14:09:12.192 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:14.892 ThaliTest[1219:2192798] server session: connected
2016-02-04 14:09:14.892 ThaliTest[1219:2192798] server session: stateChange:1->2 1454591354054.641
,2016-02-04 14:09:14.912 ThaliTest[1219:2191830] server relay: connected (to port: 56706)
,2016-02-04 14:09:15.048 ThaliTest[1219:2192817] client session: connected
,2016-02-04 14:09:15.049 ThaliTest[1219:2192817] client session: stateChange:1->2 1454591354054.641.NC190g==
,2016-02-04 14:09:15.052 ThaliTest[1219:2192817] client session: fireConnectCallback: 1454591354054.641.NC190g==
,2016-02-04 14:09:15.053 ThaliTest[1219:2192817] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-04 14:09:15.058 ThaliTest[1219:2191830] client: relay established
,2016-02-04 14:09:15.059 ThaliTest[1219:2191830] client: new accepted socket: 0x185601e0
,data in 10950

,data in 17520

,data in 31755

,data in 35040

,data in 49133

,data in 62273

,data in 65700

2016-02-04 14:09:15.303 ThaliTest[1219:2192836] server session: not connected 1454591354054.641
,data in 86505

,data in 104025

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 14:09:15.337 ThaliTest[1219:2192187] jxcore: disconnect
2016-02-04 14:09:15.337 ThaliTest[1219:2192187] client session: disconnectFromPeer: 1454591354054.641.NC190g==
2016-02-04 14:09:15.337 ThaliTest[1219:2192187] client session: disconnect
2016-02-04 14:09:15.337 ThaliTest[1219:2192187] client session: stateChange:2->0 1454591354054.641.NC190g==
,2016-02-04 14:09:15.342 ThaliTest[1219:2192187] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 14:09:15.359 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:09:15.359 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:09:15.360 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:09:15.,360 ThaliTest[1219:2192187] client session: disconnect
2016-02-04 14:09:15.360 ThaliTest[1219:2192187] client session: stateChange:1->0 1454591348406.641.sA/FUQ==
2016-02-04 14:09:15.360 ThaliTest[1219:2192187] server session: disconnect
2016-02-04 14:09:15.361 ThaliTest[1219:2192187] server session: stateChange:2->0 1454591354054.641
,2016-02-04 14:09:15.363 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,got: setup_ThaliEmitter handles socket disconnect correctly

ack: setup_ThaliEmitter handles socket disconnect correctly_ok

,# teardown

,echo server started on port: 56713

,2016-02-04 14:09:16.363 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:16.367 ThaliTest[1219:2192187] server: starting 1454591356362.1219.3jvSOA==
2016-02-04 14:09:16.367 ThaliTest[1219:2192187] multipeer session: start timer: 0x185621a0
2016-02-04 14:09:16.368 ThaliTest[1219:2192187] THEMultipeerSession initialized peer 1454591356362.1219
2016-02-04 14:09:16.368 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-04 14:09:17.032 ThaliTest[1219:2191830] client: found peer: 1454591354054.641.NC190g==
[{"peerIdentifier":"1454591354054.641.NC190g==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 14:09:17.035 ThaliTest[1219:2192187] jxcore: connect 1454591354054.641.NC190g==
,2016-02-04 14:09:17.035 ThaliTest[1219:2192187] client session: connect
,2016-02-04 14:09:17.036 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591354054.641.NC190g==
,2016-02-04 14:09:17.677 ThaliTest[1219:2191830] client: found peer: 1454591359488.641.myjmpQ==
[{"peerIdentifier":"1454591359488.641.myjmpQ==","peerName":"(null)","peerAvailable":true}]

2016-02-04 14:09:17.679 ThaliTest[1219:2192187] jxcore: connect 1454591359488.641.myjmpQ==
2016-02-04 14:09:17.679 ThaliTest[1219:2192187] client session: connect
,2016-02-04 14:09:17.680 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591359488.641.myjmpQ==
,2016-02-04 14:09:18.079 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:18.079 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:09:18.079 ThaliTest[1219:2191830] multipeer session: start timer: 0x185621a0
2016-,02-04 14:09:18.080 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:18.080 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591359488.641
,2016-02-04 14:09:18.091 ThaliTest[1219:2191830] server: accepting invitation 1454591359488.641
,2016-02-04 14:09:21.218 ThaliTest[1219:2192837] server session: connected
,2016-02-04 14:09:21.218 ThaliTest[1219:2192837] server session: stateChange:1->2 1454591359488.641
,2016-02-04 14:09:21.385 ThaliTest[1219:2191830] server relay: connected (to port: 56713)
,2016-02-04 14:09:21.677 ThaliTest[1219:2192836] client session: connected
2016-02-04 14:09:21.678 ThaliTest[1219:2192836] client session: stateChange:1->2 1454591359488.641.myjmpQ==
,2016-02-04 14:09:21.737 ThaliTest[1219:2192836] client session: fireConnectCallback: 1454591359488.641.myjmpQ==
2016-02-04 14:09:21.738 ThaliTest[1219:2192836] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-04 14:09:21.774 ThaliTest[1219:2191830] client: relay established
2016-02-04 14:09:21.774 ThaliTest[1219:2191830] client: new accepted socket: 0x186d2d50
,2016-02-04 14:09:21.803 ThaliTest[1219:2192837] server session: not connected 1454591359488.641
,2016-02-04 14:09:21.855 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:21.855 ThaliTest[1219:2191830] multipeer session: stop timer
,2016-02-04 14:09:21.856 ThaliTest[1219:2191830] multipeer session: start timer: 0x185621a0
2016-02-04 14:09:21.856 ThaliTest[1219:2191830] server: disconnecting to refresh session (1454591359488.641)
2016-02-04 14:09:21.856 ThaliTest[1219:2191830] server session: disconnect
,2016-02-04 14:09:21.857 ThaliTest[1219:2191830] server session: stateChange:2->0 1454591359488.641
,2016-02-04 14:09:21.861 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:21.862 ThaliTest[1219:2191830] server session: stateChange:0->1 1454591359488.641
,2016-02-04 14:09:21.874 ThaliTest[1219:2191830] server: accepting invitation 1454591359488.641
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-04 14:09:22.140 ThaliTest[1219:2191830] client: socket closed
2016-02-04 14:09:22.140 ThaliTest[1219:2191830] client relay: socket disconnected
2016-02-04 14:09:22.140 ThaliTest[1219:2191830] client relay: 0x186d2d50 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 14:09:22.140 ThaliTest[1219:2191830] client session: socket closed: 1454591359488.641.myjmpQ==
2016-02-04 1,4:09:22.140 ThaliTest[1219:2191830] client session: onLinkFailure: 1454591359488.641.myjmpQ==
2016-02-04 14:09:22.141 ThaliTest[1219:2191830] client session: disconnect
2016-02-04 14:09:22.141 ThaliTest[1219:2191830] client session: stateChange:2->0 1454591359488.641.myjmpQ==
,2016-02-04 14:09:22.147 ThaliTest[1219:2191830] client session: fireConnectionErrorEvent: 1454591359488.641.myjmpQ==
,2016-02-04 14:09:22.149 ThaliTest[1219:2192187] jxcore: connect 1454591359488.641.myjmpQ==
2016-02-04 14:09:22.150 ThaliTest[1219:2192187] client session: connect
2016-02-04 14:09:22.150 ThaliTest[1219:2192187] client session: stateChange:0->1 1454591359488.641.myjmpQ==
,2016-02-04 14:09:23.605 ThaliTest[1219:2192837] server session: connected
2016-02-04 14:09:23.607 ThaliTest[1219:2192837] server session: stateChange:1->2 1454591359488.641
,2016-02-04 14:09:23.851 ThaliTest[1219:2191830] server relay: connected (to port: 56713)
,2016-02-04 14:09:24.936 ThaliTest[1219:2192817] server session: not connected 1454591359488.641
,2016-02-04 14:09:24.952 ThaliTest[1219:2192817] client session: connected
2016-02-04 14:09:24.952 ThaliTest[1219:2192817] client session: stateChange:1->2 1454591359488.641.myjmpQ==
,2016-02-04 14:09:25.292 ThaliTest[1219:2192798] client session: fireConnectCallback: 1454591359488.641.myjmpQ==
,2016-02-04 14:09:25.292 ThaliTest[1219:2192798] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-04 14:09:25.328 ThaliTest[1219:2191830] client: relay established
2016-02-04 14:09:25.330 ThaliTest[1219:2191830] client: new accepted socket: 0x195e34c0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-04 14:09:26.483 ThaliTest[1219:2191830] client: socket closed
2016-02-04 14:09:26.483 ThaliTest[1219:2191830] client relay: socket disconnected
2016-02-04 14:09:26.484 ThaliTest[1219:2191830] client relay: 0x195e34c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 14:09:26.484 ThaliTest[1219:2191830] client session: socket closed: 1454591359488.641.myjmpQ==
2016-02-04 1,4:09:26.484 ThaliTest[1219:2191830] client session: onLinkFailure: 1454591359488.641.myjmpQ==
2016-02-04 14:09:26.484 ThaliTest[1219:2191830] client session: disconnect
2016-02-04 14:09:26.485 ThaliTest[1219:2191830] client session: stateChange:2->0 1454591359488.641.myjmpQ==
,2016-02-04 14:09:26.497 ThaliTest[1219:2191830] client session: fireConnectionErrorEvent: 1454591359488.641.myjmpQ==
,calling stopBroadcasting

,2016-02-04 14:09:26.850 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:09:26.851 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:09:26.851 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:09:26.,852 ThaliTest[1219:2192187] client session: disconnect
2016-02-04 14:09:26.852 ThaliTest[1219:2192187] client session: stateChange:1->0 1454591354054.641.NC190g==
2016-02-04 14:09:26.853 ThaliTest[1219:2192187] server session: disconnect
2016-02-04 14:09:26.853 ThaliTest[1219:2192187] server session: stateChange:2->0 1454591359488.641
,2016-02-04 14:09:26.865 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliReplicationManager can call start without error

,got: setup_ThaliReplicationManager can call start without error

,ack: setup_ThaliReplicationManager can call start without error_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/30F27E2F-A32B-4F31-BAD8-288AB878D9AF/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-04 14:09:27.303 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:27.304 ThaliTest[1219:2192187] server: starting bkGtE0JgcDBPSL8Zec_DPw.oqsv9A==
2016-02-04 14:09:27.304 ThaliTest[1219:2192187] multipeer session: start timer: 0x18792600
2016-02-04 14:09:27.305 ThaliTest[1219:2192187] THEMultipeerSessio,n initialized peer bkGtE0JgcDBPSL8Zec_DPw
2016-02-04 14:09:27.305 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

2016-02-04 14:09:27.306 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:09:27.306 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
2016-02-04 14:09:27.306 ThaliTest[1219:2192187] multipeer session: stop timer
2016-02-04 14:09:27.306 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

ok 116 stopped event should occur in right order

,mux server bridge listener closed

# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/30F27E2F-A32B-4F31-BAD8-288AB878D9AF/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 14:09:27.896 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:27.899 ThaliTest[1219:2192187] server: starting bkGtE0JgcDBPSL8Zec_DPw.crCOeg==
2016-02-04 14:09:27.900 ThaliTest[1219:2192187] multipeer session: start timer: 0x195ec1e0
2016-02-04 14:09:27.901 ThaliTest[1219:2192187] THEMultipeerSessio,n initialized peer bkGtE0JgcDBPSL8Zec_DPw
2016-02-04 14:09:27.901 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

,ok 118 deviceName should not be null

Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

2016-02-04 14:09:27.906 ThaliTest[1219:2192187] jxcore: stopBroadcasting
2016-02-04 14:09:27.907 ThaliTest[1219:2192187] THEMult,ipeerSession stopping peer
2016-02-04 14:09:27.907 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:09:27.907 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

,ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/30F27E2F-A32B-4F31-BAD8-288AB878D9AF/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 14:09:30.780 ThaliTest[1219:2192187] jxcore: startBroadcasting
,2016-02-04 14:09:30.781 ThaliTest[1219:2192187] server: starting bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,2016-02-04 14:09:30.782 ThaliTest[1219:2192187] multipeer session: start timer: 0x19589ff0
,2016-02-04 14:09:30.785 ThaliTest[1219:2192187] THEMultipeerSession initialized peer bkGtE0JgcDBPSL8Zec_DPw
,2016-02-04 14:09:30.786 ThaliTest[1219:2192187] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-04 14:09:31.870 ThaliTest[1219:2191830] client: found peer: 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:35.456 ThaliTest[1219:2192187] jxcore: connect 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:35.457 ThaliTest[1219:2192187] client session: connect
2016-02-04 14:09:35.457 ThaliTest[1219:2192187] client session: stateChange:0->1 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:35.486 ThaliTest[1219:2191830] multipeer session: reset timer
2016-02-04 14:09:35.486 ThaliTest[1219:2191830] multipeer session: stop timer
2016-02-04 14:09:35.486 ThaliTest[1219:2191830] multipeer session: start timer: 0x19589ff0
2016-02-04 14:09:35.486 ThaliTest[1219:2191830] server session: connect
2016-02-04 14:09:35.486 ThaliTest[1219:2191830] server session: stateChange:0->1 28j3I1BY4BW26VLKmOHvnA
,2016-02-04 14:09:35.490 ThaliTest[1219:2191830] server: accepting invitation 28j3I1BY4BW26VLKmOHvnA
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-04 14:09:38.444 ThaliTest[1219:2192798] server session: connected
,2016-02-04 14:09:38.447 ThaliTest[1219:2192798] server session: stateChange:1->2 28j3I1BY4BW26VLKmOHvnA
,2016-02-04 14:09:38.452 ThaliTest[1219:2191830] server relay: connected (to port: 56730)
,server bridge: new client socket

,2016-02-04 14:09:38.701 ThaliTest[1219:2192837] client session: connected
2016-02-04 14:09:38.701 ThaliTest[1219:2192837] client session: stateChange:1->2 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:38.713 ThaliTest[1219:2192837] client session: fireConnectCallback: 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
2016-02-04 14:09:38.713 ThaliTest[1219:2192837] jxcore: connect: success
,2016-02-04 14:09:38.724 ThaliTest[1219:2191830] client: relay established
2016-02-04 14:09:38.724 ThaliTest[1219:2191830] client: new accepted socket: 0x18746c50
,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed

client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket
,
,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: 'e723e545-ceec-4f32-a991-9c0d34fc9f74',
  rev: '2-367581171653364957238c9cf7f5ea4a' }
,
,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed
,
,client bridge: socket closed

,client bridge: new client socket
,
,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket
,
,Now in TRM stop

State of this._isStarted: true
,
About to call stopBroadcasting

,2016-02-04 14:09:52.049 ThaliTest[1219:2192187] jxcore: stopBroadcasting
,2016-02-04 14:09:52.050 ThaliTest[1219:2192187] THEMultipeerSession stopping peer
,2016-02-04 14:09:52.051 ThaliTest[1219:2192187] multipeer session: stop timer
,2016-02-04 14:09:52.052 ThaliTest[1219:2192187] client session: disconnect
,2016-02-04 14:09:52.053 ThaliTest[1219:2192187] client session: stateChange:2->0 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:52.121 ThaliTest[1219:2192187] server session: disconnect
,2016-02-04 14:09:52.121 ThaliTest[1219:2192187] server session: stateChange:2->0 28j3I1BY4BW26VLKmOHvnA
,2016-02-04 14:09:52.127 ThaliTest[1219:2192837] server session: not connected 28j3I1BY4BW26VLKmOHvnA
,2016-02-04 14:09:52.189 ThaliTest[1219:2192187] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,client bridge: socket closed

,mux server bridge listener closed

,2016-02-04 14:09:52.278 ThaliTest[1219:2192187] Error!: connect ECONNREFUSED
Stack:[{"_fileName":"net.js","_functionName":"$c","_lineNumber":"837","_columnNumber":"7","_msg":"    at $c@net.js:837:7"},{"_fileName":"net.js","_functionName":"$09","_lineNumber":"829","_columnNumber":"13","_msg":"    at $09@net.js:829:13"},{"_fileName":"net.js","_functionName":"unknown","_lineNumber":"837","_columnNumber":"7","_msg":""}]
,Uncaught Exception: Error: connect ECONNREFUSED

,[ { _fileName: 'net.js',
    _functionName: '$c',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '    at $c@net.js:837:7' },
  { _fileName: 'net.js',
    _functionName: '$09',
    _lineNumber: '829',
    _columnNumber: '13',
    _msg: '    at $09@net.js:829:13' },
  { _fileName: 'net.js',
    _functionName: 'unknown',
    _lineNumber: '837',
    _columnNumber: '7',
    _msg: '' },
  toString: [Function] ]

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****


```
