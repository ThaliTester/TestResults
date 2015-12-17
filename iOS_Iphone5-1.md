#### Test 539786639813e59_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B285D455-C76E-475B-BE59-1AAE86571E79/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/B285D455-C76E-475B-BE59-1AAE86571E79/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5C9B91B0-E27B-4715-A258-52233516EB60/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59254"
,(lldb)     command script import "/tmp/B285D455-C76E-475B-BE59-1AAE86571E79/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 15:08:04.813 ThaliTest[314:262158] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9FA65DC5-B246-4492-A671-F3220EB3174D/Library/Cookies/Cookies.binarycookies
,2015-12-17 15:08:05.327 ThaliTest[314:262158] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 15:08:05.328 ThaliTest[314:262158] Multi-tasking -> Device: YES, App: YES
,2015-12-17 15:08:05.336 ThaliTest[314:262158] Unlimited access to network resources
,2015-12-17 15:08:05.348 ThaliTest[314:262158] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 15:08:15.553 ThaliTest[314:262158] Resetting plugins due to page load.
,2015-12-17 15:08:19.132 ThaliTest[314:262158] Finished load of: file:///var/mobile/Containers/Bundle/Application/5C9B91B0-E27B-4715-A258-52233516EB60/ThaliTest.app/www/index.html
,2015-12-17 15:08:19.341 ThaliTest[314:262158] JXcore Cordova plugin initializing
,2015-12-17 15:08:19.342 ThaliTest[314:262502] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,my name is : Apple-Iphone5-1_PT5479
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
,appEnteringBackground wasn't registered
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51746
,2015-12-17 15:16:43.978 ThaliTest[314:262502] jxcore: startBroadcasting
,2015-12-17 15:16:43.993 ThaliTest[314:262502] server: starting Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:16:43.993 ThaliTest[314:262502] multipeer session: start timer: 0x1d6ddf70
2015-12-17 15:16:43.993 ThaliTest[314:262502] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT5479
2015-12-17 15:16:43.994 ThaliTest[314:262502] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17T14:16:43.996Z SendDataTCPServer.js: TCP/IP server is bound to port: 51746
,2015-12-17 15:16:46.797 ThaliTest[314:262158] client: found peer: Apple-IpadAir2-1_PT1563.8yqJeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1563.8yqJeg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
device[1]: Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17T14:16:46.803Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17T14:16:46.805Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17T14:16:46.805Z SendDataConnector.js: do connect now
,2015-12-17 15:16:46.806 ThaliTest[314:262502] jxcore: connect Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:46.806 ThaliTest[314:262502] client session: connect
2015-12-17 15:16:46.807 ThaliTest[314:262502] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT1563.8yqJeg==
,2015-12-17 15:16:47.166 ThaliTest[314:262158] client: found peer: Apple-Iphone5s-1_PT1370.za9tCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1370.za9tCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 15:16:47.676 ThaliTest[314:262158] client: found peer: Apple-Iphone6-1_PT1480.8RWX+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 15:16:51.887 ThaliTest[314:262158] multipeer session: reset timer
2015-12-17 15:16:51.887 ThaliTest[314:262158] multipeer session: stop timer
2015-12-17 15:16:51.893 ThaliTest[314:262158] multipeer session: start timer: 0x1d6ddf70
2015-12-17 15:16:51.895 ThaliTest[314:262158] server session: connect
2015-12-17 15:16:51.895 ThaliTest[314:262158] server session: stateChange:0->1 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:51.909 ThaliTest[314:262158] server: accepting invitation Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:54.037 ThaliTest[314:262158] multipeer session: reset timer
2015-12-17 15:16:54.038 ThaliTest[314:262158] multipeer session: stop timer
2015-12-17 15:16:54.038 ThaliTest[314:262158] multipeer session: start timer: 0x1d6ddf70
,2015-12-17 15:16:54.039 ThaliTest[314:262158] server session: connect
,2015-12-17 15:16:54.040 ThaliTest[314:262158] server session: stateChange:0->1 Apple-Iphone6-1_PT1480
,2015-12-17 15:16:54.047 ThaliTest[314:262158] server: accepting invitation Apple-Iphone6-1_PT1480
,2015-12-17 15:16:54.725 ThaliTest[314:263455] client session: connected
2015-12-17 15:16:54.725 ThaliTest[314:263455] client session: stateChange:1->2 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:54.731 ThaliTest[314:263455] client session: fireConnectCallback: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:54.732 ThaliTest[314:263455] jxcore: connect: success
2015-12-17T14:16:54.733Z SendDataConnector.js: CLIENT connected to 51749, error: null
,2015-12-17T14:16:54.733Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:54.736 ThaliTest[314:262158] client: relay established
2015-12-17 15:16:54.736 ThaliTest[314:262158] client: new accepted socket: 0x1d7c5350
,2015-12-17T14:16:54.750Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:55.551Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T14:16:55.565Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-17T14:16:55.629Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:16:55.630Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:55.632Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:55.633Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:55.634 ThaliTest[314:262502] jxcore: disconnect
2015-12-17 15:16:55.634 ThaliTest[314:262502] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1563.8yqJeg==
2015-12-17 15:16:55.635 ThaliTest[314:262502] client session: disconnect
,2015-12-17 15:16:55.635 ThaliTest[314:262502] client session: stateChange:2->0 Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:55.645 ThaliTest[314:262502] jxcore: disconnect: success
2015-12-17T14:16:55.645Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1563.8yqJeg==
---- round done--------
device[2]: Apple-Iphone5s-1_PT1370.z,a9tCA==
2015-12-17T14:16:55.647Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17T14:16:55.648Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17T14:16:55.648Z SendDataCo,nnector.js: do connect now
2015-12-17 15:16:55.648 ThaliTest[314:262502] jxcore: connect Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:55.649 ThaliTest[314:262502] client session: connect
2015-12-17 15:16:55.649 ThaliTest[314:262502] client session:, stateChange:0->1 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:56.073 ThaliTest[314:263450] server session: connected
2015-12-17 15:16:56.074 ThaliTest[314:263450] server session: stateChange:1->2 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:56.137 ThaliTest[314:262158] server relay: connected (to port: 51746)
,2015-12-17T14:16:56.150Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17 15:16:56.325 ThaliTest[314:262158] multipeer session: reset timer
2015-12-17 15:16:56.326 ThaliTest[314:262158] multipeer session: stop timer
2015-12-17 15:16:56.326 ThaliTest[314:262158] multipeer session: start timer: 0x1d6ddf70
2015-12-17 15:16:56.326 ThaliTest[314:262158] server session: connect
2015-12-17 15:16:56.326 ThaliTest[314:262158] server session: stateChange:0->1 Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:56.332 ThaliTest[314:262158] server: accepting invitation Apple-IpadAir2-1_PT1563
,2015-12-17T14:16:56.601Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-17T14:16:56.616Z SendDataTCPServer.js: TCP/IP server has received 25996 bytes of data
,2015-12-17T14:16:56.630Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-17T14:16:56.645Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-17T14:16:56.662Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:56.709 ThaliTest[314:263455] server session: not connected Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:56.867 ThaliTest[314:263450] server session: connected
2015-12-17 15:16:56.867 ThaliTest[314:263450] server session: stateChange:1->2 Apple-Iphone6-1_PT1480
,2015-12-17 15:16:56.887 ThaliTest[314:262158] server relay: connected (to port: 51746)
2015-12-17T14:16:56.888Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:57.154Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-17T14:16:57.200Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
2015-12-17T14:16:57.223Z SendDataTCPServer.js: TCP/IP server has received 32566 bytes of data
,2015-12-17T14:16:57.238Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-17T14:16:57.326Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-17T14:16:57.660Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:57.718 ThaliTest[314:263450] server session: not connected Apple-Iphone6-1_PT1480
,2015-12-17 15:16:59.355 ThaliTest[314:263450] server session: connected
2015-12-17 15:16:59.355 ThaliTest[314:263450] server session: stateChange:1->2 Apple-IpadAir2-1_PT1563
2015-12-17 15:16:59.358 ThaliTest[314:262158] server relay: connected (to port: 51746)
,2015-12-17T14:16:59.370Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:59.754Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-17T14:16:59.770Z SendDataTCPServer.js: TCP/IP server has received 25996 bytes of data
,2015-12-17T14:16:59.784Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-17T14:16:59.798Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-17T14:16:59.813Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-17T14:16:59.828Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:59.880 ThaliTest[314:263450] client session: connected
2015-12-17 15:16:59.881 ThaliTest[314:263450] client session: stateChange:1->2 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:59.943 ThaliTest[314:263455] server session: not connected Apple-IpadAir2-1_PT1563
,2015-12-17 15:17:00.075 ThaliTest[314:263455] client session: fireConnectCallback: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:17:00.075 ThaliTest[314:263455] jxcore: connect: success
2015-12-17T14:17:00.076Z SendDataConnector.js: CLIENT connected to ,51755, error: null
2015-12-17T14:17:00.076Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:17:00.078 ThaliTest[314:262158] client: relay established
,2015-12-17 15:17:00.079 ThaliTest[314:262158] client: new accepted socket: 0x1d677920
,2015-12-17T14:17:00.091Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:17:00.847Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T14:17:00.859Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-17T14:17:00.873Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:17:00.874Z SendDataConnector.js: got all data for this round
,2015-12-17T14:17:00.876Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:17:00.876Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:17:00.877 ThaliTest[314:262502] jxcore: disconnect
2015-12-17 15:17:00.877 ThaliTest[314:262502] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:17:00.877 ThaliTest[314:262502] client session: disconnect
2015-12-17 15:17:00.877 ThaliTest[314:262502] client session: stateChange:2->0 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:17:00.899 ThaliTest[314:262502] jxcore: disconnect: success
,2015-12-17T14:17:00.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1370.za9tCA==
,---- round done--------
,device[3]: Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:17:00.910Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:17:00.911Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:17:00.912Z SendDataConnector.js: do connect now
,2015-12-17 15:17:00.916 ThaliTest[314:262502] jxcore: connect Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:17:00.918 ThaliTest[314:262502] client session: connect
,2015-12-17 15:17:00.919 ThaliTest[314:262502] client session: stateChange:0->1 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:17:03.702 ThaliTest[314:263450] client session: connected
2015-12-17 15:17:03.702 ThaliTest[314:263450] client session: stateChange:1->2 Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:17:03.705 ThaliTest[314:263450] client session: fireConne,ctCallback: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:17:03.705 ThaliTest[314:263450] jxcore: connect: success
2015-12-17T14:17:03.706Z SendDataConnector.js: CLIENT connected to 51758, error: null
2015-12-17T14:17:03.706Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:17:03.710 ThaliTest[314:262158] client: relay established
2015-12-17 15:17:03.710 ThaliTest[314:262158] client: new accepted socket: 0x1d6fb380
,2015-12-17T14:17:03.721Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:17:04.265Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T14:17:04.292Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T14:17:04.307Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T14:17:04.322Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-17T14:17:04.337Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T14:17:04.450Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T14:17:04.450Z SendDataConnector.js: got all data for this round
,2015-12-17T14:17:04.452Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:17:04.453Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:17:04.454 ThaliTest[314:262502] jxcore: disconnect
,2015-12-17 15:17:04.455 ThaliTest[314:262502] client session: disconnectFromPeer: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:17:04.455 ThaliTest[314:262502] client session: disconnect
2015-12-17 15:17:04.456 ThaliTest[314:262502] client session: stateChange:2->0 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:17:04.464 ThaliTest[314:262502] jxcore: disconnect: success
2015-12-17T14:17:04.464Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1480.8RWX+A==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT5479","time":20496,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT1563.8yqJeg==","time":8827,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT1370.za9tCA==","time":5226,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT1480.8RWX+A==","time":3540,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 8827 ms, 99% : 8827 ms, 95 : 8827 ms, 90% : 8827 ms.
Result count 3, range 3540 ms to  8827 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-12-17T14:17:04.477Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:17:04.477Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-17 15:17:07.000 ThaliTest[314:262502] jxcore: stopBroadcasting
2015-12-17 15:17:07.000 ThaliTest[314:262502] THEMultipeerSession stopping peer
2015-12-17 15:17:07.000 ThaliTest[314:262502] multipeer session: stop timer
2015-12-17 15:17:07.001 ThaliTest[314:262502] server session: disconnect
2015-12-17 15:17:07.001 ThaliTest[314:262502] server session: stateChange:2->0 Apple-Iphone5s-1_PT1370
,2015-12-17 15:17:07.066 ThaliTest[314:262502] server session: disconnect
2015-12-17 15:17:07.066 ThaliTest[314:262502] server session: stateChange:2->0 Apple-IpadAir2-1_PT1563
,2015-12-17 15:17:07.070 ThaliTest[314:262502] server session: disconnect
2015-12-17 15:17:07.071 ThaliTest[314:262502] server session: stateChange:2->0 Apple-Iphone6-1_PT1480
,2015-12-17 15:17:07.077 ThaliTest[314:262502] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-17T14:17:07.094Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:07.095Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:07.097Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:07.097Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1480.8RWX+A==\",\"time\":3540,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT1370.za9tCA==\",\"time\":5226,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-IpadAir2-1_PT1563.8yqJeg==\",\"time\":8827,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
