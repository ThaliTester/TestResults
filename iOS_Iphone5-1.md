#### Test 5133502802397d9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/833D90F5-0D8E-403B-AB5F-CEAAB2E5800A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/833D90F5-0D8E-403B-AB5F-CEAAB2E5800A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/56163613-1404-4775-986B-F9974D87E463/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54828"
,(lldb)     command script import "/tmp/833D90F5-0D8E-403B-AB5F-CEAAB2E5800A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 17:04:33.289 ThaliTest[728:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-24 17:04:33.293 ThaliTest[728:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-24 17:04:33.299 ThaliTest[728:60b] Unlimited access to network resources
,2015-11-24 17:04:33.307 ThaliTest[728:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 17:04:44.043 ThaliTest[728:60b] Resetting plugins due to page load.
,2015-11-24 17:04:44.913 ThaliTest[728:60b] Finished load of: file:///var/mobile/Applications/56163613-1404-4775-986B-F9974D87E463/ThaliTest.app/www/index.html
,2015-11-24 17:04:45.092 ThaliTest[728:60b] JXcore Cordova plugin initializing
,2015-11-24 17:04:45.094 ThaliTest[728:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5-1_PT7498
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 62698
,2015-11-24 17:10:24.801 ThaliTest[728:6707] jxcore: startBroadcasting
,2015-11-24 17:10:24.812 ThaliTest[728:6707] server: starting Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:24.826 ThaliTest[728:6707] multipeer session: start timer: 0x1ae6de40
,2015-11-24 17:10:24.828 ThaliTest[728:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT7498
,2015-11-24 17:10:24.829 ThaliTest[728:6707] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-24T16:10:24.831Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-24 17:10:25.213 ThaliTest[728:60b] client: found peer: Apple-Iphone5s-1_PT8445.HcGyQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8445.HcGyQA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:25.217Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24T16:10:25.218Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24T16:10:25.218Z SendDataConnector.js: do connect now
,2015-11-24 17:10:25.219 ThaliTest[728:6707] jxcore: connect Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24 17:10:25.220 ThaliTest[728:6707] client session: connect
2015-11-24 17:10:25.221 ThaliTest[728:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:25.491 ThaliTest[728:60b] client: found peer: Apple-Iphone6-1_PT1630.4rgQcA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1630.4rgQcA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:26.002 ThaliTest[728:60b] client: found peer: Apple-IpadAir2-1_PT7208.gEcfnw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7208.gEcfnw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:27.665 ThaliTest[728:21b] client session: connected
2015-11-24 17:10:27.666 ThaliTest[728:21b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:27.679 ThaliTest[728:7523] client session: fireConnectCallback: Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:27.680 ThaliTest[728:7523] jxcore: connect: success
,2015-11-24T16:10:27.682Z SendDataConnector.js: CLIENT connected to 62701, error: null
,2015-11-24T16:10:27.682Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:27.683 ThaliTest[728:60b] client: relay established
,2015-11-24 17:10:27.684 ThaliTest[728:60b] client: new accepted socket: 0x1ae778c0
,2015-11-24T16:10:27.695Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:28.163Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-24T16:10:28.176Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-24T16:10:28.189Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-24T16:10:28.202Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-24T16:10:28.237Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-24T16:10:28.237Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:28.240Z SendDataConnector.js: CLIENT Stop now
,2015-11-24T16:10:28.240Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:28.242 ThaliTest[728:6707] jxcore: disconnect
,2015-11-24 17:10:28.243 ThaliTest[728:6707] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:28.243 ThaliTest[728:6707] client session: disconnect
,2015-11-24 17:10:28.244 ThaliTest[728:6707] client session: stateChange:2->0 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:28.425 ThaliTest[728:6707] jxcore: disconnect: success
,2015-11-24T16:10:28.426Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8445.HcGyQA==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:28.428Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:28.428Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:28.428Z SendDataConnector.js: do connect now
,2015-11-24 17:10:28.429 ThaliTest[728:6707] jxcore: connect Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:28.430 ThaliTest[728:6707] client session: connect
,2015-11-24 17:10:28.431 ThaliTest[728:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:30.776 ThaliTest[728:7523] client session: connected
2015-11-24 17:10:30.777 ThaliTest[728:7523] client session: stateChange:1->2 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:30.781 ThaliTest[728:7523] client session: fireConnectCallback: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:30.782 ThaliTest[728:7523] jxcore: connect: success
,2015-11-24T16:10:30.783Z SendDataConnector.js: CLIENT connected to 62705, error: null
2015-11-24T16:10:30.783Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:30.784 ThaliTest[728:60b] client: relay established
2015-11-24 17:10:30.785 ThaliTest[728:60b] client: new accepted socket: 0x1ae78940
,2015-11-24T16:10:30.796Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:31.309Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-24T16:10:31.323Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-24T16:10:31.336Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-24T16:10:31.349Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-24T16:10:31.362Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-24T16:10:31.363Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:31.365Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:31.365Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:31.366 ThaliTest[728:6707] jxcore: disconnect
,2015-11-24 17:10:31.367 ThaliTest[728:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:31.368 ThaliTest[728:6707] client session: disconnect
,2015-11-24 17:10:31.368 ThaliTest[728:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:31.371 ThaliTest[728:6707] jxcore: disconnect: success
,2015-11-24T16:10:31.373Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1630.4rgQcA==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24T16:10:31.375Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:31.375Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24T16:10:31.375Z SendDataConnector.js: do connect now
,2015-11-24 17:10:31.376 ThaliTest[728:6707] jxcore: connect Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:31.376 ThaliTest[728:6707] client session: connect
,2015-11-24 17:10:31.377 ThaliTest[728:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:33.025 ThaliTest[728:60b] multipeer session: reset timer
2015-11-24 17:10:33.026 ThaliTest[728:60b] multipeer session: stop timer
,2015-11-24 17:10:33.027 ThaliTest[728:60b] multipeer session: start timer: 0x1ae6de40
,2015-11-24 17:10:33.028 ThaliTest[728:60b] server session: connect
,2015-11-24 17:10:33.028 ThaliTest[728:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:33.032 ThaliTest[728:60b] server: accepting invitation Apple-Iphone6-1_PT1630
,2015-11-24 17:10:33.968 ThaliTest[728:60b] multipeer session: reset timer
,2015-11-24 17:10:33.970 ThaliTest[728:60b] multipeer session: stop timer
2015-11-24 17:10:33.971 ThaliTest[728:60b] multipeer session: start timer: 0x1ae6de40
,2015-11-24 17:10:33.972 ThaliTest[728:60b] server session: connect
,2015-11-24 17:10:33.972 ThaliTest[728:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:33.976 ThaliTest[728:60b] server: accepting invitation Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:35.131 ThaliTest[728:7523] server session: connected
2015-11-24 17:10:35.134 ThaliTest[728:7523] server session: stateChange:1->2 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:35.137 ThaliTest[728:60b] server relay: connected (to port: 62698)
,2015-11-24T16:10:35.145Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24 17:10:35.221 ThaliTest[728:60b] multipeer session: reset timer
,2015-11-24 17:10:35.222 ThaliTest[728:60b] multipeer session: stop timer
2015-11-24 17:10:35.224 ThaliTest[728:60b] multipeer session: start timer: 0x1ae6de40
,2015-11-24 17:10:35.224 ThaliTest[728:60b] server session: connect
,2015-11-24 17:10:35.225 ThaliTest[728:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:35.228 ThaliTest[728:60b] server: accepting invitation Apple-IpadAir2-1_PT7208
,2015-11-24T16:10:35.247Z SendDataTCPServer.js: TCP/IP server has received 10666 bytes of data
,2015-11-24T16:10:35.260Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-24T16:10:35.536Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-24T16:10:35.548Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-24T16:10:35.561Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-24T16:10:35.574Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-24T16:10:35.586Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-11-24T16:10:35.691Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-24T16:10:35.703Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:36.278 ThaliTest[728:8003] server session: connected
,2015-11-24 17:10:36.279 ThaliTest[728:8003] server session: stateChange:1->2 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:36.559 ThaliTest[728:7523] server session: not connected Apple-Iphone6-1_PT1630
,2015-11-24 17:10:36.562 ThaliTest[728:60b] server relay: connected (to port: 62698)
,2015-11-24T16:10:36.571Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:36.584Z SendDataTCPServer.js: TCP/IP server has received 28186 bytes of data
,2015-11-24T16:10:36.599Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-24T16:10:36.611Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:36.631 ThaliTest[728:8003] server session: not connected Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:38.894 ThaliTest[728:7b07] client session: connected
,2015-11-24 17:10:38.895 ThaliTest[728:7b07] client session: stateChange:1->2 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:38.906 ThaliTest[728:8003] client session: fireConnectCallback: Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:38.907 ThaliTest[728:8003] jxcore: connect: success
,2015-11-24T16:10:38.908Z SendDataConnector.js: CLIENT connected to 62710, error: null
2015-11-24T16:10:38.908Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:38.910 ThaliTest[728:60b] client: relay established
,2015-11-24 17:10:38.911 ThaliTest[728:60b] client: new accepted socket: 0x1af2f2c0
2015-11-24 17:10:38.911 ThaliTest[728:8003] server session: connected
,2015-11-24 17:10:38.913 ThaliTest[728:8003] server session: stateChange:1->2 Apple-IpadAir2-1_PT7208
,2015-11-24T16:10:38.921Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:39.501Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-24T16:10:39.558Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-24T16:10:39.582Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-24T16:10:39.606Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-24 17:10:39.939 ThaliTest[728:60b] server relay: connected (to port: 62698)
,2015-11-24T16:10:39.950Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:40.150Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-24T16:10:40.185Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-24T16:10:40.486Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-24T16:10:40.510Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-24T16:10:40.511Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:40.512Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:40.513Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:40.514 ThaliTest[728:6707] jxcore: disconnect
,2015-11-24 17:10:40.514 ThaliTest[728:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:40.515 ThaliTest[728:6707] client session: disconnect
,2015-11-24 17:10:40.516 ThaliTest[728:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:40.518 ThaliTest[728:6707] jxcore: disconnect: success
2015-11-24T16:10:40.519Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7208.gEcfnw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT7498","time":15728,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8445.HcGyQA==","time":3022,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT1630.4rgQcA==","time":2935,"result":"OK","connections":,1},{"name":"Apple-IpadAir2-1_PT7208.gEcfnw==","time":9136,"result":"OK","connections":1}]}
sendList : 100% : 9136 ms, 99% : 9136 ms, 95 : 9136 ms, 90% : 9136 ms.
Result count 3, range 2935 ms to  9136 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-24T16:10:40.528Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:40.528Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24T16:10:40.564Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-24T16:10:40.604Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-24T16:10:40.616Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:41.035 ThaliTest[728:9427] server session: not connected Apple-IpadAir2-1_PT7208
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-24 17:10:41.446 ThaliTest[728:6707] jxcore: stopBroadcasting
,2015-11-24 17:10:41.447 ThaliTest[728:6707] THEMultipeerSession stopping peer
,2015-11-24 17:10:41.448 ThaliTest[728:6707] multipeer session: stop timer
,2015-11-24 17:10:41.448 ThaliTest[728:6707] server session: disconnect
2015-11-24 17:10:41.450 ThaliTest[728:6707] server session: stateChange:2->0 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:41.455 ThaliTest[728:6707] server session: disconnect
,2015-11-24 17:10:41.455 ThaliTest[728:6707] server session: stateChange:2->0 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:41.461 ThaliTest[728:6707] server session: disconnect
,2015-11-24 17:10:41.464 ThaliTest[728:6707] server session: stateChange:2->0 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:41.470 ThaliTest[728:6707] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-24T16:10:41.489Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-24T16:10:41.490Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:41.490Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:41.490Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2935,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":3022,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":9136,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQ,cA==\",\"time\":2721,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":2803,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":2871,\"result\":\"OK\",\"connections\":1},{\",name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2935,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":3022,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":3397,\"re,sult\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":3428,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":4431,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1,_PT8445.HcGyQA==\",\"time\":5210,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":5907,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":7047,\"result\":\"OK\",\"connecti,ons\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":9136,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coo
```
