#### Test 552541413820a6d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/41CB7B2B-133E-46B6-B5AF-FEBC83E31EEF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/41CB7B2B-133E-46B6-B5AF-FEBC83E31EEF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7ECF5716-635B-4D5C-8E7E-F9BE96199B0C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49299"
,(lldb)     command script import "/tmp/41CB7B2B-133E-46B6-B5AF-FEBC83E31EEF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-06 20:50:25.984 ThaliTest[1392:2986788] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B4C41B2-1246-43B4-9E46-C754C029D680/Library/Cookies/Cookies.binarycookies
,2016-01-06 20:50:26.344 ThaliTest[1392:2986788] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-06 20:50:26.345 ThaliTest[1392:2986788] Multi-tasking -> Device: YES, App: YES
,2016-01-06 20:50:26.355 ThaliTest[1392:2986788] Unlimited access to network resources
,2016-01-06 20:50:26.366 ThaliTest[1392:2986788] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-06 20:50:35.510 ThaliTest[1392:2986788] Resetting plugins due to page load.
,2016-01-06 20:50:38.788 ThaliTest[1392:2986788] Finished load of: file:///var/mobile/Containers/Bundle/Application/7ECF5716-635B-4D5C-8E7E-F9BE96199B0C/ThaliTest.app/www/index.html
,2016-01-06 20:50:38.975 ThaliTest[1392:2986788] JXcore Cordova plugin initializing
,2016-01-06 20:50:38.977 ThaliTest[1392:2987020] JXcore instance initializing
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
,2016-01-06 20:50:40.061 ThaliTest[1392:2986788] THREAD WARNING: ['JXcore'] took '80.155029' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-06 20:57:02.705 ThaliTest[1392:2987020] jxcore: startBroadcasting
,2016-01-06 20:57:02.721 ThaliTest[1392:2987020] server: starting Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:02.722 ThaliTest[1392:2987020] multipeer session: start timer: 0x16c50830
2016-01-06 20:57:02.723 ThaliTest[1392:2987020] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9564
,2016-01-06 20:57:02.726 ThaliTest[1392:2987020] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-06 20:57:03.752 ThaliTest[1392:2986788] client: found peer: Apple-IpadAir2-1_PT6789.T0JZzA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-06 20:57:03.957 ThaliTest[1392:2986788] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:11.124 ThaliTest[1392:2986788] client: found peer: Apple-Iphone5s-1_PT1776.pROaFQ==
,teardown
,testFindPeers stopped
,2016-01-06 20:57:11.822 ThaliTest[1392:2987020] jxcore: stopBroadcasting
,2016-01-06 20:57:11.824 ThaliTest[1392:2987020] THEMultipeerSession stopping peer
2016-01-06 20:57:11.824 ThaliTest[1392:2987020] multipeer session: stop timer
2016-01-06 20:57:11.825 ThaliTest[1392:2987020] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 63762
,2016-01-06 20:57:11.864 ThaliTest[1392:2987020] jxcore: startBroadcasting
,2016-01-06 20:57:11.867 ThaliTest[1392:2987020] server: starting Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:11.868 ThaliTest[1392:2987020] multipeer session: start timer: 0x16c52ef0
2016-01-06 20:57:11.868 ThaliTest[1392:2987020] THEMultipeerSession initialized peer Apple-Iphone6-1_PT9564
2016-01-06 20:57:11.869 ThaliTest[1392:2987020] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-06T19:57:11.874Z SendDataTCPServer.js: TCP/IP server is bound to port: 63762
,2016-01-06 20:57:12.790 ThaliTest[1392:2986788] client: found peer: Apple-Iphone6-1_PT9564.cvfn7A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerName":"(null)","peerAvailable":true}]
2016-01-06 20:57:12.793 ThaliTest[,1392:2986788] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:12.802Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:12.803Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:12.803Z SendDataConnector.js: do connect now
,2016-01-06 20:57:12.804 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:12.806 ThaliTest[1392:2987020] client session: connect
,2016-01-06 20:57:12.807 ThaliTest[1392:2987020] client session: stateChange:0->1 Apple-Iphone6-1_PT9564.cvfn7A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:12.893 ThaliTest[1392:2986788] client: lost peer: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:12.894 ThaliTest[1392:2986788] client session: onPeerLost: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:12.894 ThaliTest[1392:2986788], client session: onLinkFailure: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:12.894 ThaliTest[1392:2986788] client session: disconnect
2016-01-06 20:57:12.894 ThaliTest[1392:2986788] client session: stateChange:1->0 Apple-Iphone6-1_PT9564.cvfn7A==
2,016-01-06 20:57:12.895 ThaliTest[1392:2986788] client session: fireConnectCallback: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:12.895 ThaliTest[1392:2986788] jxcore: connect: fail: Peer disconnected
2016-01-06 20:57:12.896 ThaliTest[1392:2986788] c,lient: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:57:12.901Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-06T19:57:12.904Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-06T19:57:12.905Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.cvfn7A==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.hQhn/g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-06 20:57:13.263 ThaliTest[1392:2986788] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1776.mp8cwQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:15.364 ThaliTest[1392:2986788] multipeer session: reset timer
2016-01-06 20:57:15.364 ThaliTest[1392:2986788] multipeer session: stop timer
2016-01-06 20:57:15.364 ThaliTest[1392:2986788] multipeer session: start timer: 0x16c52ef0
2016-,01-06 20:57:15.365 ThaliTest[1392:2986788] server session: connect
2016-01-06 20:57:15.365 ThaliTest[1392:2986788] server session: stateChange:0->1 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:15.374 ThaliTest[1392:2986788] server: accepting invitation Apple-Iphone5-1_PT2360
,2016-01-06 20:57:16.286 ThaliTest[1392:2986788] client: lost peer: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:16.286 ThaliTest[1392:2986788] client session: onPeerLost: Apple-Iphone5-1_PT2360.KoeEnA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-06 20:57:16.421 ThaliTest[1392:2986788] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.wZr66g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06T19:57:17.912Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06T19:57:17.913Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:18.050 ThaliTest[1392:2988378] server session: connected
2016-01-06 20:57:18.050 ThaliTest[1392:2988378] server session: stateChange:1->2 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:18.058 ThaliTest[1392:2986788] server relay: connected (to port: 63762)
,2016-01-06T19:57:18.068Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:57:18.623Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-06T19:57:18.638Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-06T19:57:18.651Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-06T19:57:18.669Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-06T19:57:18.684Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:57:18.760 ThaliTest[1392:2988374] server session: not connected Apple-Iphone5-1_PT2360
,2016-01-06 20:57:22.925 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:57:22.925 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:57:22.926Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.cvfn7,A==
2016-01-06T19:57:22.926Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT9564.cvfn7A== with availability status: true
2016-01-06T19:57:22.927Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:22.927Z SendDataConnector.js: do connect now
,2016-01-06 20:57:22.928 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:22.929 ThaliTest[1392:2987020] client: connect: unreachable Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:22.929 ThaliTest[1392:2987020] j,xcore: connect: fail: Peer unreachable
2016-01-06T19:57:22.930Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:22.930Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:57:22.931Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:27.935Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:27.935Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:32.945 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:57:32.946 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:57:32.947Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.cvfn7,A==
2016-01-06T19:57:32.947Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT9564.cvfn7A== with availability status: true
2016-01-06T19:57:32.947Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.cvfn7A==
2,016-01-06T19:57:32.947Z SendDataConnector.js: do connect now
,2016-01-06 20:57:32.948 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:32.949 ThaliTest[1392:2987020] client: connect: unreachable Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:32.951 ThaliTest[1392:2987020] jxcore: connect: fail: Peer unreachable
2016-01-06T19:57:32.952Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:32.952Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:57:32.953Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:37.965Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:37.966Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:42.977 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:57:42.978 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:57:42.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.cvfn7,A==
2016-01-06T19:57:42.979Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT9564.cvfn7A== with availability status: true
2016-01-06T19:57:42.979Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06T19:57:42.979Z SendDataConnector.js: do connect now
,2016-01-06 20:57:42.980 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:42.981 ThaliTest[1392:2987020] client: connect: unreachable Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:42.982 ThaliTest[1392:2987020] jxcore: connect: fail: Peer unreachable
2016-01-06T19:57:42.982Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:42.983Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2016-01-06T19:57:42.983Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06 20:57:45.366 ThaliTest[1392:2986788] multipeer session: restart
,2016-01-06T19:57:47.991Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06T19:57:47.992Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:53.003 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:57:53.004 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:57:53.005Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.cvfn7,A==
2016-01-06T19:57:53.005Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT9564.cvfn7A== with availability status: true
2016-01-06T19:57:53.005Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.cvfn7A==
2,016-01-06T19:57:53.005Z SendDataConnector.js: do connect now
,2016-01-06 20:57:53.006 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:53.007 ThaliTest[1392:2987020] client: connect: unreachable Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:53.007 ThaliTest[1392:2987020] j,xcore: connect: fail: Peer unreachable
,2016-01-06T19:57:53.008Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:53.009Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-06T19:57:53.012Z SendDataConnector.js: CLIENT Stop now
,2016-01-06 20:57:53.013 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:57:53.014 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:57:53.014Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.cvfn7,A==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:57:53.018Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:57:53.019Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:57:53.020Z SendDataConnector.js: do connect now
,2016-01-06 20:57:53.021 ThaliTest[1392:2987020] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.021 ThaliTest[1392:2987020] client session: connect
2016-01-06 20:57:53.021 ThaliTest[1392:2987020] client session: stateChange:0->1 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:53.033 ThaliTest[1392:2986788] client: lost peer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.033 ThaliTest[1392:2986788] client session: onPeerLost: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.033 ThaliTest[1392:298678,8] client session: onLinkFailure: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.034 ThaliTest[1392:2986788] client session: disconnect
2016-01-06 20:57:53.034 ThaliTest[1392:2986788] client session: stateChange:1->0 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:53.089 ThaliTest[1392:2986788] client session: fireConnectCallback: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.090 ThaliTest[1392:2986788] jxcore: connect: fail: Peer disconnected
2016-01-06T19:57:53.091Z SendDataConnector.js: ,CLIENT connected to 0, error: Peer disconnected
2016-01-06T19:57:53.092Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-06T19:57:53.096Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"A,pple-IpadAir2-1_PT6789.hQhn/g==","peerName":"(null)","peerAvailable":false}]
,2016-01-06 20:57:53.161 ThaliTest[1392:2986788] multipeer session: reset timer
,2016-01-06 20:57:53.163 ThaliTest[1392:2986788] multipeer session: stop timer
,2016-01-06 20:57:53.163 ThaliTest[1392:2986788] multipeer session: start timer: 0x16c52ef0
,2016-01-06 20:57:53.164 ThaliTest[1392:2986788] server session: connect
2016-01-06 20:57:53.164 ThaliTest[1392:2986788] server session: stateChange:0->1 Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:53.173 ThaliTest[1392:2986788] server: accepting invitation Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:56.759 ThaliTest[1392:2988516] server session: connected
2016-01-06 20:57:56.759 ThaliTest[1392:2988516] server session: stateChange:1->2 Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:56.766 ThaliTest[1392:2986788] server relay: connected (to port: 63762)
2016-01-06T19:57:56.772Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06 20:57:56.821 ThaliTest[1392:2986788] multipeer session: reset timer
2016-01-06 20:57:56.821 ThaliTest[1392:2986788] multipeer session: stop timer
2016-01-06 20:57:56.822 ThaliTest[1392:2986788] multipeer session: start timer: 0x16c52ef0
2016-,01-06 20:57:56.822 ThaliTest[1392:2986788] server session: connect
2016-01-06 20:57:56.822 ThaliTest[1392:2986788] server session: stateChange:0->1 Apple-Iphone5s-1_PT1776
,2016-01-06 20:57:56.831 ThaliTest[1392:2986788] server: accepting invitation Apple-Iphone5s-1_PT1776
,2016-01-06T19:57:57.041Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-06T19:57:57.054Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-06T19:57:57.067Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06T19:57:58.106Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:57:58.107Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:59.349 ThaliTest[1392:2988519] server session: connected
2016-01-06 20:57:59.349 ThaliTest[1392:2988519] server session: stateChange:1->2 Apple-Iphone5s-1_PT1776
,2016-01-06 20:57:59.366 ThaliTest[1392:2986788] server relay: connected (to port: 63762)
,2016-01-06T19:57:59.374Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:57:59.848Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-06T19:57:59.866Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-06T19:57:59.881Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-06T19:57:59.898Z SendDataTCPServer.js: TCP/IP server has received 93886 bytes of data
,2016-01-06T19:57:59.914Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:57:59.950 ThaliTest[1392:2988494] server session: not connected Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:03.119 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:03.119 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:58:03.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn,/g==
2016-01-06T19:58:03.120Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6789.hQhn/g== with availability status: true
2016-01-06T19:58:03.121Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:58:03.121Z SendDataConnector.js: do connect now
,2016-01-06 20:58:03.122 ThaliTest[1392:2987020] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:03.123 ThaliTest[1392:2987020] client: connect: unreachable Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:03.124 ThaliTest[1392:2987020], jxcore: connect: fail: Peer unreachable
2016-01-06T19:58:03.124Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:58:03.124Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:58:03.125Z SendD,ataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:58:08.132Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:58:08.133Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:08.175 ThaliTest[1392:2988518] server session: not connected Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:13.137 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:13.138 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:58:13.138Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn,/g==
2016-01-06T19:58:13.139Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT6789.hQhn/g== with availability status: true
2016-01-06T19:58:13.139Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==,
2016-01-06T19:58:13.140Z SendDataConnector.js: do connect now
,2016-01-06 20:58:13.141 ThaliTest[1392:2987020] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:13.142 ThaliTest[1392:2987020] client: connect: unreachable Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:13.142 ThaliTest[1392:2987020], jxcore: connect: fail: Peer unreachable
2016-01-06T19:58:13.142Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:58:13.143Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:58:13.143Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:58:18.147Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:58:18.148Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:23.153 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:23.154 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:58:23.154Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn,/g==
2016-01-06T19:58:23.155Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT6789.hQhn/g== with availability status: true
2016-01-06T19:58:23.155Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:58:23.155Z SendDataConnector.js: do connect now
2016-01-06 20:58:23.157 ThaliTest[1392:2987020] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:23.157 ThaliTest[1392:2987020] client: connect: unreachable Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:23.158 ThaliTest[1392:2987020] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:58:23.159Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:58:23.160Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:58:23.160Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06 20:58:26.823 ThaliTest[1392:2986788] multipeer session: restart
,2016-01-06 20:58:26.859 ThaliTest[1392:2986788] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:26.862 ThaliTest[1392:2986788] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:26.863 ThaliTest[1392:2986788] clie,nt: found peer: Apple-Iphone5-1_PT2360.wZr66g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.hQhn/g==","peerName":"(null)","peerAvailable":true}]
,2016-01-06T19:58:28.164Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06T19:58:28.165Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:33.178 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:33.179 ThaliTest[1392:2987020] jxcore: disconnect: fail
2016-01-06T19:58:33.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn,/g==
2016-01-06T19:58:33.180Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT6789.hQhn/g== with availability status: true
2016-01-06T19:58:33.180Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==,
2016-01-06T19:58:33.180Z SendDataConnector.js: do connect now
,2016-01-06 20:58:33.181 ThaliTest[1392:2987020] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:33.182 ThaliTest[1392:2987020] client session: connect
2016-01-06 20:58:33.183 ThaliTest[1392:2987020] client session: stateChange:0->1 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:36.685 ThaliTest[1392:2988588] client session: connected
2016-01-06 20:58:36.685 ThaliTest[1392:2988588] client session: stateChange:1->2 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:36.689 ThaliTest[1392:2988588] client session: fireConnectCallback: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:36.690 ThaliTest[1392:2988588] jxcore: connect: success
,2016-01-06T19:58:36.693Z SendDataConnector.js: CLIENT connected to 63773, error: null
2016-01-06T19:58:36.693Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:36.697 ThaliTest[1392:2986788] client: relay established
2016-01-06 20:58:36.698 ThaliTest[1392:2986788] client: new accepted socket: 0x16be5f90
,2016-01-06T19:58:36.712Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:37.129Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:58:37.142Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-06T19:58:37.155Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:58:37.155Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-06T19:58:37.156Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:37.156Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:37.157 ThaliTest[1392:2987020] jxcore: disconnect
,2016-01-06 20:58:37.157 ThaliTest[1392:2987020] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:37.158 ThaliTest[1392:2987020] client session: disconnect
,2016-01-06 20:58:37.158 ThaliTest[1392:2987020] client session: stateChange:2->0 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:37.223 ThaliTest[1392:2987020] jxcore: disconnect: success
,2016-01-06T19:58:37.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn/g==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06T19:58:37.225Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06T19:58:37.225Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06T19:58:37.225Z SendDataConnector.js: do connect now
,2016-01-06 20:58:37.226 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:37.226 ThaliTest[1392:2987020] client session: connect
,2016-01-06 20:58:37.227 ThaliTest[1392:2987020] client session: stateChange:0->1 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:39.776 ThaliTest[1392:2988581] client session: connected
,2016-01-06 20:58:39.776 ThaliTest[1392:2988581] client session: stateChange:1->2 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:39.797 ThaliTest[1392:2988587] client session: fireConnectCallback: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:39.797 ThaliTest[1392:2988587] jxcore: connect: success
,2016-01-06T19:58:39.799Z SendDataConnector.js: CLIENT connected to 63776, error: null
,2016-01-06T19:58:39.800Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:39.804 ThaliTest[1392:2986788] client: relay established
2016-01-06 20:58:39.804 ThaliTest[1392:2986788] client: new accepted socket: 0x16beeb30
,2016-01-06T19:58:39.817Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:40.281Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-06T19:58:40.307Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:58:40.307Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-06T19:58:40.308Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:40.308Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:40.308 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:40.309 ThaliTest[1392:2987020] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:40.309 ThaliTest[1392:2987020] client session: discon,nect
2016-01-06 20:58:40.309 ThaliTest[1392:2987020] client session: stateChange:2->0 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:58:40.316 ThaliTest[1392:2987020] jxcore: disconnect: success
2016-01-06T19:58:40.318Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:40.318Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:40.318Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06T19:58:40.319Z SendDataConnector.js: do connect now
2016-01-06 20:58:40.321 ThaliTest[1392:2987020] jxcore: connect Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:40.321 ThaliTest[1392:2987020] client session: connect
2016-01-06 20:58:40.321 ThaliTest[1392:2987020] client session: stateChange:0->1 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:43.483 ThaliTest[1392:2988588] client session: connected
2016-01-06 20:58:43.483 ThaliTest[1392:2988588] client session: stateChange:1->2 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:43.490 ThaliTest[1392:2988588] client session: fireConnectCallback: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:43.490 ThaliTest[1392:2988588] jxcore: connect: success
2016-01-06T19:58:43.491Z SendDataConnector.js: CLIENT connected ,to 63779, error: null
2016-01-06T19:58:43.492Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:43.496 ThaliTest[1392:2986788] client: relay established
2016-01-06 20:58:43.496 ThaliTest[1392:2986788] client: new accepted socket: 0x16be63d0
,2016-01-06T19:58:43.509Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:43.950Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-06T19:58:43.972Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:58:43.984Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-06T19:58:43.997Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-06T19:58:43.997Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-06T19:58:43.997Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:43.998Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:43.998 ThaliTest[1392:2987020] jxcore: disconnect
2016-01-06 20:58:43.998 ThaliTest[1392:2987020] client session: disconnectFromPeer: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:43.998 ThaliTest[1392:2987020] client session: disconnect
2016-01-06 20:58:43.998 ThaliTest[1392:2987020] client session: stateChange:2->0 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:44.002 ThaliTest[1392:2987020] jxcore: disconnect: success
2016-01-06T19:58:44.002Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.wZr66g==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-06T19:58:44.013Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:44.013Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:56.823 ThaliTest[1392:2986788] multipeer session: restart
,teardown
,testSendData stopped
,2016-01-06 20:59:02.684 ThaliTest[1392:2987020] jxcore: stopBroadcasting
,2016-01-06 20:59:02.686 ThaliTest[1392:2987020] THEMultipeerSession stopping peer
2016-01-06 20:59:02.686 ThaliTest[1392:2987020] multipeer session: stop timer
2016-01-06 20:59:02.686 ThaliTest[1392:2987020] server session: disconnect
2016-01-06 20:59:0,2.687 ThaliTest[1392:2987020] server session: stateChange:2->0 Apple-Iphone5-1_PT2360
,2016-01-06 20:59:02.695 ThaliTest[1392:2987020] server session: disconnect
2016-01-06 20:59:02.696 ThaliTest[1392:2987020] server session: stateChange:2->0 Apple-Iphone5s-1_PT1776
,2016-01-06 20:59:02.708 ThaliTest[1392:2987020] server session: disconnect
2016-01-06 20:59:02.708 ThaliTest[1392:2987020] server session: stateChange:2->0 Apple-IpadAir2-1_PT6789
,2016-01-06 20:59:02.782 ThaliTest[1392:2987020] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-06T19:59:02.799Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:02.801Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:02.802Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:02.803Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
