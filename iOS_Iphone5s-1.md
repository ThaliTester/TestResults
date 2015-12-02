#### Test 51986340441e256_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/50C57C52-A154-4364-8B02-8D3657D2DA00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/50C57C52-A154-4364-8B02-8D3657D2DA00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8460B556-4B9B-4548-845C-EF5742A58655/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59787"
,(lldb)     command script import "/tmp/50C57C52-A154-4364-8B02-8D3657D2DA00/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:55:54.951 ThaliTest[2348:2204080] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/31E75CD6-9C8F-45EA-9E82-C14124A3748A/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:55:55.365 ThaliTest[2348:2204080] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:55:55.367 ThaliTest[2348:2204080] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:55:55.374 ThaliTest[2348:2204080] Unlimited access to network resources
,2015-12-02 18:55:55.381 ThaliTest[2348:2204080] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:55:59.131 ThaliTest[2348:2204080] Resetting plugins due to page load.
,2015-12-02 18:55:59.366 ThaliTest[2348:2204080] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8460B556-4B9B-4548-845C-EF5742A58655/ThaliTest.app/www/index.html
,2015-12-02 18:55:59.509 ThaliTest[2348:2204080] JXcore Cordova plugin initializing
,2015-12-02 18:55:59.511 ThaliTest[2348:2204194] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT3324
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 49479
,2015-12-02 19:01:51.483 ThaliTest[2348:2204194] jxcore: startBroadcasting
,2015-12-02 19:01:51.495 ThaliTest[2348:2204194] server: starting Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:51.496 ThaliTest[2348:2204194] multipeer session: start timer: 0x1a6b3ab0
2015-12-02 19:01:51.497 ThaliTest[2348:2204194] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT3324
2015-12-02 19:01:51.498 ThaliTest[2348:2204194] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-02T18:01:51.503Z SendDataTCPServer.js: TCP/IP server is bound to port: 49479
,2015-12-02 19:01:51.625 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT367.AiGtHw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T18:01:51.634Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02T18:01:51.636Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T18:01:51.636Z SendDataConnector.js: do connect now
2015-12-02 19:01:51.637 ThaliTest[2348:2204194] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:01:51.638 ThaliTest[2348:2204194] client session: connect
2015-12-02 19:01:51.638 ThaliTest[2348:2204194] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:01:51.908 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1792.Nse+hg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:51.973 ThaliTest[2348:2204080] multipeer session: reset timer
2015-12-02 19:01:51.973 ThaliTest[2348:2204080] multipeer session: stop timer
2015-12-02 19:01:51.973 ThaliTest[2348:2204080] multipeer session: start timer: 0x1a6b3ab0
2015-12-02 19:01:51.973 ThaliTest[2348:2204080] server session: connect
2015-12-02 19:01:51.974 ThaliTest[2348:2204080] server session: stateChange:0->1 Apple-Iphone5-1_PT1792
,2015-12-02 19:01:51.979 ThaliTest[2348:2204080] server: accepting invitation Apple-Iphone5-1_PT1792
,2015-12-02 19:01:52.576 ThaliTest[2348:2204080] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8086.XWQOsA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 19:01:53.528 ThaliTest[2348:2204080] multipeer session: reset timer
2015-12-02 19:01:53.529 ThaliTest[2348:2204080] multipeer session: stop timer
2015-12-02 19:01:53.530 ThaliTest[2348:2204080] multipeer session: start timer: 0x1a6b3ab0
2015-,12-02 19:01:53.530 ThaliTest[2348:2204080] server session: connect
2015-12-02 19:01:53.531 ThaliTest[2348:2204080] server session: stateChange:0->1 Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:53.539 ThaliTest[2348:2204080] server: accepting invitation Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:53.644 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-02 19:01:54.184 ThaliTest[2348:2204777] server session: connected
,2015-12-02 19:01:54.187 ThaliTest[2348:2204777] server session: stateChange:1->2 Apple-Iphone5-1_PT1792
,2015-12-02 19:01:54.194 ThaliTest[2348:2204080] server relay: connected (to port: 49479)
,2015-12-02T18:01:54.204Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:01:54.743Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-02T18:01:54.759Z SendDataTCPServer.js: TCP/IP server has received 13888 bytes of data
,2015-12-02T18:01:54.776Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-12-02T18:01:54.795Z SendDataTCPServer.js: TCP/IP server has received 41664 bytes of data
,2015-12-02T18:01:54.812Z SendDataTCPServer.js: TCP/IP server has received 51584 bytes of data
,2015-12-02T18:01:54.828Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-12-02T18:01:54.840Z SendDataTCPServer.js: TCP/IP server has received 69440 bytes of data
,2015-12-02T18:01:54.855Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-12-02T18:01:54.868Z SendDataTCPServer.js: TCP/IP server has received 92256 bytes of data
,2015-12-02T18:01:54.880Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:01:54.902 ThaliTest[2348:2204786] server session: not connected Apple-Iphone5-1_PT1792
,2015-12-02 19:01:55.422 ThaliTest[2348:2204080] multipeer session: reset timer
2015-12-02 19:01:55.423 ThaliTest[2348:2204080] multipeer session: stop timer
2015-12-02 19:01:55.424 ThaliTest[2348:2204080] multipeer session: start timer: 0x1a6b3ab0
2015-,12-02 19:01:55.424 ThaliTest[2348:2204080] server session: connect
2015-12-02 19:01:55.425 ThaliTest[2348:2204080] server session: stateChange:0->1 Apple-Iphone6-1_PT8308
,2015-12-02 19:01:55.437 ThaliTest[2348:2204080] server: accepting invitation Apple-Iphone6-1_PT8308
,2015-12-02 19:01:56.384 ThaliTest[2348:2204784] server session: connected
2015-12-02 19:01:56.385 ThaliTest[2348:2204784] server session: stateChange:1->2 Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:56.391 ThaliTest[2348:2204080] server relay: connected (to port: 49479)
,2015-12-02T18:01:56.399Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:01:56.640Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-02T18:01:56.656Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-02T18:01:56.671Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-02T18:01:56.859Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-02T18:01:56.924Z SendDataTCPServer.js: TCP/IP server has received 87092 bytes of data
,2015-12-02T18:01:56.941Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:01:57.008 ThaliTest[2348:2204790] server session: not connected Apple-IpadAir2-1_PT8086
,2015-12-02 19:01:57.757 ThaliTest[2348:2204790] server session: connected
2015-12-02 19:01:57.758 ThaliTest[2348:2204790] server session: stateChange:1->2 Apple-Iphone6-1_PT8308
,2015-12-02 19:01:57.765 ThaliTest[2348:2204080] server relay: connected (to port: 49479)
2015-12-02T18:01:57.767Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:01:58.050Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-02T18:01:58.104Z SendDataTCPServer.js: TCP/IP server has received 10666 bytes of data
,2015-12-02T18:01:58.119Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-02T18:01:58.183Z SendDataTCPServer.js: TCP/IP server has received 38568 bytes of data
,2015-12-02T18:01:58.198Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:01:58.238 ThaliTest[2348:2204786] server session: not connected Apple-Iphone6-1_PT8308
,2015-12-02 19:02:24.643 ThaliTest[2348:2204856] client session: not connected Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:02:24.644 ThaliTest[2348:2204856] client session: onLinkFailure: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:02:24.644 ThaliTest,[2348:2204856] client session: disconnect
2015-12-02 19:02:24.645 ThaliTest[2348:2204856] client session: stateChange:1->0 Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:02:24.646 ThaliTest[2348:2204856] client session: fireConnectCallback: Apple-Iphone5s,-1_PT367.AiGtHw==
2015-12-02 19:02:24.646 ThaliTest[2348:2204856] jxcore: connect: fail: Peer disconnected
,2015-12-02T18:02:24.649Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-02T18:02:24.649Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-02T18:02:24.651Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02 19:02:25.425 ThaliTest[2348:2204080] multipeer session: restart
,2015-12-02 19:02:25.447 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:25.450 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:25.453 ThaliTest[2348:2204080] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
2015-12-02 19:02:25.457 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02T18:02:29.656Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02T18:02:29.657Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:02:34.666 ThaliTest[2348:2204194] jxcore: disconnect
2015-12-02 19:02:34.666 ThaliTest[2348:2204194] jxcore: disconnect: fail
2015-12-02T18:02:34.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT367.AiGtH,w==
,2015-12-02T18:02:34.668Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT367.AiGtHw== with availability status: true
2015-12-02T18:02:34.668Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-1,2-02T18:02:34.669Z SendDataConnector.js: do connect now
,2015-12-02 19:02:34.669 ThaliTest[2348:2204194] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:02:34.670 ThaliTest[2348:2204194] client session: connect
,2015-12-02 19:02:34.671 ThaliTest[2348:2204194] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:02:55.426 ThaliTest[2348:2204080] multipeer session: restart
,2015-12-02 19:02:55.451 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:02:55.456 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:55.456 ThaliTest[2348:2204080] client,: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:02:55.458 ThaliTest[2348:2204080] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:03:03.337 ThaliTest[2348:2204080] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:03:03.338 ThaliTest[2348:2204080] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:03:06.592 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-02 19:03:07.680 ThaliTest[2348:2204903] client session: not connected Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:07.681 ThaliTest[2348:2204903] client session: onLinkFailure: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:07.682 ThaliTest,[2348:2204903] client session: disconnect
2015-12-02 19:03:07.683 ThaliTest[2348:2204903] client session: stateChange:1->0 Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:07.683 ThaliTest[2348:2204903] client session: fireConnectCallback: Apple-Iphone5s,-1_PT367.AiGtHw==
2015-12-02 19:03:07.684 ThaliTest[2348:2204903] jxcore: connect: fail: Peer disconnected
,2015-12-02T18:03:07.686Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-02T18:03:07.686Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-02T18:03:07.687Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02 19:03:09.704 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02T18:03:12.691Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02T18:03:12.692Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:03:17.695 ThaliTest[2348:2204194] jxcore: disconnect
2015-12-02 19:03:17.696 ThaliTest[2348:2204194] jxcore: disconnect: fail
2015-12-02T18:03:17.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT367.AiGtH,w==
2015-12-02T18:03:17.697Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT367.AiGtHw== with availability status: true
,2015-12-02T18:03:17.698Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T18:03:17.698Z SendDataConnector.js: do connect now
,2015-12-02 19:03:17.699 ThaliTest[2348:2204194] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:03:17.701 ThaliTest[2348:2204194] client session: connect
2015-12-02 19:03:17.701 ThaliTest[2348:2204194] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:03:25.426 ThaliTest[2348:2204080] multipeer session: restart
,2015-12-02 19:03:25.453 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:03:25.457 ThaliTest[2348:2204080] client: found peer: Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:03:25.458 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:03:25.460 ThaliTest[2348:2204080] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 19:03:33.843 ThaliTest[2348:2204080] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:03:33.844 ThaliTest[2348:2204080] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-02 19:03:36.475 ThaliTest[2348:2204080] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-02 19:03:50.710 ThaliTest[2348:2204903] client session: not connected Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:50.711 ThaliTest[2348:2204903] client session: onLinkFailure: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:50.711 ThaliTest,[2348:2204903] client session: disconnect
2015-12-02 19:03:50.712 ThaliTest[2348:2204903] client session: stateChange:1->0 Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 19:03:50.712 ThaliTest[2348:2204903] client session: fireConnectCallback: Apple-Iphone5s,-1_PT367.AiGtHw==
2015-12-02 19:03:50.713 ThaliTest[2348:2204903] jxcore: connect: fail: Peer disconnected
,2015-12-02T18:03:50.715Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-02T18:03:50.716Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-02T18:03:50.716Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-02 19:03:55.426 ThaliTest[2348:2204080] multipeer session: restart
,2015-12-02 19:03:55.434 ThaliTest[2348:2204080] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c42,97 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0xab5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2348 stopped
* thread #1: tid = 0x21a1b0, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x21a1b0, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x000ab5e2 ThaliTest`main + 50

```
