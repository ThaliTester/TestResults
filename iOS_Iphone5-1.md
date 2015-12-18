#### Test 506502781a07ac8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/957ABA89-F077-458B-BF50-C10D18465B4D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/957ABA89-F077-458B-BF50-C10D18465B4D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0CD5751B-C155-4BAD-8175-EBAFDFD43871/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59755"
,(lldb)     command script import "/tmp/957ABA89-F077-458B-BF50-C10D18465B4D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 12:23:10.067 ThaliTest[339:393546] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8DE0DB8-6BC1-48FD-83ED-999776BC8CD9/Library/Cookies/Cookies.binarycookies
,2015-12-18 12:23:10.643 ThaliTest[339:393546] Apache Cordova native platform version 3.9.2 is starting.
2015-12-18 12:23:10.644 ThaliTest[339:393546] Multi-tasking -> Device: YES, App: YES
,2015-12-18 12:23:10.649 ThaliTest[339:393546] Unlimited access to network resources
,2015-12-18 12:23:10.663 ThaliTest[339:393546] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 12:23:20.886 ThaliTest[339:393546] Resetting plugins due to page load.
,2015-12-18 12:23:24.479 ThaliTest[339:393546] Finished load of: file:///var/mobile/Containers/Bundle/Application/0CD5751B-C155-4BAD-8175-EBAFDFD43871/ThaliTest.app/www/index.html
,2015-12-18 12:23:24.691 ThaliTest[339:393546] JXcore Cordova plugin initializing
,2015-12-18 12:23:24.692 ThaliTest[339:393744] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-18 12:23:27.164 ThaliTest[339:393546] THREAD WARNING: ['JXcore'] took '155.769043' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 12:31:19.910 ThaliTest[339:393744] jxcore: startBroadcasting
,2015-12-18 12:31:19.923 ThaliTest[339:393744] server: starting Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:19.924 ThaliTest[339:393744] multipeer session: start timer: 0x1cc80af0
2015-12-18 12:31:19.925 ThaliTest[339:393744] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6300
,2015-12-18 12:31:19.925 ThaliTest[339:393744] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 12:31:19.952 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT1480.8RWX+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT1480.8RWX+A==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-18 12:31:22.130 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:22.131 ThaliTest[339:393546] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
,teardown
,testFindPeers stopped
,2015-12-18 12:31:23.035 ThaliTest[339:393744] jxcore: stopBroadcasting
2015-12-18 12:31:23.035 ThaliTest[339:393744] THEMultipeerSession stopping peer
2015-12-18 12:31:23.036 ThaliTest[339:393744] multipeer session: stop timer
2015-12-18 12:31:23.036 ThaliTest[339:393744] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52319
,2015-12-18 12:31:23.100 ThaliTest[339:393744] jxcore: startBroadcasting
,2015-12-18 12:31:23.103 ThaliTest[339:393744] server: starting Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:31:23.104 ThaliTest[339:393744] multipeer session: start timer: 0x1cb4be50
2015-12-18 12:31:23.104 ThaliTest[339:393744] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT6300
2015-12-18 12:31:23.105 ThaliTest[339:393744] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-18T11:31:23.111Z SendDataTCPServer.js: TCP/IP server is bound to port: 52319
,2015-12-18 12:31:24.078 ThaliTest[339:393546] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:24.079 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-18 12:31:24.079 ThaliTest[339:393546] client: fou,nd peer: Apple-Iphone6-1_PT3077.XaIcQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT611,5.H3bAHA==
2015-12-18T11:31:24.082Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18T11:31:24.083Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18T11:31:24.083Z SendDat,aConnector.js: do connect now
2015-12-18 12:31:24.084 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:24.084 ThaliTest[339:393744] client session: connect
2015-12-18 12:31:24.085 ThaliTest[339:393744] client sessi,on: stateChange:0->1 Apple-IpadAir2-1_PT6115.H3bAHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:24.423 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:31:24.424 ThaliTest[339:393546] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6,-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-18 12:31:24.708 ThaliTest[339:393546] client: found peer: Apple-Iphone5s-1_PT8285.POBncQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:25.665 ThaliTest[339:393546] client: lost peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:25.665 ThaliTest[339:393546] client session: onPeerLost: Apple-Iphone6-1_PT3077.XaIcQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:27.721 ThaliTest[339:393546] client: lost peer: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:27.721 ThaliTest[339:393546] client session: onPeerLost: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:27.722 ThaliTest[339:393546] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:27.722 ThaliTest[339:393546] client session: disconnect
2015-12-18 12:31:27.722 ThaliTest[339:393546] client session: stateChange:1->0 Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12,-18 12:31:27.723 ThaliTest[339:393546] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:27.723 ThaliTest[339:393546] jxcore: connect: fail: Peer disconnected
2015-12-18T11:31:27.724Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-18T11:31:27.724Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-18T11:31:27.725Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 12:31:27.758 ThaliTest[339:393546] client: lost peer: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-18 12:31:27.758 ThaliTest[339:393546] client session: onPeerLost: Apple-Iphone6-1_PT1480.8RWX+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:28.186 ThaliTest[339:393546] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:30.870 ThaliTest[339:393546] client: lost peer: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.872 ThaliTest[339:393546] client session: onPeerLost: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.873 ThaliTest[339:393546] cli,ent: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":,"Apple-Iphone5s-1_PT8285.14R9MQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18T11:31:32.733Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:31:32.734Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:35.199 ThaliTest[339:393546] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-18 12:31:35.199 ThaliTest[339:393546] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:37.738 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:31:37.739 ThaliTest[339:393744] jxcore: disconnect: fail
2015-12-18T11:31:37.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.H3bAHA==,
2015-12-18T11:31:37.740Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6115.H3bAHA== with availability status: true
2015-12-18T11:31:37.740Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:31:37.741Z SendDataConnector.js: do connect now
2015-12-18 12:31:37.741 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:37.742 ThaliTest[339:393744] client: connect: unreachable Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:37.742 ThaliTest[339:393744] jxcore: connect: fail: Peer unreachable
2015-12-18T11:31:37.742Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:37.743Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:37.743Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:42.750Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:31:42.750Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:47.753 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:31:47.753 ThaliTest[339:393744] jxcore: disconnect: fail
2015-12-18T11:31:47.754Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.H3bAHA==,
2015-12-18T11:31:47.754Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6115.H3bAHA== with availability status: true
2015-12-18T11:31:47.755Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18T11:31:47.755Z SendDataConnector.js: do connect now
,2015-12-18 12:31:47.756 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:47.756 ThaliTest[339:393744] client: connect: unreachable Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:47.757 ThaliTest[339:393744] jxcor,e: connect: fail: Peer unreachable
,2015-12-18T11:31:47.757Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:47.757Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:47.758Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:52.762Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:31:52.762Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:53.106 ThaliTest[339:393546] multipeer session: restart
,2015-12-18 12:31:53.152 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:31:53.152 ThaliTest[339:393546] client: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:31:53.153 ThaliTest[339:393546] client: fou,nd peer: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:31:57.765 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:31:57.766 ThaliTest[339:393744] jxcore: disconnect: fail
2015-12-18T11:31:57.767Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.H3bAHA==,
2015-12-18T11:31:57.767Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6115.H3bAHA== with availability status: true
2015-12-18T11:31:57.768Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:31:57.768Z SendDataConnector.js: do connect now
2015-12-18 12:31:57.769 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:57.769 ThaliTest[339:393744] client: connect: unreachable Apple-IpadAir2-1_PT611,5.H3bAHA==
2015-12-18 12:31:57.770 ThaliTest[339:393744] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:31:57.770Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:57.770Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:57.770Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:02.780Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18T11:32:02.781Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:32:07.793 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:32:07.793 ThaliTest[339:393744] jxcore: disconnect: fail
2015-12-18T11:32:07.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.H3bAHA==,
2015-12-18T11:32:07.794Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6115.H3bAHA== with availability status: true
2015-12-18T11:32:07.795Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18T11:32:07.795Z SendDataConnector.js: do connect now
,2015-12-18 12:32:07.796 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:32:07.797 ThaliTest[339:393744] client: connect: unreachable Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:32:07.797 ThaliTest[339:393744] jxcor,e: connect: fail: Peer unreachable
,2015-12-18T11:32:07.797Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:07.797Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-18T11:32:07.799Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 12:32:07.800 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:32:07.800 ThaliTest[339:393744] jxcore: disconnect: fail
2015-12-18T11:32:07.800Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.H3bAHA==
,---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:07.802Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:07.802Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:07.803Z SendDataConnector.js: do connect now
,2015-12-18 12:32:07.803 ThaliTest[339:393744] jxcore: connect Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:07.804 ThaliTest[339:393744] client session: connect
,2015-12-18 12:32:07.804 ThaliTest[339:393744] client session: stateChange:0->1 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:09.275 ThaliTest[339:393546] multipeer session: reset timer
2015-12-18 12:32:09.275 ThaliTest[339:393546] multipeer session: stop timer
2015-12-18 12:32:09.275 ThaliTest[339:393546] multipeer session: start timer: 0x1cb4be50
,2015-12-18 12:32:09.276 ThaliTest[339:393546] server session: connect
2015-12-18 12:32:09.277 ThaliTest[339:393546] server session: stateChange:0->1 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:09.282 ThaliTest[339:393546] server: accepting invitation Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:10.654 ThaliTest[339:394693] client session: connected
2015-12-18 12:32:10.654 ThaliTest[339:394693] client session: stateChange:1->2 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:10.697 ThaliTest[339:394710] client session: fireConnectCallback: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:10.697 ThaliTest[339:394710] jxcore: connect: success
2015-12-18T11:32:10.698Z SendDataConnector.js: CLIENT connected to 52323, error: null
2015-12-18T11:32:10.698Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:10.701 ThaliTest[339:393546] client: relay established
2015-12-18 12:32:10.701 ThaliTest[339:393546] client: new accepted socket: 0x1cc9bcc0
,2015-12-18T11:32:10.717Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 12:32:11.262 ThaliTest[339:393546] multipeer session: reset timer
2015-12-18 12:32:11.262 ThaliTest[339:393546] multipeer session: stop timer
2015-12-18 12:32:11.262 ThaliTest[339:393546] multipeer session: start timer: 0x1cb4be50
2015-12-18 ,12:32:11.263 ThaliTest[339:393546] server session: connect
2015-12-18 12:32:11.263 ThaliTest[339:393546] server session: stateChange:0->1 Apple-Iphone5s-1_PT8285
2015-12-18 12:32:11.268 ThaliTest[339:393546] server: accepting invitation Apple-Iphone5s-1_,PT8285
,2015-12-18T11:32:11.304Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T11:32:11.318Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T11:32:11.330Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:11.331Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:11.332Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:11.333Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:11.334 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:32:11.335 ThaliTest[339:393744] client session: disconnectFromPeer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:11.335 ThaliTest[339:393744] client session: disconnect
,2015-12-18 12:32:11.336 ThaliTest[339:393744] client session: stateChange:2->0 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:11.361 ThaliTest[339:393744] jxcore: disconnect: success
2015-12-18T11:32:11.363Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3077.TwkGOQ==
---- round done--------
startWithNextDevice
device[3]: Apple,-IpadAir2-1_PT6115.GXbC4w==
2015-12-18T11:32:11.364Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:11.365Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:11.366Z SendDataConnector.js: do connect now
,2015-12-18 12:32:11.367 ThaliTest[339:393744] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:11.369 ThaliTest[339:393744] client session: connect
,2015-12-18 12:32:11.370 ThaliTest[339:393744] client session: stateChange:0->1 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:11.977 ThaliTest[339:394710] server session: connected
2015-12-18 12:32:11.977 ThaliTest[339:394710] server session: stateChange:1->2 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:12.004 ThaliTest[339:393546] server relay: connected (to port: 52319)
2015-12-18T11:32:12.016Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:12.221Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T11:32:12.237Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T11:32:12.254Z SendDataTCPServer.js: TCP/IP server has received 68010 bytes of data
,2015-12-18T11:32:12.269Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:12.319 ThaliTest[339:394688] server session: not connected Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:14.045 ThaliTest[339:394688] server session: connected
2015-12-18 12:32:14.045 ThaliTest[339:394688] server session: stateChange:1->2 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:14.271 ThaliTest[339:394693] client session: connected
,2015-12-18 12:32:14.272 ThaliTest[339:393546] server relay: connected (to port: 52319)
2015-12-18 12:32:14.271 ThaliTest[339:394693] client session: stateChange:1->2 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:14.280Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 12:32:14.293 ThaliTest[339:394685] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:14.293 ThaliTest[339:394685] jxcore: connect: success
2015-12-18T11:32:14.295Z SendDataConnector.js: CLIENT connected to ,52328, error: null
2015-12-18T11:32:14.295Z SendDataConnector.js: CLIENT starting client 
2015-12-18 12:32:14.297 ThaliTest[339:393546] client: relay established
2015-12-18 12:32:14.297 ThaliTest[339:393546] client: new accepted socket: 0x1ccabcc0
,2015-12-18T11:32:14.310Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:14.828Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T11:32:14.858Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T11:32:14.896Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:14.910Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18 12:32:14.918 ThaliTest[339:394693] server session: not connected Apple-Iphone5s-1_PT8285
,2015-12-18T11:32:14.922Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T11:32:14.936Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T11:32:14.937Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:14.938Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:14.939Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:14.940 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:32:14.940 ThaliTest[339:393744] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:14.940 ThaliTest[339:393744] client session: disconnect
2015-12-18 12:32:14.941 ThaliTest[339:393744] client session: stateChange:2->0 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:14.950 ThaliTest[339:393744] jxcore: disconnect: success
2015-12-18T11:32:14.950Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT8285.14R9MQ==
2015-12-18T11:32:14.951Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18T11:32:14.951Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18T11:,32:14.951Z SendDataConnector.js: do connect now
2015-12-18 12:32:14.952 ThaliTest[339:393744] jxcore: connect Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:14.952 ThaliTest[339:393744] client session: connect
2015-12-18 12:32:14.952 ThaliTest[339:39,3744] client session: stateChange:0->1 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:18.061 ThaliTest[339:394723] client session: connected
2015-12-18 12:32:18.061 ThaliTest[339:394723] client session: stateChange:1->2 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:18.080 ThaliTest[339:394688] client session: fireConnectCallback: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:18.080 ThaliTest[339:394688] jxcore: connect: success
,2015-12-18T11:32:18.081Z SendDataConnector.js: CLIENT connected to 52331, error: null
2015-12-18T11:32:18.081Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:18.083 ThaliTest[339:393546] client: relay established
,2015-12-18 12:32:18.084 ThaliTest[339:393546] client: new accepted socket: 0x1cb2e870
,2015-12-18T11:32:18.096Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:18.661Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T11:32:18.726Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T11:32:18.727Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:18.729Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:18.729Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:18.730 ThaliTest[339:393744] jxcore: disconnect
2015-12-18 12:32:18.730 ThaliTest[339:393744] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:18.731 ThaliTest[339:393744] client session: disconnect
,2015-12-18 12:32:18.731 ThaliTest[339:393744] client session: stateChange:2->0 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:18.738 ThaliTest[339:393744] jxcore: disconnect: success
2015-12-18T11:32:18.738Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.14R9MQ==
---- round done--------
startWithNextDevice
weAreDoneNow, r,esultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-18T11:32:18.743Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:18.743Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:23.454 ThaliTest[339:393546] client: lost peer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:23.455 ThaliTest[339:393546] client session: onPeerLost: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:23.455 ThaliTest[339:393546] client: lost peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:23.457 ThaliTest[339:393546] client session: onPeerLost: Apple-IpadAir2-1_PT6115.GXbC4w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable",:false}]
startWithNextDevice
,2015-12-18 12:32:41.264 ThaliTest[339:393546] multipeer session: restart
,2015-12-18 12:32:41.300 ThaliTest[339:393546] client: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:41.301 ThaliTest[339:393546] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:41.301 ThaliTest[339:393546] client: fou,nd peer: Apple-IpadAir2-1_PT6115.GXbC4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXb,C4w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 12:32:50.030 ThaliTest[339:393546] multipeer session: reset timer
2015-12-18 12:32:50.031 ThaliTest[339:393546] multipeer session: stop timer
2015-12-18 12:32:50.031 ThaliTest[339:393546] multipeer session: start timer: 0x1cb4be50
2015-12-18 ,12:32:50.031 ThaliTest[339:393546] server session: connect
2015-12-18 12:32:50.031 ThaliTest[339:393546] server session: stateChange:0->1 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:50.038 ThaliTest[339:393546] server: accepting invitation Apple-Iphone6-1_PT3077
,2015-12-18 12:32:52.526 ThaliTest[339:394873] server session: connected
2015-12-18 12:32:52.526 ThaliTest[339:394873] server session: stateChange:1->2 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:52.545 ThaliTest[339:393546] server relay: connected (to port: 52319)
,2015-12-18T11:32:52.552Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:52.807Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T11:32:52.823Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-18T11:32:52.837Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-18T11:32:52.851Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-18T11:32:52.865Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:52.899 ThaliTest[339:394866] server session: not connected Apple-Iphone6-1_PT3077
,teardown
,testSendData stopped
,2015-12-18 12:32:57.095 ThaliTest[339:393744] jxcore: stopBroadcasting
2015-12-18 12:32:57.095 ThaliTest[339:393744] THEMultipeerSession stopping peer
,2015-12-18 12:32:57.095 ThaliTest[339:393744] multipeer session: stop timer
,2015-12-18 12:32:57.096 ThaliTest[339:393744] server session: disconnect
2015-12-18 12:32:57.096 ThaliTest[339:393744] server session: stateChange:2->0 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:57.101 ThaliTest[339:393744] server session: disconnect
2015-12-18 12:32:57.102 ThaliTest[339:393744] server session: stateChange:2->0 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:57.110 ThaliTest[339:393744] server session: disconnect
2015-12-18 12:32:57.111 ThaliTest[339:393744] server session: stateChange:2->0 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:57.413 ThaliTest[339:393744] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T11:32:57.431Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.433Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.434Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.434Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
