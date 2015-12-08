#### Test 52971095c1e9930_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/A47B4282-C2E0-4B13-B427-E52469403D9A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A47B4282-C2E0-4B13-B427-E52469403D9A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2FB9CE45-8142-4569-B5E7-B14C0A510BD6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51297"
,(lldb)     command script import "/tmp/A47B4282-C2E0-4B13-B427-E52469403D9A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:45:32.579 ThaliTest[505:303051] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E5C44131-DE09-48E6-AE39-7189E25A5BD3/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:45:32.966 ThaliTest[505:303051] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:45:32.968 ThaliTest[505:303051] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:45:32.978 ThaliTest[505:303051] Unlimited access to network resources
,2015-12-08 17:45:32.992 ThaliTest[505:303051] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:45:42.279 ThaliTest[505:303051] Resetting plugins due to page load.
,2015-12-08 17:45:45.930 ThaliTest[505:303051] Finished load of: file:///var/mobile/Containers/Bundle/Application/2FB9CE45-8142-4569-B5E7-B14C0A510BD6/ThaliTest.app/www/index.html
,2015-12-08 17:45:46.115 ThaliTest[505:303051] JXcore Cordova plugin initializing
,2015-12-08 17:45:46.117 ThaliTest[505:303335] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT1987
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 52035
,2015-12-08 17:52:35.912 ThaliTest[505:303335] jxcore: startBroadcasting
,2015-12-08 17:52:35.932 ThaliTest[505:303335] server: starting Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:35.934 ThaliTest[505:303335] multipeer session: start timer: 0x15f497a0
,2015-12-08 17:52:35.935 ThaliTest[505:303335] THEMultipeerSession initialized peer Apple-Iphone6-1_PT1987
,2015-12-08 17:52:35.936 ThaliTest[505:303335] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-08T16:52:35.938Z SendDataTCPServer.js: TCP/IP server is bound to port: 52035
,2015-12-08 17:52:37.104 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,device[1]: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08T16:52:37.112Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08T16:52:37.113Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08T16:52:37.113Z SendDataConnector.js: do connect now
,2015-12-08 17:52:37.114 ThaliTest[505:303335] jxcore: connect Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:37.115 ThaliTest[505:303335] client session: connect
2015-12-08 17:52:37.115 ThaliTest[505:303335] client session: stateChange:0->1 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:37.164 ThaliTest[505:303051] multipeer session: reset timer
2015-12-08 17:52:37.164 ThaliTest[505:303051] multipeer session: stop timer
2015-12-08 17:52:37.165 ThaliTest[505:303051] multipeer session: start timer: 0x15f497a0
2015-12-08 ,17:52:37.165 ThaliTest[505:303051] server session: connect
2015-12-08 17:52:37.166 ThaliTest[505:303051] server session: stateChange:0->1 Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:37.181 ThaliTest[505:303051] server: accepting invitation Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:37.296 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6318.xt9ojg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:37.696 ThaliTest[505:303051] multipeer session: reset timer
2015-12-08 17:52:37.696 ThaliTest[505:303051] multipeer session: stop timer
2015-12-08 17:52:37.696 ThaliTest[505:303051] multipeer session: start timer: 0x15f497a0
2015-12-08 ,17:52:37.697 ThaliTest[505:303051] server session: connect
,2015-12-08 17:52:37.697 ThaliTest[505:303051] server session: stateChange:0->1 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:37.707 ThaliTest[505:303051] server: accepting invitation Apple-Iphone5-1_PT5966
,2015-12-08 17:52:39.223 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5978.hVAckA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:40.056 ThaliTest[505:304081] server session: connected
2015-12-08 17:52:40.057 ThaliTest[505:304081] server session: stateChange:1->2 Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:40.115 ThaliTest[505:303051] server relay: connected (to port: 52035)
,2015-12-08T16:52:40.124Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:40.384Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-08T16:52:40.398Z SendDataTCPServer.js: TCP/IP server has received 45280 bytes of data
,2015-12-08T16:52:40.415Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-08T16:52:40.428Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:40.466 ThaliTest[505:304079] server session: not connected Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:40.780 ThaliTest[505:304079] server session: connected
2015-12-08 17:52:40.780 ThaliTest[505:304079] server session: stateChange:1->2 Apple-Iphone5-1_PT5966
,2015-12-08 17:52:40.797 ThaliTest[505:304079] client session: connected
2015-12-08 17:52:40.798 ThaliTest[505:304079] client session: stateChange:1->2 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08T16:52:40.810Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08 17:52:40.808 ThaliTest[505:303051] server relay: connected (to port: 52035)
,2015-12-08 17:52:40.833 ThaliTest[505:304081] client session: fireConnectCallback: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:40.833 ThaliTest[505:304081] jxcore: connect: success
,2015-12-08T16:52:40.836Z SendDataConnector.js: CLIENT connected to 52040, error: null
,2015-12-08T16:52:40.836Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:40.840 ThaliTest[505:303051] client: relay established
2015-12-08 17:52:40.841 ThaliTest[505:303051] client: new accepted socket: 0x15e98b10
,2015-12-08T16:52:40.857Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:41.394Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:52:41.420Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-08T16:52:41.432Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-08T16:52:41.434Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:52:41.447Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-08T16:52:41.496Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-08T16:52:41.497Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-08T16:52:41.524Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-08T16:52:41.926Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:41.927Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:41.930Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:41.930Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:41.933 ThaliTest[505:303335] jxcore: disconnect
2015-12-08 17:52:41.934 ThaliTest[505:303335] client session: disconnectFromPeer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:52:41.934 ThaliTest[505:303335] client session: disconnect
2,015-12-08 17:52:41.934 ThaliTest[505:303335] client session: stateChange:2->0 Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:41.950 ThaliTest[505:303335] jxcore: disconnect: success
2015-12-08T16:52:41.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5966.KrGtFw==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:41.963Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:41.964Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6318.xt9ojg==,
2015-12-08T16:52:41.964Z SendDataConnector.js: do connect now
2015-12-08 17:52:41.965 ThaliTest[505:303335] jxcore: connect Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:41.965 ThaliTest[505:303335] client session: connect
,2015-12-08 17:52:41.965 ThaliTest[505:303335] client session: stateChange:0->1 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08T16:52:41.991Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:42.285 ThaliTest[505:304132] server session: not connected Apple-Iphone5-1_PT5966
,2015-12-08 17:52:42.436 ThaliTest[505:303051] multipeer session: reset timer
2015-12-08 17:52:42.437 ThaliTest[505:303051] multipeer session: stop timer
2015-12-08 17:52:42.437 ThaliTest[505:303051] multipeer session: start timer: 0x15f497a0
,2015-12-08 17:52:42.437 ThaliTest[505:303051] server session: connect
2015-12-08 17:52:42.439 ThaliTest[505:303051] server session: stateChange:0->1 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:42.447 ThaliTest[505:303051] server: accepting invitation Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:45.102 ThaliTest[505:304080] client session: connected
,2015-12-08 17:52:45.105 ThaliTest[505:304080] client session: stateChange:1->2 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:45.127 ThaliTest[505:304080] client session: fireConnectCallback: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:45.128 ThaliTest[505:304080] jxcore: connect: success
2015-12-08T16:52:45.129Z SendDataConnector.js: CLIENT connected to ,52043, error: null
2015-12-08T16:52:45.129Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:45.132 ThaliTest[505:303051] client: relay established
2015-12-08 17:52:45.133 ThaliTest[505:303051] client: new accepted socket: 0x15f60b60
,2015-12-08T16:52:45.144Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:52:45.153 ThaliTest[505:304132] server session: connected
2015-12-08 17:52:45.153 ThaliTest[505:304132] server session: stateChange:1->2 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:45.190 ThaliTest[505:303051] server relay: connected (to port: 52035)
,2015-12-08T16:52:45.457Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:45.502Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-08T16:52:45.505Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-08T16:52:45.526Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:45.526Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:45.527Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:45.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:45.528 ThaliTest[505:303335] jxcore: disconnect
,2015-12-08 17:52:45.529 ThaliTest[505:303335] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:45.529 ThaliTest[505:303335] client session: disconnect
,2015-12-08 17:52:45.530 ThaliTest[505:303335] client session: stateChange:2->0 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:45.597 ThaliTest[505:303335] jxcore: disconnect: success
,2015-12-08T16:52:45.598Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6318.xt9ojg==
,---- round done--------
,device[3]: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08T16:52:45.599Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08T16:52:45.600Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08T16:52:45.600Z SendDataConnector.js: do connect now
,2015-12-08 17:52:45.600 ThaliTest[505:303335] jxcore: connect Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:45.601 ThaliTest[505:303335] client session: connect
,2015-12-08 17:52:45.602 ThaliTest[505:303335] client session: stateChange:0->1 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08T16:52:45.612Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:45.663 ThaliTest[505:304080] server session: not connected Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:48.348 ThaliTest[505:304090] client session: connected
,2015-12-08 17:52:48.348 ThaliTest[505:304090] client session: stateChange:1->2 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:48.567 ThaliTest[505:304089] client session: fireConnectCallback: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:52:48.570 ThaliTest[505:304089] jxcore: connect: success
2015-12-08T16:52:48.571Z SendDataConnector.js: CLIENT connected to ,52047, error: null
2015-12-08T16:52:48.572Z SendDataConnector.js: CLIENT starting client 
2015-12-08 17:52:48.577 ThaliTest[505:303051] client: relay established
2015-12-08 17:52:48.577 ThaliTest[505:303051] client: new accepted socket: 0x15e8bd10
,2015-12-08T16:52:48.589Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:49.163Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:49.164Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:49.165Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:49.165Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:49.166 ThaliTest[505:303335] jxcore: disconnect
,2015-12-08 17:52:49.167 ThaliTest[505:303335] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:49.168 ThaliTest[505:303335] client session: disconnect
,2015-12-08 17:52:49.169 ThaliTest[505:303335] client session: stateChange:2->0 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:49.244 ThaliTest[505:303335] jxcore: disconnect: success
,2015-12-08T16:52:49.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5978.hVAckA==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT1987","time":13351,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT5966.KrGtFw==","time":4817,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT6318.xt9ojg==","time":3563,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5978.hVAckA==","time":3564,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4817 ms, 99% : 4817 ms, 95 : 4817 ms, 90% : 4817 ms.
,Result count 3, range 3563 ms to  4817 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-08T16:52:49.255Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:49.255Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:53:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:53:12.489 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:53:12.493 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:53:12.493 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:53:42.439 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:53:42.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:53:42.483 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:53:42.484 ThaliTest[505:303051] client: fou,nd peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:53:56.950 ThaliTest[505:303051] client: lost peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:53:56.950 ThaliTest[505:303051] client session: onPeerLost: Apple-Iphone5s-1_PT5978.hVAckA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT5978.hVAckA==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:54:12.481 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:54:12.488 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:54:12.489 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5978.hVAckA==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:19.831 ThaliTest[505:303051] client: lost peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:54:19.832 ThaliTest[505:303051] client session: onPeerLost: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:22.731 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:54:42.486 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:54:42.490 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:54:42.490 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:55:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:55:12.482 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:55:12.483 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:55:12.484 ThaliTest[505:303051] client: fou,nd peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:20.663 ThaliTest[505:303051] client: lost peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:55:20.664 ThaliTest[505:303051] client session: onPeerLost: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":false}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:36.435 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:55:42.479 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:55:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:56:12.437 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:56:12.475 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:56:12.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:56:12.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:56:33.113 ThaliTest[505:303051] client: lost peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:56:33.113 ThaliTest[505:303051] client session: onPeerLost: Apple-Iphone5-1_PT5966.KrGtFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":false}]
,2015-12-08 17:56:33.165 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5966.KrGtFw==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:56:42.438 ThaliTest[505:303051] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 17:57:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:57:12.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:57:12.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:57:12.874 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:57:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:57:42.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:57:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:57:42.483 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:58:12.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:58:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:58:12.485 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:42.438 ThaliTest[505:303051] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:42.715 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:58:42.715 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:58:42.717 ThaliTest[505:303051] client: fo,und peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:59:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:59:12.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:59:12.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:59:13.363 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:59:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 17:59:42.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 17:59:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:59:42.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:00:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:00:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:00:12.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:00:12.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:00:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:00:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:00:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:00:42.479 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:01:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:01:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:01:12.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:01:12.481 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:01:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:01:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:01:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:01:42.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:02:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:02:12.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:02:12.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:02:12.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:02:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:02:42.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:02:42.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:02:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:03:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:03:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:03:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:03:12.479 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:03:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:03:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:03:42.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:03:42.481 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:04:12.438 ThaliTest[505:303051] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:04:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:04:42.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:04:42.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:04:42.480 ThaliTest[505:303051] client: fou,nd peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:05:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:05:12.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:05:12.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:05:12.870 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:05:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:05:42.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:05:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:05:42.881 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:06:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:06:12.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:06:12.480 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:06:12.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:06:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:06:42.476 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:06:42.482 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:06:42.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:07:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:07:12.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:07:12.482 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:07:12.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:07:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:07:42.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:07:42.478 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:07:42.484 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:08:12.437 ThaliTest[505:303051] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:08:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:08:42.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:08:42.477 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:08:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:09:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:09:12.476 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:09:12.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:09:12.555 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:09:42.438 ThaliTest[505:303051] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:10:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:10:12.476 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:10:12.478 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:10:12.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:10:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:10:42.479 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:10:42.480 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:10:42.482 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:11:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:11:12.476 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:11:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:11:13.006 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:11:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:11:42.478 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:11:42.481 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:11:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:12:12.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:12:12.477 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
2015-12-08 18:12:12.478 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:12:12.479 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:12:42.438 ThaliTest[505:303051] multipeer session: restart
,2015-12-08 18:12:42.476 ThaliTest[505:303051] client: found peer: Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 18:12:42.481 ThaliTest[505:303051] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:12:42.481 ThaliTest[505:303051] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server

```
