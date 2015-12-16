#### Test 50650278923ff9f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/633C96D9-8825-4AA8-877F-C74CEE60EAA8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/633C96D9-8825-4AA8-877F-C74CEE60EAA8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278923ff9f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8DF42E15-7560-48A1-91AB-ABB142372558/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58661"
,(lldb)     command script import "/tmp/633C96D9-8825-4AA8-877F-C74CEE60EAA8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 16:44:07.063 ThaliTest[291:104454] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/96519168-8463-4EF8-ABFD-CA58C5B027C5/Library/Cookies/Cookies.binarycookies
,2015-12-16 16:44:07.520 ThaliTest[291:104454] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 16:44:07.521 ThaliTest[291:104454] Multi-tasking -> Device: YES, App: YES
,2015-12-16 16:44:07.531 ThaliTest[291:104454] Unlimited access to network resources
,2015-12-16 16:44:07.544 ThaliTest[291:104454] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 16:44:16.392 ThaliTest[291:104454] Resetting plugins due to page load.
,2015-12-16 16:44:20.160 ThaliTest[291:104454] Finished load of: file:///var/mobile/Containers/Bundle/Application/8DF42E15-7560-48A1-91AB-ABB142372558/ThaliTest.app/www/index.html
,2015-12-16 16:44:20.372 ThaliTest[291:104454] JXcore Cordova plugin initializing
2015-12-16 16:44:20.373 ThaliTest[291:104681] JXcore instance initializing
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
,2015-12-16 16:44:21.690 ThaliTest[291:104454] THREAD WARNING: ['JXcore'] took '92.440918' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 16:49:28.952 ThaliTest[291:104681] jxcore: startBroadcasting
,2015-12-16 16:49:28.976 ThaliTest[291:104681] server: starting Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:28.978 ThaliTest[291:104681] multipeer session: start timer: 0x15b98770
2015-12-16 16:49:28.979 ThaliTest[291:104681] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1155
2015-12-16 16:49:28.980 ThaliTest[291:104681] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
,2015-12-16 16:49:29.779 ThaliTest[291:104454] client: found peer: Apple-IpadAir2-1_PT1077.nIXSkg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.nIXSkg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT1077.nIXSkg==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-16 16:49:30.192 ThaliTest[291:104454] client: found peer: Apple-Iphone6-1_PT3392.Ts8/9g==
,2015-12-16 16:49:30.314 ThaliTest[291:104454] client: found peer: Apple-Iphone5-1_PT9225.vQjqPA==
,2015-12-16 16:49:32.085 ThaliTest[291:104454] multipeer session: reset timer
2015-12-16 16:49:32.085 ThaliTest[291:104454] multipeer session: stop timer
2015-12-16 16:49:32.086 ThaliTest[291:104454] multipeer session: start timer: 0x15b98770
,2015-12-16 16:49:32.088 ThaliTest[291:104454] server session: connect
2015-12-16 16:49:32.088 ThaliTest[291:104454] server session: stateChange:0->1 Apple-Iphone5-1_PT9225
,2015-12-16 16:49:32.101 ThaliTest[291:104454] server: accepting invitation Apple-Iphone5-1_PT9225
,teardown
testFindPeers stopped
2015-12-16 16:49:32.208 ThaliTest[291:104681] jxcore: stopBroadcasting
2015-12-16 16:49:32.209 ThaliTest[291:104681] THEMultipeerSession stopping peer
2015-12-16 16:49:32.210 ThaliTest[291:104681] multipeer session: stop timer
2015-12-16 16:49:32.210 ThaliTest[291:104681] server session: disconnect
2015-12-16 16:49:32.210 ThaliTest[291:104681] server session: stateChange:1->0 Apple-Iphone5-1_PT9225
2015-12-16 16:49:32.214 ThaliTest[291:104681] jxcore: stopBroadcasting: ,success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 49973
,2015-12-16 16:49:32.313 ThaliTest[291:104681] jxcore: startBroadcasting
,2015-12-16 16:49:32.317 ThaliTest[291:104681] server: starting Apple-Iphone5s-1_PT1155.Bev+OQ==
,2015-12-16 16:49:32.320 ThaliTest[291:104681] multipeer session: start timer: 0x15baa600
,2015-12-16 16:49:32.322 ThaliTest[291:104681] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1155
,2015-12-16 16:49:32.323 ThaliTest[291:104681] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-16T15:49:32.331Z SendDataTCPServer.js: TCP/IP server is bound to port: 49973
,2015-12-16 16:49:32.891 ThaliTest[291:104454] client: found peer: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:32.893 ThaliTest[291:104454] client: found peer: Apple-Iphone5-1_PT9225.kJjMbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5,s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16T15:49:32.896Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_,PT1155.WIj3og==
2015-12-16T15:49:32.896Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16T15:49:32.897Z SendDataConnector.js: do connect now
,2015-12-16 16:49:32.900 ThaliTest[291:104681] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:32.901 ThaliTest[291:104681] client session: connect
,2015-12-16 16:49:32.902 ThaliTest[291:104681] client session: stateChange:0->1 Apple-Iphone5s-1_PT1155.WIj3og==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9225.kJjMbg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 16:49:33.373 ThaliTest[291:104454] client: lost peer: Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:33.373 ThaliTest[291:104454] client session: onPeerLost: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.374 ThaliTest[291:104454] client session: onLinkFailure: Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.375 ThaliTest[291,:104454] client session: disconnect
2015-12-16 16:49:33.375 ThaliTest[291:104454] client session: stateChange:1->0 Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:33.376 ThaliTest[291:104454] client session: fireConnectCallback: Apple-Iphone5s-1_PT1155,.WIj3og==
2015-12-16 16:49:33.377 ThaliTest[291:104454] jxcore: connect: fail: Peer disconnected
2015-12-16 16:49:33.377 ThaliTest[291:104454] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16T15:49:33.380Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-16T15:49:33.380Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T15:49:33.381Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5s-1_PT1155.WIj3og==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3392.EGNu6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-16 16:49:33.388 ThaliT,est[291:104454] client: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1077.khzDiQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16T15:49:38.392Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:38.393Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:43.401 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:49:43.401 ThaliTest[291:104681] jxcore: disconnect: fail
2015-12-16T15:49:43.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:49:43.403Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:49:43.404Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:43.404Z SendDataConnector.js: do connect now
2015-12-16 16:49:43.405 ThaliTest[291:104681] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:43.406 ThaliTest[291:104681] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:49:43.407 ThaliTest[291:104681] jxcore: connect: fail: Peer unreachable
2015-12-16T15:49:43.408Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-16T15:49:43.408Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:43.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:48.409Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:48.410Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:53.410 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:49:53.411 ThaliTest[291:104681] jxcore: disconnect: fail
2015-12-16T15:49:53.411Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:49:53.412Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:49:53.412Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:53.412Z SendDataConnector.js: do connect now
2015-12-16 16:49:53.413 ThaliTest[291:104681] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:53.415 ThaliTest[291:104681] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:49:53.415 ThaliTest[291:104681] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:49:53.416Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:49:53.417Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:49:53.418Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:49:58.413Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:49:58.413Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:02.307 ThaliTest[291:104454] multipeer session: restart
,2015-12-16 16:50:02.378 ThaliTest[291:104454] client: found peer: Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:02.379 ThaliTest[291:104454] client: found peer: Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:02.398 ThaliTest[291:104454] client: found peer: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:03.419 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:50:03.420 ThaliTest[291:104681] jxcore: disconnect: fail
2015-12-16T15:50:03.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:50:03.420Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:50:03.421Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
20,15-12-16T15:50:03.421Z SendDataConnector.js: do connect now
,2015-12-16 16:50:03.421 ThaliTest[291:104681] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
2015-12-16 16:50:03.422 ThaliTest[291:104681] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:03.422 ThaliTest[291:104681] jxcore: connect: fail: Peer unreachable
2015-12-16T15:50:03.423Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:03.424Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T15:50:03.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T15:50:08.430Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:50:08.430Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:13.433 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:50:13.434 ThaliTest[291:104681] jxcore: disconnect: fail
2015-12-16T15:50:13.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==,
2015-12-16T15:50:13.435Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT1155.WIj3og== with availability status: true
2015-12-16T15:50:13.435Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16T15:50:13.436Z SendDataConnector.js: do connect now
2015-12-16 16:50:13.436 ThaliTest[291:104681] jxcore: connect Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:13.437 ThaliTest[291:104681] client: connect: unreachable Apple-Iphone5s-1_PT1155.WIj3og==
,2015-12-16 16:50:13.438 ThaliTest[291:104681] jxcore: connect: fail: Peer unreachable
,2015-12-16T15:50:13.439Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T15:50:13.440Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-16T15:50:13.442Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 16:50:13.443 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:50:13.444 ThaliTest[291:104681] jxcore: disconnect: fail
,2015-12-16T15:50:13.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1155.WIj3og==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:13.449Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:13.450Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16T15:50:13.451Z SendDataConnector.js: do connect now
,2015-12-16 16:50:13.452 ThaliTest[291:104681] jxcore: connect Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:13.453 ThaliTest[291:104681] client session: connect
2015-12-16 16:50:13.453 ThaliTest[291:104681] client session: stateChange:0->1 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:16.956 ThaliTest[291:104454] multipeer session: reset timer
2015-12-16 16:50:16.957 ThaliTest[291:104454] multipeer session: stop timer
2015-12-16 16:50:16.957 ThaliTest[291:104454] multipeer session: start timer: 0x15baa600
2015-12-16 ,16:50:16.958 ThaliTest[291:104454] server session: connect
2015-12-16 16:50:16.958 ThaliTest[291:104454] server session: stateChange:0->1 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:16.975 ThaliTest[291:104454] server: accepting invitation Apple-Iphone6-1_PT3392
,2015-12-16 16:50:19.496 ThaliTest[291:105527] server session: connected
2015-12-16 16:50:19.497 ThaliTest[291:105527] server session: stateChange:1->2 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:19.524 ThaliTest[291:105510] client session: connected
2015-12-16 16:50:19.526 ThaliTest[291:105510] client session: stateChange:1->2 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:19.530 ThaliTest[291:104454] server relay: connected (to port: 49973)
2015-12-16 16:50:19.533 ThaliTest[291:105510] client session: fireConnectCallback: Apple-Iphone5-1_PT9225.kJjMbg==
2015-12-16 16:50:19.533 ThaliTest[291:105510] jxcore,: connect: success
2015-12-16T15:50:19.534Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T15:50:19.542Z SendDataConnector.js: CLIENT connected to 49981, error: null
2015-12-16T15:50:19.542Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:19.546 ThaliTest[291:104454] client: relay established
,2015-12-16 16:50:19.547 ThaliTest[291:104454] client: new accepted socket: 0x15bb8b30
,2015-12-16T15:50:19.560Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:19.981Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16T15:50:19.994Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:20.009Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16 16:50:20.023 ThaliTest[291:105324] server session: not connected Apple-Iphone6-1_PT3392
,2015-12-16T15:50:20.026Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-16T15:50:20.038Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:20.038Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T15:50:20.039Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:20.039Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:20.040 ThaliTest[291:104681] jxcore: disconnect
,2015-12-16 16:50:20.041 ThaliTest[291:104681] client session: disconnectFromPeer: Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:20.041 ThaliTest[291:104681] client session: disconnect
,2015-12-16 16:50:20.042 ThaliTest[291:104681] client session: stateChange:2->0 Apple-Iphone5-1_PT9225.kJjMbg==
,2015-12-16 16:50:20.046 ThaliTest[291:104681] jxcore: disconnect: success
,2015-12-16T15:50:20.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9225.kJjMbg==
,---- round done--------
,startWithNextDevice
device[3]: Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:20.054Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:20.054Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16T15:50:20.055Z SendDataConnector.js: do connect now
,2015-12-16 16:50:20.055 ThaliTest[291:104681] jxcore: connect Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:20.056 ThaliTest[291:104681] client session: connect
,2015-12-16 16:50:20.056 ThaliTest[291:104681] client session: stateChange:0->1 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:20.616 ThaliTest[291:104454] multipeer session: reset timer
2015-12-16 16:50:20.616 ThaliTest[291:104454] multipeer session: stop timer
,2015-12-16 16:50:20.617 ThaliTest[291:104454] multipeer session: start timer: 0x15baa600
,2015-12-16 16:50:20.618 ThaliTest[291:104454] server session: connect
,2015-12-16 16:50:20.619 ThaliTest[291:104454] server session: stateChange:0->1 Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:20.629 ThaliTest[291:104454] server: accepting invitation Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:21.602 ThaliTest[291:104454] multipeer session: reset timer
2015-12-16 16:50:21.602 ThaliTest[291:104454] multipeer session: stop timer
2015-12-16 16:50:21.603 ThaliTest[291:104454] multipeer session: start timer: 0x15baa600
2015-12-16 ,16:50:21.603 ThaliTest[291:104454] server session: connect
2015-12-16 16:50:21.603 ThaliTest[291:104454] server session: stateChange:0->1 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:21.616 ThaliTest[291:104454] server: accepting invitation Apple-Iphone5-1_PT9225
,2015-12-16 16:50:22.282 ThaliTest[291:105324] client session: connected
2015-12-16 16:50:22.282 ThaliTest[291:105324] client session: stateChange:1->2 Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:22.288 ThaliTest[291:105324] client session: fireConne,ctCallback: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:22.288 ThaliTest[291:105324] jxcore: connect: success
,2015-12-16T15:50:22.292Z SendDataConnector.js: CLIENT connected to 49984, error: null
2015-12-16T15:50:22.292Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:22.296 ThaliTest[291:104454] client: relay established
2015-12-16 16:50:22.297 ThaliTest[291:104454] client: new accepted socket: 0x15bbb960
,2015-12-16T15:50:22.307Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:22.592Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T15:50:22.619Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:22.632Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16T15:50:22.643Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:22.656Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:22.657Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T15:50:22.657Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:22.657Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:22.658 ThaliTest[291:104681] jxcore: disconnect
2015-12-16 16:50:22.658 ThaliTest[291:104681] client session: disconnectFromPeer: Apple-Iphone6-1_PT3392.EGNu6Q==
2015-12-16 16:50:22.658 ThaliTest[291:104681] client session: disconnect
2,015-12-16 16:50:22.658 ThaliTest[291:104681] client session: stateChange:2->0 Apple-Iphone6-1_PT3392.EGNu6Q==
,2015-12-16 16:50:22.664 ThaliTest[291:104681] jxcore: disconnect: success
2015-12-16T15:50:22.664Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3392.EGNu6Q==
---- round done--------
startWithNextDevice
device[4]: Apple,-IpadAir2-1_PT1077.khzDiQ==
2015-12-16T15:50:22.665Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16T15:50:22.665Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16T15:50:22.665Z SendDataConnector.js: do connect now
2015-12-16 16:50:22.667 ThaliTest[291:104681] jxcore: connect Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:22.667 ThaliTest[291:104681] client session: connect
2015-12-16 16:50:22.667 ThaliTest[291:104681] client session: stateChange:0->1 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:23.218 ThaliTest[291:105324] server session: connected
2015-12-16 16:50:23.219 ThaliTest[291:105324] server session: stateChange:1->2 Apple-IpadAir2-1_PT1077
,2015-12-16T15:50:23.236Z SendDataTCPServer.js: TCP/IP server connected
2015-12-16 16:50:23.237 ThaliTest[291:104454] server relay: connected (to port: 49973)
,2015-12-16T15:50:23.639Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-16T15:50:23.659Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-16T15:50:23.681Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-16T15:50:23.699Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-16T15:50:23.717Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:23.756 ThaliTest[291:105324] server session: not connected Apple-IpadAir2-1_PT1077
,2015-12-16 16:50:24.190 ThaliTest[291:105509] server session: connected
2015-12-16 16:50:24.193 ThaliTest[291:105509] server session: stateChange:1->2 Apple-Iphone5-1_PT9225
,2015-12-16T15:50:24.208Z SendDataTCPServer.js: TCP/IP server connected
2015-12-16 16:50:24.212 ThaliTest[291:104454] server relay: connected (to port: 49973)
,2015-12-16T15:50:24.718Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-16T15:50:24.736Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-16T15:50:24.757Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-16T15:50:24.779Z SendDataTCPServer.js: TCP/IP server has received 74318 bytes of data
,2015-12-16T15:50:24.797Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-16T15:50:24.812Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 16:50:24.892 ThaliTest[291:105510] server session: not connected Apple-Iphone5-1_PT9225
,2015-12-16 16:50:25.240 ThaliTest[291:105510] client session: connected
2015-12-16 16:50:25.241 ThaliTest[291:105510] client session: stateChange:1->2 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:25.259 ThaliTest[291:105527] client session: fireConnectCallback: Apple-IpadAir2-1_PT1077.khzDiQ==
2015-12-16 16:50:25.259 ThaliTest[291:105527] jxcore: connect: success
,2015-12-16T15:50:25.261Z SendDataConnector.js: CLIENT connected to 49989, error: null
,2015-12-16T15:50:25.263Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 16:50:25.266 ThaliTest[291:104454] client: relay established
,2015-12-16 16:50:25.268 ThaliTest[291:104454] client: new accepted socket: 0x15c97af0
,2015-12-16T15:50:25.279Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T15:50:25.754Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-16T15:50:25.766Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T15:50:25.779Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T15:50:25.780Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-16T15:50:25.780Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T15:50:25.781Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 16:50:25.781 ThaliTest[291:104681] jxcore: disconnect
,2015-12-16 16:50:25.782 ThaliTest[291:104681] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:25.782 ThaliTest[291:104681] client session: disconnect
,2015-12-16 16:50:25.783 ThaliTest[291:104681] client session: stateChange:2->0 Apple-IpadAir2-1_PT1077.khzDiQ==
,2015-12-16 16:50:25.851 ThaliTest[291:104681] jxcore: disconnect: success
,2015-12-16T15:50:25.852Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1077.khzDiQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-16T15:50:25.856Z SendDataConnector.js: CLIENT Stop now
2015-12-16T15:50:25.856Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-16 16:50:34.579 ThaliTest[291:104681] jxcore: stopBroadcasting
2015-12-16 16:50:34.581 ThaliTest[291:104681] THEMultipeerSession stopping peer
2015-12-16 16:50:34.581 ThaliTest[291:104681] multipeer session: stop timer
2015-12-16 16:50:34.582 Th,aliTest[291:104681] server session: disconnect
2015-12-16 16:50:34.582 ThaliTest[291:104681] server session: stateChange:2->0 Apple-IpadAir2-1_PT1077
2015-12-16 16:50:34.590 ThaliTest[291:104681] server session: disconnect
2015-12-16 16:50:34.590 ThaliT,est[291:104681] server session: stateChange:2->0 Apple-Iphone5-1_PT9225
,2015-12-16 16:50:34.701 ThaliTest[291:104681] server session: disconnect
,2015-12-16 16:50:34.703 ThaliTest[291:104681] server session: stateChange:2->0 Apple-Iphone6-1_PT3392
,2015-12-16 16:50:34.710 ThaliTest[291:104681] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-16T15:50:34.735Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.736Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.739Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T15:50:34.739Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
