#### Test 56204092c98eeae_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/126E7566-36A9-4FD1-8BEC-EE65C7D23135/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/126E7566-36A9-4FD1-8BEC-EE65C7D23135/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FE0B98B1-1BD7-4DE2-8DA3-2C64C16D2AAF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56518"
,(lldb)     command script import "/tmp/126E7566-36A9-4FD1-8BEC-EE65C7D23135/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 19:42:00.703 ThaliTest[1431:4663610] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/39A46943-D4E3-4FBF-8D4C-E8D5E6E9FB11/Library/Cookies/Cookies.binarycookies
,2016-01-15 19:42:01.053 ThaliTest[1431:4663610] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 19:42:01.054 ThaliTest[1431:4663610] Multi-tasking -> Device: YES, App: YES
,2016-01-15 19:42:01.059 ThaliTest[1431:4663610] Unlimited access to network resources
,2016-01-15 19:42:01.070 ThaliTest[1431:4663610] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 19:42:07.186 ThaliTest[1431:4663610] Resetting plugins due to page load.
,2016-01-15 19:42:09.035 ThaliTest[1431:4663610] Finished load of: file:///var/mobile/Containers/Bundle/Application/FE0B98B1-1BD7-4DE2-8DA3-2C64C16D2AAF/ThaliTest.app/www/index.html
,2016-01-15 19:42:09.243 ThaliTest[1431:4663610] JXcore Cordova plugin initializing
2016-01-15 19:42:09.246 ThaliTest[1431:4663736] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-15 19:48:22.245 ThaliTest[1431:4663736] jxcore: startBroadcasting
,2016-01-15 19:48:22.263 ThaliTest[1431:4663736] server: starting Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:22.264 ThaliTest[1431:4663736] multipeer session: start timer: 0x1abe8480
2016-01-15 19:48:22.264 ThaliTest[1431:4663736] THEMultipeerSessio,n initialized peer Apple-Iphone5-1_PT5004
2016-01-15 19:48:22.264 ThaliTest[1431:4663736] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-15 19:48:23.056 ThaliTest[1431:4663610] client: found peer: Apple-IpadAir2-1_PT6810.+fMbbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT6810.+fMbbA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2016-01-15 19:48:23.322 ThaliTest[1431:4663610] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:26.072 ThaliTest[1431:4663610] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
,teardown
testFindPeers stopped
2016-01-15 19:48:29.613 ThaliTest[1431:4663736] jxcore: stopBroadcasting
2016-01-15 19:48:29.613 ThaliTest[1431:4663736] THEMultipeerSession stopping peer
2016-01-15 19:48:29.613 ThaliTest[1431:4663736] multipeer session:, stop timer
2016-01-15 19:48:29.613 ThaliTest[1431:4663736] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"data,Timeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53235
,2016-01-15 19:48:29.656 ThaliTest[1431:4663736] jxcore: startBroadcasting
,2016-01-15 19:48:29.662 ThaliTest[1431:4663736] server: starting Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:48:29.666 ThaliTest[1431:4663736] multipeer session: start timer: 0x1abeabf0
,2016-01-15 19:48:29.674 ThaliTest[1431:4663736] THEMultipeerSession initialized peer Apple-Iphone5-1_PT5004
,2016-01-15 19:48:29.678 ThaliTest[1431:4663736] jxcore: startBroadcasting: success
StartBroadcasting started ok
2016-01-15 19:48:29.681 ThaliTest[1431:4663610] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
null
2016-01-15T18:48:29.684Z SendDataTC,PServer.js: TCP/IP server is bound to port: 53235
2016-01-15 19:48:29.684 ThaliTest[1431:4663610] client: found peer: Apple-IpadAir2-1_PT6810.+fMbbA==
,2016-01-15 19:48:29.685 ThaliTest[1431:4663610] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:29.687 ThaliTest[1431:4663610] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:29.699Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:29.700Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:29.700Z SendDataConnector.js: do connect now
,2016-01-15 19:48:29.701 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:29.702 ThaliTest[1431:4663736] client session: connect
,2016-01-15 19:48:29.703 ThaliTest[1431:4663736] client session: stateChange:0->1 Apple-Iphone5-1_PT5004.158h0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-15 19:48:30.840 ThaliTest[1431:4663610] client: lost peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.841 ThaliTest[1431:4663610] client session: onPeerLost: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.841 ThaliTest[1431:4663610], client session: onLinkFailure: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.841 ThaliTest[1431:4663610] client session: disconnect
2016-01-15 19:48:30.841 ThaliTest[1431:4663610] client session: stateChange:1->0 Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15 19:48:30.842 ThaliTest[1431:4663610] client session: fireConnectCallback: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.842 ThaliTest[1431:4663610] jxcore: connect: fail: Peer disconnected
2016-01-15T18:48:30.843Z SendDataConnector.js: CL,IENT connected to 0, error: Peer disconnected
2016-01-15T18:48:30.843Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-15T18:48:30.843Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":false}]
,2016-01-15 19:48:30.953 ThaliTest[1431:4663610] client: lost peer: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:30.953 ThaliTest[1431:4663610] client session: onPeerLost: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:30.954 ThaliTest[1431:466361,0] client: lost peer: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:30.955 ThaliTest[1431:4663610] client session: onPeerLost: Apple-Iphone6-1_PT3224.cXLr/Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(n,ull)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-15 19:48:31.400 ThaliTest[1431:4663610] client: lost peer: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:31.401 ThaliTest[1431:4663610] client session: onPeerLost: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:31.401 ThaliTest[1431:466361,0] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentif,ier":"Apple-Iphone6-1_PT3224.81B+Sg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:31.424 ThaliTest[1431:4663610] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.TN0Czw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2016-01-15 19:48:31.530 ThaliTest[1431:4663610] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.kDDcMw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2016-01-15T18:48:35.852Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:35.852Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:40.861 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:48:40.861 ThaliTest[1431:4663736] jxcore: disconnect: fail
2016-01-15T18:48:40.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:48:40.862Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:48:40.862Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15T18:48:40.862Z SendDataConnector.js: do connect now
,2016-01-15 19:48:40.863 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:40.863 ThaliTest[1431:4663736] client: connect: unreachable Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:40.863 ThaliTest[1431:4663736] j,xcore: connect: fail: Peer unreachable
2016-01-15T18:48:40.864Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-15T18:48:40.865Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:48:40.865Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:45.874Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:45.874Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:50.877 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:48:50.877 ThaliTest[1431:4663736] jxcore: disconnect: fail
2016-01-15T18:48:50.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:48:50.878Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:48:50.878Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15T18:48:50.878Z SendDataConnector.js: do connect now
2016-01-15 19:48:50.878 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:50.879 ThaliTest[1431:4663736] client: connect: unreachable Apple-Iphone5-1_PT50,04.158h0w==
2016-01-15 19:48:50.879 ThaliTest[1431:4663736] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:50.879Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:50.879Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer unreachable
2016-01-15T18:48:50.884Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:55.890Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:55.891Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:59.667 ThaliTest[1431:4663610] multipeer session: restart
,2016-01-15 19:48:59.700 ThaliTest[1431:4663610] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:48:59.700 ThaliTest[1431:4663610] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:48:59.701 ThaliTest[1431:4663610] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:00.898 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:49:00.899 ThaliTest[1431:4663736] jxcore: disconnect: fail
2016-01-15T18:49:00.899Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:49:00.899Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:49:00.899Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15T18:49:00.900Z SendDataConnector.js: do connect now
2016-01-15 19:49:00.900 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:00.900 ThaliTest[1431:4663736] client: connect: unreachable Apple-Iphone5-1_PT50,04.158h0w==
2016-01-15 19:49:00.900 ThaliTest[1431:4663736] jxcore: connect: fail: Peer unreachable
2016-01-15T18:49:00.900Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:49:00.901Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer unreachable
2016-01-15T18:49:00.903Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:49:05.912Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:49:05.913Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:49:10.914 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:49:10.914 ThaliTest[1431:4663736] jxcore: disconnect: fail
2016-01-15T18:49:10.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:49:10.915Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:49:10.915Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15T18:49:10.915Z SendDataConnector.js: do connect now
,2016-01-15 19:49:10.916 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:10.916 ThaliTest[1431:4663736] client: connect: unreachable Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:10.916 ThaliTest[1431:4663736] j,xcore: connect: fail: Peer unreachable
2016-01-15T18:49:10.917Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-15T18:49:10.917Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-15T18:49:10.918Z SendDataConnector.js: CLIENT Stop now
2016-01-15 19:49:10.919 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:49:10.919 ThaliTest[1431:4663736] jxcore: disconnect: fail
2016-01-15T18:49:10.919Z SendDataConnector.js: Mob,ile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0w==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15T18:49:10.921Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15T18:49:10.921Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15T18:49:10.921Z SendDataConnector.js: do connect now
,2016-01-15 19:49:10.922 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:10.922 ThaliTest[1431:4663736] client session: connect
2016-01-15 19:49:10.923 ThaliTest[1431:4663736] client session: stateChange:0->1 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:13.932 ThaliTest[1431:4664532] client session: connected
,2016-01-15 19:49:13.932 ThaliTest[1431:4664532] client session: stateChange:1->2 Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:13.939 ThaliTest[1431:4664532] client session: fireConnectCallback: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:13.939 ,ThaliTest[1431:4664532] jxcore: connect: success
2016-01-15T18:49:13.940Z SendDataConnector.js: CLIENT connected to 53242, error: null
2016-01-15T18:49:13.940Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:13.944 ThaliTest[1431:4663610] client: relay established
2016-01-15 19:49:13.944 ThaliTest[1431:4663610] client: new accepted socket: 0x1acbabc0
,2016-01-15T18:49:13.955Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:14.487Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-15T18:49:14.717Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:14.717Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-15T18:49:14.718Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:1,4.718Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-15 19:49:14.719 ThaliTest[1431:4663736] jxcore: disconnect
2016-01-15 19:49:14.719 ThaliTest[1431:4663736] client session: disconnectFromPeer: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49,:14.719 ThaliTest[1431:4663736] client session: disconnect
2016-01-15 19:49:14.719 ThaliTest[1431:4663736] client session: stateChange:2->0 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:14.730 ThaliTest[1431:4663736] jxcore: disconnect: success
2016-01-15T18:49:14.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.81B+Sg==
---- round done--------
startWithNextDevice
device[3]: App,le-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18:49:14.731Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18:49:14.731Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18,:49:14.731Z SendDataConnector.js: do connect now
2016-01-15 19:49:14.731 ThaliTest[1431:4663736] jxcore: connect Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:14.732 ThaliTest[1431:4663736] client session: connect
2016-01-15 19:49:14.732 ThaliTest[1,431:4663736] client session: stateChange:0->1 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:15.663 ThaliTest[1431:4663610] multipeer session: reset timer
2016-01-15 19:49:15.665 ThaliTest[1431:4663610] multipeer session: stop timer
2016-01-15 19:49:15.665 ThaliTest[1431:4663610] multipeer session: start timer: 0x1abeabf0
2016-,01-15 19:49:15.666 ThaliTest[1431:4663610] server session: connect
2016-01-15 19:49:15.666 ThaliTest[1431:4663610] server session: stateChange:0->1 Apple-Iphone6-1_PT3224
2016-01-15 19:49:15.671 ThaliTest[1431:4663610] server: accepting invitation Apple-Iphone6-1_PT3224
,2016-01-15 19:49:15.679 ThaliTest[1431:4663610] multipeer session: reset timer
2016-01-15 19:49:15.679 ThaliTest[1431:4663610] multipeer session: stop timer
,2016-01-15 19:49:15.679 ThaliTest[1431:4663610] multipeer session: start timer: 0x1abeabf0
2016-01-15 19:49:15.681 ThaliTest[1431:4663610] server session: connect
2016-01-15 19:49:15.682 ThaliTest[1431:4663610] server session: stateChange:0->1 Apple-Ipad,Air2-1_PT6810
2016-01-15 19:49:15.690 ThaliTest[1431:4663610] server: accepting invitation Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:17.634 ThaliTest[1431:4664532] client session: connected
2016-01-15 19:49:17.635 ThaliTest[1431:4664532] client session: stateChange:1->2 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:17.639 ThaliTest[1431:4664532] client session: fireConnectCallback: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:17.640 ThaliTest[1431:4664532] jxcore: connect: success
2016-01-15T18:49:17.640Z SendDataConnector.js: CLIENT connected, to 53245, error: null
2016-01-15T18:49:17.640Z SendDataConnector.js: CLIENT starting client 
2016-01-15 19:49:17.643 ThaliTest[1431:4663610] client: relay established
2016-01-15 19:49:17.644 ThaliTest[1431:4663610] client: new accepted socket: 0x1ab4f830
,2016-01-15T18:49:17.656Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:18.185Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-15 19:49:18.261 ThaliTest[1431:4664529] server session: connected
2016-01-15 19:49:18.261 ThaliTest[1431:4664529] server session: stateChange:1->2 Apple-Iphone6-1_PT3224
,2016-01-15T18:49:18.282Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15 19:49:18.282 ThaliTest[1431:4663610] server relay: connected (to port: 53235)
2016-01-15T18:49:18.282Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-15T18:49:18.286Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:18.287Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:18.288 ThaliTest[1431:4663736] jxcore: disconnect
,2016-01-15 19:49:18.288 ThaliTest[1431:4663736] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:18.289 ThaliTest[1431:4663736] client session: disconnect
,2016-01-15 19:49:18.290 ThaliTest[1431:4663736] client session: stateChange:2->0 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:18.361 ThaliTest[1431:4663736] jxcore: disconnect: success
,2016-01-15T18:49:18.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6477.TN0Czw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:18.364Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:18.365Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:18.365Z SendDataConnector.js: do connect now
,2016-01-15 19:49:18.366 ThaliTest[1431:4663736] jxcore: connect Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:18.366 ThaliTest[1431:4663736] client session: connect
,2016-01-15 19:49:18.367 ThaliTest[1431:4663736] client session: stateChange:0->1 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:18.376Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:18.635Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-15T18:49:18.648Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:18.683 ThaliTest[1431:4664558] server session: not connected Apple-Iphone6-1_PT3224
,2016-01-15 19:49:19.140 ThaliTest[1431:4664529] server session: connected
2016-01-15 19:49:19.141 ThaliTest[1431:4664529] server session: stateChange:1->2 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:19.195 ThaliTest[1431:4663610] server relay: connected (to port: 53235)
,2016-01-15T18:49:19.204Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:19.406Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-15T18:49:19.446Z SendDataTCPServer.js: TCP/IP server has received 31998 bytes of data
,2016-01-15T18:49:19.463Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:19.557 ThaliTest[1431:4664535] server session: not connected Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:20.441 ThaliTest[1431:4663610] multipeer session: reset timer
2016-01-15 19:49:20.442 ThaliTest[1431:4663610] multipeer session: stop timer
2016-01-15 19:49:20.442 ThaliTest[1431:4663610] multipeer session: start timer: 0x1abeabf0
2016-01-15 19:49:20.442 ThaliTest[1431:4663610] server session: connect
2016-01-15 19:49:20.442 ThaliTest[1431:4663610] server session: stateChange:0->1 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:20.450 ThaliTest[1431:4663610] server: accepting invitation Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:21.816 ThaliTest[1431:4664535] client session: connected
2016-01-15 19:49:21.816 ThaliTest[1431:4664535] client session: stateChange:1->2 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:21.830 ThaliTest[1431:4664558] client session: fireConnectCallback: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:21.830 ThaliTest[1431:4664558] jxcore: connect: success
2016-01-15T18:49:21.831Z SendDataConnector.js: CLIENT connected, to 53250, error: null
2016-01-15T18:49:21.831Z SendDataConnector.js: CLIENT starting client 
2016-01-15 19:49:21.833 ThaliTest[1431:4663610] client: relay established
2016-01-15 19:49:21.834 ThaliTest[1431:4663610] client: new accepted socket: 0x1acba410
,2016-01-15T18:49:21.846Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:22.368Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-15T18:49:22.409Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-15T18:49:22.422Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-15T18:49:22.473Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-15T18:49:22.473Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:22.474Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:22.474Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:22.475 ThaliTest[1431:4663736] jxcore: disconnect
,2016-01-15 19:49:22.476 ThaliTest[1431:4663736] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:22.477 ThaliTest[1431:4663736] client session: disconnect
,2016-01-15 19:49:22.478 ThaliTest[1431:4663736] client session: stateChange:2->0 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:22.549 ThaliTest[1431:4663736] jxcore: disconnect: success
,2016-01-15T18:49:22.550Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-15T18:49:22.566Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:22.566Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:23.000 ThaliTest[1431:4664535] server session: connected
2016-01-15 19:49:23.003 ThaliTest[1431:4664535] server session: stateChange:1->2 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:23.008 ThaliTest[1431:4663610] server relay: connected (to port: 53235)
,2016-01-15T18:49:23.014Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:23.405Z SendDataTCPServer.js: TCP/IP server has received 6428 bytes of data
2016-01-15T18:49:23.420Z SendDataTCPServer.js: TCP/IP server has received 47754 bytes of data
,2016-01-15T18:49:23.435Z SendDataTCPServer.js: TCP/IP server has received 98266 bytes of data
,2016-01-15T18:49:23.449Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:23.528 ThaliTest[1431:4664529] server session: not connected Apple-Iphone5s-1_PT6477
,teardown
testSendData stopped
2016-01-15 19:49:24.244 ThaliTest[1431:4663736] jxcore: stopBroadcasting
2016-01-15 19:49:24.244 ThaliTest[1431:4663736] THEMultipeerSession stopping peer
2016-01-15 19:49:24.245 ThaliTest[1431:4663736] multipeer session: stop timer
2016-01-15 19:49:24.245 ThaliTest[1431:4663736] server session: disconnect
2016-01-15 19:49:24.245 ThaliTest[1431:4663736] server session: stateChange:2->0 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:24.518 ThaliTest[1431:4663736] server session: disconnect
2016-01-15 19:49:24.519 ThaliTest[1431:4663736] server session: stateChange:2->0 Apple-Iphone5s-1_PT6477
2016-01-15 19:49:24.521 ThaliTest[1431:4663736] server session: disconnect,
2016-01-15 19:49:24.521 ThaliTest[1431:4663736] server session: stateChange:2->0 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:24.530 ThaliTest[1431:4663736] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
