#### Test 519863409bc5c94_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F47AC2EB-776A-4DA4-9A36-178BF7C7ABF9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F47AC2EB-776A-4DA4-9A36-178BF7C7ABF9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863409bc5c94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/396394EA-8E67-41A4-9386-A8671285C08D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58052"
,(lldb)     command script import "/tmp/F47AC2EB-776A-4DA4-9A36-178BF7C7ABF9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-30 11:49:18.712 ThaliTest[2161:1843418] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31F5D30F-1D7A-4CFC-A4BA-84209644AAAE/Library/Cookies/Cookies.binarycookies
,2015-11-30 11:49:19.100 ThaliTest[2161:1843418] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-30 11:49:19.101 ThaliTest[2161:1843418] Multi-tasking -> Device: YES, App: YES
,2015-11-30 11:49:19.109 ThaliTest[2161:1843418] Unlimited access to network resources
,2015-11-30 11:49:19.114 ThaliTest[2161:1843418] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-30 11:49:22.714 ThaliTest[2161:1843418] Resetting plugins due to page load.
,2015-11-30 11:49:23.080 ThaliTest[2161:1843418] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/396394EA-8E67-41A4-9386-A8671285C08D/ThaliTest.app/www/index.html
,2015-11-30 11:49:23.207 ThaliTest[2161:1843418] JXcore Cordova plugin initializing
,2015-11-30 11:49:23.208 ThaliTest[2161:1843560] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT7389
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 63587
,2015-11-30 11:55:59.725 ThaliTest[2161:1843560] jxcore: startBroadcasting
,2015-11-30 11:55:59.738 ThaliTest[2161:1843560] server: starting Apple-Iphone6-1_PT7389.2i+JNA==
,2015-11-30 11:55:59.739 ThaliTest[2161:1843560] multipeer session: start timer: 0x1be88b20
2015-11-30 11:55:59.740 ThaliTest[2161:1843560] THEMultipeerSession initialized peer Apple-Iphone6-1_PT7389
2015-11-30 11:55:59.740 ThaliTest[2161:1843560] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-11-30T10:55:59.741Z SendDataTCPServer.js: TCP/IP server is bound to port: 63587
,2015-11-30 11:55:59.992 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2455.0R5G/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30T10:55:59.995Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30T10:55:59.995Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2455.0R5G/g==
20,15-11-30T10:55:59.995Z SendDataConnector.js: do connect now
,2015-11-30 11:55:59.995 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:55:59.996 ThaliTest[2161:1843560] client session: connect
,2015-11-30 11:55:59.996 ThaliTest[2161:1843560] client session: stateChange:0->1 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:00.074 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4872.+CDkQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:00.078 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-30 11:56:03.830 ThaliTest[2161:1844203] client session: connected
2015-11-30 11:56:03.831 ThaliTest[2161:1844203] client session: stateChange:1->2 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:03.836 ThaliTest[2161:1844203] client session: fireConnectCallback: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:03.836 ThaliTest[2161:1844203] jxcore: connect: success
,2015-11-30T10:56:03.838Z SendDataConnector.js: CLIENT connected to 63590, error: null
,2015-11-30T10:56:03.839Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:03.845 ThaliTest[2161:1843418] client: relay established
2015-11-30 11:56:03.845 ThaliTest[2161:1843418] client: new accepted socket: 0x1756fa10
,2015-11-30T10:56:03.859Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:05.203Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-30T10:56:05.203Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:05.206Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:56:05.206Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:05.208 ThaliTest[2161:1843560] jxcore: disconnect
,2015-11-30 11:56:05.210 ThaliTest[2161:1843560] client session: disconnectFromPeer: Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:05.210 ThaliTest[2161:1843560] client session: disconnect
,2015-11-30 11:56:05.211 ThaliTest[2161:1843560] client session: stateChange:2->0 Apple-Iphone5-1_PT2455.0R5G/g==
,2015-11-30 11:56:05.214 ThaliTest[2161:1843560] jxcore: disconnect: success
2015-11-30T10:56:05.218Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2455.0R5G/g==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:05.222Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:05.223Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:56:05.223Z SendDataConnector.js: do connect now
,2015-11-30 11:56:05.224 ThaliTest[2161:1843560] jxcore: connect Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:56:05.225 ThaliTest[2161:1843560] client session: connect
2015-11-30 11:56:05.225 ThaliTest[2161:1843560] client session: stateChange:0->1 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:05.491 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:56:05.491 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:56:05.492 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-11-30 11:56:05.492 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:56:05.492 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:05.496 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:05.733 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:56:05.734 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:56:05.734 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 11:56:05.734 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:56:05.735 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:05.741 ThaliTest[2161:1843418] server: accepting invitation Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:05.818 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:56:05.819 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:56:05.819 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 11:56:05.819 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:56:05.819 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30 11:56:05.823 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 11:56:07.820 ThaliTest[2161:1844243] server session: connected
2015-11-30 11:56:07.821 ThaliTest[2161:1844243] server session: stateChange:1->2 Apple-Iphone5s-1_PT7955
,2015-11-30 11:56:07.828 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T10:56:07.837Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:56:07.982 ThaliTest[2161:1844244] client session: connected
2015-11-30 11:56:07.983 ThaliTest[2161:1844244] client session: stateChange:1->2 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:07.988 ThaliTest[2161:1844244] client session: fireConnectCallback: Apple-IpadAir2-1_PT4872.+CDkQA==
2015-11-30 11:56:07.989 ThaliTest[2161:1844244] jxcore: connect: success
2015-11-30T10:56:07.990Z SendDataConnector.js: CLIENT connected, to 63594, error: null
,2015-11-30T10:56:07.990Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:07.993 ThaliTest[2161:1843418] client: relay established
2015-11-30 11:56:07.994 ThaliTest[2161:1843418] client: new accepted socket: 0x1beab080
,2015-11-30 11:56:08.005 ThaliTest[2161:1844244] server session: connected
2015-11-30T10:56:08.005Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
2015-11-30 11:56:08.006 ThaliTest[2161:1844244] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 11:56:08.014 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T10:56:08.356Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:56:08.357Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 11:56:08.377 ThaliTest[2161:1844203] server session: connected
2015-11-30 11:56:08.378 ThaliTest[2161:1844203] server session: stateChange:1->2 Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:08.380 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T10:56:08.385Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:56:08.387 ThaliTest[2161:1844243] server session: not connected Apple-Iphone5s-1_PT7955
,2015-11-30T10:56:08.432Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-30T10:56:08.432Z SendDataConnector.js: got all data for this round
,2015-11-30T10:56:08.433Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T10:56:08.433Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:56:08.434 ThaliTest[2161:1843560] jxcore: disconnect
,2015-11-30 11:56:08.435 ThaliTest[2161:1843560] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:08.435 ThaliTest[2161:1843560] client session: disconnect
,2015-11-30 11:56:08.436 ThaliTest[2161:1843560] client session: stateChange:2->0 Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:08.495 ThaliTest[2161:1843560] jxcore: disconnect: success
,2015-11-30T10:56:08.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4872.+CDkQA==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:56:08.497Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:56:08.498Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:56:08.498Z SendDataConnector.js: do connect now
,2015-11-30 11:56:08.498 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:08.499 ThaliTest[2161:1843560] client session: connect
,2015-11-30 11:56:08.499 ThaliTest[2161:1843560] client session: stateChange:0->1 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:56:08.832Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-11-30T10:56:08.844Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30T10:56:08.858Z SendDataTCPServer.js: TCP/IP server has received 20832 bytes of data
,2015-11-30T10:56:08.870Z SendDataTCPServer.js: TCP/IP server has received 61504 bytes of data
,2015-11-30T10:56:08.919Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-11-30T10:56:08.931Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-11-30T10:56:08.944Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-11-30 11:56:08.995 ThaliTest[2161:1844244] server session: not connected Apple-IpadAir2-1_PT4872
,2015-11-30 11:56:11.021 ThaliTest[2161:1844244] client session: connected
2015-11-30 11:56:11.022 ThaliTest[2161:1844244] client session: stateChange:1->2 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:56:11.028 ThaliTest[2161:1844244] client session: fireConnectCallback: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:56:11.029 ThaliTest[2161:1844244] jxcore: connect: success
2015-11-30T10:56:11.031Z SendDataConnector.js: CLIENT connected to 63600, error: null
,2015-11-30T10:56:11.032Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:56:11.035 ThaliTest[2161:1843418] client: relay established
2015-11-30 11:56:11.036 ThaliTest[2161:1843418] client: new accepted socket: 0x1be8ea10
,2015-11-30T10:56:11.048Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-30T10:56:11.499Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-30T10:56:11.523Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-30T10:56:11.535Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-30 11:56:35.820 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:56:35.841 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:56:35.843 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:56:35.843 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:56:59.173 ThaliTest[2161:1844244] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30T10:57:01.538Z SendDataConnector.js: Receiving data timeout now
,2015-11-30T10:57:01.539Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:57:01.540Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:57:01.541Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:57:01.541Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30 11:57:01.543 ThaliTest[2161:1843418] client: socket closed
2015-11-30 11:57:01.544 ThaliTest[2161:1843418] client relay: socket disconnected
2015-11-30 11:57:01.544 ThaliTest[2161:1843418] client relay: 0x1be8ea10 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo=0x1bf3ae10 {NSLocalizedDescription=Socket closed by remote peer} 
2015-11-30 11:57:01.545 ThaliTest[2161:1843418] client session: socket closed: Apple-Iphone5s-1_PT7955.qINS9,Q==
2015-11-30 11:57:01.545 ThaliTest[2161:1843418] client session: onLinkFailure: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:01.546 ThaliTest[2161:1843418] client session: disconnect
2015-11-30 11:57:01.546 ThaliTest[2161:1843418] client session,: stateChange:2->0 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:01.549 ThaliTest[2161:1843418] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:05.820 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:57:05.837 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:05.840 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:57:05.840 ThaliTest[2161:1843418] clien,t: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30T10:57:06.546Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:57:06.547Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:09.278 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:57:09.278 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:57:09.279 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 11:57:09.279 ThaliTest[2161:1843418] server: disconnecting to refresh session (Apple-Iphone5-1_PT2455)
2015-11-30 11:57:09.279 ThaliTest[2161:1843418] server session: disconnect
2015-11-30 11:57:09.279 ThaliTest[2161:1843418] server session: stateChange:2->0 Apple-Iphone5-1_PT2455
,2015-11-30 11:57:09.281 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:57:09.281 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30 11:57:09.284 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30T10:57:09.292Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30 11:57:11.385 ThaliTest[2161:1844320] server session: connected
2015-11-30 11:57:11.386 ThaliTest[2161:1844320] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 11:57:11.392 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
2015-11-30T10:57:11.394Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:57:11.471Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-30T10:57:11.485Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 11:57:11.550 ThaliTest[2161:1843560] jxcore: disconnect
2015-11-30 11:57:11.551 ThaliTest[2161:1843560] jxcore: disconnect: fail
2015-11-30T10:57:11.553Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:57:11.553Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT7955.qINS9Q== with availability status: true
2015-11-30T10:57:11.553Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:57:11.554Z SendDataConnector.js: do connect now
,2015-11-30 11:57:11.555 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:11.556 ThaliTest[2161:1843560] client session: connect
2015-11-30 11:57:11.556 ThaliTest[2161:1843560] client session: stateChange:0->1 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:14.082 ThaliTest[2161:1844320] client session: connected
2015-11-30 11:57:14.082 ThaliTest[2161:1844320] client session: stateChange:1->2 Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:14.087 ThaliTest[2161:1844244] client session: fireConnectCallback: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:14.088 ThaliTest[2161:1844244] jxcore: connect: success
2015-11-30T10:57:14.089Z SendDataConnector.js: CLIENT connected, to 63607, error: null
2015-11-30T10:57:14.090Z SendDataConnector.js: CLIENT starting client 
,2015-11-30 11:57:14.094 ThaliTest[2161:1843418] client: relay established
2015-11-30 11:57:14.095 ThaliTest[2161:1843418] client: new accepted socket: 0x1769d320
,2015-11-30T10:57:14.107Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-11-30 11:57:14.350 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:14.870 ThaliTest[2161:1844244] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30 11:57:19.135 ThaliTest[2161:1843418] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:19.136 ThaliTest[2161:1843418] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:19.136 ThaliTest[2161:184341,8] client session: onLinkFailure: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:19.137 ThaliTest[2161:1843418] client session: disconnect
2015-11-30 11:57:19.137 ThaliTest[2161:1843418] client session: stateChange:2->0 Apple-Iphone5s-1_PT7955.qINS9Q=,=
2015-11-30 11:57:19.140 ThaliTest[2161:1843418] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7955.qINS9Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:20.113 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30 11:57:39.278 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:57:39.295 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:57:39.295 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:39.297 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:57:46.844 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:57:52.584 ThaliTest[2161:1843418] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:57:52.584 ThaliTest[2161:1843418] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30 11:57:53.657 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":true}]
,2015-11-30T10:58:04.173Z SendDataConnector.js: Receiving data timeout now
2015-11-30T10:58:04.174Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:58:04.174Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:58:04.175Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:58:04.175Z SendDataConnector.js: ----------------- closeClientSocket
,2015-11-30T10:58:09.177Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:58:09.177Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:09.177Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:09.277 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:58:09.296 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:09.298 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:58:09.299 ThaliTest[2161:1843418] clien,t: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:58:11.632 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:58:11.633 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:58:11.633 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 11:58:11.634 ThaliTest[2161:1843418] server: disconnecting to refresh session (Apple-Iphone5-1_PT2455)
2015-11-30 11:58:11.635 ThaliTest[2161:1843418] server session: disconnect
2015-11-30 11:58:11.635 ThaliTest[2161:1843418] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2455
2015-11-30 11:58:11.638 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:58:11.639 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30T10:58:11.650Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-30 11:58:11.655 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 11:58:14.111 ThaliTest[2161:1844442] server session: connected
,2015-11-30 11:58:14.111 ThaliTest[2161:1844442] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 11:58:14.128 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T10:58:14.138Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30 11:58:14.178 ThaliTest[2161:1843560] jxcore: disconnect
2015-11-30 11:58:14.179 ThaliTest[2161:1843560] jxcore: disconnect: fail
2015-11-30T10:58:14.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS,9Q==
2015-11-30T10:58:14.180Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT7955.qINS9Q== with availability status: true
,2015-11-30T10:58:14.180Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:14.180Z SendDataConnector.js: do connect now
,2015-11-30 11:58:14.181 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:14.182 ThaliTest[2161:1843560] client session: connect
2015-11-30 11:58:14.183 ThaliTest[2161:1843560] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:58:14.597Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 11:58:15.671 ThaliTest[2161:1843418] client: lost peer: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:15.672 ThaliTest[2161:1843418] client session: onPeerLost: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:15.672 ThaliTest[2161:184341,8] client session: onLinkFailure: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:15.673 ThaliTest[2161:1843418] client session: disconnect
2015-11-30 11:58:15.673 ThaliTest[2161:1843418] client session: stateChange:1->0 Apple-Iphone5s-1_PT7955.qINS9Q=,=
2015-11-30 11:58:15.674 ThaliTest[2161:1843418] client session: fireConnectCallback: Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:15.674 ThaliTest[2161:1843418] jxcore: connect: fail: Peer disconnected
2015-11-30T10:58:15.675Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2015-11-30T10:58:15.676Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-11-30T10:58:15.676Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-30T10:58:15.677Z SendDataConnecto,r.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7955.qINS9Q==","peerName":"(null)","peerAvailable":false}]
,2015-11-30T10:58:20.684Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:58:20.685Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:20.685Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:25.688 ThaliTest[2161:1843560] jxcore: disconnect
2015-11-30 11:58:25.689 ThaliTest[2161:1843560] jxcore: disconnect: fail
2015-11-30T10:58:25.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS,9Q==
2015-11-30T10:58:25.690Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT7955.qINS9Q== with availability status: true
2015-11-30T10:58:25.690Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:25.690Z SendDataConnector.js: do connect now
,2015-11-30 11:58:25.691 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:25.692 ThaliTest[2161:1843560] client: connect: unreachable Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:58:25.692 ThaliTest[2161:1843560] jxcore: connect: fail: Peer unreachable
2015-11-30T10:58:25.694Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-11-30T10:58:25.694Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-11-30T10:58:25.694Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:58:25.695Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-11-30T10:58:30.705Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:30.705Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30T10:58:30.706Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:35.707 ThaliTest[2161:1843560] jxcore: disconnect
2015-11-30 11:58:35.708 ThaliTest[2161:1843560] jxcore: disconnect: fail
2015-11-30T10:58:35.709Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:35.709Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT7955.qINS9Q== with availability status: true
,2015-11-30T10:58:35.709Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30T10:58:35.710Z SendDataConnector.js: do connect now
,2015-11-30 11:58:35.711 ThaliTest[2161:1843560] jxcore: connect Apple-Iphone5s-1_PT7955.qINS9Q==
,2015-11-30 11:58:35.712 ThaliTest[2161:1843560] client: connect: unreachable Apple-Iphone5s-1_PT7955.qINS9Q==
2015-11-30 11:58:35.712 ThaliTest[2161:1843560] jxcore: connect: fail: Peer unreachable
2015-11-30T10:58:35.713Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-11-30T10:58:35.714Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-11-30T10:58:35.714Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30T10:58:35.716Z SendDataConnector.js: CLIENT Stop now
2015-11-30T10:58:35.716Z SendDataConnector.js: Stop data retrieving timer
2015-11-30T10:58:35.717Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:35.717 ThaliTest[2161:1843560] jxcore: disconnect
2015-11-30 11:58:35.718 ThaliTest[2161:1843560] jxcore: disconnect: fail
2015-11-30T10:58:35.719Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7955.qINS,9Q==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT7389","time":156011,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT2455.0R5G/g==","time":5209,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1,_PT4872.+CDkQA==","time":3209,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7955.qINS9Q==","time":147216,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"d,ataReceived":90000}]}
,sendList : 100% : 5209 ms, 99% : 5209 ms, 95 : 5209 ms, 90% : 5209 ms.
,Result count 2, range 3209 ms to  5209 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT7955.qINS9Q==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-11-30T10:58:35.732Z SendDataConnector.js: CLIENT Stop now
,2015-11-30T10:58:35.733Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-30 11:58:41.635 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:58:41.650 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:58:41.651 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:58:44.500 ThaliTest[2161:1844490] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30 11:59:11.635 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:59:11.652 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:59:11.654 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 11:59:14.945 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 11:59:14.946 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 11:59:14.946 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 11:59:14.947 ThaliTest[2161:1843418] server: disconnecting to refresh session (Apple-Iphone5-1_PT2455)
2015-11-30 11:59:14.947 ThaliTest[2161:1843418] server session: disconnect
2015-11-30 11:59:14.948 ThaliTest[2161:1843418] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2455
2015-11-30 11:59:14.952 ThaliTest[2161:1843418] server session: connect
2015-11-30 11:59:14.952 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
,2015-11-30T10:59:14.963Z SendDataTCPServer.js: TCP/IP server is ended
2015-11-30 11:59:14.971 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 11:59:17.171 ThaliTest[2161:1844570] server session: connected
2015-11-30 11:59:17.172 ThaliTest[2161:1844570] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 11:59:17.177 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T10:59:17.188Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T10:59:17.390Z SendDataTCPServer.js: TCP/IP server has received 8928 bytes of data
,2015-11-30T10:59:17.403Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 11:59:44.948 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 11:59:44.965 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 11:59:44.966 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 12:00:07.319 ThaliTest[2161:1844673] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30 12:00:14.946 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 12:00:14.961 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 12:00:14.962 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,2015-11-30 12:00:17.834 ThaliTest[2161:1843418] multipeer session: reset timer
2015-11-30 12:00:17.834 ThaliTest[2161:1843418] multipeer session: stop timer
2015-11-30 12:00:17.835 ThaliTest[2161:1843418] multipeer session: start timer: 0x1be88b20
2015-,11-30 12:00:17.836 ThaliTest[2161:1843418] server: disconnecting to refresh session (Apple-Iphone5-1_PT2455)
2015-11-30 12:00:17.836 ThaliTest[2161:1843418] server session: disconnect
2015-11-30 12:00:17.837 ThaliTest[2161:1843418] server session: stateC,hange:2->0 Apple-Iphone5-1_PT2455
2015-11-30 12:00:17.839 ThaliTest[2161:1843418] server session: connect
2015-11-30 12:00:17.840 ThaliTest[2161:1843418] server session: stateChange:0->1 Apple-Iphone5-1_PT2455
2015-11-30T11:00:17.844Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-11-30 12:00:17.855 ThaliTest[2161:1843418] server: accepting invitation Apple-Iphone5-1_PT2455
,2015-11-30 12:00:20.099 ThaliTest[2161:1844707] server session: connected
2015-11-30 12:00:20.100 ThaliTest[2161:1844707] server session: stateChange:1->2 Apple-Iphone5-1_PT2455
,2015-11-30 12:00:20.107 ThaliTest[2161:1843418] server relay: connected (to port: 63587)
,2015-11-30T11:00:20.115Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-30T11:00:20.427Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-11-30T11:00:20.442Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-11-30 12:00:24.150 ThaliTest[2161:1844676] server session: not connected Apple-Iphone5-1_PT2455
,2015-11-30 12:00:47.837 ThaliTest[2161:1843418] multipeer session: restart
,2015-11-30 12:00:47.852 ThaliTest[2161:1843418] client: found peer: Apple-Iphone5-1_PT2455.0R5G/g==
2015-11-30 12:00:47.855 ThaliTest[2161:1843418] client: found peer: Apple-IpadAir2-1_PT4872.+CDkQA==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
2015-11-30 12:01:11.119 ThaliTest[2161:1843560] jxcore: stopBroadcasting
2015-11-30 12:01:11.120 ThaliTest[2161:1843560] THEMultipeerSession stopping peer
2015-11-30 12:01:11.120 ThaliTest[2161:18435,60] multipeer session: stop timer
2015-11-30 12:01:11.121 ThaliTest[2161:1843560] server session: disconnect
2015-11-30 12:01:11.122 ThaliTest[2161:1843560] server session: stateChange:2->0 Apple-IpadAir2-1_PT4872
,2015-11-30 12:01:11.132 ThaliTest[2161:1843560] server session: disconnect
,2015-11-30 12:01:11.134 ThaliTest[2161:1843560] server session: stateChange:2->0 Apple-Iphone5s-1_PT7955
,2015-11-30 12:01:11.138 ThaliTest[2161:1843560] server session: disconnect
2015-11-30 12:01:11.138 ThaliTest[2161:1843560] server session: stateChange:2->0 Apple-Iphone5-1_PT2455
2015-11-30 12:01:11.146 ThaliTest[2161:1843560] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-30T11:01:11.166Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:11.168Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:11.170Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-30T11:01:11.170Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT4872.+CDkQA==\",\"time\":3209,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5-1_PT2455.0R5G/g==\",\"time\":5209,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT7955.qINS9Q==\",\"time\":147216,,\"result\":\"Peer unreachable\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
