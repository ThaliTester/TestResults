#### Test 55467363832a26e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D106D9F5-B19A-4FF7-A8A1-792D0005622C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D106D9F5-B19A-4FF7-A8A1-792D0005622C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A271A1F7-60AB-4D21-8126-EA199787DCEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50692"
,(lldb)     command script import "/tmp/D106D9F5-B19A-4FF7-A8A1-792D0005622C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:51:46.779 ThaliTest[1535:3222637] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/84AC246B-2ABE-4A6D-AAE2-32C815C8489A/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:51:47.230 ThaliTest[1535:3222637] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:51:47.232 ThaliTest[1535:3222637] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:51:47.243 ThaliTest[1535:3222637] Unlimited access to network resources
,2016-01-08 17:51:47.258 ThaliTest[1535:3222637] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:51:56.234 ThaliTest[1535:3222637] Resetting plugins due to page load.
,2016-01-08 17:52:00.147 ThaliTest[1535:3222637] Finished load of: file:///var/mobile/Containers/Bundle/Application/A271A1F7-60AB-4D21-8126-EA199787DCEB/ThaliTest.app/www/index.html
,2016-01-08 17:52:00.337 ThaliTest[1535:3222637] JXcore Cordova plugin initializing
,2016-01-08 17:52:00.338 ThaliTest[1535:3222861] JXcore instance initializing
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
,2016-01-08 17:52:01.818 ThaliTest[1535:3222637] THREAD WARNING: ['JXcore'] took '89.700928' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 17:57:05.087 ThaliTest[1535:3222861] jxcore: startBroadcasting
,2016-01-08 17:57:05.108 ThaliTest[1535:3222861] server: starting Apple-Iphone5s-1.kFnM8A==
,2016-01-08 17:57:05.109 ThaliTest[1535:3222861] multipeer session: start timer: 0x1645ac10
,2016-01-08 17:57:05.111 ThaliTest[1535:3222861] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-08 17:57:05.111 ThaliTest[1535:3222861] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 17:57:05.722 ThaliTest[1535:3222637] client: found peer: Apple-IpadAir2-1.hiitZQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.hiitZQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 17:57:05.801 ThaliTest[1535:3222637] client: found peer: Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:06.366 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.vqNzbw==
,teardown
,testFindPeers stopped
,2016-01-08 17:57:06.508 ThaliTest[1535:3222861] jxcore: stopBroadcasting
2016-01-08 17:57:06.509 ThaliTest[1535:3222861] THEMultipeerSession stopping peer
2016-01-08 17:57:06.509 ThaliTest[1535:3222861] multipeer session: stop timer
2016-01-08 17:57:06.,510 ThaliTest[1535:3222861] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57012
,2016-01-08 17:57:06.593 ThaliTest[1535:3222861] jxcore: startBroadcasting
,2016-01-08 17:57:06.596 ThaliTest[1535:3222861] server: starting Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:57:06.605 ThaliTest[1535:3222861] multipeer session: start timer: 0x163cffa0
,2016-01-08 17:57:06.609 ThaliTest[1535:3222861] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-08 17:57:06.614 ThaliTest[1535:3222861] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2016-01-08 17:57:06.621 ThaliTest[1535:3222637] client: found peer: Apple-Iphone6-1.3GMDyQ==
null
2016-01-08T16:57:06.624Z SendDataTCPServer.js: TCP/IP server is bound to port: 57012
2016-01-08 17:57:06.624 ThaliTest[1535:3,222637] client: found peer: Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:06.627 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:06.628 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5s-1.kFnM8A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:06.634Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:06.634Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:06.634Z SendDataConnector.js: do connect now
,2016-01-08 17:57:06.635 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:06.636 ThaliTest[1535:3222861] client session: connect
,2016-01-08 17:57:06.638 ThaliTest[1535:3222861] client session: stateChange:0->1 Apple-Iphone6-1.3GMDyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:07.746 ThaliTest[1535:3222637] client: lost peer: Apple-Iphone5s-1.kFnM8A==
2016-01-08 17:57:07.746 ThaliTest[1535:3222637] client session: onPeerLost: Apple-Iphone5s-1.kFnM8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.kFnM8A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:07.859 ThaliTest[1535:3222637] client: lost peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.860 ThaliTest[1535:3222637] client session: onPeerLost: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.860 ThaliTest[1535:3222637] client: fou,nd peer: Apple-Iphone6-1.g6FFQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.g6FFQA,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:07.873 ThaliTest[1535:3222637] client: found peer: Apple-IpadAir2-1.lYAIVQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.lYAIVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:08.003 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.kBkHjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kBkHjQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:08.804 ThaliTest[1535:3222637] client: lost peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.805 ThaliTest[1535:3222637] client session: onPeerLost: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.805 ThaliTest[1535:3222637] client sessio,n: onLinkFailure: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.805 ThaliTest[1535:3222637] client session: disconnect
2016-01-08 17:57:08.806 ThaliTest[1535:3222637] client session: stateChange:1->0 Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.807 Thali,Test[1535:3222637] client session: fireConnectCallback: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.807 ThaliTest[1535:3222637] jxcore: connect: fail: Peer disconnected
2016-01-08T16:57:08.812Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-08T16:57:08.812Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T16:57:08.813Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-08T16:57:13.816Z SendDataConnector.js: re-try now : Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:13.817Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:14.042 ThaliTest[1535:3222637] client: lost peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:14.043 ThaliTest[1535:3222637] client session: onPeerLost: Apple-Iphone5-1.vqNzbw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:18.820 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:18.821 ThaliTest[1535:3222861] jxcore: disconnect: fail
2016-01-08T16:57:18.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.3GMDyQ==
20,16-01-08T16:57:18.822Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.3GMDyQ== with availability status: true
,2016-01-08T16:57:18.823Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.3GMDyQ==
2016-01-08T16:57:18.823Z SendDataConnector.js: do connect now
,2016-01-08 17:57:18.824 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:18.825 ThaliTest[1535:3222861] client: connect: unreachable Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:18.826 ThaliTest[1535:3222861] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:18.827Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:18.828Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:18.828Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:23.839Z SendDataConnector.js: re-try now : Apple-Iphone6-1.3GMDyQ==
2016-01-08T16:57:23.840Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:28.841 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:28.842 ThaliTest[1535:3222861] jxcore: disconnect: fail
2016-01-08T16:57:28.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.3GMDyQ==
20,16-01-08T16:57:28.843Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.3GMDyQ== with availability status: true
2016-01-08T16:57:28.843Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:28.843Z SendDataConnector.js: do connect now
2016-01-08 17:57:28.844 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:28.845 ThaliTest[1535:3222861] client: connect: unreachable Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:28.846 ThaliTest[1535:3222861] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:28.847Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:28.847Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:28.848Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:33.850Z SendDataConnector.js: re-try now : Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:33.851Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:36.610 ThaliTest[1535:3222637] multipeer session: restart
,2016-01-08 17:57:36.668 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:36.672 ThaliTest[1535:3222637] client: found peer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:36.673 ThaliTest[1535:3222637] client: found peer:, Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:38.857 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:38.857 ThaliTest[1535:3222861] jxcore: disconnect: fail
2016-01-08T16:57:38.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.3GMDyQ==
20,16-01-08T16:57:38.858Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.3GMDyQ== with availability status: true
2016-01-08T16:57:38.859Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:38.859Z SendDataConnector.js: do connect now
2016-01-08 17:57:38.860 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:38.860 ThaliTest[1535:3222861] client: connect: unreachable Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:38.861 ThaliTest[1535:3222861] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:38.862Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T16:57:38.863Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:38.864Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 17:57:43.567 ThaliTest[1535:3222637] client: lost peer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:43.567 ThaliTest[1535:3222637] client session: onPeerLost: Apple-IpadAir2-1.lYAIVQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-,1.lYAIVQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:43.583 ThaliTest[1535:3222637] client: lost peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:43.583 ThaliTest[1535:3222637] client session: onPeerLost: Apple-Iphone5-1.kBkHjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kBkHjQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08T16:57:43.870Z SendDataConnector.js: re-try now : Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:43.871Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:44.507 ThaliTest[1535:3222637] client: lost peer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:44.507 ThaliTest[1535:3222637] client session: onPeerLost: Apple-Iphone6-1.g6FFQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.g,6FFQA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:48.583 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.kBkHjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kBkHjQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:48.874 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:48.875 ThaliTest[1535:3222861] jxcore: disconnect: fail
2016-01-08T16:57:48.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.3GMDyQ==
20,16-01-08T16:57:48.876Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.3GMDyQ== with availability status: true
2016-01-08T16:57:48.876Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.3GMDyQ==
,2016-01-08T16:57:48.877Z SendDataConnector.js: do connect now
2016-01-08 17:57:48.877 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:48.878 ThaliTest[1535:3222861] client: connect: unreachable Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:48.879 ThaliTest[1535:3222861] jxcore: connect: fail: Peer unreachable
2016-01-08T16:57:48.880Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T16:57:48.880Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-08T16:57:48.884Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 17:57:48.885 ThaliTest[1535:3222861] jxcore: disconnect
,2016-01-08 17:57:48.885 ThaliTest[1535:3222861] jxcore: disconnect: fail
2016-01-08T16:57:48.887Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.3GMDyQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:57:48.890Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:57:48.891Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:57:48.892Z SendDataConnector.js: do connect now
,2016-01-08 17:57:48.893 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:48.894 ThaliTest[1535:3222861] client session: connect
2016-01-08 17:57:48.894 ThaliTest[1535:3222861] client session: stateChange:0->1 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:57:49.186 ThaliTest[1535:3222637] client: found peer: Apple-Iphone6-1.g6FFQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.g6FFQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:50.692 ThaliTest[1535:3222637] client: found peer: Apple-IpadAir2-1.lYAIVQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.lYAIVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:52.708 ThaliTest[1535:3223563] client session: connected
2016-01-08 17:57:52.708 ThaliTest[1535:3223563] client session: stateChange:1->2 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:57:52.733 ThaliTest[1535:3223563] client session: fireConnectCallback: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:52.734 ThaliTest[1535:3223563] jxcore: connect: success
2016-01-08T16:57:52.735Z SendDataConnector.js: CLIENT connected to 5702,2, error: null
2016-01-08T16:57:52.736Z SendDataConnector.js: CLIENT starting client 
2016-01-08 17:57:52.740 ThaliTest[1535:3222637] client: relay established
2016-01-08 17:57:52.740 ThaliTest[1535:3222637] client: new accepted socket: 0x16471e60
,2016-01-08T16:57:52.755Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:57:53.255Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T16:57:53.305Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T16:57:53.363Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T16:57:53.376Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T16:57:53.388Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T16:57:53.426Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:57:53.426Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T16:57:53.427Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:57:53.427Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:53.428 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:53.428 ThaliTest[1535:3222861] client session: disconnectFromPeer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:53.428 ThaliTest[1535:3222861] client session: disconnect
2016-01-08 17:57:53.429 ThaliTest[1535:3222861] client session: stateChange:2->0 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:57:53.434 ThaliTest[1535:3222861] jxcore: disconnect: success
2016-01-08T16:57:53.434Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kBkHjQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1.g6FFQA==
2016-01-08T16:57:53.434Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.g6FFQA==
2016-01-08T16:57:53.435Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.g6FFQA==
2016-01-08T16:57:53.435Z SendDataConnector.j,s: do connect now
2016-01-08 17:57:53.435 ThaliTest[1535:3222861] jxcore: connect Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:53.435 ThaliTest[1535:3222861] client session: connect
2016-01-08 17:57:53.435 ThaliTest[1535:3222861] client session: stateChange:0->1 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:56.412 ThaliTest[1535:3223563] client session: connected
2016-01-08 17:57:56.412 ThaliTest[1535:3223563] client session: stateChange:1->2 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:56.444 ThaliTest[1535:3223563] client session: fireConnectCallback: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:56.444 ThaliTest[1535:3223563] jxcore: connect: success
,2016-01-08T16:57:56.446Z SendDataConnector.js: CLIENT connected to 57025, error: null
,2016-01-08T16:57:56.448Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:57:56.452 ThaliTest[1535:3222637] client: relay established
2016-01-08 17:57:56.453 ThaliTest[1535:3222637] client: new accepted socket: 0x163e5910
,2016-01-08T16:57:56.463Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:57:56.961Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T16:57:57.010Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T16:57:57.021Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T16:57:57.044Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T16:57:57.058Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T16:57:57.094Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:57:57.094Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:57:57.095Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:57:57.095Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:57.096 ThaliTest[1535:3222861] jxcore: disconnect
2016-01-08 17:57:57.096 ThaliTest[1535:3222861] client session: disconnectFromPeer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:57.096 ThaliTest[1535:3222861] client session: disconnect
20,16-01-08 17:57:57.096 ThaliTest[1535:3222861] client session: stateChange:2->0 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:57.102 ThaliTest[1535:3222861] jxcore: disconnect: success
2016-01-08T16:57:57.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.g6FFQA==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipad,Air2-1.lYAIVQ==
2016-01-08T16:57:57.103Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:57.103Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:57.103Z SendDataConnector.js: do connect now
2016-01-08 17:57:57.103 ThaliTest[1535:3222861] jxcore: connect Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:57.103 ThaliTest[1535:3222861] client session: connect
2016-01-08 17:57:57.103 ThaliTest[1535:3222861] client session: stateC,hange:0->1 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:58.669 ThaliTest[1535:3222637] multipeer session: reset timer
2016-01-08 17:57:58.669 ThaliTest[1535:3222637] multipeer session: stop timer
2016-01-08 17:57:58.669 ThaliTest[1535:3222637] multipeer session: start timer: 0x163cffa0
2016-01-08 17:57:58.670 ThaliTest[1535:3222637] server session: connect
,2016-01-08 17:57:58.670 ThaliTest[1535:3222637] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 17:57:58.681 ThaliTest[1535:3222637] server: accepting invitation Apple-Iphone6-1
,2016-01-08 17:57:59.005 ThaliTest[1535:3222637] multipeer session: reset timer
2016-01-08 17:57:59.005 ThaliTest[1535:3222637] multipeer session: stop timer
2016-01-08 17:57:59.005 ThaliTest[1535:3222637] multipeer session: start timer: 0x163cffa0
2016-,01-08 17:57:59.006 ThaliTest[1535:3222637] server session: connect
2016-01-08 17:57:59.006 ThaliTest[1535:3222637] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 17:57:59.022 ThaliTest[1535:3222637] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 17:57:59.066 ThaliTest[1535:3222637] multipeer session: reset timer
2016-01-08 17:57:59.067 ThaliTest[1535:3222637] multipeer session: stop timer
2016-01-08 17:57:59.067 ThaliTest[1535:3222637] multipeer session: start timer: 0x163cffa0
2016-,01-08 17:57:59.067 ThaliTest[1535:3222637] server session: connect
2016-01-08 17:57:59.067 ThaliTest[1535:3222637] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 17:57:59.077 ThaliTest[1535:3222637] server: accepting invitation Apple-Iphone5-1
,2016-01-08 17:58:01.103 ThaliTest[1535:3223705] client session: connected
,2016-01-08 17:58:01.104 ThaliTest[1535:3223705] client session: stateChange:1->2 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:58:01.113 ThaliTest[1535:3223705] client session: fireConnectCallback: Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:58:01.113 ThaliTest[1535:3223705] jxcore: connect: success
,2016-01-08T16:58:01.116Z SendDataConnector.js: CLIENT connected to 57028, error: null
,2016-01-08T16:58:01.117Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:01.122 ThaliTest[1535:3222637] client: relay established
,2016-01-08 17:58:01.122 ThaliTest[1535:3222637] client: new accepted socket: 0x164792a0
,2016-01-08T16:58:01.135Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 17:58:01.356 ThaliTest[1535:3223760] server session: connected
2016-01-08 17:58:01.356 ThaliTest[1535:3223760] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 17:58:01.384 ThaliTest[1535:3222637] server relay: connected (to port: 57012)
,2016-01-08T16:58:01.722Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:58:01.809Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T16:58:01.823Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T16:58:01.860Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T16:58:01.885Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T16:58:01.886Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T16:58:01.943Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-08T16:58:01.983Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-08T16:58:02.009Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T16:58:02.010Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:58:02.011Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:58:02.012Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:58:02.012Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:02.013 ThaliTest[1535:3222861] jxcore: disconnect
,2016-01-08 17:58:02.014 ThaliTest[1535:3222861] client session: disconnectFromPeer: Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:58:02.015 ThaliTest[1535:3222861] client session: disconnect
,2016-01-08 17:58:02.015 ThaliTest[1535:3222861] client session: stateChange:2->0 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:58:02.083 ThaliTest[1535:3223760] server session: connected
2016-01-08 17:58:02.084 ThaliTest[1535:3223760] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 17:58:02.086 ThaliTest[1535:3222861] jxcore: disconnect: success
,2016-01-08T16:58:02.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.lYAIVQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T16:58:02.102Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:58:02.102Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08T16:58:02.116Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:02.149 ThaliTest[1535:3222637] server relay: connected (to port: 57012)
,2016-01-08T16:58:02.153Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 17:58:02.217 ThaliTest[1535:3223760] server session: not connected Apple-Iphone6-1
,2016-01-08 17:58:02.807 ThaliTest[1535:3223705] server session: connected
2016-01-08 17:58:02.807 ThaliTest[1535:3223705] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 17:58:02.816 ThaliTest[1535:3222637] server relay: connected (to port: 57012)
2016-01-08T16:58:02.818Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:58:03.268Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-08T16:58:03.270Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T16:58:03.288Z SendDataTCPServer.js: TCP/IP server has received 11974 bytes of data
,2016-01-08T16:58:03.290Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-08T16:58:03.309Z SendDataTCPServer.js: TCP/IP server has received 16425 bytes of data
,2016-01-08T16:58:03.311Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-08T16:58:03.332Z SendDataTCPServer.js: TCP/IP server has received 18615 bytes of data
,2016-01-08T16:58:03.335Z SendDataTCPServer.js: TCP/IP server has received 20805 bytes of data
,2016-01-08T16:58:03.350Z SendDataTCPServer.js: TCP/IP server has received 25185 bytes of data
,2016-01-08T16:58:03.353Z SendDataTCPServer.js: TCP/IP server has received 25185 bytes of data
,2016-01-08T16:58:03.368Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
2016-01-08T16:58:03.370Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-08T16:58:03.425Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-08T16:58:03.439Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-08T16:58:03.474Z SendDataTCPServer.js: TCP/IP server has received 90885 bytes of data
,2016-01-08T16:58:03.482Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2016-01-08T16:58:03.496Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:03.605 ThaliTest[1535:3223705] server session: not connected Apple-IpadAir2-1
2016-01-08T16:58:03.610Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-08T16:58:03.711Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T16:58:03.725Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:03.833 ThaliTest[1535:3223705] server session: not connected Apple-Iphone5-1
,2016-01-08 17:58:29.068 ThaliTest[1535:3222637] multipeer session: restart
,2016-01-08 17:58:29.129 ThaliTest[1535:3222637] client: found peer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:58:29.129 ThaliTest[1535:3222637] client: found peer: Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:29.518 ThaliTest[1535:3222637] client: found peer: Apple-IpadAir2-1.lYAIVQ==
,teardown
,testSendData stopped
2016-01-08 17:58:37.415 ThaliTest[1535:3222861] jxcore: stopBroadcasting
,2016-01-08 17:58:37.415 ThaliTest[1535:3222861] THEMultipeerSession stopping peer
2016-01-08 17:58:37.416 ThaliTest[1535:3222861] multipeer session: stop timer
,2016-01-08 17:58:37.417 ThaliTest[1535:3222861] server session: disconnect
2016-01-08 17:58:37.418 ThaliTest[1535:3222861] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-08 17:58:37.424 ThaliTest[1535:3222861] server session: disconnect
2016-0,1-08 17:58:37.425 ThaliTest[1535:3222861] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 17:58:37.436 ThaliTest[1535:3222861] server session: disconnect
2016-01-08 17:58:37.438 ThaliTest[1535:3222861] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 17:58:37.557 ThaliTest[1535:3222861] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
