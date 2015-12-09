#### Test 5319156460e1811_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/3124DC2A-0D04-47B1-99B9-6950CE1E98E4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3124DC2A-0D04-47B1-99B9-6950CE1E98E4/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5319156460e1811/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A236DF20-8E59-48EA-BB5A-1AF20BD4BCD0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52701"
,(lldb)     command script import "/tmp/3124DC2A-0D04-47B1-99B9-6950CE1E98E4/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 00:11:15.459 ThaliTest[547:557065] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/17BE52FB-A339-4CF3-90B3-D7231056CFFE/Library/Cookies/Cookies.binarycookies
,2015-12-10 00:11:15.965 ThaliTest[547:557065] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 00:11:15.967 ThaliTest[547:557065] Multi-tasking -> Device: YES, App: YES
,2015-12-10 00:11:15.974 ThaliTest[547:557065] Unlimited access to network resources
,2015-12-10 00:11:15.987 ThaliTest[547:557065] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 00:11:26.324 ThaliTest[547:557065] Resetting plugins due to page load.
,2015-12-10 00:11:29.924 ThaliTest[547:557065] Finished load of: file:///var/mobile/Containers/Bundle/Application/A236DF20-8E59-48EA-BB5A-1AF20BD4BCD0/ThaliTest.app/www/index.html
,2015-12-10 00:11:30.135 ThaliTest[547:557065] JXcore Cordova plugin initializing
,2015-12-10 00:11:30.137 ThaliTest[547:557253] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5-1_PT9815
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,serverPort is 54392
,2015-12-10 00:19:38.302 ThaliTest[547:557253] jxcore: startBroadcasting
,2015-12-10 00:19:38.315 ThaliTest[547:557253] server: starting Apple-Iphone5-1_PT9815.s7QXZQ==
2015-12-10 00:19:38.316 ThaliTest[547:557253] multipeer session: start timer: 0x1deb76f0
2015-12-10 00:19:38.317 ThaliTest[547:557253] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT9815
2015-12-10 00:19:38.317 ThaliTest[547:557253] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-09T23:19:38.319Z SendDataTCPServer.js: TCP/IP server is bound to port: 54392
,2015-12-10 00:19:41.915 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5811.hStH7w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:19:41.921Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:19:41.921Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:19:41.921Z SendDataConnector.js: do connect now
,2015-12-10 00:19:41.922 ThaliTest[547:557253] jxcore: connect Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:41.923 ThaliTest[547:557253] client session: connect
,2015-12-10 00:19:41.924 ThaliTest[547:557253] client session: stateChange:0->1 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:47.855 ThaliTest[547:557065] multipeer session: reset timer
2015-12-10 00:19:47.856 ThaliTest[547:557065] multipeer session: stop timer
2015-12-10 00:19:47.856 ThaliTest[547:557065] multipeer session: start timer: 0x1deb76f0
2015-12-10 ,00:19:47.857 ThaliTest[547:557065] server session: connect
2015-12-10 00:19:47.858 ThaliTest[547:557065] server session: stateChange:0->1 Apple-Iphone6-1_PT5811
2015-12-10 00:19:47.873 ThaliTest[547:557065] server: accepting invitation Apple-Iphone6-1_PT5811
,2015-12-10 00:19:50.651 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1537.Uf7bCw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:50.710 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6044.nbqPWA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 00:19:51.177 ThaliTest[547:557065] multipeer session: reset timer
2015-12-10 00:19:51.177 ThaliTest[547:557065] multipeer session: stop timer
2015-12-10 00:19:51.177 ThaliTest[547:557065] multipeer session: start timer: 0x1deb76f0
2015-12-10 00:19:51.177 ThaliTest[547:557065] server session: connect
2015-12-10 00:19:51.177 ThaliTest[547:557065] server session: stateChange:0->1 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:51.185 ThaliTest[547:557065] server: accepting invitation Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:52.769 ThaliTest[547:557065] multipeer session: reset timer
2015-12-10 00:19:52.770 ThaliTest[547:557065] multipeer session: stop timer
2015-12-10 00:19:52.771 ThaliTest[547:557065] multipeer session: start timer: 0x1deb76f0
2015-12-10 ,00:19:52.771 ThaliTest[547:557065] server session: connect
2015-12-10 00:19:52.771 ThaliTest[547:557065] server session: stateChange:0->1 Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:52.778 ThaliTest[547:557065] server: accepting invitation Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:56.017 ThaliTest[547:558175] server session: connected
2015-12-10 00:19:56.017 ThaliTest[547:558175] server session: stateChange:1->2 Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:56.053 ThaliTest[547:557065] server relay: connected (to port: 54392)
2015-12-09T23:19:56.054Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:56.417Z SendDataTCPServer.js: TCP/IP server has received 12714 bytes of data
,2015-12-09T23:19:56.432Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-09T23:19:56.606Z SendDataTCPServer.js: TCP/IP server has received 28186 bytes of data
,2015-12-09T23:19:56.620Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:56.729 ThaliTest[547:558166] server session: not connected Apple-IpadAir2-1_PT6044
,2015-12-10 00:19:58.394 ThaliTest[547:558171] server session: connected
2015-12-10 00:19:58.394 ThaliTest[547:558171] server session: stateChange:1->2 Apple-Iphone6-1_PT5811
,2015-12-10 00:19:58.428 ThaliTest[547:557065] server relay: connected (to port: 54392)
,2015-12-09T23:19:58.435Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-10 00:19:58.481 ThaliTest[547:558175] client session: connected
2015-12-10 00:19:58.481 ThaliTest[547:558175] client session: stateChange:1->2 Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:19:58.482 ThaliTest[547:558175] client session: fireConnectCallback: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:19:58.482 ThaliTest[547:558175] jxcore: connect: success
2015-12-09T23:19:58.486Z SendDataConnector.js: CLIENT connected to 54397, error: null
2015-12-09T23:19:58.486Z SendDataConnector.js: CLIENT starting client 
2015-12-10 00:19:58.489 ThaliTest[547:557065] client: relay established
2015-12-10 00:19:58.490 ThaliTest[547:557065] client: new accepted socket: 0x1decebb0
,2015-12-09T23:19:58.503Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-10 00:19:59.102 ThaliTest[547:558173] server session: connected
,2015-12-10 00:19:59.103 ThaliTest[547:558173] server session: stateChange:1->2 Apple-Iphone5s-1_PT1537
,2015-12-10 00:19:59.129 ThaliTest[547:557065] server relay: connected (to port: 54392)
,2015-12-09T23:19:59.132Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T23:19:59.552Z SendDataTCPServer.js: TCP/IP server has received 8334 bytes of data
,2015-12-09T23:19:59.566Z SendDataTCPServer.js: TCP/IP server has received 36946 bytes of data
,2015-12-09T23:19:59.582Z SendDataTCPServer.js: TCP/IP server has received 63084 bytes of data
,2015-12-09T23:19:59.597Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:19:59.652 ThaliTest[547:558166] server session: not connected Apple-Iphone5s-1_PT1537
,2015-12-09T23:19:59.776Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T23:19:59.839Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T23:20:00.125Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-09T23:20:00.517Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-09T23:20:00.764Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-09T23:20:00.951Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T23:20:01.098Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-09T23:20:01.353Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-09T23:20:01.486Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-09T23:20:01.773Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-09T23:20:02.071Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-09T23:20:02.356Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T23:20:02.640Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-09T23:20:02.791Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-09T23:20:03.092Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-09T23:20:03.540Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T23:20:03.666Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T23:20:04.105Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-09T23:20:04.325Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-09T23:20:04.441Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T23:20:04.576Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-09T23:20:04.940Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-09T23:20:05.168Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-09T23:20:05.425Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-09T23:20:05.735Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-09T23:20:06.082Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-09T23:20:06.233Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-09T23:20:06.492Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-09T23:20:06.742Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-09T23:20:06.955Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-10 00:20:07.317 ThaliTest[547:558175] client session: not connected Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:07.319 ThaliTest[547:558175] client session: onLinkFailure: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:07.319 ThaliTest[547,:558175] client session: disconnect
2015-12-10 00:20:07.319 ThaliTest[547:558175] client session: stateChange:2->0 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:20:07.321 ThaliTest[547:558175] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:20:07.352Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-09T23:20:07.416Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-09T23:20:07.870Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-09T23:20:07.884Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-09T23:20:07.971Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-09T23:20:08.515Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-09T23:20:08.579Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-09T23:20:08.715Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-09T23:20:08.766Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-09T23:20:08.868Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-09T23:20:08.931Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-09T23:20:08.983Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-09T23:20:09.022Z SendDataConnector.js: Receiving data timeout now
,2015-12-09T23:20:09.023Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09T23:20:09.024Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09T23:20:09.025Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T23:20:09.026Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-09T23:20:09.112Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-09T23:20:09.162Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-09T23:20:09.175Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-09T23:20:09.201Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10 00:20:12.589 ThaliTest[547:558173] server session: not connected Apple-Iphone6-1_PT5811
,2015-12-09T23:20:14.036Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:20:14.037Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:20:14.038Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:20:19.049 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:20:19.050 ThaliTest[547:557253] jxcore: disconnect: fail
2015-12-09T23:20:19.050Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5811.hStH7w==,
2015-12-09T23:20:19.051Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT5811.hStH7w== with availability status: true
2015-12-09T23:20:19.051Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:20:19.052Z SendDataConnector.js: do connect now
,2015-12-10 00:20:19.054 ThaliTest[547:557253] jxcore: connect Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:19.054 ThaliTest[547:557253] client session: connect
2015-12-10 00:20:19.054 ThaliTest[547:557253] client session: stateChange:0->1 Apple-Iphon,e6-1_PT5811.hStH7w==
,2015-12-10 00:20:22.772 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:20:22.815 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:20:22.819 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:20:22.819 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:20:45.537 ThaliTest[547:557065] multipeer session: reset timer
2015-12-10 00:20:45.537 ThaliTest[547:557065] multipeer session: stop timer
2015-12-10 00:20:45.537 ThaliTest[547:557065] multipeer session: start timer: 0x1deb76f0
2015-12-10 ,00:20:45.537 ThaliTest[547:557065] server: disconnecting to refresh session (Apple-Iphone6-1_PT5811)
2015-12-10 00:20:45.537 ThaliTest[547:557065] server session: disconnect
2015-12-10 00:20:45.538 ThaliTest[547:557065] server session: stateChange:2->0 Apple-Iphone6-1_PT5811
,2015-12-10 00:20:45.542 ThaliTest[547:557065] server session: connect
2015-12-10 00:20:45.542 ThaliTest[547:557065] server session: stateChange:0->1 Apple-Iphone6-1_PT5811
2015-12-09T23:20:45.544Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-10 00:20:45.552 ThaliTest[547:557065] server: accepting invitation Apple-Iphone6-1_PT5811
,2015-12-10 00:20:48.291 ThaliTest[547:558486] server session: connected
2015-12-10 00:20:48.291 ThaliTest[547:558486] server session: stateChange:1->2 Apple-Iphone6-1_PT5811
,2015-12-09T23:20:48.295Z SendDataTCPServer.js: TCP/IP server connected
2015-12-10 00:20:48.296 ThaliTest[547:557065] server relay: connected (to port: 54392)
,2015-12-09T23:20:49.526Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-09T23:20:49.829Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-09T23:20:50.124Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-09T23:20:50.273Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-09T23:20:50.469Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-10 00:20:50.669 ThaliTest[547:558541] client session: not connected Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:50.670 ThaliTest[547:558541] client session: onLinkFailure: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:50.670 ThaliTest[547,:558541] client session: disconnect
2015-12-10 00:20:50.670 ThaliTest[547:558541] client session: stateChange:1->0 Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:20:50.671 ThaliTest[547:558541] client session: fireConnectCallback: Apple-Iphone6-1_PT5811.h,StH7w==
2015-12-10 00:20:50.671 ThaliTest[547:558541] jxcore: connect: fail: Peer disconnected
2015-12-09T23:20:50.673Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-09T23:20:50.673Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-09T23:20:50.673Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-09T23:20:50.673Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T23:20:50.788Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-09T23:20:50.872Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-09T23:20:51.163Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-09T23:20:51.372Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-09T23:20:51.510Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-09T23:20:51.575Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-09T23:20:51.750Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-09T23:20:52.267Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-09T23:20:52.557Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-09T23:20:52.709Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-09T23:20:52.951Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-09T23:20:53.087Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-09T23:20:53.348Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-09T23:20:53.669Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-09T23:20:53.867Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-09T23:20:53.941Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-09T23:20:54.140Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-09T23:20:54.330Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-09T23:20:54.466Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-09T23:20:54.603Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-09T23:20:54.765Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-09T23:20:54.926Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-09T23:20:55.062Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-09T23:20:55.578Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-09T23:20:55.677Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:20:55.677Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-09T23:20:55.678Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09T23:20:55.880Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-09T23:20:56.019Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-09T23:20:56.227Z SendDataTCPServer.js: TCP/IP server has received 70000 bytes of data
,2015-12-10 00:20:57.910 ThaliTest[547:558543] server session: not connected Apple-Iphone6-1_PT5811
,2015-12-10 00:21:00.683 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:21:00.683 ThaliTest[547:557253] jxcore: disconnect: fail
2015-12-09T23:21:00.684Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5811.hStH7w==,
2015-12-09T23:21:00.684Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT5811.hStH7w== with availability status: true
2015-12-09T23:21:00.684Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5811.hStH7w==
2015-12-09T23:21:00.685Z SendDataConnector.js: do connect now
,2015-12-10 00:21:00.686 ThaliTest[547:557253] jxcore: connect Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:00.686 ThaliTest[547:557253] client session: connect
2015-12-10 00:21:00.687 ThaliTest[547:557253] client session: stateChange:0->1 Apple-Iphon,e6-1_PT5811.hStH7w==
,2015-12-10 00:21:03.246 ThaliTest[547:558543] client session: connected
,2015-12-10 00:21:03.246 ThaliTest[547:558543] client session: stateChange:1->2 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:21:03.282 ThaliTest[547:558547] client session: fireConnectCallback: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:03.282 ThaliTest[547:558547] jxcore: connect: success
2015-12-09T23:21:03.282Z SendDataConnector.js: CLIENT connected to 5,4405, error: null
2015-12-09T23:21:03.283Z SendDataConnector.js: CLIENT starting client 
2015-12-10 00:21:03.284 ThaliTest[547:557065] client: relay established
2015-12-10 00:21:03.285 ThaliTest[547:557065] client: new accepted socket: 0x1df864a0
,2015-12-09T23:21:03.297Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:21:05.372Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T23:21:06.483Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T23:21:07.852Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T23:21:08.811Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T23:21:09.176Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-09T23:21:10.051Z SendDataConnector.js: CLIENT is data received : 60000
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,2015-12-09T23:21:10.379Z SendDataConnector.js: CLIENT is data received : 70000
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-09T23:21:11.623Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T23:21:12.805Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T23:21:13.235Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:21:13.236Z SendDataConnector.js: got all data for this round
,2015-12-09T23:21:13.239Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:21:13.239Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:21:13.239 ThaliTest[547:557253] jxcore: disconnect
,2015-12-10 00:21:13.240 ThaliTest[547:557253] client session: disconnectFromPeer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:13.241 ThaliTest[547:557253] client session: disconnect
,2015-12-10 00:21:13.241 ThaliTest[547:557253] client session: stateChange:2->0 Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:21:13.246 ThaliTest[547:557253] jxcore: disconnect: success
2015-12-09T23:21:13.246Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5811.hStH7w==
---- round done--------
device[2]: Apple-Iphone5s-1_PT1537.Uf,7bCw==
2015-12-09T23:21:13.247Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-09T23:21:13.248Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-09T23:21:13.248Z SendDataConnector.js: do connect now
,2015-12-10 00:21:13.248 ThaliTest[547:557253] jxcore: connect Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:21:13.252 ThaliTest[547:557253] client session: connect
2015-12-10 00:21:13.252 ThaliTest[547:557253] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:21:15.577 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:21:15.578 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:15.732 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:17.300 ThaliTest[547:558543] client session: connected
2015-12-10 00:21:17.300 ThaliTest[547:558543] client session: stateChange:1->2 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:17.330 ThaliTest[547:558614] client session: fireConnectCallback: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:21:17.330 ThaliTest[547:558614] jxcore: connect: success
2015-12-09T23:21:17.331Z SendDataConnector.js: CLIENT connected to 54412, error: null
2015-12-09T23:21:17.331Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:21:17.333 ThaliTest[547:557065] client: relay established
2015-12-10 00:21:17.334 ThaliTest[547:557065] client: new accepted socket: 0x1ddf6680
,2015-12-09T23:21:17.346Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T23:21:19.468Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T23:21:19.855Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-09T23:21:20.029Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:21:20.030Z SendDataConnector.js: got all data for this round
,2015-12-09T23:21:20.031Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:21:20.032Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:21:20.033 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:21:20.033 ThaliTest[547:557253] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:20.034 ThaliTest[547:557253] client session: disconnect
2015-12-10 00:21:20.035 ThaliTest[547:557253] client session: stateChange:2->0 Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:21:20.041 ThaliTest[547:557253] jxcore: disconnect: success
2015-12-09T23:21:20.042Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1537.Uf7bCw==
---- round done--------
device[3]: Apple-IpadAir2-1_PT6044.n,bqPWA==
2015-12-09T23:21:20.043Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:21:20.043Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:21:20.043Z SendDataConnector.js: do connect now
,2015-12-10 00:21:20.044 ThaliTest[547:557253] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:21:20.049 ThaliTest[547:557253] client session: connect
2015-12-10 00:21:20.049 ThaliTest[547:557253] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT6044.nbqPWA==
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
,2015-12-10 00:21:45.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-10 00:21:53.056 ThaliTest[547:558613] client session: not connected Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:21:53.056 ThaliTest[547:558613] client session: onLinkFailure: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:21:53.056 ThaliTest[5,47:558613] client session: disconnect
2015-12-10 00:21:53.057 ThaliTest[547:558613] client session: stateChange:1->0 Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:21:53.058 ThaliTest[547:558613] client session: fireConnectCallback: Apple-IpadAir2-1_PT60,44.nbqPWA==
2015-12-10 00:21:53.058 ThaliTest[547:558613] jxcore: connect: fail: Peer disconnected
2015-12-09T23:21:53.059Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-09T23:21:53.060Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T23:21:53.060Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-09T23:21:58.075Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:21:58.076Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:03.083 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:22:03.083 ThaliTest[547:557253] jxcore: disconnect: fail
2015-12-09T23:22:03.084Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:22:03.084Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6044.nbqPWA== with availability status: true
2015-12-09T23:22:03.085Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:22:03.085Z SendDataConnector.js: do connect now
2015-12-10 00:22:03.086 ThaliTest[547:557253] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:03.087 ThaliTest[547:557253] client session: connect
,2015-12-10 00:22:03.087 ThaliTest[547:557253] client session: stateChange:0->1 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:22:03.095 ThaliTest[547:557065] client: lost peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:03.095 ThaliTest[547:557065] client session: onPeerLost: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:03.095 ThaliTest[547:557065] client session: onLinkFailure: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:03.095 ThaliTest[547:557065] client session: disconnect
,2015-12-10 00:22:03.095 ThaliTest[547:557065] client session: stateChange:1->0 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:22:03.149 ThaliTest[547:557065] client session: fireConnectCallback: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:03.150 ThaliTest[547:557065] jxcore: connect: fail: Peer disconnected
,2015-12-09T23:22:03.153Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-09T23:22:03.153Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-09T23:22:03.153Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6044.nbqPWA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-09T23:22:08.163Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:22:08.163Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-10 00:22:13.173 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:22:13.173 ThaliTest[547:557253] jxcore: disconnect: fail
2015-12-09T23:22:13.174Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==,
2015-12-09T23:22:13.174Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6044.nbqPWA== with availability status: true
2015-12-09T23:22:13.174Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-09T23:22:13.175Z SendDataConnector.js: do connect now
,2015-12-10 00:22:13.176 ThaliTest[547:557253] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:13.176 ThaliTest[547:557253] client: connect: unreachable Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:13.177 ThaliTest[547:557253] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T23:22:13.177Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T23:22:13.177Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T23:22:13.178Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10 00:22:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:22:15.567 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:22:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:22:15.571 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT6044.nbqPWA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-09T23:22:18.183Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-09T23:22:18.184Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:23.202 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:22:23.202 ThaliTest[547:557253] jxcore: disconnect: fail
2015-12-09T23:22:23.203Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==,
2015-12-09T23:22:23.203Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6044.nbqPWA== with availability status: true
2015-12-09T23:22:23.204Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6044.nbqPWA==
20,15-12-09T23:22:23.204Z SendDataConnector.js: do connect now
,2015-12-10 00:22:23.205 ThaliTest[547:557253] jxcore: connect Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:23.206 ThaliTest[547:557253] client session: connect
2015-12-10 00:22:23.206 ThaliTest[547:557253] client session: stateChange:0->1 Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:36.013 ThaliTest[547:558770] client session: connected
2015-12-10 00:22:36.014 ThaliTest[547:558770] client session: stateChange:1->2 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:22:36.060 ThaliTest[547:558826] client session: fireConnectCallback: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:22:36.060 ThaliTest[547:558826] jxcore: connect: success
2015-12-09T23:22:36.061Z SendDataConnector.js: CLIENT connected to ,54434, error: null
2015-12-09T23:22:36.061Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 00:22:36.063 ThaliTest[547:557065] client: relay established
2015-12-10 00:22:36.064 ThaliTest[547:557065] client: new accepted socket: 0x1dbb3ea0
,2015-12-09T23:22:36.077Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-09T23:22:36.616Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-09T23:22:36.912Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-09T23:22:37.049Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T23:22:37.171Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T23:22:37.172Z SendDataConnector.js: got all data for this round
,2015-12-09T23:22:37.174Z SendDataConnector.js: CLIENT Stop now
2015-12-09T23:22:37.174Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 00:22:37.175 ThaliTest[547:557253] jxcore: disconnect
2015-12-10 00:22:37.175 ThaliTest[547:557253] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:22:37.176 ThaliTest[547:557253] client session: disconnect
2015-12-10 00:22:37.177 ThaliTest[547:557253] client session: stateChange:2->0 Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:22:37.187 ThaliTest[547:557253] jxcore: disconnect: success
2015-12-09T23:22:37.188Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6044.nbqPWA==
---- round done--------
weAreDoneNow , resultArray.length: 3,
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT9815","time":178897,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5811.hStH7w==","time":91316,"result":"OK","connections":3,"do,neRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT1537.Uf7bCw==","time":6782,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6044.nbqPWA==","time":77130,"r,esult":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 91316 ms, 99% : 91316 ms, 95 : 91316 ms, 90% : 91316 ms.
Result count 3, range 6782 ms to  91316 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-09T23:22:37.196Z SendDataConnector.js: CLIEN,T Stop now
2015-12-09T23:22:37.197Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:22:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:22:45.572 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:22:45.572 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:22:45.572 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:23:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:23:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:23:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-10 00:23:17.981 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:23:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:23:45.568 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:23:45.574 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:23:45.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:24:15.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:24:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:24:45.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:24:45.574 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:24:45.575 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:25:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:25:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:25:15.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:25:15.575 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:25:45.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:26:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:26:15.568 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:26:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:26:15.572 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
Error type "connect_error" when connecting to the test server
,2015-12-10 00:26:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:26:45.570 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:26:45.572 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:26:45.573 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,2015-12-10 00:27:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:27:15.572 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:27:15.573 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:27:15.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:27:45.538 ThaliTest[547:557065] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:28:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:28:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:28:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:28:15.575 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-10 00:28:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:28:45.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:28:45.573 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:28:45.574 ThaliTest[547:557065] client: fou,nd peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:29:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:29:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:29:15.571 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:29:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:29:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:29:45.574 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:29:45.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:29:45.574 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:30:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:30:15.570 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:30:15.574 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:30:15.575 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,2015-12-10 00:30:45.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:31:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:31:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:31:15.570 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:31:15.570 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
Error type "connect_error" when connecting to the test server
,2015-12-10 00:31:45.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:32:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:32:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:32:15.569 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:32:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:32:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:32:45.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:32:45.569 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,2015-12-10 00:32:45.576 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:33:15.538 ThaliTest[547:557065] multipeer session: restart
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
,2015-12-10 00:33:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:33:45.570 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:33:45.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:33:45.571 ThaliTest[547:557065] client: fou,nd peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:34:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:34:15.568 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:34:15.572 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:34:15.572 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-10 00:34:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:34:46.555 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
,2015-12-10 00:34:46.559 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:34:46.559 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:35:15.539 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:35:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:35:15.571 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:35:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,2015-12-10 00:35:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:35:45.566 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:35:45.567 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,2015-12-10 00:35:45.734 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:36:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:36:15.570 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:36:15.570 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:36:15.571 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:36:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:36:45.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:36:45.569 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:36:45.570 ThaliTest[547:557065] client: fou,nd peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:37:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:37:16.558 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:37:16.558 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:37:16.558 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
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
,2015-12-10 00:37:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:37:45.569 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:37:45.570 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:37:45.570 ThaliTest[547:557065] client: fo,und peer: Apple-Iphone6-1_PT5811.hStH7w==
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
,2015-12-10 00:38:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:38:15.567 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:38:15.567 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
2015-12-10 00:38:15.568 ThaliTest[547:557065] client: fo,und peer: Apple-Iphone6-1_PT5811.hStH7w==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:38:45.538 ThaliTest[547:557065] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-10 00:39:15.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:39:15.568 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:39:15.569 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:15.569 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-10 00:39:45.538 ThaliTest[547:557065] multipeer session: restart
,2015-12-10 00:39:45.569 ThaliTest[547:557065] client: found peer: Apple-Iphone6-1_PT5811.hStH7w==
2015-12-10 00:39:45.571 ThaliTest[547:557065] client: found peer: Apple-Iphone5s-1_PT1537.Uf7bCw==
2015-12-10 00:39:45.572 ThaliTest[547:557065] client: found peer: Apple-IpadAir2-1_PT6044.nbqPWA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
