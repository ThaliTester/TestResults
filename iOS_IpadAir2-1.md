#### Test 58135655a685cd3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/29A3C9F7-C5F1-41B6-9913-8C55B4D65E86/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/29A3C9F7-C5F1-41B6-9913-8C55B4D65E86/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655a685cd3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50060"
,(lldb)     command script import "/tmp/29A3C9F7-C5F1-41B6-9913-8C55B4D65E86/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-02-04 14:03:26.440 ThaliTest[641:974730] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC8C57FE-0730-4F66-B553-96E9AECC98C6/Library/Cookies/Cookies.binarycookies
,2016-02-04 14:03:26.860 ThaliTest[641:974730] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-04 14:03:26.861 ThaliTest[641:974730] Multi-tasking -> Device: YES, App: YES
,2016-02-04 14:03:26.870 ThaliTest[641:974730] Unlimited access to network resources
,2016-02-04 14:03:26.879 ThaliTest[641:974730] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-04 14:03:36.800 ThaliTest[641:974730] Resetting plugins due to page load.
,2016-02-04 14:03:40.785 ThaliTest[641:974730] Finished load of: file:///var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/index.html
,2016-02-04 14:03:40.939 ThaliTest[641:974730] JXcore Cordova plugin initializing
,2016-02-04 14:03:40.940 ThaliTest[641:974978] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/88770C80-CC00-4FC6-84A4-4E1C32EAFBE2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,got: setup_multiplex can send data

,ack: setup_multiplex can send data_ok

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

ack: setup_basic_ok

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

ack: setup_successfully create a new pkcs12 file and return hash value_ok

,# teardown

,ok 13 should be equal

,ok 14 null

,ok 15 (unnamed assert)

ok 16 should be equal

,ok 17 should not throw

,# setup

,# successfully read a previous pkcs12 file and return hash value

,got: setup_successfully read a previous pkcs12 file and return hash value

,ack: setup_successfully read a previous pkcs12 file and return hash value_ok

,# teardown

,ok 18 (unnamed assert)

,ok 19 (unnamed assert)

,ok 20 should not throw

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

,ack: setup_failed to get mobile documents path_ok

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

ack: setup_#startBroadcasting should throw on empty string device name_ok

,# teardown

,ok 30 should throw

,# setup

,# #startBroadcasting should throw on non-number port

,got: setup_#startBroadcasting should throw on non-number port

ack: setup_#startBroadcasting should throw on non-number port_ok

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

ack: setup_#startBroadcasting should throw on negative port_ok

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

,ack: setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error_ok

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

ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok

,# teardown

,ok 41 should be equal

,ok 42 should be equal

,# setup

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,got: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error_ok

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

,2016-02-04 14:08:39.768 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.785 ThaliTest[641:974978] server: starting 1454591319768.641.C/VnmA==
,2016-02-04 14:08:39.786 ThaliTest[641:974978] multipeer session: start timer: 0xd22860
2016-02-04 14:08:39.787 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319768.641
2016-02-04 14:08:39.787 ThaliTest[641:974978] jxcore: startBroadca,sting: success
ok 54 Should be able to call startBroadcasting without error

,2016-02-04 14:08:39.791 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:39.791 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:39.792 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.793 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 55 Should be able to call stopBroadcasting without error

2016-02-04 14:08:39.799 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.803 ThaliTest[641:974978] server: starting 1454591319799.641.JrmJRw==
,2016-02-04 14:08:39.807 ThaliTest[641:974978] multipeer session: start timer: 0x89d56c0
2016-02-04 14:08:39.807 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319799.641
2016-02-04 14:08:39.808 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 56 Should be able to call startBroadcasting without error

,2016-02-04 14:08:39.811 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:08:39.811 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.812 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.812 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 57 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.815 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.819 ThaliTest[641:974978] server: starting 1454591319814.641.62a5Ag==
2016-02-04 14:08:39.820 ThaliTest[641:974978] multipeer session: start timer: 0x84c6bb0
2016-02-04 14:08:39.820 ThaliTest[641:974978] THEMultipeerSession initialize,d peer 1454591319814.641
2016-02-04 14:08:39.820 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 58 Should be able to call startBroadcasting without error

2016-02-04 14:08:39.822 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 1,4:08:39.823 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.823 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.824 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 59 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.827 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.831 ThaliTest[641:974978] server: starting 1454591319826.641.SqLh2g==
2016-02-04 14:08:39.833 ThaliTest[641:974978] multipeer session: start timer: 0x93706b0
2016-02-04 14:08:39.833 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319826.641
2016-02-04 14:08:39.834 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 60 Should be able to call startBroadcasting without error

2016-02-04 14:08:39.837 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:08:39.838 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.838 ThaliTest[641:9,74978] multipeer session: stop timer
2016-02-04 14:08:39.839 ThaliTest[641:974978] jxcore: stopBroadcasting: success
ok 61 Should be able to call stopBroadcasting without error

2016-02-04 14:08:39.841 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.847 ThaliTest[641:974978] server: starting 1454591319840.641.ZgVl9w==
2016-02-04 14:08:39.847 ThaliTest[641:974978] multipeer session: start timer: 0xcecda0
2016-02-04 14:08:39.848 ThaliTest[641:974978] THEMultipeerSession initialized, peer 1454591319840.641
2016-02-04 14:08:39.848 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

2016-02-04 14:08:39.850 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14,:08:39.851 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.851 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.851 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 63 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.854 ThaliTest[641:974978] jxcore: startBroadcasting
2016-02-04 14:08:39.857 ThaliTest[641:974978] server: starting 1454591319853.641.2/DMiQ==
2016-02-04 14:08:39.858 ThaliTest[641:974978] multipeer session: start timer: 0xd4b4c0
2016-02-04 14:08:39.858 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319853.641
,2016-02-04 14:08:39.860 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 64 Should be able to call startBroadcasting without error

2016-02-04 14:08:39.862 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:08:39.862 ThaliTest[641:,974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.862 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.863 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.865 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.870 ThaliTest[641:974978] server: starting 1454591319864.641.y/skNg==
,2016-02-04 14:08:39.871 ThaliTest[641:974978] multipeer session: start timer: 0xd4c2b0
,2016-02-04 14:08:39.872 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319864.641
,2016-02-04 14:08:39.873 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 66 Should be able to call startBroadcasting without error

,2016-02-04 14:08:39.877 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:08:39.877 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:39.878 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:08:39.878 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

2016-02-04 14:08:39.881 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.884 ThaliTest[641:974978] server: starting 1454591319880.641.0FvuIA==
,2016-02-04 14:08:39.885 ThaliTest[641:974978] multipeer session: start timer: 0xd4bc00
,2016-02-04 14:08:39.886 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319880.641
,2016-02-04 14:08:39.887 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-04 14:08:39.890 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:39.891 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:39.892 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:39.895 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.897 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.900 ThaliTest[641:974978] server: starting 1454591319897.641.VVqpcQ==
,2016-02-04 14:08:39.902 ThaliTest[641:974978] multipeer session: start timer: 0xd4bcd0
,2016-02-04 14:08:39.905 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319897.641
,2016-02-04 14:08:39.908 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-04 14:08:39.911 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:39.912 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:39.913 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:39.914 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-04 14:08:39.918 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:39.921 ThaliTest[641:974978] server: starting 1454591319918.641.vSyfZg==
,2016-02-04 14:08:39.923 ThaliTest[641:974978] multipeer session: start timer: 0xd4c630
,2016-02-04 14:08:39.926 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591319918.641
2016-02-04 14:08:39.926 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error
,
,2016-02-04 14:08:39.930 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:39.930 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:39.931 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:39.932 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok

,# teardown

,2016-02-04 14:08:40.572 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:40.576 ThaliTest[641:974978] server: starting 1454591320572.641.1EQqcg==
,2016-02-04 14:08:40.577 ThaliTest[641:974978] multipeer session: start timer: 0xcefd20
2016-02-04 14:08:40.577 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591320572.641
2016-02-04 14:08:40.578 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-04 14:08:40.581 ThaliTest[641:974978] jxcore: startBroadcasting
2016-02-04 14:08:40.581 ThaliTest[641:974978] jxcore: startBroadcasting: failure
ok 75 Cannot call startBroadcasting twice

,2016-02-04 14:08:40.586 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:08:40.587 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:40.587 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:40.588 ThaliTest[641:974978] jxcore: stopBroadcasting: success
ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

,ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-04 14:08:40.764 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:40.768 ThaliTest[641:974978] server: starting 1454591320764.641.mBVMPw==
,2016-02-04 14:08:40.768 ThaliTest[641:974978] multipeer session: start timer: 0xcde620
,2016-02-04 14:08:40.769 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591320764.641
2016-02-04 14:08:40.770 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

,2016-02-04 14:08:40.772 ThaliTest[641:974978] jxcore: connect foobar
2016-02-04 14:08:40.773 ThaliTest[641:974978] client: unknown peer foobar
2016-02-04 14:08:40.773 ThaliTest[641:974978] jxcore: connect: fail: Unknown peer
,ok 78 Should not connect to a bad peer

,2016-02-04 14:08:40.779 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:40.779 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:08:40.779 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:40.780 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-04 14:08:42.323 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:42.326 ThaliTest[641:974978] server: starting 1454591322322.641.LNvzsA==
,2016-02-04 14:08:42.327 ThaliTest[641:974978] multipeer session: start timer: 0xa018210
,2016-02-04 14:08:42.328 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591322322.641
2016-02-04 14:08:42.330 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 80 Should be able to call startBroadcasting without error

,2016-02-04 14:08:42.332 ThaliTest[641:974978] jxcore: disconnect
2016-02-04 14:08:42.333 ThaliTest[641:974978] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 

,2016-02-04 14:08:42.340 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:42.340 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:42.341 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:42.342 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-04 14:08:43.801 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:08:43.805 ThaliTest[641:974978] server: starting 1454591323801.641.noJRcg==
,2016-02-04 14:08:43.806 ThaliTest[641:974978] multipeer session: start timer: 0x8ee6d10
,2016-02-04 14:08:43.807 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591323801.641
2016-02-04 14:08:43.807 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 83 Should be able to call startBroadcasting without error

,2016-02-04 14:08:44.635 ThaliTest[641:974730] client: found peer: 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:44.637 ThaliTest[641:974978] jxcore: connect 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:44.638 ThaliTest[641:974978] client session: connect
,2016-02-04 14:08:44.638 ThaliTest[641:974978] client session: stateChange:0->1 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:45.418 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:08:45.418 ThaliTest[641:974730] multipeer session: stop timer
2016-02-04 14:08:45.419 ThaliTest[641:974730] multipeer session: start timer: 0x8ee6d10
2016-02-04 1,4:08:45.419 ThaliTest[641:974730] server session: connect
2016-02-04 14:08:45.419 ThaliTest[641:974730] server session: stateChange:0->1 1454591320545.1219
,2016-02-04 14:08:45.426 ThaliTest[641:974730] server: accepting invitation 1454591320545.1219
,2016-02-04 14:08:48.133 ThaliTest[641:975508] client session: connected
2016-02-04 14:08:48.133 ThaliTest[641:975508] client session: stateChange:1->2 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:48.168 ThaliTest[641:975508] client session: fireConnectCallback: 1454591320545.1219.6wynUQ==
2016-02-04 14:08:48.168 ThaliTest[641:975508] jxcore: connect: success
,ok 84 Should be able to connect without error

,ok 85 Port should be within range

,2016-02-04 14:08:48.173 ThaliTest[641:974978] jxcore: disconnect
,2016-02-04 14:08:48.173 ThaliTest[641:974978] client session: disconnectFromPeer: 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:48.175 ThaliTest[641:974978] client session: disconnect
,2016-02-04 14:08:48.175 ThaliTest[641:974978] client session: stateChange:2->0 1454591320545.1219.6wynUQ==
,2016-02-04 14:08:48.185 ThaliTest[641:974978] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 14:08:48.433 ThaliTest[641:975554] server session: connected
,2016-02-04 14:08:48.434 ThaliTest[641:975554] server session: stateChange:1->2 1454591320545.1219
,2016-02-04 14:08:48.490 ThaliTest[641:974730] server relay: socket disconnected
2016-02-04 14:08:48.490 ThaliTest[641:974730] server relay: 0xa006230 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:08:48.561 ThaliTest[641:975520] server session: not connected 1454591320545.1219
,calling stopBroadcasting

,2016-02-04 14:08:48.573 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:08:48.574 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:08:48.575 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:08:48.576 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:08:48.577 ThaliTest[641:974978] server session: stateChange:2->0 1454591320545.1219
,2016-02-04 14:08:48.581 ThaliTest[641:974978] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-04 14:09:00.670 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:00.674 ThaliTest[641:974978] server: starting 1454591340670.641.ch05nQ==
,2016-02-04 14:09:00.675 ThaliTest[641:974978] multipeer session: start timer: 0x8fcc710
,2016-02-04 14:09:00.675 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591340670.641
,2016-02-04 14:09:00.676 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 87 Should be able to call startBroadcasting without error

,2016-02-04 14:09:02.423 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:02.423 ThaliTest[641:974730] multipeer session: stop timer
2016-02-04 14:09:02.424 ThaliTest[641:974730] multipeer session: start timer: 0x8fcc710
2016-02-04 14:09:02.424 ThaliTest[641:974730] server session: connect
,2016-02-04 14:09:02.424 ThaliTest[641:974730] server session: stateChange:0->1 1454591339088.1219
,2016-02-04 14:09:02.431 ThaliTest[641:974730] server: accepting invitation 1454591339088.1219
,2016-02-04 14:09:03.112 ThaliTest[641:974730] client: found peer: 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:03.113 ThaliTest[641:974978] jxcore: connect 1454591339088.1219.inLX2Q==
2016-02-04 14:09:03.114 ThaliTest[641:974978] client session: connect
2016-02-04 14:09:03.114 ThaliTest[641:974978] client session: stateChange:0->1 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:05.297 ThaliTest[641:975577] server session: connected
,2016-02-04 14:09:05.298 ThaliTest[641:975577] server session: stateChange:1->2 1454591339088.1219
,2016-02-04 14:09:05.302 ThaliTest[641:974730] server relay: socket disconnected
2016-02-04 14:09:05.302 ThaliTest[641:974730] server relay: 0xde2cd0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalized,FailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-04 14:09:05.366 ThaliTest[641:975577] server session: not connected 1454591339088.1219
,2016-02-04 14:09:05.910 ThaliTest[641:975577] client session: connected
2016-02-04 14:09:05.910 ThaliTest[641:975577] client session: stateChange:1->2 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:05.915 ThaliTest[641:975577] client session: fireConnectCallback: 1454591339088.1219.inLX2Q==
2016-02-04 14:09:05.916 ThaliTest[641:975577] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-04 14:09:05.920 ThaliTest[641:974978] jxcore: connect 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:05.920 ThaliTest[641:974978] client: already connect(ing/ed) to 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:05.921 ThaliTest[641:974978] jxcore: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-04 14:09:05.925 ThaliTest[641:974978] jxcore: disconnect
2016-02-04 14:09:05.926 ThaliTest[641:974978] client session: disconnectFromPeer: 1454591339088.1219.inLX2Q==
2016-02-04 14:09:05.926 ThaliTest[641:974978] client session: disconnect
2016-,02-04 14:09:05.927 ThaliTest[641:974978] client session: stateChange:2->0 1454591339088.1219.inLX2Q==
,2016-02-04 14:09:05.937 ThaliTest[641:974978] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 14:09:06.389 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:09:06.389 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:09:06.390 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:09:06.391 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:09:06.391 ThaliTest[641:974978] server session: stateChange:2->0 1454591339088.1219
,2016-02-04 14:09:06.958 ThaliTest[641:974978] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-04 14:09:08.407 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:08.411 ThaliTest[641:974978] server: starting 1454591348406.641.sA/FUQ==
,2016-02-04 14:09:08.411 ThaliTest[641:974978] multipeer session: start timer: 0x84b4cc0
,2016-02-04 14:09:08.412 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591348406.641
,2016-02-04 14:09:08.412 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 92 Should be able to call startBroadcasting without error

,2016-02-04 14:09:09.797 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:09.797 ThaliTest[641:974730] multipeer session: stop timer
2016-02-04 14:09:09.797 ThaliTest[641:974730] multipeer session: start timer: 0x84b4cc0
,2016-02-04 14:09:09.798 ThaliTest[641:974730] server session: connect
2016-02-04 14:09:09.798 ThaliTest[641:974730] server session: stateChange:0->1 1454591345275.1219
,2016-02-04 14:09:09.805 ThaliTest[641:974730] server: accepting invitation 1454591345275.1219
,2016-02-04 14:09:09.974 ThaliTest[641:974730] client: found peer: 1454591345275.1219.8JsXAQ==
2016-02-04 14:09:09.975 ThaliTest[641:974978] jxcore: connect 1454591345275.1219.8JsXAQ==
,2016-02-04 14:09:09.975 ThaliTest[641:974978] client session: connect
,2016-02-04 14:09:09.976 ThaliTest[641:974978] client session: stateChange:0->1 1454591345275.1219.8JsXAQ==
,2016-02-04 14:09:12.574 ThaliTest[641:975578] server session: connected
2016-02-04 14:09:12.574 ThaliTest[641:975578] server session: stateChange:1->2 1454591345275.1219
,2016-02-04 14:09:12.609 ThaliTest[641:974730] server relay: socket disconnected
,2016-02-04 14:09:12.610 ThaliTest[641:974730] server relay: 0x8f38350 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection ref,used} 
,2016-02-04 14:09:12.654 ThaliTest[641:975578] server session: not connected 1454591345275.1219
,2016-02-04 14:09:12.975 ThaliTest[641:975606] client session: connected
2016-02-04 14:09:12.976 ThaliTest[641:975606] client session: stateChange:1->2 1454591345275.1219.8JsXAQ==
,2016-02-04 14:09:12.993 ThaliTest[641:975606] client session: fireConnectCallback: 1454591345275.1219.8JsXAQ==
2016-02-04 14:09:12.994 ThaliTest[641:975606] jxcore: connect: success
,ok 93 Should be able to connect without error

,ok 94 Port should be within range

,2016-02-04 14:09:12.998 ThaliTest[641:974978] jxcore: disconnect
,2016-02-04 14:09:12.999 ThaliTest[641:974978] client session: disconnectFromPeer: 1454591345275.1219.8JsXAQ==
,2016-02-04 14:09:12.999 ThaliTest[641:974978] client session: disconnect
,2016-02-04 14:09:13.000 ThaliTest[641:974978] client session: stateChange:2->0 1454591345275.1219.8JsXAQ==
,2016-02-04 14:09:13.010 ThaliTest[641:974978] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-04 14:09:13.014 ThaliTest[641:974978] jxcore: disconnect
,2016-02-04 14:09:13.015 ThaliTest[641:974978] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-04 14:09:13.209 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:09:13.210 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:09:13.211 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:09:13.212 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:09:13.212 ThaliTest[641:974978] server session: stateChange:2->0 1454591345275.1219
,2016-02-04 14:09:13.218 ThaliTest[641:974978] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

,ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 53070

,2016-02-04 14:09:14.054 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:14.055 ThaliTest[641:974978] server: starting 1454591354054.641.NC190g==
,2016-02-04 14:09:14.055 ThaliTest[641:974978] multipeer session: start timer: 0x8f42890
2016-02-04 14:09:14.056 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591354054.641
2016-02-04 14:09:14.056 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 97 Should be able to call startBroadcasting without error

,2016-02-04 14:09:14.967 ThaliTest[641:974730] client: found peer: 1454591350730.1219.09eirA==
,2016-02-04 14:09:14.969 ThaliTest[641:974978] jxcore: connect 1454591350730.1219.09eirA==
2016-02-04 14:09:14.970 ThaliTest[641:974978] client session: connect
,2016-02-04 14:09:14.970 ThaliTest[641:974978] client session: stateChange:0->1 1454591350730.1219.09eirA==
,2016-02-04 14:09:15.254 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:15.254 ThaliTest[641:974730] multipeer session: stop timer
,2016-02-04 14:09:15.255 ThaliTest[641:974730] multipeer session: start timer: 0x8f42890
,2016-02-04 14:09:15.255 ThaliTest[641:974730] server session: connect
,2016-02-04 14:09:15.255 ThaliTest[641:974730] server session: stateChange:0->1 1454591350730.1219
,2016-02-04 14:09:15.262 ThaliTest[641:974730] server: accepting invitation 1454591350730.1219
,2016-02-04 14:09:18.014 ThaliTest[641:975632] client session: connected
2016-02-04 14:09:18.014 ThaliTest[641:975632] client session: stateChange:1->2 1454591350730.1219.09eirA==
,2016-02-04 14:09:18.044 ThaliTest[641:975578] client session: fireConnectCallback: 1454591350730.1219.09eirA==
2016-02-04 14:09:18.044 ThaliTest[641:975578] jxcore: connect: success
,ok 98 Should be able to connect without error

,ok 99 Port should be within range

,2016-02-04 14:09:18.050 ThaliTest[641:974730] client: relay established
2016-02-04 14:09:18.051 ThaliTest[641:974730] client: new accepted socket: 0x5417000
,data in 2190

,data in 5475

,data in 6570

,data in 7665

,data in 24090

,2016-02-04 14:09:18.168 ThaliTest[641:975577] server session: connected
2016-02-04 14:09:18.168 ThaliTest[641:975577] server session: stateChange:1->2 1454591350730.1219
,data in 62415

,2016-02-04 14:09:18.184 ThaliTest[641:974730] server relay: connected (to port: 53070)
,data in 75555

,data in 87600

,data in 97455

,data in 102930

,data in 114975

,data in 131072

,ok 100 the test messages should be equal

,2016-02-04 14:09:18.388 ThaliTest[641:974978] jxcore: disconnect
,2016-02-04 14:09:18.388 ThaliTest[641:974978] client session: disconnectFromPeer: 1454591350730.1219.09eirA==
2016-02-04 14:09:18.388 ThaliTest[641:974978] client session: disconnect
2016-02-04 14:09:18.389 ThaliTest[641:974978] client session: stateChange:2->0 1454591350730.1219.09eirA==
,2016-02-04 14:09:18.395 ThaliTest[641:974978] jxcore: disconnect: success
ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-04 14:09:18.490 ThaliTest[641:975605] server session: not connected 1454591350730.1219
,calling stopBroadcasting

2016-02-04 14:09:18.498 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:09:18.498 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:09:18.498 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:09:18.498 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:09:18.498 ThaliTest[641:974978] server session: stateChange:2->0 1454591350730.1219
,2016-02-04 14:09:18.502 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter handles socket disconnect correctly

,got: setup_ThaliEmitter handles socket disconnect correctly

,ack: setup_ThaliEmitter handles socket disconnect correctly_ok

,# teardown

,echo server started on port: 53076

,2016-02-04 14:09:19.489 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:19.492 ThaliTest[641:974978] server: starting 1454591359488.641.myjmpQ==
,2016-02-04 14:09:19.493 ThaliTest[641:974978] multipeer session: start timer: 0xa073030
2016-02-04 14:09:19.493 ThaliTest[641:974978] THEMultipeerSession initialized peer 1454591359488.641
2016-02-04 14:09:19.494 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 102 Should be able to call startBroadcasting without error

,2016-02-04 14:09:20.158 ThaliTest[641:974730] client: found peer: 1454591350730.1219.09eirA==
,[{"peerIdentifier":"1454591350730.1219.09eirA==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 14:09:20.161 ThaliTest[641:974978] jxcore: connect 1454591350730.1219.09eirA==
2016-02-04 14:09:20.162 ThaliTest[641:974978] client session: connect
,2016-02-04 14:09:20.162 ThaliTest[641:974978] client session: stateChange:0->1 1454591350730.1219.09eirA==
,2016-02-04 14:09:20.680 ThaliTest[641:974730] client: found peer: 1454591356362.1219.3jvSOA==
,[{"peerIdentifier":"1454591356362.1219.3jvSOA==","peerName":"(null)","peerAvailable":true}]

,2016-02-04 14:09:20.682 ThaliTest[641:974978] jxcore: connect 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:20.682 ThaliTest[641:974978] client session: connect
,2016-02-04 14:09:20.683 ThaliTest[641:974978] client session: stateChange:0->1 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:21.597 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:21.597 ThaliTest[641:974730] multipeer session: stop timer
2016-02-04 14:09:21.597 ThaliTest[641:974730] multipeer session: start timer: 0xa073030
2016-02-04 1,4:09:21.598 ThaliTest[641:974730] server session: connect
2016-02-04 14:09:21.598 ThaliTest[641:974730] server session: stateChange:0->1 1454591356362.1219
2016-02-04 14:09:21.603 ThaliTest[641:974730] server: accepting invitation 1454591356362.1219
,2016-02-04 14:09:24.478 ThaliTest[641:975606] client session: connected
2016-02-04 14:09:24.478 ThaliTest[641:975606] client session: stateChange:1->2 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:24.752 ThaliTest[641:975606] client session: fireConnectCallback: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:24.753 ThaliTest[641:975606] jxcore: connect: success
,ok 103 Should be able to connect without error

ok 104 Port should be within range

,ok 105 First connect should succeed

,2016-02-04 14:09:24.794 ThaliTest[641:974730] client: relay established
2016-02-04 14:09:24.795 ThaliTest[641:974730] client: new accepted socket: 0xc342600
,2016-02-04 14:09:24.853 ThaliTest[641:975606] server session: connected
2016-02-04 14:09:24.854 ThaliTest[641:975606] server session: stateChange:1->2 1454591356362.1219
,ok 106 the test messages should be equal

,ok 107 First send should succeed

,2016-02-04 14:09:24.876 ThaliTest[641:974730] client: socket closed
,2016-02-04 14:09:24.877 ThaliTest[641:974730] client relay: socket disconnected
,2016-02-04 14:09:24.877 ThaliTest[641:974730] client relay: 0xc342600 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-02-04 14:09:24.877 ThaliTest[641:974730] client session: socket closed: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:24.878 ThaliTest[641:974730] client session: onLinkFailure: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:24.878 ThaliTest[641:974730] client session: disconnect
2016-02-04 14:09:24.878 ThaliTest[641:974730] client session: stateChange:2->0 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:24.890 ThaliTest[641:974730] client session: fireConnectionErrorEvent: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:24.893 ThaliTest[641:974978] jxcore: connect 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:24.893 ThaliTest[641:974978] client session: connect
2016-02-04 14:09:24.896 ThaliTest[641:974978] client session: stateChange:0->1 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:25.223 ThaliTest[641:974730] server relay: connected (to port: 53076)
,2016-02-04 14:09:25.304 ThaliTest[641:975576] server session: not connected 1454591356362.1219
,2016-02-04 14:09:25.971 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:25.972 ThaliTest[641:974730] multipeer session: stop timer
2016-02-04 14:09:25.972 ThaliTest[641:974730] multipeer session: start timer: 0xa073030
,2016-02-04 14:09:25.972 ThaliTest[641:974730] server: disconnecting to refresh session (1454591356362.1219)
2016-02-04 14:09:25.973 ThaliTest[641:974730] server session: disconnect
2016-02-04 14:09:25.973 ThaliTest[641:974730] server session: stateChange:2->0 1454591356362.1219
,2016-02-04 14:09:26.163 ThaliTest[641:974730] server session: connect
2016-02-04 14:09:26.164 ThaliTest[641:974730] server session: stateChange:0->1 1454591356362.1219
,2016-02-04 14:09:26.170 ThaliTest[641:974730] server: accepting invitation 1454591356362.1219
,2016-02-04 14:09:26.914 ThaliTest[641:975605] client session: connected
2016-02-04 14:09:26.914 ThaliTest[641:975605] client session: stateChange:1->2 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:26.975 ThaliTest[641:975606] client session: fireConnectCallback: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:26.975 ThaliTest[641:975606] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-04 14:09:27.011 ThaliTest[641:974730] client: relay established
2016-02-04 14:09:27.011 ThaliTest[641:974730] client: new accepted socket: 0xaa97da0
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-04 14:09:27.986 ThaliTest[641:974730] client: socket closed
,2016-02-04 14:09:27.987 ThaliTest[641:974730] client relay: socket disconnected
2016-02-04 14:09:27.987 ThaliTest[641:974730] client relay: 0xaa97da0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-04 14:09:27.987 ThaliTest[641:974730] client session: socket closed: 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:27.988 ThaliTest[641:974730] client session: onLinkFailure: 1454591356362.1219.3jvSOA==
2016-02-04 14:09:27.989 ThaliTest[641:974730] client session: disconnect
2016-02-04 14:09:27.989 ThaliTest[641:974730] client session: stateChange:2-,>0 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:28.001 ThaliTest[641:974730] client session: fireConnectionErrorEvent: 1454591356362.1219.3jvSOA==
,2016-02-04 14:09:28.359 ThaliTest[641:975605] server session: connected
2016-02-04 14:09:28.359 ThaliTest[641:975605] server session: stateChange:1->2 1454591356362.1219
,2016-02-04 14:09:28.364 ThaliTest[641:974730] server relay: connected (to port: 53076)
,2016-02-04 14:09:29.652 ThaliTest[641:975633] server session: not connected 1454591356362.1219
,calling stopBroadcasting

,2016-02-04 14:09:29.981 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:09:29.982 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:09:29.982 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:09:29.983 ThaliTest[641:974978] client session: disconnect
2016-02-04 14:09:29.983 ThaliTest[641:974978] client session: stateChange:1->0 1454591350730.1219.09eirA==
2016-02-04 14:09:29.984 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:09:29.984 ThaliTest[641:974978] server session: stateChange:2->0 1454591356362.1219
,2016-02-04 14:09:29.989 ThaliTest[641:974978] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,got: setup_ThaliReplicationManager can call start without error

,ack: setup_ThaliReplicationManager can call start without error_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FC8C57FE-0730-4F66-B553-96E9AECC98C6/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-04 14:09:30.480 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:30.481 ThaliTest[641:974978] server: starting 28j3I1BY4BW26VLKmOHvnA.PrN5gg==
,2016-02-04 14:09:30.482 ThaliTest[641:974978] multipeer session: start timer: 0x5418530
2016-02-04 14:09:30.482 ThaliTest[641:974978] THEMultipeerSession initialized peer 28j3I1BY4BW26VLKmOHvnA
2016-02-04 14:09:30.482 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 114 started event should occur in right order

Now in TRM stop

,State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-04 14:09:30.484 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:09:30.484 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:09:30.484 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:09:30.484 ThaliTest[641:974978] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FC8C57FE-0730-4F66-B553-96E9AECC98C6/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue":{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 14:09:31.023 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:31.027 ThaliTest[641:974978] server: starting 28j3I1BY4BW26VLKmOHvnA.0rVw5w==
,2016-02-04 14:09:31.028 ThaliTest[641:974978] multipeer session: start timer: 0xd82580
,2016-02-04 14:09:31.028 ThaliTest[641:974978] THEMultipeerSession initialized peer 28j3I1BY4BW26VLKmOHvnA
2016-02-04 14:09:31.029 ThaliTest[641:974978] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

,Now in TRM stop

,State of this._isStarted: true

,About to call stopBroadcasting

,2016-02-04 14:09:31.034 ThaliTest[641:974978] jxcore: stopBroadcasting
2016-02-04 14:09:31.034 ThaliTest[641:974978] THEMultipeerSession stopping peer
2016-02-04 14:09:31.035 ThaliTest[641:974978] multipeer session: stop timer
2016-02-04 14:09:31.035 ThaliTest[641:974978] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

,ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/FC8C57FE-0730-4F66-B553-96E9AECC98C6/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-04 14:09:33.678 ThaliTest[641:974978] jxcore: startBroadcasting
,2016-02-04 14:09:33.679 ThaliTest[641:974978] server: starting 28j3I1BY4BW26VLKmOHvnA.5+IY5w==
,2016-02-04 14:09:33.680 ThaliTest[641:974978] multipeer session: start timer: 0x54afa00
2016-02-04 14:09:33.680 ThaliTest[641:974978] THEMultipeerSession initialized peer 28j3I1BY4BW26VLKmOHvnA
2016-02-04 14:09:33.680 ThaliTest[641:974978] jxcore: startBroadcasting: success
,ok 119 getDeviceIdentity should not return an error

,ok 120 deviceName should not be null

,2016-02-04 14:09:34.899 ThaliTest[641:974730] client: found peer: bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,2016-02-04 14:09:37.879 ThaliTest[641:974978] jxcore: connect bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,2016-02-04 14:09:37.879 ThaliTest[641:974978] client session: connect
2016-02-04 14:09:37.879 ThaliTest[641:974978] client session: stateChange:0->1 bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-04 14:09:38.679 ThaliTest[641:974730] multipeer session: reset timer
2016-02-04 14:09:38.679 ThaliTest[641:974730] multipeer session: stop timer
,2016-02-04 14:09:38.679 ThaliTest[641:974730] multipeer session: start timer: 0x54afa00
2016-02-04 14:09:38.680 ThaliTest[641:974730] server session: connect
,2016-02-04 14:09:38.680 ThaliTest[641:974730] server session: stateChange:0->1 bkGtE0JgcDBPSL8Zec_DPw
,2016-02-04 14:09:38.688 ThaliTest[641:974730] server: accepting invitation bkGtE0JgcDBPSL8Zec_DPw
,2016-02-04 14:09:41.565 ThaliTest[641:975577] client session: connected
2016-02-04 14:09:41.565 ThaliTest[641:975577] client session: stateChange:1->2 bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,2016-02-04 14:09:41.584 ThaliTest[641:975633] client session: fireConnectCallback: bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
2016-02-04 14:09:41.584 ThaliTest[641:975633] jxcore: connect: success
,2016-02-04 14:09:41.597 ThaliTest[641:974730] client: relay established
2016-02-04 14:09:41.598 ThaliTest[641:974730] client: new accepted socket: 0x8f17770
,client bridge: new client socket

,client bridge: new client socket

,2016-02-04 14:09:41.806 ThaliTest[641:975633] server session: connected
2016-02-04 14:09:41.807 ThaliTest[641:975633] server session: stateChange:1->2 bkGtE0JgcDBPSL8Zec_DPw
,2016-02-04 14:09:41.880 ThaliTest[641:974730] server relay: connected (to port: 53092)
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

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: '410ca3d8-ac95-488e-914c-17a1f1a37f06',
  rev: '2-6d5918203c3e3add90f36c097b8b2d4d' }

,client bridge: new client socket

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,ok 126 Local changes occur in strict order

ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,2016-02-04 14:09:55.207 ThaliTest[641:975795] server session: not connected bkGtE0JgcDBPSL8Zec_DPw
,Now in TRM stop

,State of this._isStarted: true

About to call stopBroadcasting

,2016-02-04 14:09:55.216 ThaliTest[641:974978] jxcore: stopBroadcasting
,2016-02-04 14:09:55.216 ThaliTest[641:974978] THEMultipeerSession stopping peer
,2016-02-04 14:09:55.217 ThaliTest[641:974978] multipeer session: stop timer
,2016-02-04 14:09:55.218 ThaliTest[641:974978] client session: disconnect
2016-02-04 14:09:55.218 ThaliTest[641:974978] client session: stateChange:2->0 bkGtE0JgcDBPSL8Zec_DPw.BqdAjA==
,2016-02-04 14:09:55.225 ThaliTest[641:974978] server session: disconnect
2016-02-04 14:09:55.226 ThaliTest[641:974978] server session: stateChange:2->0 bkGtE0JgcDBPSL8Zec_DPw
,2016-02-04 14:09:55.245 ThaliTest[641:974978] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined
,
,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,Error in mux client bridge Error: write EPIPE

,mux server bridge listener closed

,syncRetry called when not started

client bridge: socket closed

,server bridge: socket closed

,client bridge: socket closed

,got: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ack: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted_ok

,# teardown

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered


```
