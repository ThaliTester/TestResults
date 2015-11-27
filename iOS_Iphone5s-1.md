#### Test 51986340bb0815b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/687BCC9E-A5B9-49C1-B02C-DE9012697B9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/687BCC9E-A5B9-49C1-B02C-DE9012697B9C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/500DEAF4-4967-4F83-891E-4C1C36275464/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56955"
,(lldb)     command script import "/tmp/687BCC9E-A5B9-49C1-B02C-DE9012697B9C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-27 13:09:43.498 ThaliTest[1853:1602942] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DD45CB07-C2F7-4EAA-A7F3-C43E2C330A26/Library/Cookies/Cookies.binarycookies
,2015-11-27 13:09:43.908 ThaliTest[1853:1602942] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 13:09:43.909 ThaliTest[1853:1602942] Multi-tasking -> Device: YES, App: YES
,2015-11-27 13:09:43.916 ThaliTest[1853:1602942] Unlimited access to network resources
,2015-11-27 13:09:43.923 ThaliTest[1853:1602942] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 13:09:47.269 ThaliTest[1853:1602942] Resetting plugins due to page load.
,2015-11-27 13:09:47.668 ThaliTest[1853:1602942] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/500DEAF4-4967-4F83-891E-4C1C36275464/ThaliTest.app/www/index.html
,2015-11-27 13:09:47.829 ThaliTest[1853:1602942] JXcore Cordova plugin initializing
2015-11-27 13:09:47.830 ThaliTest[1853:1603054] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT8509
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
serverPort is 62998
,2015-11-27 13:16:20.640 ThaliTest[1853:1603054] jxcore: startBroadcasting
,2015-11-27 13:16:20.653 ThaliTest[1853:1603054] server: starting Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:20.654 ThaliTest[1853:1603054] multipeer session: start timer: 0x19f856b0
2015-11-27 13:16:20.655 ThaliTest[1853:1603054] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:20.656 ThaliTest[1853:1603054] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-27T12:16:20.668Z SendDataTCPServer.js: TCP/IP server is bound to port: 62998
,2015-11-27 13:16:20.831 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:20.839Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:20.840Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:16:20.840Z SendDataConnector.js: do connect now
,2015-11-27 13:16:20.842 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:20.843 ThaliTest[1853:1603054] client session: connect
2015-11-27 13:16:20.843 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:21.513 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:16:21.514 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:16:21.515 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:16:21.515 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:16:21.516 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:21.524 ThaliTest[1853:1602942] server: accepting invitation Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:21.847 ThaliTest[1853:1602942] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1479.RH8WAQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
2015-11-27 13:16:21.854 ThaliTest[1853:1602942] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3767.CF0kqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-27 13:16:22.037 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:16:22.037 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:16:22.038 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:16:22.039 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:16:22.039 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:22.052 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:16:23.976 ThaliTest[1853:1603586] server session: connected
2015-11-27 13:16:23.977 ThaliTest[1853:1603586] server session: stateChange:1->2 Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:23.988 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
2015-11-27T12:16:23.989Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27 13:16:24.072 ThaliTest[1853:1603592] client session: connected
2015-11-27 13:16:24.073 ThaliTest[1853:1603592] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:24.078 ThaliTest[1853:1603586] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:24.079 ThaliTest[1853:1603586] jxcore: connect: success
,2015-11-27T12:16:24.081Z SendDataConnector.js: CLIENT connected to 63002, error: null
2015-11-27T12:16:24.082Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:24.088 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:16:24.089 ThaliTest[1853:1602942] client: new accepted socket: 0x19efab40
,2015-11-27T12:16:24.102Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27 13:16:24.257 ThaliTest[1853:1603586] server session: connected
,2015-11-27 13:16:24.258 ThaliTest[1853:1603586] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:24.264 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
,2015-11-27T12:16:24.460Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27T12:16:24.464Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27 13:16:24.491 ThaliTest[1853:1603588] server session: not connected Apple-IpadAir2-1_PT3767
,2015-11-27T12:16:24.770Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-27T12:16:24.784Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-11-27T12:16:24.801Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27T12:16:24.805Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-27T12:16:24.806Z SendDataConnector.js: got all data for this round
,2015-11-27T12:16:24.807Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:16:24.807Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:24.809 ThaliTest[1853:1603054] jxcore: disconnect
,2015-11-27 13:16:24.809 ThaliTest[1853:1603054] client session: disconnectFromPeer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:24.810 ThaliTest[1853:1603054] client session: disconnect
2015-11-27 13:16:24.810 ThaliTest[1853:1603054] client session:, stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:24.813 ThaliTest[1853:1603054] jxcore: disconnect: success
2015-11-27T12:16:24.813Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:24.817Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:24.817Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:16:24.817Z SendDataConnector.js: do connect now
,2015-11-27 13:16:24.817 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:24.818 ThaliTest[1853:1603054] client session: connect
2015-11-27 13:16:24.819 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:24.846 ThaliTest[1853:1603592] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27 13:16:27.103 ThaliTest[1853:1603601] client session: connected
2015-11-27 13:16:27.104 ThaliTest[1853:1603601] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:27.115 ThaliTest[1853:1603588] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:27.115 ThaliTest[1853:1603588] jxcore: connect: success
2015-11-27T12:16:27.116Z SendDataConnector.js: CLIENT connected ,to 63006, error: null
2015-11-27T12:16:27.117Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:27.121 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:16:27.122 ThaliTest[1853:1602942] client: new accepted socket: 0x15dca5a0
,2015-11-27T12:16:27.133Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:27.427Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-27T12:16:27.450Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-27T12:16:27.463Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-27T12:16:27.476Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-27T12:16:37.489Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:16:37.489Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:37.490Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:37.491Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:16:37.492Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:16:37.494 ThaliTest[1853:1602942] client: socket closed
2015-11-27 13:16:37.494 ThaliTest[1853:1602942] client relay: socket disconnected
2015-11-27 13:16:37.495 ThaliTest[1853:1602942] client relay: 0x15dca5a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19ee8b50 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:16:37.496 ThaliTest[1853:1602942] client session: socket closed: Apple-Iphone5-1_PT1479.RH8WAQ,==
2015-11-27 13:16:37.496 ThaliTest[1853:1602942] client session: onLinkFailure: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:37.496 ThaliTest[1853:1602942] client session: disconnect
2015-11-27 13:16:37.497 ThaliTest[1853:1602942] client session: ,stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:37.500 ThaliTest[1853:1602942] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:42.495Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:42.496Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:47.497 ThaliTest[1853:1603054] jxcore: disconnect
2015-11-27 13:16:47.498 ThaliTest[1853:1603054] jxcore: disconnect: fail
2015-11-27T12:16:47.499Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:47.500Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT1479.RH8WAQ== with availability status: true
2015-11-27T12:16:47.500Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:47.501Z SendDataConnector.js: do connect now
,2015-11-27 13:16:47.502 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:47.503 ThaliTest[1853:1603054] client session: connect
2015-11-27 13:16:47.504 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple,-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:50.093 ThaliTest[1853:1603648] client session: connected
2015-11-27 13:16:50.093 ThaliTest[1853:1603648] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:50.103 ThaliTest[1853:1603654] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:50.103 ThaliTest[1853:1603654] jxcore: connect: success
2015-11-27T12:16:50.105Z SendDataConnector.js: CLIENT connected to 63008, error: null
,2015-11-27T12:16:50.105Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:50.110 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:16:50.111 ThaliTest[1853:1602942] client: new accepted socket: 0x15dca5a0
,2015-11-27T12:16:50.121Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:16:52.040 ThaliTest[1853:1602942] multipeer session: restart
,2015-11-27 13:16:52.155 ThaliTest[1853:1602942] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:52.156 ThaliTest[1853:1602942] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:52.157 ThaliTest[1853:1602942] clien,t: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:00.190Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:00.191Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:17:00.191Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:17:00.191Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:00.191Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:00.192 ThaliTest[1853:1602942] client: socket closed
2015-11-27 13:17:00.192 ThaliTest[1853:1602942] client relay: socket disconnected
2015-11-27 13:17:00.193 ThaliTest[1853:1602942] client relay: 0x15dca5a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x199bfac0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:17:00.193 ThaliTest[1853:1602942] client session: socket closed: Apple-Iphone5-1_PT1479.RH8WAQ,==
2015-11-27 13:17:00.193 ThaliTest[1853:1602942] client session: onLinkFailure: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:00.193 ThaliTest[1853:1602942] client session: disconnect
2015-11-27 13:17:00.193 ThaliTest[1853:1602942] client session: stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:00.194 ThaliTest[1853:1602942] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:05.196Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:05.197Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:10.201 ThaliTest[1853:1603054] jxcore: disconnect
2015-11-27 13:17:10.202 ThaliTest[1853:1603054] jxcore: disconnect: fail
2015-11-27T12:17:10.203Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WA,Q==
2015-11-27T12:17:10.204Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT1479.RH8WAQ== with availability status: true
,2015-11-27T12:17:10.204Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:17:10.204Z SendDataConnector.js: do connect now
2015-11-27 13:17:10.205 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone5-1_PT1479,.RH8WAQ==
,2015-11-27 13:17:10.206 ThaliTest[1853:1603054] client session: connect
,2015-11-27 13:17:10.206 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:12.595 ThaliTest[1853:1603716] client session: connected
2015-11-27 13:17:12.596 ThaliTest[1853:1603716] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:12.607 ThaliTest[1853:1603713] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:12.607 ThaliTest[1853:1603713] jxcore: connect: success
2015-11-27T12:17:12.608Z SendDataConnector.js: CLIENT connected to 63012, error: null
2015-11-27T12:17:12.609Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:12.613 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:17:12.614 ThaliTest[1853:1602942] client: new accepted socket: 0x19f80e50
,2015-11-27T12:17:12.626Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:22.039 ThaliTest[1853:1602942] multipeer session: restart
,2015-11-27 13:17:22.068 ThaliTest[1853:1602942] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:22.070 ThaliTest[1853:1602942] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:22.071 ThaliTest[1853:1602942] clien,t: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:22.689Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:22.689Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:22.690Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:22.690Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:22.691Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:22.693 ThaliTest[1853:1602942] client: socket closed
2015-11-27 13:17:22.694 ThaliTest[1853:1602942] client relay: socket disconnected
2015-11-27 13:17:22.694 ThaliTest[1853:1602942] client relay: 0x19f80e50 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19ee8760 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:17:22.695 ThaliTest[1853:1602942] client session: socket closed: Apple-Iphone5-1_PT1479.RH8WAQ,==
2015-11-27 13:17:22.696 ThaliTest[1853:1602942] client session: onLinkFailure: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:22.696 ThaliTest[1853:1602942] client session: disconnect
2015-11-27 13:17:22.697 ThaliTest[1853:1602942] client session: stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:22.698 ThaliTest[1853:1602942] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:27.697Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:27.698Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:32.708 ThaliTest[1853:1603054] jxcore: disconnect
2015-11-27 13:17:32.709 ThaliTest[1853:1603054] jxcore: disconnect: fail
2015-11-27T12:17:32.710Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WA,Q==
2015-11-27T12:17:32.710Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT1479.RH8WAQ== with availability status: true
,2015-11-27T12:17:32.711Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27T12:17:32.711Z SendDataConnector.js: do connect now
,2015-11-27 13:17:32.712 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:32.713 ThaliTest[1853:1603054] client session: connect
2015-11-27 13:17:32.714 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:35.112 ThaliTest[1853:1603742] client session: connected
2015-11-27 13:17:35.113 ThaliTest[1853:1603742] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:35.123 ThaliTest[1853:1603763] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:35.124 ThaliTest[1853:1603763] jxcore: connect: success
2015-11-27T12:17:35.125Z SendDataConnector.js: CLIENT connected ,to 63016, error: null
2015-11-27T12:17:35.126Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:35.129 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:17:35.130 ThaliTest[1853:1602942] client: new accepted socket: 0x15dcabe0
,2015-11-27T12:17:35.142Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27T12:17:45.204Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:45.205Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:45.205Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:45.206Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:45.207Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:45.208 ThaliTest[1853:1602942] client: socket closed
2015-11-27 13:17:45.209 ThaliTest[1853:1602942] client relay: socket disconnected
2015-11-27 13:17:45.210 ThaliTest[1853:1602942] client relay: 0x15dcabe0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19f85f30 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:17:45.210 ThaliTest[1853:1602942] client session: socket closed: Apple-Iphone5-1_PT1479.RH8WAQ,==
2015-11-27 13:17:45.211 ThaliTest[1853:1602942] client session: onLinkFailure: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:45.211 ThaliTest[1853:1602942] client session: disconnect
2015-11-27 13:17:45.212 ThaliTest[1853:1602942] client session: ,stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:45.214 ThaliTest[1853:1602942] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:50.213Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:50.214Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:52.040 ThaliTest[1853:1602942] multipeer session: restart
,2015-11-27 13:17:52.474 ThaliTest[1853:1602942] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:52.475 ThaliTest[1853:1602942] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:52.476 ThaliTest[1853:1602942] clien,t: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:55.227 ThaliTest[1853:1603054] jxcore: disconnect
2015-11-27 13:17:55.228 ThaliTest[1853:1603054] jxcore: disconnect: fail
2015-11-27T12:17:55.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WA,Q==
2015-11-27T12:17:55.229Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT1479.RH8WAQ== with availability status: true
2015-11-27T12:17:55.229Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:17:55.230Z SendDataConnector.js: do connect now
,2015-11-27 13:17:55.230 ThaliTest[1853:1603054] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:55.232 ThaliTest[1853:1603054] client session: connect
,2015-11-27 13:17:55.232 ThaliTest[1853:1603054] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:58.081 ThaliTest[1853:1603795] client session: connected
2015-11-27 13:17:58.082 ThaliTest[1853:1603795] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:17:58.092 ThaliTest[1853:1603795] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:17:58.093 ThaliTest[1853:1603795] jxcore: connect: success
2015-11-27T12:17:58.094Z SendDataConnector.js: CLIENT connected ,to 63020, error: null
,2015-11-27T12:17:58.095Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:58.100 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:17:58.101 ThaliTest[1853:1602942] client: new accepted socket: 0x15dcabe0
,2015-11-27T12:17:58.112Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:18:06.454 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:18:06.455 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:18:06.456 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:18:06.457 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:18:06.457 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:06.465 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27T12:18:08.183Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:18:08.184Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:08.185Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:08.186Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:18:08.187Z SendDataConnector.js: Stop data retrieving timer
2015-11-27T12:18:08.187Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27 13:18:08.188 ThaliTest[1853:1603054] jxcore: disconnect
,2015-11-27 13:18:08.189 ThaliTest[1853:1603054] client session: disconnectFromPeer: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:18:08.189 ThaliTest[1853:1603054] client session: disconnect
,2015-11-27 13:18:08.190 ThaliTest[1853:1603054] client session: stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:18:08.195 ThaliTest[1853:1603054] jxcore: disconnect: success
2015-11-27T12:18:08.198Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WAQ==
---- round done--------
device[3]: Apple-IpadAir2-1_PT3767.,CF0kqQ==
2015-11-27T12:18:08.200Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:18:08.201Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27T12:18:08.202Z SendDataConnector.js: do connect now
,2015-11-27 13:18:08.203 ThaliTest[1853:1603054] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:08.204 ThaliTest[1853:1603054] client session: connect
2015-11-27 13:18:08.205 ThaliTest[1853:1603054] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:18:08.213Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:18:08.788 ThaliTest[1853:1603817] server session: connected
2015-11-27 13:18:08.789 ThaliTest[1853:1603817] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:08.799 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
,2015-11-27T12:18:08.803Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:18:09.608Z SendDataTCPServer.js: TCP/IP server has received 5024 bytes of data
,2015-11-27T12:18:09.622Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-11-27T12:18:09.638Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-11-27T12:18:09.653Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-27T12:18:09.668Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-11-27T12:18:09.684Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-11-27T12:18:09.699Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-11-27T12:18:09.713Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-11-27T12:18:09.726Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-27T12:18:09.739Z SendDataTCPServer.js: TCP/IP server has received 94240 bytes of data
,2015-11-27T12:18:09.753Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:18:11.189 ThaliTest[1853:1603787] client session: connected
2015-11-27 13:18:11.190 ThaliTest[1853:1603787] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:11.192 ThaliTest[1853:1603787] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:11.194 ThaliTest[1853:1603787] jxcore: connect: success
2015-11-27T12:18:11.195Z SendDataConnector.js: CLIENT connected to 63024, error: null
2015-11-27T12:18:11.195Z SendDataConnector,.js: CLIENT starting client 
,2015-11-27 13:18:11.201 ThaliTest[1853:1602942] client: relay established
2015-11-27 13:18:11.202 ThaliTest[1853:1602942] client: new accepted socket: 0x15dcabe0
,2015-11-27T12:18:11.213Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:18:11.495Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-27T12:18:11.495Z SendDataConnector.js: got all data for this round
,2015-11-27T12:18:11.496Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:18:11.496Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27 13:18:11.496 ThaliTest[1853:1603054] jxcore: disconnect
,2015-11-27 13:18:11.497 ThaliTest[1853:1603054] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:11.497 ThaliTest[1853:1603054] client session: disconnect
,2015-11-27 13:18:11.498 ThaliTest[1853:1603054] client session: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:11.499 ThaliTest[1853:1603054] jxcore: disconnect: success
2015-11-27T12:18:11.499Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT8509","time":110877,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6911.ZjHo2g==","time":3967,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1479.RH8WAQ==","time":103368,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT3767.CF0kqQ==","time":3294,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataRe,ceived":100000}]}
sendList : 100% : 3967 ms, 99% : 3967 ms, 95 : 3967 ms, 90% : 3967 ms.
Result count 2, range 3294 ms to  3967 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT1479.RH8WAQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-27T12:18:11.506Z SendDataConnector.js: CLIENT Stop now
,2015-11-27T12:18:11.506Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:18:20.082 ThaliTest[1853:1603787] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:18:30.090 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:18:30.090 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:18:30.091 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:18:30.092 ThaliTest[1853:1602942] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:18:30.092 ThaliTest[1853:1602942] server session: disconnect
2015-11-27 13:18:30.093 ThaliTest[1853:1602942] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:18:30.097 ThaliTest[1853:1602942] server session: connect
2015-11-27T12:18:30.100Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27 13:18:30.098 ThaliTest[1853:1602942] server session: stateChange:0,->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:30.123 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:18:32.304 ThaliTest[1853:1603862] server session: connected
2015-11-27 13:18:32.304 ThaliTest[1853:1603862] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:32.316 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
2015-11-27T12:18:32.321Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:18:32.409Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-11-27T12:18:32.670Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:18:33.710 ThaliTest[1853:1602942] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:18:33.711 ThaliTest[1853:1602942] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:18:40.525 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:18:42.622 ThaliTest[1853:1603823] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:18:52.772 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:18:52.774 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:18:52.774 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:18:52.775 ThaliTest[1853:1602942] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:18:52.776 ThaliTest[1853:1602942] server session: disconnect
2015-11-27 13:18:52.776 ThaliTest[1853:1602942] server session: stateChange:2->0 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:52.779 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:18:52.780 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
2015-11-27T12:18:52.783Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:18:52.790 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:18:54.694 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:18:55.215 ThaliTest[1853:1603900] server session: connected
2015-11-27 13:18:55.216 ThaliTest[1853:1603900] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:18:55.226 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
,2015-11-27T12:18:55.232Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:18:55.311Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-27T12:18:55.323Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:19:05.306 ThaliTest[1853:1603896] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:19:15.790 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:19:15.791 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:19:15.791 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:19:15.792 ThaliTest[1853:1602942] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:19:15.793 ThaliTest[1853:1602942] server session: disconnect
2015-11-27 13:19:15.793 ThaliTest[1853:1602942] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:19:15.799 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:19:15.800 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
,2015-11-27T12:19:15.811Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27 13:19:15.818 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:19:18.308 ThaliTest[1853:1604100] server session: connected
2015-11-27 13:19:18.309 ThaliTest[1853:1604100] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:18.320 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
,2015-11-27T12:19:18.329Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:19:18.443Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-11-27T12:19:18.458Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:19:26.256 ThaliTest[1853:1602942] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:19:26.257 ThaliTest[1853:1602942] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:19:28.228 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:19:28.413 ThaliTest[1853:1604100] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:19:36.609 ThaliTest[1853:1602942] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:19:36.609 ThaliTest[1853:1602942] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:19:37.731 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,2015-11-27 13:19:38.764 ThaliTest[1853:1602942] multipeer session: reset timer
2015-11-27 13:19:38.765 ThaliTest[1853:1602942] multipeer session: stop timer
2015-11-27 13:19:38.765 ThaliTest[1853:1602942] multipeer session: start timer: 0x19f856b0
2015-,11-27 13:19:38.766 ThaliTest[1853:1602942] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:19:38.767 ThaliTest[1853:1602942] server session: disconnect
2015-11-27 13:19:38.767 ThaliTest[1853:1602942] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:19:38.772 ThaliTest[1853:1602942] server session: connect
2015-11-27 13:19:38.773 ThaliTest[1853:1602942] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
2015-11-27T12:19:38.780Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-11-27 13:19:38.796 ThaliTest[1853:1602942] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:19:41.342 ThaliTest[1853:1604168] server session: connected
2015-11-27 13:19:41.343 ThaliTest[1853:1604168] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:41.354 ThaliTest[1853:1602942] server relay: connected (to port: 62998)
,2015-11-27T12:19:41.363Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:19:41.515Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-11-27T12:19:41.530Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:19:51.451 ThaliTest[1853:1604100] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:19:56.009 ThaliTest[1853:1602942] client: lost peer: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:19:56.010 ThaliTest[1853:1602942] client session: onPeerLost: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":false}]
,2015-11-27 13:19:56.136 ThaliTest[1853:1602942] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-27 13:19:57.038 ThaliTest[1853:1603054] jxcore: stopBroadcasting
,2015-11-27 13:19:57.040 ThaliTest[1853:1603054] THEMultipeerSession stopping peer
,2015-11-27 13:19:57.040 ThaliTest[1853:1603054] multipeer session: stop timer
,2015-11-27 13:19:57.042 ThaliTest[1853:1603054] server session: disconnect
2015-11-27 13:19:57.043 ThaliTest[1853:1603054] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:19:57.054 ThaliTest[1853:1603054] server session: disconnect
,2015-11-27 13:19:57.055 ThaliTest[1853:1603054] server session: stateChange:2->0 Apple-IpadAir2-1_PT3767
2015-11-27 13:19:57.062 ThaliTest[1853:1603054] server session: disconnect
2015-11-27 13:19:57.063 ThaliTest[1853:1603054] server session: stateChang,e:2->0 Apple-Iphone5-1_PT1479
,2015-11-27 13:19:57.068 ThaliTest[1853:1603054] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-27T12:19:57.107Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.109Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.112Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:57.114Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT3767.CF0kqQ==\",\"time\":3294,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT6911.ZjHo2g==\",\"time\":3967,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5-1_PT1479.RH8WAQ==\",\"time\":103368,\,"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
