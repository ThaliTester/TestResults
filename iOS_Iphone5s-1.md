#### Test 51790364c93db41_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2921BE27-C783-4FA3-8A5F-118F036B250B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2921BE27-C783-4FA3-8A5F-118F036B250B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51790364c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/255323BE-451B-4BEA-9BAC-9F437FAD24AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55625"
,(lldb)     command script import "/tmp/2921BE27-C783-4FA3-8A5F-118F036B250B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 14:26:21.021 ThaliTest[1635:1378239] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14EA2DA8-B465-460C-81F1-3E2972AE30FC/Library/Cookies/Cookies.binarycookies
,2015-11-25 14:26:21.453 ThaliTest[1635:1378239] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 14:26:21.454 ThaliTest[1635:1378239] Multi-tasking -> Device: YES, App: YES
,2015-11-25 14:26:21.464 ThaliTest[1635:1378239] Unlimited access to network resources
,2015-11-25 14:26:21.471 ThaliTest[1635:1378239] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 14:26:24.985 ThaliTest[1635:1378239] Resetting plugins due to page load.
,2015-11-25 14:26:25.199 ThaliTest[1635:1378239] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/255323BE-451B-4BEA-9BAC-9F437FAD24AC/ThaliTest.app/www/index.html
,2015-11-25 14:26:25.339 ThaliTest[1635:1378239] JXcore Cordova plugin initializing
,2015-11-25 14:26:25.343 ThaliTest[1635:1378454] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
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
,my name is : Apple-Iphone5s-1_PT8640
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 62157
2015-11-25 14:32:34.993 ThaliTest[1635:1378454] jxcore: startBroadcasting
,2015-11-25 14:32:35.005 ThaliTest[1635:1378454] server: starting Apple-Iphone5s-1_PT8640.H39DFw==
,2015-11-25 14:32:35.007 ThaliTest[1635:1378454] multipeer session: start timer: 0x19e89d30
2015-11-25 14:32:35.008 ThaliTest[1635:1378454] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8640
2015-11-25 14:32:35.009 ThaliTest[1635:1378454] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-25T13:32:35.015Z SendDataTCPServer.js: TCP/IP server is bound to port: 62157
,2015-11-25 14:32:35.133 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5807.1C0pWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T13:32:35.143Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T13:32:35.143Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T13:32:35.143Z SendDataConnector.js: do connect now
,2015-11-25 14:32:35.144 ThaliTest[1635:1378454] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:32:35.144 ThaliTest[1635:1378454] client session: connect
2015-11-25 14:32:35.144 ThaliTest[1635:1378454] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:32:35.256 ThaliTest[1635:1378239] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8475.0elZ3A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 14:32:35.651 ThaliTest[1635:1378239] multipeer session: reset timer
2015-11-25 14:32:35.652 ThaliTest[1635:1378239] multipeer session: stop timer
2015-11-25 14:32:35.653 ThaliTest[1635:1378239] multipeer session: start timer: 0x19e89d30
2015-,11-25 14:32:35.653 ThaliTest[1635:1378239] server session: connect
2015-11-25 14:32:35.654 ThaliTest[1635:1378239] server session: stateChange:0->1 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:35.666 ThaliTest[1635:1378239] server: accepting invitation Apple-Iphone6-1_PT8475
,2015-11-25 14:32:35.850 ThaliTest[1635:1378239] multipeer session: reset timer
,2015-11-25 14:32:35.851 ThaliTest[1635:1378239] multipeer session: stop timer
2015-11-25 14:32:35.854 ThaliTest[1635:1378239] multipeer session: start timer: 0x19e89d30
2015-11-25 14:32:35.854 ThaliTest[1635:1378239] server session: connect
2015-11-25 1,4:32:35.855 ThaliTest[1635:1378239] server session: stateChange:0->1 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:35.863 ThaliTest[1635:1378239] server: accepting invitation Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:36.883 ThaliTest[1635:1378239] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1710.FkeXvQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
2015-11-25 14:32:36.888 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6254.8TiZaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Availab,le: true
,2015-11-25 14:32:37.949 ThaliTest[1635:1379049] server session: connected
2015-11-25 14:32:37.950 ThaliTest[1635:1379049] server session: stateChange:1->2 Apple-Iphone6-1_PT8475
,2015-11-25 14:32:37.963 ThaliTest[1635:1378239] server relay: connected (to port: 62157)
,2015-11-25T13:32:37.971Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:38.079Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-11-25T13:32:38.098Z SendDataTCPServer.js: TCP/IP server has received 36946 bytes of data
,2015-11-25T13:32:38.115Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-11-25T13:32:38.129Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:38.169 ThaliTest[1635:1379055] server session: not connected Apple-Iphone6-1_PT8475
,2015-11-25 14:32:38.479 ThaliTest[1635:1379054] server session: connected
2015-11-25 14:32:38.482 ThaliTest[1635:1379054] server session: stateChange:1->2 Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:38.487 ThaliTest[1635:1378239] server relay: connected (to port: 62157)
,2015-11-25T13:32:38.495Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:38.558Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-25T13:32:38.584Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T13:32:38.599Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-11-25T13:32:38.931Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-25T13:32:38.949Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
2015-11-25T13:32:38.965Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
2015-11-25 14:32:38.970 ThaliTest[1635:1378239] multipeer session:, reset timer
2015-11-25 14:32:38.970 ThaliTest[1635:1378239] multipeer session: stop timer
2015-11-25 14:32:38.971 ThaliTest[1635:1378239] multipeer session: start timer: 0x19e89d30
2015-11-25 14:32:38.972 ThaliTest[1635:1378239] server session: connect,
2015-11-25 14:32:38.972 ThaliTest[1635:1378239] server session: stateChange:0->1 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:39.013 ThaliTest[1635:1378239] server: accepting invitation Apple-Iphone5-1_PT6254
2015-11-25T13:32:39.028Z SendDataTCPServer.js: TCP/IP server has received 93804 bytes of data
,2015-11-25T13:32:39.044Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:39.069 ThaliTest[1635:1379049] server session: not connected Apple-IpadAir2-1_PT1710
,2015-11-25 14:32:41.192 ThaliTest[1635:1379044] server session: connected
2015-11-25 14:32:41.193 ThaliTest[1635:1379044] server session: stateChange:1->2 Apple-Iphone5-1_PT6254
,2015-11-25 14:32:41.200 ThaliTest[1635:1378239] server relay: connected (to port: 62157)
2015-11-25T13:32:41.204Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T13:32:41.539Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-25T13:32:41.553Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-11-25T13:32:41.569Z SendDataTCPServer.js: TCP/IP server has received 24800 bytes of data
,2015-11-25T13:32:41.585Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-25T13:32:41.602Z SendDataTCPServer.js: TCP/IP server has received 54560 bytes of data
,2015-11-25T13:32:41.621Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-25T13:32:41.637Z SendDataTCPServer.js: TCP/IP server has received 72416 bytes of data
,2015-11-25T13:32:41.653Z SendDataTCPServer.js: TCP/IP server has received 88288 bytes of data
,2015-11-25T13:32:41.669Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 14:32:41.693 ThaliTest[1635:1379054] server session: not connected Apple-Iphone5-1_PT6254
,2015-11-25 14:33:08.148 ThaliTest[1635:1379108] client session: not connected Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:08.149 ThaliTest[1635:1379108] client session: onLinkFailure: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:08.150 ThaliTe,st[1635:1379108] client session: disconnect
2015-11-25 14:33:08.150 ThaliTest[1635:1379108] client session: stateChange:1->0 Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:08.151 ThaliTest[1635:1379108] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT5807.1C0pWw==
2015-11-25 14:33:08.151 ThaliTest[1635:1379108] jxcore: connect: fail: Peer disconnected
,2015-11-25T13:33:08.154Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-25T13:33:08.155Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-25T13:33:08.156Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-25 14:33:08.973 ThaliTest[1635:1378239] multipeer session: restart
,2015-11-25 14:33:08.996 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:33:08.997 ThaliTest[1635:1378239] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:33:08.997 ThaliTest[1635:1378239] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
2015-11-25 14:33:08.998 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T13:33:13.159Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T13:33:13.160Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:33:18.171 ThaliTest[1635:1378454] jxcore: disconnect
2015-11-25 14:33:18.172 ThaliTest[1635:1378454] jxcore: disconnect: fail
2015-11-25T13:33:18.173Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T13:33:18.174Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5807.1C0pWw== with availability status: true
2015-11-25T13:33:18.174Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015,-11-25T13:33:18.174Z SendDataConnector.js: do connect now
,2015-11-25 14:33:18.176 ThaliTest[1635:1378454] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:18.176 ThaliTest[1635:1378454] client session: connect
2015-11-25 14:33:18.177 ThaliTest[1635:1378454] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:33:38.973 ThaliTest[1635:1378239] multipeer session: restart
,2015-11-25 14:33:38.998 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
,2015-11-25 14:33:39.001 ThaliTest[1635:1378239] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:33:39.005 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:33:39.699 ThaliTest[1635:1378239] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
,2015-11-25 14:33:51.186 ThaliTest[1635:1379310] client session: not connected Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:51.187 ThaliTest[1635:1379310] client session: onLinkFailure: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:51.188 ThaliTe,st[1635:1379310] client session: disconnect
2015-11-25 14:33:51.188 ThaliTest[1635:1379310] client session: stateChange:1->0 Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:51.189 ThaliTest[1635:1379310] client session: fireConnectCallback: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:33:51.189 ThaliTest[1635:1379310] jxcore: connect: fail: Peer disconnected
,2015-11-25T13:33:51.191Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-25T13:33:51.192Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-25T13:33:51.192Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-25T13:33:56.198Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T13:33:56.198Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:34:01.204 ThaliTest[1635:1378454] jxcore: disconnect
2015-11-25 14:34:01.205 ThaliTest[1635:1378454] jxcore: disconnect: fail
2015-11-25T13:34:01.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5807.1C0p,Ww==
2015-11-25T13:34:01.206Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT5807.1C0pWw== with availability status: true
,2015-11-25T13:34:01.206Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T13:34:01.207Z SendDataConnector.js: do connect now
,2015-11-25 14:34:01.207 ThaliTest[1635:1378454] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:34:01.208 ThaliTest[1635:1378454] client session: connect
,2015-11-25 14:34:01.209 ThaliTest[1635:1378454] client session: stateChange:0->1 Apple-Iphone5s-1_PT5807.1C0pWw==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-11-25 14:34:08.973 ThaliTest[1635:1378239] multipeer session: restart
,2015-11-25 14:34:09.011 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5-1_PT6254.8TiZaA==
2015-11-25 14:34:09.012 ThaliTest[1635:1378239] client: found peer: Apple-Iphone6-1_PT8475.0elZ3A==
,2015-11-25 14:34:09.013 ThaliTest[1635:1378239] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 14:34:10.096 ThaliTest[1635:1378239] client: found peer: Apple-IpadAir2-1_PT1710.FkeXvQ==
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
,2015-11-25 14:34:34.217 ThaliTest[1635:1379310] client session: not connected Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:34:34.217 ThaliTest[1635:1379310] client session: onLinkFailure: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:34:34.218 ThaliTe,st[1635:1379310] client session: disconnect
2015-11-25 14:34:34.218 ThaliTest[1635:1379310] client session: stateChange:1->0 Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 14:34:34.219 ThaliTest[1635:1379310] client session: fireConnectCallback: Apple-Iphon,e5s-1_PT5807.1C0pWw==
2015-11-25 14:34:34.220 ThaliTest[1635:1379310] jxcore: connect: fail: Peer disconnected
,2015-11-25T13:34:34.222Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-11-25T13:34:34.223Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-25T13:34:34.223Z SendDataConnector.js: tryAgain afer: 5000 ms.
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-11-25 14:34:38.972 ThaliTest[1635:1378239] multipeer session: restart
2015-11-25 14:34:38.978 ThaliTest[1635:1378239] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x325e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x1507bf, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000325e2 ThaliTest`main + 50

```
