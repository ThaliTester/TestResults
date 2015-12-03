#### Test 50650278c5de1fe_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/86D77900-9106-4EB3-80D3-28B1A3C23165/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/86D77900-9106-4EB3-80D3-28B1A3C23165/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E72CF34-0641-4DB1-8202-2B59B00F4451/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60948"
,(lldb)     command script import "/tmp/86D77900-9106-4EB3-80D3-28B1A3C23165/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 19:23:53.860 ThaliTest[1973:3025282] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA00A237-631A-4DA6-A278-8E678ACBD2F7/Library/Cookies/Cookies.binarycookies
,2015-12-03 19:23:54.127 ThaliTest[1973:3025282] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 19:23:54.128 ThaliTest[1973:3025282] Multi-tasking -> Device: YES, App: YES
,2015-12-03 19:23:54.134 ThaliTest[1973:3025282] Unlimited access to network resources
,2015-12-03 19:23:54.140 ThaliTest[1973:3025282] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 19:23:58.314 ThaliTest[1973:3025282] Resetting plugins due to page load.
,2015-12-03 19:23:59.754 ThaliTest[1973:3025282] Finished load of: file:///var/mobile/Containers/Bundle/Application/4E72CF34-0641-4DB1-8202-2B59B00F4451/ThaliTest.app/www/index.html
,2015-12-03 19:23:59.903 ThaliTest[1973:3025282] JXcore Cordova plugin initializing
,2015-12-03 19:23:59.904 ThaliTest[1973:3025467] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrupt pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter handles socket disconnect correctly","ThaliReplicationManager can call start without error","ThaliReplicationManager receives identity","ThaliReplicationManager replicates database"]
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
ok 2 sane
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
running teardown
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
running teardown
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
running teardown
,# failed to get mobile documents path
,CoordinatorConnector-debug: setup:failed to get mobile documents path
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
running teardown
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
running teardown
,# #init should register the networkChanged event
,CoordinatorConnector-debug: setup:#init should register the networkChanged event
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#init should register the networkChanged event
,ok 19 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the networkChanged event
running teardown
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
running teardown
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
running teardown
,# #startBroadcasting should throw on NaN port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on NaN port
,# teardown
--- running teardown
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
running teardown
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
--- running teardown
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
ok 38 should be equal
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
running teardown
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
,2015-12-03 19:26:19.280 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.371 ThaliTest[1973:3025467] server: starting 1449167179280.1973.yW9vaw==
,2015-12-03 19:26:19.371 ThaliTest[1973:3025467] multipeer session: start timer: 0x1897b720
,2015-12-03 19:26:19.372 ThaliTest[1973:3025467] THEMultipeerSession initialized peer 1449167179280.1973
,2015-12-03 19:26:19.372 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
,2015-12-03 19:26:19.377 ThaliTest[1973:3025467] jxcore: stopBroadcasting
,2015-12-03 19:26:19.377 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
,2015-12-03 19:26:19.377 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.378 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
2015-12-03 19:26:19.379 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.380 ThaliTest[1973:3025467] server: starting 1449167179378.1973.uleESw==
2015-12-03 19:26:19.380 ThaliTest[1973:3025467] multipeer session: start timer: 0x1897eae0
2015-12-03 19:26:19.380 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179378.1973
2015-12-03 19:26:19.381 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.381 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2,015-12-03 19:26:19.381 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.381 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.382 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-03 19:26:19.383 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.386 ThaliTest[1973:3025467] server: starting 1449167179383.1973.DQ57ng==
2015-12-03 19:26:19.386 ThaliTest[1973:3025467] multipeer session: start timer: 0x1897f450
2015-12-03 19:26:19.387 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179383.1973
,2015-12-03 19:26:19.387 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.388 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2015-12-03 19:26:19.388 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.389 ThaliTest[197,3:3025467] multipeer session: stop timer
2015-12-03 19:26:19.389 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:19.391 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.393 ThaliTest[1973:3025467] server: starting 1449167179390.1973.Kp4+Mg==
2015-12-03 19:26:19.393 ThaliTest[1973:3025467] multipeer session: start timer: 0x16424420
2015-12-03 19:26:19.393 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179390.1973
2015-12-03 19:26:19.393 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.394 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2,015-12-03 19:26:19.394 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.394 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.394 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 52 Should, be able to call stopBroadcasting without error
2015-12-03 19:26:19.395 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.397 ThaliTest[1973:3025467] server: starting 1449167179395.1973.tMYaRw==
,2015-12-03 19:26:19.398 ThaliTest[1973:3025467] multipeer session: start timer: 0x18981350
2015-12-03 19:26:19.398 ThaliTest[1973:3025467] THEMultipeerSession initialized peer 1449167179395.1973
2015-12-03 19:26:19.398 ThaliTest[1973:3025467] jxcore: sta,rtBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.399 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2015-12-03 19:26:19.399 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.399 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.399 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:19.399 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.404 ThaliTest[1973:3025467] server: starting 1449167179399.1973.J8FuuA==
2015-12-03 19:26:19.404 ThaliTest[1973:3025467] multipeer session: start timer: 0x1641f520
2015-12-03 19:26:19.404 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179399.1973
2015-12-03 19:26:19.404 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.405 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2,015-12-03 19:26:19.405 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.405 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.405 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 56 Should, be able to call stopBroadcasting without error
2015-12-03 19:26:19.406 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.408 ThaliTest[1973:3025467] server: starting 1449167179405.1973.jQ+0Sg==
2015-12-03 19:26:19.408 ThaliTest[1973:3025467] multipeer session: start timer: 0x189837d0
2015-12-03 19:26:19.408 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179405.1973
2015-12-03 19:26:19.408 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
,2015-12-03 19:26:19.409 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2015-12-03 19:26:19.409 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.410 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.,410 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2015-12-03 19:26:19.410 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.412 ThaliTest[1973:3025467] server: starting 1449167179410.1973.LMRV/Q==
,2015-12-03 19:26:19.412 ThaliTest[1973:3025467] multipeer session: start timer: 0x18984830
,2015-12-03 19:26:19.413 ThaliTest[1973:3025467] THEMultipeerSession initialized peer 1449167179410.1973
2015-12-03 19:26:19.413 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.414 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2015-12-03 19:26:19.414 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.414 ThaliTest[197,3:3025467] multipeer session: stop timer
2015-12-03 19:26:19.414 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2015-12-03 19:26:19.415 ThaliTest[1973:3025467] jxcore: startBroadcast,ing
,2015-12-03 19:26:19.417 ThaliTest[1973:3025467] server: starting 1449167179415.1973./tzBMg==
2015-12-03 19:26:19.418 ThaliTest[1973:3025467] multipeer session: start timer: 0x16421070
2015-12-03 19:26:19.418 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179415.1973
2015-12-03 19:26:19.418 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.418 ThaliTest[1973:3025467] jxcore: stopBroadcasting
,2015-12-03 19:26:19.418 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.420 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.420 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:19.421 ThaliTest[1973:3025467] jxcore: startBroadcasting
,2015-12-03 19:26:19.426 ThaliTest[1973:3025467] server: starting 1449167179421.1973.pMdOdw==
2015-12-03 19:26:19.427 ThaliTest[1973:3025467] multipeer session: start timer: 0x1641fa60
2015-12-03 19:26:19.427 ThaliTest[1973:3025467] THEMultipeerSession in,itialized peer 1449167179421.1973
2015-12-03 19:26:19.427 ThaliTest[1973:3025467] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2015-12-03 19:26:19.427 ThaliTest[1973:3025467] jxcore: stopBroadcasting
2,015-12-03 19:26:19.427 ThaliTest[1973:3025467] THEMultipeerSession stopping peer
2015-12-03 19:26:19.428 ThaliTest[1973:3025467] multipeer session: stop timer
2015-12-03 19:26:19.428 ThaliTest[1973:3025467] jxcore: stopBroadcasting: success
ok 64 Should, be able to call stopBroadcasting without error
,# setup

```
