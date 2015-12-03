#### Test 525393149f38b37_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/B5FD484D-9234-4D6C-BEF7-815C1CA2022C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B5FD484D-9234-4D6C-BEF7-815C1CA2022C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app' (armv7).
,(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/510833F0-2819-4283-9A8B-A80B4BF09C50/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60632"
,(lldb)     command script import "/tmp/B5FD484D-9234-4D6C-BEF7-815C1CA2022C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 16:21:18.883 ThaliTest[1224:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 16:21:18.886 ThaliTest[1224:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 16:21:18.893 ThaliTest[1224:60b] Unlimited access to network resources
,2015-12-03 16:21:18.900 ThaliTest[1224:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 16:21:29.645 ThaliTest[1224:60b] Resetting plugins due to page load.
,2015-12-03 16:21:30.518 ThaliTest[1224:60b] Finished load of: file:///var/mobile/Applications/510833F0-2819-4283-9A8B-A80B4BF09C50/ThaliTest.app/www/index.html
,2015-12-03 16:21:30.698 ThaliTest[1224:60b] JXcore Cordova plugin initializing
,2015-12-03 16:21:30.701 ThaliTest[1224:6807] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5-1_PT9874
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63457
,2015-12-03 16:26:44.933 ThaliTest[1224:6807] jxcore: startBroadcasting
,2015-12-03 16:26:44.944 ThaliTest[1224:6807] server: starting Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:44.948 ThaliTest[1224:6807] multipeer session: start timer: 0x1c6d5660
,2015-12-03 16:26:44.955 ThaliTest[1224:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9874
,2015-12-03 16:26:44.956 ThaliTest[1224:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03T15:26:44.959Z SendDataTCPServer.js: TCP/IP server is bound to port: 63457
,2015-12-03 16:26:45.223 ThaliTest[1224:60b] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03T15:26:45.227Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03T15:26:45.227Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03T15:26:45.228Z SendDataConnector.js: do connect now
,2015-12-03 16:26:45.228 ThaliTest[1224:6807] jxcore: connect Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:45.229 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:26:45.229 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:45.935 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2877.NAxVhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:47.459 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:47.835 ThaliTest[1224:8103] client session: connected
2015-12-03 16:26:47.837 ThaliTest[1224:8103] client session: stateChange:1->2 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:47.841 ThaliTest[1224:8103] client session: fireConnectCallback: Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:47.842 ThaliTest[1224:8103] jxcore: connect: success
,2015-12-03T15:26:47.843Z SendDataConnector.js: CLIENT connected to 63460, error: null
,2015-12-03T15:26:47.844Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:47.845 ThaliTest[1224:60b] client: relay established
2015-12-03 16:26:47.846 ThaliTest[1224:60b] client: new accepted socket: 0x1c6dd0a0
,2015-12-03T15:26:47.859Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:26:48.768Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T15:26:48.793Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:26:49.291Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T15:26:49.304Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T15:26:49.318Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T15:26:49.318Z SendDataConnector.js: got all data for this round
,2015-12-03T15:26:49.321Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:26:49.321Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:26:49.322 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:26:49.323 ThaliTest[1224:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:49.324 ThaliTest[1224:6807] client session: disconnect
,2015-12-03 16:26:49.324 ThaliTest[1224:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:49.327 ThaliTest[1224:6807] jxcore: disconnect: success
,2015-12-03T15:26:49.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8182.c6Lgog==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:26:49.333Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:26:49.333Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:26:49.333Z SendDataConnector.js: do connect now
,2015-12-03 16:26:49.334 ThaliTest[1224:6807] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:49.335 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:26:49.335 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:50.670 ThaliTest[1224:60b] multipeer session: reset timer
2015-12-03 16:26:50.672 ThaliTest[1224:60b] multipeer session: stop timer
,2015-12-03 16:26:50.672 ThaliTest[1224:60b] multipeer session: start timer: 0x1c6d5660
,2015-12-03 16:26:50.673 ThaliTest[1224:60b] server session: connect
,2015-12-03 16:26:50.674 ThaliTest[1224:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:50.678 ThaliTest[1224:60b] server: accepting invitation Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:52.316 ThaliTest[1224:8103] client session: connected
,2015-12-03 16:26:52.317 ThaliTest[1224:8103] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:52.351 ThaliTest[1224:8403] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:26:52.351 ThaliTest[1224:8403] jxcore: connect: success
,2015-12-03T15:26:52.353Z SendDataConnector.js: CLIENT connected to 63463, error: null
2015-12-03T15:26:52.353Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:52.354 ThaliTest[1224:60b] client: relay established
,2015-12-03 16:26:52.356 ThaliTest[1224:60b] client: new accepted socket: 0x1c6ee160
,2015-12-03T15:26:52.366Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03 16:26:52.795 ThaliTest[1224:60b] multipeer session: reset timer
2015-12-03 16:26:52.795 ThaliTest[1224:60b] multipeer session: stop timer
2015-12-03 16:26:52.796 ThaliTest[1224:60b] multipeer session: start timer: 0x1c6d5660
2015-12-03 16:26:52.796 ThaliTest[1224:60b] server session: connect
2015-12-03 16:26:52.797 ThaliTest[1224:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:52.803 ThaliTest[1224:60b] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03T15:26:53.006Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T15:26:53.018Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:26:53.277Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T15:26:53.312Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 16:26:53.345 ThaliTest[1224:7423] server session: connected
2015-12-03 16:26:53.346 ThaliTest[1224:7423] server session: stateChange:1->2 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:53.351 ThaliTest[1224:60b] server relay: connected (to port: 63457)
,2015-12-03T15:26:53.359Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:53.802Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-03T15:26:53.816Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-03T15:26:53.829Z SendDataTCPServer.js: TCP/IP server has received 67606 bytes of data
,2015-12-03T15:26:53.843Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:53.866 ThaliTest[1224:7423] server session: not connected Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:55.437 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:55.441 ThaliTest[1224:7423] server session: connected
,2015-12-03 16:26:55.441 ThaliTest[1224:7423] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:55.496 ThaliTest[1224:60b] server relay: connected (to port: 63457)
,2015-12-03T15:26:55.506Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:55.905Z SendDataTCPServer.js: TCP/IP server has received 25854 bytes of data
,2015-12-03T15:26:55.918Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-03T15:26:55.931Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:56.050 ThaliTest[1224:8103] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03T15:27:03.315Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:03.315Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:03.316Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:03.317Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:03.318Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:03.319 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:27:03.320 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:27:03.320 ThaliTest[1224:60b] client relay: 0x1c6ee160 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c6f3f40 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:27:03.321 ThaliTest[1224:60b] client session: socket closed: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:03.322 ThaliTest[1224:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:03.322 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:27:03.323 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:03.324 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:08.327Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:08.328Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:13.336 ThaliTest[1224:6807] jxcore: disconnect
2015-12-03 16:27:13.337 ThaliTest[1224:6807] jxcore: disconnect: fail
,2015-12-03T15:27:13.339Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:27:13.339Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2877.NAxVhQ== with availability status,: true
2015-12-03T15:27:13.340Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:27:13.340Z SendDataConnector.js: do connect now
,2015-12-03 16:27:13.340 ThaliTest[1224:6807] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:13.341 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:27:13.342 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:16.342 ThaliTest[1224:7423] client session: connected
2015-12-03 16:27:16.344 ThaliTest[1224:7423] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:16.363 ThaliTest[1224:7423] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:16.364 ThaliTest[1224:7423] jxcore: connect: success
,2015-12-03T15:27:16.365Z SendDataConnector.js: CLIENT connected to 63468, error: null
,2015-12-03T15:27:16.365Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:16.367 ThaliTest[1224:60b] client: relay established
,2015-12-03 16:27:16.368 ThaliTest[1224:60b] client: new accepted socket: 0x1c542790
,2015-12-03T15:27:16.378Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:27:22.798 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03T15:27:26.510Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:26.510Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:27:26.511Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:26.511Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T15:27:26.512Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:26.513 ThaliTest[1224:60b] client: socket closed
,2015-12-03 16:27:26.514 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:27:26.515 ThaliTest[1224:60b] client relay: 0x1c542790 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x165badb0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:27:26.515 ThaliTest[1224:60b] client session: socket closed: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:27:26.516 ThaliTest[1224:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:26.517 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:27:26.517 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:26.519 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:31.518Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:31.519Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:36.526 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:27:36.527 ThaliTest[1224:6807] jxcore: disconnect: fail
2015-12-03T15:27:36.529Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:27:36.529Z SendDataConnector.js: Connect (retry cou,nt 2) to peer Apple-IpadAir2-1_PT2877.NAxVhQ== with availability status: true
2015-12-03T15:27:36.529Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:27:36.530Z SendDataConnector.js: do connect now
,2015-12-03 16:27:36.530 ThaliTest[1224:6807] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:36.531 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:27:36.531 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:39.405 ThaliTest[1224:8713] client session: connected
2015-12-03 16:27:39.407 ThaliTest[1224:8713] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:39.426 ThaliTest[1224:8713] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:39.427 ThaliTest[1224:8713] jxcore: connect: success
,2015-12-03T15:27:39.428Z SendDataConnector.js: CLIENT connected to 63473, error: null
,2015-12-03T15:27:39.428Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:39.430 ThaliTest[1224:60b] client: relay established
,2015-12-03 16:27:39.430 ThaliTest[1224:60b] client: new accepted socket: 0x1c5468c0
,2015-12-03T15:27:39.441Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:27:49.513Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:49.513Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:27:49.514Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:49.514Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T15:27:49.515Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:49.516 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:27:49.517 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:27:49.518 ThaliTest[1224:60b] client relay: 0x1c5468c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x165c29a0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:27:49.519 ThaliTest[1224:60b] client session: socket closed: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:27:49.519 ThaliTest[1224:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:49.520 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:27:49.520 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:49.522 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:52.797 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:27:52.993 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:52.996 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:52.996 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:27:53.554 ThaliTest[1224:60b] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03T15:27:54.516Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:54.517Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:59.518 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:27:59.519 ThaliTest[1224:6807] jxcore: disconnect: fail
2015-12-03T15:27:59.521Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:59.522Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2877.NAxVhQ== with availability status: true
2015-12-03T15:27:59.522Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:27:59.522Z SendDataConnector.js: do connect now
,2015-12-03 16:27:59.523 ThaliTest[1224:6807] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:59.523 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:27:59.524 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:02.573 ThaliTest[1224:8713] client session: connected
2015-12-03 16:28:02.574 ThaliTest[1224:8713] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:02.589 ThaliTest[1224:8713] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:02.590 ThaliTest[1224:8713] jxcore: connect: success
,2015-12-03T15:28:02.591Z SendDataConnector.js: CLIENT connected to 63477, error: null
,2015-12-03T15:28:02.592Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:28:02.593 ThaliTest[1224:60b] client: relay established
2015-12-03 16:28:02.594 ThaliTest[1224:60b] client: new accepted socket: 0x1c554410
,2015-12-03T15:28:02.606Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:28:12.663Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:28:12.663Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:12.664Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:28:12.664Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:28:12.665Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:28:12.666 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:28:12.667 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:28:12.668 ThaliTest[1224:60b] client relay: 0x1c554410 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c6dee10 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:28:12.668 ThaliTest[1224:60b] client session: socket closed: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:28:12.669 ThaliTest[1224:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:12.670 ThaliTest[1224:60b] client session: disconnect
2015-12-03 16:28:12.670 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:12.671 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:28:17.670Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:28:17.670Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:22.677 ThaliTest[1224:6807] jxcore: disconnect
2015-12-03 16:28:22.678 ThaliTest[1224:6807] jxcore: disconnect: fail
2015-12-03T15:28:22.680Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:28:22.680Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2877.NAxVhQ== with availability status: true
2015-12-03T15:28:22.681Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015,-12-03T15:28:22.681Z SendDataConnector.js: do connect now
,2015-12-03 16:28:22.681 ThaliTest[1224:6807] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:28:22.682 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:28:22.682 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:22.797 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:28:22.807 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:22.809 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:22.809 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:22.810 ThaliTest[1224:60b] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:28:25.696 ThaliTest[1224:8413] client session: connected
,2015-12-03 16:28:25.697 ThaliTest[1224:8413] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:25.705 ThaliTest[1224:8413] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:28:25.706 ThaliTest[1224:8413] jxcore: connect: success
,2015-12-03T15:28:25.708Z SendDataConnector.js: CLIENT connected to 63481, error: null
2015-12-03T15:28:25.708Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:28:25.710 ThaliTest[1224:60b] client: relay established
2015-12-03 16:28:25.710 ThaliTest[1224:60b] client: new accepted socket: 0x1c6fbfd0
,2015-12-03T15:28:25.722Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:28:35.779Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:28:35.779Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:35.780Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:35.783Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:28:35.783Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T15:28:35.783Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:28:35.784 ThaliTest[1224:6807] jxcore: disconnect
2015-12-03 16:28:35.785 ThaliTest[1224:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:28:35.786 ThaliTest[1224:6807] client session: disconnect
,2015-12-03 16:28:35.786 ThaliTest[1224:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:35.788 ThaliTest[1224:6807] jxcore: disconnect: success
2015-12-03T15:28:35.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
---- round done--------
device[3]: Apple-Iphone6-1_PT4561.tcw,UUA==
2015-12-03T15:28:35.790Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:35.791Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:35.791Z SendDataConnec,tor.js: do connect now
,2015-12-03 16:28:35.793 ThaliTest[1224:6807] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:35.793 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:28:35.794 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:28:35.799Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:28:38.953 ThaliTest[1224:ae27] client session: connected
2015-12-03 16:28:38.954 ThaliTest[1224:ae27] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:38.956 ThaliTest[1224:ae27] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:38.957 ThaliTest[1224:ae27] jxcore: connect: success
,2015-12-03T15:28:38.960Z SendDataConnector.js: CLIENT connected to 63485, error: null
,2015-12-03T15:28:38.960Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:28:38.962 ThaliTest[1224:60b] client: relay established
,2015-12-03 16:28:38.963 ThaliTest[1224:60b] client: new accepted socket: 0x165b97b0
,2015-12-03T15:28:38.973Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:28:39.464Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T15:28:39.499Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:28:39.526Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T15:28:39.539Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 16:28:46.313 ThaliTest[1224:60b] client: lost peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:28:46.315 ThaliTest[1224:60b] client session: onPeerLost: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":false}]
,2015-12-03T15:28:49.539Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:28:49.539Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:49.540Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:49.541Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:28:49.541Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:28:49.543 ThaliTest[1224:60b] client: socket closed
,2015-12-03 16:28:49.544 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:28:49.544 ThaliTest[1224:60b] client relay: 0x165b97b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c59ead0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:28:49.545 ThaliTest[1224:60b] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:49.545 ThaliTest[1224:60b] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:49.546 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:28:49.547 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:49.548 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:52.797 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:28:52.809 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:52.810 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:28:52.811 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:28:54.552Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:28:54.552Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:59.554 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:28:59.556 ThaliTest[1224:6807] jxcore: disconnect: fail
2015-12-03T15:28:59.557Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:59.558Z SendDataConnector.js: Connect (retry coun,t 1) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
2015-12-03T15:28:59.558Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:59.558Z SendDataConnector.js: do connect now
,2015-12-03 16:28:59.559 ThaliTest[1224:6807] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:59.560 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:28:59.560 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:02.922 ThaliTest[1224:ae2b] client session: connected
2015-12-03 16:29:02.924 ThaliTest[1224:ae2b] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:02.926 ThaliTest[1224:ae2b] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:02.927 ThaliTest[1224:ae2b] jxcore: connect: success
,2015-12-03T15:29:02.929Z SendDataConnector.js: CLIENT connected to 63491, error: null
2015-12-03T15:29:02.929Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:29:02.930 ThaliTest[1224:60b] client: relay established
2015-12-03 16:29:02.931 ThaliTest[1224:60b] client: new accepted socket: 0x1c69ba70
,2015-12-03T15:29:02.942Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:29:12.999Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:29:12.999Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:29:13.000Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:29:13.000Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T15:29:13.001Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:29:13.003 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:29:13.003 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:29:13.004 ThaliTest[1224:60b] client relay: 0x1c69ba70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c6d3880 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:29:13.005 ThaliTest[1224:60b] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:13.005 ThaliTest[1224:60b] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:13.006 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:29:13.006 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:13.008 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:29:18.008Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:29:18.009Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:22.798 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:29:22.808 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:22.809 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:29:22.810 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:29:23.018 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:29:23.019 ThaliTest[1224:6807] jxcore: disconnect: fail
,2015-12-03T15:29:23.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:29:23.021Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
,2015-12-03T15:29:23.022Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:29:23.022Z SendDataConnector.js: do connect now
,2015-12-03 16:29:23.022 ThaliTest[1224:6807] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:23.023 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:29:23.024 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:25.817 ThaliTest[1224:ae2b] client session: connected
2015-12-03 16:29:25.818 ThaliTest[1224:ae2b] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:25.821 ThaliTest[1224:ae2b] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:25.822 ThaliTest[1224:ae2b] jxcore: connect: success
,2015-12-03T15:29:25.823Z SendDataConnector.js: CLIENT connected to 63496, error: null
2015-12-03T15:29:25.824Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:29:25.826 ThaliTest[1224:60b] client: relay established
,2015-12-03 16:29:25.828 ThaliTest[1224:60b] client: new accepted socket: 0x165346b0
,2015-12-03T15:29:25.837Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:29:35.892Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:29:35.893Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:29:35.894Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:29:35.895Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:29:35.896Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:29:35.897 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:29:35.898 ThaliTest[1224:60b] client relay: socket disconnected
2015-12-03 16:29:35.898 ThaliTest[1224:60b] client relay: 0x165346b0 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c54f5c0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:29:35.899 ThaliTest[1224:60b] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:35.900 ThaliTest[1224:60b] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:35.900 ThaliTest[1224:60b] client session: disconnect
2015-12-03 16:29:35.901 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:35.903 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:29:40.904Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:29:40.905Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:45.909 ThaliTest[1224:6807] jxcore: disconnect
2015-12-03 16:29:45.911 ThaliTest[1224:6807] jxcore: disconnect: fail
,2015-12-03T15:29:45.912Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:29:45.913Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: ,true
2015-12-03T15:29:45.913Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:29:45.913Z SendDataConnector.js: do connect now
,2015-12-03 16:29:45.913 ThaliTest[1224:6807] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:45.914 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:29:45.915 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:48.476 ThaliTest[1224:b413] client session: connected
2015-12-03 16:29:48.478 ThaliTest[1224:b413] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:48.479 ThaliTest[1224:b413] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:48.480 ThaliTest[1224:b413] jxcore: connect: success
2015-12-03T15:29:48.481Z SendDataConnector.js: CLIENT connected to 63501, error: null
,2015-12-03T15:29:48.482Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:29:48.484 ThaliTest[1224:60b] client: relay established
2015-12-03 16:29:48.484 ThaliTest[1224:60b] client: new accepted socket: 0x1c2a7de0
,2015-12-03T15:29:48.495Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:29:52.797 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03T15:29:58.552Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:29:58.553Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:29:58.554Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:29:58.554Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T15:29:58.555Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:29:58.556 ThaliTest[1224:60b] client: socket closed
2015-12-03 16:29:58.557 ThaliTest[1224:60b] client relay: socket disconnected
,2015-12-03 16:29:58.558 ThaliTest[1224:60b] client relay: 0x1c2a7de0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1c6fb860 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 16:29:58.558 ThaliTest[1224:60b] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:58.559 ThaliTest[1224:60b] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:58.560 ThaliTest[1224:60b] client session: disconnect
,2015-12-03 16:29:58.560 ThaliTest[1224:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:29:58.562 ThaliTest[1224:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:30:03.564Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:30:03.564Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:30:08.571 ThaliTest[1224:6807] jxcore: disconnect
2015-12-03 16:30:08.572 ThaliTest[1224:6807] jxcore: disconnect: fail
,2015-12-03T15:30:08.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:30:08.574Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: ,true
2015-12-03T15:30:08.574Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:30:08.574Z SendDataConnector.js: do connect now
,2015-12-03 16:30:08.575 ThaliTest[1224:6807] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:30:08.576 ThaliTest[1224:6807] client session: connect
,2015-12-03 16:30:08.576 ThaliTest[1224:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:30:11.017 ThaliTest[1224:60b] multipeer session: reset timer
,2015-12-03 16:30:11.019 ThaliTest[1224:60b] multipeer session: stop timer
,2015-12-03 16:30:11.019 ThaliTest[1224:60b] multipeer session: start timer: 0x1c6d5660
,2015-12-03 16:30:11.020 ThaliTest[1224:60b] server session: connect
,2015-12-03 16:30:11.021 ThaliTest[1224:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT4561
,2015-12-03 16:30:11.024 ThaliTest[1224:60b] server: accepting invitation Apple-Iphone6-1_PT4561
,2015-12-03 16:30:11.039 ThaliTest[1224:8973] client session: connected
,2015-12-03 16:30:11.040 ThaliTest[1224:8973] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:30:11.047 ThaliTest[1224:8973] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:30:11.048 ThaliTest[1224:8973] jxcore: connect: success
,2015-12-03T15:30:11.050Z SendDataConnector.js: CLIENT connected to 63506, error: null
2015-12-03T15:30:11.050Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:30:11.052 ThaliTest[1224:60b] client: relay established
2015-12-03 16:30:11.053 ThaliTest[1224:60b] client: new accepted socket: 0x1c423130
,2015-12-03T15:30:11.064Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:30:13.134 ThaliTest[1224:7f2b] server session: connected
,2015-12-03 16:30:13.136 ThaliTest[1224:7f2b] server session: stateChange:1->2 Apple-Iphone6-1_PT4561
,2015-12-03 16:30:13.140 ThaliTest[1224:60b] server relay: connected (to port: 63457)
,2015-12-03T15:30:13.149Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:30:13.504Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T15:30:13.517Z SendDataTCPServer.js: TCP/IP server has received 30518 bytes of data
,2015-12-03T15:30:13.532Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-03T15:30:13.544Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-03T15:30:13.557Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T15:30:21.126Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:30:21.127Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:30:21.127Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:30:21.129Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:30:21.129Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T15:30:21.129Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:30:21.130 ThaliTest[1224:6807] jxcore: disconnect
,2015-12-03 16:30:21.131 ThaliTest[1224:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:30:21.131 ThaliTest[1224:6807] client session: disconnect
,2015-12-03 16:30:21.132 ThaliTest[1224:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:30:21.134 ThaliTest[1224:6807] jxcore: disconnect: success
2015-12-03T15:30:21.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9874","time":216217,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8182.c6Lgog==","time":4092,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT2877.NAxVhQ==","time":106448,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone6-1_PT4561.tcwUUA==","time":105337,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":10,0000,"dataReceived":90000}]}
sendList : 100% : 4092 ms, 99% : 4092 ms, 95 : 4092 ms, 90% : 4092 ms.
Result count 1, range 4092 ms to  4092 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-IpadAir2-1_PT2877.NAxVhQ==, Tried : 5,
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T15:30:21.142Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:30:21.142Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:30:,21.143Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:30:24.048 ThaliTest[1224:7f2b] server session: not connected Apple-Iphone6-1_PT4561
,2015-12-03 16:30:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:30:41.032 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:30:41.033 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:30:41.033 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:30:47.896 ThaliTest[1224:60b] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:30:47.898 ThaliTest[1224:60b] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 16:30:50.195 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:31:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:31:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:31:41.529 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:31:41.530 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:31:41.531 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:32:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:32:11.032 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:32:11.398 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:32:11.399 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:32:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:33:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:33:11.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:33:11.032 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:33:11.034 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:28.269 ThaliTest[1224:60b] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:33:28.270 ThaliTest[1224:60b] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 16:33:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:33:41.736 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:33:41.745 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:33:41.772 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:34:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:34:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:34:41.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:34:41.033 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:34:42.402 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:35:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:35:11.032 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:35:11.034 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:35:11.035 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:35:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:35:41.032 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:35:41.034 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:35:41.035 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:36:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:36:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:36:41.032 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:36:41.034 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:36:41.035 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:36:47.774 ThaliTest[1224:60b] client: lost peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:36:47.776 ThaliTest[1224:60b] client session: onPeerLost: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 16:36:52.921 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 16:37:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:37:11.878 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:37:11.880 ThaliTest[1224:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:37:31.872 ThaliTest[1224:60b] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:37:31.873 ThaliTest[1224:60b] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 16:37:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:38:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:38:11.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:38:41.020 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:39:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:39:11.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:39:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:39:41.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:40:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:40:11.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:40:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:41:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:41:11.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:41:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:42:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:42:11.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:42:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:42:41.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:43:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:43:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:43:41.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:44:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:44:11.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:44:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:45:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:45:11.031 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:45:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:46:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:46:11.029 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:46:41.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:46:41.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:47:11.021 ThaliTest[1224:60b] multipeer session: restart
,2015-12-03 16:47:11.030 ThaliTest[1224:60b] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==

```
