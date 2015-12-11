#### Test 50650278f6345ef_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/207B3C1D-E73F-4216-AECA-97A028FA7898/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/207B3C1D-E73F-4216-AECA-97A028FA7898/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6BFDBEDF-59DF-4F2A-B16C-B5678C728711/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54160"
,(lldb)     command script import "/tmp/207B3C1D-E73F-4216-AECA-97A028FA7898/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 13:12:25.306 ThaliTest[836:707384] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/27DBB031-9552-4785-86A7-AAD0E2F293C2/Library/Cookies/Cookies.binarycookies
,2015-12-11 13:12:25.320 ThaliTest[836:707384] <CATransformLayer: 0x16e7a8e0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-11 13:12:25.323 ThaliTest[836:707384] <CATransformLayer: 0x16e7ae70> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-11 13:12:25.323 ThaliTest[836:707384] <CATransformLayer: 0x16e7c970> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-11 13:12:25.616 ThaliTest[836:707384] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 13:12:25.616 ThaliTest[836:707384] Multi-tasking -> Device: YES, App: YES
,2015-12-11 13:12:25.624 ThaliTest[836:707384] Unlimited access to network resources
,2015-12-11 13:12:25.630 ThaliTest[836:707384] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 13:12:34.305 ThaliTest[836:707384] Resetting plugins due to page load.
,2015-12-11 13:12:37.627 ThaliTest[836:707384] Finished load of: file:///var/mobile/Containers/Bundle/Application/6BFDBEDF-59DF-4F2A-B16C-B5678C728711/ThaliTest.app/www/index.html
,2015-12-11 13:12:37.766 ThaliTest[836:707384] JXcore Cordova plugin initializing
,2015-12-11 13:12:37.767 ThaliTest[836:707643] JXcore instance initializing
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
,2015-12-11 13:12:38.774 ThaliTest[836:707384] THREAD WARNING: ['JXcore'] took '82.302002' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 13:17:50.618 ThaliTest[836:707643] jxcore: startBroadcasting
,2015-12-11 13:17:50.635 ThaliTest[836:707643] server: starting Apple-IpadAir2-1_PT8639.QAAa6w==
,2015-12-11 13:17:50.635 ThaliTest[836:707643] multipeer session: start timer: 0x16f39010
2015-12-11 13:17:50.636 ThaliTest[836:707643] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8639
,2015-12-11 13:17:50.637 ThaliTest[836:707643] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11 13:17:51.725 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.5CC0vg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT7734.5CC0vg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-11 13:17:52.190 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.k/CT+g==
,teardown
,testFindPeers stopped
,2015-12-11 13:17:53.102 ThaliTest[836:707643] jxcore: stopBroadcasting
,2015-12-11 13:17:53.103 ThaliTest[836:707643] THEMultipeerSession stopping peer
,2015-12-11 13:17:53.103 ThaliTest[836:707643] multipeer session: stop timer
,2015-12-11 13:17:53.104 ThaliTest[836:707643] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56215
,2015-12-11 13:17:53.509 ThaliTest[836:707643] jxcore: startBroadcasting
,2015-12-11 13:17:53.512 ThaliTest[836:707643] server: starting Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:17:53.513 ThaliTest[836:707643] multipeer session: start timer: 0x16f35560
2015-12-11 13:17:53.513 ThaliTest[836:707643] THEMultipeerSession ini,tialized peer Apple-IpadAir2-1_PT8639
2015-12-11 13:17:53.514 ThaliTest[836:707643] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-11T12:17:53.520Z SendDataTCPServer.js: TCP/IP server is bound to port: 56215
,2015-12-11 13:17:54.236 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:54.237 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.k/CT+g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:17:54.241Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:17:54.242Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:17:54.242Z SendDataConnector.js: do connect now
,2015-12-11 13:17:54.243 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:54.244 ThaliTest[836:707643] client session: connect
,2015-12-11 13:17:54.245 ThaliTest[836:707643] client session: stateChange:0->1 Apple-Iphone6-1_PT7734.5CC0vg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.k/CT+g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 13:17:54.339 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1055.SsV7MA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:55.726 ThaliTest[836:707384] client: lost peer: Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:55.727 ThaliTest[836:707384] client session: onPeerLost: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:55.727 ThaliTest[836:707384] client session: onLinkFailure: Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:55.727 ThaliTest[836:707384] client session: disconnect
2015-12-11 13:17:55.727 ThaliTest[836:707384] client session: stateChange:1->0 Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:17:55.728 ThaliTest[836:707384] client session: fireConnectCallback: Apple-Iphone6-1_PT7734.5CC0vg==
2015-12-11 13:17:55.728 ThaliTest[836:707384] jxcore: connect: fail: Peer disconnected
2015-12-11 13:17:55.729 ThaliTest[836:707384] client,: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:17:55.732Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-11T12:17:55.732Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-11T12:17:55.733Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:55.831 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.Jd0UjA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:57.444 ThaliTest[836:707384] client: lost peer: Apple-Iphone5-1_PT6904.k/CT+g==
2015-12-11 13:17:57.444 ThaliTest[836:707384] client session: onPeerLost: Apple-Iphone5-1_PT6904.k/CT+g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6904.k/CT+g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-11T12:18:00.745Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:00.746Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:03.054 ThaliTest[836:707384] multipeer session: reset timer
2015-12-11 13:18:03.055 ThaliTest[836:707384] multipeer session: stop timer
2015-12-11 13:18:03.055 ThaliTest[836:707384] multipeer session: start timer: 0x16f35560
,2015-12-11 13:18:03.055 ThaliTest[836:707384] server session: connect
,2015-12-11 13:18:03.056 ThaliTest[836:707384] server session: stateChange:0->1 Apple-Iphone5-1_PT6904
,2015-12-11 13:18:03.062 ThaliTest[836:707384] server: accepting invitation Apple-Iphone5-1_PT6904
,2015-12-11 13:18:05.758 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:05.759 ThaliTest[836:707643] jxcore: disconnect: fail
,2015-12-11T12:18:05.760Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:05.761Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
,2015-12-11T12:18:05.761Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:05.762Z SendDataConnector.js: do connect now
,2015-12-11 13:18:05.763 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:05.763 ThaliTest[836:707643] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:05.764 ThaliTest[836:707643] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:05.765Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T12:18:05.765Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T12:18:05.766Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11 13:18:06.361 ThaliTest[836:708222] server session: connected
2015-12-11 13:18:06.362 ThaliTest[836:708222] server session: stateChange:1->2 Apple-Iphone5-1_PT6904
,2015-12-11 13:18:06.865 ThaliTest[836:707384] server relay: connected (to port: 56215)
,2015-12-11T12:18:06.872Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:07.443Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-11T12:18:07.458Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-11T12:18:07.475Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-11T12:18:07.515Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-11T12:18:07.532Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:07.849 ThaliTest[836:708222] server session: not connected Apple-Iphone5-1_PT6904
,2015-12-11T12:18:10.773Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:10.773Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:15.781 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:15.782 ThaliTest[836:707643] jxcore: disconnect: fail
,2015-12-11T12:18:15.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:15.783Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
,2015-12-11T12:18:15.784Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:15.785Z SendDataConnector.js: do connect now
,2015-12-11 13:18:15.785 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:15.786 ThaliTest[836:707643] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:15.787 ThaliTest[836:707643] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:15.788Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-11T12:18:15.788Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T12:18:15.789Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:20.790Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:20.790Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:25.795 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:25.795 ThaliTest[836:707643] jxcore: disconnect: fail
,2015-12-11T12:18:25.796Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:25.797Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
,2015-12-11T12:18:25.798Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:25.798Z SendDataConnector.js: do connect now
,2015-12-11 13:18:25.799 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:25.800 ThaliTest[836:707643] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:25.800 ThaliTest[836:707643] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:25.801Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T12:18:25.801Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-11T12:18:25.802Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-11T12:18:30.807Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:30.808Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:33.056 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:18:33.085 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:18:33.085 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:33.086 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:35.811 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:35.812 ThaliTest[836:707643] jxcore: disconnect: fail
,2015-12-11T12:18:35.813Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:35.813Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7734.5CC0vg== with availability status: true
,2015-12-11T12:18:35.814Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11T12:18:35.815Z SendDataConnector.js: do connect now
,2015-12-11 13:18:35.816 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:35.816 ThaliTest[836:707643] client: connect: unreachable Apple-Iphone6-1_PT7734.5CC0vg==
,2015-12-11 13:18:35.817 ThaliTest[836:707643] jxcore: connect: fail: Peer unreachable
,2015-12-11T12:18:35.817Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-11T12:18:35.819Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-11T12:18:35.821Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 13:18:35.821 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:35.822 ThaliTest[836:707643] jxcore: disconnect: fail
,2015-12-11T12:18:35.823Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.5CC0vg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:35.826Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:35.827Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:18:35.828Z SendDataConnector.js: do connect now
,2015-12-11 13:18:35.829 ThaliTest[836:707643] jxcore: connect Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:35.829 ThaliTest[836:707643] client session: connect
,2015-12-11 13:18:35.830 ThaliTest[836:707643] client session: stateChange:0->1 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:41.044 ThaliTest[836:707384] multipeer session: reset timer
2015-12-11 13:18:41.045 ThaliTest[836:707384] multipeer session: stop timer
,2015-12-11 13:18:41.045 ThaliTest[836:707384] multipeer session: start timer: 0x16f35560
2015-12-11 13:18:41.046 ThaliTest[836:707384] server session: connect
,2015-12-11 13:18:41.046 ThaliTest[836:707384] server session: stateChange:0->1 Apple-Iphone6-1_PT7734
,2015-12-11 13:18:41.053 ThaliTest[836:707384] server: accepting invitation Apple-Iphone6-1_PT7734
,2015-12-11 13:18:41.508 ThaliTest[836:708334] client session: connected
,2015-12-11 13:18:41.508 ThaliTest[836:708334] client session: stateChange:1->2 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:41.521 ThaliTest[836:708333] client session: fireConnectCallback: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:41.522 ThaliTest[836:708333] jxcore: connect: success
,2015-12-11T12:18:41.523Z SendDataConnector.js: CLIENT connected to 56221, error: null
,2015-12-11T12:18:41.523Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:41.525 ThaliTest[836:707384] client: relay established
,2015-12-11 13:18:41.526 ThaliTest[836:707384] client: new accepted socket: 0x16eb0b70
,2015-12-11T12:18:41.540Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:41.850Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:18:41.875Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T12:18:41.886Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:41.945Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:41.945Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:41.946Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:41.947Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:41.948 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:41.949 ThaliTest[836:707643] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:41.950 ThaliTest[836:707643] client session: disconnect
,2015-12-11 13:18:41.950 ThaliTest[836:707643] client session: stateChange:2->0 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:42.023 ThaliTest[836:707643] jxcore: disconnect: success
2015-12-11T12:18:42.024Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:42.025Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:42.026Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:18:42.027Z SendDataConnector.js: do connect now
,2015-12-11 13:18:42.028 ThaliTest[836:707643] jxcore: connect Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:42.029 ThaliTest[836:707643] client session: connect
,2015-12-11 13:18:42.030 ThaliTest[836:707643] client session: stateChange:0->1 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:43.474 ThaliTest[836:708326] server session: connected
,2015-12-11 13:18:43.475 ThaliTest[836:708326] server session: stateChange:1->2 Apple-Iphone6-1_PT7734
,2015-12-11 13:18:43.494 ThaliTest[836:707384] server relay: connected (to port: 56215)
,2015-12-11T12:18:43.501Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:43.783Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-11T12:18:43.798Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-11T12:18:43.815Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-11T12:18:43.855Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-11T12:18:43.872Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:43.925 ThaliTest[836:708326] server session: not connected Apple-Iphone6-1_PT7734
,2015-12-11 13:18:44.065 ThaliTest[836:707384] multipeer session: reset timer
2015-12-11 13:18:44.065 ThaliTest[836:707384] multipeer session: stop timer
,2015-12-11 13:18:44.066 ThaliTest[836:707384] multipeer session: start timer: 0x16f35560
,2015-12-11 13:18:44.066 ThaliTest[836:707384] server session: connect
,2015-12-11 13:18:44.067 ThaliTest[836:707384] server session: stateChange:0->1 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:44.073 ThaliTest[836:707384] server: accepting invitation Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:44.494 ThaliTest[836:708326] client session: connected
2015-12-11 13:18:44.494 ThaliTest[836:708326] client session: stateChange:1->2 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:44.503 ThaliTest[836:708326] client session: fireConnectCallback: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:44.503 ThaliTest[836:708326] jxcore: connect: success
,2015-12-11T12:18:44.504Z SendDataConnector.js: CLIENT connected to 56225, error: null
,2015-12-11T12:18:44.505Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:44.506 ThaliTest[836:707384] client: relay established
2015-12-11 13:18:44.506 ThaliTest[836:707384] client: new accepted socket: 0x18cf8b80
,2015-12-11T12:18:44.520Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:44.751Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T12:18:44.762Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-11T12:18:44.775Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T12:18:44.788Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T12:18:44.799Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-11T12:18:44.799Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:44.799Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:44.799Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:44.800 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:44.800 ThaliTest[836:707643] client session: disconnectFromPeer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:44.800 ThaliTest[836:707643] client session: disconnect
2015-12-11 13:18:44.800 ThaliTest[836:707643] client session: stateChange:2->0 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:44.803 ThaliTest[836:707643] jxcore: disconnect: success
2015-12-11T12:18:44.803Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.oRkpZA==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:44.804Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11T12:18:44.804Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11T12:18:44.806Z SendDataConnector.js: do connect now
2015-12-11 13:18:44.806 ThaliTest[836:707643] jxcore: connect Apple-Iphone5-1_PT6904.J,d0UjA==
2015-12-11 13:18:44.806 ThaliTest[836:707643] client session: connect
2015-12-11 13:18:44.806 ThaliTest[836:707643] client session: stateChange:0->1 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:46.584 ThaliTest[836:708331] server session: connected
2015-12-11 13:18:46.584 ThaliTest[836:708331] server session: stateChange:1->2 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:46.607 ThaliTest[836:707384] server relay: connected (to port: 56215)
,2015-12-11T12:18:46.610Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:47.052Z SendDataTCPServer.js: TCP/IP server has received 8618 bytes of data
,2015-12-11T12:18:47.068Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-11T12:18:47.082Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:47.119 ThaliTest[836:708371] server session: not connected Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:47.517 ThaliTest[836:708371] client session: connected
2015-12-11 13:18:47.518 ThaliTest[836:708371] client session: stateChange:1->2 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:47.532 ThaliTest[836:708333] client session: fireConnectCallback: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:18:47.532 ThaliTest[836:708333] jxcore: connect: success
,2015-12-11T12:18:47.535Z SendDataConnector.js: CLIENT connected to 56229, error: null
,2015-12-11T12:18:47.536Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:47.538 ThaliTest[836:707384] client: relay established
2015-12-11 13:18:47.538 ThaliTest[836:707384] client: new accepted socket: 0x18c59960
,2015-12-11T12:18:47.552Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:47.801Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-11T12:18:47.812Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:18:47.823Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:47.836Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T12:18:47.849Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-11T12:18:47.862Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:18:47.863Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-11T12:18:47.863Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:47.863Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:47.864 ThaliTest[836:707643] jxcore: disconnect
,2015-12-11 13:18:47.864 ThaliTest[836:707643] client session: disconnectFromPeer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:47.864 ThaliTest[836:707643] client session: disconnect
,2015-12-11 13:18:47.865 ThaliTest[836:707643] client session: stateChange:2->0 Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:18:47.868 ThaliTest[836:707643] jxcore: disconnect: success
,2015-12-11T12:18:47.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6904.Jd0UjA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-11T12:18:47.874Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:47.874Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:19:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:19:14.097 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:19:14.097 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:19:14.098 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:19:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:19:44.096 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:19:44.130 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:19:44.130 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:20:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:20:14.097 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:20:14.154 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:20:14.154 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:20:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:20:44.096 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:20:44.096 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:20:44.096 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:21:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:21:14.096 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:21:14.097 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:21:14.097 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:21:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:21:44.097 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:21:44.097 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:21:44.098 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:22:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:22:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:22:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:22:14.096 ThaliTest[836:707384] client: fou,nd peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:22:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:22:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:22:44.124 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:22:44.124 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:23:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:23:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:23:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:23:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:23:44.100 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:23:44.101 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:23:44.101 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:24:14.068 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:24:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:24:44.092 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:24:44.547 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:24:44.547 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:25:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:25:14.092 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:25:14.364 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:25:14.365 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:25:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:25:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:25:44.320 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:25:44.321 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:26:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:26:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:26:14.114 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:26:14.114 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:26:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:26:44.094 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:26:44.095 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:26:44.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:27:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:27:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:27:44.092 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:27:44.278 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:27:44.278 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:28:14.068 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:28:14.092 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:28:14.221 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:28:14.221 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:28:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:28:44.094 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:28:44.094 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:28:44.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:29:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:29:14.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:29:14.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:29:14.093 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:29:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:29:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:29:44.376 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:29:44.377 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:30:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:30:14.094 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:30:14.185 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:30:14.187 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:30:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:30:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:30:44.132 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:30:44.132 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:31:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:31:14.091 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:31:14.533 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:31:14.534 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:31:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:31:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:31:44.345 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:31:44.346 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:32:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:32:14.092 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:32:14.288 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:32:14.288 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:32:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:32:44.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:32:44.113 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:32:44.115 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:33:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:33:14.093 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:33:14.094 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:33:14.095 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:33:44.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:33:44.090 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:33:44.448 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:33:44.448 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:34:14.067 ThaliTest[836:707384] multipeer session: restart
,2015-12-11 13:34:14.093 ThaliTest[836:707384] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:34:14.260 ThaliTest[836:707384] client: found peer: Apple-Iphone5-1_PT6904.Jd0UjA==
2015-12-11 13:34:14.261 ThaliTest[836:707384] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,teardown
,testSendData stopped
,2015-12-11 13:34:34.572 ThaliTest[836:707643] jxcore: stopBroadcasting
,2015-12-11 13:34:34.573 ThaliTest[836:707643] THEMultipeerSession stopping peer
,2015-12-11 13:34:34.573 ThaliTest[836:707643] multipeer session: stop timer
,2015-12-11 13:34:34.575 ThaliTest[836:707643] server session: disconnect
2015-12-11 13:34:34.575 ThaliTest[836:707643] server session: stateChange:2->0 Apple-Iphone5-1_PT6904
,2015-12-11 13:34:34.583 ThaliTest[836:707643] server session: disconnect
,2015-12-11 13:34:34.585 ThaliTest[836:707643] server session: stateChange:2->0 Apple-Iphone6-1_PT7734
,2015-12-11 13:34:34.651 ThaliTest[836:707643] server session: disconnect
,2015-12-11 13:34:34.652 ThaliTest[836:707643] server session: stateChange:2->0 Apple-Iphone5s-1_PT1055
,2015-12-11 13:34:34.714 ThaliTest[836:707643] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-11T12:34:34.730Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:34.732Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:34.733Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:34.734Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
