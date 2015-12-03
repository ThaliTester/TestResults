#### Test 506502788f08dc7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/80CC8670-C174-401A-836C-3505A445B482/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/80CC8670-C174-401A-836C-3505A445B482/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7FF2A043-B831-403E-88C3-EFDFC7F43D8C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60710"
,(lldb)     command script import "/tmp/80CC8670-C174-401A-836C-3505A445B482/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:03:08.963 ThaliTest[2635:2221189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5107B6C4-D364-4916-9990-00C73BDA6E43/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:03:09.359 ThaliTest[2635:2221189] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 17:03:09.360 ThaliTest[2635:2221189] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:03:09.369 ThaliTest[2635:2221189] Unlimited access to network resources
,2015-12-03 17:03:09.374 ThaliTest[2635:2221189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:03:12.853 ThaliTest[2635:2221189] Resetting plugins due to page load.
,2015-12-03 17:03:13.214 ThaliTest[2635:2221189] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/7FF2A043-B831-403E-88C3-EFDFC7F43D8C/ThaliTest.app/www/index.html
,2015-12-03 17:03:13.338 ThaliTest[2635:2221189] JXcore Cordova plugin initializing
2015-12-03 17:03:13.339 ThaliTest[2635:2221318] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to ,bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter can connect and se,nd data","ThaliEmitter handles socket disconnect correctly"]
,TAP version 13
,# setup
,# multiplex can send data
,CoordinatorConnector-debug: setup:multiplex can send data
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:multiplex can send data
,ok 1 String should be length:200
,# setup
,CoordinatorConnector-debug: teardown:multiplex can send data
,running teardown
,# basic
,CoordinatorConnector-debug: setup:basic
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:basic
,ok 2 sane
,# setup
,CoordinatorConnector-debug: teardown:basic
,running teardown
,# another
,CoordinatorConnector-debug: setup:another
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:another
,ok 3 sane
,# setup
,CoordinatorConnector-debug: teardown:another
,running teardown
,# successfully create a new pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully create a new pkcs12 file and return hash value
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:successfully create a new pkcs12 file and return hash value
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
,ok 7 should be equal
,ok 8 should not throw
,# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
running teardown
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:successfully read a previous pkcs12 file and return hash value
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
,CoordinatorConnector-debug: teardown:successfully read a previous pkcs12 file and return hash value
,running teardown
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
,running teardown
,# failed to get mobile documents path
,CoordinatorConnector-debug: setup:failed to get mobile documents path
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
,running teardown
,# #init should register the peerAvailabilityChanged event
,CoordinatorConnector-debug: setup:#init should register the peerAvailabilityChanged event
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#init should register the peerAvailabilityChanged event
,ok 16 should be equal
,ok 17 should be equal
,ok 18 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the peerAvailabilityChanged event
,running teardown
,# #init should register the networkChanged event
,CoordinatorConnector-debug: setup:#init should register the networkChanged event
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#init should register the networkChanged event
,ok 19 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the networkChanged event
,running teardown
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
,running teardown
,# #startBroadcasting should throw on empty string device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on empty string device name
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on empty string device name
,ok 21 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on empty string device name
,running teardown
,# #startBroadcasting should throw on non-number port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on non-number port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on non-number port
,ok 22 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on non-number port
,running teardown
,# #startBroadcasting should throw on NaN port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on NaN port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on NaN port
,ok 23 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on NaN port
,running teardown
,# #startBroadcasting should throw on negative port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on negative port
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on negative port
,ok 24 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on negative port
,running teardown
,# #startBroadcasting should throw on too large port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on too large port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on too large port
,ok 25 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on too large port
,running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,ok 26 should be equal
,ok 27 should be equal
,ok 28 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") without an error
running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
running teardown
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,ok 32 should be equal
,ok 33 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,running teardown
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,ok 34 should be equal
,ok 35 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
running teardown
,# #connect should call Mobile("Connect") with a port and without an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") with a port and without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") with a port and without an error
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") with a port and without an error
,running teardown
,# #connect should call Mobile("Connect") and handle an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") and handle an error
,ok 39 should be equal
,ok 40 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") and handle an error
,running teardown
,# should call Mobile("Disconnect") without an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") without an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") without an error
,ok 41 should be equal
,ok 42 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") without an error
,running teardown
,# should call Mobile("Disconnect") and handle an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") and handle an error
,ok 43 should be equal
,ok 44 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") and handle an error
,running teardown
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,CoordinatorConnector-debug: setup:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,2015-12-03 17:04:35.685 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.864 ThaliTest[2635:2221318] server: starting 1449158675684.2635.ScMYbg==
,2015-12-03 17:04:35.866 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bd2fbc0
2015-12-03 17:04:35.867 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158675684.2635
,2015-12-03 17:04:35.867 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.871 ThaliTest[2635:2221318] jxcore: stopBroadcasting
2015-12-03 17:04:35.873 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
2015-12-03 17:04:35.873 ThaliTest[2635:2221318] multipeer session: stop timer
2015-12-03 17:04:35.,874 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.876 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.889 ThaliTest[2635:2221318] server: starting 1449158675876.2635.Zs3zrg==
2015-12-03 17:04:35.890 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bd2c100
2015-12-03 17:04:35.890 ThaliTest[2635:2221318] THEMultipeerSession in,itialized peer 1449158675876.2635
2015-12-03 17:04:35.891 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.895 ThaliTest[2635:2221318] jxcore: stopBroadcasting
2015-12-03 17:04:35.897 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
2015-12-03 17:04:35.898 ThaliTest[2635:2221318] multipeer session: stop timer
2015-12-03 17:04:35.,898 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2015-12-03 17:04:35.901 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.908 ThaliTest[2635:2221318] server: starting 1449158675900.2635.5wtBBw==
2015-12-03 17:04:35.909 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bd291b0
2015-12-03 17:04:35.910 ThaliTest[2635:2221318] THEMultipeerSession in,itialized peer 1449158675900.2635
,2015-12-03 17:04:35.910 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.920 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:35.921 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.922 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:35.923 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2015-12-03 17:04:35.926 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.932 ThaliTest[2635:2221318] server: starting 1449158675925.2635.JOsTkA==
,2015-12-03 17:04:35.934 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bd27f50
2015-12-03 17:04:35.935 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158675925.2635
2015-12-03 17:04:35.936 ThaliTest[2635:2221318] jxcore: sta,rtBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-03 17:04:35.939 ThaliTest[2635:2221318] jxcore: stopBroadcasting
2015-12-03 17:04:35.939 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
2015-12-03 1,7:04:35.940 ThaliTest[2635:2221318] multipeer session: stop timer
2015-12-03 17:04:35.940 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.953 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.956 ThaliTest[2635:2221318] server: starting 1449158675952.2635.A34Wag==
,2015-12-03 17:04:35.958 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae1c20
,2015-12-03 17:04:35.962 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158675952.2635
,2015-12-03 17:04:35.963 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.966 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:35.967 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.968 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:35.969 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.974 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.975 ThaliTest[2635:2221318] server: starting 1449158675973.2635.vNCwtg==
,2015-12-03 17:04:35.977 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae2590
,2015-12-03 17:04:35.982 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158675973.2635
,2015-12-03 17:04:35.983 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.986 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:35.987 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.988 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:35.989 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.994 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:35.996 ThaliTest[2635:2221318] server: starting 1449158675994.2635.5wPxtA==
,2015-12-03 17:04:35.997 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae1f80
,2015-12-03 17:04:36.000 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158675994.2635
,2015-12-03 17:04:36.003 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.005 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:36.006 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.008 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:36.009 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.013 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:36.015 ThaliTest[2635:2221318] server: starting 1449158676013.2635.bZZk+g==
,2015-12-03 17:04:36.016 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae6dd0
,2015-12-03 17:04:36.019 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158676013.2635
,2015-12-03 17:04:36.021 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.023 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:36.024 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.025 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:36.026 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.031 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:36.034 ThaliTest[2635:2221318] server: starting 1449158676031.2635.mA5xCw==
,2015-12-03 17:04:36.035 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae6e50
,2015-12-03 17:04:36.039 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158676031.2635
,2015-12-03 17:04:36.040 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.043 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:36.044 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.044 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:36.045 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.050 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:36.052 ThaliTest[2635:2221318] server: starting 1449158676050.2635.vqfENA==
,2015-12-03 17:04:36.053 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae4a90
,2015-12-03 17:04:36.057 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158676050.2635
,2015-12-03 17:04:36.058 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.061 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:36.061 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.062 ThaliTest[2635:2221318] multipeer session: stop timer
,2015-12-03 17:04:36.063 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:04:37.898 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:37.902 ThaliTest[2635:2221318] server: starting 1449158677898.2635.2pwX0Q==
,2015-12-03 17:04:37.903 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bd23d80
2015-12-03 17:04:37.904 ThaliTest[2635:2221318] THEMultipeerSession initialized peer 1449158677898.2635
2015-12-03 17:04:37.905 ThaliTest[2635:2221318] jxcore: sta,rtBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2015-12-03 17:04:37.910 ThaliTest[2635:2221318] jxcore: startBroadcasting
2015-12-03 17:04:37.910 ThaliTest[2635:2221318] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-03 17:04:37.914 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:37.915 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.915 ThaliTest[2635:2221318] multipeer session: stop timer
2015-12-03 17:04:37.917 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:04:39.858 ThaliTest[2635:2221318] jxcore: startBroadcasting
,2015-12-03 17:04:39.861 ThaliTest[2635:2221318] server: starting 1449158679858.2635.Eb+tBA==
2015-12-03 17:04:39.862 ThaliTest[2635:2221318] multipeer session: start timer: 0x1bae0770
2015-12-03 17:04:39.862 ThaliTest[2635:2221318] THEMultipeerSession in,itialized peer 1449158679858.2635
2015-12-03 17:04:39.863 ThaliTest[2635:2221318] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-03 17:04:39.867 ThaliTest[2635:2221318] jxcore: connect foobar
2015-12-03 17:04:39.867 ThaliTest[2635:2221318] client: unknown peer foobar
,2015-12-03 17:04:39.868 ThaliTest[2635:2221318] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2015-12-03 17:04:39.872 ThaliTest[2635:2221318] jxcore: stopBroadcasting
,2015-12-03 17:04:39.872 ThaliTest[2635:2221318] THEMultipeerSession stopping peer
2015-12-03 17:04:39.873 ThaliTest[2635:2221318] multipeer session: stop timer
2015-12-03 17:04:39.874 ThaliTest[2635:2221318] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup

```
