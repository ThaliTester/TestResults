#### Test 5253548629578ed_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3C9876D4-136B-4DE0-8676-B3DB59FAE417/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3C9876D4-136B-4DE0-8676-B3DB59FAE417/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A8783FF-99B4-469B-9950-67A8B848B008/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60394"
,(lldb)     command script import "/tmp/3C9876D4-136B-4DE0-8676-B3DB59FAE417/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 14:58:43.820 ThaliTest[2462:2303436] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8CD49682-E69F-4DA0-A85C-213EC01F3654/Library/Cookies/Cookies.binarycookies
,2015-12-03 14:58:44.227 ThaliTest[2462:2303436] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 14:58:44.228 ThaliTest[2462:2303436] Multi-tasking -> Device: YES, App: YES
,2015-12-03 14:58:44.237 ThaliTest[2462:2303436] Unlimited access to network resources
,2015-12-03 14:58:44.244 ThaliTest[2462:2303436] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 14:58:47.492 ThaliTest[2462:2303436] Resetting plugins due to page load.
,2015-12-03 14:58:47.818 ThaliTest[2462:2303436] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/6A8783FF-99B4-469B-9950-67A8B848B008/ThaliTest.app/www/index.html
,2015-12-03 14:58:48.005 ThaliTest[2462:2303436] JXcore Cordova plugin initializing
,2015-12-03 14:58:48.008 ThaliTest[2462:2303565] JXcore instance initializing
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT7727
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50334
,2015-12-03 15:05:04.610 ThaliTest[2462:2303565] jxcore: startBroadcasting
,2015-12-03 15:05:04.626 ThaliTest[2462:2303565] server: starting Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:05:04.629 ThaliTest[2462:2303565] multipeer session: start timer: 0x1b6c39a0
,2015-12-03 15:05:04.649 ThaliTest[2462:2303565] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7727
,2015-12-03 15:05:04.649 ThaliTest[2462:2303565] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03T14:05:04.651Z SendDataTCPServer.js: TCP/IP server is bound to port: 50334
,2015-12-03 15:05:05.187 ThaliTest[2462:2303436] client: found peer: Apple-Iphone5-1_PT2690.vOZHlg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2690.vOZHlg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,device[1]: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:05.194Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:05.195Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
20,15-12-03T14:05:05.195Z SendDataConnector.js: do connect now
,2015-12-03 15:05:05.196 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:05.197 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:05:05.198 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:05.243 ThaliTest[2462:2303436] client: found peer: Apple-IpadAir2-1_PT7511.wgBJEg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7511.wgBJEg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:06.620 ThaliTest[2462:2303436] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:08.314 ThaliTest[2462:2304197] client session: connected
2015-12-03 15:05:08.315 ThaliTest[2462:2304197] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:08.327 ThaliTest[2462:2304197] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:08.328 ThaliTest[2462:2304197] jxcore: connect: success
,2015-12-03T14:05:08.330Z SendDataConnector.js: CLIENT connected to 50337, error: null
2015-12-03T14:05:08.331Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:08.335 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:05:08.335 ThaliTest[2462:2303436] client: new accepted socket: 0x1b508c80
,2015-12-03T14:05:08.351Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:05:08.737Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:05:08.751Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:05:14.679 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:05:14.680 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:05:14.680 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:05:14.681 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:05:14.682 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:14.693 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:05:16.808 ThaliTest[2462:2304198] server session: connected
,2015-12-03 15:05:16.809 ThaliTest[2462:2304198] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03T14:05:16.821Z SendDataTCPServer.js: TCP/IP server connected
2015-12-03 15:05:16.822 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:05:17.100Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-03T14:05:17.114Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-03T14:05:17.127Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-03T14:05:17.143Z SendDataTCPServer.js: TCP/IP server has received 50228 bytes of data
,2015-12-03T14:05:17.157Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-03T14:05:17.175Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-03T14:05:17.190Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:05:18.758Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:18.759Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:18.761Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:18.761Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:18.762Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:18.764 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:05:18.765 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:05:18.766 ThaliTest[2462:2303436] client relay: 0x1b508c80 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b5012f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:18.767 ThaliTest[2462:2303436] client session: socket closed: Apple-Iphone5-1_PT2690.vOZHlg,==
2015-12-03 15:05:18.767 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:18.767 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:05:18.768 ThaliTest[2462:2303436] client session: ,stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:18.770 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:23.771Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:23.772Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:27.208 ThaliTest[2462:2304199] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:05:28.775 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:05:28.775 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:05:28.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHl,g==
2015-12-03T14:05:28.777Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2690.vOZHlg== with availability status: true
,2015-12-03T14:05:28.777Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:28.778Z SendDataConnector.js: do connect now
,2015-12-03 15:05:28.778 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:28.779 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:05:28.780 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:31.289 ThaliTest[2462:2304198] client session: connected
2015-12-03 15:05:31.290 ThaliTest[2462:2304198] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:31.299 ThaliTest[2462:2304277] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:31.300 ThaliTest[2462:2304277] jxcore: connect: success
,2015-12-03T14:05:31.303Z SendDataConnector.js: CLIENT connected to 50340, error: null
2015-12-03T14:05:31.304Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:31.309 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:05:31.310 ThaliTest[2462:2303436] client: new accepted socket: 0x1b74d8c0
,2015-12-03T14:05:31.322Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:05:37.662 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:05:37.663 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:05:37.664 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
,2015-12-03 15:05:37.665 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-Iphone6-1_PT7057)
,2015-12-03 15:05:37.665 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:05:37.666 ThaliTest[2462:2303436] server session: stateChange:2->0 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:37.671 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:05:37.672 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03T14:05:37.679Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:37.682 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:05:39.855 ThaliTest[2462:2304197] server session: connected
2015-12-03 15:05:39.856 ThaliTest[2462:2304197] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:39.867 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:05:39.873Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:39.962Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T14:05:39.976Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:05:41.392Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:41.392Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:41.393Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:41.394Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:41.395Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:41.397 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:05:41.398 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:05:41.398 ThaliTest[2462:2303436] client relay: 0x1b74d8c0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6cd3f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:41.399 ThaliTest[2462:2303436] client session: socket closed: Apple-Iphone5-1_PT2690.vOZHlg,==
2015-12-03 15:05:41.399 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:41.400 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:05:41.400 ThaliTest[2462:2303436] client session: stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:41.403 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:46.404Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:46.404Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:50.110 ThaliTest[2462:2304309] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:05:51.414 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:05:51.415 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:05:51.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHl,g==
2015-12-03T14:05:51.417Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2690.vOZHlg== with availability status: true
,2015-12-03T14:05:51.417Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:51.417Z SendDataConnector.js: do connect now
2015-12-03 15:05:51.418 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone5-1_PT2690,.vOZHlg==
,2015-12-03 15:05:51.419 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:05:51.420 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:54.444 ThaliTest[2462:2304308] client session: connected
2015-12-03 15:05:54.445 ThaliTest[2462:2304308] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:54.455 ThaliTest[2462:2304308] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:54.457 ThaliTest[2462:2304308] jxcore: connect: success
2015-12-03T14:05:54.458Z SendDataConnector.js: CLIENT connected ,to 50343, error: null
,2015-12-03T14:05:54.459Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:54.463 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:05:54.464 ThaliTest[2462:2303436] client: new accepted socket: 0x1b74cc30
,2015-12-03T14:05:54.476Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:00.205 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:06:00.205 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:06:00.205 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:06:00.206 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-Iphone6-1_PT7057)
2015-12-03 15:06:00.206 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:06:00.206 ThaliTest[2462:2303436] server session: stateC,hange:2->0 Apple-Iphone6-1_PT7057
2015-12-03 15:06:00.207 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:06:00.207 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03 15:06:00.211 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03T14:06:00.214Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:02.320 ThaliTest[2462:2304308] server session: connected
2015-12-03 15:06:02.321 ThaliTest[2462:2304308] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:06:02.332 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:06:02.336Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:02.428Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T14:06:02.439Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:06:04.542Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:04.543Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:04.543Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:04.544Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:04.545Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:04.546 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:06:04.547 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:06:04.548 ThaliTest[2462:2303436] client relay: 0x1b74cc30 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b74fb40 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:04.549 ThaliTest[2462:2303436] client session: socket closed: Apple-Iphone5-1_PT2690.vOZHlg,==
2015-12-03 15:06:04.549 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:04.550 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:06:04.550 ThaliTest[2462:2303436] client session: ,stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:04.554 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:06:09.556Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:06:09.557Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:12.648 ThaliTest[2462:2304288] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:06:14.568 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:06:14.569 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:06:14.569Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHl,g==
2015-12-03T14:06:14.570Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2690.vOZHlg== with availability status: true
,2015-12-03T14:06:14.570Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:06:14.571Z SendDataConnector.js: do connect now
,2015-12-03 15:06:14.572 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:14.573 ThaliTest[2462:2303565] client session: connect
2015-12-03 15:06:14.573 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple,-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:17.031 ThaliTest[2462:2304288] client session: connected
2015-12-03 15:06:17.032 ThaliTest[2462:2304288] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:17.042 ThaliTest[2462:2304334] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:17.043 ThaliTest[2462:2304334] jxcore: connect: success
2015-12-03T14:06:17.044Z SendDataConnector.js: CLIENT connected ,to 50346, error: null
,2015-12-03T14:06:17.044Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:17.049 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:06:17.050 ThaliTest[2462:2303436] client: new accepted socket: 0x1b7532e0
,2015-12-03T14:06:17.063Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:22.753 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:06:22.754 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:06:22.754 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:06:22.755 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-Iphone6-1_PT7057)
2015-12-03 15:06:22.756 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:06:22.756 ThaliTest[2462:2303436] server session: stateC,hange:2->0 Apple-Iphone6-1_PT7057
,2015-12-03 15:06:22.761 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:06:22.763 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03T14:06:22.771Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:22.774 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:06:24.961 ThaliTest[2462:2304384] server session: connected
2015-12-03 15:06:24.961 ThaliTest[2462:2304384] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:06:24.972 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:06:24.974Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:25.077Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:06:27.117Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:27.117Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:27.118Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:27.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:27.120Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:27.123 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:06:27.124 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:06:27.125 ThaliTest[2462:2303436] client relay: 0x1b7532e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6dd5b0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:27.125 ThaliTest[2462:2303436] client session: socket closed: Apple-Iphone5-1_PT2690.vOZHlg,==
2015-12-03 15:06:27.126 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:27.127 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:06:27.127 ThaliTest[2462:2303436] client session: ,stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:27.129 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:06:32.128Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:06:32.128Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:35.188 ThaliTest[2462:2304334] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:06:37.140 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:06:37.141 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:06:37.142Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHl,g==
2015-12-03T14:06:37.142Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2690.vOZHlg== with availability status: true
2015-12-03T14:06:37.143Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:06:37.143Z SendDataConnector.js: do connect now
2015-12-03 15:06:37.144 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:37.145 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:06:37.145 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:39.526 ThaliTest[2462:2304411] client session: connected
2015-12-03 15:06:39.527 ThaliTest[2462:2304411] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:39.536 ThaliTest[2462:2304411] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:39.536 ThaliTest[2462:2304411] jxcore: connect: success
2015-12-03T14:06:39.538Z SendDataConnector.js: CLIENT connected ,to 50349, error: null
2015-12-03T14:06:39.538Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:39.542 ThaliTest[2462:2303436] client: relay established
,2015-12-03 15:06:39.543 ThaliTest[2462:2303436] client: new accepted socket: 0x1b6e12b0
,2015-12-03T14:06:39.555Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:45.215 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:06:45.216 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:06:45.217 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:06:45.218 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-Iphone6-1_PT7057)
2015-12-03 15:06:45.219 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:06:45.219 ThaliTest[2462:2303436] server session: stateC,hange:2->0 Apple-Iphone6-1_PT7057
2015-12-03 15:06:45.223 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:06:45.224 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03T14:06:45.238Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:06:45.245 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:06:47.429 ThaliTest[2462:2304411] server session: connected
2015-12-03 15:06:47.430 ThaliTest[2462:2304411] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:06:47.440 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:06:47.447Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:47.525Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03T14:06:47.539Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:06:49.670Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:49.671Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:49.672Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:49.675Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:06:49.675Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:06:49.676Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:06:49.677 ThaliTest[2462:2303565] jxcore: disconnect
,2015-12-03 15:06:49.679 ThaliTest[2462:2303565] client session: disconnectFromPeer: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:06:49.680 ThaliTest[2462:2303565] client session: disconnect
2015-12-03 15:06:49.680 ThaliTest[2462:2303565] client session:, stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:06:49.684 ThaliTest[2462:2303565] jxcore: disconnect: success
2015-12-03T14:06:49.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHlg==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:49.691Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:06:49.691Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:06:49.691Z SendDataConnector.j,s: do connect now
2015-12-03 15:06:49.692 ThaliTest[2462:2303565] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:49.693 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:06:49.693 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:06:49.708Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:52.619 ThaliTest[2462:2304411] client session: connected
2015-12-03 15:06:52.619 ThaliTest[2462:2304411] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:06:52.680 ThaliTest[2462:2304384] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:06:52.681 ThaliTest[2462:2304384] jxcore: connect: success
2015-12-03T14:06:52.682Z SendDataConnector.js: CLIENT connected, to 50353, error: null
2015-12-03T14:06:52.683Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:52.687 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:06:52.688 ThaliTest[2462:2303436] client: new accepted socket: 0x1b5891b0
,2015-12-03T14:06:52.701Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:06:53.048Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:06:53.558Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:06:57.726 ThaliTest[2462:2304384] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:06:57.781 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:06:57.782 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:06:57.783 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:06:57.784 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:06:57.784 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:57.799 ThaliTest[2462:2303436] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:06:58.361 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:06:58.361 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:06:58.363 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:06:58.364 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:06:58.364 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03 15:06:58.376 ThaliTest[2462:2303436] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:00.027 ThaliTest[2462:2304288] server session: connected
2015-12-03 15:07:00.027 ThaliTest[2462:2304288] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:07:00.047 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:07:00.057Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:00.593Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-03T14:07:00.606Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-03T14:07:00.628Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-12-03T14:07:00.642Z SendDataTCPServer.js: TCP/IP server has received 44640 bytes of data
,2015-12-03T14:07:00.656Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-12-03T14:07:00.680Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-03T14:07:00.694Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-12-03T14:07:00.708Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:07:00.720 ThaliTest[2462:2304424] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03 15:07:00.743 ThaliTest[2462:2304431] server session: connected
2015-12-03 15:07:00.743 ThaliTest[2462:2304431] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:00.750 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:07:00.757Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:00.960Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-03T14:07:00.975Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-03T14:07:01.009Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-03T14:07:01.026Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-03T14:07:01.045Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-03T14:07:01.063Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:07:03.564Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:03.565Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:03.566Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:03.567Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:03.568Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:03.569 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:07:03.570 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:07:03.571 ThaliTest[2462:2303436] client relay: 0x1b5891b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b465ec0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:07:03.571 ThaliTest[2462:2303436] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJE,g==
2015-12-03 15:07:03.572 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:03.572 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:07:03.573 ThaliTest[2462:2303436] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:03.575 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:08.574Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:08.574Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:11.353 ThaliTest[2462:2304288] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:13.583 ThaliTest[2462:2303565] jxcore: disconnect
,2015-12-03 15:07:13.584 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:07:13.585Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:13.585Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
,2015-12-03T14:07:13.586Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:07:13.586Z SendDataConnector.js: do connect now
,2015-12-03 15:07:13.587 ThaliTest[2462:2303565] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:13.588 ThaliTest[2462:2303565] client session: connect
2015-12-03 15:07:13.589 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:16.664 ThaliTest[2462:2304288] client session: connected
,2015-12-03 15:07:16.665 ThaliTest[2462:2304288] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:16.731 ThaliTest[2462:2304488] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:16.732 ThaliTest[2462:2304488] jxcore: connect: success
2015-12-03T14:07:16.734Z SendDataConnector.js: CLIENT connected, to 50358, error: null
2015-12-03T14:07:16.734Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:16.738 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:07:16.739 ThaliTest[2462:2303436] client: new accepted socket: 0x17637dc0
,2015-12-03T14:07:16.751Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:07:22.512 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:07:22.513 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:07:22.513 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:07:22.514 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:07:22.515 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:07:22.515 ThaliTest[2462:2303436] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03T14:07:22.521Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:07:22.581 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:07:22.582 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:22.593 ThaliTest[2462:2303436] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:24.920 ThaliTest[2462:2304504] server session: connected
2015-12-03 15:07:24.921 ThaliTest[2462:2304504] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:24.931 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:07:24.939Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:24.988Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:07:26.817Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:26.817Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:26.818Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:26.819Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:26.819Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:26.821 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:07:26.822 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:07:26.822 ThaliTest[2462:2303436] client relay: 0x17637dc0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b405120 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:07:26.823 ThaliTest[2462:2303436] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJE,g==
2015-12-03 15:07:26.823 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:26.824 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:07:26.824 ThaliTest[2462:2303436] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:26.826 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:31.830Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:31.830Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:34.972 ThaliTest[2462:2304504] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:36.832 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:07:36.833 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:07:36.834Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJ,Eg==
,2015-12-03T14:07:36.835Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
2015-12-03T14:07:36.835Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015,-12-03T14:07:36.835Z SendDataConnector.js: do connect now
,2015-12-03 15:07:36.836 ThaliTest[2462:2303565] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:36.837 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:07:36.838 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:39.689 ThaliTest[2462:2304411] client session: connected
2015-12-03 15:07:39.690 ThaliTest[2462:2304411] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:39.790 ThaliTest[2462:2304411] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:39.791 ThaliTest[2462:2304411] jxcore: connect: success
2015-12-03T14:07:39.792Z SendDataConnector.js: CLIENT connected, to 50362, error: null
,2015-12-03T14:07:39.793Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:39.797 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:07:39.798 ThaliTest[2462:2303436] client: new accepted socket: 0x1b51d460
,2015-12-03T14:07:39.810Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:07:46.110 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:07:46.111 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:07:46.111 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:07:46.112 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:07:46.112 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:07:46.113 ThaliTest[2462:2303436] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03 15:07:46.117 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:07:46.117 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:07:46.131Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:07:46.137 ThaliTest[2462:2303436] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:48.515 ThaliTest[2462:2304533] server session: connected
2015-12-03 15:07:48.516 ThaliTest[2462:2304533] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:48.537 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:07:48.548Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:48.588Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:07:49.868Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:49.869Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:49.870Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:49.871Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:49.872Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:49.874 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:07:49.875 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:07:49.875 ThaliTest[2462:2303436] client relay: 0x1b51d460 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6ba5e0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:07:49.876 ThaliTest[2462:2303436] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJE,g==
2015-12-03 15:07:49.876 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:07:49.877 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:07:49.877 ThaliTest[2462:2303436] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:49.879 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:54.876Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:07:54.876Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:58.578 ThaliTest[2462:2304411] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03 15:07:59.886 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:07:59.887 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:07:59.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJ,Eg==
2015-12-03T14:07:59.888Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
,2015-12-03T14:07:59.888Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:07:59.889Z SendDataConnector.js: do connect now
,2015-12-03 15:07:59.890 ThaliTest[2462:2303565] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:07:59.891 ThaliTest[2462:2303565] client session: connect
,2015-12-03 15:07:59.892 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:02.732 ThaliTest[2462:2304411] client session: connected
2015-12-03 15:08:02.733 ThaliTest[2462:2304411] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:02.754 ThaliTest[2462:2304554] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:02.755 ThaliTest[2462:2304554] jxcore: connect: success
2015-12-03T14:08:02.756Z SendDataConnector.js: CLIENT connected to 50366, error: null
,2015-12-03T14:08:02.757Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:02.761 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:08:02.762 ThaliTest[2462:2303436] client: new accepted socket: 0x1b5d7ad0
,2015-12-03T14:08:02.774Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:08:08.828 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:08:08.828 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:08:08.829 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:08:08.830 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:08:08.830 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:08:08.830 ThaliTest[2462:2303436] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
2015-12-03 15:08:08.835 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:08:08.835 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03T14:08:08.848Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:08:08.855 ThaliTest[2462:2303436] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:11.147 ThaliTest[2462:2304579] server session: connected
2015-12-03 15:08:11.147 ThaliTest[2462:2304579] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:11.158 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:08:11.171Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:11.199Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T14:08:11.214Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:08:12.841Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:12.841Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:12.842Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:12.843Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:08:12.844Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:12.845 ThaliTest[2462:2303436] client: socket closed
2015-12-03 15:08:12.846 ThaliTest[2462:2303436] client relay: socket disconnected
2015-12-03 15:08:12.847 ThaliTest[2462:2303436] client relay: 0x1b5d7ad0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x175ae5a0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:08:12.847 ThaliTest[2462:2303436] client session: socket closed: Apple-IpadAir2-1_PT7511.wgBJE,g==
2015-12-03 15:08:12.848 ThaliTest[2462:2303436] client session: onLinkFailure: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:12.848 ThaliTest[2462:2303436] client session: disconnect
2015-12-03 15:08:12.849 ThaliTest[2462:2303436] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:12.851 ThaliTest[2462:2303436] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:08:17.850Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03T14:08:17.850Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:21.206 ThaliTest[2462:2304554] server session: not connected Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:22.856 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:08:22.857 ThaliTest[2462:2303565] jxcore: disconnect: fail
2015-12-03T14:08:22.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJ,Eg==
2015-12-03T14:08:22.858Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT7511.wgBJEg== with availability status: true
,2015-12-03T14:08:22.859Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03T14:08:22.859Z SendDataConnector.js: do connect now
,2015-12-03 15:08:22.860 ThaliTest[2462:2303565] jxcore: connect Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:22.861 ThaliTest[2462:2303565] client session: connect
2015-12-03 15:08:22.862 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:25.864 ThaliTest[2462:2304579] client session: connected
2015-12-03 15:08:25.865 ThaliTest[2462:2304579] client session: stateChange:1->2 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:25.873 ThaliTest[2462:2304579] client session: fireConnectCallback: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:25.874 ThaliTest[2462:2304579] jxcore: connect: success
2015-12-03T14:08:25.876Z SendDataConnector.js: CLIENT connected to 50370, error: null
,2015-12-03T14:08:25.876Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:25.880 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:08:25.881 ThaliTest[2462:2303436] client: new accepted socket: 0x1b5f45e0
,2015-12-03T14:08:25.893Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:08:31.581 ThaliTest[2462:2303436] multipeer session: reset timer
2015-12-03 15:08:31.582 ThaliTest[2462:2303436] multipeer session: stop timer
2015-12-03 15:08:31.582 ThaliTest[2462:2303436] multipeer session: start timer: 0x1b6c39a0
2015-,12-03 15:08:31.583 ThaliTest[2462:2303436] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7511)
2015-12-03 15:08:31.583 ThaliTest[2462:2303436] server session: disconnect
2015-12-03 15:08:31.584 ThaliTest[2462:2303436] server session: state,Change:2->0 Apple-IpadAir2-1_PT7511
,2015-12-03T14:08:31.597Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:08:31.645 ThaliTest[2462:2303436] server session: connect
2015-12-03 15:08:31.646 ThaliTest[2462:2303436] server session: stateChange:0->1 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:31.653 ThaliTest[2462:2303436] server: accepting invitation Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:34.241 ThaliTest[2462:2304579] server session: connected
2015-12-03 15:08:34.242 ThaliTest[2462:2304579] server session: stateChange:1->2 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:34.250 ThaliTest[2462:2303436] server relay: connected (to port: 50334)
,2015-12-03T14:08:34.259Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:34.299Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:08:35.958Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:35.958Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:35.959Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:35.961Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:08:35.961Z SendDataConnector.js: Stop data retrieving timer
2015-12-03T14:08:35.962Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:08:35.963 ThaliTest[2462:2303565] jxcore: disconnect
,2015-12-03 15:08:35.964 ThaliTest[2462:2303565] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:08:35.964 ThaliTest[2462:2303565] client session: disconnect
2015-12-03 15:08:35.966 ThaliTest[2462:2303565] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7511.wgBJEg==
,2015-12-03 15:08:35.969 ThaliTest[2462:2303565] jxcore: disconnect: success
2015-12-03T14:08:35.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7511.wgBJEg==
---- round done--------
,device[3]: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:08:35.974Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:35.974Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:35.975Z SendDataConnector.js: do connect now
,2015-12-03 15:08:35.976 ThaliTest[2462:2303565] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:35.978 ThaliTest[2462:2303565] client session: connect
2015-12-03 15:08:35.979 ThaliTest[2462:2303565] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:08:35.988Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:38.441 ThaliTest[2462:2304623] client session: connected
2015-12-03 15:08:38.442 ThaliTest[2462:2304623] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:08:38.450 ThaliTest[2462:2304611] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:38.451 ThaliTest[2462:2304611] jxcore: connect: success
2015-12-03T14:08:38.451Z SendDataConnector.js: CLIENT connected ,to 50375, error: null
2015-12-03T14:08:38.452Z SendDataConnector.js: CLIENT starting client 
2015-12-03 15:08:38.456 ThaliTest[2462:2303436] client: relay established
2015-12-03 15:08:38.457 ThaliTest[2462:2303436] client: new accepted socket: 0x1b6c788,0
,2015-12-03T14:08:38.468Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:08:38.741Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T14:08:38.755Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:08:38.768Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T14:08:38.780Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:08:38.806Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:08:38.806Z SendDataConnector.js: got all data for this round
,2015-12-03T14:08:38.807Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:08:38.807Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:08:38.807 ThaliTest[2462:2303565] jxcore: disconnect
2015-12-03 15:08:38.808 ThaliTest[2462:2303565] cli,ent session: disconnectFromPeer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:38.808 ThaliTest[2462:2303565] client session: disconnect
2015-12-03 15:08:38.808 ThaliTest[2462:2303565] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:08:38.809 ThaliTest[2462:2303565] jxcore: disconnect: success
2015-12-03T14:08:38.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7727","time":214219,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT2690.vOZHlg==","time":104478,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT7511.wgBJEg==","time":106269,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone6-1_PT7057.4CFLyQ==","time":2832,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 2832 ms, 99% : 2832 ms, 95 : 2832 ms, 90% : 2832 ms.
Result count 1, range 2832 ms to  2832 ms.
,sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone5-1_PT2690.vOZHlg==, Tried : 5
- Peer ID : Apple-IpadAir2-1_PT7511.wgBJEg==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T14:08:38.814Z SendDataConnector.j,s: CLIENT Stop now
,2015-12-03T14:08:38.814Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:08:44.298 ThaliTest[2462:2304623] server session: not connected Apple-IpadAir2-1_PT7511
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-03 15:08:47.177 ThaliTest[2462:2303565] jxcore: stopBroadcasting
,2015-12-03 15:08:47.178 ThaliTest[2462:2303565] THEMultipeerSession stopping peer
,2015-12-03 15:08:47.179 ThaliTest[2462:2303565] multipeer session: stop timer
,2015-12-03 15:08:47.180 ThaliTest[2462:2303565] server session: disconnect
2015-12-03 15:08:47.181 ThaliTest[2462:2303565] server session: stateChange:2->0 Apple-IpadAir2-1_PT7511
,2015-12-03 15:08:47.190 ThaliTest[2462:2303565] server session: disconnect
2015-12-03 15:08:47.191 ThaliTest[2462:2303565] server session: stateChange:2->0 Apple-Iphone6-1_PT7057
,2015-12-03 15:08:47.197 ThaliTest[2462:2303565] server session: disconnect
2015-12-03 15:08:47.198 ThaliTest[2462:2303565] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:08:47.270 ThaliTest[2462:2303565] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-03T14:08:47.291Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:47.293Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:47.295Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:08:47.295Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT7057.4CFLyQ==\",\"time\":2832,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],,\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5-1_PT2690.vOZHlg==\",\"time\":104478,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-IpadAir2-1_PT7511.wgBJEg==\",\"time,\":106269,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
