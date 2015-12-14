#### Test 5357450766a890e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F8543E8D-926F-4978-909C-676C2B059C43/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/F8543E8D-926F-4978-909C-676C2B059C43/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/87F73BAA-C4B6-442A-9013-948172F04F07/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55351"
,(lldb)     command script import "/tmp/F8543E8D-926F-4978-909C-676C2B059C43/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 16:15:53.559 ThaliTest[774:1272735] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0C332117-8532-4AE5-9884-55A5F254E0F6/Library/Cookies/Cookies.binarycookies
,2015-12-14 16:15:53.675 ThaliTest[774:1272735] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 16:15:53.676 ThaliTest[774:1272735] Multi-tasking -> Device: YES, App: YES
,2015-12-14 16:15:53.681 ThaliTest[774:1272735] Unlimited access to network resources
,2015-12-14 16:15:53.693 ThaliTest[774:1272735] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 16:16:04.710 ThaliTest[774:1272735] Resetting plugins due to page load.
,2015-12-14 16:16:08.344 ThaliTest[774:1272735] Finished load of: file:///var/mobile/Containers/Bundle/Application/87F73BAA-C4B6-442A-9013-948172F04F07/ThaliTest.app/www/index.html
,2015-12-14 16:16:08.552 ThaliTest[774:1272735] JXcore Cordova plugin initializing
2015-12-14 16:16:08.554 ThaliTest[774:1272921] JXcore instance initializing
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
,my name is : Apple-Iphone5-1_PT949
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
serverPort is 58179
2015-12-14 16:24:08.162 ThaliTest[774:1272921] jxcore: startBroadcasting
,2015-12-14 16:24:08.175 ThaliTest[774:1272921] server: starting Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:08.176 ThaliTest[774:1272921] multipeer session: start timer: 0x1af99250
2015-12-14 16:24:08.176 ThaliTest[774:1272921] THEMultipeerSession in,itialized peer Apple-Iphone5-1_PT949
2015-12-14 16:24:08.176 ThaliTest[774:1272921] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-14T15:24:08.179Z SendDataTCPServer.js: TCP/IP server is bound to port: 58179
,2015-12-14 16:24:09.401 ThaliTest[774:1272735] client: found peer: Apple-IpadAir2-1_PT6360.8G12NA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6360.8G12NA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:09.405Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:09.406Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:09.406Z SendDataConnector.js: do connect now
2015-12-14 16:24:09.406 ThaliTest[774:1272921] jxcore: connect Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:09.406 ThaliTest[774:1272921] client session: connect
2015-12-14 16:24:09.407, ThaliTest[774:1272921] client session: stateChange:0->1 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:09.714 ThaliTest[774:1272735] client: found peer: Apple-Iphone6-1_PT9718.G9NStw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9718.G9NStw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 16:24:11.226 ThaliTest[774:1272735] multipeer session: reset timer
2015-12-14 16:24:11.226 ThaliTest[774:1272735] multipeer session: stop timer
2015-12-14 16:24:11.226 ThaliTest[774:1272735] multipeer session: start timer: 0x1af99250
2015-12-,14 16:24:11.227 ThaliTest[774:1272735] server session: connect
2015-12-14 16:24:11.227 ThaliTest[774:1272735] server session: stateChange:0->1 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:11.233 ThaliTest[774:1272735] server: accepting invitation Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:12.273 ThaliTest[774:1272735] client: found peer: Apple-Iphone5s-1_PT3702.8+Ivtg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3702.8+Ivtg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 16:24:12.461 ThaliTest[774:1273785] client session: connected
,2015-12-14 16:24:12.461 ThaliTest[774:1273785] client session: stateChange:1->2 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:12.491 ThaliTest[774:1273781] client session: fireConnectCallback: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:12.491 ThaliTest[774:1273781] jxcore: connect: success
2015-12-14T15:24:12.492Z SendDataConnector.js: CLIENT connected to 58182, error: null
2015-12-14T15:24:12.492Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:12.495 ThaliTest[774:1272735] client: relay established
2015-12-14 16:24:12.495 ThaliTest[774:1272735] client: new accepted socket: 0x1afa4780
,2015-12-14T15:24:12.509Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:13.185Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T15:24:13.313Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T15:24:13.328Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:13.328Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:13.331Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:13.331Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-14 16:24:13.333 ThaliTest[774:1272921] jxcore: disconnect
2015-12-14 16:24:13.333 ThaliTest[774:1272921] clien,t session: disconnectFromPeer: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:13.333 ThaliTest[774:1272921] client session: disconnect
2015-12-14 16:24:13.333 ThaliTest[774:1272921] client session: stateChange:2->0 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:13.345 ThaliTest[774:1272921] jxcore: disconnect: success
2015-12-14T15:24:13.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6360.8G12NA==
---- round done--------
device[2]: Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14T15:24:13.349Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:13.351Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14T15:24:13.351Z SendDataConnector.js: do connect now
2015-12-14 16:24:13.352 ThaliTest[774:1272921] jxcore: connect Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:13.352 ThaliTest[774:1272921] client session: connect
2015-12-14 16:24:13.352 ThaliTest[774:1272921] client session: stateCha,nge:0->1 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:13.388 ThaliTest[774:1272735] multipeer session: reset timer
2015-12-14 16:24:13.389 ThaliTest[774:1272735] multipeer session: stop timer
2015-12-14 16:24:13.389 ThaliTest[774:1272735] multipeer session: start timer: 0x1af99250
2015-12-,14 16:24:13.389 ThaliTest[774:1272735] server session: connect
2015-12-14 16:24:13.390 ThaliTest[774:1272735] server session: stateChange:0->1 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:13.398 ThaliTest[774:1272735] server: accepting invitation Apple-Iphone6-1_PT9718
,2015-12-14 16:24:13.459 ThaliTest[774:1272735] multipeer session: reset timer
,2015-12-14 16:24:13.460 ThaliTest[774:1272735] multipeer session: stop timer
,2015-12-14 16:24:13.460 ThaliTest[774:1272735] multipeer session: start timer: 0x1af99250
,2015-12-14 16:24:13.460 ThaliTest[774:1272735] server session: connect
2015-12-14 16:24:13.461 ThaliTest[774:1272735] server session: stateChange:0->1 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:13.469 ThaliTest[774:1272735] server: accepting invitation Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:13.836 ThaliTest[774:1273786] server session: connected
2015-12-14 16:24:13.836 ThaliTest[774:1273786] server session: stateChange:1->2 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:13.862 ThaliTest[774:1272735] server relay: connected (to port: 58179)
,2015-12-14T15:24:13.868Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:14.240Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T15:24:14.254Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-14T15:24:14.275Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
2015-12-14T15:24:14.287Z SendDataTCPServer.js: TCP/IP server has received 58562 bytes of data
,2015-12-14T15:24:14.302Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T15:24:14.318Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
2015-12-14T15:24:14.330Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
2015-12-14T15:24:14.343Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-14T15:24:14.357Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-14T15:24:14.371Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:14.436 ThaliTest[774:1273784] server session: not connected Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:16.443 ThaliTest[774:1273784] server session: connected
2015-12-14 16:24:16.443 ThaliTest[774:1273784] server session: stateChange:1->2 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:16.460 ThaliTest[774:1272735] server relay: connected (to port: 58179)
,2015-12-14T15:24:16.461Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 16:24:16.581 ThaliTest[774:1273784] server session: connected
,2015-12-14 16:24:16.581 ThaliTest[774:1273784] server session: stateChange:1->2 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:16.642 ThaliTest[774:1272735] server relay: connected (to port: 58179)
,2015-12-14T15:24:16.652Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:16.853Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-14T15:24:16.866Z SendDataTCPServer.js: TCP/IP server has received 28186 bytes of data
2015-12-14T15:24:16.880Z SendDataTCPServer.js: TCP/IP server has received 74034 bytes of data
,2015-12-14T15:24:16.894Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:16.904 ThaliTest[774:1273830] client session: connected
2015-12-14 16:24:16.904 ThaliTest[774:1273830] client session: stateChange:1->2 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14T15:24:16.924Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T15:24:16.942Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
2015-12-14 16:24:16.953 ThaliTest[774:1273781] client session: fireConnectCallback: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:16.953 ThaliTest[774:1273781] jxcore: connect: success
,2015-12-14T15:24:16.954Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
2015-12-14T15:24:16.956Z SendDataConnector.js: CLIENT connected to 58188, error: null
2015-12-14T15:24:16.957Z SendDataConnector.js: CLIENT starting client 
20,15-12-14 16:24:16.960 ThaliTest[774:1272735] client: relay established
2015-12-14 16:24:16.960 ThaliTest[774:1272735] client: new accepted socket: 0x1afc06e0
,2015-12-14T15:24:16.974Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 16:24:17.041 ThaliTest[774:1273830] server session: not connected Apple-IpadAir2-1_PT6360
,2015-12-14T15:24:17.565Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T15:24:17.648Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14 16:24:17.895 ThaliTest[774:1273830] server session: not connected Apple-Iphone6-1_PT9718
2015-12-14T15:24:17.900Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:17.900Z SendDataConnector.js: got all data for this round,
2015-12-14T15:24:17.901Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:17.901Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-14 16:24:17.902 ThaliTest[774:1272921] jxcore: disconnect
,2015-12-14 16:24:17.902 ThaliTest[774:1272921] client session: disconnectFromPeer: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:17.904 ThaliTest[774:1272921] client session: disconnect
2015-12-14 16:24:17.904 ThaliTest[774:1272921] client session: stateChange:2->0 Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:17.917 ThaliTest[774:1272921] jxcore: disconnect: success
2015-12-14T15:24:17.923Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9718.G9NStw==
---- round done--------
device[3]: Apple-Iphone5s-1_PT3702.8,+Ivtg==
2015-12-14T15:24:17.926Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14T15:24:17.927Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:17.927Z SendDataConnector.js: do connect now
2015-12-14 16:24:17.929 ThaliTest[774:1272921] jxcore: connect Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:17.929 ThaliTest[774:1272921] client session: connect
2015-12-14 16:24:17.929 ThaliTest[774:1272921] client session: stateChange:0->1 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:21.692 ThaliTest[774:1273784] client session: connected
2015-12-14 16:24:21.692 ThaliTest[774:1273784] client session: stateChange:1->2 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:21.756 ThaliTest[774:1273767] client session: fireConnectCallback: Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:21.756 ThaliTest[774:1273767] jxcore: connect: success
2015-12-14T15:24:21.757Z SendDataConnector.js: CLIENT connected to 58191, error: null
2015-12-14T15:24:21.757Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:21.761 ThaliTest[774:1272735] client: relay established
2015-12-14 16:24:21.761 ThaliTest[774:1272735] client: new accepted socket: 0x1aeb4f50
,2015-12-14T15:24:21.773Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:22.358Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T15:24:22.853Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T15:24:22.868Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T15:24:22.869Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:22.871Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:22.871Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:22.872 ThaliTest[774:1272921] jxcore: disconnect
2015-12-14 16:24:22.873 ThaliTest[774:1272921] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:22.873 ThaliTest[774:1272921] client session: disconnect
2015-12-14 16:24:22.873 ThaliTest[774:1272921] client session: stateChange:2->0 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:22.884 ThaliTest[774:1272921] jxcore: disconnect: success
2015-12-14T15:24:22.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT949","time":14733,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6360.8G12NA==","time":3924,"result":"OK","connections":1,"don,eRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT9718.G9NStw==","time":4549,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT3702.8+Ivtg==","time":4943,"resu,lt":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 4943 ms, 99% : 4943 ms, 95 : 4943 ms, 90% : 4943 ms.
Result count 3, range 3924 ms to  4943 ms.
sendList failed peers count : 0 [0 %]
sendList never ,tried peers count : 0 [0 %]
2015-12-14T15:24:22.900Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:22.901Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:24.765 ThaliTest[774:1272735] client: lost peer: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:24.765 ThaliTest[774:1272735] client session: onPeerLost: Apple-IpadAir2-1_PT6360.8G12NA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6360.8G12NA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 16:24:25.242 ThaliTest[774:1272735] client: lost peer: Apple-Iphone6-1_PT9718.G9NStw==
2015-12-14 16:24:25.242 ThaliTest[774:1272735] client session: onPeerLost: Apple-Iphone6-1_PT9718.G9NStw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT9718.G9NStw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-14 16:24:27.123 ThaliTest[774:1272921] jxcore: stopBroadcasting
2015-12-14 16:24:27.123 ThaliTest[774:1272921] THEMultipeerSession stopping peer
2015-12-14 16:24:27.124 ThaliTest[774:1272921] multipeer session: stop timer
2015-12-14 16:24:27.124 ThaliTest[774:1272921] server session: disconnect
2015-12-14 16:24:27.124 ThaliTest[774:1272921] server session: stateChange:2->0 Apple-Iphone6-1_PT9718
,2015-12-14 16:24:27.137 ThaliTest[774:1272921] server session: disconnect
2015-12-14 16:24:27.138 ThaliTest[774:1272921] server session: stateChange:2->0 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:27.150 ThaliTest[774:1272921] server session: disconnect
2015-12-14 16:24:27.150 ThaliTest[774:1272921] server session: stateChange:2->0 Apple-Iphone5s-1_PT3702
2015-12-14 16:24:27.156 ThaliTest[774:1272921] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T15:24:27.171Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-14T15:24:27.172Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:27.174Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:27.175Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT6360.8G12NA==\",\"time\":3924,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT9718.G9NStw==\",\"time\":4549,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5s-1_PT3702.8+Ivtg==\",\"time\":4943,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
CoordinatorConnector close called

```
