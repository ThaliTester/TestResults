#### Test 525354860130a71_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D8CF063A-63A1-40F9-9F07-10EC983A7E00/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D8CF063A-63A1-40F9-9F07-10EC983A7E00/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/00D726CA-1ACD-47D0-97BF-B0B2FC62761F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61432"
,(lldb)     command script import "/tmp/D8CF063A-63A1-40F9-9F07-10EC983A7E00/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:43:14.779 ThaliTest[2755:2306569] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D215183-9C10-4DE2-BE64-A9B2F72D12E4/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:43:15.158 ThaliTest[2755:2306569] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:43:15.159 ThaliTest[2755:2306569] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:43:15.167 ThaliTest[2755:2306569] Unlimited access to network resources
,2015-12-04 09:43:15.173 ThaliTest[2755:2306569] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:43:18.855 ThaliTest[2755:2306569] Resetting plugins due to page load.
,2015-12-04 09:43:19.256 ThaliTest[2755:2306569] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/00D726CA-1ACD-47D0-97BF-B0B2FC62761F/ThaliTest.app/www/index.html
,2015-12-04 09:43:19.462 ThaliTest[2755:2306569] JXcore Cordova plugin initializing
2015-12-04 09:43:19.463 ThaliTest[2755:2306700] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT7135
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51460
,2015-12-04 09:49:52.819 ThaliTest[2755:2306700] jxcore: startBroadcasting
,2015-12-04 09:49:52.829 ThaliTest[2755:2306700] server: starting Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:52.831 ThaliTest[2755:2306700] multipeer session: start timer: 0x1ad95020
2015-12-04 09:49:52.832 ThaliTest[2755:2306700] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7135
2015-12-04 09:49:52.833 ThaliTest[2755:2306700] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-04T08:49:52.837Z SendDataTCPServer.js: TCP/IP server is bound to port: 51460
,2015-12-04 09:49:53.157 ThaliTest[2755:2306569] client: found peer: Apple-Iphone5s-1_PT7213.N3FSeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7213.N3FSeg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:49:53.160Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04T08:49:53.161Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04T08:49:53.161Z SendDataConnector.js: do connect now
,2015-12-04 09:49:53.162 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5s-1_PT7213.N3FSeg==
2015-12-04 09:49:53.162 ThaliTest[2755:2306700] client session: connect
2015-12-04 09:49:53.162 ThaliTest[2755:2306700] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:53.632 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:49:53.632 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:49:53.633 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-,12-04 09:49:53.634 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:49:53.634 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
,2015-12-04 09:49:53.654 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04 09:49:53.784 ThaliTest[2755:2306569] client: found peer: Apple-IpadAir2-1_PT6975.MZRWVw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6975.MZRWVw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:53.815 ThaliTest[2755:2306569] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9194.4xGkjQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:53.882 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:49:53.883 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:49:53.883 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-12-04 09:49:53.883 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:49:53.883 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04 09:49:53.889 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:49:55.795 ThaliTest[2755:2307238] server session: connected
2015-12-04 09:49:55.796 ThaliTest[2755:2307238] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:49:55.803 ThaliTest[2755:2306569] server relay: connected (to port: 51460)
,2015-12-04T08:49:55.814Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04 09:49:55.831 ThaliTest[2755:2307233] client session: connected
2015-12-04 09:49:55.832 ThaliTest[2755:2307233] client session: stateChange:1->2 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:55.836 ThaliTest[2755:2307233] client session: fireConnectCallback: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:55.838 ThaliTest[2755:2307233] jxcore: connect: success
,2015-12-04T08:49:55.841Z SendDataConnector.js: CLIENT connected to 51464, error: null
,2015-12-04T08:49:55.841Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:55.845 ThaliTest[2755:2306569] client: relay established
2015-12-04 09:49:55.846 ThaliTest[2755:2306569] client: new accepted socket: 0x1666aea0
,2015-12-04T08:49:55.861Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04 09:49:55.931 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:49:55.931 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:49:55.932 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-12-04 09:49:55.932 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:49:55.932 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
,2015-12-04 09:49:55.935 ThaliTest[2755:2306569] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04T08:49:56.313Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-04T08:49:56.325Z SendDataTCPServer.js: TCP/IP server has received 23808 bytes of data
,2015-12-04T08:49:56.326Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04 09:49:56.329 ThaliTest[2755:2307243] server session: connected
2015-12-04 09:49:56.329 ThaliTest[2755:2307243] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
2015-12-04 09:49:56.331 ThaliTest[2755:2306569] server relay: connected (to, port: 51460)
,2015-12-04T08:49:56.338Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-12-04T08:49:56.343Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-04T08:49:56.344Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:49:56.355Z SendDataTCPServer.js: TCP/IP server has received 72416 bytes of data
,2015-12-04T08:49:56.358Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-04T08:49:56.358Z SendDataConnector.js: got all data for this round
,2015-12-04T08:49:56.360Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:49:56.360Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:49:56.366 ThaliTest[2755:2306700] jxcore: disconnect
,2015-12-04 09:49:56.367 ThaliTest[2755:2306700] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:56.371 ThaliTest[2755:2306700] client session: disconnect
,2015-12-04 09:49:56.372 ThaliTest[2755:2306700] client session: stateChange:2->0 Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:56.373 ThaliTest[2755:2306700] jxcore: disconnect: success
,2015-12-04T08:49:56.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7213.N3FSeg==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04T08:49:56.380Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04T08:49:56.380Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04T08:49:56.380Z SendDataConnector.js: do connect now
,2015-12-04 09:49:56.381 ThaliTest[2755:2306700] jxcore: connect Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:49:56.386 ThaliTest[2755:2306700] client session: connect
,2015-12-04 09:49:56.389 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04T08:49:56.408Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:49:56.455 ThaliTest[2755:2307243] server session: not connected Apple-Iphone5-1_PT9194
,2015-12-04T08:49:56.772Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:49:56.785Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-04T08:49:56.800Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-04T08:49:56.813Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:49:58.405 ThaliTest[2755:2307243] server session: connected
2015-12-04 09:49:58.406 ThaliTest[2755:2307243] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04T08:49:58.410Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04 09:49:58.412 ThaliTest[2755:2306569] server relay: connected (to port: 51460)
,2015-12-04T08:49:58.640Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-04T08:49:58.653Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-04T08:49:58.670Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-04T08:49:58.687Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-04T08:49:58.705Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:49:58.899 ThaliTest[2755:2307238] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04 09:49:59.444 ThaliTest[2755:2307238] client session: connected
2015-12-04 09:49:59.444 ThaliTest[2755:2307238] client session: stateChange:1->2 Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:49:59.448 ThaliTest[2755:2307238] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:49:59.448 ThaliTest[2755:2307238] jxcore: connect: success
,2015-12-04T08:49:59.450Z SendDataConnector.js: CLIENT connected to 51469, error: null
2015-12-04T08:49:59.451Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:59.455 ThaliTest[2755:2306569] client: relay established
2015-12-04 09:49:59.455 ThaliTest[2755:2306569] client: new accepted socket: 0x1adb5940
,2015-12-04T08:49:59.468Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:49:59.950Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:49:59.950Z SendDataConnector.js: got all data for this round
,2015-12-04T08:49:59.951Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:49:59.951Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:49:59.952 ThaliTest[2755:2306700] jxcore: disconnect
,2015-12-04 09:49:59.953 ThaliTest[2755:2306700] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:49:59.954 ThaliTest[2755:2306700] client session: disconnect
,2015-12-04 09:49:59.954 ThaliTest[2755:2306700] client session: stateChange:2->0 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:50:00.014 ThaliTest[2755:2306700] jxcore: disconnect: success
,2015-12-04T08:50:00.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6975.MZRWVw==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:00.017Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:00.018Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:00.018Z SendDataConnector.js: do connect now
,2015-12-04 09:50:00.020 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:00.024 ThaliTest[2755:2306700] client session: connect
,2015-12-04 09:50:00.025 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:02.238 ThaliTest[2755:2307233] client session: connected
2015-12-04 09:50:02.239 ThaliTest[2755:2307233] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:02.255 ThaliTest[2755:2307242] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:02.256 ThaliTest[2755:2307242] jxcore: connect: success
2015-12-04T08:50:02.257Z SendDataConnector.js: CLIENT connected to 51472, error: null
2015-12-04T08:50:02.258Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:02.261 ThaliTest[2755:2306569] client: relay established
,2015-12-04 09:50:02.262 ThaliTest[2755:2306569] client: new accepted socket: 0x16682520
,2015-12-04T08:50:02.274Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:50:02.563Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-04T08:50:02.589Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04 09:50:06.840 ThaliTest[2755:2307242] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04T08:50:12.600Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:12.601Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:12.602Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:12.602Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:12.603Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:12.605 ThaliTest[2755:2306569] client: socket closed
2015-12-04 09:50:12.606 ThaliTest[2755:2306569] client relay: socket disconnected
2015-12-04 09:50:12.606 ThaliTest[2755:2306569] client relay: 0x16682520 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1a95ad50 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:12.607 ThaliTest[2755:2306569] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ,==
2015-12-04 09:50:12.607 ThaliTest[2755:2306569] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:12.608 ThaliTest[2755:2306569] client session: disconnect
2015-12-04 09:50:12.608 ThaliTest[2755:2306569] client session: ,stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:12.610 ThaliTest[2755:2306569] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:17.395 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:50:17.396 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:50:17.396 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-,12-04 09:50:17.397 ThaliTest[2755:2306569] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7213)
2015-12-04 09:50:17.398 ThaliTest[2755:2306569] server session: disconnect
2015-12-04 09:50:17.398 ThaliTest[2755:2306569] server session: state,Change:2->0 Apple-Iphone5s-1_PT7213
2015-12-04T08:50:17.405Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04 09:50:17.406 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:50:17.408 ThaliTest[2755:2306569] server session: stateChange,:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04 09:50:17.422 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04T08:50:17.610Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:17.611Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:19.910 ThaliTest[2755:2307243] server session: connected
2015-12-04 09:50:19.911 ThaliTest[2755:2307243] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
,2015-12-04 09:50:19.918 ThaliTest[2755:2306569] server relay: connected (to port: 51460)
2015-12-04T08:50:19.923Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:20.035Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:50:20.049Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:50:22.615 ThaliTest[2755:2306700] jxcore: disconnect
2015-12-04 09:50:22.615 ThaliTest[2755:2306700] jxcore: disconnect: fail
2015-12-04T08:50:22.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:22.617Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
,2015-12-04T08:50:22.617Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:22.617Z SendDataConnector.js: do connect now
,2015-12-04 09:50:22.618 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:22.619 ThaliTest[2755:2306700] client session: connect
2015-12-04 09:50:22.620 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:25.087 ThaliTest[2755:2307309] client session: connected
,2015-12-04 09:50:25.088 ThaliTest[2755:2307309] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:25.093 ThaliTest[2755:2307309] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:25.093 ThaliTest[2755:2307309] jxcore: connect: success
,2015-12-04T08:50:25.095Z SendDataConnector.js: CLIENT connected to 51475, error: null
,2015-12-04T08:50:25.096Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:25.100 ThaliTest[2755:2306569] client: relay established
2015-12-04 09:50:25.100 ThaliTest[2755:2306569] client: new accepted socket: 0x1ada0780
,2015-12-04T08:50:25.112Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:30.317 ThaliTest[2755:2307309] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04T08:50:35.188Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:50:35.189Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:35.190Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:35.190Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:35.191Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:35.192 ThaliTest[2755:2306569] client: socket closed
2015-12-04 09:50:35.193 ThaliTest[2755:2306569] client relay: socket disconnected
2015-12-04 09:50:35.194 ThaliTest[2755:2306569] client relay: 0x1ada0780 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1ac0ae00 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:35.194 ThaliTest[2755:2306569] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ,==
2015-12-04 09:50:35.195 ThaliTest[2755:2306569] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:35.195 ThaliTest[2755:2306569] client session: disconnect
2015-12-04 09:50:35.195 ThaliTest[2755:2306569] client session: ,stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:35.198 ThaliTest[2755:2306569] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:50:40.202Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:40.203Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:40.393 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:50:40.394 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:50:40.394 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-,12-04 09:50:40.395 ThaliTest[2755:2306569] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7213)
2015-12-04 09:50:40.396 ThaliTest[2755:2306569] server session: disconnect
2015-12-04 09:50:40.396 ThaliTest[2755:2306569] server session: state,Change:2->0 Apple-Iphone5s-1_PT7213
2015-12-04 09:50:40.400 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:50:40.400 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04T08:50:40.414Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04 09:50:40.419 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:50:42.910 ThaliTest[2755:2307376] server session: connected
2015-12-04 09:50:42.911 ThaliTest[2755:2307376] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
,2015-12-04 09:50:42.915 ThaliTest[2755:2306569] server relay: connected (to port: 51460)
2015-12-04T08:50:42.916Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:43.023Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-04T08:50:43.038Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:50:45.207 ThaliTest[2755:2306700] jxcore: disconnect
2015-12-04 09:50:45.208 ThaliTest[2755:2306700] jxcore: disconnect: fail
2015-12-04T08:50:45.208Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkj,Q==
2015-12-04T08:50:45.209Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
2015-12-04T08:50:45.209Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:50:45.209Z SendDataConnector.js: do connect now
,2015-12-04 09:50:45.210 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:45.211 ThaliTest[2755:2306700] client session: connect
2015-12-04 09:50:45.211 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:47.754 ThaliTest[2755:2307242] client session: connected
2015-12-04 09:50:47.755 ThaliTest[2755:2307242] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:47.771 ThaliTest[2755:2307309] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:47.772 ThaliTest[2755:2307309] jxcore: connect: success
,2015-12-04T08:50:47.775Z SendDataConnector.js: CLIENT connected to 51478, error: null
,2015-12-04T08:50:47.776Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:47.779 ThaliTest[2755:2306569] client: relay established
2015-12-04 09:50:47.780 ThaliTest[2755:2306569] client: new accepted socket: 0x1a90bd10
,2015-12-04T08:50:47.790Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:53.033 ThaliTest[2755:2307242] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04T08:50:57.866Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:57.867Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:57.867Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:57.868Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:57.869Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:57.870 ThaliTest[2755:2306569] client: socket closed
2015-12-04 09:50:57.871 ThaliTest[2755:2306569] client relay: socket disconnected
2015-12-04 09:50:57.871 ThaliTest[2755:2306569] client relay: 0x1a90bd10 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1667d790 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:57.872 ThaliTest[2755:2306569] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ,==
2015-12-04 09:50:57.872 ThaliTest[2755:2306569] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:50:57.873 ThaliTest[2755:2306569] client session: disconnect
2015-12-04 09:50:57.873 ThaliTest[2755:2306569] client session: ,stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:50:57.875 ThaliTest[2755:2306569] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:02.869Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:02.869Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:03.459 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:51:03.460 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:51:03.460 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-,12-04 09:51:03.461 ThaliTest[2755:2306569] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7213)
2015-12-04 09:51:03.461 ThaliTest[2755:2306569] server session: disconnect
2015-12-04 09:51:03.462 ThaliTest[2755:2306569] server session: state,Change:2->0 Apple-Iphone5s-1_PT7213
,2015-12-04T08:51:03.475Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:51:03.527 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:51:03.528 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:03.534 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:05.968 ThaliTest[2755:2307405] server session: connected
2015-12-04 09:51:05.970 ThaliTest[2755:2307405] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
2015-12-04 09:51:05.974 ThaliTest[2755:2306569] server relay: connected (to, port: 51460)
2015-12-04T08:51:05.975Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:06.099Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:07.880 ThaliTest[2755:2306700] jxcore: disconnect
2015-12-04 09:51:07.880 ThaliTest[2755:2306700] jxcore: disconnect: fail
2015-12-04T08:51:07.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:07.882Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
,2015-12-04T08:51:07.882Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:07.882Z SendDataConnector.js: do connect now
,2015-12-04 09:51:07.883 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:07.884 ThaliTest[2755:2306700] client session: connect
2015-12-04 09:51:07.884 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:11.304 ThaliTest[2755:2307405] client session: connected
2015-12-04 09:51:11.305 ThaliTest[2755:2307405] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:11.309 ThaliTest[2755:2307242] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:11.310 ThaliTest[2755:2307242] jxcore: connect: success
2015-12-04T08:51:11.312Z SendDataConnector.js: CLIENT connected ,to 51481, error: null
2015-12-04T08:51:11.312Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:11.316 ThaliTest[2755:2306569] client: relay established
,2015-12-04 09:51:11.316 ThaliTest[2755:2306569] client: new accepted socket: 0x1a9df1e0
,2015-12-04T08:51:11.328Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:16.109 ThaliTest[2755:2307242] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04T08:51:21.404Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:21.404Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:21.405Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:21.406Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:51:21.407Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:21.408 ThaliTest[2755:2306569] client: socket closed
2015-12-04 09:51:21.409 ThaliTest[2755:2306569] client relay: socket disconnected
2015-12-04 09:51:21.409 ThaliTest[2755:2306569] client relay: 0x1a9df1e0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1acdec60 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:51:21.410 ThaliTest[2755:2306569] client session: socket closed: Apple-Iphone5-1_PT9194.4xGkjQ,==
2015-12-04 09:51:21.410 ThaliTest[2755:2306569] client session: onLinkFailure: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:21.411 ThaliTest[2755:2306569] client session: disconnect
2015-12-04 09:51:21.411 ThaliTest[2755:2306569] client session: ,stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:21.413 ThaliTest[2755:2306569] client session: fireConnectionErrorEvent: Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:26.415Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:26.415Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:26.466 ThaliTest[2755:2306569] multipeer session: reset timer
2015-12-04 09:51:26.467 ThaliTest[2755:2306569] multipeer session: stop timer
2015-12-04 09:51:26.468 ThaliTest[2755:2306569] multipeer session: start timer: 0x1ad95020
2015-,12-04 09:51:26.468 ThaliTest[2755:2306569] server: disconnecting to refresh session (Apple-Iphone5s-1_PT7213)
2015-12-04 09:51:26.469 ThaliTest[2755:2306569] server session: disconnect
2015-12-04 09:51:26.469 ThaliTest[2755:2306569] server session: state,Change:2->0 Apple-Iphone5s-1_PT7213
2015-12-04 09:51:26.474 ThaliTest[2755:2306569] server session: connect
2015-12-04 09:51:26.474 ThaliTest[2755:2306569] server session: stateChange:0->1 Apple-Iphone5s-1_PT7213
2015-12-04T08:51:26.478Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-04 09:51:26.493 ThaliTest[2755:2306569] server: accepting invitation Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:28.713 ThaliTest[2755:2307309] server session: connected
2015-12-04 09:51:28.714 ThaliTest[2755:2307309] server session: stateChange:1->2 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:28.719 ThaliTest[2755:2306569] server relay: connected (to port: 51460)
,2015-12-04T08:51:28.731Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:28.818Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-04T08:51:28.831Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:31.422 ThaliTest[2755:2306700] jxcore: disconnect
2015-12-04 09:51:31.423 ThaliTest[2755:2306700] jxcore: disconnect: fail
2015-12-04T08:51:31.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkj,Q==
2015-12-04T08:51:31.424Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT9194.4xGkjQ== with availability status: true
,2015-12-04T08:51:31.425Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:31.425Z SendDataConnector.js: do connect now
,2015-12-04 09:51:31.426 ThaliTest[2755:2306700] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:31.427 ThaliTest[2755:2306700] client session: connect
2015-12-04 09:51:31.428 ThaliTest[2755:2306700] client session: stateChange:0->1 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:33.883 ThaliTest[2755:2307455] client session: connected
,2015-12-04 09:51:33.884 ThaliTest[2755:2307455] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:33.890 ThaliTest[2755:2307455] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:33.890 ThaliTest[2755:2307455] jxcore: connect: success
2015-12-04T08:51:33.892Z SendDataConnector.js: CLIENT connected to 51484, error: null
,2015-12-04T08:51:33.892Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:33.897 ThaliTest[2755:2306569] client: relay established
2015-12-04 09:51:33.897 ThaliTest[2755:2306569] client: new accepted socket: 0x166d55b0
,2015-12-04T08:51:33.910Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:39.051 ThaliTest[2755:2307309] server session: not connected Apple-Iphone5s-1_PT7213
,2015-12-04T08:51:43.978Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:43.978Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:43.979Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:43.981Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:43.981Z SendDataConnector.js: Stop data retrieving timer
2015-12-04T08:51:43.981Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:43.982 ThaliTest[2755:2306700] jxcore: disconnect
,2015-12-04 09:51:43.983 ThaliTest[2755:2306700] client session: disconnectFromPeer: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:43.984 ThaliTest[2755:2306700] client session: disconnect
2015-12-04 09:51:43.984 ThaliTest[2755:2306700] client session:, stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:43.987 ThaliTest[2755:2306700] jxcore: disconnect: success
,2015-12-04T08:51:43.988Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7135","time":111188,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT7213.N3FSeg==","time":3198,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-,1_PT6975.MZRWVw==","time":3571,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9194.4xGkjQ==","time":103962,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
,sendList : 100% : 3571 ms, 99% : 3571 ms, 95 : 3571 ms, 90% : 3571 ms.
Result count 2, range 3198 ms to  3571 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5-1_PT9194.4xGkjQ==, Tried : 5
sendList never tried peers c,ount : 0 [0 %]
2015-12-04T08:51:44.003Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:44.003Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:51:44.004Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:52.612 ThaliTest[2755:2306569] client: lost peer: Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:51:52.613 ThaliTest[2755:2306569] client session: onPeerLost: Apple-IpadAir2-1_PT6975.MZRWVw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6975.MZRWVw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-04 09:51:53.096 ThaliTest[2755:2306700] jxcore: stopBroadcasting
2015-12-04 09:51:53.097 ThaliTest[2755:2306700] THEMultipeerSession stopping peer
2015-12-04 09:51:53.097 ThaliTest[2755:2306700] multipeer session: stop timer
2015-12-04 09:51:53.,098 ThaliTest[2755:2306700] server session: disconnect
2015-12-04 09:51:53.098 ThaliTest[2755:2306700] server session: stateChange:2->0 Apple-Iphone5s-1_PT7213
,2015-12-04 09:51:53.165 ThaliTest[2755:2306700] server session: disconnect
,2015-12-04 09:51:53.167 ThaliTest[2755:2306700] server session: stateChange:2->0 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:53.171 ThaliTest[2755:2306700] server session: disconnect
,2015-12-04 09:51:53.173 ThaliTest[2755:2306700] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:53.176 ThaliTest[2755:2306700] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-04T08:51:53.192Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-04T08:51:53.192Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:53.193Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:53.193Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7213.N3FSeg==\",\"time\":3198,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT6975.MZRWVw==\",\"time\":3571,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5-1_PT9194.4xGkjQ==\",\"time\":103962,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
