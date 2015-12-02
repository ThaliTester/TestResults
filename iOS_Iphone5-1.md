#### Test 52445159d291820_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D580B413-5ECD-46BB-A214-EB56254A2038/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D580B413-5ECD-46BB-A214-EB56254A2038/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/A3F65178-6AD7-4E11-9B38-40BCE99EE10C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59951"
,(lldb)     command script import "/tmp/D580B413-5ECD-46BB-A214-EB56254A2038/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 21:06:59.624 ThaliTest[1155:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 21:06:59.628 ThaliTest[1155:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-02 21:06:59.635 ThaliTest[1155:60b] Unlimited access to network resources
,2015-12-02 21:06:59.642 ThaliTest[1155:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 21:07:10.358 ThaliTest[1155:60b] Resetting plugins due to page load.
,2015-12-02 21:07:11.232 ThaliTest[1155:60b] Finished load of: file:///var/mobile/Applications/A3F65178-6AD7-4E11-9B38-40BCE99EE10C/ThaliTest.app/www/index.html
,2015-12-02 21:07:11.412 ThaliTest[1155:60b] JXcore Cordova plugin initializing
,2015-12-02 21:07:11.413 ThaliTest[1155:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone5-1_PT3314
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 60927
,2015-12-02 21:12:26.002 ThaliTest[1155:6807] jxcore: startBroadcasting
,2015-12-02 21:12:26.013 ThaliTest[1155:6807] server: starting Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:26.016 ThaliTest[1155:6807] multipeer session: start timer: 0x1ad22da0
2015-12-02 21:12:26.018 ThaliTest[1155:6807] THEMultipeerSession initial,ized peer Apple-Iphone5-1_PT3314
2015-12-02 21:12:26.020 ThaliTest[1155:6807] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-02T20:12:26.023Z SendDataTCPServer.js: TCP/IP server is bound to port: 60927
,2015-12-02 21:12:27.245 ThaliTest[1155:60b] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT369.LHPK5g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:12:27.250Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:12:27.250Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02T20:12:27.250Z SendDataConnector.js: do connect now
,2015-12-02 21:12:27.251 ThaliTest[1155:6807] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:27.252 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:12:27.253 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:28.286 ThaliTest[1155:60b] multipeer session: reset timer
,2015-12-02 21:12:28.288 ThaliTest[1155:60b] multipeer session: stop timer
,2015-12-02 21:12:28.289 ThaliTest[1155:60b] multipeer session: start timer: 0x1ad22da0
,2015-12-02 21:12:28.290 ThaliTest[1155:60b] server session: connect
,2015-12-02 21:12:28.290 ThaliTest[1155:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02 21:12:28.294 ThaliTest[1155:60b] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:12:28.368 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:29.213 ThaliTest[1155:60b] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:29.686 ThaliTest[1155:60b] multipeer session: reset timer
,2015-12-02 21:12:29.687 ThaliTest[1155:60b] multipeer session: stop timer
,2015-12-02 21:12:29.687 ThaliTest[1155:60b] multipeer session: start timer: 0x1ad22da0
,2015-12-02 21:12:29.688 ThaliTest[1155:60b] server session: connect
2015-12-02 21:12:29.689 ThaliTest[1155:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:29.693 ThaliTest[1155:60b] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:30.347 ThaliTest[1155:8103] client session: connected
,2015-12-02 21:12:30.349 ThaliTest[1155:8103] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:30.357 ThaliTest[1155:770f] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:12:30.358 ThaliTest[1155:770f] jxcore: connect: success
,2015-12-02T20:12:30.360Z SendDataConnector.js: CLIENT connected to 60930, error: null
,2015-12-02T20:12:30.360Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:30.361 ThaliTest[1155:60b] client: relay established
2015-12-02 21:12:30.362 ThaliTest[1155:60b] client: new accepted socket: 0x1ad15110
,2015-12-02T20:12:30.375Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02 21:12:30.717 ThaliTest[1155:770f] server session: connected
2015-12-02 21:12:30.717 ThaliTest[1155:770f] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02 21:12:30.741 ThaliTest[1155:60b] server relay: connected (to port: 60927)
,2015-12-02T20:12:30.875Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:30.942Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-02T20:12:30.965Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-02T20:12:30.979Z SendDataTCPServer.js: TCP/IP server has received 56088 bytes of data
,2015-12-02T20:12:30.994Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-02T20:12:31.007Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T20:12:31.009Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-02T20:12:31.345Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T20:12:31.380Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02 21:12:31.396 ThaliTest[1155:2223] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02T20:12:31.471Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T20:12:31.471Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:31.474Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:31.474Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:31.475 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:12:31.476 ThaliTest[1155:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:12:31.477 ThaliTest[1155:6807] client session: disconnect
,2015-12-02 21:12:31.477 ThaliTest[1155:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:31.479 ThaliTest[1155:6807] jxcore: disconnect: success
,2015-12-02T20:12:31.481Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5g==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:31.483Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:12:31.483Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:12:31.483Z SendDataConnector.js: do connect now
,2015-12-02 21:12:31.484 ThaliTest[1155:6807] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:31.485 ThaliTest[1155:6807] client session: connect
2015-12-02 21:12:31.485 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:31.815 ThaliTest[1155:7813] server session: connected
,2015-12-02 21:12:31.816 ThaliTest[1155:7813] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02T20:12:31.827Z SendDataTCPServer.js: TCP/IP server connected
2015-12-02 21:12:31.826 ThaliTest[1155:60b] server relay: connected (to port: 60927)
,2015-12-02T20:12:32.314Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-02T20:12:32.326Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-02T20:12:32.351Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-02T20:12:32.364Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-02T20:12:32.379Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-02T20:12:32.393Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:32.423 ThaliTest[1155:2223] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:32.943 ThaliTest[1155:60b] multipeer session: reset timer
,2015-12-02 21:12:32.944 ThaliTest[1155:60b] multipeer session: stop timer
2015-12-02 21:12:32.945 ThaliTest[1155:60b] multipeer session: start timer: 0x1ad22da0
,2015-12-02 21:12:32.946 ThaliTest[1155:60b] server session: connect
,2015-12-02 21:12:32.946 ThaliTest[1155:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT3258
,2015-12-02 21:12:32.950 ThaliTest[1155:60b] server: accepting invitation Apple-Iphone6-1_PT3258
,2015-12-02 21:12:33.983 ThaliTest[1155:8103] client session: connected
,2015-12-02 21:12:33.984 ThaliTest[1155:8103] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:33.994 ThaliTest[1155:770f] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:33.997 ThaliTest[1155:770f] jxcore: connect: success
,2015-12-02T20:12:33.999Z SendDataConnector.js: CLIENT connected to 60935, error: null
2015-12-02T20:12:33.999Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:34.000 ThaliTest[1155:60b] client: relay established
2015-12-02 21:12:34.002 ThaliTest[1155:60b] client: new accepted socket: 0x1aea5660
,2015-12-02T20:12:34.012Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:34.532Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T20:12:34.567Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:12:34.580Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T20:12:34.593Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T20:12:34.605Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02 21:12:35.115 ThaliTest[1155:2223] server session: connected
,2015-12-02 21:12:35.117 ThaliTest[1155:2223] server session: stateChange:1->2 Apple-Iphone6-1_PT3258
,2015-12-02 21:12:35.130 ThaliTest[1155:60b] server relay: connected (to port: 60927)
,2015-12-02T20:12:35.135Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:35.513Z SendDataTCPServer.js: TCP/IP server has received 21048 bytes of data
,2015-12-02T20:12:35.526Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-02T20:12:35.541Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-02T20:12:35.554Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-02T20:12:35.568Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:35.603 ThaliTest[1155:2223] server session: not connected Apple-Iphone6-1_PT3258
,2015-12-02T20:12:44.609Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:12:44.610Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:44.611Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:44.611Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:12:44.612Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:12:44.613 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:12:44.614 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:12:44.615 ThaliTest[1155:60b] client relay: 0x1aea5660 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ad06890 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:12:44.615 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:44.616 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:44.616 ThaliTest[1155:60b] client session: disconnect
,2015-12-02 21:12:44.617 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:44.618 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:49.613Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:49.614Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:54.623 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:12:54.625 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:12:54.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:12:54.627Z SendDataConnector.js: Connect (retry coun,t 1) to peer Apple-Iphone6-1_PT3258.XmE3ag== with availability status: true
2015-12-02T20:12:54.627Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:54.627Z SendDataConnector.js: do connect now
,2015-12-02 21:12:54.628 ThaliTest[1155:6807] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:54.629 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:12:54.629 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:57.468 ThaliTest[1155:770f] client session: connected
,2015-12-02 21:12:57.469 ThaliTest[1155:770f] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:57.477 ThaliTest[1155:2223] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:57.478 ThaliTest[1155:2223] jxcore: connect: success
,2015-12-02T20:12:57.479Z SendDataConnector.js: CLIENT connected to 60940, error: null
,2015-12-02T20:12:57.479Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:57.481 ThaliTest[1155:60b] client: relay established
2015-12-02 21:12:57.482 ThaliTest[1155:60b] client: new accepted socket: 0x1aea83f0
,2015-12-02T20:12:57.493Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:13:02.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02T20:13:07.622Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:07.623Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:07.623Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:07.624Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:07.625Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:07.627 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:13:07.627 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:13:07.628 ThaliTest[1155:60b] client relay: 0x1aea83f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ace2b60 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:13:07.629 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:07.629 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:07.630 ThaliTest[1155:60b] client session: disconnect
,2015-12-02 21:13:07.630 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:07.632 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:13:12.631Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:13:12.632Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:17.633 ThaliTest[1155:6807] jxcore: disconnect
2015-12-02 21:13:17.634 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:13:17.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
2,015-12-02T20:13:17.635Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3258.XmE3ag== with availability status: true
2015-12-02T20:13:17.636Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:13:17.636Z SendDataConnector.js: do connect now
,2015-12-02 21:13:17.636 ThaliTest[1155:6807] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:13:17.637 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:13:17.638 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:20.657 ThaliTest[1155:8737] client session: connected
,2015-12-02 21:13:20.659 ThaliTest[1155:8737] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:20.667 ThaliTest[1155:8737] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:20.668 ThaliTest[1155:8737] jxcore: connect: success
,2015-12-02T20:13:20.669Z SendDataConnector.js: CLIENT connected to 60946, error: null
2015-12-02T20:13:20.669Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:20.671 ThaliTest[1155:60b] client: relay established
2015-12-02 21:13:20.671 ThaliTest[1155:60b] client: new accepted socket: 0x1ac193d0
,2015-12-02T20:13:20.684Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:13:30.746Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:30.746Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:30.747Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:30.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:30.748Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:30.750 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:13:30.751 ThaliTest[1155:60b] client relay: socket disconnected
2015-12-02 21:13:30.751 ThaliTest[1155:60b] client relay: 0x1ac193d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1aa00dc0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:13:30.752 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:13:30.753 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:13:30.753 ThaliTest[1155:6,0b] client session: disconnect
2015-12-02 21:13:30.754 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:30.755 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:32.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02 21:13:32.959 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:32.960 ThaliTest[1155:60b] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:13:32.961 ThaliTest[1155:60b] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:13:35.758Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:13:35.759Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:40.765 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:13:40.766 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:13:40.768Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:13:40.768Z SendDataConnector.js: Connect (retry coun,t 3) to peer Apple-Iphone6-1_PT3258.XmE3ag== with availability status: true
2015-12-02T20:13:40.768Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:13:40.768Z SendDataConnector.js: do connect now
,2015-12-02 21:13:40.769 ThaliTest[1155:6807] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:40.769 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:13:40.770 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:43.271 ThaliTest[1155:2223] client session: connected
,2015-12-02 21:13:43.272 ThaliTest[1155:2223] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:43.281 ThaliTest[1155:2223] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:13:43.282 ThaliTest[1155:2223] jxcore: connect: success
,2015-12-02T20:13:43.283Z SendDataConnector.js: CLIENT connected to 60951, error: null
2015-12-02T20:13:43.283Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:43.284 ThaliTest[1155:60b] client: relay established
2015-12-02 21:13:43.285 ThaliTest[1155:60b] client: new accepted socket: 0x1ac193d0
,2015-12-02T20:13:43.296Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:13:53.354Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:13:53.354Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:13:53.355Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:53.356Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:53.356Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:53.358 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:13:53.359 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:13:53.359 ThaliTest[1155:60b] client relay: 0x1ac193d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1acccf20 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:13:53.360 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:53.361 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:53.361 ThaliTest[1155:60b] client session: disconnect
2015-12-02 21:13:53.362 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:13:54.231 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:13:58.357Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:13:58.358Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:02.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02 21:14:02.957 ThaliTest[1155:60b] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:14:02.959 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:03.120 ThaliTest[1155:60b] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:03.366 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:14:03.367 ThaliTest[1155:6807] jxcore: disconnect: fail
,2015-12-02T20:14:03.369Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:14:03.370Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3258.XmE3ag== with availability status: true
,2015-12-02T20:14:03.370Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:14:03.370Z SendDataConnector.js: do connect now
,2015-12-02 21:14:03.371 ThaliTest[1155:6807] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:03.371 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:14:03.372 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:05.751 ThaliTest[1155:873b] client session: connected
,2015-12-02 21:14:05.752 ThaliTest[1155:873b] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:05.760 ThaliTest[1155:b807] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:05.762 ThaliTest[1155:b807] jxcore: connect: success
,2015-12-02T20:14:05.763Z SendDataConnector.js: CLIENT connected to 60956, error: null
2015-12-02T20:14:05.763Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:14:05.765 ThaliTest[1155:60b] client: relay established
2015-12-02 21:14:05.766 ThaliTest[1155:60b] client: new accepted socket: 0x1aea8680
,2015-12-02T20:14:05.777Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:14:15.833Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:14:15.834Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:14:15.834Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:15.836Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:14:15.836Z SendDataConnector.js: Stop data retrieving timer
2015-12-02T20:14:15.836Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:14:15.837 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:14:15.838 ThaliTest[1155:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:15.839 ThaliTest[1155:6807] client session: disconnect
,2015-12-02 21:14:15.839 ThaliTest[1155:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:14:15.842 ThaliTest[1155:6807] jxcore: disconnect: success
2015-12-02T20:14:15.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:15.844Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:15.844Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:15.844Z SendDataConnector.js: do connect now
,2015-12-02 21:14:15.845 ThaliTest[1155:6807] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:15.845 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:14:15.846 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:14:15.850Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:14:18.721 ThaliTest[1155:b807] client session: connected
,2015-12-02 21:14:18.722 ThaliTest[1155:b807] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:18.732 ThaliTest[1155:873f] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:18.733 ThaliTest[1155:873f] jxcore: connect: success
,2015-12-02T20:14:18.735Z SendDataConnector.js: CLIENT connected to 60961, error: null
,2015-12-02T20:14:18.735Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:14:18.737 ThaliTest[1155:60b] client: relay established
,2015-12-02 21:14:18.737 ThaliTest[1155:60b] client: new accepted socket: 0x1a979bf0
,2015-12-02T20:14:18.750Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:14:19.256Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T20:14:19.269Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T20:14:19.291Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:14:19.326Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T20:14:19.351Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T20:14:29.360Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:14:29.361Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:29.362Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:29.362Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:14:29.363Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:14:29.364 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:14:29.365 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:14:29.366 ThaliTest[1155:60b] client relay: 0x1a979bf0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ab95f80 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:14:29.367 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:29.367 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:29.368 ThaliTest[1155:60b] client session: disconnect
2015-12-02 21:14:29.369 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:29.370 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:32.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02T20:14:34.372Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:14:34.372Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:39.382 ThaliTest[1155:6807] jxcore: disconnect
2015-12-02 21:14:39.384 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:14:39.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:14:39.386Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
2015-12-02T20:14:39.386Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:39.386Z SendDataConnector.js: do connect now
,2015-12-02 21:14:39.386 ThaliTest[1155:6807] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:39.387 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:14:39.388 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:41.935 ThaliTest[1155:8a47] client session: connected
,2015-12-02 21:14:41.936 ThaliTest[1155:8a47] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:41.946 ThaliTest[1155:8a47] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:41.947 ThaliTest[1155:8a47] jxcore: connect: success
,2015-12-02T20:14:41.948Z SendDataConnector.js: CLIENT connected to 60966, error: null
2015-12-02T20:14:41.949Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:14:41.950 ThaliTest[1155:60b] client: relay established
2015-12-02 21:14:41.950 ThaliTest[1155:60b] client: new accepted socket: 0x1acade10
,2015-12-02T20:14:41.964Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:14:52.017Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:14:52.018Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:14:52.018Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:52.018Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-02T20:14:52.019Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:14:52.020 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:14:52.021 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:14:52.022 ThaliTest[1155:60b] client relay: 0x1acade10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1abd2430 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:14:52.023 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:52.023 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:52.024 ThaliTest[1155:60b] client session: disconnect
,2015-12-02 21:14:52.024 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:52.026 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:14:57.025Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:14:57.026Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:02.035 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:15:02.036 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:15:02.038Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:15:02.039Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
2015-12-02T20:15:02.039Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015,-12-02T20:15:02.039Z SendDataConnector.js: do connect now
,2015-12-02 21:15:02.040 ThaliTest[1155:6807] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:02.040 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:15:02.041 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:02.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02 21:15:02.957 ThaliTest[1155:60b] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:02.959 ThaliTest[1155:60b] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:15:02.960 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:15:04.683 ThaliTest[1155:b80b] client session: connected
2015-12-02 21:15:04.685 ThaliTest[1155:b80b] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:04.693 ThaliTest[1155:b80b] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:15:04.694 ThaliTest[1155:b80b] jxcore: connect: success
,2015-12-02T20:15:04.696Z SendDataConnector.js: CLIENT connected to 60971, error: null
2015-12-02T20:15:04.696Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:15:04.697 ThaliTest[1155:60b] client: relay established
2015-12-02 21:15:04.698 ThaliTest[1155:60b] client: new accepted socket: 0x1aadf150
,2015-12-02T20:15:04.710Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:15:12.729 ThaliTest[1155:60b] client: lost peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:15:12.730 ThaliTest[1155:60b] client session: onPeerLost: Apple-Iphone6-1_PT3258.XmE3ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 21:15:14.253 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
,2015-12-02T20:15:14.763Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:15:14.763Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:15:14.764Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:15:14.764Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:15:14.765Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:15:14.767 ThaliTest[1155:60b] client: socket closed
,2015-12-02 21:15:14.767 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:15:14.768 ThaliTest[1155:60b] client relay: 0x1aadf150 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1acc2420 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:15:14.769 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:14.769 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:15:14.770 ThaliTest[1155:60b] client session: disconnect
,2015-12-02 21:15:14.771 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:14.772 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:15:19.772Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:15:19.772Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:24.782 ThaliTest[1155:6807] jxcore: disconnect
2015-12-02 21:15:24.783 ThaliTest[1155:6807] jxcore: disconnect: fail
,2015-12-02T20:15:24.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:15:24.785Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status,: true
2015-12-02T20:15:24.786Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:15:24.786Z SendDataConnector.js: do connect now
,2015-12-02 21:15:24.786 ThaliTest[1155:6807] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:24.787 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:15:24.788 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:27.891 ThaliTest[1155:7c1b] client session: connected
,2015-12-02 21:15:27.893 ThaliTest[1155:7c1b] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:27.901 ThaliTest[1155:8f4b] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:15:27.903 ThaliTest[1155:8f4b] jxcore: connect: success
,2015-12-02T20:15:27.904Z SendDataConnector.js: CLIENT connected to 60976, error: null
,2015-12-02T20:15:27.905Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:15:27.906 ThaliTest[1155:60b] client: relay established
2015-12-02 21:15:27.907 ThaliTest[1155:60b] client: new accepted socket: 0x1ad6bb10
,2015-12-02T20:15:27.918Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:15:32.947 ThaliTest[1155:60b] multipeer session: restart
,2015-12-02 21:15:32.957 ThaliTest[1155:60b] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:32.959 ThaliTest[1155:60b] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:15:32.960 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:15:37.972Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:15:37.972Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:15:37.974Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:15:37.974Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:15:37.975Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:15:37.976 ThaliTest[1155:60b] client: socket closed
2015-12-02 21:15:37.977 ThaliTest[1155:60b] client relay: socket disconnected
,2015-12-02 21:15:37.978 ThaliTest[1155:60b] client relay: 0x1ad6bb10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1aa22ee0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-02 21:15:37.978 ThaliTest[1155:60b] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:37.979 ThaliTest[1155:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:15:37.980 ThaliTest[1155:60b] client session: disconnect
,2015-12-02 21:15:37.980 ThaliTest[1155:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:37.982 ThaliTest[1155:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:42.606 ThaliTest[1155:60b] client: lost peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:15:42.608 ThaliTest[1155:60b] client session: onPeerLost: Apple-Iphone6-1_PT3258.XmE3ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":false}]
,2015-12-02T20:15:42.976Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:15:42.976Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:47.274 ThaliTest[1155:60b] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 21:15:47.983 ThaliTest[1155:6807] jxcore: disconnect
,2015-12-02 21:15:47.985 ThaliTest[1155:6807] jxcore: disconnect: fail
2015-12-02T20:15:47.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:15:47.987Z SendDataConnector.js: Connect (retry cou,nt 4) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
,2015-12-02T20:15:47.987Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:15:47.987Z SendDataConnector.js: do connect now
,2015-12-02 21:15:47.987 ThaliTest[1155:6807] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:47.988 ThaliTest[1155:6807] client session: connect
,2015-12-02 21:15:47.989 ThaliTest[1155:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:52.004 ThaliTest[1155:ac2b] client session: connected
2015-12-02 21:15:52.005 ThaliTest[1155:ac2b] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:52.014 ThaliTest[1155:7c1b] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:52.015 ThaliTest[1155:7c1b] jxcore: connect: success
,2015-12-02T20:15:52.017Z SendDataConnector.js: CLIENT connected to 60981, error: null
2015-12-02T20:15:52.017Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:15:52.018 ThaliTest[1155:60b] client: relay established
,2015-12-02 21:15:52.019 ThaliTest[1155:60b] client: new accepted socket: 0x1ac08d60
,2015-12-02T20:15:52.031Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:16:02.087Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:16:02.087Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:16:02.088Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:16:02.090Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:16:02.091Z SendDataConnector.js: Stop data retrieving timer
2015-12-02T20:16:02.091Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:16:02.091 ThaliTest[1155:6807] jxcore: disconnect
2015-12-02 21:16:02.092 ThaliTest[1155:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:16:02.093 ThaliTest[1155:6807] client session: disconnect
,2015-12-02 21:16:02.093 ThaliTest[1155:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:16:02.095 ThaliTest[1155:6807] jxcore: disconnect: success
2015-12-02T20:16:02.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT3314","time":216104,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT369.LHPK5g==","time":4223,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_,PT3258.XmE3ag==","time":104352,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","time":106245,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100,000,"dataReceived":90000}]}
,sendList : 100% : 4223 ms, 99% : 4223 ms, 95 : 4223 ms, 90% : 4223 ms.
Result count 1, range 4223 ms to  4223 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT3258.XmE3ag==, Tried : 5
- Peer ID : Apple-Iphone5s-1_,PT4399.Q1E7LQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
2015-12-02T20:16:02.104Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:16:02.104Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:16:02.105Z SendDataConnector.js: ----------------- closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
testSendData stopped
,2015-12-02 21:16:02.387 ThaliTest[1155:6807] jxcore: stopBroadcasting
,2015-12-02 21:16:02.388 ThaliTest[1155:6807] THEMultipeerSession stopping peer
,2015-12-02 21:16:02.388 ThaliTest[1155:6807] multipeer session: stop timer
,2015-12-02 21:16:02.389 ThaliTest[1155:6807] server session: disconnect
,2015-12-02 21:16:02.391 ThaliTest[1155:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02 21:16:02.396 ThaliTest[1155:6807] server session: disconnect
,2015-12-02 21:16:02.397 ThaliTest[1155:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT3258
,2015-12-02 21:16:02.403 ThaliTest[1155:6807] server session: disconnect
2015-12-02 21:16:02.405 ThaliTest[1155:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT369
,2015-12-02 21:16:02.412 ThaliTest[1155:6807] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-02T20:16:02.431Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.432Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.433Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:02.434Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT369.LHPK5g==\",\"time\":4223,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],,\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT3258.XmE3ag==\",\"time\":104352,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-Iphone5s-1_PT4399.Q1E7LQ==\",\"time,\":106245,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
