#### Test 5133502830f515a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/30F1C0BD-EB51-469C-875B-69E1724358CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/30F1C0BD-EB51-469C-875B-69E1724358CC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/C82E3C0E-DB5E-4C99-BFB4-84E53633A1A9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55324"
,(lldb)     command script import "/tmp/30F1C0BD-EB51-469C-875B-69E1724358CC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 11:09:42.324 ThaliTest[765:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 11:09:42.327 ThaliTest[765:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-25 11:09:42.333 ThaliTest[765:60b] Unlimited access to network resources
,2015-11-25 11:09:42.339 ThaliTest[765:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.appl,e.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 11:09:53.061 ThaliTest[765:60b] Resetting plugins due to page load.
,2015-11-25 11:09:53.932 ThaliTest[765:60b] Finished load of: file:///var/mobile/Applications/C82E3C0E-DB5E-4C99-BFB4-84E53633A1A9/ThaliTest.app/www/index.html
,2015-11-25 11:09:54.109 ThaliTest[765:60b] JXcore Cordova plugin initializing
,2015-11-25 11:09:54.111 ThaliTest[765:6807] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT7626
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 63963
,2015-11-25 11:15:34.568 ThaliTest[765:6807] jxcore: startBroadcasting
,2015-11-25 11:15:34.579 ThaliTest[765:6807] server: starting Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:15:34.582 ThaliTest[765:6807] multipeer session: start timer: 0x1a5d2df0
2015-11-25 11:15:34.584 ThaliTest[765:6807] THEMultipeerSession initialize,d peer Apple-Iphone5-1_PT7626
,2015-11-25 11:15:34.585 ThaliTest[765:6807] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-25T10:15:34.595Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 11:15:35.014 ThaliTest[765:60b] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25T10:15:35.018Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25T10:15:35.019Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25T10:15:35.019Z SendDataConnector.js: do connect now
,2015-11-25 11:15:35.019 ThaliTest[765:6807] jxcore: connect Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:35.020 ThaliTest[765:6807] client session: connect
,2015-11-25 11:15:35.021 ThaliTest[765:6807] client session: stateChange:0->1 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:35.263 ThaliTest[765:60b] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 11:15:35.572 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-11-25 11:15:41.634 ThaliTest[765:60b] multipeer session: reset timer
2015-11-25 11:15:41.636 ThaliTest[765:60b] multipeer session: stop timer
,2015-11-25 11:15:41.637 ThaliTest[765:60b] multipeer session: start timer: 0x1a5d2df0
2015-11-25 11:15:41.637 ThaliTest[765:60b] server session: connect
,2015-11-25 11:15:41.638 ThaliTest[765:60b] server session: stateChange:0->1 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:41.641 ThaliTest[765:60b] server: accepting invitation Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:43.701 ThaliTest[765:622b] client session: connected
,2015-11-25 11:15:43.702 ThaliTest[765:622b] client session: stateChange:1->2 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:43.713 ThaliTest[765:8403] client session: fireConnectCallback: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:43.713 ThaliTest[765:8403] jxcore: connect: success
,2015-11-25T10:15:43.715Z SendDataConnector.js: CLIENT connected to 63966, error: null
,2015-11-25T10:15:43.715Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:43.716 ThaliTest[765:60b] client: relay established
,2015-11-25 11:15:43.717 ThaliTest[765:60b] client: new accepted socket: 0x1a6347d0
,2015-11-25T10:15:43.730Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25 11:15:43.809 ThaliTest[765:622b] server session: connected
2015-11-25 11:15:43.810 ThaliTest[765:622b] server session: stateChange:1->2 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:43.820 ThaliTest[765:60b] server relay: connected (to port: 63963)
,2015-11-25T10:15:43.873Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:44.201Z SendDataTCPServer.js: TCP/IP server has received 12998 bytes of data
,2015-11-25T10:15:44.214Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-11-25T10:15:44.229Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-11-25T10:15:44.244Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
2015-11-25T10:15:44.248Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T10:15:44.263Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
2015-11-25T10:15:44.264Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T10:15:44.264Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:44.266Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:44.267Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 11:15:44.269 ThaliTest[765:6807] jxcore: disconnect
,2015-11-25 11:15:44.270 ThaliTest[765:6807] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:15:44.270 ThaliTest[765:6807] client session: disconnect
,2015-11-25 11:15:44.272 ThaliTest[765:6807] client session: stateChange:2->0 Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:15:44.277 ThaliTest[765:6807] jxcore: disconnect: success
,2015-11-25T10:15:44.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9949.0t9DBw==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:44.283Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:44.284Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:44.284Z SendDataConnector.js: do connect now
,2015-11-25 11:15:44.284 ThaliTest[765:6807] jxcore: connect Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:44.286 ThaliTest[765:6807] client session: connect
,2015-11-25 11:15:44.286 ThaliTest[765:6807] client session: stateChange:0->1 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25T10:15:44.305Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:44.385 ThaliTest[765:8403] server session: not connected Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:45.312 ThaliTest[765:60b] multipeer session: reset timer
2015-11-25 11:15:45.313 ThaliTest[765:60b] multipeer session: stop timer
,2015-11-25 11:15:45.314 ThaliTest[765:60b] multipeer session: start timer: 0x1a5d2df0
2015-11-25 11:15:45.315 ThaliTest[765:60b] server session: connect
,2015-11-25 11:15:45.315 ThaliTest[765:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:45.319 ThaliTest[765:60b] server: accepting invitation Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:47.370 ThaliTest[765:622b] client session: connected
2015-11-25 11:15:47.372 ThaliTest[765:622b] client session: stateChange:1->2 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:47.374 ThaliTest[765:622b] client session: fireConnectCallback: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:47.375 ThaliTest[765:622b] jxcore: connect: success
,2015-11-25T10:15:47.377Z SendDataConnector.js: CLIENT connected to 63970, error: null
2015-11-25T10:15:47.378Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:47.379 ThaliTest[765:60b] client: relay established
,2015-11-25 11:15:47.381 ThaliTest[765:60b] client: new accepted socket: 0x1a5ee2b0
,2015-11-25T10:15:47.391Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:47.561Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T10:15:47.585Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T10:15:47.598Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T10:15:47.865Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T10:15:47.877Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T10:15:47.890Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T10:15:47.892Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:47.893Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:47.894Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:47.895 ThaliTest[765:6807] jxcore: disconnect
,2015-11-25 11:15:47.896 ThaliTest[765:6807] client session: disconnectFromPeer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:47.897 ThaliTest[765:6807] client session: disconnect
,2015-11-25 11:15:47.899 ThaliTest[765:7813] server session: connected
2015-11-25 11:15:47.898 ThaliTest[765:6807] client session: stateChange:2->0 Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:15:47.901 ThaliTest[765:7813] server session: stateChange:1->2 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:47.903 ThaliTest[765:60b] server relay: connected (to port: 63963)
,2015-11-25 11:15:47.905 ThaliTest[765:6807] jxcore: disconnect: success
2015-11-25T10:15:47.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5679.a5FFow==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25T10:15:47.911Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25T10:15:47.911Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25T10:15:47.911Z SendDataConnector.js: do connect now
,2015-11-25 11:15:47.912 ThaliTest[765:6807] jxcore: connect Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:47.912 ThaliTest[765:6807] client session: connect
,2015-11-25 11:15:47.913 ThaliTest[765:6807] client session: stateChange:0->1 Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25T10:15:47.934Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:47.981Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-25T10:15:48.017Z SendDataTCPServer.js: TCP/IP server has received 63368 bytes of data
,2015-11-25T10:15:48.034Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:48.116 ThaliTest[765:a207] server session: not connected Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:50.551 ThaliTest[765:7813] client session: connected
2015-11-25 11:15:50.554 ThaliTest[765:7813] client session: stateChange:1->2 Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:50.556 ThaliTest[765:7813] client session: fireConnectCallback: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:50.557 ThaliTest[765:7813] jxcore: connect: success
,2015-11-25T10:15:50.558Z SendDataConnector.js: CLIENT connected to 63974, error: null
,2015-11-25T10:15:50.559Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 11:15:50.561 ThaliTest[765:60b] client: relay established
2015-11-25 11:15:50.562 ThaliTest[765:60b] client: new accepted socket: 0x1a637ed0
,2015-11-25T10:15:50.572Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T10:15:51.045Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T10:15:51.124Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T10:15:51.558Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25T10:15:51.571Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T10:15:51.571Z SendDataConnector.js: got all data for this round
,2015-11-25T10:15:51.573Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:51.574Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:15:51.574 ThaliTest[765:6807] jxcore: disconnect
,2015-11-25 11:15:51.575 ThaliTest[765:6807] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:51.575 ThaliTest[765:6807] client session: disconnect
,2015-11-25 11:15:51.576 ThaliTest[765:6807] client session: stateChange:2->0 Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:15:51.579 ThaliTest[765:6807] jxcore: disconnect: success
2015-11-25T10:15:51.580Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2339.pNGAWw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT7626","time":17022,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT9949.0t9DBw==","time":9247,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT5679.a5FFow==","time":3608,"result":"OK","connections":,1},{"name":"Apple-IpadAir2-1_PT2339.pNGAWw==","time":3660,"result":"OK","connections":1}]}
,sendList : 100% : 9247 ms, 99% : 9247 ms, 95 : 9247 ms, 90% : 9247 ms.
Result count 3, range 3608 ms to  9247 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-25T10:15:51.587Z SendDataConnector.js: CLIENT Stop now
2015-11-25T10:15:51.587Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 11:16:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:16:16.694 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:16:16.826 ThaliTest[765:60b] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
,2015-11-25 11:16:16.829 ThaliTest[765:60b] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:16:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:17:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:17:15.326 ThaliTest[765:60b] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:15.327 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:17:20.647 ThaliTest[765:60b] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:17:23.964 ThaliTest[765:60b] client: lost peer: Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:17:23.966 ThaliTest[765:60b] client session: onPeerLost: Apple-Iphone6-1_PT5679.a5FFow==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:17:26.402 ThaliTest[765:60b] client: found peer: Apple-Iphone6-1_PT5679.a5FFow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5679.a5FFow==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:17:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:18:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:18:16.394 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:18:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:18:45.751 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:19:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:19:15.325 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:19:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:19:45.494 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:20:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:20:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:20:57.595 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:20:57.596 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:20:59.921 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
2015-11-25 11:20:59.923 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:21:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:21:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:21:45.324 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:22:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:22:15.416 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:22:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:22:46.864 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:23:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:23:19.366 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:23:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:23:46.621 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:24:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:24:15.992 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:24:26.218 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:24:26.219 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:24:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:25:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:25:18.887 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:25:36.117 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:25:36.118 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:25:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:26:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:26:25.988 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:26:41.610 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:26:41.611 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:26:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:27:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:27:24.713 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:27:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:28:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:28:15.325 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:28:17.045 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:28:17.047 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:28:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:29:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:29:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:30:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:30:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:30:45.324 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:31:00.979 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:31:00.981 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:31:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:31:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:31:49.932 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:32:06.288 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:32:06.289 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:32:07.729 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:32:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:32:15.325 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:32:25.113 ThaliTest[765:60b] client: lost peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:32:25.114 ThaliTest[765:60b] client session: onPeerLost: Apple-IpadAir2-1_PT2339.pNGAWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":false}]
,2015-11-25 11:32:42.328 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
,2015-11-25 11:32:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:33:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:33:15.867 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:33:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:33:46.274 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:34:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:34:15.632 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:34:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:35:15.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:35:16.415 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
,2015-11-25 11:35:45.316 ThaliTest[765:60b] multipeer session: restart
,2015-11-25 11:35:45.786 ThaliTest[765:60b] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==

```
