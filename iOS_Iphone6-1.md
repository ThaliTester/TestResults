#### Test 525393149f38b37_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2B791AD1-3107-4E0A-BBF3-FE1F7EF73025/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2B791AD1-3107-4E0A-BBF3-FE1F7EF73025/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/525393149f38b37/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C553684-CCD5-4A42-B49C-18502812CA15/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60631"
,(lldb)     command script import "/tmp/2B791AD1-3107-4E0A-BBF3-FE1F7EF73025/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 16:20:27.958 ThaliTest[2622:2216316] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/76B2BD6A-CA78-4C1C-A73A-942E29B9915D/Library/Cookies/Cookies.binarycookies
,2015-12-03 16:20:28.338 ThaliTest[2622:2216316] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 16:20:28.339 ThaliTest[2622:2216316] Multi-tasking -> Device: YES, App: YES
,2015-12-03 16:20:28.347 ThaliTest[2622:2216316] Unlimited access to network resources
,2015-12-03 16:20:28.353 ThaliTest[2622:2216316] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 16:20:31.773 ThaliTest[2622:2216316] Resetting plugins due to page load.
,2015-12-03 16:20:32.144 ThaliTest[2622:2216316] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/3C553684-CCD5-4A42-B49C-18502812CA15/ThaliTest.app/www/index.html
,2015-12-03 16:20:32.268 ThaliTest[2622:2216316] JXcore Cordova plugin initializing
,2015-12-03 16:20:32.269 ThaliTest[2622:2216455] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT4561
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 50499
,2015-12-03 16:26:45.578 ThaliTest[2622:2216455] jxcore: startBroadcasting
,2015-12-03 16:26:45.589 ThaliTest[2622:2216455] server: starting Apple-Iphone6-1_PT4561.tcwUUA==
2015-12-03 16:26:45.590 ThaliTest[2622:2216455] multipeer session: start timer: 0x19ec0a70
2015-12-03 16:26:45.591 ThaliTest[2622:2216455] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT4561
2015-12-03 16:26:45.593 ThaliTest[2622:2216455] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03T15:26:45.601Z SendDataTCPServer.js: TCP/IP server is bound to port: 50499
,2015-12-03 16:26:46.707 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:26:46.709 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:26:46.717Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:26:46.718 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03T15:26:46.719Z SendDataConnector.js: doCo,nnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T15:26:46.721Z SendDataConnector.js: do connect now
2015-12-03 16:26:46.721 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:26:46.721 ThaliTest[2,622:2216455] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:26:46.722 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:26:46.722 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9874.kgLPmg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2877.NAxVhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 16:26:52.849 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:26:52.850 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:26:52.850 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-12-03 16:26:52.850 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:26:52.850 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:52.853 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:55.041 ThaliTest[2622:2216980] server session: connected
2015-12-03 16:26:55.042 ThaliTest[2622:2216980] server session: stateChange:1->2 Apple-Iphone5s-1_PT8182
,2015-12-03 16:26:55.057 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:26:55.066Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:55.357Z SendDataTCPServer.js: TCP/IP server has received 25854 bytes of data
,2015-12-03T15:26:55.374Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-03T15:26:55.388Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-03T15:26:55.404Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:26:57.087 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:26:57.088 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:26:57.088 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:26:57.089 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:26:57.089 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:57.100 ThaliTest[2622:2216316] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:59.543 ThaliTest[2622:2216977] server session: connected
2015-12-03 16:26:59.543 ThaliTest[2622:2216977] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:26:59.567 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:26:59.573Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:26:59.808Z SendDataTCPServer.js: TCP/IP server has received 23948 bytes of data
,2015-12-03T15:26:59.823Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-03T15:26:59.839Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-03T15:26:59.855Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:27:05.420 ThaliTest[2622:2216970] server session: not connected Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:10.080 ThaliTest[2622:2216970] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:16.326 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:27:16.327 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:27:16.328 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:27:16.328 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8182)
2015-12-03 16:27:16.329 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:27:16.329 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-Iphone5s-1_PT8182
2015-12-03 16:27:16.332 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:27:16.333 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5s-1_PT8182
2015-12-03T15:27:16.340Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-03 16:27:16.352 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:18.589 ThaliTest[2622:2217008] server session: connected
,2015-12-03 16:27:18.590 ThaliTest[2622:2217008] server session: stateChange:1->2 Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:18.604 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:27:18.614Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:18.691Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T15:27:18.705Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:27:19.739 ThaliTest[2622:2216970] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:27:19.740 ThaliTest[2622:2216970] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:27:19.741 ThaliTest,[2622:2216970] client session: disconnect
2015-12-03 16:27:19.741 ThaliTest[2622:2216970] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:27:19.742 ThaliTest[2622:2216970] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 16:27:19.742 ThaliTest[2622:2216970] jxcore: connect: fail: Peer disconnected
,2015-12-03T15:27:19.745Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T15:27:19.745Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T15:27:19.746Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03 16:27:21.215 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:27:21.216 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:27:21.217 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:27:21.217 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2877)
2015-12-03 16:27:21.217 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:27:21.218 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-IpadAir2-1_PT2877
2015-12-03 16:27:21.221 ThaliTest[2622:2216316] server session: connect
2015-12-03T15:27:21.226Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:27:21.222 ThaliTest[2622:2216316] server session: stateChange,:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:21.242 ThaliTest[2622:2216316] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:23.807 ThaliTest[2622:2217026] server session: connected
2015-12-03 16:27:23.807 ThaliTest[2622:2217026] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:23.827 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
2015-12-03T15:27:23.828Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:23.854Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-03T15:27:23.868Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03T15:27:24.748Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:27:24.749Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:27:28.887 ThaliTest[2622:2217029] server session: not connected Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:29.753 ThaliTest[2622:2216455] jxcore: disconnect
2015-12-03 16:27:29.754 ThaliTest[2622:2216455] jxcore: disconnect: fail
2015-12-03T15:27:29.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:27:29.755Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T15:27:29.755Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-1,2-03T15:27:29.756Z SendDataConnector.js: do connect now
,2015-12-03 16:27:29.757 ThaliTest[2622:2216455] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:27:29.758 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:27:29.759 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:27:34.128 ThaliTest[2622:2217026] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:38.931 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:27:38.932 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:27:38.932 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:27:38.933 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8182)
2015-12-03 16:27:38.933 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:27:38.934 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-Iphone5s-1_PT8182
2015-12-03 16:27:38.937 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:27:38.938 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5s-1_PT8182
,2015-12-03T15:27:38.949Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:27:38.954 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:41.335 ThaliTest[2622:2217029] server session: connected
2015-12-03 16:27:41.336 ThaliTest[2622:2217029] server session: stateChange:1->2 Apple-Iphone5s-1_PT8182
,2015-12-03 16:27:41.346 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
2015-12-03T15:27:41.349Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:41.440Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T15:27:41.454Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:27:44.118 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:27:44.118 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:27:44.119 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:27:44.119 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2877)
2015-12-03 16:27:44.120 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:27:44.120 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-IpadAir2-1_PT2877
2015-12-03 16:27:44.125 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:27:44.125 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03T15:27:44.136Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:27:44.141 ThaliTest[2622:2216316] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:46.519 ThaliTest[2622:2217029] server session: connected
2015-12-03 16:27:46.520 ThaliTest[2622:2217029] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:46.544 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:27:46.556Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:27:46.583Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:27:51.471 ThaliTest[2622:2216316] client: lost peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:27:51.471 ThaliTest[2622:2216316] client session: onPeerLost: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 16:27:51.954 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 16:27:56.666 ThaliTest[2622:2217029] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:27:59.405 ThaliTest[2622:2217026] server session: not connected Apple-Iphone5s-1_PT8182
,2015-12-03 16:28:02.762 ThaliTest[2622:2217029] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:02.763 ThaliTest[2622:2217029] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:02.763 ThaliTest,[2622:2217029] client session: disconnect
2015-12-03 16:28:02.764 ThaliTest[2622:2217029] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:02.765 ThaliTest[2622:2217029] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 16:28:02.765 ThaliTest[2622:2217029] jxcore: connect: fail: Peer disconnected
,2015-12-03T15:28:02.767Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T15:28:02.768Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T15:28:02.768Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03 16:28:06.892 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:28:06.893 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:28:06.894 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:28:06.895 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2877)
2015-12-03 16:28:06.895 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:28:06.896 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-IpadAir2-1_PT2877
2015-12-03 16:28:06.899 ThaliTest[2622:2216316] server session: connect
,2015-12-03 16:28:06.900 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:06.908 ThaliTest[2622:2216316] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03T15:28:06.910Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T15:28:07.777Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:28:07.778Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:28:09.255 ThaliTest[2622:2217071] server session: connected
2015-12-03 16:28:09.256 ThaliTest[2622:2217071] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:09.263 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:28:09.276Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:28:09.314Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:28:12.784 ThaliTest[2622:2216455] jxcore: disconnect
2015-12-03 16:28:12.784 ThaliTest[2622:2216455] jxcore: disconnect: fail
2015-12-03T15:28:12.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T15:28:12.786Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
,2015-12-03T15:28:12.786Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T15:28:12.786Z SendDataConnector.js: do connect now
,2015-12-03 16:28:12.787 ThaliTest[2622:2216455] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:28:12.788 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:28:12.789 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:28:19.321 ThaliTest[2622:2217071] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:29.714 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:28:29.715 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:28:29.716 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:28:29.716 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-IpadAir2-1_PT2877)
2015-12-03 16:28:29.717 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:28:29.717 ThaliTest[2622:2216316] server session: state,Change:2->0 Apple-IpadAir2-1_PT2877
,2015-12-03T15:28:29.731Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 16:28:29.778 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:28:29.779 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:29.785 ThaliTest[2622:2216316] server: accepting invitation Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:32.144 ThaliTest[2622:2217117] server session: connected
2015-12-03 16:28:32.145 ThaliTest[2622:2217117] server session: stateChange:1->2 Apple-IpadAir2-1_PT2877
,2015-12-03T15:28:32.181Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03 16:28:32.181 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:28:32.221Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:28:34.954 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:28:34.954 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:28:34.955 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:28:34.956 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:28:34.956 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:34.967 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:28:37.231 ThaliTest[2622:2217142] server session: connected
2015-12-03 16:28:37.232 ThaliTest[2622:2217142] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:37.363 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
2015-12-03T15:28:37.368Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:28:37.841Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-03T15:28:37.855Z SendDataTCPServer.js: TCP/IP server has received 16864 bytes of data
,2015-12-03T15:28:37.870Z SendDataTCPServer.js: TCP/IP server has received 27776 bytes of data
,2015-12-03T15:28:37.883Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
,2015-12-03T15:28:37.898Z SendDataTCPServer.js: TCP/IP server has received 53568 bytes of data
,2015-12-03T15:28:37.912Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-03T15:28:37.926Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-12-03T15:28:37.941Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 16:28:42.268 ThaliTest[2622:2217150] server session: not connected Apple-IpadAir2-1_PT2877
,2015-12-03 16:28:43.017 ThaliTest[2622:2217071] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:43.018 ThaliTest[2622:2217071] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:43.018 ThaliTest,[2622:2217071] client session: disconnect
2015-12-03 16:28:43.019 ThaliTest[2622:2217071] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:43.020 ThaliTest[2622:2217071] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 16:28:43.020 ThaliTest[2622:2217071] jxcore: connect: fail: Peer disconnected
,2015-12-03T15:28:43.022Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T15:28:43.022Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T15:28:43.023Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T15:28:48.030Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T15:28:48.031Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:28:48.036 ThaliTest[2622:2217071] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:28:51.336 ThaliTest[2622:2216316] client: lost peer: Apple-Iphone5s-1_PT8182.c6Lgog==
2015-12-03 16:28:51.336 ThaliTest[2622:2216316] client session: onPeerLost: Apple-Iphone5s-1_PT8182.c6Lgog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8182.c6Lgog==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-03 16:28:53.038 ThaliTest[2622:2216455] jxcore: disconnect
2015-12-03 16:28:53.039 ThaliTest[2622:2216455] jxcore: disconnect: fail
2015-12-03T15:28:53.039Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T15:28:53.040Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
,2015-12-03T15:28:53.040Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T15:28:53.041Z SendDataConnector.js: do connect now
,2015-12-03 16:28:53.041 ThaliTest[2622:2216455] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:28:53.043 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:28:53.043 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:28:58.545 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:28:58.546 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:28:58.546 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:28:58.547 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:28:58.547 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:28:58.548 ThaliTest[2622:2216316] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9874
2015-12-03 16:28:58.551 ThaliTest[2622:2216316] server session: connect
2015-12-03T15:28:58.554Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:28:58.551 ThaliTest[2622:2216316] server session: stateChange:0,->1 Apple-Iphone5-1_PT9874
,2015-12-03 16:28:58.568 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:29:01.321 ThaliTest[2622:2217071] server session: connected
2015-12-03 16:29:01.321 ThaliTest[2622:2217071] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:29:01.332 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
2015-12-03T15:29:01.334Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:29:01.410Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-12-03T15:29:01.424Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:29:11.621 ThaliTest[2622:2217153] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:29:21.735 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:29:21.736 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:29:21.737 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:29:21.737 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:29:21.738 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:29:21.738 ThaliTest[2622:2216316] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9874
2015-12-03 16:29:21.741 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:29:21.741 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03T15:29:21.753Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:29:21.757 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:29:24.214 ThaliTest[2622:2217228] server session: connected
2015-12-03 16:29:24.215 ThaliTest[2622:2217228] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:29:24.225 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:29:24.231Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:29:24.306Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:29:26.049 ThaliTest[2622:2217228] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:29:26.049 ThaliTest[2622:2217228] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:29:26.050 ThaliTest,[2622:2217228] client session: disconnect
2015-12-03 16:29:26.050 ThaliTest[2622:2217228] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:29:26.051 ThaliTest[2622:2217228] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:29:26.051 ThaliTest[2622:2217228] jxcore: connect: fail: Peer disconnected
,2015-12-03T15:29:26.053Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T15:29:26.054Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T15:29:26.054Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-03T15:29:31.055Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:29:31.056Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:29:34.311 ThaliTest[2622:2217228] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:29:36.069 ThaliTest[2622:2216455] jxcore: disconnect
2015-12-03 16:29:36.070 ThaliTest[2622:2216455] jxcore: disconnect: fail
2015-12-03T15:29:36.070Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T15:29:36.071Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T15:29:36.071Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T15:29:36.071Z SendDataConnector.js: do connect now
2015-12-03 16:29:36.072 ThaliTest[2622:2216455] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:29:36.073 ThaliTest[2622:2216455] client session: connect
,2015-12-03 16:29:36.074 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:29:44.708 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:29:44.708 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:29:44.709 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:29:44.710 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:29:44.710 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:29:44.710 ThaliTest[2622:2216316] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9874
2015-12-03 16:29:44.715 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:29:44.716 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
,2015-12-03T15:29:44.729Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 16:29:44.734 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:29:46.871 ThaliTest[2622:2217227] server session: connected
2015-12-03 16:29:46.872 ThaliTest[2622:2217227] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:29:46.883 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:29:46.887Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:29:46.953Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T15:29:46.966Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:29:57.292 ThaliTest[2622:2217316] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:30:07.205 ThaliTest[2622:2216316] multipeer session: reset timer
2015-12-03 16:30:07.206 ThaliTest[2622:2216316] multipeer session: stop timer
2015-12-03 16:30:07.207 ThaliTest[2622:2216316] multipeer session: start timer: 0x19ec0a70
2015-,12-03 16:30:07.207 ThaliTest[2622:2216316] server: disconnecting to refresh session (Apple-Iphone5-1_PT9874)
2015-12-03 16:30:07.208 ThaliTest[2622:2216316] server session: disconnect
2015-12-03 16:30:07.208 ThaliTest[2622:2216316] server session: stateC,hange:2->0 Apple-Iphone5-1_PT9874
2015-12-03 16:30:07.212 ThaliTest[2622:2216316] server session: connect
2015-12-03 16:30:07.212 ThaliTest[2622:2216316] server session: stateChange:0->1 Apple-Iphone5-1_PT9874
2015-12-03T15:30:07.214Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-03 16:30:07.229 ThaliTest[2622:2216316] server: accepting invitation Apple-Iphone5-1_PT9874
,2015-12-03 16:30:09.078 ThaliTest[2622:2217367] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:30:09.079 ThaliTest[2622:2217367] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:30:09.080 ThaliTest,[2622:2217367] client session: disconnect
2015-12-03 16:30:09.080 ThaliTest[2622:2217367] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:30:09.081 ThaliTest[2622:2217367] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 16:30:09.082 ThaliTest[2622:2217367] jxcore: connect: fail: Peer disconnected
,2015-12-03T15:30:09.083Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T15:30:09.084Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T15:30:09.087Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 16:30:09.089 ThaliTest[2622:2216455] jxcore: disconnect
,2015-12-03 16:30:09.090 ThaliTest[2622:2216455] jxcore: disconnect: fail
,2015-12-03T15:30:09.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:30:09.094Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:30:09.095Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03T15:30:09.095Z SendDataConnector.js: do connect now
,2015-12-03 16:30:09.096 ThaliTest[2622:2216455] jxcore: connect Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:30:09.097 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:30:09.097 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:30:09.435 ThaliTest[2622:2217316] server session: connected
2015-12-03 16:30:09.436 ThaliTest[2622:2217316] server session: stateChange:1->2 Apple-Iphone5-1_PT9874
,2015-12-03 16:30:09.449 ThaliTest[2622:2216316] server relay: connected (to port: 50499)
,2015-12-03T15:30:09.456Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T15:30:09.518Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T15:30:09.532Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 16:30:11.531 ThaliTest[2622:2217315] client session: connected
2015-12-03 16:30:11.532 ThaliTest[2622:2217315] client session: stateChange:1->2 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:30:11.540 ThaliTest[2622:2217316] client session: fireConnectCallback: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:30:11.541 ThaliTest[2622:2217316] jxcore: connect: success
2015-12-03T15:30:11.543Z SendDataConnector.js: CLIENT connected ,to 50530, error: null
2015-12-03T15:30:11.543Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:30:11.547 ThaliTest[2622:2216316] client: relay established
2015-12-03 16:30:11.548 ThaliTest[2622:2216316] client: new accepted socket: 0x19f58ad0
,2015-12-03T15:30:11.563Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:30:11.928Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-03T15:30:11.940Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T15:30:11.953Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T15:30:11.953Z SendDataConnector.js: got all data for this round
,2015-12-03T15:30:11.954Z SendDataConnector.js: CLIENT Stop now
2015-12-03T15:30:11.954Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03 16:30:11.955 ThaliTest[2622:2216455] jxcore: disconnect
,2015-12-03 16:30:11.956 ThaliTest[2622:2216455] client session: disconnectFromPeer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:30:11.956 ThaliTest[2622:2216455] client session: disconnect
2015-12-03 16:30:11.956 ThaliTest[2622:2216455] client session: stateChange:2->0 Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:30:11.957 ThaliTest[2622:2216455] jxcore: disconnect: success
2015-12-03T15:30:11.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9874.kgLPmg==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03T15:30:11.960Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:30:11.960Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03T15:30:11.960Z SendDataConnector.js: do connect now
,2015-12-03 16:30:11.960 ThaliTest[2622:2216455] jxcore: connect Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:30:11.961 ThaliTest[2622:2216455] client session: connect
2015-12-03 16:30:11.961 ThaliTest[2622:2216455] client session: stateChange:0->1 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:30:15.783 ThaliTest[2622:2217370] client session: connected
2015-12-03 16:30:15.784 ThaliTest[2622:2217370] client session: stateChange:1->2 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:30:15.791 ThaliTest[2622:2217316] client session: fireConnectCallback: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:30:15.792 ThaliTest[2622:2217316] jxcore: connect: success
2015-12-03T15:30:15.793Z SendDataConnector.js: CLIENT connected to 50533, error: null
2015-12-03T15:30:15.794Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 16:30:15.797 ThaliTest[2622:2216316] client: relay established
2015-12-03 16:30:15.798 ThaliTest[2622:2216316] client: new accepted socket: 0x19f675d0
,2015-12-03T15:30:15.810Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T15:30:16.125Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-03T15:30:16.138Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T15:30:16.139Z SendDataConnector.js: got all data for this round
,2015-12-03T15:30:16.139Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T15:30:16.140Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:30:16.140 ThaliTest[2622:2216455] jxcore: disconnect
,2015-12-03 16:30:16.141 ThaliTest[2622:2216455] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:30:16.142 ThaliTest[2622:2216455] client session: disconnect
,2015-12-03 16:30:16.142 ThaliTest[2622:2216455] client session: stateChange:2->0 Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:30:16.201 ThaliTest[2622:2216455] jxcore: disconnect: success
,2015-12-03T15:30:16.202Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2877.NAxVhQ==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT4561","time":210642,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7057.4CFLyQ==","time":202367,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Appl,e-Iphone5-1_PT9874.kgLPmg==","time":2859,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT2877.NAxVhQ==","time":4179,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4179 ms, 99% : 4179 ms, 95 : 4179 ms, 90% : 4179 ms.
,Result count 2, range 2859 ms to  4179 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-03T15:30:16.209Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T15:30:16.210Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 16:30:19.764 ThaliTest[2622:2217370] server session: not connected Apple-Iphone5-1_PT9874
,2015-12-03 16:30:37.208 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:30:37.231 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:30:37.232 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:30:37.233 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:31:07.208 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:31:07.226 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:31:07.229 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:31:07.230 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:31:37.208 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:31:37.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:31:37.226 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:31:37.229 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:32:07.206 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:32:07.224 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:32:07.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:32:07.227 ThaliTest[2622:2216316] clien,t: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:32:37.206 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:32:37.224 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:32:37.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:32:37.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:07.206 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:33:07.225 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:33:07.226 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:33:07.228 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:33:37.206 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:33:37.224 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:33:37.226 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:33:37.226 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:34:07.206 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:34:07.223 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:34:07.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:34:07.228 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:34:37.204 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:34:37.221 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:34:37.222 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:34:37.224 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:35:07.204 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:35:07.223 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:35:07.224 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:35:07.226 ThaliTest[2622:2216316] clien,t: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:35:37.204 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:35:37.225 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:35:37.226 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:35:37.226 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:36:07.204 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:36:07.221 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
2015-12-03 16:36:07.222 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
,2015-12-03 16:36:07.223 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 16:36:37.204 ThaliTest[2622:2216316] multipeer session: restart
,2015-12-03 16:36:37.218 ThaliTest[2622:2216316] client: found peer: Apple-IpadAir2-1_PT2877.NAxVhQ==
2015-12-03 16:36:37.220 ThaliTest[2622:2216316] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 16:36:37.221 ThaliTest[2622:2216316] client: found peer: Apple-Iphone5-1_PT9874.kgLPmg==
,2015-12-03 16:37:07.204 ThaliTest[2622:2216316] multipeer session: restart
2015-12-03 16:37:07.209 ThaliTest[2622:2216316] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x485e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2622 stopped
* thread #1: tid = 0x21d17c, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x21d17c, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000485e2 ThaliTest`main + 50

```
