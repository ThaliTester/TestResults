#### Test 52539314a265f91_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/255F6B0F-2422-4290-A931-6D609591465E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/255F6B0F-2422-4290-A931-6D609591465E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/506940EA-96D4-47D6-82A9-CE8513CCE4D2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61276"
,(lldb)     command script import "/tmp/255F6B0F-2422-4290-A931-6D609591465E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-04 09:02:07.459 ThaliTest[2008:3117511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0FCA34F1-BF8A-4E97-9476-508C7E6D92AF/Library/Cookies/Cookies.binarycookies
,2015-12-04 09:02:07.746 ThaliTest[2008:3117511] Apache Cordova native platform version 3.9.2 is starting.
2015-12-04 09:02:07.746 ThaliTest[2008:3117511] Multi-tasking -> Device: YES, App: YES
,2015-12-04 09:02:07.752 ThaliTest[2008:3117511] Unlimited access to network resources
,2015-12-04 09:02:07.758 ThaliTest[2008:3117511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:02:11.705 ThaliTest[2008:3117511] Resetting plugins due to page load.
,2015-12-04 09:02:13.114 ThaliTest[2008:3117511] Finished load of: file:///var/mobile/Containers/Bundle/Application/506940EA-96D4-47D6-82A9-CE8513CCE4D2/ThaliTest.app/www/index.html
,2015-12-04 09:02:13.259 ThaliTest[2008:3117511] JXcore Cordova plugin initializing
,2015-12-04 09:02:13.260 ThaliTest[2008:3117716] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT2716
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":2,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 51734
,2015-12-04 09:09:28.047 ThaliTest[2008:3117716] jxcore: startBroadcasting
,2015-12-04 09:09:28.053 ThaliTest[2008:3117716] server: starting Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:28.053 ThaliTest[2008:3117716] multipeer session: start timer: 0x16cbdb50
,2015-12-04 09:09:28.054 ThaliTest[2008:3117716] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2716
,2015-12-04 09:09:28.055 ThaliTest[2008:3117716] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-04T08:09:28.056Z SendDataTCPServer.js: TCP/IP server is bound to port: 51734
,2015-12-04 09:09:28.361 ThaliTest[2008:3117511] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9579.WOzdIQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:09:28.363Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:09:28.363Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:09:28.363Z SendDataConnector.js: do connect now
,2015-12-04 09:09:28.366 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:09:28.366 ThaliTest[2008:3117716] client session: connect
2015-12-04 09:09:28.366 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:29.177 ThaliTest[2008:3117511] client: found peer: Apple-Iphone5-1_PT1372.xmPKsQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1372.xmPKsQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-04 09:09:29.922 ThaliTest[2008:3117511] multipeer session: reset timer
2015-12-04 09:09:29.922 ThaliTest[2008:3117511] multipeer session: stop timer
2015-12-04 09:09:29.923 ThaliTest[2008:3117511] multipeer session: start timer: 0x16cbdb50
,2015-12-04 09:09:29.923 ThaliTest[2008:3117511] server session: connect
,2015-12-04 09:09:29.923 ThaliTest[2008:3117511] server session: stateChange:0->1 Apple-Iphone6-1_PT9579
,2015-12-04 09:09:29.925 ThaliTest[2008:3117511] server: accepting invitation Apple-Iphone6-1_PT9579
,2015-12-04 09:09:31.195 ThaliTest[2008:3118574] client session: connected
2015-12-04 09:09:31.195 ThaliTest[2008:3118574] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:31.199 ThaliTest[2008:3118573] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:09:31.199 ThaliTest[2008:3118573] jxcore: connect: success
2015-12-04T08:09:31.199Z SendDataConnector.js: CLIENT connected to 51737, error: null
2015-12-04T08:09:31.200Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:31.201 ThaliTest[2008:3117511] client: relay established
2015-12-04 09:09:31.201 ThaliTest[2008:3117511] client: new accepted socket: 0x18041af0
,2015-12-04T08:09:31.215Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:09:31.441Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-04T08:09:31.452Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:09:31.465Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-04T08:09:31.745Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-04 09:09:31.907 ThaliTest[2008:3117511] multipeer session: reset timer
2015-12-04 09:09:31.907 ThaliTest[2008:3117511] multipeer session: stop timer
2015-12-04 09:09:31.907 ThaliTest[2008:3117511] multipeer session: start timer: 0x16cbdb50
2015-,12-04 09:09:31.908 ThaliTest[2008:3117511] server session: connect
2015-12-04 09:09:31.908 ThaliTest[2008:3117511] server session: stateChange:0->1 Apple-Iphone5-1_PT1372
,2015-12-04 09:09:31.910 ThaliTest[2008:3117511] server: accepting invitation Apple-Iphone5-1_PT1372
,2015-12-04 09:09:32.328 ThaliTest[2008:3118562] server session: connected
2015-12-04 09:09:32.328 ThaliTest[2008:3118562] server session: stateChange:1->2 Apple-Iphone6-1_PT9579
,2015-12-04 09:09:32.331 ThaliTest[2008:3117511] server relay: connected (to port: 51734)
,2015-12-04T08:09:32.337Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:09:32.750Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-04T08:09:32.763Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-04T08:09:32.813Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-04T08:09:32.827Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:09:32.868 ThaliTest[2008:3118563] server session: not connected Apple-Iphone6-1_PT9579
,2015-12-04 09:09:34.454 ThaliTest[2008:3118563] server session: connected
2015-12-04 09:09:34.454 ThaliTest[2008:3118563] server session: stateChange:1->2 Apple-Iphone5-1_PT1372
,2015-12-04 09:09:34.457 ThaliTest[2008:3117511] server relay: connected (to port: 51734)
,2015-12-04T08:09:34.463Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:09:34.959Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-04T08:09:34.970Z SendDataTCPServer.js: TCP/IP server has received 10912 bytes of data
,2015-12-04T08:09:34.984Z SendDataTCPServer.js: TCP/IP server has received 24800 bytes of data
,2015-12-04T08:09:34.997Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-12-04T08:09:35.019Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-12-04T08:09:35.572Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-12-04 09:09:36.418 ThaliTest[2008:3118573] server session: not connected Apple-Iphone5-1_PT1372
,2015-12-04T08:09:41.753Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:09:41.753Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:09:41.754Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:09:41.754Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:09:41.755Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:09:41.755 ThaliTest[2008:3117511] client: socket closed
2015-12-04 09:09:41.756 ThaliTest[2008:3117511] client relay: socket disconnected
,2015-12-04 09:09:41.756 ThaliTest[2008:3117511] client relay: 0x18041af0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:09:41.756 ThaliTest[2008:3117511] client session: socket closed: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:09:41.756 ThaliTest[2008:3117511] client session: onLinkFailure: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:09:41.756 ThaliTest[2008:3117511] c,lient session: disconnect
2015-12-04 09:09:41.756 ThaliTest[2008:3117511] client session: stateChange:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:41.758 ThaliTest[2008:3117511] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:09:46.755Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:09:46.755Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:51.763 ThaliTest[2008:3117716] jxcore: disconnect
,2015-12-04 09:09:51.763 ThaliTest[2008:3117716] jxcore: disconnect: fail
,2015-12-04T08:09:51.764Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:09:51.764Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT9579.WOzdIQ== with availability status: true
2015-12-04T08:09:51.764Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:09:51.765Z SendDataConnector.js: do connect now
,2015-12-04 09:09:51.765 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:51.766 ThaliTest[2008:3117716] client session: connect
,2015-12-04 09:09:51.766 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:55.711 ThaliTest[2008:3118647] client session: connected
2015-12-04 09:09:55.711 ThaliTest[2008:3118647] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:55.713 ThaliTest[2008:3118647] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:09:55.713 ThaliTest[2008:3118647] jxcore: connect: success
2015-12-04T08:09:55.713Z SendDataConnector.js: CLIENT connected to 51743, error: null
2015-12-04T08:09:55.714Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:55.715 ThaliTest[2008:3117511] client: relay established
2015-12-04 09:09:55.715 ThaliTest[2008:3117511] client: new accepted socket: 0x1803dd70
,2015-12-04T08:09:55.728Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04 09:10:01.909 ThaliTest[2008:3117511] multipeer session: restart
,2015-12-04 09:10:01.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:01.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:10:05.751Z SendDataConnector.js: Receiving data timeout now
,2015-12-04T08:10:05.751Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:10:05.751Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-04T08:10:05.751Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:10:05.752Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:10:05.752 ThaliTest[2008:3117511] client: socket closed
2015-12-04 09:10:05.752 ThaliTest[2008:3117511] client relay: socket disconnected
2015-12-04 09:10:05.752 ThaliTest[2008:3117511] client relay: 0x1803dd70 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:10:05.752 ThaliTest[2008:3117511] client session: socket closed: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12,-04 09:10:05.753 ThaliTest[2008:3117511] client session: onLinkFailure: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:05.753 ThaliTest[2008:3117511] client session: disconnect
2015-12-04 09:10:05.753 ThaliTest[2008:3117511] client session: stateChange,:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:05.755 ThaliTest[2008:3117511] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:10.752Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:10.752Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:15.759 ThaliTest[2008:3117716] jxcore: disconnect
,2015-12-04 09:10:15.759 ThaliTest[2008:3117716] jxcore: disconnect: fail
2015-12-04T08:10:15.759Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:15.760Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT9579.WOzdIQ== with availability status: true
,2015-12-04T08:10:15.760Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:10:15.760Z SendDataConnector.js: do connect now
2015-12-04 09:10:15.760 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:15.761 ThaliTest[2008:3117716] client session: connect
2015-12-04 09:10:15.761 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:19.460 ThaliTest[2008:3118706] client session: connected
2015-12-04 09:10:19.460 ThaliTest[2008:3118706] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:19.462 ThaliTest[2008:3118706] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:19.462 ThaliTest[2008:3118706] jxcore: connect: success
,2015-12-04T08:10:19.463Z SendDataConnector.js: CLIENT connected to 51748, error: null
,2015-12-04T08:10:19.463Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:10:19.464 ThaliTest[2008:3117511] client: relay established
2015-12-04 09:10:19.464 ThaliTest[2008:3117511] client: new accepted socket: 0x16f2b7a0
,2015-12-04T08:10:19.477Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04T08:10:29.508Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:10:29.509Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:10:29.509Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:10:29.509Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:10:29.510Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:10:29.510 ThaliTest[2008:3117511] client: socket closed
2015-12-04 09:10:29.510 ThaliTest[2008:3117511] client relay: socket disconnected
,2015-12-04 09:10:29.511 ThaliTest[2008:3117511] client relay: 0x16f2b7a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-04 09:10:,29.511 ThaliTest[2008:3117511] client session: socket closed: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:29.511 ThaliTest[2008:3117511] client session: onLinkFailure: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:29.511 ThaliTest[2008:3117511] client session: disconnect
2015-12-04 09:10:29.511 ThaliTest[2008:3117511] client session: stateChange:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:29.513 ThaliTest[2008:3117511] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:31.909 ThaliTest[2008:3117511] multipeer session: restart
,2015-12-04 09:10:31.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:10:31.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:34.513Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:34.513Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:39.517 ThaliTest[2008:3117716] jxcore: disconnect
2015-12-04 09:10:39.517 ThaliTest[2008:3117716] jxcore: disconnect: fail
2015-12-04T08:10:39.517Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:10:39.517Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT9579.WOzdIQ== with availability status: true
2015-12-04T08:10:39.517Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:10:39.517Z SendDataConnector.js: do connect now
,2015-12-04 09:10:39.518 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:39.518 ThaliTest[2008:3117716] client session: connect
2015-12-04 09:10:39.519 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:42.992 ThaliTest[2008:3118744] client session: connected
2015-12-04 09:10:42.992 ThaliTest[2008:3118744] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:43.007 ThaliTest[2008:3118744] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:43.008 ThaliTest[2008:3118744] jxcore: connect: success
2015-12-04T08:10:43.008Z SendDataConnector.js: CLIENT connected to 51753, error: null
2015-12-04T08:10:43.008Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:10:43.009 ThaliTest[2008:3117511] client: relay established
2015-12-04 09:10:43.009 ThaliTest[2008:3117511] client: new accepted socket: 0x16cd6450
,2015-12-04T08:10:43.023Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04T08:10:53.077Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:10:53.078Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:10:53.078Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:10:53.078Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-04T08:10:53.079Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:10:53.079 ThaliTest[2008:3117511] client: socket closed
2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client relay: socket disconnected
,2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client relay: 0x16cd6450 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client session: socket closed: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client session: onLinkFailure: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client session: disconnect
2015-12-04 09:10:53.080 ThaliTest[2008:3117511] client session: stateChange:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:53.082 ThaliTest[2008:3117511] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:58.080Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:10:58.081Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:01.909 ThaliTest[2008:3117511] multipeer session: restart
,2015-12-04 09:11:01.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:11:01.920 ThaliTest[2008:3117511] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:03.091 ThaliTest[2008:3117716] jxcore: disconnect
2015-12-04 09:11:03.091 ThaliTest[2008:3117716] jxcore: disconnect: fail
2015-12-04T08:11:03.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdI,Q==
2015-12-04T08:11:03.091Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT9579.WOzdIQ== with availability status: true
2015-12-04T08:11:03.091Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:11:03.091Z SendDataConnector.js: do connect now
,2015-12-04 09:11:03.092 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:11:03.092 ThaliTest[2008:3117716] client session: connect
2015-12-04 09:11:03.092 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:06.348 ThaliTest[2008:3118835] client session: connected
2015-12-04 09:11:06.348 ThaliTest[2008:3118835] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:06.403 ThaliTest[2008:3118809] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:11:06.403 ThaliTest[2008:3118809] jxcore: connect: success
,2015-12-04T08:11:06.404Z SendDataConnector.js: CLIENT connected to 51758, error: null
2015-12-04T08:11:06.405Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:11:06.406 ThaliTest[2008:3117511] client: relay established
,2015-12-04 09:11:06.406 ThaliTest[2008:3117511] client: new accepted socket: 0x18029660
,2015-12-04T08:11:06.418Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-04T08:11:16.454Z SendDataConnector.js: Receiving data timeout now
2015-12-04T08:11:16.454Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:11:16.454Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04T08:11:16.456Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:11:16.456Z SendDataConnector.js: Stop data retrieving timer
,2015-12-04T08:11:16.456Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:11:16.458 ThaliTest[2008:3117716] jxcore: disconnect
2015-12-04 09:11:16.459 ThaliTest[2008:3117716] client session: disconnectFromPeer: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04 09:11:16.459 ThaliTest[2008:3117716] client session: disconnect
,2015-12-04 09:11:16.460 ThaliTest[2008:3117716] client session: stateChange:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:16.463 ThaliTest[2008:3117716] jxcore: disconnect: success
2015-12-04T08:11:16.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdIQ==
---- round done--------
device[2]: Apple-Iphone5-1_PT1372.x,mPKsQ==
2015-12-04T08:11:16.465Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:11:16.465Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04T08:11:16.465Z SendDataConnector.js: do connect now
2015-12-04 09:11:16.466 ThaliTest[2008:3117716] jxcore: connect Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:11:16.466 ThaliTest[2008:3117716] client session: connect
,2015-12-04 09:11:16.466 ThaliTest[2008:3117716] client session: stateChange:0->1 Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04T08:11:16.472Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-04 09:11:19.323 ThaliTest[2008:3118809] client session: connected
2015-12-04 09:11:19.323 ThaliTest[2008:3118809] client session: stateChange:1->2 Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:11:19.326 ThaliTest[2008:3118859] client session: fireConnectCallback: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:11:19.326 ThaliTest[2008:3118859] jxcore: connect: success
2015-12-04T08:11:19.326Z SendDataConnector.js: CLIENT connected to 51761, error: null
,2015-12-04T08:11:19.327Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:11:19.328 ThaliTest[2008:3117511] client: relay established
2015-12-04 09:11:19.328 ThaliTest[2008:3117511] client: new accepted socket: 0x16b522a0
,2015-12-04T08:11:19.340Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:11:19.670Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:11:19.681Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-04T08:11:19.681Z SendDataConnector.js: got all data for this round
,2015-12-04T08:11:19.682Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:11:19.682Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:11:19.684 ThaliTest[2008:3117716] jxcore: disconnect
,2015-12-04 09:11:19.684 ThaliTest[2008:3117716] client session: disconnectFromPeer: Apple-Iphone5-1_PT1372.xmPKsQ==
2015-12-04 09:11:19.684 ThaliTest[2008:3117716] client session: disconnect
2015-12-04 09:11:19.684 ThaliTest[2008:3117716] client session: stateChange:2->0 Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:11:19.689 ThaliTest[2008:3117716] jxcore: disconnect: success
2015-12-04T08:11:19.690Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1372.xmPKsQ==
---- round done--------
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2716","time":111649,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9579.WOzdIQ==","time":108092,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000},{"name":"Apple-Iphone5-1_PT1372.xmPKsQ==","time":3216,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 3216 ms, 99% : 3216 ms, 95 : 3216 ms, 90% : 3216 ms.
Result count 1, range 3216 ms to  3216 ms.
sendList failed peers count : 1 [50 %]
- Peer ID : Apple-Iphone6-1_PT9579.WOzdIQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-04T08:11:19.697Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:11:19.697Z SendDataConnector.js: CLIENT closeC,lientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
2015-12-04 09:11:20.211 ThaliTest[2008:3117716] jxcore: stopBroadcasting
,2015-12-04 09:11:20.211 ThaliTest[2008:3117716] THEMultipeerSession stopping peer
,2015-12-04 09:11:20.212 ThaliTest[2008:3117716] multipeer session: stop timer
,2015-12-04 09:11:20.212 ThaliTest[2008:3117716] server session: disconnect
2015-12-04 09:11:20.212 ThaliTest[2008:3117716] server session: stateChange:2->0 Apple-Iphone5-1_PT1372
,2015-12-04 09:11:20.214 ThaliTest[2008:3117716] server session: disconnect
2015-12-04 09:11:20.214 ThaliTest[2008:3117716] server session: stateChange:2->0 Apple-Iphone6-1_PT9579
,2015-12-04 09:11:20.218 ThaliTest[2008:3117716] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-04T08:11:20.233Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:11:20.234Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:11:20.234Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT1372.xmPKsQ==\",\"time\":3216,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT9579.WOzdIQ==\",\"time\":108092,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":3,"addressList":[],}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
