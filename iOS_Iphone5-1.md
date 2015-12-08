#### Test 52971095c1e9930_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/058023C8-FFA1-4E57-BBB3-2927EDD27E59/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/058023C8-FFA1-4E57-BBB3-2927EDD27E59/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52971095c1e9930/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0BFF6D76-0823-41C3-90A3-C24215B66B43/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51258"
,(lldb)     command script import "/tmp/058023C8-FFA1-4E57-BBB3-2927EDD27E59/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-08 17:44:12.918 ThaliTest[459:351956] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0315219-847B-4FA9-AAAB-EDE182C420A2/Library/Cookies/Cookies.binarycookies
,2015-12-08 17:44:13.408 ThaliTest[459:351956] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-08 17:44:13.409 ThaliTest[459:351956] Multi-tasking -> Device: YES, App: YES
,2015-12-08 17:44:13.416 ThaliTest[459:351956] Unlimited access to network resources
,2015-12-08 17:44:13.426 ThaliTest[459:351956] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-08 17:44:24.068 ThaliTest[459:351956] Resetting plugins due to page load.
,2015-12-08 17:44:27.892 ThaliTest[459:351956] Finished load of: file:///var/mobile/Containers/Bundle/Application/0BFF6D76-0823-41C3-90A3-C24215B66B43/ThaliTest.app/www/index.html
,2015-12-08 17:44:28.101 ThaliTest[459:351956] JXcore Cordova plugin initializing
,2015-12-08 17:44:28.103 ThaliTest[459:352148] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5-1_PT5966
,attempting to connect to test coordinator
,check test folder
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
serverPort is 52651
,2015-12-08 17:52:35.939 ThaliTest[459:352148] jxcore: startBroadcasting
,2015-12-08 17:52:35.952 ThaliTest[459:352148] server: starting Apple-Iphone5-1_PT5966.KrGtFw==
,2015-12-08 17:52:35.954 ThaliTest[459:352148] multipeer session: start timer: 0x1de1e440
2015-12-08 17:52:35.954 ThaliTest[459:352148] THEMultipeerSession initialized peer Apple-Iphone5-1_PT5966
2015-12-08 17:52:35.955 ThaliTest[459:352148] jxcore: start,Broadcasting: success
StartBroadcasting started ok
2015-12-08T16:52:35.956Z SendDataTCPServer.js: TCP/IP server is bound to port: 52651
,2015-12-08 17:52:37.206 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1987.2bYzJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08T16:52:37.210Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08T16:52:37.210Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1987.2bYzJA==
20,15-12-08T16:52:37.210Z SendDataConnector.js: do connect now
2015-12-08 17:52:37.211 ThaliTest[459:352148] jxcore: connect Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:37.211 ThaliTest[459:352148] client session: connect
2015-12-08 17:52:37.211 ThaliTest[459:352148] client session: stateChange:0->1 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:37.266 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6318.xt9ojg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:37.660 ThaliTest[459:351956] multipeer session: reset timer
2015-12-08 17:52:37.660 ThaliTest[459:351956] multipeer session: stop timer
2015-12-08 17:52:37.660 ThaliTest[459:351956] multipeer session: start timer: 0x1de1e440
2015-12-08 17:52:37.660 ThaliTest[459:351956] server session: connect
2015-12-08 17:52:37.660 ThaliTest[459:351956] server session: stateChange:0->1 Apple-Iphone6-1_PT1987
,2015-12-08 17:52:37.667 ThaliTest[459:351956] server: accepting invitation Apple-Iphone6-1_PT1987
,2015-12-08 17:52:37.791 ThaliTest[459:351956] multipeer session: reset timer
2015-12-08 17:52:37.791 ThaliTest[459:351956] multipeer session: stop timer
2015-12-08 17:52:37.792 ThaliTest[459:351956] multipeer session: start timer: 0x1de1e440
2015-12-08 ,17:52:37.792 ThaliTest[459:351956] server session: connect
2015-12-08 17:52:37.793 ThaliTest[459:351956] server session: stateChange:0->1 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:37.804 ThaliTest[459:351956] server: accepting invitation Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:38.289 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5978.hVAckA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-08 17:52:40.746 ThaliTest[459:353505] client session: connected
2015-12-08 17:52:40.748 ThaliTest[459:353505] client session: stateChange:1->2 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:40.761 ThaliTest[459:353507] client session: fireConnectCallback: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:40.762 ThaliTest[459:353507] jxcore: connect: success
,2015-12-08T16:52:40.763Z SendDataConnector.js: CLIENT connected to 52654, error: null
2015-12-08T16:52:40.764Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:40.767 ThaliTest[459:351956] client: relay established
2015-12-08 17:52:40.767 ThaliTest[459:351956] client: new accepted socket: 0x1dd330d0
,2015-12-08 17:52:40.775 ThaliTest[459:353507] server session: connected
2015-12-08 17:52:40.776 ThaliTest[459:353507] server session: stateChange:1->2 Apple-Iphone6-1_PT1987
,2015-12-08T16:52:40.782Z SendDataTCPServer.js: TCP/IP server connected
2015-12-08 17:52:40.783 ThaliTest[459:351956] server relay: connected (to port: 52651)
,2015-12-08T16:52:40.784Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08 17:52:40.921 ThaliTest[459:353505] server session: connected
,2015-12-08 17:52:40.922 ThaliTest[459:353505] server session: stateChange:1->2 Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:41.220 ThaliTest[459:351956] server relay: connected (to port: 52651)
,2015-12-08T16:52:41.345Z SendDataTCPServer.js: TCP/IP server connected
2015-12-08T16:52:41.346Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-08T16:52:41.363Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-08T16:52:41.474Z SendDataTCPServer.js: TCP/IP server has received 35100 bytes of data
,2015-12-08T16:52:41.488Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-08T16:52:41.504Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-08T16:52:41.728Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-08T16:52:41.730Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-08T16:52:41.743Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08T16:52:41.749Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-08T16:52:41.766Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:41.941 ThaliTest[459:353532] server session: not connected Apple-Iphone6-1_PT1987
,2015-12-08T16:52:41.976Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:41.976Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:41.979Z SendDataConnector.js: CLIENT Stop now
,2015-12-08T16:52:41.979Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:41.981 ThaliTest[459:352148] jxcore: disconnect
2015-12-08 17:52:41.981 ThaliTest[459:352148] client session: disconnectFromPeer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:52:41.982 ThaliTest[459:352148] client session: disconnect
2,015-12-08 17:52:41.982 ThaliTest[459:352148] client session: stateChange:2->0 Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:52:41.997 ThaliTest[459:352148] jxcore: disconnect: success
2015-12-08T16:52:41.998Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1987.2bYzJA==
---- round done--------
device[2]: Apple-IpadAir2-1_PT6318.xt,9ojg==
2015-12-08T16:52:42.000Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:42.000Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08T16:52:42.001Z SendDataCon,nector.js: do connect now
,2015-12-08 17:52:42.002 ThaliTest[459:352148] jxcore: connect Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:42.006 ThaliTest[459:352148] client session: connect
2015-12-08 17:52:42.006 ThaliTest[459:352148] client session: stateChange:0->1 Apple-Ipad,Air2-1_PT6318.xt9ojg==
,2015-12-08 17:52:42.249 ThaliTest[459:353509] server session: not connected Apple-Iphone5s-1_PT5978
,2015-12-08 17:52:45.075 ThaliTest[459:353509] client session: connected
2015-12-08 17:52:45.075 ThaliTest[459:353509] client session: stateChange:1->2 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:45.133 ThaliTest[459:351956] multipeer session: reset timer
2015-12-08 17:52:45.133 ThaliTest[459:351956] multipeer session: stop timer
2015-12-08 17:52:45.134 ThaliTest[459:351956] multipeer session: start timer: 0x1de1e440
2015-12-08 ,17:52:45.134 ThaliTest[459:351956] server session: connect
2015-12-08 17:52:45.134 ThaliTest[459:351956] server session: stateChange:0->1 Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:45.142 ThaliTest[459:351956] server: accepting invitation Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:45.148 ThaliTest[459:353511] client session: fireConnectCallback: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:45.148 ThaliTest[459:353511] jxcore: connect: success
2015-12-08T16:52:45.149Z SendDataConnector.js: CLIENT connected to ,52659, error: null
2015-12-08T16:52:45.149Z SendDataConnector.js: CLIENT starting client 
2015-12-08 17:52:45.153 ThaliTest[459:351956] client: relay established
2015-12-08 17:52:45.153 ThaliTest[459:351956] client: new accepted socket: 0x1dd24530
,2015-12-08T16:52:45.166Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:46.056Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-08T16:52:46.117Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:46.117Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:46.119Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:46.120Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:46.120 ThaliTest[459:352148] jxcore: disconnect
2015-12-08 17:52:46.121 ThaliTest[459:352148] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:52:46.121 ThaliTest[459:352148] client session: disconnect
,2015-12-08 17:52:46.121 ThaliTest[459:352148] client session: stateChange:2->0 Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:52:46.132 ThaliTest[459:352148] jxcore: disconnect: success
2015-12-08T16:52:46.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6318.xt9ojg==
---- round done--------
device[3]: Apple-Iphone5s-1_PT5978.h,VAckA==
2015-12-08T16:52:46.134Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08T16:52:46.134Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08T16:52:46.135Z SendDataCo,nnector.js: do connect now
,2015-12-08 17:52:46.135 ThaliTest[459:352148] jxcore: connect Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:46.140 ThaliTest[459:352148] client session: connect
2015-12-08 17:52:46.141 ThaliTest[459:352148] client session: stateChange:0->1 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:47.785 ThaliTest[459:353505] server session: connected
2015-12-08 17:52:47.785 ThaliTest[459:353505] server session: stateChange:1->2 Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:47.800 ThaliTest[459:351956] server relay: connected (to port: 52651)
,2015-12-08T16:52:47.812Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-08T16:52:48.089Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-08T16:52:48.107Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-08T16:52:48.121Z SendDataTCPServer.js: TCP/IP server has received 93602 bytes of data
,2015-12-08T16:52:48.136Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-08 17:52:48.160 ThaliTest[459:353505] server session: not connected Apple-IpadAir2-1_PT6318
,2015-12-08 17:52:49.093 ThaliTest[459:353509] client session: connected
2015-12-08 17:52:49.093 ThaliTest[459:353509] client session: stateChange:1->2 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:49.179 ThaliTest[459:353505] client session: fireConnectCallback: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:52:49.179 ThaliTest[459:353505] jxcore: connect: success
2015-12-08T16:52:49.180Z SendDataConnector.js: CLIENT connected to ,52663, error: null
2015-12-08T16:52:49.180Z SendDataConnector.js: CLIENT starting client 
,2015-12-08 17:52:49.183 ThaliTest[459:351956] client: relay established
2015-12-08 17:52:49.183 ThaliTest[459:351956] client: new accepted socket: 0x1dd40fa0
,2015-12-08T16:52:49.198Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-08T16:52:49.791Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-08T16:52:49.842Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-08T16:52:50.630Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-08T16:52:50.631Z SendDataConnector.js: got all data for this round
,2015-12-08T16:52:50.632Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:50.632Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:52:50.632 ThaliTest[459:352148] jxcore: disconnect
2015-12-08 17:52:50.633 ThaliTest[459:352148] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:50.633 ThaliTest[459:352148] client session: disconnect
2015-12-08 17:52:50.634 ThaliTest[459:352148] client session: stateChange:2->0 Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:52:50.648 ThaliTest[459:352148] jxcore: disconnect: success
2015-12-08T16:52:50.651Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5978.hVAckA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5-1_PT5966","time":14723,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1987.2bYzJA==","time":4768,"result":"OK","connections":1,"doneRo,unds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT6318.xt9ojg==","time":4118,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5978.hVAckA==","time":4497,"result,":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4768 ms, 99% : 4768 ms, 95 : 4768 ms, 90% : 4768 ms.
,Result count 3, range 4118 ms to  4768 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-08T16:52:50.662Z SendDataConnector.js: CLIENT Stop now
2015-12-08T16:52:50.662Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-08 17:53:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:53:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:53:45.170 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:53:45.170 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:53:45.171 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-08 17:54:15.134 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:54:15.173 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:54:15.173 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 17:54:15.178 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:54:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:54:45.172 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:54:45.173 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:54:45.173 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,Wifi toggled for connection repairment
,2015-12-08 17:55:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:55:15.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:55:15.170 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:55:15.170 ThaliTest[459:351956] client: fou,nd peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:55:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:55:45.168 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 17:55:45.171 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 17:55:45.332 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,Wifi toggled for connection repairment
,2015-12-08 17:56:15.135 ThaliTest[459:351956] multipeer session: restart
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
,2015-12-08 17:56:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:56:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:56:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:56:45.170 ThaliTest[459:351956] client: fou,nd peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 17:57:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:57:15.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:57:15.169 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:57:15.170 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 17:57:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:57:45.176 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:57:45.176 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 17:57:45.177 ThaliTest[459:351956] client: fou,nd peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 17:58:15.135 ThaliTest[459:351956] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 17:58:45.164 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:58:45.164 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 17:58:45.667 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 17:59:15.135 ThaliTest[459:351956] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,2015-12-08 17:59:15.503 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 17:59:15.504 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 17:59:15.504 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 17:59:45.135 ThaliTest[459:351956] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 18:00:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:00:15.165 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:00:15.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:00:15.169 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 18:00:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:00:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:00:45.171 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:00:45.547 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:01:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:01:15.166 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:01:15.167 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:01:15.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
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
,2015-12-08 18:01:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:01:45.165 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:01:45.166 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:01:45.469 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:02:15.135 ThaliTest[459:351956] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:02:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:02:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:02:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:02:45.168 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,2015-12-08 18:03:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:03:15.166 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:03:15.166 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:03:15.382 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
Error type "connect_error" when connecting to the test server
,2015-12-08 18:03:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:03:45.171 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:03:45.172 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:03:45.172 ThaliTest[459:351956] client: fo,und peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:04:15.135 ThaliTest[459:351956] multipeer session: restart
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
Error type "connect_error" when connecting to the test server
,2015-12-08 18:04:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:04:45.166 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:04:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:04:45.168 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:05:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:05:15.169 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:05:15.169 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:05:15.607 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:05:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:05:45.165 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:05:45.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:05:45.363 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
,2015-12-08 18:06:15.135 ThaliTest[459:351956] multipeer session: restart
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
,2015-12-08 18:06:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:06:45.165 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:06:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:06:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
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
,2015-12-08 18:07:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:07:15.166 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:07:15.167 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:07:15.173 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:07:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:07:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:07:45.167 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:07:45.174 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:08:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:08:15.166 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:08:15.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,2015-12-08 18:08:15.196 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
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
,2015-12-08 18:08:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:08:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:08:45.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
2015-12-08 18:08:45.169 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
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
,2015-12-08 18:09:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:09:15.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:09:15.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:09:15.649 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:09:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:09:45.169 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:09:45.170 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:09:45.172 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,2015-12-08 18:10:15.135 ThaliTest[459:351956] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:10:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:10:45.164 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
,2015-12-08 18:10:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:10:45.169 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:11:15.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:11:15.167 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:11:15.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:11:15.169 ThaliTest[459:351956] client: fou,nd peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:11:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:11:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:11:45.168 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
,2015-12-08 18:11:45.175 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-08 18:12:15.135 ThaliTest[459:351956] multipeer session: restart
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
,2015-12-08 18:12:45.135 ThaliTest[459:351956] multipeer session: restart
,2015-12-08 18:12:45.610 ThaliTest[459:351956] client: found peer: Apple-Iphone5s-1_PT5978.hVAckA==
2015-12-08 18:12:45.610 ThaliTest[459:351956] client: found peer: Apple-Iphone6-1_PT1987.2bYzJA==
2015-12-08 18:12:45.610 ThaliTest[459:351956] client: found peer: Apple-IpadAir2-1_PT6318.xt9ojg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server

```
