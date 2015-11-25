#### Test 5133502830f515a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/337B6FA0-BF70-46B7-AA6B-F3861DF0C206/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/337B6FA0-BF70-46B7-AA6B-F3861DF0C206/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502830f515a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7C9F5848-4837-48DA-A131-C87C9BF13C40/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55326"
,(lldb)     command script import "/tmp/337B6FA0-BF70-46B7-AA6B-F3861DF0C206/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 11:08:52.684 ThaliTest[1649:1288224] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36627C61-6B8E-4ABD-908A-F5B1CFB3EC21/Library/Cookies/Cookies.binarycookies
,2015-11-25 11:08:53.059 ThaliTest[1649:1288224] Apache Cordova native platform version 3.9.2 is starting.
2015-11-25 11:08:53.060 ThaliTest[1649:1288224] Multi-tasking -> Device: YES, App: YES
,2015-11-25 11:08:53.069 ThaliTest[1649:1288224] Unlimited access to network resources
,2015-11-25 11:08:53.075 ThaliTest[1649:1288224] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 11:08:56.559 ThaliTest[1649:1288224] Resetting plugins due to page load.
,2015-11-25 11:08:56.894 ThaliTest[1649:1288224] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/7C9F5848-4837-48DA-A131-C87C9BF13C40/ThaliTest.app/www/index.html
,2015-11-25 11:08:57.021 ThaliTest[1649:1288224] JXcore Cordova plugin initializing
,2015-11-25 11:08:57.022 ThaliTest[1649:1288360] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT5679
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 61645
,2015-11-25 11:15:32.163 ThaliTest[1649:1288360] jxcore: startBroadcasting
,2015-11-25 11:15:32.173 ThaliTest[1649:1288360] server: starting Apple-Iphone6-1_PT5679.a5FFow==
2015-11-25 11:15:32.175 ThaliTest[1649:1288360] multipeer session: start timer: 0x1be6b2d0
,2015-11-25 11:15:32.185 ThaliTest[1649:1288224] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:15:32.176 ThaliTest[1649:1288360] THEMultipeerSession initialized peer Apple-Iphone6-1_PT5679
2015-11-25 11:15:32.186 ThaliTest[1649:1288360] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T10:15:32.187Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8682.g043PA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:15:32.191Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:15:32.192Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:15:32.192Z SendDataConnector.js: do connect now
,2015-11-25 11:15:32.193 ThaliTest[1649:1288360] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:15:32.194 ThaliTest[1649:1288360] client session: connect
,2015-11-25 11:15:32.195 ThaliTest[1649:1288360] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:15:33.175 ThaliTest[1649:1288224] multipeer session: reset timer
2015-11-25 11:15:33.176 ThaliTest[1649:1288224] multipeer session: stop timer
2015-11-25 11:15:33.177 ThaliTest[1649:1288224] multipeer session: start timer: 0x1be6b2d0
2015-,11-25 11:15:33.178 ThaliTest[1649:1288224] server session: connect
2015-11-25 11:15:33.178 ThaliTest[1649:1288224] server session: stateChange:0->1 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:33.189 ThaliTest[1649:1288224] server: accepting invitation Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:33.637 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
2015-11-25 11:15:33.641 ThaliTest[1649:1288224] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2339.pNGAWw==","peerName":"(null)","peerAvailable":true}]
2015-11-25 11:15:33.642 Th,aliTest[1649:1288224] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7626.iyJViA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), A,vailable: true
,2015-11-25 11:15:34.769 ThaliTest[1649:1288224] multipeer session: reset timer
2015-11-25 11:15:34.770 ThaliTest[1649:1288224] multipeer session: stop timer
2015-11-25 11:15:34.771 ThaliTest[1649:1288224] multipeer session: start timer: 0x1be6b2d0
2015-11-25 11:15:34.771 ThaliTest[1649:1288224] server session: connect
2015-11-25 11:15:34.772 ThaliTest[1649:1288224] server session: stateChange:0->1 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:34.782 ThaliTest[1649:1288224] server: accepting invitation Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:35.513 ThaliTest[1649:1288932] server session: connected
,2015-11-25 11:15:35.514 ThaliTest[1649:1288932] server session: stateChange:1->2 Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:35.527 ThaliTest[1649:1288224] server relay: connected (to port: 61645)
,2015-11-25T10:15:35.533Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:35.638Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-25T10:15:35.656Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-25T10:15:35.673Z SendDataTCPServer.js: TCP/IP server has received 74318 bytes of data
,2015-11-25T10:15:35.688Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-11-25T10:15:35.704Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:35.729 ThaliTest[1649:1288932] server session: not connected Apple-Iphone5s-1_PT9949
,2015-11-25 11:15:37.668 ThaliTest[1649:1288932] server session: connected
2015-11-25 11:15:37.669 ThaliTest[1649:1288932] server session: stateChange:1->2 Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:37.674 ThaliTest[1649:1288224] server relay: connected (to port: 61645)
2015-11-25T10:15:37.677Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:37.741Z SendDataTCPServer.js: TCP/IP server has received 12998 bytes of data
,2015-11-25T10:15:37.755Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-25T10:15:37.771Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-11-25T10:15:37.797Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-25T10:15:37.810Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-25T10:15:37.824Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-11-25T10:15:37.839Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:37.859 ThaliTest[1649:1288932] server session: not connected Apple-IpadAir2-1_PT2339
,2015-11-25 11:15:42.511 ThaliTest[1649:1288224] multipeer session: reset timer
2015-11-25 11:15:42.511 ThaliTest[1649:1288224] multipeer session: stop timer
2015-11-25 11:15:42.512 ThaliTest[1649:1288224] multipeer session: start timer: 0x1be6b2d0
2015-,11-25 11:15:42.512 ThaliTest[1649:1288224] server session: connect
2015-11-25 11:15:42.513 ThaliTest[1649:1288224] server session: stateChange:0->1 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:42.524 ThaliTest[1649:1288224] server: accepting invitation Apple-Iphone5-1_PT7626
,2015-11-25 11:15:44.964 ThaliTest[1649:1288930] server session: connected
2015-11-25 11:15:44.965 ThaliTest[1649:1288930] server session: stateChange:1->2 Apple-Iphone5-1_PT7626
,2015-11-25 11:15:44.985 ThaliTest[1649:1288224] server relay: connected (to port: 61645)
2015-11-25T10:15:44.991Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T10:15:45.132Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-25T10:15:45.148Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-11-25T10:15:45.165Z SendDataTCPServer.js: TCP/IP server has received 29760 bytes of data
,2015-11-25T10:15:45.177Z SendDataTCPServer.js: TCP/IP server has received 42656 bytes of data
,2015-11-25T10:15:45.189Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-11-25T10:15:45.204Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-25T10:15:45.218Z SendDataTCPServer.js: TCP/IP server has received 75392 bytes of data
,2015-11-25T10:15:45.232Z SendDataTCPServer.js: TCP/IP server has received 90272 bytes of data
,2015-11-25T10:15:45.246Z SendDataTCPServer.js: TCP/IP server has received 92256 bytes of data
,2015-11-25T10:15:45.469Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-25T10:15:45.485Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 11:15:45.515 ThaliTest[1649:1288930] server session: not connected Apple-Iphone5-1_PT7626
,2015-11-25 11:16:05.197 ThaliTest[1649:1288932] client session: not connected Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:05.198 ThaliTest[1649:1288932] client session: onLinkFailure: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:05.199 ThaliTest,[1649:1288932] client session: disconnect
2015-11-25 11:16:05.199 ThaliTest[1649:1288932] client session: stateChange:1->0 Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:05.200 ThaliTest[1649:1288932] client session: fireConnectCallback: Apple-Iphone6-,1_PT8682.g043PA==
2015-11-25 11:16:05.200 ThaliTest[1649:1288932] jxcore: connect: fail: Peer disconnected
,2015-11-25T10:16:05.202Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-25T10:16:05.203Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-25T10:16:05.204Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-25T10:16:10.212Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:16:10.213Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:16:12.510 ThaliTest[1649:1288224] multipeer session: restart
,2015-11-25 11:16:12.529 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:16:12.530 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:16:12.535 ThaliTest[1649:1288224] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:16:12.536 ThaliTest[1649:1288224] clien,t: found peer: Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:16:15.214 ThaliTest[1649:1288360] jxcore: disconnect
2015-11-25 11:16:15.214 ThaliTest[1649:1288360] jxcore: disconnect: fail
2015-11-25T10:16:15.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T10:16:15.216Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT8682.g043PA== with availability status: true
,2015-11-25T10:16:15.216Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T10:16:15.216Z SendDataConnector.js: do connect now
,2015-11-25 11:16:15.217 ThaliTest[1649:1288360] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:15.218 ThaliTest[1649:1288360] client session: connect
2015-11-25 11:16:15.219 ThaliTest[1649:1288360] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:16:42.511 ThaliTest[1649:1288224] multipeer session: restart
,2015-11-25 11:16:42.536 ThaliTest[1649:1288224] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:16:42.537 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:16:42.537 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:16:42.539 ThaliTest[1649:1288224] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:16:48.231 ThaliTest[1649:1289061] client session: not connected Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:48.231 ThaliTest[1649:1289061] client session: onLinkFailure: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:48.232 ThaliTest,[1649:1289061] client session: disconnect
2015-11-25 11:16:48.232 ThaliTest[1649:1289061] client session: stateChange:1->0 Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:48.233 ThaliTest[1649:1289061] client session: fireConnectCallback: Apple-Iphone6-,1_PT8682.g043PA==
2015-11-25 11:16:48.233 ThaliTest[1649:1289061] jxcore: connect: fail: Peer disconnected
,2015-11-25T10:16:48.235Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-25T10:16:48.235Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-25T10:16:48.236Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-11-25T10:16:53.244Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T10:16:53.244Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:16:58.250 ThaliTest[1649:1288360] jxcore: disconnect
2015-11-25 11:16:58.250 ThaliTest[1649:1288360] jxcore: disconnect: fail
2015-11-25T10:16:58.251Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T10:16:58.252Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT8682.g043PA== with availability status: true
,2015-11-25T10:16:58.252Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T10:16:58.252Z SendDataConnector.js: do connect now
,2015-11-25 11:16:58.253 ThaliTest[1649:1288360] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:16:58.254 ThaliTest[1649:1288360] client session: connect
2015-11-25 11:16:58.255 ThaliTest[1649:1288360] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:17:11.949 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,2015-11-25 11:17:12.511 ThaliTest[1649:1288224] multipeer session: restart
,2015-11-25 11:17:12.531 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5-1_PT7626.iyJViA==
2015-11-25 11:17:12.533 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:17:12.533 ThaliTest[1649:1288224] client: found peer: Apple-IpadAir2-1_PT2339.pNGAWw==
2015-11-25 11:17:12.534 ThaliTest[1649:1288224] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:17:18.466 ThaliTest[1649:1288224] client: lost peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:17:18.466 ThaliTest[1649:1288224] client session: onPeerLost: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-25 11:17:22.956 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-11-25 11:17:31.262 ThaliTest[1649:1289121] client session: not connected Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:17:31.263 ThaliTest[1649:1289121] client session: onLinkFailure: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:17:31.263 ThaliTest,[1649:1289121] client session: disconnect
2015-11-25 11:17:31.264 ThaliTest[1649:1289121] client session: stateChange:1->0 Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:17:31.264 ThaliTest[1649:1289121] client session: fireConnectCallback: Apple-Iphone6-,1_PT8682.g043PA==
2015-11-25 11:17:31.265 ThaliTest[1649:1289121] jxcore: connect: fail: Peer disconnected
,2015-11-25T10:17:31.267Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-11-25T10:17:31.268Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-11-25T10:17:31.268Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-25T10:17:36.281Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:17:36.281Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:17:41.283 ThaliTest[1649:1288360] jxcore: disconnect
2015-11-25 11:17:41.284 ThaliTest[1649:1288360] jxcore: disconnect: fail
2015-11-25T10:17:41.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043P,A==
2015-11-25T10:17:41.286Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT8682.g043PA== with availability status: true
2015-11-25T10:17:41.286Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25T10:17:41.287Z SendDataConnector.js: do connect now
,2015-11-25 11:17:41.288 ThaliTest[1649:1288360] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 11:17:41.289 ThaliTest[1649:1288360] client session: connect
2015-11-25 11:17:41.289 ThaliTest[1649:1288360] client session: stateChange:0->1 Apple,-Iphone6-1_PT8682.g043PA==
,2015-11-25 11:17:41.349 ThaliTest[1649:1288224] client: lost peer: Apple-Iphone5s-1_PT9949.0t9DBw==
2015-11-25 11:17:41.350 ThaliTest[1649:1288224] client session: onPeerLost: Apple-Iphone5s-1_PT9949.0t9DBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-11-25 11:17:41.355 ThaliTest[1649:1288224] client: found peer: Apple-Iphone5s-1_PT9949.0t9DBw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9949.0t9DBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 11:17:42.511 ThaliTest[1649:1288224] multipeer session: restart
2015-11-25 11:17:42.517 ThaliTest[1649:1288224] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x565e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 1649 stopped
* thread #1: tid = 0x13a820, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x13a820, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x000565e2 ThaliTest`main + 50

```
