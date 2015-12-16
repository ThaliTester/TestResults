#### Test 50650278923ff9f_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4B689914-7E7C-4A18-B2B2-2EC684599A2A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4B689914-7E7C-4A18-B2B2-2EC684599A2A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BB58AEBC-AEF9-499B-82B6-624726D2EAC2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58622"
,(lldb)     command script import "/tmp/4B689914-7E7C-4A18-B2B2-2EC684599A2A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 16:42:41.922 ThaliTest[251:122202] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC68B511-116A-4C10-ADF1-58383F8B4DC8/Library/Cookies/Cookies.binarycookies
,2015-12-16 16:42:42.046 ThaliTest[251:122202] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 16:42:42.048 ThaliTest[251:122202] Multi-tasking -> Device: YES, App: YES
,2015-12-16 16:42:42.053 ThaliTest[251:122202] Unlimited access to network resources
,2015-12-16 16:42:42.068 ThaliTest[251:122202] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 16:42:52.331 ThaliTest[251:122202] Resetting plugins due to page load.
,2015-12-16 16:42:56.590 ThaliTest[251:122202] Finished load of: file:///var/mobile/Containers/Bundle/Application/BB58AEBC-AEF9-499B-82B6-624726D2EAC2/ThaliTest.app/www/index.html
,2015-12-16 16:42:56.798 ThaliTest[251:122202] JXcore Cordova plugin initializing
,2015-12-16 16:42:56.799 ThaliTest[251:122520] JXcore instance initializing
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
,2015-12-16 16:42:59.255 ThaliTest[251:122202] THREAD WARNING: ['JXcore'] took '155.271240' ms. Plugin should use a background thread.
,appEnteringBackground wasn't registered
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 16:49:28.775 ThaliTest[251:122520] jxcore: startBroadcasting
,2015-12-16 16:49:28.787 ThaliTest[251:122520] server: starting Apple-Iphone5-1_PT9225.vQjqPA==
,2015-12-16 16:49:28.789 ThaliTest[251:122520] multipeer session: start timer: 0x1ac44aa0
,2015-12-16 16:49:28.790 ThaliTest[251:122520] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9225
2015-12-16 16:49:28.790 ThaliTest[251:122520] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-16 16:49:29.620 ThaliTest[251:122202] client: found peer: Apple-IpadAir2-1_PT1077.nIXSkg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT1077.nIXSkg==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-16 16:49:29.989 ThaliTest[251:122202] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:30.133 ThaliTest[251:122202] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
,teardown
,testFindPeers stopped
2015-12-16 16:49:31.039 ThaliTest[251:122520] jxcore: stopBroadcasting
,2015-12-16 16:49:31.039 ThaliTest[251:122520] THEMultipeerSession stopping peer
2015-12-16 16:49:31.040 ThaliTest[251:122520] multipeer session: stop timer
2015-12-16 16:49:31.040 ThaliTest[251:122520] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 50511
,2015-12-16 16:49:31.103 ThaliTest[251:122520] jxcore: startBroadcasting
,2015-12-16 16:49:31.106 ThaliTest[251:122520] server: starting Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:49:31.106 ThaliTest[251:122520] multipeer session: start timer: 0x1abb88b0
2015-12-16 16:49:31.106 ThaliTest[251:122520] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT9225
2015-12-16 16:49:31.107 ThaliTest[251:122520] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-16T15:49:31.110Z SendDataTCPServer.js: TCP/IP server is bound to port: 50511
,2015-12-16 16:49:31.588 ThaliTest[251:122202] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:31.588 ThaliTest[251:122202] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:31.588 ThaliTest[251:122202] client: fou,nd peer: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:31.590 ThaliTest[251:122202] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":,true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16T15:49:31.593Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16T15:49:31.593Z SendDataConnect,or.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16T15:49:31.593Z SendDataConnector.js: do connect now
2015-12-16 16:49:31.594 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:31.595 Thali,Test[251:122520] client session: connect
2015-12-16 16:49:31.598 ThaliTest[251:122520] client session: stateChange:0->1 Apple-Iphone5s-1_PT1155.WIj3og==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:49:32.170 ThaliTest[251:122202] client: lost peer: Apple-Iphone5-1_PT9225.vQjqPA==
2015-12-16 16:49:32.170 ThaliTest[251:122202] client session: onPeerLost: Apple-Iphone5-1_PT9225.vQjqPA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.vQjqPA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 16:49:32.632 ThaliTest[251:122202] client: lost peer: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.633 ThaliTest[251:122202] client session: onPeerLost: Apple-IpadAir2-1_PT1077.nIXSkg==
2015-12-16 16:49:32.633 ThaliTest[251:122202] cli,ent: lost peer: Apple-Iphone6-1_PT3392.Ts8/9g==
2015-12-16 16:49:32.633 ThaliTest[251:122202] client session: onPeerLost: Apple-Iphone6-1_PT3392.Ts8/9g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)","p,eerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.Ts8/9g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 16:49:32.717 ThaliTest[251:122202] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.EGNu6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-16 16:49:33.683 ThaliTest[251:122202] client: lost peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.683 ThaliTest[251:122202] client session: onPeerLost: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.683 ThaliTest[251:122202] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.683 ThaliTest[251:122202] client session: disconnect
2015-12-16 16:49:33.684 ThaliTest[251:122202] client session: stateChange:1->0 Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:33.748 ThaliTest[251:122202] client session: fireConnectCallback: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.748 ThaliTest[251:122202] jxcore: connect: fail: Peer disconnected
2015-12-16T15:49:33.749Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-16T15:49:33.750Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T15:49:33.750Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-16 16:49:33.750 ThaliTest[251:122202] cli,ent: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:49:33.751 ThaliTest[251:122202] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.WIj3og==","peerName":"(null)","peerAv,ailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.khzDiQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1155.Bev+OQ==",,"peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16T15:49:38.763Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:38.764Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:43.768 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:49:43.768 ThaliTest[251:122520] jxcore: disconnect: fail
2015-12-16T15:49:43.769Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:49:43.769Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:49:43.770Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:43.770Z SendDataConnector.js: do connect now
2015-12-16 16:49:43.771 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:43.771 ThaliTest[251:122520] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:43.772 ThaliTest[251:122520] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:49:43.773Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:49:43.774Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:43.774Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:48.778Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:48.779Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:53.788 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:49:53.788 ThaliTest[251:122520] jxcore: disconnect: fail
2015-12-16T15:49:53.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:49:53.789Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:49:53.790Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
20,15-12-16T15:49:53.790Z SendDataConnector.js: do connect now
,2015-12-16 16:49:53.791 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:53.791 ThaliTest[251:122520] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:53.791 ThaliTest[251:122520] jxcor,e: connect: fail: Peer unreachable
2015-12-16T15:49:53.792Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:49:53.792Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:53.792Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:58.801Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:58.802Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:01.108 ThaliTest[251:122202] multipeer session: restart
,2015-12-16 16:50:01.142 ThaliTest[251:122202] client: found peer: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:01.142 ThaliTest[251:122202] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:01.143 ThaliTest[251:122202] client: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:03.806 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:50:03.807 ThaliTest[251:122520] jxcore: disconnect: fail
2015-12-16T15:50:03.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:50:03.808Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:50:03.808Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
20,15-12-16T15:50:03.809Z SendDataConnector.js: do connect now
2015-12-16 16:50:03.810 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:50:03.810 ThaliTest[251:122520] client: connect: unreachable Apple-Iphone5s-1_PT1155.,WIj3og==
2015-12-16 16:50:03.810 ThaliTest[251:122520] jxcore: connect: fail: Peer unreachable
2015-12-16T15:50:03.810Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:03.811Z SendDataConnector.js: CLIENT Can not Co,nnect: Peer unreachable
,2015-12-16T15:50:03.813Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:50:08.823Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:50:08.824Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:13.056 ThaliTest[251:122202] multipeer session: reset timer
2015-12-16 16:50:13.056 ThaliTest[251:122202] multipeer session: stop timer
2015-12-16 16:50:13.057 ThaliTest[251:122202] multipeer session: start timer: 0x1abb88b0
2015-12-16 16:50:13.057 ThaliTest[251:122202] server session: connect
,2015-12-16 16:50:13.057 ThaliTest[251:122202] server session: stateChange:0->1 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:13.067 ThaliTest[251:122202] server: accepting invitation Apple-Iphone6-1_PT3392
,2015-12-16 16:50:13.837 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:50:13.838 ThaliTest[251:122520] jxcore: disconnect: fail
2015-12-16T15:50:13.838Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:50:13.839Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:50:13.839Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:50:13.840Z SendDataConnector.js: do connect now
2015-12-16 16:50:13.840 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:50:13.841 ThaliTest[251:122520] client: connect: unreachable Apple-Iphone5s-1_PT115,5.WIj3og==
2015-12-16 16:50:13.841 ThaliTest[251:122520] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:50:13.842Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:13.842Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-16T15:50:13.843Z SendDataConnector.js: CLIENT Stop now
2015-12-16 16:50:13.844 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:50:13.844 ThaliTest[251:122520] jxcore: disconnect: fail
2015-12-16T15:50:13.844Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.846Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.846Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:13.847Z SendDataConnector.js: do connect now
,2015-12-16 16:50:13.848 ThaliTest[251:122520] jxcore: connect Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:13.848 ThaliTest[251:122520] client session: connect
2015-12-16 16:50:13.848 ThaliTest[251:122520] client session: stateChange:0->1 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:15.735 ThaliTest[251:123388] server session: connected
2015-12-16 16:50:15.735 ThaliTest[251:123388] server session: stateChange:1->2 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:15.797 ThaliTest[251:122202] server relay: connected (to port: 50511)
,2015-12-16T15:50:15.802Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:16.182Z SendDataTCPServer.js: TCP/IP server has received 12288 bytes of data
,2015-12-16T15:50:16.195Z SendDataTCPServer.js: TCP/IP server has received 41326 bytes of data
,2015-12-16T15:50:16.211Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-16T15:50:16.228Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:16.265 ThaliTest[251:123381] server session: not connected Apple-Iphone6-1_PT3392
,2015-12-16 16:50:16.702 ThaliTest[251:123389] client session: connected
2015-12-16 16:50:16.702 ThaliTest[251:123389] client session: stateChange:1->2 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:16.713 ThaliTest[251:122202] multipeer session: reset timer
2015-12-16 16:50:16.713 ThaliTest[251:122202] multipeer session: stop timer
,2015-12-16 16:50:16.713 ThaliTest[251:122202] multipeer session: start timer: 0x1abb88b0
2015-12-16 16:50:16.715 ThaliTest[251:122202] server session: connect
,2015-12-16 16:50:16.715 ThaliTest[251:122202] server session: stateChange:0->1 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:16.724 ThaliTest[251:122202] server: accepting invitation Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:16.742 ThaliTest[251:123338] client session: fireConnectCallback: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:16.743 ThaliTest[251:123338] jxcore: connect: success
2015-12-16T15:50:16.744Z SendDataConnector.js: CLIENT connected to 5,0517, error: null
2015-12-16T15:50:16.745Z SendDataConnector.js: CLIENT starting client 
2015-12-16 16:50:16.749 ThaliTest[251:122202] client: relay established
2015-12-16 16:50:16.749 ThaliTest[251:122202] client: new accepted socket: 0x1ac60c10
,2015-12-16T15:50:16.761Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16 16:50:17.029 ThaliTest[251:122202] multipeer session: reset timer
2015-12-16 16:50:17.030 ThaliTest[251:122202] multipeer session: stop timer
2015-12-16 16:50:17.030 ThaliTest[251:122202] multipeer session: start timer: 0x1abb88b0
2015-12-16 ,16:50:17.030 ThaliTest[251:122202] server session: connect
2015-12-16 16:50:17.030 ThaliTest[251:122202] server session: stateChange:0->1 Apple-IpadAir2-1_PT1077
2015-12-16 16:50:17.037 ThaliTest[251:122202] server: accepting invitation Apple-IpadAir2-1_PT1077
,2015-12-16T15:50:17.407Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:17.429Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:17.441Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T15:50:17.456Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:17.456Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:17.458Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:17.459Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:17.460 ThaliTest[251:122520] jxcore: disconnect
,2015-12-16 16:50:17.461 ThaliTest[251:122520] client session: disconnectFromPeer: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:17.462 ThaliTest[251:122520] client session: disconnect
,2015-12-16 16:50:17.462 ThaliTest[251:122520] client session: stateChange:2->0 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:17.537 ThaliTest[251:122520] jxcore: disconnect: success
2015-12-16T15:50:17.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.EGNu6Q==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16T15:50:17.539Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16T15:50:17.540Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16T15:50:17.541Z SendDataConnector.js: do connect now
,2015-12-16 16:50:17.541 ThaliTest[251:122520] jxcore: connect Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:17.542 ThaliTest[251:122520] client session: connect
2015-12-16 16:50:17.542 ThaliTest[251:122520] client session: stateChange:0->1 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:19.246 ThaliTest[251:123668] server session: connected
2015-12-16 16:50:19.246 ThaliTest[251:123668] server session: stateChange:1->2 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:19.297 ThaliTest[251:122202] server relay: connected (to port: 50511)
2015-12-16T15:50:19.299Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:19.718Z SendDataTCPServer.js: TCP/IP server has received 12714 bytes of data
,2015-12-16T15:50:19.739Z SendDataTCPServer.js: TCP/IP server has received 41326 bytes of data
,2015-12-16T15:50:19.761Z SendDataTCPServer.js: TCP/IP server has received 82652 bytes of data
2015-12-16T15:50:19.776Z SendDataTCPServer.js: TCP/IP server has received 95650 bytes of data
,2015-12-16T15:50:19.793Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:19.806 ThaliTest[251:123680] server session: connected
,2015-12-16 16:50:19.807 ThaliTest[251:123680] server session: stateChange:1->2 Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:19.833 ThaliTest[251:122202] server relay: connected (to port: 50511)
,2015-12-16T15:50:19.835Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16 16:50:19.839 ThaliTest[251:123338] server session: not connected Apple-Iphone5s-1_PT1155
,2015-12-16T15:50:20.174Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-16T15:50:20.190Z SendDataTCPServer.js: TCP/IP server has received 30376 bytes of data
,2015-12-16T15:50:20.206Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-16T15:50:20.221Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-16T15:50:20.239Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:20.275 ThaliTest[251:123668] server session: not connected Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:20.411 ThaliTest[251:123668] client session: connected
2015-12-16 16:50:20.411 ThaliTest[251:123668] client session: stateChange:1->2 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:20.424 ThaliTest[251:123668] client session: fireConnectCallback: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:20.424 ThaliTest[251:123668] jxcore: connect: success
,2015-12-16T15:50:20.425Z SendDataConnector.js: CLIENT connected to 50522, error: null
,2015-12-16T15:50:20.425Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:20.429 ThaliTest[251:122202] client: relay established
2015-12-16 16:50:20.429 ThaliTest[251:122202] client: new accepted socket: 0x1ac76760
,2015-12-16T15:50:20.442Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:20.964Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:20.979Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-16T15:50:20.993Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T15:50:21.008Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:21.009Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:21.010Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:21.011Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:21.011 ThaliTest[251:122520] jxcore: disconnect
2015-12-16 16:50:21.012 ThaliTest[251:122520] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:21.012 ThaliTest[251:122520] client session: disconnect
2015-12-16 16:50:21.012 ThaliTest[251:122520] client session: stateChange:2->0 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:21.022 ThaliTest[251:122520] jxcore: disconnect: success
2015-12-16T15:50:21.024Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.khzDiQ==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:50:21.025Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:50:21.025Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16T15:,50:21.025Z SendDataConnector.js: do connect now
2015-12-16 16:50:21.025 ThaliTest[251:122520] jxcore: connect Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:21.026 ThaliTest[251:122520] client session: connect
2015-12-16 16:50:21.026 ThaliTest[251:122520] client session: stateChange:0->1 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:23.940 ThaliTest[251:123668] client session: connected
2015-12-16 16:50:23.941 ThaliTest[251:123668] client session: stateChange:1->2 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:23.965 ThaliTest[251:123338] client session: fireConnectCallback: Apple-Iphone5s-1_PT1155.Bev+OQ==
2015-12-16 16:50:23.965 ThaliTest[251:123338] jxcore: connect: success
2015-12-16T15:50:23.966Z SendDataConnector.js: CLIENT connected to ,50525, error: null
2015-12-16T15:50:23.966Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:23.969 ThaliTest[251:122202] client: relay established
2015-12-16 16:50:23.969 ThaliTest[251:122202] client: new accepted socket: 0x1ac638c0
,2015-12-16T15:50:23.982Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:24.530Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:24.544Z SendDataConnector.js: CLIENT is data received : 50000
2015-12-16T15:50:24.558Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:24.578Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T15:50:24.600Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:24.601Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:24.602Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:24.602Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:24.603 ThaliTest[251:122520] jxcore: disconnect
,2015-12-16 16:50:24.605 ThaliTest[251:122520] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:24.606 ThaliTest[251:122520] client session: disconnect
,2015-12-16 16:50:24.607 ThaliTest[251:122520] client session: stateChange:2->0 Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:50:24.695 ThaliTest[251:122520] jxcore: disconnect: success
,2015-12-16T15:50:24.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.Bev+OQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-16T15:50:24.708Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:24.708Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-16 16:50:34.450 ThaliTest[251:122520] jxcore: stopBroadcasting
2015-12-16 16:50:34.450 ThaliTest[251:122520] THEMultipeerSession stopping peer
2015-12-16 16:50:34.450 ThaliTest[251:122520] multipeer session: stop timer
2015-12-16 16:50:34.451 Th,aliTest[251:122520] server session: disconnect
2015-12-16 16:50:34.451 ThaliTest[251:122520] server session: stateChange:2->0 Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:34.459 ThaliTest[251:122520] server session: disconnect
2015-12-16 16:50:34.460 ThaliTest[251:122520] server session: stateChange:2->0 Apple-Iphone5s-1_PT1155
,2015-12-16 16:50:34.481 ThaliTest[251:122520] server session: disconnect
2015-12-16 16:50:34.482 ThaliTest[251:122520] server session: stateChange:2->0 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:34.548 ThaliTest[251:122520] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T15:50:34.565Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.566Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.567Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.568Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
