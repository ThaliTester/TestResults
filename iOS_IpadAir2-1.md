#### Test 50650278c902ea2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C998191F-AD06-407D-8ECB-A991A212A407/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C998191F-AD06-407D-8ECB-A991A212A407/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/018E3A3C-388E-4519-871F-2577139C3B3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60786"
,(lldb)     command script import "/tmp/C998191F-AD06-407D-8ECB-A991A212A407/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:35:03.311 ThaliTest[1938:3010113] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F279EA6-AF1F-4305-A4A4-4C9721473796/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:35:03.598 ThaliTest[1938:3010113] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 17:35:03.599 ThaliTest[1938:3010113] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:35:03.605 ThaliTest[1938:3010113] Unlimited access to network resources
,2015-12-03 17:35:03.611 ThaliTest[1938:3010113] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:35:07.592 ThaliTest[1938:3010113] Resetting plugins due to page load.
,2015-12-03 17:35:08.987 ThaliTest[1938:3010113] Finished load of: file:///var/mobile/Containers/Bundle/Application/018E3A3C-388E-4519-871F-2577139C3B3B/ThaliTest.app/www/index.html
,2015-12-03 17:35:09.126 ThaliTest[1938:3010113] JXcore Cordova plugin initializing
,2015-12-03 17:35:09.127 ThaliTest[1938:3010286] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to ,bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter handles socket dis,connect correctly"]
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
running teardown
,# basic
,CoordinatorConnector-debug: setup:basic
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:basic
,ok 2 sane
,# setup
,CoordinatorConnector-debug: teardown:basic
running teardown
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
--- running teardown
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
running teardown
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
running teardown
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
--- running teardown
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
--- running teardown
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
running teardown
,# #startBroadcasting should throw on negative port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on negative port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on negative port
,ok 24 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on negative port
running teardown
,# #startBroadcasting should throw on too large port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on too large port
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on too large port
,ok 25 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on too large port
running teardown
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
--- running teardown
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
running teardown
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
running teardown
,# #connect should call Mobile("Connect") and handle an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") and handle an error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") and handle an error
,ok 39 should be equal
,ok 40 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") and handle an error
running teardown
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
running teardown
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,CoordinatorConnector-debug: setup:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,2015-12-03 17:36:57.005 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.094 ThaliTest[1938:3010286] server: starting 1449160617005.1938.gQe8Ew==
,2015-12-03 17:36:57.094 ThaliTest[1938:3010286] multipeer session: start timer: 0x19d569a0
2015-12-03 17:36:57.094 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617005.1938
2015-12-03 17:36:57.094 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-03 17:36:57.096 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.096 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:57.096 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.,096 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.097 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.100 ThaliTest[1938:3010286] server: starting 1449160617097.1938.dbI1fw==
2015-12-03 17:36:57.100 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e64800
2015-12-03 17:36:57.100 ThaliTest[1938:3010286] THEMultipeerSession in,itialized peer 1449160617097.1938
2015-12-03 17:36:57.100 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-03 17:36:57.102 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.102 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
,2015-12-03 17:36:57.103 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.103 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.104 ThaliTest,[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.107 ThaliTest[1938:3010286] server: starting 1449160617104.1938./00gFg==
,2015-12-03 17:36:57.107 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e63220
2015-12-03 17:36:57.108 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617104.1938
,2015-12-03 17:36:57.108 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:36:57.111 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.111 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:57.111 ThaliTest[1938:3010286] multipeer session: stop timer
,2015-12-03 17:36:57.112 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:57.113 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.117 ThaliTest[1938:3010286] server: starting 1449160617112.1938.G7fyXA==
,2015-12-03 17:36:57.117 ThaliTest[1938:3010286] multipeer session: start timer: 0x17d00e80
2015-12-03 17:36:57.117 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617112.1938
2015-12-03 17:36:57.118 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.119 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.119 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:57.119 ThaliTest[193,8:3010286] multipeer session: stop timer
2015-12-03 17:36:57.119 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.120 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.123 ThaliTest[1938:3010286] server: starting 1449160617120.1938.r+Hnfg==
2015-12-03 17:36:57.123 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e62350
2015-12-03 17:36:57.123 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617120.1938
,2015-12-03 17:36:57.124 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.125 ThaliTest[1938:3010286] jxcore: stopBroadcasting
,2015-12-03 17:36:57.126 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
,2015-12-03 17:36:57.126 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.126 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:57.128 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.130 ThaliTest[1938:3010286] server: starting 1449160617128.1938.EiZTPw==
2015-12-03 17:36:57.130 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e62620
2015-12-03 17:36:57.131 ThaliTest[1938:3010286] THEMultipeerSession in,itialized peer 1449160617128.1938
2015-12-03 17:36:57.131 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:36:57.132 ThaliTest[1938:3010286] jxcore: stopBroadcasting
,2015-12-03 17:36:57.132 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
,2015-12-03 17:36:57.132 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.133 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.134 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.135 ThaliTest[1938:3010286] server: starting 1449160617133.1938.AYxKLA==
,2015-12-03 17:36:57.136 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e5f5d0
2015-12-03 17:36:57.138 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617133.1938
2015-12-03 17:36:57.138 ThaliTest[1938:3010286] jxcore: sta,rtBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.139 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.140 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 1,7:36:57.140 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.140 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:57.141 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.143 ThaliTest[1938:3010286] server: starting 1449160617140.1938.U1tdRg==
2015-12-03 17:36:57.144 ThaliTest[1938:3010286] multipeer session: start timer: 0x17d04170
2015-12-03 17:36:57.144 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617140.1938
2015-12-03 17:36:57.144 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.146 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.146 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
,2015-12-03 17:36:57.147 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.148 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.149 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.152 ThaliTest[1938:3010286] server: starting 1449160617148.1938.XNsUTQ==
,2015-12-03 17:36:57.153 ThaliTest[1938:3010286] multipeer session: start timer: 0x19e62ca0
2015-12-03 17:36:57.153 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160617148.1938
2015-12-03 17:36:57.153 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.155 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:57.155 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:57.155 ThaliTest[193,8:3010286] multipeer session: stop timer
2015-12-03 17:36:57.155 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
2015-12-03 17:36:57.156 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:57.157 ThaliTest[1938:3010286] server: starting 1449160617156.1938.TVLajg==
2015-12-03 17:36:57.158 ThaliTest[1938:3010286] multipeer session: start timer: 0x17d04910
2015-12-03 17:36:57.158 ThaliTest[1938:3010286] THEMultipeerSession in,itialized peer 1449160617156.1938
2015-12-03 17:36:57.158 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2015-12-03 17:36:57.159 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2,015-12-03 17:36:57.159 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:57.159 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:57.159 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 64 Should, be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:36:59.401 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:59.403 ThaliTest[1938:3010286] server: starting 1449160619401.1938.pYxXoQ==
2015-12-03 17:36:59.403 ThaliTest[1938:3010286] multipeer session: start timer: 0x19d54290
2015-12-03 17:36:59.403 ThaliTest[1938:3010286] THEMultipeerSession in,itialized peer 1449160619401.1938
2015-12-03 17:36:59.403 ThaliTest[1938:3010286] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-12-03 17:36:59.404 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:36:59.404 ThaliTest[1938:3010286] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-03 17:36:59.407 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:36:59.407 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:36:59.407 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:36:59.407 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:37:02.562 ThaliTest[1938:3010286] jxcore: startBroadcasting
,2015-12-03 17:37:02.563 ThaliTest[1938:3010286] server: starting 1449160622562.1938.QsfsVQ==
,2015-12-03 17:37:02.563 ThaliTest[1938:3010286] multipeer session: start timer: 0x17d075d0
2015-12-03 17:37:02.564 ThaliTest[1938:3010286] THEMultipeerSession initialized peer 1449160622562.1938
2015-12-03 17:37:02.564 ThaliTest[1938:3010286] jxcore: sta,rtBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2015-12-03 17:37:02.564 ThaliTest[1938:3010286] jxcore: connect foobar
2015-12-03 17:37:02.565 ThaliTest[1938:3010286] client: unknown peer foobar
2015-12-03 17:37:02.565 ThaliTest[1938:3010286] jxcore: connect: fail: Unknown peer
ok 69 Should not conne,ct to a bad peer
2015-12-03 17:37:02.566 ThaliTest[1938:3010286] jxcore: stopBroadcasting
2015-12-03 17:37:02.566 ThaliTest[1938:3010286] THEMultipeerSession stopping peer
2015-12-03 17:37:02.566 ThaliTest[1938:3010286] multipeer session: stop timer
2015-12-03 17:37:02.566 ThaliTest[1938:3010286] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup

```
