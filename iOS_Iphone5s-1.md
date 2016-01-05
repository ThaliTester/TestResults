#### Test 550731521dbc378_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/14729896-64DE-4FC0-B370-4696D2682385/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/14729896-64DE-4FC0-B370-4696D2682385/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2FC86004-D806-4276-8C35-79E32F66685D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64911"
,(lldb)     command script import "/tmp/14729896-64DE-4FC0-B370-4696D2682385/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 11:17:23.286 ThaliTest[1284:2753294] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5F7DF85F-9CFA-4199-8345-9652BEE8DD49/Library/Cookies/Cookies.binarycookies
,2016-01-05 11:17:23.769 ThaliTest[1284:2753294] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 11:17:23.771 ThaliTest[1284:2753294] Multi-tasking -> Device: YES, App: YES
,2016-01-05 11:17:23.780 ThaliTest[1284:2753294] Unlimited access to network resources
,2016-01-05 11:17:23.793 ThaliTest[1284:2753294] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 11:17:32.743 ThaliTest[1284:2753294] Resetting plugins due to page load.
,2016-01-05 11:17:36.181 ThaliTest[1284:2753294] Finished load of: file:///var/mobile/Containers/Bundle/Application/2FC86004-D806-4276-8C35-79E32F66685D/ThaliTest.app/www/index.html
,2016-01-05 11:17:36.385 ThaliTest[1284:2753294] JXcore Cordova plugin initializing
,2016-01-05 11:17:36.386 ThaliTest[1284:2753490] JXcore instance initializing
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
,2016-01-05 11:17:37.703 ThaliTest[1284:2753294] THREAD WARNING: ['JXcore'] took '82.977783' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 11:23:09.690 ThaliTest[1284:2753490] jxcore: startBroadcasting
,2016-01-05 11:23:09.709 ThaliTest[1284:2753490] server: starting Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:09.710 ThaliTest[1284:2753490] multipeer session: start timer: 0x14611e50
2016-01-05 11:23:09.711 ThaliTest[1284:2753490] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-05 11:23:09.711 ThaliTest[1284:2753490] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 11:23:10.990 ThaliTest[1284:2753294] client: found peer: Apple-Iphone5-1.+hwmKw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.+hwmKw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-05 11:23:11.702 ThaliTest[1284:2753294] client: found peer: Apple-IpadAir2-1.o3kBVg==
,teardown
,testFindPeers stopped
,2016-01-05 11:23:13.117 ThaliTest[1284:2753490] jxcore: stopBroadcasting
2016-01-05 11:23:13.118 ThaliTest[1284:2753490] THEMultipeerSession stopping peer
2016-01-05 11:23:13.118 ThaliTest[1284:2753490] multipeer session: stop timer
2016-01-05 11:23:13.119 ThaliTest[1284:2753490] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 54982
,2016-01-05 11:23:13.214 ThaliTest[1284:2753490] jxcore: startBroadcasting
,2016-01-05 11:23:13.218 ThaliTest[1284:2753490] server: starting Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:23:13.218 ThaliTest[1284:2753490] multipeer session: start timer: 0x1460b0c0
2016-01-05 11:23:13.219 ThaliTest[1284:2753490] THEMultipeerSession init,ialized peer Apple-Iphone5s-1
2016-01-05 11:23:13.219 ThaliTest[1284:2753490] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-05T10:23:13.222Z SendDataTCPServer.js: TCP/IP server is bound to port: 54982
,2016-01-05 11:23:14.175 ThaliTest[1284:2753294] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":true}]
2016-01-05 11:23:14.180 ThaliTest[1284:2753294,] client: found peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:14.180 ThaliTest[1284:2753294] client: found peer: Apple-IpadAir2-1.o3kBVg==
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:14.185Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:14.187Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Jzs4Xw==
2016-01-05T10:23:14.187Z SendDataConnector.js: do connect now
2016-01-05 11:23:14.189 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5s-1.Jzs4Xw==
2,016-01-05 11:23:14.190 ThaliTest[1284:2753490] client session: connect
2016-01-05 11:23:14.190 ThaliTest[1284:2753490] client session: stateChange:0->1 Apple-Iphone5s-1.Jzs4Xw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 11:23:14.384 ThaliTest[1284:2753294] client: lost peer: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.384 ThaliTest[1284:2753294] client session: onPeerLost: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.384 ThaliTest[1284:2753294] client session: onLinkFailure: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.385 ThaliTest[1284:2753294] client session: disconnect
2016-01-05 11:23:14.385 ThaliTest[1284:2753294] client session: stateChange:1->0 Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.386 T,haliTest[1284:2753294] client session: fireConnectCallback: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.386 ThaliTest[1284:2753294] jxcore: connect: fail: Peer disconnected
2016-01-05T10:23:14.388Z SendDataConnector.js: CLIENT connected to 0, error: Pe,er disconnected
2016-01-05T10:23:14.389Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T10:23:14.389Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerN,ame":"(null)","peerAvailable":false}]
,2016-01-05 11:23:14.663 ThaliTest[1284:2753294] client: found peer: Apple-IpadAir2-1.C4KP1Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.C4KP1Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:14.675 ThaliTest[1284:2753294] client: found peer: Apple-Iphone5-1.GgrI3w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.GgrI3w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:14.784 ThaliTest[1284:2753294] client: found peer: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:23:14.785 ThaliTest[1284:2753294] client: lost peer: Apple-IpadAir2-1.o3kBVg==
2016-01-05 11:23:14.786 ThaliTest[1284:2753294] client session: onPe,erLost: Apple-IpadAir2-1.o3kBVg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DQd5Sw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==,","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 11:23:15.725 ThaliTest[1284:2753294] client: lost peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:15.725 ThaliTest[1284:2753294] client session: onPeerLost: Apple-Iphone5-1.+hwmKw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+,hwmKw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05T10:23:19.395Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:19.396Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:24.400 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:23:24.401 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:23:24.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Jzs4Xw==
2,016-01-05T10:23:24.402Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.Jzs4Xw== with availability status: true
2016-01-05T10:23:24.402Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Jzs4Xw==
2016-01-05T10:23:24.403Z SendDataConnector.js: do connect now
,2016-01-05 11:23:24.404 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:24.404 ThaliTest[1284:2753490] client: connect: unreachable Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:24.405 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:24.406Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:24.408Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T10:23:24.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:29.414Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:29.414Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:34.428 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:23:34.428 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:23:34.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Jzs4Xw==
2,016-01-05T10:23:34.429Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.Jzs4Xw== with availability status: true
2016-01-05T10:23:34.430Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Jzs4Xw==
2016-01-05T10:23:34,.430Z SendDataConnector.js: do connect now
,2016-01-05 11:23:34.431 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:34.432 ThaliTest[1284:2753490] client: connect: unreachable Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:34.432 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:34.433Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T10:23:34.434Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-05T10:23:34.435Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:39.441Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:39.441Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:43.220 ThaliTest[1284:2753294] multipeer session: restart
,2016-01-05 11:23:44.447 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:23:44.448 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:23:44.448Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Jzs4Xw==
2,016-01-05T10:23:44.449Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.Jzs4Xw== with availability status: true
2016-01-05T10:23:44.449Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:44.449Z SendDataConnector.js: do connect now
2016-01-05 11:23:44.450 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:44.451 ThaliTest[1284:2753490] client: connect: unreachable Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:44.452 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:44.453Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:44.453Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:44.454Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:49.455Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:49.456Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:54.465 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:23:54.465 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:23:54.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Jzs4Xw==
2,016-01-05T10:23:54.466Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.Jzs4Xw== with availability status: true
2016-01-05T10:23:54.467Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05T10:23:54.467Z SendDataConnector.js: do connect now
2016-01-05 11:23:54.468 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:54.469 ThaliTest[1284:2753490] client: connect: unreachable Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:54.469 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:54.471Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:54.471Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-05T10:23:54.473Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 11:23:54.475 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:23:54.475 ThaliTest[1284:2753490] jxcore: disconnect: fail
,2016-01-05T10:23:54.477Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Jzs4Xw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:54.481Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:54.481Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:54.482Z SendDataConnector.js: do connect now
,2016-01-05 11:23:54.483 ThaliTest[1284:2753490] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:54.484 ThaliTest[1284:2753490] client session: connect
2016-01-05 11:23:54.484 ThaliTest[1284:2753490] client session: stateChange:0->1 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:54.499 ThaliTest[1284:2753294] client: lost peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:54.500 ThaliTest[1284:2753294] client session: onPeerLost: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:54.500 ThaliTest[1284:2753294] client sess,ion: onLinkFailure: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:54.500 ThaliTest[1284:2753294] client session: disconnect
2016-01-05 11:23:54.500 ThaliTest[1284:2753294] client session: stateChange:1->0 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:54.555 ThaliTest[1284:2753294] client session: fireConnectCallback: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:54.556 ThaliTest[1284:2753294] jxcore: connect: fail: Peer disconnected
2016-01-05T10:23:54.557Z SendDataConnector.js: CLIENT ,connected to 0, error: Peer disconnected
2016-01-05T10:23:54.557Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T10:23:54.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,adAir2-1.C4KP1Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-05T10:23:59.567Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:59.567Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:00.922 ThaliTest[1284:2753294] multipeer session: reset timer
2016-01-05 11:24:00.923 ThaliTest[1284:2753294] multipeer session: stop timer
2016-01-05 11:24:00.923 ThaliTest[1284:2753294] multipeer session: start timer: 0x1460b0c0
2016-,01-05 11:24:00.923 ThaliTest[1284:2753294] server session: connect
2016-01-05 11:24:00.924 ThaliTest[1284:2753294] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 11:24:00.933 ThaliTest[1284:2753294] server: accepting invitation Apple-Iphone6-1
,2016-01-05 11:24:02.435 ThaliTest[1284:2753294] multipeer session: reset timer
,2016-01-05 11:24:02.435 ThaliTest[1284:2753294] multipeer session: stop timer
,2016-01-05 11:24:02.435 ThaliTest[1284:2753294] multipeer session: start timer: 0x1460b0c0
,2016-01-05 11:24:02.437 ThaliTest[1284:2753294] server session: connect
,2016-01-05 11:24:02.438 ThaliTest[1284:2753294] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 11:24:02.452 ThaliTest[1284:2753294] server: accepting invitation Apple-Iphone5-1
,2016-01-05 11:24:02.520 ThaliTest[1284:2753294] multipeer session: reset timer
2016-01-05 11:24:02.521 ThaliTest[1284:2753294] multipeer session: stop timer
2016-01-05 11:24:02.522 ThaliTest[1284:2753294] multipeer session: start timer: 0x1460b0c0
2016-01-05 11:24:02.522 ThaliTest[1284:2753294] server session: connect
,2016-01-05 11:24:02.522 ThaliTest[1284:2753294] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 11:24:02.542 ThaliTest[1284:2753294] server: accepting invitation Apple-IpadAir2-1
,2016-01-05 11:24:03.488 ThaliTest[1284:2754157] server session: connected
2016-01-05 11:24:03.489 ThaliTest[1284:2754157] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 11:24:03.544 ThaliTest[1284:2753294] server relay: connected (to port: 54982)
,2016-01-05T10:24:03.553Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:03.804Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-05T10:24:03.822Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-05T10:24:03.842Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-05T10:24:03.860Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-05T10:24:03.878Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-05T10:24:03.892Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:04.002 ThaliTest[1284:2754124] server session: not connected Apple-Iphone6-1
,2016-01-05 11:24:04.572 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:04.573 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:24:04.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
2,016-01-05T10:24:04.574Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.C4KP1Q== with availability status: true
2016-01-05T10:24:04.574Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:24:04.574Z SendDataConnector.js: do connect now
2016-01-05 11:24:04.576 ThaliTest[1284:2753490] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:04.578 ThaliTest[1284:2753490] client: connect: unreachable Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:04.578 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
2016-01-05T10:24:04.579Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2016-01-05T10:24:04.579Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:24:04.580Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05 11:24:05.148 ThaliTest[1284:2754157] server session: connected
2016-01-05 11:24:05.150 ThaliTest[1284:2754157] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05T10:24:05.168Z SendDataTCPServer.js: TCP/IP server connected
2016-01-05 11:24:05.169 ThaliTest[1284:2753294] server relay: connected (to port: 54982)
,2016-01-05T10:24:05.714Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
2016-01-05T10:24:05.728Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-05T10:24:05.743Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2016-01-05T10:24:05.759Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-05T10:24:05.773Z SendDataTCPServer.js: TCP/IP server has received 49944 bytes of data
,2016-01-05T10:24:05.788Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-05T10:24:05.802Z SendDataTCPServer.js: TCP/IP server has received 72128 bytes of data
,2016-01-05 11:24:05.816 ThaliTest[1284:2754126] server session: connected
2016-01-05T10:24:05.817Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-05 11:24:05.817 ThaliTest[1284:2754126] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 11:24:05.827 ThaliTest[1284:2753294] server relay: connected (to port: 54982)
,2016-01-05T10:24:05.835Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
2016-01-05T10:24:05.836Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:05.849Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:05.971 ThaliTest[1284:2754127] server session: not connected Apple-Iphone5-1
,2016-01-05T10:24:06.098Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-05T10:24:06.116Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2016-01-05T10:24:06.132Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-05T10:24:06.148Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2016-01-05T10:24:06.167Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-05T10:24:06.183Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-05T10:24:06.198Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:06.247 ThaliTest[1284:2754157] server session: not connected Apple-IpadAir2-1
,2016-01-05T10:24:09.586Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:24:09.586Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:14.590 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:14.591 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:24:14.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
2,016-01-05T10:24:14.592Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.C4KP1Q== with availability status: true
2016-01-05T10:24:14.592Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:24:14.593Z SendDataConnector.js: do connect now
,2016-01-05 11:24:14.594 ThaliTest[1284:2753490] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:14.594 ThaliTest[1284:2753490] client: connect: unreachable Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:14.595 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
2016-01-05T10:24:14.597Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:24:14.597Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2016-01-05T10:24:14.597Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:24:19.603Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:24:19.603Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:24.616 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:24.616 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:24:24.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
2,016-01-05T10:24:24.617Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.C4KP1Q== with availability status: true
2016-01-05T10:24:24.618Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:24:24,.618Z SendDataConnector.js: do connect now
,2016-01-05 11:24:24.619 ThaliTest[1284:2753490] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:24.620 ThaliTest[1284:2753490] client: connect: unreachable Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:24.620 ThaliTest[1284:2753490] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:24:24.621Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:24:24.622Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:24:24.623Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:24:29.628Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:24:29.628Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:32.523 ThaliTest[1284:2753294] multipeer session: restart
,2016-01-05 11:24:32.578 ThaliTest[1284:2753294] client: found peer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:32.578 ThaliTest[1284:2753294] client: found peer: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:32.579 ThaliTest[1284:2753294] client: found peer: ,Apple-IpadAir2-1.C4KP1Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.C4KP1Q==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 11:24:34.630 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:34.631 ThaliTest[1284:2753490] jxcore: disconnect: fail
2016-01-05T10:24:34.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
2,016-01-05T10:24:34.632Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.C4KP1Q== with availability status: true
2016-01-05T10:24:34.632Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:24:34.633Z SendDataConnector.js: do connect now
,2016-01-05 11:24:34.634 ThaliTest[1284:2753490] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:34.634 ThaliTest[1284:2753490] client session: connect
,2016-01-05 11:24:34.635 ThaliTest[1284:2753490] client session: stateChange:0->1 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:38.279 ThaliTest[1284:2754243] client session: connected
2016-01-05 11:24:38.279 ThaliTest[1284:2754243] client session: stateChange:1->2 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:38.295 ThaliTest[1284:2754263] client session: fireConnectCallback: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:38.295 ThaliTest[1284:2754263] jxcore: connect: success
2016-01-05T10:24:38.297Z SendDataConnector.js: CLIENT connected to 54993, error: null
2016-01-05T10:24:38.297Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:38.301 ThaliTest[1284:2753294] client: relay established
2016-01-05 11:24:38.302 ThaliTest[1284:2753294] client: new accepted socket: 0x15b20200
,2016-01-05T10:24:38.318Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:38.695Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T10:24:38.721Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05T10:24:38.757Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:24:38.758Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T10:24:38.758Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:38.758Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:38.759 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:38.760 ThaliTest[1284:2753490] client session: disconnectFromPeer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:38.760 ThaliTest[1284:2753490] client session: disconnect
2,016-01-05 11:24:38.760 ThaliTest[1284:2753490] client session: stateChange:2->0 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:38.766 ThaliTest[1284:2753490] jxcore: disconnect: success
2016-01-05T10:24:38.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5-1.GgrI3w==
2016-01-05T10:24:38.767Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.GgrI3w==
2016-01-05T10:24:38.767Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.GgrI3w==
2016-01-05T10:24:38.767Z SendDataConnector.js: do connect now
2016-01-05 11:24:38.767 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:38.767 ThaliTest[1284:2753490] client session: connect
2016-01-05 11:24:38.768 ThaliTest[1284:2753490] client session: stateChan,ge:0->1 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:42.730 ThaliTest[1284:2754241] client session: connected
2016-01-05 11:24:42.730 ThaliTest[1284:2754241] client session: stateChange:1->2 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:42.913 ThaliTest[1284:2754243] client session: fireConnectCallback: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:42.914 ThaliTest[1284:2754243] jxcore: connect: success
2016-01-05T10:24:42.915Z SendDataConnector.js: CLIENT connected to 5499,6, error: null
2016-01-05T10:24:42.916Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:42.920 ThaliTest[1284:2753294] client: relay established
2016-01-05 11:24:42.921 ThaliTest[1284:2753294] client: new accepted socket: 0x15c37e80
,2016-01-05T10:24:42.932Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:43.270Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T10:24:43.284Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T10:24:43.309Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05T10:24:43.334Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:43.335Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T10:24:43.335Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:43.335Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:43.336 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:43.336 ThaliTest[1284:2753490] client session: disconnectFromPeer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:43.336 ThaliTest[1284:2753490] client session: disconnect
2016-01-05 11:24:43.336 ThaliTest[1284:2753490] client session: stateChange:2->0 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:43.342 ThaliTest[1284:2753490] jxcore: disconnect: success
2016-01-05T10:24:43.342Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.GgrI3w==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,ne6-1.DQd5Sw==
2016-01-05T10:24:43.343Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DQd5Sw==
2016-01-05T10:24:43.343Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DQd5Sw==
2016-01-05T10:24:43.343Z SendDataConnector.j,s: do connect now
2016-01-05 11:24:43.344 ThaliTest[1284:2753490] jxcore: connect Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:43.344 ThaliTest[1284:2753490] client session: connect
2016-01-05 11:24:43.344 ThaliTest[1284:2753490] client session: stateChange:0->1 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:48.237 ThaliTest[1284:2754243] client session: connected
2016-01-05 11:24:48.237 ThaliTest[1284:2754243] client session: stateChange:1->2 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:48.563 ThaliTest[1284:2754270] client session: fireConnectCallback: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:48.563 ThaliTest[1284:2754270] jxcore: connect: success
2016-01-05T10:24:48.564Z SendDataConnector.js: CLIENT connected to 5499,9, error: null
2016-01-05T10:24:48.565Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:48.569 ThaliTest[1284:2753294] client: relay established
2016-01-05 11:24:48.570 ThaliTest[1284:2753294] client: new accepted socket: 0x15c41660
,2016-01-05T10:24:48.580Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:49.065Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T10:24:49.078Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05T10:24:49.138Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:49.138Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T10:24:49.139Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:49.139Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:49.140 ThaliTest[1284:2753490] jxcore: disconnect
2016-01-05 11:24:49.140 ThaliTest[1284:2753490] client session: disconnectFromPeer: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:49.140 ThaliTest[1284:2753490] client session: disconnect
20,16-01-05 11:24:49.140 ThaliTest[1284:2753490] client session: stateChange:2->0 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:49.146 ThaliTest[1284:2753490] jxcore: disconnect: success
2016-01-05T10:24:49.146Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DQd5Sw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2016-01-05T10:24:49.149Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:49.149Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-05 11:24:50.051 ThaliTest[1284:2753490] jxcore: stopBroadcasting
,2016-01-05 11:24:50.052 ThaliTest[1284:2753490] THEMultipeerSession stopping peer
,2016-01-05 11:24:50.052 ThaliTest[1284:2753490] multipeer session: stop timer
,2016-01-05 11:24:50.054 ThaliTest[1284:2753490] server session: disconnect
2016-01-05 11:24:50.057 ThaliTest[1284:2753490] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-05 11:24:50.064 ThaliTest[1284:2753490] server session: disconnect
2016-0,1-05 11:24:50.065 ThaliTest[1284:2753490] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-05 11:24:50.130 ThaliTest[1284:2753490] server session: disconnect
2016-01-05 11:24:50.131 ThaliTest[1284:2753490] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-05 11:24:50.147 ThaliTest[1284:2753490] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-05T10:24:50.167Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.169Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.171Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.172Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
