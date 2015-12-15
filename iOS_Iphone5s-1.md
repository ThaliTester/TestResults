#### Test 50650278cb112b9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D311C415-7CF6-48CA-A7BF-E575DDC7BD88/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D311C415-7CF6-48CA-A7BF-E575DDC7BD88/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1188155-EC31-4667-8B3A-B5E41169D564/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56164"
,(lldb)     command script import "/tmp/D311C415-7CF6-48CA-A7BF-E575DDC7BD88/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 04:20:34.133 ThaliTest[1030:1247418] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6A5A8BBA-BD60-40B4-AFE3-19594CBE6C41/Library/Cookies/Cookies.binarycookies
,2015-12-15 04:20:34.553 ThaliTest[1030:1247418] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 04:20:34.555 ThaliTest[1030:1247418] Multi-tasking -> Device: YES, App: YES
,2015-12-15 04:20:34.564 ThaliTest[1030:1247418] Unlimited access to network resources
,2015-12-15 04:20:34.576 ThaliTest[1030:1247418] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 04:20:42.725 ThaliTest[1030:1247418] Resetting plugins due to page load.
,2015-12-15 04:20:45.560 ThaliTest[1030:1247418] Finished load of: file:///var/mobile/Containers/Bundle/Application/B1188155-EC31-4667-8B3A-B5E41169D564/ThaliTest.app/www/index.html
,2015-12-15 04:20:45.780 ThaliTest[1030:1247418] JXcore Cordova plugin initializing
,2015-12-15 04:20:45.782 ThaliTest[1030:1247708] JXcore instance initializing
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
,2015-12-15 04:20:47.068 ThaliTest[1030:1247418] THREAD WARNING: ['JXcore'] took '83.140869' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 04:25:45.822 ThaliTest[1030:1247708] jxcore: startBroadcasting
,2015-12-15 04:25:45.843 ThaliTest[1030:1247708] server: starting Apple-Iphone5s-1_PT9749.bbnlcg==
,2015-12-15 04:25:45.844 ThaliTest[1030:1247708] multipeer session: start timer: 0x183d2790
2015-12-15 04:25:45.846 ThaliTest[1030:1247708] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9749
2015-12-15 04:25:45.846 ThaliTest[1030:1247708] jxcore,: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 04:25:46.024 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT1123.S9LZPw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-15 04:25:46.244 ThaliTest[1030:1247708] jxcore: stopBroadcasting
2015-12-15 04:25:46.245 ThaliTest[1030:1247708] THEMultipeerSession stopping peer
2015-12-15 04:25:46.246 ThaliTest[1030:1247708] multipeer session: stop timer
2015-12-15 04:25:46.,246 ThaliTest[1030:1247708] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
serverPort is 59184
,2015-12-15 04:25:46.315 ThaliTest[1030:1247708] jxcore: startBroadcasting
,2015-12-15 04:25:46.320 ThaliTest[1030:1247708] server: starting Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:25:46.321 ThaliTest[1030:1247708] multipeer session: start timer: 0x18482930
2015-12-15 04:25:46.321 ThaliTest[1030:1247708] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT9749
2015-12-15 04:25:46.321 ThaliTest[1030:1247708] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-15T03:25:46.326Z SendDataTCPServer.js: TCP/IP server is bound to port: 59184
,2015-12-15 04:25:46.343 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:25:46.349Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:46.349Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:46.350Z SendDataConnector.js: do connect now
,2015-12-15 04:25:46.352 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:46.352 ThaliTest[1030:1247708] client session: connect
2015-12-15 04:25:46.352 ThaliTest[1030:1247708] client session: stateChange:0->1 Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:46.474 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 04:25:46.895 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.mlJOKQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:47.575 ThaliTest[1030:1247418] client: lost peer: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.575 ThaliTest[1030:1247418] client session: onPeerLost: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.576 ThaliTest[1030:1247418], client session: onLinkFailure: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.577 ThaliTest[1030:1247418] client session: disconnect
2015-12-15 04:25:47.577 ThaliTest[1030:1247418] client session: stateChange:1->0 Apple-Iphone6-1_PT1123.S9LZPw==
2,015-12-15 04:25:47.578 ThaliTest[1030:1247418] client session: fireConnectCallback: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.578 ThaliTest[1030:1247418] jxcore: connect: fail: Peer disconnected
2015-12-15 04:25:47.579 ThaliTest[1030:1247418] c,lient: lost peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15 04:25:47.579 ThaliTest[1030:1247418] client session: onPeerLost: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15T03:25:47.580Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected,
2015-12-15T03:25:47.586Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T03:25:47.587Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 04:25:47.877 ThaliTest[1030:1247418] client: lost peer: Apple-Iphone5-1_PT9128.mlJOKQ==
2015-12-15 04:25:47.878 ThaliTest[1030:1247418] client session: onPeerLost: Apple-Iphone5-1_PT9128.mlJOKQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 04:25:48.010 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1123.uhofxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-15 04:25:48.056 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.h41t3A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 04:25:48.839 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.H9FQ7Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15T03:25:52.595Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:52.596Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:56.900 ThaliTest[1030:1247418] multipeer session: reset timer
2015-12-15 04:25:56.901 ThaliTest[1030:1247418] multipeer session: stop timer
2015-12-15 04:25:56.901 ThaliTest[1030:1247418] multipeer session: start timer: 0x18482930
2015-,12-15 04:25:56.902 ThaliTest[1030:1247418] server session: connect
2015-12-15 04:25:56.902 ThaliTest[1030:1247418] server session: stateChange:0->1 Apple-Iphone5-1_PT9128
,2015-12-15 04:25:56.913 ThaliTest[1030:1247418] server: accepting invitation Apple-Iphone5-1_PT9128
,2015-12-15 04:25:57.598 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:25:57.598 ThaliTest[1030:1247708] jxcore: disconnect: fail
2015-12-15T03:25:57.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZP,w==
2015-12-15T03:25:57.600Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:25:57.600Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:57.600Z SendDataConnector.js: do connect now
2015-12-15 04:25:57.602 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:57.602 ThaliTest[1030:1247708] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:57.604 ThaliTest[1030:1247708] jxcore: connect: fail: Peer unreachable
2015-12-15T03:25:57.605Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:25:57.605Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2015-12-15T03:25:57.606Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:02.613Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:26:02.614Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:02.697 ThaliTest[1030:1248352] server session: connected
2015-12-15 04:26:02.697 ThaliTest[1030:1248352] server session: stateChange:1->2 Apple-Iphone5-1_PT9128
,2015-12-15 04:26:02.711 ThaliTest[1030:1247418] server relay: connected (to port: 59184)
2015-12-15T03:26:02.716Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:03.267Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-15T03:26:03.283Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-15T03:26:03.387Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-15T03:26:03.405Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-15T03:26:03.425Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-15T03:26:03.441Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-15T03:26:03.647Z SendDataTCPServer.js: TCP/IP server has received 93886 bytes of data
,2015-12-15T03:26:03.661Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:03.744 ThaliTest[1030:1248347] server session: not connected Apple-Iphone5-1_PT9128
,2015-12-15 04:26:07.615 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:26:07.615 ThaliTest[1030:1247708] jxcore: disconnect: fail
2015-12-15T03:26:07.616Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZP,w==
2015-12-15T03:26:07.616Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:07.617Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:07.617Z SendDataConnector.js: do connect now
2015-12-15 04:26:07.618 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:07.619 ThaliTest[1030:1247708] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:07.619 ThaliTest[1030:1247708] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:26:07.620Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:26:07.621Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T03:26:07.622Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:12.629Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:12.630Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:17.633 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:26:17.633 ThaliTest[1030:1247708] jxcore: disconnect: fail
2015-12-15T03:26:17.634Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZP,w==
2015-12-15T03:26:17.634Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:17.635Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
2,015-12-15T03:26:17.635Z SendDataConnector.js: do connect now
,2015-12-15 04:26:17.636 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:17.636 ThaliTest[1030:1247708] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:17.637 ThaliTest[1030:1247708] jxcore: connect: fail: Peer unreachable
,2015-12-15T03:26:17.638Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T03:26:17.639Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T03:26:17.640Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:22.650Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:22.650Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:26.903 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:26:26.944 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:26:26.944 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:26.945 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:27.670 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:26:27.671 ThaliTest[1030:1247708] jxcore: disconnect: fail
2015-12-15T03:26:27.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZP,w==
2015-12-15T03:26:27.674Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:27.674Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
2,015-12-15T03:26:27.675Z SendDataConnector.js: do connect now
,2015-12-15 04:26:27.676 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:27.678 ThaliTest[1030:1247708] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:27.679 ThaliTest[1030:1247708] j,xcore: connect: fail: Peer unreachable
2015-12-15T03:26:27.680Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:26:27.680Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-15T03:26:27.694Z SendDataConnector.js: CLIENT Stop now
2015-12-15 04:26:27.695 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:26:27.696 ThaliTest[1030:1247708] jxcore: disconnect: fail
2015-12-15T03:26:27.697Z SendDataConnector.js: Mob,ile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15T03:26:27.702Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15T03:26:27.706Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15T03:26:27.706Z SendDataConnector.js:, do connect now
,2015-12-15 04:26:27.708 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:27.709 ThaliTest[1030:1247708] client session: connect
2015-12-15 04:26:27.710 ThaliTest[1030:1247708] client session: stateChange:0->1 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:31.147 ThaliTest[1030:1248347] client session: connected
2015-12-15 04:26:31.148 ThaliTest[1030:1248347] client session: stateChange:1->2 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:31.212 ThaliTest[1030:1248445] client session: fireConnectCallback: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:26:31.214 ThaliTest[1030:1248445] jxcore: connect: success
2015-12-15T03:26:31.216Z SendDataConnector.js: CLIENT connected ,to 59191, error: null
2015-12-15T03:26:31.216Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:31.221 ThaliTest[1030:1247418] client: relay established
2015-12-15 04:26:31.221 ThaliTest[1030:1247418] client: new accepted socket: 0x183e81c0
,2015-12-15T03:26:31.237Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15 04:26:31.339 ThaliTest[1030:1247418] multipeer session: reset timer
2015-12-15 04:26:31.340 ThaliTest[1030:1247418] multipeer session: stop timer
2015-12-15 04:26:31.340 ThaliTest[1030:1247418] multipeer session: start timer: 0x18482930
2015-,12-15 04:26:31.341 ThaliTest[1030:1247418] server session: connect
2015-12-15 04:26:31.341 ThaliTest[1030:1247418] server session: stateChange:0->1 Apple-Iphone6-1_PT1123
,2015-12-15 04:26:31.352 ThaliTest[1030:1247418] server: accepting invitation Apple-Iphone6-1_PT1123
,2015-12-15T03:26:32.279Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-15T03:26:32.298Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-15T03:26:32.312Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:32.312Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:32.314Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:32.314Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:32.317 ThaliTest[1030:1247708] jxcore: disconnect
,2015-12-15 04:26:32.319 ThaliTest[1030:1247708] client session: disconnectFromPeer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:32.320 ThaliTest[1030:1247708] client session: disconnect
,2015-12-15 04:26:32.321 ThaliTest[1030:1247708] client session: stateChange:2->0 Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:26:32.336 ThaliTest[1030:1247708] jxcore: disconnect: success
,2015-12-15T03:26:32.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.uhofxg==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:32.348Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:32.349Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:32.350Z SendDataConnector.js: do connect now
,2015-12-15 04:26:32.351 ThaliTest[1030:1247708] jxcore: connect Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:32.352 ThaliTest[1030:1247708] client session: connect
,2015-12-15 04:26:32.353 ThaliTest[1030:1247708] client session: stateChange:0->1 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:33.900 ThaliTest[1030:1248444] server session: connected
2015-12-15 04:26:33.901 ThaliTest[1030:1248444] server session: stateChange:1->2 Apple-Iphone6-1_PT1123
,2015-12-15 04:26:33.931 ThaliTest[1030:1247418] server relay: connected (to port: 59184)
,2015-12-15T03:26:33.940Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:34.294Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-15T03:26:34.313Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-15T03:26:34.329Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-15T03:26:34.344Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-15T03:26:34.362Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-15T03:26:34.377Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-15T03:26:34.392Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:34.492 ThaliTest[1030:1248446] server session: not connected Apple-Iphone6-1_PT1123
,2015-12-15 04:26:35.532 ThaliTest[1030:1247418] multipeer session: reset timer
2015-12-15 04:26:35.534 ThaliTest[1030:1247418] multipeer session: stop timer
2015-12-15 04:26:35.534 ThaliTest[1030:1247418] multipeer session: start timer: 0x18482930
2015-,12-15 04:26:35.536 ThaliTest[1030:1247418] server session: connect
2015-12-15 04:26:35.536 ThaliTest[1030:1247418] server session: stateChange:0->1 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:35.545 ThaliTest[1030:1247418] server: accepting invitation Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:35.576 ThaliTest[1030:1248445] client session: connected
2015-12-15 04:26:35.576 ThaliTest[1030:1248445] client session: stateChange:1->2 Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:35.587 ThaliTest[1030:1248445] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:35.587 ThaliTest[1030:1248445] jxcore: connect: success
,2015-12-15T03:26:35.590Z SendDataConnector.js: CLIENT connected to 59195, error: null
2015-12-15T03:26:35.590Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:35.602 ThaliTest[1030:1247418] client: relay established
2015-12-15 04:26:35.602 ThaliTest[1030:1247418] client: new accepted socket: 0x183efd30
,2015-12-15T03:26:35.614Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:35.990Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-15T03:26:36.004Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-15T03:26:36.052Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:36.053Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:36.053Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:36.053Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:36.054 ThaliTest[1030:1247708] jxcore: disconnect
,2015-12-15 04:26:36.055 ThaliTest[1030:1247708] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:36.055 ThaliTest[1030:1247708] client session: disconnect
,2015-12-15 04:26:36.056 ThaliTest[1030:1247708] client session: stateChange:2->0 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:36.124 ThaliTest[1030:1247708] jxcore: disconnect: success
,2015-12-15T03:26:36.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7023.h41t3A==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15T03:26:36.126Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15T03:26:36.126Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15T03:26:36.127Z SendDataConnector.js: do connect now
,2015-12-15 04:26:36.127 ThaliTest[1030:1247708] jxcore: connect Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:36.128 ThaliTest[1030:1247708] client session: connect
,2015-12-15 04:26:36.128 ThaliTest[1030:1247708] client session: stateChange:0->1 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:38.555 ThaliTest[1030:1248443] server session: connected
,2015-12-15 04:26:38.555 ThaliTest[1030:1248443] server session: stateChange:1->2 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:38.565 ThaliTest[1030:1247418] server relay: connected (to port: 59184)
,2015-12-15T03:26:38.571Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:26:39.015Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-15T03:26:39.031Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-15T03:26:39.047Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-15T03:26:39.090Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
2015-12-15T03:26:39.109Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-15T03:26:39.126Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:39.592 ThaliTest[1030:1248446] client session: connected
2015-12-15 04:26:39.592 ThaliTest[1030:1248446] client session: stateChange:1->2 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:39.607 ThaliTest[1030:1248446] client session: fireConnectCallback: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:39.612 ThaliTest[1030:1248446] jxcore: connect: success
2015-12-15T03:26:39.613Z SendDataConnector.js: CLIENT connected ,to 59200, error: null
2015-12-15T03:26:39.614Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:39.619 ThaliTest[1030:1247418] client: relay established
2015-12-15 04:26:39.622 ThaliTest[1030:1247418] client: new accepted socket: 0x1835a390
2015-12-15 04:26:39.624 ThaliTest[1030:1248443] server session: not connected Apple-IpadAir2-1_PT7023
,2015-12-15T03:26:39.631Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:40.126Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T03:26:40.152Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:40.152Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:40.153Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:40.153Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:40.154 ThaliTest[1030:1247708] jxcore: disconnect
2015-12-15 04:26:40.154 ThaliTest[1030:1247708] client session: disconnectFromPeer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:40.154 ThaliTest[1030:1247708] client session: disconnect
2015-12-15 04:26:40.154 ThaliTest[1030:1247708] client session: stateChange:2->0 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:40.161 ThaliTest[1030:1247708] jxcore: disconnect: success
2015-12-15T03:26:40.161Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-15T03:26:40.165Z SendDataConnector.js: CLIENT Stop now
2015-12-15T03:26:40.165Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:27:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:27:05.597 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:27:05.598 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:27:05.599 ThaliTest[1030:1247418] client,: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:27:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:27:35.598 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:27:35.599 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:27:35.602 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:28:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:28:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:28:35.595 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:28:35.595 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:28:35.596 ThaliTest[1030:1247418] client,: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:29:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:29:05.861 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:29:05.862 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:29:05.862 ThaliTest[1030:1247418] client,: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:29:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:30:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:30:05.586 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:30:05.995 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:30:09.742 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:30:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:31:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:31:05.586 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:31:05.592 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:31:05.592 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:31:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:31:35.593 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:31:35.594 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:31:35.739 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:32:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:32:05.589 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:32:05.589 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:32:05.602 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:32:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:32:35.579 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:32:36.271 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:32:38.232 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:33:05.536 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:33:35.537 ThaliTest[1030:1247418] multipeer session: restart
,Connected to the server!
,2015-12-15 04:33:42.078 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:33:45.364 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:33:47.839 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:34:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:34:05.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:34:05.594 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:34:05.595 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:34:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:34:35.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:34:35.932 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:34:35.933 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:35:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:35:05.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:05.591 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:35:05.594 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:35:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:35:35.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:35:35.591 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:35.592 ThaliTest[1030:1247418] client,: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:36:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:36:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:36:35.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:36:35.594 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:36:35.594 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:37:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:37:05.589 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:37:05.589 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:37:05.592 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:37:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:38:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:38:05.588 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:38:05.749 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:38:05.749 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:38:35.536 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:39:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:39:05.587 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:39:05.588 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:39:05.590 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:39:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:39:35.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:39:35.594 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:39:35.597 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:40:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:40:06.373 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:40:06.377 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:40:06.378 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:40:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:40:35.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:40:35.599 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:40:35.599 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:41:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:41:05.591 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:41:05.592 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:41:05.592 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:41:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:41:35.586 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:41:35.588 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:41:35.588 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:42:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:42:06.313 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:42:06.321 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:42:06.321 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:42:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:42:35.588 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:42:35.589 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:42:35.591 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:43:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:43:05.591 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:43:05.592 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:43:05.592 ThaliTest[1030:1247418] client,: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:43:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:43:35.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:43:35.685 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:43:35.685 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:44:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:44:05.590 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:44:05.591 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:44:05.603 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:44:35.536 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:44:35.588 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:44:35.588 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:44:35.599 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:45:05.536 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:45:05.583 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:45:05.589 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:45:05.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:45:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:46:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:46:05.589 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:46:05.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
,2015-12-15 04:46:05.594 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:46:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:46:35.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:46:35.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:46:35.594 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:47:05.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:47:35.537 ThaliTest[1030:1247418] multipeer session: restart
,2015-12-15 04:47:35.592 ThaliTest[1030:1247418] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:47:35.593 ThaliTest[1030:1247418] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:47:35.595 ThaliTest[1030:1247418] clien,t: found peer: Apple-Iphone6-1_PT1123.uhofxg==

```
