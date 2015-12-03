#### Test 5253548629578ed_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/BB2CFE5E-39A6-47DD-8F42-28E666DC9A55/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BB2CFE5E-39A6-47DD-8F42-28E666DC9A55/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/1032E0DF-9270-4DB6-92AF-6C000EC24822/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60390"
,(lldb)     command script import "/tmp/BB2CFE5E-39A6-47DD-8F42-28E666DC9A55/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 14:59:20.305 ThaliTest[1206:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 14:59:20.308 ThaliTest[1206:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 14:59:20.316 ThaliTest[1206:60b] Unlimited access to network resources
,2015-12-03 14:59:20.322 ThaliTest[1206:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 14:59:29.749 ThaliTest[1206:60b] Resetting plugins due to page load.
,2015-12-03 14:59:30.524 ThaliTest[1206:60b] Finished load of: file:///var/mobile/Applications/1032E0DF-9270-4DB6-92AF-6C000EC24822/ThaliTest.app/www/index.html
,2015-12-03 14:59:30.712 ThaliTest[1206:60b] JXcore Cordova plugin initializing
,2015-12-03 14:59:30.715 ThaliTest[1206:6807] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT2690
,attempting to connect to test coordinator
,check test folder
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63114
,2015-12-03 15:05:04.485 ThaliTest[1206:6807] jxcore: startBroadcasting
,2015-12-03 15:05:04.497 ThaliTest[1206:6807] server: starting Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:04.501 ThaliTest[1206:6807] multipeer session: start timer: 0x1d5f3f70
2015-12-03 15:05:04.502 ThaliTest[1206:6807] THEMultipeerSession initial,ized peer Apple-Iphone5-1_PT2690
2015-12-03 15:05:04.503 ThaliTest[1206:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-03T14:05:04.505Z SendDataTCPServer.js: TCP/IP server is bound to port: 63114
,2015-12-03 15:05:06.151 ThaliTest[1206:60b] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7511.wgBJEg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:05:06.155Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:06.156Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:05:06.156Z SendDataConnector.js: do connect now
,2015-12-03 15:05:06.156 ThaliTest[1206:6807] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:06.157 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:05:06.158 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:06.690 ThaliTest[1206:60b] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7727.aEO4Zw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:06.850 ThaliTest[1206:60b] multipeer session: reset timer
,2015-12-03 15:05:06.852 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:05:06.853 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
,2015-12-03 15:05:06.854 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:05:06.854 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:06.857 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:08.329 ThaliTest[1206:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:08.356 ThaliTest[1206:60b] multipeer session: reset timer
,2015-12-03 15:05:08.357 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:05:08.358 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
,2015-12-03 15:05:08.359 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:05:08.359 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:08.363 ThaliTest[1206:60b] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:09.239 ThaliTest[1206:60b] multipeer session: reset timer
2015-12-03 15:05:09.241 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:05:09.242 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
,2015-12-03 15:05:09.242 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:05:09.243 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:09.247 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:05:09.819 ThaliTest[1206:790b] server session: connected
,2015-12-03 15:05:09.820 ThaliTest[1206:790b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:09.826 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:05:09.834Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:10.211Z SendDataTCPServer.js: TCP/IP server has received 17236 bytes of data
,2015-12-03T14:05:10.224Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-03T14:05:10.239Z SendDataTCPServer.js: TCP/IP server has received 85126 bytes of data
,2015-12-03T14:05:10.253Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:05:10.954 ThaliTest[1206:790b] server session: connected
,2015-12-03 15:05:10.955 ThaliTest[1206:790b] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:10.975 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:05:10.986Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:11.265Z SendDataTCPServer.js: TCP/IP server has received 23806 bytes of data
,2015-12-03T14:05:11.280Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-03T14:05:11.294Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:05:11.349 ThaliTest[1206:2913] client session: connected
,2015-12-03 15:05:11.350 ThaliTest[1206:2913] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:11.375 ThaliTest[1206:221f] server session: not connected Apple-IpadAir2-1_PT7511
2015-12-03 15:05:11.376 ThaliTest[1206:2913] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:11.376 ThaliTest[1206:2913] jxcore: connect: success
,2015-12-03T14:05:11.379Z SendDataConnector.js: CLIENT connected to 63119, error: null
,2015-12-03T14:05:11.379Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:11.380 ThaliTest[1206:60b] client: relay established
2015-12-03 15:05:11.382 ThaliTest[1206:60b] client: new accepted socket: 0x1d70d4a0
,2015-12-03T14:05:11.394Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03 15:05:11.460 ThaliTest[1206:790b] server session: connected
2015-12-03 15:05:11.461 ThaliTest[1206:790b] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:11.467 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:05:11.906Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:11.918Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:05:11.938Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T14:05:11.950Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:05:11.976Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03 15:05:11.986 ThaliTest[1206:221f] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03T14:05:11.988Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:05:12.012Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:05:12.356Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:05:12.402Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:05:20.300 ThaliTest[1206:221f] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:05:22.409Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:22.409Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:22.411Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:22.412Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:22.412Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:22.413 ThaliTest[1206:60b] client: socket closed
2015-12-03 15:05:22.414 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:05:22.415 ThaliTest[1206:60b] client relay: 0x1d70d4a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d6629e0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:05:22.415 ThaliTest[1206:60b] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:22.416 ThaliTest[1206:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:22.417 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:05:22.417 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:22.419 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:27.417Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:27.418Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:30.308 ThaliTest[1206:60b] multipeer session: reset timer
2015-12-03 15:05:30.309 ThaliTest[1206:60b] multipeer session: stop timer
2015-12-03 15:05:30.310 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
,2015-12-03 15:05:30.310 ThaliTest[1206:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
,2015-12-03 15:05:30.311 ThaliTest[1206:60b] server session: disconnect
2015-12-03 15:05:30.311 ThaliTest[1206:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:30.313 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:05:30.314 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:30.319 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:05:30.324Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:32.425 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:05:32.426 ThaliTest[1206:6807] jxcore: disconnect: fail
,2015-12-03T14:05:32.428Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:32.429Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
,2015-12-03T14:05:32.429Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:05:32.429Z SendDataConnector.js: do connect now
,2015-12-03 15:05:32.430 ThaliTest[1206:6807] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:32.430 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:05:32.431 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:32.794 ThaliTest[1206:790b] server session: connected
2015-12-03 15:05:32.795 ThaliTest[1206:790b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:32.799 ThaliTest[1206:60b] server relay: connected (to port: 63114)
2015-12-03T14:05:32.801Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:32.903Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:05:35.400 ThaliTest[1206:8a07] client session: connected
,2015-12-03 15:05:35.402 ThaliTest[1206:8a07] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:35.429 ThaliTest[1206:221f] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:35.431 ThaliTest[1206:221f] jxcore: connect: success
,2015-12-03T14:05:35.432Z SendDataConnector.js: CLIENT connected to 63124, error: null
,2015-12-03T14:05:35.433Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:35.434 ThaliTest[1206:60b] client: relay established
,2015-12-03 15:05:35.435 ThaliTest[1206:60b] client: new accepted socket: 0x1d7074c0
,2015-12-03T14:05:35.446Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:05:43.247 ThaliTest[1206:221f] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:05:45.507Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:45.507Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:45.508Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:45.509Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:45.510Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:45.511 ThaliTest[1206:60b] client: socket closed
,2015-12-03 15:05:45.512 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:05:45.512 ThaliTest[1206:60b] client relay: 0x1d7074c0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d652580 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:05:45.513 ThaliTest[1206:60b] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:05:45.513 ThaliTest[1206:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:45.514 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:05:45.515 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:45.516 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:50.515Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:50.515Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:53.185 ThaliTest[1206:60b] multipeer session: reset timer
2015-12-03 15:05:53.186 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:05:53.186 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
2015-12-03 15:05:53.187 ThaliTest[1206:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
2015-12-03 15:05:53.188 ThaliTest[1206:60b] server session: disconnect
2015-12-03 15:05:53.188 ThaliTest[1206:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:53.191 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:05:53.192 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:53.196 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:05:53.200Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:55.525 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:05:55.527 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:05:55.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:55.529Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
2015-12-03T14:05:55.529Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015,-12-03T14:05:55.529Z SendDataConnector.js: do connect now
,2015-12-03 15:05:55.530 ThaliTest[1206:6807] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:55.530 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:05:55.531 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:55.950 ThaliTest[1206:790b] server session: connected
2015-12-03 15:05:55.952 ThaliTest[1206:790b] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:55.955 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:05:55.957Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:56.047Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:05:59.655 ThaliTest[1206:790b] client session: connected
,2015-12-03 15:05:59.657 ThaliTest[1206:790b] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:59.982 ThaliTest[1206:790b] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:05:59.983 ThaliTest[1206:790b] jxcore: connect: success
,2015-12-03T14:05:59.984Z SendDataConnector.js: CLIENT connected to 63129, error: null
2015-12-03T14:05:59.984Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:59.985 ThaliTest[1206:60b] client: relay established
2015-12-03 15:05:59.986 ThaliTest[1206:60b] client: new accepted socket: 0x1d720080
,2015-12-03T14:05:59.998Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:06.290 ThaliTest[1206:b01b] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:06:10.067Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:10.067Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:06:10.068Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:10.068Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T14:06:10.069Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:10.070 ThaliTest[1206:60b] client: socket closed
,2015-12-03 15:06:10.071 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:06:10.072 ThaliTest[1206:60b] client relay: 0x1d720080 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d702c30 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:06:10.072 ThaliTest[1206:60b] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:10.073 ThaliTest[1206:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:10.074 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:06:10.074 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:10.075 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:15.078Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:15.078Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:16.316 ThaliTest[1206:60b] multipeer session: reset timer
2015-12-03 15:06:16.318 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:06:16.318 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
2015-12-03 15:06:16.319 ThaliTest[1206:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
,2015-12-03 15:06:16.319 ThaliTest[1206:60b] server session: disconnect
,2015-12-03 15:06:16.320 ThaliTest[1206:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:16.322 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:06:16.323 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:16.327 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:06:16.331Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:18.538 ThaliTest[1206:2223] server session: connected
,2015-12-03 15:06:18.539 ThaliTest[1206:2223] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:18.543 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:06:18.554Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:18.677Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T14:06:18.689Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:20.082 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:06:20.083 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:06:20.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:20.085Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
2015-12-03T14:06:20.086Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:06:20.086Z SendDataConnector.js: do connect now
,2015-12-03 15:06:20.086 ThaliTest[1206:6807] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:20.087 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:06:20.088 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:24.160 ThaliTest[1206:961f] client session: connected
2015-12-03 15:06:24.161 ThaliTest[1206:961f] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:24.188 ThaliTest[1206:b01b] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:24.189 ThaliTest[1206:b01b] jxcore: connect: success
,2015-12-03T14:06:24.190Z SendDataConnector.js: CLIENT connected to 63133, error: null
2015-12-03T14:06:24.190Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:24.191 ThaliTest[1206:60b] client: relay established
,2015-12-03 15:06:24.193 ThaliTest[1206:60b] client: new accepted socket: 0x1d723b30
,2015-12-03T14:06:24.203Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:28.845 ThaliTest[1206:b01b] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:06:34.266Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:34.266Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:34.267Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:34.268Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:34.269Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:34.270 ThaliTest[1206:60b] client: socket closed
,2015-12-03 15:06:34.271 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:06:34.271 ThaliTest[1206:60b] client relay: 0x1d723b30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d723040 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:06:34.272 ThaliTest[1206:60b] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:34.273 ThaliTest[1206:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:34.273 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:06:34.274 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:34.275 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:38.790 ThaliTest[1206:60b] multipeer session: reset timer
2015-12-03 15:06:38.792 ThaliTest[1206:60b] multipeer session: stop timer
,2015-12-03 15:06:38.792 ThaliTest[1206:60b] multipeer session: start timer: 0x1d5f3f70
2015-12-03 15:06:38.793 ThaliTest[1206:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
,2015-12-03 15:06:38.793 ThaliTest[1206:60b] server session: disconnect
,2015-12-03 15:06:38.794 ThaliTest[1206:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:38.796 ThaliTest[1206:60b] server session: connect
,2015-12-03 15:06:38.797 ThaliTest[1206:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:38.801 ThaliTest[1206:60b] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:06:38.807Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:06:39.272Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:39.273Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:41.031 ThaliTest[1206:2223] server session: connected
2015-12-03 15:06:41.033 ThaliTest[1206:2223] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:41.037 ThaliTest[1206:60b] server relay: connected (to port: 63114)
,2015-12-03T14:06:41.048Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:41.216Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T14:06:41.229Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:44.277 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:06:44.278 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:06:44.280Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:44.281Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
2015-12-03T14:06:44.281Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:06:44.281Z SendDataConnector.js: do connect now
,2015-12-03 15:06:44.281 ThaliTest[1206:6807] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:44.282 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:06:44.283 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:48.352 ThaliTest[1206:2223] client session: connected
2015-12-03 15:06:48.353 ThaliTest[1206:2223] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:48.361 ThaliTest[1206:2223] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:48.362 ThaliTest[1206:2223] jxcore: connect: success
,2015-12-03T14:06:48.363Z SendDataConnector.js: CLIENT connected to 63137, error: null
2015-12-03T14:06:48.364Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:48.366 ThaliTest[1206:60b] client: relay established
2015-12-03 15:06:48.366 ThaliTest[1206:60b] client: new accepted socket: 0x1d72a3d0
,2015-12-03T14:06:48.377Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:51.367 ThaliTest[1206:2223] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:06:58.438Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:58.438Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:58.439Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:58.442Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:06:58.442Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:06:58.442Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:06:58.443 ThaliTest[1206:6807] jxcore: disconnect
2015-12-03 15:06:58.444 ThaliTest[1206:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:58.444 ThaliTest[1206:6807] client session: disconnect
201,5-12-03 15:06:58.445 ThaliTest[1206:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:58.447 ThaliTest[1206:6807] jxcore: disconnect: success
2015-12-03T14:06:58.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:58.452Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:06:58.453Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:58.453Z SendDataConnector.js: do connect now
,2015-12-03 15:06:58.453 ThaliTest[1206:6807] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:58.454 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:06:58.455 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:58.460Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:01.532 ThaliTest[1206:2223] client session: connected
2015-12-03 15:07:01.534 ThaliTest[1206:2223] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:01.537 ThaliTest[1206:2223] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:01.538 ThaliTest[1206:2223] jxcore: connect: success
,2015-12-03T14:07:01.539Z SendDataConnector.js: CLIENT connected to 63142, error: null
,2015-12-03T14:07:01.539Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:01.541 ThaliTest[1206:60b] client: relay established
,2015-12-03 15:07:01.543 ThaliTest[1206:60b] client: new accepted socket: 0x1d67fd30
,2015-12-03T14:07:01.553Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:07:02.151Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:07:02.164Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:07:02.178Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:07:02.213Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:07:02.214Z SendDataConnector.js: got all data for this round
,2015-12-03T14:07:02.215Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:07:02.216Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:07:02.217 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:07:02.218 ThaliTest[1206:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:02.219 ThaliTest[1206:6807] client session: disconnect
,2015-12-03 15:07:02.219 ThaliTest[1206:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:02.221 ThaliTest[1206:6807] jxcore: disconnect: success
2015-12-03T14:07:02.222Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
---- round done--------
,device[3]: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:07:02.224Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:07:02.224Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
20,15-12-03T14:07:02.224Z SendDataConnector.js: do connect now
,2015-12-03 15:07:02.224 ThaliTest[1206:6807] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:02.226 ThaliTest[1206:6807] client session: connect
2015-12-03 15:07:02.227 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:05.025 ThaliTest[1206:b01b] client session: connected
2015-12-03 15:07:05.026 ThaliTest[1206:b01b] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:05.029 ThaliTest[1206:b01b] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:07:05.030 ThaliTest[1206:b01b] jxcore: connect: success
,2015-12-03T14:07:05.031Z SendDataConnector.js: CLIENT connected to 63145, error: null
2015-12-03T14:07:05.031Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:05.033 ThaliTest[1206:60b] client: relay established
2015-12-03 15:07:05.035 ThaliTest[1206:60b] client: new accepted socket: 0x1d729ba0
,2015-12-03T14:07:05.044Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:07:05.557Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:07:05.569Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:07:05.605Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:07:05.630Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:07:05.654Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:07:08.794 ThaliTest[1206:60b] multipeer session: restart
,2015-12-03T14:07:15.660Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:15.661Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:07:15.661Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:07:15.662Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T14:07:15.662Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:15.664 ThaliTest[1206:60b] client: socket closed
,2015-12-03 15:07:15.664 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:07:15.666 ThaliTest[1206:60b] client relay: 0x1d729ba0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1765eaa0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:07:15.667 ThaliTest[1206:60b] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:15.667 ThaliTest[1206:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:07:15.668 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:07:15.668 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:15.670 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:07:20.669Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:07:20.669Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:25.676 ThaliTest[1206:6807] jxcore: disconnect
2015-12-03 15:07:25.677 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:07:25.679Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2,015-12-03T14:07:25.680Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:07:25.680Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:07:25.680Z SendDataConnector.js: do connect now
2015-12-03 15:07:25.680 ThaliTest[1206:6807] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:07:25.681 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:07:25.682 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:28.610 ThaliTest[1206:2223] client session: connected
2015-12-03 15:07:28.612 ThaliTest[1206:2223] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:28.615 ThaliTest[1206:2223] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:28.616 ThaliTest[1206:2223] jxcore: connect: success
,2015-12-03T14:07:28.617Z SendDataConnector.js: CLIENT connected to 63150, error: null
2015-12-03T14:07:28.617Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:28.618 ThaliTest[1206:60b] client: relay established
2015-12-03 15:07:28.620 ThaliTest[1206:60b] client: new accepted socket: 0x1d676de0
,2015-12-03T14:07:28.631Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:07:38.693Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:38.694Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:38.694Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:38.695Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:38.696Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:38.697 ThaliTest[1206:60b] client: socket closed
2015-12-03 15:07:38.698 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:07:38.699 ThaliTest[1206:60b] client relay: 0x1d676de0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d582930 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03, 15:07:38.700 ThaliTest[1206:60b] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:38.700 ThaliTest[1206:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:07:38.701 ThaliTest[1206:60b] client session: disconnect
,2015-12-03 15:07:38.701 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:38.703 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:38.794 ThaliTest[1206:60b] multipeer session: restart
,2015-12-03 15:07:38.804 ThaliTest[1206:60b] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:38.805 ThaliTest[1206:60b] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:38.806 ThaliTest[1206:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:07:43.700Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:07:43.700Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:48.708 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:07:48.710 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:07:48.711Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:07:48.712Z SendDataConnector.js: Connect (retry coun,t 2) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:07:48.712Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:07:48.713Z SendDataConnector.js: do connect now
,2015-12-03 15:07:48.713 ThaliTest[1206:6807] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:48.714 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:07:48.714 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:51.665 ThaliTest[1206:8a1b] client session: connected
,2015-12-03 15:07:51.667 ThaliTest[1206:8a1b] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:51.670 ThaliTest[1206:8a1b] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:51.671 ThaliTest[1206:8a1b] jxcore: connect: success
,2015-12-03T14:07:51.672Z SendDataConnector.js: CLIENT connected to 63155, error: null
2015-12-03T14:07:51.673Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:51.675 ThaliTest[1206:60b] client: relay established
2015-12-03 15:07:51.675 ThaliTest[1206:60b] client: new accepted socket: 0x1d729ba0
,2015-12-03T14:07:51.686Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:08:01.747Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:01.748Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:01.748Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:01.749Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:08:01.750Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:01.751 ThaliTest[1206:60b] client: socket closed
2015-12-03 15:08:01.752 ThaliTest[1206:60b] client relay: socket disconnected
,2015-12-03 15:08:01.753 ThaliTest[1206:60b] client relay: 0x1d729ba0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1d115de0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:08:01.753 ThaliTest[1206:60b] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:01.754 ThaliTest[1206:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:01.755 ThaliTest[1206:60b] client session: disconnect
2015-12-03 15:08:01.755 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:01.757 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:06.755Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:06.755Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:08.794 ThaliTest[1206:60b] multipeer session: restart
,2015-12-03 15:08:08.805 ThaliTest[1206:60b] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:08.806 ThaliTest[1206:60b] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:08.807 ThaliTest[1206:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:11.761 ThaliTest[1206:6807] jxcore: disconnect
,2015-12-03 15:08:11.763 ThaliTest[1206:6807] jxcore: disconnect: fail
,2015-12-03T14:08:11.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:11.765Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:08:11.765Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:11.766Z SendDataConnector.js: do connect now
,2015-12-03 15:08:11.766 ThaliTest[1206:6807] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:11.767 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:08:11.767 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:14.720 ThaliTest[1206:b333] client session: connected
2015-12-03 15:08:14.722 ThaliTest[1206:b333] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:14.724 ThaliTest[1206:b333] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:14.725 ThaliTest[1206:b333] jxcore: connect: success
,2015-12-03T14:08:14.726Z SendDataConnector.js: CLIENT connected to 63161, error: null
2015-12-03T14:08:14.726Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:14.728 ThaliTest[1206:60b] client: relay established
2015-12-03 15:08:14.729 ThaliTest[1206:60b] client: new accepted socket: 0x1d729ba0
,2015-12-03T14:08:14.739Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:08:24.799Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:24.800Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:24.800Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:24.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T14:08:24.801Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:24.803 ThaliTest[1206:60b] client: socket closed
,2015-12-03 15:08:24.803 ThaliTest[1206:60b] client relay: socket disconnected
2015-12-03 15:08:24.804 ThaliTest[1206:60b] client relay: 0x1d729ba0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInf,o=0x1d36fc10 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:08:24.805 ThaliTest[1206:60b] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:24.805 ThaliTest[1206:60b] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:24.806 ThaliTest[1206:60b] client session: disconnect
2015-12-03 15:08:24.807 ThaliTest[1206:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:24.808 ThaliTest[1206:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:29.809Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:29.810Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:34.815 ThaliTest[1206:6807] jxcore: disconnect
2015-12-03 15:08:34.816 ThaliTest[1206:6807] jxcore: disconnect: fail
2015-12-03T14:08:34.817Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2,015-12-03T14:08:34.818Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
,2015-12-03T14:08:34.818Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:08:34.818Z SendDataConnector.js: do connect now
2015-12-03 15:08:34.819 ThaliTest[1206:6807] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:34.820 ThaliTest[1206:6807] client session: connect
,2015-12-03 15:08:34.820 ThaliTest[1206:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:38.459 ThaliTest[1206:9043] client session: connected
2015-12-03 15:08:38.462 ThaliTest[1206:9043] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:38.465 ThaliTest[1206:9043] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:38.466 ThaliTest[1206:9043] jxcore: connect: success
2015-12-03T14:08:38.467Z SendDataConnector.js: CLIENT connected to 63165, error: null
,2015-12-03T14:08:38.467Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:38.469 ThaliTest[1206:60b] client: relay established
2015-12-03 15:08:38.470 ThaliTest[1206:60b] client: new accepted socket: 0x1d3b54c0
,2015-12-03T14:08:38.481Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:08:38.793 ThaliTest[1206:60b] multipeer session: restart
,2015-12-03 15:08:38.803 ThaliTest[1206:60b] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:38.804 ThaliTest[1206:60b] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:38.805 ThaliTest[1206:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:48.535Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:48.536Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:48.536Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:48.538Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:08:48.539Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:08:48.539Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:08:48.539 ThaliTest[1206:6807] jxcore: disconnect
2015-12-03 15:08:48.540 ThaliTest[1206:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:48.541 ThaliTest[1206:6807] client session: disconnect
2015-12-03 15:08:48.541 ThaliTest[1206:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:48.545 ThaliTest[1206:6807] jxcore: disconnect: success
,2015-12-03T14:08:48.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT2690","time":224070,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT7511.wgBJEg==","time":112285,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Appl,e-Iphone5s-1_PT7727.aEO4Zw==","time":3762,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT7057.4CFLyQ==","time":106313,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":10,0000,"dataReceived":90000}]}
,sendList : 100% : 3762 ms, 99% : 3762 ms, 95 : 3762 ms, 90% : 3762 ms.
Result count 1, range 3762 ms to  3762 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5
,- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T14:08:48.554Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:08:48.555Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:48.555Z SendDataConnector.js: ----------------- closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-03 15:08:48.695 ThaliTest[1206:6807] jxcore: stopBroadcasting
,2015-12-03 15:08:48.696 ThaliTest[1206:6807] THEMultipeerSession stopping peer
,2015-12-03 15:08:48.696 ThaliTest[1206:6807] multipeer session: stop timer
,2015-12-03 15:08:48.697 ThaliTest[1206:6807] server session: disconnect
2015-12-03 15:08:48.698 ThaliTest[1206:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:58.177 ThaliTest[1206:6807] server session: disconnect
2015-12-03 15:08:58.177 ThaliTest[1206:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT7057
,2015-12-03 15:08:58.180 ThaliTest[1206:6807] server session: disconnect
2015-12-03 15:08:58.181 ThaliTest[1206:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:58.184 ThaliTest[1206:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-03T14:08:58.200Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:58.201Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:58.202Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:58.203Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7727.aEO4Zw==\",\"time\":3762,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-IpadAir2-1_PT7511.wgBJEg==\",\"time\":112285,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-Iphone6-1_PT7057.4CFLyQ==\",\"tim,e\":106313,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
