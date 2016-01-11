#### Test 55613145dd493c6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3D70AA17-7676-4185-BF50-131CDABF8443/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3D70AA17-7676-4185-BF50-131CDABF8443/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A76EAF29-7214-4D74-884E-17D1A1CF4153/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52223"
,(lldb)     command script import "/tmp/3D70AA17-7676-4185-BF50-131CDABF8443/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 13:54:51.545 ThaliTest[1768:3777999] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C68C1EFF-76E4-4FD0-B5E6-3FD611C42D12/Library/Cookies/Cookies.binarycookies
,2016-01-11 13:54:51.983 ThaliTest[1768:3777999] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 13:54:51.984 ThaliTest[1768:3777999] Multi-tasking -> Device: YES, App: YES
,2016-01-11 13:54:51.993 ThaliTest[1768:3777999] Unlimited access to network resources
,2016-01-11 13:54:52.001 ThaliTest[1768:3777999] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 13:55:01.480 ThaliTest[1768:3777999] Resetting plugins due to page load.
,2016-01-11 13:55:05.383 ThaliTest[1768:3777999] Finished load of: file:///var/mobile/Containers/Bundle/Application/A76EAF29-7214-4D74-884E-17D1A1CF4153/ThaliTest.app/www/index.html
,2016-01-11 13:55:05.564 ThaliTest[1768:3777999] JXcore Cordova plugin initializing
,2016-01-11 13:55:05.564 ThaliTest[1768:3778229] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-11 13:55:06.681 ThaliTest[1768:3777999] THREAD WARNING: ['JXcore'] took '68.837891' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-11 13:59:33.366 ThaliTest[1768:3778229] jxcore: startBroadcasting
,2016-01-11 13:59:33.384 ThaliTest[1768:3778229] server: starting Apple-IpadAir2-1.xr446Q==
,2016-01-11 13:59:33.386 ThaliTest[1768:3778229] multipeer session: start timer: 0x19ca62f0
,2016-01-11 13:59:33.387 ThaliTest[1768:3778229] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-11 13:59:33.387 ThaliTest[1768:3778229] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-11 13:59:34.441 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5s-1.hXPtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.hXPtug==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-11 13:59:34.526 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5-1.b8hDBw==
,teardown
testFindPeers stopped
,2016-01-11 13:59:35.260 ThaliTest[1768:3778229] jxcore: stopBroadcasting
2016-01-11 13:59:35.260 ThaliTest[1768:3778229] THEMultipeerSession stopping peer
2016-01-11 13:59:35.260 ThaliTest[1768:3778229] multipeer session: stop timer
,2016-01-11 13:59:35.260 ThaliTest[1768:3778229] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 50157
,2016-01-11 13:59:35.268 ThaliTest[1768:3778229] jxcore: startBroadcasting
,2016-01-11 13:59:35.269 ThaliTest[1768:3778229] server: starting Apple-IpadAir2-1.oW56/g==
,2016-01-11 13:59:35.269 ThaliTest[1768:3778229] multipeer session: start timer: 0x19ca6a70
2016-01-11 13:59:35.269 ThaliTest[1768:3778229] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-11 13:59:35.269 ThaliTest[1768:3778229] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-11T12:59:35.274Z SendDataTCPServer.js: TCP/IP server is bound to port: 50157
,2016-01-11 13:59:35.277 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:35.277 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5s-1.hXPtug==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:35.279Z SendDataConnector.js:, Start called with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:35.279Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:35.279Z SendDataConnector.js: do connect now
2016-01-11 13:59:35.279 ThaliTest[1768:3777999] client: found peer: Apple-IpadAir2-1.xr446Q==
2016-01-11 13:59:35.279 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:35.279 ThaliTest[1768:3778229] client session: connect
2016-01-11 13:59:35.280 ThaliTest[1768:3778229] client session: stateChange:0->1 Apple-Iphone5-1.b8hDBw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client: lost peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client session: onPeerLost: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client: los,t peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client session: onPeerLost: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client session: onLinkFailure: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client session: disconnect
2016-01-11 13:59:36.531 ThaliTest[1768:3777999] client session: stateChange:1->0 Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.532 ThaliTest[1768:3777999] client session: fireConnectCallback: App,le-Iphone5-1.b8hDBw==
2016-01-11 13:59:36.532 ThaliTest[1768:3777999] jxcore: connect: fail: Peer disconnected
2016-01-11 13:59:36.532 ThaliTest[1768:3777999] client: lost peer: Apple-IpadAir2-1.xr446Q==
2016-01-11 13:59:36.532 ThaliTest[1768:3777999] client session: onPeerLost: Apple-IpadAir2-1.xr446Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11T12:59:36.533Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-11T12:59:36.533Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-11T12:59:36.534Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-11 13:59:36.539 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5-1.03CIBg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.03CIBg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:36.638 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5s-1.yPThEg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.yPThEg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:37.072 ThaliTest[1768:3777999] client: found peer: Apple-Iphone6-1.zQytdg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.zQytdg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11T12:59:41.537Z SendDataConnector.js: re-try now : Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:41.537Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:46.547 ThaliTest[1768:3778229] jxcore: disconnect
2016-01-11 13:59:46.547 ThaliTest[1768:3778229] jxcore: disconnect: fail
,2016-01-11T12:59:46.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:46.548Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.b8hDBw== with availability status: true
2016-01-,11T12:59:46.548Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:46.548Z SendDataConnector.js: do connect now
2016-01-11 13:59:46.548 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:46.548 ThaliTest[1768:3778229] client: connect: unreachable Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:46.548 ThaliTest[1768:3778229] jxcore: connect: fail: Peer unreachable
,2016-01-11T12:59:46.548Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:46.549Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T12:59:46.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T12:59:51.554Z SendDataConnector.js: re-try now : Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:51.554Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:56.559 ThaliTest[1768:3778229] jxcore: disconnect
,2016-01-11 13:59:56.559 ThaliTest[1768:3778229] jxcore: disconnect: fail
,2016-01-11T12:59:56.560Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T12:59:56.560Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.b8hDBw== with availability status: true
2016-01-,11T12:59:56.560Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.b8hDBw==
,2016-01-11T12:59:56.560Z SendDataConnector.js: do connect now
,2016-01-11 13:59:56.560 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:56.561 ThaliTest[1768:3778229] client: connect: unreachable Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:56.561 ThaliTest[1768:3778229] jxcore: connect,: fail: Peer unreachable
2016-01-11T12:59:56.561Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:56.561Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T12:59:56.561Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:01.562Z SendDataConnector.js: re-try now : Apple-Iphone5-1.b8hDBw==
,2016-01-11T13:00:01.562Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.b8hDBw==
,2016-01-11 14:00:05.270 ThaliTest[1768:3777999] multipeer session: restart
,2016-01-11 14:00:05.280 ThaliTest[1768:3777999] client: found peer: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:05.281 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:05.282 ThaliTest[1768:3777999] client: found peer: Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:06.572 ThaliTest[1768:3778229] jxcore: disconnect
2016-01-11 14:00:06.572 ThaliTest[1768:3778229] jxcore: disconnect: fail
2016-01-11T13:00:06.572Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.b8hDBw==
20,16-01-11T13:00:06.573Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.b8hDBw== with availability status: true
2016-01-11T13:00:06.573Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T13:00:06.573Z SendDataConnector.js: do connect now
2016-01-11 14:00:06.573 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.b8hDBw==
2016-01-11 14:00:06.573 ThaliTest[1768:3778229] client: connect: unreachable Apple-Iphone5-1.b8hDBw==
2016-01-11 14:00:06.573 ThaliTest[1768:3778229] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:06.573Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:06.573Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-,01-11T13:00:06.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:11.574Z SendDataConnector.js: re-try now : Apple-Iphone5-1.b8hDBw==
2016-01-11T13:00:11.575Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.b8hDBw==
,2016-01-11 14:00:16.580 ThaliTest[1768:3778229] jxcore: disconnect
2016-01-11 14:00:16.580 ThaliTest[1768:3778229] jxcore: disconnect: fail
2016-01-11T13:00:16.580Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.b8hDBw==
20,16-01-11T13:00:16.580Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.b8hDBw== with availability status: true
2016-01-11T13:00:16.580Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.b8hDBw==
2016-01-11T13:00:16.58,0Z SendDataConnector.js: do connect now
2016-01-11 14:00:16.580 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.b8hDBw==
2016-01-11 14:00:16.581 ThaliTest[1768:3778229] client: connect: unreachable Apple-Iphone5-1.b8hDBw==
2016-01-11 14:00:16.58,1 ThaliTest[1768:3778229] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:16.581Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:16.581Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRo,undDownNow
,2016-01-11T13:00:16.582Z SendDataConnector.js: CLIENT Stop now
,2016-01-11 14:00:16.583 ThaliTest[1768:3778229] jxcore: disconnect
2016-01-11 14:00:16.583 ThaliTest[1768:3778229] jxcore: disconnect: fail
2016-01-11T13:00:16.583Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.b8hDBw==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5-1.03CIBg==
2016-01-11T13:00:16.584Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.03CIBg==
2016-01-11T13:00:16.584Z SendDataConnector.js: doConnect called with peer Apple,-Iphone5-1.03CIBg==
2016-01-11T13:00:16.584Z SendDataConnector.js: do connect now
2016-01-11 14:00:16.584 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:16.584 ThaliTest[1768:3778229] client session: connect
2016-01-11 14:00:16.584 ThaliTest[1768:3778229] client session: stateChange:0->1 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:17.494 ThaliTest[1768:3777999] multipeer session: reset timer
2016-01-11 14:00:17.494 ThaliTest[1768:3777999] multipeer session: stop timer
2016-01-11 14:00:17.494 ThaliTest[1768:3777999] multipeer session: start timer: 0x19ca6a70
2016-01-11 14:00:17.494 ThaliTest[1768:3777999] server session: connect
2016-01-11 14:00:17.494 ThaliTest[1768:3777999] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-11 14:00:17.497 ThaliTest[1768:3777999] server: accepting invitation Apple-Iphone5,-1
,2016-01-11 14:00:18.422 ThaliTest[1768:3777999] multipeer session: reset timer
2016-01-11 14:00:18.422 ThaliTest[1768:3777999] multipeer session: stop timer
2016-01-11 14:00:18.422 ThaliTest[1768:3777999] multipeer session: start timer: 0x19ca6a70
,2016-01-11 14:00:18.422 ThaliTest[1768:3777999] server session: connect
2016-01-11 14:00:18.422 ThaliTest[1768:3777999] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-11 14:00:18.426 ThaliTest[1768:3777999] server: accepting invitation Apple-Iphone6-1
,2016-01-11 14:00:21.826 ThaliTest[1768:3778764] client session: connected
2016-01-11 14:00:21.826 ThaliTest[1768:3778764] client session: stateChange:1->2 Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:21.827 ThaliTest[1768:3778790] server session: connected
,2016-01-11 14:00:21.828 ThaliTest[1768:3778790] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 14:00:21.832 ThaliTest[1768:3777999] multipeer session: reset timer
2016-01-11 14:00:21.832 ThaliTest[1768:3777999] multipeer session: stop timer
2016-01-11 14:00:21.832 ThaliTest[1768:3777999] multipeer session: start timer: 0x19ca6a70
2016-,01-11 14:00:21.832 ThaliTest[1768:3777999] server session: connect
2016-01-11 14:00:21.833 ThaliTest[1768:3777999] server session: stateChange:0->1 Apple-Iphone5s-1
2016-01-11 14:00:21.834 ThaliTest[1768:3777999] server: accepting invitation Apple-Iphone5s-1
,2016-01-11 14:00:21.893 ThaliTest[1768:3778790] client session: fireConnectCallback: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:21.893 ThaliTest[1768:3778790] jxcore: connect: success
2016-01-11T13:00:21.894Z SendDataConnector.js: CLIENT connected to 50162, error: null
2016-01-11T13:00:21.894Z SendDataConnector.js: CLIENT starting client 
2016-01-11 14:00:21.895 ThaliTest[1768:3777999] client: relay established
2016-01-11 14:00:21.895 ThaliTest[1768:3777999] client: new accepted socket: 0x17fd4e00
2016-01-11 14:00:21.896 ThaliTest[1768:3777999] server relay: connected (to port: 50157)
,2016-01-11T13:00:21.909Z SendDataTCPServer.js: TCP/IP server connected
2016-01-11T13:00:21.909Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 14:00:22.164 ThaliTest[1768:3778825] server session: connected
2016-01-11 14:00:22.164 ThaliTest[1768:3778825] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 14:00:22.348 ThaliTest[1768:3777999] server relay: connected (to port: 50157)
,2016-01-11T13:00:22.352Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:22.949Z SendDataTCPServer.js: TCP/IP server has received 20805 bytes of data
,2016-01-11T13:00:22.973Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-11T13:00:22.997Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-11T13:00:23.011Z SendDataTCPServer.js: TCP/IP server has received 69916 bytes of data
,2016-01-11T13:00:23.012Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-11T13:00:23.071Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11T13:00:23.207Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T13:00:23.220Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:23.221Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-11 14:00:23.326 ThaliTest[1768:3778764] server session: not connected Apple-Iphone6-1
,2016-01-11T13:00:23.333Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-11T13:00:23.334Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:23.334Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:23.334Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:23.334Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:23.335 ThaliTest[1768:3778229] jxcore: disconnect
,2016-01-11 14:00:23.335 ThaliTest[1768:3778229] client session: disconnectFromPeer: Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:23.335 ThaliTest[1768:3778229] client session: disconnect
,2016-01-11 14:00:23.335 ThaliTest[1768:3778229] client session: stateChange:2->0 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:23.339 ThaliTest[1768:3778229] jxcore: disconnect: success
2016-01-11T13:00:23.339Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.03CIBg==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:23.340Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:23.340Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.yPThEg==
2016-01-11T13:00:23.340Z SendDataConnector.js: do connect now
,2016-01-11 14:00:23.341 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:23.341 ThaliTest[1768:3778229] client session: connect
,2016-01-11 14:00:23.341 ThaliTest[1768:3778229] client session: stateChange:0->1 Apple-Iphone5s-1.yPThEg==
,2016-01-11T13:00:23.861Z SendDataTCPServer.js: TCP/IP server has received 95194 bytes of data
,2016-01-11T13:00:23.874Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:23.972 ThaliTest[1768:3778817] server session: not connected Apple-Iphone5-1
,2016-01-11 14:00:24.902 ThaliTest[1768:3778764] server session: connected
2016-01-11 14:00:24.902 ThaliTest[1768:3778764] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 14:00:24.912 ThaliTest[1768:3777999] server relay: connected (to port: 50157)
,2016-01-11T13:00:24.916Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:25.360Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-11T13:00:25.372Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-11T13:00:25.384Z SendDataTCPServer.js: TCP/IP server has received 42705 bytes of data
,2016-01-11T13:00:25.396Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-11T13:00:25.409Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-11T13:00:25.420Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-11T13:00:25.433Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:25.451 ThaliTest[1768:3778766] server session: not connected Apple-Iphone5s-1
,2016-01-11 14:00:26.600 ThaliTest[1768:3778766] client session: connected
2016-01-11 14:00:26.600 ThaliTest[1768:3778766] client session: stateChange:1->2 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:26.609 ThaliTest[1768:3778766] client session: fireConnectCallback: Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:26.610 ThaliTest[1768:3778766] jxcore: connect: success
2016-01-11T13:00:26.610Z SendDataConnector.js: CLIENT connected to 50168, error: null
2016-01-11T13:00:26.610Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:26.611 ThaliTest[1768:3777999] client: relay established
2016-01-11 14:00:26.611 ThaliTest[1768:3777999] client: new accepted socket: 0x19cc0f80
,2016-01-11T13:00:26.624Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:27.140Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T13:00:27.226Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:27.262Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:27.262Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T13:00:27.263Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:27.263Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:27.263 ThaliTest[1768:3778229] jxcore: disconnect
2016-01-11 14:00:27.263 ThaliTest[1768:3778229] client session: disconnectFromPeer: Apple-Iphone5s-1.yPThEg==
2016-01-11 14:00:27.263 ThaliTest[1768:3778229] client session: disconnect
2016-01-11 14:00:27.264 ThaliTest[1768:3778229] client session: stateChange:2->0 Apple-Iphone5s-1.yPThEg==
,2016-01-11 14:00:27.267 ThaliTest[1768:3778229] jxcore: disconnect: success
2016-01-11T13:00:27.268Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.yPThEg==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one6-1.zQytdg==
2016-01-11T13:00:27.268Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.zQytdg==
2016-01-11T13:00:27.268Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.zQytdg==
2016-01-11T13:00:27.268Z SendDataConnector.,js: do connect now
2016-01-11 14:00:27.268 ThaliTest[1768:3778229] jxcore: connect Apple-Iphone6-1.zQytdg==
2016-01-11 14:00:27.268 ThaliTest[1768:3778229] client session: connect
2016-01-11 14:00:27.269 ThaliTest[1768:3778229] client session: stateChange:0->1 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:30.470 ThaliTest[1768:3778764] client session: connected
2016-01-11 14:00:30.470 ThaliTest[1768:3778764] client session: stateChange:1->2 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:30.479 ThaliTest[1768:3778766] client session: fireConnectCallback: Apple-Iphone6-1.zQytdg==
2016-01-11 14:00:30.479 ThaliTest[1768:3778766] jxcore: connect: success
2016-01-11T13:00:30.479Z SendDataConnector.js: CLIENT connected to 50171, error: null
2016-01-11T13:00:30.479Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:30.480 ThaliTest[1768:3777999] client: relay established
2016-01-11 14:00:30.480 ThaliTest[1768:3777999] client: new accepted socket: 0x19cb61a0
,2016-01-11T13:00:30.493Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:30.939Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-11T13:00:30.965Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:31.002Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:31.002Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T13:00:31.003Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:31.003Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 14:00:31.003 ThaliTest[1768:3778229] jxcore: disconnect
,2016-01-11 14:00:31.003 ThaliTest[1768:3778229] client session: disconnectFromPeer: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.004 ThaliTest[1768:3778229] client session: disconnect
,2016-01-11 14:00:31.004 ThaliTest[1768:3778229] client session: stateChange:2->0 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.067 ThaliTest[1768:3778229] jxcore: disconnect: success
,2016-01-11T13:00:31.067Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.zQytdg==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-11T13:00:31.077Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:31.078Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-11 14:00:33.940 ThaliTest[1768:3778229] jxcore: stopBroadcasting
2016-01-11 14:00:33.940 ThaliTest[1768:3778229] THEMultipeerSession stopping peer
2016-01-11 14:00:33.940 ThaliTest[1768:3778229] multipeer session: stop timer
,2016-01-11 14:00:33.941 ThaliTest[1768:3778229] server session: disconnect
2016-01-11 14:00:33.941 ThaliTest[1768:3778229] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-11 14:00:33.943 ThaliTest[1768:3778229] server session: disconnect
2016-01-11 14:00:33.943 ThaliTest[1768:3778229] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-11 14:00:33.949 ThaliTest[1768:3778229] server session: disconnect
2016-01-11 14:00:33.949 ThaliTest[1768:3778229] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-11 14:00:33.951 ThaliTest[1768:3778229] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
