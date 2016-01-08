#### Test 55467363832a26e_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DE0DFAF5-3957-41B0-89FD-913FB72AA024/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DE0DFAF5-3957-41B0-89FD-913FB72AA024/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E519DFA-BA62-4FF4-ACEC-347929FD7918/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50655"
,(lldb)     command script import "/tmp/DE0DFAF5-3957-41B0-89FD-913FB72AA024/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:50:15.957 ThaliTest[1110:3601512] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88A9ED75-7CC2-4AEE-B4F9-03C3A30CF093/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:50:16.447 ThaliTest[1110:3601512] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:50:16.448 ThaliTest[1110:3601512] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:50:16.455 ThaliTest[1110:3601512] Unlimited access to network resources
,2016-01-08 17:50:16.466 ThaliTest[1110:3601512] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:50:26.943 ThaliTest[1110:3601512] Resetting plugins due to page load.
,2016-01-08 17:50:30.709 ThaliTest[1110:3601512] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E519DFA-BA62-4FF4-ACEC-347929FD7918/ThaliTest.app/www/index.html
,2016-01-08 17:50:30.925 ThaliTest[1110:3601512] JXcore Cordova plugin initializing
,2016-01-08 17:50:30.927 ThaliTest[1110:3601705] JXcore instance initializing
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
,2016-01-08 17:50:33.594 ThaliTest[1110:3601512] THREAD WARNING: ['JXcore'] took '156.854004' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2016-01-08 17:57:04.666 ThaliTest[1110:3601705] jxcore: startBroadcasting
,2016-01-08 17:57:04.680 ThaliTest[1110:3601705] server: starting Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:04.681 ThaliTest[1110:3601705] multipeer session: start timer: 0x1b38cf40
,2016-01-08 17:57:04.682 ThaliTest[1110:3601705] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-08 17:57:04.682 ThaliTest[1110:3601705] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-08 17:57:05.323 ThaliTest[1110:3601512] client: found peer: Apple-Iphone6-1.3GMDyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.3GMDyQ==, peerAvail,able: true
weAreDoneNow
,done, now sending data to server
,2016-01-08 17:57:06.219 ThaliTest[1110:3601512] client: found peer: Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:06.351 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.kFnM8A==
,teardown
,testFindPeers stopped
,2016-01-08 17:57:06.506 ThaliTest[1110:3601705] jxcore: stopBroadcasting
,2016-01-08 17:57:06.507 ThaliTest[1110:3601705] THEMultipeerSession stopping peer
,2016-01-08 17:57:06.507 ThaliTest[1110:3601705] multipeer session: stop timer
,2016-01-08 17:57:06.508 ThaliTest[1110:3601705] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 49608
,2016-01-08 17:57:06.563 ThaliTest[1110:3601705] jxcore: startBroadcasting
,2016-01-08 17:57:06.566 ThaliTest[1110:3601705] server: starting Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:06.566 ThaliTest[1110:3601705] multipeer session: start timer: 0x1b3951e0
2016-01-08 17:57:06.568 ThaliTest[1110:3601705] THEMultipeerSession initialized peer Apple-Iphone5-1
2016-01-08 17:57:06.568 ThaliTest[1110:3601705] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-08T16:57:06.585Z SendDataTCPServer.js: TCP/IP server is bound to port: 49608
,2016-01-08 17:57:06.677 ThaliTest[1110:3601512] client: found peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:06.677 ThaliTest[1110:3601512] client: found peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:06.678 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.kFnM8A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:06.687Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:06.688Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:06.688Z SendDataConnector.js: do connect now
,2016-01-08 17:57:06.690 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:06.691 ThaliTest[1110:3601705] client session: connect
,2016-01-08 17:57:06.692 ThaliTest[1110:3601705] client session: stateChange:0->1 Apple-IpadAir2-1.hiitZQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:07.811 ThaliTest[1110:3601512] client: lost peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.811 ThaliTest[1110:3601512] client session: onPeerLost: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.811 ThaliTest[1110:3601512] client sess,ion: onLinkFailure: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.811 ThaliTest[1110:3601512] client session: disconnect
2016-01-08 17:57:07.812 ThaliTest[1110:3601512] client session: stateChange:1->0 Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.812 T,haliTest[1110:3601512] client session: fireConnectCallback: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.812 ThaliTest[1110:3601512] jxcore: connect: fail: Peer disconnected
2016-01-08 17:57:07.813 ThaliTest[1110:3601512] client: lost peer: Apple-Iphone,5s-1.kFnM8A==
2016-01-08 17:57:07.813 ThaliTest[1110:3601512] client session: onPeerLost: Apple-Iphone5s-1.kFnM8A==
,2016-01-08T16:57:07.817Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T16:57:07.817Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T16:57:07.818Z SendDataConnector.js: tryAgain afer: 5000 ms.,
2016-01-08 17:57:07.818 ThaliTest[1110:3601512] client: found peer: Apple-Iphone6-1.g6FFQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":",Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.g6FFQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available:, true
,2016-01-08 17:57:07.913 ThaliTest[1110:3601512] client: found peer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:07.914 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.PGcCxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.lYAIVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:08.792 ThaliTest[1110:3601512] client: lost peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.793 ThaliTest[1110:3601512] client session: onPeerLost: Apple-Iphone6-1.3GMDyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08T16:57:12.827Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:12.829Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:17.832 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:17.833 ThaliTest[1110:3601705] jxcore: disconnect: fail
2016-01-08T16:57:17.833Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hiitZQ==
2016-01-08T16:57:17.834Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.hiitZQ== with availability status: true
2016-01-08T16:57:17.834Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:17.834Z SendDataConnector.js: do connect now
2016-01-08 17:57:17.835 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:17.836 ThaliTest[1110:3601705] client: connect: unreachable Apple-IpadAir2-1.hiitZQ==,
,2016-01-08 17:57:17.836 ThaliTest[1110:3601705] jxcore: connect: fail: Peer unreachable
2016-01-08T16:57:17.836Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:17.837Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:17.837Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:22.839Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:22.839Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:27.848 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:27.848 ThaliTest[1110:3601705] jxcore: disconnect: fail
2016-01-08T16:57:27.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hiitZQ==
2016-01-08T16:57:27.849Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.hiitZQ== with availability status: true
2016-01-08T16:57:27.850Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hiitZQ==
2016-01-08T16:57:27.850Z SendDataConnector.js: do connect now
,2016-01-08 17:57:27.851 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:27.852 ThaliTest[1110:3601705] client: connect: unreachable Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:27.852 ThaliTest[1110:3601705] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:27.852Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:27.853Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:27.853Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:32.863Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:32.864Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:36.568 ThaliTest[1110:3601512] multipeer session: restart
,2016-01-08 17:57:36.603 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:36.603 ThaliTest[1110:3601512] client: found peer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:36.604 ThaliTest[1110:3601512] client: found peer: Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:37.875 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:37.875 ThaliTest[1110:3601705] jxcore: disconnect: fail
2016-01-08T16:57:37.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:37.877Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.hiitZQ== with availability status: true
2016-01-08T16:57:37.877Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hiitZQ==
2016-01-08T16:57:37.878Z SendDataConnector.js: do connect now
,2016-01-08 17:57:37.878 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:37.878 ThaliTest[1110:3601705] client: connect: unreachable Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:37.879 ThaliTest[1110:3601705] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:37.879Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:37.880Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:37.880Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:42.884Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hiitZQ==
,2016-01-08T16:57:42.885Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:43.804 ThaliTest[1110:3601512] client: lost peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:43.805 ThaliTest[1110:3601512] client session: onPeerLost: Apple-Iphone5s-1.PGcCxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:47.893 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:47.894 ThaliTest[1110:3601705] jxcore: disconnect: fail
2016-01-08T16:57:47.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hiitZQ==
2,016-01-08T16:57:47.895Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.hiitZQ== with availability status: true
2016-01-08T16:57:47.895Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hiitZQ==
2016-01-08T16:57:47.895Z SendDataConnector.js: do connect now
,2016-01-08 17:57:47.896 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:47.897 ThaliTest[1110:3601705] client: connect: unreachable Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:47.897 ThaliTest[1110:3601705] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:47.897Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:47.898Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-08T16:57:47.899Z SendDataConnector.js: CLIENT S,top now
2016-01-08 17:57:47.899 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:47.900 ThaliTest[1110:3601705] jxcore: disconnect: fail
2016-01-08T16:57:47.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hi,itZQ==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1.g6FFQA==
2016-01-08T16:57:47.902Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.g6FFQA==
,2016-01-08T16:57:47.902Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.g6FFQA==
2016-01-08T16:57:47.902Z SendDataConnector.js: do connect now
,2016-01-08 17:57:47.903 ThaliTest[1110:3601705] jxcore: connect Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:47.903 ThaliTest[1110:3601705] client session: connect
2016-01-08 17:57:47.903 ThaliTest[1110:3601705] client session: stateChange:0->1 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:48.567 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.PGcCxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:49.299 ThaliTest[1110:3601512] multipeer session: reset timer
2016-01-08 17:57:49.299 ThaliTest[1110:3601512] multipeer session: stop timer
2016-01-08 17:57:49.299 ThaliTest[1110:3601512] multipeer session: start timer: 0x1b3951e0
2016-01-08 17:57:49.300 ThaliTest[1110:3601512] server session: connect
2016-01-08 17:57:49.300 ThaliTest[1110:3601512] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 17:57:49.307 ThaliTest[1110:3601512] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 17:57:51.921 ThaliTest[1110:3603037] client session: connected
2016-01-08 17:57:51.923 ThaliTest[1110:3603037] client session: stateChange:1->2 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:51.928 ThaliTest[1110:3603037] client session: fireConnectCallback: Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:51.930 ThaliTest[1110:3603037] jxcore: connect: success
,2016-01-08T16:57:51.932Z SendDataConnector.js: CLIENT connected to 49613, error: null
,2016-01-08T16:57:51.932Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:57:51.935 ThaliTest[1110:3601512] client: relay established
,2016-01-08 17:57:51.937 ThaliTest[1110:3601512] client: new accepted socket: 0x1b468760
,2016-01-08T16:57:51.950Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 17:57:52.699 ThaliTest[1110:3603021] server session: connected
2016-01-08 17:57:52.699 ThaliTest[1110:3603021] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 17:57:52.721 ThaliTest[1110:3601512] server relay: connected (to port: 49608)
,2016-01-08T16:57:52.953Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:57:52.988Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T16:57:53.035Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T16:57:53.062Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T16:57:53.089Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T16:57:53.126Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:57:53.127Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:57:53.129Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:57:53.129Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:53.130 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:53.131 ThaliTest[1110:3601705] client session: disconnectFromPeer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:53.131 ThaliTest[1110:3601705] client session: disconnect
20,16-01-08 17:57:53.131 ThaliTest[1110:3601705] client session: stateChange:2->0 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:53.139 ThaliTest[1110:3601705] jxcore: disconnect: success
2016-01-08T16:57:53.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.g6FFQA==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipad,Air2-1.lYAIVQ==
2016-01-08T16:57:53.140Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:53.141Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:53.141Z SendDataConnecto,r.js: do connect now
2016-01-08 17:57:53.141 ThaliTest[1110:3601705] jxcore: connect Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:53.141 ThaliTest[1110:3601705] client session: connect
2016-01-08 17:57:53.142 ThaliTest[1110:3601705] client session: stateC,hange:0->1 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08T16:57:53.231Z SendDataTCPServer.js: TCP/IP server has received 10666 bytes of data
,2016-01-08T16:57:53.246Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-08T16:57:53.262Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-08T16:57:53.276Z SendDataTCPServer.js: TCP/IP server has received 42705 bytes of data
,2016-01-08T16:57:53.294Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-08T16:57:53.306Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T16:57:53.323Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-08T16:57:53.350Z SendDataTCPServer.js: TCP/IP server has received 82125 bytes of data
,2016-01-08T16:57:53.369Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T16:57:53.385Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:57:53.486 ThaliTest[1110:3603036] server session: not connected Apple-Iphone5s-1
,2016-01-08 17:57:57.297 ThaliTest[1110:3603021] client session: connected
2016-01-08 17:57:57.298 ThaliTest[1110:3603021] client session: stateChange:1->2 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:57.330 ThaliTest[1110:3603023] client session: fireConnectCallback: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:57.330 ThaliTest[1110:3603023] jxcore: connect: success
2016-01-08T16:57:57.331Z SendDataConnector.js: CLIENT connected to 496,17, error: null
2016-01-08T16:57:57.331Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:57:57.333 ThaliTest[1110:3601512] client: relay established
2016-01-08 17:57:57.334 ThaliTest[1110:3601512] client: new accepted socket: 0x1b3a52c0
,2016-01-08T16:57:57.346Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:57:58.530Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:57:58.531Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:57:58.532Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:57:58.533Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:58.534 ThaliTest[1110:3601705] jxcore: disconnect
2016-01-08 17:57:58.534 ThaliTest[1110:3601705] client session: disconnectFromPeer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:58.535 ThaliTest[1110:3601705] client session: disconnect
2,016-01-08 17:57:58.535 ThaliTest[1110:3601705] client session: stateChange:2->0 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:58.543 ThaliTest[1110:3601705] jxcore: disconnect: success
2016-01-08T16:57:58.543Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.lYAIVQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one5s-1.PGcCxg==
2016-01-08T16:57:58.544Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.PGcCxg==
2016-01-08T16:57:58.544Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.PGcCxg==
2016-01-08T16:57:58.545Z SendDataConnect,or.js: do connect now
2016-01-08 17:57:58.545 ThaliTest[1110:3601705] jxcore: connect Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:58.545 ThaliTest[1110:3601705] client session: connect
2016-01-08 17:57:58.546 ThaliTest[1110:3601705] client session: state,Change:0->1 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:02.131 ThaliTest[1110:3603023] client session: connected
2016-01-08 17:58:02.131 ThaliTest[1110:3603023] client session: stateChange:1->2 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:02.138 ThaliTest[1110:3603023] client session: fireConnectCallback: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:58:02.138 ThaliTest[1110:3603023] jxcore: connect: success
2016-01-08T16:58:02.139Z SendDataConnector.js: CLIENT connected to 496,20, error: null
2016-01-08T16:58:02.139Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:02.142 ThaliTest[1110:3601512] client: relay established
2016-01-08 17:58:02.142 ThaliTest[1110:3601512] client: new accepted socket: 0x1b4723a0
,2016-01-08T16:58:02.154Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 17:58:02.345 ThaliTest[1110:3601512] multipeer session: reset timer
2016-01-08 17:58:02.345 ThaliTest[1110:3601512] multipeer session: stop timer
2016-01-08 17:58:02.346 ThaliTest[1110:3601512] multipeer session: start timer: 0x1b3951e0
2016-01-08 17:58:02.346 ThaliTest[1110:3601512] server session: connect
2016-01-08 17:58:02.346 ThaliTest[1110:3601512] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-08 17:58:02.353 ThaliTest[1110:3601512] server: accepting invitation Apple-Iphone6-1
,2016-01-08T16:58:03.326Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T16:58:03.417Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T16:58:03.457Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T16:58:03.517Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08 17:58:03.702 ThaliTest[1110:3601512] multipeer session: reset timer
2016-01-08 17:58:03.702 ThaliTest[1110:3601512] multipeer session: stop timer
2016-01-08 17:58:03.702 ThaliTest[1110:3601512] multipeer session: start timer: 0x1b3951e0
2016-01-08 17:58:03.702 ThaliTest[1110:3601512] server session: connect
2016-01-08 17:58:03.703 ThaliTest[1110:3601512] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 17:58:03.709 ThaliTest[1110:3601512] server: accepting invitation Apple-IpadAir2-1
,2016-01-08T16:58:03.744Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:58:03.745Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T16:58:03.745Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:58:03.745Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:03.746 ThaliTest[1110:3601705] jxcore: disconnect
,2016-01-08 17:58:03.750 ThaliTest[1110:3601705] client session: disconnectFromPeer: Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:03.752 ThaliTest[1110:3601705] client session: disconnect
,2016-01-08 17:58:03.754 ThaliTest[1110:3601705] client session: stateChange:2->0 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:03.875 ThaliTest[1110:3601705] jxcore: disconnect: success
,2016-01-08T16:58:03.875Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.PGcCxg==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T16:58:03.904Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:58:03.904Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:04.961 ThaliTest[1110:3603036] server session: connected
2016-01-08 17:58:04.961 ThaliTest[1110:3603036] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 17:58:05.013 ThaliTest[1110:3601512] server relay: connected (to port: 49608)
,2016-01-08T16:58:05.018Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:58:05.544Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-08T16:58:05.558Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-08T16:58:05.573Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-08T16:58:05.588Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-08T16:58:05.601Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-08T16:58:05.616Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-08T16:58:05.630Z SendDataTCPServer.js: TCP/IP server has received 77745 bytes of data
,2016-01-08T16:58:05.671Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-08T16:58:05.686Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T16:58:05.738Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:05.829 ThaliTest[1110:3603111] server session: not connected Apple-Iphone6-1
,2016-01-08 17:58:07.182 ThaliTest[1110:3603111] server session: connected
2016-01-08 17:58:07.182 ThaliTest[1110:3603111] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 17:58:07.190 ThaliTest[1110:3601512] server relay: connected (to port: 49608)
,2016-01-08T16:58:07.196Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:58:07.669Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T16:58:07.685Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-08T16:58:07.701Z SendDataTCPServer.js: TCP/IP server has received 28399 bytes of data
,2016-01-08T16:58:07.715Z SendDataTCPServer.js: TCP/IP server has received 42563 bytes of data
,2016-01-08T16:58:07.730Z SendDataTCPServer.js: TCP/IP server has received 55845 bytes of data
,2016-01-08T16:58:07.746Z SendDataTCPServer.js: TCP/IP server has received 67819 bytes of data
,2016-01-08T16:58:07.762Z SendDataTCPServer.js: TCP/IP server has received 86292 bytes of data
,2016-01-08T16:58:07.776Z SendDataTCPServer.js: TCP/IP server has received 99645 bytes of data
,2016-01-08T16:58:07.790Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:07.828 ThaliTest[1110:3603036] server session: not connected Apple-IpadAir2-1
,2016-01-08 17:58:33.703 ThaliTest[1110:3601512] multipeer session: restart
,2016-01-08 17:58:33.736 ThaliTest[1110:3601512] client: found peer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:58:33.736 ThaliTest[1110:3601512] client: found peer: Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:58:33.744 ThaliTest[1110:3601512] client: found peer: Apple-Iphone5s-1.PGcCxg==
,teardown
,testSendData stopped
,2016-01-08 17:58:37.518 ThaliTest[1110:3601705] jxcore: stopBroadcasting
2016-01-08 17:58:37.519 ThaliTest[1110:3601705] THEMultipeerSession stopping peer
2016-01-08 17:58:37.519 ThaliTest[1110:3601705] multipeer session: stop timer
2016-01-08 17:58:37.519 ThaliTest[1110:3601705] server session: disconnect
2016-01-08 17:58:37.520 ThaliTest[1110:3601705] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 17:58:37.525 ThaliTest[1110:3601705] server session: disconnect
2016-01-08 17:58:37.525 ThaliTest[1110:3601705] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-08 17:58:37.527 ThaliTest[1110:3601705] server session: disconnect
2016-,01-08 17:58:37.527 ThaliTest[1110:3601705] server session: stateChange:2->0 Apple-Iphone5s-1
2016-01-08 17:58:37.532 ThaliTest[1110:3601705] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
