#### Test 50650278b28a87a_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5D805018-16D6-4627-B9CA-CEA4ED63EACC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/5D805018-16D6-4627-B9CA-CEA4ED63EACC/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b28a87a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/670F66D0-9E0D-4B7D-A3AB-A5A87B95075A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52109"
,(lldb)     command script import "/tmp/5D805018-16D6-4627-B9CA-CEA4ED63EACC/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 15:24:04.675 ThaliTest[512:495114] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8A9440A1-E4E1-4468-A235-F9607855EF67/Library/Cookies/Cookies.binarycookies
,2015-12-09 15:24:05.184 ThaliTest[512:495114] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 15:24:05.185 ThaliTest[512:495114] Multi-tasking -> Device: YES, App: YES
,2015-12-09 15:24:05.192 ThaliTest[512:495114] Unlimited access to network resources
,2015-12-09 15:24:05.203 ThaliTest[512:495114] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 15:24:15.839 ThaliTest[512:495114] Resetting plugins due to page load.
,2015-12-09 15:24:19.336 ThaliTest[512:495114] Finished load of: file:///var/mobile/Containers/Bundle/Application/670F66D0-9E0D-4B7D-A3AB-A5A87B95075A/ThaliTest.app/www/index.html
,2015-12-09 15:24:19.553 ThaliTest[512:495114] JXcore Cordova plugin initializing
,2015-12-09 15:24:19.555 ThaliTest[512:495304] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-09 15:24:21.999 ThaliTest[512:495114] THREAD WARNING: ['JXcore'] took '155.333008' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-09 15:30:42.724 ThaliTest[512:495304] jxcore: startBroadcasting
,2015-12-09 15:30:42.736 ThaliTest[512:495304] server: starting Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:42.737 ThaliTest[512:495304] multipeer session: start timer: 0x1cc872c0
2015-12-09 15:30:42.737 ThaliTest[512:495304] THEMultipeerSession initialized peer Apple-Iphone5-1_PT9641
,2015-12-09 15:30:42.738 ThaliTest[512:495304] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-09 15:30:43.732 ThaliTest[512:495114] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT3959.Sz9P+A==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-09 15:30:43.937 ThaliTest[512:495114] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:44.295 ThaliTest[512:495114] client: found peer: Apple-Iphone6-1_PT7748.MiTYRw==
,teardown
,testFindPeers stopped
,2015-12-09 15:30:45.159 ThaliTest[512:495304] jxcore: stopBroadcasting
2015-12-09 15:30:45.159 ThaliTest[512:495304] THEMultipeerSession stopping peer
2015-12-09 15:30:45.159 ThaliTest[512:495304] multipeer session: stop timer
2015-12-09 15:30:45.160 ThaliTest[512:495304] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"servertimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
serverPort is 53261
,2015-12-09 15:30:45.225 ThaliTest[512:495304] jxcore: startBroadcasting
,2015-12-09 15:30:45.228 ThaliTest[512:495304] server: starting Apple-Iphone5-1_PT9641.4z6eyA==
2015-12-09 15:30:45.228 ThaliTest[512:495304] multipeer session: start timer: 0x1cb78c10
2015-12-09 15:30:45.228 ThaliTest[512:495304] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT9641
2015-12-09 15:30:45.229 ThaliTest[512:495304] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-09T14:30:45.231Z SendDataTCPServer.js: TCP/IP server is bound to port: 53261
,2015-12-09 15:30:45.702 ThaliTest[512:495114] client: found peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:45.703 ThaliTest[512:495114] client: found peer: Apple-Iphone5-1_PT9641.ucdqLA==
2015-12-09 15:30:45.703 ThaliTest[512:495114] client: fou,nd peer: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:45.703 ThaliTest[512:495114] client: found peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":,true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.707Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.707Z SendDataConnect,or.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:45.708Z SendDataConnector.js: do connect now
2015-12-09 15:30:45.708 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:45.709 Thali,Test[512:495304] client session: connect
2015-12-09 15:30:45.714 ThaliTest[512:495304] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.sabYWA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.279 ThaliTest[512:495114] client: lost peer: Apple-Iphone5-1_PT9641.ucdqLA==
,2015-12-09 15:30:46.280 ThaliTest[512:495114] client session: onPeerLost: Apple-Iphone5-1_PT9641.ucdqLA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9641.ucdqLA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09 15:30:46.353 ThaliTest[512:495114] client: lost peer: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:46.353 ThaliTest[512:495114] client session: onPeerLost: Apple-Iphone5s-1_PT3959.Sz9P+A==
2015-12-09 15:30:46.354 ThaliTest[512:495114] cli,ent: lost peer: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.354 ThaliTest[512:495114] client session: onPeerLost: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.354 ThaliTest[512:495114] client session: onLinkFailure: Apple-IpadAir2-1_PT91,97.sabYWA==
2015-12-09 15:30:46.354 ThaliTest[512:495114] client session: disconnect
2015-12-09 15:30:46.355 ThaliTest[512:495114] client session: stateChange:1->0 Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.356 ThaliTest[512:495114] client ses,sion: fireConnectCallback: Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:46.356 ThaliTest[512:495114] jxcore: connect: fail: Peer disconnected
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.Sz9P+A==","peerName":"(null)","peerAva,i,lable":false}]
,Found peer : (null), Available: false
2015-12-09T14:30:46.362Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-09T14:30:46.362Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T14:30:46.363Z SendDa,taConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.sabYWA==","peerName":"(null)","peerAvailable":false}]
,2015-12-09 15:30:46.433 ThaliTest[512:495114] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":true}]
2015-12-09 15:30:46.434 ThaliTest[,512:495114] client: found peer: Apple-Iphone6-1_PT7748.7slvbQ==
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.7slvbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:46.517 ThaliTest[512:495114] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.46F2bw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-09 15:30:47.389 ThaliTest[512:495114] client: lost peer: Apple-Iphone6-1_PT7748.MiTYRw==
2015-12-09 15:30:47.389 ThaliTest[512:495114] client session: onPeerLost: Apple-Iphone6-1_PT7748.MiTYRw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7748.MiTYRw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-09T14:30:51.366Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:30:51.367Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:30:56.373 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:30:56.373 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:30:56.375Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:30:56.375Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:30:56.376Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:30:56.376Z SendDataConnector.js: do connect now
,2015-12-09 15:30:56.377 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:56.377 ThaliTest[512:495304] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:30:56.377 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T14:30:56.377Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:30:56.378Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:30:56.378Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:01.389Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:01.389Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:06.393 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:06.393 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:06.394Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:06.394Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:06.394Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:31:06.395Z SendDataConnector.js: do connect now
,2015-12-09 15:31:06.396 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:06.396 ThaliTest[512:495304] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:06.397 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
2015-12-09T14:31:06.397Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:06.397Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:06.397Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:11.404Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:11.404Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:15.230 ThaliTest[512:495114] multipeer session: restart
,2015-12-09 15:31:16.417 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:16.418 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:16.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:16.419Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:16.419Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
20,15-12-09T14:31:16.420Z SendDataConnector.js: do connect now
,2015-12-09 15:31:16.420 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:16.421 ThaliTest[512:495304] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:16.421 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T14:31:16.422Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:16.422Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:16.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:21.426Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09T14:31:21.427Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT9197.sabYWA==
,2015-12-09 15:31:26.435 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:26.436 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:26.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==,
2015-12-09T14:31:26.437Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT9197.sabYWA== with availability status: true
2015-12-09T14:31:26.437Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09T14:31:26.438Z SendDataConnector.js: do connect now
,2015-12-09 15:31:26.439 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:26.439 ThaliTest[512:495304] client: connect: unreachable Apple-IpadAir2-1_PT9197.sabYWA==
2015-12-09 15:31:26.439 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T14:31:26.440Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:26.440Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-09T14:31:26.442Z SendDataConnector.js: CLIENT S,top now
,2015-12-09 15:31:26.442 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:26.442 ThaliTest[512:495304] jxcore: disconnect: fail
,2015-12-09T14:31:26.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.sabYWA==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09T14:31:26.445Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:26.445Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:26.445Z SendDataConnector.js: do connect now
,2015-12-09 15:31:26.446 ThaliTest[512:495304] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:26.446 ThaliTest[512:495304] client session: connect
2015-12-09 15:31:26.447 ThaliTest[512:495304] client session: stateChange:0->1 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:26.454 ThaliTest[512:495114] client: lost peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.454 ThaliTest[512:495114] client session: onPeerLost: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.454 ThaliTest[512:495114] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.454 ThaliTest[512:495114] client session: disconnect
2015-12-09 15:31:26.455 ThaliTest[512:495114] client session: stateChange:1->0 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:26.509 ThaliTest[512:495114] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:26.510 ThaliTest[512:495114] jxcore: connect: fail: Peer disconnected
2015-12-09T14:31:26.511Z SendDataConnector.js: CLIE,NT connected to 0, error: Peer disconnected
2015-12-09T14:31:26.511Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-09T14:31:26.512Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":false}]
,2015-12-09T14:31:31.512Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:31.512Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:35.064 ThaliTest[512:495114] multipeer session: reset timer
2015-12-09 15:31:35.065 ThaliTest[512:495114] multipeer session: stop timer
2015-12-09 15:31:35.065 ThaliTest[512:495114] multipeer session: start timer: 0x1cb78c10
2015-12-09 15:31:35.065 ThaliTest[512:495114] server session: connect
2015-12-09 15:31:35.065 ThaliTest[512:495114] server session: stateChange:0->1 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:35.072 ThaliTest[512:495114] server: accepting invitation Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:35.385 ThaliTest[512:495114] multipeer session: reset timer
2015-12-09 15:31:35.386 ThaliTest[512:495114] multipeer session: stop timer
2015-12-09 15:31:35.386 ThaliTest[512:495114] multipeer session: start timer: 0x1cb78c10
2015-12-09 ,15:31:35.387 ThaliTest[512:495114] server session: connect
2015-12-09 15:31:35.387 ThaliTest[512:495114] server session: stateChange:0->1 Apple-Iphone5s-1_PT3959
2015-12-09 15:31:35.394 ThaliTest[512:495114] server: accepting invitation Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:36.514 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:36.514 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:36.515Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:36.515Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:36.516Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
20,15-12-09T14:31:36.516Z SendDataConnector.js: do connect now
,2015-12-09 15:31:36.517 ThaliTest[512:495304] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:36.518 ThaliTest[512:495304] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:36.518 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
,2015-12-09T14:31:36.518Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:36.519Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:36.520Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09 15:31:38.155 ThaliTest[512:496176] server session: connected
2015-12-09 15:31:38.155 ThaliTest[512:496176] server session: stateChange:1->2 Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:38.175 ThaliTest[512:495114] server relay: connected (to port: 53261)
,2015-12-09T14:31:38.183Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:31:38.548Z SendDataTCPServer.js: TCP/IP server has received 70910 bytes of data
,2015-12-09T14:31:38.568Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:38.745 ThaliTest[512:496176] server session: connected
2015-12-09 15:31:38.745 ThaliTest[512:496176] server session: stateChange:1->2 Apple-Iphone5s-1_PT3959
,2015-12-09 15:31:38.802 ThaliTest[512:496176] server session: not connected Apple-IpadAir2-1_PT9197
,2015-12-09 15:31:38.872 ThaliTest[512:495114] server relay: connected (to port: 53261)
2015-12-09T14:31:38.877Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:31:39.140Z SendDataTCPServer.js: TCP/IP server has received 33052 bytes of data
,2015-12-09T14:31:39.155Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-09T14:31:39.344Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:31:39.534 ThaliTest[512:496176] server session: not connected Apple-Iphone5s-1_PT3959
,2015-12-09T14:31:41.532Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:41.532Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:46.537 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:46.538 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:46.539Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:46.539Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:46.539Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
20,15-12-09T14:31:46.540Z SendDataConnector.js: do connect now
,2015-12-09 15:31:46.541 ThaliTest[512:495304] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:46.541 ThaliTest[512:495304] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:46.541 ThaliTest[512:495304] jxcore: connect: fail: Peer unreachable
,2015-12-09T14:31:46.542Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:46.543Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-09T14:31:46.543Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:31:51.544Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:31:51.545Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:31:56.557 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:31:56.557 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:31:56.558Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:31:56.558Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:31:56.559Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09T14:31:56.559Z SendDataConnector.js: do connect now
,2015-12-09 15:31:56.560 ThaliTest[512:495304] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:56.561 ThaliTest[512:495304] client: connect: unreachable Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:31:56.561 ThaliTest[512:495304] jxcor,e: connect: fail: Peer unreachable
2015-12-09T14:31:56.561Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-09T14:31:56.561Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-09T14:31:56.562Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-09T14:32:01.567Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09T14:32:01.567Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:05.388 ThaliTest[512:495114] multipeer session: restart
,2015-12-09 15:32:05.420 ThaliTest[512:495114] client: found peer: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:05.421 ThaliTest[512:495114] client: found peer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:05.421 ThaliTest[512:495114] client: fo,und peer: Apple-Iphone6-1_PT7748.7slvbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3959.ieNWQg==","peerName":"(null)","peerAvailable":true}]
,2015-12-09 15:32:06.573 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:32:06.573 ThaliTest[512:495304] jxcore: disconnect: fail
2015-12-09T14:32:06.574Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==,
2015-12-09T14:32:06.574Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT3959.ieNWQg== with availability status: true
2015-12-09T14:32:06.575Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3959.ieNWQg==
20,15-12-09T14:32:06.575Z SendDataConnector.js: do connect now
,2015-12-09 15:32:06.576 ThaliTest[512:495304] jxcore: connect Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:06.576 ThaliTest[512:495304] client session: connect
2015-12-09 15:32:06.577 ThaliTest[512:495304] client session: stateChange:0->1 Apple-Ipho,ne5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:10.459 ThaliTest[512:496241] client session: connected
,2015-12-09 15:32:10.459 ThaliTest[512:496241] client session: stateChange:1->2 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:10.502 ThaliTest[512:496240] client session: fireConnectCallback: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:10.503 ThaliTest[512:496240] jxcore: connect: success
2015-12-09T14:32:10.503Z SendDataConnector.js: CLIENT connected to 53270, error: null
2015-12-09T14:32:10.504Z SendDataConnector.js: CLIENT starting client 
2015-12-09 15:32:10.507 ThaliTest[512:495114] client: relay established
,2015-12-09 15:32:10.507 ThaliTest[512:495114] client: new accepted socket: 0x1cb8da80
,2015-12-09T14:32:10.520Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:11.249Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T14:32:11.264Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-09T14:32:11.305Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T14:32:11.370Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-09T14:32:11.433Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:32:11.434Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:32:11.436Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:32:11.437Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:11.438 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:32:11.438 ThaliTest[512:495304] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3959.ieNWQg==
2015-12-09 15:32:11.438 ThaliTest[512:495304] client session: disconnect
2015-12-09 15:32:11.438 ThaliTest[512:495304] client session: stateChange:2->0 Apple-Iphone5s-1_PT3959.ieNWQg==
,2015-12-09 15:32:11.447 ThaliTest[512:495304] jxcore: disconnect: success
2015-12-09T14:32:11.448Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3959.ieNWQg==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09T14:32:11.449Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09T14:32:11.449Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09T14:32:,11.449Z SendDataConnector.js: do connect now
2015-12-09 15:32:11.450 ThaliTest[512:495304] jxcore: connect Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:32:11.450 ThaliTest[512:495304] client session: connect
2015-12-09 15:32:11.450 ThaliTest[512:495304] client session: stateChange:0->1 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:32:18.707 ThaliTest[512:495114] multipeer session: reset timer
,2015-12-09 15:32:18.708 ThaliTest[512:495114] multipeer session: stop timer
,2015-12-09 15:32:18.710 ThaliTest[512:495114] multipeer session: start timer: 0x1cb78c10
,2015-12-09 15:32:18.711 ThaliTest[512:495114] server session: connect
,2015-12-09 15:32:18.712 ThaliTest[512:495114] server session: stateChange:0->1 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:18.723 ThaliTest[512:495114] server: accepting invitation Apple-Iphone6-1_PT7748
,2015-12-09 15:32:19.169 ThaliTest[512:496239] client session: connected
2015-12-09 15:32:19.170 ThaliTest[512:496239] client session: stateChange:1->2 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:32:19.189 ThaliTest[512:496251] client session: fireConnectCallback: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:32:19.189 ThaliTest[512:496251] jxcore: connect: success
2015-12-09T14:32:19.190Z SendDataConnector.js: CLIENT connected to 53273, error: null
2015-12-09T14:32:19.190Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:32:19.193 ThaliTest[512:495114] client: relay established
2015-12-09 15:32:19.193 ThaliTest[512:495114] client: new accepted socket: 0x1ccad130
,2015-12-09T14:32:19.206Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:19.816Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-09T14:32:19.830Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-09T14:32:19.882Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:32:19.883Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:32:19.884Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:32:19.885Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:19.886 ThaliTest[512:495304] jxcore: disconnect
2015-12-09 15:32:19.886 ThaliTest[512:495304] client session: disconnectFromPeer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:32:19.886 ThaliTest[512:495304] client session: disconnect
2015-12-09 15:32:19.887 ThaliTest[512:495304] client session: stateChange:2->0 Apple-Iphone6-1_PT7748.7slvbQ==
,2015-12-09 15:32:19.897 ThaliTest[512:495304] jxcore: disconnect: success
2015-12-09T14:32:19.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7748.7slvbQ==
---- round done--------
startWithNextDevice
device[4]: Apple,-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:32:19.899Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:32:19.899Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09T14:3,2:19.900Z SendDataConnector.js: do connect now
2015-12-09 15:32:19.900 ThaliTest[512:495304] jxcore: connect Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:19.900 ThaliTest[512:495304] client session: connect
2015-12-09 15:32:19.900 ThaliTest[512:495,304] client session: stateChange:0->1 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:21.790 ThaliTest[512:496240] server session: connected
2015-12-09 15:32:21.790 ThaliTest[512:496240] server session: stateChange:1->2 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:21.796 ThaliTest[512:495114] server relay: connected (to port: 53261)
2015-12-09T14:32:21.801Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-09T14:32:22.248Z SendDataTCPServer.js: TCP/IP server has received 12714 bytes of data
,2015-12-09T14:32:22.262Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-09T14:32:22.278Z SendDataTCPServer.js: TCP/IP server has received 61178 bytes of data
,2015-12-09T14:32:22.292Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-09 15:32:22.355 ThaliTest[512:496239] server session: not connected Apple-Iphone6-1_PT7748
,2015-12-09 15:32:23.322 ThaliTest[512:496239] client session: connected
2015-12-09 15:32:23.322 ThaliTest[512:496239] client session: stateChange:1->2 Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:23.325 ThaliTest[512:496239] client session: fireConn,ectCallback: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:23.325 ThaliTest[512:496239] jxcore: connect: success
2015-12-09T14:32:23.326Z SendDataConnector.js: CLIENT connected to 53277, error: null
2015-12-09T14:32:23.327Z SendDataConnector.js: CLIENT starting client 
,2015-12-09 15:32:23.330 ThaliTest[512:495114] client: relay established
2015-12-09 15:32:23.330 ThaliTest[512:495114] client: new accepted socket: 0x1ccb3a80
,2015-12-09T14:32:23.343Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-09T14:32:23.917Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-09T14:32:23.933Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-09T14:32:23.934Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-09T14:32:23.936Z SendDataConnector.js: CLIENT Stop now
,2015-12-09T14:32:23.936Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:23.937 ThaliTest[512:495304] jxcore: disconnect
,2015-12-09 15:32:23.938 ThaliTest[512:495304] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:23.939 ThaliTest[512:495304] client session: disconnect
,2015-12-09 15:32:23.939 ThaliTest[512:495304] client session: stateChange:2->0 Apple-IpadAir2-1_PT9197.46F2bw==
,2015-12-09 15:32:24.024 ThaliTest[512:495304] jxcore: disconnect: success
,2015-12-09T14:32:24.025Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9197.46F2bw==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-09T14:32:24.032Z SendDataConnector.js: CLIENT Stop now
2015-12-09T14:32:24.033Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-09 15:32:29.309 ThaliTest[512:495114] client: lost peer: Apple-IpadAir2-1_PT9197.46F2bw==
2015-12-09 15:32:29.310 ThaliTest[512:495114] client session: onPeerLost: Apple-IpadAir2-1_PT9197.46F2bw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9197.46F2bw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-09 15:32:29.338 ThaliTest[512:495114] client: lost peer: Apple-Iphone6-1_PT7748.7slvbQ==
2015-12-09 15:32:29.338 ThaliTest[512:495114] client session: onPeerLost: Apple-Iphone6-1_PT7748.7slvbQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7748.7slvbQ==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,teardown
,testSendData stopped
2015-12-09 15:32:29.522 ThaliTest[512:495304] jxcore: stopBroadcasting
,2015-12-09 15:32:29.522 ThaliTest[512:495304] THEMultipeerSession stopping peer
,2015-12-09 15:32:29.523 ThaliTest[512:495304] multipeer session: stop timer
,2015-12-09 15:32:29.524 ThaliTest[512:495304] server session: disconnect
2015-12-09 15:32:29.524 ThaliTest[512:495304] server session: stateChange:2->0 Apple-IpadAir2-1_PT9197
,2015-12-09 15:32:29.531 ThaliTest[512:495304] server session: disconnect
2015-12-09 15:32:29.531 ThaliTest[512:495304] server session: stateChange:2->0 Apple-Iphone5s-1_PT3959
,2015-12-09 15:32:29.550 ThaliTest[512:495304] server session: disconnect
2015-12-09 15:32:29.550 ThaliTest[512:495304] server session: stateChange:2->0 Apple-Iphone6-1_PT7748
,2015-12-09 15:32:29.559 ThaliTest[512:495304] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-09T14:32:29.579Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.580Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.582Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-09T14:32:29.582Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
