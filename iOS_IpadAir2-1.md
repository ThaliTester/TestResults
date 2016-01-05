#### Test 550731521dbc378_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/41B279BB-7542-4CF0-8C09-9F6BB506D4E4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/41B279BB-7542-4CF0-8C09-9F6BB506D4E4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D10954DC-286A-430C-922E-DD11B43436E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64907"
,(lldb)     command script import "/tmp/41B279BB-7542-4CF0-8C09-9F6BB506D4E4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 11:17:22.926 ThaliTest[1306:2855090] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/12943BA3-07F6-4C5D-85F3-668AB053DD48/Library/Cookies/Cookies.binarycookies
,2016-01-05 11:17:23.247 ThaliTest[1306:2855090] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 11:17:23.248 ThaliTest[1306:2855090] Multi-tasking -> Device: YES, App: YES
,2016-01-05 11:17:23.255 ThaliTest[1306:2855090] Unlimited access to network resources
,2016-01-05 11:17:23.261 ThaliTest[1306:2855090] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 11:17:32.149 ThaliTest[1306:2855090] Resetting plugins due to page load.
,2016-01-05 11:17:35.931 ThaliTest[1306:2855090] Finished load of: file:///var/mobile/Containers/Bundle/Application/D10954DC-286A-430C-922E-DD11B43436E1/ThaliTest.app/www/index.html
,2016-01-05 11:17:36.089 ThaliTest[1306:2855090] JXcore Cordova plugin initializing
,2016-01-05 11:17:36.089 ThaliTest[1306:2855321] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-05 11:17:37.081 ThaliTest[1306:2855090] THREAD WARNING: ['JXcore'] took '70.484131' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 11:23:12.757 ThaliTest[1306:2855321] jxcore: startBroadcasting
,2016-01-05 11:23:12.773 ThaliTest[1306:2855321] server: starting Apple-IpadAir2-1.o3kBVg==
,2016-01-05 11:23:12.775 ThaliTest[1306:2855321] multipeer session: start timer: 0x1647d200
2016-01-05 11:23:12.775 ThaliTest[1306:2855321] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-05 11:23:12.777 ThaliTest[1306:2855321] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 11:23:13.848 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5-1.+hwmKw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1.+hwmKw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-05 11:23:14.456 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
,teardown
,testFindPeers stopped
,2016-01-05 11:23:15.233 ThaliTest[1306:2855321] jxcore: stopBroadcasting
2016-01-05 11:23:15.233 ThaliTest[1306:2855321] THEMultipeerSession stopping peer
,2016-01-05 11:23:15.234 ThaliTest[1306:2855321] multipeer session: stop timer
,2016-01-05 11:23:15.235 ThaliTest[1306:2855321] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63317
,2016-01-05 11:23:15.298 ThaliTest[1306:2855321] jxcore: startBroadcasting
,2016-01-05 11:23:15.301 ThaliTest[1306:2855321] server: starting Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:15.302 ThaliTest[1306:2855321] multipeer session: start timer: 0x162587f0
2016-01-05 11:23:15.303 ThaliTest[1306:2855321] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-05 11:23:15.303 ThaliTest[1306:2855321] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-05T10:23:15.307Z SendDataTCPServer.js: TCP/IP server is bound to port: 63317
,2016-01-05 11:23:15.316 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:15.316 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:15.317 ThaliTest[1306:2855090] client: found peer: Apple-IpadAir2-1.o3kBVg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:15.320Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:15.321Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:15.321Z SendDataConnector.js: do connect now
,2016-01-05 11:23:15.322 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:15.322 ThaliTest[1306:2855321] client session: connect
,2016-01-05 11:23:15.323 ThaliTest[1306:2855321] client session: stateChange:0->1 Apple-Iphone5-1.+hwmKw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:16.453 ThaliTest[1306:2855090] client: lost peer: Apple-IpadAir2-1.o3kBVg==
,2016-01-05 11:23:16.453 ThaliTest[1306:2855090] client session: onPeerLost: Apple-IpadAir2-1.o3kBVg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-05 11:23:16.567 ThaliTest[1306:2855090] client: lost peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:16.567 ThaliTest[1306:2855090] client session: onPeerLost: Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:16.567 ThaliTest[1306:2855090] client session: onLinkFailure: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:16.568 ThaliTest[1306:2855090] client session: disconnect
,2016-01-05 11:23:16.568 ThaliTest[1306:2855090] client session: stateChange:1->0 Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:16.570 ThaliTest[1306:2855090] client session: fireConnectCallback: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:16.570 ThaliTest[1306:2855090] jxcore: connect: fail: Peer disconnected
2016-01-05 11:23:16.570 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:16.572Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-05T10:23:16.573Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-05T10:23:16.574Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.GgrI3w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:17.004 ThaliTest[1306:2855090] client: found peer: Apple-Iphone6-1.DQd5Sw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DQd5Sw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 11:23:18.016 ThaliTest[1306:2855090] client: lost peer: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:18.017 ThaliTest[1306:2855090] client session: onPeerLost: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:18.017 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.R3Z2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05T10:23:21.583Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:21.584Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:26.590 ThaliTest[1306:2855321] jxcore: disconnect
2016-01-05 11:23:26.590 ThaliTest[1306:2855321] jxcore: disconnect: fail
,2016-01-05T10:23:26.592Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:26.592Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
,2016-01-05T10:23:26.593Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:26.593Z SendDataConnector.js: do connect now
,2016-01-05 11:23:26.595 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:26.595 ThaliTest[1306:2855321] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:26.596 ThaliTest[1306:2855321] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:26.596Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T10:23:26.597Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T10:23:26.598Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:31.599Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:31.600Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:36.609 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:23:36.610 ThaliTest[1306:2855321] jxcore: disconnect: fail
,2016-01-05T10:23:36.611Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:36.611Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
,2016-01-05T10:23:36.612Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:36.612Z SendDataConnector.js: do connect now
,2016-01-05 11:23:36.613 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:36.614 ThaliTest[1306:2855321] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:36.615 ThaliTest[1306:2855321] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:36.616Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T10:23:36.616Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T10:23:36.617Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:41.625Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:41.626Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:45.304 ThaliTest[1306:2855090] multipeer session: restart
,2016-01-05 11:23:45.331 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:45.331 ThaliTest[1306:2855090] client: found peer: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:23:45.332 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:23:46.630 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:23:46.631 ThaliTest[1306:2855321] jxcore: disconnect: fail
,2016-01-05T10:23:46.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:46.633Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
,2016-01-05T10:23:46.633Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:46.634Z SendDataConnector.js: do connect now
,2016-01-05 11:23:46.635 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:46.635 ThaliTest[1306:2855321] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:46.636 ThaliTest[1306:2855321] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:46.636Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T10:23:46.637Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T10:23:46.638Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:51.646Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:51.647Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:56.658 ThaliTest[1306:2855321] jxcore: disconnect
2016-01-05 11:23:56.658 ThaliTest[1306:2855321] jxcore: disconnect: fail
,2016-01-05T10:23:56.659Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:56.660Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
,2016-01-05T10:23:56.660Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:56.661Z SendDataConnector.js: do connect now
,2016-01-05 11:23:56.662 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:56.663 ThaliTest[1306:2855321] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:56.663 ThaliTest[1306:2855321] jxcore: connect: fail: Peer unreachable
2016-01-05T10:23:56.664Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T10:23:56.665Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-05T10:23:56.667Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 11:23:56.668 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:23:56.669 ThaliTest[1306:2855321] jxcore: disconnect: fail
,2016-01-05T10:23:56.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:56.673Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:56.674Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:56.675Z SendDataConnector.js: do connect now
,2016-01-05 11:23:56.676 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:56.677 ThaliTest[1306:2855321] client session: connect
,2016-01-05 11:23:56.677 ThaliTest[1306:2855321] client session: stateChange:0->1 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:23:57.233 ThaliTest[1306:2855090] multipeer session: reset timer
2016-01-05 11:23:57.233 ThaliTest[1306:2855090] multipeer session: stop timer
2016-01-05 11:23:57.234 ThaliTest[1306:2855090] multipeer session: start timer: 0x162587f0
2016-,01-05 11:23:57.234 ThaliTest[1306:2855090] server session: connect
2016-01-05 11:23:57.235 ThaliTest[1306:2855090] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 11:23:57.241 ThaliTest[1306:2855090] server: accepting invitation Apple-Iphone5-1
,2016-01-05 11:23:59.915 ThaliTest[1306:2855090] multipeer session: reset timer
2016-01-05 11:23:59.916 ThaliTest[1306:2855090] multipeer session: stop timer
,2016-01-05 11:23:59.916 ThaliTest[1306:2855090] multipeer session: start timer: 0x162587f0
,2016-01-05 11:23:59.916 ThaliTest[1306:2855090] server session: connect
2016-01-05 11:23:59.917 ThaliTest[1306:2855090] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 11:23:59.923 ThaliTest[1306:2855090] server: accepting invitation Apple-Iphone6-1
,2016-01-05 11:24:00.644 ThaliTest[1306:2856075] client session: connected
2016-01-05 11:24:00.644 ThaliTest[1306:2856075] client session: stateChange:1->2 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:00.703 ThaliTest[1306:2856079] server session: connected
2016-01-05 11:24:00.703 ThaliTest[1306:2856079] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05 11:24:00.705 ThaliTest[1306:2855090] server relay: connected (to port: 63317)
,2016-01-05T10:24:00.711Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 11:24:01.053 ThaliTest[1306:2856075] client session: fireConnectCallback: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:01.053 ThaliTest[1306:2856075] jxcore: connect: success
,2016-01-05T10:24:01.054Z SendDataConnector.js: CLIENT connected to 63323, error: null
,2016-01-05T10:24:01.055Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:01.057 ThaliTest[1306:2855090] client: relay established
2016-01-05 11:24:01.058 ThaliTest[1306:2855090] client: new accepted socket: 0x164a0dc0
,2016-01-05T10:24:01.073Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:01.336Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-05T10:24:01.351Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05T10:24:01.414Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T10:24:01.427Z SendDataConnector.js: CLIENT is data received : 50000
2016-01-05 11:24:01.427 ThaliTest[1306:2856060] server session: not connected Apple-Iphone5-1
,2016-01-05T10:24:01.478Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:24:01.478Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T10:24:01.478Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:01.478Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:01.479 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:24:01.479 ThaliTest[1306:2855321] client session: disconnectFromPeer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:01.480 ThaliTest[1306:2855321] client session: disconnect
2016-01-05 11:24:01.480 ThaliTest[1306:2855321] client session: stateChange:2->0 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:01.537 ThaliTest[1306:2855321] jxcore: disconnect: success
2016-01-05T10:24:01.537Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.GgrI3w==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone6-1.DQd5Sw==
,2016-01-05T10:24:01.538Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DQd5Sw==
,2016-01-05T10:24:01.538Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DQd5Sw==
,2016-01-05T10:24:01.539Z SendDataConnector.js: do connect now
,2016-01-05 11:24:01.539 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:01.539 ThaliTest[1306:2855321] client session: connect
2016-01-05 11:24:01.539 ThaliTest[1306:2855321] client session: stateChange:0->1 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:03.193 ThaliTest[1306:2856079] server session: connected
2016-01-05 11:24:03.193 ThaliTest[1306:2856079] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 11:24:03.213 ThaliTest[1306:2855090] server relay: connected (to port: 63317)
,2016-01-05T10:24:03.218Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:03.484Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-05T10:24:03.499Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-05T10:24:03.525Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-05T10:24:03.542Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-05T10:24:03.559Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:03.613 ThaliTest[1306:2856075] server session: not connected Apple-Iphone6-1
,2016-01-05 11:24:04.766 ThaliTest[1306:2856079] client session: connected
2016-01-05 11:24:04.766 ThaliTest[1306:2856079] client session: stateChange:1->2 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:04.787 ThaliTest[1306:2856075] client session: fireConnectCallback: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:04.787 ThaliTest[1306:2856075] jxcore: connect: success
,2016-01-05T10:24:04.789Z SendDataConnector.js: CLIENT connected to 63327, error: null
,2016-01-05T10:24:04.790Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:04.793 ThaliTest[1306:2855090] client: relay established
2016-01-05 11:24:04.793 ThaliTest[1306:2855090] client: new accepted socket: 0x1663b110
,2016-01-05T10:24:04.807Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:05.093Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T10:24:05.142Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:05.142Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T10:24:05.143Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:05.143Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:05.143 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:24:05.144 ThaliTest[1306:2855321] client session: disconnectFromPeer: Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:05.144 ThaliTest[1306:2855321] client session: disconnect
,2016-01-05 11:24:05.144 ThaliTest[1306:2855321] client session: stateChange:2->0 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:05.207 ThaliTest[1306:2855321] jxcore: disconnect: success
,2016-01-05T10:24:05.208Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DQd5Sw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1.R3Z2qA==
2016-01-05T10:24:05.209Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:05.209Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.R3Z2qA==
2016-01-05T10:24:05.209Z SendDataConnector.js: do connect now
,2016-01-05 11:24:05.209 ThaliTest[1306:2855321] jxcore: connect Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:05.210 ThaliTest[1306:2855321] client session: connect
,2016-01-05 11:24:05.210 ThaliTest[1306:2855321] client session: stateChange:0->1 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:08.658 ThaliTest[1306:2856129] client session: connected
2016-01-05 11:24:08.658 ThaliTest[1306:2856129] client session: stateChange:1->2 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:08.692 ThaliTest[1306:2856129] client session: fireConnectCallback: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:08.693 ThaliTest[1306:2856129] jxcore: connect: success
,2016-01-05T10:24:08.694Z SendDataConnector.js: CLIENT connected to 63330, error: null
,2016-01-05T10:24:08.695Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:08.697 ThaliTest[1306:2855090] client: relay established
2016-01-05 11:24:08.698 ThaliTest[1306:2855090] client: new accepted socket: 0x1649e790
,2016-01-05T10:24:08.712Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:08.983Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T10:24:09.021Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T10:24:09.082Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:09.082Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T10:24:09.082Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:09.082Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:09.083 ThaliTest[1306:2855321] jxcore: disconnect
,2016-01-05 11:24:09.083 ThaliTest[1306:2855321] client session: disconnectFromPeer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:09.083 ThaliTest[1306:2855321] client session: disconnect
2016-01-05 11:24:09.083 ThaliTest[1306:2855321] client session: stateChange:2->0 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:09.086 ThaliTest[1306:2855321] jxcore: disconnect: success
2016-01-05T10:24:09.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.R3Z2qA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2016-01-05T10:24:09.089Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:09.089Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:29.918 ThaliTest[1306:2855090] multipeer session: restart
,2016-01-05 11:24:29.945 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:29.945 ThaliTest[1306:2855090] client: found peer: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:29.946 ThaliTest[1306:2855090] client: found peer: Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:37.809 ThaliTest[1306:2855090] multipeer session: reset timer
2016-01-05 11:24:37.809 ThaliTest[1306:2855090] multipeer session: stop timer
,2016-01-05 11:24:37.810 ThaliTest[1306:2855090] multipeer session: start timer: 0x162587f0
,2016-01-05 11:24:37.811 ThaliTest[1306:2855090] server session: connect
,2016-01-05 11:24:37.811 ThaliTest[1306:2855090] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 11:24:37.817 ThaliTest[1306:2855090] server: accepting invitation Apple-Iphone5s-1
,2016-01-05 11:24:41.129 ThaliTest[1306:2856168] server session: connected
2016-01-05 11:24:41.130 ThaliTest[1306:2856168] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05 11:24:41.157 ThaliTest[1306:2855090] server relay: connected (to port: 63317)
,2016-01-05T10:24:41.160Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:41.503Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-05T10:24:41.519Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-05T10:24:41.536Z SendDataTCPServer.js: TCP/IP server has received 63226 bytes of data
,2016-01-05T10:24:41.552Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-05T10:24:41.592Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:41.648 ThaliTest[1306:2856170] server session: not connected Apple-Iphone5s-1
,teardown
,testSendData stopped
,2016-01-05 11:24:52.628 ThaliTest[1306:2855321] jxcore: stopBroadcasting
,2016-01-05 11:24:52.629 ThaliTest[1306:2855321] THEMultipeerSession stopping peer
,2016-01-05 11:24:52.629 ThaliTest[1306:2855321] multipeer session: stop timer
,2016-01-05 11:24:52.630 ThaliTest[1306:2855321] server session: disconnect
2016-01-05 11:24:52.631 ThaliTest[1306:2855321] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-05 11:24:52.644 ThaliTest[1306:2855321] server session: disconnect
2016-01-05 11:24:52.645 ThaliTest[1306:2855321] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-05 11:24:52.714 ThaliTest[1306:2855321] server session: disconnect
,2016-01-05 11:24:52.715 ThaliTest[1306:2855321] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-05 11:24:52.721 ThaliTest[1306:2855321] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-05T10:24:52.740Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:52.741Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:52.743Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:52.743Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
