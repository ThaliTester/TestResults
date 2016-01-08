#### Test 5546736337bcedb_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BEC3F76D-0E06-4339-BBDC-7903C9DC6B44/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BEC3F76D-0E06-4339-BBDC-7903C9DC6B44/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DAEC3BDB-E9AB-4635-963A-BD9F345EA52B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50245"
,(lldb)     command script import "/tmp/BEC3F76D-0E06-4339-BBDC-7903C9DC6B44/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 15:46:53.509 ThaliTest[1091:3584407] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/696750C0-F6BF-4959-8B52-FA3F208A2277/Library/Cookies/Cookies.binarycookies
,2016-01-08 15:46:53.636 ThaliTest[1091:3584407] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 15:46:53.637 ThaliTest[1091:3584407] Multi-tasking -> Device: YES, App: YES
,2016-01-08 15:46:53.645 ThaliTest[1091:3584407] Unlimited access to network resources
,2016-01-08 15:46:53.659 ThaliTest[1091:3584407] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 15:47:04.516 ThaliTest[1091:3584407] Resetting plugins due to page load.
,2016-01-08 15:47:08.077 ThaliTest[1091:3584407] Finished load of: file:///var/mobile/Containers/Bundle/Application/DAEC3BDB-E9AB-4635-963A-BD9F345EA52B/ThaliTest.app/www/index.html
,2016-01-08 15:47:08.286 ThaliTest[1091:3584407] JXcore Cordova plugin initializing
,2016-01-08 15:47:08.288 ThaliTest[1091:3584602] JXcore instance initializing
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
,2016-01-08 15:47:10.985 ThaliTest[1091:3584407] THREAD WARNING: ['JXcore'] took '156.348389' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 15:53:15.234 ThaliTest[1091:3584602] jxcore: startBroadcasting
,2016-01-08 15:53:15.246 ThaliTest[1091:3584602] server: starting Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:15.248 ThaliTest[1091:3584602] multipeer session: start timer: 0x1c220310
2016-01-08 15:53:15.249 ThaliTest[1091:3584602] THEMultipeerSession initialized peer Apple-Iphone5-1
2016-01-08 15:53:15.249 ThaliTest[1091:3584602] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 15:53:16.818 ThaliTest[1091:3584407] client: found peer: Apple-Iphone6-1.j1bF8Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.j1bF8Q==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-08 15:53:18.262 ThaliTest[1091:3584407] client: found peer: Apple-IpadAir2-1.xmg6Nw==
,2016-01-08 15:53:18.328 ThaliTest[1091:3584407] client: found peer: Apple-Iphone5s-1.MP5wlA==
,teardown
,testFindPeers stopped
,2016-01-08 15:53:19.070 ThaliTest[1091:3584602] jxcore: stopBroadcasting
2016-01-08 15:53:19.071 ThaliTest[1091:3584602] THEMultipeerSession stopping peer
2016-01-08 15:53:19.071 ThaliTest[1091:3584602] multipeer session: stop timer
2016-01-08 15:53:19.071 ThaliTest[1091:3584602] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 49182
2016-01-08 15:53:19.088 ThaliTest[1091:3584602] jxcore: startBroadcasting
,2016-01-08 15:53:19.094 ThaliTest[1091:3584602] server: starting Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:53:19.095 ThaliTest[1091:3584602] multipeer session: start timer: 0x1c211700
2016-01-08 15:53:19.095 ThaliTest[1091:3584602] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-08 15:53:19.095 ThaliTest[1091:3584602] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-08T14:53:19.099Z SendDataTCPServer.js: TCP/IP server is bound to port: 49182
,2016-01-08 15:53:19.136 ThaliTest[1091:3584407] client: found peer: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:19.137 ThaliTest[1091:3584407] client: found peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:19.138 ThaliTest[1091:3584407] client: found peer: ,Apple-IpadAir2-1.xmg6Nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:19,.143Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:19.146Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:19.146Z SendDataConnector.js: do connect now
2016-01-08 15:53,:19.147 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:19.147 ThaliTest[1091:3584602] client session: connect
2016-01-08 15:53:19.147 ThaliTest[1091:3584602] client session: stateChange:0->1 Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:19.154 ThaliTest[1091:3584407] client: found peer: Apple-Iphone5s-1.MP5wlA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailabl,e":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:20.342 ThaliTest[1091:3584407] client: lost peer: Apple-IpadAir2-1.xmg6Nw==
,2016-01-08 15:53:20.343 ThaliTest[1091:3584407] client session: onPeerLost: Apple-IpadAir2-1.xmg6Nw==
2016-01-08 15:53:20.344 ThaliTest[1091:3584407] client: lost peer: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:20.344 ThaliTest[1091:3584407] client sessi,on: onPeerLost: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:20.344 ThaliTest[1091:3584407] client session: onLinkFailure: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:20.345 ThaliTest[1091:3584407] client session: disconnect
2016-01-08 15:53:20.345 ThaliTest,[1091:3584407] client session: stateChange:1->0 Apple-Iphone5-1.oJtw2A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-08 15:53:20.345 Tha,liTest[1091:3584407] client session: fireConnectCallback: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:20.346 ThaliTest[1091:3584407] jxcore: connect: fail: Peer disconnected
2016-01-08T14:53:20.347Z SendDataConnector.js: CLIENT connected to 0, error: Peer ,disconnected
,2016-01-08T14:53:20.349Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T14:53:20.351Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 15:53:20.867 ThaliTest[1091:3584407] client: lost peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.867 ThaliTest[1091:3584407] client session: onPeerLost: Apple-Iphone6-1.j1bF8Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j,1bF8Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 15:53:20.910 ThaliTest[1091:3584407] client: lost peer: Apple-Iphone5s-1.MP5wlA==
2016-01-08 15:53:20.910 ThaliTest[1091:3584407] client session: onPeerLost: Apple-Iphone5s-1.MP5wlA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 15:53:21.015 ThaliTest[1091:3584407] client: found peer: Apple-IpadAir2-1.+bX+WA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.+bX+WA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:21.334 ThaliTest[1091:3584407] client: found peer: Apple-Iphone5s-1.zHt1vQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.zHt1vQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 15:53:21.474 ThaliTest[1091:3584407] client: found peer: Apple-Iphone6-1.bICwVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.bICwVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T14:53:25.363Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:25.364Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:30.375 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:53:30.376 ThaliTest[1091:3584602] jxcore: disconnect: fail
2016-01-08T14:53:30.376Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
20,16-01-08T14:53:30.377Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
2016-01-08T14:53:30.377Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:30.378Z SendDataConnector.js: do connect now
,2016-01-08 15:53:30.379 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:30.380 ThaliTest[1091:3584602] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:30.380 ThaliTest[1091:3584602] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:30.381Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:30.381Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:30.381Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:35.388Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:35.389Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:40.390 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:53:40.391 ThaliTest[1091:3584602] jxcore: disconnect: fail
2016-01-08T14:53:40.391Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
20,16-01-08T14:53:40.392Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
2016-01-08T14:53:40.393Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:40.393Z SendDataConnector.js: do connect now
,2016-01-08 15:53:40.394 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:40.394 ThaliTest[1091:3584602] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:40.394 ThaliTest[1091:3584602] jxcore: connect,: fail: Peer unreachable
,2016-01-08T14:53:40.395Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:40.395Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:40.395Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:45.398Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:45.398Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:49.125 ThaliTest[1091:3584407] multipeer session: restart
,2016-01-08 15:53:49.162 ThaliTest[1091:3584407] client: found peer: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:53:49.163 ThaliTest[1091:3584407] client: found peer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:53:49.163 ThaliTest[1091:3584407] client: found peer: Apple-Iphone6-1.bICwVA==
,2016-01-08 15:53:50.403 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:53:50.403 ThaliTest[1091:3584602] jxcore: disconnect: fail
2016-01-08T14:53:50.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
20,16-01-08T14:53:50.404Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
2016-01-08T14:53:50.404Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:53:50.405Z SendDataConnector.js: do connect now
,2016-01-08 15:53:50.406 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:50.407 ThaliTest[1091:3584602] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:50.407 ThaliTest[1091:3584602] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:50.408Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:50.408Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:50.408Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:55.417Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:55.418Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:54:00.430 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:54:00.430 ThaliTest[1091:3584602] jxcore: disconnect: fail
2016-01-08T14:54:00.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
20,16-01-08T14:54:00.431Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
2016-01-08T14:54:00.432Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:54:00.432Z SendDataConnector.js: do connect now
,2016-01-08 15:54:00.433 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5-1.oJtw2A==
2016-01-08 15:54:00.434 ThaliTest[1091:3584602] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
2016-01-08 15:54:00.434 ThaliTest[1091:3584602] jxcore: connect,: fail: Peer unreachable
,2016-01-08T14:54:00.434Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:54:00.435Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-08T14:54:00.437Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 15:54:00.438 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:54:00.438 ThaliTest[1091:3584602] jxcore: disconnect: fail
2016-01-08T14:54:00.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
---- round done--------
,startWithNextDevice
device[2]: Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.440Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.440Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:00.441Z SendDataConnector.js: do connect now
,2016-01-08 15:54:00.442 ThaliTest[1091:3584602] jxcore: connect Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:00.442 ThaliTest[1091:3584602] client session: connect
2016-01-08 15:54:00.443 ThaliTest[1091:3584602] client session: stateChange:0->1 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:00.783 ThaliTest[1091:3584407] multipeer session: reset timer
2016-01-08 15:54:00.783 ThaliTest[1091:3584407] multipeer session: stop timer
2016-01-08 15:54:00.784 ThaliTest[1091:3584407] multipeer session: start timer: 0x1c211700
2016-01-08 15:54:00.784 ThaliTest[1091:3584407] server session: connect
2016-01-08 15:54:00.784 ThaliTest[1091:3584407] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 15:54:00.791 ThaliTest[1091:3584407] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 15:54:07.079 ThaliTest[1091:3586159] client session: connected
2016-01-08 15:54:07.079 ThaliTest[1091:3586159] client session: stateChange:1->2 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.139 ThaliTest[1091:3586147] server session: connected
2016-01-08 15:54:07.140 ThaliTest[1091:3586147] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 15:54:07.761 ThaliTest[1091:3584407] server relay: connected (to port: 49182)
,2016-01-08T14:54:07.773Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:07.994 ThaliTest[1091:3586159] client session: fireConnectCallback: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:07.994 ThaliTest[1091:3586159] jxcore: connect: success
2016-01-08T14:54:07.995Z SendDataConnector.js: CLIENT connected to 49190, error: null
2016-01-08T14:54:07.996Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:07.998 ThaliTest[1091:3584407] client: relay established
2016-01-08 15:54:07.999 ThaliTest[1091:3584407] client: new accepted socket: 0x1c52f9e0
,2016-01-08T14:54:08.015Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 15:54:08.188 ThaliTest[1091:3584407] multipeer session: reset timer
2016-01-08 15:54:08.189 ThaliTest[1091:3584407] multipeer session: stop timer
2016-01-08 15:54:08.189 ThaliTest[1091:3584407] multipeer session: start timer: 0x1c211700
2016-,01-08 15:54:08.189 ThaliTest[1091:3584407] server session: connect
2016-01-08 15:54:08.189 ThaliTest[1091:3584407] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 15:54:08.200 ThaliTest[1091:3584407] server: accepting invitation Apple-Iphone6-1
,2016-01-08 15:54:08.574 ThaliTest[1091:3584407] multipeer session: reset timer
2016-01-08 15:54:08.574 ThaliTest[1091:3584407] multipeer session: stop timer
2016-01-08 15:54:08.574 ThaliTest[1091:3584407] multipeer session: start timer: 0x1c211700
2016-01-08 15:54:08.574 ThaliTest[1091:3584407] server session: connect
2016-01-08 15:54:08.575 ThaliTest[1091:3584407] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 15:54:08.584 ThaliTest[1091:3584407] server: accepting invitation Apple-Iphone5s-1
,2016-01-08T14:54:09.185Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T14:54:09.187Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:09.312 ThaliTest[1091:3586149] server session: not connected Apple-IpadAir2-1
,2016-01-08T14:54:09.331Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T14:54:09.359Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T14:54:09.533Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T14:54:09.533Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:09.535Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:09.535Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:09.537 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:54:09.537 ThaliTest[1091:3584602] client session: disconnectFromPeer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:09.537 ThaliTest[1091:3584602] client session: disconnect
2016-01-08 15:54:09.537 ThaliTest[1091:3584602] client session: stateChange:2->0 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:09.546 ThaliTest[1091:3584602] jxcore: disconnect: success
2016-01-08T14:54:09.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.+bX+WA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5s-1.zHt1vQ==
2016-01-08T14:54:09.549Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.zHt1vQ==
2016-01-08T14:54:09.549Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.zHt1vQ==
2016-01-08T14:54:09.549Z SendDataConnect,or.js: do connect now
2016-01-08 15:54:09.550 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:09.550 ThaliTest[1091:3584602] client session: connect
2016-01-08 15:54:09.550 ThaliTest[1091:3584602] client session: state,Change:0->1 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:10.862 ThaliTest[1091:3586149] server session: connected
2016-01-08 15:54:10.863 ThaliTest[1091:3586149] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 15:54:10.869 ThaliTest[1091:3584407] server relay: connected (to port: 49182)
,2016-01-08T14:54:10.875Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:11.210 ThaliTest[1091:3586148] server session: connected
2016-01-08 15:54:11.210 ThaliTest[1091:3586148] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 15:54:11.226 ThaliTest[1091:3584407] server relay: connected (to port: 49182)
,2016-01-08T14:54:11.236Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T14:54:11.325Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T14:54:11.339Z SendDataTCPServer.js: TCP/IP server has received 18615 bytes of data
,2016-01-08T14:54:11.359Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-08T14:54:11.410Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-08T14:54:11.426Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-08T14:54:11.487Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-08T14:54:11.529Z SendDataTCPServer.js: TCP/IP server has received 76508 bytes of data
,2016-01-08T14:54:11.543Z SendDataTCPServer.js: TCP/IP server has received 85339 bytes of data
,2016-01-08T14:54:11.559Z SendDataTCPServer.js: TCP/IP server has received 99645 bytes of data
,2016-01-08T14:54:11.571Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:11.622 ThaliTest[1091:3586149] server session: not connected Apple-Iphone6-1
,2016-01-08T14:54:11.981Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T14:54:11.996Z SendDataTCPServer.js: TCP/IP server has received 18544 bytes of data
,2016-01-08T14:54:12.011Z SendDataTCPServer.js: TCP/IP server has received 25185 bytes of data
,2016-01-08T14:54:12.025Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-08T14:54:12.053Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
,2016-01-08T14:54:12.070Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-08T14:54:12.085Z SendDataTCPServer.js: TCP/IP server has received 78414 bytes of data
,2016-01-08T14:54:12.101Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T14:54:12.125Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-08T14:54:12.186Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-08T14:54:12.212Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T14:54:12.248Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:12.312 ThaliTest[1091:3586149] server session: not connected Apple-Iphone5s-1
,2016-01-08 15:54:12.603 ThaliTest[1091:3586149] client session: connected
2016-01-08 15:54:12.603 ThaliTest[1091:3586149] client session: stateChange:1->2 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:12.632 ThaliTest[1091:3586159] client session: fireConnectCallback: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:12.632 ThaliTest[1091:3586159] jxcore: connect: success
,2016-01-08T14:54:12.633Z SendDataConnector.js: CLIENT connected to 49195, error: null
2016-01-08T14:54:12.633Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:12.635 ThaliTest[1091:3584407] client: relay established
2016-01-08 15:54:12.636 ThaliTest[1091:3584407] client: new accepted socket: 0x1c545b80
,2016-01-08T14:54:12.649Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:13.764Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T14:54:13.816Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T14:54:13.892Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T14:54:13.893Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:13.895Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:13.895Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:13.896 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:54:13.896 ThaliTest[1091:3584602] client session: disconnectFromPeer: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:13.897 ThaliTest[1091:3584602] client session: disconnect
2016-01-08 15:54:13.897 ThaliTest[1091:3584602] client session: stateChange:2->0 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:13.906 ThaliTest[1091:3584602] jxcore: disconnect: success
2016-01-08T14:54:13.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.zHt1vQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one6-1.bICwVA==
2016-01-08T14:54:13.908Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:13.908Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:13.908Z SendDataConnector.,js: do connect now
2016-01-08 15:54:13.909 ThaliTest[1091:3584602] jxcore: connect Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:13.909 ThaliTest[1091:3584602] client session: connect
2016-01-08 15:54:13.909 ThaliTest[1091:3584602] client session: stateChan,ge:0->1 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:16.511 ThaliTest[1091:3586149] client session: connected
2016-01-08 15:54:16.511 ThaliTest[1091:3586149] client session: stateChange:1->2 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:16.566 ThaliTest[1091:3586147] client session: fireConnectCallback: Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:16.566 ThaliTest[1091:3586147] jxcore: connect: success
2016-01-08T14:54:16.567Z SendDataConnector.js: CLIENT connected to 4920,0, error: null
2016-01-08T14:54:16.567Z SendDataConnector.js: CLIENT starting client 
2016-01-08 15:54:16.569 ThaliTest[1091:3584407] client: relay established
2016-01-08 15:54:16.569 ThaliTest[1091:3584407] client: new accepted socket: 0x1c431990
,2016-01-08T14:54:16.582Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:17.752Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T14:54:17.765Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T14:54:17.778Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T14:54:17.829Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T14:54:17.881Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T14:54:17.881Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:17.883Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:17.883Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:17.884 ThaliTest[1091:3584602] jxcore: disconnect
2016-01-08 15:54:17.885 ThaliTest[1091:3584602] client session: disconnectFromPeer: Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:17.885 ThaliTest[1091:3584602] client session: disconnect
2016-01-08 15:54:17.885 ThaliTest[1091:3584602] client session: stateChange:2->0 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:17.894 ThaliTest[1091:3584602] jxcore: disconnect: success
2016-01-08T14:54:17.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.bICwVA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T14:54:17.914Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:17.914Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-08 15:54:18.863 ThaliTest[1091:3584602] jxcore: stopBroadcasting
,2016-01-08 15:54:18.865 ThaliTest[1091:3584602] THEMultipeerSession stopping peer
2016-01-08 15:54:18.865 ThaliTest[1091:3584602] multipeer session: stop timer
,2016-01-08 15:54:18.866 ThaliTest[1091:3584602] server session: disconnect
2016-01-08 15:54:18.866 ThaliTest[1091:3584602] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 15:54:18.886 ThaliTest[1091:3584602] server session: disconnect
,2016-01-08 15:54:18.890 ThaliTest[1091:3584602] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 15:54:18.967 ThaliTest[1091:3584602] server session: disconnect
,2016-01-08 15:54:18.968 ThaliTest[1091:3584602] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 15:54:19.031 ThaliTest[1091:3584602] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
