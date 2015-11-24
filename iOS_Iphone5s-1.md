#### Test 5133502802397d9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/792F54E5-B425-4573-8BFA-4C39FC5989D8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/792F54E5-B425-4573-8BFA-4C39FC5989D8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4B8A583-E318-4EFD-B52C-1C4A47CDF40D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54832"
,(lldb)     command script import "/tmp/792F54E5-B425-4573-8BFA-4C39FC5989D8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-24 17:03:42.227 ThaliTest[1516:1269390] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D256A63-F98C-4056-BBD8-626F3CA8D9B6/Library/Cookies/Cookies.binarycookies
,2015-11-24 17:03:42.642 ThaliTest[1516:1269390] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 17:03:42.644 ThaliTest[1516:1269390] Multi-tasking -> Device: YES, App: YES
,2015-11-24 17:03:42.652 ThaliTest[1516:1269390] Unlimited access to network resources
,2015-11-24 17:03:42.658 ThaliTest[1516:1269390] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 17:03:46.050 ThaliTest[1516:1269390] Resetting plugins due to page load.
,2015-11-24 17:03:46.394 ThaliTest[1516:1269390] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/E4B8A583-E318-4EFD-B52C-1C4A47CDF40D/ThaliTest.app/www/index.html
,2015-11-24 17:03:46.548 ThaliTest[1516:1269390] JXcore Cordova plugin initializing
,2015-11-24 17:03:46.550 ThaliTest[1516:1269508] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT8445
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 61435
,2015-11-24 17:10:23.668 ThaliTest[1516:1269508] jxcore: startBroadcasting
,2015-11-24 17:10:23.681 ThaliTest[1516:1269508] server: starting Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:23.682 ThaliTest[1516:1269508] multipeer session: start timer: 0x1b6a4b30
2015-11-24 17:10:23.683 ThaliTest[1516:1269508] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8445
2015-11-24 17:10:23.684 ThaliTest[1516:1269508] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-24T16:10:23.693Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-24 17:10:23.933 ThaliTest[1516:1269390] client: found peer: Apple-Iphone6-1_PT1630.4rgQcA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1630.4rgQcA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:23.941Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:23.946Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24T16:10:23.946Z SendDataConnector.js: do connect now
,2015-11-24 17:10:23.947 ThaliTest[1516:1269508] jxcore: connect Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:23.947 ThaliTest[1516:1269508] client session: connect
2015-11-24 17:10:23.948 ThaliTest[1516:1269508] client session: stateChange:0->1 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:24.305 ThaliTest[1516:1269390] multipeer session: reset timer
2015-11-24 17:10:24.305 ThaliTest[1516:1269390] multipeer session: stop timer
2015-11-24 17:10:24.305 ThaliTest[1516:1269390] multipeer session: start timer: 0x1b6a4b30
2015-11-24 17:10:24.305 ThaliTest[1516:1269390] server session: connect
2015-11-24 17:10:24.305 ThaliTest[1516:1269390] server session: stateChange:0->1 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:24.311 ThaliTest[1516:1269390] server: accepting invitation Apple-Iphone5-1_PT7498
,2015-11-24 17:10:24.514 ThaliTest[1516:1269390] multipeer session: reset timer
2015-11-24 17:10:24.515 ThaliTest[1516:1269390] multipeer session: stop timer
2015-11-24 17:10:24.515 ThaliTest[1516:1269390] multipeer session: start timer: 0x1b6a4b30
2015-11-24 17:10:24.516 ThaliTest[1516:1269390] server session: connect
2015-11-24 17:10:24.516 ThaliTest[1516:1269390] server session: stateChange:0->1 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:24.526 ThaliTest[1516:1269390] server: accepting invitation Apple-Iphone6-1_PT1630
,2015-11-24 17:10:25.449 ThaliTest[1516:1269390] client: found peer: Apple-IpadAir2-1_PT7208.gEcfnw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7208.gEcfnw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
2015-11-24 17:10:25.453 ThaliTest[1516:1269390] client: found peer: Apple-Iphone5-1_PT7498.cV5UxA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7498.cV5UxA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:26.464 ThaliTest[1516:1270075] client session: connected
,2015-11-24 17:10:26.466 ThaliTest[1516:1270075] client session: stateChange:1->2 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:26.473 ThaliTest[1516:1270075] client session: fireConnectCallback: Apple-Iphone6-1_PT1630.4rgQcA==
2015-11-24 17:10:26.475 ThaliTest[1516:1270075] jxcore: connect: success
,2015-11-24T16:10:26.479Z SendDataConnector.js: CLIENT connected to 61438, error: null
2015-11-24T16:10:26.479Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:26.483 ThaliTest[1516:1269390] client: relay established
2015-11-24 17:10:26.484 ThaliTest[1516:1269390] client: new accepted socket: 0x1b6bcab0
,2015-11-24T16:10:26.496Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24 17:10:26.515 ThaliTest[1516:1270064] server session: connected
2015-11-24 17:10:26.516 ThaliTest[1516:1270064] server session: stateChange:1->2 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:26.529 ThaliTest[1516:1269390] server relay: connected (to port: 61435)
,2015-11-24T16:10:26.603Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:26.650Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-24T16:10:26.663Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:26.664Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:26.665Z SendDataConnector.js: CLIENT Stop now
,2015-11-24T16:10:26.665Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:26.666 ThaliTest[1516:1269508] jxcore: disconnect
,2015-11-24 17:10:26.667 ThaliTest[1516:1269508] client session: disconnectFromPeer: Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:26.668 ThaliTest[1516:1269508] client session: disconnect
,2015-11-24 17:10:26.669 ThaliTest[1516:1269508] client session: stateChange:2->0 Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:26.672 ThaliTest[1516:1269508] jxcore: disconnect: success
,2015-11-24T16:10:26.673Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1630.4rgQcA==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:26.675Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:26.675Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:26.676Z SendDataConnector.js: do connect now
,2015-11-24 17:10:26.676 ThaliTest[1516:1269508] jxcore: connect Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:26.677 ThaliTest[1516:1269508] client session: connect
,2015-11-24 17:10:26.678 ThaliTest[1516:1269508] client session: stateChange:0->1 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:26.934 ThaliTest[1516:1270076] server session: connected
2015-11-24 17:10:26.934 ThaliTest[1516:1270076] server session: stateChange:1->2 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:26.937 ThaliTest[1516:1269390] server relay: connected (to port: 61435)
,2015-11-24T16:10:26.946Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:26.960Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-11-24T16:10:26.974Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-11-24T16:10:26.986Z SendDataTCPServer.js: TCP/IP server has received 60512 bytes of data
,2015-11-24T16:10:26.999Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-11-24T16:10:27.012Z SendDataTCPServer.js: TCP/IP server has received 77376 bytes of data
,2015-11-24T16:10:27.036Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-11-24T16:10:27.049Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24T16:10:27.050Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-11-24T16:10:27.063Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-24 17:10:27.095 ThaliTest[1516:1270064] server session: not connected Apple-Iphone5-1_PT7498
,2015-11-24T16:10:27.165Z SendDataTCPServer.js: TCP/IP server has received 77704 bytes of data
,2015-11-24T16:10:27.179Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:27.199 ThaliTest[1516:1270064] server session: not connected Apple-Iphone6-1_PT1630
,2015-11-24 17:10:28.593 ThaliTest[1516:1269390] multipeer session: reset timer
2015-11-24 17:10:28.593 ThaliTest[1516:1269390] multipeer session: stop timer
2015-11-24 17:10:28.594 ThaliTest[1516:1269390] multipeer session: start timer: 0x1b6a4b30
2015-,11-24 17:10:28.594 ThaliTest[1516:1269390] server session: connect
2015-11-24 17:10:28.595 ThaliTest[1516:1269390] server session: stateChange:0->1 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:28.607 ThaliTest[1516:1269390] server: accepting invitation Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:31.707 ThaliTest[1516:1270070] server session: connected
2015-11-24 17:10:31.708 ThaliTest[1516:1270070] server session: stateChange:1->2 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:31.712 ThaliTest[1516:1270091] client session: connected
2015-11-24 17:10:31.713 ThaliTest[1516:1270091] client session: stateChange:1->2 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:31.722 ThaliTest[1516:1269390] server relay: connected (to port: 61435)
,2015-11-24T16:10:31.726Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24 17:10:31.759 ThaliTest[1516:1270070] client session: fireConnectCallback: Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24 17:10:31.760 ThaliTest[1516:1270070] jxcore: connect: success
2015-11-24T16:10:31.761Z SendDataConnector.js: CLIENT connected, to 61444, error: null
,2015-11-24T16:10:31.761Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:31.765 ThaliTest[1516:1269390] client: relay established
2015-11-24 17:10:31.766 ThaliTest[1516:1269390] client: new accepted socket: 0x1b6afee0
,2015-11-24T16:10:31.778Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:32.294Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-24T16:10:32.498Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-24T16:10:32.520Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-24T16:10:32.541Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-11-24T16:10:32.563Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-11-24T16:10:32.579Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-24T16:10:32.581Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-24T16:10:32.582Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:32.584Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:32.585Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:32.586 ThaliTest[1516:1269508] jxcore: disconnect
,2015-11-24 17:10:32.587 ThaliTest[1516:1269508] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24 17:10:32.588 ThaliTest[1516:1269508] client session: disconnect
2015-11-24 17:10:32.589 ThaliTest[1516:1269508] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:32.592 ThaliTest[1516:1269508] jxcore: disconnect: success
2015-11-24T16:10:32.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7208.gEcfnw==
---- round done--------
device[3]: Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24T16:10:32.598Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:32.598Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:32.598Z SendDataConnector.js: do connect now
,2015-11-24 17:10:32.599 ThaliTest[1516:1269508] jxcore: connect Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:32.600 ThaliTest[1516:1269508] client session: connect
2015-11-24 17:10:32.600 ThaliTest[1516:1269508] client session: stateChange:0->1 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24T16:10:32.620Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:32.813 ThaliTest[1516:1270070] server session: not connected Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:35.127 ThaliTest[1516:1270091] client session: connected
2015-11-24 17:10:35.128 ThaliTest[1516:1270091] client session: stateChange:1->2 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:35.141 ThaliTest[1516:1270091] client session: fireConnectCallback: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:35.142 ThaliTest[1516:1270091] jxcore: connect: success
2015-11-24T16:10:35.143Z SendDataConnector.js: CLIENT connected to 61447, error: null
,2015-11-24T16:10:35.144Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:35.147 ThaliTest[1516:1269390] client: relay established
2015-11-24 17:10:35.148 ThaliTest[1516:1269390] client: new accepted socket: 0x1b790a20
,2015-11-24T16:10:35.160Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:35.442Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-24T16:10:35.455Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-24T16:10:35.468Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:35.469Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:35.469Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:35.469Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-24 17:10:35.470 ThaliTest[1516:1269508] jxcore: disconnect
2015-11-24 17:10:35.470 ThaliTest[1516:1269508] client session: disconnectFromPeer: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:35.470 ThaliTest[1516:1269508] client session: disconnect
,2015-11-24 17:10:35.470 ThaliTest[1516:1269508] client session: stateChange:2->0 Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:35.472 ThaliTest[1516:1269508] jxcore: disconnect: success
2015-11-24T16:10:35.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7498.cV5UxA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT8445","time":11824,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1630.4rgQcA==","time":2721,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7208.gEcfnw==","time":5907,"result":"OK","connections",:1},{"name":"Apple-Iphone5-1_PT7498.cV5UxA==","time":2871,"result":"OK","connections":1}]}
sendList : 100% : 5907 ms, 99% : 5907 ms, 95 : 5907 ms, 90% : 5907 ms.
Result count 3, range 2721 ms to  5907 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-24T16:10:35.479Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:35.479Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-24 17:10:40.303 ThaliTest[1516:1269508] jxcore: stopBroadcasting
2015-11-24 17:10:40.304 ThaliTest[1516:1269508] THEMultipeerSession stopping peer
2015-11-24 17:10:40.305 ThaliTest[1516:1269508] multipeer session: stop timer
,2015-11-24 17:10:40.306 ThaliTest[1516:1269508] server session: disconnect
2015-11-24 17:10:40.307 ThaliTest[1516:1269508] server session: stateChange:2->0 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:40.317 ThaliTest[1516:1269508] server session: disconnect
,2015-11-24 17:10:40.320 ThaliTest[1516:1269508] server session: stateChange:2->0 Apple-IpadAir2-1_PT7208
2015-11-24 17:10:40.325 ThaliTest[1516:1269508] server session: disconnect
2015-11-24 17:10:40.325 ThaliTest[1516:1269508] server session: stateChang,e:2->0 Apple-Iphone6-1_PT1630
,2015-11-24 17:10:40.333 ThaliTest[1516:1269508] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-24T16:10:40.358Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.360Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.361Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.362Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2721,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":2871,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":5907,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQc,A==\",\"time\":2721,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":2803,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":2871,\"result\":\"OK\",\"connections\":1},{\"n,ame\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2935,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":3022,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":3397,\"res,ult\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":3428,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":4431,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_,PT8445.HcGyQA==\",\"time\":5210,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":5907,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":7047,\"result\":\"OK\",\"connectio,ns\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":9136,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coor
```
