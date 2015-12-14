#### Test 5065027870036d7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/408C76AE-5D02-499A-AF87-72A882D385C5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/408C76AE-5D02-499A-AF87-72A882D385C5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027870036d7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AEAC81E3-05B5-4D0F-8060-669C2B9E045F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55973"
,(lldb)     command script import "/tmp/408C76AE-5D02-499A-AF87-72A882D385C5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 22:15:14.331 ThaliTest[1103:1181965] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9372C86B-0585-4D00-AC2E-B8DFBF0FAE5E/Library/Cookies/Cookies.binarycookies
,2015-12-14 22:15:14.679 ThaliTest[1103:1181965] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 22:15:14.680 ThaliTest[1103:1181965] Multi-tasking -> Device: YES, App: YES
,2015-12-14 22:15:14.689 ThaliTest[1103:1181965] Unlimited access to network resources
,2015-12-14 22:15:14.698 ThaliTest[1103:1181965] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 22:15:24.175 ThaliTest[1103:1181965] Resetting plugins due to page load.
,2015-12-14 22:15:27.892 ThaliTest[1103:1181965] Finished load of: file:///var/mobile/Containers/Bundle/Application/AEAC81E3-05B5-4D0F-8060-669C2B9E045F/ThaliTest.app/www/index.html
,2015-12-14 22:15:28.075 ThaliTest[1103:1181965] JXcore Cordova plugin initializing
,2015-12-14 22:15:28.076 ThaliTest[1103:1182187] JXcore instance initializing
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
,2015-12-14 22:15:29.049 ThaliTest[1103:1181965] THREAD WARNING: ['JXcore'] took '70.735840' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 22:20:20.441 ThaliTest[1103:1182187] jxcore: startBroadcasting
,2015-12-14 22:20:20.458 ThaliTest[1103:1182187] server: starting Apple-IpadAir2-1_PT1227.oXDKcw==
,2015-12-14 22:20:20.459 ThaliTest[1103:1182187] multipeer session: start timer: 0x16c5b320
,2015-12-14 22:20:20.460 ThaliTest[1103:1182187] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1227
,2015-12-14 22:20:20.462 ThaliTest[1103:1182187] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 22:20:21.179 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT2471.QNnKyw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-14 22:20:21.562 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.QDCMPg==
,2015-12-14 22:20:24.243 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.6YBI9g==
,teardown
,testFindPeers stopped
,2015-12-14 22:20:24.630 ThaliTest[1103:1182187] jxcore: stopBroadcasting
,2015-12-14 22:20:24.631 ThaliTest[1103:1182187] THEMultipeerSession stopping peer
,2015-12-14 22:20:24.631 ThaliTest[1103:1182187] multipeer session: stop timer
,2015-12-14 22:20:24.632 ThaliTest[1103:1182187] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 58076
,2015-12-14 22:20:24.698 ThaliTest[1103:1182187] jxcore: startBroadcasting
,2015-12-14 22:20:24.703 ThaliTest[1103:1182187] server: starting Apple-IpadAir2-1_PT1227.Q+hGxg==
,2015-12-14 22:20:24.704 ThaliTest[1103:1182187] multipeer session: start timer: 0x16d61650
2015-12-14 22:20:24.705 ThaliTest[1103:1182187] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1227
2015-12-14 22:20:24.705 ThaliTest[1103:1182187] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-14T21:20:24.711Z SendDataTCPServer.js: TCP/IP server is bound to port: 58076
,2015-12-14 22:20:25.708 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:25.709 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.6YBI9g==
2015-12-14 22:20:25.709 ThaliTest[1103:1181965] clien,t: found peer: Apple-IpadAir2-1_PT1227.oXDKcw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_,PT2471.QNnKyw==
,2015-12-14T21:20:25.713Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:25.714Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14T21:20:25.715Z SendDataConnector.js: do connect now
,2015-12-14 22:20:25.716 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:25.717 ThaliTest[1103:1182187] client session: connect
2015-12-14 22:20:25.717 ThaliTest[1103:1182187] client session: stateChange:0->1 Apple-Iphone5-1_PT2471.QNnKyw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.6YBI9g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 22:20:25.836 ThaliTest[1103:1181965] client: lost peer: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:25.837 ThaliTest[1103:1181965] client session: onPeerLost: Apple-IpadAir2-1_PT1227.oXDKcw==
2015-12-14 22:20:25.837 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:20:25.838 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1227.oXDKcw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.1SWIqQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.xdA4DQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 22:20:25.881 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4552.wIXR0A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 22:20:28.323 ThaliTest[1103:1181965] client: lost peer: Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:28.323 ThaliTest[1103:1181965] client session: onPeerLost: Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:28.324 ThaliTest[1103:1181965] client session: onLinkFailure: Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:28.324 ThaliTest[1103:1181965] client session: disconnect
2015-12-14 22:20:28.324 ThaliTest[1103:1181965] client session: stateChange:1->0 Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:28.325 ThaliTest[1103:1181965] client session: fireConnectCallback: Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:28.325 ThaliTest[1103:1181965] jxcore: connect: fail: Peer disconnected
,2015-12-14T21:20:28.327Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-14T21:20:28.328Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T21:20:28.329Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2471.QNnKyw==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 22:20:30.728 ThaliTest[1103:1181965] client: lost peer: Apple-Iphone5s-1_PT4984.6YBI9g==
2015-12-14 22:20:30.729 ThaliTest[1103:1181965] client session: onPeerLost: Apple-Iphone5s-1_PT4984.6YBI9g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4984.6YBI9g==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-14T21:20:33.335Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:33.336Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:38.349 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:20:38.350 ThaliTest[1103:1182187] jxcore: disconnect: fail
,2015-12-14T21:20:38.351Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:38.351Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2471.QNnKyw== with availability status: true
,2015-12-14T21:20:38.352Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:38.353Z SendDataConnector.js: do connect now
,2015-12-14 22:20:38.354 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:38.354 ThaliTest[1103:1182187] client: connect: unreachable Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:38.355 ThaliTest[1103:1182187] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:38.356Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:38.356Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:20:38.357Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:43.357Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:43.358Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:48.363 ThaliTest[1103:1182187] jxcore: disconnect
2015-12-14 22:20:48.364 ThaliTest[1103:1182187] jxcore: disconnect: fail
,2015-12-14T21:20:48.365Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:48.366Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2471.QNnKyw== with availability status: true
,2015-12-14T21:20:48.366Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:48.367Z SendDataConnector.js: do connect now
,2015-12-14 22:20:48.368 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14 22:20:48.369 ThaliTest[1103:1182187] client: connect: unreachable Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:48.369 ThaliTest[1103:1182187] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:48.371Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T21:20:48.371Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:20:48.372Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:20:53.381Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:20:53.381Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:54.706 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:20:54.735 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:20:54.735 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:20:54.737 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:20:58.383 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:20:58.383 ThaliTest[1103:1182187] jxcore: disconnect: fail
,2015-12-14T21:20:58.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14T21:20:58.385Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2471.QNnKyw== with availability status: ,true
2015-12-14T21:20:58.385Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14T21:20:58.386Z SendDataConnector.js: do connect now
,2015-12-14 22:20:58.386 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:58.387 ThaliTest[1103:1182187] client: connect: unreachable Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:20:58.388 ThaliTest[1103:1182187] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:20:58.388Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:20:58.389Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T21:20:58.389Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T21:21:03.396Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:21:03.397Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:21:08.407 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:21:08.408 ThaliTest[1103:1182187] jxcore: disconnect: fail
,2015-12-14T21:21:08.409Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.QNnKyw==
2015-12-14T21:21:08.409Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2471.QNnKyw== with availability status: ,true
2015-12-14T21:21:08.410Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14T21:21:08.410Z SendDataConnector.js: do connect now
,2015-12-14 22:21:08.411 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:21:08.412 ThaliTest[1103:1182187] client: connect: unreachable Apple-Iphone5-1_PT2471.QNnKyw==
,2015-12-14 22:21:08.412 ThaliTest[1103:1182187] jxcore: connect: fail: Peer unreachable
,2015-12-14T21:21:08.413Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T21:21:08.413Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-14T21:21:08.415Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 22:21:08.416 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:21:08.417 ThaliTest[1103:1182187] jxcore: disconnect: fail
,2015-12-14T21:21:08.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.QNnKyw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:08.421Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:08.422Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14T21:21:08.423Z SendDataConnector.js: do connect now
,2015-12-14 22:21:08.424 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:08.424 ThaliTest[1103:1182187] client session: connect
,2015-12-14 22:21:08.425 ThaliTest[1103:1182187] client session: stateChange:0->1 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:11.489 ThaliTest[1103:1182792] client session: connected
2015-12-14 22:21:11.489 ThaliTest[1103:1182792] client session: stateChange:1->2 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:11.539 ThaliTest[1103:1182803] client session: fireConnectCallback: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:11.539 ThaliTest[1103:1182803] jxcore: connect: success
,2015-12-14T21:21:11.541Z SendDataConnector.js: CLIENT connected to 58081, error: null
,2015-12-14T21:21:11.541Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:11.544 ThaliTest[1103:1181965] client: relay established
2015-12-14 22:21:11.545 ThaliTest[1103:1181965] client: new accepted socket: 0x16c66250
,2015-12-14T21:21:11.562Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:12.598Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T21:21:12.613Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T21:21:12.613Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T21:21:12.614Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T21:21:12.615Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:12.617 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:21:12.618 ThaliTest[1103:1182187] client session: disconnectFromPeer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:12.618 ThaliTest[1103:1182187] client session: disconnect
2015-12-14 22:21:12.619 ThaliTest[1103:1182187] client session: stateChange:2->0 Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:21:12.628 ThaliTest[1103:1182187] jxcore: disconnect: success
2015-12-14T21:21:12.629Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2471.1SWIqQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:12.630Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21:21:12.631Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14T21,:21:12.631Z SendDataConnector.js: do connect now
2015-12-14 22:21:12.632 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:12.632 ThaliTest[1103:1182187] client session: connect
,2015-12-14 22:21:12.636 ThaliTest[1103:1182187] client session: stateChange:0->1 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:15.646 ThaliTest[1103:1182818] client session: connected
,2015-12-14 22:21:15.647 ThaliTest[1103:1182818] client session: stateChange:1->2 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:15.707 ThaliTest[1103:1182803] client session: fireConnectCallback: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:15.708 ThaliTest[1103:1182803] jxcore: connect: success
,2015-12-14T21:21:15.709Z SendDataConnector.js: CLIENT connected to 58084, error: null
,2015-12-14T21:21:15.709Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:15.712 ThaliTest[1103:1181965] client: relay established
2015-12-14 22:21:15.712 ThaliTest[1103:1181965] client: new accepted socket: 0x16d6dec0
,2015-12-14T21:21:15.726Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:16.041Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T21:21:16.065Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T21:21:16.076Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T21:21:16.089Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T21:21:16.138Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T21:21:16.138Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T21:21:16.138Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:16.138Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:16.139 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:21:16.139 ThaliTest[1103:1182187] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:16.139 ThaliTest[1103:1182187] client session: disconnect
,2015-12-14 22:21:16.140 ThaliTest[1103:1182187] client session: stateChange:2->0 Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:21:16.143 ThaliTest[1103:1182187] jxcore: disconnect: success
,2015-12-14T21:21:16.144Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4984.xdA4DQ==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14T21:21:16.146Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:16.146Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14T21:21:16.146Z SendDataConnector.js: do connect now
,2015-12-14 22:21:16.146 ThaliTest[1103:1182187] jxcore: connect Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:16.147 ThaliTest[1103:1182187] client session: connect
,2015-12-14 22:21:16.147 ThaliTest[1103:1182187] client session: stateChange:0->1 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:19.879 ThaliTest[1103:1182817] client session: connected
2015-12-14 22:21:19.879 ThaliTest[1103:1182817] client session: stateChange:1->2 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:19.884 ThaliTest[1103:1182795] client session: fireConnectCallback: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:21:19.884 ThaliTest[1103:1182795] jxcore: connect: success
,2015-12-14T21:21:19.885Z SendDataConnector.js: CLIENT connected to 58087, error: null
,2015-12-14T21:21:19.886Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 22:21:19.889 ThaliTest[1103:1181965] client: relay established
2015-12-14 22:21:19.889 ThaliTest[1103:1181965] client: new accepted socket: 0x16d6c200
,2015-12-14T21:21:19.903Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T21:21:20.234Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T21:21:20.246Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T21:21:20.257Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T21:21:20.270Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T21:21:20.283Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T21:21:20.283Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-14T21:21:20.284Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:20.284Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:20.284 ThaliTest[1103:1182187] jxcore: disconnect
,2015-12-14 22:21:20.284 ThaliTest[1103:1182187] client session: disconnectFromPeer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:20.285 ThaliTest[1103:1182187] client session: disconnect
2015-12-14 22:21:20.285 ThaliTest[1103:1182187] client session: stateChange:2->0 Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:20.288 ThaliTest[1103:1182187] jxcore: disconnect: success
2015-12-14T21:21:20.288Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4552.wIXR0A==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
,done, now sending data to server
,2015-12-14T21:21:20.290Z SendDataConnector.js: CLIENT Stop now
2015-12-14T21:21:20.290Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 22:21:24.706 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:21:24.734 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:21:24.735 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:21:24.735 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:21:47.206 ThaliTest[1103:1181965] multipeer session: reset timer
2015-12-14 22:21:47.206 ThaliTest[1103:1181965] multipeer session: stop timer
2015-12-14 22:21:47.207 ThaliTest[1103:1181965] multipeer session: start timer: 0x16d61650
2015-12-14 22:21:47.207 ThaliTest[1103:1181965] server session: connect
2015-12-14 22:21:47.207 ThaliTest[1103:1181965] server session: stateChange:0->1 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:47.214 ThaliTest[1103:1181965] server: accepting invitation Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:49.815 ThaliTest[1103:1182888] server session: connected
2015-12-14 22:21:49.815 ThaliTest[1103:1182888] server session: stateChange:1->2 Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:49.852 ThaliTest[1103:1181965] server relay: connected (to port: 58076)
,2015-12-14T21:21:49.858Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:50.150Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T21:21:50.165Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-14T21:21:50.206Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-14T21:21:50.221Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-14T21:21:50.236Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:50.328 ThaliTest[1103:1182918] server session: not connected Apple-Iphone5s-1_PT4984
,2015-12-14 22:21:52.703 ThaliTest[1103:1181965] multipeer session: reset timer
,2015-12-14 22:21:52.703 ThaliTest[1103:1181965] multipeer session: stop timer
,2015-12-14 22:21:52.703 ThaliTest[1103:1181965] multipeer session: start timer: 0x16d61650
,2015-12-14 22:21:52.704 ThaliTest[1103:1181965] server session: connect
,2015-12-14 22:21:52.704 ThaliTest[1103:1181965] server session: stateChange:0->1 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:52.712 ThaliTest[1103:1181965] server: accepting invitation Apple-Iphone5-1_PT2471
,2015-12-14 22:21:55.392 ThaliTest[1103:1182897] server session: connected
,2015-12-14 22:21:55.392 ThaliTest[1103:1182897] server session: stateChange:1->2 Apple-Iphone5-1_PT2471
,2015-12-14 22:21:55.419 ThaliTest[1103:1181965] server relay: connected (to port: 58076)
,2015-12-14T21:21:55.428Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:55.982Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T21:21:55.996Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-14T21:21:56.037Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-14T21:21:56.052Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:56.157 ThaliTest[1103:1182888] server session: not connected Apple-Iphone5-1_PT2471
,2015-12-14 22:21:56.725 ThaliTest[1103:1181965] multipeer session: reset timer
2015-12-14 22:21:56.725 ThaliTest[1103:1181965] multipeer session: stop timer
2015-12-14 22:21:56.725 ThaliTest[1103:1181965] multipeer session: start timer: 0x16d61650
,2015-12-14 22:21:56.726 ThaliTest[1103:1181965] server session: connect
2015-12-14 22:21:56.726 ThaliTest[1103:1181965] server session: stateChange:0->1 Apple-Iphone6-1_PT4552
,2015-12-14 22:21:56.732 ThaliTest[1103:1181965] server: accepting invitation Apple-Iphone6-1_PT4552
,2015-12-14 22:21:59.393 ThaliTest[1103:1182918] server session: connected
2015-12-14 22:21:59.394 ThaliTest[1103:1182918] server session: stateChange:1->2 Apple-Iphone6-1_PT4552
,2015-12-14 22:21:59.445 ThaliTest[1103:1181965] server relay: connected (to port: 58076)
,2015-12-14T21:21:59.452Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T21:21:59.746Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T21:21:59.763Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-14T21:21:59.784Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-14T21:21:59.801Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 22:21:59.814 ThaliTest[1103:1182918] server session: not connected Apple-Iphone6-1_PT4552
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 22:22:16.681 ThaliTest[1103:1182187] jxcore: startBroadcasting
,2015-12-14 22:22:16.681 ThaliTest[1103:1182187] jxcore: startBroadcasting: failure
,weAreDoneNow
,done, now sending data to server
,done, now sending data to server
,2015-12-14 22:22:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:22:26.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:22:26.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:22:26.784 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:22:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:22:56.752 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:22:56.752 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:22:56.752 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:23:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:23:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:23:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:23:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:23:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:23:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:24:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:24:26.759 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:24:26.759 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:24:26.761 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:24:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:24:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:24:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:24:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:25:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:25:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:25:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:25:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:25:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:25:56.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:25:56.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:25:56.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,Connected to the server!
,2015-12-14 22:26:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:26:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:26:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:26:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:26:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:26:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:26:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:26:57.526 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:27:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:27:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:27:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:27:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:27:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:27:57.433 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:27:57.433 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:27:57.433 ThaliTest[1103:1181965] client,: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:28:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:28:26.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:28:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:28:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:28:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:28:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:28:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:28:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:29:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:29:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:29:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:29:27.000 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:29:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:29:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:29:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:29:56.816 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:30:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:30:26.753 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:30:26.753 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:30:26.753 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,Connected to the server!
,2015-12-14 22:30:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:30:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:30:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:30:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:31:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:31:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:31:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:31:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:31:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:31:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:31:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:31:56.928 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:32:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:32:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:32:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:32:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:32:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:32:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:32:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:33:08.453 ThaliTest[1103:1181965] client: lost peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:33:08.453 ThaliTest[1103:1181965] client session: onPeerLost: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:33:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:33:26.750 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:33:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:33:56.876 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:23.632 ThaliTest[1103:1181965] client: lost peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:34:23.632 ThaliTest[1103:1181965] client session: onPeerLost: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:34:39.470 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:39.476 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:39.481 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:34:39.558 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:34:56.726 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:34:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:34:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:34:56.759 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:35:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:35:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:35:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:35:26.757 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:35:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:35:56.754 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:35:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:35:56.988 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:36:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:36:26.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:36:26.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:36:26.796 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:36:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:36:56.753 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:36:56.753 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:36:56.758 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:37:26.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:37:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:37:26.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:37:26.758 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:37:56.727 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:37:56.755 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:37:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:37:56.756 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:38:26.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:38:26.741 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:38:26.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:38:26.886 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,timeout now
,2015-12-14 22:38:56.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:38:56.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:38:56.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:38:56.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:39:26.711 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:39:26.739 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:39:26.740 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:39:26.740 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:39:56.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:39:56.744 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:39:56.746 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:39:56.746 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:40:26.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:40:26.739 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:40:26.740 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:40:26.858 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:40:56.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:40:56.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:40:56.743 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:40:56.801 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:41:26.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:41:26.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:41:26.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
2015-12-14 22:41:26.743 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
,2015-12-14 22:41:56.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:41:56.742 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
2015-12-14 22:41:56.743 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:41:56.744 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==
,2015-12-14 22:42:26.712 ThaliTest[1103:1181965] multipeer session: restart
,2015-12-14 22:42:26.739 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5-1_PT2471.1SWIqQ==
2015-12-14 22:42:26.739 ThaliTest[1103:1181965] client: found peer: Apple-Iphone5s-1_PT4984.xdA4DQ==
,2015-12-14 22:42:26.952 ThaliTest[1103:1181965] client: found peer: Apple-Iphone6-1_PT4552.wIXR0A==

```
