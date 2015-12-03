#### Test 506502782b2305a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6C3C64AE-6DE0-4052-8DBE-9981B94865FD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6C3C64AE-6DE0-4052-8DBE-9981B94865FD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782b2305a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/67AEBF2E-6CCD-4498-9584-67E9B24686FE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60114"
,(lldb)     command script import "/tmp/6C3C64AE-6DE0-4052-8DBE-9981B94865FD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 01:40:25.187 ThaliTest[1859:2899852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8F942462-9E61-460E-86A7-D0C405116686/Library/Cookies/Cookies.binarycookies
,2015-12-03 01:40:25.475 ThaliTest[1859:2899852] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 01:40:25.476 ThaliTest[1859:2899852] Multi-tasking -> Device: YES, App: YES
,2015-12-03 01:40:25.481 ThaliTest[1859:2899852] Unlimited access to network resources
,2015-12-03 01:40:25.487 ThaliTest[1859:2899852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 01:40:29.697 ThaliTest[1859:2899852] Resetting plugins due to page load.
,2015-12-03 01:40:30.972 ThaliTest[1859:2899852] Finished load of: file:///var/mobile/Containers/Bundle/Application/67AEBF2E-6CCD-4498-9584-67E9B24686FE/ThaliTest.app/www/index.html
,2015-12-03 01:40:31.117 ThaliTest[1859:2899852] JXcore Cordova plugin initializing
,2015-12-03 01:40:31.118 ThaliTest[1859:2900030] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
Coordinator is now connected to the server!
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testFindPeers.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5,
     peerCount: 4 },
  addressList: [] }
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-03 01:42:24.211 ThaliTest[1859:2900030] jxcore: startBroadcasting
,2015-12-03 01:42:24.218 ThaliTest[1859:2900030] server: starting Apple-IpadAir2-1_PT7682.e4J7ag==
,2015-12-03 01:42:24.219 ThaliTest[1859:2900030] multipeer session: start timer: 0x14734460
2015-12-03 01:42:24.219 ThaliTest[1859:2900030] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7682
,2015-12-03 01:42:24.220 ThaliTest[1859:2900030] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03 01:42:24.432 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT2613.bcJOyQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7682","time":223,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerAvailable":true,"time":222}]}
,peersList : 100% : 222 ms, 99% : 222 ms, 95 : 222 ms, 90% : 222 ms.
,Result count 1, range 222 ms to  222 ms.
,2015-12-03 01:42:24.783 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
,CoordinatorConnector-debug: stop:undefined
,stop tests now !
stop current!
testFindPeers stopped
2015-12-03 01:42:25.122 ThaliTest[1859:2900030] jxcore: stopBroadcasting
2015-12-03 01:42:25.123 ThaliTest[1859:2900030] THEMultipeerSession stopping peer
2015-12-03 01:42:25.123 ThaliTest[1859:2900030] multipeer session: stop timer
,2015-12-03 01:42:25.123 ThaliTest[1859:2900030] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,CoordinatorConnector-debug: start:[object Object]
,{ testName: 'testSendData.js',
  testData: 
   { servertimeout: 1200000,
     timeout: 1000000,
     rounds: 1,
     dataTimeout: 10000,
     dataAmount: 100000,
     conReTryTimeout: 5000,
     conReTryCount: 5,
     peerCount: 4 },
  addressList: [] }
,testSendData created [object Object], bt-address length : 0
,check server
,serverPort is 50035
,2015-12-03 01:42:25.170 ThaliTest[1859:2900030] jxcore: startBroadcasting
,2015-12-03 01:42:25.172 ThaliTest[1859:2900030] server: starting Apple-IpadAir2-1_PT7682.INb6UQ==
,2015-12-03 01:42:25.172 ThaliTest[1859:2900030] multipeer session: start timer: 0x147338c0
2015-12-03 01:42:25.173 ThaliTest[1859:2900030] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7682
2015-12-03 01:42:25.173 ThaliTest[1859:2900030] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-03T00:42:25.175Z SendDataTCPServer.js: TCP/IP server is bound to port: 50035
,2015-12-03 01:42:25.178 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.bcJOyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
device[1]: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:25.180 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03T00:42:25.180Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:25.181Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:25.181Z SendDataConnector.js: do connect now
,2015-12-03 01:42:25.182 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:25.183 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:42:25.183 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.bcJOyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:25.442 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796./19b4A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796./19b4A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:26.448 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5-1_PT8796./19b4A==
2015-12-03 01:42:26.448 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5-1_PT8796./19b4A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796./19b4A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-03 01:42:26.450 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8796.xJ9gmA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-03 01:42:26.870 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:27.376 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client session: stateChange:1->0 Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:28.774 ThaliTest[1859:2899852] jxcore: connect: fail: Peer disconnected
2015-12-03T00:42:28.775Z SendDataConnector.js: CL,IENT connected to 0, error: Peer disconnected
2015-12-03T00:42:28.775Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T00:42:28.775Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT2613.bcJOyQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:42:30.572 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.8qCfew==
2015-12-03 01:42:30.572 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.8qCfew==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.8qCfew==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-03T00:42:33.781Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:33.782Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:38.790 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:42:38.790 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:42:38.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOy,Q==
2015-12-03T00:42:38.790Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:42:38.790Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2,015-12-03T00:42:38.790Z SendDataConnector.js: do connect now
2015-12-03 01:42:38.791 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:38.791 ThaliTest[1859:2900030] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:38.791 ThaliTest[1859:2900030] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:38.791Z SendDataConnector.js: CLIENT con,nected to 0, error: Peer unreachable
2015-12-03T00:42:38.791Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:38.792Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:43.796Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:43.797Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:48.799 ThaliTest[1859:2900030] jxcore: disconnect
,2015-12-03 01:42:48.799 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:42:48.800Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:42:48.800Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:42:48.800Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:48.800Z SendDataConnector.js: do connect now
2015-12-03 01:42:48.800 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:48.801 ThaliTest[1859:2900030] client: connect: unreachable Apple-Iphone6-1_PT2613.bc,JOyQ==
2015-12-03 01:42:48.801 ThaliTest[1859:2900030] jxcore: connect: fail: Peer unreachable
2015-12-03T00:42:48.801Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:48.801Z SendDataConnector.js: CLIENT Can not Co,nnect: Peer unreachable
2015-12-03T00:42:48.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:42:53.812Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:53.813Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:42:55.173 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:42:55.185 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:42:55.185 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:42:55.186 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:42:58.814 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:42:58.814 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:42:58.814Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:58.815Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:42:58.815Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:42:58.815Z SendDataConnector.js: do connect now
,2015-12-03 01:42:58.815 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:58.815 ThaliTest[1859:2900030] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:42:58.815 ThaliTest[1859:2900030] j,xcore: connect: fail: Peer unreachable
2015-12-03T00:42:58.815Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:42:58.816Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-03T00:42:58.816Z SendDat,aConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:03.824Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03T00:43:03.824Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:43:04.773 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:04.773 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:04.773 ThaliTest[1859:2899852], client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:43:04.773 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-03 01:43:08.829 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:43:08.829 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:43:08.829Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03T00:43:08.830Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT2613.bcJOyQ== with availability status: true
2015-12-03T00:43:08.830Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.bcJOyQ==
2015-1,2-03T00:43:08.830Z SendDataConnector.js: do connect now
,2015-12-03 01:43:08.830 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.bcJOyQ==
,2015-12-03 01:43:08.830 ThaliTest[1859:2900030] client: connect: unreachable Apple-Iphone6-1_PT2613.bcJOyQ==
2015-12-03 01:43:08.831 ThaliTest[1859:2900030] jxcore: connect: fail: Peer unreachable
,2015-12-03T00:43:08.831Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-03T00:43:08.831Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:43:08.832Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 01:43:08.833 ThaliTest[1859:2900030] jxcore: disconnect
,2015-12-03 01:43:08.833 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:43:08.833Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.bcJOyQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.834Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.834Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03T00:43:08.835Z SendDataConnector.js: do connect now
,2015-12-03 01:43:08.835 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:08.835 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:43:08.835 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:09.020 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
2015-12-03 01:43:09.022 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 01:43:11.217 ThaliTest[1859:2900396] client session: connected
2015-12-03 01:43:11.217 ThaliTest[1859:2900396] client session: stateChange:1->2 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:11.243 ThaliTest[1859:2900396] client session: fireConnectCallback: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:11.243 ThaliTest[1859:2900396] jxcore: connect: success
2015-12-03T00:43:11.244Z SendDataConnector.js: CLIENT connected to 50039, error: null
2015-12-03T00:43:11.244Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:11.245 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:43:11.246 ThaliTest[1859:2899852] client: new accepted socket: 0x1630c580
,2015-12-03T00:43:11.259Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:11.515Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T00:43:11.515Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
oneRoundDownNow:2
,2015-12-03T00:43:11.516Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:43:11.516Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:43:11.517 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:43:11.517 ThaliTest[1859:2900030] client session: disconnectFromPeer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:11.517 ThaliTest[1859:2900030] client session: disconnect
2015-12-03 01:43:11.518 ThaliTest[1859:2900030] client session: stateChange:2->0 Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:43:11.521 ThaliTest[1859:2900030] jxcore: disconnect: success
2015-12-03T00:43:11.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8796.xJ9gmA==
---- round done--------
device[3]: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:11.522Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:11.522Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:11.522Z SendDataConn,ector.js: do connect now
2015-12-03 01:43:11.522 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:11.522 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:43:11.522 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:14.093 ThaliTest[1859:2900400] client session: connected
,2015-12-03 01:43:14.093 ThaliTest[1859:2900400] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:14.100 ThaliTest[1859:2900415] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:14.101 ThaliTest[1859:2900415] jxcore: connect: success
2015-12-03T00:43:14.101Z SendDataConnector.js: CLIENT connected ,to 50043, error: null
2015-12-03T00:43:14.101Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:14.103 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:43:14.103 ThaliTest[1859:2899852] client: new accepted socket: 0x1630fe40
,2015-12-03T00:43:14.115Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:43:14.348Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T00:43:14.361Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:43:14.386Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:43:14.774 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:43:14.774 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:43:14.775 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:43:14.775 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:43:14.775 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:14.777 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:17.132 ThaliTest[1859:2900359] server session: connected
2015-12-03 01:43:17.132 ThaliTest[1859:2900359] server session: stateChange:1->2 Apple-Iphone5s-1_PT5704
,2015-12-03 01:43:17.146 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:43:17.148Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:43:17.429Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-03T00:43:17.442Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-03T00:43:17.507Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:43:17.574 ThaliTest[1859:2900415] server session: not connected Apple-Iphone5s-1_PT5704
,2015-12-03T00:43:24.394Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:43:24.394Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:24.394Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:43:24.395Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:24.395Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client: socket closed
,2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client relay: 0x1630fe40 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:24.396 ThaliTes,t[1859:2899852] client session: disconnect
2015-12-03 01:43:24.396 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:24.399 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:29.400Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:29.400Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:34.402 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:43:34.402 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:43:34.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:34.403Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: ,true
2015-12-03T00:43:34.403Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:34.403Z SendDataConnector.js: do connect now
,2015-12-03 01:43:34.403 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:34.404 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:43:34.404 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:38.465 ThaliTest[1859:2900417] client session: connected
2015-12-03 01:43:38.465 ThaliTest[1859:2900417] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:38.472 ThaliTest[1859:2900359] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:38.472 ThaliTest[1859:2900359] jxcore: connect: success
,2015-12-03T00:43:38.473Z SendDataConnector.js: CLIENT connected to 50048, error: null
,2015-12-03T00:43:38.474Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:43:38.475 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:43:38.475 ThaliTest[1859:2899852] client: new accepted socket: 0x1645f650
,2015-12-03T00:43:38.488Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:43:44.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:43:44.789 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:43:44.789 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:43:44.789 ThaliTest[1859:2899852] clien,t: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:48.511Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:43:48.512Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:43:48.512Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:43:48.512Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:43:48.512Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client: socket closed
,2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client relay: 0x1645f650 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client session: onLinkFailure:, Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:48.513 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:43:48.514 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:48.516 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:53.514Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:53.514Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:43:58.517 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:43:58.517 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:43:58.517Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:43:58.518Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
2015-12-03T00:43:58.518Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:43:58.518Z SendDataConnector.js: do connect now
,2015-12-03 01:43:58.518 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:43:58.519 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:43:58.519 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:01.823 ThaliTest[1859:2900490] client session: connected
2015-12-03 01:44:01.823 ThaliTest[1859:2900490] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:01.844 ThaliTest[1859:2900520] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:01.844 ThaliTest[1859:2900520] jxcore: connect: success
2015-12-03T00:44:01.844Z SendDataConnector.js: CLIENT connected to 50053, error: null
2015-12-03T00:44:01.844Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:01.845 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:44:01.846 ThaliTest[1859:2899852] client: new accepted socket: 0x16462ac0
,2015-12-03T00:44:01.859Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:44:11.885Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:11.885Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:44:11.886Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:44:11.886Z SendDataConnector.js: tryAgain afer: 5000 ms.
2015-12-03T00:44:11.887Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:11.887 ThaliTest[1859:2899852] client: socket closed
2015-12-03 01:44:11.887 ThaliTest[1859:2899852] client relay: socket disconnected
,2015-12-03 01:44:11.887 ThaliTest[1859:2899852] client relay: 0x16462ac0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2015-12-03 01:44:11.888 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:11.888 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:11.888 ThaliTes,t[1859:2899852] client session: disconnect
2015-12-03 01:44:11.888 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:11.890 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:14.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:44:14.786 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:14.786 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:44:14.786 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:16.892Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:16.892Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:21.898 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:44:21.898 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:44:21.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2p,w==
2015-12-03T00:44:21.898Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
2015-12-03T00:44:21.899Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:44:21.899Z SendDataConnector.js: do connect now
2015-12-03 01:44:21.899 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:21.899 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:44:21.899 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:24.684 ThaliTest[1859:2900579] client session: connected
2015-12-03 01:44:24.684 ThaliTest[1859:2900579] client session: stateChange:1->2 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:24.696 ThaliTest[1859:2900576] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:24.696 ThaliTest[1859:2900576] jxcore: connect: success
2015-12-03T00:44:24.696Z SendDataConnector.js: CLIENT connected to 50058, error: null
2015-12-03T00:44:24.696Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:44:24.697 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:44:24.698 ThaliTest[1859:2899852] client: new accepted socket: 0x146e4bc0
,2015-12-03T00:44:24.710Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:44:34.734Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:44:34.734Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:44:34.734Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:44:34.735Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:44:34.735Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:44:34.735 ThaliTest[1859:2899852] client: socket closed
2015-12-03 01:44:34.736 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:44:34.736 ThaliTest[1859:2899852] client relay: 0x146e4bc0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:44:34.736 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone6-1_PT2613.ais2pw==
2015-12,-03 01:44:34.736 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:34.736 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:44:34.736 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:34.738 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:44:39.743Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:44:39.743Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:44.747 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:44:44.747 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:44:44.747Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2p,w==
2015-12-03T00:44:44.747Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT2613.ais2pw== with availability status: true
2015-12-03T00:44:44.747Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03T00:44:44.747Z SendDataConnector.js: do connect now
2015-12-03 01:44:44.748 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:44:44.748 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:44:44.748 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:44.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:44:44.789 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:44:44.789 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:44:44.790 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:01.531 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:01.531 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:01.531 ThaliTest[1859:2899852], client session: onLinkFailure: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:01.531 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:45:01.531 ThaliTest[1859:2899852] client session: stateChange:1->0 Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:01.532 ThaliTest[1859:2899852] client session: fireConnectCallback: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:01.532 ThaliTest[1859:2899852] jxcore: connect: fail: Peer disconnected
2015-12-03T00:45:01.532Z SendDataConnector.js: CL,IENT connected to 0, error: Peer disconnected
2015-12-03T00:45:01.532Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
oneRoundDownNow
oneRoundDownNow:2
2015-12-03T00:45:01.532Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:45:01,.533Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03 01:45:01.534 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:45:01.534 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:45:01.534Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT2613.ais2pw==
---- round done--------
device[4]: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:01.534Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:01.535Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:01.535Z SendDataConnector.js: do connect now
,2015-12-03 01:45:01.535 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:01.535 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:45:01.535 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:45:03.265 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:45:05.816 ThaliTest[1859:2900672] client session: connected
2015-12-03 01:45:05.816 ThaliTest[1859:2900672] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:05.868 ThaliTest[1859:2900665] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:05.868 ThaliTest[1859:2900665] jxcore: connect: success
2015-12-03T00:45:05.869Z SendDataConnector.js: CLIENT connected to 50064, error: null
2015-12-03T00:45:05.869Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:05.870 ThaliTest[1859:2899852] client: relay established
,2015-12-03 01:45:05.870 ThaliTest[1859:2899852] client: new accepted socket: 0x147213b0
,2015-12-03T00:45:05.883Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T00:45:06.105Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-03T00:45:06.131Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-03T00:45:06.144Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T00:45:06.206Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-03 01:45:14.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:45:15.059 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:15.060 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:45:15.060 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03T00:45:16.211Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:45:16.212Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:16.212Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:16.212Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:16.213Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:16.213 ThaliTest[1859:2899852] client: socket closed
2015-12-03 01:45:16.213 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:45:16.213 ThaliTest[1859:2899852] client relay: 0x147213b0 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:45:16.213 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-1,2-03 01:45:16.214 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:16.214 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:45:16.214 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:16.216 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:21.219Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:21.219Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:26.221 ThaliTest[1859:2900030] jxcore: disconnect
,2015-12-03 01:45:26.221 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:45:26.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:26.222Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
,2015-12-03T00:45:26.222Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:26.222Z SendDataConnector.js: do connect now
,2015-12-03 01:45:26.223 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:26.223 ThaliTest[1859:2900030] client session: connect
,2015-12-03 01:45:26.223 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:29.562 ThaliTest[1859:2900665] client session: connected
2015-12-03 01:45:29.562 ThaliTest[1859:2900665] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:29.592 ThaliTest[1859:2900714] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:29.592 ThaliTest[1859:2900714] jxcore: connect: success
2015-12-03T00:45:29.593Z SendDataConnector.js: CLIENT connected to 50069, error: null
2015-12-03T00:45:29.593Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:29.594 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:45:29.594 ThaliTest[1859:2899852] client: new accepted socket: 0x1645c800
,2015-12-03T00:45:29.607Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:45:39.631Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:45:39.632Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:45:39.632Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:45:39.632Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:45:39.633Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:45:39.633 ThaliTest[1859:2899852] client: socket closed
,2015-12-03 01:45:39.633 ThaliTest[1859:2899852] client relay: socket disconnected
,2015-12-03 01:45:39.633 ThaliTest[1859:2899852] client relay: 0x1645c800 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:45:39.634 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:39.634 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:39.634 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:45:39.634 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:39.636 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:45:44.639Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:44.639Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:44.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:45:44.787 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:45:44.787 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:45:44.787 ThaliTest[1859:2899852] client,: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:49.641 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:45:49.642 ThaliTest[1859:2900030] jxcore: disconnect: fail
,2015-12-03T00:45:49.642Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:49.642Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:45:49.642Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:45:49.642Z SendDataConnector.js: do connect now
,2015-12-03 01:45:49.643 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:49.643 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:45:49.643 ThaliTest[1859:2900030] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:53.116 ThaliTest[1859:2900805] client session: connected
,2015-12-03 01:45:53.116 ThaliTest[1859:2900805] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:45:53.156 ThaliTest[1859:2900805] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:45:53.157 ThaliTest[1859:2900805] jxcore: connect: success
2015-12-03T00:45:53.157Z SendDataConnector.js: CLIENT connected to 50074, error: null
2015-12-03T00:45:53.157Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:45:53.158 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:45:53.158 ThaliTest[1859:2899852] client: new accepted socket: 0x16466c70
,2015-12-03T00:45:53.171Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:46:03.193Z SendDataConnector.js: Receiving data timeout now
,2015-12-03T00:46:03.193Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:03.193Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:03.194Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:46:03.194Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:03.194 ThaliTest[1859:2899852] client: socket closed
2015-12-03 01:46:03.195 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:46:03.195 ThaliTest[1859:2899852] client relay: 0x16466c70 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:46:03.195 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-1,2-03 01:46:03.195 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:03.195 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:46:03.195 ThaliTest[1859:2899852] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:03.197 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:46:08.199Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:46:08.199Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:13.209 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:46:13.209 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:46:13.209Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:46:13.209Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:46:13.209Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:46:13.210Z SendDataConnector.js: do connect now
,2015-12-03 01:46:13.210 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:13.210 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:46:13.210 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:14.776 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:46:14.787 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:14.787 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:46:14.788 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:46:16.564 ThaliTest[1859:2900872] client session: connected
2015-12-03 01:46:16.565 ThaliTest[1859:2900872] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:16.574 ThaliTest[1859:2900881] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:16.575 ThaliTest[1859:2900881] jxcore: connect: success
,2015-12-03T00:46:16.575Z SendDataConnector.js: CLIENT connected to 50079, error: null
,2015-12-03T00:46:16.575Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 01:46:16.576 ThaliTest[1859:2899852] client: relay established
,2015-12-03 01:46:16.577 ThaliTest[1859:2899852] client: new accepted socket: 0x1646cde0
,2015-12-03T00:46:16.589Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03T00:46:26.607Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:46:26.608Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:26.608Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:26.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T00:46:26.609Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:26.609 ThaliTest[1859:2899852] client: socket closed
2015-12-03 01:46:26.609 ThaliTest[1859:2899852] client relay: socket disconnected
2015-12-03 01:46:26.609 ThaliTest[1859:2899852] client relay: 0x1646cde0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-03 01:46:26.610 ThaliTest[1859:2899852] client session: socket closed: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:26.610 ThaliTest[1859:2899852] client session: onLinkFailure: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:26.610 ThaliTest[1859:2899852] client session: disconnect
2015-12-03 01:46:26.610 ThaliTest[1859:2899852] client session: stateChan,ge:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:26.611 ThaliTest[1859:2899852] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:46:31.613Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03T00:46:31.613Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:36.621 ThaliTest[1859:2900030] jxcore: disconnect
2015-12-03 01:46:36.622 ThaliTest[1859:2900030] jxcore: disconnect: fail
2015-12-03T00:46:36.622Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0,ig==
2015-12-03T00:46:36.622Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT5704.2nX0ig== with availability status: true
2015-12-03T00:46:36.622Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03T00:46:36.622Z SendDataConnector.js: do connect now
,2015-12-03 01:46:36.623 ThaliTest[1859:2900030] jxcore: connect Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:36.623 ThaliTest[1859:2900030] client session: connect
2015-12-03 01:46:36.623 ThaliTest[1859:2900030] client session: stateChange:0->1 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:39.284 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:46:39.284 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:46:39.284 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:46:39.284 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:46:39.284 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:46:39.286 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:46:40.912 ThaliTest[1859:2900937] client session: connected
2015-12-03 01:46:40.912 ThaliTest[1859:2900937] client session: stateChange:1->2 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:40.921 ThaliTest[1859:2900961] client session: fireConnectCallback: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:40.921 ThaliTest[1859:2900961] jxcore: connect: success
2015-12-03T00:46:40.922Z SendDataConnector.js: CLIENT connected to 50083, error: null
,2015-12-03T00:46:40.922Z SendDataConnector.js: CLIENT starting client 
2015-12-03 01:46:40.923 ThaliTest[1859:2899852] client: relay established
2015-12-03 01:46:40.923 ThaliTest[1859:2899852] client: new accepted socket: 0x163025d0
,2015-12-03T00:46:40.936Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-03 01:46:41.563 ThaliTest[1859:2900951] server session: connected
2015-12-03 01:46:41.563 ThaliTest[1859:2900951] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:46:41.595 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:46:41.607Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:41.844Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-03T00:46:41.871Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-03T00:46:41.886Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:46:44.247 ThaliTest[1859:2899852] multipeer session: reset timer
,2015-12-03 01:46:44.247 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:46:44.247 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:46:44.247 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:46:44.248 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone5-1_PT8796
,2015-12-03 01:46:44.251 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone5-1_PT8796
,2015-12-03 01:46:46.848 ThaliTest[1859:2900951] server session: connected
2015-12-03 01:46:46.848 ThaliTest[1859:2900951] server session: stateChange:1->2 Apple-Iphone5-1_PT8796
,2015-12-03 01:46:46.864 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:46:46.875Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:46:47.364Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-03T00:46:47.377Z SendDataTCPServer.js: TCP/IP server has received 17856 bytes of data
,2015-12-03T00:46:47.403Z SendDataTCPServer.js: TCP/IP server has received 23808 bytes of data
,2015-12-03T00:46:47.500Z SendDataTCPServer.js: TCP/IP server has received 36704 bytes of data
,2015-12-03T00:46:47.515Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-12-03T00:46:47.529Z SendDataTCPServer.js: TCP/IP server has received 72416 bytes of data
,2015-12-03T00:46:47.564Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
,2015-12-03T00:46:47.578Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 01:46:47.588 ThaliTest[1859:2900968] server session: not connected Apple-Iphone5-1_PT8796
,2015-12-03T00:46:50.968Z SendDataConnector.js: Receiving data timeout now
2015-12-03T00:46:50.968Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03T00:46:50.969Z SendDataConnector.js: CLIENT closeClientSocket
oneRoundDownNow
,oneRoundDownNow:2
,2015-12-03T00:46:50.970Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T00:46:50.970Z SendDataConnector.js: Stop data retrieving timer
,2015-12-03T00:46:50.970Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 01:46:50.971 ThaliTest[1859:2900030] jxcore: disconnect
,2015-12-03 01:46:50.971 ThaliTest[1859:2900030] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:46:50.971 ThaliTest[1859:2900030] client session: disconnect
2015-12-03 01:46:50.971 ThaliTest[1859:2900030] client session: stateChange:2->0 Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:46:50.974 ThaliTest[1859:2900030] jxcore: disconnect: success
2015-12-03T00:46:50.974Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5704.2nX0ig==
---- round done--------
weAreDoneNow, resultArray.length: 4
sendReportNow
,{ roundsToDo: 1,
  doneRounds: 1,
  toSendDataAmount: 100000,
  reTryTimeout: 5000,
  reTryMaxCount: 5,
  dataTimeOut: 10000,
  clientSocket: 
   { _connecting: false,
     _handle: 
      { writeQueueSize: 0,
        owner: [Circular],
        onread: [Function: onread],
        reading: true },
     _readableState: 
      { highWaterMark: 16384,
        buffer: [],
        length: 0,
        pipes: null,
        pipesCount: 0,
        flowing: false,
        ended: false,
        endEmitted: false,
        reading: true,
        calledRead: true,
        sync: false,
        needReadable: true,
        emittedReadable: false,
        readableListening: false,
        objectMode: false,
        defaultEncoding: 'utf8',
        ,ranOut: false,
        awaitDrain: 0,
        readingMore: false,
        decoder: null,
        encoding: null },
     readable: true,
     domain: null,
     _events: 
      { end: [Object],
        finish: [Function: onSocketFinish],
        _,socketEnd: [Function: onSocketEnd],
        data: [Function],
        readable: [Function],
        error: [Function] },
     _maxListeners: 10,
     _writableState: 
      { highWaterMark: 16384,
        objectMode: false,
        needDrain: false,,
        ending: true,
        ended: true,
        finished: true,
        decodeStrings: false,
        defaultEncoding: 'utf8',
        length: 0,
        writing: false,
        sync: false,
        bufferProcessing: false,
        onwrite: ,[Function],
        writecb: null,
        writelen: 0,
        buffer: [],
        errorEmitted: false },
     writable: false,
     allowHalfOpen: false,
     onend: null,
     destroyed: false,
     bytesRead: 0,
     _bytesDispatched: 5000,
,     _pendingData: null,
     _pendingEncoding: '',
     __ec_int: true,
     ___timerId: 1,
     pipe: [Function],
     addListener: [Function: addListener],
     on: [Function: addListener],
     pause: [Function],
     resume: [Function],
     ,read: [Function],
     _consuming: true },
  reTryTimer: null,
  receivedCounter: 90000,
  tryRounds: 0,
  resultArray: [],
  connectionCount: 0,
  _events: { done: [Function], debug: [Function] },
  peer: null,
  startTime: Thu Dec 03 2015 01:46:,50 GMT+0100 (CET),
  endTime: Thu Dec 03 2015 01:46:50 GMT+0100 (CET),
  endReason: '',
  dataTimerId: null,
  disconnecting: true }
done, now sending data to server
CoordinatorConnector-debug: sendData
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7682","time":265808,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT2613.bcJOyQ==","time":43651,"result":"Peer unreachable","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Apple,-Iphone5-1_PT8796.xJ9gmA==","time":2682,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT2613.ais2pw==","time":110010,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount",:100000,"dataReceived":90000},{"name":"Apple-Iphone5s-1_PT5704.2nX0ig==","time":109435,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":90000}]}
sendList : 100% : 2682 ms, 99% : 2682 ms, 95 : 2682 ms, 90% : 2682 ms,.
Result count 1, range 2682 ms to  2682 ms.
,sendList failed peers count : 3 [75 %]
,- Peer ID : Apple-Iphone6-1_PT2613.bcJOyQ==, Tried : 5
- Peer ID : Apple-Iphone6-1_PT2613.ais2pw==, Tried : 5
- Peer ID : Apple-Iphone5s-1_PT5704.2nX0ig==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-03T00:46:50.984Z SendDataConnector.js: CLIENT Stop now
2015-12-03T00:46:50.984Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-03T00:46:50.985Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-03 01:46:52.077 ThaliTest[1859:2900968] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:47:02.632 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:47:02.632 ThaliTest[1859:2899852] multipeer session: stop timer
,2015-12-03 01:47:02.632 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:47:02.632 ThaliTest[1859:2899852] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:47:02.632 ThaliTest[1859:2899852] server session: disconnect
2015-12-03 01:47:02.632 ThaliTest[1859:2899852] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:02.634 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:47:02.634 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
2015-12-03 01:47:02.636 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:47:02.639Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:47:04.872 ThaliTest[1859:2901001] server session: connected
2015-12-03 01:47:04.872 ThaliTest[1859:2901001] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:04.880 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:47:04.888Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:47:04.976Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:47:15.141 ThaliTest[1859:2900951] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:47:17.547 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:17.547 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:47:25.691 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:47:25.691 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:47:25.691 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:47:25.691 ThaliTest[1859:2899852] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:47:25.691 ThaliTest[1859:2899852] server session: disconnect
2015-12-03 01:47:25.691 ThaliTest[1859:2899852] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:25.693 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:47:25.693 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:25.696 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:47:25.703Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:47:27.954 ThaliTest[1859:2901055] server session: connected
2015-12-03 01:47:27.954 ThaliTest[1859:2901055] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:27.980 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:47:27.992Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:47:28.067Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:47:38.204 ThaliTest[1859:2901066] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:47:38.837 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:47:47.825 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:47:47.825 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:47:48.764 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:47:48.764 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:47:48.764 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:47:48.764 ThaliTest[1859:2899852] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:47:48.764 ThaliTest[1859:2899852] server session: disconnect
2015-12-03 01:47:48.765 ThaliTest[1859:2899852] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:48.766 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:47:48.766 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03T00:47:48.769Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 01:47:48.770 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03 01:47:51.034 ThaliTest[1859:2901115] server session: connected
2015-12-03 01:47:51.034 ThaliTest[1859:2901115] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:47:51.052 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:47:51.064Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:47:51.316Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:47:52.494 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:01.266 ThaliTest[1859:2901115] server session: not connected Apple-Iphone6-1_PT2613
,2015-12-03 01:48:10.233 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:10.233 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:11.242 ThaliTest[1859:2899852] multipeer session: reset timer
2015-12-03 01:48:11.242 ThaliTest[1859:2899852] multipeer session: stop timer
2015-12-03 01:48:11.242 ThaliTest[1859:2899852] multipeer session: start timer: 0x147338c0
2015-12-03 01:48:11.242 ThaliTest[1859:2899852] server: disconnecting to refresh session (Apple-Iphone6-1_PT2613)
2015-12-03 01:48:11.242 ThaliTest[1859:2899852] server session: disconnect
2015-12-03 01:48:11.242 ThaliTest[1859:2899852] server session: stateChange:2->0 Apple-Iphone6-1_PT2613
,2015-12-03 01:48:11.243 ThaliTest[1859:2899852] server session: connect
2015-12-03 01:48:11.243 ThaliTest[1859:2899852] server session: stateChange:0->1 Apple-Iphone6-1_PT2613
,2015-12-03 01:48:11.246 ThaliTest[1859:2899852] server: accepting invitation Apple-Iphone6-1_PT2613
,2015-12-03T00:48:11.255Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 01:48:13.854 ThaliTest[1859:2901160] server session: connected
2015-12-03 01:48:13.854 ThaliTest[1859:2901160] server session: stateChange:1->2 Apple-Iphone6-1_PT2613
,2015-12-03 01:48:13.863 ThaliTest[1859:2899852] server relay: connected (to port: 50035)
,2015-12-03T00:48:13.871Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T00:48:13.981Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 01:48:15.036 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:17.701 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:48:17.701 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:48:22.759 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:48:23.972 ThaliTest[1859:2901163] server session: not connected Apple-Iphone6-1_PT2613
,CoordinatorConnector-debug: disconnect:transport close
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:48:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:48:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:48:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:48:41.753 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:49:11.252 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:49:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:49:11.689 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:34.002 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:49:34.002 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:49:36.142 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:49:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:49:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:49:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:49:41.402 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:03.130 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
,2015-12-03 01:50:03.130 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:50:04.467 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:50:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:50:11.461 ThaliTest[1859:2899852] client: found peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:50:11.461 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:50:40.834 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone6-1_PT2613.ais2pw==
2015-12-03 01:50:40.834 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone6-1_PT2613.ais2pw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT2613.ais2pw==","peerName":"(null)","peerAvailable":false}]
,2015-12-03 01:50:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:50:41.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:50:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:51:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:51:11.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:51:11.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:51:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:51:41.531 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:51:41.558 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:52:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:52:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:17.641 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:52:17.641 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:22.436 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:52:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:52:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:52:41.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:53:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:53:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:53:11.253 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:53:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:53:41.410 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:53:41.456 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:54:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:54:11.442 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:54:11.809 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:54:41.242 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:54:41.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:54:41.252 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:55:11.243 ThaliTest[1859:2899852] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:55:11.568 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:55:11.613 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:55:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:55:41.627 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:55:42.014 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:56:11.243 ThaliTest[1859:2899852] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:56:41.242 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:56:41.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:56:41.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:57:11.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,2015-12-03 01:57:11.254 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:57:41.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
2015-12-03 01:57:41.252 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
,2015-12-03 01:57:43.682 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:57:43.682 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:44.670 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,2015-12-03 01:57:47.872 ThaliTest[1859:2899852] client: lost peer: Apple-Iphone5s-1_PT5704.2nX0ig==
2015-12-03 01:57:47.872 ThaliTest[1859:2899852] client session: onPeerLost: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":false}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:57:49.912 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5s-1_PT5704.2nX0ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5704.2nX0ig==","peerName":"(null)","peerAvailable":true}]
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:58:11.243 ThaliTest[1859:2899852] multipeer session: restart
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:58:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:58:41.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:59:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:59:11.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,",_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 01:59:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 01:59:41.694 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:00:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:00:11.249 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:00:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:00:41.474 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:01:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:01:11.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:01:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:01:41.252 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:02:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:02:11.614 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:02:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:02:41.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:03:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:03:11.391 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:03:41.242 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:03:41.784 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:04:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:04:11.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:04:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:04:41.556 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:05:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:05:11.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:05:41.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:05:41.251 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":fa,lse,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}
,2015-12-03 02:06:11.243 ThaliTest[1859:2899852] multipeer session: restart
,2015-12-03 02:06:11.250 ThaliTest[1859:2899852] client: found peer: Apple-Iphone5-1_PT8796.xJ9gmA==
,CoordinatorConnector-debug: Socket error: connect_error:Error: websocket error
,{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}}

```
