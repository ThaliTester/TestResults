#### Test 55613145dd493c6_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3E20B6F2-A415-44CD-A441-76668A7B0B2E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/3E20B6F2-A415-44CD-A441-76668A7B0B2E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/339E6F9A-8681-413B-B408-E852563249B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52189"
,(lldb)     command script import "/tmp/3E20B6F2-A415-44CD-A441-76668A7B0B2E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 13:53:17.097 ThaliTest[1239:4047264] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/51F7C204-51D1-483D-8B95-DC8693662D1D/Library/Cookies/Cookies.binarycookies
,2016-01-11 13:53:17.202 ThaliTest[1239:4047264] Apache Cordova native platform version 3.9.2 is starting.
2016-01-11 13:53:17.203 ThaliTest[1239:4047264] Multi-tasking -> Device: YES, App: YES
,2016-01-11 13:53:17.208 ThaliTest[1239:4047264] Unlimited access to network resources
,2016-01-11 13:53:17.220 ThaliTest[1239:4047264] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 13:53:23.193 ThaliTest[1239:4047264] Resetting plugins due to page load.
,2016-01-11 13:53:25.250 ThaliTest[1239:4047264] Finished load of: file:///var/mobile/Containers/Bundle/Application/339E6F9A-8681-413B-B408-E852563249B2/ThaliTest.app/www/index.html
,2016-01-11 13:53:25.446 ThaliTest[1239:4047264] JXcore Cordova plugin initializing
,2016-01-11 13:53:25.448 ThaliTest[1239:4047377] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
,--- start :testFindPeers.js---
testFindPeers created [object Object]
serverPort is 8876
2016-01-11 13:59:31.693 ThaliTest[1239:4047377] jxcore: startBroadcasting
,2016-01-11 13:59:31.710 ThaliTest[1239:4047377] server: starting Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:31.711 ThaliTest[1239:4047377] multipeer session: start timer: 0x19489500
2016-01-11 13:59:31.711 ThaliTest[1239:4047377] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-11 13:59:31.712 ThaliTest[1239:4047377] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-11 13:59:32.979 ThaliTest[1239:4047264] client: found peer: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:32.979 ThaliTest[1239:4047264] client: found peer: Apple-IpadAir2-1.xr446Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.4vXNuA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-11 13:59:33.303 ThaliTest[1239:4047264] client: found peer: Apple-Iphone5s-1.hXPtug==
,teardown
,testFindPeers stopped
2016-01-11 13:59:33.543 ThaliTest[1239:4047377] jxcore: stopBroadcasting
2016-01-11 13:59:33.543 ThaliTest[1239:4047377] THEMultipeerSession stopping peer
2016-01-11 13:59:33.543 ThaliTest[1239:4047377] multipeer session: stop time,r
2016-01-11 13:59:33.543 ThaliTest[1239:4047377] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":2,0000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51027
,2016-01-11 13:59:33.570 ThaliTest[1239:4047377] jxcore: startBroadcasting
,2016-01-11 13:59:33.575 ThaliTest[1239:4047377] server: starting Apple-Iphone5-1.03CIBg==
,2016-01-11 13:59:33.583 ThaliTest[1239:4047377] multipeer session: start timer: 0x1948b180
,2016-01-11 13:59:33.587 ThaliTest[1239:4047377] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-11 13:59:33.588 ThaliTest[1239:4047377] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2016-01-11 13:59:33.606 ThaliTest[1239:4047264] client: found peer: Apple-Iphone5s-1.hXPtug==
null
2016-01-11T12:59:33.608Z SendDataTCPServer.js: TCP/IP server is bound to port: 51027
2016-01-11 13:59:33.609 ThaliTest[1239:4047264] client: found peer: Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:33.613 ThaliTest[1239:4047264] client: found peer: Apple-Iphone6-1.4vXNuA==
,2016-01-11 13:59:33.614 ThaliTest[1239:4047264] client: found peer: Apple-IpadAir2-1.xr446Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5s-1.hXPtug==
,2016-01-11T12:59:33.623Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11T12:59:33.624Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11T12:59:33.624Z SendDataConnector.js: do connect now
,2016-01-11 13:59:33.625 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.hXPtug==
,2016-01-11 13:59:33.626 ThaliTest[1239:4047377] client session: connect
,2016-01-11 13:59:33.627 ThaliTest[1239:4047377] client session: stateChange:0->1 Apple-Iphone5s-1.hXPtug==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:34.712 ThaliTest[1239:4047264] client: lost peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:34.712 ThaliTest[1239:4047264] client session: onPeerLost: Apple-Iphone5-1.b8hDBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b,8hDBw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 13:59:34.811 ThaliTest[1239:4047264] client: found peer: Apple-IpadAir2-1.oW56/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.oW56/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:35.464 ThaliTest[1239:4047264] client: lost peer: Apple-IpadAir2-1.xr446Q==
2016-01-11 13:59:35.466 ThaliTest[1239:4047264] client session: onPeerLost: Apple-IpadAir2-1.xr446Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-11 13:59:35.466 ThaliTest[1239:4047264] client: found peer: Apple-Iphone5s-1.yPThEg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.yPThEg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:35.490 ThaliTest[1239:4047264] client: lost peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.490 ThaliTest[1239:4047264] client session: onPeerLost: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.490 ThaliTest[1239:4047264] client session: onLinkFailure: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.491 ThaliTest[1239:4047264] client session: disconnect
2016-01-11 13:59:35.491 ThaliTest[1239:4047264] client session: stateChange:1->0 Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.492 T,haliTest[1239:4047264] client session: fireConnectCallback: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:35.492 ThaliTest[1239:4047264] jxcore: connect: fail: Peer disconnected
2016-01-11T12:59:35.493Z SendDataConnector.js: CLIENT connected to 0, error: Pe,er disconnected
2016-01-11T12:59:35.494Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11T12:59:35.494Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerN,ame":"(null)","peerAvailable":false}]
,2016-01-11 13:59:35.508 ThaliTest[1239:4047264] client: found peer: Apple-Iphone6-1.zQytdg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.zQytdg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:39.662 ThaliTest[1239:4047264] client: lost peer: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.663 ThaliTest[1239:4047264] client session: onPeerLost: Apple-Iphone6-1.4vXNuA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11T12:59:40.501Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
,2016-01-11T12:59:40.501Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 13:59:45.504 ThaliTest[1239:4047377] jxcore: disconnect
2016-01-11 13:59:45.505 ThaliTest[1239:4047377] jxcore: disconnect: fail
2016-01-11T12:59:45.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T12:59:45.505Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T12:59:45.506Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:45,.506Z SendDataConnector.js: do connect now
2016-01-11 13:59:45.506 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:45.506 ThaliTest[1239:4047377] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:,45.506 ThaliTest[1239:4047377] jxcore: connect: fail: Peer unreachable
2016-01-11T12:59:45.507Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:45.507Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T12:59:45.507Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T12:59:50.519Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:50.519Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 13:59:55.525 ThaliTest[1239:4047377] jxcore: disconnect
2016-01-11 13:59:55.526 ThaliTest[1239:4047377] jxcore: disconnect: fail
2016-01-11T12:59:55.526Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T12:59:55.526Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T12:59:55.526Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T12:59:55,.526Z SendDataConnector.js: do connect now
2016-01-11 13:59:55.527 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:55.527 ThaliTest[1239:4047377] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:,55.527 ThaliTest[1239:4047377] jxcore: connect: fail: Peer unreachable
2016-01-11T12:59:55.527Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:55.527Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T12:59:55.528Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:00.537Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:00.537Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:03.603 ThaliTest[1239:4047264] multipeer session: restart
,2016-01-11 14:00:03.633 ThaliTest[1239:4047264] client: found peer: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:03.634 ThaliTest[1239:4047264] client: found peer: Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:03.638 ThaliTest[1239:4047264] client: found peer: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:05.540 ThaliTest[1239:4047377] jxcore: disconnect
2016-01-11 14:00:05.540 ThaliTest[1239:4047377] jxcore: disconnect: fail
2016-01-11T13:00:05.541Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
2,016-01-11T13:00:05.541Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
2016-01-11T13:00:05.541Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
2016-01-11T13:00:05.541Z SendDataConnector.js: do connect now
,2016-01-11 14:00:05.542 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:05.542 ThaliTest[1239:4047377] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
2016-01-11 14:00:05.542 ThaliTest[1239:4047377] jxcore: conne,ct: fail: Peer unreachable
2016-01-11T13:00:05.542Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-11T13:00:05.543Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T13:00:05.543Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:10.555Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.hXPtug==
,2016-01-11T13:00:10.555Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:15.342 ThaliTest[1239:4047264] multipeer session: reset timer
2016-01-11 14:00:15.342 ThaliTest[1239:4047264] multipeer session: stop timer
2016-01-11 14:00:15.342 ThaliTest[1239:4047264] multipeer session: start timer: 0x1948b180
2016-,01-11 14:00:15.343 ThaliTest[1239:4047264] server session: connect
2016-01-11 14:00:15.343 ThaliTest[1239:4047264] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-11 14:00:15.350 ThaliTest[1239:4047264] server: accepting invitation Apple-IpadAir2-1
,2016-01-11 14:00:15.559 ThaliTest[1239:4047377] jxcore: disconnect
2016-01-11 14:00:15.559 ThaliTest[1239:4047377] jxcore: disconnect: fail
,2016-01-11T13:00:15.560Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11T13:00:15.560Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.hXPtug== with availability status: true
,2016-01-11T13:00:15.561Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.hXPtug==
,2016-01-11T13:00:15.561Z SendDataConnector.js: do connect now
,2016-01-11 14:00:15.562 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:15.562 ThaliTest[1239:4047377] client: connect: unreachable Apple-Iphone5s-1.hXPtug==
,2016-01-11 14:00:15.563 ThaliTest[1239:4047377] jxcore: connect: fail: Peer unreachable
,2016-01-11T13:00:15.564Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-11T13:00:15.564Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-11T13:00:15.566Z SendDataConnector.js: CLIENT Stop now
,2016-01-11 14:00:15.566 ThaliTest[1239:4047377] jxcore: disconnect
,2016-01-11 14:00:15.567 ThaliTest[1239:4047377] jxcore: disconnect: fail
,2016-01-11T13:00:15.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.hXPtug==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.oW56/g==
,2016-01-11T13:00:15.570Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.oW56/g==
,2016-01-11T13:00:15.571Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.oW56/g==
,2016-01-11T13:00:15.571Z SendDataConnector.js: do connect now
,2016-01-11 14:00:15.572 ThaliTest[1239:4047377] jxcore: connect Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:15.572 ThaliTest[1239:4047377] client session: connect
,2016-01-11 14:00:15.573 ThaliTest[1239:4047377] client session: stateChange:0->1 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:20.135 ThaliTest[1239:4048066] server session: connected
,2016-01-11 14:00:20.135 ThaliTest[1239:4048066] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11 14:00:20.143 ThaliTest[1239:4048065] client session: connected
2016-01-11 14:00:20.144 ThaliTest[1239:4048065] client session: stateChange:1->2 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:20.148 ThaliTest[1239:4048065] client session: fireConnectCallback: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:20.148 ThaliTest[1239:4048065] jxcore: connect: success
,2016-01-11 14:00:20.149 ThaliTest[1239:4047264] server relay: connected (to port: 51027)
,2016-01-11T13:00:20.151Z SendDataTCPServer.js: TCP/IP server connected
2016-01-11T13:00:20.152Z SendDataConnector.js: CLIENT connected to 51032, error: null
2016-01-11T13:00:20.152Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:20.157 ThaliTest[1239:4047264] client: relay established
2016-01-11 14:00:20.158 ThaliTest[1239:4047264] client: new accepted socket: 0x19391ea0
,2016-01-11T13:00:20.172Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:21.259Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-11T13:00:21.293Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11T13:00:21.586Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:21.650Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11 14:00:21.767 ThaliTest[1239:4048065] server session: not connected Apple-IpadAir2-1
,2016-01-11T13:00:22.187Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:22.188Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:22.188Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:2,2.188Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 14:00:22.189 ThaliTest[1239:4047377] jxcore: disconnect
2016-01-11 14:00:22.189 ThaliTest[1239:4047377] client session: disconnectFromPeer: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:22.18,9 ThaliTest[1239:4047377] client session: disconnect
2016-01-11 14:00:22.190 ThaliTest[1239:4047377] client session: stateChange:2->0 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:22.208 ThaliTest[1239:4047377] jxcore: disconnect: success
2016-01-11T13:00:22.209Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.oW56/g==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5s-1.yPThEg==
2016-01-11T13:00:22.210Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:22.210Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:22.210Z SendDataConnect,or.js: do connect now
,2016-01-11 14:00:22.210 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:22.215 ThaliTest[1239:4047377] client session: connect
2016-01-11 14:00:22.215 ThaliTest[1239:4047377] client session: stateChange:0->1 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:22.623 ThaliTest[1239:4047264] multipeer session: reset timer
2016-01-11 14:00:22.624 ThaliTest[1239:4047264] multipeer session: stop timer
2016-01-11 14:00:22.624 ThaliTest[1239:4047264] multipeer session: start timer: 0x1948b180
2016-,01-11 14:00:22.624 ThaliTest[1239:4047264] server session: connect
2016-01-11 14:00:22.624 ThaliTest[1239:4047264] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-11 14:00:22.633 ThaliTest[1239:4047264] server: accepting invitation Apple-Iphone6-1
,2016-01-11 14:00:24.135 ThaliTest[1239:4047264] multipeer session: reset timer
2016-01-11 14:00:24.135 ThaliTest[1239:4047264] multipeer session: stop timer
2016-01-11 14:00:24.135 ThaliTest[1239:4047264] multipeer session: start timer: 0x1948b180
2016-01-11 14:00:24.136 ThaliTest[1239:4047264] server session: connect
2016-01-11 14:00:24.139 ThaliTest[1239:4047264] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-11 14:00:24.146 ThaliTest[1239:4047264] server: accepting invitation Apple-Iphone5s-1
,2016-01-11 14:00:25.243 ThaliTest[1239:4048066] client session: connected
,2016-01-11 14:00:25.244 ThaliTest[1239:4048066] client session: stateChange:1->2 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:25.248 ThaliTest[1239:4048066] client session: fireConnectCallback: Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:25.248 ThaliTest[1239:4048066] jxcore: connect: success
,2016-01-11T13:00:25.249Z SendDataConnector.js: CLIENT connected to 51035, error: null
2016-01-11T13:00:25.249Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:25.251 ThaliTest[1239:4047264] client: relay established
,2016-01-11 14:00:25.254 ThaliTest[1239:4047264] client: new accepted socket: 0x194a3cf0
,2016-01-11T13:00:25.263Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 14:00:25.375 ThaliTest[1239:4048092] server session: connected
,2016-01-11 14:00:25.376 ThaliTest[1239:4048092] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 14:00:25.379 ThaliTest[1239:4047264] server relay: connected (to port: 51027)
,2016-01-11T13:00:26.605Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:26.641Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-11T13:00:26.649Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:26.823 ThaliTest[1239:4048041] server session: not connected Apple-Iphone6-1
,2016-01-11T13:00:26.840Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T13:00:26.878Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-11T13:00:26.892Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-11T13:00:26.962Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-11T13:00:27.001Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:27.001Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T13:00:27.005Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:27.005Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:27.006 ThaliTest[1239:4047377] jxcore: disconnect
,2016-01-11 14:00:27.007 ThaliTest[1239:4047377] client session: disconnectFromPeer: Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:27.007 ThaliTest[1239:4047377] client session: disconnect
,2016-01-11 14:00:27.008 ThaliTest[1239:4047377] client session: stateChange:2->0 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:27.041 ThaliTest[1239:4048092] server session: connected
,2016-01-11 14:00:27.042 ThaliTest[1239:4048092] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 14:00:27.046 ThaliTest[1239:4047264] server relay: connected (to port: 51027)
,2016-01-11 14:00:27.082 ThaliTest[1239:4047377] jxcore: disconnect: success
,2016-01-11T13:00:27.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.yPThEg==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.085Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.085Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.085Z SendDataConnector.js: do connect now
,2016-01-11 14:00:27.086 ThaliTest[1239:4047377] jxcore: connect Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:27.087 ThaliTest[1239:4047377] client session: connect
,2016-01-11 14:00:27.087 ThaliTest[1239:4047377] client session: stateChange:0->1 Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.111Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:27.594Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-11T13:00:27.607Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-11T13:00:27.818Z SendDataTCPServer.js: TCP/IP server has received 37219 bytes of data
,2016-01-11T13:00:27.832Z SendDataTCPServer.js: TCP/IP server has received 66795 bytes of data
,2016-01-11T13:00:27.845Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-11T13:00:27.857Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-11T13:00:27.870Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-11T13:00:27.885Z SendDataTCPServer.js: TCP/IP server has received 82125 bytes of data
,2016-01-11T13:00:27.897Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-11T13:00:27.911Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2016-01-11T13:00:27.922Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:27.991 ThaliTest[1239:4048041] server session: not connected Apple-Iphone5s-1
,2016-01-11 14:00:30.053 ThaliTest[1239:4048092] client session: connected
2016-01-11 14:00:30.053 ThaliTest[1239:4048092] client session: stateChange:1->2 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:30.085 ThaliTest[1239:4048040] client session: fireConnectCallback: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:30.085 ThaliTest[1239:4048040] jxcore: connect: success
2016-01-11T13:00:30.092Z SendDataConnector.js: CLIENT connected to 51040, error: null
2016-01-11T13:00:30.092Z SendDataConnector.js: CLIENT starting client 
2016-01-11 14:00:30.095 ThaliTest[1239:4047264] client: relay established
2016-01-11 14:00:30.095 ThaliTest[1239:4047264] client: new accepted socket: 0x19399350
,2016-01-11T13:00:30.107Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:31.278Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T13:00:31.334Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-11T13:00:31.470Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T13:00:31.531Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:31.532Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T13:00:31.533Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:31.533Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:31.534 ThaliTest[1239:4047377] jxcore: disconnect
,2016-01-11 14:00:31.535 ThaliTest[1239:4047377] client session: disconnectFromPeer: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.536 ThaliTest[1239:4047377] client session: disconnect
,2016-01-11 14:00:31.536 ThaliTest[1239:4047377] client session: stateChange:2->0 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.612 ThaliTest[1239:4047377] jxcore: disconnect: success
2016-01-11T13:00:31.612Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.zQytdg==
---- round done--------
startWithNextDevice
weAreDoneNow, resultA,rray.length: 4
sendReportNow
done, now sending data to server
,2016-01-11T13:00:31.628Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:31.628Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-11 14:00:32.438 ThaliTest[1239:4047377] jxcore: stopBroadcasting
,2016-01-11 14:00:32.439 ThaliTest[1239:4047377] THEMultipeerSession stopping peer
,2016-01-11 14:00:32.439 ThaliTest[1239:4047377] multipeer session: stop timer
,2016-01-11 14:00:32.440 ThaliTest[1239:4047377] server session: disconnect
2016-01-11 14:00:32.440 ThaliTest[1239:4047377] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-11 14:00:33.154 ThaliTest[1239:4047377] server session: disconnect
2016-01-11 14:00:33.154 ThaliTest[1239:4047377] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-11 14:00:33.156 ThaliTest[1239:4047377] server session: disconnect
2016-,01-11 14:00:33.157 ThaliTest[1239:4047377] server session: stateChange:2->0 Apple-Iphone5s-1
2016-01-11 14:00:33.161 ThaliTest[1239:4047377] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
