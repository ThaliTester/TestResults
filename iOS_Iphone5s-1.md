#### Test 531915643820a6d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/1EB6E879-968D-43FF-8E00-690FA78319D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1EB6E879-968D-43FF-8E00-690FA78319D9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/65910513-B81C-4B43-8D33-D050A00897AA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53836"
,(lldb)     command script import "/tmp/1EB6E879-968D-43FF-8E00-690FA78319D9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 01:48:24.358 ThaliTest[737:641241] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9B785831-E791-4F3D-B8A7-42BF56B716A3/Library/Cookies/Cookies.binarycookies
,2015-12-11 01:48:24.820 ThaliTest[737:641241] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 01:48:24.822 ThaliTest[737:641241] Multi-tasking -> Device: YES, App: YES
,2015-12-11 01:48:24.831 ThaliTest[737:641241] Unlimited access to network resources
,2015-12-11 01:48:24.843 ThaliTest[737:641241] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 01:48:34.127 ThaliTest[737:641241] Resetting plugins due to page load.
,2015-12-11 01:48:38.186 ThaliTest[737:641241] Finished load of: file:///var/mobile/Containers/Bundle/Application/65910513-B81C-4B43-8D33-D050A00897AA/ThaliTest.app/www/index.html
,2015-12-11 01:48:38.389 ThaliTest[737:641241] JXcore Cordova plugin initializing
,2015-12-11 01:48:38.391 ThaliTest[737:641465] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT7285
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 56260
,2015-12-11 01:55:27.359 ThaliTest[737:641465] jxcore: startBroadcasting
,2015-12-11 01:55:27.382 ThaliTest[737:641465] server: starting Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:27.383 ThaliTest[737:641465] multipeer session: start timer: 0x16e7d3a0
,2015-12-11 01:55:27.384 ThaliTest[737:641465] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:27.385 ThaliTest[737:641465] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-11T00:55:27.388Z SendDataTCPServer.js: TCP/IP server is bound to port: 56260
,2015-12-11 01:55:27.972 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11T00:55:27.981Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11T00:55:27.982Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11T00:55:27.982Z SendDataConnector.js: do connect now
,2015-12-11 01:55:27.983 ThaliTest[737:641465] jxcore: connect Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:27.985 ThaliTest[737:641465] client session: connect
2015-12-11 01:55:27.985 ThaliTest[737:641465] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:28.036 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:28.503 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:34.106 ThaliTest[737:642171] client session: connected
2015-12-11 01:55:34.107 ThaliTest[737:642171] client session: stateChange:1->2 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:34.118 ThaliTest[737:642171] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:34.118 ThaliTest[737:642171] jxcore: connect: success
,2015-12-11T00:55:34.120Z SendDataConnector.js: CLIENT connected to 56263, error: null
2015-12-11T00:55:34.121Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:34.125 ThaliTest[737:641241] client: relay established
2015-12-11 01:55:34.125 ThaliTest[737:641241] client: new accepted socket: 0x16f426b0
,2015-12-11T00:55:34.145Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:35.211Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T00:55:35.225Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T00:55:35.240Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T00:55:35.240Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:35.244Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:55:35.245Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:35.247 ThaliTest[737:641465] jxcore: disconnect
2015-12-11 01:55:35.248 ThaliTest[737:641465] client session: disconnectFromPeer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:35.248 ThaliTest[737:641465] client session: disconnect
2,015-12-11 01:55:35.249 ThaliTest[737:641465] client session: stateChange:2->0 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:35.352 ThaliTest[737:641465] jxcore: disconnect: success
,2015-12-11T00:55:35.355Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.MPIGmg==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:35.362Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:35.363Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:35.366Z SendDataConnector.js: do connect now
,2015-12-11 01:55:35.368 ThaliTest[737:641465] jxcore: connect Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:35.370 ThaliTest[737:641465] client session: connect
,2015-12-11 01:55:35.373 ThaliTest[737:641465] client session: stateChange:0->1 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:38.853 ThaliTest[737:641241] multipeer session: reset timer
2015-12-11 01:55:38.853 ThaliTest[737:641241] multipeer session: stop timer
2015-12-11 01:55:38.853 ThaliTest[737:641241] multipeer session: start timer: 0x16e7d3a0
2015-12-11 ,01:55:38.854 ThaliTest[737:641241] server session: connect
2015-12-11 01:55:38.855 ThaliTest[737:641241] server session: stateChange:0->1 Apple-Iphone6-1_PT9748
,2015-12-11 01:55:38.867 ThaliTest[737:641241] server: accepting invitation Apple-Iphone6-1_PT9748
,2015-12-11 01:55:39.083 ThaliTest[737:642182] client session: connected
2015-12-11 01:55:39.083 ThaliTest[737:642182] client session: stateChange:1->2 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:39.102 ThaliTest[737:642171] client session: fireConnectCallback: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:39.103 ThaliTest[737:642171] jxcore: connect: success
2015-12-11T00:55:39.103Z SendDataConnector.js: CLIENT connected to 5,6266, error: null
2015-12-11T00:55:39.104Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:39.107 ThaliTest[737:641241] client: relay established
2015-12-11 01:55:39.107 ThaliTest[737:641241] client: new accepted socket: 0x16e93a70
,2015-12-11T00:55:39.118Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:39.501Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T00:55:39.563Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T00:55:39.589Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T00:55:39.628Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T00:55:39.938Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T00:55:39.939Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:39.941Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:55:39.942Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:39.944 ThaliTest[737:641465] jxcore: disconnect
,2015-12-11 01:55:39.946 ThaliTest[737:641465] client session: disconnectFromPeer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:39.948 ThaliTest[737:641465] client session: disconnect
,2015-12-11 01:55:39.949 ThaliTest[737:641465] client session: stateChange:2->0 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:40.059 ThaliTest[737:641465] jxcore: disconnect: success
,2015-12-11T00:55:40.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9748.JvjfiA==
,---- round done--------
,device[3]: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:55:40.067Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:55:40.070Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:55:40.071Z SendDataConnector.js: do connect now
,2015-12-11 01:55:40.072 ThaliTest[737:641465] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:40.074 ThaliTest[737:641465] client session: connect
,2015-12-11 01:55:40.075 ThaliTest[737:641465] client session: stateChange:0->1 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:40.548 ThaliTest[737:641241] multipeer session: reset timer
,2015-12-11 01:55:40.549 ThaliTest[737:641241] multipeer session: stop timer
2015-12-11 01:55:40.549 ThaliTest[737:641241] multipeer session: start timer: 0x16e7d3a0
,2015-12-11 01:55:40.550 ThaliTest[737:641241] server session: connect
,2015-12-11 01:55:40.551 ThaliTest[737:641241] server session: stateChange:0->1 Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:40.563 ThaliTest[737:641241] server: accepting invitation Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:40.652 ThaliTest[737:641241] multipeer session: reset timer
2015-12-11 01:55:40.652 ThaliTest[737:641241] multipeer session: stop timer
,2015-12-11 01:55:40.653 ThaliTest[737:641241] multipeer session: start timer: 0x16e7d3a0
,2015-12-11 01:55:40.653 ThaliTest[737:641241] server session: connect
,2015-12-11 01:55:40.654 ThaliTest[737:641241] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
,2015-12-11 01:55:40.664 ThaliTest[737:641241] server: accepting invitation Apple-Iphone5-1_PT4192
,2015-12-11 01:55:42.693 ThaliTest[737:642244] server session: connected
,2015-12-11 01:55:42.694 ThaliTest[737:642244] server session: stateChange:1->2 Apple-Iphone6-1_PT9748
,2015-12-11 01:55:42.766 ThaliTest[737:641241] server relay: connected (to port: 56260)
,2015-12-11T00:55:42.775Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 01:55:43.834 ThaliTest[737:642181] client session: connected
2015-12-11 01:55:43.835 ThaliTest[737:642181] client session: stateChange:1->2 Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:43.838 ThaliTest[737:642181] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:43.838 ThaliTest[737:642181] jxcore: connect: success
2015-12-11T00:55:43.840Z SendDataConnector.js: CLIENT connected to 56270, error: null
2015-12-11T00:55:43.840Z SendDataConnector.js: CLI,ENT starting client 
2015-12-11 01:55:43.844 ThaliTest[737:641241] client: relay established
2015-12-11 01:55:43.844 ThaliTest[737:641241] client: new accepted socket: 0x16e76770
,2015-12-11T00:55:43.857Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 01:55:44.259 ThaliTest[737:642180] server session: connected
2015-12-11 01:55:44.259 ThaliTest[737:642180] server session: stateChange:1->2 Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:44.300 ThaliTest[737:641241] server relay: connected (to port: 56260)
,2015-12-11T00:55:44.308Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:44.458Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-11T00:55:44.471Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T00:55:44.507Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-11T00:55:44.521Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T00:55:44.536Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11T00:55:44.850Z SendDataConnector.js: CLIENT is data received : 20000
,appEnteredForeground wasn't registered
,2015-12-11 01:55:51.306 ThaliTest[737:642181] server session: not connected Apple-Iphone5-1_PT4192
,2015-12-11T00:55:54.861Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T00:55:54.862Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T00:55:54.864Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T00:55:54.864Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T00:55:54.865Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 01:55:54.867 ThaliTest[737:641241] client: socket closed
2015-12-11 01:55:54.867 ThaliTest[737:641241] client relay: socket disconnected
2015-12-11 01:55:54.868 ThaliTest[737:641241] client relay: 0x16e76770 disconnected with error Error Domai,n=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 01:55:54.868 ThaliTest[737:641241] client session: socket closed: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:,55:54.868 ThaliTest[737:641241] client session: onLinkFailure: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:54.869 ThaliTest[737:641241] client session: disconnect
2015-12-11 01:55:54.869 ThaliTest[737:641241] client session: stateChange:2->0 Apple-,IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:54.874 ThaliTest[737:641241] client session: fireConnectionErrorEvent: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:58.951 ThaliTest[737:642172] server session: not connected Apple-Iphone6-1_PT9748
,2015-12-11T00:55:59.871Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:55:59.872Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:02.137 ThaliTest[737:641241] multipeer session: reset timer
2015-12-11 01:56:02.137 ThaliTest[737:641241] multipeer session: stop timer
2015-12-11 01:56:02.137 ThaliTest[737:641241] multipeer session: start timer: 0x16e7d3a0
2015-12-11 ,01:56:02.138 ThaliTest[737:641241] server: disconnecting to refresh session (Apple-Iphone5-1_PT4192)
2015-12-11 01:56:02.138 ThaliTest[737:641241] server session: disconnect
2015-12-11 01:56:02.138 ThaliTest[737:641241] server session: stateChange:1->0 A,pple-Iphone5-1_PT4192
,2015-12-11 01:56:02.192 ThaliTest[737:641241] server session: connect
2015-12-11 01:56:02.192 ThaliTest[737:641241] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
2015-12-11 01:56:02.201 ThaliTest[737:641241] server: accepting invitation Apple-Iphone5-1_PT4192
,2015-12-11 01:56:04.883 ThaliTest[737:641465] jxcore: disconnect
2015-12-11 01:56:04.883 ThaliTest[737:641465] jxcore: disconnect: fail
2015-12-11T00:56:04.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==,
2015-12-11T00:56:04.885Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT8618.Ut+byw== with availability status: true
,2015-12-11T00:56:04.885Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11T00:56:04.885Z SendDataConnector.js: do connect now
,2015-12-11 01:56:04.886 ThaliTest[737:641465] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:04.887 ThaliTest[737:641465] client session: connect
,2015-12-11 01:56:04.888 ThaliTest[737:641465] client session: stateChange:0->1 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:05.056 ThaliTest[737:642244] server session: connected
2015-12-11 01:56:05.057 ThaliTest[737:642244] server session: stateChange:1->2 Apple-Iphone5-1_PT4192
,2015-12-11 01:56:05.065 ThaliTest[737:641241] server relay: connected (to port: 56260)
2015-12-11T00:56:05.073Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:56:05.567Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T00:56:05.587Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T00:56:05.605Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-11T00:56:05.619Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-11 01:56:05.863 ThaliTest[737:642244] server session: not connected Apple-IpadAir2-1_PT8618
,2015-12-11T00:56:06.094Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:56:06.100 ThaliTest[737:641241] client: lost peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:56:06.100 ThaliTest[737:641241] client session: onPeerLost: Apple-Iphone6-1_PT9748.JvjfiA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:56:06.589 ThaliTest[737:642244] server session: not connected Apple-Iphone5-1_PT4192
,2015-12-11 01:56:17.261 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 01:56:32.139 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:56:37.892 ThaliTest[737:642514] client session: not connected Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:37.893 ThaliTest[737:642514] client session: onLinkFailure: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:37.894 ThaliTest[7,37:642514] client session: disconnect
2015-12-11 01:56:37.894 ThaliTest[737:642514] client session: stateChange:1->0 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:37.901 ThaliTest[737:642514] client session: fireConnectCallback: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:37.902 ThaliTest[737:642514] jxcore: connect: fail: Peer disconnected
2015-12-11T00:56:37.903Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-11T00:56:37.904Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T00:56:37.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T00:56:42.914Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:56:42.915Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:46.139 ThaliTest[737:641241] multipeer session: reset timer
,2015-12-11 01:56:46.139 ThaliTest[737:641241] multipeer session: stop timer
2015-12-11 01:56:46.142 ThaliTest[737:641241] multipeer session: start timer: 0x16e7d3a0
2015-12-11 01:56:46.143 ThaliTest[737:641241] server: disconnecting to refresh session (A,pple-Iphone6-1_PT9748)
2015-12-11 01:56:46.144 ThaliTest[737:641241] server session: disconnect
2015-12-11 01:56:46.144 ThaliTest[737:641241] server session: stateChange:2->0 Apple-Iphone6-1_PT9748
,2015-12-11 01:56:46.149 ThaliTest[737:641241] server session: connect
2015-12-11 01:56:46.149 ThaliTest[737:641241] server session: stateChange:0->1 Apple-Iphone6-1_PT9748
,2015-12-11T00:56:46.163Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11 01:56:46.166 ThaliTest[737:641241] server: accepting invitation Apple-Iphone6-1_PT9748
,2015-12-11 01:56:47.919 ThaliTest[737:641465] jxcore: disconnect
2015-12-11 01:56:47.920 ThaliTest[737:641465] jxcore: disconnect: fail
2015-12-11T00:56:47.920Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==,
2015-12-11T00:56:47.921Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT8618.Ut+byw== with availability status: true
2015-12-11T00:56:47.921Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
20,15-12-11T00:56:47.922Z SendDataConnector.js: do connect now
,2015-12-11 01:56:47.923 ThaliTest[737:641465] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:47.923 ThaliTest[737:641465] client session: connect
,2015-12-11 01:56:47.924 ThaliTest[737:641465] client session: stateChange:0->1 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:47.936 ThaliTest[737:641241] client: lost peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:47.937 ThaliTest[737:641241] client session: onPeerLost: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:47.937 ThaliTest[737:641241] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:47.937 ThaliTest[737:641241] client session: disconnect
2015-12-11 01:56:47.938 ThaliTest[737:641241] client session: stateChange:1->0 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:47.994 ThaliTest[737:641241] client session: fireConnectCallback: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:47.995 ThaliTest[737:641241] jxcore: connect: fail: Peer disconnected
2015-12-11T00:56:47.996Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-11T00:56:47.996Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T00:56:47.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:56:48.710 ThaliTest[737:642533] server session: connected
2015-12-11 01:56:48.710 ThaliTest[737:642533] server session: stateChange:1->2 Apple-Iphone6-1_PT9748
,2015-12-11 01:56:48.733 ThaliTest[737:641241] server relay: connected (to port: 56260)
,2015-12-11T00:56:48.742Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:56:48.980Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-11T00:56:48.994Z SendDataTCPServer.js: TCP/IP server has received 19568 bytes of data
,2015-12-11T00:56:49.010Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-11T00:56:49.029Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T00:56:49.046Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-11T00:56:49.062Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:56:49.251 ThaliTest[737:642517] server session: not connected Apple-Iphone6-1_PT9748
,2015-12-11T00:56:53.002Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:56:53.002Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:58.006 ThaliTest[737:641465] jxcore: disconnect
2015-12-11 01:56:58.007 ThaliTest[737:641465] jxcore: disconnect: fail
2015-12-11T00:56:58.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==,
2015-12-11T00:56:58.008Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT8618.Ut+byw== with availability status: true
2015-12-11T00:56:58.008Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:56:58.008Z SendDataConnector.js: do connect now
2015-12-11 01:56:58.009 ThaliTest[737:641465] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:58.010 ThaliTest[737:641465] client: connect: unreachable Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:56:58.011 ThaliTest[737:641465] jxcore: connect: fail: Peer unreachable
,2015-12-11T00:56:58.013Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T00:56:58.013Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-11T00:56:58.013Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11T00:57:03.015Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:57:03.016Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 01:57:08.025 ThaliTest[737:641465] jxcore: disconnect
2015-12-11 01:57:08.026 ThaliTest[737:641465] jxcore: disconnect: fail
2015-12-11T00:57:08.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==,
2015-12-11T00:57:08.027Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT8618.Ut+byw== with availability status: true
2015-12-11T00:57:08.027Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
20,15-12-11T00:57:08.027Z SendDataConnector.js: do connect now
,2015-12-11 01:57:08.028 ThaliTest[737:641465] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:57:08.029 ThaliTest[737:641465] client: connect: unreachable Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:57:08.029 ThaliTest[737:641465] jxcor,e: connect: fail: Peer unreachable
,2015-12-11T00:57:08.030Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T00:57:08.031Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T00:57:08.034Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:57:08.034Z SendDataConnector.js: Stop data retrieving timer
,2015-12-11 01:57:08.035 ThaliTest[737:641465] jxcore: disconnect
,2015-12-11 01:57:08.036 ThaliTest[737:641465] jxcore: disconnect: fail
,2015-12-11T00:57:08.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7285","time":100701,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT4192.MPIGmg==","time":7261,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1,_PT9748.JvjfiA==","time":4577,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT8618.Ut+byw==","time":87962,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"da,taReceived":20000}]}
,sendList : 100% : 7261 ms, 99% : 7261 ms, 95 : 7261 ms, 90% : 7261 ms.
,Result count 2, range 4577 ms to  7261 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-IpadAir2-1_PT8618.Ut+byw==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-11T00:57:08.051Z SendDataConnector.js: CLIENT Stop now
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 01:57:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:57:16.198 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:57:16.551 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:16.552 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":true}]
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
,2015-12-11 01:57:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:57:46.206 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:46.207 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:57:46.208 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 01:58:16.143 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:58:16.204 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:58:16.205 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:58:16.209 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 01:58:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:58:46.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:58:46.976 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:58:46.977 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 01:59:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:59:16.201 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:59:16.208 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:59:16.209 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,2015-12-11 01:59:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 01:59:46.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:59:46.203 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:59:46.206 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:00:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:00:16.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:00:16.976 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:00:16.979 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:00:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:00:46.202 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:00:46.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:00:46.212 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:01:16.144 ThaliTest[737:641241] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:01:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:01:46.190 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:01:46.192 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:01:46.192 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:02:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:02:16.207 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:02:16.207 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:02:16.211 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:02:46.143 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:02:46.204 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:02:46.204 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:02:46.205 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:03:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:03:16.208 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:03:16.208 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:03:16.209 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:03:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:03:46.202 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:03:46.203 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:03:46.212 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:04:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:04:16.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:04:16.207 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:04:16.498 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,2015-12-11 02:04:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:04:46.200 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:04:46.928 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:04:46.932 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:05:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:05:16.202 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:16.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:05:16.215 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:05:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:05:46.205 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:05:46.205 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:46.206 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone5-1_PT4192.MPIGmg==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:06:16.144 ThaliTest[737:641241] multipeer session: restart
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
,2015-12-11 02:06:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:06:46.206 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:06:46.206 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:06:46.208 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:07:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:07:16.202 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:07:16.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:07:16.212 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:07:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:07:46.204 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:07:46.205 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:07:46.205 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:08:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:08:16.203 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:08:16.204 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:08:16.205 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:08:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:08:46.209 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:08:46.210 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:08:46.210 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:09:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:09:16.208 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:09:16.209 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:09:16.211 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:09:46.144 ThaliTest[737:641241] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:10:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:10:16.197 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:10:16.198 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:10:16.200 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:10:46.144 ThaliTest[737:641241] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:11:16.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:11:16.204 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:11:16.204 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:11:16.205 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:11:46.144 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:11:46.205 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:11:46.206 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:11:46.216 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:12:16.114 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:12:16.173 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:12:16.174 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:12:16.174 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,2015-12-11 02:12:46.114 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:12:46.150 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:12:46.150 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:12:46.152 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:13:16.114 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:13:16.173 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:13:16.173 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:13:16.179 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:13:46.114 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:13:46.175 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:13:46.175 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:13:46.176 ThaliTest[737:641241] client: fou,nd peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:14:16.114 ThaliTest[737:641241] multipeer session: restart
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
,2015-12-11 02:14:46.114 ThaliTest[737:641241] multipeer session: restart
,2015-12-11 02:14:46.169 ThaliTest[737:641241] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:14:46.174 ThaliTest[737:641241] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:14:46.175 ThaliTest[737:641241] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:15:16.114 ThaliTest[737:641241] multipeer session: restart
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
