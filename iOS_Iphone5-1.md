#### Test 50650278b44f053_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/98138E90-7703-4C07-8086-870D889F4805/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/98138E90-7703-4C07-8086-870D889F4805/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/618F1423-91DC-4672-B63A-0C9F70CD07ED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58763"
,(lldb)     command script import "/tmp/98138E90-7703-4C07-8086-870D889F4805/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 18:39:48.464 ThaliTest[264:135789] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B4BA97F-9B79-40FE-8538-487082AC8D51/Library/Cookies/Cookies.binarycookies
,2015-12-16 18:39:48.596 ThaliTest[264:135789] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 18:39:48.598 ThaliTest[264:135789] Multi-tasking -> Device: YES, App: YES
,2015-12-16 18:39:48.605 ThaliTest[264:135789] Unlimited access to network resources
,2015-12-16 18:39:48.618 ThaliTest[264:135789] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 18:39:58.881 ThaliTest[264:135789] Resetting plugins due to page load.
,2015-12-16 18:40:02.992 ThaliTest[264:135789] Finished load of: file:///var/mobile/Containers/Bundle/Application/618F1423-91DC-4672-B63A-0C9F70CD07ED/ThaliTest.app/www/index.html
,2015-12-16 18:40:03.204 ThaliTest[264:135789] JXcore Cordova plugin initializing
,2015-12-16 18:40:03.206 ThaliTest[264:135980] JXcore instance initializing
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
,2015-12-16 18:40:05.677 ThaliTest[264:135789] THREAD WARNING: ['JXcore'] took '152.626221' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 18:46:33.809 ThaliTest[264:135980] jxcore: startBroadcasting
,2015-12-16 18:46:33.821 ThaliTest[264:135980] server: starting Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:33.822 ThaliTest[264:135980] multipeer session: start timer: 0x1a3cdb00
,2015-12-16 18:46:33.822 ThaliTest[264:135980] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6761
,2015-12-16 18:46:33.823 ThaliTest[264:135980] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 18:46:34.931 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.xtukLA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT5378.xtukLA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 18:46:36.364 ThaliTest[264:135980] jxcore: stopBroadcasting
2015-12-16 18:46:36.364 ThaliTest[264:135980] THEMultipeerSession stopping peer
2015-12-16 18:46:36.364 ThaliTest[264:135980] multipeer session: stop timer
2015-12-16 18:46:36.364 Th,aliTest[264:135980] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50700
,2015-12-16 18:46:36.430 ThaliTest[264:135980] jxcore: startBroadcasting
,2015-12-16 18:46:36.434 ThaliTest[264:135980] server: starting Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:46:36.435 ThaliTest[264:135980] multipeer session: start timer: 0x1a3d9590
2015-12-16 18:46:36.436 ThaliTest[264:135980] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT6761
2015-12-16 18:46:36.436 ThaliTest[264:135980] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-16T17:46:36.451Z SendDataTCPServer.js: TCP/IP server is bound to port: 50700
,2015-12-16 18:46:37.416 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.xtukLA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:37.419Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:37.420Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:37.420Z SendDataConnector.js: do connect now
,2015-12-16 18:46:37.421 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.421 ThaliTest[264:135980] client session: connect
2015-12-16 18:46:37.422 ThaliTest[264:135980] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT5378.xtukLA==
,2015-12-16 18:46:37.670 ThaliTest[264:135789] client: lost peer: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.670 ThaliTest[264:135789] client session: onPeerLost: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.670 ThaliTest[264:135789] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.670 ThaliTest[264:135789] client session: disconnect
2015-12-16 18:46:37.670 ThaliTest[264:135789] client session: stateChange:1->0 Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:37.673 ThaliTest[264:135789] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:37.673 ThaliTest[264:135789] jxcore: connect: fail: Peer disconnected
2015-12-16T17:46:37.674Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-16T17:46:37.675Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:46:37.675Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.xtukLA==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 18:46:37.682 ThaliTest[264:135789] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 18:46:38.231 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:46:38.232 ThaliTest[264:135789] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6682.xKUG+w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16T17:46:42.680Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:42.681Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:47.684 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:46:47.685 ThaliTest[264:135980] jxcore: disconnect: fail
2015-12-16T17:46:47.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:46:47.686Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:46:47.687Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:47.687Z SendDataConnector.js: do connect now
2015-12-16 18:46:47.688 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:47.688 ThaliTest[264:135980] client: connect: unreachable Apple-IpadAir2-1_PT537,8.xtukLA==
2015-12-16 18:46:47.688 ThaliTest[264:135980] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:46:47.689Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:46:47.689Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T17:46:47.689Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:46:52.691Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:46:52.691Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:46:57.697 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:46:57.698 ThaliTest[264:135980] jxcore: disconnect: fail
2015-12-16T17:46:57.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:46:57.699Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:46:57.699Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:46:57.699Z SendDataConnector.js: do connect now
,2015-12-16 18:46:57.700 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:57.701 ThaliTest[264:135980] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:46:57.701 ThaliTest[264:135980] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:46:57.701Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:46:57.702Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:46:57.702Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:02.703Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:02.704Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:06.437 ThaliTest[264:135789] multipeer session: restart
,2015-12-16 18:47:06.484 ThaliTest[264:135789] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:47:06.485 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:47:06.486 ThaliTest[264:135789] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:07.706 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:47:07.707 ThaliTest[264:135980] jxcore: disconnect: fail
2015-12-16T17:47:07.707Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:47:07.708Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:47:07.708Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:47:07.709Z SendDataConnector.js: do connect now
,2015-12-16 18:47:07.709 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:47:07.710 ThaliTest[264:135980] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:47:07.710 ThaliTest[264:135980] jxcore: connect: fail: Peer unreachable
,2015-12-16T17:47:07.711Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:07.711Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:07.711Z SendDataConnector.js: tryAgain afer: 5000 ms.
,appEnteredForeground wasn't registered
,2015-12-16T17:47:12.720Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16T17:47:12.721Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT5378.xtukLA==
,2015-12-16 18:47:17.731 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:47:17.732 ThaliTest[264:135980] jxcore: disconnect: fail
2015-12-16T17:47:17.732Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==,
2015-12-16T17:47:17.733Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT5378.xtukLA== with availability status: true
2015-12-16T17:47:17.733Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16T17:47:17.734Z SendDataConnector.js: do connect now
,2015-12-16 18:47:17.735 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:47:17.735 ThaliTest[264:135980] client: connect: unreachable Apple-IpadAir2-1_PT5378.xtukLA==
2015-12-16 18:47:17.735 ThaliTest[264:135980] jxcor,e: connect: fail: Peer unreachable
2015-12-16T17:47:17.736Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-16T17:47:17.736Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-16T17:47:17.738Z SendDataConnector.js: CLIENT Stop now
2015-12-16 18:47:17.738 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:47:17.738 ThaliTest[264:135980] jxcore: disconnect: fail
2015-12-16T17:47:17.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.xtukLA==
---- round done--------
,startWithNextDevice
device[2]: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:17.740Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16T17:47:17.740Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16T17:47:17.741Z SendDataConnector.js: do connect now
,2015-12-16 18:47:17.741 ThaliTest[264:135980] jxcore: connect Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:17.742 ThaliTest[264:135980] client session: connect
2015-12-16 18:47:17.742 ThaliTest[264:135980] client session: stateChange:0->1 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:25.003 ThaliTest[264:135789] multipeer session: reset timer
2015-12-16 18:47:25.003 ThaliTest[264:135789] multipeer session: stop timer
2015-12-16 18:47:25.003 ThaliTest[264:135789] multipeer session: start timer: 0x1a3d9590
2015-12-16 18:47:25.004 ThaliTest[264:135789] server session: connect
,2015-12-16 18:47:25.004 ThaliTest[264:135789] server session: stateChange:0->1 Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:25.014 ThaliTest[264:135789] server: accepting invitation Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:27.855 ThaliTest[264:135789] client: lost peer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:47:27.856 ThaliTest[264:135789] client session: onPeerLost: Apple-Iphone5s-1_PT6682.xKUG+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT6682.xKUG+w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 18:47:28.018 ThaliTest[264:137078] client session: connected
2015-12-16 18:47:28.019 ThaliTest[264:137078] client session: stateChange:1->2 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:28.053 ThaliTest[264:136769] client session: fireConnectCallback: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:28.053 ThaliTest[264:136769] jxcore: connect: success
2015-12-16T17:47:28.054Z SendDataConnector.js: CLIENT connected to 50707, error: null
2015-12-16T17:47:28.054Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:28.058 ThaliTest[264:135789] client: relay established
2015-12-16 18:47:28.058 ThaliTest[264:135789] client: new accepted socket: 0x1a4718d0
,2015-12-16T17:47:28.072Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16 18:47:28.538 ThaliTest[264:136769] server session: connected
2015-12-16 18:47:28.538 ThaliTest[264:136769] server session: stateChange:1->2 Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:28.549 ThaliTest[264:135789] server relay: connected (to port: 50700)
,2015-12-16T17:47:28.612Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:28.661Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-16T17:47:28.701Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T17:47:28.990Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T17:47:28.992Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-16T17:47:28.992Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:28.993Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:28.994 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:47:28.995 ThaliTest[264:135980] client session: disconnectFromPeer: Apple-Iphone6-1_PT3143.YUb0wA==
2015-12-16 18:47:28.996 ThaliTest[264:135980] client session: disconnect
2,015-12-16 18:47:28.996 ThaliTest[264:135980] client session: stateChange:2->0 Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:29.120 ThaliTest[264:135980] jxcore: disconnect: success
2015-12-16T17:47:29.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3143.YUb0wA==
---- round done--------
startWithNextDevice
device[3]: Apple,-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:47:29.122Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16T17:47:29.123Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16T17:47:29.123Z SendDataConnector.js: do connect now
,2015-12-16 18:47:29.123 ThaliTest[264:135980] jxcore: connect Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:47:29.124 ThaliTest[264:135980] client session: connect
,2015-12-16 18:47:29.124 ThaliTest[264:135980] client session: stateChange:0->1 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:47:29.132Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,appEnteringBackground wasn't registered
,2015-12-16 18:47:32.735 ThaliTest[264:137107] client session: connected
2015-12-16 18:47:32.737 ThaliTest[264:137107] client session: stateChange:1->2 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:47:32.754 ThaliTest[264:136781] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:47:32.754 ThaliTest[264:136781] jxcore: connect: success
,2015-12-16T17:47:32.756Z SendDataConnector.js: CLIENT connected to 50712, error: null
2015-12-16T17:47:32.757Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:32.759 ThaliTest[264:135789] client: relay established
,2015-12-16 18:47:32.759 ThaliTest[264:135789] client: new accepted socket: 0x1a3f5190
,2015-12-16T17:47:32.772Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:47:33.297Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T17:47:33.313Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-16T17:47:33.382Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:47:33.383Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T17:47:33.384Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:33.384Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:33.385 ThaliTest[264:135980] jxcore: disconnect
,2015-12-16 18:47:33.386 ThaliTest[264:135980] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:47:33.387 ThaliTest[264:135980] client session: disconnect
,2015-12-16 18:47:33.388 ThaliTest[264:135980] client session: stateChange:2->0 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:47:33.470 ThaliTest[264:135980] jxcore: disconnect: success
,2015-12-16T17:47:33.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.J91vGA==
---- round done--------
,startWithNextDevice
,2015-12-16 18:47:40.186 ThaliTest[264:136781] server session: not connected Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:44.380 ThaliTest[264:135789] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6682.xKUG+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
startWithNextDevice
device[4]: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16T17:47:44.383Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16T17:47:44.383Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:47:44.384Z SendDataConnector.js: do connect now
,2015-12-16 18:47:44.385 ThaliTest[264:135980] jxcore: connect Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:44.385 ThaliTest[264:135980] client session: connect
,2015-12-16 18:47:44.385 ThaliTest[264:135980] client session: stateChange:0->1 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:47.943 ThaliTest[264:136781] client session: connected
,2015-12-16 18:47:47.943 ThaliTest[264:136781] client session: stateChange:1->2 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:47.972 ThaliTest[264:137273] client session: fireConnectCallback: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:47.972 ThaliTest[264:137273] jxcore: connect: success
,2015-12-16T17:47:47.974Z SendDataConnector.js: CLIENT connected to 50716, error: null
,2015-12-16T17:47:47.974Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:47:47.975 ThaliTest[264:135789] client: relay established
2015-12-16 18:47:47.977 ThaliTest[264:135789] client: new accepted socket: 0x1a3f5ea0
,2015-12-16T17:47:47.989Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:47:48.573Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16T17:47:48.914Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-16T17:47:48.929Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:47:48.929Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T17:47:48.931Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:48.932Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:48.933 ThaliTest[264:135980] jxcore: disconnect
2015-12-16 18:47:48.933 ThaliTest[264:135980] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:47:48.933 ThaliTest[264:135980] client session: disconnect
,2015-12-16 18:47:48.933 ThaliTest[264:135980] client session: stateChange:2->0 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:47:49.013 ThaliTest[264:135980] jxcore: disconnect: success
2015-12-16T17:47:49.013Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6682.xKUG+w==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-16T17:47:49.020Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:47:49.020Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:47:54.790 ThaliTest[264:135789] client: lost peer: Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:47:54.793 ThaliTest[264:135789] client session: onPeerLost: Apple-Iphone6-1_PT3143.YUb0wA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-16 18:47:54.796 ThaliTest[264:135789] client: lost peer: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:47:54.797 ThaliTest[264:135789] client session: onPeerLost: Apple-IpadAir2-1_PT5378.J91vGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-16 18:47:55.004 ThaliTest[264:135789] multipeer session: restart
,2015-12-16 18:47:55.045 ThaliTest[264:135789] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.YUb0wA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-16 18:47:55.047 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":true}]
2015-12-16 18:47:55.051 ThaliTest[264:135789] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
startWithNextDevice
,2015-12-16 18:48:02.117 ThaliTest[264:135789] multipeer session: reset timer
2015-12-16 18:48:02.117 ThaliTest[264:135789] multipeer session: stop timer
2015-12-16 18:48:02.117 ThaliTest[264:135789] multipeer session: start timer: 0x1a3d9590
2015-12-16 ,18:48:02.118 ThaliTest[264:135789] server session: connect
2015-12-16 18:48:02.118 ThaliTest[264:135789] server session: stateChange:0->1 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:02.125 ThaliTest[264:135789] server: accepting invitation Apple-Iphone6-1_PT3143
,2015-12-16 18:48:04.779 ThaliTest[264:137257] server session: connected
2015-12-16 18:48:04.779 ThaliTest[264:137257] server session: stateChange:1->2 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:04.784 ThaliTest[264:135789] server relay: connected (to port: 50700)
,2015-12-16T17:48:04.795Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:48:05.160Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-16T17:48:05.175Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-16T17:48:05.189Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-16T17:48:05.204Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-16T17:48:05.218Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:48:05.256 ThaliTest[264:136769] server session: not connected Apple-Iphone6-1_PT3143
,2015-12-16 18:48:32.119 ThaliTest[264:135789] multipeer session: restart
,2015-12-16 18:48:32.161 ThaliTest[264:135789] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:48:32.162 ThaliTest[264:135789] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:32.361 ThaliTest[264:135789] client: found peer: Apple-Iphone6-1_PT3143.YUb0wA==
,teardown
,testSendData stopped
,2015-12-16 18:48:55.197 ThaliTest[264:135980] jxcore: stopBroadcasting
2015-12-16 18:48:55.198 ThaliTest[264:135980] THEMultipeerSession stopping peer
2015-12-16 18:48:55.198 ThaliTest[264:135980] multipeer session: stop timer
2015-12-16 18:48:55.198 Th,aliTest[264:135980] server session: disconnect
2015-12-16 18:48:55.198 ThaliTest[264:135980] server session: stateChange:2->0 Apple-IpadAir2-1_PT5378
,2015-12-16 18:48:55.204 ThaliTest[264:135980] server session: disconnect
2015-12-16 18:48:55.204 ThaliTest[264:135980] server session: stateChange:2->0 Apple-Iphone6-1_PT3143
,2015-12-16 18:48:55.222 ThaliTest[264:135980] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T17:48:55.239Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:55.242Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:55.242Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
