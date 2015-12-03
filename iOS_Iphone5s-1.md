#### Test 506502788f08dc7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CAB0C220-9251-411B-BC26-848A226D357D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CAB0C220-9251-411B-BC26-848A226D357D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D935DC6-D1F4-4074-B55A-09C075B0182A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60713"
,(lldb)     command script import "/tmp/CAB0C220-9251-411B-BC26-848A226D357D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:03:12.320 ThaliTest[2495:2317616] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/87F2DB39-9684-4CD8-B3C7-805F6FC5B0E7/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:03:12.730 ThaliTest[2495:2317616] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 17:03:12.731 ThaliTest[2495:2317616] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:03:12.740 ThaliTest[2495:2317616] Unlimited access to network resources
,2015-12-03 17:03:12.748 ThaliTest[2495:2317616] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:03:16.267 ThaliTest[2495:2317616] Resetting plugins due to page load.
,2015-12-03 17:03:16.717 ThaliTest[2495:2317616] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/1D935DC6-D1F4-4074-B55A-09C075B0182A/ThaliTest.app/www/index.html
,2015-12-03 17:03:16.870 ThaliTest[2495:2317616] JXcore Cordova plugin initializing
2015-12-03 17:03:16.872 ThaliTest[2495:2317742] JXcore instance initializing
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
,2015-12-03 17:04:35.680 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.864 ThaliTest[2495:2317742] server: starting 1449158675679.2495.3GkVKw==
,2015-12-03 17:04:35.866 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a3c0700
,2015-12-03 17:04:35.867 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158675679.2495
2015-12-03 17:04:35.868 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.873 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:35.874 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
2015-12-03 17:04:35.875 ThaliTest[2495:2317742] multipeer session: stop timer
2015-12-03 17:04:35.875 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
ok 46 Shoul,d be able to call stopBroadcasting without error
,2015-12-03 17:04:35.879 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.892 ThaliTest[2495:2317742] server: starting 1449158675879.2495.H2W4kw==
2015-12-03 17:04:35.894 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a412e70
2015-12-03 17:04:35.895 ThaliTest[2495:2317742] THEMultipeerSession in,itialized peer 1449158675879.2495
2015-12-03 17:04:35.896 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-03 17:04:35.899 ThaliTest[2495:2317742] jxcore: stopBroadcasting
2,015-12-03 17:04:35.900 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
2015-12-03 17:04:35.900 ThaliTest[2495:2317742] multipeer session: stop timer
2015-12-03 17:04:35.901 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
2015-12-03 17:04:35.907 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.914 ThaliTest[2495:2317742] server: starting 1449158675907.2495.8v0cjA==
2015-12-03 17:04:35.916 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a412e70
2015-12-03 17:04:35.916 ThaliTest[2495:2317742] THEMultipeerSession in,itialized peer 1449158675907.2495
2015-12-03 17:04:35.918 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.921 ThaliTest[2495:2317742] jxcore: stopBroadcasting
2015-12-03 17:04:35.922 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.923 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:35.924 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.927 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.943 ThaliTest[2495:2317742] server: starting 1449158675926.2495.AEYPXg==
,2015-12-03 17:04:35.944 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a4161e0
2015-12-03 17:04:35.947 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158675926.2495
2015-12-03 17:04:35.948 ThaliTest[2495:2317742] jxcore: sta,rtBroadcasting: success
ok 51 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.952 ThaliTest[2495:2317742] jxcore: stopBroadcasting
2015-12-03 17:04:35.954 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.954 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:35.957 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.971 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.974 ThaliTest[2495:2317742] server: starting 1449158675970.2495.7XUfkQ==
,2015-12-03 17:04:35.978 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a4146b0
,2015-12-03 17:04:35.981 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158675970.2495
,2015-12-03 17:04:35.982 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
,2015-12-03 17:04:35.985 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:35.986 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:35.988 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:35.991 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:35.995 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:35.998 ThaliTest[2495:2317742] server: starting 1449158675995.2495.AO3hVA==
,2015-12-03 17:04:36.000 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a4174a0
,2015-12-03 17:04:36.004 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158675995.2495
,2015-12-03 17:04:36.006 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 55 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.009 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:36.010 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.011 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:36.013 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 56 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.018 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:36.020 ThaliTest[2495:2317742] server: starting 1449158676018.2495.1XugCg==
,2015-12-03 17:04:36.024 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a418040
,2015-12-03 17:04:36.028 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158676018.2495
,2015-12-03 17:04:36.030 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.034 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:36.035 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.036 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:36.037 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 58 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.043 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:36.045 ThaliTest[2495:2317742] server: starting 1449158676042.2495.Hm8oVQ==
,2015-12-03 17:04:36.049 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a3babf0
,2015-12-03 17:04:36.053 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158676042.2495
,2015-12-03 17:04:36.055 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.058 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:36.059 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.060 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:36.062 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.066 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:36.068 ThaliTest[2495:2317742] server: starting 1449158676066.2495.dG41kA==
,2015-12-03 17:04:36.071 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a418680
,2015-12-03 17:04:36.074 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158676066.2495
,2015-12-03 17:04:36.074 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.077 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:36.077 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.078 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:36.080 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:36.083 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:36.084 ThaliTest[2495:2317742] server: starting 1449158676082.2495.t/3tgQ==
,2015-12-03 17:04:36.087 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a419270
,2015-12-03 17:04:36.089 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158676082.2495
,2015-12-03 17:04:36.090 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 63 Should be able to call startBroadcasting without error
,2015-12-03 17:04:36.093 ThaliTest[2495:2317742] jxcore: stopBroadcasting
,2015-12-03 17:04:36.093 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:36.094 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:36.094 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:04:37.911 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:37.914 ThaliTest[2495:2317742] server: starting 1449158677911.2495.E7xADg==
2015-12-03 17:04:37.915 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a3b6490
,2015-12-03 17:04:37.916 ThaliTest[2495:2317742] THEMultipeerSession initialized peer 1449158677911.2495
2015-12-03 17:04:37.917 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2015-12-03 17:04:37.921 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:37.922 ThaliTest[2495:2317742] jxcore: startBroadcasting: failure
,ok 66 Cannot call startBroadcasting twice
2015-12-03 17:04:37.925 ThaliTest[2495:2317742] jxcore: stopBroadcasting
2015-12-03 17:04:37.925 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:37.926 ThaliTest[2495:2317742] multipeer session: stop timer
,2015-12-03 17:04:37.927 ThaliTest[2495:2317742] jxcore: stopBroadcasting: success
,ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:04:39.862 ThaliTest[2495:2317742] jxcore: startBroadcasting
,2015-12-03 17:04:39.865 ThaliTest[2495:2317742] server: starting 1449158679861.2495./lxwog==
2015-12-03 17:04:39.866 ThaliTest[2495:2317742] multipeer session: start timer: 0x1a3b34f0
2015-12-03 17:04:39.867 ThaliTest[2495:2317742] THEMultipeerSession in,itialized peer 1449158679861.2495
2015-12-03 17:04:39.867 ThaliTest[2495:2317742] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-03 17:04:39.872 ThaliTest[2495:2317742] jxcore: connect foobar
2015-12-03 17:04:39.873 ThaliTest[2495:2317742] client: unknown peer foobar
2015-12-03 17:04:39.873 ThaliTest[2495:231774,2] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-03 17:04:39.876 ThaliTest[2495:2317742] jxcore: stopBroadcasting
2015-12-03 17:04:39.880 ThaliTest[2495:2317742] THEMultipeerSession stopping peer
,2015-12-03 17:04:39.885 ThaliTest[2495:2317742] multipeer session: stop timer
2015-12-03 17:04:39.899 ThaliTest[2495:2317881] -[__NSCFSet peers]: unrecognized selector sent to instance 0x1a41faf0
,2015-12-03 17:04:39.901 ThaliTest[2495:2317881] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '-[__NSCFSet peers]: unrecognized selector sent to instance 0x1a41faf0'
*** First throw call stack:
(0x2a8a745f 0x3876ac8b, 0x2a8ac879 0x2a8aa797 0x2a7dc008 0x2c82ad53 0x38cd52e3 0x38cdd729 0x38cd7aad 0x38cdef9f 0x38ce03c3 0x38e3bdc1 0x38e3bb14)
libc++abi.dylib: terminating with uncaught exception of type NSException
2015-12-03 17:04:39.900 ThaliTest[2495:2317742] jxcore: st,opBroadcasting: success
,* thread #1: tid = 0x235d30, 0x38dad474 libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x38dad474 libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x38dad26c libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2a86d582 CoreFoundation`<redacted> + 146
    frame #3: 0x2a86bb28 CoreFoundation`<redacted> + 1016
    frame #4: 0x2a7b93b0 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #5: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #6: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #7: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #8: 0x000995e2 ThaliTest`main + 50

```
