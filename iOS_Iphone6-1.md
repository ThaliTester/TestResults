#### Test 5253548629578ed_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B441BC27-0836-4FBE-8C7D-DF72D9BC3A3F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B441BC27-0836-4FBE-8C7D-DF72D9BC3A3F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1D5ECD89-C7E3-491F-B774-E046E04BD920/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60392"
,(lldb)     command script import "/tmp/B441BC27-0836-4FBE-8C7D-DF72D9BC3A3F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-03 14:58:40.820 ThaliTest[2599:2207546] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F9214101-55E5-440F-9710-BBBB3766A6E9/Library/Cookies/Cookies.binarycookies
,2015-12-03 14:58:41.202 ThaliTest[2599:2207546] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 14:58:41.203 ThaliTest[2599:2207546] Multi-tasking -> Device: YES, App: YES
,2015-12-03 14:58:41.212 ThaliTest[2599:2207546] Unlimited access to network resources
,2015-12-03 14:58:41.218 ThaliTest[2599:2207546] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 14:58:44.666 ThaliTest[2599:2207546] Resetting plugins due to page load.
,2015-12-03 14:58:44.992 ThaliTest[2599:2207546] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/1D5ECD89-C7E3-491F-B774-E046E04BD920/ThaliTest.app/www/index.html
,2015-12-03 14:58:45.121 ThaliTest[2599:2207546] JXcore Cordova plugin initializing
,2015-12-03 14:58:45.122 ThaliTest[2599:2207699] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-Iphone6-1_PT7057
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 50226
,2015-12-03 15:05:06.081 ThaliTest[2599:2207699] jxcore: startBroadcasting
,2015-12-03 15:05:06.093 ThaliTest[2599:2207699] server: starting Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:06.093 ThaliTest[2599:2207699] multipeer session: start timer: 0x1be6b8d0
2015-12-03 15:05:06.094 ThaliTest[2599:2207699] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7057
2015-12-03 15:05:06.094 ThaliTest[2599:2207699] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T14:05:06.095Z SendDataTCPServer.js: TCP/IP server is bound to port: 50226
,2015-12-03 15:05:06.327 ThaliTest[2599:2207546] client: found peer: Apple-Iphone5-1_PT2690.vOZHlg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2690.vOZHlg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:06.329Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:06.330Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:06.330Z SendDataConnector.js: do connect now
,2015-12-03 15:05:06.331 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:06.331 ThaliTest[2599:2207699] client session: connect
2015-12-03 15:05:06.331 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:06.620 ThaliTest[2599:2207546] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7511.wgBJEg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:06.623 ThaliTest[2599:2207546] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7727.aEO4Zw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:09.959 ThaliTest[2599:2208289] client session: connected
2015-12-03 15:05:09.960 ThaliTest[2599:2208289] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:09.968 ThaliTest[2599:2208289] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:09.970 ThaliTest[2599:2208289] jxcore: connect: success
,2015-12-03T14:05:09.972Z SendDataConnector.js: CLIENT connected to 50229, error: null
2015-12-03T14:05:09.972Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:09.976 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:05:09.976 ThaliTest[2599:2207546] client: new accepted socket: 0x17544b60
,2015-12-03T14:05:09.992Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:05:10.477Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:05:10.477Z SendDataConnector.js: got all data for this round
,2015-12-03T14:05:10.478Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:05:10.479Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:05:10.480 ThaliTest[2599:2207699] jxcore: disconnect
,2015-12-03 15:05:10.480 ThaliTest[2599:2207699] client session: disconnectFromPeer: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:10.481 ThaliTest[2599:2207699] client session: disconnect
,2015-12-03 15:05:10.482 ThaliTest[2599:2207699] client session: stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:10.538 ThaliTest[2599:2207699] jxcore: disconnect: success
,2015-12-03T14:05:10.539Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHlg==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:10.541Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:05:10.541Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:05:10.541Z SendDataConnector.js: do connect now
,2015-12-03 15:05:10.541 ThaliTest[2599:2207699] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:10.542 ThaliTest[2599:2207699] client session: connect
,2015-12-03 15:05:10.542 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:11.480 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:05:11.480 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:05:11.481 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:05:11.482 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:05:11.482 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:11.492 ThaliTest[2599:2207546] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:13.957 ThaliTest[2599:2208319] client session: connected
2015-12-03 15:05:13.957 ThaliTest[2599:2208319] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:13.978 ThaliTest[2599:2208319] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:05:13.979 ThaliTest[2599:2208319] jxcore: connect: success
2015-12-03T14:05:13.980Z SendDataConnector.js: CLIENT connected, to 50232, error: null
2015-12-03T14:05:13.981Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:13.984 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:05:13.984 ThaliTest[2599:2207546] client: new accepted socket: 0x1bf65fb0
,2015-12-03T14:05:13.996Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03 15:05:14.015 ThaliTest[2599:2208319] server session: connected
2015-12-03 15:05:14.016 ThaliTest[2599:2208319] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:14.030 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:05:14.321Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:14.334Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-03T14:05:14.479Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-03T14:05:14.492Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:05:14.503Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:05:14.503Z SendDataConnector.js: got all data for this round
,2015-12-03T14:05:14.504Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:05:14.504Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:05:14.506 ThaliTest[2599:2207699] jxcore: disconnect
,2015-12-03 15:05:14.506 ThaliTest[2599:2207699] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:14.507 ThaliTest[2599:2207699] client session: disconnect
,2015-12-03 15:05:14.508 ThaliTest[2599:2207699] client session: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:05:14.511 ThaliTest[2599:2207699] jxcore: disconnect: success
,2015-12-03T14:05:14.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:14.513Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:14.514Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:14.514Z SendDataConnector.js: do connect now
,2015-12-03 15:05:14.514 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:14.515 ThaliTest[2599:2207699] client session: connect
,2015-12-03 15:05:14.515 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:16.813 ThaliTest[2599:2208290] client session: connected
2015-12-03 15:05:16.814 ThaliTest[2599:2208290] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:16.818 ThaliTest[2599:2208319] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:05:16.819 ThaliTest[2599:2208319] jxcore: connect: success
,2015-12-03T14:05:16.822Z SendDataConnector.js: CLIENT connected to 50237, error: null
2015-12-03T14:05:16.822Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:16.825 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:05:16.826 ThaliTest[2599:2207546] client: new accepted socket: 0x1bf66d30
,2015-12-03T14:05:16.839Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:05:17.124Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T14:05:17.136Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:05:17.149Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:05:17.162Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:05:17.175Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:05:17.188Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:05:24.539 ThaliTest[2599:2208290] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03T14:05:27.196Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:27.196Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:27.197Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:27.198Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:27.199Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:27.200 ThaliTest[2599:2207546] client: socket closed
2015-12-03 15:05:27.201 ThaliTest[2599:2207546] client relay: socket disconnected
2015-12-03 15:05:27.202 ThaliTest[2599:2207546] client relay: 0x1bf66d30 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1760b670 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:27.202 ThaliTest[2599:2207546] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Z,w==
2015-12-03 15:05:27.203 ThaliTest[2599:2207546] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:05:27.203 ThaliTest[2599:2207546] client session: disconnect
2015-12-03 15:05:27.203 ThaliTest[2599:2207546] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:27.206 ThaliTest[2599:2207546] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:32.202Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:32.203Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:35.115 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:05:35.116 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:05:35.117 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:05:35.117 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:05:35.118 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:05:35.118 ThaliTest[2599:2207546] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03 15:05:35.122 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:05:35.122 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:05:35.128Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:35.131 ThaliTest[2599:2207546] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:37.208 ThaliTest[2599:2207699] jxcore: disconnect
2015-12-03 15:05:37.209 ThaliTest[2599:2207699] jxcore: disconnect: fail
2015-12-03T14:05:37.210Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:37.211Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:05:37.211Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015,-12-03T14:05:37.211Z SendDataConnector.js: do connect now
,2015-12-03 15:05:37.212 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:37.213 ThaliTest[2599:2207699] client session: connect
2015-12-03 15:05:37.214 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:37.409 ThaliTest[2599:2208318] server session: connected
2015-12-03 15:05:37.410 ThaliTest[2599:2208318] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:37.435 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:05:37.446Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:37.471Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:05:39.860 ThaliTest[2599:2208290] client session: connected
2015-12-03 15:05:39.861 ThaliTest[2599:2208290] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:39.866 ThaliTest[2599:2208290] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:05:39.866 ThaliTest[2599:2208290] jxcore: connect: success
2015-12-03T14:05:39.867Z SendDataConnector.js: CLIENT connected to 50242, error: null
,2015-12-03T14:05:39.868Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:39.872 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:05:39.873 ThaliTest[2599:2207546] client: new accepted socket: 0x1761abb0
,2015-12-03T14:05:39.885Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:05:47.488 ThaliTest[2599:2208367] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03T14:05:49.953Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:49.953Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:49.954Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:49.955Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:49.955Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:49.957 ThaliTest[2599:2207546] client: socket closed
2015-12-03 15:05:49.958 ThaliTest[2599:2207546] client relay: socket disconnected
2015-12-03 15:05:49.958 ThaliTest[2599:2207546] client relay: 0x1761abb0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bdd6810 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:49.959 ThaliTest[2599:2207546] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Z,w==
2015-12-03 15:05:49.959 ThaliTest[2599:2207546] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:05:49.960 ThaliTest[2599:2207546] client session: disconnect
2015-12-03 15:05:49.960 ThaliTest[2599:2207546] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:49.962 ThaliTest[2599:2207546] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:54.960Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:05:54.960Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:57.971 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:05:57.971 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:05:57.972 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:05:57.972 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:05:57.972 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:05:57.973 ThaliTest[2599:2207546] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03 15:05:57.975 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:05:57.976 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:05:57.981Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:05:57.981 ThaliTest[2599:2207546] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:05:59.963 ThaliTest[2599:2207699] jxcore: disconnect
2015-12-03 15:05:59.964 ThaliTest[2599:2207699] jxcore: disconnect: fail
2015-12-03T14:05:59.964Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4,Zw==
2015-12-03T14:05:59.965Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:05:59.965Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:05:59.965Z SendDataConnector.js: do connect now
,2015-12-03 15:05:59.966 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:59.967 ThaliTest[2599:2207699] client session: connect
2015-12-03 15:05:59.968 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:00.604 ThaliTest[2599:2208410] server session: connected
2015-12-03 15:06:00.604 ThaliTest[2599:2208410] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:00.612 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
2015-12-03T14:06:00.618Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:00.657Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:02.324 ThaliTest[2599:2208422] client session: connected
2015-12-03 15:06:02.325 ThaliTest[2599:2208422] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:02.329 ThaliTest[2599:2208410] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:02.329 ThaliTest[2599:2208410] jxcore: connect: success
2015-12-03T14:06:02.331Z SendDataConnector.js: CLIENT connected to 50247, error: null
,2015-12-03T14:06:02.331Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:02.335 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:06:02.336 ThaliTest[2599:2207546] client: new accepted socket: 0x1ba5fa00
,2015-12-03T14:06:02.349Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:10.662 ThaliTest[2599:2208410] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03T14:06:12.418Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:12.418Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:12.419Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:12.420Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:12.420Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:12.422 ThaliTest[2599:2207546] client: socket closed
2015-12-03 15:06:12.422 ThaliTest[2599:2207546] client relay: socket disconnected
2015-12-03 15:06:12.423 ThaliTest[2599:2207546] client relay: 0x1ba5fa00 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bf61910 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:12.424 ThaliTest[2599:2207546] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Z,w==
2015-12-03 15:06:12.424 ThaliTest[2599:2207546] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:12.425 ThaliTest[2599:2207546] client session: disconnect
2015-12-03 15:06:12.425 ThaliTest[2599:2207546] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:12.428 ThaliTest[2599:2207546] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:17.429Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:17.430Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:22.217 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:06:22.218 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:06:22.219 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:06:22.219 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:06:22.220 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:06:22.220 ThaliTest[2599:2207546] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03 15:06:22.223 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:06:22.224 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:06:22.229Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:22.232 ThaliTest[2599:2207546] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:22.436 ThaliTest[2599:2207699] jxcore: disconnect
2015-12-03 15:06:22.437 ThaliTest[2599:2207699] jxcore: disconnect: fail
2015-12-03T14:06:22.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4,Zw==
2015-12-03T14:06:22.437Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
,2015-12-03T14:06:22.437Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:06:22.438Z SendDataConnector.js: do connect now
,2015-12-03 15:06:22.438 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:22.439 ThaliTest[2599:2207699] client session: connect
,2015-12-03 15:06:22.439 ThaliTest[2599:2207699] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:24.482 ThaliTest[2599:2208452] server session: connected
2015-12-03 15:06:24.483 ThaliTest[2599:2208452] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:24.494 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:06:24.501Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:24.540Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:24.964 ThaliTest[2599:2208452] client session: connected
,2015-12-03 15:06:24.965 ThaliTest[2599:2208452] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:24.969 ThaliTest[2599:2208452] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:24.970 ThaliTest[2599:2208452] jxcore: connect: success
2015-12-03T14:06:24.971Z SendDataConnector.js: CLIENT connected, to 50252, error: null
2015-12-03T14:06:24.972Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:24.976 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:06:24.976 ThaliTest[2599:2207546] client: new accepted socket: 0x176fa860
,2015-12-03T14:06:24.989Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:34.664 ThaliTest[2599:2208452] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03T14:06:35.073Z SendDataConnector.js: Receiving data timeout now
2015-12-03T14:06:35.073Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:06:35.074Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:06:35.074Z SendDataCo,nnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:35.074Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:35.077 ThaliTest[2599:2207546] client: socket closed
2015-12-03 15:06:35.077 ThaliTest[2599:2207546] client relay: socket disconnected
2015-12-03 15:06:35.078 ThaliTest[2599:2207546] client relay: 0x176fa860 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bf55a80 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:35.078 ThaliTest[2599:2207546] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Z,w==
2015-12-03 15:06:35.079 ThaliTest[2599:2207546] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:35.079 ThaliTest[2599:2207546] client session: disconnect
2015-12-03 15:06:35.080 ThaliTest[2599:2207546] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:35.081 ThaliTest[2599:2207546] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:40.080Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:06:40.081Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:44.756 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:06:44.757 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:06:44.757 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:06:44.758 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:06:44.758 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:06:44.759 ThaliTest[2599:2207546] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:44.764 ThaliTest[2599:2207546] server session: connect
,2015-12-03 15:06:44.765 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:06:44.769Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:44.771 ThaliTest[2599:2207546] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:45.092 ThaliTest[2599:2207699] jxcore: disconnect
2015-12-03 15:06:45.093 ThaliTest[2599:2207699] jxcore: disconnect: fail
2015-12-03T14:06:45.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:06:45.094Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
,2015-12-03T14:06:45.094Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:06:45.095Z SendDataConnector.js: do connect now
,2015-12-03 15:06:45.096 ThaliTest[2599:2207699] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:45.096 ThaliTest[2599:2207699] client session: connect
2015-12-03 15:06:45.097 ThaliTest[2599:2207699] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:47.190 ThaliTest[2599:2208499] server session: connected
2015-12-03 15:06:47.190 ThaliTest[2599:2208499] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:47.226 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:06:47.234Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 15:06:47.432 ThaliTest[2599:2208499] client session: connected
2015-12-03 15:06:47.433 ThaliTest[2599:2208499] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:47.437 ThaliTest[2599:2208501] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:47.438 ThaliTest[2599:2208501] jxcore: connect: success
2015-12-03T14:06:47.440Z SendDataConnector.js: CLIENT connected to 50257, error: null
,2015-12-03T14:06:47.441Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:47.444 ThaliTest[2599:2207546] client: relay established
2015-12-03 15:06:47.445 ThaliTest[2599:2207546] client: new accepted socket: 0x17553800
,2015-12-03T14:06:47.457Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T14:06:47.870Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:06:57.525Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:57.525Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:57.526Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:57.527Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:06:57.528Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:06:57.528Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:06:57.529 ThaliTest[2599:2207699] jxcore: disconnect
,2015-12-03 15:06:57.529 ThaliTest[2599:2207699] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:06:57.530 ThaliTest[2599:2207699] client session: disconnect
2015-12-03 15:06:57.531 ThaliTest[2599:2207699] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:06:57.534 ThaliTest[2599:2207699] jxcore: disconnect: success
2015-12-03T14:06:57.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
---- round done--------
weAreDoneNow , resultArray.length:, 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7057","time":111472,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT2690.vOZHlg==","time":4148,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT7511.wgBJEg==","time":3962,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7727.aEO4Zw==","time":103012,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataR,eceived":90000}]}
,sendList : 100% : 4148 ms, 99% : 4148 ms, 95 : 4148 ms, 90% : 4148 ms.
Result count 2, range 3962 ms to  4148 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5
sendList never tried peers count : 0 [0 %]
,2015-12-03T14:06:57.550Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:06:57.550Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:57.551Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:57.888 ThaliTest[2599:2208499] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:01.057 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:07:01.057 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:07:01.058 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:07:01.058 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:07:01.059 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:01.070 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:07:03.519 ThaliTest[2599:2208499] server session: connected
2015-12-03 15:07:03.520 ThaliTest[2599:2208499] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:03.532 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:07:03.541Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:04.029Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-03T14:07:04.043Z SendDataTCPServer.js: TCP/IP server has received 22816 bytes of data
,2015-12-03T14:07:04.059Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-12-03T14:07:04.072Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
,2015-12-03T14:07:04.085Z SendDataTCPServer.js: TCP/IP server has received 57536 bytes of data
,2015-12-03T14:07:04.099Z SendDataTCPServer.js: TCP/IP server has received 68448 bytes of data
,2015-12-03T14:07:04.113Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-12-03T14:07:04.128Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-12-03T14:07:04.141Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:07:14.171 ThaliTest[2599:2208498] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03 15:07:24.637 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:07:24.637 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:07:24.638 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:07:24.638 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:07:24.638 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:07:24.638 ThaliTest[2599:2207546] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:24.640 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:07:24.640 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:24.645 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5-1_PT2690
2015-12-03T14:07:24.646Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:07:27.105 ThaliTest[2599:2208544] server session: connected
2015-12-03 15:07:27.106 ThaliTest[2599:2208544] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:27.116 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:07:27.122Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:27.269Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T14:07:27.284Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:07:37.204 ThaliTest[2599:2208577] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03 15:07:47.571 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:07:47.572 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:07:47.573 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:07:47.574 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:07:47.574 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:07:47.574 ThaliTest[2599:2207546] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2690
2015-12-03 15:07:47.577 ThaliTest[2599:2207546] server session: connect
2015-12-03T14:07:47.580Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:07:47.578 ThaliTest[2599:2207546] server session: stateChange:0,->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:47.596 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:07:50.161 ThaliTest[2599:2208624] server session: connected
2015-12-03 15:07:50.162 ThaliTest[2599:2208624] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:50.172 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:07:50.183Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:50.320Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:08:00.271 ThaliTest[2599:2208625] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03 15:08:10.601 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:08:10.602 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:08:10.602 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:08:10.603 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:08:10.603 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:08:10.604 ThaliTest[2599:2207546] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2690
2015-12-03 15:08:10.606 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:08:10.609 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03T14:08:10.620Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:08:10.625 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:08:13.214 ThaliTest[2599:2208666] server session: connected
2015-12-03 15:08:13.215 ThaliTest[2599:2208666] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:08:13.225 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:08:13.238Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:13.389Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T14:08:13.403Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:08:23.310 ThaliTest[2599:2208665] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03 15:08:34.348 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:08:34.349 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:08:34.350 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:08:34.350 ThaliTest[2599:2207546] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:08:34.351 ThaliTest[2599:2207546] server session: disconnect
2015-12-03 15:08:34.351 ThaliTest[2599:2207546] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2690
2015-12-03 15:08:34.355 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:08:34.356 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03T14:08:34.365Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:08:34.372 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:08:36.297 ThaliTest[2599:2207546] multipeer session: reset timer
2015-12-03 15:08:36.298 ThaliTest[2599:2207546] multipeer session: stop timer
2015-12-03 15:08:36.299 ThaliTest[2599:2207546] multipeer session: start timer: 0x1be6b8d0
2015-,12-03 15:08:36.299 ThaliTest[2599:2207546] server session: connect
2015-12-03 15:08:36.300 ThaliTest[2599:2207546] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:36.310 ThaliTest[2599:2207546] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:36.952 ThaliTest[2599:2208717] server session: connected
2015-12-03 15:08:36.953 ThaliTest[2599:2208717] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:08:36.963 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
,2015-12-03T14:08:36.974Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:37.037Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T14:08:37.052Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:08:38.444 ThaliTest[2599:2208717] server session: connected
2015-12-03 15:08:38.445 ThaliTest[2599:2208717] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:38.452 ThaliTest[2599:2207546] server relay: connected (to port: 50226)
2015-12-03T14:08:38.456Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:38.733Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-03T14:08:38.749Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-03T14:08:38.763Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-03T14:08:38.780Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:08:38.829 ThaliTest[2599:2208711] server session: not connected Apple-Iphone5s-1_PT7727
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-03 15:08:47.179 ThaliTest[2599:2207699] jxcore: stopBroadcasting
,2015-12-03 15:08:47.181 ThaliTest[2599:2207699] THEMultipeerSession stopping peer
,2015-12-03 15:08:47.181 ThaliTest[2599:2207699] multipeer session: stop timer
2015-12-03 15:08:47.182 ThaliTest[2599:2207699] server session: disconnect
2015-12-03 15:08:47.183 ThaliTest[2599:2207699] server session: stateChange:2->0 Apple-Iphone5s-1_PT7,727
2015-12-03 15:08:47.189 ThaliTest[2599:2207699] server session: disconnect
2015-12-03 15:08:47.190 ThaliTest[2599:2207699] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:08:47.198 ThaliTest[2599:2207699] server session: disconnect
2015-12-03 15:08:47.199 ThaliTest[2599:2207699] server session: stateChange:2->0 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:47.203 ThaliTest[2599:2207699] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-03T14:08:47.223Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:47.225Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:47.227Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03T14:08:47.228Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT7511.wgBJEg==\",\"time\":3962,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT2690.vOZHlg==\",\"time\":4148,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT7727.aEO4Zw==\",\"time\":103012,,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
