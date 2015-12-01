#### Test 52320939cae1769_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/AFB11B89-2F2A-4D18-BD7F-16B472938BF0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AFB11B89-2F2A-4D18-BD7F-16B472938BF0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52320939cae1769/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8224ABEB-7FDF-4AD1-820D-5CEF8ED21050/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58789"
,(lldb)     command script import "/tmp/AFB11B89-2F2A-4D18-BD7F-16B472938BF0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 23:00:42.624 ThaliTest[1724:2714553] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B74F7B6E-2C0A-4EEA-AA4D-B711035C5143/Library/Cookies/Cookies.binarycookies
,2015-12-01 23:00:42.913 ThaliTest[1724:2714553] Apache Cordova native platform version 3.9.2 is starting.
2015-12-01 23:00:42.914 ThaliTest[1724:2714553] Multi-tasking -> Device: YES, App: YES
,2015-12-01 23:00:42.920 ThaliTest[1724:2714553] Unlimited access to network resources
,2015-12-01 23:00:42.925 ThaliTest[1724:2714553] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 23:00:47.102 ThaliTest[1724:2714553] Resetting plugins due to page load.
,2015-12-01 23:00:48.403 ThaliTest[1724:2714553] Finished load of: file:///var/mobile/Containers/Bundle/Application/8224ABEB-7FDF-4AD1-820D-5CEF8ED21050/ThaliTest.app/www/index.html
,2015-12-01 23:00:48.541 ThaliTest[1724:2714553] JXcore Cordova plugin initializing
2015-12-01 23:00:48.541 ThaliTest[1724:2714764] JXcore instance initializing
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
Radios toggled
,my name is : Apple-IpadAir2-1_PT2654
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 64240
,2015-12-01 23:08:20.252 ThaliTest[1724:2714764] jxcore: startBroadcasting
,2015-12-01 23:08:20.259 ThaliTest[1724:2714764] server: starting Apple-IpadAir2-1_PT2654.X9QXJA==
,2015-12-01 23:08:20.260 ThaliTest[1724:2714764] multipeer session: start timer: 0x1988ff90
2015-12-01 23:08:20.260 ThaliTest[1724:2714764] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2654
2015-12-01 23:08:20.260 ThaliTest[1724:2714764] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-01T22:08:20.261Z SendDataTCPServer.js: TCP/IP server is bound to port: 64240
,2015-12-01 23:08:21.340 ThaliTest[1724:2714553] client: found peer: Apple-Iphone5-1_PT2043.ooMPSg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2043.ooMPSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01T22:08:21.343Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01T22:08:21.343Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2043.ooMPSg==
20,15-12-01T22:08:21.343Z SendDataConnector.js: do connect now
2015-12-01 23:08:21.343 ThaliTest[1724:2714764] jxcore: connect Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:21.344 ThaliTest[1724:2714764] client session: connect
2015-12-01 23:08:21.344 ThaliTest[1724:2714764] client session: stateChange:0->1 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:22.416 ThaliTest[1724:2714553] client: found peer: Apple-Iphone6-1_PT8318.eAU97Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8318.eAU97Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 23:08:24.070 ThaliTest[1724:2715591] client session: connected
2015-12-01 23:08:24.071 ThaliTest[1724:2715591] client session: stateChange:1->2 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:24.073 ThaliTest[1724:2715591] client session: fireConnectCallback: Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:24.074 ThaliTest[1724:2715591] jxcore: connect: success
,2015-12-01T22:08:24.075Z SendDataConnector.js: CLIENT connected to 64243, error: null
2015-12-01T22:08:24.075Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:24.076 ThaliTest[1724:2714553] client: relay established
2015-12-01 23:08:24.076 ThaliTest[1724:2714553] client: new accepted socket: 0x1989d740
,2015-12-01T22:08:24.090Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T22:08:24.452Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T22:08:24.477Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T22:08:24.477Z SendDataConnector.js: got all data for this round
,2015-12-01T22:08:24.478Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T22:08:24.478Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 23:08:24.480 ThaliTest[1724:2714764] jxcore: disconnect
2015-12-01 23:08:24.480 ThaliTest[1724:2714764] client session: disconnectFromPeer: Apple-Iphone5-1_PT2043.ooMPSg==
2015-12-01 23:08:24.480 ThaliTest[1724:2714764] client session: disconnect
2015-12-01 23:08:24.480 ThaliTest[1724:2714764] client session: stateChange:2->0 Apple-Iphone5-1_PT2043.ooMPSg==
,2015-12-01 23:08:24.485 ThaliTest[1724:2714764] jxcore: disconnect: success
2015-12-01T22:08:24.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2043.ooMPSg==
---- round done--------
,device[2]: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:24.487Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:24.488Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01T22:08:24.488Z SendDataConnector.js: do connect now
,2015-12-01 23:08:24.488 ThaliTest[1724:2714764] jxcore: connect Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:24.488 ThaliTest[1724:2714764] client session: connect
2015-12-01 23:08:24.489 ThaliTest[1724:2714764] client session: stateChange:0->1 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:25.553 ThaliTest[1724:2714553] client: found peer: Apple-Iphone5s-1_PT9471.ZBmsZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9471.ZBmsZA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-01 23:08:25.616 ThaliTest[1724:2714553] multipeer session: reset timer
2015-12-01 23:08:25.616 ThaliTest[1724:2714553] multipeer session: stop timer
2015-12-01 23:08:25.616 ThaliTest[1724:2714553] multipeer session: start timer: 0x1988ff90
2015-12-01 23:08:25.616 ThaliTest[1724:2714553] server session: connect
2015-12-01 23:08:25.616 ThaliTest[1724:2714553] server session: stateChange:0->1 Apple-Iphone5-1_PT2043
,2015-12-01 23:08:25.619 ThaliTest[1724:2714553] server: accepting invitation Apple-Iphone5-1_PT2043
,2015-12-01 23:08:26.135 ThaliTest[1724:2714553] multipeer session: reset timer
2015-12-01 23:08:26.135 ThaliTest[1724:2714553] multipeer session: stop timer
2015-12-01 23:08:26.135 ThaliTest[1724:2714553] multipeer session: start timer: 0x1988ff90
2015-12-01 23:08:26.135 ThaliTest[1724:2714553] server session: connect
2015-12-01 23:08:26.135 ThaliTest[1724:2714553] server session: stateChange:0->1 Apple-Iphone6-1_PT8318
,2015-12-01 23:08:26.137 ThaliTest[1724:2714553] server: accepting invitation Apple-Iphone6-1_PT8318
,2015-12-01 23:08:27.192 ThaliTest[1724:2715596] client session: connected
2015-12-01 23:08:27.192 ThaliTest[1724:2715596] client session: stateChange:1->2 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:27.199 ThaliTest[1724:2715597] client session: fireConnectCallback: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:27.199 ThaliTest[1724:2715597] jxcore: connect: success
2015-12-01T22:08:27.200Z SendDataConnector.js: CLIENT connected ,to 64247, error: null
2015-12-01T22:08:27.200Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 23:08:27.201 ThaliTest[1724:2714553] client: relay established
2015-12-01 23:08:27.201 ThaliTest[1724:2714553] client: new accepted socket: 0x18555930
,2015-12-01T22:08:27.215Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T22:08:27.609Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T22:08:27.623Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T22:08:27.636Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T22:08:27.649Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-01T22:08:27.674Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-01 23:08:28.688 ThaliTest[1724:2715591] server session: connected
2015-12-01 23:08:28.688 ThaliTest[1724:2715591] server session: stateChange:1->2 Apple-Iphone6-1_PT8318
,2015-12-01 23:08:28.692 ThaliTest[1724:2714553] server relay: connected (to port: 64240)
,2015-12-01 23:08:28.692 ThaliTest[1724:2715591] server session: connected
2015-12-01 23:08:28.693 ThaliTest[1724:2715591] server session: stateChange:1->2 Apple-Iphone5-1_PT2043
,2015-12-01T22:08:28.697Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 23:08:28.698 ThaliTest[1724:2714553] server relay: connected (to port: 64240)
,2015-12-01T22:08:28.711Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T22:08:29.154Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-01T22:08:29.167Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T22:08:29.191Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-01T22:08:29.203Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-12-01T22:08:29.217Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-12-01T22:08:29.228Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-12-01T22:08:29.242Z SendDataTCPServer.js: TCP/IP server has received 66464 bytes of data
,2015-12-01T22:08:29.256Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-12-01T22:08:29.268Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T22:08:37.684Z SendDataConnector.js: Receiving data timeout now
,2015-12-01T22:08:37.685Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T22:08:37.685Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01T22:08:37.685Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-01T22:08:37.686Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-01 23:08:37.687 ThaliTest[1724:2714553] client: socket closed
2015-12-01 23:08:37.687 ThaliTest[1724:2714553] client relay: socket disconnected
2015-12-01 23:08:37.687 ThaliTest[1724:2714553] client relay: 0x18555930 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-01 23:08:37.687 ThaliTest[1724:2714553] client session: socket closed: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12,-01 23:08:37.687 ThaliTest[1724:2714553] client session: onLinkFailure: Apple-Iphone6-1_PT8318.eAU97Q==
2015-12-01 23:08:37.687 ThaliTest[1724:2714553] client session: disconnect
2015-12-01 23:08:37.688 ThaliTest[1724:2714553] client session: stateChange:2->0 Apple-Iphone6-1_PT8318.eAU97Q==
,2015-12-01 23:08:37.690 ThaliTest[1724:2714553] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8318.eAU97Q==

```
