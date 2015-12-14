#### Test 5357450766a890e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/2836575E-FF3A-436F-A5A8-0200A596271B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2836575E-FF3A-436F-A5A8-0200A596271B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FC5DB075-2665-4A80-8BE9-A1B6ADF5533A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55391"
,(lldb)     command script import "/tmp/2836575E-FF3A-436F-A5A8-0200A596271B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 16:17:21.880 ThaliTest[943:1164090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DB44491-E7A6-4BF5-8DBA-2B631CD4D040/Library/Cookies/Cookies.binarycookies
,2015-12-14 16:17:22.316 ThaliTest[943:1164090] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 16:17:22.317 ThaliTest[943:1164090] Multi-tasking -> Device: YES, App: YES
,2015-12-14 16:17:22.328 ThaliTest[943:1164090] Unlimited access to network resources
,2015-12-14 16:17:22.343 ThaliTest[943:1164090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 16:17:31.480 ThaliTest[943:1164090] Resetting plugins due to page load.
,2015-12-14 16:17:35.274 ThaliTest[943:1164090] Finished load of: file:///var/mobile/Containers/Bundle/Application/FC5DB075-2665-4A80-8BE9-A1B6ADF5533A/ThaliTest.app/www/index.html
,2015-12-14 16:17:35.491 ThaliTest[943:1164090] JXcore Cordova plugin initializing
,2015-12-14 16:17:35.492 ThaliTest[943:1164423] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT3702
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 57755
,2015-12-14 16:24:10.576 ThaliTest[943:1164423] jxcore: startBroadcasting
,2015-12-14 16:24:10.597 ThaliTest[943:1164423] server: starting Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:10.599 ThaliTest[943:1164423] multipeer session: start timer: 0x18f36e40
2015-12-14 16:24:10.600 ThaliTest[943:1164423] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT3702
2015-12-14 16:24:10.601 ThaliTest[943:1164423] jxcore: s,tartBroadcasting: success
StartBroadcasting started ok
2015-12-14T15:24:10.603Z SendDataTCPServer.js: TCP/IP server is bound to port: 57755
,2015-12-14 16:24:10.928 ThaliTest[943:1164090] client: found peer: Apple-Iphone5-1_PT949.UkLT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT949.UkLT5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14T15:24:10.936Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:10.937Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:10.938Z SendDataConnector.js: do connect now
,2015-12-14 16:24:10.939 ThaliTest[943:1164423] jxcore: connect Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:10.941 ThaliTest[943:1164423] client session: connect
2015-12-14 16:24:10.941 ThaliTest[943:1164423] client session: stateChange:0->1 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:11.121 ThaliTest[943:1164090] client: found peer: Apple-Iphone6-1_PT9718.G9NStw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9718.G9NStw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tru,e
,2015-12-14 16:24:11.183 ThaliTest[943:1164090] client: found peer: Apple-IpadAir2-1_PT6360.8G12NA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6360.8G12NA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-12-14 16:24:13.794 ThaliTest[943:1165125] client session: connected
2015-12-14 16:24:13.795 ThaliTest[943:1165125] client session: stateChange:1->2 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:13.811 ThaliTest[943:1165126] client session: fireConnectCallback: Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:13.811 ThaliTest[943:1165126] jxcore: connect: success
2015-12-14T15:24:13.813Z SendDataConnector.js: CLIENT connected to 57758, error: null
2015-12-14T15:24:13.814Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:13.818 ThaliTest[943:1164090] client: relay established
2015-12-14 16:24:13.819 ThaliTest[943:1164090] client: new accepted socket: 0x18d87420
,2015-12-14T15:24:13.834Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:14.250Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T15:24:14.299Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T15:24:14.313Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T15:24:14.340Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:14.340Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:14.342Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:14.342Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:14.343 ThaliTest[943:1164423] jxcore: disconnect
2015-12-14 16:24:14.343 ThaliTest[943:1164423] client session: disconnectFromPeer: Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:14.343 ThaliTest[943:1164423] client session: disconnect
2015-12-14 16:24:14.343 ThaliTest[943:1164423] client session: stateChange:2->0 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:14.349 ThaliTest[943:1164423] jxcore: disconnect: success
2015-12-14T15:24:14.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT949.UkLT5Q==
---- round done--------
device[2]: Apple-Iphone6-1_PT9718.G9N,Stw==
2015-12-14T15:24:14.351Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:14.351Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:14.351Z SendDataConnec,tor.js: do connect now
2015-12-14 16:24:14.351 ThaliTest[943:1164423] jxcore: connect Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:14.352 ThaliTest[943:1164423] client session: connect
2015-12-14 16:24:14.352 ThaliTest[943:1164423] client session: stateChange:0->1 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:17.055 ThaliTest[943:1164090] multipeer session: reset timer
2015-12-14 16:24:17.055 ThaliTest[943:1164090] multipeer session: stop timer
2015-12-14 16:24:17.055 ThaliTest[943:1164090] multipeer session: start timer: 0x18f36e40
2015-12-,14 16:24:17.056 ThaliTest[943:1164090] server session: connect
2015-12-14 16:24:17.056 ThaliTest[943:1164090] server session: stateChange:0->1 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:17.068 ThaliTest[943:1164090] server: accepting invitation Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:17.260 ThaliTest[943:1165127] client session: connected
2015-12-14 16:24:17.260 ThaliTest[943:1165127] client session: stateChange:1->2 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:17.272 ThaliTest[943:1165127] client session: fireConnectCallback: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:17.272 ThaliTest[943:1165127] jxcore: connect: success
2015-12-14T15:24:17.273Z SendDataConnector.js: CLIENT connected to, 57761, error: null
2015-12-14T15:24:17.273Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:17.279 ThaliTest[943:1164090] client: relay established
2015-12-14 16:24:17.279 ThaliTest[943:1164090] client: new accepted socket: 0x18d82860
,2015-12-14T15:24:17.291Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:17.772Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T15:24:17.846Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T15:24:17.847Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:17.848Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:17.848Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:17.848 ThaliTest[943:1164423] jxcore: disconnect
2015-12-14 16:24:17.848 ThaliTest[943:1164423] client session: disconnectFromPeer: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:17.849 ThaliTest[943:1164423] client session: disconnect
2015-12-14 16:24:17.849 ThaliTest[943:1164423] client session: stateChange:2->0 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:17.857 ThaliTest[943:1164423] jxcore: disconnect: success
2015-12-14T15:24:17.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9718.G9NStw==
---- round done--------
device[3]: Apple-IpadAir2-1_PT6360.8,G12NA==
2015-12-14T15:24:17.859Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:17.859Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:17.859Z SendDataConnector.js: do connect now
2015-12-14 16:24:17.859 ThaliTest[943:1164423] jxcore: connect Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:17.859 ThaliTest[943:1164423] client session: connect
2015-12-14 16:24:17.860 ThaliTest[943:1164423] client session: stateChange:0->1 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:18.432 ThaliTest[943:1164090] multipeer session: reset timer
2015-12-14 16:24:18.432 ThaliTest[943:1164090] multipeer session: stop timer
2015-12-14 16:24:18.432 ThaliTest[943:1164090] multipeer session: start timer: 0x18f36e40
2015-12-,14 16:24:18.433 ThaliTest[943:1164090] server session: connect
2015-12-14 16:24:18.433 ThaliTest[943:1164090] server session: stateChange:0->1 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:18.445 ThaliTest[943:1164090] server: accepting invitation Apple-Iphone6-1_PT9718
,2015-12-14 16:24:18.559 ThaliTest[943:1164090] multipeer session: reset timer
2015-12-14 16:24:18.560 ThaliTest[943:1164090] multipeer session: stop timer
2015-12-14 16:24:18.560 ThaliTest[943:1164090] multipeer session: start timer: 0x18f36e40
2015-12-,14 16:24:18.560 ThaliTest[943:1164090] server session: connect
2015-12-14 16:24:18.560 ThaliTest[943:1164090] server session: stateChange:0->1 Apple-Iphone5-1_PT949
,2015-12-14 16:24:18.569 ThaliTest[943:1164090] server: accepting invitation Apple-Iphone5-1_PT949
,2015-12-14 16:24:20.537 ThaliTest[943:1165127] server session: connected
2015-12-14 16:24:20.537 ThaliTest[943:1165127] server session: stateChange:1->2 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:20.614 ThaliTest[943:1164090] server relay: connected (to port: 57755)
,2015-12-14T15:24:20.625Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:20.936Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-14T15:24:21.002Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-14T15:24:21.016Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-14T15:24:21.056Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-14T15:24:21.074Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-14T15:24:21.091Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T15:24:21.123Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T15:24:21.140Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:21.224 ThaliTest[943:1165127] server session: not connected Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:21.236 ThaliTest[943:1165125] client session: connected
,2015-12-14 16:24:21.237 ThaliTest[943:1165125] client session: stateChange:1->2 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:21.252 ThaliTest[943:1165125] client session: fireConnectCallback: Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:21.252 ThaliTest[943:1165125] jxcore: connect: success
,2015-12-14T15:24:21.256Z SendDataConnector.js: CLIENT connected to 57765, error: null
,2015-12-14T15:24:21.256Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:21.260 ThaliTest[943:1164090] client: relay established
,2015-12-14 16:24:21.261 ThaliTest[943:1164090] client: new accepted socket: 0x175c4960
,2015-12-14T15:24:21.273Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:21.642Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14 16:24:21.647 ThaliTest[943:1165127] server session: connected
2015-12-14 16:24:21.647 ThaliTest[943:1165127] server session: stateChange:1->2 Apple-Iphone5-1_PT949
,2015-12-14 16:24:21.651 ThaliTest[943:1164090] server relay: connected (to port: 57755)
,2015-12-14T15:24:21.656Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:21.695Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:21.696Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:21.696Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:21.697Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:21.698 ThaliTest[943:1164423] jxcore: disconnect
,2015-12-14 16:24:21.699 ThaliTest[943:1164423] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:21.700 ThaliTest[943:1164423] client session: disconnect
,2015-12-14 16:24:21.700 ThaliTest[943:1164423] client session: stateChange:2->0 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:21.717 ThaliTest[943:1165125] server session: connected
2015-12-14 16:24:21.717 ThaliTest[943:1165125] server session: stateChange:1->2 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:21.719 ThaliTest[943:1164423] jxcore: disconnect: success
,2015-12-14T15:24:21.723Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6360.8G12NA==
,---- round done--------
,2015-12-14 16:24:21.725 ThaliTest[943:1164090] server relay: connected (to port: 57755)
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT3702","time":11169,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT949.UkLT5Q==","time":3405,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_P,T9718.G9NStw==","time":3496,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6360.8G12NA==","time":3837,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3837 ms, 99% : 3837 ms, 95 : 3837 ms, 90% : 3837 ms.
,Result count 3, range 3405 ms to  3837 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-14T15:24:21.744Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:21.744Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14T15:24:21.759Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:22.097Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-12-14T15:24:22.117Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2015-12-14T15:24:22.142Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-14T15:24:22.168Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T15:24:22.192Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-14T15:24:22.208Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T15:24:22.259Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14 16:24:22.321 ThaliTest[943:1165194] server session: not connected Apple-Iphone6-1_PT9718
,2015-12-14T15:24:22.772Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-14T15:24:22.788Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:23.091 ThaliTest[943:1165127] server session: not connected Apple-Iphone5-1_PT949
,2015-12-14 16:24:24.711 ThaliTest[943:1164090] client: lost peer: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:24.711 ThaliTest[943:1164090] client session: onPeerLost: Apple-IpadAir2-1_PT6360.8G12NA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-IpadAir2-1_PT6360.8G12NA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 16:24:25.191 ThaliTest[943:1164090] client: lost peer: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:25.192 ThaliTest[943:1164090] client session: onPeerLost: Apple-Iphone6-1_PT9718.G9NStw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT9718.G9NStw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
2015-12-14 16:24:28.225 ThaliTest[943:1164423] jxcore: stopBroadcasting
,2015-12-14 16:24:28.225 ThaliTest[943:1164423] THEMultipeerSession stopping peer
,2015-12-14 16:24:28.225 ThaliTest[943:1164423] multipeer session: stop timer
,2015-12-14 16:24:28.227 ThaliTest[943:1164423] server session: disconnect
2015-12-14 16:24:28.227 ThaliTest[943:1164423] server session: stateChange:2->0 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:28.236 ThaliTest[943:1164423] server session: disconnect
2015-12-14 16:24:28.236 ThaliTest[943:1164423] server session: stateChange:2->0 Apple-Iphone5-1_PT949
,2015-12-14 16:24:28.248 ThaliTest[943:1164423] server session: disconnect
2015-12-14 16:24:28.249 ThaliTest[943:1164423] server session: stateChange:2->0 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:28.273 ThaliTest[943:1164423] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T15:24:28.312Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:28.319Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:28.324Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:28.325Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT949.UkLT5Q==\",\"time\":3405,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{,\"name\":\"Apple-Iphone6-1_PT9718.G9NStw==\",\"time\":3496,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT6360.8G12NA==\",\"time\":3837,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
