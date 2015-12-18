#### Test 539786637913587_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/489193DF-D6AD-40D8-87CE-FA102DA5CCE5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/489193DF-D6AD-40D8-87CE-FA102DA5CCE5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/14ECF18D-EB60-4D8C-9308-F498B8D8FC1A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59915"
,(lldb)     command script import "/tmp/489193DF-D6AD-40D8-87CE-FA102DA5CCE5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 13:45:16.886 ThaliTest[425:354288] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D9B0B80B-3D02-4CAB-A9CB-BC79D90AFA8A/Library/Cookies/Cookies.binarycookies
,2015-12-18 13:45:17.232 ThaliTest[425:354288] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 13:45:17.233 ThaliTest[425:354288] Multi-tasking -> Device: YES, App: YES
,2015-12-18 13:45:17.241 ThaliTest[425:354288] Unlimited access to network resources
,2015-12-18 13:45:17.249 ThaliTest[425:354288] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 13:45:26.416 ThaliTest[425:354288] Resetting plugins due to page load.
,2015-12-18 13:45:29.886 ThaliTest[425:354288] Finished load of: file:///var/mobile/Containers/Bundle/Application/14ECF18D-EB60-4D8C-9308-F498B8D8FC1A/ThaliTest.app/www/index.html
,2015-12-18 13:45:30.050 ThaliTest[425:354288] JXcore Cordova plugin initializing
2015-12-18 13:45:30.051 ThaliTest[425:354501] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT1412
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52227
,2015-12-18 13:53:32.412 ThaliTest[425:354501] jxcore: startBroadcasting
,2015-12-18 13:53:32.430 ThaliTest[425:354501] server: starting Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:53:32.431 ThaliTest[425:354501] multipeer session: start timer: 0x177c6f40
2015-12-18 13:53:32.432 ThaliTest[425:354501] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1412
2015-12-18 13:53:32.433 ThaliTest[425:354501] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
,2015-12-18T12:53:32.437Z SendDataTCPServer.js: TCP/IP server is bound to port: 52227
,2015-12-18 13:53:33.592 ThaliTest[425:354288] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:53:33.599Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:53:33.599Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:53:33.600Z SendDataConnector.js: do connect now
,2015-12-18 13:53:33.601 ThaliTest[425:354501] jxcore: connect Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:33.602 ThaliTest[425:354501] client session: connect
,2015-12-18 13:53:33.603 ThaliTest[425:354501] client session: stateChange:0->1 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:53:33.653 ThaliTest[425:354288] client: found peer: Apple-Iphone5-1_PT724.734x4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT724.734x4g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 13:53:35.127 ThaliTest[425:354288] client: found peer: Apple-Iphone6-1_PT215.JwJUFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT215.JwJUFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:37.334 ThaliTest[425:355645] client session: connected
2015-12-18 13:53:37.335 ThaliTest[425:355645] client session: stateChange:1->2 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:53:37.339 ThaliTest[425:355645] client session: fireConnectCallback: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:37.339 ThaliTest[425:355645] jxcore: connect: success
,2015-12-18T12:53:37.341Z SendDataConnector.js: CLIENT connected to 52230, error: null
2015-12-18T12:53:37.342Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:37.344 ThaliTest[425:354288] client: relay established
2015-12-18 13:53:37.345 ThaliTest[425:354288] client: new accepted socket: 0x197c9fd0
,2015-12-18T12:53:37.360Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 13:53:37.383 ThaliTest[425:354288] multipeer session: reset timer
2015-12-18 13:53:37.384 ThaliTest[425:354288] multipeer session: stop timer
2015-12-18 13:53:37.384 ThaliTest[425:354288] multipeer session: start timer: 0x177c6f40
2015-12-18 13:53:37.384 ThaliTest[425:354288] server session: connect
2015-12-18 13:53:37.385 ThaliTest[425:354288] server session: stateChange:0->1 Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:37.392 ThaliTest[425:354288] server: accepting invitation Apple-Iphone5s-1_PT4751
,2015-12-18T12:53:37.739Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T12:53:37.764Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T12:53:37.838Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T12:53:37.913Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T12:53:37.939Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:53:37.939Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:37.940Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:37.940Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:37.941 ThaliTest[425:354501] jxcore: disconnect
,2015-12-18 13:53:37.942 ThaliTest[425:354501] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:53:37.942 ThaliTest[425:354501] client session: disconnect
,2015-12-18 13:53:37.942 ThaliTest[425:354501] client session: stateChange:2->0 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:53:38.007 ThaliTest[425:354501] jxcore: disconnect: success
,2015-12-18T12:53:38.009Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:38.014Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:38.014Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT724.734x4g==
,2015-12-18T12:53:38.015Z SendDataConnector.js: do connect now
,2015-12-18 13:53:38.016 ThaliTest[425:354501] jxcore: connect Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:38.016 ThaliTest[425:354501] client session: connect
,2015-12-18 13:53:38.017 ThaliTest[425:354501] client session: stateChange:0->1 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:40.898 ThaliTest[425:355645] server session: connected
2015-12-18 13:53:40.898 ThaliTest[425:355645] server session: stateChange:1->2 Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:40.900 ThaliTest[425:354288] server relay: connected (to port: 52227)
,2015-12-18T12:53:40.907Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:41.385Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-18T12:53:41.401Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-18T12:53:41.415Z SendDataTCPServer.js: TCP/IP server has received 87458 bytes of data
,2015-12-18T12:53:41.429Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:41.458 ThaliTest[425:355648] client session: connected
2015-12-18 13:53:41.459 ThaliTest[425:355648] client session: stateChange:1->2 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:41.463 ThaliTest[425:355656] client session: fireConnectCallback: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 13:53:41.463 ThaliTest[425:355656] jxcore: connect: success
,2015-12-18T12:53:41.465Z SendDataConnector.js: CLIENT connected to 52234, error: null
,2015-12-18T12:53:41.465Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:41.468 ThaliTest[425:354288] client: relay established
2015-12-18 13:53:41.468 ThaliTest[425:354288] client: new accepted socket: 0x1a84ae60
,2015-12-18T12:53:41.479Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 13:53:41.498 ThaliTest[425:355646] server session: not connected Apple-Iphone5s-1_PT4751
,2015-12-18T12:53:42.226Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T12:53:42.240Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T12:53:42.241Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:42.242Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:42.243Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:42.244 ThaliTest[425:354501] jxcore: disconnect
,2015-12-18 13:53:42.245 ThaliTest[425:354501] client session: disconnectFromPeer: Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:42.245 ThaliTest[425:354501] client session: disconnect
,2015-12-18 13:53:42.245 ThaliTest[425:354501] client session: stateChange:2->0 Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:53:42.255 ThaliTest[425:354501] jxcore: disconnect: success
2015-12-18T12:53:42.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT724.734x4g==
---- round done--------
,device[3]: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:42.260Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:42.260Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18T12:53:42.260Z SendDataConnector.js: do connect now
2015-12-18 13:53:42.261 ThaliTest[425:354501] jxcore: connect Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:42.261 ThaliTest[425:354501] client session: connect
2015-12-18 13:53:42.261 ThaliTest,[425:354501] client session: stateChange:0->1 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:43.218 ThaliTest[425:354288] multipeer session: reset timer
,2015-12-18 13:53:43.219 ThaliTest[425:354288] multipeer session: stop timer
2015-12-18 13:53:43.219 ThaliTest[425:354288] multipeer session: start timer: 0x177c6f40
2015-12-18 13:53:43.219 ThaliTest[425:354288] server session: connect
2015-12-18 13:53:43.219 ThaliTest[425:354288] server session: stateChange:0->1 Apple-Iphone5-1_PT724
2015-12-18 13:53:43.221 ThaliTest[425:354288] server: accepting invitation Apple-Iphone5-1_PT724
,2015-12-18 13:53:44.955 ThaliTest[425:355759] client session: connected
2015-12-18 13:53:44.956 ThaliTest[425:355759] client session: stateChange:1->2 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:44.960 ThaliTest[425:355759] client session: fireConnectCallback: Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:44.960 ThaliTest[425:355759] jxcore: connect: success
,2015-12-18T12:53:44.961Z SendDataConnector.js: CLIENT connected to 52237, error: null
,2015-12-18T12:53:44.962Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:53:44.964 ThaliTest[425:354288] client: relay established
2015-12-18 13:53:44.965 ThaliTest[425:354288] client: new accepted socket: 0x1a850160
,2015-12-18T12:53:44.978Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 13:53:46.145 ThaliTest[425:355759] server session: connected
2015-12-18 13:53:46.145 ThaliTest[425:355759] server session: stateChange:1->2 Apple-Iphone5-1_PT724
,2015-12-18 13:53:46.150 ThaliTest[425:354288] server relay: connected (to port: 52227)
,2015-12-18T12:53:46.159Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:46.659Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T12:53:46.683Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T12:53:46.686Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T12:53:46.700Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T12:53:46.701Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-18T12:53:46.718Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T12:53:46.732Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T12:53:46.746Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-18T12:53:46.749Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:53:46.750Z SendDataConnector.js: got all data for this round
,2015-12-18T12:53:46.752Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:46.753Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:53:46.754 ThaliTest[425:354501] jxcore: disconnect
2015-12-18 13:53:46.754 ThaliTest[425:354501] client session: disconnectFromPeer: Apple-Iphone6-1_PT215.JwJUFw==
2015-12-18 13:53:46.755 ThaliTest[425:354501] client session: disconnect
2015-12-18 13:53:46.755 ThaliTest[425:354501] client session: stateChange:2->0 Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:46.773 ThaliTest[425:354501] jxcore: disconnect: success
2015-12-18T12:53:46.774Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT215.JwJUFw==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT1412","time":14379,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT4751.qR8AbA==","time":4340,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT724.734x4g==","time":4227,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT215.JwJUFw==","time":4490,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4490 ms, 99% : 4490 ms, 95 : 4490 ms, 90% : 4490 ms.
,Result count 3, range 4227 ms to  4490 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-18T12:53:46.795Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:53:46.796Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18T12:53:46.811Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:46.925 ThaliTest[425:355656] server session: not connected Apple-Iphone5-1_PT724
,2015-12-18 13:54:13.220 ThaliTest[425:354288] multipeer session: restart
,2015-12-18 13:54:13.247 ThaliTest[425:354288] client: found peer: Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:54:13.897 ThaliTest[425:354288] client: found peer: Apple-Iphone5-1_PT724.734x4g==
,2015-12-18 13:54:35.435 ThaliTest[425:354288] multipeer session: reset timer
,2015-12-18 13:54:35.435 ThaliTest[425:354288] multipeer session: stop timer
,2015-12-18 13:54:35.435 ThaliTest[425:354288] multipeer session: start timer: 0x177c6f40
,2015-12-18 13:54:35.436 ThaliTest[425:354288] server session: connect
2015-12-18 13:54:35.436 ThaliTest[425:354288] server session: stateChange:0->1 Apple-Iphone6-1_PT215
,2015-12-18 13:54:35.443 ThaliTest[425:354288] server: accepting invitation Apple-Iphone6-1_PT215
,2015-12-18 13:54:38.397 ThaliTest[425:354288] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:54:38.784 ThaliTest[425:355885] server session: connected
2015-12-18 13:54:38.784 ThaliTest[425:355885] server session: stateChange:1->2 Apple-Iphone6-1_PT215
,2015-12-18 13:54:38.788 ThaliTest[425:354288] server relay: connected (to port: 52227)
,2015-12-18T12:54:38.794Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:54:39.113Z SendDataTCPServer.js: TCP/IP server has received 21758 bytes of data
,2015-12-18T12:54:39.128Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-18T12:54:39.182Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-18T12:54:39.198Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:54:39.251 ThaliTest[425:355886] server session: not connected Apple-Iphone6-1_PT215
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-18 13:54:40.132 ThaliTest[425:354501] jxcore: stopBroadcasting
,2015-12-18 13:54:40.132 ThaliTest[425:354501] THEMultipeerSession stopping peer
,2015-12-18 13:54:40.133 ThaliTest[425:354501] multipeer session: stop timer
,2015-12-18 13:54:40.134 ThaliTest[425:354501] server session: disconnect
2015-12-18 13:54:40.135 ThaliTest[425:354501] server session: stateChange:2->0 Apple-Iphone6-1_PT215
,2015-12-18 13:54:40.144 ThaliTest[425:354501] server session: disconnect
2015-12-18 13:54:40.144 ThaliTest[425:354501] server session: stateChange:2->0 Apple-Iphone5-1_PT724
,2015-12-18 13:54:40.159 ThaliTest[425:354501] server session: disconnect
2015-12-18 13:54:40.160 ThaliTest[425:354501] server session: stateChange:2->0 Apple-Iphone5s-1_PT4751
,2015-12-18 13:54:40.168 ThaliTest[425:354501] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T12:54:40.184Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.186Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.188Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.189Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT724.734x4g==\",\"time\":4227,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{,\"name\":\"Apple-Iphone5s-1_PT4751.qR8AbA==\",\"time\":4340,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone6-1_PT215.JwJUFw==\",\"time\":4490,\"result\":\"OK\",\"connections\":1,\,"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
