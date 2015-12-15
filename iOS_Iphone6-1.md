#### Test 50650278ee43ca0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/43379C4D-ACB8-4469-9EC2-45E576A073A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/43379C4D-ACB8-4469-9EC2-45E576A073A0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278ee43ca0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6945E9D9-9605-4552-8DD0-624B66D5EB4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56311"
,(lldb)     command script import "/tmp/43379C4D-ACB8-4469-9EC2-45E576A073A0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:01:17.316 ThaliTest[1000:1256750] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0768606D-0640-4092-85DA-EE18A35D9F8D/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:01:17.677 ThaliTest[1000:1256750] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:01:17.679 ThaliTest[1000:1256750] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:01:17.688 ThaliTest[1000:1256750] Unlimited access to network resources
,2015-12-15 05:01:17.699 ThaliTest[1000:1256750] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:01:26.872 ThaliTest[1000:1256750] Resetting plugins due to page load.
,2015-12-15 05:01:30.115 ThaliTest[1000:1256750] Finished load of: file:///var/mobile/Containers/Bundle/Application/6945E9D9-9605-4552-8DD0-624B66D5EB4C/ThaliTest.app/www/index.html
,2015-12-15 05:01:30.303 ThaliTest[1000:1256750] JXcore Cordova plugin initializing
2015-12-15 05:01:30.304 ThaliTest[1000:1256949] JXcore instance initializing
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
,2015-12-15 05:01:31.371 ThaliTest[1000:1256750] THREAD WARNING: ['JXcore'] took '80.561035' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:06:32.038 ThaliTest[1000:1256949] jxcore: startBroadcasting
,2015-12-15 05:06:32.057 ThaliTest[1000:1256949] server: starting Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:32.059 ThaliTest[1000:1256949] multipeer session: start timer: 0x15b54f60
2015-12-15 05:06:32.060 ThaliTest[1000:1256949] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT9306
2015-12-15 05:06:32.060 ThaliTest[1000:1256949] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 05:06:33.089 ThaliTest[1000:1256750] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1_PT1010.7Cf2mQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-15 05:06:33.143 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:33.205 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
,teardown
,testFindPeers stopped
,2015-12-15 05:06:34.509 ThaliTest[1000:1256949] jxcore: stopBroadcasting
2015-12-15 05:06:34.509 ThaliTest[1000:1256949] THEMultipeerSession stopping peer
2015-12-15 05:06:34.509 ThaliTest[1000:1256949] multipeer session: stop timer
2015-12-15 05:06:34.,510 ThaliTest[1000:1256949] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 59147
,2015-12-15 05:06:34.582 ThaliTest[1000:1256949] jxcore: startBroadcasting
,2015-12-15 05:06:34.585 ThaliTest[1000:1256949] server: starting Apple-Iphone6-1_PT9306.EdsImg==
2015-12-15 05:06:34.586 ThaliTest[1000:1256949] multipeer session: start timer: 0x15b5b5c0
2015-12-15 05:06:34.587 ThaliTest[1000:1256949] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT9306
2015-12-15 05:06:34.587 ThaliTest[1000:1256949] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-15T04:06:34.612Z SendDataTCPServer.js: TCP/IP server is bound to port: 59147
2015-12-15 05:06:34.612 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:34.613 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:34.613 ThaliTest[1000:1256750] client: found peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:34.615 ThaliTest[1000:1256750] client: found peer: Apple-Iphone6-1_PT9306.6VQMVQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:34.624Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:34.626Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:34.626Z SendDataConnector.js: do connect now
,2015-12-15 05:06:34.627 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:34.628 ThaliTest[1000:1256949] client session: connect
,2015-12-15 05:06:34.629 ThaliTest[1000:1256949] client session: stateChange:0->1 Apple-Iphone5s-1_PT6308.pQEQSw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 05:06:35.632 ThaliTest[1000:1256750] client: lost peer: Apple-Iphone6-1_PT9306.6VQMVQ==
2015-12-15 05:06:35.633 ThaliTest[1000:1256750] client session: onPeerLost: Apple-Iphone6-1_PT9306.6VQMVQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT9306.6VQMVQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 05:06:35.703 ThaliTest[1000:1256750] client: lost peer: Apple-IpadAir2-1_PT1010.7Cf2mQ==
2015-12-15 05:06:35.704 ThaliTest[1000:1256750] client session: onPeerLost: Apple-IpadAir2-1_PT1010.7Cf2mQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.7Cf2mQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 05:06:36.167 ThaliTest[1000:1256750] client: lost peer: Apple-Iphone5-1_PT2557.cLGdMA==
2015-12-15 05:06:36.167 ThaliTest[1000:1256750] client session: onPeerLost: Apple-Iphone5-1_PT2557.cLGdMA==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT2557.cLGdMA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2015-12-15 05:06:36.169 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
peerAvailabilityChanged [{"peerIdentifie,r":"Apple-Iphone5s-1_PT6308.z27btQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:06:36.775 ThaliTest[1000:1256750] client: lost peer: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.776 ThaliTest[1000:1256750] client session: onPeerLost: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.776 ThaliTest[1000:1256750] client session: onLinkFailure: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.776 ThaliTest[1000:1256750] client session: disconnect
,2015-12-15 05:06:36.777 ThaliTest[1000:1256750] client session: stateChange:1->0 Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.780 ThaliTest[1000:1256750] client session: fireConnectCallback: Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:36.78,0 ThaliTest[1000:1256750] jxcore: connect: fail: Peer disconnected
2015-12-15 05:06:36.782 ThaliTest[1000:1256750] client: found peer: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15T04:06:36.782Z SendDataConnector.js: CLIENT connected to 0, error: Peer disc,onnected
2015-12-15 05:06:36.783 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15T04:06:36.783Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T04:06:36.783Z SendDataConnector.js: tryAgain, afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6308.pQEQSw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT1010.g7hIzw==","peerName":"(null)","peerAvailable":tr,ue}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2557.fyiFnQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15T04:06:41.786Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:41.787Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:46.800 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-15 05:06:46.801 ThaliTest[1000:1256949] jxcore: disconnect: fail
2015-12-15T04:06:46.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:06:46.802Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:06:46.802Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:46.802Z SendDataConnector.js: do connect now
,2015-12-15 05:06:46.804 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:46.804 ThaliTest[1000:1256949] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:06:46.805 ThaliTest[1000:1256949], jxcore: connect: fail: Peer unreachable
2015-12-15T04:06:46.805Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:46.806Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:06:46.806Z SendD,ataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:06:51.809Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:06:51.810Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:56.818 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-15 05:06:56.818 ThaliTest[1000:1256949] jxcore: disconnect: fail
2015-12-15T04:06:56.819Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:06:56.819Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:06:56.819Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==,
2015-12-15T04:06:56.820Z SendDataConnector.js: do connect now
,2015-12-15 05:06:56.820 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:56.821 ThaliTest[1000:1256949] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:06:56.822 ThaliTest[1000:1256949] jxcore: connect: fail: Peer unreachable
2015-12-15T04:06:56.823Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:06:56.823Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:06:56.824Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:01.836Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:01.836Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:04.588 ThaliTest[1000:1256750] multipeer session: restart
,2015-12-15 05:07:04.629 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:04.630 ThaliTest[1000:1256750] client: found peer: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:04.631 ThaliTest[1000:1256750] client: found peer: Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:06.841 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-15 05:07:06.841 ThaliTest[1000:1256949] jxcore: disconnect: fail
2015-12-15T04:07:06.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQ,Sw==
2015-12-15T04:07:06.842Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:06.842Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==,
2015-12-15T04:07:06.843Z SendDataConnector.js: do connect now
,2015-12-15 05:07:06.843 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:06.844 ThaliTest[1000:1256949] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:06.845 ThaliTest[1000:1256949] jxcore: connect: fail: Peer unreachable
2015-12-15T04:07:06.846Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:07:06.847Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T04:07:06.847Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:07:11.855Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15T04:07:11.855Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:16.845 ThaliTest[1000:1256750] multipeer session: reset timer
2015-12-15 05:07:16.845 ThaliTest[1000:1256750] multipeer session: stop timer
2015-12-15 05:07:16.846 ThaliTest[1000:1256750] multipeer session: start timer: 0x15b5b5c0
,2015-12-15 05:07:16.846 ThaliTest[1000:1256750] server session: connect
2015-12-15 05:07:16.848 ThaliTest[1000:1256750] server session: stateChange:0->1 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:16.859 ThaliTest[1000:1256750] server: accepting invitation Apple-IpadAir2-1_PT1010
2015-12-15 05:07:16.859 ThaliTest[1000:1256750] multipeer session: reset timer
2015-12-15 05:07:16.860 ThaliTest[1000:1256750] multipeer session: stop timer
,2015-12-15 05:07:16.860 ThaliTest[1000:1256750] multipeer session: start timer: 0x15b5b5c0
,2015-12-15 05:07:16.862 ThaliTest[1000:1256750] server session: connect
2015-12-15 05:07:16.863 ThaliTest[1000:1256750] server session: stateChange:0->1 Apple-Iphone5s-1_PT6308
2015-12-15 05:07:16.869 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-1,5 05:07:16.872 ThaliTest[1000:1256949] jxcore: disconnect: fail
2015-12-15T04:07:16.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:07:16.874Z SendDataConnector.js: Connect (retry count 4) ,to peer Apple-Iphone5s-1_PT6308.pQEQSw== with availability status: true
2015-12-15T04:07:16.874Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15T04:07:16.875Z SendDataConnector.js: do connect now
2015-12-15 0,5:07:16.876 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.pQEQSw==
,2015-12-15 05:07:16.879 ThaliTest[1000:1256949] client: connect: unreachable Apple-Iphone5s-1_PT6308.pQEQSw==
2015-12-15 05:07:16.882 ThaliTest[1000:1256949] jxcore: connect: fail: Peer unreachable
2015-12-15T04:07:16.884Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer unreachable
2015-12-15T04:07:16.884Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-15T04:07:16.888Z SendDataConnector.js: CLIENT Stop now
2015-12-15 05:07:16.888 ThaliTest[1000:1256949], jxcore: disconnect
2015-12-15 05:07:16.890 ThaliTest[1000:1256949] jxcore: disconnect: fail
2015-12-15T04:07:16.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.pQEQSw==
---- round done--------
startWithNextDev,ice
device[2]: Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15T04:07:16.893Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15T04:07:16.893Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6308.z27b,2015-12-15 05:07:16.895 ThaliTest[1000:1256750] server: accepting invitation Apple-Iphone5s-1_PT6308
tQ==
2015-12-15T04:07:16.913Z SendDataConnector.js: do connect now
2015-12-15 05:07:16.914 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:16.915 ThaliTest[1000:1256949] client session: connect
2015-12-15 05:07:16.935 ThaliTest[1000:1256949] client session: stateChange:0->1 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:17.230 ThaliTest[1000:1256750] multipeer session: reset timer
2015-12-15 05:07:17.230 ThaliTest[1000:1256750] multipeer session: stop timer
2015-12-15 05:07:17.230 ThaliTest[1000:1256750] multipeer session: start timer: 0x15b5b5c0
2015-,12-15 05:07:17.231 ThaliTest[1000:1256750] server session: connect
2015-12-15 05:07:17.231 ThaliTest[1000:1256750] server session: stateChange:0->1 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:17.238 ThaliTest[1000:1256750] server: accepting invitation Apple-Iphone5-1_PT2557
,2015-12-15 05:07:19.550 ThaliTest[1000:1257541] server session: connected
2015-12-15 05:07:19.554 ThaliTest[1000:1257541] server session: stateChange:1->2 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:19.563 ThaliTest[1000:1256750] server relay: connected (to port: 59147)
,2015-12-15T04:07:19.572Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:07:19.599 ThaliTest[1000:1257541] server session: connected
2015-12-15 05:07:19.599 ThaliTest[1000:1257541] server session: stateChange:1->2 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:19.603 ThaliTest[1000:1256750] server relay: connected (to port: 59147)
,2015-12-15T04:07:19.611Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 05:07:19.798 ThaliTest[1000:1257559] client session: connected
2015-12-15 05:07:19.798 ThaliTest[1000:1257559] client session: stateChange:1->2 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:19.803 ThaliTest[1000:1257559] client session: fireConnectCallback: Apple-Iphone5s-1_PT6308.z27btQ==
2015-12-15 05:07:19.803 ThaliTest[1000:1257559] jxcore: connect: success
2015-12-15T04:07:19.804Z SendDataConnector.js: CLIENT connected to 59153, error: null
2015-12-15T04:07:19.805Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:19.809 ThaliTest[1000:1256750] client: relay established
2015-12-15 05:07:19.809 ThaliTest[1000:1256750] client: new accepted socket: 0x15c5e780
,2015-12-15T04:07:19.824Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
2015-12-15 05:07:19.825 ThaliTest[1000:1257560] server session: connected
2015-12-15 05:07:19.826 ThaliTest[1000:1257560] server session: stateChange:1->2 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:19.841 ThaliTest[1000:1256750] server relay: connected (to port: 59147)
,2015-12-15T04:07:20.136Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:07:20.139Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:07:20.144Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:07:20.187Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15 05:07:20.245 ThaliTest[1000:1257583] server session: not connected Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:20.254 ThaliTest[1000:1257560] server session: not connected Apple-Iphone5s-1_PT6308
,2015-12-15T04:07:20.261Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:20.261Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:07:20.262Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:20.262Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:20.263 ThaliTest[1000:1256949] jxcore: disconnect
,2015-12-15 05:07:20.263 ThaliTest[1000:1256949] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:20.264 ThaliTest[1000:1256949] client session: disconnect
,2015-12-15 05:07:20.264 ThaliTest[1000:1256949] client session: stateChange:2->0 Apple-Iphone5s-1_PT6308.z27btQ==
,2015-12-15 05:07:20.329 ThaliTest[1000:1256949] jxcore: disconnect: success
,2015-12-15T04:07:20.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6308.z27btQ==
---- round done--------
,startWithNextDevice
device[3]: Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.331Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.331Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.331Z SendDataConnector.js: do connect now
,2015-12-15 05:07:20.331 ThaliTest[1000:1256949] jxcore: connect Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:20.332 ThaliTest[1000:1256949] client session: connect
,2015-12-15 05:07:20.332 ThaliTest[1000:1256949] client session: stateChange:0->1 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15T04:07:20.375Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-15T04:07:20.389Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-15T04:07:20.448Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-15T04:07:20.462Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:07:20.574 ThaliTest[1000:1257541] server session: not connected Apple-Iphone5-1_PT2557
,2015-12-15 05:07:23.117 ThaliTest[1000:1257541] client session: connected
2015-12-15 05:07:23.118 ThaliTest[1000:1257541] client session: stateChange:1->2 Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:23.121 ThaliTest[1000:1257541] client session: fi,reConnectCallback: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:23.121 ThaliTest[1000:1257541] jxcore: connect: success
,2015-12-15T04:07:23.122Z SendDataConnector.js: CLIENT connected to 59157, error: null
2015-12-15T04:07:23.124Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:07:23.129 ThaliTest[1000:1256750] client: relay established
2015-12-15 05:07:23.129 ThaliTest[1000:1256750] client: new accepted socket: 0x15b6e680
,2015-12-15T04:07:23.140Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:23.410Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:07:23.423Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-15T04:07:23.436Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T04:07:23.450Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:07:23.450Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:07:23.450Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:23.450Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:23.451 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-15 05:07:23.451 ThaliTest[1000:1256949] client session: disconnectFromPeer: Apple-IpadAir2-1_PT1010.g7hIzw==
2015-12-15 05:07:23.451 ThaliTest[1000:1256949] client session: disconnect
2015-12-15 05:07:23.451 ThaliTest[1000:1256949] client session: stateChange:2->0 Apple-IpadAir2-1_PT1010.g7hIzw==
,2015-12-15 05:07:23.455 ThaliTest[1000:1256949] jxcore: disconnect: success
2015-12-15T04:07:23.456Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT1010.g7hIzw==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15T04:07:23.456Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15T04:07:23.457Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15T04:07:23.457Z SendDataConnector.js: do connect now
,2015-12-15 05:07:23.457 ThaliTest[1000:1256949] jxcore: connect Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:23.458 ThaliTest[1000:1256949] client session: connect
2015-12-15 05:07:23.458 ThaliTest[1000:1256949] client session: stateChange:0->1 Apple,-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:26.389 ThaliTest[1000:1257558] client session: connected
,2015-12-15 05:07:26.389 ThaliTest[1000:1257558] client session: stateChange:1->2 Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:26.394 ThaliTest[1000:1257558] client session: fireConnectCallback: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:26.394 ,ThaliTest[1000:1257558] jxcore: connect: success
,2015-12-15T04:07:26.395Z SendDataConnector.js: CLIENT connected to 59160, error: null
2015-12-15T04:07:26.396Z SendDataConnector.js: CLIENT starting client 
2015-12-15 05:07:26.400 ThaliTest[1000:1256750] client: relay established
2015-12-15 05:07:26.400 ThaliTest[1000:1256750] client: new accepted socket: 0x15b57fe0
,2015-12-15T04:07:26.411Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:07:26.736Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:07:26.736Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:07:26.736Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:07:26.736Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:07:26.737 ThaliTest[1000:1256949] jxcore: disconnect
2015-12-15 05:07:26.737 ThaliTest[1000:1256949] client session: disconnectFromPeer: Apple-Iphone5-1_PT2557.fyiFnQ==
2015-12-15 05:07:26.737 ThaliTest[1000:1256949] client session: disconn,ect
2015-12-15 05:07:26.737 ThaliTest[1000:1256949] client session: stateChange:2->0 Apple-Iphone5-1_PT2557.fyiFnQ==
,2015-12-15 05:07:26.741 ThaliTest[1000:1256949] jxcore: disconnect: success
2015-12-15T04:07:26.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2557.fyiFnQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-15T04:07:26.744Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:07:26.744Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-15 05:07:29.072 ThaliTest[1000:1256949] jxcore: stopBroadcasting
2015-12-15 05:07:29.073 ThaliTest[1000:1256949] THEMultipeerSession stopping peer
2015-12-15 05:07:29.073 ThaliTest[1000:1256949] multipeer session: stop timer
2015-12-15 05:07:29.,074 ThaliTest[1000:1256949] server session: disconnect
2015-12-15 05:07:29.074 ThaliTest[1000:1256949] server session: stateChange:2->0 Apple-Iphone5-1_PT2557
,2015-12-15 05:07:29.089 ThaliTest[1000:1256949] server session: disconnect
2015-12-15 05:07:29.091 ThaliTest[1000:1256949] server session: stateChange:2->0 Apple-Iphone5s-1_PT6308
,2015-12-15 05:07:29.169 ThaliTest[1000:1256949] server session: disconnect
2015-12-15 05:07:29.169 ThaliTest[1000:1256949] server session: stateChange:2->0 Apple-IpadAir2-1_PT1010
,2015-12-15 05:07:29.173 ThaliTest[1000:1256949] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:07:29.191Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:29.192Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:29.194Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:07:29.195Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
