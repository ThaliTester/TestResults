#### Test 51790364c93db41_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/C986343D-CE39-4616-AC47-34CCE4C553E6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C986343D-CE39-4616-AC47-34CCE4C553E6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/A3E108A2-4899-4ADD-89CD-64C68D3A3159/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55621"
,(lldb)     command script import "/tmp/C986343D-CE39-4616-AC47-34CCE4C553E6/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 14:27:06.618 ThaliTest[787:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-11-25 14:27:06.621 ThaliTest[787:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-25 14:27:06.627 ThaliTest[787:60b] Unlimited access to network resources
,2015-11-25 14:27:06.635 ThaliTest[787:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 14:27:17.499 ThaliTest[787:60b] Resetting plugins due to page load.
,2015-11-25 14:27:18.375 ThaliTest[787:60b] Finished load of: file:///var/mobile/Applications/A3E108A2-4899-4ADD-89CD-64C68D3A3159/ThaliTest.app/www/index.html
,2015-11-25 14:27:18.556 ThaliTest[787:60b] JXcore Cordova plugin initializing
,2015-11-25 14:27:18.558 ThaliTest[787:6907] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT6254
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 64407
,2015-11-25 14:32:34.826 ThaliTest[787:6907] jxcore: startBroadcasting
,2015-11-25 14:32:34.835 ThaliTest[787:6907] server: starting Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:32:34.837 ThaliTest[787:6907] multipeer session: start timer: 0x1b68bab0
2015-11-25 14:32:34.840 ThaliTest[787:6907] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6254
2015-11-25 14:32:34.841 ThaliTest[787:6907] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T13:32:34.844Z SendDataTCPServer.js: TCP/IP server is bound to port: 64407
,2015-11-25 14:32:35.147 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25T13:32:35.151Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25T13:32:35.152Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25T13:32:35.152Z SendDataConnector.js: do connect now
,2015-11-25 14:32:35.152 ThaliTest[787:6907] jxcore: connect Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:35.153 ThaliTest[787:6907] client session: connect
,2015-11-25 14:32:35.154 ThaliTest[787:6907] client session: stateChange:0->1 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:35.180 ThaliTest[787:60b] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 14:32:36.098 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 14:32:38.178 ThaliTest[787:7a07] client session: connected
2015-11-25 14:32:38.179 ThaliTest[787:7a07] client session: stateChange:1->2 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:38.199 ThaliTest[787:7a07] client session: fireConnectCallback: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:32:38.200 ThaliTest[787:7a07] jxcore: connect: success
,2015-11-25T13:32:38.201Z SendDataConnector.js: CLIENT connected to 64410, error: null
,2015-11-25T13:32:38.202Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:38.204 ThaliTest[787:60b] client: relay established
,2015-11-25 14:32:38.204 ThaliTest[787:60b] client: new accepted socket: 0x1b696a10
,2015-11-25T13:32:38.215Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:38.365Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T13:32:38.379Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T13:32:38.391Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T13:32:38.405Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T13:32:38.418Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T13:32:38.418Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:38.420Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:38.420Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:38.421 ThaliTest[787:6907] jxcore: disconnect
,2015-11-25 14:32:38.422 ThaliTest[787:6907] client session: disconnectFromPeer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:38.423 ThaliTest[787:6907] client session: disconnect
,2015-11-25 14:32:38.424 ThaliTest[787:6907] client session: stateChange:2->0 Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:32:38.427 ThaliTest[787:6907] jxcore: disconnect: success
2015-11-25T13:32:38.428Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8475.0elZ3A==
---- round done--------
,device[2]: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:38.432Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25T13:32:38.432Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8640.H39DFw==,
2015-11-25T13:32:38.432Z SendDataConnector.js: do connect now
2015-11-25 14:32:38.433 ThaliTest[787:6907] jxcore: connect Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:38.434 ThaliTest[787:6907] client session: connect
2015-11-25 14:32:38.434 Thali,Test[787:6907] client session: stateChange:0->1 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:41.030 ThaliTest[787:7a07] client session: connected
2015-11-25 14:32:41.031 ThaliTest[787:7a07] client session: stateChange:1->2 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:41.040 ThaliTest[787:7a07] client session: fireConnectCallback: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:32:41.041 ThaliTest[787:7a07] jxcore: connect: success
,2015-11-25T13:32:41.042Z SendDataConnector.js: CLIENT connected to 64414, error: null
,2015-11-25T13:32:41.043Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:41.044 ThaliTest[787:60b] client: relay established
,2015-11-25 14:32:41.045 ThaliTest[787:60b] client: new accepted socket: 0x1b69c850
,2015-11-25T13:32:41.055Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T13:32:41.413Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T13:32:41.427Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T13:32:41.439Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T13:32:41.463Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T13:32:41.475Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T13:32:41.498Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T13:32:41.510Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T13:32:41.523Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T13:32:41.524Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:41.525Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:41.526Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:41.526 ThaliTest[787:6907] jxcore: disconnect
,2015-11-25 14:32:41.527 ThaliTest[787:6907] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:41.528 ThaliTest[787:6907] client session: disconnect
,2015-11-25 14:32:41.528 ThaliTest[787:6907] client session: stateChange:2->0 Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:41.530 ThaliTest[787:6907] jxcore: disconnect: success
2015-11-25T13:32:41.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8640.H39DFw==
---- round done--------
device[3]: Apple-IpadAir2-1_PT1710.Fke,XvQ==
2015-11-25T13:32:41.532Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25T13:32:41.532Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25T13:32:41.533Z SendDataConnector.js: do connect now
,2015-11-25 14:32:41.534 ThaliTest[787:6907] jxcore: connect Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:32:41.535 ThaliTest[787:6907] client session: connect
,2015-11-25 14:32:41.536 ThaliTest[787:6907] client session: stateChange:0->1 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:42.975 ThaliTest[787:60b] multipeer session: reset timer
,2015-11-25 14:32:42.977 ThaliTest[787:60b] multipeer session: stop timer
2015-11-25 14:32:42.977 ThaliTest[787:60b] multipeer session: start timer: 0x1b68bab0
,2015-11-25 14:32:42.978 ThaliTest[787:60b] server session: connect
,2015-11-25 14:32:42.978 ThaliTest[787:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:42.982 ThaliTest[787:60b] server: accepting invitation Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:45.526 ThaliTest[787:60b] multipeer session: reset timer
,2015-11-25 14:32:45.527 ThaliTest[787:60b] multipeer session: stop timer
,2015-11-25 14:32:45.528 ThaliTest[787:60b] multipeer session: start timer: 0x1b68bab0
,2015-11-25 14:32:45.529 ThaliTest[787:60b] server session: connect
,2015-11-25 14:32:45.530 ThaliTest[787:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:45.533 ThaliTest[787:60b] server: accepting invitation Apple-Iphone6-1_PT8475
,2015-11-25 14:32:48.148 ThaliTest[787:7a07] server session: connected
2015-11-25 14:32:48.150 ThaliTest[787:7a07] server session: stateChange:1->2 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:48.160 ThaliTest[787:60b] server relay: connected (to port: 64407)
,2015-11-25T13:32:48.165Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:48.255Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-25T13:32:48.267Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-25T13:32:48.281Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-25T13:32:48.294Z SendDataTCPServer.js: TCP/IP server has received 89364 bytes of data
,2015-11-25T13:32:48.307Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:48.326 ThaliTest[787:7a07] server session: not connected Apple-Iphone6-1_PT8475
,2015-11-25 14:32:50.211 ThaliTest[787:7a07] client session: connected
,2015-11-25 14:32:50.213 ThaliTest[787:7a07] client session: stateChange:1->2 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:50.247 ThaliTest[787:141b] client session: fireConnectCallback: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:32:50.248 ThaliTest[787:141b] jxcore: connect: success
,2015-11-25T13:32:50.249Z SendDataConnector.js: CLIENT connected to 64418, error: null
2015-11-25T13:32:50.249Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 14:32:50.251 ThaliTest[787:60b] client: relay established
2015-11-25 14:32:50.252 ThaliTest[787:60b] client: new accepted socket: 0x1b769050
,2015-11-25T13:32:50.264Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25 14:32:50.309 ThaliTest[787:7a07] server session: connected
,2015-11-25 14:32:50.310 ThaliTest[787:7a07] server session: stateChange:1->2 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:50.318 ThaliTest[787:60b] server relay: connected (to port: 64407)
,2015-11-25T13:32:50.427Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:50.440Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25T13:32:50.923Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T13:32:51.247Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T13:32:51.337Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T13:32:51.394Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25 14:32:51.426 ThaliTest[787:5f3f] server session: not connected Apple-IpadAir2-1_PT1710
,2015-11-25T13:32:51.861Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T13:32:51.962Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T13:32:51.963Z SendDataConnector.js: got all data for this round
,2015-11-25T13:32:51.965Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:51.965Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:32:51.965 ThaliTest[787:6907] jxcore: disconnect
,2015-11-25 14:32:51.966 ThaliTest[787:6907] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:51.967 ThaliTest[787:6907] client session: disconnect
,2015-11-25 14:32:51.967 ThaliTest[787:6907] client session: stateChange:2->0 Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:32:51.969 ThaliTest[787:6907] jxcore: disconnect: success
2015-11-25T13:32:51.971Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1710.FkeXvQ==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT6254","time":17157,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8475.0elZ3A==","time":3267,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_,PT8640.H39DFw==","time":3092,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT1710.FkeXvQ==","time":10431,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 10431 ms, 99% : 10431 ms, 95 : 10431 ms, 90% : 10431 ms.
Result count 3, range 3092 ms to  10431 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-25T13:32:51.979Z SendDataConnector.js: CLIENT Stop now
2015-11-25T13:32:51.979Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 14:33:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:33:15.541 ThaliTest[787:60b] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:33:15.542 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:33:15.893 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:33:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:34:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:34:15.541 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:34:15.541 ThaliTest[787:60b] client: found peer: Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:34:16.295 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:34:41.783 ThaliTest[787:60b] client: lost peer: Apple-Iphone5s-1_PT8640.H39DFw==
2015-11-25 14:34:41.785 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone5s-1_PT8640.H39DFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8640.H39DFw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:34:45.025 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:34:45.026 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:34:45.500 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:34:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:35:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:35:15.540 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:35:17.106 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:35:19.532 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:35:19.533 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:35:23.764 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:35:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:35:45.540 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:35:48.576 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:35:55.957 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:35:55.958 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:36:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:36:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:36:50.934 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:37:04.034 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:37:12.745 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:37:12.747 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:37:12.792 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:37:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:37:15.540 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:37:15.541 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-11-25 14:37:39.218 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:37:39.219 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-11-25 14:37:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:38:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:38:15.539 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:38:18.889 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:38:18.890 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:38:21.637 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:38:21.639 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:38:22.520 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:38:44.106 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:38:44.108 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:38:44.666 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:38:44.668 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:38:45.047 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:38:45.529 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:39:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:39:15.539 ThaliTest[787:60b] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:39:41.286 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:39:43.184 ThaliTest[787:60b] client: lost peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:39:43.185 ThaliTest[787:60b] client session: onPeerLost: Apple-Iphone6-1_PT8475.0elZ3A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:39:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:39:45.539 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:40:04.290 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:40:04.291 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:40:07.492 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:40:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:40:15.538 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:40:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:40:46.267 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:41:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:41:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:42:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:42:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:42:46.843 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:43:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:43:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:43:45.541 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:44:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:44:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:44:47.399 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:45:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:45:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:45:50.298 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:46:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:46:15.540 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:46:37.202 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:46:37.203 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:46:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:47:07.874 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:47:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:47:15.539 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:47:27.210 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:47:27.212 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:47:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:47:55.094 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:48:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:48:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:48:48.515 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:49:15.059 ThaliTest[787:60b] client: lost peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
2015-11-25 14:49:15.061 ThaliTest[787:60b] client session: onPeerLost: Apple-IpadAir2-1_PT1710.FkeXvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 14:49:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:49:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:49:50.376 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 14:50:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:50:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:51:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:51:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:52:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:52:25.571 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:52:45.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:52:46.480 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:53:15.530 ThaliTest[787:60b] multipeer session: restart
,2015-11-25 14:53:15.540 ThaliTest[787:60b] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==

```
