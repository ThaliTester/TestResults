#### Test 5065027857de7f1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/4DA159EB-020A-465F-AD4F-6989CD7743BD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4DA159EB-020A-465F-AD4F-6989CD7743BD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027857de7f1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/708894DD-9076-41D9-89BE-537160EDB654/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54039"
,(lldb)     command script import "/tmp/4DA159EB-020A-465F-AD4F-6989CD7743BD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 12:10:20.352 ThaliTest[818:698646] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1175F650-C198-45B7-8E9B-89AECE78D206/Library/Cookies/Cookies.binarycookies
,2015-12-11 12:10:20.365 ThaliTest[818:698646] <CATransformLayer: 0x146610c0> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-11 12:10:20.365 ThaliTest[818:698646] <CATransformLayer: 0x1474d0a0> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-11 12:10:20.366 ThaliTest[818:698646] <CATransformLayer: 0x1474e1f0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-11 12:10:20.652 ThaliTest[818:698646] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 12:10:20.653 ThaliTest[818:698646] Multi-tasking -> Device: YES, App: YES
,2015-12-11 12:10:20.661 ThaliTest[818:698646] Unlimited access to network resources
,2015-12-11 12:10:20.666 ThaliTest[818:698646] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 12:10:29.421 ThaliTest[818:698646] Resetting plugins due to page load.
,2015-12-11 12:10:32.494 ThaliTest[818:698646] Finished load of: file:///var/mobile/Containers/Bundle/Application/708894DD-9076-41D9-89BE-537160EDB654/ThaliTest.app/www/index.html
,2015-12-11 12:10:32.635 ThaliTest[818:698646] JXcore Cordova plugin initializing
,2015-12-11 12:10:32.636 ThaliTest[818:699206] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-11 12:10:33.681 ThaliTest[818:698646] THREAD WARNING: ['JXcore'] took '93.003906' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 12:15:25.957 ThaliTest[818:699206] jxcore: startBroadcasting
,2015-12-11 12:15:25.975 ThaliTest[818:699206] server: starting Apple-IpadAir2-1_PT2428.1YTBNQ==
,2015-12-11 12:15:25.977 ThaliTest[818:699206] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:15:25.978 ThaliTest[818:699206] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2428
2015-12-11 12:15:25.979 ThaliTest[818:699206] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-11 12:15:27.008 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:27.009 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.X/CFmw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.QOwtzQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT2932.QOwtzQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-11 12:15:29.706 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.IK91fw==
,2015-12-11 12:15:31.262 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:15:31.262 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:15:31.263 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:15:31.263 ThaliTest[818:698646] server session: connect
2015-12-11 12:15:31.263 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:15:31.270 ThaliTest[818:698646] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:15:31.304 ThaliTest[818:698646] client: lost peer: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:31.304 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone6-1_PT2932.QOwtzQ==
2015-12-11 12:15:31.304 ThaliTest[818:698646] clien,t: lost peer: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.305 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone5-1_PT2684.X/CFmw==
2015-12-11 12:15:31.306 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:15:31.335 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:15:33.388 ThaliTest[818:698646] client: lost peer: Apple-Iphone5s-1_PT8695.IK91fw==
2015-12-11 12:15:33.389 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone5s-1_PT8695.IK91fw==
2015-12-11 12:15:33.389 ThaliTest[818:698646] cli,ent: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:15:33.886 ThaliTest[818:699839] server session: connected
,2015-12-11 12:15:33.887 ThaliTest[818:699839] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:15:33.932 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:15:33.933 ThaliTest[818:698646] server relay: 0x163b2920 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:15:37.758 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:15:37.758 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:15:37.759 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
2015-12-11 12:15:37.759 ThaliTest[818:698646] server session: connect
2015-12-11 12:15:37.759 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:37.766 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:40.379 ThaliTest[818:699838] server session: connected
2015-12-11 12:15:40.379 ThaliTest[818:699838] server session: stateChange:1->2 Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:40.401 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:15:40.402 ThaliTest[818:698646] server relay: 0x163b8b80 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:15:44.305 ThaliTest[818:699839] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:15:50.738 ThaliTest[818:699837] server session: not connected Apple-Iphone5s-1_PT8695
,2015-12-11 12:15:54.394 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:15:54.394 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:15:54.394 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:15:54.395 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone6-1_PT2932)
2015-12-11 12:15:54.395 ThaliTest[818:698646] server session: disconnect
2015-12-11 12:15:54.395 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone6-1_PT2932
,2015-12-11 12:15:54.396 ThaliTest[818:698646] server session: connect
,2015-12-11 12:15:54.397 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:15:54.405 ThaliTest[818:698646] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:15:57.025 ThaliTest[818:699934] server session: connected
,2015-12-11 12:15:57.025 ThaliTest[818:699934] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:15:57.083 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:15:57.083 ThaliTest[818:698646] server relay: 0x164d3cb0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:16:01.139 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:01.139 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:16:01.139 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
2015-12-11 ,12:16:01.140 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8695)
2015-12-11 12:16:01.140 ThaliTest[818:698646] server session: disconnect
2015-12-11 12:16:01.140 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:01.141 ThaliTest[818:698646] server session: connect
2015-12-11 12:16:01.142 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:01.148 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:03.829 ThaliTest[818:699935] server session: connected
2015-12-11 12:16:03.829 ThaliTest[818:699935] server session: stateChange:1->2 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:03.833 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:16:03.834 ThaliTest[818:698646] server relay: 0x1472c5a0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:16:07.367 ThaliTest[818:699837] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:16:11.696 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:11.697 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:16:11.697 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:16:11.698 ThaliTest[818:698646] server session: connect
2015-12-11 12:16:11.698 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:11.705 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5-1_PT2684
,2015-12-11 12:16:14.188 ThaliTest[818:699837] server session: not connected Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:15.307 ThaliTest[818:699935] server session: connected
2015-12-11 12:16:15.307 ThaliTest[818:699935] server session: stateChange:1->2 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:15.354 ThaliTest[818:698646] server relay: socket disconnected
2015-12-11 12:16:15.355 ThaliTest[818:698646] server relay: 0x163b82c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,2015-12-11 12:16:17.525 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:17.525 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:16:17.526 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:16:17.526 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone6-1_PT2932)
2015-12-11 12:16:17.526 ThaliTest[818:698646] server session: disconnect
2015-12-11 12:16:17.526 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:17.527 ThaliTest[818:698646] server session: connect
2015-12-11 12:16:17.528 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:17.535 ThaliTest[818:698646] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:16:20.740 ThaliTest[818:700015] server session: connected
2015-12-11 12:16:20.741 ThaliTest[818:700015] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:20.800 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:16:20.800 ThaliTest[818:698646] server relay: 0x1472d380 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:16:24.795 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:24.796 ThaliTest[818:698646] multipeer session: stop timer
,2015-12-11 12:16:24.796 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
2015-12-11 12:16:24.796 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone5s-1_PT8695)
2015-12-11 12:16:24.797 ThaliTest[818:698646] server session: disconnect
,2015-12-11 12:16:24.797 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:24.798 ThaliTest[818:698646] server session: connect
2015-12-11 12:16:24.799 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:24.808 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:26.237 ThaliTest[818:700011] server session: not connected Apple-Iphone5-1_PT2684
,2015-12-11 12:16:28.136 ThaliTest[818:700012] server session: connected
2015-12-11 12:16:28.136 ThaliTest[818:700012] server session: stateChange:1->2 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:28.143 ThaliTest[818:698646] server relay: socket disconnected
2015-12-11 12:16:28.143 ThaliTest[818:698646] server relay: 0x163b55c0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:16:31.079 ThaliTest[818:700011] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:16:36.324 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:36.324 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:16:36.325 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
,2015-12-11 12:16:36.325 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone5-1_PT2684)
,2015-12-11 12:16:36.325 ThaliTest[818:698646] server session: disconnect
2015-12-11 12:16:36.326 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:36.327 ThaliTest[818:698646] server session: connect
,2015-12-11 12:16:36.327 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:36.335 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5-1_PT2684
,2015-12-11 12:16:38.817 ThaliTest[818:700015] server session: not connected Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:39.487 ThaliTest[818:700015] server session: connected
2015-12-11 12:16:39.487 ThaliTest[818:700015] server session: stateChange:1->2 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:39.490 ThaliTest[818:698646] server relay: socket disconnected
2015-12-11 12:16:39.491 ThaliTest[818:698646] server relay: 0x163b6ca0 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection refused} 
,2015-12-11 12:16:41.174 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:16:41.174 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:16:41.175 ThaliTest[818:698646] multipeer session: start timer: 0x164cfba0
2015-12-11 12:16:41.175 ThaliTest[818:698646] server: disconnecting to refresh session (Apple-Iphone6-1_PT2932)
2015-12-11 12:16:41.175 ThaliTest[818:698646] server session: disconnect
,2015-12-11 12:16:41.176 ThaliTest[818:698646] server session: stateChange:2->0 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:41.177 ThaliTest[818:698646] server session: connect
,2015-12-11 12:16:41.177 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:41.186 ThaliTest[818:698646] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:16:43.848 ThaliTest[818:700074] server session: connected
2015-12-11 12:16:43.848 ThaliTest[818:700074] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:43.892 ThaliTest[818:698646] server relay: socket disconnected
,2015-12-11 12:16:43.892 ThaliTest[818:698646] server relay: 0x163bd570 disconnected with error Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedFailureReason=Error in connect() function, NSLocalizedDescription=Connection re,fused} 
,teardown
,testFindPeers stopped
,2015-12-11 12:16:48.277 ThaliTest[818:699206] jxcore: stopBroadcasting
,2015-12-11 12:16:48.278 ThaliTest[818:699206] THEMultipeerSession stopping peer
,2015-12-11 12:16:48.279 ThaliTest[818:699206] multipeer session: stop timer
,2015-12-11 12:16:48.279 ThaliTest[818:699206] server session: disconnect
2015-12-11 12:16:48.280 ThaliTest[818:699206] server session: stateChange:2->0 Apple-Iphone5-1_PT2684
,2015-12-11 12:16:48.297 ThaliTest[818:699206] server session: disconnect
2015-12-11 12:16:48.298 ThaliTest[818:699206] server session: stateChange:2->0 Apple-Iphone6-1_PT2932
,2015-12-11 12:16:48.313 ThaliTest[818:699206] server session: disconnect
2015-12-11 12:16:48.313 ThaliTest[818:699206] server session: stateChange:2->0 Apple-Iphone5s-1_PT8695
,2015-12-11 12:16:48.315 ThaliTest[818:699206] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56045
,2015-12-11 12:16:48.719 ThaliTest[818:699206] jxcore: startBroadcasting
,2015-12-11 12:16:48.723 ThaliTest[818:699206] server: starting Apple-IpadAir2-1_PT2428.ucnEeA==
,2015-12-11 12:16:48.725 ThaliTest[818:699206] multipeer session: start timer: 0x14729120
,2015-12-11 12:16:48.734 ThaliTest[818:699206] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2428
,2015-12-11 12:16:48.737 ThaliTest[818:699206] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-11T11:16:48.746Z SendDataTCPServer.js: TCP/IP server is bound to port: 56045
,2015-12-11 12:16:49.413 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:49.414 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-,1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
2015-12-11 12:16:49.415 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT2932.,PHL+kA==
2015-12-11T11:16:49.417Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11T11:16:49.418Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11T11:16:49.419Z SendDataConnector.js: do connect now
,2015-12-11 12:16:49.421 ThaliTest[818:699206] jxcore: connect Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:49.421 ThaliTest[818:699206] client session: connect
2015-12-11 12:16:49.422 ThaliTest[818:699206] client session: stateChange:0->1 Apple-Iphone6-1_PT2932.PHL+kA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2684.BiXlYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.iCr2Pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 12:16:52.185 ThaliTest[818:700078] client session: connected
2015-12-11 12:16:52.185 ThaliTest[818:700078] client session: stateChange:1->2 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:52.217 ThaliTest[818:700074] client session: fireConnectCallback: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:16:52.217 ThaliTest[818:700074] jxcore: connect: success
,2015-12-11T11:16:52.219Z SendDataConnector.js: CLIENT connected to 56048, error: null
,2015-12-11T11:16:52.220Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:52.223 ThaliTest[818:698646] client: relay established
2015-12-11 12:16:52.223 ThaliTest[818:698646] client: new accepted socket: 0x164d9210
,2015-12-11T11:16:52.238Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:16:52.539Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T11:16:52.564Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T11:16:52.577Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T11:16:52.577Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T11:16:52.578Z SendDataConnector.js: CLIENT Stop now
2015-12-11T11:16:52.578Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:16:52.579 ThaliTest[818:699206] jxcore: disconnect
,2015-12-11 12:16:52.579 ThaliTest[818:699206] client session: disconnectFromPeer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:52.579 ThaliTest[818:699206] client session: disconnect
,2015-12-11 12:16:52.579 ThaliTest[818:699206] client session: stateChange:2->0 Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:16:52.582 ThaliTest[818:699206] jxcore: disconnect: success
,2015-12-11T11:16:52.582Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2932.PHL+kA==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:16:52.583Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:16:52.584Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11T11:16:52.584Z SendDataConnector.js: do connect now
,2015-12-11 12:16:52.585 ThaliTest[818:699206] jxcore: connect Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:16:52.585 ThaliTest[818:699206] client session: connect
2015-12-11 12:16:52.585 ThaliTest[818:699206] client session: stateChange:0->1 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:56.865 ThaliTest[818:700079] client session: connected
2015-12-11 12:16:56.866 ThaliTest[818:700079] client session: stateChange:1->2 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:56.909 ThaliTest[818:700079] client session: fireConnectCallback: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:16:56.910 ThaliTest[818:700079] jxcore: connect: success
,2015-12-11T11:16:56.911Z SendDataConnector.js: CLIENT connected to 56051, error: null
,2015-12-11T11:16:56.912Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:16:56.914 ThaliTest[818:698646] client: relay established
2015-12-11 12:16:56.914 ThaliTest[818:698646] client: new accepted socket: 0x164d28f0
,2015-12-11T11:16:56.927Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:16:57.228Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T11:16:57.241Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T11:16:57.265Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T11:16:57.265Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-11T11:16:57.265Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:16:57.265Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:16:57.266 ThaliTest[818:699206] jxcore: disconnect
,2015-12-11 12:16:57.266 ThaliTest[818:699206] client session: disconnectFromPeer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:57.266 ThaliTest[818:699206] client session: disconnect
,2015-12-11 12:16:57.266 ThaliTest[818:699206] client session: stateChange:2->0 Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:16:57.329 ThaliTest[818:699206] jxcore: disconnect: success
,2015-12-11T11:16:57.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2684.BiXlYA==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11T11:16:57.330Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:16:57.330Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11T11:16:57.330Z SendDataConnector.js: do connect now
,2015-12-11 12:16:57.331 ThaliTest[818:699206] jxcore: connect Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:16:57.331 ThaliTest[818:699206] client session: connect
,2015-12-11 12:16:57.331 ThaliTest[818:699206] client session: stateChange:0->1 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:00.139 ThaliTest[818:700011] client session: connected
2015-12-11 12:17:00.139 ThaliTest[818:700011] client session: stateChange:1->2 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:00.163 ThaliTest[818:700074] client session: fireConnectCallback: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:00.164 ThaliTest[818:700074] jxcore: connect: success
,2015-12-11T11:17:00.165Z SendDataConnector.js: CLIENT connected to 56054, error: null
,2015-12-11T11:17:00.165Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 12:17:00.169 ThaliTest[818:698646] client: relay established
,2015-12-11 12:17:00.169 ThaliTest[818:698646] client: new accepted socket: 0x164d74b0
,2015-12-11T11:17:00.181Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T11:17:00.454Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T11:17:00.478Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T11:17:00.490Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T11:17:00.502Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T11:17:00.502Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T11:17:00.503Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T11:17:00.503Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 12:17:00.503 ThaliTest[818:699206] jxcore: disconnect
,2015-12-11 12:17:00.504 ThaliTest[818:699206] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:00.504 ThaliTest[818:699206] client session: disconnect
,2015-12-11 12:17:00.504 ThaliTest[818:699206] client session: stateChange:2->0 Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:00.507 ThaliTest[818:699206] jxcore: disconnect: success
2015-12-11T11:17:00.507Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8695.iCr2Pw==
---- round done--------
startWithNextDevice
,2015-12-11 12:17:11.986 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:17:11.986 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:17:11.987 ThaliTest[818:698646] multipeer session: start timer: 0x14729120
2015-12-11 12:17:11.987 ThaliTest[818:698646] server session: connect
,2015-12-11 12:17:11.987 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:11.994 ThaliTest[818:698646] server: accepting invitation Apple-Iphone6-1_PT2932
,2015-12-11 12:17:15.095 ThaliTest[818:700167] server session: connected
2015-12-11 12:17:15.095 ThaliTest[818:700167] server session: stateChange:1->2 Apple-Iphone6-1_PT2932
,2015-12-11 12:17:15.120 ThaliTest[818:698646] server relay: connected (to port: 56045)
,2015-12-11T11:17:15.124Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:17:15.519Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-11T11:17:15.536Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-11T11:17:15.554Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:17:15.643 ThaliTest[818:700167] server session: not connected Apple-Iphone6-1_PT2932
,2015-12-11 12:17:41.988 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:17:42.017 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:17:42.018 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:17:42.018 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:17:58.153 ThaliTest[818:698646] multipeer session: reset timer
2015-12-11 12:17:58.153 ThaliTest[818:698646] multipeer session: stop timer
2015-12-11 12:17:58.154 ThaliTest[818:698646] multipeer session: start timer: 0x14729120
2015-12-11 12:17:58.154 ThaliTest[818:698646] server session: connect
2015-12-11 12:17:58.154 ThaliTest[818:698646] server session: stateChange:0->1 Apple-Iphone5s-1_PT8695
,2015-12-11 12:17:58.161 ThaliTest[818:698646] server: accepting invitation Apple-Iphone5s-1_PT8695
,2015-12-11 12:18:01.241 ThaliTest[818:700301] server session: connected
2015-12-11 12:18:01.242 ThaliTest[818:700301] server session: stateChange:1->2 Apple-Iphone5s-1_PT8695
,2015-12-11 12:18:01.274 ThaliTest[818:698646] server relay: connected (to port: 56045)
,2015-12-11T11:18:01.280Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T11:18:01.575Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-11T11:18:01.593Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-11T11:18:01.610Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-11T11:18:01.625Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T11:18:01.652Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 12:18:01.836 ThaliTest[818:700312] server session: not connected Apple-Iphone5s-1_PT8695
,2015-12-11 12:18:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:18:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:18:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:18:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:18:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:18:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:18:58.186 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:18:58.186 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:19:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:19:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:19:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:19:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:19:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:19:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:19:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:19:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,Connected to the server!
,2015-12-11 12:20:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:20:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:20:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:20:28.186 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:20:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:20:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:20:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:20:58.357 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:21:28.154 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:21:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:21:28.184 ThaliTest[818:698646] client: fou,nd peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:21:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:21:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:21:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:21:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:22:02.180 ThaliTest[818:698646] client: lost peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:22:02.180 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone6-1_PT2932.PHL+kA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-11 12:22:03.724 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-11 12:22:22.344 ThaliTest[818:698646] client: lost peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:22:22.344 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone5s-1_PT8695.iCr2Pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.iCr2Pw==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-11 12:22:23.265 ThaliTest[818:698646] client: lost peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:22:23.266 ThaliTest[818:698646] client session: onPeerLost: Apple-Iphone6-1_PT2932.PHL+kA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-11 12:22:24.640 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2932.PHL+kA==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-11 12:22:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:22:28.180 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:22:28.181 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:22:35.058 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8695.iCr2Pw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 12:22:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:22:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:22:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:22:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:23:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:23:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:23:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:23:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:23:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:23:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:23:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:23:58.186 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:24:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:24:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:24:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:24:28.187 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:24:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:24:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:24:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:24:58.186 ThaliTest[818:698646] client: fou,nd peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:25:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:25:28.186 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:25:28.186 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:25:28.187 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:25:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:25:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:25:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:25:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:26:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:26:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:26:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:26:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:26:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:26:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:26:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:26:58.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:27:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:27:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:27:58.180 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:27:58.180 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:27:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:28:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:28:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:28:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:28:28.185 ThaliTest[818:698646] client: foun,d peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:28:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:28:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:28:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:28:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:29:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:29:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:29:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:29:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:29:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:29:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:29:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:29:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:30:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:30:28.181 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:30:28.181 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:30:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:30:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:30:58.953 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:30:58.953 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:30:59.909 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:31:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:31:28.915 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:31:28.915 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:31:28.916 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:31:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:31:58.181 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:31:58.181 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:31:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:32:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:32:28.180 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:32:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:32:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:32:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:32:58.178 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:32:58.180 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:32:58.180 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:33:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:33:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:33:28.184 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:33:28.186 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-11T11:33:28.758Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 12:33:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:33:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:33:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:33:58.184 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:34:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:34:28.181 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:34:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:34:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:34:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:34:58.180 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:34:58.181 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:34:58.181 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:35:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:35:28.181 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:35:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:35:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:35:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:35:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:35:58.183 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:35:58.184 ThaliTest[818:698646] client: fou,nd peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:36:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:36:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:36:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:36:28.183 ThaliTest[818:698646] client: foun,d peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
,2015-12-11 12:36:58.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:36:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
2015-12-11 12:36:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==
2015-12-11 12:36:58.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
,2015-12-11 12:37:28.155 ThaliTest[818:698646] multipeer session: restart
,2015-12-11 12:37:28.182 ThaliTest[818:698646] client: found peer: Apple-Iphone5-1_PT2684.BiXlYA==
2015-12-11 12:37:28.183 ThaliTest[818:698646] client: found peer: Apple-Iphone6-1_PT2932.PHL+kA==
,2015-12-11 12:37:28.185 ThaliTest[818:698646] client: found peer: Apple-Iphone5s-1_PT8695.iCr2Pw==

```
