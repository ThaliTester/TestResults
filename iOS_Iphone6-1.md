#### Test 50650278c902ea2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/801F0EEB-DB73-4D40-BACB-A4EB4BFEE7E0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/801F0EEB-DB73-4D40-BACB-A4EB4BFEE7E0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/933156F7-BCAE-4FDC-B608-CB7D075AE858/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60790"
,(lldb)     command script import "/tmp/801F0EEB-DB73-4D40-BACB-A4EB4BFEE7E0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2015-12-03 17:35:50.155 ThaliTest[2645:2224853] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67CCF3AF-11FD-4E77-BED2-1D0A4ABF19B5/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:35:50.557 ThaliTest[2645:2224853] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 17:35:50.558 ThaliTest[2645:2224853] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:35:50.566 ThaliTest[2645:2224853] Unlimited access to network resources
,2015-12-03 17:35:50.572 ThaliTest[2645:2224853] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:35:53.957 ThaliTest[2645:2224853] Resetting plugins due to page load.
,2015-12-03 17:35:54.305 ThaliTest[2645:2224853] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/933156F7-BCAE-4FDC-B608-CB7D075AE858/ThaliTest.app/www/index.html
,2015-12-03 17:35:54.432 ThaliTest[2645:2224853] JXcore Cordova plugin initializing
2015-12-03 17:35:54.432 ThaliTest[2645:2224984] JXcore instance initializing
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
running teardown
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,CoordinatorConnector-debug: setup:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,2015-12-03 17:36:54.561 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.737 ThaliTest[2645:2224984] server: starting 1449160614560.2645.puXbtQ==
,2015-12-03 17:36:54.738 ThaliTest[2645:2224984] multipeer session: start timer: 0x191e0df0
2015-12-03 17:36:54.739 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614560.2645
2015-12-03 17:36:54.739 ThaliTest[2645:2224984] jxcore: sta,rtBroadcasting: success
,ok 45 Should be able to call startBroadcasting without error
2015-12-03 17:36:54.744 ThaliTest[2645:2224984] jxcore: stopBroadcasting
2015-12-03 17:36:54.745 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
2015-12-03 17:36:54.745 ThaliTest[264,5:2224984] multipeer session: stop timer
2015-12-03 17:36:54.746 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-03 17:36:54.748 ThaliTest[2645:2224984] jxcore: startBroadcast,ing
,2015-12-03 17:36:54.763 ThaliTest[2645:2224984] server: starting 1449160614748.2645.+PoI2Q==
,2015-12-03 17:36:54.765 ThaliTest[2645:2224984] multipeer session: start timer: 0x194d0cd0
,2015-12-03 17:36:54.772 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614748.2645
,2015-12-03 17:36:54.773 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.777 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.778 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.779 ThaliTest[2645:2224984] multipeer session: stop timer
2015-12-03 17:36:54.783 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.788 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.791 ThaliTest[2645:2224984] server: starting 1449160614788.2645.9g+L/w==
,2015-12-03 17:36:54.795 ThaliTest[2645:2224984] multipeer session: start timer: 0x191dc0c0
,2015-12-03 17:36:54.800 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614788.2645
,2015-12-03 17:36:54.802 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.806 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.807 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.809 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.814 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.817 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.820 ThaliTest[2645:2224984] server: starting 1449160614817.2645.P/0dww==
,2015-12-03 17:36:54.825 ThaliTest[2645:2224984] multipeer session: start timer: 0x194d2320
,2015-12-03 17:36:54.830 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614817.2645
,2015-12-03 17:36:54.831 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.834 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.835 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.836 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.838 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.841 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.844 ThaliTest[2645:2224984] server: starting 1449160614841.2645.WeKJbg==
,2015-12-03 17:36:54.846 ThaliTest[2645:2224984] multipeer session: start timer: 0x191db590
,2015-12-03 17:36:54.848 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614841.2645
,2015-12-03 17:36:54.849 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.851 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.852 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.853 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.855 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.858 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.860 ThaliTest[2645:2224984] server: starting 1449160614858.2645.0k6Ntw==
,2015-12-03 17:36:54.863 ThaliTest[2645:2224984] multipeer session: start timer: 0x194ceb00
,2015-12-03 17:36:54.867 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614858.2645
,2015-12-03 17:36:54.868 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.870 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.871 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.872 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.875 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.879 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.881 ThaliTest[2645:2224984] server: starting 1449160614878.2645.r27APw==
,2015-12-03 17:36:54.884 ThaliTest[2645:2224984] multipeer session: start timer: 0x191d9b10
,2015-12-03 17:36:54.887 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614878.2645
,2015-12-03 17:36:54.888 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.891 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.892 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.894 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.897 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.900 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.902 ThaliTest[2645:2224984] server: starting 1449160614900.2645.CV9HBw==
,2015-12-03 17:36:54.905 ThaliTest[2645:2224984] multipeer session: start timer: 0x191d9d80
,2015-12-03 17:36:54.908 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614900.2645
,2015-12-03 17:36:54.909 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.912 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.913 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.914 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.915 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.920 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.922 ThaliTest[2645:2224984] server: starting 1449160614919.2645.evXV8A==
,2015-12-03 17:36:54.927 ThaliTest[2645:2224984] multipeer session: start timer: 0x191d7160
,2015-12-03 17:36:54.931 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614919.2645
,2015-12-03 17:36:54.933 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.935 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.936 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.938 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.940 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.942 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:54.944 ThaliTest[2645:2224984] server: starting 1449160614942.2645.xAG5AQ==
,2015-12-03 17:36:54.946 ThaliTest[2645:2224984] multipeer session: start timer: 0x191d7c80
,2015-12-03 17:36:54.948 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160614942.2645
,2015-12-03 17:36:54.949 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.951 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:54.952 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.952 ThaliTest[2645:2224984] multipeer session: stop timer
,2015-12-03 17:36:54.954 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:36:56.820 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:56.823 ThaliTest[2645:2224984] server: starting 1449160616820.2645.kSWglQ==
,2015-12-03 17:36:56.824 ThaliTest[2645:2224984] multipeer session: start timer: 0x194c9c80
,2015-12-03 17:36:56.825 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160616820.2645
2015-12-03 17:36:56.825 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
ok 65 Should be able to call startBroadcasting without error
2015-,12-03 17:36:56.828 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:36:56.829 ThaliTest[2645:2224984] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-03 17:36:56.833 ThaliTest[2645:2224984] jxcore: stopBroadcasting
,2015-12-03 17:36:56.834 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
2015-12-03 17:36:56.837 ThaliTest[2645:2224984] multipeer session: stop timer
2015-12-03 17:36:56.837 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:37:00.097 ThaliTest[2645:2224984] jxcore: startBroadcasting
,2015-12-03 17:37:00.098 ThaliTest[2645:2224984] server: starting 1449160620097.2645.pBy2Hg==
2015-12-03 17:37:00.098 ThaliTest[2645:2224984] multipeer session: start timer: 0x191d39e0
2015-12-03 17:37:00.098 ThaliTest[2645:2224984] THEMultipeerSession initialized peer 1449160620097.2645
2015-12-03 17:37:00.099 ThaliTest[2645:2224984] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
,2015-12-03 17:37:00.100 ThaliTest[2645:2224984] jxcore: connect foobar
2015-12-03 17:37:00.100 ThaliTest[2645:2224984] client: unknown peer foobar
2015-12-03 17:37:00.100 ThaliTest[2645:2224984] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-03 17:37:00.101 ThaliTest[2645:2224984] jxcore: stopBroadcasting
2015-12-03 17:37:00.102 ThaliTest[2645:2224984] THEMultipeerSession stopping peer
2015-12-03 17:37:00.102 ThaliTest[2645:2224984] multipeer session: stop timer
2015-12-03 17:37:00.,102 ThaliTest[2645:2224984] jxcore: stopBroadcasting: success
,ok 70 Should be able to call stopBroadcasting without error
,# setup

```
