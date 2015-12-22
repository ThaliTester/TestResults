#### Test 543122982543be8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/61E8D10B-5BCD-413E-930B-4F801542E6A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/61E8D10B-5BCD-413E-930B-4F801542E6A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/33A1D010-BCC1-4B95-B5BF-ACAAA5653E11/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62008"
,(lldb)     command script import "/tmp/61E8D10B-5BCD-413E-930B-4F801542E6A8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-22 01:49:37.956 ThaliTest[728:814009] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/905EB6E7-C511-4709-984E-DE4B602E306E/Library/Cookies/Cookies.binarycookies
,2015-12-22 01:49:38.437 ThaliTest[728:814009] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-22 01:49:38.439 ThaliTest[728:814009] Multi-tasking -> Device: YES, App: YES
,2015-12-22 01:49:38.449 ThaliTest[728:814009] Unlimited access to network resources
,2015-12-22 01:49:38.464 ThaliTest[728:814009] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-22 01:49:47.468 ThaliTest[728:814009] Resetting plugins due to page load.
,2015-12-22 01:49:51.211 ThaliTest[728:814009] Finished load of: file:///var/mobile/Containers/Bundle/Application/33A1D010-BCC1-4B95-B5BF-ACAAA5653E11/ThaliTest.app/www/index.html
,2015-12-22 01:49:51.409 ThaliTest[728:814009] JXcore Cordova plugin initializing
,2015-12-22 01:49:51.411 ThaliTest[728:814237] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,found test : ./testSendData2.js
,2015-12-22 01:49:52.745 ThaliTest[728:814009] THREAD WARNING: ['JXcore'] took '99.121094' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-22 01:54:51.467 ThaliTest[728:814237] jxcore: startBroadcasting
,2015-12-22 01:54:51.489 ThaliTest[728:814237] server: starting Apple-Iphone5s-1_PT9511.0JfZWg==
,2015-12-22 01:54:51.490 ThaliTest[728:814237] multipeer session: start timer: 0x15a48d40
2015-12-22 01:54:51.492 ThaliTest[728:814237] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9511
2015-12-22 01:54:51.494 ThaliTest[728:814237] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-22 01:54:52.123 ThaliTest[728:814009] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT4682.4oKZxQ==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-22 01:54:52.162 ThaliTest[728:814009] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
,teardown
,testFindPeers stopped
,2015-12-22 01:54:52.436 ThaliTest[728:814237] jxcore: stopBroadcasting
2015-12-22 01:54:52.437 ThaliTest[728:814237] THEMultipeerSession stopping peer
2015-12-22 01:54:52.438 ThaliTest[728:814237] multipeer session: stop timer
2015-12-22 01:54:52.438 Th,aliTest[728:814237] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53630
,2015-12-22 01:54:52.522 ThaliTest[728:814237] jxcore: startBroadcasting
,2015-12-22 01:54:52.528 ThaliTest[728:814237] server: starting Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:54:52.529 ThaliTest[728:814237] multipeer session: start timer: 0x14610700
2015-12-22 01:54:52.529 ThaliTest[728:814237] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT9511
2015-12-22 01:54:52.529 ThaliTest[728:814237] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-22T00:54:52.532Z SendDataTCPServer.js: TCP/IP server is bound to port: 53630
,2015-12-22 01:54:53.011 ThaliTest[728:814009] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.013 ThaliTest[728:814009] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir,2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22T00:54:53.017Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_,PT8764.Y1JJAA==
2015-12-22T00:54:53.017Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22T00:54:53.018Z SendDataConnector.js: do connect now
,2015-12-22 01:54:53.019 ThaliTest[728:814237] jxcore: connect Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.022 ThaliTest[728:814237] client session: connect
2015-12-22 01:54:53.022 ThaliTest[728:814237] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT8764.Y1JJAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:53.782 ThaliTest[728:814009] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:54:53.783 ThaliTest[728:814009] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6,-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22 01:54:54.789 ThaliTest[728:814009] client: lost peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:54.789 ThaliTest[728:814009] client session: onPeerLost: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:54.790 ThaliTest[728:814009] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:54.790 ThaliTest[728:814009] client session: disconnect
2015-12-22 01:54:54.791 ThaliTest[728:814009] client session: stateChange:1->0 Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12,-22 01:54:54.792 ThaliTest[728:814009] client session: fireConnectCallback: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:54.792 ThaliTest[728:814009] jxcore: connect: fail: Peer disconnected
2015-12-22 01:54:54.793 ThaliTest[728:814009] client: lost, peer: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.793 ThaliTest[728:814009] client session: onPeerLost: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.793 ThaliTest[728:814009] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22,T00:54:54.795Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:54:54.800Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:54:54.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvai,labilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null),, Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22T00:54:59.814Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:54:59.816Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:04.825 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:55:04.825 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:55:04.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Y1JJAA==,
2015-12-22T00:55:04.827Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT8764.Y1JJAA== with availability status: true
2015-12-22T00:55:04.827Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:04.827Z SendDataConnector.js: do connect now
,2015-12-22 01:55:04.829 ThaliTest[728:814237] jxcore: connect Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:55:04.830 ThaliTest[728:814237] client: connect: unreachable Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:55:04.830 ThaliTest[728:814237] jxcor,e: connect: fail: Peer unreachable
2015-12-22T00:55:04.831Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:04.832Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:55:04.832Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:09.836Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:09.836Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:14.841 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:55:14.842 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:55:14.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Y1JJAA==,
2015-12-22T00:55:14.843Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT8764.Y1JJAA== with availability status: true
2015-12-22T00:55:14.843Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:14.844Z SendDataConnector.js: do connect now
2015-12-22 01:55:14.845 ThaliTest[728:814237] jxcore: connect Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:55:14.845 ThaliTest[728:814237] client: connect: unreachable Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:14.846 ThaliTest[728:814237] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:14.847Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-22T00:55:14.848Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:14.848Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:19.855Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:19.856Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:22.530 ThaliTest[728:814009] multipeer session: restart
,2015-12-22 01:55:22.590 ThaliTest[728:814009] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:22.590 ThaliTest[728:814009] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:22.594 ThaliTest[728:814009] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
,2015-12-22 01:55:24.862 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:55:24.862 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:55:24.863Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Y1JJAA==,
2015-12-22T00:55:24.863Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT8764.Y1JJAA== with availability status: true
2015-12-22T00:55:24.864Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
20,15-12-22T00:55:24.864Z SendDataConnector.js: do connect now
,2015-12-22 01:55:24.865 ThaliTest[728:814237] jxcore: connect Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:24.866 ThaliTest[728:814237] client: connect: unreachable Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:24.867 ThaliTest[728:814237] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:24.868Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:24.869Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:55:24.869Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:29.876Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:29.877Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:32.480 ThaliTest[728:814009] client: lost peer: Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:55:32.480 ThaliTest[728:814009] client session: onPeerLost: Apple-Iphone5-1_PT5195.x5+2Tg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22 01:55:32.803 ThaliTest[728:814009] client: lost peer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:55:32.803 ThaliTest[728:814009] client session: onPeerLost: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22 01:55:34.887 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:55:34.888 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:55:34.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Y1JJAA==,
2015-12-22T00:55:34.889Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT8764.Y1JJAA== with availability status: true
2015-12-22T00:55:34.889Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22T00:55:34.890Z SendDataConnector.js: do connect now
2015-12-22 01:55:34.891 ThaliTest[728:814237] jxcore: connect Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:34.892 ThaliTest[728:814237] client: connect: unreachable Apple-IpadAir2-1_PT8764.Y1JJAA==
,2015-12-22 01:55:34.892 ThaliTest[728:814237] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:34.893Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:34.894Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-22T00:55:34.896Z SendDataConnector.js: CLIENT Stop now
,2015-12-22 01:55:34.899 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:55:34.899 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:55:34.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Y1JJAA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:55:34.902Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:55:34.903Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:55:34.903Z SendDataConnector.js: do connect now
,2015-12-22 01:55:34.904 ThaliTest[728:814237] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:34.904 ThaliTest[728:814237] client session: connect
2015-12-22 01:55:34.905 ThaliTest[728:814237] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:55:35.643 ThaliTest[728:814009] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-22 01:55:36.282 ThaliTest[728:814009] client: found peer: Apple-Iphone5-1_PT5195.x5+2Tg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.x5+2Tg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:55:39.520 ThaliTest[728:814009] multipeer session: reset timer
2015-12-22 01:55:39.521 ThaliTest[728:814009] multipeer session: stop timer
2015-12-22 01:55:39.521 ThaliTest[728:814009] multipeer session: start timer: 0x14610700
2015-12-22 ,01:55:39.522 ThaliTest[728:814009] server session: connect
2015-12-22 01:55:39.522 ThaliTest[728:814009] server session: stateChange:0->1 Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:39.533 ThaliTest[728:814009] server: accepting invitation Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:39.857 ThaliTest[728:814009] multipeer session: reset timer
2015-12-22 01:55:39.857 ThaliTest[728:814009] multipeer session: stop timer
2015-12-22 01:55:39.857 ThaliTest[728:814009] multipeer session: start timer: 0x14610700
,2015-12-22 01:55:39.858 ThaliTest[728:814009] server session: connect
2015-12-22 01:55:39.860 ThaliTest[728:814009] server session: stateChange:0->1 Apple-Iphone5-1_PT5195
,2015-12-22 01:55:39.870 ThaliTest[728:814009] server: accepting invitation Apple-Iphone5-1_PT5195
,2015-12-22 01:55:42.504 ThaliTest[728:815004] server session: connected
2015-12-22 01:55:42.505 ThaliTest[728:815004] server session: stateChange:1->2 Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:42.524 ThaliTest[728:815608] server session: connected
2015-12-22 01:55:42.524 ThaliTest[728:815608] server session: stateChange:1->2 Apple-Iphone5-1_PT5195
,2015-12-22 01:55:42.538 ThaliTest[728:814009] server relay: connected (to port: 53630)
2015-12-22T00:55:42.539Z SendDataTCPServer.js: TCP/IP server connected
2015-12-22 01:55:42.545 ThaliTest[728:814009] server relay: connected (to port: 53630)
,2015-12-22T00:55:42.554Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-22T00:55:42.763Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-22T00:55:42.783Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-22T00:55:42.799Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-22T00:55:42.815Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-22T00:55:42.995Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22T00:55:43.056Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-12-22T00:55:43.076Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-22 01:55:43.086 ThaliTest[728:815608] server session: not connected Apple-IpadAir2-1_PT8764
,2015-12-22T00:55:43.092Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-22T00:55:43.107Z SendDataTCPServer.js: TCP/IP server has received 50288 bytes of data
,2015-12-22T00:55:43.125Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-22T00:55:43.140Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22 01:55:43.205 ThaliTest[728:815663] server session: not connected Apple-Iphone5-1_PT5195
,2015-12-22 01:56:07.901 ThaliTest[728:815525] client session: not connected Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:07.902 ThaliTest[728:815525] client session: onLinkFailure: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:07.902 ThaliTest[728,:815525] client session: disconnect
2015-12-22 01:56:07.902 ThaliTest[728:815525] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:07.903 ThaliTest[728:815525] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.u,K405g==
2015-12-22 01:56:07.903 ThaliTest[728:815525] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:07.905Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:56:07.905Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-22T00:56:07.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22 01:56:09.859 ThaliTest[728:814009] multipeer session: restart
,2015-12-22T00:56:12.915Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:12.916Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:17.922 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:56:17.923 ThaliTest[728:814237] jxcore: disconnect: fail
2015-12-22T00:56:17.923Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==,
2015-12-22T00:56:17.924Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4682.uK405g== with availability status: true
2015-12-22T00:56:17.924Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
2015-,12-22T00:56:17.924Z SendDataConnector.js: do connect now
,2015-12-22 01:56:17.925 ThaliTest[728:814237] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.926 ThaliTest[728:814237] client session: connect
,2015-12-22 01:56:17.927 ThaliTest[728:814237] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:17.940 ThaliTest[728:814009] client: lost peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.941 ThaliTest[728:814009] client session: onPeerLost: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.941 ThaliTest[728:814009] clien,t session: onLinkFailure: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.941 ThaliTest[728:814009] client session: disconnect
2015-12-22 01:56:17.941 ThaliTest[728:814009] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:17.996 ThaliTest[728:814009] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:17.997 ThaliTest[728:814009] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:17.998Z SendDataConnector.js: CLIEN,T connected to 0, error: Peer disconnected
2015-12-22T00:56:17.998Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:56:17.998Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-,Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":false}]
,2015-12-22T00:56:23.001Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:23.002Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:27.063 ThaliTest[728:814009] multipeer session: reset timer
2015-12-22 01:56:27.063 ThaliTest[728:814009] multipeer session: stop timer
2015-12-22 01:56:27.064 ThaliTest[728:814009] multipeer session: start timer: 0x14610700
2015-12-22 ,01:56:27.064 ThaliTest[728:814009] server session: connect
2015-12-22 01:56:27.064 ThaliTest[728:814009] server session: stateChange:0->1 Apple-Iphone6-1_PT4682
,2015-12-22 01:56:27.075 ThaliTest[728:814009] server: accepting invitation Apple-Iphone6-1_PT4682
,2015-12-22 01:56:28.011 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:56:28.012 ThaliTest[728:814237] jxcore: disconnect: fail
,2015-12-22T00:56:28.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:28.013Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4682.uK405g== with availability status: true
,2015-12-22T00:56:28.014Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:28.015Z SendDataConnector.js: do connect now
2015-12-22 01:56:28.016 ThaliTest[728:814237] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:28.017 ThaliTest[728:814237] client: connect: unreachable Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:28.017 ThaliTest[728:814237] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:56:28.018Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:56:28.018Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:56:28.019Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22 01:56:29.697 ThaliTest[728:815747] server session: connected
2015-12-22 01:56:29.697 ThaliTest[728:815747] server session: stateChange:1->2 Apple-Iphone6-1_PT4682
,2015-12-22 01:56:29.709 ThaliTest[728:814009] server relay: connected (to port: 53630)
2015-12-22T00:56:29.709Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-22T00:56:30.149Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-22T00:56:30.168Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-22T00:56:30.183Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-22T00:56:30.200Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-22T00:56:30.218Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-22T00:56:30.234Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22 01:56:30.268 ThaliTest[728:815525] server session: not connected Apple-Iphone6-1_PT4682
,timeout now
,weAreDoneNow, resultArray.length: 1
,sendReportNow
,done, now sending data to server
,2015-12-22T00:56:32.550Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:56:32.551Z SendDataConnector.js: Stop retry timer
,2015-12-22 01:56:32.552 ThaliTest[728:814237] jxcore: disconnect
2015-12-22 01:56:32.553 ThaliTest[728:814237] jxcore: disconnect: fail
,2015-12-22T00:56:32.553Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==
,teardown
,testSendData stopped
,2015-12-22 01:56:37.340 ThaliTest[728:814237] jxcore: stopBroadcasting
2015-12-22 01:56:37.341 ThaliTest[728:814237] THEMultipeerSession stopping peer
2015-12-22 01:56:37.341 ThaliTest[728:814237] multipeer session: stop timer
2015-12-22 01:56:37.342 Th,aliTest[728:814237] server session: disconnect
2015-12-22 01:56:37.342 ThaliTest[728:814237] server session: stateChange:2->0 Apple-Iphone5-1_PT5195
2015-12-22 01:56:37.349 ThaliTest[728:814237] server session: disconnect
2015-12-22 01:56:37.350 ThaliTe,st[728:814237] server session: stateChange:2->0 Apple-Iphone6-1_PT4682
2015-12-22 01:56:37.357 ThaliTest[728:814237] server session: disconnect
2015-12-22 01:56:37.357 ThaliTest[728:814237] server session: stateChange:2->0 Apple-IpadAir2-1_PT8764
,2015-12-22 01:56:37.368 ThaliTest[728:814237] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-22T00:56:37.399Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:37.402Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:37.405Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-22T00:56:37.405Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
