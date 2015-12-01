#### Test 522773652a05488_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/05AF7E0E-CE70-4CDD-B449-CE453EFCB02F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/05AF7E0E-CE70-4CDD-B449-CE453EFCB02F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0A827BCC-5E23-4285-AFF8-A9F1478C3B47/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58612"
,(lldb)     command script import "/tmp/05AF7E0E-CE70-4CDD-B449-CE453EFCB02F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 17:19:59.806 ThaliTest[1704:2677193] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C8023945-6ACD-40CB-9882-BD960F3ED41E/Library/Cookies/Cookies.binarycookies
,2015-12-01 17:20:00.106 ThaliTest[1704:2677193] Apache Cordova native platform version 3.9.2 is starting.
2015-12-01 17:20:00.107 ThaliTest[1704:2677193] Multi-tasking -> Device: YES, App: YES
,2015-12-01 17:20:00.114 ThaliTest[1704:2677193] Unlimited access to network resources
,2015-12-01 17:20:00.120 ThaliTest[1704:2677193] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 17:20:04.279 ThaliTest[1704:2677193] Resetting plugins due to page load.
,2015-12-01 17:20:05.747 ThaliTest[1704:2677193] Finished load of: file:///var/mobile/Containers/Bundle/Application/0A827BCC-5E23-4285-AFF8-A9F1478C3B47/ThaliTest.app/www/index.html
,2015-12-01 17:20:05.884 ThaliTest[1704:2677193] JXcore Cordova plugin initializing
2015-12-01 17:20:05.884 ThaliTest[1704:2677374] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT7863
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 64024
,2015-12-01 17:26:58.882 ThaliTest[1704:2677374] jxcore: startBroadcasting
,2015-12-01 17:26:58.889 ThaliTest[1704:2677374] server: starting Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:26:58.889 ThaliTest[1704:2677374] multipeer session: start timer: 0x19606910
2015-12-01 17:26:58.889 ThaliTest[1704:2677374] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7863
,2015-12-01 17:26:58.890 ThaliTest[1704:2677374] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-01T16:26:58.891Z SendDataTCPServer.js: TCP/IP server is bound to port: 64024
,2015-12-01 17:26:59.598 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:26:59.599 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:26:59.601Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:26:59.602Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:26:59.602Z SendDataConnector.js: do connect now
2015-12-01 17:26:59.602 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:26:59.602 ThaliTest[1704:2677374] client session: connect
2015-12-01 17:26:59.602 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:27:00.109 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:27:02.513 ThaliTest[1704:2678174] client session: connected
2015-12-01 17:27:02.513 ThaliTest[1704:2678174] client session: stateChange:1->2 Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:27:02.514 ThaliTest[1704:2678174] client session: fir,eConnectCallback: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:27:02.514 ThaliTest[1704:2678174] jxcore: connect: success
,2015-12-01T16:27:02.516Z SendDataConnector.js: CLIENT connected to 64027, error: null
2015-12-01T16:27:02.516Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:02.517 ThaliTest[1704:2677193] client: relay established
2015-12-01 17:27:02.517 ThaliTest[1704:2677193] client: new accepted socket: 0x19601050
,2015-12-01T16:27:02.529Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:27:03.119Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:27:03.119Z SendDataConnector.js: got all data for this round
,2015-12-01T16:27:03.120Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:27:03.121Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:27:03.122 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:27:03.122 ThaliTest[1704:2677374] client session: disconnectFromPeer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:27:03.122 ThaliTest[1704:2677374] client session: disconnect
2015-12-01 17:27:03.122 ThaliTest[1704:2677374] client session: stateChange:2->0 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:27:03.127 ThaliTest[1704:2677374] jxcore: disconnect: success
2015-12-01T16:27:03.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8196.sJeqaQ==
---- round done--------
,device[2]: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:03.130Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:03.130Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:03.130Z SendDataConnector.js: do connect now
,2015-12-01 17:27:03.130 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:03.131 ThaliTest[1704:2677374] client session: connect
,2015-12-01 17:27:03.131 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:06.267 ThaliTest[1704:2678180] client session: connected
2015-12-01 17:27:06.267 ThaliTest[1704:2678180] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:06.268 ThaliTest[1704:2678180] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:06.268 ThaliTest[1704:2678180] jxcore: connect: success
2015-12-01T16:27:06.269Z SendDataConnector.js: CLIENT connected to 64031, error: null
,2015-12-01T16:27:06.269Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:06.270 ThaliTest[1704:2677193] client: relay established
2015-12-01 17:27:06.270 ThaliTest[1704:2677193] client: new accepted socket: 0x1a82a110
,2015-12-01T16:27:06.283Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01 17:27:06.398 ThaliTest[1704:2677193] multipeer session: reset timer
2015-12-01 17:27:06.398 ThaliTest[1704:2677193] multipeer session: stop timer
2015-12-01 17:27:06.399 ThaliTest[1704:2677193] multipeer session: start timer: 0x19606910
2015-,12-01 17:27:06.399 ThaliTest[1704:2677193] server session: connect
2015-12-01 17:27:06.399 ThaliTest[1704:2677193] server session: stateChange:0->1 Apple-Iphone5s-1_PT4380
2015-12-01 17:27:06.402 ThaliTest[1704:2677193] server: accepting invitation Apple-Iphone5s-1_PT4380
,2015-12-01T16:27:07.498Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T16:27:07.873Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-01T16:27:07.909Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 17:27:10.069 ThaliTest[1704:2678174] server session: connected
2015-12-01 17:27:10.069 ThaliTest[1704:2678174] server session: stateChange:1->2 Apple-Iphone5s-1_PT4380
,2015-12-01 17:27:10.073 ThaliTest[1704:2677193] server relay: connected (to port: 64024)
,2015-12-01T16:27:10.084Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:10.393Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-01T16:27:10.406Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-01T16:27:10.445Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-01T16:27:10.471Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-01T16:27:10.484Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:27:10.655 ThaliTest[1704:2678180] server session: not connected Apple-Iphone5s-1_PT4380
,2015-12-01T16:27:17.912Z SendDataConnector.js: Receiving data timeout now
2015-12-01T16:27:17.912Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:17.913Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:27:17.913Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:27:17.913Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:17.914 ThaliTest[1704:2677193] client: socket closed
2015-12-01 17:27:17.914 ThaliTest[1704:2677193] client relay: socket disconnected
2015-12-01 17:27:17.914 ThaliTest[1704:2677193] client relay: 0x1a82a110 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 17:27:17.915 ThaliTest[1704:2677193] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:17.915 ThaliTest[1704:2677193] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:17.915 ThaliTest[1704:2677193] client session: disconnect
2015-12-01 17:27:17.915 ThaliTest[1704:2677193] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:17.917 ThaliTest[1704:2677193] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:22.922Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:22.923Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:27.932 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:27:27.932 ThaliTest[1704:2677374] jxcore: disconnect: fail
,2015-12-01T16:27:27.933Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:27.933Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status,: true
2015-12-01T16:27:27.933Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:27.933Z SendDataConnector.js: do connect now
2015-12-01 17:27:27.933 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:27.933 ThaliTest[1704:2677374] client session: connect
2015-12-01 17:27:27.933 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:32.578 ThaliTest[1704:2678261] client session: connected
2015-12-01 17:27:32.578 ThaliTest[1704:2678261] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:32.580 ThaliTest[1704:2678268] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:32.580 ThaliTest[1704:2678268] jxcore: connect: success
,2015-12-01T16:27:32.581Z SendDataConnector.js: CLIENT connected to 64036, error: null
2015-12-01T16:27:32.581Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:32.582 ThaliTest[1704:2677193] client: relay established
2015-12-01 17:27:32.582 ThaliTest[1704:2677193] client: new accepted socket: 0x19358250
,2015-12-01T16:27:32.595Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 17:27:36.400 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:27:36.412 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:27:36.412 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:36.646 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:27:42.627Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:27:42.628Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:42.628Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01T16:27:42.628Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-01T16:27:42.628Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:27:42.629 ThaliTest[1704:2677193] client: socket closed
2015-12-01 17:27:42.629 ThaliTest[1704:2677193] client relay: socket disconnected
,2015-12-01 17:27:42.629 ThaliTest[1704:2677193] client relay: 0x19358250 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-01 17:27:42.629 ThaliTest[1704:2677193] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:42.630 ThaliTest[1704:2677193] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:42.630 ThaliTest[1704:2677193] client session: disconnect
2015-12-01 17:27:42.630 ThaliTest[1704:2677193] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:42.632 ThaliTest[1704:2677193] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:27:47.635Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:47.635Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:52.647 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:27:52.648 ThaliTest[1704:2677374] jxcore: disconnect: fail
2015-12-01T16:27:52.648Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAd,cQ==
2015-12-01T16:27:52.648Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:27:52.648Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:27:52.648Z SendDataConnector.js: do connect now
2015-12-01 17:27:52.648 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:52.648 ThaliTest[1704:2677374] client session: connect
,2015-12-01 17:27:52.649 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:55.605 ThaliTest[1704:2678327] client session: connected
2015-12-01 17:27:55.605 ThaliTest[1704:2678327] client session: stateChange:1->2 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:27:55.608 ThaliTest[1704:2678327] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:27:55.608 ThaliTest[1704:2678327] jxcore: connect: success
,2015-12-01T16:27:55.608Z SendDataConnector.js: CLIENT connected to 64041, error: null
,2015-12-01T16:27:55.608Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:55.609 ThaliTest[1704:2677193] client: relay established
2015-12-01 17:27:55.609 ThaliTest[1704:2677193] client: new accepted socket: 0x1967c110
,2015-12-01T16:27:55.622Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-01 17:28:02.283 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01T16:28:05.647Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T16:28:05.648Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:05.648Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T16:28:05.649Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T16:28:05.649Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client: socket closed
2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client relay: socket disconnected
2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client relay: 0x1967c110 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client session: socket closed: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-1,2-01 17:28:05.650 ThaliTest[1704:2677193] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client session: disconnect
2015-12-01 17:28:05.650 ThaliTest[1704:2677193] client session: stateChange:2->0 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:05.652 ThaliTest[1704:2677193] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:06.400 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01T16:28:10.657Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01T16:28:10.657Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:15.662 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:15.662 ThaliTest[1704:2677374] jxcore: disconnect: fail
2015-12-01T16:28:15.662Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAd,cQ==
2015-12-01T16:28:15.662Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:28:15.662Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==,
2015-12-01T16:28:15.663Z SendDataConnector.js: do connect now
2015-12-01 17:28:15.663 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:15.663 ThaliTest[1704:2677374] client session: connect
2015-12-01 17:28:15.663 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:15.666 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:15.666 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:15.666 ThaliTest[1704:2677193] client session: onLinkFailure: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:15.666 ThaliTest[1704:2677193] client session: disconnect
2015-12-01 17:28:15.666 ThaliTest[1704:2677193] client session: stateChange:1->0 Apple-Iphone5s-1_PT4380.ZyAdcQ=,=
,2015-12-01 17:28:15.719 ThaliTest[1704:2677193] client session: fireConnectCallback: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:15.719 ThaliTest[1704:2677193] jxcore: connect: fail: Peer disconnected
2015-12-01T16:28:15.720Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-01T16:28:15.720Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-01T16:28:15.720Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01T16:28:20.725Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:20.725Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:28:25.735 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:25.735 ThaliTest[1704:2677374] jxcore: disconnect: fail
2015-12-01T16:28:25.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAd,cQ==
2015-12-01T16:28:25.735Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4380.ZyAdcQ== with availability status: true
2015-12-01T16:28:25.735Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01T16:28:25.735Z SendDataConnector.js: do connect now
,2015-12-01 17:28:25.736 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:25.736 ThaliTest[1704:2677374] client: connect: unreachable Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:25.736 ThaliTest[1704:2677374] jxcore: connect: fail: Peer unreachable
2015-12-01T16:28:25.736Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-01T16:28:25.737Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-01T16:28:25.737Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T16:28:25.737Z SendDataConnector.js: Stop data retrieving timer
,2015-12-01 17:28:25.740 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:25.741 ThaliTest[1704:2677374] jxcore: disconnect: fail
2015-12-01T16:28:25.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4380.ZyAdcQ==
---- round done--------
,device[3]: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:28:25.743Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:28:25.743Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:28:25.743Z SendDataConnector.js: do connect now
,2015-12-01 17:28:25.744 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:25.744 ThaliTest[1704:2677374] client session: connect
2015-12-01 17:28:25.744 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:25.749 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:25.749 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:25.749 ThaliTest[1704:2677193] client session: onLinkFailure: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:25.749 ThaliTest[1,704:2677193] client session: disconnect
2015-12-01 17:28:25.749 ThaliTest[1704:2677193] client session: stateChange:1->0 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:25.802 ThaliTest[1704:2677193] client session: fireConnectCallback: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:25.802 ThaliTest[1704:2677193] jxcore: connect: fail: Peer disconnected
,2015-12-01T16:28:25.802Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-01T16:28:25.803Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-01T16:28:25.803Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":false}]
,2015-12-01T16:28:30.802Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:28:30.802Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:35.794 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:35.795 ThaliTest[1704:2677374] jxcore: disconnect: fail
,2015-12-01T16:28:35.795Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:35.795Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6379.NUteEA== with availability status: true
2015-12-01T16:28:35.795Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:35.795Z SendDataConnector.js: do connect now
,2015-12-01 17:28:35.796 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:35.796 ThaliTest[1704:2677374] client: connect: unreachable Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:35.796 ThaliTest[1704:2677374] jxcore: connect: fail: Peer unreachable
2015-12-01T16:28:35.796Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-01T16:28:35.796Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-01T16:28:35.796Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01 17:28:36.382 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:28:36.603 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:36.604 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:28:36.604 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":true}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01T16:28:40.807Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:40.808Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:45.329 ThaliTest[1704:2677193] multipeer session: reset timer
2015-12-01 17:28:45.329 ThaliTest[1704:2677193] multipeer session: stop timer
2015-12-01 17:28:45.329 ThaliTest[1704:2677193] multipeer session: start timer: 0x19606910
2015-12-01 17:28:45.329 ThaliTest[1704:2677193] server session: connect
2015-12-01 17:28:45.329 ThaliTest[1704:2677193] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
,2015-12-01 17:28:45.332 ThaliTest[1704:2677193] server: accepting invitation Apple-Iphone6-1_PT8196
,2015-12-01 17:28:45.814 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:45.814 ThaliTest[1704:2677374] jxcore: disconnect: fail
,2015-12-01T16:28:45.815Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:45.815Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6379.NUteEA== with availability status: ,true
2015-12-01T16:28:45.815Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01T16:28:45.815Z SendDataConnector.js: do connect now
2015-12-01 17:28:45.815 ThaliTest[1704:2677374] jxcore: connect Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:45.816 ThaliTest[1704:2677374] client session: connect
2015-12-01 17:28:45.816 ThaliTest[1704:2677374] client session: stateChange:0->1 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:47.528 ThaliTest[1704:2678477] server session: connected
2015-12-01 17:28:47.528 ThaliTest[1704:2678477] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:28:47.531 ThaliTest[1704:2677193] server relay: connected (to port: 64024)
,2015-12-01T16:28:47.533Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:47.886Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-01T16:28:47.943Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-01T16:28:47.955Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-01T16:28:48.399Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:28:48.442 ThaliTest[1704:2678477] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:28:48.470 ThaliTest[1704:2678477] client session: connected
2015-12-01 17:28:48.470 ThaliTest[1704:2678477] client session: stateChange:1->2 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:48.536 ThaliTest[1704:2678472] client session: fireConnectCallback: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:48.536 ThaliTest[1704:2678472] jxcore: connect: success
,2015-12-01T16:28:48.537Z SendDataConnector.js: CLIENT connected to 64047, error: null
,2015-12-01T16:28:48.537Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:28:48.538 ThaliTest[1704:2677193] client: relay established
2015-12-01 17:28:48.539 ThaliTest[1704:2677193] client: new accepted socket: 0x194d46b0
,2015-12-01T16:28:48.552Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:28:49.115Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T16:28:49.129Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:28:49.130Z SendDataConnector.js: got all data for this round
,2015-12-01T16:28:49.130Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:49.131Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:49.131 ThaliTest[1704:2677374] jxcore: disconnect
2015-12-01 17:28:49.131 ThaliTest[1704:2677374] client session: disconnectFromPeer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:28:49.131 ThaliTest[1704:2677374] client session: disconnect
2015-12-01 17:28:49.131 ThaliTest[1704:2677374] client session: stateChange:2->0 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:28:49.136 ThaliTest[1704:2677374] jxcore: disconnect: success
2015-12-01T16:28:49.136Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6379.NUteEA==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7863","time":110259,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8196.sJeqaQ==","time":3519,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","time":82607,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5-1_PT6379.NUteEA==",",time":23387,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 23387 ms, 99% : 23387 ms, 95 : 23387 ms, 90% : 23387 ms.
Result count 2, range 3519 ms to  23387 ms.
sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT4380.ZyAdcQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-01T16:28:49.142Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:28:49.142Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:28:59.411 ThaliTest[1704:2677193] multipeer session: reset timer
2015-12-01 17:28:59.411 ThaliTest[1704:2677193] multipeer session: stop timer
2015-12-01 17:28:59.412 ThaliTest[1704:2677193] multipeer session: start timer: 0x19606910
2015-,12-01 17:28:59.412 ThaliTest[1704:2677193] server session: connect
2015-12-01 17:28:59.412 ThaliTest[1704:2677193] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:59.414 ThaliTest[1704:2677193] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:29:01.628 ThaliTest[1704:2678472] server session: connected
2015-12-01 17:29:01.628 ThaliTest[1704:2678472] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:29:01.680 ThaliTest[1704:2677193] server relay: connected (to port: 64024)
,2015-12-01T16:29:01.684Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:29:02.138Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-12-01T16:29:02.164Z SendDataTCPServer.js: TCP/IP server has received 36704 bytes of data
,2015-12-01T16:29:02.178Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-12-01T16:29:02.292Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-01T16:29:02.550Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-12-01T16:29:02.563Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:29:02.630 ThaliTest[1704:2678522] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:29:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:29:29.424 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:29:29.424 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:29:29.424 ThaliTest[1704:2677193] clien,t: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:29:41.390 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:29:41.390 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:29:46.182 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:29:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:29:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:29:59.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:59.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:30:11.398 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:30:11.398 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:30:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:30:29.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:30:29.631 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:30.241 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:30:54.774 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:30:54.774 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:30:56.485 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:30:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:30:59.424 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:30:59.426 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:59.426 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:31:07.255 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:31:07.255 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:07.300 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:31:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:31:29.424 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:31:29.425 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:31:29.970 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:31:54.525 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:31:54.525 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:31:59.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:31:59.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:32:00.763 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:32:17.665 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:17.665 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:32:18.158 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:32:20.739 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:20.739 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:32:21.867 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:32:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:32:29.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:32:29.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:32:29.424 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:32:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:32:59.425 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:32:59.425 ThaliTest[1704:2677193] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:59.425 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:33:18.345 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:33:18.345 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:33:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:33:29.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:33:29.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:33:35.170 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:33:35.170 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:33:35.855 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:33:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:33:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:33:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:34:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:34:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:34:59.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:34:59.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:35:11.225 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:35:11.225 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:35:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:35:59.412 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:36:00.485 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:36:00.485 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:36:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:36:29.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:36:29.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:36:41.384 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:36:41.384 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:36:46.570 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:36:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:36:59.423 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:37:00.260 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:37:11.785 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:37:11.786 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:37:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:37:29.636 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:37:29.637 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:37:41.151 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:37:41.151 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:37:46.325 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:37:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:37:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:38:00.001 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:38:11.540 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:38:11.540 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:38:19.882 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:38:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:38:29.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:38:30.406 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:38:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:38:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:38:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:39:11.295 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:39:11.295 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:39:16.484 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:39:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:39:29.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:39:30.131 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:39:41.698 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:39:41.698 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:39:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:39:59.564 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:39:59.564 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:40:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:40:29.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:40:29.892 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:40:41.455 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:40:41.456 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:40:58.303 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:40:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:40:59.422 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:41:00.355 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:41:07.664 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:41:07.664 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:41:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:41:29.684 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:41:29.684 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:41:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:42:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:42:29.419 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:42:31.450 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:42:36.745 ThaliTest[1704:2677193] client: lost peer: Apple-Iphone5s-1_PT4380.ZyAdcQ==
2015-12-01 17:42:36.745 ThaliTest[1704:2677193] client session: onPeerLost: Apple-Iphone5s-1_PT4380.ZyAdcQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT4380.ZyAdcQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:42:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:42:59.787 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:43:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:43:30.243 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:43:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:44:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:44:29.986 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:44:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:45:00.346 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:45:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:45:59.412 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:46:00.145 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:46:29.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:46:29.421 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:46:59.413 ThaliTest[1704:2677193] multipeer session: restart
,2015-12-01 17:46:59.420 ThaliTest[1704:2677193] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==

```
