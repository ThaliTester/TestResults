#### Test 506502785223c58_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/521893C9-87DE-4B6A-90C4-478F5C45732F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/521893C9-87DE-4B6A-90C4-478F5C45732F/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/846EA5A8-BCD2-41D3-98EA-29F2ECE4AC96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59051"
,(lldb)     command script import "/tmp/521893C9-87DE-4B6A-90C4-478F5C45732F/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 01:35:54.354 ThaliTest[291:181896] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/168CCEB4-1B69-4E30-89F2-BC588F69048D/Library/Cookies/Cookies.binarycookies
,2015-12-17 01:35:54.472 ThaliTest[291:181896] Apache Cordova native platform version 3.9.2 is starting.
2015-12-17 01:35:54.473 ThaliTest[291:181896] Multi-tasking -> Device: YES, App: YES
2015-12-17 01:35:54.478 ThaliTest[291:181896] Unlimited access to network resources
2015-12-17 01:35:54.489 ThaliTest[291:181896] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:,
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 01:36:05.316 ThaliTest[291:181896] Resetting plugins due to page load.
,2015-12-17 01:36:08.875 ThaliTest[291:181896] Finished load of: file:///var/mobile/Containers/Bundle/Application/846EA5A8-BCD2-41D3-98EA-29F2ECE4AC96/ThaliTest.app/www/index.html
,2015-12-17 01:36:09.090 ThaliTest[291:181896] JXcore Cordova plugin initializing
2015-12-17 01:36:09.091 ThaliTest[291:182070] JXcore instance initializing
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
,2015-12-17 01:36:11.561 ThaliTest[291:181896] THREAD WARNING: ['JXcore'] took '156.227051' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-17 01:42:48.116 ThaliTest[291:182070] jxcore: startBroadcasting
,2015-12-17 01:42:48.129 ThaliTest[291:182070] server: starting Apple-Iphone5-1_PT6883.tl0S1A==
,2015-12-17 01:42:48.131 ThaliTest[291:182070] multipeer session: start timer: 0x1bb379e0
2015-12-17 01:42:48.131 ThaliTest[291:182070] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6883
2015-12-17 01:42:48.132 ThaliTest[291:182070] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17 01:42:49.227 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.aFuJbQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.aFuJbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1_PT4765.aFuJbQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-17 01:42:50.093 ThaliTest[291:182070] jxcore: stopBroadcasting
2015-12-17 01:42:50.093 ThaliTest[291:182070] THEMultipeerSession stopping peer
2015-12-17 01:42:50.093 ThaliTest[291:182070] multipeer session: stop timer
2015-12-17 01:42:50.093 ThaliTest[291:182070] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 51138
,2015-12-17 01:42:50.156 ThaliTest[291:182070] jxcore: startBroadcasting
,2015-12-17 01:42:50.159 ThaliTest[291:182070] server: starting Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:42:50.159 ThaliTest[291:182070] multipeer session: start timer: 0x175fa700
2015-12-17 01:42:50.160 ThaliTest[291:182070] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6883
2015-12-17 01:42:50.160 ThaliTest[291:182070] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-17T00:42:50.173Z SendDataTCPServer.js: TCP/IP server is bound to port: 51138
,2015-12-17 01:42:51.156 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.aFuJbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.aFuJbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:42:51.159Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:42:51.160Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17T00:42:51.161Z SendDataConnector.js: do connect now
2015-12-17 01:42:51.161 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765,.aFuJbQ==
2015-12-17 01:42:51.162 ThaliTest[291:182070] client session: connect
2015-12-17 01:42:51.162 ThaliTest[291:182070] client session: stateChange:0->1 Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:42:51.273 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
2015-12-17 01:42:51.275 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:51.790 ThaliTest[291:181896] client: lost peer: Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:42:51.790 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:42:51.790 ThaliTest[291:181896] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:42:51.791 ThaliTest[291:181896] client session: disconnect
2015-12-17 01:42:51.791 ThaliTest[291:181896] client session: stateChange:1->0 Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12,-17 01:42:51.791 ThaliTest[291:181896] client session: fireConnectCallback: Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:42:51.791 ThaliTest[291:181896] jxcore: connect: fail: Peer disconnected
2015-12-17T00:42:51.793Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-17T00:42:51.793Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-17T00:42:51.793Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5s-1_PT4765.aFuJbQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 01:42:51.913 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-17T00:42:56.802Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:42:56.802Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:00.231 ThaliTest[291:181896] multipeer session: reset timer
2015-12-17 01:43:00.232 ThaliTest[291:181896] multipeer session: stop timer
2015-12-17 01:43:00.232 ThaliTest[291:181896] multipeer session: start timer: 0x175fa700
2015-12-17 01:43:00.232 ThaliTest[291:181896] server session: connect
2015-12-17 01:43:00.232 ThaliTest[291:181896] server session: stateChange:0->1 Apple-Iphone5s-1_PT4765
,2015-12-17 01:43:00.239 ThaliTest[291:181896] server: accepting invitation Apple-Iphone5s-1_PT4765
,2015-12-17 01:43:01.804 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:01.805 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:01.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.aFuJbQ==,
2015-12-17T00:43:01.806Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4765.aFuJbQ== with availability status: true
2015-12-17T00:43:01.806Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:43:01.807Z SendDataConnector.js: do connect now
2015-12-17 01:43:01.808 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:43:01.808 ThaliTest[291:182070] client: connect: unreachable Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:01.808 ThaliTest[291:182070] jxcore: connect: fail: Peer unreachable
2015-12-17T00:43:01.809Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-17T00:43:01.809Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:01.810Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17 01:43:02.966 ThaliTest[291:182819] server session: connected
2015-12-17 01:43:02.966 ThaliTest[291:182819] server session: stateChange:1->2 Apple-Iphone5s-1_PT4765
,2015-12-17 01:43:02.979 ThaliTest[291:181896] server relay: connected (to port: 51138)
,2015-12-17T00:43:02.990Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:43:03.311Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-17T00:43:03.329Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-17T00:43:03.343Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-17T00:43:03.359Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:43:03.406 ThaliTest[291:182819] server session: not connected Apple-Iphone5s-1_PT4765
,2015-12-17T00:43:06.816Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:43:06.817Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:11.820 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:11.821 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:11.823Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.aFuJbQ==,
2015-12-17T00:43:11.823Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4765.aFuJbQ== with availability status: true
,2015-12-17T00:43:11.824Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17T00:43:11.824Z SendDataConnector.js: do connect now
,2015-12-17 01:43:11.825 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:11.825 ThaliTest[291:182070] client: connect: unreachable Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:11.826 ThaliTest[291:182070] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:11.826Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:11.827Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:11.827Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:16.830Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:43:16.831Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:21.836 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:21.837 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:21.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.aFuJbQ==,
2015-12-17T00:43:21.838Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4765.aFuJbQ== with availability status: true
2015-12-17T00:43:21.838Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
20,15-12-17T00:43:21.838Z SendDataConnector.js: do connect now
,2015-12-17 01:43:21.839 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:43:21.840 ThaliTest[291:182070] client: connect: unreachable Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:43:21.840 ThaliTest[291:182070] jxcor,e: connect: fail: Peer unreachable
,2015-12-17T00:43:21.840Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:21.840Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:43:21.841Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:26.842Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17T00:43:26.843Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:43:30.233 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:43:30.272 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.272 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:31.848 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:31.848 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:31.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17T00:43:31.849Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4765.aFuJbQ== with availability status: true
2015-12-17T00:43:31.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
20,15-12-17T00:43:31.850Z SendDataConnector.js: do connect now
,2015-12-17 01:43:31.851 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:43:31.851 ThaliTest[291:182070] client: connect: unreachable Apple-Iphone5s-1_PT4765.aFuJbQ==
2015-12-17 01:43:31.852 ThaliTest[291:182070] jxcor,e: connect: fail: Peer unreachable
2015-12-17T00:43:31.852Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-17T00:43:31.853Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-17T00:43:31.854Z SendDataConnector.js: CLIENT Stop now
2015-12-17 01:43:31.854 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:31.855 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:31.855Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.aFuJbQ==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17T00:43:31.856Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17T00:43:31.856Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17T00:43:31.856Z SendDataConnector.js: do connect now
,2015-12-17 01:43:31.857 ThaliTest[291:182070] jxcore: connect Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:31.857 ThaliTest[291:182070] client session: connect
2015-12-17 01:43:31.858 ThaliTest[291:182070] client session: stateChange:0->1 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:35.027 ThaliTest[291:182921] client session: connected
2015-12-17 01:43:35.027 ThaliTest[291:182921] client session: stateChange:1->2 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:35.418 ThaliTest[291:182922] client session: fireConnectCallback: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:35.418 ThaliTest[291:182922] jxcore: connect: success
2015-12-17T00:43:35.419Z SendDataConnector.js: CLIENT connected to 51143, error: null
2015-12-17T00:43:35.420Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:43:35.423 ThaliTest[291:181896] client: relay established
2015-12-17 01:43:35.423 ThaliTest[291:181896] client: new accepted socket: 0x1ba08920
,2015-12-17T00:43:35.436Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:43:35.970Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T00:43:35.984Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T00:43:36.009Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-17T00:43:36.327Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T00:43:36.328Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:43:36.329Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:43:36.330Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:43:36.331 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:36.331 ThaliTest[291:182070] client session: disconnectFromPeer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:36.332 ThaliTest[291:182070] client session: disconnect
2,015-12-17 01:43:36.332 ThaliTest[291:182070] client session: stateChange:2->0 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:36.340 ThaliTest[291:182070] jxcore: disconnect: success
2015-12-17T00:43:36.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.i5O+Uw==
---- round done--------
startWithNextDevice
device[3]: Apple,-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:43:36.341Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:43:36.341Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:4,3:36.341Z SendDataConnector.js: do connect now
2015-12-17 01:43:36.342 ThaliTest[291:182070] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:36.342 ThaliTest[291:182070] client session: connect
2015-12-17 01:43:36.342 ThaliTest[291:182,070] client session: stateChange:0->1 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:43:36.361 ThaliTest[291:181896] client: lost peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:36.361 ThaliTest[291:181896] client session: onPeerLost: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:36.361 ThaliTest[291:181896] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:36.362 ThaliTest[291:181896] client session: disconnect
2015-12-17 01:43:36.362 ThaliTest[291:181896] client session: stateChange:1->0 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:43:36.419 ThaliTest[291:181896] client session: fireConnectCallback: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:36.419 ThaliTest[291:181896] jxcore: connect: fail: Peer disconnected
2015-12-17T00:43:36.420Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-17T00:43:36.420Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-17T00:43:36.421Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 01:43:39.610 ThaliTest[291:181896] multipeer session: reset timer
2015-12-17 01:43:39.610 ThaliTest[291:181896] multipeer session: stop timer
2015-12-17 01:43:39.610 ThaliTest[291:181896] multipeer session: start timer: 0x175fa700
,2015-12-17 01:43:39.610 ThaliTest[291:181896] server session: connect
,2015-12-17 01:43:39.611 ThaliTest[291:181896] server session: stateChange:0->1 Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:39.617 ThaliTest[291:181896] server: accepting invitation Apple-IpadAir2-1_PT2260
,2015-12-17T00:43:41.431Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:43:41.431Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:43:43.419 ThaliTest[291:182876] server session: connected
2015-12-17 01:43:43.419 ThaliTest[291:182876] server session: stateChange:1->2 Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:43.467 ThaliTest[291:181896] server relay: connected (to port: 51138)
,2015-12-17T00:43:43.471Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:43:43.738Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-17T00:43:43.755Z SendDataTCPServer.js: TCP/IP server has received 52134 bytes of data
,2015-12-17T00:43:43.771Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-17T00:43:43.788Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:43:43.867 ThaliTest[291:182876] server session: not connected Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:46.442 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:46.443 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:46.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==,
2015-12-17T00:43:46.444Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2260.gQiHGg== with availability status: true
2015-12-17T00:43:46.444Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
20,15-12-17T00:43:46.444Z SendDataConnector.js: do connect now
,2015-12-17 01:43:46.445 ThaliTest[291:182070] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:46.446 ThaliTest[291:182070] client: connect: unreachable Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:46.446 ThaliTest[291:182070] jxcor,e: connect: fail: Peer unreachable
,2015-12-17T00:43:46.446Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:46.447Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:46.447Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:51.452Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:43:51.453Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:43:53.669 ThaliTest[291:181896] client: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:43:53.672 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
2015-12-17 01:43:53.673 ThaliTest[291:181896] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:53.675 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone,5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 01:43:56.016 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
,2015-12-17 01:43:56.464 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:43:56.464 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:43:56.465Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==,
2015-12-17T00:43:56.465Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2260.gQiHGg== with availability status: true
2015-12-17T00:43:56.466Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
20,15-12-17T00:43:56.466Z SendDataConnector.js: do connect now
,2015-12-17 01:43:56.467 ThaliTest[291:182070] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:56.467 ThaliTest[291:182070] client: connect: unreachable Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:43:56.468 ThaliTest[291:182070] jxcor,e: connect: fail: Peer unreachable
,2015-12-17T00:43:56.468Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:56.468Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:43:56.469Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:44:01.474Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:01.475Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:06.484 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:44:06.484 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:44:06.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==,
2015-12-17T00:44:06.485Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2260.gQiHGg== with availability status: true
2015-12-17T00:44:06.486Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:44:06.486Z SendDataConnector.js: do connect now
,2015-12-17 01:44:06.488 ThaliTest[291:182070] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:06.488 ThaliTest[291:182070] client: connect: unreachable Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:06.488 ThaliTest[291:182070] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:44:06.489Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:44:06.489Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-17T00:44:06.489Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17 01:44:08.585 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-17 01:44:09.612 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:44:09.645 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
2015-12-17 01:44:09.648 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:44:11.496Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:11.497Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:16.499 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:44:16.500 ThaliTest[291:182070] jxcore: disconnect: fail
2015-12-17T00:44:16.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==,
2015-12-17T00:44:16.501Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2260.gQiHGg== with availability status: true
2015-12-17T00:44:16.501Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
20,15-12-17T00:44:16.502Z SendDataConnector.js: do connect now
,2015-12-17 01:44:16.502 ThaliTest[291:182070] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:16.503 ThaliTest[291:182070] client session: connect
2015-12-17 01:44:16.503 ThaliTest[291:182070] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT2260.gQiHGg==
,2015-12-17 01:44:19.631 ThaliTest[291:183065] client session: connected
2015-12-17 01:44:19.631 ThaliTest[291:183065] client session: stateChange:1->2 Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:19.634 ThaliTest[291:183065] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:19.635 ThaliTest[291:183065] jxcore: connect: success
2015-12-17T00:44:19.635Z SendDataConnector.js: CLIENT connected to 51148, error: null
2015-12-17T00:44:19.636Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:44:19.639 ThaliTest[291:181896] client: relay established
2015-12-17 01:44:19.640 ThaliTest[291:181896] client: new accepted socket: 0x1bb20390
,2015-12-17T00:44:19.652Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:44:20.400Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T00:44:20.414Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:44:20.428Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T00:44:20.428Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:44:20.430Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:44:20.430Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:20.431 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:44:20.431 ThaliTest[291:182070] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:20.431 ThaliTest[291:182070] client session: disconnect
2015-12-17 01:44:20.432 ThaliTest[291:182070] client session: stateChange:2->0 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:20.440 ThaliTest[291:182070] jxcore: disconnect: success
2015-12-17T00:44:20.440Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:44:20.441Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:44:20.441Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:,44:20.442Z SendDataConnector.js: do connect now
,2015-12-17 01:44:20.442 ThaliTest[291:182070] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:20.445 ThaliTest[291:182070] client session: connect
2015-12-17 01:44:20.445 ThaliTest[291:182070] client session: stateChange:0->1 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:23.643 ThaliTest[291:183073] client session: connected
2015-12-17 01:44:23.643 ThaliTest[291:183073] client session: stateChange:1->2 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:23.650 ThaliTest[291:183072] client session: fireConnectCallback: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:23.650 ThaliTest[291:183072] jxcore: connect: success
2015-12-17T00:44:23.651Z SendDataConnector.js: CLIENT connected to ,51152, error: null
2015-12-17T00:44:23.651Z SendDataConnector.js: CLIENT starting client 
2015-12-17 01:44:23.653 ThaliTest[291:181896] client: relay established
2015-12-17 01:44:23.654 ThaliTest[291:181896] client: new accepted socket: 0x1bb11190
,2015-12-17T00:44:23.665Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:44:24.176Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-17T00:44:24.202Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T00:44:24.229Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:44:24.280Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T00:44:24.293Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T00:44:24.294Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:44:24.295Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:44:24.295Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:24.296 ThaliTest[291:182070] jxcore: disconnect
2015-12-17 01:44:24.296 ThaliTest[291:182070] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:24.297 ThaliTest[291:182070] client session: disconnect
,2015-12-17 01:44:24.297 ThaliTest[291:182070] client session: stateChange:2->0 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:24.311 ThaliTest[291:182070] jxcore: disconnect: success
2015-12-17T00:44:24.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
---- round done--------
startWithNextDevice
weAreDoneNow, r,esultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-17T00:44:24.316Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:44:24.317Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:28.163 ThaliTest[291:181896] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:28.163 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:44:29.324 ThaliTest[291:181896] multipeer session: reset timer
2015-12-17 01:44:29.324 ThaliTest[291:181896] multipeer session: stop timer
2015-12-17 01:44:29.324 ThaliTest[291:181896] multipeer session: start timer: 0x175fa700
2015-12-17 ,01:44:29.324 ThaliTest[291:181896] server session: connect
2015-12-17 01:44:29.325 ThaliTest[291:181896] server session: stateChange:0->1 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:29.332 ThaliTest[291:181896] server: accepting invitation Apple-Iphone6-1_PT4129
,2015-12-17 01:44:32.005 ThaliTest[291:183070] server session: connected
2015-12-17 01:44:32.006 ThaliTest[291:183070] server session: stateChange:1->2 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:32.010 ThaliTest[291:181896] server relay: connected (to port: 51138)
,2015-12-17T00:44:32.015Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:44:32.415Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-17T00:44:32.430Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-17T00:44:32.445Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-17T00:44:32.460Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-17T00:44:32.474Z SendDataTCPServer.js: TCP/IP server has received 91838 bytes of data
,2015-12-17T00:44:32.489Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:44:32.528 ThaliTest[291:183070] server session: not connected Apple-Iphone6-1_PT4129
,2015-12-17 01:44:34.188 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:44:44.568 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:44:59.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:44:59.364 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:44:59.364 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:59.367 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:45:29.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:45:29.369 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:45:29.369 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:45:29.370 ThaliTest[291:181896] client: fou,nd peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:45:59.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:45:59.365 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:45:59.371 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:45:59.372 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:46:29.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:46:29.364 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:46:29.369 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:46:29.369 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:46:59.325 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:46:59.372 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:46:59.373 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:46:59.373 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:47:29.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:47:59.325 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:47:59.359 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:47:59.360 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:47:59.360 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:48:29.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:48:29.362 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:48:29.362 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:48:29.363 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:48:59.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:48:59.362 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:48:59.363 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:48:59.363 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:49:29.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:49:29.364 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:49:29.364 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:49:29.364 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,appEnteredForeground wasn't registered
,2015-12-17 01:49:59.326 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:49:59.364 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:49:59.364 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:49:59.364 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:50:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:50:29.292 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:50:29.292 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:50:29.294 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:50:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:50:59.294 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:50:59.296 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:51:00.151 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:51:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:51:29.291 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:51:29.294 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:51:29.294 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:51:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:51:59.289 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:51:59.289 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:51:59.290 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:52:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:52:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:52:59.293 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:52:59.293 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:52:59.294 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:53:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:53:29.287 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:53:29.288 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:53:29.293 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:53:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:53:59.293 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:53:59.294 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:53:59.295 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:54:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:54:29.295 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:54:29.295 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:54:29.296 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:54:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:54:59.292 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:54:59.292 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:54:59.292 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:55:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:55:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:55:59.294 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:55:59.294 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:55:59.294 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:56:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:56:29.294 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:56:29.294 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:56:29.295 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:56:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:57:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:57:29.288 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:57:29.288 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:57:29.288 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:57:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:58:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:58:29.285 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:58:29.289 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:58:29.290 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:58:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:58:59.291 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:58:59.291 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:58:59.291 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:59:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 01:59:29.293 ThaliTest[291:181896] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:59:29.293 ThaliTest[291:181896] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:59:29.293 ThaliTest[291:181896] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:59:46.800 ThaliTest[291:181896] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:59:46.800 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:59:51.656 ThaliTest[291:181896] client: lost peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:59:51.656 ThaliTest[291:181896] client session: onPeerLost: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:59:51.657 ThaliTest[291:181896] cli,ent: lost peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:59:51.657 ThaliTest[291:181896] client session: onPeerLost: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","p,eerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:59:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:00:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:00:59.256 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:01:29.256 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:01:59.254 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:02:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:02:59.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:03:29.255 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:03:59.256 ThaliTest[291:181896] multipeer session: restart
,2015-12-17 02:04:29.255 ThaliTest[291:181896] multipeer session: restart

```
