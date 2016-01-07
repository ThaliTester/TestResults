#### Test 55311151a2306df_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AA1C2759-ACA7-4749-9234-A14CE478515C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AA1C2759-ACA7-4749-9234-A14CE478515C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2628111F-74F9-4268-89AF-1D8782EB187E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49484"
,(lldb)     command script import "/tmp/AA1C2759-ACA7-4749-9234-A14CE478515C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 09:36:50.662 ThaliTest[1417:3060934] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/16D66E2F-F771-4212-B927-C35FB7D2AF29/Library/Cookies/Cookies.binarycookies
,2016-01-07 09:36:51.018 ThaliTest[1417:3060934] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 09:36:51.019 ThaliTest[1417:3060934] Multi-tasking -> Device: YES, App: YES
,2016-01-07 09:36:51.029 ThaliTest[1417:3060934] Unlimited access to network resources
,2016-01-07 09:36:51.040 ThaliTest[1417:3060934] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 09:37:00.186 ThaliTest[1417:3060934] Resetting plugins due to page load.
,2016-01-07 09:37:03.660 ThaliTest[1417:3060934] Finished load of: file:///var/mobile/Containers/Bundle/Application/2628111F-74F9-4268-89AF-1D8782EB187E/ThaliTest.app/www/index.html
,2016-01-07 09:37:03.841 ThaliTest[1417:3060934] JXcore Cordova plugin initializing
,2016-01-07 09:37:03.842 ThaliTest[1417:3061140] JXcore instance initializing
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
,2016-01-07 09:37:04.933 ThaliTest[1417:3060934] THREAD WARNING: ['JXcore'] took '79.959961' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 09:41:49.646 ThaliTest[1417:3061140] jxcore: startBroadcasting
,2016-01-07 09:41:49.665 ThaliTest[1417:3061140] server: starting Apple-Iphone6-1.qqPEfA==
2016-01-07 09:41:49.666 ThaliTest[1417:3061140] multipeer session: start timer: 0x17450100
,2016-01-07 09:41:49.667 ThaliTest[1417:3061140] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-07 09:41:49.668 ThaliTest[1417:3061140] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-07 09:41:50.907 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.Xe0AvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1.Xe0AvA==, peerAvailable: true
,2016-01-07 09:41:51.361 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.ujszBw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.ujszBw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.ujszBw==, peerAvailable: true
,2016-01-07 09:41:52.931 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.TWDlRQ==, peerAvailable: true
,2016-01-07 09:42:19.669 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:42:49.669 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:42:49.706 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:42:49.706 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:42:49.708 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,appEnteredForeground wasn't registered
,2016-01-07 09:43:19.669 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:43:19.751 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:43:19.752 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:43:21.893 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,appEnteringBackground wasn't registered
,timeout now
,weAreDoneNow
,done, now sending data to server
,2016-01-07 09:43:33.017 ThaliTest[1417:3060934] client: lost peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:43:33.019 ThaliTest[1417:3060934] client session: onPeerLost: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:43:33.019 ThaliTest[1417:3060934] client: lost ,peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:43:33.019 ThaliTest[1417:3060934] client session: onPeerLost: Apple-IpadAir2-1.ujszBw==
,2016-01-07 09:43:49.669 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:43:49.698 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,teardown
,testFindPeers stopped
,2016-01-07 09:43:49.763 ThaliTest[1417:3061140] jxcore: stopBroadcasting
2016-01-07 09:43:49.763 ThaliTest[1417:3061140] THEMultipeerSession stopping peer
2016-01-07 09:43:49.764 ThaliTest[1417:3061140] multipeer session: stop timer
2016-01-07 09:43:49.,764 ThaliTest[1417:3061140] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 4
,daya100000
,check server
,serverPort is 63919
,2016-01-07 09:43:50.800 ThaliTest[1417:3061140] jxcore: startBroadcasting
,2016-01-07 09:43:50.804 ThaliTest[1417:3061140] server: starting Apple-Iphone6-1.I/6L8w==
2016-01-07 09:43:50.805 ThaliTest[1417:3061140] multipeer session: start timer: 0x1738f7f0
2016-01-07 09:43:50.805 ThaliTest[1417:3061140] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-07 09:43:50.806 ThaliTest[1417:3061140] jxcore: startBroadcasting: success
StartBroadcasting started ok
,[ { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 } ]
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:43:50.832Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:43:50.833Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:43:50.834Z SendDataConnector.js: do connect now
,2016-01-07 09:43:50.835 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:43:50.837 ThaliTest[1417:3061140] client: unknown peer 
,2016-01-07 09:43:50.838 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
,2016-01-07T08:43:50.840Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:43:50.841Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:43:50.842Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:43:50.844Z SendDataTCPServer.js: TCP/IP server is bound to port: 63919
,2016-01-07 09:43:51.311 ThaliTest[1417:3060934] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:43:51.312 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07T08:43:55.853Z SendDataConnector.js: re-try now : 
,2016-01-07T08:43:55.854Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:00.865 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:00.866 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:00.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:00.867Z S,endDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:44:00.867Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:00.868Z SendDataConnector.js: do connect now
,2016-01-07 09:44:00.869 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:44:00.869 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:00.870 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:00.870Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-0,7T08:44:00.871Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:00.871Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:05.875Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:05.876Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:07.047 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.LQugrg==
,2016-01-07 09:44:07.139 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.4D8zyg==
,2016-01-07 09:44:10.881 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:10.882 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:10.882Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:10.883Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:44:10.883Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:10.883Z SendDataConnector.js: do connect now
,2016-01-07 09:44:10.884 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:44:10.885 ThaliTest[1417:3061140] client: unknown peer 
,2016-01-07 09:44:10.885 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:10.886Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:10.887Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:10.887Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:15.889Z SendDataConnector.js: re-try now : 
2016-01-07T08:44:15.890Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:20.806 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:44:20.891 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:20.892 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:20.892Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:20.893Z S,endDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:44:20.893Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:20.894Z SendDataConnector.js: do connect now
,2016-01-07 09:44:20.895 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:44:20.896 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:20.896 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:20.896Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:20.897Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:20.897Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:25.899Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:25.900Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:30.905 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:30.906 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:30.906Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:30.906Z S,endDataConnector.js: Connect (retry count 4) to peer  with availability status: true
2016-01-07T08:44:30.907Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:30.907Z SendDataConnector.js: do connect now
,2016-01-07 09:44:30.908 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:44:30.908 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:30.909 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:30.910Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:30.910Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
oneRoundDownNow
,2016-01-07T08:44:30.913Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:44:30.914 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:30.914 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:30.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,---- round done--------
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:44:30.919Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:44:30.920Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:30.920Z SendDataConnector.js: do connect now
,2016-01-07 09:44:30.921 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:44:30.922 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:30.922 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:30.923Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:30.923Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:30.923Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:35.925Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:35.926Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:40.930 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:40.931 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:40.932Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:40.932Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:44:40.932Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:40.933Z SendDataConnector.js: do connect now
,2016-01-07 09:44:40.934 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:44:40.935 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:40.935 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:40.935Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:40.936Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:40.936Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:45.947Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:45.947Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:50.806 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:44:50.844 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:44:50.845 ThaliTest[1417:3060934] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:44:50.845 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.4D8zyg==
,2016-01-07 09:44:50.852 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.LQugrg==
,2016-01-07 09:44:50.956 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:44:50.957 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:44:50.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:50.958Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:44:50.958Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:50.958Z SendDataConnector.js: do connect now
,2016-01-07 09:44:50.959 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:44:50.960 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:44:50.961 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:50.961Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:50.961Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:50.962Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:55.967Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:55.968Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:00.972 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:00.973 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:45:00.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:00.974Z S,endDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:45:00.974Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:00.974Z SendDataConnector.js: do connect now
,2016-01-07 09:45:00.975 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:45:00.976 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:45:00.977 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:00.977Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:00.977Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:00.978Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:05.980Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:05.981Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:10.983 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:10.983 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:45:10.984Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:10.984Z S,endDataConnector.js: Connect (retry count 4) to peer  with availability status: true
2016-01-07T08:45:10.985Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:10.985Z SendDataConnector.js: do connect now
,2016-01-07 09:45:10.986 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:45:10.987 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:45:10.987 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:10.987Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:10.988Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
oneRoundDownNow
2016-01-07T08:45:10.988Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:10.989 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:10.989 ThaliTest[1417:3061140] jxcore: disconnect: fail
,2016-01-07T08:45:10.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: 
2016-01-07T08:45:10.993Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:45:10.993Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:10.993Z SendDataConnector.js: do connect now
,2016-01-07 09:45:10.995 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:45:10.995 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:45:10.996 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:10.996Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:10.996Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:10.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:16.000Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:16.001Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:20.806 ThaliTest[1417:3060934] multipeer session: restart
,2016-01-07 09:45:20.851 ThaliTest[1417:3060934] client: found peer: Apple-IpadAir2-1.LQugrg==
2016-01-07 09:45:20.852 ThaliTest[1417:3060934] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:45:20.853 ThaliTest[1417:3060934] client: found peer:, Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:45:20.854 ThaliTest[1417:3060934] client: found peer: Apple-Iphone5-1.4D8zyg==
,2016-01-07 09:45:21.012 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:21.013 ThaliTest[1417:3061140] jxcore: disconnect: fail
,2016-01-07T08:45:21.013Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:21.014Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
,2016-01-07T08:45:21.015Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:21.015Z SendDataConnector.js: do connect now
,2016-01-07 09:45:21.016 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:45:21.017 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:45:21.018 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:21.018Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:21.018Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:21.019Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:26.020Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:26.021Z SendDataConnector.js: ReStart called with peer 
,timeout now
,weAreDoneNow, resultArray.length: 0
,sendReportNow
,done, now sending data to server
,2016-01-07T08:45:30.857Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:30.858 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:30.859 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:45:30.860Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07 09:45:31.026 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:31.026 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:45:31.027Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:31.027Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:45:31.028Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:31.028Z SendDataConnector.js: do connect now
,2016-01-07 09:45:31.029 ThaliTest[1417:3061140] jxcore: connect 
2016-01-07 09:45:31.030 ThaliTest[1417:3061140] client: unknown peer 
2016-01-07 09:45:31.030 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:31.031Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:31.031Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:31.031Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:36.033Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:36.034Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:41.042 ThaliTest[1417:3061140] jxcore: disconnect
2016-01-07 09:45:41.043 ThaliTest[1417:3061140] jxcore: disconnect: fail
2016-01-07T08:45:41.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:41.043Z S,endDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:45:41.044Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:41.044Z SendDataConnector.js: do connect now
,2016-01-07 09:45:41.045 ThaliTest[1417:3061140] jxcore: connect 
,2016-01-07 09:45:41.045 ThaliTest[1417:3061140] client: unknown peer 
,2016-01-07 09:45:41.046 ThaliTest[1417:3061140] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:41.047Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:41.048Z SendDataConnector.js: CLIENT Can not Connect: Unknown p,eer
2016-01-07T08:45:41.048Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:46.048Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:46.049Z SendDataConnector.js: ReStart called with peer 
,teardown
,testSendData stopped
2016-01-07 09:45:50.273 ThaliTest[1417:3061140] jxcore: stopBroadcasting
2016-01-07 09:45:50.273 ThaliTest[1417:3061140] THEMultipeerSession stopping peer
2016-01-07 09:45:50.273 ThaliTest[1417:3061140] multipeer session: stop timer,
2016-01-07 09:45:50.274 ThaliTest[1417:3061140] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-07T08:45:50.278Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
