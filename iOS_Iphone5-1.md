#### Test 522773652a05488_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5587B323-E65E-4B9B-A9BC-9D946DF0A5D8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5587B323-E65E-4B9B-A9BC-9D946DF0A5D8/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/7B6BA717-23DA-455E-A91B-A9613369546A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58614"
,(lldb)     command script import "/tmp/5587B323-E65E-4B9B-A9BC-9D946DF0A5D8/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 17:21:03.604 ThaliTest[1042:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-01 17:21:03.607 ThaliTest[1042:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-01 17:21:03.614 ThaliTest[1042:60b] Unlimited access to network resources
,2015-12-01 17:21:03.622 ThaliTest[1042:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 17:21:14.480 ThaliTest[1042:60b] Resetting plugins due to page load.
,2015-12-01 17:21:15.352 ThaliTest[1042:60b] Finished load of: file:///var/mobile/Applications/7B6BA717-23DA-455E-A91B-A9613369546A/ThaliTest.app/www/index.html
,2015-12-01 17:21:15.534 ThaliTest[1042:60b] JXcore Cordova plugin initializing
,2015-12-01 17:21:15.536 ThaliTest[1042:6907] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT6379
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
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 57515
,2015-12-01 17:26:57.562 ThaliTest[1042:6907] jxcore: startBroadcasting
,2015-12-01 17:26:57.572 ThaliTest[1042:6907] server: starting Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:26:57.574 ThaliTest[1042:6907] multipeer session: start timer: 0x1de889c0
2015-12-01 17:26:57.574 ThaliTest[1042:6907] THEMultipeerSession initial,ized peer Apple-Iphone5-1_PT6379
2015-12-01 17:26:57.575 ThaliTest[1042:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-01T16:26:57.578Z SendDataTCPServer.js: TCP/IP server is bound to port: 57515
,2015-12-01 17:26:58.056 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:58.060Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:58.060Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:26:58.061Z SendDataConnector.js: do connect now
,2015-12-01 17:26:58.061 ThaliTest[1042:6907] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:26:58.062 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:26:58.062 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:26:58.367 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:26:58.984 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:27:00.653 ThaliTest[1042:751b] client session: connected
,2015-12-01 17:27:00.654 ThaliTest[1042:751b] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:00.856 ThaliTest[1042:1617] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:00.857 ThaliTest[1042:1617] jxcore: connect: success
,2015-12-01T16:27:00.858Z SendDataConnector.js: CLIENT connected to 57518, error: null
2015-12-01T16:27:00.859Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:00.860 ThaliTest[1042:60b] client: relay established
2015-12-01 17:27:00.861 ThaliTest[1042:60b] client: new accepted socket: 0x1de8e7d0
,2015-12-01T16:27:00.875Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:27:01.439Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T16:27:01.476Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01T16:27:01.500Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T16:27:01.514Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T16:27:01.527Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-01T16:27:01.540Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 17:27:02.147 ThaliTest[1042:60b] multipeer session: reset timer
2015-12-01 17:27:02.149 ThaliTest[1042:60b] multipeer session: stop timer
,2015-12-01 17:27:02.149 ThaliTest[1042:60b] multipeer session: start timer: 0x1de889c0
,2015-12-01 17:27:02.150 ThaliTest[1042:60b] server session: connect
,2015-12-01 17:27:02.151 ThaliTest[1042:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT4380
,2015-12-01 17:27:02.154 ThaliTest[1042:60b] server: accepting invitation Apple-Iphone5s-1_PT4380
,2015-12-01 17:27:04.575 ThaliTest[1042:751b] server session: connected
2015-12-01 17:27:04.577 ThaliTest[1042:751b] server session: stateChange:1->2 Apple-Iphone5s-1_PT4380
,2015-12-01 17:27:04.581 ThaliTest[1042:60b] server relay: connected (to port: 57515)
2015-12-01T16:27:04.583Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:04.996Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2015-12-01T16:27:05.011Z SendDataTCPServer.js: TCP/IP server has received 54324 bytes of data
,2015-12-01T16:27:05.023Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:27:05.047 ThaliTest[1042:751b] server session: not connected Apple-Iphone5s-1_PT4380
,2015-12-01T16:27:11.546Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:11.547Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:11.549Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:11.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:11.550Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:11.551 ThaliTest[1042:60b] client: socket closed
2015-12-01 17:27:11.551 ThaliTest[1042:60b] client relay: socket disconnected
,2015-12-01 17:27:11.552 ThaliTest[1042:60b] client relay: 0x1de8e7d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1de94960 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 17:27:11.553 ThaliTest[1042:60b] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:11.554 ThaliTest[1042:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:11.554 ThaliTest[1042:60b] client session: disconnect
,2015-12-01 17:27:11.555 ThaliTest[1042:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:11.556 ThaliTest[1042:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:16.553Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:16.554Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:21.554 ThaliTest[1042:6907] jxcore: disconnect
,2015-12-01 17:27:21.556 ThaliTest[1042:6907] jxcore: disconnect: fail
2015-12-01T16:27:21.558Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:21.558Z SendDataConnector.js: Connect (retry cou,nt 1) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:27:21.559Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:21.559Z SendDataConnector.js: do connect now
,2015-12-01 17:27:21.559 ThaliTest[1042:6907] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:21.560 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:27:21.561 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:24.011 ThaliTest[1042:751b] client session: connected
2015-12-01 17:27:24.013 ThaliTest[1042:751b] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:24.017 ThaliTest[1042:751b] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:24.017 ThaliTest[1042:751b] jxcore: connect: success
,2015-12-01T16:27:24.018Z SendDataConnector.js: CLIENT connected to 57523, error: null
2015-12-01T16:27:24.019Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:24.021 ThaliTest[1042:60b] client: relay established
2015-12-01 17:27:24.022 ThaliTest[1042:60b] client: new accepted socket: 0x1dea16f0
,2015-12-01T16:27:24.033Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 17:27:32.151 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01T16:27:34.099Z SendDataConnector.js: Receiving data timeout now
2015-12-01T16:27:34.100Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:34.100Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:34.101Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:34.101Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:34.103 ThaliTest[1042:60b] client: socket closed
2015-12-01 17:27:34.103 ThaliTest[1042:60b] client relay: socket disconnected
,2015-12-01 17:27:34.104 ThaliTest[1042:60b] client relay: 0x1dea16f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1df74c90 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 17:27:34.105 ThaliTest[1042:60b] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:34.105 ThaliTest[1042:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:34.106 ThaliTest[1042:60b] client session: disconnect
,2015-12-01 17:27:34.107 ThaliTest[1042:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:34.108 ThaliTest[1042:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:39.101Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:39.102Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:44.105 ThaliTest[1042:6907] jxcore: disconnect
2015-12-01 17:27:44.106 ThaliTest[1042:6907] jxcore: disconnect: fail
2015-12-01T16:27:44.107Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:44.108Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
,2015-12-01T16:27:44.108Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:44.108Z SendDataConnector.js: do connect now
2015-12-01 17:27:44.109 ThaliTest[1042:6907] jxcore: connect Apple-Iphone5s-1_PT4380.,ZyAdcQ==
,2015-12-01 17:27:44.109 ThaliTest[1042:6907] client session: connect
2015-12-01 17:27:44.110 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:47.578 ThaliTest[1042:9f13] client session: connected
2015-12-01 17:27:47.581 ThaliTest[1042:9f13] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:47.583 ThaliTest[1042:9f13] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:47.584 ThaliTest[1042:9f13] jxcore: connect: success
,2015-12-01T16:27:47.585Z SendDataConnector.js: CLIENT connected to 57529, error: null
2015-12-01T16:27:47.586Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:47.587 ThaliTest[1042:60b] client: relay established
,2015-12-01 17:27:47.589 ThaliTest[1042:60b] client: new accepted socket: 0x1df677d0
,2015-12-01T16:27:47.599Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:27:57.653Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:57.654Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:57.655Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:57.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-01T16:27:57.656Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:57.657 ThaliTest[1042:60b] client: socket closed
,2015-12-01 17:27:57.658 ThaliTest[1042:60b] client relay: socket disconnected
,2015-12-01 17:27:57.659 ThaliTest[1042:60b] client relay: 0x1df677d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1de9bcd0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 17:27:57.659 ThaliTest[1042:60b] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:57.660 ThaliTest[1042:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:57.661 ThaliTest[1042:60b] client session: disconnect
,2015-12-01 17:27:57.661 ThaliTest[1042:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:57.663 ThaliTest[1042:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:02.151 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:28:02.259 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:02.260 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:02.261 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:28:02.666Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:02.666Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:07.667 ThaliTest[1042:6907] jxcore: disconnect
,2015-12-01 17:28:07.669 ThaliTest[1042:6907] jxcore: disconnect: fail
2015-12-01T16:28:07.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:07.671Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:28:07.671Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:07.671Z SendDataConnector.js: do connect now
,2015-12-01 17:28:07.672 ThaliTest[1042:6907] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:07.673 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:28:07.673 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:10.695 ThaliTest[1042:9f13] client session: connected
2015-12-01 17:28:10.698 ThaliTest[1042:9f13] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:10.700 ThaliTest[1042:9f13] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:10.701 ThaliTest[1042:9f13] jxcore: connect: success
,2015-12-01T16:28:10.702Z SendDataConnector.js: CLIENT connected to 57534, error: null
2015-12-01T16:28:10.702Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:10.704 ThaliTest[1042:60b] client: relay established
2015-12-01 17:28:10.705 ThaliTest[1042:60b] client: new accepted socket: 0x1de981a0
,2015-12-01T16:28:10.717Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:28:20.779Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:28:20.779Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:28:20.780Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:20.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-01T16:28:20.781Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:28:20.783 ThaliTest[1042:60b] client: socket closed
2015-12-01 17:28:20.784 ThaliTest[1042:60b] client relay: socket disconnected
2015-12-01 17:28:20.784 ThaliTest[1042:60b] client relay: 0x1de981a0 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1df81830 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 17:28:20.785 ThaliTest[1042:60b] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:20.785 ThaliTest[1042:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:20.786 ThaliTest[1042:60b] client session: disconnect
2015-12-01 17:28:20.787 ThaliTest[1042:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:20.788 ThaliTest[1042:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:25.790Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:25.791Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:30.799 ThaliTest[1042:6907] jxcore: disconnect
2015-12-01 17:28:30.800 ThaliTest[1042:6907] jxcore: disconnect: fail
,2015-12-01T16:28:30.802Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:30.802Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status,: true
2015-12-01T16:28:30.803Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:30.803Z SendDataConnector.js: do connect now
,2015-12-01 17:28:30.803 ThaliTest[1042:6907] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:30.804 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:28:30.804 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:31.468 ThaliTest[1042:60b] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:28:31.470 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:28:31.470 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:28:32.151 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:28:32.162 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:28:32.164 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:32.165 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:33.175 ThaliTest[1042:9c17] client session: connected
2015-12-01 17:28:33.176 ThaliTest[1042:9c17] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:33.179 ThaliTest[1042:9c17] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:33.180 ThaliTest[1042:9c17] jxcore: connect: success
,2015-12-01T16:28:33.181Z SendDataConnector.js: CLIENT connected to 57539, error: null
2015-12-01T16:28:33.182Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:33.184 ThaliTest[1042:60b] client: relay established
,2015-12-01 17:28:33.185 ThaliTest[1042:60b] client: new accepted socket: 0x1df8a5d0
,2015-12-01T16:28:33.197Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01T16:28:43.260Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:28:43.261Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:28:43.261Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:43.264Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:43.264Z SendDataConnector.js: Stop data retrieving timer
2015-12-01T16:28:43.264Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:43.265 ThaliTest[1042:6907] jxcore: disconnect
2015-12-01 17:28:43.266 ThaliTest[1042:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:43.266 ThaliTest[1042:6907] client session: disconnect
2015-12-01 17:28:43.267 ThaliTest[1042:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:43.269 ThaliTest[1042:6907] jxcore: disconnect: success
,2015-12-01T16:28:43.270Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,---- round done--------
device[2]: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:28:43.274Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:28:43.274Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:28:43.274Z SendDataConnector.js: do connect now
,2015-12-01 17:28:43.274 ThaliTest[1042:6907] jxcore: connect Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:43.275 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:28:43.276 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:28:43.282Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:28:44.738 ThaliTest[1042:60b] multipeer session: reset timer
,2015-12-01 17:28:44.739 ThaliTest[1042:60b] multipeer session: stop timer
,2015-12-01 17:28:44.740 ThaliTest[1042:60b] multipeer session: start timer: 0x1de889c0
,2015-12-01 17:28:44.741 ThaliTest[1042:60b] server session: connect
,2015-12-01 17:28:44.742 ThaliTest[1042:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7863
,2015-12-01 17:28:44.745 ThaliTest[1042:60b] server: accepting invitation Apple-IpadAir2-1_PT7863
,2015-12-01 17:28:46.810 ThaliTest[1042:8637] client session: connected
2015-12-01 17:28:46.811 ThaliTest[1042:8637] client session: stateChange:1->2 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:46.812 ThaliTest[1042:8637] client session: fireConnectCallback: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:28:46.813 ThaliTest[1042:8637] jxcore: connect: success
,2015-12-01T16:28:46.815Z SendDataConnector.js: CLIENT connected to 57544, error: null
2015-12-01T16:28:46.815Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:46.817 ThaliTest[1042:60b] client: relay established
,2015-12-01 17:28:46.818 ThaliTest[1042:60b] client: new accepted socket: 0x1df8e300
,2015-12-01T16:28:46.829Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01 17:28:47.330 ThaliTest[1042:8637] server session: connected
2015-12-01 17:28:47.331 ThaliTest[1042:8637] server session: stateChange:1->2 Apple-IpadAir2-1_PT7863
,2015-12-01 17:28:47.335 ThaliTest[1042:60b] server relay: connected (to port: 57515)
,2015-12-01T16:28:47.382Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 17:28:47.413 ThaliTest[1042:60b] multipeer session: reset timer
2015-12-01 17:28:47.414 ThaliTest[1042:60b] multipeer session: stop timer
2015-12-01 17:28:47.415 ThaliTest[1042:60b] multipeer session: start timer: 0x1de889c0
2015-12-01 17:28:,47.416 ThaliTest[1042:60b] server session: connect
2015-12-01 17:28:47.416 ThaliTest[1042:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
2015-12-01T16:28:47.419Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01 17:28:47.422 ThaliTest[1042:60b] server: accepting invitation Apple-Iphone6-1_PT8196
,2015-12-01T16:28:47.432Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T16:28:47.446Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T16:28:47.723Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-01T16:28:47.736Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-01T16:28:47.761Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-01T16:28:47.797Z SendDataTCPServer.js: TCP/IP server has received 39278 bytes of data
,2015-12-01T16:28:47.809Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T16:28:47.902Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:28:47.902Z SendDataConnector.js: got all data for this round
,2015-12-01T16:28:47.903Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T16:28:47.904Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:47.905 ThaliTest[1042:6907] jxcore: disconnect
,2015-12-01 17:28:47.906 ThaliTest[1042:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:47.907 ThaliTest[1042:6907] client session: disconnect
,2015-12-01 17:28:47.908 ThaliTest[1042:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:47.949 ThaliTest[1042:8637] server session: not connected Apple-IpadAir2-1_PT7863
,2015-12-01 17:28:49.960 ThaliTest[1042:8637] server session: connected
,2015-12-01 17:28:49.962 ThaliTest[1042:8637] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:28:49.979 ThaliTest[1042:60b] server relay: connected (to port: 57515)
,2015-12-01 17:28:56.799 ThaliTest[1042:6907] jxcore: disconnect: success
2015-12-01T16:28:56.800Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8196.sJeqaQ==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01T16:28:56.801Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01T16:28:56.802Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:56.802Z SendDataConnector.js: do connect now
,2015-12-01 17:28:56.803 ThaliTest[1042:6907] jxcore: connect Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:28:56.804 ThaliTest[1042:6907] client session: connect
,2015-12-01 17:28:56.804 ThaliTest[1042:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01T16:28:56.823Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:56.835Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:28:57.707 ThaliTest[1042:8637] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:29:00.430 ThaliTest[1042:9c17] client session: connected
2015-12-01 17:29:00.432 ThaliTest[1042:9c17] client session: stateChange:1->2 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:00.435 ThaliTest[1042:9c17] client session: fireConnectCallback: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:00.436 ThaliTest[1042:9c17] jxcore: connect: success
,2015-12-01T16:29:00.437Z SendDataConnector.js: CLIENT connected to 57549, error: null
2015-12-01T16:29:00.437Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:29:00.440 ThaliTest[1042:60b] client: relay established
,2015-12-01 17:29:00.440 ThaliTest[1042:60b] client: new accepted socket: 0x1df600a0
,2015-12-01T16:29:00.450Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:29:00.969Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T16:29:01.004Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T16:29:01.359Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-01T16:29:01.372Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T16:29:01.385Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:29:01.386Z SendDataConnector.js: got all data for this round
,2015-12-01T16:29:01.387Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:29:01.388Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:29:01.389 ThaliTest[1042:6907] jxcore: disconnect
2015-12-01 17:29:01.389 ThaliTest[1042:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:01.390 ThaliTest[1042:6907] client session: disconnect
,2015-12-01 17:29:01.391 ThaliTest[1042:6907] client session: stateChange:2->0 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:01.393 ThaliTest[1042:6907] jxcore: disconnect: success
,2015-12-01T16:29:01.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7863.GmxszQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT6379","time":123845,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","time":105202,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Appl,e-Iphone6-1_PT8196.sJeqaQ==","time":4629,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7863.GmxszQ==","time":4584,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRe,ceived":100000}]}
sendList : 100% : 4629 ms, 99% : 4629 ms, 95 : 4629 ms, 90% : 4629 ms.
Result count 2, range 4584 ms to  4629 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT4380.ZyAdcQ==, Tried : 5
sendList, never tried peers count : 0 [0 %]
2015-12-01T16:29:01.404Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:29:01.404Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:29:17.416 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:29:17.426 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:29:17.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:17.668 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:40.190 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:29:40.191 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:29:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:29:47.427 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:29:48.115 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:29:48.617 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:53.292 ThaliTest[1042:60b] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:53.294 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:29:58.143 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:30:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:30:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:30:47.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:30:47.430 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:30:47.430 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:09.993 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:31:09.994 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:15.015 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:31:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:31:17.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:31:17.428 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:31:17.429 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:40.226 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:31:40.228 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:44.892 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:31:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:31:47.428 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:31:47.430 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:31:47.430 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:10.132 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:32:10.133 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:32:15.819 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:32:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:32:17.427 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:17.428 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:17.429 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:39.981 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:32:39.982 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:32:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:32:47.426 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:47.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:32:47.800 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:32:53.608 ThaliTest[1042:60b] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:32:53.609 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:32:59.323 ThaliTest[1042:60b] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:33:17.101 ThaliTest[1042:60b] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:33:17.103 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:33:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:33:17.426 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:33:17.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:33:40.259 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:33:40.261 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:33:46.136 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:33:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:33:47.426 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:33:47.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:34:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:34:18.471 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:34:18.537 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:34:40.015 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:34:40.017 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:34:44.816 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:34:47.416 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:35:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:35:17.427 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:35:17.428 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:35:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:35:47.427 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:35:47.428 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:36:10.174 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:36:10.175 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:36:14.840 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:36:17.416 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:36:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:36:47.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:36:47.501 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:37:10.456 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:37:10.457 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:37:15.124 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:37:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:37:17.426 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:37:17.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:37:39.948 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:37:39.950 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:37:44.998 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:37:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-01 17:38:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:38:17.425 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:38:18.677 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:38:37.101 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:38:37.103 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:38:40.219 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:38:40.220 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:38:42.313 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:38:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:38:47.426 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:39:10.006 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:39:10.007 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:39:15.156 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:39:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:39:17.425 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:39:20.548 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:39:37.024 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:39:37.025 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:39:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:40:06.657 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:40:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:40:17.427 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:40:17.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:40:37.045 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:40:37.047 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:40:40.123 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:40:40.124 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:40:44.796 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:40:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:40:47.426 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:00.181 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:06.230 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:41:06.231 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:41:06.298 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:41:06.300 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:41:06.954 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:10.001 ThaliTest[1042:60b] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:41:10.002 ThaliTest[1042:60b] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:14.287 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:41:16.920 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:41:17.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:41:47.427 ThaliTest[1042:60b] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:41:48.351 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:42:17.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:42:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:42:48.119 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:43:17.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 17:43:19.497 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:43:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:43:52.071 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:44:08.836 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:44:08.838 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:44:17.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:44:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:44:53.938 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:45:06.010 ThaliTest[1042:60b] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:45:06.012 ThaliTest[1042:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-01 17:45:11.772 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:45:17.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:45:47.417 ThaliTest[1042:60b] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:45:53.673 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:46:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:46:17.426 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:46:47.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:46:47.425 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 17:47:17.417 ThaliTest[1042:60b] multipeer session: restart
,2015-12-01 17:47:17.554 ThaliTest[1042:60b] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
