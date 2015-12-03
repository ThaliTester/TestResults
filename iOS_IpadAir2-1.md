#### Test 506502788f08dc7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C001773A-593B-499A-8BC6-B4374377EDA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C001773A-593B-499A-8BC6-B4374377EDA4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f08dc7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/29E223ED-6B0E-4D14-AF3A-E06B2BB40FE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60708"
,(lldb)     command script import "/tmp/C001773A-593B-499A-8BC6-B4374377EDA4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 17:02:22.706 ThaliTest[1929:3005024] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2131F67E-A430-4EB5-ABCD-D25B839B40FD/Library/Cookies/Cookies.binarycookies
,2015-12-03 17:02:22.988 ThaliTest[1929:3005024] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 17:02:22.989 ThaliTest[1929:3005024] Multi-tasking -> Device: YES, App: YES
,2015-12-03 17:02:22.995 ThaliTest[1929:3005024] Unlimited access to network resources
,2015-12-03 17:02:23.001 ThaliTest[1929:3005024] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 17:02:27.188 ThaliTest[1929:3005024] Resetting plugins due to page load.
,2015-12-03 17:02:28.617 ThaliTest[1929:3005024] Finished load of: file:///var/mobile/Containers/Bundle/Application/29E223ED-6B0E-4D14-AF3A-E06B2BB40FE0/ThaliTest.app/www/index.html
,2015-12-03 17:02:28.764 ThaliTest[1929:3005024] JXcore Cordova plugin initializing
2015-12-03 17:02:28.764 ThaliTest[1929:3005196] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrupt pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error","ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error","ThaliEmitter calls startBroadcasting twice with error","ThaliEmitter throws on connection to bad peer","ThaliEmitter throws on disconnect to ,bad peer","ThaliEmitter can discover and connect to peers","ThaliEmitter can discover and connect to peers and then fail on double connect","ThaliEmitter can discover and connect to peers and then fail on double disconnect","ThaliEmitter can connect and se,nd data","ThaliEmitter handles socket disconnect correctly"]
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
running teardown
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
,ok 7 should be equal
,ok 8 should not throw
,# setup
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
--- running teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
ok 32 should be equal
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
ok 37 should be equal
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
,running teardown
,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,CoordinatorConnector-debug: setup:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,2015-12-03 17:04:38.119 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.208 ThaliTest[1929:3005196] server: starting 1449158678119.1929.ueOkTQ==
,2015-12-03 17:04:38.208 ThaliTest[1929:3005196] multipeer session: start timer: 0x16f20b40
,2015-12-03 17:04:38.209 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678119.1929
2015-12-03 17:04:38.209 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
ok 45 Should be able to call startBroadcasting without error
,2015-12-03 17:04:38.211 ThaliTest[1929:3005196] jxcore: stopBroadcasting
,2015-12-03 17:04:38.211 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.211 ThaliTest[1929:3005196] multipeer session: stop timer
2015-12-03 17:04:38.212 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 46 Should be able to call stopBroadcasting without error
2015-12-03 17:04:38.212 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.215 ThaliTest[1929:3005196] server: starting 1449158678212.1929.kAjENQ==
2015-12-03 17:04:38.215 ThaliTest[1929:3005196] multipeer session: start timer: 0x18d350d0
2015-12-03 17:04:38.215 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678212.1929
2015-12-03 17:04:38.215 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
ok 47 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.216 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2,015-12-03 17:04:38.216 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.217 ThaliTest[1929:3005196] multipeer session: stop timer
,2015-12-03 17:04:38.218 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 48 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:38.219 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.221 ThaliTest[1929:3005196] server: starting 1449158678219.1929.zZIZTQ==
2015-12-03 17:04:38.221 ThaliTest[1929:3005196] multipeer session: start timer: 0x18d33e10
2015-12-03 17:04:38.221 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678219.1929
2015-12-03 17:04:38.221 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
ok 49 Should be able to call startBroadcasting without error
,2015-12-03 17:04:38.222 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:38.223 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.223 ThaliTest[1929:3005196] multipeer session: stop timer
,2015-12-03 17:04:38.225 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
,ok 50 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:38.226 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.228 ThaliTest[1929:3005196] server: starting 1449158678226.1929.Tk/XSA==
,2015-12-03 17:04:38.229 ThaliTest[1929:3005196] multipeer session: start timer: 0x16f1f0c0
2015-12-03 17:04:38.229 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678226.1929
2015-12-03 17:04:38.229 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 51 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.230 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:38.230 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.231 ThaliTest[192,9:3005196] multipeer session: stop timer
2015-12-03 17:04:38.231 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
,ok 52 Should be able to call stopBroadcasting without error
2015-12-03 17:04:38.233 ThaliTest[1929:3005196] jxcore: startBroadcasting
2015-12-03 17:04:38.234 ThaliTest[1929:3005196] server: starting 1449158678232.1929.LujSqg==
2015-12-03 17:04:38.234 Th,aliTest[1929:3005196] multipeer session: start timer: 0x16f254b0
2015-12-03 17:04:38.234 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678232.1929
2015-12-03 17:04:38.234 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 53 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.236 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:38.236 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.236 ThaliTest[1929:3005196] multipeer session: stop timer
,2015-12-03 17:04:38.237 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 54 Should be able to call stopBroadcasting without error
,2015-12-03 17:04:38.239 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.242 ThaliTest[1929:3005196] server: starting 1449158678238.1929.SYP98Q==
2015-12-03 17:04:38.243 ThaliTest[1929:3005196] multipeer session: start timer: 0x16f25730
2015-12-03 17:04:38.243 ThaliTest[1929:3005196] THEMultipeerSession in,itialized peer 1449158678238.1929
2015-12-03 17:04:38.243 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
ok 55 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.244 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2,015-12-03 17:04:38.244 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.244 ThaliTest[1929:3005196] multipeer session: stop timer
2015-12-03 17:04:38.244 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 56 Should, be able to call stopBroadcasting without error
,2015-12-03 17:04:38.244 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.247 ThaliTest[1929:3005196] server: starting 1449158678244.1929.3w2d9g==
,2015-12-03 17:04:38.248 ThaliTest[1929:3005196] multipeer session: start timer: 0x16f1f480
2015-12-03 17:04:38.248 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678244.1929
2015-12-03 17:04:38.248 ThaliTest[1929:3005196] jxcore: sta,rtBroadcasting: success
,ok 57 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.250 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:38.251 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.251 ThaliTest[192,9:3005196] multipeer session: stop timer
2015-12-03 17:04:38.251 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 58 Should be able to call stopBroadcasting without error
2015-12-03 17:04:38.252 ThaliTest[1929:3005196] jxcore: startBroadcast,ing
2015-12-03 17:04:38.254 ThaliTest[1929:3005196] server: starting 1449158678251.1929.AIGPxg==
2015-12-03 17:04:38.254 ThaliTest[1929:3005196] multipeer session: start timer: 0x18d28490
,2015-12-03 17:04:38.254 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678251.1929
2015-12-03 17:04:38.254 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 59 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.255 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:38.255 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:38.255 ThaliTest[192,9:3005196] multipeer session: stop timer
2015-12-03 17:04:38.256 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
,ok 60 Should be able to call stopBroadcasting without error
2015-12-03 17:04:38.258 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.260 ThaliTest[1929:3005196] server: starting 1449158678258.1929./V3pNQ==
,2015-12-03 17:04:38.261 ThaliTest[1929:3005196] multipeer session: start timer: 0x16f23f50
2015-12-03 17:04:38.262 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158678258.1929
2015-12-03 17:04:38.262 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 61 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.265 ThaliTest[1929:3005196] jxcore: stopBroadcasting
,2015-12-03 17:04:38.265 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
,2015-12-03 17:04:38.265 ThaliTest[1929:3005196] multipeer session: stop timer
2015-12-03 17:04:38.266 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
,ok 62 Should be able to call stopBroadcasting without error
2015-12-03 17:04:38.268 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:38.269 ThaliTest[1929:3005196] server: starting 1449158678267.1929.r6qY+g==
2015-12-03 17:04:38.269 ThaliTest[1929:3005196] multipeer session: start timer: 0x18d2e2e0
2015-12-03 17:04:38.269 ThaliTest[1929:3005196] THEMultipeerSession in,itialized peer 1449158678267.1929
2015-12-03 17:04:38.270 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
ok 63 Should be able to call startBroadcasting without error
2015-12-03 17:04:38.270 ThaliTest[1929:3005196] jxcore: stopBroadcasting
,2015-12-03 17:04:38.270 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
,2015-12-03 17:04:38.274 ThaliTest[1929:3005196] multipeer session: stop timer
,2015-12-03 17:04:38.275 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
,ok 64 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
,running teardown
,# ThaliEmitter calls startBroadcasting twice with error
,CoordinatorConnector-debug: setup:ThaliEmitter calls startBroadcasting twice with error
,# teardown
,--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter calls startBroadcasting twice with error
,2015-12-03 17:04:40.147 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:40.148 ThaliTest[1929:3005196] server: starting 1449158680147.1929.9DpWqg==
,2015-12-03 17:04:40.148 ThaliTest[1929:3005196] multipeer session: start timer: 0x16ff7d00
2015-12-03 17:04:40.149 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158680147.1929
2015-12-03 17:04:40.149 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 65 Should be able to call startBroadcasting without error
2015-12-03 17:04:40.151 ThaliTest[1929:3005196] jxcore: startBroadcasting
2015-12-03 17:04:40.151 ThaliTest[1929:3005196] jxcore: startBroadcasting: failure
ok 66 Cannot call startBroadcasting twice
,2015-12-03 17:04:40.151 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:40.151 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:40.152 ThaliTest[1929:3005196] multipeer session: stop timer
2015-12-03 17:04:40.152 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 67 Should be able to call stopBroadcasting without error
,# setup
,CoordinatorConnector-debug: teardown:ThaliEmitter calls startBroadcasting twice with error
running teardown
,# ThaliEmitter throws on connection to bad peer
,CoordinatorConnector-debug: setup:ThaliEmitter throws on connection to bad peer
,# teardown
--- running teardown
,CoordinatorConnector-debug: start_test:ThaliEmitter throws on connection to bad peer
,2015-12-03 17:04:41.647 ThaliTest[1929:3005196] jxcore: startBroadcasting
,2015-12-03 17:04:41.648 ThaliTest[1929:3005196] server: starting 1449158681647.1929.+LD9aw==
2015-12-03 17:04:41.648 ThaliTest[1929:3005196] multipeer session: start timer: 0x18c00d70
2015-12-03 17:04:41.648 ThaliTest[1929:3005196] THEMultipeerSession initialized peer 1449158681647.1929
,2015-12-03 17:04:41.650 ThaliTest[1929:3005196] jxcore: startBroadcasting: success
,ok 68 Should be able to call startBroadcasting without error
2015-12-03 17:04:41.651 ThaliTest[1929:3005196] jxcore: connect foobar
2015-12-03 17:04:41.651 ThaliTest[1929:3005196] client: unknown peer foobar
2015-12-03 17:04:41.651 ThaliTest[1929:3005196] jxcore: connect: fail: Unknown peer
ok 69 Should not connect to a bad peer
,2015-12-03 17:04:41.653 ThaliTest[1929:3005196] jxcore: stopBroadcasting
2015-12-03 17:04:41.653 ThaliTest[1929:3005196] THEMultipeerSession stopping peer
2015-12-03 17:04:41.653 ThaliTest[1929:3005196] multipeer session: stop timer
2015-12-03 17:04:41.,653 ThaliTest[1929:3005196] jxcore: stopBroadcasting: success
ok 70 Should be able to call stopBroadcasting without error
,# setup

```
