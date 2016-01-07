#### Test 5531115118861c0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D01EA296-50DD-4A3D-8DF8-E08A36B40781/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D01EA296-50DD-4A3D-8DF8-E08A36B40781/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D301C2EE-A6D9-439C-91BA-1869E26CBB8F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49605"
,(lldb)     command script import "/tmp/D01EA296-50DD-4A3D-8DF8-E08A36B40781/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 10:42:32.223 ThaliTest[1451:3150885] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/26D74DE1-7FC1-4B1E-8083-5BCDB338599C/Library/Cookies/Cookies.binarycookies
,2016-01-07 10:42:32.601 ThaliTest[1451:3150885] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 10:42:32.602 ThaliTest[1451:3150885] Multi-tasking -> Device: YES, App: YES
,2016-01-07 10:42:32.612 ThaliTest[1451:3150885] Unlimited access to network resources
,2016-01-07 10:42:32.624 ThaliTest[1451:3150885] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 10:42:41.231 ThaliTest[1451:3150885] Resetting plugins due to page load.
,2016-01-07 10:42:44.805 ThaliTest[1451:3150885] Finished load of: file:///var/mobile/Containers/Bundle/Application/D301C2EE-A6D9-439C-91BA-1869E26CBB8F/ThaliTest.app/www/index.html
,2016-01-07 10:42:44.979 ThaliTest[1451:3150885] JXcore Cordova plugin initializing
,2016-01-07 10:42:44.980 ThaliTest[1451:3151119] JXcore instance initializing
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
,2016-01-07 10:42:45.957 ThaliTest[1451:3150885] THREAD WARNING: ['JXcore'] took '70.698975' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 10:47:32.208 ThaliTest[1451:3151119] jxcore: startBroadcasting
,2016-01-07 10:47:32.225 ThaliTest[1451:3151119] server: starting Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:32.226 ThaliTest[1451:3151119] multipeer session: start timer: 0x185c25a0
,2016-01-07 10:47:32.227 ThaliTest[1451:3151119] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-07 10:47:32.228 ThaliTest[1451:3151119] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-07 10:47:32.728 ThaliTest[1451:3150885] client: found peer: Apple-IpadAir2-1.LQugrg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.LQugrg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1.LQugrg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-07 10:47:33.269 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5-1.kLcgag==
,2016-01-07 10:47:33.334 ThaliTest[1451:3150885] client: found peer: Apple-Iphone6-1.W/Fi/g==
,teardown
,testFindPeers stopped
,2016-01-07 10:47:35.707 ThaliTest[1451:3151119] jxcore: stopBroadcasting
,2016-01-07 10:47:35.707 ThaliTest[1451:3151119] THEMultipeerSession stopping peer
2016-01-07 10:47:35.708 ThaliTest[1451:3151119] multipeer session: stop timer
,2016-01-07 10:47:35.709 ThaliTest[1451:3151119] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64391
,2016-01-07 10:47:35.743 ThaliTest[1451:3151119] jxcore: startBroadcasting
,2016-01-07 10:47:35.746 ThaliTest[1451:3151119] server: starting Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:47:35.747 ThaliTest[1451:3151119] multipeer session: start timer: 0x16623090
,2016-01-07 10:47:35.748 ThaliTest[1451:3151119] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-07 10:47:35.748 ThaliTest[1451:3151119] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-07T09:47:35.755Z SendDataTCPServer.js: TCP/IP server is bound to port: 64391
,2016-01-07 10:47:35.775 ThaliTest[1451:3150885] client: found peer: Apple-IpadAir2-1.LQugrg==
2016-01-07 10:47:35.775 ThaliTest[1451:3150885] client: found peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.776 ThaliTest[1451:3150885] client: found peer: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:35.776 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.LQugrg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:35.780Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:35.781Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:35.781Z SendDataConnector.js: do connect now
,2016-01-07 10:47:35.782 ThaliTest[1451:3151119] jxcore: connect Apple-IpadAir2-1.LQugrg==
2016-01-07 10:47:35.782 ThaliTest[1451:3151119] client session: connect
2016-01-07 10:47:35.783 ThaliTest[1451:3151119] client session: stateChange:0->1 Apple-IpadAir2-1.LQugrg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:37.135 ThaliTest[1451:3150885] client: lost peer: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:37.136 ThaliTest[1451:3150885] client session: onPeerLost: Apple-Iphone6-1.W/Fi/g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-07 10:47:37.419 ThaliTest[1451:3150885] client: lost peer: Apple-Iphone5-1.kLcgag==
2016-01-07 10:47:37.420 ThaliTest[1451:3150885] client session: onPeerLost: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-07 10:47:37.481 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5s-1.Waegsg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:37.753 ThaliTest[1451:3150885] client: lost peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:37.754 ThaliTest[1451:3150885] client session: onPeerLost: Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:37.754 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5-1.XzilZw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.XzilZw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-07 10:47:38.131 ThaliTest[1451:3150885] client: found peer: Apple-Iphone6-1.Uf4Y7g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.Uf4Y7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:47.637 ThaliTest[1451:3150885] client: lost peer: Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:47:47.637 ThaliTest[1451:3150885] client session: onPeerLost: Apple-IpadAir2-1.LQugrg==
2016-01-07 10:47:47.637 ThaliTest[1451:3150885] client session: onLinkFailure: Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:47:47.638 ThaliTest[1451:3150885] client session: disconnect
2016-01-07 10:47:47.638 ThaliTest[1451:3150885] client session: stateChange:1->0 Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:47:47.638 ThaliTest[1451:3150885] client session: fireConnectCallback: Apple-IpadAir2-1.LQugrg==
2016-01-07 10:47:47.639 ThaliTest[1451:3150885] jxcore: connect: fail: Peer disconnected
,2016-01-07T09:47:47.640Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-07T09:47:47.641Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-07T09:47:47.642Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.LQugrg==","peerName":"(null)","peerAvailable":false}]
,2016-01-07T09:47:52.651Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:52.652Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:47:57.663 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:47:57.663 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:47:57.664Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:57.665Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.LQugrg== with availability status: true
,2016-01-07T09:47:57.665Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:47:57.666Z SendDataConnector.js: do connect now
,2016-01-07 10:47:57.667 ThaliTest[1451:3151119] jxcore: connect Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:47:57.667 ThaliTest[1451:3151119] client: connect: unreachable Apple-IpadAir2-1.LQugrg==
2016-01-07 10:47:57.668 ThaliTest[1451:3151119] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:47:57.669Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-07T09:47:57.669Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-07T09:47:57.670Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:02.678Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:02.678Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:05.749 ThaliTest[1451:3150885] multipeer session: restart
,2016-01-07 10:48:05.777 ThaliTest[1451:3150885] client: found peer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:05.777 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:05.780 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:07.686 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:07.687 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:48:07.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.LQugrg==
2016-01-07T09:48:07.688Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.LQugrg== with availability status: true
2016-01-07T09:48:07.688Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:07.689Z SendDataConnector.js: do connect now
,2016-01-07 10:48:07.690 ThaliTest[1451:3151119] jxcore: connect Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:07.690 ThaliTest[1451:3151119] client: connect: unreachable Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:07.691 ThaliTest[1451:3151119] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:48:07.691Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-07T09:48:07.693Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-07T09:48:07.693Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:12.699Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:12.700Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:17.705 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:17.706 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:48:17.707Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:17.708Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.LQugrg== with availability status: true
,2016-01-07T09:48:17.709Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:17.709Z SendDataConnector.js: do connect now
,2016-01-07 10:48:17.710 ThaliTest[1451:3151119] jxcore: connect Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:17.711 ThaliTest[1451:3151119] client: connect: unreachable Apple-IpadAir2-1.LQugrg==
2016-01-07 10:48:17.711 ThaliTest[1451:3151119] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:48:17.712Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-07T09:48:17.712Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-07T09:48:17.713Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:22.714Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:22.714Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:27.727 ThaliTest[1451:3151119] jxcore: disconnect
2016-01-07 10:48:27.728 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:48:27.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:27.729Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.LQugrg== with availability status: true
,2016-01-07T09:48:27.729Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.LQugrg==
,2016-01-07T09:48:27.729Z SendDataConnector.js: do connect now
,2016-01-07 10:48:27.731 ThaliTest[1451:3151119] jxcore: connect Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:27.731 ThaliTest[1451:3151119] client: connect: unreachable Apple-IpadAir2-1.LQugrg==
,2016-01-07 10:48:27.732 ThaliTest[1451:3151119] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:48:27.732Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-07T09:48:27.733Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-07T09:48:27.735Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 10:48:27.736 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:27.736 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:48:27.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.LQugrg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:27.741Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:27.741Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:27.742Z SendDataConnector.js: do connect now
,2016-01-07 10:48:27.743 ThaliTest[1451:3151119] jxcore: connect Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:27.743 ThaliTest[1451:3151119] client session: connect
,2016-01-07 10:48:27.744 ThaliTest[1451:3151119] client session: stateChange:0->1 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:28.508 ThaliTest[1451:3150885] multipeer session: reset timer
2016-01-07 10:48:28.508 ThaliTest[1451:3150885] multipeer session: stop timer
,2016-01-07 10:48:28.508 ThaliTest[1451:3150885] multipeer session: start timer: 0x16623090
2016-01-07 10:48:28.509 ThaliTest[1451:3150885] server session: connect
,2016-01-07 10:48:28.509 ThaliTest[1451:3150885] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-07 10:48:28.516 ThaliTest[1451:3150885] server: accepting invitation Apple-Iphone5-1
,2016-01-07 10:48:31.512 ThaliTest[1451:3150885] client: lost peer: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:31.513 ThaliTest[1451:3150885] client session: onPeerLost: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:31.513 ThaliTest[1451:3150885] client sess,ion: onLinkFailure: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:31.513 ThaliTest[1451:3150885] client session: disconnect
2016-01-07 10:48:31.513 ThaliTest[1451:3150885] client session: stateChange:1->0 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:31.514 ThaliTest[1451:3150885] client session: fireConnectCallback: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:31.514 ThaliTest[1451:3150885] jxcore: connect: fail: Peer disconnected
,2016-01-07T09:48:31.515Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-07T09:48:31.516Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-07T09:48:31.517Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg==","peerName":"(null)","peerAvailable":false}]
,2016-01-07 10:48:31.768 ThaliTest[1451:3151827] server session: connected
2016-01-07 10:48:31.769 ThaliTest[1451:3151827] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-07 10:48:31.776 ThaliTest[1451:3150885] server relay: connected (to port: 64391)
2016-01-07T09:48:31.777Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07 10:48:32.511 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5s-1.Waegsg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg==","peerName":"(null)","peerAvailable":true}]
,2016-01-07 10:48:32.632 ThaliTest[1451:3150885] multipeer session: reset timer
2016-01-07 10:48:32.632 ThaliTest[1451:3150885] multipeer session: stop timer
2016-01-07 10:48:32.633 ThaliTest[1451:3150885] multipeer session: start timer: 0x16623090
,2016-01-07 10:48:32.633 ThaliTest[1451:3150885] server session: connect
2016-01-07 10:48:32.633 ThaliTest[1451:3150885] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-07 10:48:32.640 ThaliTest[1451:3150885] server: accepting invitation Apple-Iphone5s-1
,2016-01-07T09:48:33.026Z SendDataTCPServer.js: TCP/IP server has received 16283 bytes of data
,2016-01-07T09:48:33.038Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-07T09:48:33.052Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-07T09:48:33.088Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-07T09:48:33.101Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:33.625 ThaliTest[1451:3151803] server session: not connected Apple-Iphone5-1
,2016-01-07T09:48:36.529Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:36.529Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:39.970 ThaliTest[1451:3150885] multipeer session: reset timer
2016-01-07 10:48:39.971 ThaliTest[1451:3150885] multipeer session: stop timer
,2016-01-07 10:48:39.971 ThaliTest[1451:3150885] multipeer session: start timer: 0x16623090
,2016-01-07 10:48:39.971 ThaliTest[1451:3150885] server: disconnecting to refresh session (Apple-Iphone5s-1)
2016-01-07 10:48:39.972 ThaliTest[1451:3150885] server session: disconnect
,2016-01-07 10:48:39.972 ThaliTest[1451:3150885] server session: stateChange:1->0 Apple-Iphone5s-1
,2016-01-07 10:48:39.977 ThaliTest[1451:3150885] server session: connect
2016-01-07 10:48:39.978 ThaliTest[1451:3150885] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-07 10:48:39.986 ThaliTest[1451:3150885] server: accepting invitation Apple-Iphone5s-1
,2016-01-07 10:48:41.531 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:41.532 ThaliTest[1451:3151119] jxcore: disconnect: fail
,2016-01-07T09:48:41.533Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:41.534Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.Waegsg== with availability status: true
,2016-01-07T09:48:41.534Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Waegsg==
,2016-01-07T09:48:41.535Z SendDataConnector.js: do connect now
,2016-01-07 10:48:41.536 ThaliTest[1451:3151119] jxcore: connect Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:41.537 ThaliTest[1451:3151119] client session: connect
,2016-01-07 10:48:41.537 ThaliTest[1451:3151119] client session: stateChange:0->1 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:43.651 ThaliTest[1451:3151800] server session: connected
,2016-01-07 10:48:43.651 ThaliTest[1451:3151800] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-07 10:48:43.672 ThaliTest[1451:3150885] server relay: connected (to port: 64391)
,2016-01-07T09:48:43.677Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:44.169Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-07T09:48:44.183Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-07T09:48:44.200Z SendDataTCPServer.js: TCP/IP server has received 42705 bytes of data
,2016-01-07T09:48:44.214Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-07T09:48:44.231Z SendDataTCPServer.js: TCP/IP server has received 78769 bytes of data
,2016-01-07T09:48:44.248Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:44.283 ThaliTest[1451:3151838] server session: not connected Apple-Iphone5s-1
,2016-01-07 10:48:45.678 ThaliTest[1451:3151838] client session: connected
2016-01-07 10:48:45.679 ThaliTest[1451:3151838] client session: stateChange:1->2 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:45.721 ThaliTest[1451:3151800] client session: fireConnectCallback: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:45.721 ThaliTest[1451:3151800] jxcore: connect: success
,2016-01-07T09:48:45.722Z SendDataConnector.js: CLIENT connected to 64398, error: null
,2016-01-07T09:48:45.723Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:45.725 ThaliTest[1451:3150885] client: relay established
2016-01-07 10:48:45.726 ThaliTest[1451:3150885] client: new accepted socket: 0x185d0c90
,2016-01-07T09:48:45.740Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:46.273Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-07T09:48:46.335Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-07T09:48:46.348Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-07T09:48:46.383Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-07T09:48:46.393Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-07T09:48:46.664Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-07T09:48:46.664Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-07T09:48:46.666Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:46.666Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:46.668 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:46.669 ThaliTest[1451:3151119] client session: disconnectFromPeer: Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:46.670 ThaliTest[1451:3151119] client session: disconnect
,2016-01-07 10:48:46.670 ThaliTest[1451:3151119] client session: stateChange:2->0 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:46.681 ThaliTest[1451:3151119] jxcore: disconnect: success
2016-01-07T09:48:46.681Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Waegsg==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5-1.XzilZw==
2016-01-07T09:48:46.683Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.XzilZw==
2016-01-07T09:48:46.683Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.XzilZw==
2016-01-07T09:48:46.683Z SendDataConnector.,js: do connect now
2016-01-07 10:48:46.684 ThaliTest[1451:3151119] jxcore: connect Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:46.684 ThaliTest[1451:3151119] client session: connect
,2016-01-07 10:48:46.685 ThaliTest[1451:3151119] client session: stateChange:0->1 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:50.141 ThaliTest[1451:3151839] client session: connected
2016-01-07 10:48:50.141 ThaliTest[1451:3151839] client session: stateChange:1->2 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:50.157 ThaliTest[1451:3151800] client session: fireConnectCallback: Apple-Iphone5-1.XzilZw==
2016-01-07 10:48:50.157 ThaliTest[1451:3151800] jxcore: connect: success
,2016-01-07T09:48:50.159Z SendDataConnector.js: CLIENT connected to 64401, error: null
,2016-01-07T09:48:50.159Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:50.162 ThaliTest[1451:3150885] client: relay established
2016-01-07 10:48:50.162 ThaliTest[1451:3150885] client: new accepted socket: 0x16606280
,2016-01-07T09:48:50.175Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:50.653Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-07T09:48:50.666Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-07T09:48:50.688Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-07T09:48:50.712Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-07T09:48:50.725Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-07T09:48:50.725Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-07T09:48:50.725Z SendDataConnector.js: CLIENT Stop now
2016-01-07T09:48:50.725Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:50.726 ThaliTest[1451:3151119] jxcore: disconnect
,2016-01-07 10:48:50.726 ThaliTest[1451:3151119] client session: disconnectFromPeer: Apple-Iphone5-1.XzilZw==
2016-01-07 10:48:50.726 ThaliTest[1451:3151119] client session: disconnect
,2016-01-07 10:48:50.726 ThaliTest[1451:3151119] client session: stateChange:2->0 Apple-Iphone5-1.XzilZw==
,2016-01-07 10:48:50.787 ThaliTest[1451:3151119] jxcore: disconnect: success
2016-01-07T09:48:50.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.XzilZw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:50.788Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:50.788Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:50.788Z SendDataConnector.js: do connect now
,2016-01-07 10:48:50.789 ThaliTest[1451:3151119] jxcore: connect Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:50.789 ThaliTest[1451:3151119] client session: connect
,2016-01-07 10:48:50.789 ThaliTest[1451:3151119] client session: stateChange:0->1 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:54.132 ThaliTest[1451:3151827] client session: connected
2016-01-07 10:48:54.132 ThaliTest[1451:3151827] client session: stateChange:1->2 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:54.137 ThaliTest[1451:3151827] client session: fireConnectCallback: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:54.137 ThaliTest[1451:3151827] jxcore: connect: success
,2016-01-07T09:48:54.138Z SendDataConnector.js: CLIENT connected to 64404, error: null
,2016-01-07T09:48:54.139Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:54.142 ThaliTest[1451:3150885] client: relay established
,2016-01-07 10:48:54.143 ThaliTest[1451:3150885] client: new accepted socket: 0x16610d00
,2016-01-07T09:48:54.155Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:54.727Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-07T09:48:54.849Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-07T09:48:54.849Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-07T09:48:54.849Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:54.850Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-07 10:48:54.850 ThaliTest[1451:3151119] jxcore: disconnect
2016-01-07 10:48:54.850 ThaliTest[1451:3151119] client session: disconnectFromPeer: Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:54.850 ThaliTest[1451:3151119] client session: disconnect
,2016-01-07 10:48:54.851 ThaliTest[1451:3151119] client session: stateChange:2->0 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:54.854 ThaliTest[1451:3151119] jxcore: disconnect: success
2016-01-07T09:48:54.854Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.Uf4Y7g==
,---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2016-01-07T09:48:54.865Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:54.865Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:49:09.973 ThaliTest[1451:3150885] multipeer session: restart
,2016-01-07 10:49:10.001 ThaliTest[1451:3150885] client: found peer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:49:10.001 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5-1.XzilZw==
2016-01-07 10:49:10.001 ThaliTest[1451:3150885] client: found peer: Apple-Iphone5s-1.Waegsg==
,teardown
,testSendData stopped
,2016-01-07 10:49:16.005 ThaliTest[1451:3151119] jxcore: stopBroadcasting
,2016-01-07 10:49:16.005 ThaliTest[1451:3151119] THEMultipeerSession stopping peer
,2016-01-07 10:49:16.006 ThaliTest[1451:3151119] multipeer session: stop timer
,2016-01-07 10:49:16.007 ThaliTest[1451:3151119] server session: disconnect
2016-01-07 10:49:16.008 ThaliTest[1451:3151119] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-07 10:49:16.020 ThaliTest[1451:3151119] server session: disconnect
2016-01-07 10:49:16.021 ThaliTest[1451:3151119] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-07 10:49:16.034 ThaliTest[1451:3151119] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
