#### Test 51790364a0f6051_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/94B47C9C-FAEF-42DF-B94B-F1B95F1F3383/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/94B47C9C-FAEF-42DF-B94B-F1B95F1F3383/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364a0f6051/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/CDD1C9AF-4ADD-495E-9FF9-C7E5976995A5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56142"
,(lldb)     command script import "/tmp/94B47C9C-FAEF-42DF-B94B-F1B95F1F3383/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-26 07:49:21.937 ThaliTest[829:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-26 07:49:21.940 ThaliTest[829:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-26 07:49:21.947 ThaliTest[829:60b] Unlimited access to network resources
,2015-11-26 07:49:21.954 ThaliTest[829:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-26 07:49:32.763 ThaliTest[829:60b] Resetting plugins due to page load.
,2015-11-26 07:49:33.596 ThaliTest[829:60b] Finished load of: file:///var/mobile/Applications/CDD1C9AF-4ADD-495E-9FF9-C7E5976995A5/ThaliTest.app/www/index.html
,2015-11-26 07:49:33.775 ThaliTest[829:60b] JXcore Cordova plugin initializing
,2015-11-26 07:49:33.777 ThaliTest[829:6807] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5-1_PT6002
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
serverPort is 49197
,2015-11-26 07:55:08.467 ThaliTest[829:6807] jxcore: startBroadcasting
,2015-11-26 07:55:08.478 ThaliTest[829:6807] server: starting Apple-Iphone5-1_PT6002.+4nCyw==
2015-11-26 07:55:08.480 ThaliTest[829:6807] multipeer session: start timer: 0x19e625c0
2015-11-26 07:55:08.481 ThaliTest[829:6807] THEMultipeerSession initialize,d peer Apple-Iphone5-1_PT6002
2015-11-26 07:55:08.483 ThaliTest[829:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-26T06:55:08.489Z SendDataTCPServer.js: TCP/IP server is bound to port: 49197
,2015-11-26 07:55:09.023 ThaliTest[829:60b] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:09.027Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26T06:55:09.028Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26T06:55:09.028Z SendDataConnector.js: do connect now
,2015-11-26 07:55:09.029 ThaliTest[829:6807] jxcore: connect Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:09.030 ThaliTest[829:6807] client session: connect
2015-11-26 07:55:09.030 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone5s-1,_PT6114.M0DCbA==
,2015-11-26 07:55:09.366 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2617.KcJttQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:09.893 ThaliTest[829:60b] multipeer session: reset timer
,2015-11-26 07:55:09.894 ThaliTest[829:60b] multipeer session: stop timer
,2015-11-26 07:55:09.895 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
,2015-11-26 07:55:09.896 ThaliTest[829:60b] server session: connect
,2015-11-26 07:55:09.897 ThaliTest[829:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:09.900 ThaliTest[829:60b] server: accepting invitation Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:09.908 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-26 07:55:11.640 ThaliTest[829:8303] client session: connected
2015-11-26 07:55:11.643 ThaliTest[829:8303] client session: stateChange:1->2 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:11.645 ThaliTest[829:8303] client session: fireConnectCallback: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:55:11.646 ThaliTest[829:8303] jxcore: connect: success
,2015-11-26T06:55:11.648Z SendDataConnector.js: CLIENT connected to 49200, error: null
2015-11-26T06:55:11.649Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:11.651 ThaliTest[829:60b] client: relay established
2015-11-26 07:55:11.652 ThaliTest[829:60b] client: new accepted socket: 0x19f33e40
,2015-11-26T06:55:11.664Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26 07:55:12.121 ThaliTest[829:8303] server session: connected
2015-11-26 07:55:12.122 ThaliTest[829:8303] server session: stateChange:1->2 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:12.131 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:55:12.160Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:12.650Z SendDataTCPServer.js: TCP/IP server has received 17378 bytes of data
,2015-11-26T06:55:12.665Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-26T06:55:12.681Z SendDataTCPServer.js: TCP/IP server has received 91696 bytes of data
,2015-11-26T06:55:12.684Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-26T06:55:12.696Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26T06:55:12.698Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-26T06:55:12.698Z SendDataConnector.js: got all data for this round
,2015-11-26T06:55:12.700Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:12.700Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:55:12.701 ThaliTest[829:6807] jxcore: disconnect
,2015-11-26 07:55:12.702 ThaliTest[829:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:12.702 ThaliTest[829:6807] client session: disconnect
,2015-11-26 07:55:12.703 ThaliTest[829:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:55:12.705 ThaliTest[829:6807] jxcore: disconnect: success
,2015-11-26T06:55:12.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6114.M0DCbA==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT2617.KcJttQ==
2015-11-26T06:55:12.710Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26T06:55:12.710Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26T06:55:12.712Z SendDataConnector.js: do connect now
,2015-11-26 07:55:12.712 ThaliTest[829:6807] jxcore: connect Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:12.713 ThaliTest[829:6807] client session: connect
,2015-11-26 07:55:12.714 ThaliTest[829:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:13.143 ThaliTest[829:60b] multipeer session: reset timer
2015-11-26 07:55:13.145 ThaliTest[829:60b] multipeer session: stop timer
,2015-11-26 07:55:13.146 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
,2015-11-26 07:55:13.147 ThaliTest[829:60b] server session: connect
2015-11-26 07:55:13.148 ThaliTest[829:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:13.369 ThaliTest[829:60b] server: accepting invitation Apple-Iphone6-1_PT8881
,2015-11-26 07:55:15.858 ThaliTest[829:131f] server session: connected
,2015-11-26 07:55:15.859 ThaliTest[829:131f] server session: stateChange:1->2 Apple-Iphone6-1_PT8881
,2015-11-26 07:55:15.869 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:55:15.872Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26 07:55:15.926 ThaliTest[829:131f] client session: connected
,2015-11-26 07:55:15.928 ThaliTest[829:131f] client session: stateChange:1->2 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:15.939 ThaliTest[829:8303] client session: fireConnectCallback: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:15.939 ThaliTest[829:8303] jxcore: connect: success
,2015-11-26T06:55:15.940Z SendDataConnector.js: CLIENT connected to 49205, error: null
,2015-11-26T06:55:15.941Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:15.942 ThaliTest[829:60b] client: relay established
,2015-11-26 07:55:15.943 ThaliTest[829:60b] client: new accepted socket: 0x19e6b2f0
,2015-11-26T06:55:15.954Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:16.536Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26T06:55:16.894Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-26 07:55:16.898 ThaliTest[829:741b] server session: not connected Apple-Iphone6-1_PT8881
,2015-11-26T06:55:16.908Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-26T06:55:16.932Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-26T06:55:17.001Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-26T06:55:17.013Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-26T06:55:17.026Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-26T06:55:17.026Z SendDataConnector.js: got all data for this round
,2015-11-26T06:55:17.027Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:55:17.027Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:55:17.028 ThaliTest[829:6807] jxcore: disconnect
,2015-11-26 07:55:17.029 ThaliTest[829:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:17.030 ThaliTest[829:6807] client session: disconnect
,2015-11-26 07:55:17.030 ThaliTest[829:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:55:17.033 ThaliTest[829:6807] jxcore: disconnect: success
2015-11-26T06:55:17.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2617.KcJttQ==
---- round done--------
,device[3]: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:55:17.040Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:55:17.041Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
20,15-11-26T06:55:17.041Z SendDataConnector.js: do connect now
,2015-11-26 07:55:17.041 ThaliTest[829:6807] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:17.043 ThaliTest[829:6807] client session: connect
,2015-11-26 07:55:17.044 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:19.597 ThaliTest[829:131f] client session: connected
,2015-11-26 07:55:19.599 ThaliTest[829:131f] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:19.608 ThaliTest[829:741b] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:19.609 ThaliTest[829:741b] jxcore: connect: success
,2015-11-26T06:55:19.610Z SendDataConnector.js: CLIENT connected to 49208, error: null
2015-11-26T06:55:19.611Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:19.612 ThaliTest[829:60b] client: relay established
2015-11-26 07:55:19.613 ThaliTest[829:60b] client: new accepted socket: 0x19bcc0f0
,2015-11-26T06:55:19.626Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-26T06:55:20.138Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-26T06:55:20.163Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-26T06:55:20.175Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-26T06:55:20.199Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-26T06:55:20.223Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-26 07:55:22.721 ThaliTest[829:8303] server session: not connected Apple-Iphone5s-1_PT6114
,2015-11-26T06:55:30.225Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:55:30.226Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:30.227Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:30.227Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:30.228Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:30.229 ThaliTest[829:60b] client: socket closed
2015-11-26 07:55:30.230 ThaliTest[829:60b] client relay: socket disconnected
,2015-11-26 07:55:30.231 ThaliTest[829:60b] client relay: 0x19bcc0f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19b9a490 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-26 07:55:30.232 ThaliTest[829:60b] client session: socket closed: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:30.232 ThaliTest[829:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:30.233 ThaliTest[829:60b] client session: disconnect
,2015-11-26 07:55:30.233 ThaliTest[829:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:30.235 ThaliTest[829:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:33.068 ThaliTest[829:60b] multipeer session: reset timer
2015-11-26 07:55:33.070 ThaliTest[829:60b] multipeer session: stop timer
,2015-11-26 07:55:33.071 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
2015-11-26 07:55:33.071 ThaliTest[829:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT6114)
,2015-11-26 07:55:33.072 ThaliTest[829:60b] server session: disconnect
2015-11-26 07:55:33.072 ThaliTest[829:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:33.075 ThaliTest[829:60b] server session: connect
,2015-11-26 07:55:33.075 ThaliTest[829:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:33.080 ThaliTest[829:60b] server: accepting invitation Apple-Iphone5s-1_PT6114
,2015-11-26T06:55:33.086Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-26T06:55:35.229Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:55:35.229Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:35.312 ThaliTest[829:741b] server session: connected
2015-11-26 07:55:35.314 ThaliTest[829:741b] server session: stateChange:1->2 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:35.317 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:55:35.320Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:35.499Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:55:40.241 ThaliTest[829:6807] jxcore: disconnect
2015-11-26 07:55:40.242 ThaliTest[829:6807] jxcore: disconnect: fail
,2015-11-26T06:55:40.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:55:40.244Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT8881.4jE3Ag== with availability status: ,true
2015-11-26T06:55:40.244Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:55:40.244Z SendDataConnector.js: do connect now
,2015-11-26 07:55:40.245 ThaliTest[829:6807] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:40.246 ThaliTest[829:6807] client session: connect
,2015-11-26 07:55:40.246 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:43.039 ThaliTest[829:131f] client session: connected
,2015-11-26 07:55:43.040 ThaliTest[829:131f] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:43.059 ThaliTest[829:741b] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:55:43.060 ThaliTest[829:741b] jxcore: connect: success
,2015-11-26T06:55:43.061Z SendDataConnector.js: CLIENT connected to 49214, error: null
,2015-11-26T06:55:43.061Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:55:43.063 ThaliTest[829:60b] client: relay established
,2015-11-26 07:55:43.063 ThaliTest[829:60b] client: new accepted socket: 0x19f27c70
,2015-11-26T06:55:43.074Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:55:45.681 ThaliTest[829:741b] server session: not connected Apple-Iphone5s-1_PT6114
,2015-11-26T06:55:53.136Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:55:53.137Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:53.137Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:55:53.138Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:55:53.139Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:55:53.141 ThaliTest[829:60b] client: socket closed
2015-11-26 07:55:53.141 ThaliTest[829:60b] client relay: socket disconnected
,2015-11-26 07:55:53.142 ThaliTest[829:60b] client relay: 0x19f27c70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19bc6710 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-26 07:55:53.143 ThaliTest[829:60b] client session: socket closed: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:53.143 ThaliTest[829:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:53.144 ThaliTest[829:60b] client session: disconnect
,2015-11-26 07:55:53.144 ThaliTest[829:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:53.146 ThaliTest[829:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:55.607 ThaliTest[829:60b] multipeer session: reset timer
2015-11-26 07:55:55.608 ThaliTest[829:60b] multipeer session: stop timer
,2015-11-26 07:55:55.609 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
2015-11-26 07:55:55.609 ThaliTest[829:60b] server: disconnecting to refresh session (Apple-Iphone5s-1_PT6114)
,2015-11-26 07:55:55.610 ThaliTest[829:60b] server session: disconnect
2015-11-26 07:55:55.611 ThaliTest[829:60b] server session: stateChange:2->0 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:55.613 ThaliTest[829:60b] server session: connect
2015-11-26T06:55:55.614Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-26 07:55:55.614 ThaliTest[829:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:55.619 ThaliTest[829:60b] server: accepting invitation Apple-Iphone5s-1_PT6114
,2015-11-26T06:55:58.145Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:55:58.146Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:55:58.244 ThaliTest[829:741b] server session: connected
,2015-11-26 07:55:58.246 ThaliTest[829:741b] server session: stateChange:1->2 Apple-Iphone5s-1_PT6114
,2015-11-26 07:55:58.249 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:55:58.259Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:55:58.338Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:56:03.149 ThaliTest[829:6807] jxcore: disconnect
2015-11-26 07:56:03.151 ThaliTest[829:6807] jxcore: disconnect: fail
2015-11-26T06:56:03.152Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:03.153Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8881.4jE3Ag== with availability status: true
2015-11-26T06:56:03.153Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:56:03.153Z SendDataConnector.js: do connect now
,2015-11-26 07:56:03.153 ThaliTest[829:6807] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:56:03.154 ThaliTest[829:6807] client session: connect
,2015-11-26 07:56:03.155 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:05.775 ThaliTest[829:131f] client session: connected
,2015-11-26 07:56:05.777 ThaliTest[829:131f] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:05.784 ThaliTest[829:131f] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:05.786 ThaliTest[829:131f] jxcore: connect: success
,2015-11-26T06:56:05.787Z SendDataConnector.js: CLIENT connected to 49219, error: null
,2015-11-26T06:56:05.787Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:56:05.789 ThaliTest[829:60b] client: relay established
2015-11-26 07:56:05.789 ThaliTest[829:60b] client: new accepted socket: 0x19a258e0
,2015-11-26T06:56:05.801Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:56:08.845 ThaliTest[829:741b] server session: not connected Apple-Iphone5s-1_PT6114
,2015-11-26T06:56:15.852Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:56:15.852Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-26T06:56:15.853Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:56:15.853Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-11-26T06:56:15.854Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:56:15.855 ThaliTest[829:60b] client: socket closed
2015-11-26 07:56:15.856 ThaliTest[829:60b] client relay: socket disconnected
2015-11-26 07:56:15.857 ThaliTest[829:60b] client relay: 0x19a258e0 disconnected with error Error Domain=GCDAsyn,cSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19afb240 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-26 07:56:15.857 ThaliTest[829:60b] client session: socket closed: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:56:15.858 ThaliTest[829:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:15.859 ThaliTest[829:60b] client session: disconnect
2015-11-26 07:56:15.859 ThaliTest[829:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:15.861 ThaliTest[829:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:20.863Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:20.864Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:25.611 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:56:25.621 ThaliTest[829:60b] client: found peer: Apple-Iphone5s-1_PT6114.M0DCbA==
,2015-11-26 07:56:25.623 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:56:25.624 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:25.871 ThaliTest[829:6807] jxcore: disconnect
,2015-11-26 07:56:25.873 ThaliTest[829:6807] jxcore: disconnect: fail
2015-11-26T06:56:25.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:25.875Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8881.4jE3Ag== with availability status: true
2015-11-26T06:56:25.875Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26T06:56:25.875Z SendDataConnector.js: do connect now
,2015-11-26 07:56:25.876 ThaliTest[829:6807] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:25.876 ThaliTest[829:6807] client session: connect
,2015-11-26 07:56:25.877 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:28.641 ThaliTest[829:820b] client session: connected
2015-11-26 07:56:28.642 ThaliTest[829:820b] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:28.650 ThaliTest[829:820b] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:56:28.651 ThaliTest[829:820b] jxcore: connect: success
,2015-11-26T06:56:28.653Z SendDataConnector.js: CLIENT connected to 49224, error: null
,2015-11-26T06:56:28.653Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:56:28.655 ThaliTest[829:60b] client: relay established
,2015-11-26 07:56:28.655 ThaliTest[829:60b] client: new accepted socket: 0x19b10100
,2015-11-26T06:56:28.666Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26T06:56:38.729Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:56:38.729Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:56:38.730Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:56:38.731Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-26T06:56:38.731Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:56:38.733 ThaliTest[829:60b] client: socket closed
2015-11-26 07:56:38.734 ThaliTest[829:60b] client relay: socket disconnected
,2015-11-26 07:56:38.734 ThaliTest[829:60b] client relay: 0x19b10100 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19e7fd30 {NSLocalizedDescription=Socket closed by remote peer} 
,2015-11-26 07:56:38.735 ThaliTest[829:60b] client session: socket closed: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:56:38.736 ThaliTest[829:60b] client session: onLinkFailure: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:38.736 ThaliTest[829:60b] client session: disconnect
2015-11-26 07:56:38.737 ThaliTest[829:60b] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:38.738 ThaliTest[829:60b] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:43.734Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:43.734Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:48.448 ThaliTest[829:60b] multipeer session: reset timer
2015-11-26 07:56:48.449 ThaliTest[829:60b] multipeer session: stop timer
,2015-11-26 07:56:48.450 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
2015-11-26 07:56:48.451 ThaliTest[829:60b] server session: connect
,2015-11-26 07:56:48.451 ThaliTest[829:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2617
,2015-11-26 07:56:48.455 ThaliTest[829:60b] server: accepting invitation Apple-IpadAir2-1_PT2617
,2015-11-26 07:56:48.738 ThaliTest[829:6807] jxcore: disconnect
,2015-11-26 07:56:48.739 ThaliTest[829:6807] jxcore: disconnect: fail
,2015-11-26T06:56:48.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:48.742Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT8881.4jE3Ag== with availability status: true
2015-11-26T06:56:48.742Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26T06:56:48.742Z SendDataConnector.js: do connect now
,2015-11-26 07:56:48.743 ThaliTest[829:6807] jxcore: connect Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:48.743 ThaliTest[829:6807] client session: connect
,2015-11-26 07:56:48.744 ThaliTest[829:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:52.229 ThaliTest[829:983f] client session: connected
,2015-11-26 07:56:52.231 ThaliTest[829:983f] client session: stateChange:1->2 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:52.239 ThaliTest[829:820b] client session: fireConnectCallback: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:56:52.240 ThaliTest[829:820b] jxcore: connect: success
,2015-11-26T06:56:52.241Z SendDataConnector.js: CLIENT connected to 49229, error: null
,2015-11-26T06:56:52.241Z SendDataConnector.js: CLIENT starting client 
,2015-11-26 07:56:52.243 ThaliTest[829:60b] client: relay established
2015-11-26 07:56:52.243 ThaliTest[829:60b] client: new accepted socket: 0x19b139a0
,2015-11-26T06:56:52.256Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-26 07:56:56.137 ThaliTest[829:60b] client: lost peer: Apple-Iphone5s-1_PT6114.M0DCbA==
2015-11-26 07:56:56.139 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone5s-1_PT6114.M0DCbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6114.M0DCbA==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:56:56.553 ThaliTest[829:983f] server session: connected
,2015-11-26 07:56:56.555 ThaliTest[829:983f] server session: stateChange:1->2 Apple-IpadAir2-1_PT2617
,2015-11-26 07:56:56.575 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:56:56.584Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:56:56.943Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-11-26T06:56:56.955Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-26T06:56:57.012Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-11-26T06:56:57.070Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-26T06:56:57.082Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-11-26T06:56:57.107Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-26T06:57:02.312Z SendDataConnector.js: Receiving data timeout now
,2015-11-26T06:57:02.313Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:57:02.314Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26T06:57:02.316Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:57:02.316Z SendDataConnector.js: Stop data retrieving timer
2015-11-26T06:57:02.317Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-26 07:57:02.317 ThaliTest[829:6807] jxcore: disconnect
,2015-11-26 07:57:02.318 ThaliTest[829:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:57:02.318 ThaliTest[829:6807] client session: disconnect
,2015-11-26 07:57:02.319 ThaliTest[829:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:57:02.322 ThaliTest[829:6807] jxcore: disconnect: success
2015-11-26T06:57:02.322Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8881.4jE3Ag==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT6002","time":113865,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT6114.M0DCbA==","time":3672,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-,1_PT2617.KcJttQ==","time":4317,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT8881.4jE3Ag==","time":105275,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataR,eceived":90000}]}
sendList : 100% : 4317 ms, 99% : 4317 ms, 95 : 4317 ms, 90% : 4317 ms.
Result count 2, range 3672 ms to  4317 ms.
sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone6-1_PT8881.4jE3Ag==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-11-26T06:57:02.332Z SendDataConnector.js: CLIENT Stop now
2015-11-26T06:57:02.332Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-26T06:57:02,.333Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-26 07:57:07.419 ThaliTest[829:951f] server session: not connected Apple-IpadAir2-1_PT2617
,2015-11-26 07:57:18.452 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:57:47.439 ThaliTest[829:60b] multipeer session: reset timer
2015-11-26 07:57:47.440 ThaliTest[829:60b] multipeer session: stop timer
2015-11-26 07:57:47.441 ThaliTest[829:60b] multipeer session: start timer: 0x19e625c0
2015-11-26 07:57:47.,442 ThaliTest[829:60b] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2617)
2015-11-26 07:57:47.443 ThaliTest[829:60b] server session: disconnect
2015-11-26 07:57:47.443 ThaliTest[829:60b] server session: stateChange:2->0 Apple-IpadAir2-1_PT2617
,2015-11-26 07:57:47.446 ThaliTest[829:60b] server session: connect
2015-11-26 07:57:47.448 ThaliTest[829:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2617
2015-11-26T06:57:47.448Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-26 07:57:47.451 ThaliTest[829:60b] server: accepting invitation Apple-IpadAir2-1_PT2617
,2015-11-26 07:57:50.006 ThaliTest[829:9527] server session: connected
,2015-11-26 07:57:50.007 ThaliTest[829:9527] server session: stateChange:1->2 Apple-IpadAir2-1_PT2617
,2015-11-26 07:57:50.015 ThaliTest[829:60b] server relay: connected (to port: 49197)
,2015-11-26T06:57:50.022Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-26T06:57:50.079Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-26 07:58:00.364 ThaliTest[829:ae57] server session: not connected Apple-IpadAir2-1_PT2617
,2015-11-26 07:58:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:58:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:58:17.455 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 07:58:39.201 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:58:39.203 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:58:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:58:47.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:58:47.687 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 07:59:13.269 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 07:59:13.271 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 07:59:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:59:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 07:59:47.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 07:59:47.970 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:00:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:00:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:00:17.454 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:00:37.038 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:00:37.040 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:00:39.184 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:00:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:01:17.442 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:01:17.454 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:01:18.043 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:01:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:01:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:01:47.454 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:02:09.393 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:02:09.394 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:02:10.392 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:02:13.586 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:02:13.588 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:02:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:02:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:02:18.251 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:02:43.463 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:02:43.465 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:02:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:03:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:03:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:03:17.455 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:03:43.235 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:03:43.236 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:03:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:03:47.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:03:48.484 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:04:13.245 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:04:13.247 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:04:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:04:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:04:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:04:47.800 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:05:13.377 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:05:13.379 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:05:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:05:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:05:17.662 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:05:43.300 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:05:43.301 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:05:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:05:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:05:47.920 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:06:09.463 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:06:09.464 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:06:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:06:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:06:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:06:47.811 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:07:13.413 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
,2015-11-26 08:07:13.414 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:07:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:07:18.031 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:07:18.146 ThaliTest[829:60b] client: found peer: Apple-Iphone6-1_PT8881.4jE3Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":true}]
,2015-11-26 08:07:37.425 ThaliTest[829:60b] client: lost peer: Apple-Iphone6-1_PT8881.4jE3Ag==
2015-11-26 08:07:37.427 ThaliTest[829:60b] client session: onPeerLost: Apple-Iphone6-1_PT8881.4jE3Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8881.4jE3Ag==","peerName":"(null)","peerAvailable":false}]
,2015-11-26 08:07:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:08:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:08:17.454 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:08:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:09:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:09:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:09:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:09:47.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:10:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:10:17.454 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:10:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:11:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:11:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:11:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:11:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:12:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:12:17.454 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:12:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:12:47.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:13:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:13:17.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:13:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:14:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:14:17.452 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==
,2015-11-26 08:14:47.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:15:17.443 ThaliTest[829:60b] multipeer session: restart
,2015-11-26 08:15:17.453 ThaliTest[829:60b] client: found peer: Apple-IpadAir2-1_PT2617.KcJttQ==

```
