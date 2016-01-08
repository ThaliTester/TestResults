#### Test 55431344148e3f8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/03116B2D-7EC0-44C4-9793-6961B59B14F1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/03116B2D-7EC0-44C4-9793-6961B59B14F1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344148e3f8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4DF13E90-0F4B-4CC7-A142-6A9760AAC149/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49982"
,(lldb)     command script import "/tmp/03116B2D-7EC0-44C4-9793-6961B59B14F1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 10:46:48.639 ThaliTest[1508:3299721] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/297A2300-FD1F-4944-9451-E0B5044333E0/Library/Cookies/Cookies.binarycookies
,2016-01-08 10:46:48.982 ThaliTest[1508:3299721] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 10:46:48.983 ThaliTest[1508:3299721] Multi-tasking -> Device: YES, App: YES
,2016-01-08 10:46:48.992 ThaliTest[1508:3299721] Unlimited access to network resources
,2016-01-08 10:46:49.000 ThaliTest[1508:3299721] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 10:46:57.917 ThaliTest[1508:3299721] Resetting plugins due to page load.
,2016-01-08 10:47:01.582 ThaliTest[1508:3299721] Finished load of: file:///var/mobile/Containers/Bundle/Application/4DF13E90-0F4B-4CC7-A142-6A9760AAC149/ThaliTest.app/www/index.html
,2016-01-08 10:47:01.713 ThaliTest[1508:3299721] JXcore Cordova plugin initializing
,2016-01-08 10:47:01.713 ThaliTest[1508:3299959] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-08 10:47:02.812 ThaliTest[1508:3299721] THREAD WARNING: ['JXcore'] took '68.471924' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 10:51:34.681 ThaliTest[1508:3299959] jxcore: startBroadcasting
,2016-01-08 10:51:34.698 ThaliTest[1508:3299959] server: starting Apple-IpadAir2-1.TL+VGA==
,2016-01-08 10:51:34.700 ThaliTest[1508:3299959] multipeer session: start timer: 0x147ba170
2016-01-08 10:51:34.700 ThaliTest[1508:3299959] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-08 10:51:34.702 ThaliTest[1508:3299959] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 10:51:35.866 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1.1B6pGw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 10:51:36.257 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:36.263 ThaliTest[1508:3299721] client: found peer: Apple-Iphone6-1.hx3ANw==
,teardown
,testFindPeers stopped
,2016-01-08 10:51:36.659 ThaliTest[1508:3299959] jxcore: stopBroadcasting
,2016-01-08 10:51:36.659 ThaliTest[1508:3299959] THEMultipeerSession stopping peer
,2016-01-08 10:51:36.660 ThaliTest[1508:3299959] multipeer session: stop timer
,2016-01-08 10:51:36.663 ThaliTest[1508:3299959] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64740
,2016-01-08 10:51:36.693 ThaliTest[1508:3299959] jxcore: startBroadcasting
,2016-01-08 10:51:36.697 ThaliTest[1508:3299959] server: starting Apple-IpadAir2-1.7azU7Q==
,2016-01-08 10:51:36.698 ThaliTest[1508:3299959] multipeer session: start timer: 0x163845e0
,2016-01-08 10:51:36.699 ThaliTest[1508:3299959] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-08 10:51:36.700 ThaliTest[1508:3299959] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-08T09:51:36.705Z SendDataTCPServer.js: TCP/IP server is bound to port: 64740
,2016-01-08 10:51:36.724 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:36.725 ThaliTest[1508:3299721] client: found peer: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:36.725 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:36.726 ThaliTest[1508:3299721] client: found peer: Apple-IpadAir2-1.TL+VGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.rHC9Aw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:51:36.729Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:51:36.730Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.rHC9Aw==
2016-01-08T09:51:36.730Z SendDataConnector.js: do connect now
,2016-01-08 10:51:36.731 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:36.731 ThaliTest[1508:3299959] client session: connect
,2016-01-08 10:51:36.731 ThaliTest[1508:3299959] client session: stateChange:0->1 Apple-Iphone5-1.rHC9Aw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:37.883 ThaliTest[1508:3299721] client: lost peer: Apple-Iphone6-1.hx3ANw==
2016-01-08 10:51:37.884 ThaliTest[1508:3299721] client session: onPeerLost: Apple-Iphone6-1.hx3ANw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.hx3ANw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 10:51:38.031 ThaliTest[1508:3299721] client: lost peer: Apple-IpadAir2-1.TL+VGA==
2016-01-08 10:51:38.032 ThaliTest[1508:3299721] client session: onPeerLost: Apple-IpadAir2-1.TL+VGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.TL+VGA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 10:51:38.357 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5-1.AdDQ5g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.AdDQ5g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 10:51:38.443 ThaliTest[1508:3299721] client: lost peer: Apple-Iphone5s-1.1B6pGw==
2016-01-08 10:51:38.443 ThaliTest[1508:3299721] client session: onPeerLost: Apple-Iphone5s-1.1B6pGw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.1B6pGw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 10:51:38.900 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:51:38.901 ThaliTest[1508:3299721] client: found peer: Apple-Iphone6-1.0EeFvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.KjG2gw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.0EeFvA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 10:51:43.815 ThaliTest[1508:3299721] client: lost peer: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:43.815 ThaliTest[1508:3299721] client session: onPeerLost: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:43.815 ThaliTest[1508:3299721] client session: onLinkFailure: Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:43.815 ThaliTest[1508:3299721] client session: disconnect
2016-01-08 10:51:43.816 ThaliTest[1508:3299721] client session: stateChange:1->0 Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:43.817 ThaliTest[1508:3299721] client session: fireConnectCallback: Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:43.817 ThaliTest[1508:3299721] jxcore: connect: fail: Peer disconnected
,2016-01-08T09:51:43.819Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-08T09:51:43.819Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T09:51:43.820Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.rHC9Aw==","peerName":"(null)","peerAvailable":false}]
,2016-01-08T09:51:48.829Z SendDataConnector.js: re-try now : Apple-Iphone5-1.rHC9Aw==
2016-01-08T09:51:48.830Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:53.841 ThaliTest[1508:3299959] jxcore: disconnect
,2016-01-08 10:51:53.842 ThaliTest[1508:3299959] jxcore: disconnect: fail
,2016-01-08T09:51:53.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:51:53.844Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.rHC9Aw== with availability status: true
,2016-01-08T09:51:53.844Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:51:53.845Z SendDataConnector.js: do connect now
,2016-01-08 10:51:53.846 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:51:53.846 ThaliTest[1508:3299959] client: connect: unreachable Apple-Iphone5-1.rHC9Aw==
2016-01-08 10:51:53.847 ThaliTest[1508:3299959] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:51:53.847Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:51:53.848Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T09:51:53.849Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:51:58.853Z SendDataConnector.js: re-try now : Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:51:58.853Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:03.861 ThaliTest[1508:3299959] jxcore: disconnect
,2016-01-08 10:52:03.861 ThaliTest[1508:3299959] jxcore: disconnect: fail
,2016-01-08T09:52:03.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:03.863Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.rHC9Aw== with availability status: true
,2016-01-08T09:52:03.864Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:03.864Z SendDataConnector.js: do connect now
,2016-01-08 10:52:03.865 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:03.865 ThaliTest[1508:3299959] client: connect: unreachable Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:03.866 ThaliTest[1508:3299959] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:03.867Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:52:03.867Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T09:52:03.868Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 10:52:06.700 ThaliTest[1508:3299721] multipeer session: restart
,2016-01-08 10:52:06.728 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:06.728 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:06.728 ThaliTest[1508:3299721] client: found peer: Apple-Iphone6-1.0EeFvA==
,2016-01-08T09:52:08.873Z SendDataConnector.js: re-try now : Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:08.873Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:13.880 ThaliTest[1508:3299959] jxcore: disconnect
2016-01-08 10:52:13.881 ThaliTest[1508:3299959] jxcore: disconnect: fail
,2016-01-08T09:52:13.882Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:13.882Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.rHC9Aw== with availability status: true
,2016-01-08T09:52:13.883Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:13.884Z SendDataConnector.js: do connect now
,2016-01-08 10:52:13.885 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:13.885 ThaliTest[1508:3299959] client: connect: unreachable Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:13.886 ThaliTest[1508:3299959] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:13.887Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:52:13.888Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T09:52:13.888Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T09:52:18.895Z SendDataConnector.js: re-try now : Apple-Iphone5-1.rHC9Aw==
2016-01-08T09:52:18.895Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:23.900 ThaliTest[1508:3299959] jxcore: disconnect
2016-01-08 10:52:23.901 ThaliTest[1508:3299959] jxcore: disconnect: fail
,2016-01-08T09:52:23.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:23.902Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.rHC9Aw== with availability status: true
,2016-01-08T09:52:23.903Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.rHC9Aw==
,2016-01-08T09:52:23.903Z SendDataConnector.js: do connect now
,2016-01-08 10:52:23.905 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:23.905 ThaliTest[1508:3299959] client: connect: unreachable Apple-Iphone5-1.rHC9Aw==
,2016-01-08 10:52:23.906 ThaliTest[1508:3299959] jxcore: connect: fail: Peer unreachable
,2016-01-08T09:52:23.907Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T09:52:23.908Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T09:52:23.910Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 10:52:23.910 ThaliTest[1508:3299959] jxcore: disconnect
,2016-01-08 10:52:23.911 ThaliTest[1508:3299959] jxcore: disconnect: fail
,2016-01-08T09:52:23.912Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.rHC9Aw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:23.915Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:23.915Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.AdDQ5g==
,2016-01-08T09:52:23.916Z SendDataConnector.js: do connect now
,2016-01-08 10:52:23.917 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:23.918 ThaliTest[1508:3299959] client session: connect
,2016-01-08 10:52:23.919 ThaliTest[1508:3299959] client session: stateChange:0->1 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:24.123 ThaliTest[1508:3299721] multipeer session: reset timer
2016-01-08 10:52:24.124 ThaliTest[1508:3299721] multipeer session: stop timer
2016-01-08 10:52:24.124 ThaliTest[1508:3299721] multipeer session: start timer: 0x163845e0
,2016-01-08 10:52:24.124 ThaliTest[1508:3299721] server session: connect
2016-01-08 10:52:24.125 ThaliTest[1508:3299721] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 10:52:24.131 ThaliTest[1508:3299721] server: accepting invitation Apple-Iphone6-1
,2016-01-08 10:52:27.636 ThaliTest[1508:3300644] server session: connected
2016-01-08 10:52:27.636 ThaliTest[1508:3300644] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 10:52:27.697 ThaliTest[1508:3300651] client session: connected
,2016-01-08 10:52:27.697 ThaliTest[1508:3300651] client session: stateChange:1->2 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:27.723 ThaliTest[1508:3300649] client session: fireConnectCallback: Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:27.723 ThaliTest[1508:3300649] jxcore: connect: success
,2016-01-08T09:52:27.725Z SendDataConnector.js: CLIENT connected to 64744, error: null
,2016-01-08T09:52:27.725Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:52:27.728 ThaliTest[1508:3299721] client: relay established
2016-01-08 10:52:27.729 ThaliTest[1508:3299721] client: new accepted socket: 0x16689630
,2016-01-08T09:52:27.744Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 10:52:27.809 ThaliTest[1508:3299721] server relay: connected (to port: 64740)
,2016-01-08T09:52:28.184Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:52:28.806Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T09:52:28.821Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T09:52:28.885Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-08T09:52:28.935Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-08T09:52:28.952Z SendDataTCPServer.js: TCP/IP server has received 40515 bytes of data
,2016-01-08T09:52:28.968Z SendDataTCPServer.js: TCP/IP server has received 68985 bytes of data
,2016-01-08T09:52:28.984Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-08T09:52:28.998Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-08T09:52:29.013Z SendDataTCPServer.js: TCP/IP server has received 90885 bytes of data
,2016-01-08T09:52:29.028Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:52:29.068 ThaliTest[1508:3300644] server session: not connected Apple-Iphone6-1
,2016-01-08T09:52:29.347Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T09:52:29.361Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:52:29.362Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:52:29.363Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:52:29.363Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:29.366 ThaliTest[1508:3299959] jxcore: disconnect
,2016-01-08 10:52:29.366 ThaliTest[1508:3299959] client session: disconnectFromPeer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:29.367 ThaliTest[1508:3299959] client session: disconnect
2016-01-08 10:52:29.367 ThaliTest[1508:3299959] client session: stateChange:2->0 Apple-Iphone5-1.AdDQ5g==
,2016-01-08 10:52:29.376 ThaliTest[1508:3299959] jxcore: disconnect: success
2016-01-08T09:52:29.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.AdDQ5g==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1.KjG2gw==
2016-01-08T09:52:29.378Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.KjG2gw==
2016-01-08T09:52:29.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.KjG2gw==
2016-01-08T09:52:29.379Z SendDataConnecto,r.js: do connect now
2016-01-08 10:52:29.379 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:29.380 ThaliTest[1508:3299959] client session: connect
2016-01-08 10:52:29.380 ThaliTest[1508:3299959] client session: stateChange:0->1 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:33.135 ThaliTest[1508:3300648] client session: connected
,2016-01-08 10:52:33.135 ThaliTest[1508:3300648] client session: stateChange:1->2 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:33.159 ThaliTest[1508:3300649] client session: fireConnectCallback: Apple-Iphone5s-1.KjG2gw==
2016-01-08 10:52:33.160 ThaliTest[1508:3300649] jxcore: connect: success
,2016-01-08T09:52:33.161Z SendDataConnector.js: CLIENT connected to 64748, error: null
,2016-01-08T09:52:33.161Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:52:33.164 ThaliTest[1508:3299721] client: relay established
2016-01-08 10:52:33.164 ThaliTest[1508:3299721] client: new accepted socket: 0x1659eb60
,2016-01-08T09:52:33.178Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:52:33.652Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T09:52:33.666Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:52:33.725Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T09:52:33.784Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T09:52:33.796Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T09:52:33.797Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T09:52:33.797Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:52:33.797Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:33.798 ThaliTest[1508:3299959] jxcore: disconnect
2016-01-08 10:52:33.798 ThaliTest[1508:3299959] client session: disconnectFromPeer: Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:33.798 ThaliTest[1508:3299959] client session: disconnect
,2016-01-08 10:52:33.798 ThaliTest[1508:3299959] client session: stateChange:2->0 Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:33.801 ThaliTest[1508:3299959] jxcore: disconnect: success
2016-01-08T09:52:33.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.KjG2gw==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one6-1.0EeFvA==
2016-01-08T09:52:33.802Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.0EeFvA==
2016-01-08T09:52:33.802Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.0EeFvA==
2016-01-08T09:52:33.802Z SendDataConnector.js: do connect now
2016-01-08 10:52:33.802 ThaliTest[1508:3299959] jxcore: connect Apple-Iphone6-1.0EeFvA==
2016-01-08 10:52:33.802 ThaliTest[1508:3299959] client session: connect
2016-01-08 10:52:33.802 ThaliTest[1508:3299959] client session: stateChange:0->1 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:37.132 ThaliTest[1508:3300644] client session: connected
2016-01-08 10:52:37.133 ThaliTest[1508:3300644] client session: stateChange:1->2 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:37.174 ThaliTest[1508:3300648] client session: fireConnectCallback: Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:37.175 ThaliTest[1508:3300648] jxcore: connect: success
,2016-01-08T09:52:37.176Z SendDataConnector.js: CLIENT connected to 64751, error: null
2016-01-08T09:52:37.176Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 10:52:37.179 ThaliTest[1508:3299721] client: relay established
2016-01-08 10:52:37.179 ThaliTest[1508:3299721] client: new accepted socket: 0x16592500
,2016-01-08T09:52:37.192Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T09:52:37.707Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T09:52:37.719Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T09:52:37.780Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T09:52:37.817Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T09:52:37.818Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T09:52:37.818Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T09:52:37.819Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:37.819 ThaliTest[1508:3299959] jxcore: disconnect
,2016-01-08 10:52:37.820 ThaliTest[1508:3299959] client session: disconnectFromPeer: Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:37.820 ThaliTest[1508:3299959] client session: disconnect
2016-01-08 10:52:37.821 ThaliTest[1508:3299959] client session: stateChange:2->0 Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:37.881 ThaliTest[1508:3299959] jxcore: disconnect: success
,2016-01-08T09:52:37.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.0EeFvA==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T09:52:37.892Z SendDataConnector.js: CLIENT Stop now
2016-01-08T09:52:37.892Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 10:52:54.126 ThaliTest[1508:3299721] multipeer session: restart
,2016-01-08 10:52:54.154 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5-1.AdDQ5g==
2016-01-08 10:52:54.154 ThaliTest[1508:3299721] client: found peer: Apple-Iphone6-1.0EeFvA==
,2016-01-08 10:52:54.156 ThaliTest[1508:3299721] client: found peer: Apple-Iphone5s-1.KjG2gw==
,2016-01-08 10:52:58.308 ThaliTest[1508:3299721] multipeer session: reset timer
2016-01-08 10:52:58.309 ThaliTest[1508:3299721] multipeer session: stop timer
2016-01-08 10:52:58.309 ThaliTest[1508:3299721] multipeer session: start timer: 0x163845e0
,2016-01-08 10:52:58.310 ThaliTest[1508:3299721] server session: connect
2016-01-08 10:52:58.310 ThaliTest[1508:3299721] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 10:52:58.316 ThaliTest[1508:3299721] server: accepting invitation Apple-Iphone5-1
,2016-01-08 10:53:01.963 ThaliTest[1508:3300746] server session: connected
2016-01-08 10:53:01.964 ThaliTest[1508:3300746] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 10:53:01.990 ThaliTest[1508:3299721] server relay: connected (to port: 64740)
,2016-01-08T09:53:02.000Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:53:03.793Z SendDataTCPServer.js: TCP/IP server has received 5404 bytes of data
,2016-01-08T09:53:03.808Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-08T09:53:03.825Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-08T09:53:03.864Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-08T09:53:03.878Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T09:53:03.918Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-08T09:53:03.934Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T09:53:03.950Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:53:04.054 ThaliTest[1508:3300747] server session: not connected Apple-Iphone5-1
,2016-01-08 10:53:08.561 ThaliTest[1508:3299721] multipeer session: reset timer
,2016-01-08 10:53:08.562 ThaliTest[1508:3299721] multipeer session: stop timer
,2016-01-08 10:53:08.562 ThaliTest[1508:3299721] multipeer session: start timer: 0x163845e0
2016-01-08 10:53:08.562 ThaliTest[1508:3299721] server session: connect
,2016-01-08 10:53:08.563 ThaliTest[1508:3299721] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 10:53:08.569 ThaliTest[1508:3299721] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 10:53:11.815 ThaliTest[1508:3300652] server session: connected
,2016-01-08 10:53:11.816 ThaliTest[1508:3300652] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 10:53:11.894 ThaliTest[1508:3299721] server relay: connected (to port: 64740)
,2016-01-08T09:53:11.904Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T09:53:12.404Z SendDataTCPServer.js: TCP/IP server has received 3143 bytes of data
,2016-01-08T09:53:12.417Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-08T09:53:12.430Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-08T09:53:12.446Z SendDataTCPServer.js: TCP/IP server has received 20805 bytes of data
,2016-01-08T09:53:12.460Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-08T09:53:12.475Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-08T09:53:12.502Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T09:53:12.518Z SendDataTCPServer.js: TCP/IP server has received 68985 bytes of data
,2016-01-08T09:53:12.774Z SendDataTCPServer.js: TCP/IP server has received 73081 bytes of data
,2016-01-08T09:53:12.788Z SendDataTCPServer.js: TCP/IP server has received 97313 bytes of data
,2016-01-08T09:53:12.803Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 10:53:12.914 ThaliTest[1508:3300795] server session: not connected Apple-Iphone5s-1
,teardown
,testSendData stopped
,2016-01-08 10:53:34.574 ThaliTest[1508:3299959] jxcore: stopBroadcasting
,2016-01-08 10:53:34.575 ThaliTest[1508:3299959] THEMultipeerSession stopping peer
,2016-01-08 10:53:34.575 ThaliTest[1508:3299959] multipeer session: stop timer
,2016-01-08 10:53:34.576 ThaliTest[1508:3299959] server session: disconnect
2016-01-08 10:53:34.577 ThaliTest[1508:3299959] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 10:53:34.586 ThaliTest[1508:3299959] server session: disconnect
2016-01-08 10:53:34.587 ThaliTest[1508:3299959] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 10:53:34.594 ThaliTest[1508:3299959] server session: disconnect
2016-01-08 10:53:34.595 ThaliTest[1508:3299959] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 10:53:34.603 ThaliTest[1508:3299959] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-08T09:53:34.621Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.623Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.624Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T09:53:34.625Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
