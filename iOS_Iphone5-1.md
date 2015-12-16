#### Test 50650278cd699a4_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FDE125D7-75E6-4821-89A2-78987915324E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FDE125D7-75E6-4821-89A2-78987915324E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C9A4F52-6A59-4DCD-A6E1-FA565CAFBB3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58441"
,(lldb)     command script import "/tmp/FDE125D7-75E6-4821-89A2-78987915324E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 05:34:49.531 ThaliTest[232:56307] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C706D80A-2BC2-499C-8A92-2B24955EF5AA/Library/Cookies/Cookies.binarycookies
,2015-12-16 05:34:49.648 ThaliTest[232:56307] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 05:34:49.649 ThaliTest[232:56307] Multi-tasking -> Device: YES, App: YES
,2015-12-16 05:34:49.654 ThaliTest[232:56307] Unlimited access to network resources
,2015-12-16 05:34:49.664 ThaliTest[232:56307] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 05:34:59.817 ThaliTest[232:56307] Resetting plugins due to page load.
,2015-12-16 05:35:03.811 ThaliTest[232:56307] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C9A4F52-6A59-4DCD-A6E1-FA565CAFBB3C/ThaliTest.app/www/index.html
,2015-12-16 05:35:04.024 ThaliTest[232:56307] JXcore Cordova plugin initializing
2015-12-16 05:35:04.025 ThaliTest[232:56492] JXcore instance initializing
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
,2015-12-16 05:35:06.499 ThaliTest[232:56307] THREAD WARNING: ['JXcore'] took '151.923828' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 05:41:40.233 ThaliTest[232:56492] jxcore: startBroadcasting
,2015-12-16 05:41:40.245 ThaliTest[232:56492] server: starting Apple-Iphone5-1_PT1441.9FcBSA==
,2015-12-16 05:41:40.246 ThaliTest[232:56492] multipeer session: start timer: 0x19b77770
,2015-12-16 05:41:40.247 ThaliTest[232:56492] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1441
,2015-12-16 05:41:40.247 ThaliTest[232:56492] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 05:41:41.288 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.Ya3H6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4432.Ya3H6w==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT4432.Ya3H6w==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 05:41:43.915 ThaliTest[232:56492] jxcore: stopBroadcasting
,2015-12-16 05:41:43.916 ThaliTest[232:56492] THEMultipeerSession stopping peer
,2015-12-16 05:41:43.917 ThaliTest[232:56492] multipeer session: stop timer
,2015-12-16 05:41:43.917 ThaliTest[232:56492] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":2}bt-address length : 0
,daya100000
check server
,serverPort is 49975
2015-12-16 05:41:44.170 ThaliTest[232:56492] jxcore: startBroadcasting
,2015-12-16 05:41:44.173 ThaliTest[232:56492] server: starting Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16 05:41:44.188 ThaliTest[232:56492] multipeer session: start timer: 0x19c8a130
2015-12-16 05:41:44.188 ThaliTest[232:56492] THEMultipeerSession initial,ized peer Apple-Iphone5-1_PT1441
2015-12-16 05:41:44.188 ThaliTest[232:56492] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-16T04:41:44.191Z SendDataTCPServer.js: TCP/IP server is bound to port: 49975
,2015-12-16 05:41:45.128 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4432.nDL3Zg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16T04:41:45.133Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16T04:41:45.134Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16T04:41:45.134Z SendDataConnector.js: do connect now
,2015-12-16 05:41:45.135 ThaliTest[232:56492] jxcore: connect Apple-Iphone6-1_PT4432.nDL3Zg==
2015-12-16 05:41:45.136 ThaliTest[232:56492] client session: connect
2015-12-16 05:41:45.136 ThaliTest[232:56492] client session: stateChange:0->1 Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:41:45.625 ThaliTest[232:56307] multipeer session: reset timer
2015-12-16 05:41:45.625 ThaliTest[232:56307] multipeer session: stop timer
2015-12-16 05:41:45.625 ThaliTest[232:56307] multipeer session: start timer: 0x19c8a130
2015-12-16 05:41:45.625 ThaliTest[232:56307] server session: connect
2015-12-16 05:41:45.626 ThaliTest[232:56307] server session: stateChange:0->1 Apple-Iphone6-1_PT4432
,2015-12-16 05:41:45.632 ThaliTest[232:56307] server: accepting invitation Apple-Iphone6-1_PT4432
,2015-12-16 05:41:48.247 ThaliTest[232:57211] client session: connected
2015-12-16 05:41:48.247 ThaliTest[232:57211] client session: stateChange:1->2 Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:41:48.251 ThaliTest[232:57214] server session: connected
2015-12-16 05:41:48.252 ThaliTest[232:57214] server session: stateChange:1->2 Apple-Iphone6-1_PT4432
2015-12-16 05:41:48.254 ThaliTest[232:57211] client session: fireConnectCallback: Apple-Iphone6-1_PT4432.nDL3Zg==
2015-12-16 05:41:48.254 ThaliTest[232:57211] jxcore: connect: success
,2015-12-16T04:41:48.256Z SendDataConnector.js: CLIENT connected to 49978, error: null
2015-12-16T04:41:48.257Z SendDataConnector.js: CLIENT starting client 
2015-12-16 05:41:48.259 ThaliTest[232:56307] client: relay established
2015-12-16 05:41:48.259 ThaliTest[232:56307] client: new accepted socket: 0x19b907f0
,2015-12-16 05:41:48.265 ThaliTest[232:56307] server relay: connected (to port: 49975)
,2015-12-16T04:41:48.273Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T04:41:48.274Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T04:41:48.787Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16T04:41:48.815Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T04:41:48.839Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T04:41:48.854Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16 05:41:48.868 ThaliTest[232:57211] server session: not connected Apple-Iphone6-1_PT4432
,2015-12-16T04:41:48.930Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T04:41:48.931Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T04:41:48.934Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T04:41:48.934Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 05:41:48.935 ThaliTest[232:56492] jxcore: disconnect
2015-12-16 05:41:48.935 ThaliTest[232:56492] client session: disconnectFromPeer: Apple-Iphone6-1_PT4432.nDL3Zg==
2015-12-16 05:41:48.936 ThaliTest[232:56492] client session: disconnect
2015-12-16 05:41:48.936 ThaliTest[232:56492] client session: stateChange:2->0 Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:41:48.944 ThaliTest[232:56492] jxcore: disconnect: success
2015-12-16T04:41:48.946Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4432.nDL3Zg==
,---- round done--------
startWithNextDevice
,2015-12-16 05:42:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:42:15.659 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:42:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:42:46.332 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:43:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:43:15.656 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:43:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:43:45.660 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:44:15.626 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:44:15.660 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:44:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:44:45.657 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:45:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:45:15.659 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:45:45.627 ThaliTest[232:56307] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-16 05:46:15.626 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:46:15.649 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,appEnteringBackground wasn't registered
,2015-12-16 05:46:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:47:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:47:15.649 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:47:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:47:45.649 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:48:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:48:15.651 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:48:45.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:49:15.627 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:49:15.651 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:49:45.626 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:49:45.651 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,appEnteredForeground wasn't registered
,2015-12-16 05:50:15.626 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:50:15.653 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:50:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:51:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:51:16.298 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:51:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:51:45.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:51:47.291 ThaliTest[232:56307] client: lost peer: Apple-Iphone6-1_PT4432.nDL3Zg==
2015-12-16 05:51:47.292 ThaliTest[232:56307] client session: onPeerLost: Apple-Iphone6-1_PT4432.nDL3Zg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one6-1_PT4432.nDL3Zg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-16 05:51:50.540 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4432.nDL3Zg==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-16 05:52:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:52:15.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:52:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:52:45.581 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:53:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:53:15.580 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:53:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:53:45.581 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:54:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:54:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:54:45.580 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:55:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:55:15.581 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:55:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:55:45.579 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:56:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:56:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:56:45.580 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:57:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:57:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:57:45.580 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:58:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:58:15.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,timeout now
,weAreDoneNow, resultArray.length: 1
,sendReportNow
,done, now sending data to server
,2015-12-16T04:58:24.127Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 05:58:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:58:45.583 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:59:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:59:15.579 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 05:59:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 05:59:45.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 06:00:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:00:15.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 06:00:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:01:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:01:15.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 06:01:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:01:45.580 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 06:02:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:02:15.582 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==
,2015-12-16 06:02:45.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:03:15.556 ThaliTest[232:56307] multipeer session: restart
,2015-12-16 06:03:15.581 ThaliTest[232:56307] client: found peer: Apple-Iphone6-1_PT4432.nDL3Zg==

```
