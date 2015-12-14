#### Test 5065027870036d7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/4DE17478-BEBF-4F20-A779-FB3ACF0C78EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4DE17478-BEBF-4F20-A779-FB3ACF0C78EE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E62B6219-E949-4180-9138-88B75C863AFC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55977"
,(lldb)     command script import "/tmp/4DE17478-BEBF-4F20-A779-FB3ACF0C78EE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 22:15:15.376 ThaliTest[1004:1207463] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7651D7E8-A86C-4FD0-900F-E159C0D64D4D/Library/Cookies/Cookies.binarycookies
,2015-12-14 22:15:15.807 ThaliTest[1004:1207463] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 22:15:15.809 ThaliTest[1004:1207463] Multi-tasking -> Device: YES, App: YES
,2015-12-14 22:15:15.820 ThaliTest[1004:1207463] Unlimited access to network resources
,2015-12-14 22:15:15.835 ThaliTest[1004:1207463] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 22:15:25.024 ThaliTest[1004:1207463] Resetting plugins due to page load.
,2015-12-14 22:15:28.384 ThaliTest[1004:1207463] Finished load of: file:///var/mobile/Containers/Bundle/Application/E62B6219-E949-4180-9138-88B75C863AFC/ThaliTest.app/www/index.html
,2015-12-14 22:15:28.601 ThaliTest[1004:1207463] JXcore Cordova plugin initializing
2015-12-14 22:15:28.602 ThaliTest[1004:1207796] JXcore instance initializing
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
,2015-12-14 22:15:29.906 ThaliTest[1004:1207463] THREAD WARNING: ['JXcore'] took '89.652832' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 22:20:21.456 ThaliTest[1004:1207796] jxcore: startBroadcasting
,2015-12-14 22:20:21.481 ThaliTest[1004:1207796] server: starting Apple-Iphone5s-1_PT4984.6YBI9g==
,2015-12-14 22:20:21.483 ThaliTest[1004:1207796] multipeer session: start timer: 0x18493310
,2015-12-14 22:20:21.484 ThaliTest[1004:1207796] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4984
,2015-12-14 22:20:21.485 ThaliTest[1004:1207796] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 22:20:22.528 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.QDCMPg==
2015-12-14 22:20:22.529 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one6-1_PT4552.QDCMPg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT4552.QDCMPg==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-14 22:20:22.941 ThaliTest[1004:1207796] jxcore: stopBroadcasting
,2015-12-14 22:20:22.942 ThaliTest[1004:1207796] THEMultipeerSession stopping peer
,2015-12-14 22:20:22.942 ThaliTest[1004:1207796] multipeer session: stop timer
,2015-12-14 22:20:22.944 ThaliTest[1004:1207796] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58795
,2015-12-14 22:20:23.042 ThaliTest[1004:1207796] jxcore: startBroadcasting
,2015-12-14 22:20:23.045 ThaliTest[1004:1207796] server: starting Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:20:23.047 ThaliTest[1004:1207796] multipeer session: start timer: 0x18492870
,2015-12-14 22:20:23.051 ThaliTest[1004:1207796] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4984
,2015-12-14 22:20:23.053 ThaliTest[1004:1207796] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-14T21:20:23.061Z SendDataTCPServer.js: TCP/IP server is bound to port: 58795
,2015-12-14 22:20:24.023 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.025 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipa,dAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:24.030Z SendDataConnector.js: Start called with peer Apple-IpadAir,2-1_PT1227.oXDKcw==
2015-12-14T21:20:24.031Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:24.031Z SendDataConnector.js: do connect now
2015-12-14 22:20:24.032 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:24.034 ThaliTest[1004:1207796] client session: connect
2015-12-14 22:20:24.034 ThaliTest[1004:1207796] client session: stateChange:0->1 Apple-IpadAir2-1_PT1227.oXDKcw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.590 ThaliTest[1004:1207463] client: lost peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.590 ThaliTest[1004:1207463] client session: onPeerLost: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.591 ThaliTest[1004:120746,3] client session: onLinkFailure: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.592 ThaliTest[1004:1207463] client session: disconnect
2015-12-14 22:20:24.593 ThaliTest[1004:1207463] client session: stateChange:1->0 Apple-IpadAir2-1_PT1227.oXDKcw=,=
2015-12-14 22:20:24.594 ThaliTest[1004:1207463] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.595 ThaliTest[1004:1207463] jxcore: connect: fail: Peer disconnected
2015-12-14 22:20:24.597 ThaliTest[1004:12074,63] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14T21:20:24.598Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T21:20:24.599Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T2,1:20:24.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGx,g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.609 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.1SWIqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.689 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-14 22:20:26.642 ThaliTest[1004:1207463] client: lost peer: Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:26.642 ThaliTest[1004:1207463] client session: onPeerLost: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T21:20:29.608Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:29.609Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:34.619 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:20:34.620 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:20:34.621Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDK,cw==
2015-12-14T21:20:34.621Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:34.621Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==,
,2015-12-14T21:20:34.622Z SendDataConnector.js: do connect now
2015-12-14 22:20:34.622 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:34.623 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_P,T1227.oXDKcw==
,2015-12-14 22:20:34.624 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
2015-12-14T21:20:34.625Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:34.626Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-14T21:20:34.627Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:39.633Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:39.633Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:44.636 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:20:44.637 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:20:44.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDK,cw==
2015-12-14T21:20:44.638Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:44.639Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:44.639Z SendDataConnector.js: do connect now
2015-12-14 22:20:44.640 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:44.641 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:44.641 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:44.642Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T21:20:44.643Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:44.644Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:49.651Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:49.651Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:53.053 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:20:54.656 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:20:54.657 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:20:54.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDK,cw==
2015-12-14T21:20:54.658Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:54.658Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==,
,2015-12-14T21:20:54.659Z SendDataConnector.js: do connect now
2015-12-14 22:20:54.660 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:54.661 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:54.662 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
2015-12-14T21:20:54.663Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-14T21:20:54.663Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:54.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:59.673Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:59.674Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.683 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:04.684 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:04.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDK,cw==
2015-12-14T21:21:04.685Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:21:04.685Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:21:04.686Z SendDataConnector.js: do connect now
2015-12-14 22:21:04.687 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:21:04.688 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_P,T1227.oXDKcw==
,2015-12-14 22:21:04.689 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:04.689Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T21:21:04.690Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-14T21:21:04.694Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 22:21:04.695 ThaliTest[1004:1207796] jxcore: disconnect
,2015-12-14 22:21:04.696 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:04.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:04.701Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:04.702Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:04.703Z SendDataConnector.js: do connect now
,2015-12-14 22:21:04.704 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:04.705 ThaliTest[1004:1207796] client session: connect
2015-12-14 22:21:04.706 ThaliTest[1004:1207796] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:04.720 ThaliTest[1004:1207463] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:04.720 ThaliTest[1004:1207463] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:04.720 ThaliTest[1004:120746,3] client session: onLinkFailure: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:04.721 ThaliTest[1004:1207463] client session: disconnect
2015-12-14 22:21:04.721 ThaliTest[1004:1207463] client session: stateChange:1->0 Apple-IpadAir2-1_PT1227.Q+hGxg=,=
2015-12-14 22:21:04.722 ThaliTest[1004:1207463] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:04.722 ThaliTest[1004:1207463] jxcore: connect: fail: Peer disconnected
2015-12-14T21:21:04.724Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2015-12-14T21:21:04.724Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:21:04.725Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier",:"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":false}]
,2015-12-14T21:21:09.726Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:09.727Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:11.251 ThaliTest[1004:1207463] multipeer session: reset timer
2015-12-14 22:21:11.251 ThaliTest[1004:1207463] multipeer session: stop timer
2015-12-14 22:21:11.251 ThaliTest[1004:1207463] multipeer session: start timer: 0x18492870
2015-,12-14 22:21:11.252 ThaliTest[1004:1207463] server session: connect
2015-12-14 22:21:11.253 ThaliTest[1004:1207463] server session: stateChange:0->1 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:11.265 ThaliTest[1004:1207463] server: accepting invitation Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:14.004 ThaliTest[1004:1208402] server session: connected
2015-12-14 22:21:14.004 ThaliTest[1004:1208402] server session: stateChange:1->2 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:14.016 ThaliTest[1004:1207463] server relay: connected (to port: 58795)
2015-12-14T21:21:14.017Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:14.333Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-14T21:21:14.352Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-14T21:21:14.370Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-14T21:21:14.389Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T21:21:14.403Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-14T21:21:14.419Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-14T21:21:14.435Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:14.499 ThaliTest[1004:1208402] server session: not connected Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:14.734 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:14.734 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:14.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hG,xg==
2015-12-14T21:21:14.735Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1227.Q+hGxg== with availability status: true
2015-12-14T21:21:14.736Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:14.736Z SendDataConnector.js: do connect now
2015-12-14 22:21:14.737 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:14.738 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:14.738 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
2015-12-14T21:21:14.739Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-14T21:21:14.740Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:21:14.740Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:19.743Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:19.744Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:24.746 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:24.746 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:24.747Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hG,xg==
2015-12-14T21:21:24.748Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1227.Q+hGxg== with availability status: true
2015-12-14T21:21:24.748Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:24.748Z SendDataConnector.js: do connect now
2015-12-14 22:21:24.749 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:24.750 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_P,T1227.Q+hGxg==
,2015-12-14 22:21:24.750 ThaliTest[1004:1207796] jxcore: connect: fail: Peer unreachable
2015-12-14T21:21:24.751Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T21:21:24.752Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:21:24.753Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:29.757Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:29.757Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:34.771 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:34.771 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:34.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hG,xg==
2015-12-14T21:21:34.772Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1227.Q+hGxg== with availability status: true
2015-12-14T21:21:34.773Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==,
2015-12-14T21:21:34.773Z SendDataConnector.js: do connect now
,2015-12-14 22:21:34.774 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:34.775 ThaliTest[1004:1207796] client: connect: unreachable Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:34.775 ThaliTest[1004:1207796], jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:34.776Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T21:21:34.776Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:21:34.778Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:39.780Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14T21:21:39.781Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:41.253 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:21:41.305 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:41.305 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:41.306 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
,2015-12-14 22:21:44.784 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:44.784 ThaliTest[1004:1207796] jxcore: disconnect: fail
2015-12-14T21:21:44.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hG,xg==
2015-12-14T21:21:44.786Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1227.Q+hGxg== with availability status: true
,2015-12-14T21:21:44.787Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14T21:21:44.787Z SendDataConnector.js: do connect now
,2015-12-14 22:21:44.788 ThaliTest[1004:1207796] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:44.789 ThaliTest[1004:1207796] client session: connect
,2015-12-14 22:21:44.790 ThaliTest[1004:1207796] client session: stateChange:0->1 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:48.143 ThaliTest[1004:1208513] client session: connected
2015-12-14 22:21:48.143 ThaliTest[1004:1208513] client session: stateChange:1->2 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:48.148 ThaliTest[1004:1208513] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:48.149 ThaliTest[1004:1208513] jxcore: connect: success
2015-12-14T21:21:48.150Z SendDataConnector.js: CLIENT connected to 58802, error: null
2015-12-14T21:21:48.150Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:48.157 ThaliTest[1004:1207463] client: relay established
2015-12-14 22:21:48.158 ThaliTest[1004:1207463] client: new accepted socket: 0x184a3590
,2015-12-14T21:21:48.171Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:48.530Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T21:21:48.592Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:48.593Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T21:21:48.593Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:48.594Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:48.594 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:48.595 ThaliTest[1004:1207796] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:48.595 ThaliTest[1004:1207796] client session: disconnect
2015-12-14 22:21:48.595 ThaliTest[1004:1207796] client session: stateChange:2->0 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:48.601 ThaliTest[1004:1207796] jxcore: disconnect: success
2015-12-14T21:21:48.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
---- round done--------
startWithNextDevice
device[3]: Ap,ple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14T21:21:48.602Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14T21:21:48.602Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14T21:21:48.602Z SendDataConnector.js: do connect now
2015-12-14 22:21:48.602 ThaliTest[1004:1207796] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:48.602 ThaliTest[1004:1207796] client session: connect
2015-12-14 22:21:48.602 ThaliTest[1004:1207796] client session: stateChange:0->1 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:52.214 ThaliTest[1004:1208512] client session: connected
2015-12-14 22:21:52.214 ThaliTest[1004:1208512] client session: stateChange:1->2 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:52.224 ThaliTest[1004:1208511] client session: fireConnectCallback: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:52.224 ThaliTest[1004:1208511] jxcore: connect: success
2015-12-14T21:21:52.225Z SendDataConnector.js: CLIENT connected to 58805, error: null
2015-12-14T21:21:52.226Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:52.230 ThaliTest[1004:1207463] client: relay established
2015-12-14 22:21:52.231 ThaliTest[1004:1207463] client: new accepted socket: 0x184b17b0
,2015-12-14T21:21:52.241Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:52.617Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T21:21:52.653Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T21:21:52.667Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:52.667Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T21:21:52.668Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:52.668Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:52.669 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:52.669 ThaliTest[1004:1207796] client session: disconnectFromPeer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:52.669 ThaliTest[1004:1207796] client session: disconnect
2015-12-14 22:21:52.669 ThaliTest[1004:1207796] client session: stateChange:2->0 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:52.675 ThaliTest[1004:1207796] jxcore: disconnect: success
2015-12-14T21:21:52.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21:52.676Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21:52.676Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21,:52.676Z SendDataConnector.js: do connect now
2015-12-14 22:21:52.676 ThaliTest[1004:1207796] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:52.676 ThaliTest[1004:1207796] client session: connect
2015-12-14 22:21:52.676 ThaliTest[1004:1207796] client session: stateChange:0->1 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:55.347 ThaliTest[1004:1207463] multipeer session: reset timer
2015-12-14 22:21:55.348 ThaliTest[1004:1207463] multipeer session: stop timer
2015-12-14 22:21:55.348 ThaliTest[1004:1207463] multipeer session: start timer: 0x18492870
2015-,12-14 22:21:55.349 ThaliTest[1004:1207463] server session: connect
2015-12-14 22:21:55.349 ThaliTest[1004:1207463] server session: stateChange:0->1 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:55.361 ThaliTest[1004:1207463] server: accepting invitation Apple-Iphone5-1_PT2471
,2015-12-14 22:21:55.493 ThaliTest[1004:1208512] client session: connected
2015-12-14 22:21:55.493 ThaliTest[1004:1208512] client session: stateChange:1->2 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:55.509 ThaliTest[1004:1208511] client session: fireConnectCallback: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:55.509 ThaliTest[1004:1208511] jxcore: connect: success
2015-12-14T21:21:55.510Z SendDataConnector.js: CLIENT connected ,to 58808, error: null
2015-12-14T21:21:55.511Z SendDataConnector.js: CLIENT starting client 
2015-12-14 22:21:55.516 ThaliTest[1004:1207463] client: relay established
2015-12-14 22:21:55.516 ThaliTest[1004:1207463] client: new accepted socket: 0x183f3d00
,2015-12-14T21:21:55.529Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:55.836Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T21:21:55.996Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T21:21:56.023Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T21:21:56.023Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T21:21:56.024Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:56.024Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:56.024 ThaliTest[1004:1207796] jxcore: disconnect
2015-12-14 22:21:56.025 ThaliTest[1004:1207796] client session: disconnectFromPeer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:56.025 ThaliTest[1004:1207796] client session: disconnect
2015-12-14 22:21:56.025 ThaliTest[1004:1207796] client session: stateChange:2->0 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:56.031 ThaliTest[1004:1207796] jxcore: disconnect: success
2015-12-14T21:21:56.031Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T21:21:56.035Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:56.035Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:57.949 ThaliTest[1004:1208513] server session: connected
2015-12-14 22:21:57.949 ThaliTest[1004:1208513] server session: stateChange:1->2 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:57.957 ThaliTest[1004:1207463] server relay: connected (to port: 58795)
,2015-12-14T21:21:57.968Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14 22:21:58.229 ThaliTest[1004:1207463] multipeer session: reset timer
2015-12-14 22:21:58.229 ThaliTest[1004:1207463] multipeer session: stop timer
2015-12-14 22:21:58.229 ThaliTest[1004:1207463] multipeer session: start timer: 0x18492870
2015-,12-14 22:21:58.230 ThaliTest[1004:1207463] server session: connect
2015-12-14 22:21:58.230 ThaliTest[1004:1207463] server session: stateChange:0->1 Apple-Iphone6-1_PT4552
,2015-12-14 22:21:58.242 ThaliTest[1004:1207463] server: accepting invitation Apple-Iphone6-1_PT4552
,2015-12-14T21:21:58.485Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T21:21:58.500Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T21:21:58.552Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-14T21:21:58.570Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-14T21:21:58.587Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:58.674 ThaliTest[1004:1208513] server session: not connected Apple-Iphone5-1_PT2471
,2015-12-14 22:22:00.794 ThaliTest[1004:1208513] server session: connected
2015-12-14 22:22:00.795 ThaliTest[1004:1208513] server session: stateChange:1->2 Apple-Iphone6-1_PT4552
,2015-12-14 22:22:00.810 ThaliTest[1004:1207463] server relay: connected (to port: 58795)
,2015-12-14T21:22:00.820Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:22:01.110Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T21:22:01.123Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-14T21:22:01.140Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-14T21:22:01.158Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-14T21:22:01.176Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-14T21:22:01.191Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:22:01.308 ThaliTest[1004:1208511] server session: not connected Apple-Iphone6-1_PT4552
,2015-12-14 22:22:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:22:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:22:58.269 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:22:58.274 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:22:58.275 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-14 22:23:04.940 ThaliTest[1004:1207796] jxcore: startBroadcasting
2015-12-14 22:23:04.941 ThaliTest[1004:1207796] jxcore: startBroadcasting: failure
weAreDoneNow
done, now sending data to server
,done, now sending data to server
,2015-12-14 22:23:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:23:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:23:58.284 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:23:58.284 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:23:58.289 ThaliTest[1004:1207463] clien,t: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:24:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:24:28.283 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:24:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:24:28.417 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:24:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:24:58.286 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:24:58.287 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:24:58.289 ThaliTest[1004:1207463] clien,t: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:25:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:25:28.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:25:28.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:25:28.711 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:25:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:25:58.281 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:25:58.288 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:25:58.289 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:26:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:26:28.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:26:28.287 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:26:28.287 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:26:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:26:58.730 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:26:58.735 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:00.790 ThaliTest[1004:1207463] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:27:00.790 ThaliTest[1004:1207463] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:07.531 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:27:08.035 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:27:28.283 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:27:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:27:28.288 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:27:58.288 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:27:58.289 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:27:58.298 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:28:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:28:28.284 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:28:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:28:28.289 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:28:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:28:58.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:28:58.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:28:58.285 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:29:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:29:28.280 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:29:28.288 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:29:28.289 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:29:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:29:58.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:29:58.289 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:29:58.328 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:30:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:30:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:30:58.281 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:30:58.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:30:58.291 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:31:28.230 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:31:28.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:31:28.284 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:31:28.287 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:31:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:32:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:32:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:32:28.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:32:28.296 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:32:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:33:28.230 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:33:28.271 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:33:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:33:58.272 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:34:05.361 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:34:28.276 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:34:28.277 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:37.843 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:34:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:34:58.283 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:34:58.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:34:58.285 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:35:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:35:28.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:35:28.283 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:35:28.288 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:35:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:35:58.283 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:35:58.284 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:35:58.295 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:36:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:36:28.280 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:36:28.280 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:36:28.292 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:36:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:36:58.294 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:36:58.295 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:36:58.298 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:37:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:37:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:37:58.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:37:58.285 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:37:58.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:38:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:38:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:38:28.293 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:38:28.429 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:38:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:38:58.288 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:38:58.289 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:38:58.299 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:39:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:39:28.282 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:39:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:39:28.286 ThaliTest[1004:1207463] client,: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,timeout now
,2015-12-14 22:39:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:40:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:40:28.284 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:40:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:40:28.285 ThaliTest[1004:1207463] clien,t: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:40:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:41:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:41:28.280 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:41:28.281 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:41:28.292 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:41:58.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:41:58.284 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:41:58.285 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:41:58.286 ThaliTest[1004:1207463] clien,t: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:42:28.231 ThaliTest[1004:1207463] multipeer session: restart
,2015-12-14 22:42:28.285 ThaliTest[1004:1207463] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:42:28.286 ThaliTest[1004:1207463] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:42:28.286 ThaliTest[1004:1207463] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==

```
