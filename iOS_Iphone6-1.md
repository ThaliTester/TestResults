#### Test 5319156460e1811_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BDD09E10-84D3-49A1-9760-3E48579A2C84/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BDD09E10-84D3-49A1-9760-3E48579A2C84/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E83525F2-AFC7-41DB-8BDA-F81A8012E114/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52738"
,(lldb)     command script import "/tmp/BDD09E10-84D3-49A1-9760-3E48579A2C84/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 00:12:36.495 ThaliTest[630:486317] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B1611EE-8CE4-4CF8-947B-E86282485BF4/Library/Cookies/Cookies.binarycookies
,2015-12-10 00:12:36.825 ThaliTest[630:486317] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 00:12:36.826 ThaliTest[630:486317] Multi-tasking -> Device: YES, App: YES
,2015-12-10 00:12:36.835 ThaliTest[630:486317] Unlimited access to network resources
,2015-12-10 00:12:36.845 ThaliTest[630:486317] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 00:12:45.703 ThaliTest[630:486317] Resetting plugins due to page load.
,2015-12-10 00:12:49.246 ThaliTest[630:486317] Finished load of: file:///var/mobile/Containers/Bundle/Application/E83525F2-AFC7-41DB-8BDA-F81A8012E114/ThaliTest.app/www/index.html
,2015-12-10 00:12:49.426 ThaliTest[630:486317] JXcore Cordova plugin initializing
,2015-12-10 00:12:49.427 ThaliTest[630:486498] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
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
,my name is : Apple-Iphone6-1_PT5811
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
serverPort is 53708
,2015-12-10 00:19:35.950 ThaliTest[630:486498] jxcore: startBroadcasting
,2015-12-10 00:19:35.971 ThaliTest[630:486498] server: starting Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:35.973 ThaliTest[630:486498] multipeer session: start timer: 0x15ec5e60
2015-12-10 00:19:35.973 ThaliTest[630:486498] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT5811
2015-12-10 00:19:35.974 ThaliTest[630:486498] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-09T23:19:35.976Z SendDataTCPServer.js: TCP/IP server is bound to port: 53708
,2015-12-10 00:19:37.295 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6044.nbqPWA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:19:37.302Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:19:37.303Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:19:37.303Z SendDataConnector.js: do connect now
,2015-12-10 00:19:37.304 ThaliTest[630:486498] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:19:37.305 ThaliTest[630:486498] client session: connect
2015-12-10 00:19:37.305 ThaliTest[630:486498] client session: stateChange:0->1 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:37.731 ThaliTest[630:486317] multipeer session: reset timer
2015-12-10 00:19:37.731 ThaliTest[630:486317] multipeer session: stop timer
2015-12-10 00:19:37.732 ThaliTest[630:486317] multipeer session: start timer: 0x15ec5e60
2015-12-10 ,00:19:37.732 ThaliTest[630:486317] server session: connect
2015-12-10 00:19:37.732 ThaliTest[630:486317] server session: stateChange:0->1 Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:37.742 ThaliTest[630:486317] server: accepting invitation Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:39.176 ThaliTest[630:486317] multipeer session: reset timer
2015-12-10 00:19:39.177 ThaliTest[630:486317] multipeer session: stop timer
2015-12-10 00:19:39.177 ThaliTest[630:486317] multipeer session: start timer: 0x15ec5e60
2015-12-10 ,00:19:39.178 ThaliTest[630:486317] server session: connect
2015-12-10 00:19:39.178 ThaliTest[630:486317] server session: stateChange:0->1 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:39.187 ThaliTest[630:486317] server: accepting invitation Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:39.778 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1537.Uf7bCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-10 00:19:40.355 ThaliTest[630:487159] client session: connected
2015-12-10 00:19:40.355 ThaliTest[630:487159] client session: stateChange:1->2 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:40.384 ThaliTest[630:487167] client session: fireConnectCallback: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:19:40.384 ThaliTest[630:487167] jxcore: connect: success
2015-12-09T23:19:40.386Z SendDataConnector.js: CLIENT connected to 53711, error: null
,2015-12-09T23:19:40.387Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:40.391 ThaliTest[630:486317] client: relay established
2015-12-10 00:19:40.392 ThaliTest[630:486317] client: new accepted socket: 0x15ed44c0
,2015-12-09T23:19:40.408Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:40.744Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T23:19:40.820Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T23:19:40.868Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T23:19:40.868Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:40.869Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:19:40.870Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:40.871 ThaliTest[630:486498] jxcore: disconnect
,2015-12-10 00:19:40.872 ThaliTest[630:486498] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:40.872 ThaliTest[630:486498] client session: disconnect
,2015-12-10 00:19:40.873 ThaliTest[630:486498] client session: stateChange:2->0 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:40.941 ThaliTest[630:486498] jxcore: disconnect: success
,2015-12-09T23:19:40.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:40.943Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:40.943Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:40.944Z SendDataConnector.js: do connect now
,2015-12-10 00:19:40.944 ThaliTest[630:486498] jxcore: connect Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:40.947 ThaliTest[630:487158] server session: connected
2015-12-10 00:19:40.947 ThaliTest[630:487158] server session: stateChange:1->2 Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:40.948 ThaliTest[630:486498] client session: connect
,2015-12-10 00:19:40.949 ThaliTest[630:486498] client session: stateChange:0->1 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:40.973 ThaliTest[630:486317] server relay: connected (to port: 53708)
,2015-12-09T23:19:40.983Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:41.242Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T23:19:41.256Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-09T23:19:41.345Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-09T23:19:41.360Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:41.402 ThaliTest[630:487158] server session: not connected Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:42.089 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9815.s7QXZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:42.386 ThaliTest[630:487157] server session: connected
2015-12-10 00:19:42.387 ThaliTest[630:487157] server session: stateChange:1->2 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:42.425 ThaliTest[630:486317] server relay: connected (to port: 53708)
2015-12-09T23:19:42.428Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:42.775Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-09T23:19:42.790Z SendDataTCPServer.js: TCP/IP server has received 30234 bytes of data
,2015-12-09T23:19:42.806Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T23:19:42.821Z SendDataTCPServer.js: TCP/IP server has received 65558 bytes of data
,2015-12-09T23:19:42.838Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-09T23:19:42.854Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:42.911 ThaliTest[630:487159] server session: not connected Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:44.494 ThaliTest[630:487159] client session: connected
2015-12-10 00:19:44.495 ThaliTest[630:487159] client session: stateChange:1->2 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:44.557 ThaliTest[630:487157] client session: fireConnectCallback: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:19:44.557 ThaliTest[630:487157] jxcore: connect: success
,2015-12-09T23:19:44.559Z SendDataConnector.js: CLIENT connected to 53716, error: null
,2015-12-09T23:19:44.560Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:44.564 ThaliTest[630:486317] client: relay established
2015-12-10 00:19:44.564 ThaliTest[630:486317] client: new accepted socket: 0x15fa74c0
,2015-12-09T23:19:44.576Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:45.065Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T23:19:45.078Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T23:19:45.078Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:45.079Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:19:45.079Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:45.080 ThaliTest[630:486498] jxcore: disconnect
,2015-12-10 00:19:45.081 ThaliTest[630:486498] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:45.081 ThaliTest[630:486498] client session: disconnect
,2015-12-10 00:19:45.082 ThaliTest[630:486498] client session: stateChange:2->0 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:45.151 ThaliTest[630:486498] jxcore: disconnect: success
,2015-12-09T23:19:45.152Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:45.154Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:45.154Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:19:45.155Z SendDataConnector.js: do connect now
,2015-12-10 00:19:45.155 ThaliTest[630:486498] jxcore: connect Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:45.156 ThaliTest[630:486498] client session: connect
,2015-12-10 00:19:45.157 ThaliTest[630:486498] client session: stateChange:0->1 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:48.064 ThaliTest[630:486317] multipeer session: reset timer
2015-12-10 00:19:48.064 ThaliTest[630:486317] multipeer session: stop timer
2015-12-10 00:19:48.064 ThaliTest[630:486317] multipeer session: start timer: 0x15ec5e60
2015-12-10 ,00:19:48.065 ThaliTest[630:486317] server session: connect
2015-12-10 00:19:48.065 ThaliTest[630:486317] server session: stateChange:0->1 Apple-Iphone5-1_PT9815
,2015-12-10 00:19:48.075 ThaliTest[630:486317] server: accepting invitation Apple-Iphone5-1_PT9815
,2015-12-10 00:19:58.364 ThaliTest[630:487167] client session: connected
2015-12-10 00:19:58.364 ThaliTest[630:487167] client session: stateChange:1->2 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:58.421 ThaliTest[630:487167] server session: connected
,2015-12-10 00:19:58.422 ThaliTest[630:487167] server session: stateChange:1->2 Apple-Iphone5-1_PT9815
,2015-12-10 00:19:58.494 ThaliTest[630:487159] client session: fireConnectCallback: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:58.494 ThaliTest[630:487159] jxcore: connect: success
2015-12-09T23:19:58.495Z SendDataConnector.js: CLIENT connected to 5,3720, error: null
2015-12-09T23:19:58.496Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:58.499 ThaliTest[630:486317] client: relay established
2015-12-10 00:19:58.500 ThaliTest[630:486317] client: new accepted socket: 0x15ed2a60
,2015-12-09T23:19:58.512Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-10 00:19:59.135 ThaliTest[630:486317] server relay: connected (to port: 53708)
,2015-12-09T23:19:59.140Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:20:00.851Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T23:20:02.071Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T23:20:03.094Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T23:20:13.102Z SendDataConnector.js: Receiving data timeout now
,2015-12-09T23:20:13.102Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09T23:20:13.104Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09T23:20:13.104Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T23:20:13.105Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-10 00:20:13.107 ThaliTest[630:486317] client: socket closed
2015-12-10 00:20:13.108 ThaliTest[630:486317] client relay: socket disconnected
2015-12-10 00:20:13.109 ThaliTest[630:486317] client relay: 0x15ed2a60 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-10 00:20:13.109 ThaliTest[630:486317] client session: socket closed: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:2,0:13.109 ThaliTest[630:486317] client session: onLinkFailure: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:13.109 ThaliTest[630:486317] client session: disconnect
2015-12-10 00:20:13.110 ThaliTest[630:486317] client session: stateChange:2->0 Apple-Ip,hone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:13.116 ThaliTest[630:486317] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:15.171 ThaliTest[630:487365] server session: not connected Apple-Iphone5-1_PT9815
,2015-12-10 00:20:18.066 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:20:18.113 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:18.113 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:20:18.113 ThaliTest[630:486317] client: fou,nd peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:20:18.116Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-09T23:20:18.117Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:23.127 ThaliTest[630:486498] jxcore: disconnect
2015-12-10 00:20:23.128 ThaliTest[630:486498] jxcore: disconnect: fail
2015-12-09T23:20:23.128Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9815.s7QXZQ==,
2015-12-09T23:20:23.129Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9815.s7QXZQ== with availability status: true
2015-12-09T23:20:23.129Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-09T23:20:23.129Z SendDataConnector.js: do connect now
,2015-12-10 00:20:23.131 ThaliTest[630:486498] jxcore: connect Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:23.132 ThaliTest[630:486498] client session: connect
2015-12-10 00:20:23.132 ThaliTest[630:486498] client session: stateChange:0->1 Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-10 00:20:48.066 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:20:48.109 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:20:48.111 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:20:48.112 ThaliTest[630:486317] client: fo,und peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:48.218 ThaliTest[630:487561] client session: connected
,2015-12-10 00:20:48.218 ThaliTest[630:487561] client session: stateChange:1->2 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:48.716 ThaliTest[630:487556] client session: fireConnectCallback: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:48.716 ThaliTest[630:487556] jxcore: connect: success
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-09T23:20:48.729Z SendDataConnector.js: CLIENT connected to 53732, error: null
,2015-12-09T23:20:48.730Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:20:48.733 ThaliTest[630:486317] client: relay established
2015-12-10 00:20:48.734 ThaliTest[630:486317] client: new accepted socket: 0x15ed2a60
,2015-12-09T23:20:48.747Z SendDataConnector.js: CLIENT now sending 70000 bytes of data
,2015-12-09T23:20:50.778Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T23:20:51.568Z SendDataConnector.js: CLIENT is data received : 50000
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-09T23:20:52.699Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-09T23:20:53.810Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T23:20:54.389Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T23:20:55.444Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T23:20:56.372Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:20:56.372Z SendDataConnector.js: got all data for this round
,2015-12-09T23:20:56.374Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:20:56.375Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-10 00:20:56.376 ThaliTest[630:486498] jxcore: disconnect
,2015-12-10 00:20:56.377 ThaliTest[630:486498] client session: disconnectFromPeer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:56.378 ThaliTest[630:486498] client session: disconnect
2015-12-10 00:20:56.378 ThaliTest[630:486498] client session: state,Change:2->0 Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:56.383 ThaliTest[630:486498] jxcore: disconnect: success
2015-12-09T23:20:56.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9815.s7QXZQ==
---- round done--,------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT5811","time":80451,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6044.nbqPWA==","time":3567,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT1537.Uf7bCw==","time":4136,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9815.s7QXZQ==","time":71219,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 71219 ms, 99% : 71219 ms, 95 : 71219 ms, 90% : 71219 ms.
Result count 3, range 3567 ms to  71219 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-09T23:20:56.405Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:20:56.406Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:00.827 ThaliTest[630:486317] multipeer session: reset timer
2015-12-10 00:21:00.828 ThaliTest[630:486317] multipeer session: stop timer
2015-12-10 00:21:00.828 ThaliTest[630:486317] multipeer session: start timer: 0x15ec5e60
,2015-12-10 00:21:00.828 ThaliTest[630:486317] server: disconnecting to refresh session (Apple-Iphone5-1_PT9815)
2015-12-10 00:21:00.830 ThaliTest[630:486317] server session: disconnect
2015-12-10 00:21:00.830 ThaliTest[630:486317] server session: stateCh,ange:2->0 Apple-Iphone5-1_PT9815
2015-12-10 00:21:00.834 ThaliTest[630:486317] server session: connect
2015-12-10 00:21:00.834 ThaliTest[630:486317] server session: stateChange:0->1 Apple-Iphone5-1_PT9815
,2015-12-09T23:21:00.842Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-10 00:21:00.848 ThaliTest[630:486317] server: accepting invitation Apple-Iphone5-1_PT9815
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:03.179 ThaliTest[630:487585] server session: connected
2015-12-10 00:21:03.180 ThaliTest[630:487585] server session: stateChange:1->2 Apple-Iphone5-1_PT9815
,2015-12-10 00:21:03.333 ThaliTest[630:486317] server relay: connected (to port: 53708)
2015-12-09T23:21:03.335Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:21:04.084Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T23:21:04.285Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T23:21:04.845Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-09T23:21:04.972Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-09T23:21:05.235Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-09T23:21:05.426Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T23:21:05.586Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-09T23:21:05.662Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-09T23:21:05.978Z SendDataTCPServer.js: TCP/IP server has received 19568 bytes of data
,2015-12-09T23:21:05.990Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-09T23:21:06.239Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-09T23:21:06.705Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-09T23:21:07.022Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T23:21:07.331Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-09T23:21:07.662Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-09T23:21:07.863Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-09T23:21:07.927Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T23:21:08.063Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T23:21:08.494Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-09T23:21:08.660Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-09T23:21:08.870Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T23:21:09.107Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-09T23:21:09.144Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-09T23:21:09.158Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-09T23:21:09.172Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-09T23:21:09.247Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-09T23:21:09.387Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-09T23:21:09.588Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-09T23:21:09.918Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-09T23:21:10.118Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-09T23:21:10.284Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-09T23:21:10.298Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-09T23:21:10.310Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-09T23:21:10.323Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-09T23:21:10.436Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-09T23:21:10.810Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-09T23:21:11.202Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-09T23:21:11.482Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-09T23:21:11.686Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-09T23:21:11.988Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-09T23:21:12.136Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-09T23:21:12.387Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-09T23:21:12.738Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-09T23:21:12.849Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-09T23:21:12.951Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-09T23:21:13.090Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-09T23:21:13.205Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:21:30.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:21:30.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:32.021 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:51.099 ThaliTest[630:487556] server session: not connected Apple-Iphone5-1_PT9815
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:00.829 ThaliTest[630:486317] multipeer session: restart
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
,2015-12-10 00:22:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:22:30.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:22:30.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:32.853 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:23:00.829 ThaliTest[630:486317] multipeer session: restart
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
,2015-12-10 00:23:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:23:30.863 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:23:30.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:23:32.459 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:24:00.829 ThaliTest[630:486317] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:24:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:24:30.864 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:24:30.865 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:24:30.867 ThaliTest[630:486317] client: fou,nd peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:25:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:25:00.871 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:25:00.871 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:25:00.872 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:25:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:25:30.872 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:25:30.872 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:25:30.875 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:26:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:26:00.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:26:00.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:26:00.870 ThaliTest[630:486317] client: fou,nd peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:26:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:26:30.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:26:30.868 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:26:30.871 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:27:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:27:00.867 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:27:00.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:27:00.868 ThaliTest[630:486317] client: fo,und peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:27:30.830 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:27:30.865 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:27:30.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:27:30.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:28:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:28:00.870 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:28:00.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:28:00.872 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-10 00:28:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:28:30.868 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:28:30.869 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:28:30.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:29:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:29:00.867 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:29:00.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:29:00.868 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:29:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:29:30.876 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:29:30.876 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:29:30.876 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:30:00.829 ThaliTest[630:486317] multipeer session: restart
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
,2015-12-10 00:30:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:30:30.866 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:30:30.867 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:30:30.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:31:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:31:00.867 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:31:00.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:31:00.870 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:31:30.829 ThaliTest[630:486317] multipeer session: restart
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:32:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:32:00.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:32:00.869 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:32:00.869 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:32:30.829 ThaliTest[630:486317] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:33:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:33:00.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:33:00.866 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:33:00.869 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:33:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:33:30.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:33:30.866 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:33:30.873 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:34:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:34:00.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:34:00.868 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:34:00.868 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:34:30.829 ThaliTest[630:486317] multipeer session: restart
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:35:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:35:00.865 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:35:00.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:35:00.867 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:35:30.829 ThaliTest[630:486317] multipeer session: restart
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:36:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:36:00.864 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:36:00.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:36:00.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,2015-12-10 00:36:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:36:30.866 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:36:30.867 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:36:30.870 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:37:00.829 ThaliTest[630:486317] multipeer session: restart
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
,2015-12-10 00:37:30.828 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:37:30.861 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:37:30.864 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:37:30.864 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:38:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:38:00.863 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:38:00.865 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:38:00.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
,2015-12-10 00:38:30.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:38:30.863 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:38:30.864 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:38:30.866 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:39:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:39:00.869 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:39:00.869 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:39:00.871 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,2015-12-10 00:39:30.829 ThaliTest[630:486317] multipeer session: restart
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:40:00.829 ThaliTest[630:486317] multipeer session: restart
,2015-12-10 00:40:00.859 ThaliTest[630:486317] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:40:00.860 ThaliTest[630:486317] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:40:00.860 ThaliTest[630:486317] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==

```
