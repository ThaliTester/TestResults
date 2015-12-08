#### Test 52971095c7b67a5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/9B0D1633-57D5-40E7-84AC-104BBC5A8CB2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9B0D1633-57D5-40E7-84AC-104BBC5A8CB2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c7b67a5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4B8DF96E-E02D-435A-B5A3-FE05F1C1BC59/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50646"
,(lldb)     command script import "/tmp/9B0D1633-57D5-40E7-84AC-104BBC5A8CB2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 13:06:30.474 ThaliTest[454:269316] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FB1A219A-99A6-45A8-B656-AEED91449786/Library/Cookies/Cookies.binarycookies
,2015-12-08 13:06:30.906 ThaliTest[454:269316] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 13:06:30.908 ThaliTest[454:269316] Multi-tasking -> Device: YES, App: YES
,2015-12-08 13:06:30.917 ThaliTest[454:269316] Unlimited access to network resources
,2015-12-08 13:06:30.930 ThaliTest[454:269316] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 13:06:39.816 ThaliTest[454:269316] Resetting plugins due to page load.
,2015-12-08 13:06:43.680 ThaliTest[454:269316] Finished load of: file:///var/mobile/Containers/Bundle/Application/4B8DF96E-E02D-435A-B5A3-FE05F1C1BC59/ThaliTest.app/www/index.html
,2015-12-08 13:06:43.903 ThaliTest[454:269316] JXcore Cordova plugin initializing
,2015-12-08 13:06:43.904 ThaliTest[454:269523] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone5s-1_PT8639
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51325
,2015-12-08 13:12:58.639 ThaliTest[454:269523] jxcore: startBroadcasting
,2015-12-08 13:12:58.659 ThaliTest[454:269523] server: starting Apple-Iphone5s-1_PT8639.zsASLQ==
,2015-12-08 13:12:58.661 ThaliTest[454:269523] multipeer session: start timer: 0x1848d8d0
2015-12-08 13:12:58.662 ThaliTest[454:269523] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8639
2015-12-08 13:12:58.662 ThaliTest[454:269523] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
2015-12-08T12:12:58.666Z SendDataTCPServer.js: TCP/IP server is bound to port: 51325
,2015-12-08 13:13:00.411 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,device[1]: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08T12:13:00.417Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:00.421Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08T12:13:00.422Z SendDataConnector.js: do connect now
,2015-12-08 13:13:00.423 ThaliTest[454:269523] jxcore: connect Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:00.424 ThaliTest[454:269523] client session: connect
2015-12-08 13:13:00.424 ThaliTest[454:269523] client session: stateChange:0->1 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:02.981 ThaliTest[454:269316] multipeer session: reset timer
2015-12-08 13:13:02.981 ThaliTest[454:269316] multipeer session: stop timer
2015-12-08 13:13:02.982 ThaliTest[454:269316] multipeer session: start timer: 0x1848d8d0
2015-12-08 ,13:13:02.982 ThaliTest[454:269316] server session: connect
2015-12-08 13:13:02.982 ThaliTest[454:269316] server session: stateChange:0->1 Apple-IpadAir2-1_PT3979
2015-12-08 13:13:02.991 ThaliTest[454:269316] server: accepting invitation Apple-IpadAir2-1_,PT3979
,2015-12-08 13:13:05.341 ThaliTest[454:270151] client session: connected
2015-12-08 13:13:05.345 ThaliTest[454:270151] client session: stateChange:1->2 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:05.354 ThaliTest[454:270151] client session: fireConnectCallback: Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:05.355 ThaliTest[454:270151] jxcore: connect: success
,2015-12-08T12:13:05.357Z SendDataConnector.js: CLIENT connected to 51328, error: null
,2015-12-08T12:13:05.358Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 13:13:05.363 ThaliTest[454:269316] client: relay established
2015-12-08 13:13:05.363 ThaliTest[454:269316] client: new accepted socket: 0x1873c0a0
,2015-12-08T12:13:05.379Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:05.729Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-08T12:13:05.791Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:05.792Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:05.793Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:05.793Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:05.794 ThaliTest[454:269523] jxcore: disconnect
2015-12-08 13:13:05.794 ThaliTest[454:269523] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:13:05.795 ThaliTest[454:269523] client session: disconnect
2015-12-08 13:13:05.795 ThaliTest[454:269523] client session: stateChange:2->0 Apple-IpadAir2-1_PT3979.Fg9L1g==
,2015-12-08 13:13:05.801 ThaliTest[454:269523] jxcore: disconnect: success
2015-12-08T12:13:05.803Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3979.Fg9L1g==
---- round done--------
,2015-12-08 13:13:06.194 ThaliTest[454:270161] server session: connected
,2015-12-08 13:13:06.194 ThaliTest[454:270161] server session: stateChange:1->2 Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:06.204 ThaliTest[454:269316] server relay: connected (to port: 51325)
,2015-12-08T12:13:06.212Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 13:13:06.242 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT785.mqQzsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[2]: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08T12:13:06.248Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08T12:13:06.248Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT785.mqQzsA==
2015-,12-08T12:13:06.248Z SendDataConnector.js: do connect now
2015-12-08 13:13:06.249 ThaliTest[454:269523] jxcore: connect Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:06.250 ThaliTest[454:269523] client session: connect
2015-12-08 13:13:06.251 ThaliTest,[454:269523] client session: stateChange:0->1 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08T12:13:06.659Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-08T12:13:06.674Z SendDataTCPServer.js: TCP/IP server has received 26138 bytes of data
,2015-12-08T12:13:06.689Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-08T12:13:06.720Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-08T12:13:06.736Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-08 13:13:07.301 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4714.SIFsmA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08T12:13:07.370Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:07.701 ThaliTest[454:270151] server session: not connected Apple-IpadAir2-1_PT3979
,2015-12-08 13:13:08.484 ThaliTest[454:269316] multipeer session: reset timer
2015-12-08 13:13:08.484 ThaliTest[454:269316] multipeer session: stop timer
2015-12-08 13:13:08.485 ThaliTest[454:269316] multipeer session: start timer: 0x1848d8d0
2015-12-08 ,13:13:08.485 ThaliTest[454:269316] server session: connect
2015-12-08 13:13:08.485 ThaliTest[454:269316] server session: stateChange:0->1 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:08.497 ThaliTest[454:269316] server: accepting invitation Apple-Iphone6-1_PT4714
,2015-12-08 13:13:10.632 ThaliTest[454:269316] multipeer session: reset timer
2015-12-08 13:13:10.633 ThaliTest[454:269316] multipeer session: stop timer
2015-12-08 13:13:10.633 ThaliTest[454:269316] multipeer session: start timer: 0x1848d8d0
2015-12-08 ,13:13:10.634 ThaliTest[454:269316] server session: connect
2015-12-08 13:13:10.634 ThaliTest[454:269316] server session: stateChange:0->1 Apple-Iphone5-1_PT785
,2015-12-08 13:13:10.644 ThaliTest[454:269316] server: accepting invitation Apple-Iphone5-1_PT785
,2015-12-08 13:13:11.634 ThaliTest[454:270188] server session: connected
,2015-12-08 13:13:11.635 ThaliTest[454:270188] server session: stateChange:1->2 Apple-Iphone6-1_PT4714
,2015-12-08 13:13:11.904 ThaliTest[454:270151] client session: connected
,2015-12-08 13:13:11.904 ThaliTest[454:270151] client session: stateChange:1->2 Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:11.909 ThaliTest[454:270151] client session: fireConnectCallback: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:11.909 ThaliT,est[454:270151] jxcore: connect: success
2015-12-08T12:13:11.911Z SendDataConnector.js: CLIENT connected to 51332, error: null
2015-12-08T12:13:11.911Z SendDataConnector.js: CLIENT starting client 
2015-12-08 13:13:11.914 ThaliTest[454:269316] client: r,elay established
2015-12-08 13:13:11.915 ThaliTest[454:269316] client: new accepted socket: 0x187432b0
,2015-12-08T12:13:11.927Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 13:13:12.405 ThaliTest[454:269316] server relay: connected (to port: 51325)
,2015-12-08T12:13:12.411Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:12.487Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T12:13:12.539Z SendDataTCPServer.js: TCP/IP server has received 14904 bytes of data
,2015-12-08T12:13:12.553Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
2015-12-08T12:13:12.555Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08T12:13:12.568Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-08T12:13:12.581Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-08T12:13:12.607Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
2015-12-08T12:13:12.609Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T12:13:12.622Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08T12:13:12.952Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:12.953Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:12.955Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:12.955Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:12.956 ThaliTest[454:269523] jxcore: disconnect
2015-12-08 13:13:12.957 ThaliTest[454:269523] client session: disconnectFromPeer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:13:12.957 ThaliTest[454:269523] client session: disconnect
20,15-12-08 13:13:12.958 ThaliTest[454:269523] client session: stateChange:2->0 Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:13:12.978 ThaliTest[454:269523] jxcore: disconnect: success
2015-12-08T12:13:12.979Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT785.mqQzsA==
---- round done--------
device[3]: Apple-Iphone6-1_PT4714.SIFs,mA==
2015-12-08T12:13:12.981Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:13:12.982Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08T12:13:12.982Z SendDataConnect,or.js: do connect now
2015-12-08 13:13:12.983 ThaliTest[454:269523] jxcore: connect Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:12.983 ThaliTest[454:269523] client session: connect
2015-12-08 13:13:12.989 ThaliTest[454:269523] client session: stateChange:0->1 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:13.042 ThaliTest[454:270161] server session: not connected Apple-Iphone6-1_PT4714
,2015-12-08 13:13:14.119 ThaliTest[454:270161] server session: connected
2015-12-08 13:13:14.120 ThaliTest[454:270161] server session: stateChange:1->2 Apple-Iphone5-1_PT785
,2015-12-08 13:13:14.127 ThaliTest[454:269316] server relay: connected (to port: 51325)
,2015-12-08T12:13:14.139Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T12:13:14.788Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-08T12:13:14.802Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-08T12:13:15.042Z SendDataTCPServer.js: TCP/IP server has received 35952 bytes of data
,2015-12-08T12:13:15.061Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-08T12:13:15.078Z SendDataTCPServer.js: TCP/IP server has received 83078 bytes of data
,2015-12-08T12:13:15.095Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-08T12:13:15.111Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-08T12:13:15.127Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 13:13:15.297 ThaliTest[454:270152] server session: not connected Apple-Iphone5-1_PT785
,2015-12-08 13:13:16.344 ThaliTest[454:270152] client session: connected
2015-12-08 13:13:16.344 ThaliTest[454:270152] client session: stateChange:1->2 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:16.375 ThaliTest[454:270161] client session: fireConnectCallback: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:16.375 ThaliTest[454:270161] jxcore: connect: success
2015-12-08T12:13:16.376Z SendDataConnector.js: CLIENT connected to 5,1337, error: null
2015-12-08T12:13:16.377Z SendDataConnector.js: CLIENT starting client 
2015-12-08 13:13:16.380 ThaliTest[454:269316] client: relay established
2015-12-08 13:13:16.381 ThaliTest[454:269316] client: new accepted socket: 0x184a2be0
,2015-12-08T12:13:16.393Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T12:13:19.753Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T12:13:19.754Z SendDataConnector.js: got all data for this round
,2015-12-08T12:13:19.756Z SendDataConnector.js: CLIENT Stop now
2015-12-08T12:13:19.756Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:19.758 ThaliTest[454:269523] jxcore: disconnect
2015-12-08 13:13:19.758 ThaliTest[454:269523] client session: disconnectFromPeer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:13:19.759 ThaliTest[454:269523] client session: disconnect
2,015-12-08 13:13:19.759 ThaliTest[454:269523] client session: stateChange:2->0 Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:13:19.775 ThaliTest[454:269523] jxcore: disconnect: success
2015-12-08T12:13:19.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4714.SIFsmA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT8639","time":21157,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT3979.Fg9L1g==","time":5372,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT785.mqQzsA==","time":6705,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT4714.SIFsmA==","time":6772,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 6772 ms, 99% : 6772 ms, 95 : 6772 ms, 90% : 6772 ms.
,Result count 3, range 5372 ms to  6772 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T12:13:19.834Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T12:13:19.835Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 13:13:40.635 ThaliTest[454:269316] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 13:14:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:14:10.693 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:14:10.693 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:10.694 ThaliTest[454:269316] client: found, peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:14:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:14:40.693 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:14:40.694 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:14:40.694 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:14:57.787 ThaliTest[454:269316] client: lost peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:14:57.787 ThaliTest[454:269316] client session: onPeerLost: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 13:14:58.786 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3979.Fg9L1g==","peerName":"(null)","peerAvailable":true}]
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
,2015-12-08 13:15:10.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:15:10.701 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:15:10.701 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:15:10.705 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:15:40.634 ThaliTest[454:269316] multipeer session: restart
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
,2015-12-08 13:16:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:16:10.691 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:10.692 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:21.461 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 13:16:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:16:40.691 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:16:40.692 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:16:40.693 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:17:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:17:10.694 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:17:10.695 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:17:10.696 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:17:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:17:40.689 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:17:40.696 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:17:40.697 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,2015-12-08 13:18:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:18:10.689 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:18:10.691 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:18:10.695 ThaliTest[454:269316] client: found, peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:18:40.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:18:40.703 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:18:40.704 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:18:40.704 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 13:19:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:19:10.698 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:19:10.698 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:19:10.699 ThaliTest[454:269316] client: foun,d peer: Apple-Iphone6-1_PT4714.SIFsmA==
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
,2015-12-08 13:19:40.635 ThaliTest[454:269316] multipeer session: restart
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
,2015-12-08 13:20:10.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:20:10.692 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:20:10.692 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:20:10.701 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:20:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:20:40.678 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:20:40.678 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:20:40.679 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:21:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:21:10.679 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:21:10.679 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:21:10.683 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:21:40.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:21:40.697 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:21:40.698 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:21:40.705 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:22:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:22:10.689 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:22:10.690 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:22:10.701 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:22:40.635 ThaliTest[454:269316] multipeer session: restart
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
,2015-12-08 13:23:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:23:10.696 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:23:10.696 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:23:10.697 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:23:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:23:40.691 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:23:40.692 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:23:40.694 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:24:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:24:10.695 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:24:10.695 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:24:10.696 ThaliTest[454:269316] client: found, peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:24:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:24:40.691 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:24:40.692 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:24:40.693 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:25:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:25:10.695 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:25:10.696 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:25:10.696 ThaliTest[454:269316] client: fou,nd peer: Apple-Iphone5-1_PT785.mqQzsA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:25:40.635 ThaliTest[454:269316] multipeer session: restart
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
,2015-12-08 13:26:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:26:10.687 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:26:10.687 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:26:10.695 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
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
,2015-12-08 13:26:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:26:40.695 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:26:40.700 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:26:40.701 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
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
,2015-12-08 13:27:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:27:10.689 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:10.690 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:27:10.699 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:27:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:27:40.691 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:27:40.694 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:27:40.695 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:28:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:28:10.690 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:28:10.691 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:28:10.695 ThaliTest[454:269316] client: found, peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:28:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:28:40.693 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:28:40.694 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:28:40.695 ThaliTest[454:269316] client: found, peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:29:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:29:10.688 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:29:10.691 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:29:10.692 ThaliTest[454:269316] client: foun,d peer: Apple-Iphone6-1_PT4714.SIFsmA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:29:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:29:40.688 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:29:40.689 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:29:40.698 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:30:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:30:10.695 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:30:10.696 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:30:10.709 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:30:40.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:30:40.692 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:30:40.693 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:30:40.703 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:31:10.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:31:10.683 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:31:10.686 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:31:10.688 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:31:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:31:40.684 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:31:40.685 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:31:40.687 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
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
,2015-12-08 13:32:10.634 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:32:10.685 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:32:10.686 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
,2015-12-08 13:32:10.695 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:32:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:32:40.689 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:32:40.694 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
2015-12-08 13:32:40.694 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
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
,2015-12-08 13:33:10.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:33:10.689 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
,2015-12-08 13:33:10.696 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:33:10.696 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
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
,2015-12-08 13:33:40.635 ThaliTest[454:269316] multipeer session: restart
,2015-12-08 13:33:40.691 ThaliTest[454:269316] client: found peer: Apple-Iphone5-1_PT785.mqQzsA==
2015-12-08 13:33:40.692 ThaliTest[454:269316] client: found peer: Apple-Iphone6-1_PT4714.SIFsmA==
2015-12-08 13:33:40.692 ThaliTest[454:269316] client: found peer: Apple-IpadAir2-1_PT3979.Fg9L1g==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
