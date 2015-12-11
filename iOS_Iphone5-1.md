#### Test 531915643820a6d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/78DDD558-18A9-4ACD-82D9-79D7D6C747B9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/78DDD558-18A9-4ACD-82D9-79D7D6C747B9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08417072-9095-4390-AA12-71BC518A792E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53794"
,(lldb)     command script import "/tmp/78DDD558-18A9-4ACD-82D9-79D7D6C747B9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 01:46:51.450 ThaliTest[614:727232] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E71F181-CD7E-4623-A93E-50D9E58C95FB/Library/Cookies/Cookies.binarycookies
,2015-12-11 01:46:51.596 ThaliTest[614:727232] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 01:46:51.598 ThaliTest[614:727232] Multi-tasking -> Device: YES, App: YES
,2015-12-11 01:46:51.605 ThaliTest[614:727232] Unlimited access to network resources
,2015-12-11 01:46:51.616 ThaliTest[614:727232] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 01:47:02.532 ThaliTest[614:727232] Resetting plugins due to page load.
,2015-12-11 01:47:06.070 ThaliTest[614:727232] Finished load of: file:///var/mobile/Containers/Bundle/Application/08417072-9095-4390-AA12-71BC518A792E/ThaliTest.app/www/index.html
,2015-12-11 01:47:06.279 ThaliTest[614:727232] JXcore Cordova plugin initializing
,2015-12-11 01:47:06.281 ThaliTest[614:727485] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-Iphone5-1_PT4192
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,serverPort is 56875
,2015-12-11 01:55:25.717 ThaliTest[614:727485] jxcore: startBroadcasting
,2015-12-11 01:55:25.728 ThaliTest[614:727485] server: starting Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:25.729 ThaliTest[614:727485] multipeer session: start timer: 0x1ce4cbb0
2015-12-11 01:55:25.730 ThaliTest[614:727485] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4192
2015-12-11 01:55:25.731 ThaliTest[614:727485] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-11T00:55:25.732Z SendDataTCPServer.js: TCP/IP server is bound to port: 56875
,2015-12-11 01:55:26.840 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11T00:55:26.845Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11T00:55:26.845Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9748.JvjfiA==
20,15-12-11T00:55:26.845Z SendDataConnector.js: do connect now
2015-12-11 01:55:26.846 ThaliTest[614:727485] jxcore: connect Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:26.846 ThaliTest[614:727485] client session: connect
2015-12-11 01:55:26.847 ThaliTest[614:727485] client session: stateChange:0->1 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:27.488 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:29.464 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7285.LNATEw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-11 01:55:30.714 ThaliTest[614:727232] multipeer session: reset timer
2015-12-11 01:55:30.714 ThaliTest[614:727232] multipeer session: stop timer
2015-12-11 01:55:30.714 ThaliTest[614:727232] multipeer session: start timer: 0x1ce4cbb0
2015-12-11 ,01:55:30.715 ThaliTest[614:727232] server session: connect
2015-12-11 01:55:30.715 ThaliTest[614:727232] server session: stateChange:0->1 Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:30.721 ThaliTest[614:727232] server: accepting invitation Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:33.760 ThaliTest[614:728410] server session: connected
2015-12-11 01:55:33.761 ThaliTest[614:728410] server session: stateChange:1->2 Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:34.122 ThaliTest[614:727232] server relay: connected (to port: 56875)
2015-12-11T00:55:34.123Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 01:55:34.148 ThaliTest[614:727232] multipeer session: reset timer
2015-12-11 01:55:34.148 ThaliTest[614:727232] multipeer session: stop timer
2015-12-11 01:55:34.148 ThaliTest[614:727232] multipeer session: start timer: 0x1ce4cbb0
2015-12-11 ,01:55:34.149 ThaliTest[614:727232] server session: connect
2015-12-11 01:55:34.149 ThaliTest[614:727232] server session: stateChange:0->1 Apple-Iphone6-1_PT9748
,2015-12-11 01:55:34.155 ThaliTest[614:727232] server: accepting invitation Apple-Iphone6-1_PT9748
,2015-12-11 01:55:34.279 ThaliTest[614:728410] client session: connected
2015-12-11 01:55:34.280 ThaliTest[614:728410] client session: stateChange:1->2 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:34.301 ThaliTest[614:728410] client session: fireConnectCallback: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:34.301 ThaliTest[614:728410] jxcore: connect: success
2015-12-11T00:55:34.303Z SendDataConnector.js: CLIENT connected to 5,6879, error: null
2015-12-11T00:55:34.304Z SendDataConnector.js: CLIENT starting client 
2015-12-11 01:55:34.307 ThaliTest[614:727232] client: relay established
2015-12-11 01:55:34.307 ThaliTest[614:727232] client: new accepted socket: 0x1ce34060
,2015-12-11T00:55:34.320Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 01:55:34.839 ThaliTest[614:727232] multipeer session: reset timer
2015-12-11 01:55:34.840 ThaliTest[614:727232] multipeer session: stop timer
2015-12-11 01:55:34.840 ThaliTest[614:727232] multipeer session: start timer: 0x1ce4cbb0
2015-12-11 01:55:34.840 ThaliTest[614:727232] server session: connect
2015-12-11 01:55:34.841 ThaliTest[614:727232] server session: stateChange:0->1 Apple-IpadAir2-1_PT8618
2015-12-11 01:55:34.847 ThaliTest[614:727232] server: accepting invitation Apple-IpadAir2-1_PT8618
,2015-12-11T00:55:34.965Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11T00:55:35.156Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T00:55:35.255Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T00:55:35.273Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T00:55:35.287Z SendDataConnector.js: got all data for this round
,2015-12-11 01:55:35.293 ThaliTest[614:728410] server session: not connected Apple-Iphone5s-1_PT7285
,2015-12-11T00:55:35.293Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:55:35.304Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:35.306 ThaliTest[614:727485] jxcore: disconnect
,2015-12-11 01:55:35.308 ThaliTest[614:727485] client session: disconnectFromPeer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:35.311 ThaliTest[614:727485] client session: disconnect
,2015-12-11 01:55:35.312 ThaliTest[614:727485] client session: stateChange:2->0 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:35.401 ThaliTest[614:727485] jxcore: disconnect: success
2015-12-11T00:55:35.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9748.JvjfiA==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11T00:55:35.405Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11T00:55:35.405Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==,
2015-12-11T00:55:35.405Z SendDataConnector.js: do connect now
2015-12-11 01:55:35.405 ThaliTest[614:727485] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:35.406 ThaliTest[614:727485] client session: connect
2015-12-11 01:55:35.406 T,haliTest[614:727485] client session: stateChange:0->1 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:37.237 ThaliTest[614:728410] server session: connected
2015-12-11 01:55:37.237 ThaliTest[614:728410] server session: stateChange:1->2 Apple-Iphone6-1_PT9748
,2015-12-11 01:55:37.299 ThaliTest[614:727232] server relay: connected (to port: 56875)
2015-12-11T00:55:37.304Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:37.749Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T00:55:37.764Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T00:55:37.780Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2015-12-11T00:55:37.795Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-11T00:55:37.835Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-11T00:55:37.850Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T00:55:37.953Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-11T00:55:37.966Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:55:38.543 ThaliTest[614:728411] server session: not connected Apple-Iphone6-1_PT9748
,2015-12-11 01:55:38.810 ThaliTest[614:728411] server session: connected
2015-12-11 01:55:38.810 ThaliTest[614:728411] server session: stateChange:1->2 Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:38.864 ThaliTest[614:727232] server relay: connected (to port: 56875)
,2015-12-11T00:55:38.875Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 01:55:38.883 ThaliTest[614:728477] client session: connected
2015-12-11 01:55:38.884 ThaliTest[614:728477] client session: stateChange:1->2 Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:38.886 ThaliTest[614:728477] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:38.886 ThaliTest[614:728477] jxcore: connect: success
2015-12-11T00:55:38.887Z SendDataConnector.js: CLIENT connected to 56884, error: null
2015-12-11T00:55:38.887Z SendDataConnector.js: CLI,ENT starting client 
2015-12-11 01:55:38.890 ThaliTest[614:727232] client: relay established
2015-12-11 01:55:38.890 ThaliTest[614:727232] client: new accepted socket: 0x1ce1e370
,2015-12-11T00:55:38.902Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:39.499Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11T00:55:39.557Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11 01:55:39.965 ThaliTest[614:728477] server session: not connected Apple-IpadAir2-1_PT8618
2015-12-11T00:55:39.966Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T00:55:39.966Z SendDataConnector.js: got all data for this round,
,2015-12-11T00:55:39.967Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:55:39.968Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-11 01:55:39.969 ThaliTest[614:727485] jxcore: disconnect
2015-12-11 01:55:39.969 ThaliTest[614:727485] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:39.969 ThaliTest[614:727485] client session: disconnect
,2015-12-11 01:55:39.969 ThaliTest[614:727485] client session: stateChange:2->0 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:39.980 ThaliTest[614:727485] jxcore: disconnect: success
2015-12-11T00:55:39.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==
---- round done--------
device[3]: Apple-Iphone5s-1_PT7285.L,NATEw==
2015-12-11T00:55:39.981Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:39.982Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:39.982Z SendDataCo,nnector.js: do connect now
2015-12-11 01:55:39.982 ThaliTest[614:727485] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:39.983 ThaliTest[614:727485] client session: connect
,2015-12-11 01:55:39.983 ThaliTest[614:727485] client session: stateChange:0->1 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:51.893 ThaliTest[614:728403] client session: not connected Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:51.893 ThaliTest[614:728403] client session: onLinkFailure: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:51.893 ThaliTest[6,14:728403] client session: disconnect
2015-12-11 01:55:51.894 ThaliTest[614:728403] client session: stateChange:1->0 Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:51.894 ThaliTest[614:728403] client session: fireConnectCallback: Apple-Iphone5s-1_PT72,85.LNATEw==
2015-12-11 01:55:51.894 ThaliTest[614:728403] jxcore: connect: fail: Peer disconnected
2015-12-11T00:55:51.895Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T00:55:51.895Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer disconnected
2015-12-11T00:55:51.896Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T00:55:56.907Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:55:56.909Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:01.915 ThaliTest[614:727485] jxcore: disconnect
2015-12-11 01:56:01.916 ThaliTest[614:727485] jxcore: disconnect: fail
2015-12-11T00:56:01.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==,
2015-12-11T00:56:01.917Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7285.LNATEw== with availability status: true
2015-12-11T00:56:01.917Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:56:01.917Z SendDataConnector.js: do connect now
,2015-12-11 01:56:01.918 ThaliTest[614:727485] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:01.919 ThaliTest[614:727485] client session: connect
2015-12-11 01:56:01.919 ThaliTest[614:727485] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT7285.LNATEw==
,2015-12-11 01:56:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:56:04.875 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:04.886 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:04.886 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:56:05.028 ThaliTest[614:728403] client session: connected
2015-12-11 01:56:05.028 ThaliTest[614:728403] client session: stateChange:1->2 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:05.049 ThaliTest[614:728531] client session: fireConnectCallback: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:05.049 ThaliTest[614:728531] jxcore: connect: success
2015-12-11T00:56:05.050Z SendDataConnector.js: CLIENT connected to 56889, error: null
2015-12-11T00:56:05.050Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:56:05.053 ThaliTest[614:727232] client: relay established
2015-12-11 01:56:05.053 ThaliTest[614:727232] client: new accepted socket: 0x1cdc81a0
,2015-12-11T00:56:05.066Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:56:06.050Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T00:56:06.074Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T00:56:06.088Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T00:56:06.102Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T00:56:06.103Z SendDataConnector.js: got all data for this round
,2015-12-11T00:56:06.104Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:56:06.104Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:56:06.105 ThaliTest[614:727485] jxcore: disconnect
2015-12-11 01:56:06.105 ThaliTest[614:727485] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:06.106 ThaliTest[614:727485] client session: disconnect
2015-12-11 01:56:06.107 ThaliTest[614:727485] client session: stateChange:2->0 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:06.131 ThaliTest[614:727485] jxcore: disconnect: success
,2015-12-11T00:56:06.136Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT4192","time":40430,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9748.JvjfiA==","time":8446,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT8618.Ut+byw==","time":4561,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7285.LNATEw==","time":26122,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 26122 ms, 99% : 26122 ms, 95 : 26122 ms, 90% : 26122 ms.
,Result count 3, range 4561 ms to  26122 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-11T00:56:06.157Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:56:06.157Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:56:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:56:34.874 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:35.178 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:57:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:57:04.875 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:04.877 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:57:05.037 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:57:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:57:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:34.872 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:57:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:57:49.287 ThaliTest[614:727232] client: lost peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:49.288 ThaliTest[614:727232] client session: onPeerLost: Apple-Iphone6-1_PT9748.JvjfiA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:58:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:58:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:58:35.756 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:58:35.758 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:59:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:59:04.869 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:59:08.125 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:59:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 01:59:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:59:34.872 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:59:40.431 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 02:00:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:00:04.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:00:04.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:00:05.158 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:00:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:01:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:01:04.869 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:01:04.870 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:01:08.038 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:01:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:01:34.876 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:01:34.878 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:01:34.878 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:02:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:02:04.874 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:02:04.878 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:02:05.347 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:02:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:02:34.868 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:02:34.869 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:02:34.869 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:03:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:03:04.871 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:03:04.871 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:03:04.873 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:03:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:04:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:04:04.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:04:04.875 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:04:04.957 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:04:34.841 ThaliTest[614:727232] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-11 02:05:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:05:04.869 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:04.871 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:05:04.872 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-11 02:05:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:05:34.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:05:34.874 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 02:06:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:06:04.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:06:04.873 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:06:04.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:06:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:06:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:06:34.874 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:06:35.424 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:07:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:07:04.871 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:07:05.199 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:07:05.724 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:07:34.840 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:07:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:07:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:07:35.234 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:08:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:08:04.875 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:08:04.875 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:08:05.615 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:08:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:08:34.871 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:08:35.000 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:08:35.906 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:09:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:09:04.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:09:04.874 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:09:04.874 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:09:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:10:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:10:04.871 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:10:04.872 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:10:05.033 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:10:34.842 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:11:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:11:04.871 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:11:04.871 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:11:04.874 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:11:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:11:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:11:34.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:11:34.875 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 02:12:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:12:04.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:12:04.874 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:12:05.615 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:12:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:12:34.870 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:12:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:12:35.064 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:13:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:13:04.873 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:13:04.873 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:13:04.875 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:13:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:14:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:14:04.868 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:14:04.870 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:14:05.067 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:14:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:14:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:14:34.873 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:14:34.892 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:15:04.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:15:34.841 ThaliTest[614:727232] multipeer session: restart
,2015-12-11 02:15:34.872 ThaliTest[614:727232] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:15:34.872 ThaliTest[614:727232] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:15:35.233 ThaliTest[614:727232] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==

```
