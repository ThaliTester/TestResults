#### Test 51790364a0f6051_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/44DD76EC-F3F2-4D67-B28B-294ABC4DAF73/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/44DD76EC-F3F2-4D67-B28B-294ABC4DAF73/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2623B3B4-BAE9-4533-9A09-C9123D7FF928/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56126"
,(lldb)     command script import "/tmp/44DD76EC-F3F2-4D67-B28B-294ABC4DAF73/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 07:47:43.934 ThaliTest[1360:1846247] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/13180583-BD5D-4674-A671-1B1795B4BCB0/Library/Cookies/Cookies.binarycookies
,2015-11-26 07:47:44.234 ThaliTest[1360:1846247] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-26 07:47:44.235 ThaliTest[1360:1846247] Multi-tasking -> Device: YES, App: YES
,2015-11-26 07:47:44.241 ThaliTest[1360:1846247] Unlimited access to network resources
,2015-11-26 07:47:44.247 ThaliTest[1360:1846247] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 07:47:48.472 ThaliTest[1360:1846247] Resetting plugins due to page load.
,2015-11-26 07:47:49.935 ThaliTest[1360:1846247] Finished load of: file:///var/mobile/Containers/Bundle/Application/2623B3B4-BAE9-4533-9A09-C9123D7FF928/ThaliTest.app/www/index.html
,2015-11-26 07:47:50.089 ThaliTest[1360:1846247] JXcore Cordova plugin initializing
,2015-11-26 07:47:50.090 ThaliTest[1360:1846453] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-IpadAir2-1_PT2617
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 62035
,2015-11-26 07:55:09.163 ThaliTest[1360:1846453] jxcore: startBroadcasting
,2015-11-26 07:55:09.169 ThaliTest[1360:1846453] server: starting Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26 07:55:09.169 ThaliTest[1360:1846453] multipeer session: start timer: 0x18f62d30
,2015-11-26 07:55:09.169 ThaliTest[1360:1846453] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2617
2015-11-26 07:55:09.169 ThaliTest[1360:1846453] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-26T06:55:09.170Z SendDataTCPServer.js: TCP/IP server is bound to port: 62035
,2015-11-26 07:55:09.796 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:09.798Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:09.799Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:09.799Z SendDataConnector.js: do connect now
2015-11-26 07:55:09.799 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:09.799 ThaliTest[1360:1846453] client session: connect
2015-11-26 07:55:09.799 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:10.176 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6002.+4nCyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:10.593 ThaliTest[1360:1846247] multipeer session: reset timer
2015-11-26 07:55:10.593 ThaliTest[1360:1846247] multipeer session: stop timer
2015-11-26 07:55:10.593 ThaliTest[1360:1846247] multipeer session: start timer: 0x18f62d30
2015-11-26 07:55:10.594 ThaliTest[1360:1846247] server session: connect
2015-11-26 07:55:10.594 ThaliTest[1360:1846247] server session: stateChange:0->1 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:10.596 ThaliTest[1360:1846247] server: accepting invitation Apple-Iphone6-1_PT8881
,2015-11-26 07:55:10.753 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:12.287 ThaliTest[1360:1847245] client session: connected
2015-11-26 07:55:12.287 ThaliTest[1360:1847245] client session: stateChange:1->2 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:12.290 ThaliTest[1360:1847235] client session: fireConnectCallback: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:12.290 ThaliTest[1360:1847235] jxcore: connect: success
2015-11-26T06:55:12.291Z SendDataConnector.js: CLIENT connected to 62038, error: null
,2015-11-26T06:55:12.291Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:12.293 ThaliTest[1360:1846247] client: relay established
2015-11-26 07:55:12.293 ThaliTest[1360:1846247] client: new accepted socket: 0x1a014d30
,2015-11-26T06:55:12.306Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:12.685Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-26T06:55:12.698Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-26T06:55:12.749Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-26 07:55:12.888 ThaliTest[1360:1847245] server session: connected
2015-11-26 07:55:12.888 ThaliTest[1360:1847245] server session: stateChange:1->2 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:12.902 ThaliTest[1360:1846247] server relay: connected (to port: 62035)
,2015-11-26T06:55:12.913Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:13.223Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-26T06:55:13.236Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-11-26T06:55:13.253Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:55:13.276 ThaliTest[1360:1847244] server session: not connected Apple-Iphone6-1_PT8881
,2015-11-26 07:55:13.485 ThaliTest[1360:1846247] multipeer session: reset timer
2015-11-26 07:55:13.485 ThaliTest[1360:1846247] multipeer session: stop timer
2015-11-26 07:55:13.486 ThaliTest[1360:1846247] multipeer session: start timer: 0x18f62d30
,2015-11-26 07:55:13.486 ThaliTest[1360:1846247] server session: connect
2015-11-26 07:55:13.486 ThaliTest[1360:1846247] server session: stateChange:0->1 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:13.488 ThaliTest[1360:1846247] server: accepting invitation Apple-Iphone5-1_PT6002
,2015-11-26 07:55:16.638 ThaliTest[1360:1847244] server session: connected
2015-11-26 07:55:16.638 ThaliTest[1360:1847244] server session: stateChange:1->2 Apple-Iphone5-1_PT6002
,2015-11-26 07:55:16.640 ThaliTest[1360:1846247] server relay: connected (to port: 62035)
,2015-11-26T06:55:16.645Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:17.248Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-26T06:55:17.260Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-11-26T06:55:17.272Z SendDataTCPServer.js: TCP/IP server has received 20832 bytes of data
,2015-11-26T06:55:17.285Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-11-26T06:55:17.299Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-11-26T06:55:17.585Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-11-26T06:55:17.598Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-11-26T06:55:17.609Z SendDataTCPServer.js: TCP/IP server has received 51584 bytes of data
,2015-11-26T06:55:17.621Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-26T06:55:17.635Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-26T06:55:17.697Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-11-26T06:55:17.710Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-11-26T06:55:17.722Z SendDataTCPServer.js: TCP/IP server has received 96224 bytes of data
,2015-11-26T06:55:17.734Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26 07:55:17.746 ThaliTest[1360:1847244] server session: not connected Apple-Iphone5-1_PT6002
,2015-11-26T06:55:22.758Z SendDataConnector.js: Receiving data timeout now
2015-11-26T06:55:22.758Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:22.759Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:22.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:22.760Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client: socket closed
2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client relay: socket disconnected
2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client relay: 0x1a014d30 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client session: socket closed: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-1,1-26 07:55:22.761 ThaliTest[1360:1846247] client session: onLinkFailure: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client session: disconnect
2015-11-26 07:55:22.761 ThaliTest[1360:1846247] client session: stateChange:2->0 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:22.763 ThaliTest[1360:1846247] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:27.771Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:27.771Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:32.778 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:55:32.778 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:55:32.778Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DC,bA==
2015-11-26T06:55:32.778Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT6114.M0DCbA== with availability status: true
2015-11-26T06:55:32.778Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:32.779Z SendDataConnector.js: do connect now
,2015-11-26 07:55:32.779 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:32.779 ThaliTest[1360:1846453] client session: connect
2015-11-26 07:55:32.779 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:35.359 ThaliTest[1360:1847324] client session: connected
2015-11-26 07:55:35.359 ThaliTest[1360:1847324] client session: stateChange:1->2 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:35.378 ThaliTest[1360:1847299] client session: fireConnectCallback: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:35.378 ThaliTest[1360:1847299] jxcore: connect: success
,2015-11-26T06:55:35.379Z SendDataConnector.js: CLIENT connected to 62044, error: null
2015-11-26T06:55:35.379Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:35.380 ThaliTest[1360:1846247] client: relay established
,2015-11-26 07:55:35.380 ThaliTest[1360:1846247] client: new accepted socket: 0x18f6ae60
,2015-11-26T06:55:35.393Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:55:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26T06:55:45.422Z SendDataConnector.js: Receiving data timeout now
2015-11-26T06:55:45.422Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:45.423Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:45.423Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:45.423Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client: socket closed
2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client relay: socket disconnected
2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client relay: 0x18f6ae60 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client session: socket closed: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-1,1-26 07:55:45.424 ThaliTest[1360:1846247] client session: onLinkFailure: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client session: disconnect
2015-11-26 07:55:45.424 ThaliTest[1360:1846247] client session: stateChange:2->0 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:45.427 ThaliTest[1360:1846247] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:50.430Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:50.431Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:55.442 ThaliTest[1360:1846453] jxcore: disconnect
,2015-11-26 07:55:55.442 ThaliTest[1360:1846453] jxcore: disconnect: fail
,2015-11-26T06:55:55.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:55.443Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT6114.M0DCbA== with availability status: true
2015-11-26T06:55:55.443Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:55.443Z SendDataConnector.js: do connect now
,2015-11-26 07:55:55.443 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:55.443 ThaliTest[1360:1846453] client session: connect
,2015-11-26 07:55:55.444 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client session: onLinkFailure: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client session: disconnect
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client session: stateChange:1->0 Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] client session: fireConnectCallback: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:55.447 ThaliTest[1360:1846247] jxcore: connect: fail: Peer disconnected
2015-11-26T06:55:55.448Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2015-11-26T06:55:55.448Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-26T06:55:55.448Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier",:"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":false}]
,2015-11-26T06:56:00.450Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:56:00.450Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:05.460 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:56:05.461 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:56:05.461Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:56:05.461Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT6114.M0DCbA== with availability status: true
2015-11-26T06:56:05.461Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==,
2015-11-26T06:56:05.461Z SendDataConnector.js: do connect now
2015-11-26 07:56:05.461 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:05.462 ThaliTest[1360:1846453] client: connect: unreachable Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:05.462 ThaliTest[1360:1846453], jxcore: connect: fail: Peer unreachable
,2015-11-26T06:56:05.462Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-26T06:56:05.462Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-26T06:56:05.463Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:56:10.470Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:56:10.470Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:56:13.497 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:56:13.497 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:13.498 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 07:56:15.471 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:56:15.471 ThaliTest[1360:1846453] jxcore: disconnect: fail
,2015-11-26T06:56:15.471Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:56:15.472Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT6114.M0DCbA== with availability status: true
2015-11-26T06:56:15.472Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:56:15.472Z SendDataConnector.js: do connect now
2015-11-26 07:56:15.472 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:15.472 ThaliTest[1360:1846453] client session: connect
,2015-11-26 07:56:15.472 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:56:43.499 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:56:43.500 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:56:43.500 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:48.363 ThaliTest[1360:1847475] client session: not connected Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:48.363 ThaliTest[1360:1847475] client session: onLinkFailure: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:48.363 ThaliTe,st[1360:1847475] client session: disconnect
2015-11-26 07:56:48.363 ThaliTest[1360:1847475] client session: stateChange:1->0 Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:48.363 ThaliTest[1360:1847475] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT6114.M0DCbA==
2015-11-26 07:56:48.363 ThaliTest[1360:1847475] jxcore: connect: fail: Peer disconnected
2015-11-26T06:56:48.364Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-26T06:56:48.364Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-26T06:56:48.367Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:56:48.367Z SendDataConnector.js: Stop data retrieving timer
,2015-11-26 07:56:48.367 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:56:48.368 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:56:48.368Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
---- round done--------
,device[2]: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:56:48.369Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:56:48.369Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:56:48.369Z SendDataConnector.js: do connect now
,2015-11-26 07:56:48.369 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:56:48.369 ThaliTest[1360:1846453] client session: connect
,2015-11-26 07:56:48.370 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:56:53.873 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:53.873 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone5s-1_PT6114.M0DCbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:56:57.264 ThaliTest[1360:1847474] client session: connected
2015-11-26 07:56:57.264 ThaliTest[1360:1847474] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:56:57.266 ThaliTest[1360:1847476] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:56:57.267 ThaliTest[1360:1847476] jxcore: connect: success
2015-11-26T06:56:57.267Z SendDataConnector.js: CLIENT connected to 62051, error: null
2015-11-26T06:56:57.267Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:56:57.268 ThaliTest[1360:1846247] client: relay established
,2015-11-26 07:56:57.268 ThaliTest[1360:1846247] client: new accepted socket: 0x16eac730
,2015-11-26T06:56:57.281Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:56:57.680Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-26T06:56:57.743Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-26T06:56:57.833Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-26T06:57:07.838Z SendDataConnector.js: Receiving data timeout now
2015-11-26T06:57:07.839Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:57:07.839Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-26T06:57:07.839Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:57:07.840Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:57:07.840 ThaliTest[1360:1846247] client: socket closed
2015-11-26 07:57:07.840 ThaliTest[1360:1846247] client relay: socket disconnected
,2015-11-26 07:57:07.841 ThaliTest[1360:1846247] client relay: 0x16eac730 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-26 07:57:07.841 ThaliTest[1360:1846247] client session: socket closed: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:07.841 ThaliTest[1360:1846247] client session: onLinkFailure: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:07.841 ThaliTest[1360:1846247] client session: disconnect
,2015-11-26 07:57:07.841 ThaliTest[1360:1846247] client session: stateChange:2->0 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:07.843 ThaliTest[1360:1846247] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:57:12.840Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:12.840Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:57:17.842 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:57:17.842 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:57:17.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCy,w==
2015-11-26T06:57:17.842Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:57:17.843Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:17.843Z SendDataConnector.js: do connect now
,2015-11-26 07:57:17.843 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:17.843 ThaliTest[1360:1846453] client session: connect
2015-11-26 07:57:17.843 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple,-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:17.847 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:17.847 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:17.847 ThaliTest[1360:1846247] client session: onLinkFailure: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:17.847 ThaliTest[1360:1846247] client session: disconnect
2015-11-26 07:57:17.847 ThaliTest[1360:1846247] client session: stateChange:1->0 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:17.899 ThaliTest[1360:1846247] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:17.899 ThaliTest[1360:1846247] jxcore: connect: fail: Peer disconnected
2015-11-26T06:57:17.899Z SendDataConnector.js: C,LIENT connected to 0, error: Peer disconnected
2015-11-26T06:57:17.899Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-26T06:57:17.899Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6002.+4nCyw==","peerName":"(null)","peerAvailable":false}]
,2015-11-26T06:57:22.907Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:57:22.907Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:27.912 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:57:27.912 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:57:27.913Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:27.913Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:57:27.913Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2,015-11-26T06:57:27.913Z SendDataConnector.js: do connect now
2015-11-26 07:57:27.913 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:27.913 ThaliTest[1360:1846453] client: connect: unreachable Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:27.913 ThaliTest[1360:1846453] jxcore: connect: fail: Peer unreachable
,2015-11-26T06:57:27.914Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-26T06:57:27.914Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-11-26T06:57:27.914Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:57:32.925Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:32.925Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:37.930 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:57:37.931 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:57:37.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:37.931Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:57:37.931Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2,015-11-26T06:57:37.931Z SendDataConnector.js: do connect now
2015-11-26 07:57:37.931 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:37.931 ThaliTest[1360:1846453] client: connect: unreachable Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:37.932 ThaliTest[1360:1846453] jxcore: connect: fail: Peer unreachable
,2015-11-26T06:57:37.932Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-26T06:57:37.932Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-11-26T06:57:37.932Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:57:42.940Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26T06:57:42.940Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:57:43.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:43.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6002.+4nCyw==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 07:57:47.943 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:57:47.943 ThaliTest[1360:1846453] jxcore: disconnect: fail
2015-11-26T06:57:47.943Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCy,w==
2015-11-26T06:57:47.943Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6002.+4nCyw== with availability status: true
2015-11-26T06:57:47.943Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26T06:57:47.943Z SendDataConnector.js: do connect now
2015-11-26 07:57:47.944 ThaliTest[1360:1846453] jxcore: connect Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:47.944 ThaliTest[1360:1846453] client session: connect
,2015-11-26 07:57:47.945 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:50.717 ThaliTest[1360:1847613] client session: connected
2015-11-26 07:57:50.717 ThaliTest[1360:1847613] client session: stateChange:1->2 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:57:50.723 ThaliTest[1360:1847612] client session: fireConnectCallback: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:57:50.723 ThaliTest[1360:1847612] jxcore: connect: success
2015-11-26T06:57:50.724Z SendDataConnector.js: CLIENT connected to 62056, error: null
2015-11-26T06:57:50.724Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:57:50.725 ThaliTest[1360:1846247] client: relay established
2015-11-26 07:57:50.725 ThaliTest[1360:1846247] client: new accepted socket: 0x16fc8950
,2015-11-26T06:57:50.738Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:57:59.026 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:57:59.026 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-11-26T06:58:00.763Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:58:00.763Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-26T06:58:00.763Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:58:00.764Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:58:00.764Z SendDataConnector.js: Stop data retrieving timer
,2015-11-26T06:58:00.765Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:58:00.765 ThaliTest[1360:1846453] jxcore: disconnect
2015-11-26 07:58:00.765 ThaliTest[1360:1846453] client session: disconnectFromPeer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:58:00.765 ThaliTest[1360:1846453] client session: disconnect
2015-11-26 07:58:00.765 ThaliTest[1360:1846453] client session: stateChange:2->0 Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 07:58:00.768 ThaliTest[1360:1846453] jxcore: disconnect: success
2015-11-26T06:58:00.768Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6002.+4nCyw==
---- round done--------
2015-11-26T06:58:00.768Z SendDataCo,nnector.js: ----------------- closeClientSocket
,2015-11-26 07:58:03.818 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[3]: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:58:03.819Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:58:03.819Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:58:03.819Z SendDataConnector.js: do connect now
2015-11-26 07:58:03.819 ThaliTest[13,60:1846453] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:58:03.820 ThaliTest[1360:1846453] client session: connect
2015-11-26 07:58:03.820 ThaliTest[1360:1846453] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:07.955 ThaliTest[1360:1847613] client session: connected
2015-11-26 07:58:07.955 ThaliTest[1360:1847613] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:07.963 ThaliTest[1360:1847657] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:58:07.963 ThaliTest[1360:1847657] jxcore: connect: success
2015-11-26T06:58:07.963Z SendDataConnector.js: CLIENT connected to 62060, error: null
2015-11-26T06:58:07.963Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:58:07.964 ThaliTest[1360:1846247] client: relay established
2015-11-26 07:58:07.965 ThaliTest[1360:1846247] client: new accepted socket: 0x18f68970
,2015-11-26T06:58:07.977Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:58:08.422Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-26T06:58:08.448Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-26T06:58:08.460Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-26T06:58:08.472Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-26T06:58:08.472Z SendDataConnector.js: got all data for this round
,2015-11-26T06:58:08.473Z SendDataConnector.js: CLIENT Stop now
,2015-11-26T06:58:08.473Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:58:08.475 ThaliTest[1360:1846453] jxcore: disconnect
,2015-11-26 07:58:08.475 ThaliTest[1360:1846453] client session: disconnectFromPeer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:08.476 ThaliTest[1360:1846453] client session: disconnect
,2015-11-26 07:58:08.476 ThaliTest[1360:1846453] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:08.543 ThaliTest[1360:1846453] jxcore: disconnect: success
,2015-11-26T06:58:08.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2617","time":179388,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT6114.M0DCbA==","time":98566,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":,"Apple-Iphone5-1_PT6002.+4nCyw==","time":72394,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone6-1_PT8881.4jE3Ag==","time":4653,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 4653 ms, 99% : 4653 ms, 95 : 4653 ms, 90% : 4653 ms.
,Result count 1, range 4653 ms to  4653 ms.
,sendList failed peers count : 2 [66.66666666666667 %]
,- Peer ID : Apple-Iphone5s-1_PT6114.M0DCbA==, Tried : 5
,- Peer ID : Apple-Iphone5-1_PT6002.+4nCyw==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-26T06:58:08.551Z SendDataConnector.js: CLIENT Stop now
,2015-11-26T06:58:08.551Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:58:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:58:13.497 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:58:13.498 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:39.812 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:58:39.812 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:58:39.856 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 07:58:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:59:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:59:13.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:59:13.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:59:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 07:59:43.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:59:43.811 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:00:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:00:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:00:43.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:00:43.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:01:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:01:13.920 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:01:14.019 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:01:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:01:43.929 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:01:44.965 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:02:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:02:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:02:13.798 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:02:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:02:44.077 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:02:45.168 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:03:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:03:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:03:13.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:03:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:03:43.882 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:03:44.543 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:04:10.141 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:04:10.142 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:04:10.748 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:04:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:04:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:04:13.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:04:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:05:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:05:13.493 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:05:13.669 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:05:37.711 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:05:37.711 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:05:39.809 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:05:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:05:43.497 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:05:43.498 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:06:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:06:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:06:13.796 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:06:37.852 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:06:37.852 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:06:37.920 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:06:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:06:43.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 08:06:43.497 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:07:10.072 ThaliTest[1360:1846247] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:07:10.073 ThaliTest[1360:1846247] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:07:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:07:13.494 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:07:14.140 ThaliTest[1360:1846247] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:07:43.486 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:07:44.625 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:08:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:08:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:08:43.493 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:09:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:09:13.494 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:09:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:10:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:10:13.493 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:10:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:10:43.494 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:11:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:11:13.494 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:11:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:11:43.494 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:12:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:12:13.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:12:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:12:43.823 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:13:13.486 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:13:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:13:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:13:43.496 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:14:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:14:13.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:14:43.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:14:43.495 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==
,2015-11-26 08:15:13.487 ThaliTest[1360:1846247] multipeer session: restart
,2015-11-26 08:15:13.493 ThaliTest[1360:1846247] client: found peer: Apple-Iphone5-1_PT6002.+4nCyw==

```
