#### Test 525393149f38b37_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/538349A5-4460-4BEA-A77B-BCF7ED7060DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/538349A5-4460-4BEA-A77B-BCF7ED7060DA/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6EFD9275-DEA6-43B8-901E-312F684C06AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60629"
,(lldb)     command script import "/tmp/538349A5-4460-4BEA-A77B-BCF7ED7060DA/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 16:19:40.572 ThaliTest[1918:2998139] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15931739-8281-47B3-9523-48BFA6AA5990/Library/Cookies/Cookies.binarycookies
,2015-12-03 16:19:40.863 ThaliTest[1918:2998139] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 16:19:40.863 ThaliTest[1918:2998139] Multi-tasking -> Device: YES, App: YES
,2015-12-03 16:19:40.869 ThaliTest[1918:2998139] Unlimited access to network resources
,2015-12-03 16:19:40.876 ThaliTest[1918:2998139] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 16:19:45.016 ThaliTest[1918:2998139] Resetting plugins due to page load.
,2015-12-03 16:19:46.445 ThaliTest[1918:2998139] Finished load of: file:///var/mobile/Containers/Bundle/Application/6EFD9275-DEA6-43B8-901E-312F684C06AF/ThaliTest.app/www/index.html
,2015-12-03 16:19:46.591 ThaliTest[1918:2998139] JXcore Cordova plugin initializing
2015-12-03 16:19:46.593 ThaliTest[1918:2998331] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-IpadAir2-1_PT2877
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
,DBG, CoordinatorConnector connect_error called
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
serverPort is 51077
,2015-12-03 16:26:45.720 ThaliTest[1918:2998331] jxcore: startBroadcasting
,2015-12-03 16:26:45.726 ThaliTest[1918:2998331] server: starting Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:26:45.727 ThaliTest[1918:2998331] multipeer session: start timer: 0x17d891d0
,2015-12-03 16:26:45.727 ThaliTest[1918:2998331] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2877
2015-12-03 16:26:45.728 ThaliTest[1918:2998331] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-12-03T15:26:45.729Z SendDataTCPServer.js: TCP/IP server is bound to port: 51077
,2015-12-03 16:26:46.489 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03T15:26:46.493Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03T15:26:46.493Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8182.c6Lgog==,
2015-12-03T15:26:46.493Z SendDataConnector.js: do connect now
2015-12-03 16:26:46.493 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:26:46.493 ThaliTest[1918:2998331] client session: connect
2015-12-03 16:26:46.494 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:47.420 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:26:47.420 ThaliTest[1918:2998139] multipeer session: stop timer
,2015-12-03 16:26:47.420 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
,2015-12-03 16:26:47.421 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:26:47.421 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:47.423 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:48.589 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9874.kgLPmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:49.593 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 16:26:50.135 ThaliTest[1918:2999072] server session: connected
2015-12-03 16:26:50.135 ThaliTest[1918:2999072] server session: stateChange:1->2 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:50.139 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:26:50.153Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 16:26:50.208 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:26:50.208 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:26:50.208 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
,2015-12-03 16:26:50.208 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:26:50.209 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:26:50.211 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:26:50.414 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-03T15:26:50.469Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T15:26:50.493Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-03T15:26:50.688Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-03T15:26:51.020Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:51.713 ThaliTest[1918:2999073] server session: not connected Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:52.762 ThaliTest[1918:2999073] client session: connected
2015-12-03 16:26:52.762 ThaliTest[1918:2999073] client session: stateChange:1->2 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:52.763 ThaliTest[1918:2999073] client session: fireConnectCallback: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:26:52.764 ThaliTest[1918:2999073] jxcore: connect: success
,2015-12-03T15:26:52.764Z SendDataConnector.js: CLIENT connected to 51081, error: null
,2015-12-03T15:26:52.765Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:52.766 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:26:52.766 ThaliTest[1918:2998139] client: new accepted socket: 0x17f1f920
,2015-12-03T15:26:52.780Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:26:53.121Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03 16:26:53.149 ThaliTest[1918:2999073] server session: connected
2015-12-03 16:26:53.149 ThaliTest[1918:2999073] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:26:53.151 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:26:53.158Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:53.235Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T15:26:53.235Z SendDataConnector.js: got all data for this round
,2015-12-03T15:26:53.237Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T15:26:53.237Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:26:53.239 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:26:53.239 ThaliTest[1918:2998331] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:26:53.239 ThaliTest[1918:2998331] client session: disconnect
2015-12-03 16:26:53.239 ThaliTest[1918:2998331] client session: stateChange:2->0 Apple-Iphone5s-1_PT8182.c6Lgog==
,2015-12-03 16:26:53.245 ThaliTest[1918:2998331] jxcore: disconnect: success
2015-12-03T15:26:53.246Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8182.c6Lgog==
---- round done--------
,device[2]: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03T15:26:53.247Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03T15:26:53.247Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:26:53.247Z SendDataConnector.js: do connect now
,2015-12-03 16:26:53.247 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:53.248 ThaliTest[1918:2998331] client session: connect
,2015-12-03 16:26:53.248 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:26:53.761Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T15:26:53.774Z SendDataTCPServer.js: TCP/IP server has received 39808 bytes of data
,2015-12-03T15:26:53.789Z SendDataTCPServer.js: TCP/IP server has received 56544 bytes of data
,2015-12-03T15:26:54.099Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-03T15:26:54.159Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:56.258 ThaliTest[1918:2999072] client session: connected
2015-12-03 16:26:56.258 ThaliTest[1918:2999072] client session: stateChange:1->2 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:56.272 ThaliTest[1918:2999081] client session: fireConnectCallback: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:26:56.272 ThaliTest[1918:2999081] jxcore: connect: success
2015-12-03T15:26:56.273Z SendDataConnector.js: CLIENT connected to 51085, error: null
2015-12-03T15:26:56.273Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:26:56.274 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:26:56.274 ThaliTest[1918:2998139] client: new accepted socket: 0x19058ea0
,2015-12-03T15:26:56.287Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:26:56.741Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T15:26:56.816Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T15:26:56.842Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T15:26:56.842Z SendDataConnector.js: got all data for this round
,2015-12-03T15:26:56.843Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T15:26:56.843Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 16:26:56.844 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:26:56.844 ThaliTest[1918:2998331] client session: disconnectFromPeer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:26:56.844 ThaliTest[1918:2998331] client session: disconnect
2015-12-03 16:26:56.844 ThaliTest[1918:2998331] client session: stateChange:2->0 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:26:56.849 ThaliTest[1918:2998331] jxcore: disconnect: success
2015-12-03T15:26:56.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9874.kgLPmg==
---- round done--------
device[3]: Apple-Iphone6-1_PT4561.t,cwUUA==
2015-12-03T15:26:56.850Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:26:56.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:26:56.850Z SendDataConnector.js: do connect now
2015-12-03 16:26:56.850 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:26:56.850 ThaliTest[1918:2998331] client session: connect
2015-12-03 16:26:56.853 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:01.960 ThaliTest[1918:2999081] client session: connected
2015-12-03 16:27:01.960 ThaliTest[1918:2999081] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:01.996 ThaliTest[1918:2999081] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:01.996 ThaliTest[1918:2999081] jxcore: connect: success
2015-12-03T15:27:01.996Z SendDataConnector.js: CLIENT connected to 51089, error: null
2015-12-03T15:27:01.997Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:01.998 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:27:01.998 ThaliTest[1918:2998139] client: new accepted socket: 0x17e99500
,2015-12-03T15:27:02.011Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:27:02.268Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T15:27:02.281Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T15:27:02.480Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 16:27:04.176 ThaliTest[1918:2999077] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03T15:27:12.482Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T15:27:12.482Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:27:12.483Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:12.483Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:12.483Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:12.484 ThaliTest[1918:2998139] client: socket closed
,2015-12-03 16:27:12.484 ThaliTest[1918:2998139] client relay: socket disconnected
2015-12-03 16:27:12.484 ThaliTest[1918:2998139] client relay: 0x17e99500 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:27:12.485 ThaliTest[1918:2998139] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:12.485 ThaliTest[1918:2998139] client session: onLinkFailure:, Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:12.485 ThaliTest[1918:2998139] client session: disconnect
2015-12-03 16:27:12.485 ThaliTest[1918:2998139] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:12.487 ThaliTest[1918:2998139] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:14.526 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:27:14.526 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:27:14.526 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
2015-12-03 16:27:14.526 ThaliTest[1918:2998139] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:27:14.526 ThaliTest[1918:2998139] s,erver session: disconnect
2015-12-03 16:27:14.526 ThaliTest[1918:2998139] server session: stateChange:2->0 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:14.528 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:27:14.528 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:14.531 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03T15:27:14.537Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 16:27:17.160 ThaliTest[1918:2999164] server session: connected
2015-12-03 16:27:17.160 ThaliTest[1918:2999164] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:17.177 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:27:17.185Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:17.329Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-03T15:27:17.341Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-03T15:27:17.353Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T15:27:17.493Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:27:17.494Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:22.496 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:27:22.496 ThaliTest[1918:2998331] jxcore: disconnect: fail
2015-12-03T15:27:22.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUU,A==
2015-12-03T15:27:22.496Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
2015-12-03T15:27:22.496Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:27:22.496Z SendDataConnector.js: do connect now
,2015-12-03 16:27:22.497 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:22.497 ThaliTest[1918:2998331] client session: connect
2015-12-03 16:27:22.497 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:26.222 ThaliTest[1918:2999130] client session: connected
2015-12-03 16:27:26.223 ThaliTest[1918:2999130] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:26.226 ThaliTest[1918:2999077] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:26.226 ThaliTest[1918:2999077] jxcore: connect: success
,2015-12-03T15:27:26.226Z SendDataConnector.js: CLIENT connected to 51094, error: null
2015-12-03T15:27:26.227Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:27:26.228 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:27:26.229 ThaliTest[1918:2998139] client: new accepted socket: 0x17b46830
,2015-12-03T15:27:26.240Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:27:27.680 ThaliTest[1918:2999077] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03T15:27:36.265Z SendDataConnector.js: Receiving data timeout now
2015-12-03T15:27:36.265Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:27:36.265Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:36.266Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:36.266Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client: socket closed
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client relay: socket disconnected
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client relay: 0x17b46830 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client session: disconnect
2015-12-03 16:27:36.267 ThaliTest[1918:2998139] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:36.270 ThaliTest[1918:2998139] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:37.764 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:27:37.764 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:27:37.764 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
,2015-12-03 16:27:37.765 ThaliTest[1918:2998139] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:27:37.765 ThaliTest[1918:2998139] server session: disconnect
2015-12-03 16:27:37.765 ThaliTest[1918:2998139] server session: s,tateChange:2->0 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:37.767 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:27:37.767 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:37.769 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5-1_PT9874
2015-12-03T15:27:37.770Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 16:27:40.223 ThaliTest[1918:2999130] server session: connected
2015-12-03 16:27:40.223 ThaliTest[1918:2999130] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:27:40.260 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:27:40.271Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:40.421Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-03T15:27:40.434Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T15:27:41.269Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:27:41.269Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:46.272 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:27:46.272 ThaliTest[1918:2998331] jxcore: disconnect: fail
,2015-12-03T15:27:46.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:27:46.273Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
,2015-12-03T15:27:46.273Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:27:46.273Z SendDataConnector.js: do connect now
,2015-12-03 16:27:46.274 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:46.274 ThaliTest[1918:2998331] client session: connect
2015-12-03 16:27:46.274 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:48.935 ThaliTest[1918:2999214] client session: connected
2015-12-03 16:27:48.935 ThaliTest[1918:2999214] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:48.937 ThaliTest[1918:2999214] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:48.937 ThaliTest[1918:2999214] jxcore: connect: success
2015-12-03T15:27:48.938Z SendDataConnector.js: CLIENT connected ,to 51099, error: null
2015-12-03T15:27:48.938Z SendDataConnector.js: CLIENT starting client 
2015-12-03 16:27:48.939 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:27:48.939 ThaliTest[1918:2998139] client: new accepted socket: 0x15f06820
,2015-12-03T15:27:48.951Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:27:50.695 ThaliTest[1918:2999077] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:27:53.911 ThaliTest[1918:2998139] client: lost peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:27:53.911 ThaliTest[1918:2998139] client session: onPeerLost: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 16:27:54.463 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":true}]
,2015-12-03T15:27:58.983Z SendDataConnector.js: Receiving data timeout now
2015-12-03T15:27:58.983Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:58.983Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:27:58.984Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:27:58.984Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client: socket closed
2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client relay: socket disconnected
2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client relay: 0x15f06820 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12,-03 16:27:58.985 ThaliTest[1918:2998139] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client session: disconnect
2015-12-03 16:27:58.985 ThaliTest[1918:2998139] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:27:58.988 ThaliTest[1918:2998139] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:00.703 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:28:00.703 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:28:00.703 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
2015-,12-03 16:28:00.703 ThaliTest[1918:2998139] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:28:00.703 ThaliTest[1918:2998139] server session: disconnect
2015-12-03 16:28:00.703 ThaliTest[1918:2998139] server session: stateChange:2->0 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:00.705 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:28:00.705 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:00.708 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03T15:28:00.714Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 16:28:03.391 ThaliTest[1918:2999077] server session: connected
2015-12-03 16:28:03.391 ThaliTest[1918:2999077] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:03.408 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:28:03.411Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:28:03.487Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T15:28:03.996Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:28:03.996Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:09.002 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:28:09.002 ThaliTest[1918:2998331] jxcore: disconnect: fail
2015-12-03T15:28:09.002Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUU,A==
2015-12-03T15:28:09.002Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
2015-12-03T15:28:09.002Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:09.002Z SendDataConnector.js: do connect now
2015-12-03 16:28:09.002 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:09.003 ThaliTest[1918:2998331] client session: connect
2015-12-03 16:28:09.003 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:11.671 ThaliTest[1918:2999270] client session: connected
2015-12-03 16:28:11.671 ThaliTest[1918:2999270] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:11.673 ThaliTest[1918:2999077] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:11.673 ThaliTest[1918:2999077] jxcore: connect: success
2015-12-03T15:28:11.673Z SendDataConnector.js: CLIENT connected to 51104, error: null
2015-12-03T15:28:11.674Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:28:11.675 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:28:11.675 ThaliTest[1918:2998139] client: new accepted socket: 0x15e072e0
,2015-12-03T15:28:11.688Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:28:13.759 ThaliTest[1918:2999215] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03T15:28:21.723Z SendDataConnector.js: Receiving data timeout now
2015-12-03T15:28:21.723Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:21.723Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:28:21.724Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:28:21.724Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:28:21.724 ThaliTest[1918:2998139] client: socket closed
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client relay: socket disconnected
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client relay: 0x15e072e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client session: socket closed: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client session: onLinkFailure: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client session: disconnect
2015-12-03 16:28:21.725 ThaliTest[1918:2998139] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:21.727 ThaliTest[1918:2998139] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:23.791 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:28:23.791 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:28:23.791 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
2015-12-03 16:28:23.791 ThaliTest[1918:2998139] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:28:23.791 ThaliTest[1918:2998139] server session: disconnect
2015-12-03 16:28:23.791 ThaliTest[1918:2998139] server session: stateChange:2->0 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:23.793 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:28:23.793 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03T15:28:23.794Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 16:28:23.796 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:28:26.513 ThaliTest[1918:2999322] server session: connected
2015-12-03 16:28:26.513 ThaliTest[1918:2999322] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:26.515 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:28:26.519Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:28:26.605Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-12-03T15:28:26.728Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:26.728Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03T15:28:26.873Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:28:31.716 ThaliTest[1918:2998331] jxcore: disconnect
,2015-12-03 16:28:31.717 ThaliTest[1918:2998331] jxcore: disconnect: fail
,2015-12-03T15:28:31.717Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:31.717Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4561.tcwUUA== with availability status: true
2015-12-03T15:28:31.717Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03T15:28:31.717Z SendDataConnector.js: do connect now
,2015-12-03 16:28:31.717 ThaliTest[1918:2998331] jxcore: connect Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:31.718 ThaliTest[1918:2998331] client session: connect
,2015-12-03 16:28:31.718 ThaliTest[1918:2998331] client session: stateChange:0->1 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:34.560 ThaliTest[1918:2999270] client session: connected
2015-12-03 16:28:34.561 ThaliTest[1918:2999270] client session: stateChange:1->2 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:34.562 ThaliTest[1918:2999270] client session: fireConnectCallback: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:34.563 ThaliTest[1918:2999270] jxcore: connect: success
2015-12-03T15:28:34.563Z SendDataConnector.js: CLIENT connected to 51109, error: null
2015-12-03T15:28:34.563Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:28:34.564 ThaliTest[1918:2998139] client: relay established
2015-12-03 16:28:34.564 ThaliTest[1918:2998139] client: new accepted socket: 0x15f06820
,2015-12-03T15:28:34.577Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 16:28:36.807 ThaliTest[1918:2999322] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03T15:28:44.608Z SendDataConnector.js: Receiving data timeout now
2015-12-03T15:28:44.608Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:44.608Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T15:28:44.609Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:28:44.609Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T15:28:44.609Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:28:44.610 ThaliTest[1918:2998331] jxcore: disconnect
2015-12-03 16:28:44.610 ThaliTest[1918:2998331] client session: disconnectFromPeer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:44.610 ThaliTest[1918:2998331] client session: disconn,ect
2015-12-03 16:28:44.610 ThaliTest[1918:2998331] client session: stateChange:2->0 Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:28:44.613 ThaliTest[1918:2998331] jxcore: disconnect: success
2015-12-03T15:28:44.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4561.tcwUUA==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2877","time":118897,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8182.c6Lgog==","time":6743,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-,1_PT9874.kgLPmg==","time":3595,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4561.tcwUUA==","time":107758,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataR,eceived":90000}]}
sendList : 100% : 6743 ms, 99% : 6743 ms, 95 : 6743 ms, 90% : 6743 ms.
,Result count 2, range 3595 ms to  6743 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT4561.tcwUUA==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T15:28:44.618Z SendDataConnector.js: CLIENT St,op now
2015-12-03T15:28:44.618Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T15:28:44.618Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 16:28:47.432 ThaliTest[1918:2998139] client: lost peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:28:47.432 ThaliTest[1918:2998139] client session: onPeerLost: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 16:28:53.776 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:28:53.789 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:53.789 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:28:53.789 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:29:23.776 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:29:23.786 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:29:23.787 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:23.787 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:29:53.776 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:29:53.788 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:29:53.788 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:29:53.790 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:30:15.883 ThaliTest[1918:2998139] multipeer session: reset timer
2015-12-03 16:30:15.883 ThaliTest[1918:2998139] multipeer session: stop timer
2015-12-03 16:30:15.884 ThaliTest[1918:2998139] multipeer session: start timer: 0x17d891d0
2015-12-03 16:30:15.884 ThaliTest[1918:2998139] server session: connect
2015-12-03 16:30:15.884 ThaliTest[1918:2998139] server session: stateChange:0->1 Apple-Iphone6-1_PT4561
,2015-12-03 16:30:15.886 ThaliTest[1918:2998139] server: accepting invitation Apple-Iphone6-1_PT4561
,2015-12-03 16:30:18.186 ThaliTest[1918:2999608] server session: connected
2015-12-03 16:30:18.186 ThaliTest[1918:2999608] server session: stateChange:1->2 Apple-Iphone6-1_PT4561
,2015-12-03 16:30:18.189 ThaliTest[1918:2998139] server relay: connected (to port: 51077)
,2015-12-03T15:30:18.200Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:30:18.513Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-03T15:30:18.527Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:30:18.549 ThaliTest[1918:2999614] server session: not connected Apple-Iphone6-1_PT4561
,2015-12-03 16:30:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:30:46.877 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:30:46.878 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:30:46.878 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:31:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:31:15.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:31:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:31:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:31:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:31:45.895 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:31:45.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:31:46.555 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:32:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:32:15.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:32:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:32:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:32:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:32:46.635 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:32:46.635 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:32:46.637 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:33:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:33:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:33:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:41.534 ThaliTest[1918:2998139] client: lost peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:33:41.534 ThaliTest[1918:2998139] client session: onPeerLost: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 16:33:41.872 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 16:33:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:33:45.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:33:45.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:45.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:34:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:34:15.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:34:15.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:34:15.898 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:34:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:34:45.895 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:34:45.898 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:34:45.898 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:35:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:35:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:35:45.895 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:35:45.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:35:46.711 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:36:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:36:15.894 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:36:15.896 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:36:15.897 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:36:45.884 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:36:45.894 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:36:45.895 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:36:45.895 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT4561.tcwUUA==
,2015-12-03 16:37:12.545 ThaliTest[1918:2998139] client: lost peer: Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:37:12.545 ThaliTest[1918:2998139] client session: onPeerLost: Apple-Iphone6-1_PT4561.tcwUUA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4561.tcwUUA==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 16:37:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:37:15.894 ThaliTest[1918:2998139] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:37:16.456 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:37:28.864 ThaliTest[1918:2998139] client: lost peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:37:28.864 ThaliTest[1918:2998139] client session: onPeerLost: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 16:37:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:37:45.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:38:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:38:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:38:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:38:45.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:39:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:39:15.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:39:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:39:45.894 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:40:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:40:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:40:45.884 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:40:45.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:41:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:41:15.891 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:41:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:41:45.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:42:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:42:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:42:45.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:43:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:43:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:43:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:43:46.457 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:44:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:44:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:44:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:44:45.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:45:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:45:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:45:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:46:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:46:15.891 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:46:45.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:46:45.893 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:47:15.885 ThaliTest[1918:2998139] multipeer session: restart
,2015-12-03 16:47:15.892 ThaliTest[1918:2998139] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==

```
