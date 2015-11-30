#### Test 51986340a77003b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/6DEB65E1-2D2D-4843-AF36-E525ECFD231B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/6DEB65E1-2D2D-4843-AF36-E525ECFD231B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340a77003b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/854702E9-68DC-44D2-9E11-FBD28070ACC2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57917"
,(lldb)     command script import "/tmp/6DEB65E1-2D2D-4843-AF36-E525ECFD231B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 10:47:19.944 ThaliTest[983:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 10:47:19.948 ThaliTest[983:60b] Multi-tasking -> Device: YES, App: YES
2015-11-30 10:47:19.954 ThaliTest[983:60b] Unlimited access to network resources
,2015-11-30 10:47:19.962 ThaliTest[983:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 10:47:30.736 ThaliTest[983:60b] Resetting plugins due to page load.
,2015-11-30 10:47:31.596 ThaliTest[983:60b] Finished load of: file:///var/mobile/Applications/854702E9-68DC-44D2-9E11-FBD28070ACC2/ThaliTest.app/www/index.html
,2015-11-30 10:47:31.782 ThaliTest[983:60b] JXcore Cordova plugin initializing
,2015-11-30 10:47:31.784 ThaliTest[983:6807] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT2135
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 55400
,2015-11-30 10:53:35.325 ThaliTest[983:6807] jxcore: startBroadcasting
,2015-11-30 10:53:35.337 ThaliTest[983:6807] server: starting Apple-Iphone5-1_PT2135.SJMPng==
2015-11-30 10:53:35.339 ThaliTest[983:6807] multipeer session: start timer: 0x1c669ab0
2015-11-30 10:53:35.341 ThaliTest[983:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2135
,2015-11-30 10:53:35.342 ThaliTest[983:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-30T09:53:35.348Z SendDataTCPServer.js: TCP/IP server is bound to port: 55400
,2015-11-30 10:53:35.595 ThaliTest[983:60b] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7971.JDbK/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:35.600Z SendDataConnector.js: Start ,called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:53:35.601Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:53:35.601Z SendDataConnector.js: do connect now
,2015-11-30 10:53:35.602 ThaliTest[983:60b] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:53:35.601 ThaliTest[983:6807] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:35.604 ThaliTest[983:6807] client session: connect
,2015-11-30 10:53:35.604 ThaliTest[983:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9746.l6NbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 10:53:36.268 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7551.0H/lSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 10:53:38.352 ThaliTest[983:8403] client session: connected
2015-11-30 10:53:38.353 ThaliTest[983:8403] client session: stateChange:1->2 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:38.358 ThaliTest[983:8403] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:53:38.359 ThaliTest[983:8403] jxcore: connect: success
,2015-11-30T09:53:38.360Z SendDataConnector.js: CLIENT connected to 55403, error: null
2015-11-30T09:53:38.361Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:53:38.362 ThaliTest[983:60b] client: relay established
2015-11-30 10:53:38.363 ThaliTest[983:60b] client: new accepted socket: 0x1c735a80
,2015-11-30T09:53:38.375Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:53:38.894Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30T09:53:38.907Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-30T09:53:38.952Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T09:53:38.965Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-30T09:53:39.110Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 10:53:44.267 ThaliTest[983:60b] multipeer session: reset timer
2015-11-30 10:53:44.269 ThaliTest[983:60b] multipeer session: stop timer
2015-11-30 10:53:44.270 ThaliTest[983:60b] multipeer session: start timer: 0x1c669ab0
,2015-11-30 10:53:44.270 ThaliTest[983:60b] server session: connect
,2015-11-30 10:53:44.271 ThaliTest[983:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:44.275 ThaliTest[983:60b] server: accepting invitation Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:44.387 ThaliTest[983:60b] multipeer session: reset timer
,2015-11-30 10:53:44.389 ThaliTest[983:60b] multipeer session: stop timer
2015-11-30 10:53:44.390 ThaliTest[983:60b] multipeer session: start timer: 0x1c669ab0
,2015-11-30 10:53:44.391 ThaliTest[983:60b] server session: connect
,2015-11-30 10:53:44.391 ThaliTest[983:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7971
,2015-11-30 10:53:44.395 ThaliTest[983:60b] server: accepting invitation Apple-Iphone6-1_PT7971
,2015-11-30 10:53:46.458 ThaliTest[983:790b] server session: connected
2015-11-30 10:53:46.461 ThaliTest[983:790b] server session: stateChange:1->2 Apple-Iphone5s-1_PT9746
,2015-11-30 10:53:46.465 ThaliTest[983:60b] server relay: connected (to port: 55400)
,2015-11-30T09:53:46.469Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 10:53:46.512 ThaliTest[983:760b] server session: connected
2015-11-30 10:53:46.515 ThaliTest[983:760b] server session: stateChange:1->2 Apple-Iphone6-1_PT7971
,2015-11-30 10:53:46.518 ThaliTest[983:60b] server relay: connected (to port: 55400)
,2015-11-30T09:53:46.526Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:53:46.807Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
2015-11-30T09:53:46.808Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-30T09:53:46.820Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-30T09:53:46.822Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-30T09:53:46.838Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2015-11-30T09:53:46.850Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-30T09:53:46.863Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-30T09:53:46.878Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-11-30T09:53:46.936Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-11-30T09:53:46.948Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-30T09:53:46.968Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-11-30T09:53:46.993Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T09:53:46.994Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-11-30T09:53:47.338Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:53:47.365 ThaliTest[983:790b] server session: not connected Apple-Iphone6-1_PT7971
,2015-11-30 10:54:14.392 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:54:14.403 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:54:14.404 ThaliTest[983:60b] client: found peer: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:14.405 ThaliTest[983:60b] client: found peer: Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30T09:54:29.114Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T09:54:29.115Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T09:54:29.117Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T09:54:29.117Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:54:29.118Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 10:54:29.119 ThaliTest[983:60b] client: socket closed
2015-11-30 10:54:29.119 ThaliTest[983:60b] client relay: socket disconnected
,2015-11-30 10:54:29.120 ThaliTest[983:60b] client relay: 0x1c735a80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c6870f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-30 10:54:29.121 ThaliTest[983:60b] client session: socket closed: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:29.122 ThaliTest[983:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:29.122 ThaliTest[983:60b] client session: disconnect
,2015-11-30 10:54:29.123 ThaliTest[983:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:29.124 ThaliTest[983:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:54:34.120Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:54:34.121Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:39.127 ThaliTest[983:6807] jxcore: disconnect
2015-11-30 10:54:39.129 ThaliTest[983:6807] jxcore: disconnect: fail
,2015-11-30T09:54:39.130Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:54:39.131Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
,2015-11-30T09:54:39.131Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:54:39.131Z SendDataConnector.js: do connect now
,2015-11-30 10:54:39.132 ThaliTest[983:6807] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:39.132 ThaliTest[983:6807] client session: connect
,2015-11-30 10:54:39.133 ThaliTest[983:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:39.170 ThaliTest[983:60b] client: lost peer: Apple-Iphone5s-1_PT9746.l6NbbA==
,2015-11-30 10:54:39.172 ThaliTest[983:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9746.l6NbbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9746.l6NbbA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-30 10:54:41.480 ThaliTest[983:980b] client session: connected
2015-11-30 10:54:41.482 ThaliTest[983:980b] client session: stateChange:1->2 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:41.485 ThaliTest[983:aa07] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:54:41.486 ThaliTest[983:aa07] jxcore: connect: success
,2015-11-30T09:54:41.487Z SendDataConnector.js: CLIENT connected to 55410, error: null
2015-11-30T09:54:41.487Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:54:41.489 ThaliTest[983:60b] client: relay established
2015-11-30 10:54:41.489 ThaliTest[983:60b] client: new accepted socket: 0x1c72bdd0
,2015-11-30T09:54:41.500Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 10:54:43.867 ThaliTest[983:7613] server session: not connected Apple-Iphone5s-1_PT9746
,2015-11-30 10:54:44.391 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:55:14.392 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:55:14.403 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:55:17.911 ThaliTest[983:7617] client session: not connected Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:17.912 ThaliTest[983:7617] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:17.915 ThaliTest[983:7617] client session: disconnect
,2015-11-30 10:55:17.915 ThaliTest[983:7617] client session: stateChange:2->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:17.917 ThaliTest[983:7617] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:55:31.559Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T09:55:31.559Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T09:55:31.559Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T09:55:31.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:55:31.560Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30T09:55:36.569Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:55:36.570Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:55:36.570Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:55:41.577 ThaliTest[983:6807] jxcore: disconnect
,2015-11-30 10:55:41.579 ThaliTest[983:6807] jxcore: disconnect: fail
,2015-11-30T09:55:41.580Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:55:41.581Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
2015-11-30T09:55:41.581Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:55:41.581Z SendDataConnector.js: do connect now
,2015-11-30 10:55:41.582 ThaliTest[983:6807] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:41.583 ThaliTest[983:6807] client session: connect
,2015-11-30 10:55:41.583 ThaliTest[983:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:55:41.990 ThaliTest[983:60b] multipeer session: reset timer
,2015-11-30 10:55:41.991 ThaliTest[983:60b] multipeer session: stop timer
,2015-11-30 10:55:41.992 ThaliTest[983:60b] multipeer session: start timer: 0x1c669ab0
,2015-11-30 10:55:41.993 ThaliTest[983:60b] server session: connect
,2015-11-30 10:55:41.994 ThaliTest[983:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7551
,2015-11-30 10:55:41.997 ThaliTest[983:60b] server: accepting invitation Apple-IpadAir2-1_PT7551
,2015-11-30 10:55:44.814 ThaliTest[983:8a0f] server session: connected
2015-11-30 10:55:44.815 ThaliTest[983:8a0f] server session: stateChange:1->2 Apple-IpadAir2-1_PT7551
,2015-11-30 10:55:44.818 ThaliTest[983:60b] server relay: connected (to port: 55400)
,2015-11-30T09:55:44.827Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T09:55:45.130Z SendDataTCPServer.js: TCP/IP server has received 36662 bytes of data
,2015-11-30T09:55:45.145Z SendDataTCPServer.js: TCP/IP server has received 65558 bytes of data
,2015-11-30T09:55:45.158Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-11-30T09:55:45.171Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 10:55:45.184 ThaliTest[983:8813] server session: not connected Apple-IpadAir2-1_PT7551
,2015-11-30 10:56:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:56:12.004 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:56:14.573 ThaliTest[983:ac1b] client session: not connected Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:14.574 ThaliTest[983:ac1b] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:56:14.576 ThaliTest[983:ac1b] client session: disconnect
,2015-11-30 10:56:14.577 ThaliTest[983:ac1b] client session: stateChange:1->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:14.577 ThaliTest[983:ac1b] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:14.578 ThaliTest[983:ac1b] jxcore: connect: fail: Peer disconnected
,2015-11-30T09:56:14.579Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-30T09:56:14.579Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-30T09:56:14.580Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T09:56:14.580Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:56:19.584Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:56:19.584Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:56:19.585Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:56:24.588 ThaliTest[983:6807] jxcore: disconnect
2015-11-30 10:56:24.590 ThaliTest[983:6807] jxcore: disconnect: fail
,2015-11-30T09:56:24.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:56:24.592Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: ,true
2015-11-30T09:56:24.592Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:56:24.592Z SendDataConnector.js: do connect now
,2015-11-30 10:56:24.593 ThaliTest[983:6807] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:24.594 ThaliTest[983:6807] client session: connect
,2015-11-30 10:56:24.594 ThaliTest[983:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:56:42.412 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:56:57.589 ThaliTest[983:ac27] client session: not connected Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:56:57.591 ThaliTest[983:ac27] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:57.592 ThaliTest[983:ac27] client session: disconnect
2015-11-30 10:56:57.593 ThaliTest[983:ac27] client session: stateChange:1->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:57.593 ThaliTest[983:ac27] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:56:57.594 ThaliTest[983:ac27] jxcore: connect: fail: Peer disconnected
,2015-11-30T09:56:57.595Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-30T09:56:57.596Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-30T09:56:57.596Z SendDataConnector.js: CLIENT closeClientSocke,t
2015-11-30T09:56:57.596Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T09:57:02.605Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:57:02.606Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:57:02.606Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:57:07.608 ThaliTest[983:6807] jxcore: disconnect
2015-11-30 10:57:07.609 ThaliTest[983:6807] jxcore: disconnect: fail
2015-11-30T09:57:07.610Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30T09:57:07.610Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7971.JDbK/w== with availability status: true
2015-11-30T09:57:07.610Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30T09:57:07.611Z SendDataConnector.js: do connect now
,2015-11-30 10:57:07.611 ThaliTest[983:6807] jxcore: connect Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:57:07.612 ThaliTest[983:6807] client session: connect
,2015-11-30 10:57:07.612 ThaliTest[983:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:57:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:57:12.225 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:40.614 ThaliTest[983:ac2b] client session: not connected Apple-Iphone6-1_PT7971.JDbK/w==
2015-11-30 10:57:40.616 ThaliTest[983:ac2b] client session: onLinkFailure: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:57:40.617 ThaliTest[983:ac2b] client session: disconnect
2015-11-30 10:57:40.618 ThaliTest[983:ac2b] client session: stateChange:1->0 Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:57:40.618 ThaliTest[983:ac2b] client session: fireConnectCallback: Apple-Iphone6-1_PT7971.JDbK/w==
,2015-11-30 10:57:40.619 ThaliTest[983:ac2b] jxcore: connect: fail: Peer disconnected
,2015-11-30T09:57:40.620Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-30T09:57:40.620Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-30T09:57:40.621Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T09:57:40.622Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:57:40.622Z SendDataConnector.js: Stop data retrieving timer
2015-11-30T09:57:40.623Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30 10:57:40.623 ThaliTest[983:6807] jxcore: disconnect
,2015-11-30 10:57:40.624 ThaliTest[983:6807] jxcore: disconnect: fail
,2015-11-30T09:57:40.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7971.JDbK/w==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30T09:57:40.628Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30T09:57:40.628Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7551.0H/lSg==
2015-11-30T09:57:40.628Z SendDataConnector.js: do connect now
,2015-11-30 10:57:40.628 ThaliTest[983:6807] jxcore: connect Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:40.629 ThaliTest[983:6807] client session: connect
,2015-11-30 10:57:40.630 ThaliTest[983:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:57:44.390 ThaliTest[983:762f] client session: connected
2015-11-30 10:57:44.392 ThaliTest[983:762f] client session: stateChange:1->2 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:44.394 ThaliTest[983:762f] client session: fireConnectCallback: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:44.395 ThaliTest[983:762f] jxcore: connect: success
,2015-11-30T09:57:44.396Z SendDataConnector.js: CLIENT connected to 55424, error: null
,2015-11-30T09:57:44.396Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 10:57:44.398 ThaliTest[983:60b] client: relay established
,2015-11-30 10:57:44.400 ThaliTest[983:60b] client: new accepted socket: 0x1c6b4100
,2015-11-30T09:57:44.410Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T09:57:45.033Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30T09:57:45.049Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T09:57:45.073Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T09:57:45.142Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T09:57:45.142Z SendDataConnector.js: got all data for this round
,2015-11-30T09:57:45.144Z SendDataConnector.js: CLIENT Stop now
2015-11-30T09:57:45.144Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 10:57:45.146 ThaliTest[983:6807] jxcore: disconnect
,2015-11-30 10:57:45.147 ThaliTest[983:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:45.148 ThaliTest[983:6807] client session: disconnect
,2015-11-30 10:57:45.148 ThaliTest[983:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:57:45.151 ThaliTest[983:6807] jxcore: disconnect: success
2015-11-30T09:57:45.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7551.0H/lSg==
---- round done--------
,2015-11-30 10:58:11.993 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:58:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:58:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:59:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 10:59:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 10:59:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:00:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:00:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:00:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:01:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:01:12.002 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:01:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:02:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:02:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:02:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:03:11.993 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:03:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:03:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:04:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:04:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:04:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:04:42.004 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:05:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:05:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:05:42.002 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:06:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:06:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:06:42.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:07:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:07:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:07:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:08:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:08:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:08:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:08:42.004 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:09:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:09:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:09:42.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:10:11.994 ThaliTest[983:60b] multipeer session: restart
,timeout now
,dun
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT2135","time":1000039,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT7971.JDbK/w==","time":245021,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"n,ame":"Apple-IpadAir2-1_PT7551.0H/lSg==","time":4515,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4515 ms, 99% : 4515 ms, 95 : 4515 ms, 90% : 4515 ms.
Result count 1, range 4515 ms to  4515 ms.
,sendList failed peers count : 1 [50 %]
- Peer ID : Apple-Iphone6-1_PT7971.JDbK/w==, Tried : 5
sendList never tried peers count : 0 [0 %]
,2015-11-30T10:10:15.360Z SendDataConnector.js: CLIENT Stop now
,2015-11-30 11:10:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:10:42.004 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:11:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:11:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:11:42.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:12:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:12:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==
,2015-11-30 11:12:41.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:13:11.994 ThaliTest[983:60b] multipeer session: restart
,2015-11-30 11:13:12.003 ThaliTest[983:60b] client: found peer: Apple-IpadAir2-1_PT7551.0H/lSg==

```
