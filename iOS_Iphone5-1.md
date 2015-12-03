#### Test 50650278c5de1fe_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/178C8C40-E87F-47E3-A793-CC5B409F63E0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/178C8C40-E87F-47E3-A793-CC5B409F63E0/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/56C6509C-87E1-405D-8146-A330A6C0E4FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60952"
,(lldb)     command script import "/tmp/178C8C40-E87F-47E3-A793-CC5B409F63E0/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 19:25:39.102 ThaliTest[1269:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 19:25:39.106 ThaliTest[1269:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 19:25:39.113 ThaliTest[1269:60b] Unlimited access to network resources
,2015-12-03 19:25:39.122 ThaliTest[1269:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 19:25:49.887 ThaliTest[1269:60b] Resetting plugins due to page load.
,2015-12-03 19:25:50.787 ThaliTest[1269:60b] Finished load of: file:///var/mobile/Applications/56C6509C-87E1-405D-8146-A330A6C0E4FF/ThaliTest.app/www/index.html
,2015-12-03 19:25:50.965 ThaliTest[1269:60b] JXcore Cordova plugin initializing
,(JX_LoopOnce) Did you initialize the JXEngine instance for this thread? (ret_val: 0)
,2015-12-03 19:25:50.968 ThaliTest[1269:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to ,bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter handles socket dis,connect correctly","ThaliReplicationManager can call start without error","ThaliReplicationManager receives identity","ThaliReplicationManager replicates database"]
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
--- running teardown
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
# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
,running teardown
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
--- running teardown
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
running teardown
,# #init should register the peerAvailabilityChanged event
,CoordinatorConnector-debug: setup:#init should register the peerAvailabilityChanged event
,# teardown
--- running teardown
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
running teardown
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
running teardown
,# #startBroadcasting should throw on empty string device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on empty string device name
,# teardown
--- running teardown
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
running teardown
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
--- running teardown
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
--- running teardown
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
--- running teardown
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
,2015-12-03 19:26:18.497 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.725 ThaliTest[1269:6707] server: starting 1449167178496.1269.jj12Lw==
,2015-12-03 19:26:18.727 ThaliTest[1269:6707] multipeer session: start timer: 0x19663920
2015-12-03 19:26:18.728 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178496.1269
2015-12-03 19:26:18.729 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-03 19:26:18.731 ThaliTest[1269:6707] jxcore: stopBroadcasting
2015-12-03 19:26:18.732 ThaliTest[1269:6707] THEMultipeerSession stopping peer
2015-12-03 19:26:18.732 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.733 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.737 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.741 ThaliTest[1269:6707] server: starting 1449167178737.1269.DnEf/A==
,2015-12-03 19:26:18.742 ThaliTest[1269:6707] multipeer session: start timer: 0x1959d370
,2015-12-03 19:26:18.742 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178737.1269
2015-12-03 19:26:18.745 ThaliTest[1269:6707] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.747 ThaliTest[1269:6707] jxcore: stopBroadcasting
2015-12-03 19:26:18.747 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.748 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.749 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.751 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.756 ThaliTest[1269:6707] server: starting 1449167178751.1269.edFkRg==
2015-12-03 19:26:18.757 ThaliTest[1269:6707] multipeer session: start timer: 0x1966a160
2015-12-03 19:26:18.758 ThaliTest[1269:6707] THEMultipeerSession initialized, peer 1449167178751.1269
,2015-12-03 19:26:18.758 ThaliTest[1269:6707] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.761 ThaliTest[1269:6707] jxcore: stopBroadcasting
2015-12-03 19:26:18.762 ThaliTest[1269:6707] THEMultipeerSession stopping peer
2015-12-03 19:26:18.763 ThaliTest[1269:6707] multipeer session: stop timer
2015-12-03 19:26:18.764 Thali,Test[1269:6707] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
2015-12-03 19:26:18.766 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.773 ThaliTest[1269:6707] server: starting 1449167178766.1269.xJHzSQ==
,2015-12-03 19:26:18.774 ThaliTest[1269:6707] multipeer session: start timer: 0x1959e640
2015-12-03 19:26:18.775 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178766.1269
2015-12-03 19:26:18.776 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2015-12-03 19:26:18.778 ThaliTest[1269:6707] jxcore: stopBroadcasting
2015-12-03 19:26:18.779 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.780 ThaliTest[1269:6707] multipeer session: stop timer
2015-12-03 19:26:18.781 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.784 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.790 ThaliTest[1269:6707] server: starting 1449167178784.1269.u27gsg==
,2015-12-03 19:26:18.791 ThaliTest[1269:6707] multipeer session: start timer: 0x1966c1c0
2015-12-03 19:26:18.792 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178784.1269
2015-12-03 19:26:18.793 ThaliTest[1269:6707] jxcore: startBroadca,sting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.798 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.800 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.801 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.804 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.808 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.812 ThaliTest[1269:6707] server: starting 1449167178807.1269.8Zkh6g==
,2015-12-03 19:26:18.813 ThaliTest[1269:6707] multipeer session: start timer: 0x195a0600
,2015-12-03 19:26:18.817 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178807.1269
,2015-12-03 19:26:18.819 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.821 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.823 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.824 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.825 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.830 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.834 ThaliTest[1269:6707] server: starting 1449167178829.1269.OQ1QTw==
,2015-12-03 19:26:18.835 ThaliTest[1269:6707] multipeer session: start timer: 0x1966c900
,2015-12-03 19:26:18.840 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178829.1269
,2015-12-03 19:26:18.841 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.843 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.844 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.845 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.846 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.850 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.854 ThaliTest[1269:6707] server: starting 1449167178849.1269.YZexXQ==
,2015-12-03 19:26:18.855 ThaliTest[1269:6707] multipeer session: start timer: 0x1966cd70
,2015-12-03 19:26:18.858 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178849.1269
,2015-12-03 19:26:18.859 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.861 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.862 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.863 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.865 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.868 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.872 ThaliTest[1269:6707] server: starting 1449167178868.1269.ntmgpA==
,2015-12-03 19:26:18.873 ThaliTest[1269:6707] multipeer session: start timer: 0x195a2660
,2015-12-03 19:26:18.876 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178868.1269
,2015-12-03 19:26:18.877 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.880 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.881 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.882 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.882 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:18.886 ThaliTest[1269:6707] jxcore: startBroadcasting
,2015-12-03 19:26:18.890 ThaliTest[1269:6707] server: starting 1449167178886.1269.DiiOTg==
,2015-12-03 19:26:18.891 ThaliTest[1269:6707] multipeer session: start timer: 0x1966cf90
,2015-12-03 19:26:18.894 ThaliTest[1269:6707] THEMultipeerSession initialized peer 1449167178886.1269
,2015-12-03 19:26:18.895 ThaliTest[1269:6707] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 19:26:18.898 ThaliTest[1269:6707] jxcore: stopBroadcasting
,2015-12-03 19:26:18.899 ThaliTest[1269:6707] THEMultipeerSession stopping peer
,2015-12-03 19:26:18.900 ThaliTest[1269:6707] multipeer session: stop timer
,2015-12-03 19:26:18.901 ThaliTest[1269:6707] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup

```
