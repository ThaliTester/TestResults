#### Test 51986340bb0815b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68E9B4C6-6909-4DB0-8C3D-83A7EA82403A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/68E9B4C6-6909-4DB0-8C3D-83A7EA82403A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340bb0815b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/B716E8F2-52E3-4410-AB15-F763580F0076/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56951"
,(lldb)     command script import "/tmp/68E9B4C6-6909-4DB0-8C3D-83A7EA82403A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 13:10:33.794 ThaliTest[905:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 13:10:33.797 ThaliTest[905:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-27 13:10:33.804 ThaliTest[905:60b] Unlimited access to network resources
,2015-11-27 13:10:33.814 ThaliTest[905:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 13:10:44.710 ThaliTest[905:60b] Resetting plugins due to page load.
,2015-11-27 13:10:45.583 ThaliTest[905:60b] Finished load of: file:///var/mobile/Applications/B716E8F2-52E3-4410-AB15-F763580F0076/ThaliTest.app/www/index.html
,2015-11-27 13:10:45.761 ThaliTest[905:60b] JXcore Cordova plugin initializing
,2015-11-27 13:10:45.763 ThaliTest[905:6907] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5-1_PT1479
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51188
,2015-11-27 13:16:21.641 ThaliTest[905:6907] jxcore: startBroadcasting
,2015-11-27 13:16:21.652 ThaliTest[905:6907] server: starting Apple-Iphone5-1_PT1479.RH8WAQ==
,2015-11-27 13:16:21.656 ThaliTest[905:6907] multipeer session: start timer: 0x15d91d80
2015-11-27 13:16:21.657 ThaliTest[905:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1479
2015-11-27 13:16:21.659 ThaliTest[905:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-27T12:16:21.662Z SendDataTCPServer.js: TCP/IP server is bound to port: 51188
,2015-11-27 13:16:21.854 ThaliTest[905:60b] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6911.ZjHo2g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:21.858Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:21.859Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:21.859Z SendDataConnector.js: do connect now
,2015-11-27 13:16:21.860 ThaliTest[905:6907] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:21.861 ThaliTest[905:6907] client session: connect
,2015-11-27 13:16:21.861 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:22.189 ThaliTest[905:60b] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-27 13:16:22.653 ThaliTest[905:60b] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3767.CF0kqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-27 13:16:24.259 ThaliTest[905:780b] client session: connected
,2015-11-27 13:16:24.260 ThaliTest[905:780b] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:24.265 ThaliTest[905:7b07] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:24.266 ThaliTest[905:7b07] jxcore: connect: success
,2015-11-27T12:16:24.268Z SendDataConnector.js: CLIENT connected to 51191, error: null
2015-11-27T12:16:24.268Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:24.270 ThaliTest[905:60b] client: relay established
2015-11-27 13:16:24.270 ThaliTest[905:60b] client: new accepted socket: 0x1b756a80
,2015-11-27T12:16:24.283Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:16:24.816Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-27T12:16:24.828Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-27T12:16:24.841Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-27T12:16:24.854Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-27T12:16:24.867Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-27T12:16:24.879Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-27 13:16:25.949 ThaliTest[905:60b] multipeer session: reset timer
2015-11-27 13:16:25.951 ThaliTest[905:60b] multipeer session: stop timer
,2015-11-27 13:16:25.951 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:16:25.952 ThaliTest[905:60b] server session: connect
,2015-11-27 13:16:25.953 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:25.957 ThaliTest[905:60b] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:26.020 ThaliTest[905:60b] multipeer session: reset timer
,2015-11-27 13:16:26.021 ThaliTest[905:60b] multipeer session: stop timer
,2015-11-27 13:16:26.022 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:16:26.023 ThaliTest[905:60b] server session: connect
,2015-11-27 13:16:26.024 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:26.027 ThaliTest[905:60b] server: accepting invitation Apple-Iphone6-1_PT6911
,2015-11-27 13:16:28.128 ThaliTest[905:780b] server session: connected
2015-11-27 13:16:28.130 ThaliTest[905:780b] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:28.134 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:16:28.141Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:28.444Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-11-27 13:16:28.454 ThaliTest[905:780b] server session: connected
2015-11-27T12:16:28.458Z SendDataTCPServer.js: TCP/IP server has received 39278 bytes of data
2015-11-27 13:16:28.456 ThaliTest[905:780b] server session: stateChange:1->2 Apple-Iphone6-1_PT6911
,2015-11-27 13:16:28.465 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:16:28.473Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
2015-11-27T12:16:28.476Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:28.488Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-11-27T12:16:28.501Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27T12:16:29.084Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-27T12:16:29.108Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-11-27T12:16:29.144Z SendDataTCPServer.js: TCP/IP server has received 63996 bytes of data
,2015-11-27T12:16:29.159Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:16:29.683 ThaliTest[905:60b] multipeer session: reset timer
2015-11-27 13:16:29.685 ThaliTest[905:60b] multipeer session: stop timer
,2015-11-27 13:16:29.686 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:16:29.686 ThaliTest[905:60b] server session: connect
,2015-11-27 13:16:29.687 ThaliTest[905:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:29.690 ThaliTest[905:60b] server: accepting invitation Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:32.219 ThaliTest[905:8603] server session: connected
2015-11-27 13:16:32.221 ThaliTest[905:8603] server session: stateChange:1->2 Apple-IpadAir2-1_PT3767
,2015-11-27 13:16:32.224 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:16:32.226Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:32.615Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-11-27T12:16:32.628Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-11-27T12:16:32.641Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-11-27T12:16:32.766Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-27 13:16:33.175 ThaliTest[905:7b07] server session: not connected Apple-IpadAir2-1_PT3767
,2015-11-27T12:16:34.881Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:16:34.881Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:34.884Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:34.884Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:16:34.885Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:16:34.886 ThaliTest[905:60b] client: socket closed
,2015-11-27 13:16:34.887 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:16:34.888 ThaliTest[905:60b] client relay: 0x1b756a80 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6b8db0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:16:34.889 ThaliTest[905:60b] client session: socket closed: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:34.889 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:34.890 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:16:34.890 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:34.892 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:38.527 ThaliTest[905:8603] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:39.695 ThaliTest[905:7b07] server session: not connected Apple-Iphone6-1_PT6911
,2015-11-27T12:16:39.890Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:16:39.891Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:44.896 ThaliTest[905:6907] jxcore: disconnect
2015-11-27 13:16:44.898 ThaliTest[905:6907] jxcore: disconnect: fail
,2015-11-27T12:16:44.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:44.900Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT6911.ZjHo2g== with availability status: ,true
2015-11-27T12:16:44.900Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:16:44.900Z SendDataConnector.js: do connect now
,2015-11-27 13:16:44.901 ThaliTest[905:6907] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:44.901 ThaliTest[905:6907] client session: connect
,2015-11-27 13:16:44.902 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:47.820 ThaliTest[905:8603] client session: connected
2015-11-27 13:16:47.822 ThaliTest[905:8603] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:47.825 ThaliTest[905:7b07] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:47.826 ThaliTest[905:7b07] jxcore: connect: success
,2015-11-27T12:16:47.827Z SendDataConnector.js: CLIENT connected to 51197, error: null
,2015-11-27T12:16:47.828Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:16:47.829 ThaliTest[905:60b] client: relay established
2015-11-27 13:16:47.830 ThaliTest[905:60b] client: new accepted socket: 0x1b6bcb40
,2015-11-27T12:16:47.841Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:16:48.851 ThaliTest[905:60b] multipeer session: reset timer
2015-11-27 13:16:48.852 ThaliTest[905:60b] multipeer session: stop timer
,2015-11-27 13:16:48.853 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:16:48.854 ThaliTest[905:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8509)
2015-11-27 13:16:48.855 ThaliTest[905:60b] server session: disconnect
,2015-11-27 13:16:48.855 ThaliTest[905:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27T12:16:48.859Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27 13:16:48.858 ThaliTest[905:60b] server session: connect
,2015-11-27 13:16:48.859 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:48.863 ThaliTest[905:60b] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:51.117 ThaliTest[905:780b] server session: connected
2015-11-27 13:16:51.119 ThaliTest[905:780b] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:16:51.123 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:16:51.125Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:16:51.347Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27T12:16:57.900Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:16:57.900Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:57.901Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:16:57.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:16:57.903Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:16:57.904 ThaliTest[905:60b] client: socket closed
2015-11-27 13:16:57.905 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:16:57.906 ThaliTest[905:60b] client relay: 0x1b6bcb40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6ba590 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:16:57.907 ThaliTest[905:60b] client session: socket closed: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:57.908 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:16:57.908 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:16:57.909 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:16:57.911 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:01.445 ThaliTest[905:8603] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27T12:17:02.910Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:02.911Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:07.912 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:17:07.913 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:17:07.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:17:07.916Z SendDataConnector.js: Connect (retry count, 2) to peer Apple-Iphone6-1_PT6911.ZjHo2g== with availability status: true
2015-11-27T12:17:07.916Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:17:07.916Z SendDataConnector.js: do connect now
,2015-11-27 13:17:07.917 ThaliTest[905:6907] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:07.918 ThaliTest[905:6907] client session: connect
,2015-11-27 13:17:07.918 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:11.442 ThaliTest[905:8603] client session: connected
2015-11-27 13:17:11.444 ThaliTest[905:8603] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:11.446 ThaliTest[905:60b] multipeer session: reset timer
2015-11-27 13:17:11.448 ThaliTest[905:60b] multipeer session: stop timer
2015-11-27 13:17:11.448 ThaliTest[905:8603] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:11.449 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:17:11.449 ThaliTest[905:8603] jxcore: connect: success
2015-11-27 13:17:11.450 ThaliTest[905:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8509)
2015-11-27T12:17:11.453Z SendDataConnector.js: CLIENT connected to 51203, e,rror: null
2015-11-27 13:17:11.453 ThaliTest[905:60b] server session: disconnect
2015-11-27T12:17:11.453Z SendDataConnector.js: CLIENT starting client 
2015-11-27 13:17:11.453 ThaliTest[905:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:11.458 ThaliTest[905:60b] server session: connect
2015-11-27 13:17:11.459 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:11.463 ThaliTest[905:60b] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:11.464 ThaliTest[905:60b] client: relay established
2015-11-27 13:17:11.465 ThaliTest[905:60b] client: new accepted socket: 0x1b6a9f70
,2015-11-27T12:17:11.467Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27T12:17:11.467Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:13.620 ThaliTest[905:8603] server session: connected
2015-11-27 13:17:13.622 ThaliTest[905:8603] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:13.626 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:17:13.635Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:13.727Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27T12:17:21.526Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:21.527Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:17:21.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:21.528Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:21.529Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:21.530 ThaliTest[905:60b] client: socket closed
2015-11-27 13:17:21.531 ThaliTest[905:60b] client relay: socket disconnected
2015-11-27 13:17:21.532 ThaliTest[905:60b] client relay: 0x1b6a9f70 disconnected with error Error Domain=GCDAsyn,cSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6b61b0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:17:21.532 ThaliTest[905:60b] client session: socket closed: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:17:21.533 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:21.533 ThaliTest[905:60b] client session: disconnect
2015-11-27 13:17:21.534 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:21.535 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:24.038 ThaliTest[905:23b] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27T12:17:26.531Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:26.532Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:31.543 ThaliTest[905:6907] jxcore: disconnect
2015-11-27 13:17:31.545 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:17:31.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:31.547Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT6911.ZjHo2g== with availability status: true
2015-11-27T12:17:31.547Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-1,1-27T12:17:31.547Z SendDataConnector.js: do connect now
,2015-11-27 13:17:31.547 ThaliTest[905:6907] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:17:31.548 ThaliTest[905:6907] client session: connect
,2015-11-27 13:17:31.548 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:33.955 ThaliTest[905:60b] multipeer session: reset timer
2015-11-27 13:17:33.957 ThaliTest[905:60b] multipeer session: stop timer
,2015-11-27 13:17:33.957 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
,2015-11-27 13:17:33.958 ThaliTest[905:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8509)
,2015-11-27 13:17:33.959 ThaliTest[905:60b] server session: disconnect
2015-11-27 13:17:33.959 ThaliTest[905:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:33.962 ThaliTest[905:60b] server session: connect
2015-11-27 13:17:33.963 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:33.967 ThaliTest[905:60b] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27T12:17:33.972Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:17:34.096 ThaliTest[905:23b] client session: connected
2015-11-27 13:17:34.098 ThaliTest[905:23b] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:34.101 ThaliTest[905:23b] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:34.102 ThaliTest[905:23b] jxcore: connect: success
,2015-11-27T12:17:34.103Z SendDataConnector.js: CLIENT connected to 51208, error: null
,2015-11-27T12:17:34.103Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:34.105 ThaliTest[905:60b] client: relay established
2015-11-27 13:17:34.106 ThaliTest[905:60b] client: new accepted socket: 0x1b6934a0
,2015-11-27T12:17:34.117Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:36.139 ThaliTest[905:780b] server session: connected
2015-11-27 13:17:36.140 ThaliTest[905:780b] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:36.144 ThaliTest[905:60b] server relay: connected (to port: 51188)
,2015-11-27T12:17:36.155Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:36.234Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27T12:17:44.182Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:17:44.182Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:44.183Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:17:44.184Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:17:44.185Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:17:44.186 ThaliTest[905:60b] client: socket closed
2015-11-27 13:17:44.187 ThaliTest[905:60b] client relay: socket disconnected
2015-11-27 13:17:44.187 ThaliTest[905:60b] client relay: 0x1b6934a0 disconnected with error Error Domain=GCDAsyn,cSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b6c5b90 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:17:44.188 ThaliTest[905:60b] client session: socket closed: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:17:44.189 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27 13:17:44.189 ThaliTest[905:60b], client session: disconnect
2015-11-27 13:17:44.190 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:44.191 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:46.513 ThaliTest[905:8603] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27T12:17:49.188Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:49.189Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:54.198 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:17:54.200 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:17:54.201Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
2015-11-27T12:17:54.202Z SendDataConnector.js: Connect (retry count, 4) to peer Apple-Iphone6-1_PT6911.ZjHo2g== with availability status: true
2015-11-27T12:17:54.202Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:17:54.202Z SendDataConnector.js: do connect now
,2015-11-27 13:17:54.203 ThaliTest[905:6907] jxcore: connect Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:54.204 ThaliTest[905:6907] client session: connect
,2015-11-27 13:17:54.204 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:56.644 ThaliTest[905:60b] multipeer session: reset timer
,2015-11-27 13:17:56.646 ThaliTest[905:60b] multipeer session: stop timer
2015-11-27 13:17:56.647 ThaliTest[905:60b] multipeer session: start timer: 0x15d91d80
2015-11-27 13:17:56.648 ThaliTest[905:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8509)
,2015-11-27 13:17:56.649 ThaliTest[905:60b] server session: disconnect
,2015-11-27 13:17:56.650 ThaliTest[905:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:56.652 ThaliTest[905:60b] server session: connect
,2015-11-27 13:17:56.654 ThaliTest[905:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT8509
,2015-11-27T12:17:56.656Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27 13:17:56.658 ThaliTest[905:60b] server: accepting invitation Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:56.796 ThaliTest[905:780b] client session: connected
2015-11-27 13:17:56.798 ThaliTest[905:780b] client session: stateChange:1->2 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:56.800 ThaliTest[905:780b] client session: fireConnectCallback: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:17:56.801 ThaliTest[905:780b] jxcore: connect: success
,2015-11-27T12:17:56.802Z SendDataConnector.js: CLIENT connected to 51213, error: null
2015-11-27T12:17:56.803Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:17:56.804 ThaliTest[905:60b] client: relay established
2015-11-27 13:17:56.805 ThaliTest[905:60b] client: new accepted socket: 0x1b781020
,2015-11-27T12:17:56.818Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:17:59.107 ThaliTest[905:780b] server session: connected
,2015-11-27 13:17:59.109 ThaliTest[905:780b] server session: stateChange:1->2 Apple-Iphone5s-1_PT8509
,2015-11-27 13:17:59.112 ThaliTest[905:60b] server relay: connected (to port: 51188)
2015-11-27T12:17:59.114Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-27T12:17:59.227Z SendDataTCPServer.js: TCP/IP server has received 6286 bytes of data
,2015-11-27T12:17:59.239Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-27 13:18:02.811 ThaliTest[905:60b] client: lost peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:02.813 ThaliTest[905:60b] client session: onPeerLost: Apple-Iphone5s-1_PT8509.17j4Hw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-27 13:18:03.940 ThaliTest[905:60b] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8509.17j4Hw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-27T12:18:06.881Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:18:06.882Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:06.883Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:06.886Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:18:06.886Z SendDataConnector.js: Stop data retrieving timer
2015-11-27T12:18:06.886Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:18:06.887 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:18:06.888 ThaliTest[905:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:18:06.889 ThaliTest[905:6907] client session: disconnect
,2015-11-27 13:18:06.890 ThaliTest[905:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27 13:18:06.892 ThaliTest[905:6907] jxcore: disconnect: success
,2015-11-27T12:18:06.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6911.ZjHo2g==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:06.898Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:18:06.898Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:06.898Z SendDataConnector.js: do connect now
,2015-11-27 13:18:06.898 ThaliTest[905:6907] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:06.901 ThaliTest[905:6907] client session: connect
,2015-11-27 13:18:06.902 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:06.906Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:18:09.224 ThaliTest[905:23f] server session: not connected Apple-Iphone5s-1_PT8509
,2015-11-27 13:18:09.813 ThaliTest[905:23f] client session: connected
2015-11-27 13:18:09.815 ThaliTest[905:23f] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:09.819 ThaliTest[905:23f] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:09.819 ThaliTest[905:23f] jxcore: connect: success
,2015-11-27T12:18:09.820Z SendDataConnector.js: CLIENT connected to 51218, error: null
2015-11-27T12:18:09.820Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:18:09.822 ThaliTest[905:60b] client: relay established
,2015-11-27 13:18:09.823 ThaliTest[905:60b] client: new accepted socket: 0x1b782c20
,2015-11-27T12:18:09.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27T12:18:10.656Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-27T12:18:10.669Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-27T12:18:10.682Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-27T12:18:10.707Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-27T12:18:10.720Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-27T12:18:10.755Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-27T12:18:10.767Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-27T12:18:10.814Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-27T12:18:20.817Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:18:20.817Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:18:20.818Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:20.818Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-27T12:18:20.819Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:18:20.820 ThaliTest[905:60b] client: socket closed
2015-11-27 13:18:20.821 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:18:20.822 ThaliTest[905:60b] client relay: 0x1b782c20 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b3525f0 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:18:20.822 ThaliTest[905:60b] client session: socket closed: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:20.823 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:20.823 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:18:20.824 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:20.826 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:25.822Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:25.823Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:26.649 ThaliTest[905:60b] multipeer session: restart
,2015-11-27 13:18:30.832 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:18:30.833 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:18:30.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:18:30.835Z SendDataConnector.js: Connect (retry coun,t 1) to peer Apple-Iphone5s-1_PT8509.17j4Hw== with availability status: true
2015-11-27T12:18:30.835Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:30.836Z SendDataConnector.js: do connect now
2015-11-27 13:18:30.836 ThaliTest[905:6907] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:30.837 ThaliTest[905:6907] client session: connect
,2015-11-27 13:18:30.837 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:33.330 ThaliTest[905:780b] client session: connected
,2015-11-27 13:18:33.332 ThaliTest[905:780b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:33.335 ThaliTest[905:780b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:33.336 ThaliTest[905:780b] jxcore: connect: success
,2015-11-27T12:18:33.337Z SendDataConnector.js: CLIENT connected to 51224, error: null
2015-11-27T12:18:33.337Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:18:33.338 ThaliTest[905:60b] client: relay established
2015-11-27 13:18:33.339 ThaliTest[905:60b] client: new accepted socket: 0x1b752a30
,2015-11-27T12:18:33.350Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27T12:18:43.422Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:18:43.423Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:18:43.423Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:18:43.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-27T12:18:43.424Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:18:43.426 ThaliTest[905:60b] client: socket closed
2015-11-27 13:18:43.427 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:18:43.427 ThaliTest[905:60b] client relay: 0x1b752a30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b764420 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:18:43.428 ThaliTest[905:60b] client session: socket closed: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:43.429 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:43.429 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:18:43.430 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:43.432 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:48.426Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:18:48.426Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:53.434 ThaliTest[905:6907] jxcore: disconnect
2015-11-27 13:18:53.435 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:18:53.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:18:53.437Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT8509.17j4Hw== with availability status: true
,2015-11-27T12:18:53.437Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:18:53.438Z SendDataConnector.js: do connect now
2015-11-27 13:18:53.438 ThaliTest[905:6907] jxcore: connect Apple-Iphone5s-1_PT8509.1,7j4Hw==
,2015-11-27 13:18:53.439 ThaliTest[905:6907] client session: connect
,2015-11-27 13:18:53.440 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:56.241 ThaliTest[905:780b] client session: connected
2015-11-27 13:18:56.243 ThaliTest[905:780b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:56.246 ThaliTest[905:780b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:18:56.247 ThaliTest[905:780b] jxcore: connect: success
,2015-11-27T12:18:56.248Z SendDataConnector.js: CLIENT connected to 51228, error: null
2015-11-27T12:18:56.248Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:18:56.250 ThaliTest[905:60b] client: relay established
,2015-11-27 13:18:56.252 ThaliTest[905:60b] client: new accepted socket: 0x1b752a30
,2015-11-27T12:18:56.262Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:18:56.649 ThaliTest[905:60b] multipeer session: restart
,2015-11-27 13:18:56.659 ThaliTest[905:60b] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:18:56.660 ThaliTest[905:60b] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:18:56.661 ThaliTest[905:60b] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:19:06.318Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:19:06.318Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:19:06.319Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:19:06.319Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-27T12:19:06.320Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:19:06.321 ThaliTest[905:60b] client: socket closed
,2015-11-27 13:19:06.323 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:19:06.324 ThaliTest[905:60b] client relay: 0x1b752a30 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b12ba00 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:19:06.324 ThaliTest[905:60b] client session: socket closed: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:19:06.325 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:06.326 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:19:06.326 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:06.328 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:11.324Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:11.325Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:16.330 ThaliTest[905:6907] jxcore: disconnect
2015-11-27 13:19:16.331 ThaliTest[905:6907] jxcore: disconnect: fail
,2015-11-27T12:19:16.333Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:19:16.333Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT8509.17j4Hw== with availability status,: true
2015-11-27T12:19:16.333Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:19:16.334Z SendDataConnector.js: do connect now
,2015-11-27 13:19:16.334 ThaliTest[905:6907] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:16.335 ThaliTest[905:6907] client session: connect
,2015-11-27 13:19:16.335 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:19.334 ThaliTest[905:bc2b] client session: connected
,2015-11-27 13:19:19.336 ThaliTest[905:bc2b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:19.339 ThaliTest[905:bc2b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:19.340 ThaliTest[905:bc2b] jxcore: connect: success
,2015-11-27T12:19:19.341Z SendDataConnector.js: CLIENT connected to 51234, error: null
2015-11-27T12:19:19.341Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:19:19.343 ThaliTest[905:60b] client: relay established
2015-11-27 13:19:19.344 ThaliTest[905:60b] client: new accepted socket: 0x1b4d60e0
,2015-11-27T12:19:19.355Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27 13:19:26.649 ThaliTest[905:60b] multipeer session: restart
,2015-11-27 13:19:26.659 ThaliTest[905:60b] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:19:26.660 ThaliTest[905:60b] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:19:26.661 ThaliTest[905:60b] client: found peer: Apple-Iphone6-1_PT6911.ZjHo2g==
,2015-11-27T12:19:29.412Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:19:29.413Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:19:29.413Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:19:29.414Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-27T12:19:29.415Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:19:29.416 ThaliTest[905:60b] client: socket closed
2015-11-27 13:19:29.417 ThaliTest[905:60b] client relay: socket disconnected
,2015-11-27 13:19:29.418 ThaliTest[905:60b] client relay: 0x1b4d60e0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1b5d4b60 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-27 13:19:29.419 ThaliTest[905:60b] client session: socket closed: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:29.419 ThaliTest[905:60b] client session: onLinkFailure: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:29.420 ThaliTest[905:60b] client session: disconnect
,2015-11-27 13:19:29.420 ThaliTest[905:60b] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:29.422 ThaliTest[905:60b] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:34.422Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:34.423Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:39.429 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:19:39.431 ThaliTest[905:6907] jxcore: disconnect: fail
2015-11-27T12:19:39.432Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:39.433Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT8509.17j4Hw== with availability status: true
2015-11-27T12:19:39.433Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27T12:19:39.433Z SendDataConnector.js: do connect now
,2015-11-27 13:19:39.433 ThaliTest[905:6907] jxcore: connect Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:39.434 ThaliTest[905:6907] client session: connect
,2015-11-27 13:19:39.435 ThaliTest[905:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:42.369 ThaliTest[905:bc2b] client session: connected
,2015-11-27 13:19:42.371 ThaliTest[905:bc2b] client session: stateChange:1->2 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:42.374 ThaliTest[905:780b] client session: fireConnectCallback: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:42.375 ThaliTest[905:780b] jxcore: connect: success
,2015-11-27T12:19:42.377Z SendDataConnector.js: CLIENT connected to 51239, error: null
2015-11-27T12:19:42.377Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:19:42.379 ThaliTest[905:60b] client: relay established
,2015-11-27 13:19:42.380 ThaliTest[905:60b] client: new accepted socket: 0x15ed38e0
,2015-11-27T12:19:42.390Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-27T12:19:52.449Z SendDataConnector.js: Receiving data timeout now
,2015-11-27T12:19:52.449Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27T12:19:52.450Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27T12:19:52.451Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:19:52.452Z SendDataConnector.js: Stop data retrieving timer
2015-11-27T12:19:52.452Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-27 13:19:52.453 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:19:52.454 ThaliTest[905:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8509.17j4Hw==
2015-11-27 13:19:52.454 ThaliTest[905:6907] client session: disconnect
2015-11-27 13:19:52.455 ThaliTest[905:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27 13:19:52.458 ThaliTest[905:6907] jxcore: disconnect: success
2015-11-27T12:19:52.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8509.17j4Hw==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27T12:19:52.463Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27T12:19:52.463Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3767.CF0kqQ==,
2015-11-27T12:19:52.463Z SendDataConnector.js: do connect now
2015-11-27 13:19:52.463 ThaliTest[905:6907] jxcore: connect Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:19:52.464 ThaliTest[905:6907] client session: connect
2015-11-27 13:19:52.465 ThaliTest[905:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27T12:19:52.470Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-27 13:19:56.577 ThaliTest[905:bc2b] client session: connected
2015-11-27 13:19:56.578 ThaliTest[905:bc2b] client session: stateChange:1->2 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:19:56.580 ThaliTest[905:bc2b] client session: fireConnectCallback: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:19:56.581 ThaliTest[905:bc2b] jxcore: connect: success
,2015-11-27T12:19:56.582Z SendDataConnector.js: CLIENT connected to 51242, error: null
,2015-11-27T12:19:56.582Z SendDataConnector.js: CLIENT starting client 
,2015-11-27 13:19:56.584 ThaliTest[905:60b] client: relay established
,2015-11-27 13:19:56.586 ThaliTest[905:60b] client: new accepted socket: 0x1b4f2180
,2015-11-27T12:19:56.596Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-27 13:19:56.649 ThaliTest[905:60b] multipeer session: restart
,2015-11-27 13:19:57.133 ThaliTest[905:60b] client: found peer: Apple-IpadAir2-1_PT3767.CF0kqQ==
2015-11-27 13:19:57.134 ThaliTest[905:60b] client: found peer: Apple-Iphone5s-1_PT8509.17j4Hw==
,2015-11-27T12:19:57.147Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-27T12:19:57.272Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-27T12:19:57.595Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-27T12:19:57.596Z SendDataConnector.js: got all data for this round
,2015-11-27T12:19:57.598Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:19:57.598Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-27 13:19:57.599 ThaliTest[905:6907] jxcore: disconnect
,2015-11-27 13:19:57.600 ThaliTest[905:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:19:57.601 ThaliTest[905:6907] client session: disconnect
,2015-11-27 13:19:57.601 ThaliTest[905:6907] client session: stateChange:2->0 Apple-IpadAir2-1_PT3767.CF0kqQ==
,2015-11-27 13:19:57.603 ThaliTest[905:6907] jxcore: disconnect: success
2015-11-27T12:19:57.604Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3767.CF0kqQ==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT1479","time":215975,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT6911.ZjHo2g==","time":105025,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple,-Iphone5s-1_PT8509.17j4Hw==","time":105552,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-IpadAir2-1_PT3767.CF0kqQ==","time":5133,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100,000,"dataReceived":100000}]}
,sendList : 100% : 5133 ms, 99% : 5133 ms, 95 : 5133 ms, 90% : 5133 ms.
Result count 1, range 5133 ms to  5133 ms.
sendList failed peers count : 2 [66.66666666666667 %]
- Peer ID : Apple-Iphone6-1_PT6911.ZjHo2g==, Tried : 5
,- Peer ID : Apple-Iphone5s-1_PT8509.17j4Hw==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-11-27T12:19:57.613Z SendDataConnector.js: CLIENT Stop now
2015-11-27T12:19:57.614Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-27 13:19:58.009 ThaliTest[905:6907] jxcore: stopBroadcasting
,2015-11-27 13:19:58.010 ThaliTest[905:6907] THEMultipeerSession stopping peer
,2015-11-27 13:19:58.010 ThaliTest[905:6907] multipeer session: stop timer
,2015-11-27 13:19:58.011 ThaliTest[905:6907] server session: disconnect
2015-11-27 13:19:58.011 ThaliTest[905:6907] server session: stateChange:2->0 Apple-Iphone5s-1_PT8509
,2015-11-27 13:19:58.015 ThaliTest[905:6907] server session: disconnect
,2015-11-27 13:19:58.016 ThaliTest[905:6907] server session: stateChange:2->0 Apple-Iphone6-1_PT6911
,2015-11-27 13:19:58.021 ThaliTest[905:6907] server session: disconnect
,2015-11-27 13:19:58.024 ThaliTest[905:6907] server session: stateChange:2->0 Apple-IpadAir2-1_PT3767
,2015-11-27 13:20:06.101 ThaliTest[905:6907] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-27T12:20:06.119Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-27T12:20:06.119Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:20:06.120Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-27T12:20:06.120Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT3767.CF0kqQ==\",\"time\":5133,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT6911.ZjHo2g==\",\"time\":105025,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000},{\"name\":\"Apple-Iphone5s-1_PT8509.17j4Hw==\",\"tim,e\":105552,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
