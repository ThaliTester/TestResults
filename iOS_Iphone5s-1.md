#### Test 51790364a0f6051_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F7E24E4F-43EA-4829-A67C-214666496ED1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F7E24E4F-43EA-4829-A67C-214666496ED1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CBF6FC38-0C86-4F39-A6D6-CC491F8C0F13/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56145"
,(lldb)     command script import "/tmp/F7E24E4F-43EA-4829-A67C-214666496ED1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 07:48:32.282 ThaliTest[1713:1461737] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5FAE032-020D-4AAE-966D-3F6D98C262A5/Library/Cookies/Cookies.binarycookies
,2015-11-26 07:48:32.674 ThaliTest[1713:1461737] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 07:48:32.676 ThaliTest[1713:1461737] Multi-tasking -> Device: YES, App: YES
,2015-11-26 07:48:32.683 ThaliTest[1713:1461737] Unlimited access to network resources
,2015-11-26 07:48:32.690 ThaliTest[1713:1461737] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 07:48:36.035 ThaliTest[1713:1461737] Resetting plugins due to page load.
,2015-11-26 07:48:36.378 ThaliTest[1713:1461737] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/CBF6FC38-0C86-4F39-A6D6-CC491F8C0F13/ThaliTest.app/www/index.html
,2015-11-26 07:48:36.532 ThaliTest[1713:1461737] JXcore Cordova plugin initializing
,2015-11-26 07:48:36.533 ThaliTest[1713:1461861] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT6114
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 62463
,2015-11-26 07:55:07.464 ThaliTest[1713:1461861] jxcore: startBroadcasting
,2015-11-26 07:55:07.477 ThaliTest[1713:1461861] server: starting Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:07.479 ThaliTest[1713:1461861] multipeer session: start timer: 0x1852fd00
2015-11-26 07:55:07.480 ThaliTest[1713:1461861] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:07.481 ThaliTest[1713:1461861] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-26T06:55:07.487Z SendDataTCPServer.js: TCP/IP server is bound to port: 62463
,2015-11-26 07:55:08.176 ThaliTest[1713:1461737] multipeer session: reset timer
2015-11-26 07:55:08.177 ThaliTest[1713:1461737] multipeer session: stop timer
2015-11-26 07:55:08.178 ThaliTest[1713:1461737] multipeer session: start timer: 0x1852fd00
2015-,11-26 07:55:08.179 ThaliTest[1713:1461737] server session: connect
2015-11-26 07:55:08.179 ThaliTest[1713:1461737] server session: stateChange:0->1 Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:08.195 ThaliTest[1713:1461737] server: accepting invitation Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:08.284 ThaliTest[1713:1461737] multipeer session: reset timer
2015-11-26 07:55:08.284 ThaliTest[1713:1461737] multipeer session: stop timer
2015-11-26 07:55:08.285 ThaliTest[1713:1461737] multipeer session: start timer: 0x1852fd00
2015-,11-26 07:55:08.285 ThaliTest[1713:1461737] server session: connect
2015-11-26 07:55:08.286 ThaliTest[1713:1461737] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:08.291 ThaliTest[1713:1461737] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:55:08.665 ThaliTest[1713:1461737] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6002.+4nCyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:08.678Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:08.678 ThaliTest[1713:1461737] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26T06:55:08.679Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:55:08.680Z SendDataConnector.js: do connect now
,2015-11-26 07:55:08.681 ThaliTest[1713:1461861] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:08.682 ThaliTest[1713:1461861] client session: connect
2015-11-26 07:55:08.683 ThaliTest[1713:1461861] client session: stateChange:0->1 Apple-Iphone5-1_PT6002.+4nCyw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2617.KcJttQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:08.879 ThaliTest[1713:1461737] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:10.544 ThaliTest[1713:1462428] server session: connected
2015-11-26 07:55:10.546 ThaliTest[1713:1462428] server session: stateChange:1->2 Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:10.560 ThaliTest[1713:1461737] server relay: connected (to port: 62463)
,2015-11-26T06:55:10.567Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26 07:55:10.598 ThaliTest[1713:1462428] server session: connected
2015-11-26 07:55:10.598 ThaliTest[1713:1462428] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:10.621 ThaliTest[1713:1461737] server relay: connected (to port: 62463)
,2015-11-26T06:55:10.633Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:10.800Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-26T06:55:10.816Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-11-26T06:55:10.833Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-26T06:55:10.850Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-26T06:55:10.880Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-11-26T06:55:10.893Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-11-26T06:55:11.082Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:55:11.089 ThaliTest[1713:1462427] client session: connected
2015-11-26 07:55:11.090 ThaliTest[1713:1462427] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:11.097 ThaliTest[1713:1462427] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:11.098 ThaliTest[1713:1462427] jxcore: connect: success
,2015-11-26T06:55:11.102Z SendDataConnector.js: CLIENT connected to 62468, error: null
2015-11-26T06:55:11.102Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:11.106 ThaliTest[1713:1461737] client: relay established
2015-11-26 07:55:11.107 ThaliTest[1713:1461737] client: new accepted socket: 0x18636120
,2015-11-26T06:55:11.122Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-11-26T06:55:11.124Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:11.522Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26T06:55:11.651Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-26T06:55:11.665Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-26 07:55:11.679 ThaliTest[1713:1462422] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26 07:55:17.012 ThaliTest[1713:1461737] multipeer session: reset timer
2015-11-26 07:55:17.013 ThaliTest[1713:1461737] multipeer session: stop timer
2015-11-26 07:55:17.013 ThaliTest[1713:1461737] multipeer session: start timer: 0x1852fd00
2015-,11-26 07:55:17.014 ThaliTest[1713:1461737] server session: connect
2015-11-26 07:55:17.015 ThaliTest[1713:1461737] server session: stateChange:0->1 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:17.030 ThaliTest[1713:1461737] server: accepting invitation Apple-Iphone6-1_PT8881
,2015-11-26 07:55:19.514 ThaliTest[1713:1462427] server session: connected
2015-11-26 07:55:19.515 ThaliTest[1713:1462427] server session: stateChange:1->2 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:19.527 ThaliTest[1713:1461737] server relay: connected (to port: 62463)
,2015-11-26T06:55:19.537Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:19.790Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-26T06:55:20.024Z SendDataTCPServer.js: TCP/IP server has received 33194 bytes of data
,2015-11-26T06:55:20.040Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:55:20.064 ThaliTest[1713:1462428] server session: not connected Apple-Iphone6-1_PT8881
,2015-11-26 07:55:21.032 ThaliTest[1713:1462428] server session: not connected Apple-IpadAir2-1_PT2617
,2015-11-26T06:55:21.671Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:55:21.672Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:21.674Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:21.675Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:21.675Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:21.677 ThaliTest[1713:1461737] client: socket closed
2015-11-26 07:55:21.678 ThaliTest[1713:1461737] client relay: socket disconnected
2015-11-26 07:55:21.679 ThaliTest[1713:1461737] client relay: 0x18636120 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1851db30 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-26 07:55:21.680 ThaliTest[1713:1461737] client session: socket closed: Apple-Iphone5-1_PT6002.+4nCyw,==
2015-11-26 07:55:21.681 ThaliTest[1713:1461737] client session: onLinkFailure: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:21.681 ThaliTest[1713:1461737] client session: disconnect
2015-11-26 07:55:21.682 ThaliTest[1713:1461737] client session: ,stateChange:2->0 Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:21.684 ThaliTest[1713:1461737] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:26.687Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:26.689Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:31.183 ThaliTest[1713:1461737] multipeer session: reset timer
2015-11-26 07:55:31.184 ThaliTest[1713:1461737] multipeer session: stop timer
2015-11-26 07:55:31.184 ThaliTest[1713:1461737] multipeer session: start timer: 0x1852fd00
2015-,11-26 07:55:31.185 ThaliTest[1713:1461737] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2617)
2015-11-26 07:55:31.186 ThaliTest[1713:1461737] server session: disconnect
2015-11-26 07:55:31.187 ThaliTest[1713:1461737] server session: state,Change:2->0 Apple-IpadAir2-1_PT2617
2015-11-26T06:55:31.198Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-26 07:55:31.257 ThaliTest[1713:1461737] server session: connect
2015-11-26 07:55:31.257 ThaliTest[1713:1461737] server session: stateChange:0->1 Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:31.265 ThaliTest[1713:1461737] server: accepting invitation Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:31.698 ThaliTest[1713:1461861] jxcore: disconnect
2015-11-26 07:55:31.699 ThaliTest[1713:1461861] jxcore: disconnect: fail
2015-11-26T06:55:31.700Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:31.701Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:55:31.701Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-1,1-26T06:55:31.701Z SendDataConnector.js: do connect now
,2015-11-26 07:55:31.702 ThaliTest[1713:1461861] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:31.704 ThaliTest[1713:1461861] client session: connect
2015-11-26 07:55:31.704 ThaliTest[1713:1461861] client session: stateChange:0->1 Apple,-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:33.619 ThaliTest[1713:1462427] server session: connected
2015-11-26 07:55:33.619 ThaliTest[1713:1462427] server session: stateChange:1->2 Apple-IpadAir2-1_PT2617
,2015-11-26 07:55:33.642 ThaliTest[1713:1461737] server relay: connected (to port: 62463)
2015-11-26T06:55:33.644Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:33.696Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:55:34.279 ThaliTest[1713:1462422] client session: connected
2015-11-26 07:55:34.280 ThaliTest[1713:1462422] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:34.290 ThaliTest[1713:1462427] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:34.290 ThaliTest[1713:1462427] jxcore: connect: success
2015-11-26T06:55:34.292Z SendDataConnector.js: CLIENT connected ,to 62472, error: null
2015-11-26T06:55:34.292Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:34.296 ThaliTest[1713:1461737] client: relay established
2015-11-26 07:55:34.297 ThaliTest[1713:1461737] client: new accepted socket: 0x185b2bd0
,2015-11-26T06:55:34.309Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:55:43.699 ThaliTest[1713:1462422] server session: not connected Apple-IpadAir2-1_PT2617
,2015-11-26T06:55:44.385Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:55:44.386Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:44.386Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:44.387Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:44.388Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:44.389 ThaliTest[1713:1461737] client: socket closed
2015-11-26 07:55:44.390 ThaliTest[1713:1461737] client relay: socket disconnected
,2015-11-26 07:55:44.392 ThaliTest[1713:1461737] client relay: 0x185b2bd0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x14de8470 {NSLocalizedDescription=Socket closed by remote peer} 
2015-1,1-26 07:55:44.392 ThaliTest[1713:1461737] client session: socket closed: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:44.393 ThaliTest[1713:1461737] client session: onLinkFailure: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:44.393 ThaliTest[1713,:1461737] client session: disconnect
2015-11-26 07:55:44.394 ThaliTest[1713:1461737] client session: stateChange:2->0 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:44.397 ThaliTest[1713:1461737] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:49.392Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:49.393Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:54.401 ThaliTest[1713:1461861] jxcore: disconnect
2015-11-26 07:55:54.402 ThaliTest[1713:1461861] jxcore: disconnect: fail
2015-11-26T06:55:54.403Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCy,w==
2015-11-26T06:55:54.403Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:55:54.403Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:55:54.404Z SendDataConnector.js: do connect now
2015-11-26 07:55:54.404 ThaliTest[1713:1461861] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:54.405 ThaliTest[1713:1461861] client session: connect
,2015-11-26 07:55:54.406 ThaliTest[1713:1461861] client session: stateChange:0->1 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:57.212 ThaliTest[1713:1462427] client session: connected
2015-11-26 07:55:57.213 ThaliTest[1713:1462427] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:55:57.221 ThaliTest[1713:1462526] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:57.222 ThaliTest[1713:1462526] jxcore: connect: success
2015-11-26T06:55:57.224Z SendDataConnector.js: CLIENT connected to 62474, error: null
2015-11-26T06:55:57.225Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:57.229 ThaliTest[1713:1461737] client: relay established
2015-11-26 07:55:57.230 ThaliTest[1713:1461737] client: new accepted socket: 0x185b2bd0
,2015-11-26T06:55:57.241Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:56:01.187 ThaliTest[1713:1461737] multipeer session: restart
2015-11-26 07:56:01.193 ThaliTest[1713:1461737] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x765e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 1713 stopped
* thread #1: tid = 0x164de9, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x164de9, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000765e2 ThaliTest`main + 50

```
