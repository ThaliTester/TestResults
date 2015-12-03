#### Test 50650278c5de1fe_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4DB07DC3-440F-40A5-90B4-D17DFEDBABE4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4DB07DC3-440F-40A5-90B4-D17DFEDBABE4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c5de1fe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3756B816-DDDD-4087-966A-00A7414601BF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60950"
,(lldb)     command script import "/tmp/4DB07DC3-440F-40A5-90B4-D17DFEDBABE4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 19:24:40.904 ThaliTest[2674:2236964] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31E5FC54-780A-47D8-BFCE-A8DC84D93405/Library/Cookies/Cookies.binarycookies
,2015-12-03 19:24:41.290 ThaliTest[2674:2236964] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 19:24:41.291 ThaliTest[2674:2236964] Multi-tasking -> Device: YES, App: YES
,2015-12-03 19:24:41.299 ThaliTest[2674:2236964] Unlimited access to network resources
,2015-12-03 19:24:41.305 ThaliTest[2674:2236964] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 19:24:44.846 ThaliTest[2674:2236964] Resetting plugins due to page load.
,2015-12-03 19:24:45.239 ThaliTest[2674:2236964] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/3756B816-DDDD-4087-966A-00A7414601BF/ThaliTest.app/www/index.html
,2015-12-03 19:24:45.362 ThaliTest[2674:2236964] JXcore Cordova plugin initializing
2015-12-03 19:24:45.363 ThaliTest[2674:2237102] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
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
--- running teardown
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
,running teardown
,# another
,CoordinatorConnector-debug: setup:another
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:another
,ok 3 sane
,# setup
,CoordinatorConnector-debug: teardown:another
running teardown
,# successfully create a new pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully create a new pkcs12 file and return hash value
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:successfully create a new pkcs12 file and return hash value
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
ok 7 should be equal
,ok 8 should not throw
,# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
running teardown
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:successfully read a previous pkcs12 file and return hash value
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
ok 11 should not throw
,ok 12 should be equal
,ok 13 should be equal
,# setup
,CoordinatorConnector-debug: teardown:successfully read a previous pkcs12 file and return hash value
,running teardown
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
,--- running teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
,running teardown
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
,running teardown
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
--- running teardown
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
,2015-12-03 19:26:16.708 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:16.888 ThaliTest[2674:2237102] server: starting 1449167176707.2674.9x4A3Q==
,2015-12-03 19:26:16.889 ThaliTest[2674:2237102] multipeer session: start timer: 0x18adcf40
,2015-12-03 19:26:16.890 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167176707.2674
2015-12-03 19:26:16.891 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-03 19:26:16.897 ThaliTest[2674:2237102] jxcore: stopBroadcasting
2015-12-03 19:26:16.898 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.898 ThaliTest[2674:2237102] multipeer session: stop timer
2015-12-03 19:26:16.,899 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.902 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:16.907 ThaliTest[2674:2237102] server: starting 1449167176901.2674.TMBHDg==
2015-12-03 19:26:16.910 ThaliTest[2674:2237102] multipeer session: start timer: 0x18ade660
2015-12-03 19:26:16.914 ThaliTest[2674:2237102] THEMultipeerSession in,itialized peer 1449167176901.2674
,2015-12-03 19:26:16.915 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-03 19:26:16.926 ThaliTest[2674:2237102] jxcore: stopBroadcasting
2015-12-03 19:26:16.926 ThaliTest[26,74:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.927 ThaliTest[2674:2237102] multipeer session: stop timer
2015-12-03 19:26:16.927 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.930 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:16.935 ThaliTest[2674:2237102] server: starting 1449167176929.2674.MsIzIg==
,2015-12-03 19:26:16.936 ThaliTest[2674:2237102] multipeer session: start timer: 0x18e0aea0
,2015-12-03 19:26:16.937 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167176929.2674
,2015-12-03 19:26:16.937 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
2015-12-03 19:26:16.940 ThaliTest[2674:2237102] jxcore: stopBroadcasting
2015-12-03 19:26:16.941 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.942 ThaliTest[267,4:2237102] multipeer session: stop timer
2015-12-03 19:26:16.943 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.946 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:16.954 ThaliTest[2674:2237102] server: starting 1449167176945.2674.AOgpBA==
2015-12-03 19:26:16.955 ThaliTest[2674:2237102] multipeer session: start timer: 0x18e07e40
2015-12-03 19:26:16.956 ThaliTest[2674:2237102] THEMultipeerSession in,itialized peer 1449167176945.2674
2015-12-03 19:26:16.957 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2015-12-03 19:26:16.960 ThaliTest[2674:2237102] jxcore: stopBroadcasting
2015-12-03 19:26:16.961 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.961 ThaliTest[267,4:2237102] multipeer session: stop timer
2015-12-03 19:26:16.962 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-03 19:26:16.964 ThaliTest[2674:2237102] jxcore: startBroadcast,ing
,2015-12-03 19:26:16.977 ThaliTest[2674:2237102] server: starting 1449167176963.2674.DFXN+A==
,2015-12-03 19:26:16.978 ThaliTest[2674:2237102] multipeer session: start timer: 0x18ae0430
2015-12-03 19:26:16.978 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167176963.2674
2015-12-03 19:26:16.979 ThaliTest[2674:2237102] jxcore: sta,rtBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
2015-12-03 19:26:16.984 ThaliTest[2674:2237102] jxcore: stopBroadcasting
2015-12-03 19:26:16.984 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.985 ThaliTest[267,4:2237102] multipeer session: stop timer
2015-12-03 19:26:16.985 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:16.988 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:16.993 ThaliTest[2674:2237102] server: starting 1449167176987.2674.6koiqQ==
2015-12-03 19:26:16.994 ThaliTest[2674:2237102] multipeer session: start timer: 0x18ae14d0
2015-12-03 19:26:16.995 ThaliTest[2674:2237102] THEMultipeerSession in,itialized peer 1449167176987.2674
2015-12-03 19:26:16.996 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-03 19:26:16.998 ThaliTest[2674:2237102] jxcore: stopBroadcasting
,2015-12-03 19:26:16.999 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
2015-12-03 19:26:16.999 ThaliTest[2674:2237102] multipeer session: stop timer
,2015-12-03 19:26:16.999 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:17.001 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:17.011 ThaliTest[2674:2237102] server: starting 1449167177001.2674.X50oGA==
,2015-12-03 19:26:17.013 ThaliTest[2674:2237102] multipeer session: start timer: 0x18e06800
,2015-12-03 19:26:17.017 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167177001.2674
,2015-12-03 19:26:17.018 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 19:26:17.021 ThaliTest[2674:2237102] jxcore: stopBroadcasting
,2015-12-03 19:26:17.022 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
,2015-12-03 19:26:17.023 ThaliTest[2674:2237102] multipeer session: stop timer
,2015-12-03 19:26:17.026 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:17.029 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:17.031 ThaliTest[2674:2237102] server: starting 1449167177029.2674.ZGxLlA==
,2015-12-03 19:26:17.032 ThaliTest[2674:2237102] multipeer session: start timer: 0x18ae0970
,2015-12-03 19:26:17.035 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167177029.2674
,2015-12-03 19:26:17.037 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 19:26:17.040 ThaliTest[2674:2237102] jxcore: stopBroadcasting
,2015-12-03 19:26:17.041 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
,2015-12-03 19:26:17.041 ThaliTest[2674:2237102] multipeer session: stop timer
,2015-12-03 19:26:17.043 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:17.048 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:17.049 ThaliTest[2674:2237102] server: starting 1449167177047.2674.+6MW5g==
,2015-12-03 19:26:17.050 ThaliTest[2674:2237102] multipeer session: start timer: 0x18e04650
,2015-12-03 19:26:17.055 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167177047.2674
,2015-12-03 19:26:17.056 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 19:26:17.059 ThaliTest[2674:2237102] jxcore: stopBroadcasting
,2015-12-03 19:26:17.060 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
,2015-12-03 19:26:17.061 ThaliTest[2674:2237102] multipeer session: stop timer
,2015-12-03 19:26:17.062 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 19:26:17.067 ThaliTest[2674:2237102] jxcore: startBroadcasting
,2015-12-03 19:26:17.069 ThaliTest[2674:2237102] server: starting 1449167177066.2674.6VO3yQ==
,2015-12-03 19:26:17.071 ThaliTest[2674:2237102] multipeer session: start timer: 0x18e04480
,2015-12-03 19:26:17.074 ThaliTest[2674:2237102] THEMultipeerSession initialized peer 1449167177066.2674
,2015-12-03 19:26:17.075 ThaliTest[2674:2237102] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 19:26:17.077 ThaliTest[2674:2237102] jxcore: stopBroadcasting
,2015-12-03 19:26:17.078 ThaliTest[2674:2237102] THEMultipeerSession stopping peer
,2015-12-03 19:26:17.079 ThaliTest[2674:2237102] multipeer session: stop timer
,2015-12-03 19:26:17.081 ThaliTest[2674:2237102] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup

```
