#### Test 519863409bc5c94_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1AAB884E-9CF4-45F8-B1FD-7BCFC0EE6B35/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1AAB884E-9CF4-45F8-B1FD-7BCFC0EE6B35/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/74C04405-D30F-4208-9E4E-60F6D75D866D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58023"
,(lldb)     command script import "/tmp/1AAB884E-9CF4-45F8-B1FD-7BCFC0EE6B35/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-30 11:48:30.265 ThaliTest[1631:2485524] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0C5A526-E613-4FD8-8C2C-98BD9E9F77E3/Library/Cookies/Cookies.binarycookies
,2015-11-30 11:48:30.554 ThaliTest[1631:2485524] Apache Cordova native platform version 3.9.2 is starting.
2015-11-30 11:48:30.555 ThaliTest[1631:2485524] Multi-tasking -> Device: YES, App: YES
,2015-11-30 11:48:30.561 ThaliTest[1631:2485524] Unlimited access to network resources
,2015-11-30 11:48:30.567 ThaliTest[1631:2485524] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 11:48:34.760 ThaliTest[1631:2485524] Resetting plugins due to page load.
,2015-11-30 11:48:36.243 ThaliTest[1631:2485524] Finished load of: file:///var/mobile/Containers/Bundle/Application/74C04405-D30F-4208-9E4E-60F6D75D866D/ThaliTest.app/www/index.html
,2015-11-30 11:48:36.388 ThaliTest[1631:2485524] JXcore Cordova plugin initializing
,2015-11-30 11:48:36.389 ThaliTest[1631:2485719] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT4872
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63558
,2015-11-30 11:55:57.953 ThaliTest[1631:2485719] jxcore: startBroadcasting
,2015-11-30 11:55:57.959 ThaliTest[1631:2485719] server: starting Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:55:57.959 ThaliTest[1631:2485719] multipeer session: start timer: 0x185caa60
,2015-11-30 11:55:57.960 ThaliTest[1631:2485719] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4872
,2015-11-30 11:55:57.961 ThaliTest[1631:2485719] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-30T10:55:57.962Z SendDataTCPServer.js: TCP/IP server is bound to port: 63558
,2015-11-30 11:55:58.647 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:55:58.649Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:55:58.650Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:55:58.650Z SendDataConnector.js: do connect now
2015-11-30 11:55:58.650 ThaliTest[1631:2485719] jxcore: connect Apple-Iphone5s-1_PT79,55.qINS9Q==
,2015-11-30 11:55:58.650 ThaliTest[1631:2485719] client session: connect
2015-11-30 11:55:58.650 ThaliTest[1631:2485719] client session: stateChange:0->1 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:55:59.811 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2455.0R5G/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:01.284 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:01.764 ThaliTest[1631:2486471] client session: connected
,2015-11-30 11:56:01.765 ThaliTest[1631:2486471] client session: stateChange:1->2 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:01.767 ThaliTest[1631:2486471] client session: fireConnectCallback: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:56:01.768 ThaliTest[1631:2486471] jxcore: connect: success
,2015-11-30T10:56:01.768Z SendDataConnector.js: CLIENT connected to 63561, error: null
2015-11-30T10:56:01.769Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:01.770 ThaliTest[1631:2485524] client: relay established
2015-11-30 11:56:01.770 ThaliTest[1631:2485524] client: new accepted socket: 0x19857a80
,2015-11-30T10:56:01.784Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:02.200Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-30T10:56:02.214Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T10:56:02.214Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:02.215Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:02.215Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:02.216 ThaliTest[1631:2485719] jxcore: disconnect
2015-11-30 11:56:02.217 ThaliTest[1631:2485719] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:02.217 ThaliTest[1631:2485719] client session: disconnect
,2015-11-30 11:56:02.217 ThaliTest[1631:2485719] client session: stateChange:2->0 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:02.283 ThaliTest[1631:2485719] jxcore: disconnect: success
2015-11-30T10:56:02.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30T10:56:02.284Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30T10:56:02.285Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30T10:56:02.285Z SendDataConnector.js: do connect now
,2015-11-30 11:56:02.286 ThaliTest[1631:2485719] jxcore: connect Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:02.286 ThaliTest[1631:2485719] client session: connect
2015-11-30 11:56:02.286 ThaliTest[1631:2485719] client session: stateChange:0->1 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:02.328 ThaliTest[1631:2485524] multipeer session: reset timer
2015-11-30 11:56:02.328 ThaliTest[1631:2485524] multipeer session: stop timer
2015-11-30 11:56:02.328 ThaliTest[1631:2485524] multipeer session: start timer: 0x185caa60
,2015-11-30 11:56:02.328 ThaliTest[1631:2485524] server session: connect
2015-11-30 11:56:02.328 ThaliTest[1631:2485524] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30 11:56:02.331 ThaliTest[1631:2485524] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 11:56:02.357 ThaliTest[1631:2485524] multipeer session: reset timer
2015-11-30 11:56:02.357 ThaliTest[1631:2485524] multipeer session: stop timer
2015-11-30 11:56:02.358 ThaliTest[1631:2485524] multipeer session: start timer: 0x185caa60
2015-,11-30 11:56:02.358 ThaliTest[1631:2485524] server session: connect
2015-11-30 11:56:02.358 ThaliTest[1631:2485524] server session: stateChange:0->1 Apple-Iphone5s-1_PT7955
2015-11-30 11:56:02.361 ThaliTest[1631:2485524] server: accepting invitation Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:05.006 ThaliTest[1631:2486480] server session: connected
2015-11-30 11:56:05.006 ThaliTest[1631:2486480] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30T10:56:05.010Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:56:05.011 ThaliTest[1631:2485524] server relay: connected (to port: 63558)
,2015-11-30 11:56:05.397 ThaliTest[1631:2486470] server session: connected
2015-11-30 11:56:05.397 ThaliTest[1631:2486470] server session: stateChange:1->2 Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:05.400 ThaliTest[1631:2485524] server relay: connected (to port: 63558)
,2015-11-30T10:56:05.405Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:56:05.807 ThaliTest[1631:2486479] client session: connected
2015-11-30 11:56:05.807 ThaliTest[1631:2486479] client session: stateChange:1->2 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30T10:56:05.809Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-30 11:56:05.809 ThaliTest[1631:2486479] client session: fireConnectCallback: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:05.810 ThaliTest[1631:2486479] jxcore: connect: success
2015-11-30T10:56:05.810Z SendDataTCPServer.js: TCP/IP server has, received 6016 bytes of data
2015-11-30T10:56:05.810Z SendDataConnector.js: CLIENT connected to 63566, error: null
,2015-11-30T10:56:05.811Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:05.812 ThaliTest[1631:2485524] client: relay established
2015-11-30 11:56:05.812 ThaliTest[1631:2485524] client: new accepted socket: 0x1986ae60
,2015-11-30T10:56:05.825Z SendDataTCPServer.js: TCP/IP server has received 10912 bytes of data
,2015-11-30T10:56:05.826Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:06.065Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-11-30T10:56:06.066Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-11-30T10:56:06.080Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-30T10:56:06.339Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-11-30T10:56:06.389Z SendDataTCPServer.js: TCP/IP server has received 47616 bytes of data
,2015-11-30T10:56:06.402Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-11-30T10:56:06.473Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:06.511Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-11-30T10:56:06.511Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-30 11:56:06.519 ThaliTest[1631:2486470] server session: not connected Apple-Iphone5s-1_PT7955
,2015-11-30T10:56:06.524Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:06.525Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T10:56:06.525Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:06.526Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:06.526Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:06.527 ThaliTest[1631:2485719] jxcore: disconnect
2015-11-30 11:56:06.527 ThaliTest[1631:2485719] client session: disconnectFromPeer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:06.527 ThaliTest[1631:2485719] client session: disconn,ect
2015-11-30 11:56:06.527 ThaliTest[1631:2485719] client session: stateChange:2->0 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:06.532 ThaliTest[1631:2485719] jxcore: disconnect: success
2015-11-30T10:56:06.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2455.0R5G/g==
---- round done--------
,device[3]: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:06.534Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:06.535Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30T10:56:06.535Z SendDataConnector.js: do connect now
2015-11-30 11:56:06.535 ThaliTest[1631:2485719] jxcore: connect Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:06.535 ThaliTest[1631:2485719] client session: connect
2015-11-30 11:56:06.536 ThaliTest[1631:2485719] client session: stateChange:0->1 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:06.552 ThaliTest[1631:2485524] multipeer session: reset timer
2015-11-30 11:56:06.552 ThaliTest[1631:2485524] multipeer session: stop timer
2015-11-30 11:56:06.552 ThaliTest[1631:2485524] multipeer session: start timer: 0x185caa60
2015-11-30 11:56:06.554 ThaliTest[1631:2485524] server session: connect
2015-11-30 11:56:06.554 ThaliTest[1631:2485524] server session: stateChange:0->1 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:06.557 ThaliTest[1631:2485524] server: accepting invitation Apple-Iphone6-1_PT7389
,2015-11-30 11:56:06.860 ThaliTest[1631:2486471] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30 11:56:09.142 ThaliTest[1631:2486515] server session: connected
,2015-11-30 11:56:09.142 ThaliTest[1631:2486515] server session: stateChange:1->2 Apple-Iphone6-1_PT7389
,2015-11-30 11:56:09.161 ThaliTest[1631:2485524] server relay: connected (to port: 63558)
,2015-11-30T10:56:09.167Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:09.526Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-30 11:56:09.527 ThaliTest[1631:2486480] client session: connected
2015-11-30 11:56:09.528 ThaliTest[1631:2486480] client session: stateChange:1->2 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30T10:56:09.538Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-11-30T10:56:09.554Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 11:56:09.577 ThaliTest[1631:2486470] client session: fireConnectCallback: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:09.577 ThaliTest[1631:2486470] jxcore: connect: success
2015-11-30T10:56:09.577Z SendDataConnector.js: CLIENT connected to 63571, error: null
2015-11-30T10:56:09.577Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:09.578 ThaliTest[1631:2485524] client: relay established
2015-11-30 11:56:09.578 ThaliTest[1631:2485524] client: new accepted socket: 0x185462d0
,2015-11-30T10:56:09.591Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30 11:56:09.610 ThaliTest[1631:2486480] server session: not connected Apple-Iphone6-1_PT7389
,2015-11-30T10:56:10.007Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-30T10:56:10.120Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T10:56:10.120Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:10.121Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:10.122Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:10.122 ThaliTest[1631:2485719] jxcore: disconnect
2015-11-30 11:56:10.122 ThaliTest[1631:2485719] client session: disconnectFromPeer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:10.122 ThaliTest[1631:2485719] client session: disconnect
2015-11-30 11:56:10.122 ThaliTest[1631:2485719] client session: stateChange:2->0 Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:56:10.185 ThaliTest[1631:2485719] jxcore: disconnect: success
2015-11-30T10:56:10.185Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7389.2i+JNA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT4872","time":12238,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT7955.qINS9Q==","time":3565,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT2455.0R5G/g==","time":4240,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT7389.2i+JNA==","time":3586,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
,sendList : 100% : 4240 ms, 99% : 4240 ms, 95 : 4240 ms, 90% : 4240 ms.
,Result count 3, range 3565 ms to  4240 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-30T10:56:10.191Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:10.191Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:36.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:56:36.564 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:36.565 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:56:36.566 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:57:06.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:57:06.567 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:06.567 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:57:06.567 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:57:13.364 ThaliTest[1631:2485524] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:13.364 ThaliTest[1631:2485524] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:13.411 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:19.749 ThaliTest[1631:2485524] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:19.750 ThaliTest[1631:2485524] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:35.425 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:36.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:57:36.564 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:57:36.565 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:37.520 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:06.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:58:06.568 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 11:58:06.568 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:58:06.568 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:58:17.446 ThaliTest[1631:2485524] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:17.446 ThaliTest[1631:2485524] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:58:36.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:58:36.563 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:58:36.565 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:52.007 ThaliTest[1631:2485524] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:58:52.008 ThaliTest[1631:2485524] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:59:06.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:59:36.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 11:59:36.561 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:59:36.562 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 12:00:06.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 12:00:06.561 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:00:07.131 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 12:00:19.148 ThaliTest[1631:2485524] client: lost peer: Apple-Iphone6-1_PT7389.2i+JNA==
2015-11-30 12:00:19.148 ThaliTest[1631:2485524] client session: onPeerLost: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 12:00:35.729 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7389.2i+JNA==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 12:00:36.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 12:00:36.563 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 12:00:36.563 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 12:01:06.554 ThaliTest[1631:2485524] multipeer session: restart
,2015-11-30 12:01:06.562 ThaliTest[1631:2485524] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 12:01:07.176 ThaliTest[1631:2485524] client: found peer: Apple-Iphone6-1_PT7389.2i+JNA==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-11-30 12:01:12.292 ThaliTest[1631:2485719] jxcore: stopBroadcasting
2015-11-30 12:01:12.292 ThaliTest[1631:2485719] THEMultipeerSession stopping peer
2015-11-30 12:01:12.292 ThaliTest[1631:2485719] multipeer session: stop timer
2015-11-30 12:01:12.293 ThaliTest[1631:2485719] server session: disconnect
2015-11-30 12:01:12.293 ThaliTest[1631:2485719] server session: stateChange:2->0 Apple-Iphone6-1_PT7389
,2015-11-30 12:01:12.297 ThaliTest[1631:2485719] server session: disconnect
2015-11-30 12:01:12.297 ThaliTest[1631:2485719] server session: stateChange:2->0 Apple-Iphone5-1_PT2455
,2015-11-30 12:01:12.300 ThaliTest[1631:2485719] server session: disconnect
2015-11-30 12:01:12.300 ThaliTest[1631:2485719] server session: stateChange:2->0 Apple-Iphone5s-1_PT7955
,2015-11-30 12:01:12.361 ThaliTest[1631:2485719] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-30T11:01:12.375Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:12.376Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:12.376Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:12.377Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT7955.qINS9Q==\",\"time\":3565,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT7389.2i+JNA==\",\"time\":3586,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT2455.0R5G/g==\",\"time\":4240,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
