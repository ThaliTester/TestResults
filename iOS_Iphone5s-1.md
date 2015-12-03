#### Test 525393149f38b37_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C8A296BC-38F1-4642-8D74-58454EE904EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C8A296BC-38F1-4642-8D74-58454EE904EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/006CA424-5FE7-4D55-813A-07DF47A5C0FC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60635"
,(lldb)     command script import "/tmp/C8A296BC-38F1-4642-8D74-58454EE904EE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 16:20:31.270 ThaliTest[2484:2312438] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1A97EA01-97CA-4A21-870B-273A5195A79B/Library/Cookies/Cookies.binarycookies
,2015-12-03 16:20:31.686 ThaliTest[2484:2312438] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 16:20:31.687 ThaliTest[2484:2312438] Multi-tasking -> Device: YES, App: YES
,2015-12-03 16:20:31.696 ThaliTest[2484:2312438] Unlimited access to network resources
,2015-12-03 16:20:31.704 ThaliTest[2484:2312438] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 16:20:35.391 ThaliTest[2484:2312438] Resetting plugins due to page load.
,2015-12-03 16:20:35.844 ThaliTest[2484:2312438] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/006CA424-5FE7-4D55-813A-07DF47A5C0FC/ThaliTest.app/www/index.html
,2015-12-03 16:20:36.001 ThaliTest[2484:2312438] JXcore Cordova plugin initializing
2015-12-03 16:20:36.002 ThaliTest[2484:2312557] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-Iphone5s-1_PT8182
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50620
,2015-12-03 16:26:43.353 ThaliTest[2484:2312557] jxcore: startBroadcasting
,2015-12-03 16:26:43.366 ThaliTest[2484:2312557] server: starting Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:43.368 ThaliTest[2484:2312557] multipeer session: start timer: 0x1a783790
2015-12-03 16:26:43.369 ThaliTest[2484:2312557] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8182
2015-12-03 16:26:43.369 ThaliTest[2484:2312557] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T15:26:43.374Z SendDataTCPServer.js: TCP/IP server is bound to port: 50620
,2015-12-03 16:26:43.903 ThaliTest[2484:2312438] multipeer session: reset timer
2015-12-03 16:26:43.904 ThaliTest[2484:2312438] multipeer session: stop timer
2015-12-03 16:26:43.904 ThaliTest[2484:2312438] multipeer session: start timer: 0x1a783790
2015-12-03 16:26:43.904 ThaliTest[2484:2312438] server session: connect
2015-12-03 16:26:43.905 ThaliTest[2484:2312438] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:26:43.908 ThaliTest[2484:2312438] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:26:44.341 ThaliTest[2484:2312438] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2877.NAxVhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:26:44.351Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:26:44.352Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==,
2015-12-03T15:26:44.352Z SendDataConnector.js: do connect now
2015-12-03 16:26:44.353 ThaliTest[2484:2312557] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:26:44.355 ThaliTest[2484:2312557] client session: connect
2015-12-03 16:26:44.3,57 ThaliTest[2484:2312557] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:44.431 ThaliTest[2484:2312438] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9874.kgLPmg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 16:26:45.866 ThaliTest[2484:2312438] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:46.239 ThaliTest[2484:2313113] server session: connected
2015-12-03 16:26:46.240 ThaliTest[2484:2313113] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:26:46.253 ThaliTest[2484:2312438] server relay: connected (to port: 50620)
,2015-12-03T15:26:46.260Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:46.752Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-03T15:26:46.769Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-12-03T15:26:46.785Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-12-03T15:26:47.179Z SendDataTCPServer.js: TCP/IP server has received 36704 bytes of data
,2015-12-03T15:26:47.196Z SendDataTCPServer.js: TCP/IP server has received 44640 bytes of data
,2015-12-03T15:26:47.213Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
2015-12-03 16:26:47.220 ThaliTest[2484:2312438] multipeer session: reset timer
2015-12-03 16:26:47.221 ThaliTest[2484:2312438] multipeer session: stop timer
20,15-12-03 16:26:47.221 ThaliTest[2484:2312438] multipeer session: start timer: 0x1a783790
2015-12-03 16:26:47.222 ThaliTest[2484:2312438] server session: connect
2015-12-03 16:26:47.223 ThaliTest[2484:2312438] server session: stateChange:0->1 Apple-IpadAi,r2-1_PT2877
2015-12-03T15:26:47.229Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-12-03 16:26:47.263 ThaliTest[2484:2312438] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03T15:26:47.272Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-12-03T15:26:47.298Z SendDataTCPServer.js: TCP/IP server has received 75392 bytes of data
,2015-12-03T15:26:47.313Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-12-03T15:26:47.326Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:47.724 ThaliTest[2484:2313113] client session: connected
2015-12-03 16:26:47.725 ThaliTest[2484:2313113] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:47.733 ThaliTest[2484:2313113] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:26:47.734 ThaliTest[2484:2313113] jxcore: connect: success
2015-12-03T15:26:47.736Z SendDataConnector.js: CLIENT connected, to 50624, error: null
2015-12-03T15:26:47.738Z SendDataConnector.js: CLIENT starting client 
2015-12-03 16:26:47.738 ThaliTest[2484:2313113] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:26:47.745 ThaliTest[2484:2312438] client: relay established
,2015-12-03 16:26:47.746 ThaliTest[2484:2312438] client: new accepted socket: 0x1a6b5470
,2015-12-03T15:26:47.758Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03 16:26:48.005 ThaliTest[2484:2312438] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03T15:26:48.110Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:26:48.297Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T15:26:48.671Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T15:26:48.672Z SendDataConnector.js: got all data for this round
,2015-12-03T15:26:48.675Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:26:48.676Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 16:26:48.678 ThaliTest[2484:2312557] jxcore: disconnect
,2015-12-03 16:26:48.679 ThaliTest[2484:2312557] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:48.679 ThaliTest[2484:2312557] client session: disconnect
,2015-12-03 16:26:48.680 ThaliTest[2484:2312557] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:26:48.686 ThaliTest[2484:2312557] jxcore: disconnect: success
2015-12-03T15:26:48.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:26:48.700Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:26:48.702Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:26:48.703Z SendDataConnector.js: do connect now
,2015-12-03 16:26:48.704 ThaliTest[2484:2312557] jxcore: connect Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:48.706 ThaliTest[2484:2312557] client session: connect
,2015-12-03 16:26:48.707 ThaliTest[2484:2312557] client session: stateChange:0->1 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:50.347 ThaliTest[2484:2313113] server session: connected
2015-12-03 16:26:50.348 ThaliTest[2484:2313113] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:50.360 ThaliTest[2484:2312438] server relay: connected (to port: 50620)
2015-12-03T15:26:50.368Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:50.630Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T15:26:50.647Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-03T15:26:50.668Z SendDataTCPServer.js: TCP/IP server has received 67606 bytes of data
,2015-12-03T15:26:50.685Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-03T15:26:50.700Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:50.852 ThaliTest[2484:2313107] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:51.750 ThaliTest[2484:2313113] client session: connected
2015-12-03 16:26:51.750 ThaliTest[2484:2313113] client session: stateChange:1->2 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:51.758 ThaliTest[2484:2313099] client session: fireConnectCallback: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:26:51.758 ThaliTest[2484:2313099] jxcore: connect: success
2015-12-03T15:26:51.760Z SendDataConnector.js: CLIENT connected ,to 50628, error: null
2015-12-03T15:26:51.761Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:51.765 ThaliTest[2484:2312438] client: relay established
2015-12-03 16:26:51.766 ThaliTest[2484:2312438] client: new accepted socket: 0x1a6c1b50
,2015-12-03T15:26:51.778Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:26:52.215Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T15:26:52.228Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T15:26:52.240Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:26:52.251Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T15:26:52.265Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T15:26:52.265Z SendDataConnector.js: got all data for this round
,2015-12-03T15:26:52.265Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:26:52.266Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 16:26:52.266 ThaliTest[2484:2312557] jxcore: disconnect
2015-12-03 16:26:52.266 ThaliTest[2484:2312557] client session: disconnectFromPeer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:52.266 ThaliTest[2484:2312557] client session: disconnect
2015-12-03 16:26:52.267 ThaliTest[2484:2312557] client session: stateChange:2->0 Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:26:52.268 ThaliTest[2484:2312557] jxcore: disconnect: success
2015-12-03T15:26:52.268Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9874.kgLPmg==
---- round done--------
,device[3]: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:26:52.271Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:26:52.272Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:26:52.272Z SendDataConnector.js: do connect now
,2015-12-03 16:26:52.272 ThaliTest[2484:2312557] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:26:52.273 ThaliTest[2484:2312557] client session: connect
2015-12-03 16:26:52.273 ThaliTest[2484:2312557] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:26:55.048 ThaliTest[2484:2313113] client session: connected
2015-12-03 16:26:55.049 ThaliTest[2484:2313113] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:26:55.052 ThaliTest[2484:2313113] client session: fir,eConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:26:55.053 ThaliTest[2484:2313113] jxcore: connect: success
2015-12-03T15:26:55.054Z SendDataConnector.js: CLIENT connected to 50632, error: null
2015-12-03T15:26:55.055Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:55.060 ThaliTest[2484:2312438] client: relay established
2015-12-03 16:26:55.061 ThaliTest[2484:2312438] client: new accepted socket: 0x1a797ce0
,2015-12-03T15:26:55.072Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:26:55.380Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T15:26:55.393Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T15:26:55.404Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03T15:27:05.405Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:05.406Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:05.407Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:05.408Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:05.409Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:05.411 ThaliTest[2484:2312438] client: socket closed
2015-12-03 16:27:05.412 ThaliTest[2484:2312438] client relay: socket disconnected
2015-12-03 16:27:05.413 ThaliTest[2484:2312438] client relay: 0x1a797ce0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a77fda0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:27:05.413 ThaliTest[2484:2312438] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA,==
2015-12-03 16:27:05.414 ThaliTest[2484:2312438] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:05.414 ThaliTest[2484:2312438] client session: disconnect
2015-12-03 16:27:05.415 ThaliTest[2484:2312438] client session: ,stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:05.416 ThaliTest[2484:2312438] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:10.418Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:10.419Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:15.427 ThaliTest[2484:2312557] jxcore: disconnect
2015-12-03 16:27:15.428 ThaliTest[2484:2312557] jxcore: disconnect: fail
2015-12-03T15:27:15.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:15.430Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
2015-12-03T15:27:15.431Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-1,2-03T15:27:15.431Z SendDataConnector.js: do connect now
,2015-12-03 16:27:15.432 ThaliTest[2484:2312557] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:15.433 ThaliTest[2484:2312557] client session: connect
2015-12-03 16:27:15.434 ThaliTest[2484:2312557] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:17.223 ThaliTest[2484:2312438] multipeer session: restart
,2015-12-03 16:27:17.253 ThaliTest[2484:2312438] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:27:17.254 ThaliTest[2484:2312438] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:27:17.256 ThaliTest[2484:2312438] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:17.259 ThaliTest[2484:2312438] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:27:18.596 ThaliTest[2484:2313179] client session: connected
2015-12-03 16:27:18.597 ThaliTest[2484:2313179] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:18.603 ThaliTest[2484:2313179] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:18.604 ThaliTest[2484:2313179] jxcore: connect: success
,2015-12-03T15:27:18.605Z SendDataConnector.js: CLIENT connected to 50637, error: null
2015-12-03T15:27:18.606Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:18.611 ThaliTest[2484:2312438] client: relay established
2015-12-03 16:27:18.612 ThaliTest[2484:2312438] client: new accepted socket: 0x1a52dc80
,2015-12-03T15:27:18.623Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T15:27:28.689Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:28.691Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:28.691Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:28.692Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:28.693Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:28.694 ThaliTest[2484:2312438] client: socket closed
2015-12-03 16:27:28.695 ThaliTest[2484:2312438] client relay: socket disconnected
2015-12-03 16:27:28.696 ThaliTest[2484:2312438] client relay: 0x1a52dc80 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a42bcf0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:27:28.696 ThaliTest[2484:2312438] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA,==
2015-12-03 16:27:28.697 ThaliTest[2484:2312438] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:28.697 ThaliTest[2484:2312438] client session: disconnect
2015-12-03 16:27:28.698 ThaliTest[2484:2312438] client session: ,stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:28.699 ThaliTest[2484:2312438] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:33.704Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:33.704Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:38.705 ThaliTest[2484:2312557] jxcore: disconnect
2015-12-03 16:27:38.706 ThaliTest[2484:2312557] jxcore: disconnect: fail
2015-12-03T15:27:38.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUU,A==
2015-12-03T15:27:38.707Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
,2015-12-03T15:27:38.707Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:27:38.708Z SendDataConnector.js: do connect now
,2015-12-03 16:27:38.709 ThaliTest[2484:2312557] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:38.710 ThaliTest[2484:2312557] client session: connect
2015-12-03 16:27:38.711 ThaliTest[2484:2312557] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:41.340 ThaliTest[2484:2313401] client session: connected
2015-12-03 16:27:41.341 ThaliTest[2484:2313401] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:41.346 ThaliTest[2484:2313401] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:41.347 ThaliTest[2484:2313401] jxcore: connect: success
,2015-12-03T15:27:41.352Z SendDataConnector.js: CLIENT connected to 50641, error: null
2015-12-03T15:27:41.352Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:41.356 ThaliTest[2484:2312438] client: relay established
2015-12-03 16:27:41.357 ThaliTest[2484:2312438] client: new accepted socket: 0x1a52dc80
,2015-12-03T15:27:41.368Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:27:47.222 ThaliTest[2484:2312438] multipeer session: restart
2015-12-03 16:27:47.228 ThaliTest[2484:2312438] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x905e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 2484 stopped
* thread #1: tid = 0x2348f6, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x2348f6, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000905e2 ThaliTest`main + 50

```
