#### Test 50650278c902ea2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BDC1EF9C-7537-4B71-AD6F-454BD26154EC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BDC1EF9C-7537-4B71-AD6F-454BD26154EC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/689D97FF-3DD5-4EB7-BB05-BB02604C7FE1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60788"
,(lldb)     command script import "/tmp/BDC1EF9C-7537-4B71-AD6F-454BD26154EC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:36:26.921 ThaliTest[1242:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 17:36:26.924 ThaliTest[1242:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:36:26.931 ThaliTest[1242:60b] Unlimited access to network resources
,2015-12-03 17:36:26.938 ThaliTest[1242:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:36:36.498 ThaliTest[1242:60b] Resetting plugins due to page load.
,2015-12-03 17:36:37.284 ThaliTest[1242:60b] Finished load of: file:///var/mobile/Applications/689D97FF-3DD5-4EB7-BB05-BB02604C7FE1/ThaliTest.app/www/index.html
,2015-12-03 17:36:37.469 ThaliTest[1242:60b] JXcore Cordova plugin initializing
,2015-12-03 17:36:37.472 ThaliTest[1242:6807] JXcore instance initializing
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
,2015-12-03 17:36:56.223 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.443 ThaliTest[1242:6807] server: starting 1449160616222.1242.0L6YVw==
,2015-12-03 17:36:56.445 ThaliTest[1242:6807] multipeer session: start timer: 0x1da01de0
,2015-12-03 17:36:56.446 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616222.1242
,2015-12-03 17:36:56.448 ThaliTest[1242:6807] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2015-12-03 17:36:56.450 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.451 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.452 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.452 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2015-12-03 17:36:56.454 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.459 ThaliTest[1242:6807] server: starting 1449160616454.1242.fxsQUA==
,2015-12-03 17:36:56.460 ThaliTest[1242:6807] multipeer session: start timer: 0x1da07750
2015-12-03 17:36:56.460 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616454.1242
2015-12-03 17:36:56.461 ThaliTest[1242:6807] jxcore: startBroadca,sting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.463 ThaliTest[1242:6807] jxcore: stopBroadcasting
2015-12-03 17:36:56.464 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.465 ThaliTest[1242:6807] multipeer session: stop timer
2015-12-03 17:36:56.465 Thali,Test[1242:6807] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-03 17:36:56.467 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.472 ThaliTest[1242:6807] server: starting 1449160616467.1242.JVEftg==
,2015-12-03 17:36:56.473 ThaliTest[1242:6807] multipeer session: start timer: 0x1da08bd0
2015-12-03 17:36:56.475 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616467.1242
2015-12-03 17:36:56.476 ThaliTest[1242:6807] jxcore: startBroadca,sting: success
ok 49 Should be able to call startBroadcasting without error
2015-12-03 17:36:56.478 ThaliTest[1242:6807] jxcore: stopBroadcasting
2015-12-03 17:36:56.478 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.479 Tha,liTest[1242:6807] multipeer session: stop timer
2015-12-03 17:36:56.480 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
2015-12-03 17:36:56.482 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.490 ThaliTest[1242:6807] server: starting 1449160616482.1242.4v0m7A==
,2015-12-03 17:36:56.491 ThaliTest[1242:6807] multipeer session: start timer: 0x1de8cba0
2015-12-03 17:36:56.491 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616482.1242
2015-12-03 17:36:56.493 ThaliTest[1242:6807] jxcore: startBroadca,sting: success
ok 51 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.495 ThaliTest[1242:6807] jxcore: stopBroadcasting
2015-12-03 17:36:56.496 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.497 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.497 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:56.503 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.507 ThaliTest[1242:6807] server: starting 1449160616502.1242.M4HCDA==
2015-12-03 17:36:56.507 ThaliTest[1242:6807] multipeer session: start timer: 0x1da08f60
,2015-12-03 17:36:56.508 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616502.1242
2015-12-03 17:36:56.509 ThaliTest[1242:6807] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-03 17:36:56.511 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.512 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:36:56.512 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.515 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:56.517 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.523 ThaliTest[1242:6807] server: starting 1449160616517.1242.1s4GDw==
,2015-12-03 17:36:56.524 ThaliTest[1242:6807] multipeer session: start timer: 0x1da08fe0
,2015-12-03 17:36:56.528 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616517.1242
,2015-12-03 17:36:56.530 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.532 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.533 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.533 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.534 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
2015-12-03 17:36:56.536 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.541 ThaliTest[1242:6807] server: starting 1449160616536.1242./4rMlw==
,2015-12-03 17:36:56.542 ThaliTest[1242:6807] multipeer session: start timer: 0x1da0b270
2015-12-03 17:36:56.543 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616536.1242
2015-12-03 17:36:56.543 ThaliTest[1242:6807] jxcore: startBroadca,sting: success
ok 57 Should be able to call startBroadcasting without error
2015-12-03 17:36:56.545 ThaliTest[1242:6807] jxcore: stopBroadcasting
2015-12-03 17:36:56.546 ThaliTest[1242:6807] THEMultipeerSession stopping peer
2015-12-03 17:36:56.547 Tha,liTest[1242:6807] multipeer session: stop timer
2015-12-03 17:36:56.547 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2015-12-03 17:36:56.549 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.555 ThaliTest[1242:6807] server: starting 1449160616549.1242.TfTYlA==
,2015-12-03 17:36:56.559 ThaliTest[1242:6807] multipeer session: start timer: 0x1da0fec0
,2015-12-03 17:36:56.561 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616549.1242
,2015-12-03 17:36:56.562 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.564 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.565 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:36:56.566 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.567 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:56.570 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.574 ThaliTest[1242:6807] server: starting 1449160616570.1242.2V9Kdg==
,2015-12-03 17:36:56.575 ThaliTest[1242:6807] multipeer session: start timer: 0x1de8cff0
,2015-12-03 17:36:56.578 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616570.1242
,2015-12-03 17:36:56.579 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.581 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.583 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:36:56.584 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.585 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:56.588 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:56.592 ThaliTest[1242:6807] server: starting 1449160616588.1242.CfJ99w==
,2015-12-03 17:36:56.593 ThaliTest[1242:6807] multipeer session: start timer: 0x1da0e3d0
,2015-12-03 17:36:56.596 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160616588.1242
,2015-12-03 17:36:56.598 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.600 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:36:56.601 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:36:56.602 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:56.604 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:36:59.349 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:59.352 ThaliTest[1242:6807] server: starting 1449160619348.1242.UKjDiw==
,2015-12-03 17:36:59.353 ThaliTest[1242:6807] multipeer session: start timer: 0x1da141d0
2015-12-03 17:36:59.356 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160619348.1242
,2015-12-03 17:36:59.357 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-03 17:36:59.359 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:36:59.360 ThaliTest[1242:6807] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
,2015-12-03 17:36:59.361 ThaliTest[1242:6807] jxcore: stopBroadcasting
2015-12-03 17:36:59.362 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:36:59.363 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:36:59.364 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:37:01.768 ThaliTest[1242:6807] jxcore: startBroadcasting
,2015-12-03 17:37:01.772 ThaliTest[1242:6807] server: starting 1449160621768.1242.VR+bdg==
2015-12-03 17:37:01.773 ThaliTest[1242:6807] multipeer session: start timer: 0x1de82380
,2015-12-03 17:37:01.774 ThaliTest[1242:6807] THEMultipeerSession initialized peer 1449160621768.1242
2015-12-03 17:37:01.774 ThaliTest[1242:6807] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-03 17:37:01.776 ThaliTest[1242:6807] jxcore: connect foobar
2015-12-03 17:37:01.777 ThaliTest[1242:6807] client: unknown peer foobar
,2015-12-03 17:37:01.778 ThaliTest[1242:6807] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
,2015-12-03 17:37:01.782 ThaliTest[1242:6807] jxcore: stopBroadcasting
,2015-12-03 17:37:01.783 ThaliTest[1242:6807] THEMultipeerSession stopping peer
,2015-12-03 17:37:01.783 ThaliTest[1242:6807] multipeer session: stop timer
,2015-12-03 17:37:01.784 ThaliTest[1242:6807] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup

```
