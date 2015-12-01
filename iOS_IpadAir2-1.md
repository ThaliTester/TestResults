#### Test 519863408c638e9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C3F2920D-407F-47A4-9238-80633B76DCD7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C3F2920D-407F-47A4-9238-80633B76DCD7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74708AE8-FEE4-4D3D-911E-E753C5AD3ED2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58398"
,(lldb)     command script import "/tmp/C3F2920D-407F-47A4-9238-80633B76DCD7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 11:46:45.072 ThaliTest[1682:2637805] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21485CDB-2A05-4CF6-931B-057B1A09B181/Library/Cookies/Cookies.binarycookies
,2015-12-01 11:46:45.374 ThaliTest[1682:2637805] Apache Cordova native platform version 3.9.2 is starting.
2015-12-01 11:46:45.375 ThaliTest[1682:2637805] Multi-tasking -> Device: YES, App: YES
,2015-12-01 11:46:45.381 ThaliTest[1682:2637805] Unlimited access to network resources
,2015-12-01 11:46:45.387 ThaliTest[1682:2637805] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 11:46:49.564 ThaliTest[1682:2637805] Resetting plugins due to page load.
,2015-12-01 11:46:50.898 ThaliTest[1682:2637805] Finished load of: file:///var/mobile/Containers/Bundle/Application/74708AE8-FEE4-4D3D-911E-E753C5AD3ED2/ThaliTest.app/www/index.html
,2015-12-01 11:46:51.037 ThaliTest[1682:2637805] JXcore Cordova plugin initializing
2015-12-01 11:46:51.038 ThaliTest[1682:2637998] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT7493
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63814
,2015-12-01 11:54:34.494 ThaliTest[1682:2637998] jxcore: startBroadcasting
,2015-12-01 11:54:34.500 ThaliTest[1682:2637998] server: starting Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:34.500 ThaliTest[1682:2637998] multipeer session: start timer: 0x18478f70
,2015-12-01 11:54:34.501 ThaliTest[1682:2637998] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7493
2015-12-01 11:54:34.501 ThaliTest[1682:2637998] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-01T10:54:34.502Z SendDataTCPServer.js: TCP/IP server is bound to port: 63814
,2015-12-01 11:54:35.194 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:35.197Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:35.197Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:35.197Z SendDataConnector.js: do connect now
2015-12-01 11:54:35.197 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:35.197 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:54:35.197 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:35.513 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9531.MSI13Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:36.772 ThaliTest[1682:2637805] client: found peer: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:38.188 ThaliTest[1682:2638866] client session: connected
2015-12-01 11:54:38.188 ThaliTest[1682:2638866] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:38.203 ThaliTest[1682:2638856] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:38.203 ThaliTest[1682:2638856] jxcore: connect: success
,2015-12-01T10:54:38.204Z SendDataConnector.js: CLIENT connected to 63817, error: null
2015-12-01T10:54:38.204Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:38.205 ThaliTest[1682:2637805] client: relay established
,2015-12-01 11:54:38.206 ThaliTest[1682:2637805] client: new accepted socket: 0x18787e80
,2015-12-01T10:54:38.219Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:38.790Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 11:54:38.864 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:54:38.864 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:54:38.864 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-12-01 11:54:38.864 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:54:38.864 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
,2015-12-01 11:54:38.867 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01 11:54:39.195 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:54:39.195 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:54:39.195 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
,2015-12-01 11:54:39.195 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:54:39.196 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:39.198 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:40.306 ThaliTest[1682:2637805] multipeer session: reset timer
,2015-12-01 11:54:40.306 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:54:40.306 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-12-01 11:54:40.306 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:54:40.306 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone6-1_PT127
,2015-12-01 11:54:40.309 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone6-1_PT127
,2015-12-01 11:54:41.426 ThaliTest[1682:2638858] server session: connected
2015-12-01 11:54:41.426 ThaliTest[1682:2638858] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:54:41.436 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01T10:54:41.439Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:42.015Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-12-01T10:54:42.027Z SendDataTCPServer.js: TCP/IP server has received 56544 bytes of data
,2015-12-01T10:54:42.041Z SendDataTCPServer.js: TCP/IP server has received 76384 bytes of data
,2015-12-01T10:54:42.341Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-12-01T10:54:42.354Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 11:54:42.600 ThaliTest[1682:2638858] server session: connected
2015-12-01 11:54:42.600 ThaliTest[1682:2638858] server session: stateChange:1->2 Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:42.609 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01 11:54:42.610 ThaliTest[1682:2638858] server session: connected
2015-12-01 11:54:42.610 ThaliTest[1682:2638858] server session: stateChange:1->2 Apple-Iphone6-1_PT127
,2015-12-01 11:54:42.616 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
2015-12-01T10:54:42.617Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:42.618Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:42.934Z SendDataTCPServer.js: TCP/IP server has received 52418 bytes of data
,2015-12-01T10:54:42.945Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T10:54:42.948Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-01T10:54:42.962Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-01 11:54:42.970 ThaliTest[1682:2638856] server session: not connected Apple-Iphone6-1_PT127
,2015-12-01T10:54:42.985Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-01T10:54:42.998Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 11:54:43.022 ThaliTest[1682:2638858] server session: not connected Apple-Iphone5s-1_PT9146
,2015-12-01 11:55:10.307 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01T10:55:28.792Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:55:28.792Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:55:28.793Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:55:28.793Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:55:28.793Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:55:28.794 ThaliTest[1682:2637805] client: socket closed
,2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client relay: socket disconnected
2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client relay: 0x18787e80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client session: socket closed: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client session: onLinkFailure,: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:55:28.795 ThaliTest[1682:2637805] client session: stateChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:28.797 ThaliTest[1682:2637805] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:32.654 ThaliTest[1682:2639008] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01T10:55:33.793Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:55:33.794Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:38.805 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:55:38.806 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T10:55:38.806Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:55:38.806Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT9146.afM/PQ== with availability status: true
2015-12-01T10:55:38.806Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:55:38.806Z SendDataConnector.js: do connect now
,2015-12-01 11:55:38.806 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:38.807 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:55:38.807 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:38.810 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:38.810 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:38.810 ThaliTest[1682:263780,5] client session: onLinkFailure: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:38.810 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:55:38.810 ThaliTest[1682:2637805] client session: stateChange:1->0 Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:38.810 ThaliTest[1682:2637805] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:38.810 ThaliTest[1682:2637805] jxcore: connect: fail: Peer disconnected
2015-12-01T10:55:38.812Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-01T10:55:38.812Z SendDataConnector.js: CLIENT Can not Connect:, Peer disconnected
2015-12-01T10:55:38.812Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:55:40.307 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:55:40.317 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:40.318 ThaliTest[1682:2637805] client: found peer: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
2015-12-01 11:55:40.318 ThaliTest[,1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:55:42.644 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:55:42.644 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:55:42.644 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-12-01 11:55:42.644 ThaliTest[1682:2637805] server: disconnecting to refresh session (Apple-Iphone5-1_PT9531)
2015-12-01 11:55:42.644 ThaliTest[1682:2637805] server session: disconnect
2015-12-01 11:55:42.644 ThaliTest[1682:2637805] server session: stateChange:2->0 Apple-Iphone5-1_PT9531
,2015-12-01T10:55:42.646Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01 11:55:42.646 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:55:42.646 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
,2015-12-01 11:55:42.649 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01T10:55:43.820Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:55:43.820Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:45.430 ThaliTest[1682:2639027] server session: connected
2015-12-01 11:55:45.431 ThaliTest[1682:2639027] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:55:45.440 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01T10:55:45.452Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:55:45.811Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-01T10:55:45.824Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 11:55:47.809 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:47.809 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-01 11:55:48.827 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:55:48.827 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T10:55:48.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/,PQ==
2015-12-01T10:55:48.828Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT9146.afM/PQ== with availability status: true
2015-12-01T10:55:48.828Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:55:48.828Z SendDataConnector.js: do connect now
,2015-12-01 11:55:48.828 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:48.828 ThaliTest[1682:2637998] client session: connect
,2015-12-01 11:55:48.829 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:52.252 ThaliTest[1682:2639025] client session: connected
2015-12-01 11:55:52.252 ThaliTest[1682:2639025] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:52.273 ThaliTest[1682:2639008] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:52.274 ThaliTest[1682:2639008] jxcore: connect: success
2015-12-01T10:55:52.274Z SendDataConnector.js: CLIENT connected to 63827, error: null
2015-12-01T10:55:52.274Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:55:52.275 ThaliTest[1682:2637805] client: relay established
2015-12-01 11:55:52.276 ThaliTest[1682:2637805] client: new accepted socket: 0x1878a540
,2015-12-01T10:55:52.288Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:56:12.645 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:56:12.654 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:12.654 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:56:17.802 ThaliTest[1682:2639025] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01T10:56:42.310Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:56:42.310Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:56:42.310Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:56:42.311Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:56:42.311Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client: socket closed
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client relay: socket disconnected
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client relay: 0x1878a540 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client session: socket closed: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client session: onLinkFailure: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:56:42.312 ThaliTest[1682:2637805] client session: stateChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:42.314 ThaliTest[1682:2637805] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:42.645 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:56:42.654 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:42.655 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:56:45.675 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:56:45.675 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:56:45.675 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-,12-01 11:56:45.675 ThaliTest[1682:2637805] server: disconnecting to refresh session (Apple-Iphone5-1_PT9531)
2015-12-01 11:56:45.675 ThaliTest[1682:2637805] server session: disconnect
2015-12-01 11:56:45.675 ThaliTest[1682:2637805] server session: stateChange:2->0 Apple-Iphone5-1_PT9531
,2015-12-01 11:56:45.677 ThaliTest[1682:2637805] server session: connect
,2015-12-01 11:56:45.678 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
,2015-12-01T10:56:45.679Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 11:56:45.680 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01T10:56:47.312Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T10:56:47.312Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:48.269 ThaliTest[1682:2639159] server session: connected
2015-12-01 11:56:48.269 ThaliTest[1682:2639159] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:56:48.278 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01T10:56:48.283Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:56:48.960Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-01T10:56:48.973Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 11:56:52.318 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:56:52.318 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T10:56:52.318Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/,PQ==
2015-12-01T10:56:52.319Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT9146.afM/PQ== with availability status: true
2015-12-01T10:56:52.319Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:56:52.319Z SendDataConnector.js: do connect now
,2015-12-01 11:56:52.319 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:52.319 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:56:52.319 ThaliTest[1682:2637998] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:56.582 ThaliTest[1682:2639160] client session: connected
2015-12-01 11:56:56.582 ThaliTest[1682:2639160] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:56.722 ThaliTest[1682:2639160] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:56.722 ThaliTest[1682:2639160] jxcore: connect: success
2015-12-01T10:56:56.722Z SendDataConnector.js: CLIENT connected to 63834, error: null
2015-12-01T10:56:56.722Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:56:56.723 ThaliTest[1682:2637805] client: relay established
2015-12-01 11:56:56.724 ThaliTest[1682:2637805] client: new accepted socket: 0x1845f6a0
,2015-12-01T10:56:56.737Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:56:58.671 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:58.671 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:58.671 ThaliTest[1682:2637805] client session: onLinkFailure: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:56:58.671 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:56:58.671 ThaliTest[1682:2637805] client session: sta,teChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:56:58.675 ThaliTest[1682:2637805] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:57:02.288 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 11:57:15.676 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:57:38.458 ThaliTest[1682:2639159] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01 11:57:45.676 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:57:46.267 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:57:46.267 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:57:46.793Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:57:46.793Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:57:46.793Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:57:46.793Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:57:46.794Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:57:48.429 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:57:48.429 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:57:48.429 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-12-01 11:57:48.429 ThaliTest[1682:2637805] server: disconnecting to refresh session (Apple-Iphone5-1_PT9531)
2015-12-01 11:57:48.429 ThaliTest[1682:2637805] server session: disconnect
,2015-12-01 11:57:48.429 ThaliTest[1682:2637805] server session: stateChange:2->0 Apple-Iphone5-1_PT9531
,2015-12-01 11:57:48.431 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:57:48.431 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
,2015-12-01 11:57:48.434 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01T10:57:48.440Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 11:57:51.046 ThaliTest[1682:2639307] server session: connected
2015-12-01 11:57:51.047 ThaliTest[1682:2639307] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:57:51.112 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01T10:57:51.122Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:57:51.198Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01T10:57:51.799Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T10:57:51.799Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:57:51.800Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:57:56.812 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:57:56.812 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T10:57:56.812Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T10:57:56.813Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT9146.afM/PQ== with availability status: true
2015-12-01T10:57:56.813Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:57:56.813Z SendDataConnector.js: do connect now
,2015-12-01 11:57:56.813 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:57:56.813 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:57:56.813 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:58:03.686 ThaliTest[1682:2639293] client session: connected
2015-12-01 11:58:03.686 ThaliTest[1682:2639293] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:58:03.750 ThaliTest[1682:2639291] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:58:03.750 ThaliTest[1682:2639291] jxcore: connect: success
,2015-12-01T10:58:03.751Z SendDataConnector.js: CLIENT connected to 63843, error: null
,2015-12-01T10:58:03.751Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:58:03.752 ThaliTest[1682:2637805] client: relay established
,2015-12-01 11:58:03.752 ThaliTest[1682:2637805] client: new accepted socket: 0x183bdf60
,2015-12-01T10:58:03.765Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 11:58:18.430 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:58:18.441 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:58:18.441 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:58:33.969 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:58:33.970 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:58:33.970 ThaliTest[1682:263780,5] client session: onLinkFailure: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:58:33.970 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:58:33.970 ThaliTest[1682:2637805] client session: stateChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:58:33.973 ThaliTest[1682:2637805] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:58:34.148 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 11:58:41.356 ThaliTest[1682:2639400] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01 11:58:48.430 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:58:51.331 ThaliTest[1682:2637805] multipeer session: reset timer
2015-12-01 11:58:51.331 ThaliTest[1682:2637805] multipeer session: stop timer
2015-12-01 11:58:51.331 ThaliTest[1682:2637805] multipeer session: start timer: 0x18478f70
2015-,12-01 11:58:51.331 ThaliTest[1682:2637805] server: disconnecting to refresh session (Apple-Iphone5-1_PT9531)
2015-12-01 11:58:51.331 ThaliTest[1682:2637805] server session: disconnect
2015-12-01 11:58:51.332 ThaliTest[1682:2637805] server session: stateChange:2->0 Apple-Iphone5-1_PT9531
,2015-12-01 11:58:51.334 ThaliTest[1682:2637805] server session: connect
2015-12-01 11:58:51.334 ThaliTest[1682:2637805] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
2015-12-01T10:58:51.334Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 11:58:51.337 ThaliTest[1682:2637805] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01T10:58:53.790Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T10:58:53.790Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:58:53.791Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:58:53.792Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T10:58:53.792Z SendDataConnector.js: Stop data retrieving timer
2015-12-01T10:58:53.792Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:58:53.793 ThaliTest[1682:2637998] jxcore: disconnect
,2015-12-01 11:58:53.793 ThaliTest[1682:2637998] jxcore: disconnect: fail
,2015-12-01T10:58:53.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/PQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:58:53.794Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:58:53.795Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:58:53.795Z SendDataConnector.js: do connect now
,2015-12-01 11:58:53.795 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:58:53.795 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:58:53.795 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:58:53.799Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 11:58:53.807 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:58:53.807 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:58:53.808 ThaliTest[1682:2637805] client session: onLinkFailure: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:58:53.808 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 11:58:53.808 ThaliTest[1682:2637805] client session: stateChange:1->0 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:58:53.860 ThaliTest[1682:2637805] client session: fireConnectCallback: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:58:53.860 ThaliTest[1682:2637805] jxcore: connect: fail: Peer disconnected
2015-12-01T10:58:53.860Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-01T10:58:53.860Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-01T10:58:53.860Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:58:53.861Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9531.MSI13Q==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:58:54.080 ThaliTest[1682:2639437] server session: connected
2015-12-01 11:58:54.080 ThaliTest[1682:2639437] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:58:54.135 ThaliTest[1682:2637805] server relay: connected (to port: 63814)
,2015-12-01T10:58:54.141Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:58:54.460Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-01T10:58:54.471Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01T10:58:58.863Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:58:58.863Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:58:58.863Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:59:03.872 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:59:03.872 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T10:59:03.872Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13,Q==
2015-12-01T10:59:03.872Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9531.MSI13Q== with availability status: true
2015-12-01T10:59:03.872Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:59:03.872Z SendDataConnector.js: do connect now
2015-12-01 11:59:03.873 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:03.873 ThaliTest[1682:2637998] client: connect: unreachable Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:03.873 ThaliTest[1682:2637998] jxcore: connect: fail: Peer unreachable
2015-12-01T10:59:03.874Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-01T10:59:03.874Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-01T10:59:03.874Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T10:59:03.874Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:59:08.875Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:59:08.875Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:59:08.876Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:59:13.887 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:59:13.887 ThaliTest[1682:2637998] jxcore: disconnect: fail
,2015-12-01T10:59:13.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:59:13.888Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9531.MSI13Q== with availability status: true
2015-12-01T10:59:13.888Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:59:13.888Z SendDataConnector.js: do connect now
,2015-12-01 11:59:13.888 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:13.889 ThaliTest[1682:2637998] client: connect: unreachable Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:13.889 ThaliTest[1682:2637998] jxcore: connect: fail: Peer unreachable
2015-12-01T10:59:13.889Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-01T10:59:13.889Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-01T10:59:13.889Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T10:59:13.889Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T10:59:18.893Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:59:18.893Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:59:18.893Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:59:21.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:59:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9531.MSI13Q==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 11:59:23.902 ThaliTest[1682:2637998] jxcore: disconnect
2015-12-01 11:59:23.902 ThaliTest[1682:2637998] jxcore: disconnect: fail
,2015-12-01T10:59:23.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:59:23.903Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9531.MSI13Q== with availability status: true
,2015-12-01T10:59:23.903Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:59:23.903Z SendDataConnector.js: do connect now
,2015-12-01 11:59:23.904 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:23.904 ThaliTest[1682:2637998] client session: connect
2015-12-01 11:59:23.904 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:27.031 ThaliTest[1682:2639437] client session: connected
2015-12-01 11:59:27.031 ThaliTest[1682:2639437] client session: stateChange:1->2 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:27.040 ThaliTest[1682:2639488] client session: fireConnectCallback: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:27.040 ThaliTest[1682:2639488] jxcore: connect: success
2015-12-01T10:59:27.040Z SendDataConnector.js: CLIENT connected to 63850, error: null
2015-12-01T10:59:27.041Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:59:27.042 ThaliTest[1682:2637805] client: relay established
2015-12-01 11:59:27.042 ThaliTest[1682:2637805] client: new accepted socket: 0x16750760
,2015-12-01T10:59:27.055Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:59:27.572Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01T10:59:27.610Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 11:59:44.389 ThaliTest[1682:2639540] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01 11:59:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 11:59:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:59:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T11:00:17.612Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T11:00:17.613Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T11:00:17.613Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T11:00:17.613Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T11:00:17.613Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 12:00:17.614 ThaliTest[1682:2637805] client: socket closed
,2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client relay: socket disconnected
2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client relay: 0x16750760 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client session: socket closed: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client session: onLinkFailure:, Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client session: disconnect
2015-12-01 12:00:17.615 ThaliTest[1682:2637805] client session: stateChange:2->0 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:17.617 ThaliTest[1682:2637805] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:00:21.342 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:21.343 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T11:00:22.615Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T11:00:22.615Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:27.617 ThaliTest[1682:2637998] jxcore: disconnect
,2015-12-01 12:00:27.617 ThaliTest[1682:2637998] jxcore: disconnect: fail
2015-12-01T11:00:27.618Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T11:00:27.618Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9531.MSI13Q== with availability status: true
,2015-12-01T11:00:27.618Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T11:00:27.618Z SendDataConnector.js: do connect now
,2015-12-01 12:00:27.619 ThaliTest[1682:2637998] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:00:27.619 ThaliTest[1682:2637998] client session: connect
2015-12-01 12:00:27.619 ThaliTest[1682:2637998] client session: stateChange:0->1 Apple,-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:32.555 ThaliTest[1682:2639607] client session: connected
2015-12-01 12:00:32.555 ThaliTest[1682:2639607] client session: stateChange:1->2 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:32.565 ThaliTest[1682:2639606] client session: fireConnectCallback: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:00:32.565 ThaliTest[1682:2639606] jxcore: connect: success
2015-12-01T11:00:32.565Z SendDataConnector.js: CLIENT connected to 63856, error: null
2015-12-01T11:00:32.566Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 12:00:32.567 ThaliTest[1682:2637805] client: relay established
2015-12-01 12:00:32.567 ThaliTest[1682:2637805] client: new accepted socket: 0x166c1140
,2015-12-01T11:00:32.580Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 12:00:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:00:51.343 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:00:51.343 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:01:10.406 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:01:10.406 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:01:15.198 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:01:21.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:01:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:01:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01T11:01:22.607Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T11:01:22.607Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T11:01:22.608Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T11:01:22.609Z SendDataConnector.js: CLIENT Stop now
2015-12-01T11:01:22.609Z SendDataConnector.js: Stop data retrieving timer
2015-12-01T11:01:22.609Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 12:01:22.610 ThaliTest[1682:2637998] jxcore: disconnect
,2015-12-01 12:01:22.610 ThaliTest[1682:2637998] client session: disconnectFromPeer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:01:22.610 ThaliTest[1682:2637998] client session: disconnect
2015-12-01 12:01:22.610 ThaliTest[1682:2637998] client session: stateChange:2->0 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:01:22.613 ThaliTest[1682:2637998] jxcore: disconnect: success
2015-12-01T11:01:22.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
---- round done--------
2015-12-01T11:01:22.613Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 12:01:41.858 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:01:41.858 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:01:45.074 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:01:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:01:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:01:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:02:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:02:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:02:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:02:51.342 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:03:10.288 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:03:10.288 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:03:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:03:21.893 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:03:22.711 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:03:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:03:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:03:52.168 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:04:10.091 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:04:10.091 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:04:15.235 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:04:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:04:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:04:21.553 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:04:36.258 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:04:36.258 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:04:37.251 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:04:40.542 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:04:40.542 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:04:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:04:51.340 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:04:52.938 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:05:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:05:22.387 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:05:22.387 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:05:40.203 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:05:40.203 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:05:45.393 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:05:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:05:51.342 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:05:51.342 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:06:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:06:21.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:06:22.166 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:06:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:06:51.341 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 12:06:51.342 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 12:07:10.365 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:07:10.365 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:07:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:07:21.339 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:07:21.868 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 12:07:34.376 ThaliTest[1682:2637805] client: lost peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 12:07:34.376 ThaliTest[1682:2637805] client session: onPeerLost: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 12:07:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:07:52.249 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:08:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:08:21.340 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:08:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:08:53.053 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:09:21.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:09:21.359 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:09:51.332 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:09:51.340 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:10:21.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:10:51.333 ThaliTest[1682:2637805] multipeer session: restart
,2015-12-01 12:10:52.567 ThaliTest[1682:2637805] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,timeout now
dun
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7493","time":1000022,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5s-1_PT9146.afM/PQ==","time":258594,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5-1_PT9531.MSI13Q==","time":148813,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
Results list d,oes not contain any items
sendList failed peers count : 2 [100 %]
- Peer ID : Apple-Iphone5s-1_PT9146.afM/PQ==, Tried : 5
,- Peer ID : Apple-Iphone5-1_PT9531.MSI13Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-01T11:11:14.516Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-01 12:11:15.141 ThaliTest[1682:2637998] jxcore: stopBroadcasting
2015-12-01 12:11:15.142 ThaliTest[1682:2637998] THEMultipeerSession stopping peer
,2015-12-01 12:11:15.142 ThaliTest[1682:2637998] multipeer session: stop timer
2015-12-01 12:11:15.142 ThaliTest[1682:2637998] server session: disconnect
,2015-12-01 12:11:15.142 ThaliTest[1682:2637998] server session: stateChange:2->0 Apple-Iphone5s-1_PT9146
,2015-12-01 12:11:15.147 ThaliTest[1682:2637998] server session: disconnect
,2015-12-01 12:11:15.148 ThaliTest[1682:2637998] server session: stateChange:2->0 Apple-Iphone5-1_PT9531
,2015-12-01 12:11:15.151 ThaliTest[1682:2637998] server session: disconnect
2015-12-01 12:11:15.151 ThaliTest[1682:2637998] server session: stateChange:2->0 Apple-Iphone6-1_PT127
,2015-12-01 12:11:15.154 ThaliTest[1682:2637998] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-01T11:11:15.169Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01T11:11:15.170Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01T11:11:15.170Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01T11:11:15.171Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT9146.afM/PQ==\",\"time\":258594,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\,"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-Iphone5-1_PT9531.MSI13Q==\",\"time\":148813,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"ad,dressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
