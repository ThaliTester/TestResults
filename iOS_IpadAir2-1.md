#### Test 55742142a5c2fdb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CEAC6EE9-252D-4A73-BDC2-2B4EED614C28/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CEAC6EE9-252D-4A73-BDC2-2B4EED614C28/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/89AAFC44-D072-40F9-B0C8-08DD60722FAD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53493"
,(lldb)     command script import "/tmp/CEAC6EE9-252D-4A73-BDC2-2B4EED614C28/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-12 13:14:21.430 ThaliTest[1855:3933191] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/79E67A7A-29DC-4198-9CE3-08EB916A353F/Library/Cookies/Cookies.binarycookies
,2016-01-12 13:14:21.659 ThaliTest[1855:3933191] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-12 13:14:21.660 ThaliTest[1855:3933191] Multi-tasking -> Device: YES, App: YES
,2016-01-12 13:14:21.666 ThaliTest[1855:3933191] Unlimited access to network resources
,2016-01-12 13:14:21.671 ThaliTest[1855:3933191] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 13:14:25.779 ThaliTest[1855:3933191] Resetting plugins due to page load.
,2016-01-12 13:14:27.036 ThaliTest[1855:3933191] Finished load of: file:///var/mobile/Containers/Bundle/Application/89AAFC44-D072-40F9-B0C8-08DD60722FAD/ThaliTest.app/www/index.html
,2016-01-12 13:14:27.175 ThaliTest[1855:3933191] JXcore Cordova plugin initializing
,2016-01-12 13:14:27.176 ThaliTest[1855:3933382] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-12 13:14:28.230 ThaliTest[1855:3933191] THREAD WARNING: ['JXcore'] took '61.029785' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-12 13:19:33.985 ThaliTest[1855:3933382] jxcore: startBroadcasting
,2016-01-12 13:19:33.991 ThaliTest[1855:3933382] server: starting Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:33.991 ThaliTest[1855:3933382] multipeer session: start timer: 0x195833a0
,2016-01-12 13:19:33.992 ThaliTest[1855:3933382] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-12 13:19:33.992 ThaliTest[1855:3933382] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-12 13:19:35.378 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5s-1.+FhoNw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.+FhoNw==, peerAv,ailable: true
weAreDoneNow
done, now sending data to server
,2016-01-12 13:19:35.864 ThaliTest[1855:3933191] client: found peer: Apple-Iphone6-1.vdOTuw==
,teardown
testFindPeers stopped
2016-01-12 13:19:36.053 ThaliTest[1855:3933382] jxcore: stopBroadcasting
,2016-01-12 13:19:36.053 ThaliTest[1855:3933382] THEMultipeerSession stopping peer
2016-01-12 13:19:36.053 ThaliTest[1855:3933382] multipeer session: stop timer
2016-01-12 13:19:36.054 ThaliTest[1855:3933382] jxcore: stopBroadcasting: success
StopBroadca,sting went ok
--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 50905
2016-01-12 13:19:36.064 ThaliTest[1855:3933382] jxcore: startBroadcasting
,2016-01-12 13:19:36.069 ThaliTest[1855:3933382] server: starting Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:19:36.069 ThaliTest[1855:3933382] multipeer session: start timer: 0x193fa540
2016-01-12 13:19:36.069 ThaliTest[1855:3933382] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-12 13:19:36.069 ThaliTest[1855:3933382] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2016-01-12T12:19:36.072Z SendDataTCPServer.js: TCP/IP server is bound to port: 50905
,2016-01-12 13:19:36.084 ThaliTest[1855:3933191] client: found peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:36.084 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:36.084 ThaliTest[1855:3933191] client: found peer: Apple-Iphone6-1.vdOTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:36.085Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:36.085Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:36.086Z SendDataConnector.js: do connect now
2016-01-12 13:19:36.086 ThaliTest[1855:3933382] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:36.086 ThaliTest[1855:3933382] client session: connect
2016-01-12 13:19:36.086 ThaliTest[1855:3933382] client session: stateChange:0->1 Apple-IpadAir2-1.hA+i5,Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailabl,e":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:36.201 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5-1.IBb4nw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:37.369 ThaliTest[1855:3933191] client: lost peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:37.369 ThaliTest[1855:3933191] client session: onPeerLost: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:37.369 ThaliTest[1855:3933191] client sess,ion: onLinkFailure: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:37.370 ThaliTest[1855:3933191] client session: disconnect
2016-01-12 13:19:37.370 ThaliTest[1855:3933191] client session: stateChange:1->0 Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:37.370 ThaliTest[1855:3933191] client session: fireConnectCallback: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:37.370 ThaliTest[1855:3933191] jxcore: connect: fail: Peer disconnected
2016-01-12T12:19:37.370Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-12T12:19:37.371Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-12T12:19:37.371Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-12 13:19:37.800 ThaliTest[1855:3933191] client: lost peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:37.800 ThaliTest[1855:3933191] client session: onPeerLost: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:37.800 ThaliTest[1855:3933191] client: los,t peer: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:37.800 ThaliTest[1855:3933191] client session: onPeerLost: Apple-Iphone5-1.IBb4nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-12 13:19:37.897 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5s-1.8kws4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.8kws4w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-,12 13:19:37.898 ThaliTest[1855:3933191] client: found peer: Apple-Iphone6-1.56+AEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.56+AEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:37.903 ThaliTest[1855:3933191] client: lost peer: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:37.904 ThaliTest[1855:3933191] client session: onPeerLost: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:37.904 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5-1.mOZnMg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.mOZnMg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12T12:19:42.377Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:42.377Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:47.380 ThaliTest[1855:3933382] jxcore: disconnect
2016-01-12 13:19:47.380 ThaliTest[1855:3933382] jxcore: disconnect: fail
,2016-01-12T12:19:47.381Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:47.381Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-0,1-12T12:19:47.381Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:47.381Z SendDataConnector.js: do connect now
,2016-01-12 13:19:47.381 ThaliTest[1855:3933382] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:47.381 ThaliTest[1855:3933382] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:47.381 ThaliTest[1855:3933382] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:47.382Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:47.382Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-12T12:19:47.382Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:52.389Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:52.390Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:19:57.394 ThaliTest[1855:3933382] jxcore: disconnect
2016-01-12 13:19:57.395 ThaliTest[1855:3933382] jxcore: disconnect: fail
2016-01-12T12:19:57.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:57.395Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:19:57.395Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:19:57,.395Z SendDataConnector.js: do connect now
2016-01-12 13:19:57.395 ThaliTest[1855:3933382] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:57.395 ThaliTest[1855:3933382] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:57.395 ThaliTest[1855:3933382] jxcore: conne,ct: fail: Peer unreachable
,2016-01-12T12:19:57.396Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:57.396Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-12T12:19:57.396Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:20:02.406Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:02.407Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:20:06.079 ThaliTest[1855:3933191] multipeer session: restart
,2016-01-12 13:20:06.092 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:06.093 ThaliTest[1855:3933191] client: found peer: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:06.093 ThaliTest[1855:3933191] client: found peer: Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:07.417 ThaliTest[1855:3933382] jxcore: disconnect
2016-01-12 13:20:07.417 ThaliTest[1855:3933382] jxcore: disconnect: fail
2016-01-12T12:20:07.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:07.418Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:20:07.418Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:07.418Z SendDataConnector.js: do connect now
,2016-01-12 13:20:07.418 ThaliTest[1855:3933382] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:20:07.418 ThaliTest[1855:3933382] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:07.418 ThaliTest[1855:3933382] jxcore: connect: fail: Peer unreachable
,2016-01-12T12:20:07.419Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:07.419Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-12T12:20:07.419Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:20:12.424Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.hA+i5Q==
,2016-01-12T12:20:12.424Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.hA+i5Q==
,2016-01-12 13:20:17.430 ThaliTest[1855:3933382] jxcore: disconnect
,2016-01-12 13:20:17.430 ThaliTest[1855:3933382] jxcore: disconnect: fail
,2016-01-12T12:20:17.430Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:17.431Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.hA+i5Q== with availability status: true
2016-01-12T12:20:17.431Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.hA+i5Q==
2016-01-12T12:20:17.431Z SendDataConnector.js: do connect now
,2016-01-12 13:20:17.431 ThaliTest[1855:3933382] jxcore: connect Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:17.431 ThaliTest[1855:3933382] client: connect: unreachable Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:20:17.431 ThaliTest[1855:3933382] jxcore: conne,ct: fail: Peer unreachable
2016-01-12T12:20:17.431Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:17.432Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-12T12:20:17.432Z SendDataConnector.js: CLIENT Stop now
,2016-01-12 13:20:17.433 ThaliTest[1855:3933382] jxcore: disconnect
2016-01-12 13:20:17.433 ThaliTest[1855:3933382] jxcore: disconnect: fail
2016-01-12T12:20:17.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.hA+i5Q==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:17.434Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.8kws4w==
2016-01-12T12:20:17.434Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.8kws4w==
,2016-01-12T12:20:17.434Z SendDataConnector.js: do connect now
,2016-01-12 13:20:17.434 ThaliTest[1855:3933382] jxcore: connect Apple-Iphone5s-1.8kws4w==
2016-01-12 13:20:17.434 ThaliTest[1855:3933382] client session: connect
2016-01-12 13:20:17.434 ThaliTest[1855:3933382] client session: stateChange:0->1 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:17.869 ThaliTest[1855:3933191] multipeer session: reset timer
2016-01-12 13:20:17.869 ThaliTest[1855:3933191] multipeer session: stop timer
2016-01-12 13:20:17.869 ThaliTest[1855:3933191] multipeer session: start timer: 0x193fa540
2016-,01-12 13:20:17.869 ThaliTest[1855:3933191] server session: connect
2016-01-12 13:20:17.869 ThaliTest[1855:3933191] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-12 13:20:17.873 ThaliTest[1855:3933191] server: accepting invitation Apple-Iphone5-1
,2016-01-12 13:20:21.416 ThaliTest[1855:3933191] multipeer session: reset timer
2016-01-12 13:20:21.416 ThaliTest[1855:3933191] multipeer session: stop timer
2016-01-12 13:20:21.416 ThaliTest[1855:3933191] multipeer session: start timer: 0x193fa540
2016-01-12 13:20:21.416 ThaliTest[1855:3933191] server session: connect
2016-01-12 13:20:21.416 ThaliTest[1855:3933191] server session: stateChange:0->1 Apple-Iphone5s-1
2016-01-12 13:20:21.418 ThaliTest[1855:3933191] server: accepting invitation Apple-Iphone5s-1
,2016-01-12 13:20:21.550 ThaliTest[1855:3934161] client session: connected
2016-01-12 13:20:21.550 ThaliTest[1855:3934161] client session: stateChange:1->2 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:21.615 ThaliTest[1855:3934157] client session: fireConnectCallback: Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:21.616 ThaliTest[1855:3934157] jxcore: connect: success
,2016-01-12T12:20:21.616Z SendDataConnector.js: CLIENT connected to 50912, error: null
2016-01-12T12:20:21.616Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:21.618 ThaliTest[1855:3933191] client: relay established
2016-01-12 13:20:21.618 ThaliTest[1855:3933191] client: new accepted socket: 0x1931f010
,2016-01-12T12:20:21.632Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12 13:20:21.872 ThaliTest[1855:3934157] server session: connected
2016-01-12 13:20:21.872 ThaliTest[1855:3934157] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-12 13:20:21.937 ThaliTest[1855:3933191] server relay: connected (to port: 50905)
,2016-01-12T12:20:22.083Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:22.210Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-12T12:20:22.270Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-12T12:20:22.329Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-12T12:20:22.342Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:22.342Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-12T12:20:22.342Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:22.342Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:22.343 ThaliTest[1855:3933382] jxcore: disconnect
,2016-01-12 13:20:22.343 ThaliTest[1855:3933382] client session: disconnectFromPeer: Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:22.344 ThaliTest[1855:3933382] client session: disconnect
,2016-01-12 13:20:22.344 ThaliTest[1855:3933382] client session: stateChange:2->0 Apple-Iphone5s-1.8kws4w==
,2016-01-12 13:20:22.405 ThaliTest[1855:3933382] jxcore: disconnect: success
,2016-01-12T12:20:22.405Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.8kws4w==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:22.406Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.56+AEA==
2016-01-12T12:20:22.406Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:22.406Z SendDataConnector.js: do connect now
,2016-01-12 13:20:22.406 ThaliTest[1855:3933382] jxcore: connect Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:22.407 ThaliTest[1855:3933382] client session: connect
,2016-01-12 13:20:22.407 ThaliTest[1855:3933382] client session: stateChange:0->1 Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:22.944Z SendDataTCPServer.js: TCP/IP server has received 2119 bytes of data
,2016-01-12T12:20:22.957Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-12T12:20:22.980Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-12T12:20:22.994Z SendDataTCPServer.js: TCP/IP server has received 60225 bytes of data
,2016-01-12T12:20:23.020Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-12T12:20:23.055Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:23.111 ThaliTest[1855:3933191] multipeer session: reset timer
2016-01-12 13:20:23.111 ThaliTest[1855:3933191] multipeer session: stop timer
2016-01-12 13:20:23.111 ThaliTest[1855:3933191] multipeer session: start timer: 0x193fa540
2016-01-12 13:20:23.111 ThaliTest[1855:3933191] server session: connect
2016-01-12 13:20:23.111 ThaliTest[1855:3933191] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-12 13:20:23.113 ThaliTest[1855:3933191] server: accepting invitation Apple-Iphone6-1
,2016-01-12 13:20:23.647 ThaliTest[1855:3934157] server session: not connected Apple-Iphone5-1
,2016-01-12 13:20:24.495 ThaliTest[1855:3934149] server session: connected
,2016-01-12 13:20:24.495 ThaliTest[1855:3934149] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-12 13:20:24.536 ThaliTest[1855:3933191] server relay: connected (to port: 50905)
,2016-01-12T12:20:24.540Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:24.994Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-12T12:20:25.007Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-12T12:20:25.020Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-12T12:20:25.033Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-12T12:20:25.046Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-12T12:20:25.081Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-12T12:20:25.094Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:25.141 ThaliTest[1855:3934149] server session: not connected Apple-Iphone5s-1
,2016-01-12 13:20:26.071 ThaliTest[1855:3934149] client session: connected
2016-01-12 13:20:26.071 ThaliTest[1855:3934149] client session: stateChange:1->2 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:26.121 ThaliTest[1855:3934149] client session: fireConnectCallback: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:26.121 ThaliTest[1855:3934149] jxcore: connect: success
2016-01-12T12:20:26.122Z SendDataConnector.js: CLIENT connected to 50917, error: null
2016-01-12T12:20:26.122Z SendDataConnector.js: CLIENT starting client 
2016-01-12 13:20:26.123 ThaliTest[1855:3933191] client: relay established
2016-01-12 13:20:26.123 ThaliTest[1855:3933191] client: new accepted socket: 0x195927f0
,2016-01-12T12:20:26.135Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:26.591Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-12T12:20:26.654Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-12 13:20:26.657 ThaliTest[1855:3934149] server session: connected
2016-01-12 13:20:26.657 ThaliTest[1855:3934149] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-12T12:20:26.667Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-12T12:20:26.667Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-12T12:20:26.667Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:26.667Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:26.668 ThaliTest[1855:3933382] jxcore: disconnect
,2016-01-12 13:20:26.668 ThaliTest[1855:3933382] client session: disconnectFromPeer: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:26.668 ThaliTest[1855:3933382] client session: disconnect
,2016-01-12 13:20:26.668 ThaliTest[1855:3933382] client session: stateChange:2->0 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:26.713 ThaliTest[1855:3933191] server relay: connected (to port: 50905)
,2016-01-12 13:20:26.727 ThaliTest[1855:3933382] jxcore: disconnect: success
,2016-01-12T12:20:26.727Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.56+AEA==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1.mOZnMg==
,2016-01-12T12:20:26.728Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:26.728Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.mOZnMg==
,2016-01-12T12:20:26.728Z SendDataConnector.js: do connect now
,2016-01-12 13:20:26.728 ThaliTest[1855:3933382] jxcore: connect Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:26.729 ThaliTest[1855:3933382] client session: connect
,2016-01-12 13:20:26.729 ThaliTest[1855:3933382] client session: stateChange:0->1 Apple-Iphone5-1.mOZnMg==
,2016-01-12T12:20:26.744Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:27.105Z SendDataTCPServer.js: TCP/IP server has received 1095 bytes of data
,2016-01-12T12:20:27.119Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-12T12:20:27.133Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-12T12:20:27.179Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-12T12:20:27.193Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:27.287 ThaliTest[1855:3934161] server session: not connected Apple-Iphone6-1
,2016-01-12 13:20:29.989 ThaliTest[1855:3934149] client session: connected
2016-01-12 13:20:29.989 ThaliTest[1855:3934149] client session: stateChange:1->2 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:30.020 ThaliTest[1855:3934161] client session: fireConnectCallback: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:30.021 ThaliTest[1855:3934161] jxcore: connect: success
2016-01-12T12:20:30.021Z SendDataConnector.js: CLIENT connected to 50921, error: null
2016-01-12T12:20:30.021Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:30.022 ThaliTest[1855:3933191] client: relay established
2016-01-12 13:20:30.022 ThaliTest[1855:3933191] client: new accepted socket: 0x1958b4e0
,2016-01-12T12:20:30.035Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:30.525Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-12T12:20:30.538Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-12T12:20:30.548Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-12T12:20:30.586Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:30.598Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-12T12:20:30.648Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:30.648Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-12T12:20:30.648Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:30.648Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-12 13:20:30.648 ThaliTest[1855:3933382] jxcore: disconnect
2016-01-12 13:20:30.648 ThaliTest[1855:3933382] client session: disconnectFromPeer: Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:30.649 ThaliTest[1855:3933382] client session: disconnect
2016-01-12 13:20:30.649 ThaliTest[1855:3933382] client session: stateChange:2->0 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:30.653 ThaliTest[1855:3933382] jxcore: disconnect: success
2016-01-12T12:20:30.653Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.mOZnMg==
---- round done--------
startWithNextDevice
weAreDoneNow, resultA,rray.length: 4
sendReportNow
done, now sending data to server
,2016-01-12T12:20:30.665Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:30.665Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-12 13:20:32.754 ThaliTest[1855:3933382] jxcore: stopBroadcasting
2016-01-12 13:20:32.754 ThaliTest[1855:3933382] THEMultipeerSession stopping peer
2016-01-12 13:20:32.755 ThaliTest[1855:3933382] multipeer session: stop timer
2016-01-12 13:20:32.755 ThaliTest[1855:3933382] server session: disconnect
2016-01-12 13:20:32.755 ThaliTest[1855:3933382] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-12 13:20:32.757 ThaliTest[1855:3933382] server session: disconnect
2016-01-12 13:20:32.757 ThaliTest[1855:3933382] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-12 13:20:32.762 ThaliTest[1855:3933382] server session: disconnect
2016-01-12 13:20:32.762 ThaliTest[1855:3933382] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-12 13:20:32.765 ThaliTest[1855:3933382] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-12T12:20:32.778Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-12T12:20:32.779Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-12T12:20:32.779Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-12T12:20:32.779Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
