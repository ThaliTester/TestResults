#### Test 5357450766a890e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/09F45BDA-990F-416A-85E4-000571DB8301/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/09F45BDA-990F-416A-85E4-000571DB8301/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5357450766a890e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A69D469F-CA33-49DA-97FB-171DE4EAE965/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55389"
,(lldb)     command script import "/tmp/09F45BDA-990F-416A-85E4-000571DB8301/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 16:17:19.175 ThaliTest[909:1165847] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A9B26610-4D89-42CD-A893-A8615112FEA0/Library/Cookies/Cookies.binarycookies
,2015-12-14 16:17:19.546 ThaliTest[909:1165847] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 16:17:19.547 ThaliTest[909:1165847] Multi-tasking -> Device: YES, App: YES
,2015-12-14 16:17:19.557 ThaliTest[909:1165847] Unlimited access to network resources
,2015-12-14 16:17:19.569 ThaliTest[909:1165847] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 16:17:28.806 ThaliTest[909:1165847] Resetting plugins due to page load.
,2015-12-14 16:17:31.970 ThaliTest[909:1165847] Finished load of: file:///var/mobile/Containers/Bundle/Application/A69D469F-CA33-49DA-97FB-171DE4EAE965/ThaliTest.app/www/index.html
,2015-12-14 16:17:32.157 ThaliTest[909:1165847] JXcore Cordova plugin initializing
,2015-12-14 16:17:32.158 ThaliTest[909:1166043] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT9718
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 57562
,2015-12-14 16:24:07.927 ThaliTest[909:1166043] jxcore: startBroadcasting
,2015-12-14 16:24:07.943 ThaliTest[909:1166043] server: starting Apple-Iphone6-1_PT9718.G9NStw==
,2015-12-14 16:24:07.945 ThaliTest[909:1166043] multipeer session: start timer: 0x1659f4f0
,2015-12-14 16:24:07.947 ThaliTest[909:1166043] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9718
2015-12-14 16:24:07.948 ThaliTest[909:1166043] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-14T15:24:07.950Z SendDataTC,PServer.js: TCP/IP server is bound to port: 57562
,2015-12-14 16:24:08.976 ThaliTest[909:1165847] client: found peer: Apple-IpadAir2-1_PT6360.8G12NA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6360.8G12NA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:08.983Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14T15:24:08.984Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6360.8G12NA==,
2015-12-14T15:24:08.984Z SendDataConnector.js: do connect now
2015-12-14 16:24:08.985 ThaliTest[909:1166043] jxcore: connect Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:08.985 ThaliTest[909:1166043] client session: connect
2015-12-14 16:24:08.985, ThaliTest[909:1166043] client session: stateChange:0->1 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:09.241 ThaliTest[909:1165847] client: found peer: Apple-Iphone5-1_PT949.UkLT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT949.UkLT5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 16:24:09.641 ThaliTest[909:1165847] multipeer session: reset timer
2015-12-14 16:24:09.641 ThaliTest[909:1165847] multipeer session: stop timer
2015-12-14 16:24:09.642 ThaliTest[909:1165847] multipeer session: start timer: 0x1659f4f0
2015-12-14 16:24:09.642 ThaliTest[909:1165847] server session: connect
2015-12-14 16:24:09.642 ThaliTest[909:1165847] server session: stateChange:0->1 Apple-IpadAir2-1_PT6360
2015-12-14 16:24:09.655 ThaliTest[909:1165847] server: accepting invitation Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:12.318 ThaliTest[909:1166669] client session: connected
2015-12-14 16:24:12.319 ThaliTest[909:1166669] client session: stateChange:1->2 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:12.335 ThaliTest[909:1166678] client session: fireConnectCallback: Apple-IpadAir2-1_PT6360.8G12NA==
2015-12-14 16:24:12.335 ThaliTest[909:1166678] jxcore: connect: success
2015-12-14T15:24:12.337Z SendDataConnector.js: CLIENT connected t,o 57565, error: null
2015-12-14T15:24:12.337Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:12.342 ThaliTest[909:1165847] client: relay established
2015-12-14 16:24:12.342 ThaliTest[909:1165847] client: new accepted socket: 0x14d962e0
,2015-12-14T15:24:12.357Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 16:24:12.574 ThaliTest[909:1166668] server session: connected
,2015-12-14 16:24:12.575 ThaliTest[909:1166668] server session: stateChange:1->2 Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:12.588 ThaliTest[909:1165847] server relay: connected (to port: 57562)
,2015-12-14T15:24:12.662Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 16:24:12.839 ThaliTest[909:1165847] client: found peer: Apple-Iphone5s-1_PT3702.8+Ivtg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3702.8+Ivtg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T15:24:12.919Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2015-12-14T15:24:12.935Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-14T15:24:12.973Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T15:24:12.992Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T15:24:12.995Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:12.996Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:12.997Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:12.998Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:12.999 ThaliTest[909:1166043] jxcore: disconnect
,2015-12-14 16:24:13.000 ThaliTest[909:1166043] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:13.000 ThaliTest[909:1166043] client session: disconnect
,2015-12-14 16:24:13.001 ThaliTest[909:1166043] client session: stateChange:2->0 Apple-IpadAir2-1_PT6360.8G12NA==
,2015-12-14 16:24:13.073 ThaliTest[909:1166043] jxcore: disconnect: success
,2015-12-14T15:24:13.074Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6360.8G12NA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:13.076Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:13.077Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14T15:24:13.078Z SendDataConnector.js: do connect now
,2015-12-14 16:24:13.079 ThaliTest[909:1166043] jxcore: connect Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:13.080 ThaliTest[909:1166043] client session: connect
,2015-12-14 16:24:13.081 ThaliTest[909:1166043] client session: stateChange:0->1 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:13.105 ThaliTest[909:1166701] server session: not connected Apple-IpadAir2-1_PT6360
,2015-12-14 16:24:13.700 ThaliTest[909:1165847] multipeer session: reset timer
2015-12-14 16:24:13.701 ThaliTest[909:1165847] multipeer session: stop timer
2015-12-14 16:24:13.701 ThaliTest[909:1165847] multipeer session: start timer: 0x1659f4f0
2015-12-,14 16:24:13.701 ThaliTest[909:1165847] server session: connect
2015-12-14 16:24:13.701 ThaliTest[909:1165847] server session: stateChange:0->1 Apple-Iphone5-1_PT949
2015-12-14 16:24:13.709 ThaliTest[909:1165847] server: accepting invitation Apple-Iphone5-1_PT949
,2015-12-14 16:24:14.554 ThaliTest[909:1165847] multipeer session: reset timer
2015-12-14 16:24:14.556 ThaliTest[909:1165847] multipeer session: stop timer
2015-12-14 16:24:14.556 ThaliTest[909:1165847] multipeer session: start timer: 0x1659f4f0
2015-12-,14 16:24:14.556 ThaliTest[909:1165847] server session: connect
2015-12-14 16:24:14.557 ThaliTest[909:1165847] server session: stateChange:0->1 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:14.567 ThaliTest[909:1165847] server: accepting invitation Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:16.588 ThaliTest[909:1166678] client session: connected
2015-12-14 16:24:16.589 ThaliTest[909:1166678] client session: stateChange:1->2 Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:16.593 ThaliTest[909:1166678] client session: fireCon,nectCallback: Apple-Iphone5-1_PT949.UkLT5Q==
2015-12-14 16:24:16.594 ThaliTest[909:1166678] jxcore: connect: success
2015-12-14T15:24:16.595Z SendDataConnector.js: CLIENT connected to 57569, error: null
2015-12-14T15:24:16.595Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:16.599 ThaliTest[909:1165847] client: relay established
2015-12-14 16:24:16.600 ThaliTest[909:1165847] client: new accepted socket: 0x16743530
,2015-12-14T15:24:16.612Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14 16:24:16.910 ThaliTest[909:1166668] server session: connected
2015-12-14 16:24:16.910 ThaliTest[909:1166668] server session: stateChange:1->2 Apple-Iphone5-1_PT949
,2015-12-14T15:24:16.914Z SendDataTCPServer.js: TCP/IP server connected
2015-12-14 16:24:16.914 ThaliTest[909:1165847] server relay: connected (to port: 57562)
,2015-12-14T15:24:16.988Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T15:24:17.034Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14 16:24:17.297 ThaliTest[909:1166678] server session: connected
2015-12-14 16:24:17.297 ThaliTest[909:1166678] server session: stateChange:1->2 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:17.319 ThaliTest[909:1165847] server relay: connected (to port: 57562)
,2015-12-14T15:24:17.327Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T15:24:17.556Z SendDataTCPServer.js: TCP/IP server has received 6144 bytes of data
,2015-12-14T15:24:17.573Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T15:24:17.590Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
,2015-12-14T15:24:17.605Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T15:24:17.620Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-14T15:24:17.636Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
2015-12-14T15:24:17.637Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-14T15:24:17.643Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T15:24:17.656Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T15:24:17.660Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
2015-12-14T15:24:17.662Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T15:24:17.662Z SendDataConnector.js: got all data for this round
2015-12-14T15:24:17.664Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:17.664Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:17.665 ThaliTest[909:1166043] jxcore: disconnect
,2015-12-14 16:24:17.666 ThaliTest[909:1166043] client session: disconnectFromPeer: Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:17.667 ThaliTest[909:1166043] client session: disconnect
,2015-12-14 16:24:17.670 ThaliTest[909:1166043] client session: stateChange:2->0 Apple-Iphone5-1_PT949.UkLT5Q==
,2015-12-14 16:24:17.770 ThaliTest[909:1166043] jxcore: disconnect: success
,2015-12-14T15:24:17.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT949.UkLT5Q==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:17.775Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:17.776Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:17.777Z SendDataConnector.js: do connect now
,2015-12-14 16:24:17.778 ThaliTest[909:1166043] jxcore: connect Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:17.780 ThaliTest[909:1166043] client session: connect
,2015-12-14 16:24:17.782 ThaliTest[909:1166043] client session: stateChange:0->1 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14T15:24:17.831Z SendDataTCPServer.js: TCP/IP server has received 78474 bytes of data
,2015-12-14T15:24:17.847Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 16:24:18.092 ThaliTest[909:1166678] server session: not connected Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:18.153 ThaliTest[909:1166678] server session: not connected Apple-Iphone5-1_PT949
,2015-12-14 16:24:21.700 ThaliTest[909:1166678] client session: connected
2015-12-14 16:24:21.701 ThaliTest[909:1166678] client session: stateChange:1->2 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:21.826 ThaliTest[909:1166669] client session: fireConnectCallback: Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:21.827 ThaliTest[909:1166669] jxcore: connect: success
2015-12-14T15:24:21.828Z SendDataConnector.js: CLIENT connected t,o 57574, error: null
2015-12-14T15:24:21.828Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 16:24:21.831 ThaliTest[909:1165847] client: relay established
2015-12-14 16:24:21.832 ThaliTest[909:1165847] client: new accepted socket: 0x16396ed0
,2015-12-14T15:24:21.844Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T15:24:22.197Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T15:24:22.209Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T15:24:22.270Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T15:24:22.333Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T15:24:22.333Z SendDataConnector.js: got all data for this round
,2015-12-14T15:24:22.334Z SendDataConnector.js: CLIENT Stop now
2015-12-14T15:24:22.334Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 16:24:22.334 ThaliTest[909:1166043] jxcore: disconnect
2015-12-14 16:24:22.335 ThaliTest[909:1166043] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3702.8+Ivtg==
2015-12-14 16:24:22.335 ThaliTest[909:1166043] client session: disconnect
2015-12-14 16:24:22.335 ThaliTest[909:1166043] client session: stateChange:2->0 Apple-Iphone5s-1_PT3702.8+Ivtg==
,2015-12-14 16:24:22.340 ThaliTest[909:1166043] jxcore: disconnect: success
2015-12-14T15:24:22.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3702.8+Ivtg==
---- round done--------
weAreDoneNow , resultArray.length: ,3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone6-1_PT9718","time":14430,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6360.8G12NA==","time":4013,"result":"OK","connections":1,"do,neRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT949.UkLT5Q==","time":4586,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT3702.8+Ivtg==","time":4557,"resu,lt":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 4586 ms, 99% : 4586 ms, 95 : 4586 ms, 90% : 4586 ms.
Result count 3, range 4013 ms to  4586 ms.
sendList failed peers count : 0 [0 %]
sendList never ,tried peers count : 0 [0 %]
2015-12-14T15:24:22.343Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T15:24:22.344Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
2015-12-14 16:24:23.660 ThaliTest[909:1166043] jxcore: stopBroadcasting
2015-12-14 16:24:23.660 ThaliTest[909:1166043] THEMultipeerSession stopping peer
2015-12-14 16:24:23.660 ThaliTest[909:1166043], multipeer session: stop timer
2015-12-14 16:24:23.661 ThaliTest[909:1166043] server session: disconnect
2015-12-14 16:24:23.661 ThaliTest[909:1166043] server session: stateChange:2->0 Apple-IpadAir2-1_PT6360
2015-12-14 16:24:23.670 ThaliTest[909:116604,3] server session: disconnect
2015-12-14 16:24:23.670 ThaliTest[909:1166043] server session: stateChange:2->0 Apple-Iphone5s-1_PT3702
,2015-12-14 16:24:24.089 ThaliTest[909:1166043] server session: disconnect
2015-12-14 16:24:24.089 ThaliTest[909:1166043] server session: stateChange:2->0 Apple-Iphone5-1_PT949
2015-12-14 16:24:24.092 ThaliTest[909:1166043] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T15:24:24.109Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:24.111Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:24.112Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T15:24:24.113Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT6360.8G12NA==\",\"time\":4013,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT3702.8+Ivtg==\",\"time\":4557,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT949.UkLT5Q==\",\"time\":4586,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
