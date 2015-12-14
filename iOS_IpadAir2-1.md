#### Test 506502788f5bfb2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/591483B4-133B-4CBD-A35A-898EF07F1918/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/591483B4-133B-4CBD-A35A-898EF07F1918/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788f5bfb2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F84A0D24-40B1-47F4-8C41-F84149B0970F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55818"
,(lldb)     command script import "/tmp/591483B4-133B-4CBD-A35A-898EF07F1918/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 21:16:07.209 ThaliTest[1069:1171554] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/150CEDBE-3E71-4AE8-8E6F-B94A5E8E93BA/Library/Cookies/Cookies.binarycookies
,2015-12-14 21:16:07.585 ThaliTest[1069:1171554] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 21:16:07.586 ThaliTest[1069:1171554] Multi-tasking -> Device: YES, App: YES
,2015-12-14 21:16:07.595 ThaliTest[1069:1171554] Unlimited access to network resources
,2015-12-14 21:16:07.603 ThaliTest[1069:1171554] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 21:16:17.215 ThaliTest[1069:1171554] Resetting plugins due to page load.
,2015-12-14 21:16:20.614 ThaliTest[1069:1171554] Finished load of: file:///var/mobile/Containers/Bundle/Application/F84A0D24-40B1-47F4-8C41-F84149B0970F/ThaliTest.app/www/index.html
,2015-12-14 21:16:20.792 ThaliTest[1069:1171554] JXcore Cordova plugin initializing
,2015-12-14 21:16:20.793 ThaliTest[1069:1171815] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-14 21:16:21.770 ThaliTest[1069:1171554] THREAD WARNING: ['JXcore'] took '70.141113' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 21:21:35.607 ThaliTest[1069:1171815] jxcore: startBroadcasting
,2015-12-14 21:21:35.624 ThaliTest[1069:1171815] server: starting Apple-IpadAir2-1_PT1173.P6/fMg==
,2015-12-14 21:21:35.626 ThaliTest[1069:1171815] multipeer session: start timer: 0x18c240d0
2015-12-14 21:21:35.627 ThaliTest[1069:1171815] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1173
,2015-12-14 21:21:35.628 ThaliTest[1069:1171815] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 21:21:36.650 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4966.GaMN6Q==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-14 21:21:36.735 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.KnhjEg==
,teardown
,testFindPeers stopped
,2015-12-14 21:21:39.781 ThaliTest[1069:1171815] jxcore: stopBroadcasting
2015-12-14 21:21:39.782 ThaliTest[1069:1171815] THEMultipeerSession stopping peer
2015-12-14 21:21:39.782 ThaliTest[1069:1171815] multipeer session: stop timer
,2015-12-14 21:21:39.783 ThaliTest[1069:1171815] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57846
,2015-12-14 21:21:39.849 ThaliTest[1069:1171815] jxcore: startBroadcasting
,2015-12-14 21:21:39.853 ThaliTest[1069:1171815] server: starting Apple-IpadAir2-1_PT1173.b8TW0A==
,2015-12-14 21:21:39.854 ThaliTest[1069:1171815] multipeer session: start timer: 0x16fc0410
,2015-12-14 21:21:39.859 ThaliTest[1069:1171815] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1173
,2015-12-14 21:21:39.861 ThaliTest[1069:1171815] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-14T20:21:39.866Z SendDataTCPServer.js: TCP/IP server is bound to port: 57846
,2015-12-14 21:21:40.834 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:40.835 ThaliTest[1069:1171554] client: found peer: Apple-IpadAir2-1_PT1173.P6/fMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:40.840Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:40.842Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:40.842Z SendDataConnector.js: do connect now
,2015-12-14 21:21:40.843 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:40.844 ThaliTest[1069:1171815] client session: connect
,2015-12-14 21:21:40.845 ThaliTest[1069:1171815] client session: stateChange:0->1 Apple-Iphone6-1_PT4966.GaMN6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 21:21:41.004 ThaliTest[1069:1171554] client: lost peer: Apple-IpadAir2-1_PT1173.P6/fMg==
2015-12-14 21:21:41.005 ThaliTest[1069:1171554] client session: onPeerLost: Apple-IpadAir2-1_PT1173.P6/fMg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1173.P6/fMg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 21:21:41.510 ThaliTest[1069:1171554] client: lost peer: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:41.510 ThaliTest[1069:1171554] client session: onPeerLost: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:41.510 ThaliTest[1069:1171554], client session: onLinkFailure: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:41.511 ThaliTest[1069:1171554] client session: disconnect
2015-12-14 21:21:41.511 ThaliTest[1069:1171554] client session: stateChange:1->0 Apple-Iphone6-1_PT4966.GaMN6Q==
2,015-12-14 21:21:41.512 ThaliTest[1069:1171554] client session: fireConnectCallback: Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:41.512 ThaliTest[1069:1171554] jxcore: connect: fail: Peer disconnected
2015-12-14 21:21:41.512 ThaliTest[1069:1171554] c,lient: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:21:41.513 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:21:41.513 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14T20:21:41.516Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T20:21:41.516Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T20:21:41.517Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.GaMN6Q==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5395.sHfmmA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5632.ug/nGg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4966.0C8RjA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14T20:21:46.524Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:46.524Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:51.530 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:21:51.531 ThaliTest[1069:1171815] jxcore: disconnect: fail
,2015-12-14T20:21:51.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:51.533Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
,2015-12-14T20:21:51.533Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:21:51.534Z SendDataConnector.js: do connect now
,2015-12-14 21:21:51.535 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:21:51.535 ThaliTest[1069:1171815] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:21:51.536 ThaliTest[1069:1171815] jxcore: connect: fail: Peer unreachable
2015-12-14T20:21:51.537Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T20:21:51.538Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T20:21:51.538Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:21:56.549Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:21:56.550Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:01.562 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:22:01.562 ThaliTest[1069:1171815] jxcore: disconnect: fail
,2015-12-14T20:22:01.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:01.564Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
,2015-12-14T20:22:01.564Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:01.565Z SendDataConnector.js: do connect now
,2015-12-14 21:22:01.566 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:01.567 ThaliTest[1069:1171815] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:01.568 ThaliTest[1069:1171815] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:01.569Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T20:22:01.569Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T20:22:01.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:06.573Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14T20:22:06.574Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:09.861 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:22:09.890 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:09.890 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:09.891 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:11.582 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:22:11.583 ThaliTest[1069:1171815] jxcore: disconnect: fail
,2015-12-14T20:22:11.584Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:11.585Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
,2015-12-14T20:22:11.585Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:11.586Z SendDataConnector.js: do connect now
,2015-12-14 21:22:11.587 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:11.587 ThaliTest[1069:1171815] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:11.588 ThaliTest[1069:1171815] jxcore: connect: fail: Peer unreachable
,2015-12-14T20:22:11.588Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T20:22:11.589Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T20:22:11.589Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T20:22:16.601Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:16.602Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14 21:22:21.446 ThaliTest[1069:1171554] multipeer session: reset timer
2015-12-14 21:22:21.446 ThaliTest[1069:1171554] multipeer session: stop timer
2015-12-14 21:22:21.446 ThaliTest[1069:1171554] multipeer session: start timer: 0x16fc0410
,2015-12-14 21:22:21.447 ThaliTest[1069:1171554] server session: connect
2015-12-14 21:22:21.447 ThaliTest[1069:1171554] server session: stateChange:0->1 Apple-Iphone6-1_PT4966
,2015-12-14 21:22:21.454 ThaliTest[1069:1171554] server: accepting invitation Apple-Iphone6-1_PT4966
,2015-12-14 21:22:21.606 ThaliTest[1069:1171815] jxcore: disconnect
2015-12-14 21:22:21.606 ThaliTest[1069:1171815] jxcore: disconnect: fail
2015-12-14T20:22:21.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6,Q==
2015-12-14T20:22:21.607Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4966.GaMN6Q== with availability status: true
2015-12-14T20:22:21.607Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,2015-12-14T20:22:21.608Z SendDataConnector.js: do connect now
,2015-12-14 21:22:21.609 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:22:21.609 ThaliTest[1069:1171815] client: connect: unreachable Apple-Iphone6-1_PT4966.GaMN6Q==
2015-12-14 21:22:21.609 ThaliTest[1069:1171815] j,xcore: connect: fail: Peer unreachable
2015-12-14T20:22:21.610Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T20:22:21.610Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-14T20:22:21.612Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 21:22:21.613 ThaliTest[1069:1171815] jxcore: disconnect
2015-12-14 21:22:21.613 ThaliTest[1069:1171815] jxcore: disconnect: fail
2015-12-14T20:22:21.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.GaMN6Q==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:21.616Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:21.617Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14T20:22:21.617Z SendDataConnector.js: do connect now
,2015-12-14 21:22:21.618 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:21.618 ThaliTest[1069:1171815] client session: connect
2015-12-14 21:22:21.618 ThaliTest[1069:1171815] client session: stateChange:0->1 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:24.003 ThaliTest[1069:1172457] server session: connected
,2015-12-14 21:22:24.004 ThaliTest[1069:1172457] server session: stateChange:1->2 Apple-Iphone6-1_PT4966
,2015-12-14 21:22:24.454 ThaliTest[1069:1171554] server relay: connected (to port: 57846)
,2015-12-14T20:22:24.465Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:24.482Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-14T20:22:24.522Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T20:22:24.540Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:24.633 ThaliTest[1069:1172454] server session: not connected Apple-Iphone6-1_PT4966
,2015-12-14 21:22:26.099 ThaliTest[1069:1171554] multipeer session: reset timer
2015-12-14 21:22:26.099 ThaliTest[1069:1171554] multipeer session: stop timer
2015-12-14 21:22:26.100 ThaliTest[1069:1171554] multipeer session: start timer: 0x16fc0410
2015-12-14 21:22:26.100 ThaliTest[1069:1171554] server session: connect
,2015-12-14 21:22:26.100 ThaliTest[1069:1171554] server session: stateChange:0->1 Apple-Iphone5-1_PT5632
,2015-12-14 21:22:26.107 ThaliTest[1069:1171554] server: accepting invitation Apple-Iphone5-1_PT5632
,2015-12-14 21:22:28.171 ThaliTest[1069:1172506] client session: connected
,2015-12-14 21:22:28.171 ThaliTest[1069:1172506] client session: stateChange:1->2 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:28.190 ThaliTest[1069:1172506] client session: fireConnectCallback: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:28.190 ThaliTest[1069:1172506] jxcore: connect: success
,2015-12-14T20:22:28.191Z SendDataConnector.js: CLIENT connected to 57852, error: null
,2015-12-14T20:22:28.192Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:28.196 ThaliTest[1069:1171554] client: relay established
2015-12-14 21:22:28.197 ThaliTest[1069:1171554] client: new accepted socket: 0x18d6d390
,2015-12-14T20:22:28.213Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:28.715Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-14T20:22:28.741Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T20:22:28.778Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:28.778Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T20:22:28.779Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T20:22:28.779Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:28.780 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:22:28.780 ThaliTest[1069:1171815] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:28.781 ThaliTest[1069:1171815] client session: disconnect
,2015-12-14 21:22:28.781 ThaliTest[1069:1171815] client session: stateChange:2->0 Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:22:28.786 ThaliTest[1069:1171815] jxcore: disconnect: success
2015-12-14T20:22:28.786Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5395.sHfmmA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:28.787Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:28.787Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14T20:22:28.787Z SendDataConnector.js: do connect now
,2015-12-14 21:22:28.788 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:28.788 ThaliTest[1069:1171815] client session: connect
2015-12-14 21:22:28.788 ThaliTest[1069:1171815] client session: stateChange:0->1 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:29.232 ThaliTest[1069:1172506] server session: connected
2015-12-14 21:22:29.232 ThaliTest[1069:1172506] server session: stateChange:1->2 Apple-Iphone5-1_PT5632
,2015-12-14 21:22:29.299 ThaliTest[1069:1171554] server relay: connected (to port: 57846)
,2015-12-14T20:22:29.308Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:22:29.829Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-14T20:22:29.842Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T20:22:29.854Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-14T20:22:29.893Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:22:30.015 ThaliTest[1069:1172454] server session: not connected Apple-Iphone5-1_PT5632
,2015-12-14 21:22:32.120 ThaliTest[1069:1172454] client session: connected
2015-12-14 21:22:32.121 ThaliTest[1069:1172454] client session: stateChange:1->2 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:32.150 ThaliTest[1069:1172506] client session: fireConnectCallback: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:32.151 ThaliTest[1069:1172506] jxcore: connect: success
,2015-12-14T20:22:32.152Z SendDataConnector.js: CLIENT connected to 57856, error: null
,2015-12-14T20:22:32.153Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:32.155 ThaliTest[1069:1171554] client: relay established
2015-12-14 21:22:32.156 ThaliTest[1069:1171554] client: new accepted socket: 0x18d6cf80
,2015-12-14T20:22:32.169Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:32.455Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T20:22:32.504Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:32.504Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-14T20:22:32.504Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:32.504Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:32.505 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:22:32.505 ThaliTest[1069:1171815] client session: disconnectFromPeer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:22:32.505 ThaliTest[1069:1171815] client session: disconnect
,2015-12-14 21:22:32.505 ThaliTest[1069:1171815] client session: stateChange:2->0 Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:22:32.508 ThaliTest[1069:1171815] jxcore: disconnect: success
2015-12-14T20:22:32.509Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5632.ug/nGg==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:22:32.511Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:22:32.511Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14T20:22:32.511Z SendDataConnector.js: do connect now
,2015-12-14 21:22:32.511 ThaliTest[1069:1171815] jxcore: connect Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:32.511 ThaliTest[1069:1171815] client session: connect
,2015-12-14 21:22:32.512 ThaliTest[1069:1171815] client session: stateChange:0->1 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:35.525 ThaliTest[1069:1172453] client session: connected
2015-12-14 21:22:35.526 ThaliTest[1069:1172453] client session: stateChange:1->2 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:35.549 ThaliTest[1069:1172506] client session: fireConnectCallback: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:35.550 ThaliTest[1069:1172506] jxcore: connect: success
,2015-12-14T20:22:35.551Z SendDataConnector.js: CLIENT connected to 57859, error: null
2015-12-14T20:22:35.551Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 21:22:35.553 ThaliTest[1069:1171554] client: relay established
2015-12-14 21:22:35.554 ThaliTest[1069:1171554] client: new accepted socket: 0x18d717a0
,2015-12-14T20:22:35.567Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T20:22:36.098Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T20:22:36.109Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T20:22:36.109Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T20:22:36.110Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:36.110Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:36.110 ThaliTest[1069:1171815] jxcore: disconnect
,2015-12-14 21:22:36.111 ThaliTest[1069:1171815] client session: disconnectFromPeer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:36.111 ThaliTest[1069:1171815] client session: disconnect
,2015-12-14 21:22:36.111 ThaliTest[1069:1171815] client session: stateChange:2->0 Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:22:36.114 ThaliTest[1069:1171815] jxcore: disconnect: success
2015-12-14T20:22:36.114Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4966.0C8RjA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T20:22:36.117Z SendDataConnector.js: CLIENT Stop now
2015-12-14T20:22:36.117Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 21:22:56.101 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:22:56.132 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:22:56.132 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:22:56.133 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:23:11.276 ThaliTest[1069:1171554] multipeer session: reset timer
,2015-12-14 21:23:11.276 ThaliTest[1069:1171554] multipeer session: stop timer
2015-12-14 21:23:11.277 ThaliTest[1069:1171554] multipeer session: start timer: 0x16fc0410
,2015-12-14 21:23:11.277 ThaliTest[1069:1171554] server session: connect
,2015-12-14 21:23:11.278 ThaliTest[1069:1171554] server session: stateChange:0->1 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:11.284 ThaliTest[1069:1171554] server: accepting invitation Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:14.094 ThaliTest[1069:1172609] server session: connected
2015-12-14 21:23:14.094 ThaliTest[1069:1172609] server session: stateChange:1->2 Apple-Iphone5s-1_PT5395
,2015-12-14 21:23:14.118 ThaliTest[1069:1171554] server relay: connected (to port: 57846)
,2015-12-14T20:23:14.122Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T20:23:14.411Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-14T20:23:14.426Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-14T20:23:14.441Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-14T20:23:14.618Z SendDataTCPServer.js: TCP/IP server has received 56088 bytes of data
,2015-12-14T20:23:14.631Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 21:23:15.072 ThaliTest[1069:1172616] server session: not connected Apple-Iphone5s-1_PT5395
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 21:23:32.310 ThaliTest[1069:1171815] jxcore: startBroadcasting
,2015-12-14 21:23:32.311 ThaliTest[1069:1171815] jxcore: startBroadcasting: failure
,weAreDoneNow
,done, now sending data to server
,done, now sending data to server
,2015-12-14 21:23:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:24:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:24:11.679 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:24:11.679 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:24:11.680 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:24:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:24:41.517 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:24:41.518 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:24:41.518 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:25:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:25:11.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:25:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:25:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:25:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:25:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:25:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:25:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:26:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:26:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:26:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:26:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:26:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:26:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:26:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:26:41.305 ThaliTest[1069:1171554] client,: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:27:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:27:11.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:27:11.308 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:27:11.308 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:27:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:27:41.302 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:27:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:27:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:28:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:28:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:28:11.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:28:11.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,Connected to the server!
,2015-12-14 21:28:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:28:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:28:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:28:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:29:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:29:11.367 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:29:11.368 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:29:11.368 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:29:41.277 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:29:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:29:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:29:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:30:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:30:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:30:41.302 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:30:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:30:41.303 ThaliTest[1069:1171554] clien,t: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,Connected to the server!
,2015-12-14 21:31:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:31:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:31:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:31:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:31:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:31:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:31:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:31:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:32:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:32:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:32:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:32:11.306 ThaliTest[1069:1171554] clien,t: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:32:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:32:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:32:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:32:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:33:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:33:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:33:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:33:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:33:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:34:11.277 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:34:11.301 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:34:11.302 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:34:11.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:34:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:34:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:34:41.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:34:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:35:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:35:11.414 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:35:11.415 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:35:11.415 ThaliTest[1069:1171554] clien,t: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:35:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:35:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:35:41.308 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:35:41.308 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:36:11.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:36:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:36:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:36:11.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,Connected to the server!
,2015-12-14 21:36:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:36:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:36:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:36:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:37:11.277 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:37:11.302 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:37:11.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:37:11.303 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:37:41.278 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:37:41.304 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:37:41.305 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:37:41.306 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:38:11.266 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:38:11.291 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:38:11.292 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:38:11.292 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:38:41.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:38:41.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:38:41.290 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:38:41.292 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:11.262 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:39:11.287 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:39:11.288 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:11.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:39:41.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:39:41.288 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:39:41.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:39:41.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:40:11.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:40:11.290 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:40:11.291 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:40:11.292 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,timeout now
,2015-12-14 21:40:41.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:40:41.288 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:40:41.288 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:40:41.290 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:41:11.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:41:11.343 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:41:11.343 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:41:11.344 ThaliTest[1069:1171554] client,: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:41:41.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:41:41.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:41:41.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:41:41.290 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:42:11.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:42:11.291 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:42:11.291 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:42:11.291 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:30.418 ThaliTest[1069:1171554] client: lost peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:42:30.418 ThaliTest[1069:1171554] client session: onPeerLost: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:42:30.418 ThaliTest[1069:1171554] client: lost peer: Apple-Iphone5s-1_PT5395.sHfmmA==
2015-12-14 21:42:30.419 ThaliTest[1069:1171554] client session: onPeerLost: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:42:31.418 ThaliTest[1069:1171554] client: lost peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:42:31.418 ThaliTest[1069:1171554] client session: onPeerLost: Apple-Iphone5-1_PT5632.ug/nGg==
,2015-12-14 21:42:41.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:42:44.310 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
,2015-12-14 21:42:44.823 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:42:44.823 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==
,2015-12-14 21:43:11.263 ThaliTest[1069:1171554] multipeer session: restart
,2015-12-14 21:43:11.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5-1_PT5632.ug/nGg==
2015-12-14 21:43:11.289 ThaliTest[1069:1171554] client: found peer: Apple-Iphone6-1_PT4966.0C8RjA==
2015-12-14 21:43:11.290 ThaliTest[1069:1171554] client: found peer: Apple-Iphone5s-1_PT5395.sHfmmA==

```
