#### Test 525354860130a71_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/FCF42B44-01EC-4F3B-9FFD-AF38CE8E0A6E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FCF42B44-01EC-4F3B-9FFD-AF38CE8E0A6E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/50DD57FE-6F3F-4977-94A8-5BF63AC19D1E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61430"
,(lldb)     command script import "/tmp/FCF42B44-01EC-4F3B-9FFD-AF38CE8E0A6E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:44:03.307 ThaliTest[1313:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:44:03.311 ThaliTest[1313:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:44:03.317 ThaliTest[1313:60b] Unlimited access to network resources
,2015-12-04 09:44:03.325 ThaliTest[1313:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:44:14.139 ThaliTest[1313:60b] Resetting plugins due to page load.
,2015-12-04 09:44:14.952 ThaliTest[1313:60b] Finished load of: file:///var/mobile/Applications/50DD57FE-6F3F-4977-94A8-5BF63AC19D1E/ThaliTest.app/www/index.html
,2015-12-04 09:44:15.132 ThaliTest[1313:60b] JXcore Cordova plugin initializing
,2015-12-04 09:44:15.133 ThaliTest[1313:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5-1_PT9194
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 65092
,2015-12-04 09:49:52.307 ThaliTest[1313:6807] jxcore: startBroadcasting
,2015-12-04 09:49:52.317 ThaliTest[1313:6807] server: starting Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:49:52.319 ThaliTest[1313:6807] multipeer session: start timer: 0x1ae49070
2015-12-04 09:49:52.320 ThaliTest[1313:6807] THEMultipeerSession initial,ized peer Apple-Iphone5-1_PT9194
2015-12-04 09:49:52.321 ThaliTest[1313:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-04T08:49:52.323Z SendDataTCPServer.js: TCP/IP server is bound to port: 65092
,2015-12-04 09:49:52.881 ThaliTest[1313:60b] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7135.+FivAg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:49:52.885Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:49:52.886Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:49:52.886Z SendDataConnector.js: do connect now
,2015-12-04 09:49:52.886 ThaliTest[1313:6807] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:52.887 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:49:52.888 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:53.456 ThaliTest[1313:60b] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7213.N3FSeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:53.488 ThaliTest[1313:60b] client: found peer: Apple-IpadAir2-1_PT6975.MZRWVw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6975.MZRWVw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:55.580 ThaliTest[1313:7a07] client session: connected
,2015-12-04 09:49:55.582 ThaliTest[1313:7a07] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:55.593 ThaliTest[1313:7a07] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:55.594 ThaliTest[1313:7a07] jxcore: connect: success
,2015-12-04T08:49:55.596Z SendDataConnector.js: CLIENT connected to 65095, error: null
,2015-12-04T08:49:55.596Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:55.598 ThaliTest[1313:60b] client: relay established
2015-12-04 09:49:55.598 ThaliTest[1313:60b] client: new accepted socket: 0x1af543f0
,2015-12-04T08:49:55.612Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:49:56.128Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:49:56.140Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-04T08:49:56.153Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-04T08:49:56.231Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-04T08:49:56.232Z SendDataConnector.js: got all data for this round
,2015-12-04T08:49:56.234Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:49:56.235Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:49:56.236 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:49:56.236 ThaliTest[1313:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:56.237 ThaliTest[1313:6807] client session: disconnect
,2015-12-04 09:49:56.238 ThaliTest[1313:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:56.241 ThaliTest[1313:6807] jxcore: disconnect: success
2015-12-04T08:49:56.242Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivAg==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:49:56.246Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:49:56.246Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:49:56.246Z SendDataConnector.js: do connect now
,2015-12-04 09:49:56.246 ThaliTest[1313:6807] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:56.247 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:49:56.248 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:58.670 ThaliTest[1313:7a07] client session: connected
2015-12-04 09:49:58.672 ThaliTest[1313:7a07] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:58.674 ThaliTest[1313:7a07] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:58.675 ThaliTest[1313:7a07] jxcore: connect: success
,2015-12-04T08:49:58.676Z SendDataConnector.js: CLIENT connected to 65098, error: null
2015-12-04T08:49:58.676Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:58.678 ThaliTest[1313:60b] client: relay established
,2015-12-04 09:49:58.680 ThaliTest[1313:60b] client: new accepted socket: 0x1af52ea0
,2015-12-04T08:49:58.690Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:49:59.225Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04T08:49:59.239Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:49:59.251Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-04T08:49:59.364Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-04T08:49:59.378Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04 09:49:59.907 ThaliTest[1313:60b] multipeer session: reset timer
,2015-12-04 09:49:59.909 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:49:59.909 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:49:59.910 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:49:59.911 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:49:59.914 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04 09:50:02.023 ThaliTest[1313:771f] server session: connected
,2015-12-04 09:50:02.025 ThaliTest[1313:771f] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:02.046 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:02.050Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:02.328Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-04T08:50:02.342Z SendDataTCPServer.js: TCP/IP server has received 32566 bytes of data
,2015-12-04T08:50:02.359Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-04T08:50:02.374Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:50:04.096 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:50:04.097 ThaliTest[1313:60b] multipeer session: stop timer
,2015-12-04 09:50:04.098 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
2015-12-04 09:50:04.099 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:50:04.100 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:04.103 ThaliTest[1313:60b] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:07.070 ThaliTest[1313:771f] server session: connected
2015-12-04 09:50:07.071 ThaliTest[1313:771f] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:07.075 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:07.085Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:07.309Z SendDataTCPServer.js: TCP/IP server has received 12856 bytes of data
,2015-12-04T08:50:07.322Z SendDataTCPServer.js: TCP/IP server has received 50086 bytes of data
,2015-12-04T08:50:07.336Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-04T08:50:07.581Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-04T08:50:07.594Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04T08:50:09.383Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:09.384Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:09.385Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:09.386Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:09.386Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:09.388 ThaliTest[1313:60b] client: socket closed
,2015-12-04 09:50:09.388 ThaliTest[1313:60b] client relay: socket disconnected
,2015-12-04 09:50:09.389 ThaliTest[1313:60b] client relay: 0x1af52ea0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1aba97e0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:50:09.390 ThaliTest[1313:60b] client session: socket closed: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:09.390 ThaliTest[1313:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:09.391 ThaliTest[1313:60b] client session: disconnect
2015-12-04 09:50:09.391 ThaliTest[1313:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:09.393 ThaliTest[1313:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:12.419 ThaliTest[1313:9d07] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04T08:50:14.390Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:50:14.391Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:17.653 ThaliTest[1313:9d07] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:19.401 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:50:19.402 ThaliTest[1313:6807] jxcore: disconnect: fail
2015-12-04T08:50:19.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:50:19.404Z SendDataConnector.js: Connect (retry cou,nt 1) to peer Apple-Iphone5s-1_PT7213.N3FSeg== with availability status: true
,2015-12-04T08:50:19.405Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:50:19.405Z SendDataConnector.js: do connect now
,2015-12-04 09:50:19.405 ThaliTest[1313:6807] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:19.406 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:50:19.406 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:22.240 ThaliTest[1313:9d07] client session: connected
2015-12-04 09:50:22.242 ThaliTest[1313:9d07] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:22.244 ThaliTest[1313:9d07] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:50:22.245 ThaliTest[1313:9d07] jxcore: connect: success
,2015-12-04T08:50:22.246Z SendDataConnector.js: CLIENT connected to 65104, error: null
2015-12-04T08:50:22.246Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:22.248 ThaliTest[1313:60b] client: relay established
2015-12-04 09:50:22.250 ThaliTest[1313:60b] client: new accepted socket: 0x1ab18680
,2015-12-04T08:50:22.259Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:22.420 ThaliTest[1313:60b] multipeer session: reset timer
,2015-12-04 09:50:22.421 ThaliTest[1313:60b] multipeer session: stop timer
,2015-12-04 09:50:22.422 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:50:22.423 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT7135)
2015-12-04 09:50:22.423 ThaliTest[1313:60b] server session: disconnect
,2015-12-04 09:50:22.424 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:22.426 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:50:22.427 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:22.431 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04T08:50:22.436Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:24.873 ThaliTest[1313:7a07] server session: connected
2015-12-04 09:50:24.874 ThaliTest[1313:7a07] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:24.883 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:24.891Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:25.003Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:50:27.692 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:50:27.692 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:50:27.693 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
2015-12-04 09:50:,27.694 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6975)
,2015-12-04 09:50:27.694 ThaliTest[1313:60b] server session: disconnect
2015-12-04 09:50:27.695 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:27.698 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:50:27.699 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
2015-12-04T08:50:27.701Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:27.704 ThaliTest[1313:60b] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:30.151 ThaliTest[1313:7723] server session: connected
2015-12-04 09:50:30.152 ThaliTest[1313:7723] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:30.156 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:30.167Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:30.311Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04T08:50:32.323Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:32.323Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:50:32.324Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:32.324Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:32.325Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:32.327 ThaliTest[1313:60b] client: socket closed
,2015-12-04 09:50:32.327 ThaliTest[1313:60b] client relay: socket disconnected
,2015-12-04 09:50:32.328 ThaliTest[1313:60b] client relay: 0x1ab18680 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ac94e00 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:50:32.329 ThaliTest[1313:60b] client session: socket closed: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:50:32.329 ThaliTest[1313:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:32.330 ThaliTest[1313:60b] client session: disconnect
,2015-12-04 09:50:32.330 ThaliTest[1313:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:32.332 ThaliTest[1313:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:34.992 ThaliTest[1313:830b] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04T08:50:37.330Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:50:37.331Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:40.212 ThaliTest[1313:830b] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:42.339 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:50:42.341 ThaliTest[1313:6807] jxcore: disconnect: fail
2015-12-04T08:50:42.342Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:50:42.342Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7213.N3FSeg== with availability status: true
,2015-12-04T08:50:42.343Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:50:42.343Z SendDataConnector.js: do connect now
,2015-12-04 09:50:42.343 ThaliTest[1313:6807] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:42.344 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:50:42.344 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:45.017 ThaliTest[1313:7f0f] client session: connected
,2015-12-04 09:50:45.019 ThaliTest[1313:7f0f] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:45.023 ThaliTest[1313:7f0f] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:45.023 ThaliTest[1313:7f0f] jxcore: connect: success
,2015-12-04T08:50:45.024Z SendDataConnector.js: CLIENT connected to 65111, error: null
2015-12-04T08:50:45.025Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:45.027 ThaliTest[1313:60b] client: relay established
,2015-12-04 09:50:45.028 ThaliTest[1313:60b] client: new accepted socket: 0x1ad0f3f0
,2015-12-04T08:50:45.042Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:45.305 ThaliTest[1313:60b] multipeer session: reset timer
,2015-12-04 09:50:45.306 ThaliTest[1313:60b] multipeer session: stop timer
,2015-12-04 09:50:45.307 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:50:45.307 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT7135)
,2015-12-04 09:50:45.308 ThaliTest[1313:60b] server session: disconnect
2015-12-04 09:50:45.309 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:45.311 ThaliTest[1313:60b] server session: connect
2015-12-04 09:50:45.312 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:45.315 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04T08:50:45.318Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:47.542 ThaliTest[1313:7a07] server session: connected
,2015-12-04 09:50:47.544 ThaliTest[1313:7a07] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:50:47.563 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:47.571Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:47.738Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:50:50.610 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:50:50.612 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:50:50.613 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:50:50.613 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6975)
2015-12-04 09:50:50.614 ThaliTest[1313:60b] server session: disconnect
,2015-12-04 09:50:50.615 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:50.617 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:50:50.618 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
,2015-12-04T08:50:50.622Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:50.623 ThaliTest[1313:60b] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:53.348 ThaliTest[1313:7723] server session: connected
2015-12-04 09:50:53.350 ThaliTest[1313:7723] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:53.354 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:50:53.364Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:53.420Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04T08:50:55.102Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:55.103Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:55.103Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:55.104Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:55.105Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:55.107 ThaliTest[1313:60b] client: socket closed
2015-12-04 09:50:55.108 ThaliTest[1313:60b] client relay: socket disconnected
,2015-12-04 09:50:55.108 ThaliTest[1313:60b] client relay: 0x1ad0f3f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14d879d0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:50:55.109 ThaliTest[1313:60b] client session: socket closed: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:55.110 ThaliTest[1313:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:55.110 ThaliTest[1313:60b] client session: disconnect
,2015-12-04 09:50:55.111 ThaliTest[1313:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:55.112 ThaliTest[1313:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:50:57.884 ThaliTest[1313:7723] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04T08:51:00.111Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:51:00.111Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:03.683 ThaliTest[1313:7723] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:05.117 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:51:05.118 ThaliTest[1313:6807] jxcore: disconnect: fail
2015-12-04T08:51:05.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:51:05.120Z SendDataConnector.js: Connect (retry cou,nt 3) to peer Apple-Iphone5s-1_PT7213.N3FSeg== with availability status: true
2015-12-04T08:51:05.120Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:51:05.121Z SendDataConnector.js: do connect now
2015-12-04 09:51:05.121 ThaliTest[1313:6807] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:05.122 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:51:05.122 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:08.369 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:51:08.370 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:51:08.371 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:51:08.372 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT7135)
,2015-12-04 09:51:08.372 ThaliTest[1313:60b] server session: disconnect
2015-12-04 09:51:08.373 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04T08:51:08.376Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04 09:51:08.376 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:51:08.377 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:08.382 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04 09:51:11.091 ThaliTest[1313:7723] server session: connected
,2015-12-04 09:51:11.092 ThaliTest[1313:7723] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:11.101 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:51:11.105Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:11.193Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:13.695 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:51:13.696 ThaliTest[1313:60b] multipeer session: stop timer
,2015-12-04 09:51:13.697 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
2015-12-04 09:51:13.698 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6975)
,2015-12-04 09:51:13.699 ThaliTest[1313:60b] server session: disconnect
,2015-12-04 09:51:13.699 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:13.701 ThaliTest[1313:60b] server session: connect
2015-12-04 09:51:13.702 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
2015-12-04T08:51:13.703Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:51:13.706 ThaliTest[1313:60b] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:14.860 ThaliTest[1313:7f0f] client session: connected
2015-12-04 09:51:14.863 ThaliTest[1313:7f0f] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:14.866 ThaliTest[1313:7f0f] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:51:14.866 ThaliTest[1313:7f0f] jxcore: connect: success
,2015-12-04T08:51:14.867Z SendDataConnector.js: CLIENT connected to 65118, error: null
2015-12-04T08:51:14.868Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:14.869 ThaliTest[1313:60b] client: relay established
,2015-12-04 09:51:14.871 ThaliTest[1313:60b] client: new accepted socket: 0x1af4b030
,2015-12-04T08:51:14.881Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:16.307 ThaliTest[1313:7f0f] server session: connected
2015-12-04 09:51:16.309 ThaliTest[1313:7f0f] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:16.312 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:51:16.320Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:16.422Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:21.472 ThaliTest[1313:7f0f] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04T08:51:24.939Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:24.940Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:51:24.941Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:24.941Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-04T08:51:24.942Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:24.943 ThaliTest[1313:60b] client: socket closed
,2015-12-04 09:51:24.944 ThaliTest[1313:60b] client relay: socket disconnected
,2015-12-04 09:51:24.945 ThaliTest[1313:60b] client relay: 0x1af4b030 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1abbe1a0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:51:24.945 ThaliTest[1313:60b] client session: socket closed: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:24.946 ThaliTest[1313:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:24.946 ThaliTest[1313:60b] client session: disconnect
,2015-12-04 09:51:24.947 ThaliTest[1313:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:24.949 ThaliTest[1313:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:26.714 ThaliTest[1313:7f0f] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04T08:51:29.949Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:51:29.949Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:31.432 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:51:31.434 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:51:31.435 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:51:31.435 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-Iphone6-1_PT7135)
2015-12-04 09:51:31.436 ThaliTest[1313:60b] server session: disconnect
2015-12-04 09:51:31.436 ThaliTest[1313:60b] server session: stateChange:2,->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:31.439 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:51:31.440 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:31.443 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04T08:51:31.447Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:51:33.671 ThaliTest[1313:7a0b] server session: connected
,2015-12-04 09:51:33.673 ThaliTest[1313:7a0b] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:33.683 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:51:33.693Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:33.860Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:34.957 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:51:34.958 ThaliTest[1313:6807] jxcore: disconnect: fail
2015-12-04T08:51:34.959Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:51:34.960Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7213.N3FSeg== with availability status: true
,2015-12-04T08:51:34.960Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:51:34.960Z SendDataConnector.js: do connect now
,2015-12-04 09:51:34.961 ThaliTest[1313:6807] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:34.962 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:51:34.962 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:36.740 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:51:36.741 ThaliTest[1313:60b] multipeer session: stop timer
,2015-12-04 09:51:36.742 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
2015-12-04 09:51:36.743 ThaliTest[1313:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT6975)
,2015-12-04 09:51:36.743 ThaliTest[1313:60b] server session: disconnect
,2015-12-04 09:51:36.744 ThaliTest[1313:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:36.746 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:51:36.747 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:36.751 ThaliTest[1313:60b] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04T08:51:36.757Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:51:37.394 ThaliTest[1313:b207] client session: connected
,2015-12-04 09:51:37.396 ThaliTest[1313:b207] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:37.400 ThaliTest[1313:b207] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:37.401 ThaliTest[1313:b207] jxcore: connect: success
,2015-12-04T08:51:37.402Z SendDataConnector.js: CLIENT connected to 65125, error: null
2015-12-04T08:51:37.402Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:37.404 ThaliTest[1313:60b] client: relay established
2015-12-04 09:51:37.405 ThaliTest[1313:60b] client: new accepted socket: 0x14dad170
,2015-12-04T08:51:37.415Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:38.938 ThaliTest[1313:60b] multipeer session: reset timer
2015-12-04 09:51:38.939 ThaliTest[1313:60b] multipeer session: stop timer
2015-12-04 09:51:38.941 ThaliTest[1313:60b] multipeer session: start timer: 0x1ae49070
,2015-12-04 09:51:38.941 ThaliTest[1313:60b] server session: connect
,2015-12-04 09:51:38.942 ThaliTest[1313:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:38.945 ThaliTest[1313:60b] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:39.324 ThaliTest[1313:b207] server session: connected
2015-12-04 09:51:39.326 ThaliTest[1313:b207] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:39.329 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:51:39.339Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:39.408Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:51:39.420Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:41.418 ThaliTest[1313:7f0f] server session: connected
2015-12-04 09:51:41.420 ThaliTest[1313:7f0f] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:41.422 ThaliTest[1313:60b] server relay: connected (to port: 65092)
,2015-12-04T08:51:41.431Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:41.922Z SendDataTCPServer.js: TCP/IP server has received 10666 bytes of data
,2015-12-04T08:51:41.935Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-04T08:51:41.950Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-04T08:51:41.963Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:51:41.993 ThaliTest[1313:7f0f] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:44.012 ThaliTest[1313:b207] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04T08:51:47.471Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:51:47.471Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:51:47.472Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:47.473Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:47.474Z SendDataConnector.js: Stop data retrieving timer
2015-12-04T08:51:47.475Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:47.475 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:51:47.476 ThaliTest[1313:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:47.477 ThaliTest[1313:6807] client session: disconnect
,2015-12-04 09:51:47.478 ThaliTest[1313:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:51:47.480 ThaliTest[1313:6807] jxcore: disconnect: success
2015-12-04T08:51:47.481Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04T08:51:47.484Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04T08:51:47.484Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6975.MZRWVw==,
2015-12-04T08:51:47.484Z SendDataConnector.js: do connect now
,2015-12-04 09:51:47.484 ThaliTest[1313:6807] jxcore: connect Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:51:47.485 ThaliTest[1313:6807] client session: connect
,2015-12-04 09:51:47.486 ThaliTest[1313:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04T08:51:47.490Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:49.392 ThaliTest[1313:b207] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:50.444 ThaliTest[1313:b207] client session: connected
2015-12-04 09:51:50.446 ThaliTest[1313:b207] client session: stateChange:1->2 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:50.448 ThaliTest[1313:b207] client session: fireConnectCallback: Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:51:50.449 ThaliTest[1313:b207] jxcore: connect: success
,2015-12-04T08:51:50.450Z SendDataConnector.js: CLIENT connected to 65130, error: null
2015-12-04T08:51:50.451Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:50.452 ThaliTest[1313:60b] client: relay established
,2015-12-04 09:51:50.452 ThaliTest[1313:60b] client: new accepted socket: 0x1ae67f90
,2015-12-04T08:51:50.463Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:51:50.977Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-04T08:51:51.001Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-04T08:51:51.047Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-04T08:51:51.094Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-04T08:51:51.094Z SendDataConnector.js: got all data for this round
,2015-12-04T08:51:51.096Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:51.096Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:51.097 ThaliTest[1313:6807] jxcore: disconnect
,2015-12-04 09:51:51.097 ThaliTest[1313:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:51.098 ThaliTest[1313:6807] client session: disconnect
2015-12-04 09:51:51.099 ThaliTest[1313:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:51.101 ThaliTest[1313:6807] jxcore: disconnect: success
2015-12-04T08:51:51.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6975.MZRWVw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9194","time":118808,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7135.+FivAg==","time":3348,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT7213.N3FSeg==","time":111226,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT6975.MZRWVw==","time":3611,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRe,ceived":100000}]}
,sendList : 100% : 3611 ms, 99% : 3611 ms, 95 : 3611 ms, 90% : 3611 ms.
,Result count 2, range 3348 ms to  3611 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT7213.N3FSeg==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-04T08:51:51.120Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:51:51.120Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-04 09:51:52.324 ThaliTest[1313:6807] jxcore: stopBroadcasting
,2015-12-04 09:51:52.325 ThaliTest[1313:6807] THEMultipeerSession stopping peer
,2015-12-04 09:51:52.326 ThaliTest[1313:6807] multipeer session: stop timer
,2015-12-04 09:51:52.326 ThaliTest[1313:6807] server session: disconnect
2015-12-04 09:51:52.327 ThaliTest[1313:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:52.332 ThaliTest[1313:6807] server session: disconnect
,2015-12-04 09:51:52.333 ThaliTest[1313:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:52.339 ThaliTest[1313:6807] server session: disconnect
,2015-12-04 09:51:52.340 ThaliTest[1313:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:52.347 ThaliTest[1313:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-04T08:51:52.366Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:52.367Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:52.368Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:52.369Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT7135.+FivAg==\",\"time\":3348,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dat,aAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT6975.MZRWVw==\",\"time\":3611,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iph,one5s-1_PT7213.N3FSeg==\",\"time\":111226,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS,_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called
DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
The Coordinator has closed!
stop tests now !
turning Radios off
Toggling rad,ios to false
Warning: iOS does not suppor,t ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled

```
