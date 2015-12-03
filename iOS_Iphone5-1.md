#### Test 506502788f08dc7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/53C3FD71-9CDC-4249-951E-D629D17E7FDC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/53C3FD71-9CDC-4249-951E-D629D17E7FDC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/7522EAAC-F462-47A0-B7A5-004A52493542/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60712"
,(lldb)     command script import "/tmp/53C3FD71-9CDC-4249-951E-D629D17E7FDC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:04:02.460 ThaliTest[1233:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 17:04:02.463 ThaliTest[1233:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:04:02.470 ThaliTest[1233:60b] Unlimited access to network resources
,2015-12-03 17:04:02.476 ThaliTest[1233:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:04:12.117 ThaliTest[1233:60b] Resetting plugins due to page load.
,2015-12-03 17:04:12.891 ThaliTest[1233:60b] Finished load of: file:///var/mobile/Applications/7522EAAC-F462-47A0-B7A5-004A52493542/ThaliTest.app/www/index.html
,2015-12-03 17:04:13.071 ThaliTest[1233:60b] JXcore Cordova plugin initializing
,2015-12-03 17:04:13.073 ThaliTest[1233:6907] JXcore instance initializing
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
--- running teardown
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
,running teardown
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
running teardown
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
,--- running teardown
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
,running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,running teardown
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
,running teardown
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
,2015-12-03 17:04:37.314 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.537 ThaliTest[1233:6907] server: starting 1449158677313.1233.H/Fxpw==
,2015-12-03 17:04:37.538 ThaliTest[1233:6907] multipeer session: start timer: 0x1955de90
2015-12-03 17:04:37.539 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677313.1233
2015-12-03 17:04:37.539 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-03 17:04:37.543 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.544 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.545 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.547 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.550 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.554 ThaliTest[1233:6907] server: starting 1449158677550.1233.NSx8UA==
,2015-12-03 17:04:37.555 ThaliTest[1233:6907] multipeer session: start timer: 0x19561ee0
2015-12-03 17:04:37.556 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677550.1233
2015-12-03 17:04:37.557 ThaliTest[1233:6907] jxcore: startBroadca,sting: success
,ok 47 Should be able to call startBroadcasting without error
2015-12-03 17:04:37.559 ThaliTest[1233:6907] jxcore: stopBroadcasting
2015-12-03 17:04:37.559 ThaliTest[1233:6907] THEMultipeerSession stopping peer
2015-12-03 17:04:37.560 ThaliTest[1233:6907,] multipeer session: stop timer
2015-12-03 17:04:37.561 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.565 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.569 ThaliTest[1233:6907] server: starting 1449158677565.1233.ptTOog==
,2015-12-03 17:04:37.570 ThaliTest[1233:6907] multipeer session: start timer: 0x19655ad0
,2015-12-03 17:04:37.572 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677565.1233
,2015-12-03 17:04:37.575 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.578 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.580 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.580 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.582 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.585 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.590 ThaliTest[1233:6907] server: starting 1449158677585.1233.VbtVhQ==
,2015-12-03 17:04:37.591 ThaliTest[1233:6907] multipeer session: start timer: 0x19555e90
,2015-12-03 17:04:37.594 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677585.1233
,2015-12-03 17:04:37.595 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.598 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.599 ThaliTest[1233:6907] THEMultipeerSession stopping peer
2015-12-03 17:04:37.600 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.601 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.605 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.609 ThaliTest[1233:6907] server: starting 1449158677604.1233.gZz0+A==
,2015-12-03 17:04:37.610 ThaliTest[1233:6907] multipeer session: start timer: 0x19555e90
,2015-12-03 17:04:37.614 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677604.1233
,2015-12-03 17:04:37.615 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.617 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.618 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.619 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.620 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.624 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.628 ThaliTest[1233:6907] server: starting 1449158677624.1233./dxz9A==
2015-12-03 17:04:37.629 ThaliTest[1233:6907] multipeer session: start timer: 0x196535f0
,2015-12-03 17:04:37.632 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677624.1233
,2015-12-03 17:04:37.634 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.638 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.638 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.639 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.641 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.645 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.648 ThaliTest[1233:6907] server: starting 1449158677644.1233./M8rTg==
,2015-12-03 17:04:37.651 ThaliTest[1233:6907] multipeer session: start timer: 0x19553ca0
2015-12-03 17:04:37.652 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677644.1233
,2015-12-03 17:04:37.653 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.656 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.657 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.657 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.658 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.662 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.665 ThaliTest[1233:6907] server: starting 1449158677661.1233.ibNyaA==
2015-12-03 17:04:37.666 ThaliTest[1233:6907] multipeer session: start timer: 0x19553900
,2015-12-03 17:04:37.668 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677661.1233
,2015-12-03 17:04:37.671 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.673 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.674 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.675 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.676 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.679 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.682 ThaliTest[1233:6907] server: starting 1449158677679.1233.nN+Xlg==
,2015-12-03 17:04:37.685 ThaliTest[1233:6907] multipeer session: start timer: 0x19654ff0
,2015-12-03 17:04:37.688 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677679.1233
,2015-12-03 17:04:37.689 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.692 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.692 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.694 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.696 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:37.698 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:37.702 ThaliTest[1233:6907] server: starting 1449158677698.1233.aUa47A==
,2015-12-03 17:04:37.703 ThaliTest[1233:6907] multipeer session: start timer: 0x19551430
,2015-12-03 17:04:37.707 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158677698.1233
,2015-12-03 17:04:37.708 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 17:04:37.711 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:37.712 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.713 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:37.714 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:04:39.540 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:39.544 ThaliTest[1233:6907] server: starting 1449158679540.1233.dyKcjA==
,2015-12-03 17:04:39.545 ThaliTest[1233:6907] multipeer session: start timer: 0x1954ad00
2015-12-03 17:04:39.545 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158679540.1233
2015-12-03 17:04:39.546 ThaliTest[1233:6907] jxcore: startBroadca,sting: success
ok 65 Should be able to call startBroadcasting without error
,2015-12-03 17:04:39.548 ThaliTest[1233:6907] jxcore: startBroadcasting
2015-12-03 17:04:39.548 ThaliTest[1233:6907] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2015-12-03 17:04:39.551 ThaliTest[1233:6907] jxcore: stopBroadcasting
2015-12-03 17:04:39.551 ThaliTest[1233:6907] THEMultipeerSession stopping peer
,2015-12-03 17:04:39.552 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:39.553 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:04:41.143 ThaliTest[1233:6907] jxcore: startBroadcasting
,2015-12-03 17:04:41.147 ThaliTest[1233:6907] server: starting 1449158681143.1233.apIzjA==
,2015-12-03 17:04:41.148 ThaliTest[1233:6907] multipeer session: start timer: 0x195467b0
2015-12-03 17:04:41.148 ThaliTest[1233:6907] THEMultipeerSession initialized peer 1449158681143.1233
2015-12-03 17:04:41.149 ThaliTest[1233:6907] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-03 17:04:41.151 ThaliTest[1233:6907] jxcore: connect foobar
,2015-12-03 17:04:41.152 ThaliTest[1233:6907] client: unknown peer foobar
2015-12-03 17:04:41.153 ThaliTest[1233:6907] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2015-12-03 17:04:41.155 ThaliTest[1233:6907] jxcore: stopBroadcasting
,2015-12-03 17:04:41.156 ThaliTest[1233:6907] THEMultipeerSession stopping peer
2015-12-03 17:04:41.157 ThaliTest[1233:6907] multipeer session: stop timer
,2015-12-03 17:04:41.158 ThaliTest[1233:6907] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup

```
