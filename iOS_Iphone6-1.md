#### Test 531915643820a6d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/6CC8864B-38B1-4577-AD56-E59A0EAF104A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6CC8864B-38B1-4577-AD56-E59A0EAF104A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AB97257F-37C1-46D4-AF9E-F02728114470/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53833"
,(lldb)     command script import "/tmp/6CC8864B-38B1-4577-AD56-E59A0EAF104A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 01:48:18.347 ThaliTest[733:641014] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7ACB049B-C67C-4881-92D2-DA0FF66D97CE/Library/Cookies/Cookies.binarycookies
,2015-12-11 01:48:18.723 ThaliTest[733:641014] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 01:48:18.725 ThaliTest[733:641014] Multi-tasking -> Device: YES, App: YES
,2015-12-11 01:48:18.736 ThaliTest[733:641014] Unlimited access to network resources
,2015-12-11 01:48:18.748 ThaliTest[733:641014] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 01:48:27.848 ThaliTest[733:641014] Resetting plugins due to page load.
,2015-12-11 01:48:31.343 ThaliTest[733:641014] Finished load of: file:///var/mobile/Containers/Bundle/Application/AB97257F-37C1-46D4-AF9E-F02728114470/ThaliTest.app/www/index.html
,2015-12-11 01:48:31.525 ThaliTest[733:641014] JXcore Cordova plugin initializing
2015-12-11 01:48:31.527 ThaliTest[733:641224] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT9748
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 56117
,2015-12-11 01:55:25.678 ThaliTest[733:641224] jxcore: startBroadcasting
,2015-12-11 01:55:25.699 ThaliTest[733:641224] server: starting Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:25.700 ThaliTest[733:641224] multipeer session: start timer: 0x18ed0110
2015-12-11 01:55:25.701 ThaliTest[733:641224] THEMultipeerSession init,ialized peer Apple-Iphone6-1_PT9748
2015-12-11 01:55:25.701 ThaliTest[733:641224] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-11T00:55:25.703Z SendDataTCPServer.js: TCP/IP server is bound to port: 56117
,2015-12-11 01:55:27.596 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
device[1]: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11T00:55:27.602Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11T00:55:27.603Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11T00:55:27.603Z SendDataConnector.js: do connect now
,2015-12-11 01:55:27.604 ThaliTest[733:641224] jxcore: connect Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:27.604 ThaliTest[733:641224] client session: connect
2015-12-11 01:55:27.606 ThaliTest[733:641224] client session: stateChange:0->1 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:30.431 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:30.468 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7285.LNATEw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:31.056 ThaliTest[733:641014] multipeer session: reset timer
2015-12-11 01:55:31.056 ThaliTest[733:641014] multipeer session: stop timer
2015-12-11 01:55:31.056 ThaliTest[733:641014] multipeer session: start timer: 0x18ed0110
2015-12-11 ,01:55:31.057 ThaliTest[733:641014] server session: connect
2015-12-11 01:55:31.057 ThaliTest[733:641014] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
,2015-12-11 01:55:31.067 ThaliTest[733:641014] server: accepting invitation Apple-Iphone5-1_PT4192
,2015-12-11 01:55:31.115 ThaliTest[733:641014] multipeer session: reset timer
2015-12-11 01:55:31.115 ThaliTest[733:641014] multipeer session: stop timer
2015-12-11 01:55:31.115 ThaliTest[733:641014] multipeer session: start timer: 0x18ed0110
2015-12-11 01:55:31.115 ThaliTest[733:641014] server session: connect
2015-12-11 01:55:31.115 ThaliTest[733:641014] server session: stateChange:0->1 Apple-IpadAir2-1_PT8618
2015-12-11 01:55:31.126 ThaliTest[733:641014] server: accepting invitation Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:33.223 ThaliTest[733:641874] client session: connected
2015-12-11 01:55:33.224 ThaliTest[733:641874] client session: stateChange:1->2 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:33.230 ThaliTest[733:641874] client session: fireConnectCallback: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:55:33.231 ThaliTest[733:641874] jxcore: connect: success
,2015-12-11T00:55:33.233Z SendDataConnector.js: CLIENT connected to 56120, error: null
,2015-12-11T00:55:33.233Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:33.237 ThaliTest[733:641014] client: relay established
2015-12-11 01:55:33.237 ThaliTest[733:641014] client: new accepted socket: 0x18f60080
,2015-12-11T00:55:33.253Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:33.623Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T00:55:33.683Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T00:55:33.684Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:33.685Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:55:33.685Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:33.687 ThaliTest[733:641224] jxcore: disconnect
,2015-12-11 01:55:33.688 ThaliTest[733:641224] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:33.688 ThaliTest[733:641224] client session: disconnect
,2015-12-11 01:55:33.689 ThaliTest[733:641224] client session: stateChange:2->0 Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:33.754 ThaliTest[733:641224] jxcore: disconnect: success
,2015-12-11T00:55:33.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8618.Ut+byw==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11T00:55:33.756Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11T00:55:33.757Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11T00:55:33.757Z SendDataConnector.js: do connect now
,2015-12-11 01:55:33.758 ThaliTest[733:641224] jxcore: connect Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:33.758 ThaliTest[733:641224] client session: connect
,2015-12-11 01:55:33.759 ThaliTest[733:641224] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:33.861 ThaliTest[733:641875] server session: connected
,2015-12-11 01:55:33.861 ThaliTest[733:641875] server session: stateChange:1->2 Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:33.865 ThaliTest[733:641014] server relay: connected (to port: 56117)
,2015-12-11T00:55:33.868Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11 01:55:34.265 ThaliTest[733:641864] server session: connected
,2015-12-11 01:55:34.265 ThaliTest[733:641864] server session: stateChange:1->2 Apple-Iphone5-1_PT4192
,2015-12-11 01:55:34.276 ThaliTest[733:641014] server relay: connected (to port: 56117)
,2015-12-11T00:55:34.280Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:34.336Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-11T00:55:34.353Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-11T00:55:34.370Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T00:55:34.386Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11T00:55:35.130Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T00:55:35.145Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-11T00:55:35.228Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-11T00:55:35.243Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:55:35.340 ThaliTest[733:641864] server session: not connected Apple-Iphone5-1_PT4192
,2015-12-11 01:55:35.785 ThaliTest[733:641014] multipeer session: reset timer
2015-12-11 01:55:35.786 ThaliTest[733:641014] multipeer session: stop timer
2015-12-11 01:55:35.786 ThaliTest[733:641014] multipeer session: start timer: 0x18ed0110
2015-12-11 ,01:55:35.786 ThaliTest[733:641014] server session: connect
2015-12-11 01:55:35.786 ThaliTest[733:641014] server session: stateChange:0->1 Apple-Iphone5s-1_PT7285
2015-12-11 01:55:35.794 ThaliTest[733:641014] server: accepting invitation Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:37.249 ThaliTest[733:641866] client session: connected
2015-12-11 01:55:37.249 ThaliTest[733:641866] client session: stateChange:1->2 Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:37.252 ThaliTest[733:641866] client session: fireConne,ctCallback: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:37.252 ThaliTest[733:641866] jxcore: connect: success
2015-12-11T00:55:37.253Z SendDataConnector.js: CLIENT connected to 56125, error: null
2015-12-11T00:55:37.254Z SendDataConnector.js: CLIEN,T starting client 
,2015-12-11 01:55:37.258 ThaliTest[733:641014] client: relay established
2015-12-11 01:55:37.259 ThaliTest[733:641014] client: new accepted socket: 0x18ee1990
,2015-12-11T00:55:37.270Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:38.395Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T00:55:38.422Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T00:55:38.459Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T00:55:38.471Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T00:55:38.472Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:38.474Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:55:38.474Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:38.475 ThaliTest[733:641224] jxcore: disconnect
,2015-12-11 01:55:38.476 ThaliTest[733:641224] client session: disconnectFromPeer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:38.477 ThaliTest[733:641224] client session: disconnect
2015-12-11 01:55:38.478 ThaliTest[733:641224] client session: stateChange:2->0 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:38.493 ThaliTest[733:641224] jxcore: disconnect: success
2015-12-11T00:55:38.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.MPIGmg==
---- round done--------
device[3]: Apple-Iphone5s-1_PT7285.LN,ATEw==
2015-12-11T00:55:38.496Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:38.496Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:38.497Z SendDataCon,nector.js: do connect now
2015-12-11 01:55:38.497 ThaliTest[733:641224] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:38.498 ThaliTest[733:641224] client session: connect
,2015-12-11 01:55:38.503 ThaliTest[733:641224] client session: stateChange:0->1 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:39.066 ThaliTest[733:641875] server session: connected
2015-12-11 01:55:39.066 ThaliTest[733:641875] server session: stateChange:1->2 Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:39.073 ThaliTest[733:641014] server relay: connected (to port: 56117)
,2015-12-11T00:55:39.079Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:39.380Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-11T00:55:39.454Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-11T00:55:39.506Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-11T00:55:39.520Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-12-11T00:55:39.534Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-11T00:55:39.585Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-11T00:55:39.843Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T00:55:39.857Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:55:39.978 ThaliTest[733:641865] server session: not connected Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:42.667 ThaliTest[733:641865] client session: connected
2015-12-11 01:55:42.668 ThaliTest[733:641865] client session: stateChange:1->2 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:42.682 ThaliTest[733:641874] client session: fireConnectCallback: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:42.683 ThaliTest[733:641874] jxcore: connect: success
2015-12-11T00:55:42.684Z SendDataConnector.js: CLIENT connected to 56129, error: null
2015-12-11T00:55:42.685Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:42.688 ThaliTest[733:641014] client: relay established
2015-12-11 01:55:42.689 ThaliTest[733:641014] client: new accepted socket: 0x18f658f0
,2015-12-11T00:55:42.701Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 01:55:46.525 ThaliTest[733:641866] server session: not connected Apple-IpadAir2-1_PT8618
,2015-12-11T00:55:52.979Z SendDataConnector.js: Receiving data timeout now
,2015-12-11T00:55:52.979Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T00:55:52.981Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11T00:55:52.982Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T00:55:52.983Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-11 01:55:52.985 ThaliTest[733:641014] client: socket closed
2015-12-11 01:55:52.985 ThaliTest[733:641014] client relay: socket disconnected
2015-12-11 01:55:52.985 ThaliTest[733:641014] client relay: 0x18f658f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-11 01:55:52.986 ThaliTest[733:641014] client session: socket closed: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:,55:52.986 ThaliTest[733:641014] client session: onLinkFailure: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:52.986 ThaliTest[733:641014] client session: disconnect
2015-12-11 01:55:52.986 ThaliTest[733:641014] client session: stateChange:2->0 Apple-,Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:52.995 ThaliTest[733:641014] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:55:57.986Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:55:57.987Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:00.637 ThaliTest[733:641014] client: lost peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:00.637 ThaliTest[733:641014] client session: onPeerLost: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:56:02.996 ThaliTest[733:641224] jxcore: disconnect
2015-12-11 01:56:02.997 ThaliTest[733:641224] jxcore: disconnect: fail
2015-12-11T00:56:02.998Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==,
2015-12-11T00:56:02.998Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7285.LNATEw== with availability status: true
2015-12-11T00:56:02.998Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:56:02.999Z SendDataConnector.js: do connect now
,2015-12-11 01:56:03.000 ThaliTest[733:641224] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:03.000 ThaliTest[733:641224] client session: connect
2015-12-11 01:56:03.001 ThaliTest[733:641224] client session: stateChange:0->1 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:56:05.828 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:05.830 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:56:08.775 ThaliTest[733:641014] client: lost peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:56:08.776 ThaliTest[733:641014] client session: onPeerLost: Apple-Iphone5-1_PT4192.MPIGmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:56:17.096 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 01:56:17.740 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8618.Ut+byw==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 01:56:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:56:35.834 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:35.837 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 01:56:35.837 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:56:36.006 ThaliTest[733:642159] client session: not connected Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:36.007 ThaliTest[733:642159] client session: onLinkFailure: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:36.007 ThaliTest[7,33:642159] client session: disconnect
2015-12-11 01:56:36.007 ThaliTest[733:642159] client session: stateChange:1->0 Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:36.008 ThaliTest[733:642159] client session: fireConnectCallback: Apple-Iphone5s-1_PT72,85.LNATEw==
2015-12-11 01:56:36.008 ThaliTest[733:642159] jxcore: connect: fail: Peer disconnected
2015-12-11T00:56:36.010Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T00:56:36.010Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer disconnected
2015-12-11T00:56:36.010Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T00:56:41.015Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:56:41.016Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:46.017 ThaliTest[733:641224] jxcore: disconnect
2015-12-11 01:56:46.017 ThaliTest[733:641224] jxcore: disconnect: fail
2015-12-11T00:56:46.018Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==,
2015-12-11T00:56:46.018Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7285.LNATEw== with availability status: true
2015-12-11T00:56:46.018Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:56:46.019Z SendDataConnector.js: do connect now
,2015-12-11 01:56:46.019 ThaliTest[733:641224] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:46.021 ThaliTest[733:641224] client session: connect
2015-12-11 01:56:46.021 ThaliTest[733:641224] client session: stateChange:0->1 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:48.687 ThaliTest[733:642190] client session: connected
2015-12-11 01:56:48.687 ThaliTest[733:642190] client session: stateChange:1->2 Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:48.694 ThaliTest[733:642159] client session: fireConnectCallback: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:48.694 ThaliTest[733:642159] jxcore: connect: success
2015-12-11T00:56:48.696Z SendDataConnector.js: CLIENT connected to 56138, error: null
2015-12-11T00:56:48.696Z SendDataConnector.js: CLI,ENT starting client 
,2015-12-11 01:56:48.702 ThaliTest[733:641014] client: relay established
2015-12-11 01:56:48.703 ThaliTest[733:641014] client: new accepted socket: 0x176eaab0
,2015-12-11T00:56:48.714Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:56:49.175Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T00:56:49.189Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T00:56:49.189Z SendDataConnector.js: got all data for this round
,2015-12-11T00:56:49.190Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:56:49.190Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:56:49.191 ThaliTest[733:641224] jxcore: disconnect
2015-12-11 01:56:49.191 ThaliTest[733:641224] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:56:49.191 ThaliTest[733:641224] client session: disconnect
2015-12-11 01:56:49.191 ThaliTest[733:641224] client session: stateChange:2->0 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:49.201 ThaliTest[733:641224] jxcore: disconnect: success
2015-12-11T00:56:49.201Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT9748","time":83541,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT8618.Ut+byw==","time":6082,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4192.MPIGmg==","time":4715,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7285.LNATEw==","time":70693,"res,ult":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 70693 ms, 99% : 70693 ms, 95 : 70693 ms, 90% : 70693 ms.
Result count 3, range 4715 ms to  70693 ms.
sendList failed peers count : 0 [0 %]
sendList ,never tried peers count : 0 [0 %]
2015-12-11T00:56:49.211Z SendDataConnector.js: CLIENT Stop now
2015-12-11T00:56:49.211Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:57:03.811 ThaliTest[733:641014] client: lost peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:57:03.811 ThaliTest[733:641014] client session: onPeerLost: Apple-Iphone5-1_PT4192.MPIGmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:57:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:57:05.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:57:05.830 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 01:57:06.036 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:57:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:57:35.832 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:57:35.833 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:57:35.833 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:58:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:58:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:58:35.821 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:58:35.822 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:58:35.823 ThaliTest[733:641014] client: fou,nd peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:59:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:59:05.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:59:05.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:59:08.061 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:59:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 01:59:35.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:59:35.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:59:35.829 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:00:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:00:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:00:05.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:00:05.828 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:00:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:00:35.827 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:00:35.829 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:00:35.829 ThaliTest[733:641014] client: fou,nd peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:01:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:01:05.822 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:01:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:01:05.826 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,2015-12-11 02:01:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:01:35.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:01:35.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:01:35.827 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11 02:02:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:02:05.800 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:02:05.801 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:02:05.802 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,2015-12-11 02:02:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:02:35.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:02:35.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:02:35.826 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:02:38.933 ThaliTest[733:641014] client: lost peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:02:38.933 ThaliTest[733:641014] client session: onPeerLost: Apple-Iphone5s-1_PT7285.LNATEw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7285.LNATEw==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 02:02:41.428 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7285.LNATEw==","peerName":"(null)","peerAvailable":true}]
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
,2015-12-11 02:03:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:03:05.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:03:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:03:05.824 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
Error type "connect_error" when connecting to the test server
,2015-12-11 02:03:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:03:35.825 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:03:35.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:03:35.827 ThaliTest[733:641014] client: fou,nd peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:04:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:04:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:04:05.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:04:06.001 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,2015-12-11 02:04:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:04:36.774 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:04:36.774 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:04:36.774 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:05:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:05:06.808 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:05:06.808 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:06.809 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
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
,2015-12-11 02:05:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:05:35.827 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:05:35.827 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:05:35.830 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:06:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:06:05.820 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:06:05.824 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:06:05.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:06:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:06:35.825 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:06:35.826 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:06:35.827 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:07:05.786 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:07:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:07:05.824 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:07:05.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:07:35.787 ThaliTest[733:641014] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11 02:08:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:08:05.821 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:08:05.821 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:08:05.821 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
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
,2015-12-11 02:08:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:08:35.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:08:35.829 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:08:35.829 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11 02:09:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:09:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:09:05.825 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:09:05.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
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
,2015-12-11 02:09:35.787 ThaliTest[733:641014] multipeer session: restart
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
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:10:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:10:05.823 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:10:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:10:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:10:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:10:35.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:10:35.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:10:35.825 ThaliTest[733:641014] client: fou,nd peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:11:05.787 ThaliTest[733:641014] multipeer session: restart
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
,2015-12-11 02:11:35.786 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:11:35.819 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:11:35.819 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:11:35.819 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-11 02:12:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:12:05.818 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:12:05.819 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:12:05.820 ThaliTest[733:641014] client: fou,nd peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:12:35.787 ThaliTest[733:641014] multipeer session: restart
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
,2015-12-11 02:13:05.787 ThaliTest[733:641014] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11 02:13:06.808 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:13:06.809 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:13:06.809 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:13:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:13:35.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:13:35.825 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 02:13:35.831 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:14:05.787 ThaliTest[733:641014] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:14:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:14:35.822 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:14:35.823 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:14:35.828 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,2015-12-11 02:15:05.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:15:05.823 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:15:05.824 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:15:05.830 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:15:35.787 ThaliTest[733:641014] multipeer session: restart
,2015-12-11 02:15:35.825 ThaliTest[733:641014] client: found peer: Apple-IpadAir2-1_PT8618.Ut+byw==
2015-12-11 02:15:35.825 ThaliTest[733:641014] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:15:35.828 ThaliTest[733:641014] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
