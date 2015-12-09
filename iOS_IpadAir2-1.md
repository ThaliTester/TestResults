#### Test 5319156460e1811_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A2123C96-16D7-4BC3-A768-420CFD28C1C7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A2123C96-16D7-4BC3-A768-420CFD28C1C7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A381665-CDB4-4182-BB7A-6568924D09C0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52736"
,(lldb)     command script import "/tmp/A2123C96-16D7-4BC3-A768-420CFD28C1C7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 00:12:38.857 ThaliTest[660:479295] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B642D4C8-7947-4F7C-B4AC-A55F4A75B0FD/Library/Cookies/Cookies.binarycookies
,2015-12-10 00:12:38.871 ThaliTest[660:479295] <CATransformLayer: 0xa13090> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 00:12:38.872 ThaliTest[660:479295] <CATransformLayer: 0xa16dc0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-10 00:12:38.873 ThaliTest[660:479295] <CATransformLayer: 0x92c6a0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-10 00:12:39.197 ThaliTest[660:479295] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 00:12:39.198 ThaliTest[660:479295] Multi-tasking -> Device: YES, App: YES
,2015-12-10 00:12:39.206 ThaliTest[660:479295] Unlimited access to network resources
,2015-12-10 00:12:39.212 ThaliTest[660:479295] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 00:12:48.306 ThaliTest[660:479295] Resetting plugins due to page load.
,2015-12-10 00:12:51.319 ThaliTest[660:479295] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A381665-CDB4-4182-BB7A-6568924D09C0/ThaliTest.app/www/index.html
,2015-12-10 00:12:51.455 ThaliTest[660:479295] JXcore Cordova plugin initializing
,2015-12-10 00:12:51.456 ThaliTest[660:479567] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT6044
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 53295
,2015-12-10 00:19:37.490 ThaliTest[660:479567] jxcore: startBroadcasting
,2015-12-10 00:19:37.506 ThaliTest[660:479567] server: starting Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:19:37.508 ThaliTest[660:479567] multipeer session: start timer: 0x8d94c20
2015-12-10 00:19:37.508 ThaliTest[660:479567] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:37.510 ThaliTest[660:479567] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-09T23:19:37.513Z SendDataTCPServer.js: TCP/IP server is bound to port: 53295
,2015-12-10 00:19:38.542 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5811.hStH7w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:19:38.548Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:19:38.549Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:19:38.550Z SendDataConnector.js: do connect now
,2015-12-10 00:19:38.550 ThaliTest[660:479567] jxcore: connect Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:38.551 ThaliTest[660:479567] client session: connect
2015-12-10 00:19:38.552 ThaliTest[660:479567] client session: stateChange:0->1 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:39.150 ThaliTest[660:479295] multipeer session: reset timer
,2015-12-10 00:19:39.150 ThaliTest[660:479295] multipeer session: stop timer
2015-12-10 00:19:39.151 ThaliTest[660:479295] multipeer session: start timer: 0x8d94c20
,2015-12-10 00:19:39.151 ThaliTest[660:479295] server session: connect
2015-12-10 00:19:39.151 ThaliTest[660:479295] server session: stateChange:0->1 Apple-Iphone6-1_PT5811
,2015-12-10 00:19:39.158 ThaliTest[660:479295] server: accepting invitation Apple-Iphone6-1_PT5811
,2015-12-10 00:19:40.907 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9815.s7QXZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:41.239 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1537.Uf7bCw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-10 00:19:41.895 ThaliTest[660:480293] server session: connected
,2015-12-10 00:19:41.895 ThaliTest[660:480293] server session: stateChange:1->2 Apple-Iphone6-1_PT5811
,2015-12-10 00:19:41.903 ThaliTest[660:479295] server relay: connected (to port: 53295)
,2015-12-09T23:19:41.906Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:42.212Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T23:19:42.227Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T23:19:42.244Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T23:19:42.307Z SendDataTCPServer.js: TCP/IP server has received 65558 bytes of data
,2015-12-09T23:19:42.323Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-09T23:19:42.337Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-09T23:19:42.353Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-09T23:19:42.366Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:42.477 ThaliTest[660:480328] server session: not connected Apple-Iphone6-1_PT5811
,2015-12-10 00:19:42.498 ThaliTest[660:480328] client session: connected
2015-12-10 00:19:42.499 ThaliTest[660:480328] client session: stateChange:1->2 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:42.503 ThaliTest[660:480283] client session: fireConnectCallback: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:42.503 ThaliTest[660:480283] jxcore: connect: success
2015-12-09T23:19:42.505Z SendDataConnector.js: CLIENT connected to 53299, error: null
,2015-12-09T23:19:42.506Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:42.509 ThaliTest[660:479295] client: relay established
2015-12-10 00:19:42.509 ThaliTest[660:479295] client: new accepted socket: 0x8daf740
,2015-12-09T23:19:42.526Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:42.912Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-09T23:19:42.913Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:42.914Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:19:42.914Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:42.916 ThaliTest[660:479567] jxcore: disconnect
,2015-12-10 00:19:42.916 ThaliTest[660:479567] client session: disconnectFromPeer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:42.916 ThaliTest[660:479567] client session: disconnect
2015-12-10 00:19:42.916 ThaliTest[660:479567] client session: stateChange:2->0 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:42.921 ThaliTest[660:479567] jxcore: disconnect: success
2015-12-09T23:19:42.922Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5811.hStH7w==
,---- round done--------
device[2]: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-09T23:19:42.923Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-09T23:19:42.924Z SendDataConnector.js: doConnect called with peer Apple-Ipho,ne5-1_PT9815.s7QXZQ==
2015-12-09T23:19:42.924Z SendDataConnector.js: do connect now
2015-12-10 00:19:42.924 ThaliTest[660:479567] jxcore: connect Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:42.924 ThaliTest[660:479567] client session: connect
2015-12-10 00:19:42.924 ThaliTest[660:479567] client session: stateChange:0->1 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:44.588 ThaliTest[660:479295] multipeer session: reset timer
,2015-12-10 00:19:44.588 ThaliTest[660:479295] multipeer session: stop timer
,2015-12-10 00:19:44.588 ThaliTest[660:479295] multipeer session: start timer: 0x8d94c20
,2015-12-10 00:19:44.589 ThaliTest[660:479295] server session: connect
,2015-12-10 00:19:44.589 ThaliTest[660:479295] server session: stateChange:0->1 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:44.596 ThaliTest[660:479295] server: accepting invitation Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:47.724 ThaliTest[660:480292] server session: connected
2015-12-10 00:19:47.724 ThaliTest[660:480292] server session: stateChange:1->2 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:47.753 ThaliTest[660:479295] server relay: connected (to port: 53295)
,2015-12-09T23:19:47.758Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:48.507Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T23:19:48.523Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-09T23:19:48.575Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-09T23:19:48.591Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:48.640 ThaliTest[660:480292] server session: not connected Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:57.555 ThaliTest[660:480283] client session: connected
2015-12-10 00:19:57.555 ThaliTest[660:480283] client session: stateChange:1->2 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:57.599 ThaliTest[660:480358] client session: fireConnectCallback: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:57.600 ThaliTest[660:480358] jxcore: connect: success
,2015-12-09T23:19:57.600Z SendDataConnector.js: CLIENT connected to 53303, error: null
2015-12-09T23:19:57.601Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:19:57.604 ThaliTest[660:479295] client: relay established
2015-12-10 00:19:57.604 ThaliTest[660:479295] client: new accepted socket: 0x8f5d8a0
,2015-12-09T23:19:57.618Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:19:58.012Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T23:19:58.170Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T23:19:58.210Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:19:58.210Z SendDataConnector.js: got all data for this round
,2015-12-09T23:19:58.213Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:19:58.213Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:19:58.215 ThaliTest[660:479567] jxcore: disconnect
,2015-12-10 00:19:58.215 ThaliTest[660:479567] client session: disconnectFromPeer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:58.216 ThaliTest[660:479567] client session: disconnect
,2015-12-10 00:19:58.216 ThaliTest[660:479567] client session: stateChange:2->0 Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:19:58.300 ThaliTest[660:479567] jxcore: disconnect: success
,2015-12-09T23:19:58.301Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9815.s7QXZQ==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:58.303Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:58.303Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-09T23:19:58.304Z SendDataConnector.js: do connect now
,2015-12-10 00:19:58.304 ThaliTest[660:479567] jxcore: connect Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:19:58.305 ThaliTest[660:479567] client session: connect
,2015-12-10 00:19:58.306 ThaliTest[660:479567] client session: stateChange:0->1 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:20:13.215 ThaliTest[660:480418] client session: connected
2015-12-10 00:20:13.216 ThaliTest[660:480418] client session: stateChange:1->2 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:20:13.273 ThaliTest[660:480418] client session: fireConnectCallback: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:20:13.273 ThaliTest[660:480418] jxcore: connect: success
,2015-12-09T23:20:13.274Z SendDataConnector.js: CLIENT connected to 53306, error: null
,2015-12-09T23:20:13.275Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:20:13.278 ThaliTest[660:479295] client: relay established
2015-12-10 00:20:13.278 ThaliTest[660:479295] client: new accepted socket: 0xbdbc90
,2015-12-09T23:20:13.292Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:20:13.743Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T23:20:13.804Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-09T23:20:14.207Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-09T23:20:14.258Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:20:14.259Z SendDataConnector.js: got all data for this round
,2015-12-09T23:20:14.260Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:20:14.261Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:20:14.263 ThaliTest[660:479567] jxcore: disconnect
,2015-12-10 00:20:14.263 ThaliTest[660:479567] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:20:14.264 ThaliTest[660:479567] client session: disconnect
,2015-12-10 00:20:14.264 ThaliTest[660:479567] client session: stateChange:2->0 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:20:14.336 ThaliTest[660:479567] jxcore: disconnect: success
2015-12-09T23:20:14.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT6044","time":36865,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5811.hStH7w==","time":4364,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT9815.s7QXZQ==","time":15287,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT1537.Uf7bCw==","time":15956,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":10,0000}]}
,sendList : 100% : 15956 ms, 99% : 15956 ms, 95 : 15956 ms, 90% : 15956 ms.
,Result count 3, range 4364 ms to  15956 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-09T23:20:14.349Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T23:20:14.349Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:20:14.590 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:20:14.619 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:14.619 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:20:14.620 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:20:44.590 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:20:44.621 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:20:44.621 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:44.622 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:14.590 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:21:14.617 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:21:14.618 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:21:14.619 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:44.590 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:21:44.618 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:44.618 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:21:44.619 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:14.590 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:22:14.618 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:22:14.619 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:22:14.619 ThaliTest[660:479295] client: foun,d peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:34.768 ThaliTest[660:479295] multipeer session: reset timer
,2015-12-10 00:22:34.769 ThaliTest[660:479295] multipeer session: stop timer
2015-12-10 00:22:34.769 ThaliTest[660:479295] multipeer session: start timer: 0x8d94c20
,2015-12-10 00:22:34.769 ThaliTest[660:479295] server session: connect
,2015-12-10 00:22:34.770 ThaliTest[660:479295] server session: stateChange:0->1 Apple-Iphone5-1_PT9815
,2015-12-10 00:22:34.776 ThaliTest[660:479295] server: accepting invitation Apple-Iphone5-1_PT9815
,2015-12-10 00:22:37.571 ThaliTest[660:480889] server session: connected
2015-12-10 00:22:37.571 ThaliTest[660:480889] server session: stateChange:1->2 Apple-Iphone5-1_PT9815
,2015-12-10 00:22:37.577 ThaliTest[660:479295] server relay: connected (to port: 53295)
2015-12-09T23:22:37.577Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:22:38.127Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T23:22:38.140Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-09T23:22:38.533Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T23:22:38.658Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T23:22:38.674Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:22:39.007 ThaliTest[660:480779] server session: not connected Apple-Iphone5-1_PT9815
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-10 00:23:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:23:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:23:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:23:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:23:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:23:34.801 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:23:34.802 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:23:34.803 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:24:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:24:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:24:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:24:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:24:34.770 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:24:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:24:34.799 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:24:34.799 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:25:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:25:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:25:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:25:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:25:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:25:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:25:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:25:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:26:04.770 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:26:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:26:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,2015-12-10 00:26:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:26:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:26:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:26:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:26:34.799 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:27:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:27:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:27:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:27:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:27:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:27:34.800 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:27:34.801 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:27:34.801 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:28:04.770 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:28:04.791 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:28:04.791 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:28:04.791 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-10 00:28:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:28:34.831 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:28:34.832 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:28:34.832 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:29:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:29:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:29:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:29:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:29:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:29:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:29:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:29:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:30:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:30:04.799 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:30:04.799 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:30:04.799 ThaliTest[660:479295] client: fou,nd peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:30:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:30:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:30:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:30:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:31:04.770 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:31:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:31:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:31:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:31:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:31:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:31:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:31:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:32:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:32:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:32:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:32:04.797 ThaliTest[660:479295] client: foun,d peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:32:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:32:34.897 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:32:34.897 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:32:34.897 ThaliTest[660:479295] client: fou,nd peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:33:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:33:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:33:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:33:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:33:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:33:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:33:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:33:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:34:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:34:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:34:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:34:04.799 ThaliTest[660:479295] client: fou,nd peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:34:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:34:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:34:34.799 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:34:34.799 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:35:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:35:04.806 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:35:04.807 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:35:04.807 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:35:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:35:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:35:34.797 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:35:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:36:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:36:04.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:36:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:36:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:36:34.770 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:36:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:36:34.796 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:36:34.796 ThaliTest[660:479295] client: foun,d peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:37:04.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:37:04.797 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:37:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:37:04.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:37:34.771 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:37:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:37:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:37:34.798 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:38:04.771 ThaliTest[660:479295] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:38:34.755 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:38:34.782 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:38:34.782 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:38:34.783 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:39:04.755 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:39:04.778 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:04.779 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:39:04.780 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:39:34.755 ThaliTest[660:479295] multipeer session: restart
,2015-12-10 00:39:34.781 ThaliTest[660:479295] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:34.781 ThaliTest[660:479295] client: found peer: Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:39:34.781 ThaliTest[660:479295] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
