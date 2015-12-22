#### Test 543122982543be8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3430F96A-C14E-4CF2-AF2D-D568554D4861/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3430F96A-C14E-4CF2-AF2D-D568554D4861/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C7319A1A-4976-46FF-AC38-485BCD96ABB6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62004"
,(lldb)     command script import "/tmp/3430F96A-C14E-4CF2-AF2D-D568554D4861/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-22 01:49:36.034 ThaliTest[698:838908] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B38E1DF3-F2F4-41D8-89DA-414D6592410C/Library/Cookies/Cookies.binarycookies
,2015-12-22 01:49:36.404 ThaliTest[698:838908] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-22 01:49:36.405 ThaliTest[698:838908] Multi-tasking -> Device: YES, App: YES
,2015-12-22 01:49:36.414 ThaliTest[698:838908] Unlimited access to network resources
,2015-12-22 01:49:36.423 ThaliTest[698:838908] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-22 01:49:45.302 ThaliTest[698:838908] Resetting plugins due to page load.
,2015-12-22 01:49:48.235 ThaliTest[698:838908] Finished load of: file:///var/mobile/Containers/Bundle/Application/C7319A1A-4976-46FF-AC38-485BCD96ABB6/ThaliTest.app/www/index.html
,2015-12-22 01:49:48.396 ThaliTest[698:838908] JXcore Cordova plugin initializing
,2015-12-22 01:49:48.397 ThaliTest[698:839128] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,found test : ./testSendData2.js
,2015-12-22 01:49:49.397 ThaliTest[698:838908] THREAD WARNING: ['JXcore'] took '76.934082' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-22 01:54:52.089 ThaliTest[698:839128] jxcore: startBroadcasting
,2015-12-22 01:54:52.106 ThaliTest[698:839128] server: starting Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:54:52.107 ThaliTest[698:839128] multipeer session: start timer: 0x196220d0
2015-12-22 01:54:52.108 ThaliTest[698:839128] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8764
2015-12-22 01:54:52.109 ThaliTest[698:839128] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-22 01:54:53.208 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-22 01:54:54.523 ThaliTest[698:839128] jxcore: stopBroadcasting
2015-12-22 01:54:54.524 ThaliTest[698:839128] THEMultipeerSession stopping peer
,2015-12-22 01:54:54.525 ThaliTest[698:839128] multipeer session: stop timer
,2015-12-22 01:54:54.527 ThaliTest[698:839128] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 55526
,2015-12-22 01:54:54.591 ThaliTest[698:839128] jxcore: startBroadcasting
,2015-12-22 01:54:54.596 ThaliTest[698:839128] server: starting Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:54:54.599 ThaliTest[698:839128] multipeer session: start timer: 0x1951fc60
,2015-12-22 01:54:54.601 ThaliTest[698:839128] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8764
,2015-12-22 01:54:54.603 ThaliTest[698:839128] jxcore: startBroadcasting: success
,2015-12-22 01:54:54.607 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
StartBroadcasting started ok
,null
,2015-12-22T00:54:54.609Z SendDataTCPServer.js: TCP/IP server is bound to port: 55526
,2015-12-22 01:54:54.610 ThaliTest[698:838908] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:54:54.613Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:54:54.614Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:54:54.614Z SendDataConnector.js: do connect now
,2015-12-22 01:54:54.615 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:54:54.615 ThaliTest[698:839128] client session: connect
,2015-12-22 01:54:54.616 ThaliTest[698:839128] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.4oKZxQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22 01:54:55.745 ThaliTest[698:838908] client: lost peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:55.746 ThaliTest[698:838908] client session: onPeerLost: Apple-IpadAir2-1_PT8764.Y1JJAA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-22 01:54:56.347 ThaliTest[698:838908] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:56.367 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:56.726 ThaliTest[698:838908] client: lost peer: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:56.726 ThaliTest[698:838908] client session: onPeerLost: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:56.726 ThaliTest[698:838908] client session: onLinkFailure: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:56.727 ThaliTest[698:838908] client session: disconnect
,2015-12-22 01:54:56.727 ThaliTest[698:838908] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:56.728 ThaliTest[698:838908] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:54:56.728 ThaliTest[698:838908] jxcore: connect: fail: Peer disconnected
2015-12-22 01:54:56.729 ThaliTest[698:838908] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22T00:54:56.730Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:54:56.731Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-22T00:54:56.732Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22T00:55:01.735Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:01.736Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:06.749 ThaliTest[698:839128] jxcore: disconnect
2015-12-22 01:55:06.750 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:55:06.751Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:06.751Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
,2015-12-22T00:55:06.753Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:06.753Z SendDataConnector.js: do connect now
,2015-12-22 01:55:06.754 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:06.755 ThaliTest[698:839128] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:06.755 ThaliTest[698:839128] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:06.756Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-22T00:55:06.757Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:06.757Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:11.768Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:11.768Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:16.776 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:55:16.777 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:55:16.778Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:16.778Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
,2015-12-22T00:55:16.779Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:16.779Z SendDataConnector.js: do connect now
,2015-12-22 01:55:16.780 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:16.781 ThaliTest[698:839128] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:16.781 ThaliTest[698:839128] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:16.782Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:16.783Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:16.783Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:21.786Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:21.786Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:24.602 ThaliTest[698:838908] multipeer session: restart
,2015-12-22 01:55:24.635 ThaliTest[698:838908] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:24.635 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:24.635 ThaliTest[698:838908] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:26.799 ThaliTest[698:839128] jxcore: disconnect
2015-12-22 01:55:26.800 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:55:26.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:26.801Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
,2015-12-22T00:55:26.802Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:26.803Z SendDataConnector.js: do connect now
,2015-12-22 01:55:26.804 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:26.805 ThaliTest[698:839128] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:26.805 ThaliTest[698:839128] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:26.806Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-22T00:55:26.807Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:26.807Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22 01:55:31.202 ThaliTest[698:838908] client: lost peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:31.203 ThaliTest[698:838908] client session: onPeerLost: Apple-Iphone6-1_PT4682.uK405g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22T00:55:31.809Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22T00:55:31.810Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:34.929 ThaliTest[698:838908] client: lost peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:34.929 ThaliTest[698:838908] client session: onPeerLost: Apple-Iphone5s-1_PT9511.iUx4mA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22 01:55:36.823 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:55:36.823 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:55:36.824Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:36.824Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
,2015-12-22T00:55:36.825Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:36.826Z SendDataConnector.js: do connect now
,2015-12-22 01:55:36.827 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:36.827 ThaliTest[698:839128] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:36.828 ThaliTest[698:839128] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:36.829Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-22T00:55:36.830Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-22T00:55:36.832Z SendDataConnector.js: CLIENT Stop now
,2015-12-22 01:55:36.833 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:55:36.834 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:55:36.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22T00:55:36.838Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22T00:55:36.839Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22T00:55:36.839Z SendDataConnector.js: do connect now
,2015-12-22 01:55:36.840 ThaliTest[698:839128] jxcore: connect Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:36.841 ThaliTest[698:839128] client session: connect
,2015-12-22 01:55:36.842 ThaliTest[698:839128] client session: stateChange:0->1 Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:37.207 ThaliTest[698:838908] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-22 01:55:37.284 ThaliTest[698:838908] multipeer session: reset timer
2015-12-22 01:55:37.285 ThaliTest[698:838908] multipeer session: stop timer
,2015-12-22 01:55:37.285 ThaliTest[698:838908] multipeer session: start timer: 0x1951fc60
2015-12-22 01:55:37.286 ThaliTest[698:838908] server session: connect
,2015-12-22 01:55:37.286 ThaliTest[698:838908] server session: stateChange:0->1 Apple-Iphone5-1_PT5195
,2015-12-22 01:55:37.293 ThaliTest[698:838908] server: accepting invitation Apple-Iphone5-1_PT5195
,2015-12-22 01:55:40.465 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:55:40.896 ThaliTest[698:839806] server session: connected
,2015-12-22 01:55:40.898 ThaliTest[698:839806] server session: stateChange:1->2 Apple-Iphone5-1_PT5195
,2015-12-22 01:55:40.907 ThaliTest[698:839777] client session: connected
2015-12-22 01:55:40.909 ThaliTest[698:839777] client session: stateChange:1->2 Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:40.919 ThaliTest[698:838908] server relay: connected (to port: 55526)
2015-12-22T00:55:40.921Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-22 01:55:40.929 ThaliTest[698:839819] client session: fireConnectCallback: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:55:40.929 ThaliTest[698:839819] jxcore: connect: success
,2015-12-22T00:55:40.931Z SendDataConnector.js: CLIENT connected to 55531, error: null
,2015-12-22T00:55:40.931Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:55:40.934 ThaliTest[698:838908] client: relay established
2015-12-22 01:55:40.934 ThaliTest[698:838908] client: new accepted socket: 0x19531390
,2015-12-22T00:55:40.950Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:55:41.466Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-22T00:55:41.478Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-22T00:55:41.479Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-22T00:55:41.490Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-22T00:55:41.491Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-22T00:55:41.491Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-22T00:55:41.492Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:55:41.492Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:55:41.493 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:55:41.493 ThaliTest[698:839128] client session: disconnectFromPeer: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:55:41.493 ThaliTest[698:839128] client session: disconnect
2015-12-22 01:55:41.493 ThaliTest[698:839128] client session: stateChange:2->0 Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:41.497 ThaliTest[698:839128] jxcore: disconnect: success
,2015-12-22T00:55:41.497Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5195.x5+2Tg==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:55:41.498Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:41.498Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:55:41.498Z SendDataConnector.js: do connect now
2015-12-22 01:55:41.499 ThaliTest[698:839128] jxcore: connect Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:41.499 ThaliTest[698:839128] client session: connect
2015-12-22 01:55:41.499 ThaliTest[698:839128] client session: stateChange:0->1 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:41.516Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-22T00:55:41.531Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-22T00:55:41.545Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-22T00:55:41.558Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22 01:55:41.587 ThaliTest[698:839777] server session: not connected Apple-Iphone5-1_PT5195
,2015-12-22 01:55:44.507 ThaliTest[698:839819] client session: connected
2015-12-22 01:55:44.507 ThaliTest[698:839819] client session: stateChange:1->2 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:44.534 ThaliTest[698:839788] client session: fireConnectCallback: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:44.535 ThaliTest[698:839788] jxcore: connect: success
,2015-12-22T00:55:44.536Z SendDataConnector.js: CLIENT connected to 55534, error: null
2015-12-22T00:55:44.537Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:55:44.542 ThaliTest[698:838908] client: relay established
2015-12-22 01:55:44.542 ThaliTest[698:838908] client: new accepted socket: 0x1952b650
,2015-12-22T00:55:44.552Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:55:44.989Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-22T00:55:45.002Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-22T00:55:45.024Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-22T00:55:45.037Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-22T00:55:45.037Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-22T00:55:45.038Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:55:45.038Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-22 01:55:45.038 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:55:45.039 ThaliTest[698:839128] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:45.039 ThaliTest[698:839128] client session: disconnect
,2015-12-22 01:55:45.039 ThaliTest[698:839128] client session: stateChange:2->0 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:45.042 ThaliTest[698:839128] jxcore: disconnect: success
2015-12-22T00:55:45.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9511.iUx4mA==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone6-1_PT4682.uK405g==
2015-12-22T00:55:45.043Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4682.uK405g==
2015-12-22T00:55:45.044Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:55:45.044Z SendDataConnector.js: do connect now
2015-12-22 01:55:45.044 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:45.044 ThaliTest[698:839128] client session: connect
2015-12-22 01:55:45.044 ThaliTest[698:839128] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:07.286 ThaliTest[698:838908] multipeer session: restart
,2015-12-22 01:56:07.318 ThaliTest[698:838908] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:07.318 ThaliTest[698:838908] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:07.318 ThaliTest[698:838908] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:56:17.951 ThaliTest[698:839902] client session: not connected Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.951 ThaliTest[698:839902] client session: onLinkFailure: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.952 ThaliTest[698,:839902] client session: disconnect
2015-12-22 01:56:17.952 ThaliTest[698:839902] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.953 ThaliTest[698:839902] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.u,K405g==
2015-12-22 01:56:17.953 ThaliTest[698:839902] jxcore: connect: fail: Peer disconnected
,2015-12-22T00:56:17.956Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:56:17.956Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:56:17.957Z SendDataConnector.js: tryAgain afer: 5000 ms.,
,2015-12-22T00:56:22.960Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:22.960Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:27.971 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:56:27.972 ThaliTest[698:839128] jxcore: disconnect: fail
,2015-12-22T00:56:27.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:27.974Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4682.uK405g== with availability status: true
,2015-12-22T00:56:27.975Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:27.975Z SendDataConnector.js: do connect now
,2015-12-22 01:56:27.976 ThaliTest[698:839128] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:27.977 ThaliTest[698:839128] client session: connect
,2015-12-22 01:56:27.977 ThaliTest[698:839128] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:30.778 ThaliTest[698:839958] client session: connected
2015-12-22 01:56:30.778 ThaliTest[698:839958] client session: stateChange:1->2 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:30.799 ThaliTest[698:839937] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:30.800 ThaliTest[698:839937] jxcore: connect: success
,2015-12-22T00:56:30.801Z SendDataConnector.js: CLIENT connected to 55540, error: null
2015-12-22T00:56:30.801Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:56:30.804 ThaliTest[698:838908] client: relay established
2015-12-22 01:56:30.804 ThaliTest[698:838908] client: new accepted socket: 0x19532f30
,2015-12-22T00:56:30.817Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:56:31.135Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-22T00:56:31.148Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-22T00:56:31.158Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-22T00:56:31.172Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-22T00:56:31.197Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-22T00:56:31.197Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-22T00:56:31.198Z SendDataConnector.js: CLIENT Stop now
2015-12-22T00:56:31.198Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:56:31.198 ThaliTest[698:839128] jxcore: disconnect
,2015-12-22 01:56:31.198 ThaliTest[698:839128] client session: disconnectFromPeer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:31.199 ThaliTest[698:839128] client session: disconnect
2015-12-22 01:56:31.199 ThaliTest[698:839128] client session: stateChange:2->0 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:31.202 ThaliTest[698:839128] jxcore: disconnect: success
,2015-12-22T00:56:31.203Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-22T00:56:31.205Z SendDataConnector.js: CLIENT Stop now
2015-12-22T00:56:31.205Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:56:32.311 ThaliTest[698:838908] multipeer session: reset timer
2015-12-22 01:56:32.311 ThaliTest[698:838908] multipeer session: stop timer
2015-12-22 01:56:32.312 ThaliTest[698:838908] multipeer session: start timer: 0x1951fc60
2015-12-22 ,01:56:32.312 ThaliTest[698:838908] server session: connect
2015-12-22 01:56:32.312 ThaliTest[698:838908] server session: stateChange:0->1 Apple-Iphone6-1_PT4682
,2015-12-22 01:56:32.319 ThaliTest[698:838908] server: accepting invitation Apple-Iphone6-1_PT4682
,teardown
,testSendData stopped
2015-12-22 01:56:39.765 ThaliTest[698:839128] jxcore: stopBroadcasting
2015-12-22 01:56:39.765 ThaliTest[698:839128] THEMultipeerSession stopping peer
,2015-12-22 01:56:39.766 ThaliTest[698:839128] multipeer session: stop timer
,2015-12-22 01:56:39.768 ThaliTest[698:839128] server session: disconnect
2015-12-22 01:56:39.769 ThaliTest[698:839128] server session: stateChange:2->0 Apple-Iphone5-1_PT5195
,2015-12-22 01:56:39.837 ThaliTest[698:839128] server session: disconnect
2015-12-22 01:56:39.837 ThaliTest[698:839128] server session: stateChange:1->0 Apple-Iphone6-1_PT4682
,2015-12-22 01:56:39.906 ThaliTest[698:839128] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-22T00:56:39.924Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:39.925Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
