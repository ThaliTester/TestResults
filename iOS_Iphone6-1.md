#### Test 51986340bb0815b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/99F84959-9422-4F8B-AF8F-531E0941D47C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/99F84959-9422-4F8B-AF8F-531E0941D47C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D94DB8BB-F078-4BD5-AF82-921A3E8422A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56953"
,(lldb)     command script import "/tmp/99F84959-9422-4F8B-AF8F-531E0941D47C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 13:09:42.883 ThaliTest[1903:1525064] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B52F443C-7983-488A-AEF3-4D160FCA3DF5/Library/Cookies/Cookies.binarycookies
,2015-11-27 13:09:43.248 ThaliTest[1903:1525064] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 13:09:43.249 ThaliTest[1903:1525064] Multi-tasking -> Device: YES, App: YES
,2015-11-27 13:09:43.257 ThaliTest[1903:1525064] Unlimited access to network resources
,2015-11-27 13:09:43.262 ThaliTest[1903:1525064] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 13:09:46.784 ThaliTest[1903:1525064] Resetting plugins due to page load.
,2015-11-27 13:09:47.127 ThaliTest[1903:1525064] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/D94DB8BB-F078-4BD5-AF82-921A3E8422A8/ThaliTest.app/www/index.html
,2015-11-27 13:09:47.249 ThaliTest[1903:1525064] JXcore Cordova plugin initializing
2015-11-27 13:09:47.250 ThaliTest[1903:1525198] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT6911
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 62694
,2015-11-27 13:16:20.618 ThaliTest[1903:1525198] jxcore: startBroadcasting
,2015-11-27 13:16:20.630 ThaliTest[1903:1525198] server: starting Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:20.631 ThaliTest[1903:1525198] multipeer session: start timer: 0x1b5eb0b0
2015-11-27 13:16:20.633 ThaliTest[1903:1525198] THEMultipeerSession initialized peer Apple-Iphone6-1_PT6911
2015-11-27 13:16:20.633 ThaliTest[1903:1525198] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-27T12:16:20.637Z SendDataTCPServer.js: TCP/IP server is bound to port: 62694
,2015-11-27 13:16:20.942 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:16:20.942 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:16:20.942 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-11-27 13:16:20.943 ThaliTest[1903:1525064] server session: connect
2015-11-27 13:16:20.943 ThaliTest[1903:1525064] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:16:20.951 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:16:21.168 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:16:21.176Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:16:21.178Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:16:21.179Z SendDataConnector.js: do connect now
,2015-11-27 13:16:21.180 ThaliTest[1903:1525198] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:16:21.181 ThaliTest[1903:1525198] client session: connect
2015-11-27 13:16:21.181 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:21.890 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:16:21.891 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:16:21.892 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-,11-27 13:16:21.892 ThaliTest[1903:1525064] server session: connect
2015-11-27 13:16:21.893 ThaliTest[1903:1525064] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:21.903 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:22.009 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:22.010 ThaliTest[1903:1525064] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one5-1_PT1479.RH8WAQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3767.CF0kqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Availab,le: true
,2015-11-27 13:16:23.235 ThaliTest[1903:1525754] server session: connected
,2015-11-27 13:16:23.236 ThaliTest[1903:1525754] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:16:23.248 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
2015-11-27T12:16:23.250Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:23.766Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-27T12:16:23.782Z SendDataTCPServer.js: TCP/IP server has received 21824 bytes of data
,2015-11-27T12:16:23.798Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-11-27T12:16:23.814Z SendDataTCPServer.js: TCP/IP server has received 52576 bytes of data
,2015-11-27T12:16:23.830Z SendDataTCPServer.js: TCP/IP server has received 69440 bytes of data
,2015-11-27T12:16:23.846Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-11-27T12:16:23.859Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:16:24.071 ThaliTest[1903:1525766] server session: connected
2015-11-27 13:16:24.071 ThaliTest[1903:1525766] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:24.182 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
,2015-11-27T12:16:24.193Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27 13:16:24.257 ThaliTest[1903:1525765] client session: connected
2015-11-27 13:16:24.257 ThaliTest[1903:1525765] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:24.266 ThaliTest[1903:1525760] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:16:24.267 ThaliTest[1903:1525760] jxcore: connect: success
,2015-11-27T12:16:24.270Z SendDataConnector.js: CLIENT connected to 62699, error: null
2015-11-27T12:16:24.270Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:24.275 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:16:24.275 ThaliTest[1903:1525064] client: new accepted socket: 0x1b5fb8b0
,2015-11-27T12:16:24.289Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:24.614Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:16:24.820 ThaliTest[1903:1525760] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:24.822 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:16:24.822 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:16:24.822 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
,2015-11-27 13:16:24.823 ThaliTest[1903:1525064] server session: connect
,2015-11-27 13:16:24.823 ThaliTest[1903:1525064] server session: stateChange:0->1 Apple-IpadAir2-1_PT3767
,2015-11-27T12:16:24.822Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-27 13:16:24.825 ThaliTest[1903:1525064] server: accepting invitation Apple-IpadAir2-1_PT3767
,2015-11-27T12:16:24.838Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-27T12:16:24.838Z SendDataConnector.js: got all data for this round
,2015-11-27T12:16:24.839Z SendDataConnector.js: CLIENT Stop now
,2015-11-27T12:16:24.839Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:24.840 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:16:24.841 ThaliTest[1903:1525198] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:24.842 ThaliTest[1903:1525198] client session: disconnect
,2015-11-27 13:16:24.842 ThaliTest[1903:1525198] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:16:24.902 ThaliTest[1903:1525198] jxcore: disconnect: success
,2015-11-27T12:16:24.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:24.904Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:24.905Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27T12:16:24.905Z SendDataConnector.js: do connect now
,2015-11-27 13:16:24.905 ThaliTest[1903:1525198] jxcore: connect Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:24.906 ThaliTest[1903:1525198] client session: connect
,2015-11-27 13:16:24.907 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:27.426 ThaliTest[1903:1525754] client session: connected
2015-11-27 13:16:27.426 ThaliTest[1903:1525754] client session: stateChange:1->2 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:27.449 ThaliTest[1903:1525754] client session: fireConnectCallback: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:27.450 ThaliTest[1903:1525754] jxcore: connect: success
2015-11-27T12:16:27.452Z SendDataConnector.js: CLIENT connected ,to 62702, error: null
2015-11-27T12:16:27.452Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:27.457 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:16:27.458 ThaliTest[1903:1525064] client: new accepted socket: 0x1b203510
,2015-11-27T12:16:27.466Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27 13:16:27.498 ThaliTest[1903:1525766] server session: connected
2015-11-27 13:16:27.499 ThaliTest[1903:1525766] server session: stateChange:1->2 Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:27.520 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
,2015-11-27T12:16:27.745Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:28.126Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-27T12:16:28.140Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-27T12:16:28.152Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-27T12:16:28.152Z SendDataConnector.js: got all data for this round
2015-11-27T12:16:28.155Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:16:28.155Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:16:28.157 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:16:28.158 ThaliTest[1903:1525198] client session: disconnectFromPeer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:16:28.159 ThaliTest[1903:1525198] client session: disconn,ect
2015-11-27 13:16:28.159 ThaliTest[1903:1525198] client session: stateChange:2->0 Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:28.162 ThaliTest[1903:1525198] jxcore: disconnect: success
2015-11-27T12:16:28.163Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1479.RH8WAQ==
---- round done--------
device[3]: Apple-IpadAir2-1_PT3767.,CF0kqQ==
2015-11-27T12:16:28.166Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27T12:16:28.166Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:16:28.166Z SendDataConnector.js: do connect now
,2015-11-27 13:16:28.167 ThaliTest[1903:1525198] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:28.168 ThaliTest[1903:1525198] client session: connect
2015-11-27 13:16:28.169 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:16:28.206Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-27T12:16:28.219Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:16:28.702 ThaliTest[1903:1525754] server session: not connected Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:31.316 ThaliTest[1903:1525766] client session: connected
2015-11-27 13:16:31.317 ThaliTest[1903:1525766] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:31.328 ThaliTest[1903:1525767] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:31.329 ThaliTest[1903:1525767] jxcore: connect: success
2015-11-27T12:16:31.329Z SendDataConnector.js: CLIENT connected to 62706, error: null
,2015-11-27T12:16:31.330Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:31.333 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:16:31.334 ThaliTest[1903:1525064] client: new accepted socket: 0x1b5fb8b0
,2015-11-27T12:16:31.345Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:31.744Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-27 13:16:34.202 ThaliTest[1903:1525760] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27T12:16:41.753Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:16:41.753Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:41.755Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:41.755Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:16:41.756Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:16:41.758 ThaliTest[1903:1525064] client: socket closed
2015-11-27 13:16:41.758 ThaliTest[1903:1525064] client relay: socket disconnected
2015-11-27 13:16:41.759 ThaliTest[1903:1525064] client relay: 0x1b5fb8b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x16ec1030 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:16:41.760 ThaliTest[1903:1525064] client session: socket closed: Apple-IpadAir2-1_PT3767.CF0kq,Q==
2015-11-27 13:16:41.760 ThaliTest[1903:1525064] client session: onLinkFailure: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:41.761 ThaliTest[1903:1525064] client session: disconnect
2015-11-27 13:16:41.761 ThaliTest[1903:1525064] client session,: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:41.764 ThaliTest[1903:1525064] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:44.175 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:16:44.176 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:16:44.176 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-,11-27 13:16:44.177 ThaliTest[1903:1525064] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:16:44.178 ThaliTest[1903:1525064] server session: disconnect
2015-11-27 13:16:44.178 ThaliTest[1903:1525064] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27T12:16:44.186Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27 13:16:44.187 ThaliTest[1903:1525064] server session: connect
2015-11-27 13:16:44.187 ThaliTest[1903:1525064] server session: stateChange:0,->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:16:44.199 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27T12:16:46.768Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:16:46.768Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:46.796 ThaliTest[1903:1525760] server session: connected
2015-11-27 13:16:46.797 ThaliTest[1903:1525760] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:16:46.808 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
,2015-11-27T12:16:46.815Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:46.967Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:16:51.772 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:16:51.773 ThaliTest[1903:1525198] jxcore: disconnect: fail
2015-11-27T12:16:51.774Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:16:51.775Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT3767.CF0kqQ== with availability status: true
2015-11-27T12:16:51.775Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
2015,-11-27T12:16:51.775Z SendDataConnector.js: do connect now
,2015-11-27 13:16:51.776 ThaliTest[1903:1525198] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:51.777 ThaliTest[1903:1525198] client session: connect
2015-11-27 13:16:51.778 ThaliTest[1903:1525198] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:55.952 ThaliTest[1903:1525829] client session: connected
2015-11-27 13:16:55.953 ThaliTest[1903:1525829] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:16:55.963 ThaliTest[1903:1525791] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:16:55.964 ThaliTest[1903:1525791] jxcore: connect: success
2015-11-27T12:16:55.965Z SendDataConnector.js: CLIENT connected, to 62710, error: null
2015-11-27T12:16:55.966Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:55.968 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:16:55.969 ThaliTest[1903:1525064] client: new accepted socket: 0x1b2221d0
,2015-11-27T12:16:55.982Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:16:56.899 ThaliTest[1903:1525829] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27T12:17:06.053Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:06.054Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:06.055Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:06.055Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:06.056Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:06.057 ThaliTest[1903:1525064] client: socket closed
2015-11-27 13:17:06.058 ThaliTest[1903:1525064] client relay: socket disconnected
2015-11-27 13:17:06.059 ThaliTest[1903:1525064] client relay: 0x1b2221d0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b27dfd0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:17:06.059 ThaliTest[1903:1525064] client session: socket closed: Apple-IpadAir2-1_PT3767.CF0kq,Q==
2015-11-27 13:17:06.060 ThaliTest[1903:1525064] client session: onLinkFailure: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:06.060 ThaliTest[1903:1525064] client session: disconnect
2015-11-27 13:17:06.061 ThaliTest[1903:1525064] client session,: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:06.062 ThaliTest[1903:1525064] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:07.899 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:17:07.900 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:17:07.900 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-,11-27 13:17:07.901 ThaliTest[1903:1525064] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:17:07.901 ThaliTest[1903:1525064] server session: disconnect
2015-11-27 13:17:07.902 ThaliTest[1903:1525064] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:17:07.905 ThaliTest[1903:1525064] server session: connect
2015-11-27T12:17:07.908Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27 13:17:07.906 ThaliTest[1903:1525064] server session: stateChange:0,->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:17:07.921 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:17:10.418 ThaliTest[1903:1525865] server session: connected
2015-11-27 13:17:10.418 ThaliTest[1903:1525865] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:17:10.430 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
2015-11-27T12:17:10.434Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:10.511Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-27T12:17:10.526Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27T12:17:11.062Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:17:11.063Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:16.068 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:17:16.068 ThaliTest[1903:1525198] jxcore: disconnect: fail
2015-11-27T12:17:16.069Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0k,qQ==
2015-11-27T12:17:16.070Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT3767.CF0kqQ== with availability status: true
2015-11-27T12:17:16.070Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==,
,2015-11-27T12:17:16.070Z SendDataConnector.js: do connect now
2015-11-27 13:17:16.071 ThaliTest[1903:1525198] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:16.072 ThaliTest[1903:1525198] client session: connect
2015-11-27 13:17:16.073 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:19.086 ThaliTest[1903:1525766] client session: connected
2015-11-27 13:17:19.087 ThaliTest[1903:1525766] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:19.094 ThaliTest[1903:1525866] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:19.095 ThaliTest[1903:1525866] jxcore: connect: success
,2015-11-27T12:17:19.096Z SendDataConnector.js: CLIENT connected to 62714, error: null
2015-11-27T12:17:19.096Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:19.100 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:17:19.100 ThaliTest[1903:1525064] client: new accepted socket: 0x1b5fb8b0
,2015-11-27T12:17:19.112Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:21.028 ThaliTest[1903:1525866] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:17:27.144 ThaliTest[1903:1525064] client: lost peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:17:27.145 ThaliTest[1903:1525064] client session: onPeerLost: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":false}]
2015-11-27 13:17:27.148 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==,","peerName":"(null)","peerAvailable":true}]
,2015-11-27T12:17:29.189Z SendDataConnector.js: Receiving data timeout now
2015-11-27T12:17:29.189Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:29.190Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:29.190Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:29.191Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:29.193 ThaliTest[1903:1525064] client: socket closed
2015-11-27 13:17:29.194 ThaliTest[1903:1525064] client relay: socket disconnected
,2015-11-27 13:17:29.195 ThaliTest[1903:1525064] client relay: 0x1b5fb8b0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2a8990 {NSLocalizedDescription=Socket closed by remote peer} 
2015-1,1-27 13:17:29.195 ThaliTest[1903:1525064] client session: socket closed: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:29.196 ThaliTest[1903:1525064] client session: onLinkFailure: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:29.196 ThaliTest[19,03:1525064] client session: disconnect
2015-11-27 13:17:29.197 ThaliTest[1903:1525064] client session: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:29.198 ThaliTest[1903:1525064] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:30.837 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:17:30.838 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:17:30.838 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-,11-27 13:17:30.839 ThaliTest[1903:1525064] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:17:30.839 ThaliTest[1903:1525064] server session: disconnect
2015-11-27 13:17:30.840 ThaliTest[1903:1525064] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27T12:17:30.845Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:17:30.904 ThaliTest[1903:1525064] server session: connect
2015-11-27 13:17:30.904 ThaliTest[1903:1525064] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
,2015-11-27 13:17:30.910 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:17:33.073 ThaliTest[1903:1525899] server session: connected
2015-11-27 13:17:33.074 ThaliTest[1903:1525899] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:17:33.086 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
2015-11-27T12:17:33.088Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:33.438Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-27T12:17:33.452Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:17:33.964 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:17:34.196Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:17:34.197Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:39.201 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:17:39.202 ThaliTest[1903:1525198] jxcore: disconnect: fail
2015-11-27T12:17:39.202Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0k,qQ==
2015-11-27T12:17:39.203Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT3767.CF0kqQ== with availability status: true
2015-11-27T12:17:39.203Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:17:39.203Z SendDataConnector.js: do connect now
2015-11-27 13:17:39.204 ThaliTest[1903:1525198] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:39.205 ThaliTest[1903:1525198] client session: connect
,2015-11-27 13:17:39.206 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:43.001 ThaliTest[1903:1525899] client session: connected
2015-11-27 13:17:43.001 ThaliTest[1903:1525899] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:43.009 ThaliTest[1903:1525908] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:43.010 ThaliTest[1903:1525908] jxcore: connect: success
2015-11-27T12:17:43.010Z SendDataConnector.js: CLIENT connected to 62718, error: null
,2015-11-27T12:17:43.011Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:43.014 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:17:43.015 ThaliTest[1903:1525064] client: new accepted socket: 0x1b5fb8b0
,2015-11-27T12:17:43.026Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:43.393 ThaliTest[1903:1525908] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27T12:17:53.096Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:53.097Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:17:53.097Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:53.098Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:53.098Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:53.100 ThaliTest[1903:1525064] client: socket closed
2015-11-27 13:17:53.100 ThaliTest[1903:1525064] client relay: socket disconnected
2015-11-27 13:17:53.101 ThaliTest[1903:1525064] client relay: 0x1b5fb8b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b2f8580 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-27 13:17:53.102 ThaliTest[1903:1525064] client session: socket closed: Apple-IpadAir2-1_PT3767.CF0kq,Q==
2015-11-27 13:17:53.102 ThaliTest[1903:1525064] client session: onLinkFailure: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:17:53.102 ThaliTest[1903:1525064] client session: disconnect
2015-11-27 13:17:53.103 ThaliTest[1903:1525064] client session: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:53.104 ThaliTest[1903:1525064] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:17:53.372 ThaliTest[1903:1525064] multipeer session: reset timer
2015-11-27 13:17:53.373 ThaliTest[1903:1525064] multipeer session: stop timer
2015-11-27 13:17:53.373 ThaliTest[1903:1525064] multipeer session: start timer: 0x1b5eb0b0
2015-,11-27 13:17:53.374 ThaliTest[1903:1525064] server: disconnecting to refresh session (Apple-Iphone5-1_PT1479)
2015-11-27 13:17:53.374 ThaliTest[1903:1525064] server session: disconnect
2015-11-27 13:17:53.375 ThaliTest[1903:1525064] server session: stateC,hange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:17:53.378 ThaliTest[1903:1525064] server session: connect
2015-11-27 13:17:53.379 ThaliTest[1903:1525064] server session: stateChange:0->1 Apple-Iphone5-1_PT1479
2015-11-27T12:17:53.383Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-11-27 13:17:53.394 ThaliTest[1903:1525064] server: accepting invitation Apple-Iphone5-1_PT1479
,2015-11-27 13:17:55.646 ThaliTest[1903:1525950] server session: connected
2015-11-27 13:17:55.647 ThaliTest[1903:1525950] server session: stateChange:1->2 Apple-Iphone5-1_PT1479
,2015-11-27 13:17:55.784 ThaliTest[1903:1525064] server relay: connected (to port: 62694)
,2015-11-27T12:17:55.793Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:55.880Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:17:57.023 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:17:58.105Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:17:58.106Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:02.919 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:03.109 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:18:03.109 ThaliTest[1903:1525198] jxcore: disconnect: fail
2015-11-27T12:18:03.110Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0k,qQ==
2015-11-27T12:18:03.110Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT3767.CF0kqQ== with availability status: true
,2015-11-27T12:18:03.111Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27T12:18:03.111Z SendDataConnector.js: do connect now
,2015-11-27 13:18:03.112 ThaliTest[1903:1525198] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:03.113 ThaliTest[1903:1525198] client session: connect
2015-11-27 13:18:03.114 ThaliTest[1903:1525198] client session: stateChange:0->1 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:05.933 ThaliTest[1903:1525899] server session: not connected Apple-Iphone5-1_PT1479
,2015-11-27 13:18:05.997 ThaliTest[1903:1525968] client session: connected
2015-11-27 13:18:05.998 ThaliTest[1903:1525968] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:06.008 ThaliTest[1903:1525914] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:06.009 ThaliTest[1903:1525914] jxcore: connect: success
2015-11-27T12:18:06.009Z SendDataConnector.js: CLIENT connected to 62722, error: null
2015-11-27T12:18:06.010Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:18:06.013 ThaliTest[1903:1525064] client: relay established
2015-11-27 13:18:06.014 ThaliTest[1903:1525064] client: new accepted socket: 0x1b143080
,2015-11-27T12:18:06.025Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27T12:18:16.097Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:18:16.098Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:16.098Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:16.100Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:18:16.101Z SendDataConnector.js: Stop data retrieving timer
2015-11-27T12:18:16.101Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:18:16.102 ThaliTest[1903:1525198] jxcore: disconnect
2015-11-27 13:18:16.103 ThaliTest[1903:1525198] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:16.103 ThaliTest[1903:1525198] client session: discon,nect
2015-11-27 13:18:16.104 ThaliTest[1903:1525198] client session: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:16.107 ThaliTest[1903:1525198] jxcore: disconnect: success
2015-11-27T12:18:16.108Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT6911","time":115507,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8509.17j4Hw==","time":3661,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT1479.RH8WAQ==","time":3248,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT3767.CF0kqQ==","time":107933,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 3661 ms, 99% : 3661 ms, 95 : 3661 ms, 90% : 3661 ms.
Result count 2, range 3248 ms to  3661 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-IpadAir2-1_PT3767.CF0kqQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-27T12:18:16.122Z SendDataConnector.js: CLIENT Stop now
,2015-11-27T12:18:16.122Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:16.123Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:18:23.374 ThaliTest[1903:1525064] multipeer session: restart
,2015-11-27 13:18:23.392 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:23.396 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
2015-11-27 13:18:23.397 ThaliTest[1903:1525064] clien,t: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:18:53.372 ThaliTest[1903:1525064] multipeer session: restart
,2015-11-27 13:18:53.426 ThaliTest[1903:1525064] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:53.427 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:53.428 ThaliTest[1903:1525064] clie,nt: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:19:23.373 ThaliTest[1903:1525064] multipeer session: restart
,2015-11-27 13:19:23.394 ThaliTest[1903:1525064] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:19:23.395 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:23.398 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:19:53.373 ThaliTest[1903:1525064] multipeer session: restart
,2015-11-27 13:19:53.392 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:19:53.394 ThaliTest[1903:1525064] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:19:53.395 ThaliTest[1903:1525064] client: found peer: Apple-Iphone5-1_PT1479.RH8WAQ==
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-27 13:19:56.902 ThaliTest[1903:1525198] jxcore: stopBroadcasting
2015-11-27 13:19:56.903 ThaliTest[1903:1525198] THEMultipeerSession stopping peer
2015-11-27 13:19:56.903 ThaliTest[1903:1525198] multipeer session: stop timer
2015-11-27 13:19:56.,904 ThaliTest[1903:1525198] server session: disconnect
2015-11-27 13:19:56.905 ThaliTest[1903:1525198] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
2015-11-27 13:19:56.911 ThaliTest[1903:1525198] server session: disconnect
2015-11-27 13:19:5,6.911 ThaliTest[1903:1525198] server session: stateChange:2->0 Apple-IpadAir2-1_PT3767
,2015-11-27 13:19:56.919 ThaliTest[1903:1525198] server session: disconnect
2015-11-27 13:19:56.919 ThaliTest[1903:1525198] server session: stateChange:2->0 Apple-Iphone5-1_PT1479
2015-11-27 13:19:56.923 ThaliTest[1903:1525198] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-27T12:19:56.944Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:56.946Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:56.947Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:19:56.949Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT1479.RH8WAQ==\",\"time\":3248,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT8509.17j4Hw==\",\"time\":3661,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-IpadAir2-1_PT3767.CF0kqQ==\",\"time\":107933,,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
