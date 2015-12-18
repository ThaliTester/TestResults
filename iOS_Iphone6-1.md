#### Test 539786637913587_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/38BF4478-AF4B-4014-967A-66CD438A58FB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/38BF4478-AF4B-4014-967A-66CD438A58FB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786637913587/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BB8D5855-24A3-4B60-A66C-DB5B80CABAD3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59917"
,(lldb)     command script import "/tmp/38BF4478-AF4B-4014-967A-66CD438A58FB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 13:45:17.986 ThaliTest[417:344533] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B20381B-3668-4E2A-8581-241F48BD19AB/Library/Cookies/Cookies.binarycookies
,2015-12-18 13:45:18.358 ThaliTest[417:344533] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 13:45:18.359 ThaliTest[417:344533] Multi-tasking -> Device: YES, App: YES
,2015-12-18 13:45:18.369 ThaliTest[417:344533] Unlimited access to network resources
,2015-12-18 13:45:18.380 ThaliTest[417:344533] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 13:45:27.398 ThaliTest[417:344533] Resetting plugins due to page load.
,2015-12-18 13:45:30.916 ThaliTest[417:344533] Finished load of: file:///var/mobile/Containers/Bundle/Application/BB8D5855-24A3-4B60-A66C-DB5B80CABAD3/ThaliTest.app/www/index.html
,2015-12-18 13:45:31.109 ThaliTest[417:344533] JXcore Cordova plugin initializing
,2015-12-18 13:45:31.111 ThaliTest[417:344779] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone6-1_PT215
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 52204
,2015-12-18 13:53:32.192 ThaliTest[417:344779] jxcore: startBroadcasting
,2015-12-18 13:53:32.213 ThaliTest[417:344779] server: starting Apple-Iphone6-1_PT215.JwJUFw==
,2015-12-18 13:53:32.214 ThaliTest[417:344779] multipeer session: start timer: 0x175cedc0
2015-12-18 13:53:32.215 ThaliTest[417:344779] THEMultipeerSession initialized peer Apple-Iphone6-1_PT215
,2015-12-18 13:53:32.218 ThaliTest[417:344779] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-18T12:53:32.220Z SendDataTCPServer.js: TCP/IP server is bound to port: 52204
,2015-12-18 13:53:32.234 ThaliTest[417:344533] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T12:53:32.239Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:53:32.240Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:53:32.240Z SendDataConnector.js: do connect now
,2015-12-18 13:53:32.241 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:53:32.243 ThaliTest[417:344779] client session: connect
,2015-12-18 13:53:32.244 ThaliTest[417:344779] client session: stateChange:0->1 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:53:33.314 ThaliTest[417:344533] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:33.968 ThaliTest[417:344533] multipeer session: reset timer
2015-12-18 13:53:33.968 ThaliTest[417:344533] multipeer session: stop timer
2015-12-18 13:53:33.969 ThaliTest[417:344533] multipeer session: start timer: 0x175cedc0
,2015-12-18 13:53:33.969 ThaliTest[417:344533] server session: connect
2015-12-18 13:53:33.971 ThaliTest[417:344533] server session: stateChange:0->1 Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:33.980 ThaliTest[417:344533] server: accepting invitation Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:34.387 ThaliTest[417:344533] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1412.+KloFA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:35.004 ThaliTest[417:344533] client: found peer: Apple-Iphone5-1_PT724.734x4g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT724.734x4g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:53:36.638 ThaliTest[417:345930] server session: connected
2015-12-18 13:53:36.639 ThaliTest[417:345930] server session: stateChange:1->2 Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:36.652 ThaliTest[417:344533] server relay: connected (to port: 52204)
,2015-12-18T12:53:36.663Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:36.976Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T12:53:36.990Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-18T12:53:37.007Z SendDataTCPServer.js: TCP/IP server has received 44712 bytes of data
,2015-12-18T12:53:37.020Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-18T12:53:37.035Z SendDataTCPServer.js: TCP/IP server has received 83078 bytes of data
,2015-12-18T12:53:37.049Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:37.100 ThaliTest[417:345938] server session: not connected Apple-Iphone5s-1_PT4751
,2015-12-18 13:53:38.116 ThaliTest[417:344533] multipeer session: reset timer
2015-12-18 13:53:38.117 ThaliTest[417:344533] multipeer session: stop timer
2015-12-18 13:53:38.117 ThaliTest[417:344533] multipeer session: start timer: 0x175cedc0
2015-12-18 ,13:53:38.117 ThaliTest[417:344533] server session: connect
2015-12-18 13:53:38.117 ThaliTest[417:344533] server session: stateChange:0->1 Apple-Iphone5-1_PT724
,2015-12-18 13:53:38.128 ThaliTest[417:344533] server: accepting invitation Apple-Iphone5-1_PT724
,2015-12-18 13:53:40.575 ThaliTest[417:344533] client: lost peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:40.577 ThaliTest[417:344533] client session: onPeerLost: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:40.577 ThaliTest[417:344533] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:40.577 ThaliTest[417:344533] client session: disconnect
2015-12-18 13:53:40.577 ThaliTest[417:344533] client session: stateChange:1->0 Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12,-18 13:53:40.578 ThaliTest[417:344533] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:40.578 ThaliTest[417:344533] jxcore: connect: fail: Peer disconnected
2015-12-18T12:53:40.586Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-18T12:53:40.587Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-18T12:53:40.587Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 13:53:41.230 ThaliTest[417:345939] server session: connected
2015-12-18 13:53:41.231 ThaliTest[417:345939] server session: stateChange:1->2 Apple-Iphone5-1_PT724
,2015-12-18 13:53:41.239 ThaliTest[417:344533] server relay: connected (to port: 52204)
,2015-12-18T12:53:41.248Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:41.963Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T12:53:41.977Z SendDataTCPServer.js: TCP/IP server has received 21758 bytes of data
,2015-12-18T12:53:41.990Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T12:53:42.006Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-18T12:53:42.019Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-18T12:53:42.234Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:42.360 ThaliTest[417:344533] multipeer session: reset timer
,2015-12-18 13:53:42.361 ThaliTest[417:344533] multipeer session: stop timer
2015-12-18 13:53:42.361 ThaliTest[417:344533] multipeer session: start timer: 0x175cedc0
2015-12-18 13:53:42.362 ThaliTest[417:344533] server session: connect
,2015-12-18 13:53:42.362 ThaliTest[417:344533] server session: stateChange:0->1 Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:42.371 ThaliTest[417:345938] server session: not connected Apple-Iphone5-1_PT724
,2015-12-18 13:53:42.390 ThaliTest[417:344533] server: accepting invitation Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:44.486 ThaliTest[417:345939] server session: connected
2015-12-18 13:53:44.486 ThaliTest[417:345939] server session: stateChange:1->2 Apple-IpadAir2-1_PT1412
,2015-12-18T12:53:45.597Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T12:53:45.598Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:53:46.298 ThaliTest[417:344533] server relay: connected (to port: 52204)
,2015-12-18T12:53:46.305Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T12:53:46.413Z SendDataTCPServer.js: TCP/IP server has received 17236 bytes of data
,2015-12-18T12:53:46.430Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-18T12:53:46.445Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T12:53:46.460Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-18T12:53:46.473Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-18T12:53:46.488Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-18T12:53:46.502Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-18T12:53:46.515Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 13:53:46.591 ThaliTest[417:345939] server session: not connected Apple-IpadAir2-1_PT1412
,2015-12-18 13:53:50.601 ThaliTest[417:344779] jxcore: disconnect
,2015-12-18 13:53:50.602 ThaliTest[417:344779] jxcore: disconnect: fail
2015-12-18T12:53:50.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T12:53:50.604Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
,2015-12-18T12:53:50.604Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T12:53:50.605Z SendDataConnector.js: do connect now
,2015-12-18 13:53:50.606 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:50.606 ThaliTest[417:344779] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:53:50.607 ThaliTest[417:344779] jxcor,e: connect: fail: Peer unreachable
2015-12-18T12:53:50.607Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T12:53:50.608Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T12:53:50.608Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-18T12:53:55.612Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T12:53:55.612Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:53:55.887 ThaliTest[417:344533] client: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.14R9MQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:54:00.614 ThaliTest[417:344779] jxcore: disconnect
2015-12-18 13:54:00.615 ThaliTest[417:344779] jxcore: disconnect: fail
2015-12-18T12:54:00.615Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T12:54:00.616Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T12:54:00.616Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:54:00.616Z SendDataConnector.js: do connect now
,2015-12-18 13:54:00.617 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:54:00.619 ThaliTest[417:344779] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:54:00.619 ThaliTest[417:344779] jxcor,e: connect: fail: Peer unreachable
2015-12-18T12:54:00.619Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T12:54:00.620Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T12:54:00.620Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-18T12:54:05.625Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:54:05.626Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:54:10.634 ThaliTest[417:344779] jxcore: disconnect
2015-12-18 13:54:10.635 ThaliTest[417:344779] jxcore: disconnect: fail
2015-12-18T12:54:10.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T12:54:10.636Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T12:54:10.636Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:54:10.636Z SendDataConnector.js: do connect now
2015-12-18 13:54:10.637 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:54:10.638 ThaliTest[417:344779] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 13:54:10.638 ThaliTest[417:344779] jxcore: connect: fail: Peer unreachable
2015-12-18T12:54:10.639Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-18T12:54:10.639Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T12:54:10.639Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18 13:54:11.614 ThaliTest[417:344533] client: lost peer: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:54:11.614 ThaliTest[417:344533] client session: onPeerLost: Apple-Iphone5s-1_PT4751.qR8AbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 13:54:11.677 ThaliTest[417:344533] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4751.qR8AbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 13:54:12.363 ThaliTest[417:344533] multipeer session: restart
,2015-12-18 13:54:12.411 ThaliTest[417:344533] client: found peer: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:54:12.411 ThaliTest[417:344533] client: found peer: Apple-Iphone5-1_PT724.734x4g==
2015-12-18 13:54:12.412 ThaliTest[417:344533] client: found peer: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:54:15.646Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:54:15.646Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:54:20.651 ThaliTest[417:344779] jxcore: disconnect
2015-12-18 13:54:20.651 ThaliTest[417:344779] jxcore: disconnect: fail
2015-12-18T12:54:20.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==,
2015-12-18T12:54:20.652Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6115.GXbC4w== with availability status: true
2015-12-18T12:54:20.652Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T12:54:20.653Z SendDataConnector.js: do connect now
2015-12-18 13:54:20.654 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:54:20.655 ThaliTest[417:344779] client: connect: unreachable Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 13:54:20.655 ThaliTest[417:344779] jxcore: connect: fail: Peer unreachable
,2015-12-18T12:54:20.656Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T12:54:20.656Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T12:54:20.659Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 13:54:20.660 ThaliTest[417:344779] jxcore: disconnect
,2015-12-18 13:54:20.661 ThaliTest[417:344779] jxcore: disconnect: fail
,2015-12-18T12:54:20.663Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,---- round done--------
,device[2]: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:54:20.666Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:54:20.667Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18T12:54:20.667Z SendDataConnector.js: do connect now
,2015-12-18 13:54:20.668 ThaliTest[417:344779] jxcore: connect Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:54:20.669 ThaliTest[417:344779] client session: connect
2015-12-18 13:54:20.669 ThaliTest[417:344779] client session: stateChange:0->1 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:54:34.243 ThaliTest[417:346084] client session: connected
2015-12-18 13:54:34.243 ThaliTest[417:346084] client session: stateChange:1->2 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:54:34.250 ThaliTest[417:346010] client session: fireConnectCallback: Apple-Iphone5s-1_PT4751.qR8AbA==
2015-12-18 13:54:34.250 ThaliTest[417:346010] jxcore: connect: success
,2015-12-18T12:54:34.252Z SendDataConnector.js: CLIENT connected to 52211, error: null
2015-12-18T12:54:34.253Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:54:34.257 ThaliTest[417:344533] client: relay established
2015-12-18 13:54:34.257 ThaliTest[417:344533] client: new accepted socket: 0x175eaeb0
,2015-12-18T12:54:34.273Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:54:34.687Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T12:54:34.701Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T12:54:34.762Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T12:54:34.763Z SendDataConnector.js: got all data for this round
,2015-12-18T12:54:34.764Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:54:34.764Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:54:34.765 ThaliTest[417:344779] jxcore: disconnect
,2015-12-18 13:54:34.766 ThaliTest[417:344779] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:54:34.766 ThaliTest[417:344779] client session: disconnect
,2015-12-18 13:54:34.766 ThaliTest[417:344779] client session: stateChange:2->0 Apple-Iphone5s-1_PT4751.qR8AbA==
,2015-12-18 13:54:34.841 ThaliTest[417:344779] jxcore: disconnect: success
,2015-12-18T12:54:34.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4751.qR8AbA==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:54:34.844Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:54:34.844Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18T12:54:34.845Z SendDataConnector.js: do connect now
,2015-12-18 13:54:34.845 ThaliTest[417:344779] jxcore: connect Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:34.846 ThaliTest[417:344779] client session: connect
,2015-12-18 13:54:34.846 ThaliTest[417:344779] client session: stateChange:0->1 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:38.548 ThaliTest[417:345930] client session: connected
2015-12-18 13:54:38.549 ThaliTest[417:345930] client session: stateChange:1->2 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:38.591 ThaliTest[417:346084] client session: fireConnectCallback: Apple-IpadAir2-1_PT1412.+KloFA==
2015-12-18 13:54:38.591 ThaliTest[417:346084] jxcore: connect: success
2015-12-18T12:54:38.593Z SendDataConnector.js: CLIENT connected to 52215, error: null
2015-12-18T12:54:38.593Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 13:54:38.597 ThaliTest[417:344533] client: relay established
2015-12-18 13:54:38.598 ThaliTest[417:344533] client: new accepted socket: 0x17764b50
,2015-12-18T12:54:38.611Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T12:54:38.915Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T12:54:38.953Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T12:54:39.002Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T12:54:39.003Z SendDataConnector.js: got all data for this round
,2015-12-18T12:54:39.003Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:54:39.004Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 13:54:39.004 ThaliTest[417:344779] jxcore: disconnect
,2015-12-18 13:54:39.005 ThaliTest[417:344779] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:39.006 ThaliTest[417:344779] client session: disconnect
,2015-12-18 13:54:39.007 ThaliTest[417:344779] client session: stateChange:2->0 Apple-IpadAir2-1_PT1412.+KloFA==
,2015-12-18 13:54:39.076 ThaliTest[417:344779] jxcore: disconnect: success
,2015-12-18T12:54:39.077Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1412.+KloFA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT215","time":66902,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT6115.GXbC4w==","time":48418,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT4751.qR8AbA==","time":14096,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT1412.+KloFA==","time":4159,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 14096 ms, 99% : 14096 ms, 95 : 14096 ms, 90% : 14096 ms.
,Result count 2, range 4159 ms to  14096 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-IpadAir2-1_PT6115.GXbC4w==, Tried : 5
,sendList never tried peers count : 0 [0 %]
,2015-12-18T12:54:39.084Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T12:54:39.084Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
stop tests now !
stop current!
testSendData stopped
,2015-12-18 13:54:40.401 ThaliTest[417:344779] jxcore: stopBroadcasting
,2015-12-18 13:54:40.402 ThaliTest[417:344779] THEMultipeerSession stopping peer
,2015-12-18 13:54:40.402 ThaliTest[417:344779] multipeer session: stop timer
2015-12-18 13:54:40.404 ThaliTest[417:344779] server session: disconnect
2015-12-18 13:54:40.405 ThaliTest[417:344779] server session: stateChange:2->0 Apple-IpadAir2-1_PT1412
,2015-12-18 13:54:40.484 ThaliTest[417:344779] server session: disconnect
2015-12-18 13:54:40.484 ThaliTest[417:344779] server session: stateChange:2->0 Apple-Iphone5-1_PT724
,2015-12-18 13:54:40.489 ThaliTest[417:344779] server session: disconnect
2015-12-18 13:54:40.489 ThaliTest[417:344779] server session: stateChange:2->0 Apple-Iphone5s-1_PT4751
,2015-12-18 13:54:40.554 ThaliTest[417:344779] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-18T12:54:40.574Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.577Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.580Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T12:54:40.581Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-IpadAir2-1_PT1412.+KloFA==\",\"time\":4159,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT4751.qR8AbA==\",\"time\":14096,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-IpadAir2-1_PT6115.GXbC4w==\",\"time\":48418,,\"result\":\"Peer unreachable\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":0}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
