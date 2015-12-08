#### Test 52971095ef317fc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/7867227C-84C2-4F1F-AC21-835145EC0709/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7867227C-84C2-4F1F-AC21-835145EC0709/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095ef317fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0EB78ACB-0A18-4075-BA4F-9650264BB14B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51180"
,(lldb)     command script import "/tmp/7867227C-84C2-4F1F-AC21-835145EC0709/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:07:32.981 ThaliTest[495:296586] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1B0AC0F-03AA-4785-A99F-9298E56EE396/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:07:33.321 ThaliTest[495:296586] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:07:33.322 ThaliTest[495:296586] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:07:33.331 ThaliTest[495:296586] Unlimited access to network resources
,2015-12-08 17:07:33.341 ThaliTest[495:296586] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:07:42.431 ThaliTest[495:296586] Resetting plugins due to page load.
,2015-12-08 17:07:46.164 ThaliTest[495:296586] Finished load of: file:///var/mobile/Containers/Bundle/Application/0EB78ACB-0A18-4075-BA4F-9650264BB14B/ThaliTest.app/www/index.html
,2015-12-08 17:07:46.348 ThaliTest[495:296586] JXcore Cordova plugin initializing
2015-12-08 17:07:46.349 ThaliTest[495:296787] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT7651
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51679
,2015-12-08 17:14:44.134 ThaliTest[495:296787] jxcore: startBroadcasting
,2015-12-08 17:14:44.155 ThaliTest[495:296787] server: starting Apple-Iphone6-1_PT7651.u5AQgA==
,2015-12-08 17:14:44.160 ThaliTest[495:296787] multipeer session: start timer: 0x17f48500
,2015-12-08 17:14:44.179 ThaliTest[495:296787] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7651
,2015-12-08 17:14:44.181 ThaliTest[495:296787] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-08T16:14:44.184Z SendDataTCPServer.js: TCP/IP server is bound to port: 51679
,2015-12-08 17:14:45.318 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08T16:14:45.326Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8010.swwphA==
2015-12-08T16:14:45.326Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8010.swwphA==
2015-12-08T16:14:45.327Z SendDataConnector.js: do connect now
,2015-12-08 17:14:45.328 ThaliTest[495:296787] jxcore: connect Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:45.329 ThaliTest[495:296787] client session: connect
2015-12-08 17:14:45.329 ThaliTest[495:296787] client session: stateChange:0->1 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:46.173 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4957.VBxUsw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:14:46.534 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7186.b/2OUQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-08 17:14:47.006 ThaliTest[495:296586] multipeer session: reset timer
2015-12-08 17:14:47.007 ThaliTest[495:296586] multipeer session: stop timer
2015-12-08 17:14:47.008 ThaliTest[495:296586] multipeer session: start timer: 0x17f48500
2015-12-08 ,17:14:47.008 ThaliTest[495:296586] server session: connect
2015-12-08 17:14:47.009 ThaliTest[495:296586] server session: stateChange:0->1 Apple-Iphone5s-1_PT7186
2015-12-08 17:14:47.021 ThaliTest[495:296586] server: accepting invitation Apple-Iphone5s-1_PT7186
2015-12-08 17:14:47.034 ThaliTest[495:296586] multipeer session: reset timer
2015-12-08 17:14:47.034 ThaliTest[495:296586] multipeer session: stop timer
2015-12-08 17:14:47.038 ThaliTest[495:296586] multipeer session: start timer: 0x17f48500
2015-12-08 17:14:47.038 ThaliTest[495:296586] server session: connect
2015-12-08 17:14:47.039 ThaliTest[495:296586] server session: stateChange:0->1 Apple-Iphone5-1_PT8010
,2015-12-08 17:14:47.107 ThaliTest[495:296586] server: accepting invitation Apple-Iphone5-1_PT8010
,2015-12-08 17:14:47.126 ThaliTest[495:296586] multipeer session: reset timer
,2015-12-08 17:14:47.128 ThaliTest[495:296586] multipeer session: stop timer
,2015-12-08 17:14:47.129 ThaliTest[495:296586] multipeer session: start timer: 0x17f48500
,2015-12-08 17:14:47.131 ThaliTest[495:296586] server session: connect
2015-12-08 17:14:47.132 ThaliTest[495:296586] server session: stateChange:0->1 Apple-IpadAir2-1_PT4957
2015-12-08 17:14:47.147 ThaliTest[495:296586] server: accepting invitation Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:49.687 ThaliTest[495:297464] client session: connected
2015-12-08 17:14:49.687 ThaliTest[495:297464] client session: stateChange:1->2 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:49.695 ThaliTest[495:297464] client session: fireConnectCallback: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:49.696 ThaliTest[495:297464] jxcore: connect: success
,2015-12-08T16:14:49.698Z SendDataConnector.js: CLIENT connected to 51682, error: null
,2015-12-08T16:14:49.698Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:49.704 ThaliTest[495:296586] client: relay established
2015-12-08 17:14:49.704 ThaliTest[495:296586] client: new accepted socket: 0x17f60f20
,2015-12-08T16:14:49.719Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:14:49.996 ThaliTest[495:297494] server session: connected
2015-12-08 17:14:49.996 ThaliTest[495:297494] server session: stateChange:1->2 Apple-IpadAir2-1_PT4957
,2015-12-08 17:14:50.004 ThaliTest[495:296586] server relay: connected (to port: 51679)
,2015-12-08T16:14:50.006Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:14:50.127 ThaliTest[495:297523] server session: connected
2015-12-08 17:14:50.127 ThaliTest[495:297523] server session: stateChange:1->2 Apple-Iphone5s-1_PT7186
,2015-12-08 17:14:50.135 ThaliTest[495:296586] server relay: connected (to port: 51679)
,2015-12-08T16:14:50.140Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:14:50.208 ThaliTest[495:297494] server session: connected
2015-12-08 17:14:50.208 ThaliTest[495:297494] server session: stateChange:1->2 Apple-Iphone5-1_PT8010
,2015-12-08 17:14:50.211 ThaliTest[495:296586] server relay: connected (to port: 51679)
2015-12-08T16:14:50.212Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:14:50.262Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:50.262Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:50.264Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:14:50.265Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:50.266 ThaliTest[495:296787] jxcore: disconnect
2015-12-08 17:14:50.266 ThaliTest[495:296787] client session: disconnectFromPeer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:14:50.266 ThaliTest[495:296787] client session: disconnect
2,015-12-08 17:14:50.266 ThaliTest[495:296787] client session: stateChange:2->0 Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:14:50.273 ThaliTest[495:296787] jxcore: disconnect: success
2015-12-08T16:14:50.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8010.swwphA==
---- round done--------
device[2]: Apple-IpadAir2-1_PT4957.VB,xUsw==
2015-12-08T16:14:50.275Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:50.275Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08T16:14:50.275Z SendDataCon,nector.js: do connect now
2015-12-08 17:14:50.275 ThaliTest[495:296787] jxcore: connect Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:50.275 ThaliTest[495:296787] client session: connect
2015-12-08 17:14:50.276 ThaliTest[495:296787] client session: stateChange:0->1 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08T16:14:50.289Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-08T16:14:50.477Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
2015-12-08T16:14:50.478Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-08T16:14:50.493Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
2015-12-08T16:14:50.494Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
2015-12-08T16:14:50.508Z SendDataTCPServer.js: TCP/IP server has r,eceived 41610 bytes of data
2015-12-08T16:14:50.510Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
2015-12-08T16:14:50.523Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
2015-12-08T16:14:50.524Z SendDataTCPS,erver.js: TCP/IP server has received 100000 bytes of data
,2015-12-08T16:14:50.539Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:50.599 ThaliTest[495:297494] server session: not connected Apple-IpadAir2-1_PT4957
,2015-12-08T16:14:50.774Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-08 17:14:50.776 ThaliTest[495:297464] server session: not connected Apple-Iphone5s-1_PT7186
,2015-12-08T16:14:51.009Z SendDataTCPServer.js: TCP/IP server has received 6286 bytes of data
,2015-12-08T16:14:51.025Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
2015-12-08T16:14:51.040Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-08T16:14:51.080Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-08T16:14:51.095Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:14:51.206 ThaliTest[495:297463] server session: not connected Apple-Iphone5-1_PT8010
,2015-12-08 17:14:53.846 ThaliTest[495:297473] client session: connected
2015-12-08 17:14:53.848 ThaliTest[495:297473] client session: stateChange:1->2 Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:53.851 ThaliTest[495:297473] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:14:53.852 ThaliTest[495:297473] jxcore: connect: success
2015-12-08T16:14:53.854Z SendDataConnector.js: CLIENT connected to 51688, error: null
2015-12-08T16:14:53.854Z SendDataConnector.js: CLI,ENT starting client 
,2015-12-08 17:14:53.859 ThaliTest[495:296586] client: relay established
,2015-12-08 17:14:53.859 ThaliTest[495:296586] client: new accepted socket: 0x17f4e000
,2015-12-08T16:14:53.870Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:54.234Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:14:54.248Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:54.248Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:54.248Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:14:54.249Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:54.250 ThaliTest[495:296787] jxcore: disconnect
,2015-12-08 17:14:54.250 ThaliTest[495:296787] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:54.251 ThaliTest[495:296787] client session: disconnect
,2015-12-08 17:14:54.252 ThaliTest[495:296787] client session: stateChange:2->0 Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:14:54.318 ThaliTest[495:296787] jxcore: disconnect: success
,2015-12-08T16:14:54.319Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4957.VBxUsw==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:54.320Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:54.321Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08T16:14:54.321Z SendDataConnector.js: do connect now
,2015-12-08 17:14:54.321 ThaliTest[495:296787] jxcore: connect Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:54.322 ThaliTest[495:296787] client session: connect
,2015-12-08 17:14:54.323 ThaliTest[495:296787] client session: stateChange:0->1 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:57.425 ThaliTest[495:297463] client session: connected
2015-12-08 17:14:57.426 ThaliTest[495:297463] client session: stateChange:1->2 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:57.479 ThaliTest[495:297473] client session: fireConnectCallback: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:14:57.479 ThaliTest[495:297473] jxcore: connect: success
2015-12-08T16:14:57.480Z SendDataConnector.js: CLIENT connected to 51691, error: null
2015-12-08T16:14:57.481Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:14:57.485 ThaliTest[495:296586] client: relay established
2015-12-08 17:14:57.485 ThaliTest[495:296586] client: new accepted socket: 0x17b60750
,2015-12-08T16:14:57.497Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:14:57.889Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:14:57.900Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-08T16:14:57.900Z SendDataConnector.js: got all data for this round
,2015-12-08T16:14:57.901Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:14:57.901Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:14:57.902 ThaliTest[495:296787] jxcore: disconnect
,2015-12-08 17:14:57.903 ThaliTest[495:296787] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:57.903 ThaliTest[495:296787] client session: disconnect
,2015-12-08 17:14:57.903 ThaliTest[495:296787] client session: stateChange:2->0 Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:14:57.970 ThaliTest[495:296787] jxcore: disconnect: success
2015-12-08T16:14:57.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7186.b/2OUQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7651","time":13855,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT8010.swwphA==","time":4937,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT4957.VBxUsw==","time":3973,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7186.b/2OUQ==","time":3580,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4937 ms, 99% : 4937 ms, 95 : 4937 ms, 90% : 4937 ms.
Result count 3, range 3580 ms to  4937 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-12-08T16:14:57.975Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:14:57.975Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:15:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:15:17.179 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:15:17.182 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:15:17.182 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:15:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:15:47.176 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:15:47.176 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:16:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:16:17.176 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:16:17.176 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:16:17.185 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:16:27.326 ThaliTest[495:296586] client: lost peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:16:27.326 ThaliTest[495:296586] client session: onPeerLost: Apple-Iphone5-1_PT8010.swwphA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 17:16:28.517 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 17:16:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:16:47.176 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:16:47.178 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:16:47.424 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:16:56.099 ThaliTest[495:296586] client: lost peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:16:56.099 ThaliTest[495:296586] client session: onPeerLost: Apple-Iphone5-1_PT8010.swwphA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 17:17:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:17:17.173 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:17:17.174 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:17:17.176 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8010.swwphA==","peerName":"(null)","peerAvailable":true}]
,2015-12-08 17:17:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:17:47.178 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:17:47.178 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:17:47.180 ThaliTest[495:296586] client: fo,und peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:18:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:18:17.177 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:18:17.177 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:18:17.178 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,2015-12-08 17:18:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:18:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:18:47.170 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:18:47.179 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:19:17.132 ThaliTest[495:296586] multipeer session: restart
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
,2015-12-08 17:19:47.131 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:19:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:19:47.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:19:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
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
,2015-12-08 17:20:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:20:17.173 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:20:17.173 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:20:17.176 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:20:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:20:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:20:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:20:47.169 ThaliTest[495:296586] client: fou,nd peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:21:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:21:17.171 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:21:17.171 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:21:17.172 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:21:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:21:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:21:47.171 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:21:47.172 ThaliTest[495:296586] client: fou,nd peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:22:17.132 ThaliTest[495:296586] multipeer session: restart
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
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:22:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:22:47.165 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:22:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:22:47.168 ThaliTest[495:296586] client: fou,nd peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:23:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:23:17.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:23:17.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:23:17.171 ThaliTest[495:296586] client: fou,nd peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:23:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:23:47.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:23:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:23:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:24:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:24:17.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:24:17.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:24:17.171 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:24:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:24:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:24:47.170 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:24:47.172 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:25:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:25:17.171 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:25:17.172 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:25:17.173 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:25:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:25:47.170 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:25:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:25:47.172 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:26:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:26:17.173 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:17.174 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:26:17.174 ThaliTest[495:296586] client: fou,nd peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:26:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:26:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:26:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:26:47.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,2015-12-08 17:27:17.131 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:27:17.167 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:27:17.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:27:17.174 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:27:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:27:47.166 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:27:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:27:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:28:17.131 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:28:17.166 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:28:17.167 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:28:17.167 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:28:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:28:47.166 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:28:47.169 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:28:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:29:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:29:17.168 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:29:17.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
,2015-12-08 17:29:17.174 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:29:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:29:47.163 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:29:47.163 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:29:47.166 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:30:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:30:17.165 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:30:17.166 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:30:17.166 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:30:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:30:47.180 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:30:47.182 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:30:47.182 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:31:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:31:17.167 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:31:17.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:31:17.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:31:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:31:47.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:31:47.170 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:31:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
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
,2015-12-08 17:32:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:32:17.169 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:32:17.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:32:17.170 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,Wifi toggled for connection repairment
,2015-12-08 17:32:47.132 ThaliTest[495:296586] multipeer session: restart
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
,2015-12-08 17:33:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:33:17.167 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:33:17.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
2015-12-08 17:33:17.168 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
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
,Wifi toggled for connection repairment
,2015-12-08 17:33:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:33:47.167 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:33:47.168 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
,2015-12-08 17:33:47.174 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:34:17.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:34:17.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:34:17.172 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:34:17.172 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
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
,2015-12-08 17:34:47.132 ThaliTest[495:296586] multipeer session: restart
,2015-12-08 17:34:47.168 ThaliTest[495:296586] client: found peer: Apple-Iphone5-1_PT8010.swwphA==
2015-12-08 17:34:47.168 ThaliTest[495:296586] client: found peer: Apple-IpadAir2-1_PT4957.VBxUsw==
2015-12-08 17:34:47.170 ThaliTest[495:296586] client: found peer: Apple-Iphone5s-1_PT7186.b/2OUQ==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
