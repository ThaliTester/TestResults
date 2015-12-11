#### Test 534296758dfd01f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/EED41932-2674-45D8-B03A-B9BF86358DA9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/EED41932-2674-45D8-B03A-B9BF86358DA9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/534296758dfd01f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EBADB419-0BFE-4BD2-9570-7B517E1568AE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54368"
,(lldb)     command script import "/tmp/EED41932-2674-45D8-B03A-B9BF86358DA9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 20:04:23.747 ThaliTest[673:851832] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7AFC98BE-D615-4E47-873F-A1F5FC209475/Library/Cookies/Cookies.binarycookies
,2015-12-11 20:04:23.873 ThaliTest[673:851832] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 20:04:23.875 ThaliTest[673:851832] Multi-tasking -> Device: YES, App: YES
,2015-12-11 20:04:23.879 ThaliTest[673:851832] Unlimited access to network resources
,2015-12-11 20:04:23.890 ThaliTest[673:851832] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 20:04:34.316 ThaliTest[673:851832] Resetting plugins due to page load.
,2015-12-11 20:04:37.924 ThaliTest[673:851832] Finished load of: file:///var/mobile/Containers/Bundle/Application/EBADB419-0BFE-4BD2-9570-7B517E1568AE/ThaliTest.app/www/index.html
,2015-12-11 20:04:38.140 ThaliTest[673:851832] JXcore Cordova plugin initializing
,2015-12-11 20:04:38.143 ThaliTest[673:852107] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,my name is : Apple-Iphone5-1_PT4192
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
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 57489
,2015-12-11 20:12:42.473 ThaliTest[673:852107] jxcore: startBroadcasting
,2015-12-11 20:12:42.486 ThaliTest[673:852107] server: starting Apple-Iphone5-1_PT4192.mhrLvw==
,2015-12-11 20:12:42.488 ThaliTest[673:852107] multipeer session: start timer: 0x1d775950
,2015-12-11 20:12:42.509 ThaliTest[673:852107] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4192
,2015-12-11 20:12:42.510 ThaliTest[673:852107] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-11T19:12:42.514Z SendDataTCPServer.js: TCP/IP server is bound to port: 57489
,2015-12-11 20:12:43.073 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT818.I3iT5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:43.078Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:43.078Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11T19:12:43.079Z SendDataConnector.js: do connect now
,2015-12-11 20:12:43.079 ThaliTest[673:852107] jxcore: connect Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:43.080 ThaliTest[673:852107] client session: connect
,2015-12-11 20:12:43.081 ThaliTest[673:852107] client session: stateChange:0->1 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:44.036 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:44.452 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5466.2TZtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 20:12:46.672 ThaliTest[673:852996] client session: connected
2015-12-11 20:12:46.672 ThaliTest[673:852996] client session: stateChange:1->2 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:46.728 ThaliTest[673:852995] client session: fireConnectCallback: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:46.728 ThaliTest[673:852995] jxcore: connect: success
,2015-12-11T19:12:46.729Z SendDataConnector.js: CLIENT connected to 57492, error: null
,2015-12-11T19:12:46.730Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 20:12:46.732 ThaliTest[673:851832] client: relay established
2015-12-11 20:12:46.732 ThaliTest[673:851832] client: new accepted socket: 0x1d77d6a0
,2015-12-11T19:12:46.746Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:12:47.783Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T19:12:47.797Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T19:12:47.797Z SendDataConnector.js: got all data for this round
,2015-12-11T19:12:47.799Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T19:12:47.799Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:12:47.800 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:12:47.800 ThaliTest[673:852107] client session: disconnectFromPeer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:12:47.801 ThaliTest[673:852107] client session: disconnect
2,015-12-11 20:12:47.801 ThaliTest[673:852107] client session: stateChange:2->0 Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:12:47.812 ThaliTest[673:852107] jxcore: disconnect: success
2015-12-11T19:12:47.813Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT818.I3iT5Q==
---- round done--------
device[2]: Apple-Iphone6-1_PT3759.Czr,h3A==
2015-12-11T19:12:47.815Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11T19:12:47.815Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11T19:12:47.815Z SendDataConnector.js: do connect now
,2015-12-11 20:12:47.816 ThaliTest[673:852107] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:12:47.822 ThaliTest[673:852107] client session: connect
2015-12-11 20:12:47.822 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:12:49.102 ThaliTest[673:851832] multipeer session: reset timer
2015-12-11 20:12:49.102 ThaliTest[673:851832] multipeer session: stop timer
2015-12-11 20:12:49.102 ThaliTest[673:851832] multipeer session: start timer: 0x1d775950
2015-12-11 ,20:12:49.102 ThaliTest[673:851832] server session: connect
2015-12-11 20:12:49.103 ThaliTest[673:851832] server session: stateChange:0->1 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:49.109 ThaliTest[673:851832] server: accepting invitation Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:52.294 ThaliTest[673:852996] server session: connected
2015-12-11 20:12:52.294 ThaliTest[673:852996] server session: stateChange:1->2 Apple-Iphone5s-1_PT5466
,2015-12-11 20:12:52.436 ThaliTest[673:851832] server relay: connected (to port: 57489)
,2015-12-11T19:12:52.444Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T19:12:52.755Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-11T19:12:52.771Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-11T19:12:52.786Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-11T19:12:52.824Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-11T19:12:52.838Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-11T19:12:52.854Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 20:12:53.021 ThaliTest[673:852998] server session: not connected Apple-Iphone5s-1_PT5466
,2015-12-11 20:13:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:13:19.146 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:13:19.146 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:19.146 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:13:20.841 ThaliTest[673:853285] client session: not connected Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:20.842 ThaliTest[673:853285] client session: onLinkFailure: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:20.842 ThaliTest[673,:853285] client session: disconnect
2015-12-11 20:13:20.842 ThaliTest[673:853285] client session: stateChange:1->0 Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:20.843 ThaliTest[673:853285] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.C,zrh3A==
2015-12-11 20:13:20.843 ThaliTest[673:853285] jxcore: connect: fail: Peer disconnected
2015-12-11T19:13:20.845Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:13:20.845Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:13:20.846Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 20:13:22.344 ThaliTest[673:851832] client: lost peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:13:22.344 ThaliTest[673:851832] client session: onPeerLost: Apple-IpadAir2-1_PT818.I3iT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT818.I3iT5Q==","peerName":"(null)","peerAvailable":false}]
,2015-12-11T19:13:25.846Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:13:25.847Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:13:30.849 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:13:30.849 ThaliTest[673:852107] jxcore: disconnect: fail
2015-12-11T19:13:30.850Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==,
2015-12-11T19:13:30.851Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT3759.Czrh3A== with availability status: true
2015-12-11T19:13:30.851Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11T19:13:30.852Z SendDataConnector.js: do connect now
,2015-12-11 20:13:30.852 ThaliTest[673:852107] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:13:30.853 ThaliTest[673:852107] client session: connect
2015-12-11 20:13:30.853 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:13:44.206 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT818.I3iT5Q==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 20:13:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:14:03.840 ThaliTest[673:853296] client session: not connected Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:03.840 ThaliTest[673:853296] client session: onLinkFailure: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:03.840 ThaliTest[673,:853296] client session: disconnect
2015-12-11 20:14:03.840 ThaliTest[673:853296] client session: stateChange:1->0 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:03.865 ThaliTest[673:853296] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:03.865 ThaliTest[673:853296] jxcore: connect: fail: Peer disconnected
2015-12-11T19:14:03.867Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:14:03.867Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T19:14:03.867Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T19:14:08.875Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:14:08.876Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:13.880 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:14:13.881 ThaliTest[673:852107] jxcore: disconnect: fail
2015-12-11T19:14:13.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==,
2015-12-11T19:14:13.882Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3759.Czrh3A== with availability status: true
2015-12-11T19:14:13.882Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-,12-11T19:14:13.882Z SendDataConnector.js: do connect now
,2015-12-11 20:14:13.883 ThaliTest[673:852107] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:13.884 ThaliTest[673:852107] client session: connect
2015-12-11 20:14:13.884 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:13.891 ThaliTest[673:851832] client: lost peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:13.891 ThaliTest[673:851832] client session: onPeerLost: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:13.891 ThaliTest[673:851832] clien,t session: onLinkFailure: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:13.891 ThaliTest[673:851832] client session: disconnect
2015-12-11 20:14:13.892 ThaliTest[673:851832] client session: stateChange:1->0 Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:13.946 ThaliTest[673:851832] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:13.947 ThaliTest[673:851832] jxcore: connect: fail: Peer disconnected
2015-12-11T19:14:13.948Z SendDataConnector.js: CLIEN,T connected to 0, error: Peer disconnected
2015-12-11T19:14:13.948Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-11T19:14:13.948Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":false}]
,2015-12-11T19:14:18.949Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:14:18.949Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:14:19.132 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3759.Czrh3A==","peerName":"(null)","peerAvailable":true}]
2015-12-11 20:14:19.134 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:14:19.134 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:14:23.959 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:14:23.960 ThaliTest[673:852107] jxcore: disconnect: fail
2015-12-11T19:14:23.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==,
2015-12-11T19:14:23.961Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT3759.Czrh3A== with availability status: true
2015-12-11T19:14:23.961Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-,12-11T19:14:23.961Z SendDataConnector.js: do connect now
,2015-12-11 20:14:23.962 ThaliTest[673:852107] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:23.963 ThaliTest[673:852107] client session: connect
2015-12-11 20:14:23.963 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,2015-12-11 20:14:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:14:49.142 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:14:49.146 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:14:49.148 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:14:56.937 ThaliTest[673:853815] client session: not connected Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:56.937 ThaliTest[673:853815] client session: onLinkFailure: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:56.938 ThaliTest[673,:853815] client session: disconnect
2015-12-11 20:14:56.938 ThaliTest[673:853815] client session: stateChange:1->0 Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:14:56.939 ThaliTest[673:853815] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.C,zrh3A==
2015-12-11 20:14:56.939 ThaliTest[673:853815] jxcore: connect: fail: Peer disconnected
2015-12-11T19:14:56.940Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:14:56.941Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:14:56.941Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T19:15:01.947Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11T19:15:01.947Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:15:06.957 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:15:06.958 ThaliTest[673:852107] jxcore: disconnect: fail
2015-12-11T19:15:06.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==,
2015-12-11T19:15:06.959Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3759.Czrh3A== with availability status: true
2015-12-11T19:15:06.959Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11T19:15:06.960Z SendDataConnector.js: do connect now
,2015-12-11 20:15:06.960 ThaliTest[673:852107] jxcore: connect Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:15:06.961 ThaliTest[673:852107] client session: connect
2015-12-11 20:15:06.961 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Iphon,e6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:15:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:15:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:15:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:15:19.137 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:15:39.957 ThaliTest[673:853826] client session: not connected Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:15:39.958 ThaliTest[673:853826] client session: onLinkFailure: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:15:39.958 ThaliTest[673,:853826] client session: disconnect
2015-12-11 20:15:39.958 ThaliTest[673:853826] client session: stateChange:1->0 Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:15:39.959 ThaliTest[673:853826] client session: fireConnectCallback: Apple-Iphone6-1_PT3759.C,zrh3A==
2015-12-11 20:15:39.959 ThaliTest[673:853826] jxcore: connect: fail: Peer disconnected
2015-12-11T19:15:39.961Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-11T19:15:39.961Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-11T19:15:39.962Z SendDataConnector.js: CLIENT Stop now
2015-12-11 20:15:39.962 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:15:39.964 ThaliTest[673:852107] jxcore: disconnect: fail
2015-12-11T19:15:39.964Z S,e,ndDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3759.Czrh3A==
,---- round done--------
device[3]: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11T19:15:39.968Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11T19:15:39.968Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11T19:15:39.968Z SendDataConnector.js: do connect now
,2015-12-11 20:15:39.969 ThaliTest[673:852107] jxcore: connect Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:15:39.969 ThaliTest[673:852107] client session: connect
2015-12-11 20:15:39.969 ThaliTest[673:852107] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT5466.2TZtug==
,2015-12-11 20:15:43.068 ThaliTest[673:853826] client session: connected
2015-12-11 20:15:43.069 ThaliTest[673:853826] client session: stateChange:1->2 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:15:43.090 ThaliTest[673:853964] client session: fireConnectCallback: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:15:43.090 ThaliTest[673:853964] jxcore: connect: success
2015-12-11T19:15:43.091Z SendDataConnector.js: CLIENT connected to ,57519, error: null
2015-12-11T19:15:43.091Z SendDataConnector.js: CLIENT starting client 
2015-12-11 20:15:43.093 ThaliTest[673:851832] client: relay established
2015-12-11 20:15:43.093 ThaliTest[673:851832] client: new accepted socket: 0x1d63b210
,2015-12-11T19:15:43.106Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T19:15:43.708Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T19:15:43.723Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T19:15:43.738Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T19:15:43.753Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T19:15:43.767Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T19:15:43.768Z SendDataConnector.js: got all data for this round
,2015-12-11T19:15:43.769Z SendDataConnector.js: CLIENT Stop now
2015-12-11T19:15:43.769Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:15:43.770 ThaliTest[673:852107] jxcore: disconnect
2015-12-11 20:15:43.771 ThaliTest[673:852107] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:15:43.771 ThaliTest[673:852107] client session: disconnect
2015-12-11 20:15:43.771 ThaliTest[673:852107] client session: stateChange:2->0 Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:15:43.783 ThaliTest[673:852107] jxcore: disconnect: success
2015-12-11T19:15:43.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5466.2TZtug==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT4192","time":181326,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT818.I3iT5Q==","time":4720,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3759.Czrh3A==","time":172146,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple-Iphone5s-1_PT5466.2TZtug==","time":,3800,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 4720 ms, 99% : 4720 ms, 95 : 4720 ms, 90% : 4720 ms.
Result count 2, range 3800 ms to  4720 ms.
sendList failed peers count : 1 [33.33333333,3333336 %]
- Peer ID : Apple-Iphone6-1_PT3759.Czrh3A==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-11T19:15:43.794Z SendDataConnector.js: CLIENT Stop now
2015-12-11T19:15:43.794Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 20:15:49.103 ThaliTest[673:851832] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:16:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:16:19.133 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:16:19.134 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:16:21.485 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:16:49.104 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:16:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:16:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:16:49.142 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
Error type "connect_timeout" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:17:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:17:19.136 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:17:19.137 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:17:19.444 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_timeout called
,Error type "connect_timeout" when connecting to the test server
,2015-12-11 20:17:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:17:49.137 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:17:49.137 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:17:49.138 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 20:18:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:18:19.134 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:18:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:18:19.144 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:18:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:18:49.136 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:18:49.137 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:18:49.144 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:19:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:19:19.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:19:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:19:19.613 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:19:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:19:49.134 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:19:49.943 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:19:49.946 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 20:20:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:20:19.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:20:19.136 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:20:19.351 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:20:49.104 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:21:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:21:19.128 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:21:19.489 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:21:20.184 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,2015-12-11 20:21:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:21:49.499 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:21:49.500 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:21:49.501 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:22:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:22:19.135 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:22:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:22:19.137 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:22:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:22:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:22:49.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:22:49.153 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:23:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:23:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:23:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:23:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:23:49.103 ThaliTest[673:851832] multipeer session: restart
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
,2015-12-11 20:24:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:24:19.133 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:24:19.133 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:24:19.315 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-11 20:24:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:24:49.136 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:24:49.137 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:24:49.137 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:25:19.103 ThaliTest[673:851832] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,2015-12-11 20:25:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:25:49.134 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:25:49.134 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:25:49.463 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:26:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:26:19.132 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:26:19.137 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:26:19.139 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
,2015-12-11 20:26:49.103 ThaliTest[673:851832] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,2015-12-11 20:27:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:27:19.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:27:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:27:19.805 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:27:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:27:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:27:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:27:49.137 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:28:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:28:19.134 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:28:19.134 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:28:19.441 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:28:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:28:49.132 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:28:49.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
2015-12-11 20:28:49.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-11 20:29:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:29:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:29:19.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:29:19.196 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:29:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:29:49.132 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,2015-12-11 20:29:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:29:49.137 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
Error type "connect_error" when connecting to the test server
,2015-12-11 20:30:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:30:19.133 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
,2015-12-11 20:30:19.136 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:30:19.429 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:30:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:30:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:30:49.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:30:49.138 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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
,2015-12-11 20:31:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:31:19.135 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:31:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:31:19.708 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:31:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:31:49.134 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:31:49.134 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:31:49.136 ThaliTest[673:851832] client: fou,nd peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 20:32:19.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:32:19.133 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:32:19.135 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
,2015-12-11 20:32:19.435 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
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
,2015-12-11 20:32:49.103 ThaliTest[673:851832] multipeer session: restart
,2015-12-11 20:32:49.134 ThaliTest[673:851832] client: found peer: Apple-Iphone6-1_PT3759.Czrh3A==
2015-12-11 20:32:49.136 ThaliTest[673:851832] client: found peer: Apple-Iphone5s-1_PT5466.2TZtug==
2015-12-11 20:32:49.136 ThaliTest[673:851832] client: found peer: Apple-IpadAir2-1_PT818.I3iT5Q==
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

```
