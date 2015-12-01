#### Test 519863408c638e9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/422929F2-20AD-4D1B-BE66-BA8A17E399A5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/422929F2-20AD-4D1B-BE66-BA8A17E399A5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/8591558E-5E27-4727-BFDE-29425CED5CC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58421"
,(lldb)     command script import "/tmp/422929F2-20AD-4D1B-BE66-BA8A17E399A5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 11:48:20.916 ThaliTest[1020:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-01 11:48:20.919 ThaliTest[1020:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-01 11:48:20.928 ThaliTest[1020:60b] Unlimited access to network resources
,2015-12-01 11:48:20.934 ThaliTest[1020:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 11:48:31.919 ThaliTest[1020:60b] Resetting plugins due to page load.
,2015-12-01 11:48:32.787 ThaliTest[1020:60b] Finished load of: file:///var/mobile/Applications/8591558E-5E27-4727-BFDE-29425CED5CC4/ThaliTest.app/www/index.html
,2015-12-01 11:48:32.970 ThaliTest[1020:60b] JXcore Cordova plugin initializing
,2015-12-01 11:48:32.973 ThaliTest[1020:6707] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT9531
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 57020
,2015-12-01 11:54:33.252 ThaliTest[1020:6707] jxcore: startBroadcasting
,2015-12-01 11:54:33.261 ThaliTest[1020:6707] server: starting Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:54:33.263 ThaliTest[1020:6707] multipeer session: start timer: 0x1bef21f0
2015-12-01 11:54:33.264 ThaliTest[1020:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9531
,2015-12-01 11:54:33.266 ThaliTest[1020:6707] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-01T10:54:33.273Z SendDataTCPServer.js: TCP/IP server is bound to port: 57020
,2015-12-01 11:54:33.734 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:33.738Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T10:54:33.738Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:33.739Z SendDataConnector.js: do connect now
,2015-12-01 11:54:33.739 ThaliTest[1020:6707] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:33.740 ThaliTest[1020:6707] client session: connect
2015-12-01 11:54:33.740 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:34.255 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:34.844 ThaliTest[1020:60b] multipeer session: reset timer
,2015-12-01 11:54:34.845 ThaliTest[1020:60b] multipeer session: stop timer
,2015-12-01 11:54:34.847 ThaliTest[1020:60b] multipeer session: start timer: 0x1bef21f0
,2015-12-01 11:54:34.847 ThaliTest[1020:60b] server session: connect
,2015-12-01 11:54:34.848 ThaliTest[1020:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:34.852 ThaliTest[1020:60b] server: accepting invitation Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:35.611 ThaliTest[1020:60b] client: found peer: Apple-Iphone6-1_PT127.797wqw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:36.413 ThaliTest[1020:721f] client session: connected
2015-12-01 11:54:36.415 ThaliTest[1020:721f] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:36.427 ThaliTest[1020:611b] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:36.427 ThaliTest[1020:611b] jxcore: connect: success
,2015-12-01T10:54:36.429Z SendDataConnector.js: CLIENT connected to 57023, error: null
,2015-12-01T10:54:36.429Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:36.431 ThaliTest[1020:60b] client: relay established
,2015-12-01 11:54:36.431 ThaliTest[1020:60b] client: new accepted socket: 0x1bd295c0
,2015-12-01T10:54:36.444Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:36.985Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-01T10:54:37.009Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T10:54:37.029Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T10:54:37.041Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01 11:54:37.045 ThaliTest[1020:770f] server session: connected
,2015-12-01 11:54:37.047 ThaliTest[1020:770f] server session: stateChange:1->2 Apple-Iphone5s-1_PT9146
,2015-12-01T10:54:37.054Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01 11:54:37.058 ThaliTest[1020:60b] server relay: connected (to port: 57020)
,2015-12-01T10:54:37.069Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:37.095Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T10:54:37.484Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-01T10:54:37.497Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-01T10:54:37.511Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-01T10:54:37.525Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T10:54:37.528Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T10:54:37.529Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:37.531Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:54:37.531Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:54:37.533 ThaliTest[1020:6707] jxcore: disconnect
,2015-12-01 11:54:37.533 ThaliTest[1020:6707] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:37.534 ThaliTest[1020:6707] client session: disconnect
,2015-12-01 11:54:37.535 ThaliTest[1020:6707] client session: stateChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:37.537 ThaliTest[1020:6707] jxcore: disconnect: success
,2015-12-01T10:54:37.539Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/PQ==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:37.542Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:37.542Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==,
,2015-12-01T10:54:37.543Z SendDataConnector.js: do connect now
,2015-12-01 11:54:37.543 ThaliTest[1020:6707] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:37.544 ThaliTest[1020:6707] client session: connect
,2015-12-01 11:54:37.545 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:37.553 ThaliTest[1020:8303] server session: not connected Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:40.164 ThaliTest[1020:611b] client session: connected
2015-12-01 11:54:40.166 ThaliTest[1020:611b] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.168 ThaliTest[1020:611b] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.169 ThaliTest[1020:611b] jxcore: connect: success
,2015-12-01T10:54:40.171Z SendDataConnector.js: CLIENT connected to 57027, error: null
2015-12-01T10:54:40.171Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:40.173 ThaliTest[1020:60b] client: relay established
,2015-12-01 11:54:40.174 ThaliTest[1020:60b] client: new accepted socket: 0x1bd2cc80
,2015-12-01T10:54:40.184Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:40.761Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T10:54:40.786Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T10:54:40.799Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T10:54:41.143Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 11:54:41.795 ThaliTest[1020:60b] multipeer session: reset timer
2015-12-01 11:54:41.797 ThaliTest[1020:60b] multipeer session: stop timer
,2015-12-01 11:54:41.798 ThaliTest[1020:60b] multipeer session: start timer: 0x1bef21f0
,2015-12-01 11:54:41.798 ThaliTest[1020:60b] server session: connect
,2015-12-01 11:54:41.799 ThaliTest[1020:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT127
,2015-12-01 11:54:41.803 ThaliTest[1020:60b] server: accepting invitation Apple-Iphone6-1_PT127
,2015-12-01 11:54:44.804 ThaliTest[1020:721f] server session: connected
,2015-12-01 11:54:44.806 ThaliTest[1020:721f] server session: stateChange:1->2 Apple-Iphone6-1_PT127
,2015-12-01 11:54:44.815 ThaliTest[1020:60b] server relay: connected (to port: 57020)
,2015-12-01T10:54:44.827Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:45.273Z SendDataTCPServer.js: TCP/IP server has received 34046 bytes of data
,2015-12-01T10:54:45.287Z SendDataTCPServer.js: TCP/IP server has received 56230 bytes of data
,2015-12-01T10:54:45.300Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 11:54:45.321 ThaliTest[1020:611b] server session: not connected Apple-Iphone6-1_PT127
,2015-12-01 11:55:11.800 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01T10:55:31.147Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:55:31.147Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:55:31.148Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:55:31.149Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:55:31.149Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:55:31.151 ThaliTest[1020:60b] client: socket closed
,2015-12-01 11:55:31.151 ThaliTest[1020:60b] client relay: socket disconnected
,2015-12-01 11:55:31.152 ThaliTest[1020:60b] client relay: 0x1bd2cc80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ba21fb0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 11:55:31.153 ThaliTest[1020:60b] client session: socket closed: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:31.153 ThaliTest[1020:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:31.154 ThaliTest[1020:60b] client session: disconnect
,2015-12-01 11:55:31.154 ThaliTest[1020:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:31.156 ThaliTest[1020:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:55:36.151Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:55:36.152Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:41.158 ThaliTest[1020:6707] jxcore: disconnect
,2015-12-01 11:55:41.159 ThaliTest[1020:6707] jxcore: disconnect: fail
2015-12-01T10:55:41.161Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:55:41.161Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7493.hpeH+A== with availability status: true
,2015-12-01T10:55:41.162Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:55:41.162Z SendDataConnector.js: do connect now
,2015-12-01 11:55:41.162 ThaliTest[1020:6707] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:41.163 ThaliTest[1020:6707] client session: connect
,2015-12-01 11:55:41.163 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:41.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:55:41.809 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:41.810 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:55:41.811 ThaliTest[1020:60b] client: found peer: Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:55:44.168 ThaliTest[1020:611f] client session: connected
2015-12-01 11:55:44.170 ThaliTest[1020:611f] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:44.172 ThaliTest[1020:611f] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:44.173 ThaliTest[1020:611f] jxcore: connect: success
,2015-12-01T10:55:44.174Z SendDataConnector.js: CLIENT connected to 57037, error: null
2015-12-01T10:55:44.175Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:55:44.177 ThaliTest[1020:60b] client: relay established
2015-12-01 11:55:44.178 ThaliTest[1020:60b] client: new accepted socket: 0x1bef4c50
,2015-12-01T10:55:44.188Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:55:46.641 ThaliTest[1020:60b] client: lost peer: Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:55:46.643 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone6-1_PT127.797wqw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-01 11:56:05.888 ThaliTest[1020:6123] client session: not connected Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:56:05.890 ThaliTest[1020:6123] client session: onLinkFailure: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:56:05.890 ThaliTest[1020:6123] client session: disconnect
2015-12-01 11:56:05.891 ThaliTest[1020:6123] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:05.895 ThaliTest[1020:6123] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:11.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:56:11.809 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:11.810 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:56:34.258Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:56:34.258Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:56:34.259Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:56:34.259Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:56:34.260Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01T10:56:39.266Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:56:39.266Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:56:39.267Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:56:41.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:56:44.269 ThaliTest[1020:6707] jxcore: disconnect
,2015-12-01 11:56:44.270 ThaliTest[1020:6707] jxcore: disconnect: fail
2015-12-01T10:56:44.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:56:44.272Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7493.hpeH+A== with availability status: true
2015-12-01T10:56:44.273Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:56:44.273Z SendDataConnector.js: do connect now
,2015-12-01 11:56:44.273 ThaliTest[1020:6707] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:44.274 ThaliTest[1020:6707] client session: connect
,2015-12-01 11:56:44.275 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:47.006 ThaliTest[1020:a623] client session: connected
2015-12-01 11:56:47.008 ThaliTest[1020:a623] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:47.010 ThaliTest[1020:a623] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:56:47.011 ThaliTest[1020:a623] jxcore: connect: success
,2015-12-01T10:56:47.012Z SendDataConnector.js: CLIENT connected to 57044, error: null
2015-12-01T10:56:47.013Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:56:47.014 ThaliTest[1020:60b] client: relay established
,2015-12-01 11:56:47.016 ThaliTest[1020:60b] client: new accepted socket: 0x1bb74c30
,2015-12-01T10:56:47.026Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,2015-12-01 11:57:11.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:57:11.810 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:57:12.079 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 11:57:32.005 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:57:32.006 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:57:36.729 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01T10:57:37.084Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:57:37.084Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:57:37.085Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:57:37.086Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:57:37.086Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:57:37.088 ThaliTest[1020:60b] client: socket closed
,2015-12-01 11:57:37.089 ThaliTest[1020:60b] client relay: socket disconnected
,2015-12-01 11:57:37.089 ThaliTest[1020:60b] client relay: 0x1bb74c30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bd230b0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 11:57:37.090 ThaliTest[1020:60b] client session: socket closed: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:37.091 ThaliTest[1020:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:57:37.091 ThaliTest[1020:60b] client session: disconnect
,2015-12-01 11:57:37.092 ThaliTest[1020:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:37.093 ThaliTest[1020:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:41.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:57:41.809 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:41.810 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T10:57:42.090Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:57:42.090Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:47.101 ThaliTest[1020:6707] jxcore: disconnect
,2015-12-01 11:57:47.102 ThaliTest[1020:6707] jxcore: disconnect: fail
2015-12-01T10:57:47.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:57:47.104Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7493.hpeH+A== with availability status: true
,2015-12-01T10:57:47.104Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:57:47.105Z SendDataConnector.js: do connect now
,2015-12-01 11:57:47.105 ThaliTest[1020:6707] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:47.106 ThaliTest[1020:6707] client session: connect
,2015-12-01 11:57:47.107 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:49.800 ThaliTest[1020:a417] client session: connected
2015-12-01 11:57:49.801 ThaliTest[1020:a417] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:57:49.803 ThaliTest[1020:a417] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:57:49.804 ThaliTest[1020:a417] jxcore: connect: success
,2015-12-01T10:57:49.805Z SendDataConnector.js: CLIENT connected to 57056, error: null
2015-12-01T10:57:49.806Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:57:49.807 ThaliTest[1020:60b] client: relay established
2015-12-01 11:57:49.808 ThaliTest[1020:60b] client: new accepted socket: 0x16e62680
,2015-12-01T10:57:49.818Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:58:11.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:58:11.810 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:11.812 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:58:38.765 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:58:38.766 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01T10:58:39.876Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:58:39.877Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:58:39.877Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:58:39.878Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:58:39.879Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:58:39.880 ThaliTest[1020:60b] client: socket closed
,2015-12-01 11:58:39.881 ThaliTest[1020:60b] client relay: socket disconnected
,2015-12-01 11:58:39.882 ThaliTest[1020:60b] client relay: 0x16e62680 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bde1880 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 11:58:39.882 ThaliTest[1020:60b] client session: socket closed: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:58:39.883 ThaliTest[1020:60b] client session: onLinkFailure: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:39.884 ThaliTest[1020:60b] client session: disconnect
,2015-12-01 11:58:39.884 ThaliTest[1020:60b] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:39.885 ThaliTest[1020:60b] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:41.800 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:58:41.808 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:42.322 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01T10:58:44.888Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:58:44.888Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:49.890 ThaliTest[1020:6707] jxcore: disconnect
2015-12-01 11:58:49.892 ThaliTest[1020:6707] jxcore: disconnect: fail
2015-12-01T10:58:49.893Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:58:49.894Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7493.hpeH+A== with availability status: true
2015-12-01T10:58:49.894Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:58:49.894Z SendDataConnector.js: do connect now
,2015-12-01 11:58:49.894 ThaliTest[1020:6707] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:58:49.895 ThaliTest[1020:6707] client session: connect
,2015-12-01 11:58:49.896 ThaliTest[1020:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:52.845 ThaliTest[1020:b237] client session: connected
2015-12-01 11:58:52.846 ThaliTest[1020:b237] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:58:52.848 ThaliTest[1020:b237] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:58:52.849 ThaliTest[1020:b237] jxcore: connect: success
,2015-12-01T10:58:52.850Z SendDataConnector.js: CLIENT connected to 57062, error: null
,2015-12-01T10:58:52.851Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:58:52.852 ThaliTest[1020:60b] client: relay established
,2015-12-01 11:58:52.854 ThaliTest[1020:60b] client: new accepted socket: 0x1bdd51b0
,2015-12-01T10:58:52.864Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:59:08.973 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:59:08.975 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:59:11.799 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:59:23.076 ThaliTest[1020:60b] multipeer session: reset timer
2015-12-01 11:59:23.077 ThaliTest[1020:60b] multipeer session: stop timer
2015-12-01 11:59:23.078 ThaliTest[1020:60b] multipeer session: start timer: 0x1bef21f0
2015-12-01 11:59:23.079 ThaliTest[1020:60b] server session: connect
,2015-12-01 11:59:23.080 ThaliTest[1020:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01 11:59:23.083 ThaliTest[1020:60b] server: accepting invitation Apple-IpadAir2-1_PT7493
,2015-12-01 11:59:25.769 ThaliTest[1020:a62f] server session: connected
2015-12-01 11:59:25.771 ThaliTest[1020:a62f] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
,2015-12-01 11:59:25.774 ThaliTest[1020:60b] server relay: connected (to port: 57020)
,2015-12-01T10:59:25.784Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:59:25.996Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-01T10:59:26.008Z SendDataTCPServer.js: TCP/IP server has received 25854 bytes of data
,2015-12-01T10:59:26.021Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-01T10:59:26.035Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-01T10:59:26.049Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T10:59:42.920Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:59:42.921Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:59:42.921Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:59:42.924Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:59:42.924Z SendDataConnector.js: Stop data retrieving timer
,2015-12-01T10:59:42.925Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:59:42.925 ThaliTest[1020:6707] jxcore: disconnect
2015-12-01 11:59:42.926 ThaliTest[1020:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:59:42.927 ThaliTest[1020:6707] client session: disconnect
201,5-12-01 11:59:42.928 ThaliTest[1020:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:59:42.930 ThaliTest[1020:6707] jxcore: disconnect: success
,2015-12-01T10:59:42.932Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
---- round done--------
,2015-12-01T10:59:42.934Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:59:53.080 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 11:59:53.089 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:59:53.090 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:00:16.536 ThaliTest[1020:7637] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 12:00:23.080 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:00:23.090 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:00:23.092 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:00:26.942 ThaliTest[1020:60b] client: lost peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:00:26.944 ThaliTest[1020:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:00:26.945 ThaliTest[1020:60b] client: l,ost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":false}]
2015-12-01 12:00:26.946 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:00:27.100 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:00:27.557 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:00:28.728 ThaliTest[1020:60b] multipeer session: reset timer
2015-12-01 12:00:28.730 ThaliTest[1020:60b] multipeer session: stop timer
,2015-12-01 12:00:28.731 ThaliTest[1020:60b] multipeer session: start timer: 0x1bef21f0
,2015-12-01 12:00:28.732 ThaliTest[1020:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7493)
2015-12-01 12:00:28.732 ThaliTest[1020:60b] server session: disconnect
,2015-12-01 12:00:28.733 ThaliTest[1020:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT7493
,2015-12-01 12:00:28.736 ThaliTest[1020:60b] server session: connect
,2015-12-01 12:00:28.736 ThaliTest[1020:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01 12:00:28.741 ThaliTest[1020:60b] server: accepting invitation Apple-IpadAir2-1_PT7493
,2015-12-01T11:00:28.756Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 12:00:31.293 ThaliTest[1020:7637] server session: connected
2015-12-01 12:00:31.295 ThaliTest[1020:7637] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
,2015-12-01 12:00:31.299 ThaliTest[1020:60b] server relay: connected (to port: 57020)
,2015-12-01T11:00:31.307Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T11:00:31.342Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 12:00:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:01:21.668 ThaliTest[1020:724f] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 12:01:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:01:28.743 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:01:29.025 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 12:01:41.410 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:01:41.412 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 12:01:44.076 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 12:01:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:01:58.743 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:01:58.745 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
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
,2015-12-01 12:02:28.732 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:02:28.742 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:02:29.163 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-01 12:02:38.679 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:02:38.680 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:02:41.062 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 12:02:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:02:58.743 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:03:00.610 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:03:08.894 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:03:08.896 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:03:13.693 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:03:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:03:28.744 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:03:29.943 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:03:38.772 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:03:38.774 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:03:43.964 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:03:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:03:58.742 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:03:58.744 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:04:08.823 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:04:08.824 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:04:13.841 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:04:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:04:28.743 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:04:29.722 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:04:39.052 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:04:39.053 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:04:43.720 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:04:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:05:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:05:28.811 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:05:29.461 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:05:38.808 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:05:38.809 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:05:43.999 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:05:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:05:58.745 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:05:58.826 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:06:09.736 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:06:09.738 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:06:14.401 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:06:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:06:28.744 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:06:30.677 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:06:39.218 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:06:39.219 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:06:49.526 ThaliTest[1020:60b] client: lost peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:06:49.527 ThaliTest[1020:60b] client session: onPeerLost: Apple-IpadAir2-1_PT7493.hpeH+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:06:52.285 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:06:52.309 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:06:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:07:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:07:28.743 ThaliTest[1020:60b] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:07:28.985 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:07:32.978 ThaliTest[1020:60b] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:07:32.979 ThaliTest[1020:60b] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
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
Error type "connect_error" when connecting to the test server
,2015-12-01 12:07:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:07:59.372 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 12:08:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:08:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:08:59.125 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:09:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:09:30.582 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:09:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:09:58.870 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:10:28.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:10:58.733 ThaliTest[1020:60b] multipeer session: restart
,2015-12-01 12:10:59.690 ThaliTest[1020:60b] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,timeout now
,dun
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9531","time":1000037,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5s-1_PT9146.afM/PQ==","time":3792,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7493.hpeH+A==","time":305380,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 3792 ms, 99% : 3792 ms, 95 : 3792 ms, 90% : 3792 ms.
Result count 1, range 3792 ms to  3792 ms.
sendList failed peers count : 1 [50 %]
,- Peer ID : Apple-IpadAir2-1_PT7493.hpeH+A==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-01T11:11:13.285Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-01 12:11:14.718 ThaliTest[1020:6707] jxcore: stopBroadcasting
2015-12-01 12:11:14.719 ThaliTest[1020:6707] THEMultipeerSession stopping peer
2015-12-01 12:11:14.719 ThaliTest[1020:6707] multipeer session: stop timer
,2015-12-01 12:11:14.720 ThaliTest[1020:6707] server session: disconnect
2015-12-01 12:11:14.721 ThaliTest[1020:6707] server session: stateChange:2->0 Apple-Iphone5s-1_PT9146
,2015-12-01 12:11:14.725 ThaliTest[1020:6707] server session: disconnect
2015-12-01 12:11:14.726 ThaliTest[1020:6707] server session: stateChange:2->0 Apple-Iphone6-1_PT127
,2015-12-01 12:11:14.730 ThaliTest[1020:6707] server session: disconnect
,2015-12-01 12:11:14.731 ThaliTest[1020:6707] server session: stateChange:2->0 Apple-IpadAir2-1_PT7493
,2015-12-01 12:11:14.737 ThaliTest[1020:6707] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-01T11:11:14.752Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01T11:11:14.753Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01T11:11:14.754Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01T11:11:14.755Z SendDataTCPServer.,js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT9146.afM/PQ==\",\"time\":3792,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-IpadAir2-1_PT7493.hpeH+A==\",\"time\":305380,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":,[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
