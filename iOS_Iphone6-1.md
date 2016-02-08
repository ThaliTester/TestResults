#### Test 58135655812b57f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/DAC6AB38-600C-4365-8C03-F75BF39DAC34/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DAC6AB38-600C-4365-8C03-F75BF39DAC34/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/58135655812b57f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51878"
,(lldb)     command script import "/tmp/DAC6AB38-600C-4365-8C03-F75BF39DAC34/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-08 17:23:05.641 ThaliTest[1450:2812001] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76D1CA50-9522-4AC6-86DF-997B082B4032/Library/Cookies/Cookies.binarycookies
,2016-02-08 17:23:06.029 ThaliTest[1450:2812001] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-08 17:23:06.031 ThaliTest[1450:2812001] Multi-tasking -> Device: YES, App: YES
,2016-02-08 17:23:06.037 ThaliTest[1450:2812001] Unlimited access to network resources
,2016-02-08 17:23:06.054 ThaliTest[1450:2812001] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-08 17:23:14.795 ThaliTest[1450:2812001] Resetting plugins due to page load.
,2016-02-08 17:23:17.636 ThaliTest[1450:2812001] Finished load of: file:///var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/index.html
,2016-02-08 17:23:17.654 ThaliTest[1450:2812001] JXcore Cordova plugin initializing
,2016-02-08 17:23:17.656 ThaliTest[1450:2812389] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7676AE46-6393-410D-BC9F-935B333FBA9F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

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

,ack: setup_enqueue and run in order_ok

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

ack: setup_another_ok

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

,ok 20 should not throw

,ok 21 should be equal

,ok 22 should be equal

,# setup

,# failed to extract public key because of corrupt pkcs12 file

,got: setup_failed to extract public key because of corrupt pkcs12 file

,ack: setup_failed to extract public key because of corrupt pkcs12 file_ok

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

,ack: setup_#init should register the peerAvailabilityChanged event_ok

,# teardown

,ok 25 should be equal

,ok 26 should be equal

,ok 27 should be equal

,# setup

,# #init should register the networkChanged event

,got: setup_#init should register the networkChanged event

,ack: setup_#init should register the networkChanged event_ok
,
,# teardown

,ok 28 should be equal

,# setup

,# #startBroadcasting should throw on null device name

,got: setup_#startBroadcasting should throw on null device name

,ack: setup_#startBroadcasting should throw on null device name_ok

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
,
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

,ack: setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error_ok

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

,ack: setup_should call Mobile("Disconnect") without an error_ok

,# teardown

,ok 50 should be equal

,ok 51 should be equal

,# setup

,# should call Mobile("Disconnect") and handle an error

,got: setup_should call Mobile("Disconnect") and handle an error

ack: setup_should call Mobile("Disconnect") and handle an error_ok

,# teardown

,ok 52 should be equal

,ok 53 should be equal

,# setup

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,got: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

ack: setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error_ok

,# teardown

,2016-02-08 17:28:17.834 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.850 ThaliTest[1450:2812389] server: starting 1454948897834.1450.Apagpw==
,2016-02-08 17:28:17.851 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d81280
2016-02-08 17:28:17.853 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897834.1450
2016-02-08 17:28:17.853 ThaliTest[1450:2812389] jxcore: sta,rtBroadcasting: success
ok 54 Should be able to call startBroadcasting without error

,2016-02-08 17:28:17.858 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:17.859 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:17.859 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:17.,860 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
ok 55 Should be able to call stopBroadcasting without error

2016-02-08 17:28:17.862 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.870 ThaliTest[1450:2812389] server: starting 1454948897861.1450.JiaD8A==
2016-02-08 17:28:17.871 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d85000
2016-02-08 17:28:17.871 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948897861.1450
2016-02-08 17:28:17.871 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 56 Should be able to call startBroadcasting without error

2016-02-08 17:28:17.873 ThaliTest[1450:2812389] jxcore: stopBroadcasting,
2016-02-08 17:28:17.874 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:17.874 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:17.875 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
ok 57 Shou,ld be able to call stopBroadcasting without error

2016-02-08 17:28:17.877 ThaliTest[1450:2812389] jxcore: startBroadcasting
2016-02-08 17:28:17.881 ThaliTest[1450:2812389] server: starting 1454948897876.1450.wz+uTQ==
2016-02-08 17:28:17.882 ThaliTest[,1450:2812389] multipeer session: start timer: 0x159aa0d0
2016-02-08 17:28:17.889 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897876.1450
2016-02-08 17:28:17.890 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 58 Sho,uld be able to call startBroadcasting without error

,2016-02-08 17:28:17.891 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:17.899 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:17.900 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:17.,900 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
ok 59 Should be able to call stopBroadcasting without error

2016-02-08 17:28:17.903 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.915 ThaliTest[1450:2812389] server: starting 1454948897902.1450.7p0fpA==
2016-02-08 17:28:17.916 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d871a0
2016-02-08 17:28:17.917 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948897902.1450
2016-02-08 17:28:17.917 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 60 Should be able to call startBroadcasting without error

2016-02-08 17:28:17.919 ThaliTest[1450:2812389] jxcore: stopBroadcasting,
2016-02-08 17:28:17.919 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:17.919 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:17.920 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 61 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:17.923 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.930 ThaliTest[1450:2812389] server: starting 1454948897923.1450.I1keJA==
2016-02-08 17:28:17.930 ThaliTest[1450:2812389] multipeer session: start timer: 0x159abe00
2016-02-08 17:28:17.931 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897923.1450
,2016-02-08 17:28:17.931 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 62 Should be able to call startBroadcasting without error

2016-02-08 17:28:17.938 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:17.938 ThaliTest[,1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:17.938 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:17.939 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
ok 63 Should be able to call stopBroadcasting without error

2016-02-08 17:28:17.940 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.948 ThaliTest[1450:2812389] server: starting 1454948897940.1450.PwBFoQ==
,2016-02-08 17:28:17.951 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d88df0
2016-02-08 17:28:17.951 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897940.1450
2016-02-08 17:28:17.951 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 64 Should be able to call startBroadcasting without error
,
,2016-02-08 17:28:17.958 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:17.959 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:17.960 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:17.961 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 65 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:17.965 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.968 ThaliTest[1450:2812389] server: starting 1454948897965.1450.MgF2UQ==
,2016-02-08 17:28:17.970 ThaliTest[1450:2812389] multipeer session: start timer: 0x159ac7b0
,2016-02-08 17:28:17.972 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897965.1450
,2016-02-08 17:28:17.976 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 66 Should be able to call startBroadcasting without error

,2016-02-08 17:28:17.979 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:17.980 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:17.981 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:17.982 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:17.987 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:17.990 ThaliTest[1450:2812389] server: starting 1454948897987.1450.AmnW/w==
,2016-02-08 17:28:17.993 ThaliTest[1450:2812389] multipeer session: start timer: 0x145e88e0
,2016-02-08 17:28:17.996 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948897987.1450
,2016-02-08 17:28:17.998 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.001 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:18.002 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.003 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:18.006 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 69 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:18.009 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:18.012 ThaliTest[1450:2812389] server: starting 1454948898009.1450.6WKJIA==
,2016-02-08 17:28:18.015 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d88050
,2016-02-08 17:28:18.019 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948898009.1450
,2016-02-08 17:28:18.021 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 70 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.024 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:18.024 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.025 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:18.027 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 71 Should be able to call stopBroadcasting without error

,2016-02-08 17:28:18.032 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:18.034 ThaliTest[1450:2812389] server: starting 1454948898031.1450.QFIsSg==
,2016-02-08 17:28:18.037 ThaliTest[1450:2812389] multipeer session: start timer: 0x159ad2d0
,2016-02-08 17:28:18.039 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948898031.1450
,2016-02-08 17:28:18.042 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 72 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.044 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:18.045 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.045 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:18.047 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 73 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter calls startBroadcasting twice with error

,got: setup_ThaliEmitter calls startBroadcasting twice with error

,ack: setup_ThaliEmitter calls startBroadcasting twice with error_ok
,
,# teardown

,2016-02-08 17:28:18.245 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:18.249 ThaliTest[1450:2812389] server: starting 1454948898245.1450.CZ7xkg==
,2016-02-08 17:28:18.253 ThaliTest[1450:2812389] multipeer session: start timer: 0x159d3fc0
,2016-02-08 17:28:18.260 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948898245.1450
,2016-02-08 17:28:18.261 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
,ok 74 Should be able to call startBroadcasting without error

,2016-02-08 17:28:18.265 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:18.266 ThaliTest[1450:2812389] jxcore: startBroadcasting: failure
,ok 75 Cannot call startBroadcasting twice

,2016-02-08 17:28:18.271 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:18.273 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:18.274 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:18.280 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 76 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on connection to bad peer

,got: setup_ThaliEmitter throws on connection to bad peer

,ack: setup_ThaliEmitter throws on connection to bad peer_ok

,# teardown

,2016-02-08 17:28:18.832 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:18.836 ThaliTest[1450:2812389] server: starting 1454948898832.1450.zKXPcw==
2016-02-08 17:28:18.837 ThaliTest[1450:2812389] multipeer session: start timer: 0x159d2540
2016-02-08 17:28:18.837 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948898832.1450
2016-02-08 17:28:18.837 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 77 Should be able to call startBroadcasting without error

2016-02-08 17:28:18.839 ThaliTest[1450:2812389] jxcore: connect foobar
2,016-02-08 17:28:18.840 ThaliTest[1450:2812389] client: unknown peer foobar
2016-02-08 17:28:18.840 ThaliTest[1450:2812389] jxcore: connect: fail: Unknown peer
ok 78 Should not connect to a bad peer

2016-02-08 17:28:18.843 ThaliTest[1450:2812389] jxcor,e: stopBroadcasting
2016-02-08 17:28:18.844 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:18.844 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:18.844 ThaliTest[1450:2812389] jxcore: stopBroadcasting:, success
,ok 79 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter throws on disconnect to bad peer

,got: setup_ThaliEmitter throws on disconnect to bad peer

,ack: setup_ThaliEmitter throws on disconnect to bad peer_ok

,# teardown

,2016-02-08 17:28:19.333 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:19.337 ThaliTest[1450:2812389] server: starting 1454948899333.1450.qzywyw==
2016-02-08 17:28:19.338 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d90470
2016-02-08 17:28:19.338 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948899333.1450
2016-02-08 17:28:19.338 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 80 Should be able to call startBroadcasting without error

2016-02-08 17:28:19.341 ThaliTest[1450:2812389] jxcore: disconnect
2016-,02-08 17:28:19.341 ThaliTest[1450:2812389] jxcore: disconnect: fail
,ok 81 Disconnect should fail to a non-existant peer 
,
,2016-02-08 17:28:19.354 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:19.355 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:19.356 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:19.360 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,ok 82 Should be able to call stopBroadcasting without error

,# setup

,# ThaliEmitter can discover and connect to peers

,got: setup_ThaliEmitter can discover and connect to peers

,ack: setup_ThaliEmitter can discover and connect to peers_ok

,# teardown

,2016-02-08 17:28:20.215 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:20.219 ThaliTest[1450:2812389] server: starting 1454948900215.1450.ANq4tA==
2016-02-08 17:28:20.219 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d940d0
2016-02-08 17:28:20.220 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948900215.1450
2016-02-08 17:28:20.220 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 83 Should be able to call startBroadcasting without error

,2016-02-08 17:28:20.988 ThaliTest[1450:2812001] client: found peer: 1454948900167.908.a5rDug==
2016-02-08 17:28:20.990 ThaliTest[1450:2812389] jxcore: connect 1454948900167.908.a5rDug==
2016-02-08 17:28:20.991 ThaliTest[1450:2812389] client session: conn,ect
2016-02-08 17:28:20.991 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948900167.908.a5rDug==
,2016-02-08 17:28:21.258 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:21.258 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:21.259 ThaliTest[1450:2812001] multipeer session: start timer: 0x16d940d0
2016-,02-08 17:28:21.259 ThaliTest[1450:2812001] server session: connect
2016-02-08 17:28:21.259 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948900167.908
,2016-02-08 17:28:21.269 ThaliTest[1450:2812001] server: accepting invitation 1454948900167.908
,2016-02-08 17:28:23.777 ThaliTest[1450:2812980] client session: connected
,2016-02-08 17:28:23.777 ThaliTest[1450:2812980] client session: stateChange:1->2 1454948900167.908.a5rDug==
2016-02-08 17:28:23.783 ThaliTest[1450:2812980] client session: fireConnectCallback: 1454948900167.908.a5rDug==
2016-02-08 17:28:23.783 ThaliTest[,1450:2812980] jxcore: connect: success
ok 84 Should be able to connect without error

ok 85 Port should be within range

2016-02-08 17:28:23.788 ThaliTest[1450:2812389] jxcore: disconnect
,2016-02-08 17:28:23.789 ThaliTest[1450:2812389] client session: disconnectFromPeer: 1454948900167.908.a5rDug==
,2016-02-08 17:28:23.790 ThaliTest[1450:2812389] client session: disconnect
,2016-02-08 17:28:23.791 ThaliTest[1450:2812389] client session: stateChange:2->0 1454948900167.908.a5rDug==
,2016-02-08 17:28:23.807 ThaliTest[1450:2812389] jxcore: disconnect: success
,ok 86 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup

,2016-02-08 17:28:23.948 ThaliTest[1450:2812982] server session: connected
,2016-02-08 17:28:23.950 ThaliTest[1450:2812982] server session: stateChange:1->2 1454948900167.908
,2016-02-08 17:28:23.955 ThaliTest[1450:2812001] server relay: socket disconnected
2016-02-08 17:28:23.955 ThaliTest[1450:2812001] server relay: 0x15b5f250 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:28:23.995 ThaliTest[1450:2812984] server session: not connected 1454948900167.908
,calling stopBroadcasting

,2016-02-08 17:28:24.073 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:24.074 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:24.074 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:24.,075 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:28:24.075 ThaliTest[1450:2812389] server session: stateChange:2->0 1454948900167.908
2016-02-08 17:28:24.076 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double connect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double connect_ok

,# teardown

,2016-02-08 17:28:24.613 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:24.617 ThaliTest[1450:2812389] server: starting 1454948904613.1450.3lffqg==
2016-02-08 17:28:24.618 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d97720
2016-02-08 17:28:24.618 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948904613.1450
2016-02-08 17:28:24.618 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 87 Should be able to call startBroadcasting without error

,2016-02-08 17:28:25.821 ThaliTest[1450:2812001] client: found peer: 1454948904837.908.jiizJA==
2016-02-08 17:28:25.822 ThaliTest[1450:2812389] jxcore: connect 1454948904837.908.jiizJA==
2016-02-08 17:28:25.823 ThaliTest[1450:2812389] client session: conn,ect
2016-02-08 17:28:25.823 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948904837.908.jiizJA==
,2016-02-08 17:28:25.968 ThaliTest[1450:2812001] multipeer session: reset timer
,2016-02-08 17:28:25.969 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:25.970 ThaliTest[1450:2812001] multipeer session: start timer: 0x16d97720
2016-02-08 17:28:25.971 ThaliTest[1450:2812001] server session: connect
2016-02-08 1,7:28:25.971 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948904837.908
,2016-02-08 17:28:25.981 ThaliTest[1450:2812001] server: accepting invitation 1454948904837.908
,2016-02-08 17:28:28.539 ThaliTest[1450:2812984] server session: connected
,2016-02-08 17:28:28.539 ThaliTest[1450:2812984] server session: stateChange:1->2 1454948904837.908
,2016-02-08 17:28:28.569 ThaliTest[1450:2812985] client session: connected
,2016-02-08 17:28:28.572 ThaliTest[1450:2812985] client session: stateChange:1->2 1454948904837.908.jiizJA==
,2016-02-08 17:28:28.586 ThaliTest[1450:2812001] server relay: socket disconnected
,2016-02-08 17:28:28.587 ThaliTest[1450:2812001] server relay: 0x16da14c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:28:28.597 ThaliTest[1450:2812985] client session: fireConnectCallback: 1454948904837.908.jiizJA==
2016-02-08 17:28:28.597 ThaliTest[1450:2812985] jxcore: connect: success
,ok 88 Should be able to connect without error

,ok 89 Port should be within range

,2016-02-08 17:28:28.602 ThaliTest[1450:2812389] jxcore: connect 1454948904837.908.jiizJA==
2016-02-08 17:28:28.604 ThaliTest[1450:2812389] client: already connect(ing/ed) to 1454948904837.908.jiizJA==
2016-02-08 17:28:28.604 ThaliTest[1450:2812389] jxcor,e: connect: fail: Aleady connecting
,ok 90 Should fail on double connect

,2016-02-08 17:28:28.608 ThaliTest[1450:2812389] jxcore: disconnect
2016-02-08 17:28:28.608 ThaliTest[1450:2812389] client session: disconnectFromPeer: 1454948904837.908.jiizJA==
,2016-02-08 17:28:28.609 ThaliTest[1450:2812389] client session: disconnect
2016-02-08 17:28:28.609 ThaliTest[1450:2812389] client session: stateChange:2->0 1454948904837.908.jiizJA==
,2016-02-08 17:28:28.640 ThaliTest[1450:2812982] server session: not connected 1454948904837.908
,2016-02-08 17:28:28.643 ThaliTest[1450:2812389] jxcore: disconnect: success
,ok 91 Should be able to disconnect without error

,setting stopBroadcasting callback and ending test.
,
,# setup
,
,calling stopBroadcasting

,2016-02-08 17:28:28.767 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:28.767 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:28.768 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:28.769 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:28:2,8.769 ThaliTest[1450:2812389] server session: stateChange:2->0 1454948904837.908
,2016-02-08 17:28:28.770 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,stopBroadcasting returned undefined

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,got: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

,ack: setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect_ok

,# teardown

,2016-02-08 17:28:29.305 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:29.308 ThaliTest[1450:2812389] server: starting 1454948909304.1450.LkHJHA==
2016-02-08 17:28:29.309 ThaliTest[1450:2812389] multipeer session: start timer: 0x15b9e680
2016-02-08 17:28:29.310 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948909304.1450
2016-02-08 17:28:29.310 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 92 Should be able to call startBroadcasting without error

,2016-02-08 17:28:30.444 ThaliTest[1450:2812001] client: found peer: 1454948909535.908.VAwgOA==
,2016-02-08 17:28:30.446 ThaliTest[1450:2812389] jxcore: connect 1454948909535.908.VAwgOA==
2016-02-08 17:28:30.449 ThaliTest[1450:2812389] client session: connect
2016-02-08 17:28:30.450 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948909535.908.VAwgOA==
,2016-02-08 17:28:30.501 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:30.502 ThaliTest[1450:2812001] multipeer session: stop timer
,2016-02-08 17:28:30.502 ThaliTest[1450:2812001] multipeer session: start timer: 0x15b9e680
2016-02-08 17:28:30.502 ThaliTest[1450:2812001] server session: connect
,2016-02-08 17:28:30.503 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948909535.908
,2016-02-08 17:28:30.513 ThaliTest[1450:2812001] server: accepting invitation 1454948909535.908
,2016-02-08 17:28:33.016 ThaliTest[1450:2812982] server session: connected
2016-02-08 17:28:33.016 ThaliTest[1450:2812982] server session: stateChange:1->2 1454948909535.908
,2016-02-08 17:28:33.041 ThaliTest[1450:2812001] server relay: socket disconnected
2016-02-08 17:28:33.042 ThaliTest[1450:2812001] server relay: 0x15d667e0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLoc,alizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2016-02-08 17:28:33.058 ThaliTest[1450:2812980] client session: connected
2016-02-08 17:28:33.058 ThaliTest[1450:2812980] client session: stateChange:1->2 1454948909535.908.VAwgOA==
,2016-02-08 17:28:33.062 ThaliTest[1450:2812980] client session: fireConnectCallback: 1454948909535.908.VAwgOA==
2016-02-08 17:28:33.063 ThaliTest[1450:2812980] jxcore: connect: success
ok 93 Should be able to connect without error

ok 94 Port should be, within range

2016-02-08 17:28:33.067 ThaliTest[1450:2812389] jxcore: disconnect
2016-02-08 17:28:33.068 ThaliTest[1450:2812389] client session: disconnectFromPeer: 1454948909535.908.VAwgOA==
2016-02-08 17:28:33.068 ThaliTest[1450:2812389] client sess,ion: disconnect
2016-02-08 17:28:33.068 ThaliTest[1450:2812389] client session: stateChange:2->0 1454948909535.908.VAwgOA==
,2016-02-08 17:28:33.093 ThaliTest[1450:2812980] server session: not connected 1454948909535.908
,2016-02-08 17:28:33.102 ThaliTest[1450:2812389] jxcore: disconnect: success
,ok 95 Should be able to disconnect without error

,2016-02-08 17:28:33.104 ThaliTest[1450:2812389] jxcore: disconnect
,2016-02-08 17:28:33.106 ThaliTest[1450:2812389] jxcore: disconnect: fail
,ok 96 Disconnect should fail 

setting stopBroadcasting callback and ending test.

,# setup

,calling stopBroadcasting

,2016-02-08 17:28:33.454 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:33.454 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:33.455 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:33.,455 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:28:33.455 ThaliTest[1450:2812389] server session: stateChange:2->0 1454948909535.908
2016-02-08 17:28:33.456 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
stopBroadcasting ,returned undefined

,# ThaliEmitter can connect and send data

,got: setup_ThaliEmitter can connect and send data

,ack: setup_ThaliEmitter can connect and send data_ok

,# teardown

,echo server started on port: 58133

,2016-02-08 17:28:34.523 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:34.524 ThaliTest[1450:2812389] server: starting 1454948914523.1450./qNtqA==
2016-02-08 17:28:34.524 ThaliTest[1450:2812389] multipeer session: start timer: 0x15ca6570
2016-02-08 17:28:34.525 ThaliTest[1450:2812389] THEMultipeerSession initialized peer 1454948914523.1450
2016-02-08 17:28:34.525 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 97 Should be able to call startBroadcasting without error

,2016-02-08 17:28:34.690 ThaliTest[1450:2812001] client: found peer: 1454948909535.908.VAwgOA==
2016-02-08 17:28:34.690 ThaliTest[1450:2812389] jxcore: connect 1454948909535.908.VAwgOA==
2016-02-08 17:28:34.690 ThaliTest[1450:2812389] client session: conn,ect
2016-02-08 17:28:34.690 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948909535.908.VAwgOA==
,2016-02-08 17:28:35.266 ThaliTest[1450:2812001] client: found peer: 1454948914518.908.qjeQqg==
2016-02-08 17:28:35.268 ThaliTest[1450:2812389] jxcore: connect 1454948914518.908.qjeQqg==
,2016-02-08 17:28:35.268 ThaliTest[1450:2812389] client session: connect
,2016-02-08 17:28:35.269 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948914518.908.qjeQqg==
,2016-02-08 17:28:35.865 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:35.866 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:35.866 ThaliTest[1450:2812001] multipeer session: start timer: 0x15ca6570
2016-,02-08 17:28:35.866 ThaliTest[1450:2812001] server session: connect
2016-02-08 17:28:35.867 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948914518.908
,2016-02-08 17:28:35.876 ThaliTest[1450:2812001] server: accepting invitation 1454948914518.908
,2016-02-08 17:28:36.700 ThaliTest[1450:2812001] client: lost peer: 1454948909535.908.VAwgOA==
2016-02-08 17:28:36.701 ThaliTest[1450:2812001] client session: onPeerLost: 1454948909535.908.VAwgOA==
2016-02-08 17:28:36.701 ThaliTest[1450:2812001] client se,ssion: onLinkFailure: 1454948909535.908.VAwgOA==
2016-02-08 17:28:36.701 ThaliTest[1450:2812001] client session: disconnect
2016-02-08 17:28:36.701 ThaliTest[1450:2812001] client session: stateChange:1->0 1454948909535.908.VAwgOA==
2016-02-08 17:28:36.7,02 ThaliTest[1450:2812001] client session: fireConnectCallback: 1454948909535.908.VAwgOA==
2016-02-08 17:28:36.702 ThaliTest[1450:2812001] jxcore: connect: fail: Peer disconnected
,2016-02-08 17:28:37.709 ThaliTest[1450:2812389] jxcore: connect 1454948909535.908.VAwgOA==
2016-02-08 17:28:37.710 ThaliTest[1450:2812389] client: connect: unreachable 1454948909535.908.VAwgOA==
2016-02-08 17:28:37.710 ThaliTest[1450:2812389] jxcore: connect: fail: Peer unreachable
,2016-02-08 17:28:38.500 ThaliTest[1450:2812988] client session: connected
2016-02-08 17:28:38.501 ThaliTest[1450:2812988] client session: stateChange:1->2 1454948914518.908.qjeQqg==
2016-02-08 17:28:38.503 ThaliTest[1450:2812988] client session: fireConn,ectCallback: 1454948914518.908.qjeQqg==
2016-02-08 17:28:38.503 ThaliTest[1450:2812988] jxcore: connect: success
ok 98 Should be able to connect without error

ok 99 Port should be within range

,2016-02-08 17:28:38.510 ThaliTest[1450:2812001] client: relay established
2016-02-08 17:28:38.512 ThaliTest[1450:2812001] client: new accepted socket: 0x169b9220
,data in 4380
,
,data in 8760

,data in 17520
,
,data in 25712
,
,2016-02-08 17:28:38.732 ThaliTest[1450:2812980] server session: connected
,2016-02-08 17:28:38.733 ThaliTest[1450:2812980] server session: stateChange:1->2 1454948914518.908
,data in 32850

,2016-02-08 17:28:38.747 ThaliTest[1450:2812001] server relay: connected (to port: 58133)
,data in 54750

,data in 61320

,data in 82125

,data in 131072

,ok 100 the test messages should be equal

,2016-02-08 17:28:39.037 ThaliTest[1450:2812389] jxcore: disconnect
,2016-02-08 17:28:39.038 ThaliTest[1450:2812389] client session: disconnectFromPeer: 1454948914518.908.qjeQqg==
,2016-02-08 17:28:39.038 ThaliTest[1450:2812389] client session: disconnect
,2016-02-08 17:28:39.039 ThaliTest[1450:2812389] client session: stateChange:2->0 1454948914518.908.qjeQqg==
,2016-02-08 17:28:39.106 ThaliTest[1450:2812389] jxcore: disconnect: success
,ok 101 Should be able to disconnect without error

setting stopBroadcasting callback and ending test.

,# setup

,2016-02-08 17:28:39.466 ThaliTest[1450:2812980] server session: not connected 1454948914518.908
,calling stopBroadcasting

,2016-02-08 17:28:39.746 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:39.746 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:39.747 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:39.747 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:28:39.747 ThaliTest[1450:2812389] server session: stateChange:2->0 1454948914518.908
,2016-02-08 17:28:39.755 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

# ThaliEmitter handles socket disconnect correctly
,
,got: setup_ThaliEmitter handles socket disconnect correctly

ack: setup_ThaliEmitter handles socket disconnect correctly_ok

# teardown

,echo server started on port: 58144

,2016-02-08 17:28:40.316 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:40.319 ThaliTest[1450:2812389] server: starting 1454948920315.1450.tJ+2tw==
2016-02-08 17:28:40.320 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d82e10
2016-02-08 17:28:40.320 ThaliTest[1450:2812389] THEMultipeerSession in,itialized peer 1454948920315.1450
2016-02-08 17:28:40.321 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 102 Should be able to call startBroadcasting without error

,2016-02-08 17:28:41.493 ThaliTest[1450:2812001] client: found peer: 1454948920544.908.v6tM6w==
[{"peerIdentifier":"1454948920544.908.v6tM6w==","peerName":"(null)","peerAvailable":true}]

,2016-02-08 17:28:41.496 ThaliTest[1450:2812389] jxcore: connect 1454948920544.908.v6tM6w==
,2016-02-08 17:28:41.496 ThaliTest[1450:2812389] client session: connect
,2016-02-08 17:28:41.497 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948920544.908.v6tM6w==
,2016-02-08 17:28:41.632 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:41.632 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:41.632 ThaliTest[1450:2812001] multipeer session: start timer: 0x16d82e10
2016-,02-08 17:28:41.633 ThaliTest[1450:2812001] server session: connect
2016-02-08 17:28:41.633 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948920544.908
2016-02-08 17:28:41.640 ThaliTest[1450:2812001] server: accepting invitation 14549489205,44.908
,2016-02-08 17:28:44.122 ThaliTest[1450:2812985] server session: connected
2016-02-08 17:28:44.122 ThaliTest[1450:2812985] server session: stateChange:1->2 1454948920544.908
,2016-02-08 17:28:44.128 ThaliTest[1450:2812001] server relay: connected (to port: 58144)
,2016-02-08 17:28:44.197 ThaliTest[1450:2813085] client session: connected
2016-02-08 17:28:44.198 ThaliTest[1450:2813085] client session: stateChange:1->2 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.220 ThaliTest[1450:2812988] client session: fireConnectCallback: 1454948920544.908.v6tM6w==
2016-02-08 17:28:44.221 ThaliTest[1450:2812988] jxcore: connect: success
ok 103 Should be able to connect without error

ok 104 Port should ,be within range

ok 105 First connect should succeed

,2016-02-08 17:28:44.286 ThaliTest[1450:2812001] client: relay established
,2016-02-08 17:28:44.287 ThaliTest[1450:2812001] client: new accepted socket: 0x15af33a0
,ok 106 the test messages should be equal

ok 107 First send should succeed

,2016-02-08 17:28:44.399 ThaliTest[1450:2812001] client: socket closed
,2016-02-08 17:28:44.400 ThaliTest[1450:2812001] client relay: socket disconnected
2016-02-08 17:28:44.401 ThaliTest[1450:2812001] client relay: 0x15af33a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 17:28:44.401 ThaliTest[1450:2812001] client session: socket closed: 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.402 ThaliTest[1450:2812001] client session: onLinkFailure: 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.402 ThaliTest[1450:2812001] client session: disconnect
2016-02-08 17:28:44.405 ThaliTest[1450:2812001] client session: stateChange:2->0 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.408 ThaliTest[1450:2812988] server session: not connected 1454948920544.908
,2016-02-08 17:28:44.421 ThaliTest[1450:2812001] client session: fireConnectionErrorEvent: 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.424 ThaliTest[1450:2812389] jxcore: connect 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.431 ThaliTest[1450:2812389] client session: connect
,2016-02-08 17:28:44.432 ThaliTest[1450:2812389] client session: stateChange:0->1 1454948920544.908.v6tM6w==
,2016-02-08 17:28:44.581 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:44.582 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:44.582 ThaliTest[1450:2812001] multipeer session: start timer: 0x16d82e10
,2016-02-08 17:28:44.582 ThaliTest[1450:2812001] server: disconnecting to refresh session (1454948920544.908)
,2016-02-08 17:28:44.587 ThaliTest[1450:2812001] server session: disconnect
,2016-02-08 17:28:44.588 ThaliTest[1450:2812001] server session: stateChange:2->0 1454948920544.908
,2016-02-08 17:28:44.659 ThaliTest[1450:2812001] server session: connect
2016-02-08 17:28:44.660 ThaliTest[1450:2812001] server session: stateChange:0->1 1454948920544.908
,2016-02-08 17:28:44.668 ThaliTest[1450:2812001] server: accepting invitation 1454948920544.908
,2016-02-08 17:28:47.239 ThaliTest[1450:2812988] server session: connected
,2016-02-08 17:28:47.241 ThaliTest[1450:2812985] client session: connected
,2016-02-08 17:28:47.242 ThaliTest[1450:2812988] server session: stateChange:1->2 1454948920544.908
,2016-02-08 17:28:47.243 ThaliTest[1450:2812985] client session: stateChange:1->2 1454948920544.908.v6tM6w==
,2016-02-08 17:28:47.253 ThaliTest[1450:2812001] server relay: connected (to port: 58144)
,2016-02-08 17:28:47.256 ThaliTest[1450:2812985] client session: fireConnectCallback: 1454948920544.908.v6tM6w==
,2016-02-08 17:28:47.264 ThaliTest[1450:2812985] jxcore: connect: success
,ok 108 Should be able to connect without error

,ok 109 Port should be within range

,ok 110 Second connect should succeed

,2016-02-08 17:28:47.301 ThaliTest[1450:2812001] client: relay established
2016-02-08 17:28:47.302 ThaliTest[1450:2812001] client: new accepted socket: 0x16daa060
,ok 111 the test messages should be equal

,ok 112 Second send should succeed

,# setup

,2016-02-08 17:28:47.381 ThaliTest[1450:2812001] client: socket closed
2016-02-08 17:28:47.382 ThaliTest[1450:2812001] client relay: socket disconnected
2016-02-08 17:28:47.382 ThaliTest[1450:2812001] client relay: 0x16daa060 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-02-08 17:28:47.382 ThaliTest[1450:2812001] client session: socket closed: 1454948920544.908.v6tM6w==
2016-02-08 1,7:28:47.383 ThaliTest[1450:2812001] client session: onLinkFailure: 1454948920544.908.v6tM6w==
2016-02-08 17:28:47.383 ThaliTest[1450:2812001] client session: disconnect
2016-02-08 17:28:47.383 ThaliTest[1450:2812001] client session: stateChange:2->0 1454,948920544.908.v6tM6w==
,2016-02-08 17:28:47.398 ThaliTest[1450:2812001] client session: fireConnectionErrorEvent: 1454948920544.908.v6tM6w==
,2016-02-08 17:28:47.423 ThaliTest[1450:2812985] server session: not connected 1454948920544.908
,calling stopBroadcasting

,2016-02-08 17:28:48.158 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:48.159 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:48.159 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:28:48.,160 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:28:48.160 ThaliTest[1450:2812389] server session: stateChange:2->0 1454948920544.908
,2016-02-08 17:28:48.173 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
stopBroadcasting returned undefined

,# ThaliReplicationManager can call start without error

,got: setup_ThaliReplicationManager can call start without error

,ack: setup_ThaliReplicationManager can call start without error_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/76D1CA50-9522-4AC6-86DF-997B082B4032/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,ok 113 starting event should occur in right order

,2016-02-08 17:28:48.875 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:48.879 ThaliTest[1450:2812389] server: starting A8r5qr6EQ_jXLm5R5Z0FRA.iC88ew==
2016-02-08 17:28:48.879 ThaliTest[1450:2812389] multipeer session: start timer: 0x15e08220
2016-02-08 17:28:48.879 ThaliTest[1450:2812389] THEMultipeerSessio,n initialized peer A8r5qr6EQ_jXLm5R5Z0FRA
2016-02-08 17:28:48.879 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 114 started event should occur in right order

Now in TRM stop

State of this._isStarted: true

ok 115 stopping event should occur in right order

About to call stopBroadcasting

,2016-02-08 17:28:48.881 ThaliTest[1450:2812389] jxcore: stopBroadcasting
,2016-02-08 17:28:48.884 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
,2016-02-08 17:28:48.884 ThaliTest[1450:2812389] multipeer session: stop timer
,2016-02-08 17:28:48.885 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
,Got callback from stopBroadcasting with err undefined

,ok 116 stopped event should occur in right order

,mux server bridge listener closed

,# setup

,# ThaliReplicationManager receives identity

,got: setup_ThaliReplicationManager receives identity

ack: setup_ThaliReplicationManager receives identity_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/76D1CA50-9522-4AC6-86DF-997B082B4032/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:28:49.619 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:49.622 ThaliTest[1450:2812389] server: starting A8r5qr6EQ_jXLm5R5Z0FRA.Qpx/tg==
2016-02-08 17:28:49.623 ThaliTest[1450:2812389] multipeer session: start timer: 0x16962440
2016-02-08 17:28:49.623 ThaliTest[1450:2812389] THEMultipeerSessio,n initialized peer A8r5qr6EQ_jXLm5R5Z0FRA
2016-02-08 17:28:49.624 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 117 getDeviceIdentity should not return an error

ok 118 deviceName should not be null

Now in TRM stop

State of this._,isStarted: true

About to call stopBroadcasting

2016-02-08 17:28:49.627 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:28:49.627 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:28:49.627 ThaliTest[1450:2812389,] multipeer session: stop timer
2016-02-08 17:28:49.628 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,mux server bridge listener closed

# setup

,# ThaliReplicationManager replicates database

,got: setup_ThaliReplicationManager replicates database

ack: setup_ThaliReplicationManager replicates database_ok

,# teardown

,DB value for ThaliReplicationManager is: {"__opts":{"prefix":"/private/var/mobile/Containers/Data/Application/76D1CA50-9522-4AC6-86DF-997B082B4032/tmp/pouch-for-replication-test"},"prefix":"_pouch_","domain":null,"_events":{},"_maxListeners":10,"taskqueue",:{"isReady":false,"failed":false,"queue":[]},"_adapter":"leveldb","_db_name":"thali","adapter":"leveldb","replicate":{}}

,2016-02-08 17:28:52.046 ThaliTest[1450:2812389] jxcore: startBroadcasting
,2016-02-08 17:28:52.047 ThaliTest[1450:2812389] server: starting A8r5qr6EQ_jXLm5R5Z0FRA.WBGXkA==
2016-02-08 17:28:52.047 ThaliTest[1450:2812389] multipeer session: start timer: 0x16d51750
2016-02-08 17:28:52.047 ThaliTest[1450:2812389] THEMultipeerSession initialized peer A8r5qr6EQ_jXLm5R5Z0FRA
,2016-02-08 17:28:52.049 ThaliTest[1450:2812389] jxcore: startBroadcasting: success
ok 119 getDeviceIdentity should not return an error

ok 120 deviceName should not be null

,2016-02-08 17:28:53.113 ThaliTest[1450:2812001] client: found peer: 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,2016-02-08 17:28:56.641 ThaliTest[1450:2812001] multipeer session: reset timer
2016-02-08 17:28:56.641 ThaliTest[1450:2812001] multipeer session: stop timer
2016-02-08 17:28:56.641 ThaliTest[1450:2812001] multipeer session: start timer: 0x16d51750
2016-02-08 17:28:56.641 ThaliTest[1450:2812001] server session: connect
2016-02-08 17:28:56.641 ThaliTest[1450:2812001] server session: stateChange:0->1 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:28:56.646 ThaliTest[1450:2812001] server: accepting invitation 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:28:56.654 ThaliTest[1450:2812389] jxcore: connect 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
2016-02-08 17:28:56.655 ThaliTest[1450:2812389] client session: connect
2016-02-08 17:28:56.655 ThaliTest[1450:2812389] client session: stateChange:0->1 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,ok 121 Should be able to put doc without error

,ok 122 1st change of local doc should contain local id

,2016-02-08 17:28:59.103 ThaliTest[1450:2813085] server session: connected
2016-02-08 17:28:59.103 ThaliTest[1450:2813085] server session: stateChange:1->2 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:28:59.122 ThaliTest[1450:2812001] server relay: connected (to port: 58160)
,server bridge: new client socket

,2016-02-08 17:28:59.267 ThaliTest[1450:2813085] client session: connected
2016-02-08 17:28:59.267 ThaliTest[1450:2813085] client session: stateChange:1->2 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,2016-02-08 17:28:59.319 ThaliTest[1450:2812985] client session: fireConnectCallback: 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
2016-02-08 17:28:59.320 ThaliTest[1450:2812985] jxcore: connect: success
,2016-02-08 17:28:59.333 ThaliTest[1450:2812001] client: relay established
2016-02-08 17:28:59.333 ThaliTest[1450:2812001] client: new accepted socket: 0x16d99b70
,client bridge: new client socket
,
,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket

,client bridge: socket closed

client bridge: socket closed

,ok 123 1st change of remote doc should contain remote id

,client bridge: new client socket
,
,ok 124 Can update remote doc without error

,null

,{ ok: true,
  id: 'ffa33d61-6c59-4905-80f5-50a58c418db4',
  rev: '2-859c92a7ea786a368c099f0386cd16b5' }

,client bridge: new client socket

,client bridge: socket closed

,ok 125 Remote changes occur in strict order

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: new client socket

,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket

,client bridge: new client socket
,
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

,client bridge: new client socket

,client bridge: socket closed
,
,client bridge: socket closed
,
,ok 126 Local changes occur in strict order

,ok 127 2nd change of local doc should contain remote id

,# setup

,client bridge: new client socket

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: new client socket
,
,client bridge: socket closed

,client bridge: socket closed

,client bridge: new client socket
,
,2016-02-08 17:29:10.176 ThaliTest[1450:2812980] server session: not connected 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:29:10.199 ThaliTest[1450:2812988] client session: not connected 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
2016-02-08 17:29:10.200 ThaliTest[1450:2812988] client session: onLinkFailure: 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
2016-02-08 17:29:10.200 ThaliTest,[1450:2812988] client session: disconnect
2016-02-08 17:29:10.200 ThaliTest[1450:2812988] client session: stateChange:2->0 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,2016-02-08 17:29:10.202 ThaliTest[1450:2812988] client session: fireConnectionErrorEvent: 8YQKCGaSKtvCoZ666nmkBw.XdUDAg==
,Now in TRM stop

State of this._isStarted: true

About to call stopBroadcasting

,2016-02-08 17:29:10.210 ThaliTest[1450:2812389] jxcore: stopBroadcasting
2016-02-08 17:29:10.210 ThaliTest[1450:2812389] THEMultipeerSession stopping peer
2016-02-08 17:29:10.211 ThaliTest[1450:2812389] multipeer session: stop timer
2016-02-08 17:29:10.,211 ThaliTest[1450:2812389] server session: disconnect
2016-02-08 17:29:10.211 ThaliTest[1450:2812389] server session: stateChange:2->0 8YQKCGaSKtvCoZ666nmkBw
,2016-02-08 17:29:10.217 ThaliTest[1450:2812389] jxcore: stopBroadcasting: success
Got callback from stopBroadcasting with err undefined

,Error in mux client bridge Error: write EPIPE
,
,mux server bridge listener closed

,client bridge: new client socket

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,client bridge: socket closed

,server bridge: socket closed
,
,syncRetry called when not started

,got: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ack: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted_ok
,
,# teardown

,client bridge: socket closed

,client bridge: socket closed

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered


```
