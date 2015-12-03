#### Test 5253548629578ed_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/88048689-C4CC-4B97-BE75-239C0325F31B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/88048689-C4CC-4B97-BE75-239C0325F31B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5253548629578ed/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05DE7E5E-0871-465B-B0C2-86ADA335B12C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60388"
,(lldb)     command script import "/tmp/88048689-C4CC-4B97-BE75-239C0325F31B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 14:57:55.232 ThaliTest[1897:2986906] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46FFE7B3-0891-40A6-BB81-21DAEA10F77F/Library/Cookies/Cookies.binarycookies
,2015-12-03 14:57:55.509 ThaliTest[1897:2986906] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 14:57:55.510 ThaliTest[1897:2986906] Multi-tasking -> Device: YES, App: YES
,2015-12-03 14:57:55.515 ThaliTest[1897:2986906] Unlimited access to network resources
,2015-12-03 14:57:55.521 ThaliTest[1897:2986906] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 14:57:59.489 ThaliTest[1897:2986906] Resetting plugins due to page load.
,2015-12-03 14:58:00.718 ThaliTest[1897:2986906] Finished load of: file:///var/mobile/Containers/Bundle/Application/05DE7E5E-0871-465B-B0C2-86ADA335B12C/ThaliTest.app/www/index.html
,2015-12-03 14:58:00.866 ThaliTest[1897:2986906] JXcore Cordova plugin initializing
,2015-12-03 14:58:00.867 ThaliTest[1897:2987106] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT7511
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 50787
,2015-12-03 15:05:05.284 ThaliTest[1897:2987106] jxcore: startBroadcasting
,2015-12-03 15:05:05.290 ThaliTest[1897:2987106] server: starting Apple-IpadAir2-1_PT7511.wgBJEg==
2015-12-03 15:05:05.291 ThaliTest[1897:2987106] multipeer session: start timer: 0x19cfb120
,2015-12-03 15:05:05.291 ThaliTest[1897:2987106] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7511
2015-12-03 15:05:05.291 ThaliTest[1897:2987106] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T14:05:05.293Z SendDataTCPServer.js: TCP/IP server is bound to port: 50787
,2015-12-03 15:05:08.109 ThaliTest[1897:2986906] client: found peer: Apple-Iphone5-1_PT2690.vOZHlg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2690.vOZHlg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03T14:05:08.112Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:08.112Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03T14:05:08.113Z SendDataConnector.js:, do connect now
2015-12-03 15:05:08.113 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:08.113 ThaliTest[1897:2987106] client session: connect
,2015-12-03 15:05:08.113 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:08.947 ThaliTest[1897:2986906] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:09.149 ThaliTest[1897:2986906] client: found peer: Apple-Iphone5s-1_PT7727.aEO4Zw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7727.aEO4Zw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:05:09.151 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:05:09.151 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:05:09.151 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-,12-03 15:05:09.151 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:05:09.151 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
2015-12-03 15:05:09.153 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:05:11.779 ThaliTest[1897:2987903] client session: connected
2015-12-03 15:05:11.779 ThaliTest[1897:2987903] client session: stateChange:1->2 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:11.788 ThaliTest[1897:2987885] client session: fireConnectCallback: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:11.788 ThaliTest[1897:2987885] jxcore: connect: success
2015-12-03T14:05:11.788Z SendDataConnector.js: CLIENT connected to 50790, error: null
,2015-12-03T14:05:11.789Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:11.790 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:05:11.790 ThaliTest[1897:2986906] client: new accepted socket: 0x1b151990
,2015-12-03T14:05:11.804Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:05:12.147Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T14:05:12.160Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T14:05:12.174Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:05:12.174Z SendDataConnector.js: got all data for this round
,2015-12-03T14:05:12.175Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:05:12.175Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:05:12.176 ThaliTest[1897:2987106] jxcore: disconnect
,2015-12-03 15:05:12.177 ThaliTest[1897:2987903] server session: connected
2015-12-03 15:05:12.177 ThaliTest[1897:2987903] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
2015-12-03 15:05:12.176 ThaliTest[1897:2987106] client session: disconnectFr,omPeer: Apple-Iphone5-1_PT2690.vOZHlg==
2015-12-03 15:05:12.177 ThaliTest[1897:2987106] client session: disconnect
2015-12-03 15:05:12.178 ThaliTest[1897:2987106] client session: stateChange:2->0 Apple-Iphone5-1_PT2690.vOZHlg==
,2015-12-03 15:05:12.181 ThaliTest[1897:2987106] jxcore: disconnect: success
2015-12-03T14:05:12.182Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2690.vOZHlg==
---- round done--------
device[2]: Apple-Iphone6-1_PT7057.4,CFLyQ==
2015-12-03T14:05:12.183Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:05:12.183Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:05:12.183Z SendDataConn,ector.js: do connect now
2015-12-03 15:05:12.183 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:12.183 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:05:12.183 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:12.215 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:05:12.226Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:12.724Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-03T14:05:12.737Z SendDataTCPServer.js: TCP/IP server has received 10912 bytes of data
,2015-12-03T14:05:12.748Z SendDataTCPServer.js: TCP/IP server has received 31744 bytes of data
,2015-12-03T14:05:12.762Z SendDataTCPServer.js: TCP/IP server has received 37696 bytes of data
,2015-12-03T14:05:12.774Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-03T14:05:12.799Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-12-03T14:05:12.811Z SendDataTCPServer.js: TCP/IP server has received 60512 bytes of data
,2015-12-03T14:05:12.825Z SendDataTCPServer.js: TCP/IP server has received 61504 bytes of data
,2015-12-03T14:05:12.838Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-03T14:05:13.130Z SendDataTCPServer.js: TCP/IP server has received 67456 bytes of data
,2015-12-03T14:05:13.141Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-12-03T14:05:13.154Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-03T14:05:13.204Z SendDataTCPServer.js: TCP/IP server has received 88288 bytes of data
,2015-12-03T14:05:13.239Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-12-03T14:05:13.252Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-03T14:05:13.263Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:05:13.904 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:05:13.904 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:05:13.904 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:05:13.904 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:05:13.904 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:13.908 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone6-1_PT7057
,2015-12-03 15:05:16.282 ThaliTest[1897:2987884] server session: connected
2015-12-03 15:05:16.282 ThaliTest[1897:2987884] server session: stateChange:1->2 Apple-Iphone6-1_PT7057
,2015-12-03 15:05:16.299 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:05:16.306Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 15:05:16.341 ThaliTest[1897:2987883] client session: connected
2015-12-03 15:05:16.341 ThaliTest[1897:2987883] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:16.343 ThaliTest[1897:2987883] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:16.343 ThaliTest[1897:2987883] jxcore: connect: success
2015-12-03T14:05:16.343Z SendDataConnector.js: CLIENT connected ,to 50796, error: null
2015-12-03T14:05:16.344Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:16.345 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:05:16.345 ThaliTest[1897:2986906] client: new accepted socket: 0x19c3b730
,2015-12-03T14:05:16.357Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:05:16.797Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T14:05:16.809Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03T14:05:16.811Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:05:16.850Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:05:16.862 ThaliTest[1897:2987903] server session: not connected Apple-Iphone6-1_PT7057
,2015-12-03 15:05:23.247 ThaliTest[1897:2987883] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03T14:05:26.854Z SendDataConnector.js: Receiving data timeout now
2015-12-03T14:05:26.854Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:26.854Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:05:26.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:26.855Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:26.855 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:05:26.855 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:05:26.856 ThaliTest[1897:2986906] client relay: 0x19c3b730 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:26.856 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12,-03 15:05:26.856 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:26.856 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:05:26.856 ThaliTest[1897:2986906] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:26.858 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:05:31.864Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:05:31.864Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:33.588 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:05:33.588 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:05:33.589 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:05:33.589 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:05:33.589 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:05:33.589 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:05:33.591 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:05:33.591 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:05:33.594 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03T14:05:33.596Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:36.226 ThaliTest[1897:2987983] server session: connected
2015-12-03 15:05:36.227 ThaliTest[1897:2987983] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:05:36.235 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:05:36.244Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:05:36.330Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T14:05:36.343Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-03T14:05:36.367Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T14:05:36.380Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:05:36.874 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:05:36.874 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:05:36.875Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T14:05:36.875Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:05:36.875Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:05:36.875Z SendDataConnector.js: do connect now
,2015-12-03 15:05:36.875 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:36.875 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:05:36.876 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple,-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:39.735 ThaliTest[1897:2987965] client session: connected
2015-12-03 15:05:39.735 ThaliTest[1897:2987965] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:39.737 ThaliTest[1897:2987965] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:39.737 ThaliTest[1897:2987965] jxcore: connect: success
,2015-12-03T14:05:39.737Z SendDataConnector.js: CLIENT connected to 50801, error: null
2015-12-03T14:05:39.738Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:05:39.739 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:05:39.739 ThaliTest[1897:2986906] client: new accepted socket: 0x1b155ce0
,2015-12-03T14:05:39.751Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:05:46.672 ThaliTest[1897:2987983] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03T14:05:49.784Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:05:49.784Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:05:49.784Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:05:49.785Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:05:49.786Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:05:49.786 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:05:49.786 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:05:49.786 ThaliTest[1897:2986906] client relay: 0x1b155ce0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:05:49.786 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:49.786 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:05:49.787 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:05:49.787 ThaliTest[1897:2986906] client session: stateChange,:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:49.789 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:05:54.787Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:05:54.787Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:57.870 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:05:57.870 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:05:57.870 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
,2015-12-03 15:05:57.870 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:05:57.870 ThaliTest[1897:2986906] server session: disconnect
,2015-12-03 15:05:57.870 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03T14:05:57.874Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:05:57.924 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:05:57.925 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:05:57.927 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:05:59.794 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:05:59.794 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:05:59.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T14:05:59.794Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:05:59.795Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:05:59.795Z SendDataConnector.js: do connect now
2015-12-03 15:05:59.795 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:05:59.795 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:05:59.796 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:00.714 ThaliTest[1897:2988032] server session: connected
2015-12-03 15:06:00.714 ThaliTest[1897:2988032] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:00.716 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:06:00.722Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:00.891Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-03T14:06:00.904Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:02.932 ThaliTest[1897:2987983] client session: connected
,2015-12-03 15:06:02.932 ThaliTest[1897:2987983] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:02.934 ThaliTest[1897:2987983] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:02.934 ThaliTest[1897:2987983] jxcore: connect: success
,2015-12-03T14:06:02.935Z SendDataConnector.js: CLIENT connected to 50806, error: null
2015-12-03T14:06:02.935Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:02.936 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:06:02.936 ThaliTest[1897:2986906] client: new accepted socket: 0x19e18830
,2015-12-03T14:06:02.949Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:10.923 ThaliTest[1897:2988032] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03T14:06:12.974Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:06:12.974Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:06:12.975Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:12.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:12.975Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client relay: 0x19e18830 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:06:12.976 ThaliTest[1897:2986906] client session: stateChange,:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:12.979 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:06:17.979Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:06:17.979Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:21.795 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:06:21.795 ThaliTest[1897:2986906] multipeer session: stop timer
,2015-12-03 15:06:21.796 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:06:21.796 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
2015-12-03 15:06:21.796 ThaliTest[1897:2986906] server session: disconnect
,2015-12-03 15:06:21.796 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:21.797 ThaliTest[1897:2986906] server session: connect
2015-12-03T14:06:21.798Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:06:21.797 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:21.801 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:06:22.984 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:06:22.984 ThaliTest[1897:2987106] jxcore: disconnect: fail
,2015-12-03T14:06:22.985Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:06:22.985Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: ,true
2015-12-03T14:06:22.985Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:06:22.985Z SendDataConnector.js: do connect now
,2015-12-03 15:06:22.985 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:22.985 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:06:22.986 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:25.005 ThaliTest[1897:2988110] server session: connected
2015-12-03 15:06:25.006 ThaliTest[1897:2988110] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:25.007 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:06:25.015Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:25.202Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-03T14:06:25.214Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:26.813 ThaliTest[1897:2988031] client session: connected
2015-12-03 15:06:26.813 ThaliTest[1897:2988031] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:26.814 ThaliTest[1897:2988031] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:26.814 ThaliTest[1897:2988031] jxcore: connect: success
2015-12-03T14:06:26.815Z SendDataConnector.js: CLIENT connected to 50811, error: null
2015-12-03T14:06:26.815Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:26.816 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:06:26.816 ThaliTest[1897:2986906] client: new accepted socket: 0x1b155ce0
,2015-12-03T14:06:26.829Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:35.488 ThaliTest[1897:2988106] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03T14:06:36.859Z SendDataConnector.js: Receiving data timeout now
2015-12-03T14:06:36.860Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:06:36.860Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:06:36.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:06:36.861Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:06:36.861 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:06:36.862 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:06:36.862 ThaliTest[1897:2986906] client relay: 0x1b155ce0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:06:36.862 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12,-03 15:06:36.862 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:36.862 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:06:36.862 ThaliTest[1897:2986906] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:36.864 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:06:41.861Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:06:41.861Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:45.901 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:06:45.901 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:06:45.901 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-,12-03 15:06:45.902 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5-1_PT2690)
,2015-12-03 15:06:45.902 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:06:45.902 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03T14:06:45.910Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:06:45.956 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:06:45.956 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:45.959 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5-1_PT2690
,2015-12-03 15:06:46.862 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:06:46.862 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:06:46.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T14:06:46.862Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:06:46.862Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:06:46.863Z SendDataConnector.js: do connect now
2015-12-03 15:06:46.863 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:46.863 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:06:46.863 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:49.178 ThaliTest[1897:2988178] server session: connected
2015-12-03 15:06:49.178 ThaliTest[1897:2988178] server session: stateChange:1->2 Apple-Iphone5-1_PT2690
,2015-12-03 15:06:49.181 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:06:49.192Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:49.291Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-03T14:06:49.304Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:06:49.518 ThaliTest[1897:2988166] client session: connected
2015-12-03 15:06:49.518 ThaliTest[1897:2988166] client session: stateChange:1->2 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:06:50.143 ThaliTest[1897:2988163] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:06:50.144 ThaliTest[1897:2988163] jxcore: connect: success
,2015-12-03T14:06:50.144Z SendDataConnector.js: CLIENT connected to 50816, error: null
,2015-12-03T14:06:50.145Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:06:50.146 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:06:50.146 ThaliTest[1897:2986906] client: new accepted socket: 0x19e1e610
,2015-12-03T14:06:50.158Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:06:52.202 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:06:52.202 ThaliTest[1897:2986906] multipeer session: stop timer
,2015-12-03 15:06:52.202 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
,2015-12-03 15:06:52.202 ThaliTest[1897:2986906] server session: connect
,2015-12-03 15:06:52.203 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:52.205 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:54.948 ThaliTest[1897:2988162] server session: connected
2015-12-03 15:06:54.948 ThaliTest[1897:2988162] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:06:55.013 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:06:55.015Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:06:55.339Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-03T14:06:55.352Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-03T14:06:55.487Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-03T14:06:55.549Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-03T14:06:55.869Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-03T14:06:55.884Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:06:59.531 ThaliTest[1897:2988178] server session: not connected Apple-Iphone5-1_PT2690
,2015-12-03T14:07:00.189Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:00.189Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:00.190Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:00.191Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:07:00.191Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T14:07:00.192Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 15:07:00.192 ThaliTest[1897:2987106] jxcore: disconnect
,2015-12-03 15:07:00.192 ThaliTest[1897:2987106] client session: disconnectFromPeer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:07:00.192 ThaliTest[1897:2987106] client session: disconnect
2015-12-03 15:07:00.192 ThaliTest[1897:2987106] client session: stateChange:2->0 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:07:00.194 ThaliTest[1897:2987106] jxcore: disconnect: success
2015-12-03T14:07:00.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
---- round done--------
device[3]: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:07:00.195Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:00.199Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:00.199Z SendDataConnector.js: do connect now
,2015-12-03 15:07:00.199 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:00.200 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:07:00.200 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:07:00.203Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:03.073 ThaliTest[1897:2988210] client session: connected
2015-12-03 15:07:03.073 ThaliTest[1897:2988210] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:03.075 ThaliTest[1897:2988210] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:03.075 ThaliTest[1897:2988210] jxcore: connect: success
,2015-12-03T14:07:03.076Z SendDataConnector.js: CLIENT connected to 50821, error: null
,2015-12-03T14:07:03.076Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:03.078 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:07:03.078 ThaliTest[1897:2986906] client: new accepted socket: 0x19e7b100
,2015-12-03T14:07:03.090Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:07:03.471Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T14:07:03.496Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 15:07:05.910 ThaliTest[1897:2988210] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:07:13.507Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:13.507Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:07:13.507Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:13.508Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:13.508Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:13.509 ThaliTest[1897:2986906] client: socket closed
,2015-12-03 15:07:13.509 ThaliTest[1897:2986906] client relay: socket disconnected
,2015-12-03 15:07:13.509 ThaliTest[1897:2986906] client relay: 0x19e7b100 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:07:,13.509 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:13.509 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:13.509 ThaliTest[1897:2986906], client session: disconnect
2015-12-03 15:07:13.509 ThaliTest[1897:2986906] client session: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:13.512 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:16.328 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:07:16.328 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:07:16.328 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:07:16.328 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
2015-12-03 15:07:16.328 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:07:16.328 ThaliTest[1897:2986906] server session: state,Change:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:07:16.330 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:07:16.330 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03T14:07:16.333Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:07:16.334 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:07:18.509Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:18.509Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:18.996 ThaliTest[1897:2988210] server session: connected
2015-12-03 15:07:18.996 ThaliTest[1897:2988210] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:07:19.060 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:07:19.062Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:19.171Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:07:23.514 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:07:23.515 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:07:23.515Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4,Zw==
2015-12-03T14:07:23.515Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:07:23.515Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:23.515Z SendDataConnector.js: do connect now
,2015-12-03 15:07:23.515 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:23.516 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:07:23.516 ThaliTest[1897:2987106] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:27.253 ThaliTest[1897:2988210] client session: connected
2015-12-03 15:07:27.253 ThaliTest[1897:2988210] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:27.255 ThaliTest[1897:2988210] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:27.255 ThaliTest[1897:2988210] jxcore: connect: success
2015-12-03T14:07:27.255Z SendDataConnector.js: CLIENT connected to 50826, error: null
,2015-12-03T14:07:27.255Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:27.256 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:07:27.256 ThaliTest[1897:2986906] client: new accepted socket: 0x19ea20e0
,2015-12-03T14:07:27.269Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:07:29.408 ThaliTest[1897:2988234] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:07:37.290Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:07:37.290Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:07:37.290Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:07:37.291Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:07:37.291Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client relay: 0x19ea20e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:07:37.292 ThaliTest[1897:2986906] client session: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:37.294 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:39.380 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:07:39.380 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:07:39.380 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:07:39.380 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
2015-12-03 15:07:39.380 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:07:39.380 ThaliTest[1897:2986906] server session: state,Change:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:07:39.382 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:07:39.382 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:07:39.385 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03T14:07:39.394Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:07:42.099 ThaliTest[1897:2988234] server session: connected
2015-12-03 15:07:42.099 ThaliTest[1897:2988234] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:07:42.101 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:07:42.106Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:07:42.204Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:07:42.302Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:42.302Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:07:47.308Z SendDataConnector.js: do connect now
2015-12-03 15:07:47.307 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:07:47.307 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:07:47.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:07:47.308Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:07:47.308Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:47.309 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:47.309 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:07:47.309 ThaliTest[1897:2987106] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:50.847 ThaliTest[1897:2988320] client session: connected
2015-12-03 15:07:50.847 ThaliTest[1897:2988320] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:07:50.856 ThaliTest[1897:2988235] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:07:50.856 ThaliTest[1897:2988235] jxcore: connect: success
,2015-12-03T14:07:50.857Z SendDataConnector.js: CLIENT connected to 50831, error: null
,2015-12-03T14:07:50.857Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:07:50.858 ThaliTest[1897:2986906] client: relay established
,2015-12-03 15:07:50.858 ThaliTest[1897:2986906] client: new accepted socket: 0x19cc86f0
,2015-12-03T14:07:50.872Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:07:52.477 ThaliTest[1897:2988320] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:08:00.896Z SendDataConnector.js: Receiving data timeout now
2015-12-03T14:08:00.896Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:00.897Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:00.897Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:08:00.897Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:00.898 ThaliTest[1897:2986906] client: socket closed
2015-12-03 15:08:00.898 ThaliTest[1897:2986906] client relay: socket disconnected
2015-12-03 15:08:00.898 ThaliTest[1897:2986906] client relay: 0x19cc86f0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:08:00.898 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-1,2-03 15:08:00.898 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:00.898 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:08:00.899 ThaliTest[1897:2986906] client session: stateChan,ge:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:00.901 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:02.593 ThaliTest[1897:2986906] multipeer session: reset timer
2015-12-03 15:08:02.593 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:08:02.593 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-,12-03 15:08:02.593 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
2015-12-03 15:08:02.593 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:08:02.593 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03T14:08:02.595Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:08:02.595 ThaliTest[1897:2986906] server session: connect
,2015-12-03 15:08:02.595 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:02.598 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:05.064 ThaliTest[1897:2988235] server session: connected
2015-12-03 15:08:05.064 ThaliTest[1897:2988235] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:05.067 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:08:05.071Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:05.189Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:08:05.907Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03T14:08:05.907Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:10.917 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:08:10.917 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:08:10.917Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4,Zw==
2015-12-03T14:08:10.917Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:08:10.917Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:08:10.918Z SendDataConnector.js: do connect now
,2015-12-03 15:08:10.918 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:10.918 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:08:10.918 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:13.479 ThaliTest[1897:2988369] client session: connected
2015-12-03 15:08:13.479 ThaliTest[1897:2988369] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:13.481 ThaliTest[1897:2988284] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:13.481 ThaliTest[1897:2988284] jxcore: connect: success
2015-12-03T14:08:13.482Z SendDataConnector.js: CLIENT connected to 50836, error: null
,2015-12-03T14:08:13.482Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:13.483 ThaliTest[1897:2986906] client: relay established
2015-12-03 15:08:13.484 ThaliTest[1897:2986906] client: new accepted socket: 0x19aa9340
,2015-12-03T14:08:13.496Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:08:15.193 ThaliTest[1897:2988235] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:08:23.526Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T14:08:23.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:23.527Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:23.527Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:08:23.527Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 15:08:23.528 ThaliTest[1897:2986906] client: socket closed
,2015-12-03 15:08:23.528 ThaliTest[1897:2986906] client relay: socket disconnected
,2015-12-03 15:08:23.529 ThaliTest[1897:2986906] client relay: 0x19aa9340 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 15:08:,23.529 ThaliTest[1897:2986906] client session: socket closed: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:23.529 ThaliTest[1897:2986906] client session: onLinkFailure: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:23.529 ThaliTest[1897:2986906] client session: disconnect
2015-12-03 15:08:23.529 ThaliTest[1897:2986906] client session: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:23.531 ThaliTest[1897:2986906] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:25.562 ThaliTest[1897:2986906] multipeer session: reset timer
,2015-12-03 15:08:25.562 ThaliTest[1897:2986906] multipeer session: stop timer
2015-12-03 15:08:25.563 ThaliTest[1897:2986906] multipeer session: start timer: 0x19cfb120
2015-12-03 15:08:25.563 ThaliTest[1897:2986906] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7727)
,2015-12-03 15:08:25.563 ThaliTest[1897:2986906] server session: disconnect
2015-12-03 15:08:25.563 ThaliTest[1897:2986906] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:25.564 ThaliTest[1897:2986906] server session: connect
2015-12-03 15:08:25.564 ThaliTest[1897:2986906] server session: stateChange:0->1 Apple-Iphone5s-1_PT7727
,2015-12-03T14:08:25.566Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:08:25.567 ThaliTest[1897:2986906] server: accepting invitation Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:28.196 ThaliTest[1897:2988391] server session: connected
2015-12-03 15:08:28.196 ThaliTest[1897:2988391] server session: stateChange:1->2 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:28.199 ThaliTest[1897:2986906] server relay: connected (to port: 50787)
,2015-12-03T14:08:28.203Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:08:28.294Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T14:08:28.534Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03T14:08:28.534Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:33.539 ThaliTest[1897:2987106] jxcore: disconnect
2015-12-03 15:08:33.539 ThaliTest[1897:2987106] jxcore: disconnect: fail
2015-12-03T14:08:33.540Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4,Zw==
2015-12-03T14:08:33.540Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7727.aEO4Zw== with availability status: true
2015-12-03T14:08:33.540Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7727.aEO4Zw==,
2015-12-03T14:08:33.540Z SendDataConnector.js: do connect now
,2015-12-03 15:08:33.540 ThaliTest[1897:2987106] jxcore: connect Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:33.541 ThaliTest[1897:2987106] client session: connect
2015-12-03 15:08:33.541 ThaliTest[1897:2987106] client session: stateChange:0->1 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:36.574 ThaliTest[1897:2988379] client session: connected
2015-12-03 15:08:36.574 ThaliTest[1897:2988379] client session: stateChange:1->2 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:36.576 ThaliTest[1897:2988284] client session: fireConnectCallback: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:36.576 ThaliTest[1897:2988284] jxcore: connect: success
,2015-12-03T14:08:36.577Z SendDataConnector.js: CLIENT connected to 50841, error: null
2015-12-03T14:08:36.578Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:08:36.579 ThaliTest[1897:2986906] client: relay established
,2015-12-03 15:08:36.579 ThaliTest[1897:2986906] client: new accepted socket: 0x19ea4b90
,2015-12-03T14:08:36.591Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 15:08:38.610 ThaliTest[1897:2988379] server session: not connected Apple-Iphone5s-1_PT7727
,2015-12-03T14:08:46.618Z SendDataConnector.js: Receiving data timeout now
2015-12-03T14:08:46.618Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T14:08:46.618Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:46.619Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:08:46.619Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T14:08:46.620Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:08:46.620 ThaliTest[1897:2987106] jxcore: disconnect
,2015-12-03 15:08:46.620 ThaliTest[1897:2987106] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7727.aEO4Zw==
2015-12-03 15:08:46.621 ThaliTest[1897:2987106] client session: disconnect
2015-12-03 15:08:46.621 ThaliTest[1897:2987106] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7727.aEO4Zw==
,2015-12-03 15:08:46.622 ThaliTest[1897:2987106] jxcore: disconnect: success
2015-12-03T14:08:46.623Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7727.aEO4Zw==
---- round done--------
weAreDoneNow , resultArray.length:, 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7511","time":221343,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT2690.vOZHlg==","time":4062,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT7057.4CFLyQ==","time":108007,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5s-1_PT7727.aEO4Zw==","ti,me":106420,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
sendList : 100% : 4062 ms, 99% : 4062 ms, 95 : 4062 ms, 90% : 4062 ms.
Result count 1, range 4062 ms to  4062 ms.
sendList failed peers count :, 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT7727.aEO4Zw==, Tried : 5
,sendList never tried peers count : 0 [0 %]
2015-12-03T14:08:46.627Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:08:46.627Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T14:08:46.628Z SendDataConnector.js: ----------------- closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-03 15:08:49.522 ThaliTest[1897:2987106] jxcore: stopBroadcasting
,2015-12-03 15:08:49.522 ThaliTest[1897:2987106] THEMultipeerSession stopping peer
,2015-12-03 15:08:49.522 ThaliTest[1897:2987106] multipeer session: stop timer
2015-12-03 15:08:49.523 ThaliTest[1897:2987106] server session: disconnect
2015-12-03 15:08:49.523 ThaliTest[1897:2987106] server session: stateChange:2->0 Apple-Iphone5s-1_PT7727
,2015-12-03 15:08:49.525 ThaliTest[1897:2987106] server session: disconnect
,2015-12-03 15:08:49.527 ThaliTest[1897:2987106] server session: stateChange:2->0 Apple-Iphone5-1_PT2690
,2015-12-03 15:08:49.532 ThaliTest[1897:2987106] server session: disconnect
2015-12-03 15:08:49.532 ThaliTest[1897:2987106] server session: stateChange:2->0 Apple-Iphone6-1_PT7057
,2015-12-03 15:08:49.535 ThaliTest[1897:2987106] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-03T14:08:49.549Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03T14:08:49.550Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03T14:08:49.550Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03T14:08:49.550Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT2690.vOZHlg==\",\"time\":4062,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],,\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT7057.4CFLyQ==\",\"time\":108007,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-Iphone5s-1_PT7727.aEO4Zw==\",\"time,\":106420,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
