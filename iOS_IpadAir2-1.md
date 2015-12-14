#### Test 50650278e3ff7c2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/56DF1AE3-DF7E-4726-9EDA-1E8592F6F6C9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/56DF1AE3-DF7E-4726-9EDA-1E8592F6F6C9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8CCF86E8-ACE0-4425-BA8D-AA1E5E127336/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55103"
,(lldb)     command script import "/tmp/56DF1AE3-DF7E-4726-9EDA-1E8592F6F6C9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 14:37:01.323 ThaliTest[998:1125221] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4CF75D8F-4BCB-4ACD-AA7C-1ABF842E6B5B/Library/Cookies/Cookies.binarycookies
,2015-12-14 14:37:01.338 ThaliTest[998:1125221] <CATransformLayer: 0x15e7f530> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-14 14:37:01.339 ThaliTest[998:1125221] <CATransformLayer: 0x15d86770> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-14 14:37:01.339 ThaliTest[998:1125221] <CATransformLayer: 0x15d878c0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-14 14:37:01.637 ThaliTest[998:1125221] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 14:37:01.637 ThaliTest[998:1125221] Multi-tasking -> Device: YES, App: YES
,2015-12-14 14:37:01.644 ThaliTest[998:1125221] Unlimited access to network resources
,2015-12-14 14:37:01.650 ThaliTest[998:1125221] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 14:37:10.423 ThaliTest[998:1125221] Resetting plugins due to page load.
,2015-12-14 14:37:13.802 ThaliTest[998:1125221] Finished load of: file:///var/mobile/Containers/Bundle/Application/8CCF86E8-ACE0-4425-BA8D-AA1E5E127336/ThaliTest.app/www/index.html
,2015-12-14 14:37:13.933 ThaliTest[998:1125221] JXcore Cordova plugin initializing
,2015-12-14 14:37:13.934 ThaliTest[998:1125523] JXcore instance initializing
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
,2015-12-14 14:37:14.979 ThaliTest[998:1125221] THREAD WARNING: ['JXcore'] took '88.354004' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 14:44:00.287 ThaliTest[998:1125523] jxcore: startBroadcasting
,2015-12-14 14:44:00.304 ThaliTest[998:1125523] server: starting Apple-IpadAir2-1_PT6041.yRvsxw==
,2015-12-14 14:44:00.305 ThaliTest[998:1125523] multipeer session: start timer: 0x17d9ba50
,2015-12-14 14:44:00.306 ThaliTest[998:1125523] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6041
2015-12-14 14:44:00.306 ThaliTest[998:1125523] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 14:44:01.618 ThaliTest[998:1125221] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT3867.cSCWVA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-14 14:44:02.578 ThaliTest[998:1125221] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:03.272 ThaliTest[998:1125221] client: found peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
,teardown
,testFindPeers stopped
,2015-12-14 14:44:03.432 ThaliTest[998:1125523] jxcore: stopBroadcasting
2015-12-14 14:44:03.433 ThaliTest[998:1125523] THEMultipeerSession stopping peer
2015-12-14 14:44:03.433 ThaliTest[998:1125523] multipeer session: stop timer
2015-12-14 14:44:03.434, ThaliTest[998:1125523] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56885
,2015-12-14 14:44:03.489 ThaliTest[998:1125523] jxcore: startBroadcasting
,2015-12-14 14:44:03.491 ThaliTest[998:1125523] server: starting Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:03.492 ThaliTest[998:1125523] multipeer session: start timer: 0x15f58d40
2015-12-14 14:44:03.492 ThaliTest[998:1125523] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6041
2015-12-14 14:44:03.492 ThaliTest[998:1125523] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-14T13:44:03.495Z SendDataTCPServer.js: TCP/IP server is bound to port: 56885
,2015-12-14 14:44:03.505 ThaliTest[998:1125221] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:03.505 ThaliTest[998:1125221] client: found peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:03.505 ThaliTest[998:1125221] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:03.506 ThaliTest[998:1125221] client: found peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:03.509Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:03.510Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:03.510Z SendDataConnector.js: do connect now
,2015-12-14 14:44:03.511 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:03.511 ThaliTest[998:1125523] client session: connect
,2015-12-14 14:44:03.511 ThaliTest[998:1125523] client session: stateChange:0->1 Apple-Iphone6-1_PT4340.mBVNng==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.I4GUOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:04.730 ThaliTest[998:1125221] client: lost peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:04.731 ThaliTest[998:1125221] client session: onPeerLost: Apple-Iphone5-1_PT3867.cSCWVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-14 14:44:04.882 ThaliTest[998:1125221] client: lost peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:04.882 ThaliTest[998:1125221] client session: onPeerLost: Apple-IpadAir2-1_PT6041.yRvsxw==
,2015-12-14 14:44:04.884 ThaliTest[998:1125221] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.0mupng==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 14:44:04.931 ThaliTest[998:1125221] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.nJo87Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:05.715 ThaliTest[998:1125221] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.aZvv+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:10.989 ThaliTest[998:1125221] client: lost peer: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:10.990 ThaliTest[998:1125221] client session: onPeerLost: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:10.990 ThaliTest[998:1125221] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:10.990 ThaliTest[998:1125221] client session: disconnect
2015-12-14 14:44:10.991 ThaliTest[998:1125221] client session: stateChange:1->0 Apple-Iphone6-1_PT4340.mBVNng==
2015-1,2-14 14:44:10.991 ThaliTest[998:1125221] client session: fireConnectCallback: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:10.991 ThaliTest[998:1125221] jxcore: connect: fail: Peer disconnected
,2015-12-14T13:44:10.993Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-14T13:44:10.994Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T13:44:10.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 14:44:11.006 ThaliTest[998:1125221] client: lost peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
2015-12-14 14:44:11.006 ThaliTest[998:1125221] client session: onPeerLost: Apple-Iphone5s-1_PT4136.I4GUOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.I4GUOQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-14T13:44:15.998Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:15.999Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:21.005 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:21.006 ThaliTest[998:1125523] jxcore: disconnect: fail
,2015-12-14T13:44:21.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:21.008Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4340.mBVNng== with availability status: true
,2015-12-14T13:44:21.009Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:21.009Z SendDataConnector.js: do connect now
,2015-12-14 14:44:21.010 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:21.011 ThaliTest[998:1125523] client: connect: unreachable Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:21.011 ThaliTest[998:1125523] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:21.012Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:21.012Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T13:44:21.013Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:26.014Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:26.015Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:31.020 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:31.020 ThaliTest[998:1125523] jxcore: disconnect: fail
,2015-12-14T13:44:31.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:31.022Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4340.mBVNng== with availability status: true
,2015-12-14T13:44:31.022Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:31.023Z SendDataConnector.js: do connect now
,2015-12-14 14:44:31.024 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:31.025 ThaliTest[998:1125523] client: connect: unreachable Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:31.025 ThaliTest[998:1125523] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:31.026Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:31.027Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T13:44:31.028Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14 14:44:33.493 ThaliTest[998:1125221] multipeer session: restart
,2015-12-14 14:44:33.523 ThaliTest[998:1125221] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:33.523 ThaliTest[998:1125221] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:33.524 ThaliTest[998:1125221] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14T13:44:36.034Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:36.034Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:41.036 ThaliTest[998:1125523] jxcore: disconnect
2015-12-14 14:44:41.036 ThaliTest[998:1125523] jxcore: disconnect: fail
,2015-12-14T13:44:41.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:41.038Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4340.mBVNng== with availability status: true
,2015-12-14T13:44:41.038Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:41.039Z SendDataConnector.js: do connect now
,2015-12-14 14:44:41.040 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:41.040 ThaliTest[998:1125523] client: connect: unreachable Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:41.041 ThaliTest[998:1125523] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:41.042Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:41.042Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T13:44:41.043Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:46.054Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:46.055Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:46.189 ThaliTest[998:1125221] multipeer session: reset timer
2015-12-14 14:44:46.190 ThaliTest[998:1125221] multipeer session: stop timer
2015-12-14 14:44:46.190 ThaliTest[998:1125221] multipeer session: start timer: 0x15f58d40
2015-12-14 14:44:46.190 ThaliTest[998:1125221] server session: connect
2015-12-14 14:44:46.191 ThaliTest[998:1125221] server session: stateChange:0->1 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:46.197 ThaliTest[998:1125221] server: accepting invitation Apple-Iphone6-1_PT4340
,2015-12-14 14:44:48.880 ThaliTest[998:1125221] multipeer session: reset timer
2015-12-14 14:44:48.881 ThaliTest[998:1125221] multipeer session: stop timer
,2015-12-14 14:44:48.881 ThaliTest[998:1125221] multipeer session: start timer: 0x15f58d40
,2015-12-14 14:44:48.881 ThaliTest[998:1125221] server session: connect
,2015-12-14 14:44:48.882 ThaliTest[998:1125221] server session: stateChange:0->1 Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:48.888 ThaliTest[998:1125221] server: accepting invitation Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:48.944 ThaliTest[998:1126270] server session: connected
2015-12-14 14:44:48.944 ThaliTest[998:1126270] server session: stateChange:1->2 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:48.962 ThaliTest[998:1125221] server relay: connected (to port: 56885)
,2015-12-14T13:44:48.972Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:49.264Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-14T13:44:49.278Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:49.308 ThaliTest[998:1126310] server session: not connected Apple-Iphone6-1_PT4340
,2015-12-14 14:44:51.063 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:51.063 ThaliTest[998:1125523] jxcore: disconnect: fail
,2015-12-14T13:44:51.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:51.065Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4340.mBVNng== with availability status: true
,2015-12-14T13:44:51.066Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14T13:44:51.066Z SendDataConnector.js: do connect now
,2015-12-14 14:44:51.067 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:51.068 ThaliTest[998:1125523] client: connect: unreachable Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:51.068 ThaliTest[998:1125523] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:51.069Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:51.070Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-14T13:44:51.073Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 14:44:51.073 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:51.074 ThaliTest[998:1125523] jxcore: disconnect: fail
,2015-12-14T13:44:51.075Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.mBVNng==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:51.078Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:51.079Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14T13:44:51.080Z SendDataConnector.js: do connect now
,2015-12-14 14:44:51.081 ThaliTest[998:1125523] jxcore: connect Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:51.081 ThaliTest[998:1125523] client session: connect
,2015-12-14 14:44:51.082 ThaliTest[998:1125523] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:51.860 ThaliTest[998:1126292] server session: connected
2015-12-14 14:44:51.860 ThaliTest[998:1126292] server session: stateChange:1->2 Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:51.866 ThaliTest[998:1125221] server relay: connected (to port: 56885)
,2015-12-14T13:44:51.870Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:52.280Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-14T13:44:52.296Z SendDataTCPServer.js: TCP/IP server has received 50228 bytes of data
,2015-12-14T13:44:52.313Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-14T13:44:52.341Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-14T13:44:52.355Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:52.413 ThaliTest[998:1126269] server session: not connected Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:54.172 ThaliTest[998:1126292] client session: connected
2015-12-14 14:44:54.172 ThaliTest[998:1126292] client session: stateChange:1->2 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:54.184 ThaliTest[998:1126310] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:54.185 ThaliTest[998:1126310] jxcore: connect: success
,2015-12-14T13:44:54.187Z SendDataConnector.js: CLIENT connected to 56893, error: null
2015-12-14T13:44:54.188Z SendDataConnector.js: CLIENT starting client 
2015-12-14 14:44:54.192 ThaliTest[998:1125221] client: relay established
2015-12-14 14:44:54.192 ThaliTest[998:1125221] client: new accepted socket: 0x15e750d0
,2015-12-14T13:44:54.205Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:54.518Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T13:44:54.529Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T13:44:54.543Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:44:54.543Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:44:54.543Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:54.543Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:54.544 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:54.544 ThaliTest[998:1125523] client session: disconnectFromPeer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:54.544 ThaliTest[998:1125523] client session: disconnect
2015-12-14 14:44:54.545 ThaliTest[998:1125523] client session: stateChange:2->0 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:54.548 ThaliTest[998:1125523] jxcore: disconnect: success
2015-12-14T13:44:54.548Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.0mupng==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:54.548Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:44:54.548Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:54.549Z SendDataConnector.js: do connect now
2015-12-14 14:44:54.549 ThaliTest[998:1125523] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:54.550 ThaliTest[998:1125523] client session: connect
,2015-12-14 14:44:54.550 ThaliTest[998:1125523] client session: stateChange:0->1 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:57.422 ThaliTest[998:1126270] client session: connected
2015-12-14 14:44:57.423 ThaliTest[998:1126270] client session: stateChange:1->2 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:57.453 ThaliTest[998:1126270] client session: fireConnectCallback: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:57.454 ThaliTest[998:1126270] jxcore: connect: success
,2015-12-14T13:44:57.455Z SendDataConnector.js: CLIENT connected to 56896, error: null
,2015-12-14T13:44:57.456Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:57.459 ThaliTest[998:1125221] client: relay established
2015-12-14 14:44:57.460 ThaliTest[998:1125221] client: new accepted socket: 0x17db1a10
,2015-12-14T13:44:57.473Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:57.767Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T13:44:57.780Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-14T13:44:57.793Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:44:57.794Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-14T13:44:57.794Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:57.794Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:57.795 ThaliTest[998:1125523] jxcore: disconnect
,2015-12-14 14:44:57.795 ThaliTest[998:1125523] client session: disconnectFromPeer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:57.795 ThaliTest[998:1125523] client session: disconnect
,2015-12-14 14:44:57.795 ThaliTest[998:1125523] client session: stateChange:2->0 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:57.798 ThaliTest[998:1125523] jxcore: disconnect: success
2015-12-14T13:44:57.799Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:44:57.799Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:44:57.799Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:44:57.799Z SendDataConnector.js: do connect now
,2015-12-14 14:44:57.800 ThaliTest[998:1125523] jxcore: connect Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:44:57.800 ThaliTest[998:1125523] client session: connect
2015-12-14 14:44:57.800 ThaliTest[998:1125523] client session: stateChange:0->1 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:00.738 ThaliTest[998:1126330] client session: connected
2015-12-14 14:45:00.739 ThaliTest[998:1126330] client session: stateChange:1->2 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:00.791 ThaliTest[998:1126310] client session: fireConnectCallback: Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:00.791 ThaliTest[998:1126310] jxcore: connect: success
,2015-12-14T13:45:00.793Z SendDataConnector.js: CLIENT connected to 56899, error: null
2015-12-14T13:45:00.793Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:45:00.796 ThaliTest[998:1125221] client: relay established
2015-12-14 14:45:00.796 ThaliTest[998:1125221] client: new accepted socket: 0x17e84170
,2015-12-14T13:45:00.809Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:45:01.249Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T13:45:01.263Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T13:45:01.287Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-14T13:45:01.300Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:45:01.301Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:45:01.301Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:45:01.302Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:45:01.303 ThaliTest[998:1125523] jxcore: disconnect
2015-12-14 14:45:01.303 ThaliTest[998:1125523] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:45:01.303 ThaliTest[998:1125523] client session: disconnect
2015-12-14 14:45:01.304 ThaliTest[998:1125523] client session: stateChange:2->0 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:01.311 ThaliTest[998:1125523] jxcore: disconnect: success
2015-12-14T13:45:01.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4136.aZvv+w==
---- round done--------
,startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-14T13:45:01.316Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:45:01.316Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:45:18.883 ThaliTest[998:1125221] multipeer session: restart
,2015-12-14 14:45:18.912 ThaliTest[998:1125221] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:45:18.912 ThaliTest[998:1125221] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:18.912 ThaliTest[998:1125221] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:36.429 ThaliTest[998:1125221] multipeer session: reset timer
2015-12-14 14:45:36.429 ThaliTest[998:1125221] multipeer session: stop timer
,2015-12-14 14:45:36.429 ThaliTest[998:1125221] multipeer session: start timer: 0x15f58d40
,2015-12-14 14:45:36.430 ThaliTest[998:1125221] server session: connect
2015-12-14 14:45:36.430 ThaliTest[998:1125221] server session: stateChange:0->1 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:36.437 ThaliTest[998:1125221] server: accepting invitation Apple-Iphone5-1_PT3867
,2015-12-14 14:45:39.490 ThaliTest[998:1126427] server session: connected
2015-12-14 14:45:39.490 ThaliTest[998:1126427] server session: stateChange:1->2 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:39.625 ThaliTest[998:1125221] server relay: connected (to port: 56885)
,2015-12-14T13:45:39.637Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:45:40.481Z SendDataTCPServer.js: TCP/IP server has received 15188 bytes of data
,2015-12-14T13:45:40.500Z SendDataTCPServer.js: TCP/IP server has received 61036 bytes of data
,2015-12-14T13:45:40.516Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:45:40.611 ThaliTest[998:1126436] server session: not connected Apple-Iphone5-1_PT3867
,teardown
,testSendData stopped
,2015-12-14 14:45:44.932 ThaliTest[998:1125523] jxcore: stopBroadcasting
,2015-12-14 14:45:44.932 ThaliTest[998:1125523] THEMultipeerSession stopping peer
,2015-12-14 14:45:44.933 ThaliTest[998:1125523] multipeer session: stop timer
2015-12-14 14:45:44.934 ThaliTest[998:1125523] server session: disconnect
2015-12-14 14:45:44.934 ThaliTest[998:1125523] server session: stateChange:2->0 Apple-Iphone5s-1_PT4136
,2015-12-14 14:45:45.001 ThaliTest[998:1125523] server session: disconnect
2015-12-14 14:45:45.001 ThaliTest[998:1125523] server session: stateChange:2->0 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:45.006 ThaliTest[998:1125523] server session: disconnect
2015-12-14 14:45:45.006 ThaliTest[998:1125523] server session: stateChange:2->0 Apple-Iphone6-1_PT4340
,2015-12-14 14:45:45.011 ThaliTest[998:1125523] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T13:45:45.027Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:45.028Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:45.030Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:45.030Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
