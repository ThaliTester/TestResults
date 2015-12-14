#### Test 5065027870036d7_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C9E928EF-F4D3-4B11-BCD4-91719E0751AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C9E928EF-F4D3-4B11-BCD4-91719E0751AD/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/09CD9D36-B30B-44FE-B4D2-491FB685D772/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55937"
,(lldb)     command script import "/tmp/C9E928EF-F4D3-4B11-BCD4-91719E0751AD/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 22:13:51.424 ThaliTest[825:1319847] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3BDBC94C-9C51-4671-87A1-93FFF64F767A/Library/Cookies/Cookies.binarycookies
,2015-12-14 22:13:51.546 ThaliTest[825:1319847] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 22:13:51.548 ThaliTest[825:1319847] Multi-tasking -> Device: YES, App: YES
,2015-12-14 22:13:51.554 ThaliTest[825:1319847] Unlimited access to network resources
,2015-12-14 22:13:51.567 ThaliTest[825:1319847] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 22:14:02.917 ThaliTest[825:1319847] Resetting plugins due to page load.
,2015-12-14 22:14:06.487 ThaliTest[825:1319847] Finished load of: file:///var/mobile/Containers/Bundle/Application/09CD9D36-B30B-44FE-B4D2-491FB685D772/ThaliTest.app/www/index.html
,2015-12-14 22:14:06.685 ThaliTest[825:1319847] JXcore Cordova plugin initializing
,2015-12-14 22:14:06.686 ThaliTest[825:1320157] JXcore instance initializing
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
,2015-12-14 22:14:09.113 ThaliTest[825:1319847] THREAD WARNING: ['JXcore'] took '153.212891' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 22:20:18.623 ThaliTest[825:1320157] jxcore: startBroadcasting
,2015-12-14 22:20:18.635 ThaliTest[825:1320157] server: starting Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:18.636 ThaliTest[825:1320157] multipeer session: start timer: 0x18a075b0
2015-12-14 22:20:18.637 ThaliTest[825:1320157] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT2471
2015-12-14 22:20:18.637 ThaliTest[825:1320157] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 22:20:19.926 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1227.oXDKcw==, peerAvailable: true
2015-12-14 22:20:19.930 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.QDCMPg==
,weAreDoneNow
done, now sending data to server
,2015-12-14 22:20:22.610 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.6YBI9g==
,teardown
,testFindPeers stopped
,2015-12-14 22:20:22.983 ThaliTest[825:1320157] jxcore: stopBroadcasting
2015-12-14 22:20:22.983 ThaliTest[825:1320157] THEMultipeerSession stopping peer
2015-12-14 22:20:22.983 ThaliTest[825:1320157] multipeer session: stop timer
2015-12-14 22:20:22.984 ThaliTest[825:1320157] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 59291
,2015-12-14 22:20:23.047 ThaliTest[825:1320157] jxcore: startBroadcasting
,2015-12-14 22:20:23.050 ThaliTest[825:1320157] server: starting Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:20:23.050 ThaliTest[825:1320157] multipeer session: start timer: 0x18bdc3e0
2015-12-14 22:20:23.051 ThaliTest[825:1320157] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT2471
2015-12-14 22:20:23.051 ThaliTest[825:1320157] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-14T21:20:23.054Z SendDataTCPServer.js: TCP/IP server is bound to port: 59291
,2015-12-14 22:20:24.068 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.068 ThaliTest[825:1319847] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-14 22:20:24.070 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.6YBI9g==
startWithNextDevice
device[1]: Apple-IpadAir2-1_P,T1227.oXDKcw==
,2015-12-14T21:20:24.072Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:24.073Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:24.073Z SendDataConnector.j,s: do connect now
2015-12-14 22:20:24.074 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.074 ThaliTest[825:1320157] client session: connect
2015-12-14 22:20:24.075 ThaliTest[825:1320157] client session: state,Change:0->1 Apple-IpadAir2-1_PT1227.oXDKcw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.6YBI9g==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.273 ThaliTest[825:1319847] client: lost peer: Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:24.274 ThaliTest[825:1319847] client session: onPeerLost: Apple-Iphone5-1_PT2471.QNnKyw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 22:20:24.667 ThaliTest[825:1319847] client: lost peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.668 ThaliTest[825:1319847] client session: onPeerLost: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.668 ThaliTest[825:1319847] ,client session: onLinkFailure: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.668 ThaliTest[825:1319847] client session: disconnect
2015-12-14 22:20:24.668 ThaliTest[825:1319847] client session: stateChange:1->0 Apple-IpadAir2-1_PT1227.oXDKcw==
20,15-12-14 22:20:24.669 ThaliTest[825:1319847] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:24.669 ThaliTest[825:1319847] jxcore: connect: fail: Peer disconnected
2015-12-14T21:20:24.670Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-14T21:20:24.671Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:20:24.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-14 22:20:24.672 ThaliTest[825:1319847] c,lient: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","pee,rName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 22:20:24.675 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:20:24.678 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.xdA4DQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T21:20:29.680Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:29.681Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:30.392 ThaliTest[825:1319847] client: lost peer: Apple-Iphone5s-1_PT4984.6YBI9g==
2015-12-14 22:20:30.392 ThaliTest[825:1319847] client session: onPeerLost: Apple-Iphone5s-1_PT4984.6YBI9g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.6YBI9g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 22:20:34.684 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:20:34.685 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:20:34.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:34.686Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:34.687Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:34.687Z SendDataConnector.js: do connect now
,2015-12-14 22:20:34.688 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:34.688 ThaliTest[825:1320157] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:34.688 ThaliTest[825:1320157] jx,core: connect: fail: Peer unreachable
2015-12-14T21:20:34.689Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:34.689Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:20:34.689Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:39.694Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:39.695Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:44.703 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:20:44.704 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:20:44.705Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:44.705Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:44.706Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:44.706Z SendDataConnector.js: do connect now
,2015-12-14 22:20:44.707 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:44.707 ThaliTest[825:1320157] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:44.707 ThaliTest[825:1320157] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:44.708Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:44.709Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T21:20:44.709Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:49.720Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:49.721Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:53.052 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:20:54.732 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:20:54.733 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:20:54.734Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:20:54.734Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:20:54.734Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14T21:20:54.735Z SendDataConnector.js: do connect now
,2015-12-14 22:20:54.736 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:54.736 ThaliTest[825:1320157] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:54.736 ThaliTest[825:1320157] jx,core: connect: fail: Peer unreachable
,2015-12-14T21:20:54.737Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:54.737Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:20:54.737Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:59.746Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:20:59.746Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.760 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:04.761 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:04.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw,==
2015-12-14T21:21:04.761Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT1227.oXDKcw== with availability status: true
2015-12-14T21:21:04.761Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14T21:21:04.762Z SendDataConnector.js: do connect now
2015-12-14 22:21:04.762 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:21:04.762 ThaliTest[825:1320157] client: connect: unreachable Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:21:04.762 ThaliTest[825:1320157] jxcore: connect: fail: Peer unreachable
2015-12-14T21:21:04.763Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer unreachable
,2015-12-14T21:21:04.763Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-14T21:21:04.765Z SendDataConnector.js: CLIENT Stop now
2015-12-14 22:21:04.766 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:04.766 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:04.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.oXDKcw==
,---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:04.768Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:04.769Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:04.769Z SendDataConnector.js: do connect now
,2015-12-14 22:21:04.770 ThaliTest[825:1320157] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:04.770 ThaliTest[825:1320157] client session: connect
2015-12-14 22:21:04.770 ThaliTest[825:1320157] client session: stateChange:0->1 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:04.778 ThaliTest[825:1319847] client: lost peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:04.779 ThaliTest[825:1319847] client session: onPeerLost: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:04.779 ThaliTest[825:1319847] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:04.779 ThaliTest[825:1319847] client session: disconnect
2015-12-14 22:21:04.779 ThaliTest[825:1319847] client session: stateChange:1->0 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:04.834 ThaliTest[825:1319847] client session: fireConnectCallback: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:04.835 ThaliTest[825:1319847] jxcore: connect: fail: Peer disconnected
2015-12-14T21:21:04.836Z SendDataConnector.js: CLI,ENT connected to 0, error: Peer disconnected
2015-12-14T21:21:04.836Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T21:21:04.837Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 22:21:07.176 ThaliTest[825:1319847] multipeer session: reset timer
2015-12-14 22:21:07.176 ThaliTest[825:1319847] multipeer session: stop timer
2015-12-14 22:21:07.176 ThaliTest[825:1319847] multipeer session: start timer: 0x18bdc3e0
2015-12-14 22:21:07.177 ThaliTest[825:1319847] server session: connect
2015-12-14 22:21:07.177 ThaliTest[825:1319847] server session: stateChange:0->1 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:07.183 ThaliTest[825:1319847] server: accepting invitation Apple-IpadAir2-1_PT1227
,2015-12-14T21:21:09.838Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:09.839Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:09.864 ThaliTest[825:1320919] server session: connected
2015-12-14 22:21:09.864 ThaliTest[825:1320919] server session: stateChange:1->2 Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:09.870 ThaliTest[825:1319847] server relay: connected (to port: 59291)
,2015-12-14T21:21:09.881Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:10.451Z SendDataTCPServer.js: TCP/IP server has received 8476 bytes of data
,2015-12-14T21:21:10.465Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:11.020 ThaliTest[825:1320937] server session: not connected Apple-IpadAir2-1_PT1227
,2015-12-14 22:21:14.842 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:14.843 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:14.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A=,=
2015-12-14T21:21:14.844Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4552.wIXR0A== with availability status: true
2015-12-14T21:21:14.844Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21:14.844Z SendDataConnector.js: do connect now
,2015-12-14 22:21:14.845 ThaliTest[825:1320157] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:14.846 ThaliTest[825:1320157] client: connect: unreachable Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:14.846 ThaliTest[825:1320157] jxco,re: connect: fail: Peer unreachable
,2015-12-14T21:21:14.846Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:14.847Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:21:14.847Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:19.848Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:19.849Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:24.855 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:24.855 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:24.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A=,=
2015-12-14T21:21:24.856Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4552.wIXR0A== with availability status: true
2015-12-14T21:21:24.857Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21:24.857Z SendDataConnector.js: do connect now
,2015-12-14 22:21:24.858 ThaliTest[825:1320157] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:24.858 ThaliTest[825:1320157] client: connect: unreachable Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:24.859 ThaliTest[825:1320157] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:24.859Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:24.859Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:21:24.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:29.863Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:29.864Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:34.869 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:34.870 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:34.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A=,=
2015-12-14T21:21:34.871Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4552.wIXR0A== with availability status: true
2015-12-14T21:21:34.871Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
201,5-12-14T21:21:34.871Z SendDataConnector.js: do connect now
,2015-12-14 22:21:34.873 ThaliTest[825:1320157] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:34.873 ThaliTest[825:1320157] client: connect: unreachable Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:34.874 ThaliTest[825:1320157] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:34.874Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:34.874Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:21:34.875Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14 22:21:37.178 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:21:37.209 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:37.209 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:37.209 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":true}]
,2015-12-14T21:21:39.881Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:39.882Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:44.895 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:44.896 ThaliTest[825:1320157] jxcore: disconnect: fail
2015-12-14T21:21:44.896Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A=,=
2015-12-14T21:21:44.897Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4552.wIXR0A== with availability status: true
2015-12-14T21:21:44.897Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
201,5-12-14T21:21:44.898Z SendDataConnector.js: do connect now
,2015-12-14 22:21:44.899 ThaliTest[825:1320157] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:44.899 ThaliTest[825:1320157] client session: connect
2015-12-14 22:21:44.900 ThaliTest[825:1320157] client session: stateChange:0->1 Apple-Ip,hone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:49.041 ThaliTest[825:1319847] multipeer session: reset timer
2015-12-14 22:21:49.041 ThaliTest[825:1319847] multipeer session: stop timer
,2015-12-14 22:21:49.041 ThaliTest[825:1319847] multipeer session: start timer: 0x18bdc3e0
2015-12-14 22:21:49.043 ThaliTest[825:1319847] server session: connect
2015-12-14 22:21:49.043 ThaliTest[825:1319847] server session: stateChange:0->1 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:49.053 ThaliTest[825:1319847] server: accepting invitation Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:49.106 ThaliTest[825:1321189] client session: connected
,2015-12-14 22:21:49.106 ThaliTest[825:1321189] client session: stateChange:1->2 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:49.111 ThaliTest[825:1321189] client session: fireConnectCallback: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:49.111 ThaliTest[825:1321189] jxcore: connect: success
,2015-12-14T21:21:49.113Z SendDataConnector.js: CLIENT connected to 59299, error: null
2015-12-14T21:21:49.113Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:49.116 ThaliTest[825:1319847] client: relay established
2015-12-14 22:21:49.116 ThaliTest[825:1319847] client: new accepted socket: 0x18c54cf0
,2015-12-14T21:21:49.131Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:49.663Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T21:21:49.752Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T21:21:49.804Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T21:21:49.818Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T21:21:50.551Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:50.552Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T21:21:50.554Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:50.554Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:50.556 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:50.556 ThaliTest[825:1320157] client session: disconnectFromPeer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:50.556 ThaliTest[825:1320157] client session: disconnect
2015-12-14 22:21:50.556 ThaliTest[825:1320157] client session: stateChange:2->0 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:50.564 ThaliTest[825:1320157] jxcore: disconnect: success
2015-12-14T21:21:50.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A==
,---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14T21:21:50.569Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14T21:21:50.569Z SendDataConnector.js: doConnect call,ed with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14T21:21:50.569Z SendDataConnector.js: do connect now
2015-12-14 22:21:50.570 ThaliTest[825:1320157] jxcore: connect Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:50.570 ThaliTest[825:1320157] cl,ient session: connect
2015-12-14 22:21:50.570 ThaliTest[825:1320157] client session: stateChange:0->1 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:52.254 ThaliTest[825:1321187] server session: connected
2015-12-14 22:21:52.254 ThaliTest[825:1321187] server session: stateChange:1->2 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:52.279 ThaliTest[825:1319847] server relay: connected (to port: 59291)
2015-12-14T21:21:52.279Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:52.637Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T21:21:52.651Z SendDataTCPServer.js: TCP/IP server has received 34472 bytes of data
,2015-12-14T21:21:52.669Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-14T21:21:52.685Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-14T21:21:52.703Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:52.744 ThaliTest[825:1321189] server session: not connected Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:53.764 ThaliTest[825:1321189] client session: connected
2015-12-14 22:21:53.764 ThaliTest[825:1321189] client session: stateChange:1->2 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:53.816 ThaliTest[825:1321187] client session: fireConnectCallback: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:53.816 ThaliTest[825:1321187] jxcore: connect: success
2015-12-14T21:21:53.817Z SendDataConnector.js: CLIENT connected t,o 59303, error: null
2015-12-14T21:21:53.818Z SendDataConnector.js: CLIENT starting client 
2015-12-14 22:21:53.820 ThaliTest[825:1319847] client: relay established
2015-12-14 22:21:53.820 ThaliTest[825:1319847] client: new accepted socket: 0x18c54dc0
,2015-12-14T21:21:53.833Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:54.377Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T21:21:54.428Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T21:21:54.480Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:54.481Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T21:21:54.483Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:54.483Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:54.484 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:54.484 ThaliTest[825:1320157] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:21:54.485 ThaliTest[825:1320157] client session: disconnec,t
2015-12-14 22:21:54.485 ThaliTest[825:1320157] client session: stateChange:2->0 Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:21:54.492 ThaliTest[825:1320157] jxcore: disconnect: success
2015-12-14T21:21:54.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1227.Q+hGxg==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:54.493Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:54.493Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21,:21:54.493Z SendDataConnector.js: do connect now
2015-12-14 22:21:54.494 ThaliTest[825:1320157] jxcore: connect Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:54.494 ThaliTest[825:1320157] client session: connect
2015-12-14 22:21:54.494 ThaliTest[825,:1320157] client session: stateChange:0->1 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:57.956 ThaliTest[825:1321188] client session: connected
2015-12-14 22:21:57.957 ThaliTest[825:1321188] client session: stateChange:1->2 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:58.031 ThaliTest[825:1321217] client session: fireConnectCallback: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:58.031 ThaliTest[825:1321217] jxcore: connect: success
2015-12-14T21:21:58.032Z SendDataConnector.js: CLIENT connected t,o 59306, error: null
2015-12-14T21:21:58.032Z SendDataConnector.js: CLIENT starting client 
2015-12-14 22:21:58.034 ThaliTest[825:1319847] client: relay established
2015-12-14 22:21:58.035 ThaliTest[825:1319847] client: new accepted socket: 0x18bfa3a0
,2015-12-14T21:21:58.047Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:58.613Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T21:21:58.677Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:58.678Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T21:21:58.680Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:58.680Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:58.681 ThaliTest[825:1320157] jxcore: disconnect
2015-12-14 22:21:58.681 ThaliTest[825:1320157] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:58.682 ThaliTest[825:1320157] client session: disconnec,t
2015-12-14 22:21:58.682 ThaliTest[825:1320157] client session: stateChange:2->0 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:58.688 ThaliTest[825:1320157] jxcore: disconnect: success
2015-12-14T21:21:58.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T21:21:58.693Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:58.693Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:22:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:22:19.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:22:19.076 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:22:19.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:22:49.731 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:22:49.731 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:22:49.733 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:23:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:23:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:23:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:23:49.076 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:24:09.910 ThaliTest[825:1319847] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:24:09.910 ThaliTest[825:1319847] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-14 22:24:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:24:19.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:24:19.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:19.971 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-14 22:24:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:24:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:24:49.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:50.089 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:25:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:25:19.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:25:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:25:20.499 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:25:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:26:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:26:19.072 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:26:19.073 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:26:19.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:26:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:26:49.075 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:26:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:26:50.048 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:27:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:27:19.088 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:27:19.088 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:27:19.664 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:27:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:27:49.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:27:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:27:49.078 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:28:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:28:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:28:49.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:28:49.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:28:49.080 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:29:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:29:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:29:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:29:19.078 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:29:40.631 ThaliTest[825:1319847] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:29:40.632 ThaliTest[825:1319847] client session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-14 22:29:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:29:49.070 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:29:49.070 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:29:53.206 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-14 22:30:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:30:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:30:49.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:30:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:30:49.077 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:31:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:31:19.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:31:19.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:31:19.077 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:31:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:31:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:31:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:31:49.081 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:32:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:32:19.073 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:32:19.073 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:32:19.075 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:32:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:32:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:32:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:32:49.082 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:33:07.849 ThaliTest[825:1319847] client: lost peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:33:07.849 ThaliTest[825:1319847] client session: onPeerLost: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:33:07.851 ThaliTest[825:1319847] client: lost peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:33:07.851 ThaliTest[825:1319847] c,lient session: onPeerLost: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-14 22:33:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:33:19.067 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:33:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:33:49.068 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:06.861 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-14 22:34:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:34:19.070 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:34:19.071 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:37.893 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.Q+hGxg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-14 22:34:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:35:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:35:19.073 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:35:19.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:35:19.075 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:35:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:35:49.756 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:35:49.756 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:35:50.235 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:36:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:36:19.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:36:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:36:19.078 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:36:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:36:49.079 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:36:49.079 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:36:49.080 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:37:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:37:19.076 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:37:19.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:37:19.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:37:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:37:49.075 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:37:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:37:49.076 ThaliTest[825:1319847] client: ,found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:38:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:38:19.080 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:38:19.082 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:38:19.084 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:38:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:39:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:39:19.073 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:39:19.074 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:39:19.074 ThaliTest[825:1319847] client: ,found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:39:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:39:49.076 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:39:49.076 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:39:49.077 ThaliTest[825:1319847] client:, found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:40:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:40:19.073 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:40:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:40:19.080 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:40:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:40:49.077 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:40:49.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:40:49.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:41:19.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:41:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:41:19.078 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
2015-12-14 22:41:19.078 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:41:49.044 ThaliTest[825:1319847] multipeer session: restart
,2015-12-14 22:41:49.075 ThaliTest[825:1319847] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:41:49.077 ThaliTest[825:1319847] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:41:49.078 ThaliTest[825:1319847] client: found peer: Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:42:19.044 ThaliTest[825:1319847] multipeer session: restart

```
