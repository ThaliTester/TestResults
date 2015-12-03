#### Test 50650278c902ea2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ACA597DE-A15F-40BA-87B5-39BA62048FE7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/ACA597DE-A15F-40BA-87B5-39BA62048FE7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278c902ea2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A962D609-F20C-4E3E-B5FD-20F2A440D063/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60792"
,(lldb)     command script import "/tmp/ACA597DE-A15F-40BA-87B5-39BA62048FE7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:35:54.024 ThaliTest[2505:2321232] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75294496-F088-43BC-812A-B0442F005C27/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:35:54.435 ThaliTest[2505:2321232] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 17:35:54.437 ThaliTest[2505:2321232] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:35:54.445 ThaliTest[2505:2321232] Unlimited access to network resources
,2015-12-03 17:35:54.453 ThaliTest[2505:2321232] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:35:57.608 ThaliTest[2505:2321232] Resetting plugins due to page load.
,2015-12-03 17:35:57.904 ThaliTest[2505:2321232] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/A962D609-F20C-4E3E-B5FD-20F2A440D063/ThaliTest.app/www/index.html
,2015-12-03 17:35:58.075 ThaliTest[2505:2321232] JXcore Cordova plugin initializing
,2015-12-03 17:35:58.077 ThaliTest[2505:2321362] JXcore instance initializing
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
,2015-12-03 17:36:54.551 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:54.738 ThaliTest[2505:2321362] server: starting 1449160614550.2505.uWFw/A==
,2015-12-03 17:36:54.739 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a5c9fe0
2015-12-03 17:36:54.740 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614550.2505
2015-12-03 17:36:54.741 ThaliTest[2505:2321362] jxcore: sta,rtBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
2015-12-03 17:36:54.746 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:36:54.746 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 1,7:36:54.748 ThaliTest[2505:2321362] multipeer session: stop timer
2015-12-03 17:36:54.757 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
,ok 46 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.773 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:54.776 ThaliTest[2505:2321362] server: starting 1449160614772.2505.HKVr3A==
,2015-12-03 17:36:54.779 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a5c7060
,2015-12-03 17:36:54.789 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614772.2505
,2015-12-03 17:36:54.791 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
,ok 47 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.796 ThaliTest[2505:2321362] jxcore: stopBroadcasting
,2015-12-03 17:36:54.798 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.799 ThaliTest[2505:2321362] multipeer session: stop timer
,2015-12-03 17:36:54.806 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
,ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.815 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:54.818 ThaliTest[2505:2321362] server: starting 1449160614814.2505.CEN+6A==
,2015-12-03 17:36:54.829 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a5c51b0
,2015-12-03 17:36:54.830 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614814.2505
,2015-12-03 17:36:54.831 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
,ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.835 ThaliTest[2505:2321362] jxcore: stopBroadcasting
,2015-12-03 17:36:54.836 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.837 ThaliTest[2505:2321362] multipeer session: stop timer
,2015-12-03 17:36:54.841 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:36:54.846 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:54.849 ThaliTest[2505:2321362] server: starting 1449160614845.2505.pXLObA==
,2015-12-03 17:36:54.851 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a4a3ce0
,2015-12-03 17:36:54.856 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614845.2505
,2015-12-03 17:36:54.858 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
,2015-12-03 17:36:54.860 ThaliTest[2505:2321362] jxcore: stopBroadcasting
,2015-12-03 17:36:54.861 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
,2015-12-03 17:36:54.863 ThaliTest[2505:2321362] multipeer session: stop timer
,2015-12-03 17:36:54.866 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 52 Should be able to call stopBroadcasting without error
2015-12-03 17:36:54.868 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:54.870 ThaliTest[2505:2321362] server: starting 1449160614868.2505.pYyK5A==
2015-12-03 17:36:54.871 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a49c2f0
2015-12-03 17:36:54.872 ThaliTest[2505:2321362] THEMultipeerSession in,itialized peer 1449160614868.2505
2015-12-03 17:36:54.872 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 53 Should be able to call startBroadcasting without error
2015-12-03 17:36:54.874 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2,015-12-03 17:36:54.875 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.875 ThaliTest[2505:2321362] multipeer session: stop timer
2015-12-03 17:36:54.876 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 54 Should, be able to call stopBroadcasting without error
2015-12-03 17:36:54.878 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-03 17:36:54.883 ThaliTest[2505:2321362] server: starting 1449160614878.2505.diflvw==
2015-12-03 17:36:54.884 ThaliTest[2505,:2321362] multipeer session: start timer: 0x1a499420
2015-12-03 17:36:54.885 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614878.2505
2015-12-03 17:36:54.885 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 55 Should ,be able to call startBroadcasting without error
2015-12-03 17:36:54.894 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:36:54.894 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.895 ThaliTest[2505:2321362] mu,ltipeer session: stop timer
2015-12-03 17:36:54.895 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 56 Should be able to call stopBroadcasting without error
2015-12-03 17:36:54.899 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-,03 17:36:54.901 ThaliTest[2505:2321362] server: starting 1449160614897.2505.734EgQ==
2015-12-03 17:36:54.902 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a5c32c0
2015-12-03 17:36:54.904 ThaliTest[2505:2321362] THEMultipeerSession initialize,d peer 1449160614897.2505
2015-12-03 17:36:54.905 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 57 Should be able to call startBroadcasting without error
2015-12-03 17:36:54.906 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-0,3 17:36:54.907 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.907 ThaliTest[2505:2321362] multipeer session: stop timer
2015-12-03 17:36:54.908 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 58 Should be able, to call stopBroadcasting without error
2015-12-03 17:36:54.910 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-03 17:36:54.914 ThaliTest[2505:2321362] server: starting 1449160614909.2505.up5D+A==
2015-12-03 17:36:54.914 ThaliTest[2505:2321362,] multipeer session: start timer: 0x1a5c1a90
2015-12-03 17:36:54.915 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614909.2505
2015-12-03 17:36:54.915 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 59 Should be able ,to call startBroadcasting without error
2015-12-03 17:36:54.917 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:36:54.917 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.918 ThaliTest[2505:2321362] multipeer ,session: stop timer
2015-12-03 17:36:54.918 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 60 Should be able to call stopBroadcasting without error
2015-12-03 17:36:54.921 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-03 17:36,:54.925 ThaliTest[2505:2321362] server: starting 1449160614921.2505.Paz97A==
2015-12-03 17:36:54.926 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a5c22f0
2015-12-03 17:36:54.926 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1,449160614921.2505
2015-12-03 17:36:54.927 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 61 Should be able to call startBroadcasting without error
2015-12-03 17:36:54.928 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:36:,54.929 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.930 ThaliTest[2505:2321362] multipeer session: stop timer
2015-12-03 17:36:54.931 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 62 Should be able to call, stopBroadcasting without error
2015-12-03 17:36:54.932 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-03 17:36:54.935 ThaliTest[2505:2321362] server: starting 1449160614932.2505.QtlRlA==
2015-12-03 17:36:54.936 ThaliTest[2505:2321362] multip,eer session: start timer: 0x1a5c1080
2015-12-03 17:36:54.936 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160614932.2505
2015-12-03 17:36:54.936 ThaliTest[2505:2321362] jxcore: startBroadcasting: success
ok 63 Should be able to call ,startBroadcasting without error
2015-12-03 17:36:54.939 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:36:54.942 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:36:54.942 ThaliTest[2505:2321362] multipeer session:, stop timer
2015-12-03 17:36:54.945 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 64 Should be able to call stopBroadcasting without error
# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:36:56.829 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:36:56.832 ThaliTest[2505:2321362] server: starting 1449160616829.2505.R70/Mw==
,2015-12-03 17:36:56.833 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a48f3c0
2015-12-03 17:36:56.834 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160616829.2505
2015-12-03 17:36:56.835 ThaliTest[2505:2321362] jxcore: sta,rtBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
,2015-12-03 17:36:56.839 ThaliTest[2505:2321362] jxcore: startBroadcasting
2015-12-03 17:36:56.840 ThaliTest[2505:2321362] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
2015-12-03 17:36:56.843 ThaliTest[2505:2321362] jxcore,: stopBroadcasting
2015-12-03 17:36:56.845 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
,2015-12-03 17:36:56.847 ThaliTest[2505:2321362] multipeer session: stop timer
,2015-12-03 17:36:56.848 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
,running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:37:00.973 ThaliTest[2505:2321362] jxcore: startBroadcasting
,2015-12-03 17:37:00.976 ThaliTest[2505:2321362] server: starting 1449160620973.2505.8sydIg==
,2015-12-03 17:37:00.978 ThaliTest[2505:2321362] multipeer session: start timer: 0x1a492030
2015-12-03 17:37:00.979 ThaliTest[2505:2321362] THEMultipeerSession initialized peer 1449160620973.2505
2015-12-03 17:37:00.980 ThaliTest[2505:2321362] jxcore: sta,rtBroadcasting: success
ok 68 Should be able to call startBroadcasting without error
,2015-12-03 17:37:00.986 ThaliTest[2505:2321362] jxcore: connect foobar
2015-12-03 17:37:00.987 ThaliTest[2505:2321362] client: unknown peer foobar
,2015-12-03 17:37:00.988 ThaliTest[2505:2321362] jxcore: connect: fail: Unknown peer
,ok 69 Should not connect to a bad peer
2015-12-03 17:37:00.993 ThaliTest[2505:2321362] jxcore: stopBroadcasting
2015-12-03 17:37:00.995 ThaliTest[2505:2321362] THEMultipeerSession stopping peer
2015-12-03 17:37:00.997 ThaliTest[2505:2321362] multipeer s,ession: stop timer
2015-12-03 17:37:00.998 ThaliTest[2505:2321362] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup
,* thread #1: tid = 0x236b50, 0x38dad474 libsystem_kernel.dylib`mach_msg_trap + 20, queue = 'com.apple.main-thread'
  * frame #0: 0x38dad474 libsystem_kernel.dylib`mach_msg_trap + 20
    frame #1: 0x38dad26c libsystem_kernel.dylib`mach_msg + 40
    frame #2: 0x2a86d582 CoreFoundation`<redacted> + 146
    frame #3: 0x2a86bb28 CoreFoundation`<redacted> + 1016
    frame #4: 0x2a7b93b0 CoreFoundation`CFRunLoopRunSpecific + 476
    frame #5: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #6: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #7: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #8: 0x000b45e2 ThaliTest`main + 50

```
