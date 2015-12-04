#### Test 525354860130a71_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B3FC15A4-F4B2-4791-B15E-6DFDC460D99B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B3FC15A4-F4B2-4791-B15E-6DFDC460D99B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525354860130a71/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BBDD92BB-EA1D-4FCC-A05E-402243260CCA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61434"
,(lldb)     command script import "/tmp/B3FC15A4-F4B2-4791-B15E-6DFDC460D99B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:43:17.846 ThaliTest[2604:2400468] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6817087E-27F0-4773-BF0A-78D4C91ECD8D/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:43:18.248 ThaliTest[2604:2400468] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:43:18.249 ThaliTest[2604:2400468] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:43:18.258 ThaliTest[2604:2400468] Unlimited access to network resources
,2015-12-04 09:43:18.265 ThaliTest[2604:2400468] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:43:21.806 ThaliTest[2604:2400468] Resetting plugins due to page load.
,2015-12-04 09:43:22.260 ThaliTest[2604:2400468] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/BBDD92BB-EA1D-4FCC-A05E-402243260CCA/ThaliTest.app/www/index.html
,2015-12-04 09:43:22.418 ThaliTest[2604:2400468] JXcore Cordova plugin initializing
2015-12-04 09:43:22.419 ThaliTest[2604:2400591] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT7213
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51478
,2015-12-04 09:49:52.645 ThaliTest[2604:2400591] jxcore: startBroadcasting
,2015-12-04 09:49:52.658 ThaliTest[2604:2400591] server: starting Apple-Iphone5s-1_PT7213.N3FSeg==
,2015-12-04 09:49:52.660 ThaliTest[2604:2400591] multipeer session: start timer: 0x19d01d00
,2015-12-04 09:49:52.661 ThaliTest[2604:2400591] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7213
,2015-12-04 09:49:52.663 ThaliTest[2604:2400591] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-04T08:49:52.669Z SendDataTCPServer.js: TCP/IP server is bound to port: 51478
,2015-12-04 09:49:53.025 ThaliTest[2604:2400468] client: found peer: Apple-Iphone6-1_PT7135.+FivAg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7135.+FivAg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:49:53.033Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:49:53.034Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:49:53.034Z SendDataConnector.js: do connect now
,2015-12-04 09:49:53.035 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:53.036 ThaliTest[2604:2400591] client session: connect
,2015-12-04 09:49:53.037 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:49:53.526 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:49:53.526 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:49:53.527 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-,12-04 09:49:53.528 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:49:53.529 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone6-1_PT7135
,2015-12-04 09:49:53.537 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone6-1_PT7135
,2015-12-04 09:49:53.848 ThaliTest[2604:2400468] client: found peer: Apple-Iphone5-1_PT9194.4xGkjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9194.4xGkjQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-04 09:49:54.178 ThaliTest[2604:2400468] client: found peer: Apple-IpadAir2-1_PT6975.MZRWVw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6975.MZRWVw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:49:55.759 ThaliTest[2604:2401167] server session: connected
2015-12-04 09:49:55.760 ThaliTest[2604:2401167] server session: stateChange:1->2 Apple-Iphone6-1_PT7135
,2015-12-04 09:49:55.840 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
,2015-12-04T08:49:55.850Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:49:56.250Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-04T08:49:56.266Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-04T08:49:56.281Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-04 09:49:56.310 ThaliTest[2604:2401154] client session: connected
2015-12-04 09:49:56.311 ThaliTest[2604:2401154] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:49:56.318Z SendDataTCPServer.js: TCP/IP server has received 31998 bytes of data
,2015-12-04 09:49:56.334 ThaliTest[2604:2401163] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:49:56.335 ThaliTest[2604:2401163] jxcore: connect: success
2015-12-04T08:49:56.336Z SendDataTCPServer.js: TCP/IP server has, received 100000 bytes of data
2015-12-04T08:49:56.342Z SendDataConnector.js: CLIENT connected to 51482, error: null
2015-12-04T08:49:56.342Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:49:56.347 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:49:56.348 ThaliTest[2604:2400468] client: new accepted socket: 0x19ed6b70
,2015-12-04T08:49:56.363Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04 09:49:56.380 ThaliTest[2604:2401163] server session: not connected Apple-Iphone6-1_PT7135
,2015-12-04 09:49:56.590 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:49:56.591 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:49:56.591 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-12-04 09:49:56.591 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:49:56.591 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
,2015-12-04 09:49:56.596 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04T08:49:56.790Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-04T08:49:56.816Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04 09:49:58.878 ThaliTest[2604:2401167] server session: connected
2015-12-04 09:49:58.879 ThaliTest[2604:2401167] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:49:58.894 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
,2015-12-04T08:49:58.901Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:49:59.401Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-04T08:49:59.418Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-12-04T08:49:59.435Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-12-04T08:49:59.453Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-12-04T08:49:59.469Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
,2015-12-04T08:49:59.485Z SendDataTCPServer.js: TCP/IP server has received 60512 bytes of data
,2015-12-04T08:49:59.500Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-12-04T08:49:59.515Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-12-04T08:49:59.527Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:50:01.119 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:50:01.120 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:50:01.121 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-,12-04 09:50:01.121 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:50:01.122 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:01.134 ThaliTest[2604:2400468] server: accepting invitation Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:03.641 ThaliTest[2604:2401163] server session: connected
2015-12-04 09:50:03.642 ThaliTest[2604:2401163] server session: stateChange:1->2 Apple-IpadAir2-1_PT6975
,2015-12-04 09:50:03.652 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
2015-12-04T08:50:03.654Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:03.911Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-04T08:50:03.927Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-04T08:50:04.114Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-04T08:50:04.131Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-04T08:50:04.148Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-04T08:50:04.168Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:50:04.229 ThaliTest[2604:2401154] server session: not connected Apple-IpadAir2-1_PT6975
,2015-12-04T08:50:06.820Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:06.820Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:06.823Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:06.823Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:06.824Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:06.826 ThaliTest[2604:2400468] client: socket closed
2015-12-04 09:50:06.827 ThaliTest[2604:2400468] client relay: socket disconnected
2015-12-04 09:50:06.827 ThaliTest[2604:2400468] client relay: 0x19ed6b70 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19f7e050 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:06.828 ThaliTest[2604:2400468] client session: socket closed: Apple-Iphone6-1_PT7135.+FivAg,==
2015-12-04 09:50:06.828 ThaliTest[2604:2400468] client session: onLinkFailure: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:06.829 ThaliTest[2604:2400468] client session: disconnect
2015-12-04 09:50:06.829 ThaliTest[2604:2400468] client session: ,stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:06.832 ThaliTest[2604:2400468] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:09.871 ThaliTest[2604:2401154] server session: not connected Apple-Iphone5-1_PT9194
,2015-12-04T08:50:11.830Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:50:11.831Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:16.832 ThaliTest[2604:2400591] jxcore: disconnect
2015-12-04 09:50:16.833 ThaliTest[2604:2400591] jxcore: disconnect: fail
2015-12-04T08:50:16.834Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:50:16.835Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7135.+FivAg== with availability status: true
2015-12-04T08:50:16.836Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
2015-1,2-04T08:50:16.836Z SendDataConnector.js: do connect now
,2015-12-04 09:50:16.837 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:16.838 ThaliTest[2604:2400591] client session: connect
2015-12-04 09:50:16.839 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:19.906 ThaliTest[2604:2401169] client session: connected
2015-12-04 09:50:19.907 ThaliTest[2604:2401169] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:19.918 ThaliTest[2604:2401167] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:19.919 ThaliTest[2604:2401167] jxcore: connect: success
2015-12-04T08:50:19.921Z SendDataConnector.js: CLIENT connected ,to 51488, error: null
2015-12-04T08:50:19.922Z SendDataConnector.js: CLIENT starting client 
2015-12-04 09:50:19.928 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:50:19.929 ThaliTest[2604:2400468] client: new accepted socket: 0x19ee38b,0
,2015-12-04T08:50:19.937Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:20.004 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:50:20.004 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:50:20.004 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-,12-04 09:50:20.005 ThaliTest[2604:2400468] server: disconnecting to refresh session (Apple-Iphone5-1_PT9194)
2015-12-04 09:50:20.005 ThaliTest[2604:2400468] server session: disconnect
2015-12-04 09:50:20.005 ThaliTest[2604:2400468] server session: stateChange:2->0 Apple-Iphone5-1_PT9194
,2015-12-04 09:50:20.007 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:50:20.007 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
,2015-12-04 09:50:20.010 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04T08:50:20.013Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:22.122 ThaliTest[2604:2401242] server session: connected
2015-12-04 09:50:22.123 ThaliTest[2604:2401242] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:50:22.460 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
2015-12-04T08:50:22.462Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:22.542Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-04T08:50:22.556Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04T08:50:30.004Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:30.005Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:30.006Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:30.006Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:30.007Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:30.009 ThaliTest[2604:2400468] client: socket closed
2015-12-04 09:50:30.010 ThaliTest[2604:2400468] client relay: socket disconnected
2015-12-04 09:50:30.010 ThaliTest[2604:2400468] client relay: 0x19ee38b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19f7abd0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:30.011 ThaliTest[2604:2400468] client session: socket closed: Apple-Iphone6-1_PT7135.+FivAg,==
2015-12-04 09:50:30.011 ThaliTest[2604:2400468] client session: onLinkFailure: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:30.012 ThaliTest[2604:2400468] client session: disconnect
2015-12-04 09:50:30.012 ThaliTest[2604:2400468] client session: ,stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:30.015 ThaliTest[2604:2400468] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:32.571 ThaliTest[2604:2401167] server session: not connected Apple-Iphone5-1_PT9194
,2015-12-04T08:50:35.007Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:50:35.008Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:40.016 ThaliTest[2604:2400591] jxcore: disconnect
2015-12-04 09:50:40.017 ThaliTest[2604:2400591] jxcore: disconnect: fail
2015-12-04T08:50:40.017Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivA,g==
2015-12-04T08:50:40.018Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7135.+FivAg== with availability status: true
2015-12-04T08:50:40.018Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:50:40.018Z SendDataConnector.js: do connect now
2015-12-04 09:50:40.019 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:40.020 ThaliTest[2604:2400591] client session: connect
2015-12-04 09:50:40.021 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:42.905 ThaliTest[2604:2401257] client session: connected
2015-12-04 09:50:42.905 ThaliTest[2604:2401257] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:42.917 ThaliTest[2604:2401167] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:42.918 ThaliTest[2604:2401167] jxcore: connect: success
2015-12-04T08:50:42.920Z SendDataConnector.js: CLIENT connected ,to 51493, error: null
2015-12-04T08:50:42.920Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:50:42.924 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:50:42.925 ThaliTest[2604:2400468] client: new accepted socket: 0x19f8bfe0
,2015-12-04T08:50:42.936Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:50:43.068 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:50:43.069 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:50:43.069 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-12-04 09:50:43.069 ThaliTest[2604:2400468] server: disconnecting to refresh session (Apple-Iphone5-1_PT9194)
2015-12-04 09:50:43.069 ThaliTest[2604:2400468] server session: disconnect
2015-12-04 09:50:43.070 ThaliTest[2604:2400468] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9194
2015-12-04 09:50:43.071 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:50:43.071 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
,2015-12-04 09:50:43.075 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04T08:50:43.083Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04 09:50:45.226 ThaliTest[2604:2401232] server session: connected
2015-12-04 09:50:45.226 ThaliTest[2604:2401232] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:50:45.237 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
2015-12-04T08:50:45.238Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:50:45.316Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-04T08:50:45.330Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04T08:50:53.015Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:50:53.016Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:53.016Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:50:53.017Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:50:53.018Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:50:53.020 ThaliTest[2604:2400468] client: socket closed
2015-12-04 09:50:53.021 ThaliTest[2604:2400468] client relay: socket disconnected
2015-12-04 09:50:53.021 ThaliTest[2604:2400468] client relay: 0x19f8bfe0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19ede6f0 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:50:53.022 ThaliTest[2604:2400468] client session: socket closed: Apple-Iphone6-1_PT7135.+FivAg,==
2015-12-04 09:50:53.023 ThaliTest[2604:2400468] client session: onLinkFailure: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:50:53.023 ThaliTest[2604:2400468] client session: disconnect
2015-12-04 09:50:53.024 ThaliTest[2604:2400468] client session: ,stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:53.025 ThaliTest[2604:2400468] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:50:55.476 ThaliTest[2604:2401257] server session: not connected Apple-Iphone5-1_PT9194
,2015-12-04T08:50:58.026Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:50:58.027Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:03.034 ThaliTest[2604:2400591] jxcore: disconnect
2015-12-04 09:51:03.035 ThaliTest[2604:2400591] jxcore: disconnect: fail
2015-12-04T08:51:03.036Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivA,g==
2015-12-04T08:51:03.036Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7135.+FivAg== with availability status: true
2015-12-04T08:51:03.037Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:51:03.037Z SendDataConnector.js: do connect now
2015-12-04 09:51:03.038 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:03.039 ThaliTest[2604:2400591] client session: connect
,2015-12-04 09:51:03.040 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:05.496 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:51:05.497 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:51:05.497 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-,12-04 09:51:05.498 ThaliTest[2604:2400468] server: disconnecting to refresh session (Apple-Iphone5-1_PT9194)
2015-12-04 09:51:05.499 ThaliTest[2604:2400468] server session: disconnect
2015-12-04 09:51:05.499 ThaliTest[2604:2400468] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9194
2015-12-04 09:51:05.503 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:51:05.504 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
2015-12-04T08:51:05.511Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-04 09:51:05.526 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04 09:51:05.966 ThaliTest[2604:2401308] client session: connected
2015-12-04 09:51:05.966 ThaliTest[2604:2401308] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:05.974 ThaliTest[2604:2401308] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:05.975 ThaliTest[2604:2401308] jxcore: connect: success
2015-12-04T08:51:05.976Z SendDataConnector.js: CLIENT connected to 51498, error: null
2015-12-04T08:51:05.976Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:05.978 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:51:05.978 ThaliTest[2604:2400468] client: new accepted socket: 0x19ee89a0
,2015-12-04T08:51:05.989Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:15.068 ThaliTest[2604:2401290] server session: connected
2015-12-04 09:51:15.069 ThaliTest[2604:2401290] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:15.080 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
2015-12-04T08:51:15.083Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:15.403Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-04T08:51:15.418Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04 09:51:15.588 ThaliTest[2604:2401312] server session: not connected Apple-Iphone5-1_PT9194
,2015-12-04T08:51:16.094Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:16.095Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:16.095Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:16.096Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:51:16.097Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:16.098 ThaliTest[2604:2400468] client: socket closed
2015-12-04 09:51:16.099 ThaliTest[2604:2400468] client relay: socket disconnected
2015-12-04 09:51:16.100 ThaliTest[2604:2400468] client relay: 0x19ee89a0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x19d58490 {NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:51:16.101 ThaliTest[2604:2400468] client session: socket closed: Apple-Iphone6-1_PT7135.+FivAg,==
2015-12-04 09:51:16.101 ThaliTest[2604:2400468] client session: onLinkFailure: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:16.101 ThaliTest[2604:2400468] client session: disconnect
2015-12-04 09:51:16.102 ThaliTest[2604:2400468] client session: ,stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:16.104 ThaliTest[2604:2400468] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:51:21.101Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04T08:51:21.101Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:26.112 ThaliTest[2604:2400591] jxcore: disconnect
2015-12-04 09:51:26.113 ThaliTest[2604:2400591] jxcore: disconnect: fail
2015-12-04T08:51:26.114Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivA,g==
2015-12-04T08:51:26.115Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7135.+FivAg== with availability status: true
,2015-12-04T08:51:26.115Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04T08:51:26.116Z SendDataConnector.js: do connect now
,2015-12-04 09:51:26.117 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:26.118 ThaliTest[2604:2400591] client session: connect
2015-12-04 09:51:26.118 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:28.711 ThaliTest[2604:2401545] client session: connected
2015-12-04 09:51:28.711 ThaliTest[2604:2401545] client session: stateChange:1->2 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:28.720 ThaliTest[2604:2401547] client session: fireConnectCallback: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:28.721 ThaliTest[2604:2401547] jxcore: connect: success
2015-12-04T08:51:28.722Z SendDataConnector.js: CLIENT connected ,to 51506, error: null
2015-12-04T08:51:28.723Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:28.726 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:51:28.727 ThaliTest[2604:2400468] client: new accepted socket: 0x19f7a630
,2015-12-04T08:51:28.740Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:51:35.363 ThaliTest[2604:2400468] multipeer session: reset timer
2015-12-04 09:51:35.364 ThaliTest[2604:2400468] multipeer session: stop timer
2015-12-04 09:51:35.364 ThaliTest[2604:2400468] multipeer session: start timer: 0x19d01d00
2015-,12-04 09:51:35.365 ThaliTest[2604:2400468] server: disconnecting to refresh session (Apple-Iphone5-1_PT9194)
2015-12-04 09:51:35.366 ThaliTest[2604:2400468] server session: disconnect
2015-12-04 09:51:35.366 ThaliTest[2604:2400468] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9194
2015-12-04 09:51:35.370 ThaliTest[2604:2400468] server session: connect
2015-12-04 09:51:35.370 ThaliTest[2604:2400468] server session: stateChange:0->1 Apple-Iphone5-1_PT9194
2015-12-04T08:51:35.376Z SendDataTCPServer.,js: TCP/IP server is ended
2015-12-04 09:51:35.388 ThaliTest[2604:2400468] server: accepting invitation Apple-Iphone5-1_PT9194
,2015-12-04 09:51:37.602 ThaliTest[2604:2401545] server session: connected
2015-12-04 09:51:37.603 ThaliTest[2604:2401545] server session: stateChange:1->2 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:37.614 ThaliTest[2604:2400468] server relay: connected (to port: 51478)
,2015-12-04T08:51:37.623Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:51:37.944Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-04T08:51:37.958Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-04T08:51:38.817Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:51:38.818Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:38.818Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:51:38.822Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:38.822Z SendDataConnector.js: Stop data retrieving timer
2015-12-04T08:51:38.823Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:38.823 ThaliTest[2604:2400591] jxcore: disconnect
,2015-12-04 09:51:38.825 ThaliTest[2604:2400591] client session: disconnectFromPeer: Apple-Iphone6-1_PT7135.+FivAg==
2015-12-04 09:51:38.826 ThaliTest[2604:2400591] client session: disconnect
2015-12-04 09:51:38.827 ThaliTest[2604:2400591] client session: stateChange:2->0 Apple-Iphone6-1_PT7135.+FivAg==
,2015-12-04 09:51:38.830 ThaliTest[2604:2400591] jxcore: disconnect: success
,2015-12-04T08:51:38.831Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7135.+FivAg==
---- round done--------
,device[2]: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:38.836Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04T08:51:38.837Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:38.837Z SendDataConnector.js: do connect now
,2015-12-04 09:51:38.838 ThaliTest[2604:2400591] jxcore: connect Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:38.839 ThaliTest[2604:2400591] client session: connect
2015-12-04 09:51:38.840 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple,-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04T08:51:38.851Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:51:41.614 ThaliTest[2604:2401564] client session: connected
2015-12-04 09:51:41.614 ThaliTest[2604:2401564] client session: stateChange:1->2 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:41.636 ThaliTest[2604:2401564] client session: fireConnectCallback: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:41.636 ThaliTest[2604:2401564] jxcore: connect: success
2015-12-04T08:51:41.638Z SendDataConnector.js: CLIENT connected to 51510, error: null
,2015-12-04T08:51:41.639Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:41.642 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:51:41.643 ThaliTest[2604:2400468] client: new accepted socket: 0x19be6f40
,2015-12-04T08:51:41.655Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:51:42.139Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04T08:51:42.151Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:51:42.164Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-04T08:51:42.177Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-04T08:51:42.190Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:51:42.190Z SendDataConnector.js: got all data for this round
,2015-12-04T08:51:42.191Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:51:42.191Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:42.192 ThaliTest[2604:2400591] jxcore: disconnect
,2015-12-04 09:51:42.192 ThaliTest[2604:2400591] client session: disconnectFromPeer: Apple-Iphone5-1_PT9194.4xGkjQ==
2015-12-04 09:51:42.193 ThaliTest[2604:2400591] client session: disconnect
2015-12-04 09:51:42.193 ThaliTest[2604:2400591] client session:, stateChange:2->0 Apple-Iphone5-1_PT9194.4xGkjQ==
,2015-12-04 09:51:42.194 ThaliTest[2604:2400591] jxcore: disconnect: success
2015-12-04T08:51:42.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9194.4xGkjQ==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04T08:51:42.197Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04T08:51:42.197Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04T08:51:42.197Z SendDataConnector.js: do connect now
,2015-12-04 09:51:42.197 ThaliTest[2604:2400591] jxcore: connect Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:51:42.198 ThaliTest[2604:2400591] client session: connect
2015-12-04 09:51:42.198 ThaliTest[2604:2400591] client session: stateChange:0->1 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:45.336 ThaliTest[2604:2401545] client session: connected
2015-12-04 09:51:45.337 ThaliTest[2604:2401545] client session: stateChange:1->2 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:45.346 ThaliTest[2604:2401545] client session: fireConnectCallback: Apple-IpadAir2-1_PT6975.MZRWVw==
2015-12-04 09:51:45.347 ThaliTest[2604:2401545] jxcore: connect: success
2015-12-04T08:51:45.348Z SendDataConnector.js: CLIENT connected to 51513, error: null
2015-12-04T08:51:45.349Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:51:45.352 ThaliTest[2604:2400468] client: relay established
2015-12-04 09:51:45.353 ThaliTest[2604:2400468] client: new accepted socket: 0x19ab4e40
,2015-12-04T08:51:45.364Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:51:45.915Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:51:45.916Z SendDataConnector.js: got all data for this round
,2015-12-04T08:51:45.916Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:51:45.917Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:45.918 ThaliTest[2604:2400591] jxcore: disconnect
,2015-12-04 09:51:45.919 ThaliTest[2604:2400591] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:45.921 ThaliTest[2604:2400591] client session: disconnect
,2015-12-04 09:51:45.922 ThaliTest[2604:2400591] client session: stateChange:2->0 Apple-IpadAir2-1_PT6975.MZRWVw==
,2015-12-04 09:51:45.984 ThaliTest[2604:2400591] jxcore: disconnect: success
,2015-12-04T08:51:45.985Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6975.MZRWVw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT7213","time":113359,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7135.+FivAg==","time":105787,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Appl,e-Iphone5-1_PT9194.4xGkjQ==","time":3355,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6975.MZRWVw==","time":3719,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3719 ms, 99% : 3719 ms, 95 : 3719 ms, 90% : 3719 ms.
,Result count 2, range 3355 ms to  3719 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone6-1_PT7135.+FivAg==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-04T08:51:45.998Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:51:45.999Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:51:47.900 ThaliTest[2604:2401564] server session: not connected Apple-Iphone5-1_PT9194
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-04 09:51:51.891 ThaliTest[2604:2400591] jxcore: stopBroadcasting
2015-12-04 09:51:51.892 ThaliTest[2604:2400591] THEMultipeerSession stopping peer
2015-12-04 09:51:51.893 ThaliTest[2604:2400591] multipeer session: stop timer
2015-12-04 09:51:51.,894 ThaliTest[2604:2400591] server session: disconnect
2015-12-04 09:51:51.894 ThaliTest[2604:2400591] server session: stateChange:2->0 Apple-IpadAir2-1_PT6975
,2015-12-04 09:51:51.903 ThaliTest[2604:2400591] server session: disconnect
2015-12-04 09:51:51.905 ThaliTest[2604:2400591] server session: stateChange:2->0 Apple-Iphone5-1_PT9194
,2015-12-04 09:51:51.913 ThaliTest[2604:2400591] server session: disconnect
2015-12-04 09:51:51.914 ThaliTest[2604:2400591] server session: stateChange:2->0 Apple-Iphone6-1_PT7135
,2015-12-04 09:51:51.921 ThaliTest[2604:2400591] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-04T08:51:51.947Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:51.949Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:51.950Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:51:51.952Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT9194.4xGkjQ==\",\"time\":3355,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT6975.MZRWVw==\",\"time\":3719,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT7135.+FivAg==\",\"time\":105787,\,"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
