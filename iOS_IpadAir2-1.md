#### Test 55613145e2b298d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CDC985D7-1284-41EE-99A8-0E01EAFBA146/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CDC985D7-1284-41EE-99A8-0E01EAFBA146/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC1F706A-3CF0-4F3A-B29D-4573ACF9DDC0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52468"
,(lldb)     command script import "/tmp/CDC985D7-1284-41EE-99A8-0E01EAFBA146/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 15:38:07.742 ThaliTest[1789:3791245] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15F6F2D2-5007-4100-A082-686BE73E351C/Library/Cookies/Cookies.binarycookies
,2016-01-11 15:38:07.972 ThaliTest[1789:3791245] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 15:38:07.972 ThaliTest[1789:3791245] Multi-tasking -> Device: YES, App: YES
,2016-01-11 15:38:07.978 ThaliTest[1789:3791245] Unlimited access to network resources
,2016-01-11 15:38:07.984 ThaliTest[1789:3791245] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 15:38:12.069 ThaliTest[1789:3791245] Resetting plugins due to page load.
,2016-01-11 15:38:13.341 ThaliTest[1789:3791245] Finished load of: file:///var/mobile/Containers/Bundle/Application/AC1F706A-3CF0-4F3A-B29D-4573ACF9DDC0/ThaliTest.app/www/index.html
,2016-01-11 15:38:13.474 ThaliTest[1789:3791245] JXcore Cordova plugin initializing
2016-01-11 15:38:13.475 ThaliTest[1789:3791410] JXcore instance initializing
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
,2016-01-11 15:38:14.510 ThaliTest[1789:3791245] THREAD WARNING: ['JXcore'] took '60.903076' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-11 15:43:43.399 ThaliTest[1789:3791410] jxcore: startBroadcasting
,2016-01-11 15:43:43.405 ThaliTest[1789:3791410] server: starting Apple-IpadAir2-1.aUvv7Q==
2016-01-11 15:43:43.405 ThaliTest[1789:3791410] multipeer session: start timer: 0x17b1c6d0
,2016-01-11 15:43:43.405 ThaliTest[1789:3791410] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-11 15:43:43.406 ThaliTest[1789:3791410] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-11 15:43:44.448 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:44.449 ThaliTest[1789:3791245] client: found peer: Apple-Iphone6-1.UVBQ1A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.oKqzPQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
2016-01-11 15:43:48.736 ThaliTest[1789:3791410] jxcore: stopBroadcasting
2016-01-11 15:43:48.737 ThaliTest[1789:3791410] THEMultipeerSession stopping peer
2016-01-11 15:43:48.737 ThaliTest[1789:3791410] multipeer session: stop timer
2016-01-11 15:43:48.737 ThaliTest[1789:3791410] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 50410
,2016-01-11 15:43:48.743 ThaliTest[1789:3791410] jxcore: startBroadcasting
,2016-01-11 15:43:48.745 ThaliTest[1789:3791410] server: starting Apple-IpadAir2-1.3/8jow==
2016-01-11 15:43:48.745 ThaliTest[1789:3791410] multipeer session: start timer: 0x17b18d30
2016-01-11 15:43:48.745 ThaliTest[1789:3791410] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-11 15:43:48.745 ThaliTest[1789:3791410] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-11T14:43:48.747Z SendDataTCPServer.js: TCP/IP server is bound to port: 50410
,2016-01-11 15:43:48.757 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:48.757 ThaliTest[1789:3791245] client: found peer: Apple-IpadAir2-1.aUvv7Q==
2016-01-11 15:43:48.757 ThaliTest[1789:3791245] client: found peer:, Apple-Iphone6-1.UVBQ1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:48.759Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11T14:43:48.759Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:48.760Z SendDataConnector.js: do connect now
2016-01-11 15:43:48.760 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:48.760 ThaliTest[1789:3791410] client session: connect
2016-01-11 15:43:48.760 ThaliTest[1789:3791410] client session: stateChange:0->1 Apple-Iphone5-1.oKqzPQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.aUvv7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.UVBQ1A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:48.793 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5s-1.IqfRAg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.IqfRAg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:50.101 ThaliTest[1789:3791245] client: lost peer: Apple-IpadAir2-1.aUvv7Q==
2016-01-11 15:43:50.101 ThaliTest[1789:3791245] client session: onPeerLost: Apple-IpadAir2-1.aUvv7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.aUvv7Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 15:43:51.329 ThaliTest[1789:3791245] client: lost peer: Apple-Iphone5s-1.IqfRAg==
2016-01-11 15:43:51.329 ThaliTest[1789:3791245] client session: onPeerLost: Apple-Iphone5s-1.IqfRAg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.IqfRAg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 15:43:51.725 ThaliTest[1789:3791245] client: lost peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:51.725 ThaliTest[1789:3791245] client session: onPeerLost: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:51.725 ThaliTest[1789:3791245] client session: onLinkFailure: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:51.725 ThaliTest[1789:3791245] client session: disconnect
2016-01-11 15:43:51.725 ThaliTest[1789:3791245] client session: stateChange:1->0 Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:51.727 Thali,Test[1789:3791245] client session: fireConnectCallback: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:51.727 ThaliTest[1789:3791245] jxcore: connect: fail: Peer disconnected
2016-01-11T14:43:51.727Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-11T14:43:51.728Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11T14:43:51.728Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-11 15:43:51.762 ThaliTest[1789:3791245] client: lost peer: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:51.762 ThaliTest[1789:3791245] client session: onPeerLost: Apple-Iphone6-1.UVBQ1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.UVBQ1A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 15:43:51.766 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5s-1./+n+RQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1./+n+RQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:51.778 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5-1.FPpLTg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.FPpLTg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:51.836 ThaliTest[1789:3791245] multipeer session: reset timer
2016-01-11 15:43:51.836 ThaliTest[1789:3791245] multipeer session: stop timer
2016-01-11 15:43:51.836 ThaliTest[1789:3791245] multipeer session: start timer: 0x17b18d30
2016-01-11 15:43:51.836 ThaliTest[1789:3791245] server session: connect
2016-01-11 15:43:51.836 ThaliTest[1789:3791245] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-11 15:43:51.838 ThaliTest[1789:3791245] server: accepting invitation Apple-Iphone6-1
,2016-01-11 15:43:52.323 ThaliTest[1789:3791245] client: found peer: Apple-Iphone6-1.wtwmkg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.wtwmkg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:54.988 ThaliTest[1789:3792263] server session: connected
2016-01-11 15:43:54.988 ThaliTest[1789:3792263] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 15:43:55.046 ThaliTest[1789:3791245] server relay: connected (to port: 50410)
,2016-01-11T14:43:55.052Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:43:55.513Z SendDataTCPServer.js: TCP/IP server has received 1095 bytes of data
,2016-01-11T14:43:55.525Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-11T14:43:55.571Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-11T14:43:55.583Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-11T14:43:55.656Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T14:43:55.692Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:43:55.747 ThaliTest[1789:3792219] server session: not connected Apple-Iphone6-1
,2016-01-11T14:43:56.727Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:56.728Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:01.735 ThaliTest[1789:3791410] jxcore: disconnect
,2016-01-11 15:44:01.735 ThaliTest[1789:3791410] jxcore: disconnect: fail
2016-01-11T14:44:01.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:01.736Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
,2016-01-11T14:44:01.736Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:01.736Z SendDataConnector.js: do connect now
,2016-01-11 15:44:01.736 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:01.736 ThaliTest[1789:3791410] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:01.736 ThaliTest[1789:3791410] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:01.736Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:01.737Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T14:44:01.737Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:06.745Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:06.745Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:11.755 ThaliTest[1789:3791410] jxcore: disconnect
2016-01-11 15:44:11.755 ThaliTest[1789:3791410] jxcore: disconnect: fail
2016-01-11T14:44:11.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:11.755Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:11.756Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:11.75,6Z SendDataConnector.js: do connect now
2016-01-11 15:44:11.756 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:11.756 ThaliTest[1789:3791410] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:11.756 ThaliTest[1789:3791410] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:11.756Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:11.756Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T14:44:11.756Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:16.760Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:16.760Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:21.764 ThaliTest[1789:3791410] jxcore: disconnect
2016-01-11 15:44:21.764 ThaliTest[1789:3791410] jxcore: disconnect: fail
,2016-01-11T14:44:21.764Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:21.764Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:21.764Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11T14:44:21.765Z SendDataConnector.js: do connect now
,2016-01-11 15:44:21.765 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:21.765 ThaliTest[1789:3791410] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:21.765 ThaliTest[1789:3791410] jxcore: connect,: fail: Peer unreachable
2016-01-11T14:44:21.765Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:21.765Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T14:44:21.765Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11 15:44:21.838 ThaliTest[1789:3791245] multipeer session: restart
,2016-01-11 15:44:21.847 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:21.847 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:21.848 ThaliTest[1789:3791245] client: found peer: Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:26.770Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:26.770Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:31.780 ThaliTest[1789:3791410] jxcore: disconnect
2016-01-11 15:44:31.780 ThaliTest[1789:3791410] jxcore: disconnect: fail
,2016-01-11T14:44:31.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11T14:44:31.781Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:31.781Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11T14:44:31.781Z SendDataConnector.js: do connect now
,2016-01-11 15:44:31.781 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:31.781 ThaliTest[1789:3791410] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:31.781 ThaliTest[1789:3791410] jxcore: connect: fail: Peer unreachable
,2016-01-11T14:44:31.782Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:31.782Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-11T14:44:31.782Z SendDataConnector.js: CLIENT Stop now
,2016-01-11 15:44:31.783 ThaliTest[1789:3791410] jxcore: disconnect
,2016-01-11 15:44:31.783 ThaliTest[1789:3791410] jxcore: disconnect: fail
,2016-01-11T14:44:31.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1./+n+RQ==
,2016-01-11T14:44:31.784Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1./+n+RQ==
2016-01-11T14:44:31.784Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1./+n+RQ==
,2016-01-11T14:44:31.784Z SendDataConnector.js: do connect now
,2016-01-11 15:44:31.784 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:31.784 ThaliTest[1789:3791410] client session: connect
2016-01-11 15:44:31.784 ThaliTest[1789:3791410] client session: stateChange:0->1 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:32.268 ThaliTest[1789:3791245] multipeer session: reset timer
2016-01-11 15:44:32.268 ThaliTest[1789:3791245] multipeer session: stop timer
2016-01-11 15:44:32.268 ThaliTest[1789:3791245] multipeer session: start timer: 0x17b18d30
2016-,01-11 15:44:32.268 ThaliTest[1789:3791245] server session: connect
2016-01-11 15:44:32.268 ThaliTest[1789:3791245] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-11 15:44:32.271 ThaliTest[1789:3791245] server: accepting invitation Apple-Iphone5s-1
,2016-01-11 15:44:32.291 ThaliTest[1789:3791245] multipeer session: reset timer
2016-01-11 15:44:32.292 ThaliTest[1789:3791245] multipeer session: stop timer
2016-01-11 15:44:32.292 ThaliTest[1789:3791245] multipeer session: start timer: 0x17b18d30
,2016-01-11 15:44:32.292 ThaliTest[1789:3791245] server session: connect
2016-01-11 15:44:32.292 ThaliTest[1789:3791245] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-11 15:44:32.295 ThaliTest[1789:3791245] server: accepting invitation Apple-Iphone5-1
,2016-01-11 15:44:36.920 ThaliTest[1789:3792363] client session: connected
2016-01-11 15:44:36.920 ThaliTest[1789:3792363] client session: stateChange:1->2 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:36.923 ThaliTest[1789:3792351] client session: fireConnectCallback: Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:44:36.923 ThaliTest[1789:3792351] jxcore: connect: success
2016-01-11T14:44:36.924Z SendDataConnector.js: CLIENT connected to 50416, error: null
2016-01-11T14:44:36.924Z SendDataConnector.js: CLIENT starting client 
2016-01-11 15:44:36.924 ThaliTest[1789:3791245] client: relay established
2016-01-11 15:44:36.925 ThaliTest[1789:3791245] client: new accepted socket: 0x17b0fc10
,2016-01-11T14:44:36.936Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 15:44:37.076 ThaliTest[1789:3792321] server session: connected
2016-01-11 15:44:37.076 ThaliTest[1789:3792321] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 15:44:37.079 ThaliTest[1789:3791245] server relay: connected (to port: 50410)
,2016-01-11T14:44:37.303Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:37.609Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-11T14:44:37.620Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
,2016-01-11T14:44:37.635Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-11T14:44:37.636Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:44:37.650Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-11T14:44:37.652Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T14:44:37.663Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-11T14:44:37.664Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:37.664Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T14:44:37.665Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:37.665Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:37.666 ThaliTest[1789:3791410] jxcore: disconnect
,2016-01-11 15:44:37.666 ThaliTest[1789:3791410] client session: disconnectFromPeer: Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:37.666 ThaliTest[1789:3791410] client session: disconnect
,2016-01-11 15:44:37.666 ThaliTest[1789:3791410] client session: stateChange:2->0 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:37.731 ThaliTest[1789:3791410] jxcore: disconnect: success
,2016-01-11T14:44:37.732Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1./+n+RQ==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:37.732Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:37.732Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:37.732Z SendDataConnector.js: do connect now
,2016-01-11 15:44:37.733 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:37.733 ThaliTest[1789:3791410] client session: connect
,2016-01-11 15:44:37.733 ThaliTest[1789:3791410] client session: stateChange:0->1 Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:37.749Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:37.782 ThaliTest[1789:3792348] server session: not connected Apple-Iphone5s-1
,2016-01-11 15:44:37.837 ThaliTest[1789:3792321] server session: connected
2016-01-11 15:44:37.837 ThaliTest[1789:3792321] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 15:44:37.840 ThaliTest[1789:3791245] server relay: connected (to port: 50410)
,2016-01-11T14:44:37.847Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:39.215Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-11T14:44:39.228Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-11T14:44:39.275Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-11T14:44:39.289Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
,2016-01-11T14:44:39.311Z SendDataTCPServer.js: TCP/IP server has received 36135 bytes of data
,2016-01-11T14:44:39.324Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-11T14:44:39.349Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2016-01-11T14:44:39.362Z SendDataTCPServer.js: TCP/IP server has received 93075 bytes of data
,2016-01-11T14:44:39.387Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2016-01-11T14:44:39.398Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-11T14:44:39.411Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:39.467 ThaliTest[1789:3792321] server session: not connected Apple-Iphone5-1
,2016-01-11 15:44:41.111 ThaliTest[1789:3792321] client session: connected
,2016-01-11 15:44:41.111 ThaliTest[1789:3792321] client session: stateChange:1->2 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:41.113 ThaliTest[1789:3792321] client session: fireConnectCallback: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:41.113 ThaliTest[1789:3792321] jxcore: connect: success
2016-01-11T14:44:41.114Z SendDataConnector.js: CLIENT connected to 50421, error: null
2016-01-11T14:44:41.114Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:41.115 ThaliTest[1789:3791245] client: relay established
2016-01-11 15:44:41.115 ThaliTest[1789:3791245] client: new accepted socket: 0x17d4a220
,2016-01-11T14:44:41.127Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:41.575Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-11T14:44:41.589Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-11T14:44:41.736Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:44:41.774Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:41.774Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-11T14:44:41.775Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:44:41.775Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:41.775 ThaliTest[1789:3791410] jxcore: disconnect
,2016-01-11 15:44:41.776 ThaliTest[1789:3791410] client session: disconnectFromPeer: Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:41.776 ThaliTest[1789:3791410] client session: disconnect
,2016-01-11 15:44:41.776 ThaliTest[1789:3791410] client session: stateChange:2->0 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:41.836 ThaliTest[1789:3791410] jxcore: disconnect: success
,2016-01-11T14:44:41.836Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.FPpLTg==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:41.837Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:41.837Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.wtwmkg==
2016-01-11T14:44:41.837Z SendDataConnector.js: do connect now
,2016-01-11 15:44:41.838 ThaliTest[1789:3791410] jxcore: connect Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:41.838 ThaliTest[1789:3791410] client session: connect
,2016-01-11 15:44:41.838 ThaliTest[1789:3791410] client session: stateChange:0->1 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:45.105 ThaliTest[1789:3792363] client session: connected
2016-01-11 15:44:45.105 ThaliTest[1789:3792363] client session: stateChange:1->2 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:45.113 ThaliTest[1789:3792360] client session: fireConnectCallback: Apple-Iphone6-1.wtwmkg==
2016-01-11 15:44:45.113 ThaliTest[1789:3792360] jxcore: connect: success
2016-01-11T14:44:45.113Z SendDataConnector.js: CLIENT connected to 50424, error: null
,2016-01-11T14:44:45.113Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:45.114 ThaliTest[1789:3791245] client: relay established
,2016-01-11 15:44:45.114 ThaliTest[1789:3791245] client: new accepted socket: 0x17d43870
,2016-01-11T14:44:45.127Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:45.565Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-11T14:44:45.577Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T14:44:45.600Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:44:45.636Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T14:44:45.637Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T14:44:45.637Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:45.637Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 15:44:45.637 ThaliTest[1789:3791410] jxcore: disconnect
,2016-01-11 15:44:45.638 ThaliTest[1789:3791410] client session: disconnectFromPeer: Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:45.638 ThaliTest[1789:3791410] client session: disconnect
,2016-01-11 15:44:45.638 ThaliTest[1789:3791410] client session: stateChange:2->0 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:45.702 ThaliTest[1789:3791410] jxcore: disconnect: success
,2016-01-11T14:44:45.702Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.wtwmkg==
,---- round done--------
,startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-11T14:44:45.713Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:45.713Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:45:02.293 ThaliTest[1789:3791245] multipeer session: restart
,2016-01-11 15:45:02.303 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:45:02.303 ThaliTest[1789:3791245] client: found peer: Apple-Iphone6-1.wtwmkg==
2016-01-11 15:45:02.303 ThaliTest[1789:3791245] client: found peer: Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:45:21.775 ThaliTest[1789:3791245] client: lost peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:45:21.775 ThaliTest[1789:3791245] client session: onPeerLost: Apple-Iphone5-1.FPpLTg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.FPpLTg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
2016-01-11 15:45:31.269 ThaliTest[1789:3791410] jxcore: stopBroadcasting
2016-01-11 15:45:31.269 ThaliTest[1789:3791410] THEMultipeerSession stopping peer
2016-01-11 15:45:31.269 ThaliTest[1789:3791410] multipeer session: stop timer
,2016-01-11 15:45:31.269 ThaliTest[1789:3791410] server session: disconnect
2016-01-11 15:45:31.269 ThaliTest[1789:3791410] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-11 15:45:31.271 ThaliTest[1789:3791410] server session: disconnect
2016-0,1-11 15:45:31.271 ThaliTest[1789:3791410] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-11 15:45:31.272 ThaliTest[1789:3791410] server session: disconnect
2016-01-11 15:45:31.273 ThaliTest[1789:3791410] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-11 15:45:31.278 ThaliTest[1789:3791410] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-11T14:45:31.292Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:31.293Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:31.293Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:31.293Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
