#### Test 54312298af2c956_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BA662FA3-AB97-4ED2-B3CC-8F78CF4DC5F7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BA662FA3-AB97-4ED2-B3CC-8F78CF4DC5F7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CEB10CC6-2613-491F-8C95-97B509872110/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62393"
,(lldb)     command script import "/tmp/BA662FA3-AB97-4ED2-B3CC-8F78CF4DC5F7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 03:06:33.135 ThaliTest[759:983397] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0EA6341B-3A2C-4D4F-AFD4-079C5FF5D4AA/Library/Cookies/Cookies.binarycookies
,2015-12-23 03:06:33.489 ThaliTest[759:983397] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 03:06:33.490 ThaliTest[759:983397] Multi-tasking -> Device: YES, App: YES
,2015-12-23 03:06:33.499 ThaliTest[759:983397] Unlimited access to network resources
,2015-12-23 03:06:33.508 ThaliTest[759:983397] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 03:06:42.866 ThaliTest[759:983397] Resetting plugins due to page load.
,2015-12-23 03:06:46.291 ThaliTest[759:983397] Finished load of: file:///var/mobile/Containers/Bundle/Application/CEB10CC6-2613-491F-8C95-97B509872110/ThaliTest.app/www/index.html
,2015-12-23 03:06:46.446 ThaliTest[759:983397] JXcore Cordova plugin initializing
,2015-12-23 03:06:46.446 ThaliTest[759:983614] JXcore instance initializing
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
,2015-12-23 03:06:47.437 ThaliTest[759:983397] THREAD WARNING: ['JXcore'] took '75.148926' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-23 03:12:00.109 ThaliTest[759:983614] jxcore: startBroadcasting
,2015-12-23 03:12:00.127 ThaliTest[759:983614] server: starting Apple-IpadAir2-1_PT8230.LvlR6w==
,2015-12-23 03:12:00.129 ThaliTest[759:983614] multipeer session: start timer: 0x184b43d0
2015-12-23 03:12:00.129 ThaliTest[759:983614] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8230
2015-12-23 03:12:00.130 ThaliTest[759:983614] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-23 03:12:01.151 ThaliTest[759:983397] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT6053.eofveg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-23 03:12:01.222 ThaliTest[759:983397] client: found peer: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:02.285 ThaliTest[759:983397] client: found peer: Apple-Iphone5s-1_PT4021.JWtqWw==
,teardown
,testFindPeers stopped
,2015-12-23 03:12:02.672 ThaliTest[759:983614] jxcore: stopBroadcasting
,2015-12-23 03:12:02.672 ThaliTest[759:983614] THEMultipeerSession stopping peer
2015-12-23 03:12:02.673 ThaliTest[759:983614] multipeer session: stop timer
,2015-12-23 03:12:02.673 ThaliTest[759:983614] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,check server
,serverPort is 56314
,2015-12-23 03:12:02.765 ThaliTest[759:983614] jxcore: startBroadcasting
,2015-12-23 03:12:02.769 ThaliTest[759:983614] server: starting Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:02.770 ThaliTest[759:983614] multipeer session: start timer: 0x184bc990
,2015-12-23 03:12:02.776 ThaliTest[759:983614] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:02.778 ThaliTest[759:983614] jxcore: startBroadcasting: success
,2015-12-23 03:12:02.784 ThaliTest[759:983397] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
StartBroadcasting started ok
null
2015-12-23T02:12:02.787Z SendDataTCPServer.js: TCP/IP server is bound to port: 56314
2015-12-23 03:12:02.788 ThaliTest[759:983397] client: found peer: Apple-IpadAir2-1_PT8230.LvlR6w==
2015-12-23 03:12:02.788 ThaliTest[759:983397] client: found peer: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:02.790 ThaliTest[759:983397] client: found peer: Apple-Iphone5s-1_PT4021.JWtqWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.793Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.793Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.793Z SendDataConnector.js: do connect now
,2015-12-23 03:12:02.794 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:02.794 ThaliTest[759:983614] client session: connect
,2015-12-23 03:12:02.795 ThaliTest[759:983614] client session: stateChange:0->1 Apple-Iphone6-1_PT6053.eofveg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-23 03:12:03.785 ThaliTest[759:983397] client: lost peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.785 ThaliTest[759:983397] client session: onPeerLost: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.786 ThaliTest[759:983397] client session: onLinkFailure: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.786 ThaliTest[759:983397] client session: disconnect
2015-12-23 03:12:03.786 ThaliTest[759:983397] client session: stateChange:1->0 Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:03.787 ThaliTest[759:983397] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.787 ThaliTest[759:983397] jxcore: connect: fail: Peer disconnected
,2015-12-23T02:12:03.789Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-23T02:12:03.790Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-23T02:12:03.791Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":false}]
,2015-12-23 03:12:03.808 ThaliTest[759:983397] client: lost peer: Apple-Iphone5s-1_PT4021.JWtqWw==
2015-12-23 03:12:03.808 ThaliTest[759:983397] client session: onPeerLost: Apple-Iphone5s-1_PT4021.JWtqWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-23 03:12:03.923 ThaliTest[759:983397] client: lost peer: Apple-IpadAir2-1_PT8230.LvlR6w==
2015-12-23 03:12:03.923 ThaliTest[759:983397] client session: onPeerLost: Apple-IpadAir2-1_PT8230.LvlR6w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-23 03:12:04.331 ThaliTest[759:983397] client: lost peer: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:04.331 ThaliTest[759:983397] client session: onPeerLost: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:04.332 ThaliTest[759:983397] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:04.332 ThaliTest[759:983397] client: found peer: Apple-Iphone5-1_PT4216.OABFDg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.SE3R7g==","peerName":"(null,)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.OABFDg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23 03:12:04.664 ThaliTest[759:983397] client: found peer: Apple-Iphone6-1_PT6053.vUErSg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.vUErSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23T02:12:08.804Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:08.805Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.819 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:13.819 ThaliTest[759:983614] jxcore: disconnect: fail
,2015-12-23T02:12:13.820Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:13.821Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
,2015-12-23T02:12:13.821Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:13.822Z SendDataConnector.js: do connect now
,2015-12-23 03:12:13.823 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.824 ThaliTest[759:983614] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.824 ThaliTest[759:983614] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:13.825Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:13.826Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-23T02:12:13.827Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:18.828Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:18.829Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.830 ThaliTest[759:983614] jxcore: disconnect
2015-12-23 03:12:23.831 ThaliTest[759:983614] jxcore: disconnect: fail
,2015-12-23T02:12:23.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:23.832Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
,2015-12-23T02:12:23.833Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:23.833Z SendDataConnector.js: do connect now
,2015-12-23 03:12:23.834 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.835 ThaliTest[759:983614] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.835 ThaliTest[759:983614] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:23.836Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:23.837Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:23.837Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:28.849Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:28.849Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:32.776 ThaliTest[759:983397] multipeer session: restart
,2015-12-23 03:12:32.802 ThaliTest[759:983397] client: found peer: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:32.803 ThaliTest[759:983397] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:32.804 ThaliTest[759:983397] client: fou,nd peer: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:33.857 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:33.858 ThaliTest[759:983614] jxcore: disconnect: fail
,2015-12-23T02:12:33.859Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:33.859Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: ,true
2015-12-23T02:12:33.860Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:33.860Z SendDataConnector.js: do connect now
,2015-12-23 03:12:33.861 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.862 ThaliTest[759:983614] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.862 ThaliTest[759:983614] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:33.863Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:33.864Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-23T02:12:33.864Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:38.873Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:38.874Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.878 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:43.879 ThaliTest[759:983614] jxcore: disconnect: fail
,2015-12-23T02:12:43.880Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:43.881Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
,2015-12-23T02:12:43.881Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:43.881Z SendDataConnector.js: do connect now
,2015-12-23 03:12:43.883 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.883 ThaliTest[759:983614] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.883 ThaliTest[759:983614] jxcore: connect: fail: Peer unreachable
2015-12-23T02:12:43.884Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:43.885Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-23T02:12:43.887Z SendDataConnector.js: CLIENT Stop now
,2015-12-23 03:12:43.888 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:43.888 ThaliTest[759:983614] jxcore: disconnect: fail
2015-12-23T02:12:43.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,---- round done--------
,startWithNextDevice
device[2]: Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:43.892Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:43.893Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:43.894Z SendDataConnector.js: do connect now
,2015-12-23 03:12:43.895 ThaliTest[759:983614] jxcore: connect Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:43.895 ThaliTest[759:983614] client session: connect
,2015-12-23 03:12:43.897 ThaliTest[759:983614] client session: stateChange:0->1 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:44.189 ThaliTest[759:983397] multipeer session: reset timer
2015-12-23 03:12:44.190 ThaliTest[759:983397] multipeer session: stop timer
2015-12-23 03:12:44.190 ThaliTest[759:983397] multipeer session: start timer: 0x184bc990
,2015-12-23 03:12:44.190 ThaliTest[759:983397] server session: connect
2015-12-23 03:12:44.191 ThaliTest[759:983397] server session: stateChange:0->1 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:44.197 ThaliTest[759:983397] server: accepting invitation Apple-Iphone6-1_PT6053
,2015-12-23 03:12:47.096 ThaliTest[759:984266] client session: connected
,2015-12-23 03:12:47.096 ThaliTest[759:984266] client session: stateChange:1->2 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:47.150 ThaliTest[759:984265] client session: fireConnectCallback: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:47.150 ThaliTest[759:984265] jxcore: connect: success
,2015-12-23T02:12:47.152Z SendDataConnector.js: CLIENT connected to 56319, error: null
2015-12-23T02:12:47.152Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:47.155 ThaliTest[759:983397] client: relay established
2015-12-23 03:12:47.155 ThaliTest[759:983397] client: new accepted socket: 0x184cc340
,2015-12-23T02:12:47.171Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23 03:12:47.302 ThaliTest[759:984265] server session: connected
2015-12-23 03:12:47.302 ThaliTest[759:984265] server session: stateChange:1->2 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:47.310 ThaliTest[759:983397] server relay: connected (to port: 56314)
,2015-12-23T02:12:47.436Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:47.802Z SendDataTCPServer.js: TCP/IP server has received 6428 bytes of data
,2015-12-23T02:12:47.814Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:47.921 ThaliTest[759:984276] server session: not connected Apple-Iphone6-1_PT6053
,2015-12-23T02:12:47.947Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-23T02:12:48.034Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-23T02:12:48.073Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:48.074Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-23T02:12:48.075Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:48.075Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:48.078 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:48.078 ThaliTest[759:983614] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:48.079 ThaliTest[759:983614] client session: disconnect
,2015-12-23 03:12:48.080 ThaliTest[759:983614] client session: stateChange:2->0 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:48.090 ThaliTest[759:983614] jxcore: disconnect: success
2015-12-23T02:12:48.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4021.SE3R7g==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5-1_PT4216.OABFDg==
2015-12-23T02:12:48.092Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23T02:12:48.092Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23T02:12:48.092Z SendDataConnector.js: do connect now
,2015-12-23 03:12:48.094 ThaliTest[759:983614] jxcore: connect Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:48.098 ThaliTest[759:983614] client session: connect
,2015-12-23 03:12:48.099 ThaliTest[759:983614] client session: stateChange:0->1 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:48.987 ThaliTest[759:983397] multipeer session: reset timer
2015-12-23 03:12:48.988 ThaliTest[759:983397] multipeer session: stop timer
,2015-12-23 03:12:48.988 ThaliTest[759:983397] multipeer session: start timer: 0x184bc990
,2015-12-23 03:12:48.989 ThaliTest[759:983397] server session: connect
2015-12-23 03:12:48.989 ThaliTest[759:983397] server session: stateChange:0->1 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:48.996 ThaliTest[759:983397] server: accepting invitation Apple-Iphone5-1_PT4216
,2015-12-23 03:12:50.238 ThaliTest[759:983397] multipeer session: reset timer
2015-12-23 03:12:50.239 ThaliTest[759:983397] multipeer session: stop timer
2015-12-23 03:12:50.239 ThaliTest[759:983397] multipeer session: start timer: 0x184bc990
,2015-12-23 03:12:50.239 ThaliTest[759:983397] server session: connect
,2015-12-23 03:12:50.240 ThaliTest[759:983397] server session: stateChange:0->1 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:50.246 ThaliTest[759:983397] server: accepting invitation Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:52.139 ThaliTest[759:984277] server session: connected
2015-12-23 03:12:52.140 ThaliTest[759:984277] server session: stateChange:1->2 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:52.147 ThaliTest[759:984314] client session: connected
,2015-12-23 03:12:52.147 ThaliTest[759:984314] client session: stateChange:1->2 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:52.161 ThaliTest[759:983397] server relay: connected (to port: 56314)
,2015-12-23T02:12:52.173Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23 03:12:52.228 ThaliTest[759:984276] client session: fireConnectCallback: Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:52.228 ThaliTest[759:984276] jxcore: connect: success
,2015-12-23T02:12:52.230Z SendDataConnector.js: CLIENT connected to 56324, error: null
,2015-12-23T02:12:52.230Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:52.234 ThaliTest[759:983397] client: relay established
,2015-12-23 03:12:52.234 ThaliTest[759:983397] client: new accepted socket: 0x184d78e0
,2015-12-23T02:12:52.248Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:52.747Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-23T02:12:52.771Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-23T02:12:52.785Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-23T02:12:52.786Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:52.786Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-23T02:12:52.786Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:52.787Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:52.788 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:52.788 ThaliTest[759:983614] client session: disconnectFromPeer: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:52.789 ThaliTest[759:983614] client session: disconnect
,2015-12-23 03:12:52.789 ThaliTest[759:983614] client session: stateChange:2->0 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:52.793 ThaliTest[759:983614] jxcore: disconnect: success
,2015-12-23T02:12:52.797Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4216.OABFDg==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:52.798Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:52.798Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:52.798Z SendDataConnector.js: do connect now
,2015-12-23 03:12:52.799 ThaliTest[759:983614] jxcore: connect Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:52.799 ThaliTest[759:983614] client session: connect
,2015-12-23 03:12:52.799 ThaliTest[759:983614] client session: stateChange:0->1 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:52.815Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-23T02:12:52.827Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-23T02:12:52.840Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-23T02:12:52.855Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:52.895 ThaliTest[759:984314] server session: not connected Apple-Iphone5-1_PT4216
,2015-12-23 03:12:53.168 ThaliTest[759:984276] server session: connected
2015-12-23 03:12:53.168 ThaliTest[759:984276] server session: stateChange:1->2 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:53.198 ThaliTest[759:983397] server relay: connected (to port: 56314)
,2015-12-23T02:12:53.200Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:53.498Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-23T02:12:53.561Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-23T02:12:53.573Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:53.600 ThaliTest[759:984313] server session: not connected Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:55.875 ThaliTest[759:984265] client session: connected
2015-12-23 03:12:55.876 ThaliTest[759:984265] client session: stateChange:1->2 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:55.879 ThaliTest[759:984265] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:55.880 ThaliTest[759:984265] jxcore: connect: success
2015-12-23T02:12:55.881Z SendDataConnector.js: CLIENT connected to 56328, error: null
,2015-12-23T02:12:55.881Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:55.884 ThaliTest[759:983397] client: relay established
2015-12-23 03:12:55.885 ThaliTest[759:983397] client: new accepted socket: 0x185c1340
,2015-12-23T02:12:55.898Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:56.258Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-23T02:12:56.271Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-23T02:12:56.271Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-23T02:12:56.272Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:56.272Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:56.272 ThaliTest[759:983614] jxcore: disconnect
,2015-12-23 03:12:56.272 ThaliTest[759:983614] client session: disconnectFromPeer: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:56.273 ThaliTest[759:983614] client session: disconnect
,2015-12-23 03:12:56.273 ThaliTest[759:983614] client session: stateChange:2->0 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:56.276 ThaliTest[759:983614] jxcore: disconnect: success
2015-12-23T02:12:56.276Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.vUErSg==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-23T02:12:56.280Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:56.280Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-23 03:12:58.577 ThaliTest[759:983614] jxcore: stopBroadcasting
,2015-12-23 03:12:58.578 ThaliTest[759:983614] THEMultipeerSession stopping peer
2015-12-23 03:12:58.579 ThaliTest[759:983614] multipeer session: stop timer
,2015-12-23 03:12:58.579 ThaliTest[759:983614] server session: disconnect
,2015-12-23 03:12:58.580 ThaliTest[759:983614] server session: stateChange:2->0 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:58.659 ThaliTest[759:983614] server session: disconnect
,2015-12-23 03:12:58.661 ThaliTest[759:983614] server session: stateChange:2->0 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:58.666 ThaliTest[759:983614] server session: disconnect
,2015-12-23 03:12:58.672 ThaliTest[759:983614] server session: stateChange:2->0 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:58.676 ThaliTest[759:983614] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-23T02:12:58.701Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.703Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.705Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-23T02:12:58.705Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
