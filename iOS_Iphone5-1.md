#### Test 52383621712b264_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/4934553E-D897-491D-AAA4-E5D8B88B0CDF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4934553E-D897-491D-AAA4-E5D8B88B0CDF/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/C248B6C5-3AEC-4D60-A401-FF325A3013BC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60532"
,(lldb)     command script import "/tmp/4934553E-D897-491D-AAA4-E5D8B88B0CDF/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 15:40:18.307 ThaliTest[1216:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 15:40:18.311 ThaliTest[1216:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 15:40:18.318 ThaliTest[1216:60b] Unlimited access to network resources
,2015-12-03 15:40:18.325 ThaliTest[1216:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 15:40:29.071 ThaliTest[1216:60b] Resetting plugins due to page load.
,2015-12-03 15:40:29.947 ThaliTest[1216:60b] Finished load of: file:///var/mobile/Applications/C248B6C5-3AEC-4D60-A401-FF325A3013BC/ThaliTest.app/www/index.html
,2015-12-03 15:40:30.127 ThaliTest[1216:60b] JXcore Cordova plugin initializing
,2015-12-03 15:40:30.130 ThaliTest[1216:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone5-1_PT4165
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
serverPort is 63292
,2015-12-03 15:45:48.056 ThaliTest[1216:6807] jxcore: startBroadcasting
,2015-12-03 15:45:48.066 ThaliTest[1216:6807] server: starting Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:45:48.067 ThaliTest[1216:6807] multipeer session: start timer: 0x1bd37620
,2015-12-03 15:45:48.069 ThaliTest[1216:6807] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4165
,2015-12-03 15:45:48.073 ThaliTest[1216:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03T14:45:48.084Z SendDataTCPServer.js: TCP/IP server is bound to port: 63292
,2015-12-03 15:45:48.323 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:45:48.327Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03T14:45:48.327Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03T14:45:48.327Z SendDataConnector.js: do connect now
,2015-12-03 15:45:48.328 ThaliTest[1216:6807] jxcore: connect Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:48.329 ThaliTest[1216:6807] client session: connect
,2015-12-03 15:45:48.329 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:49.409 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6724.bsoISg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:50.949 ThaliTest[1216:2223] client session: connected
,2015-12-03 15:45:50.951 ThaliTest[1216:2223] client session: stateChange:1->2 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:50.956 ThaliTest[1216:2223] client session: fireConnectCallback: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:50.956 ThaliTest[1216:2223] jxcore: connect: success
,2015-12-03T14:45:50.958Z SendDataConnector.js: CLIENT connected to 63295, error: null
2015-12-03T14:45:50.958Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:50.960 ThaliTest[1216:60b] client: relay established
2015-12-03 15:45:50.961 ThaliTest[1216:60b] client: new accepted socket: 0x1bd2de40
,2015-12-03T14:45:50.972Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:45:51.540Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:45:51.577Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:45:51.601Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:45:51.637Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:45:51.651Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:45:51.664Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:45:51.676Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:45:51.677Z SendDataConnector.js: got all data for this round
,2015-12-03T14:45:51.679Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:45:51.680Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:45:51.681 ThaliTest[1216:6807] jxcore: disconnect
,2015-12-03 15:45:51.682 ThaliTest[1216:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:51.683 ThaliTest[1216:6807] client session: disconnect
,2015-12-03 15:45:51.683 ThaliTest[1216:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:45:51.685 ThaliTest[1216:6807] jxcore: disconnect: success
2015-12-03T14:45:51.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1068.V8ys1g==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:45:51.689Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:45:51.689Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03T14:45:51.689Z SendDataConnector.js: do connect now
,2015-12-03 15:45:51.690 ThaliTest[1216:6807] jxcore: connect Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:51.691 ThaliTest[1216:6807] client session: connect
2015-12-03 15:45:51.691 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:51.881 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:53.062 ThaliTest[1216:60b] multipeer session: reset timer
,2015-12-03 15:45:53.063 ThaliTest[1216:60b] multipeer session: stop timer
,2015-12-03 15:45:53.064 ThaliTest[1216:60b] multipeer session: start timer: 0x1bd37620
,2015-12-03 15:45:53.065 ThaliTest[1216:60b] server session: connect
,2015-12-03 15:45:53.066 ThaliTest[1216:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:53.069 ThaliTest[1216:60b] server: accepting invitation Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:55.017 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:55.619 ThaliTest[1216:760f] server session: connected
,2015-12-03 15:45:55.619 ThaliTest[1216:760f] server session: stateChange:1->2 Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:55.672 ThaliTest[1216:60b] server relay: connected (to port: 63292)
2015-12-03T14:45:55.675Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 15:45:55.677 ThaliTest[1216:7a07] client session: connected
2015-12-03 15:45:55.679 ThaliTest[1216:7a07] client session: stateChange:1->2 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:55.735 ThaliTest[1216:7a07] client session: fireConnectCallback: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:45:55.736 ThaliTest[1216:7a07] jxcore: connect: success
,2015-12-03T14:45:55.738Z SendDataConnector.js: CLIENT connected to 63299, error: null
,2015-12-03T14:45:55.738Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:55.739 ThaliTest[1216:60b] client: relay established
2015-12-03 15:45:55.741 ThaliTest[1216:60b] client: new accepted socket: 0x1bebff80
,2015-12-03T14:45:55.751Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:45:56.242Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:45:56.301Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03 15:45:56.639 ThaliTest[1216:760f] server session: not connected Apple-IpadAir2-1_PT6724
,2015-12-03T14:45:56.648Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:45:56.717Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:45:56.718Z SendDataConnector.js: got all data for this round
,2015-12-03T14:45:56.719Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:45:56.720Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:45:56.720 ThaliTest[1216:6807] jxcore: disconnect
2015-12-03 15:45:56.721 ThaliTest[1216:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:56.722 ThaliTest[1216:6807] client session: disconnect
2015-12-03 15:45:56.723 ThaliTest[1216:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:45:56.725 ThaliTest[1216:6807] jxcore: disconnect: success
2015-12-03T14:45:56.727Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6724.bsoISg==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:45:56.728Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:45:56.729Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:45:56.729Z SendDataConnector.js: do connect now
,2015-12-03 15:45:56.729 ThaliTest[1216:6807] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:45:56.730 ThaliTest[1216:6807] client session: connect
2015-12-03 15:45:56.731 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:45:59.364 ThaliTest[1216:880f] client session: connected
,2015-12-03 15:45:59.366 ThaliTest[1216:880f] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:45:59.407 ThaliTest[1216:880f] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:45:59.408 ThaliTest[1216:880f] jxcore: connect: success
,2015-12-03T14:45:59.409Z SendDataConnector.js: CLIENT connected to 63303, error: null
,2015-12-03T14:45:59.410Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:45:59.412 ThaliTest[1216:60b] client: relay established
,2015-12-03 15:45:59.413 ThaliTest[1216:60b] client: new accepted socket: 0x1bebe270
,2015-12-03T14:45:59.423Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:46:00.423Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:46:00.436Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:46:00.449Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03T14:46:10.456Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:10.456Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:10.457Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:10.458Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:10.459Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:10.460 ThaliTest[1216:60b] client: socket closed
2015-12-03 15:46:10.461 ThaliTest[1216:60b] client relay: socket disconnected
,2015-12-03 15:46:10.461 ThaliTest[1216:60b] client relay: 0x1bebe270 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x166a1e20 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:46:10.462 ThaliTest[1216:60b] client session: socket closed: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:10.463 ThaliTest[1216:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:10.463 ThaliTest[1216:60b] client session: disconnect
,2015-12-03 15:46:10.464 ThaliTest[1216:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:10.466 ThaliTest[1216:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:46:15.462Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:46:15.463Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:20.475 ThaliTest[1216:6807] jxcore: disconnect
2015-12-03 15:46:20.476 ThaliTest[1216:6807] jxcore: disconnect: fail
,2015-12-03T14:46:20.478Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:46:20.478Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT2374.Xv/DEA== with availability status,: true
2015-12-03T14:46:20.478Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:46:20.479Z SendDataConnector.js: do connect now
,2015-12-03 15:46:20.479 ThaliTest[1216:6807] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:20.480 ThaliTest[1216:6807] client session: connect
,2015-12-03 15:46:20.480 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:23.066 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:46:23.476 ThaliTest[1216:a41b] client session: connected
,2015-12-03 15:46:23.477 ThaliTest[1216:a41b] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:23.485 ThaliTest[1216:880f] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:23.487 ThaliTest[1216:880f] jxcore: connect: success
,2015-12-03T14:46:23.489Z SendDataConnector.js: CLIENT connected to 63309, error: null
2015-12-03T14:46:23.489Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:46:23.491 ThaliTest[1216:60b] client: relay established
,2015-12-03 15:46:23.492 ThaliTest[1216:60b] client: new accepted socket: 0x1beb3230
,2015-12-03T14:46:23.502Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:46:33.574Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:33.575Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:33.575Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:33.576Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:33.577Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:33.579 ThaliTest[1216:60b] client: socket closed
2015-12-03 15:46:33.579 ThaliTest[1216:60b] client relay: socket disconnected
2015-12-03 15:46:33.580 ThaliTest[1216:60b] client relay: 0x1beb3230 disconnected with error Error Domain=GCDA,syncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bc46de0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:46:33.581 ThaliTest[1216:60b] client session: socket closed: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:33.581 ThaliTest[1216:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:33.582 ThaliTest[1216:60b] client session: disconnect
2015-12-03 15:46:33.582 ThaliTest[1216:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:33.584 ThaliTest[1216:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:46:38.580Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:46:38.581Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:43.589 ThaliTest[1216:6807] jxcore: disconnect
,2015-12-03 15:46:43.590 ThaliTest[1216:6807] jxcore: disconnect: fail
2015-12-03T14:46:43.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:46:43.592Z SendDataConnector.js: Connect (retry cou,nt 2) to peer Apple-Iphone5s-1_PT2374.Xv/DEA== with availability status: true
2015-12-03T14:46:43.592Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:46:43.592Z SendDataConnector.js: do connect now
2015-12-03 15:46:43.593 ThaliTest[1216:6807] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:43.593 ThaliTest[1216:6807] client session: connect
,2015-12-03 15:46:43.594 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:46.592 ThaliTest[1216:880f] client session: connected
2015-12-03 15:46:46.593 ThaliTest[1216:880f] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:46.605 ThaliTest[1216:880f] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:46.605 ThaliTest[1216:880f] jxcore: connect: success
2015-12-03T14:46:46.606Z SendDataConnector.js: CLIENT connected to 63313, error: null
2015-12-03T14:46:46.607Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:46:46.608 ThaliTest[1216:60b] client: relay established
,2015-12-03 15:46:46.609 ThaliTest[1216:60b] client: new accepted socket: 0x1bac8c10
,2015-12-03T14:46:46.620Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:46:53.066 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:46:53.077 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:53.078 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:46:53.079 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:46:53.080 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:46:56.676Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:46:56.676Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:56.677Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:46:56.678Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:56.679Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:46:56.680 ThaliTest[1216:60b] client: socket closed
,2015-12-03 15:46:56.681 ThaliTest[1216:60b] client relay: socket disconnected
,2015-12-03 15:46:56.681 ThaliTest[1216:60b] client relay: 0x1bac8c10 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b92da10 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:46:56.682 ThaliTest[1216:60b] client session: socket closed: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:46:56.683 ThaliTest[1216:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:56.683 ThaliTest[1216:60b] client session: disconnect
,2015-12-03 15:46:56.684 ThaliTest[1216:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:46:56.685 ThaliTest[1216:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:47:01.684Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:47:01.685Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:06.692 ThaliTest[1216:6807] jxcore: disconnect
,2015-12-03 15:47:06.693 ThaliTest[1216:6807] jxcore: disconnect: fail
2015-12-03T14:47:06.695Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:47:06.695Z SendDataConnector.js: Connect (retry cou,nt 3) to peer Apple-Iphone5s-1_PT2374.Xv/DEA== with availability status: true
2015-12-03T14:47:06.696Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03T14:47:06.696Z SendDataConnector.js: do connect now
,2015-12-03 15:47:06.696 ThaliTest[1216:6807] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:06.697 ThaliTest[1216:6807] client session: connect
,2015-12-03 15:47:06.698 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:09.653 ThaliTest[1216:761b] client session: connected
2015-12-03 15:47:09.655 ThaliTest[1216:761b] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:09.663 ThaliTest[1216:880f] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:09.665 ThaliTest[1216:880f] jxcore: connect: success
,2015-12-03T14:47:09.666Z SendDataConnector.js: CLIENT connected to 63318, error: null
2015-12-03T14:47:09.666Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:09.668 ThaliTest[1216:60b] client: relay established
,2015-12-03 15:47:09.669 ThaliTest[1216:60b] client: new accepted socket: 0x1bd1d2d0
,2015-12-03T14:47:09.680Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:47:19.735Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:47:19.735Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:47:19.736Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:19.737Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:47:19.738Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:47:19.739 ThaliTest[1216:60b] client: socket closed
2015-12-03 15:47:19.740 ThaliTest[1216:60b] client relay: socket disconnected
,2015-12-03 15:47:19.741 ThaliTest[1216:60b] client relay: 0x1bd1d2d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b93ff90 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 15:47:19.741 ThaliTest[1216:60b] client session: socket closed: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:19.742 ThaliTest[1216:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:47:19.742 ThaliTest[1216:60b] client session: disconnect
,2015-12-03 15:47:19.743 ThaliTest[1216:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:19.745 ThaliTest[1216:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:23.066 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03T14:47:24.742Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:47:24.742Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:29.747 ThaliTest[1216:6807] jxcore: disconnect
2015-12-03 15:47:29.748 ThaliTest[1216:6807] jxcore: disconnect: fail
2015-12-03T14:47:29.748Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:47:29.749Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT2374.Xv/DEA== with availability status: true
2015-12-03T14:47:29.749Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
2015,-12-03T14:47:29.749Z SendDataConnector.js: do connect now
2015-12-03 15:47:29.749 ThaliTest[1216:6807] jxcore: connect Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:29.750 ThaliTest[1216:6807] client session: connect
2015-12-03 15:47:29.751 ThaliTest[1216:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:32.704 ThaliTest[1216:7a13] client session: connected
2015-12-03 15:47:32.706 ThaliTest[1216:7a13] client session: stateChange:1->2 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:32.713 ThaliTest[1216:7a13] client session: fireConnectCallback: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:32.714 ThaliTest[1216:7a13] jxcore: connect: success
,2015-12-03T14:47:32.715Z SendDataConnector.js: CLIENT connected to 63324, error: null
,2015-12-03T14:47:32.715Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:47:32.717 ThaliTest[1216:60b] client: relay established
,2015-12-03 15:47:32.717 ThaliTest[1216:60b] client: new accepted socket: 0x1bdf5af0
,2015-12-03T14:47:32.730Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:47:36.763 ThaliTest[1216:60b] multipeer session: reset timer
2015-12-03 15:47:36.765 ThaliTest[1216:60b] multipeer session: stop timer
,2015-12-03 15:47:36.766 ThaliTest[1216:60b] multipeer session: start timer: 0x1bd37620
2015-12-03 15:47:36.766 ThaliTest[1216:60b] server session: connect
2015-12-03 15:47:36.767 ThaliTest[1216:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:36.771 ThaliTest[1216:60b] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03T14:47:42.788Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:47:42.789Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:42.790Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:47:42.791Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:42.792Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:47:42.792Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:47:42.792 ThaliTest[1216:6807] jxcore: disconnect
2015-12-03 15:47:42.793 ThaliTest[1216:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:42.794 ThaliTest[1216:6807] client session: disconnect
,2015-12-03 15:47:42.794 ThaliTest[1216:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:47:42.798 ThaliTest[1216:6807] jxcore: disconnect: success
2015-12-03T14:47:42.799Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT2374.Xv/DEA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT4165","time":114755,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1068.V8ys1g==","time":3351,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT6724.bsoISg==","time":5029,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT2374.Xv/DEA==","time":106061,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataR,eceived":90000}]}
sendList : 100% : 5029 ms, 99% : 5029 ms, 95 : 5029 ms, 90% : 5029 ms.
Result count 2, range 3351 ms to  5029 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT2374.Xv/DEA==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T14:47:42.809Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:47:42.809Z SendDataCo,nnector.js: CLIENT closeClientSocket
2015-12-03T14:47:42.810Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:47:44.096 ThaliTest[1216:7a13] server session: connected
,2015-12-03 15:47:44.097 ThaliTest[1216:7a13] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:44.106 ThaliTest[1216:60b] server relay: connected (to port: 63292)
,2015-12-03T14:47:44.113Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:47:44.423Z SendDataTCPServer.js: TCP/IP server has received 8476 bytes of data
,2015-12-03T14:47:44.436Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-03T14:47:44.454Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-03T14:47:44.467Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:47:44.493 ThaliTest[1216:761f] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:48:06.767 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:48:06.779 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:06.780 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:06.780 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:48:07.176 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:48:36.767 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:48:36.779 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:36.780 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:48:36.782 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:36.993 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:48:39.656 ThaliTest[1216:60b] client: lost peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:48:39.657 ThaliTest[1216:60b] client session: onPeerLost: Apple-Iphone5s-1_PT2374.Xv/DEA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:48:44.357 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:48:58.454 ThaliTest[1216:60b] client: lost peer: Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:48:58.456 ThaliTest[1216:60b] client session: onPeerLost: Apple-Iphone6-1_PT1068.V8ys1g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 15:49:01.948 ThaliTest[1216:60b] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:01.950 ThaliTest[1216:60b] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 15:49:06.767 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:49:06.778 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:06.779 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:07.009 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1068.V8ys1g==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 15:49:27.304 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:49:36.766 ThaliTest[1216:60b] multipeer session: restart
,2015-12-03 15:49:36.780 ThaliTest[1216:60b] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:36.780 ThaliTest[1216:60b] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:36.781 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT1068.V8ys1g==
,2015-12-03 15:49:36.782 ThaliTest[1216:60b] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:50:01.092 ThaliTest[1216:60b] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:50:01.094 ThaliTest[1216:60b] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 15:50:02.061 ThaliTest[1216:60b] multipeer session: reset timer
2015-12-03 15:50:02.062 ThaliTest[1216:60b] multipeer session: stop timer
,2015-12-03 15:50:02.064 ThaliTest[1216:60b] multipeer session: start timer: 0x1bd37620
,2015-12-03 15:50:02.064 ThaliTest[1216:60b] server session: connect
,2015-12-03 15:50:02.065 ThaliTest[1216:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT1068
,2015-12-03 15:50:02.068 ThaliTest[1216:60b] server: accepting invitation Apple-Iphone6-1_PT1068
,2015-12-03 15:50:04.671 ThaliTest[1216:8823] server session: connected
2015-12-03 15:50:04.673 ThaliTest[1216:8823] server session: stateChange:1->2 Apple-Iphone6-1_PT1068
,2015-12-03 15:50:04.676 ThaliTest[1216:60b] server relay: connected (to port: 63292)
2015-12-03T14:50:04.677Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:50:05.122Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-03T14:50:05.135Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-03T14:50:05.148Z SendDataTCPServer.js: TCP/IP server has received 78414 bytes of data
,2015-12-03T14:50:05.162Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:50:05.187 ThaliTest[1216:776f] server session: not connected Apple-Iphone6-1_PT1068
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
testSendData stopped
2015-12-03 15:50:06.080 ThaliTest[1216:6807] jxcore: stopBroadcasting
,2015-12-03 15:50:06.081 ThaliTest[1216:6807] THEMultipeerSession stopping peer
2015-12-03 15:50:06.082 ThaliTest[1216:6807] multipeer session: stop timer
,2015-12-03 15:50:06.082 ThaliTest[1216:6807] server session: disconnect
2015-12-03 15:50:06.083 ThaliTest[1216:6807] server session: stateChange:2->0 Apple-Iphone5s-1_PT2374
,2015-12-03 15:50:11.244 ThaliTest[1216:6807] server session: disconnect
2015-12-03 15:50:11.245 ThaliTest[1216:6807] server session: stateChange:2->0 Apple-Iphone6-1_PT1068
,2015-12-03 15:50:11.247 ThaliTest[1216:6807] server session: disconnect
2015-12-03 15:50:11.248 ThaliTest[1216:6807] server session: stateChange:2->0 Apple-IpadAir2-1_PT6724
,2015-12-03 15:50:11.251 ThaliTest[1216:6807] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-03T14:50:11.270Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:11.271Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:11.272Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:11.272Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1068.V8ys1g==\",\"time\":3351,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT6724.bsoISg==\",\"time\":5029,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT2374.Xv/DEA==\",\"time\":106061,,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
