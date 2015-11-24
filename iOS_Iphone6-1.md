#### Test 5133502802397d9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0A45331A-876B-4498-939E-CB006B537241/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0A45331A-876B-4498-939E-CB006B537241/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502802397d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/99A8C850-E7B7-4AA2-8EEA-92819D90E32E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54830"
,(lldb)     command script import "/tmp/0A45331A-876B-4498-939E-CB006B537241/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 17:03:42.581 ThaliTest[1567:1204218] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1564005F-5783-49F3-AC76-914DC2D6EABA/Library/Cookies/Cookies.binarycookies
,2015-11-24 17:03:42.975 ThaliTest[1567:1204218] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 17:03:42.976 ThaliTest[1567:1204218] Multi-tasking -> Device: YES, App: YES
,2015-11-24 17:03:42.984 ThaliTest[1567:1204218] Unlimited access to network resources
,2015-11-24 17:03:42.990 ThaliTest[1567:1204218] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 17:03:46.615 ThaliTest[1567:1204218] Resetting plugins due to page load.
,2015-11-24 17:03:46.998 ThaliTest[1567:1204218] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/99A8C850-E7B7-4AA2-8EEA-92819D90E32E/ThaliTest.app/www/index.html
,2015-11-24 17:03:47.124 ThaliTest[1567:1204218] JXcore Cordova plugin initializing
2015-11-24 17:03:47.124 ThaliTest[1567:1204353] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT1630
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 61284
,2015-11-24 17:10:23.641 ThaliTest[1567:1204353] jxcore: startBroadcasting
,2015-11-24 17:10:23.653 ThaliTest[1567:1204353] server: starting Apple-Iphone6-1_PT1630.4rgQcA==
,2015-11-24 17:10:23.654 ThaliTest[1567:1204353] multipeer session: start timer: 0x1c324960
,2015-11-24 17:10:23.655 ThaliTest[1567:1204353] THEMultipeerSession initialized peer Apple-Iphone6-1_PT1630
2015-11-24 17:10:23.656 ThaliTest[1567:1204353] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2015-11-24T16:10:23.657Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-24 17:10:24.328 ThaliTest[1567:1204218] multipeer session: reset timer
2015-11-24 17:10:24.329 ThaliTest[1567:1204218] multipeer session: stop timer
2015-11-24 17:10:24.329 ThaliTest[1567:1204218] multipeer session: start timer: 0x1c324960
2015-,11-24 17:10:24.330 ThaliTest[1567:1204218] server session: connect
2015-11-24 17:10:24.331 ThaliTest[1567:1204218] server session: stateChange:0->1 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:24.339 ThaliTest[1567:1204218] server: accepting invitation Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:24.381 ThaliTest[1567:1204218] client: found peer: Apple-Iphone5s-1_PT8445.HcGyQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8445.HcGyQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,device[1]: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:24.388Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24T16:10:24.389Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8445.HcGyQA==,
2015-11-24T16:10:24.389Z SendDataConnector.js: do connect now
,2015-11-24 17:10:24.390 ThaliTest[1567:1204353] jxcore: connect Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24 17:10:24.391 ThaliTest[1567:1204353] client session: connect
,2015-11-24 17:10:24.391 ThaliTest[1567:1204353] client session: stateChange:0->1 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:24.652 ThaliTest[1567:1204218] multipeer session: reset timer
2015-11-24 17:10:24.652 ThaliTest[1567:1204218] multipeer session: stop timer
2015-11-24 17:10:24.652 ThaliTest[1567:1204218] multipeer session: start timer: 0x1c324960
2015-,11-24 17:10:24.652 ThaliTest[1567:1204218] server session: connect
2015-11-24 17:10:24.652 ThaliTest[1567:1204218] server session: stateChange:0->1 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:24.656 ThaliTest[1567:1204218] server: accepting invitation Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:24.850 ThaliTest[1567:1204218] client: found peer: Apple-IpadAir2-1_PT7208.gEcfnw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7208.gEcfnw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:25.012 ThaliTest[1567:1204218] client: found peer: Apple-Iphone5-1_PT7498.cV5UxA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7498.cV5UxA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-24 17:10:26.451 ThaliTest[1567:1204920] server session: connected
2015-11-24 17:10:26.452 ThaliTest[1567:1204920] server session: stateChange:1->2 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:26.481 ThaliTest[1567:1204218] server relay: connected (to port: 61284)
,2015-11-24T16:10:26.489Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:26.605Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-24T16:10:26.622Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-24T16:10:26.639Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-24T16:10:26.655Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:26.677 ThaliTest[1567:1204920] server session: not connected Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:26.935 ThaliTest[1567:1204919] client session: connected
2015-11-24 17:10:26.936 ThaliTest[1567:1204919] client session: stateChange:1->2 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:26.945 ThaliTest[1567:1204919] client session: fireConnectCallback: Apple-Iphone5s-1_PT8445.HcGyQA==
2015-11-24 17:10:26.946 ThaliTest[1567:1204919] jxcore: connect: success
,2015-11-24T16:10:26.949Z SendDataConnector.js: CLIENT connected to 61288, error: null
,2015-11-24T16:10:26.950Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:26.953 ThaliTest[1567:1204218] client: relay established
2015-11-24 17:10:26.953 ThaliTest[1567:1204218] client: new accepted socket: 0x1c316170
,2015-11-24T16:10:26.966Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:27.081Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-24T16:10:27.179Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-24T16:10:27.192Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:27.192Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:27.193Z SendDataConnector.js: CLIENT Stop now
,2015-11-24T16:10:27.194Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:27.194 ThaliTest[1567:1204353] jxcore: disconnect
,2015-11-24 17:10:27.196 ThaliTest[1567:1204353] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:27.197 ThaliTest[1567:1204353] client session: disconnect
,2015-11-24 17:10:27.197 ThaliTest[1567:1204353] client session: stateChange:2->0 Apple-Iphone5s-1_PT8445.HcGyQA==
,2015-11-24 17:10:27.255 ThaliTest[1567:1204353] jxcore: disconnect: success
,2015-11-24T16:10:27.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8445.HcGyQA==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:27.257Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:27.257Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24T16:10:27.258Z SendDataConnector.js: do connect now
,2015-11-24 17:10:27.258 ThaliTest[1567:1204353] jxcore: connect Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:27.259 ThaliTest[1567:1204353] client session: connect
,2015-11-24 17:10:27.259 ThaliTest[1567:1204353] client session: stateChange:0->1 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:27.480 ThaliTest[1567:1204218] multipeer session: reset timer
2015-11-24 17:10:27.480 ThaliTest[1567:1204218] multipeer session: stop timer
2015-11-24 17:10:27.480 ThaliTest[1567:1204218] multipeer session: start timer: 0x1c324960
2015-11-24 17:10:27.481 ThaliTest[1567:1204218] server session: connect
2015-11-24 17:10:27.481 ThaliTest[1567:1204218] server session: stateChange:0->1 Apple-Iphone5-1_PT7498
2015-11-24 17:10:27.482 ThaliTest[1567:1204920] server session: connected
2015-11-24 17:10:27.482 ThaliTest[1567:1204920] server session: stateChange:1->2 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:27.484 ThaliTest[1567:1204218] server: accepting invitation Apple-Iphone5-1_PT7498
,2015-11-24 17:10:27.490 ThaliTest[1567:1204218] server relay: connected (to port: 61284)
,2015-11-24T16:10:27.493Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:27.557Z SendDataTCPServer.js: TCP/IP server has received 43658 bytes of data
,2015-11-24T16:10:27.571Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:29.621 ThaliTest[1567:1204904] server session: connected
2015-11-24 17:10:29.622 ThaliTest[1567:1204904] server session: stateChange:1->2 Apple-Iphone5-1_PT7498
,2015-11-24 17:10:29.633 ThaliTest[1567:1204218] server relay: connected (to port: 61284)
,2015-11-24T16:10:29.640Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-24T16:10:29.776Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-11-24T16:10:29.790Z SendDataTCPServer.js: TCP/IP server has received 13888 bytes of data
,2015-11-24T16:10:29.804Z SendDataTCPServer.js: TCP/IP server has received 30752 bytes of data
,2015-11-24T16:10:29.822Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-11-24T16:10:29.838Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-24T16:10:30.160Z SendDataTCPServer.js: TCP/IP server has received 68448 bytes of data
,2015-11-24T16:10:30.174Z SendDataTCPServer.js: TCP/IP server has received 79360 bytes of data
,2015-11-24T16:10:30.187Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-11-24T16:10:30.200Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-24 17:10:30.224 ThaliTest[1567:1204904] server session: not connected Apple-Iphone5-1_PT7498
,2015-11-24 17:10:31.188 ThaliTest[1567:1204903] client session: connected
2015-11-24 17:10:31.189 ThaliTest[1567:1204903] client session: stateChange:1->2 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:31.197 ThaliTest[1567:1204904] client session: fireConnectCallback: Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24 17:10:31.198 ThaliTest[1567:1204904] jxcore: connect: success
2015-11-24T16:10:31.199Z SendDataConnector.js: CLIENT connected, to 61293, error: null
,2015-11-24T16:10:31.199Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:31.202 ThaliTest[1567:1204218] client: relay established
2015-11-24 17:10:31.203 ThaliTest[1567:1204218] client: new accepted socket: 0x1c651040
,2015-11-24T16:10:31.215Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:31.687Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-24T16:10:31.688Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:31.689Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:31.689Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-24 17:10:31.690 ThaliTest[1567:1204353] jxcore: disconnect
,2015-11-24 17:10:31.690 ThaliTest[1567:1204353] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7208.gEcfnw==
2015-11-24 17:10:31.691 ThaliTest[1567:1204353] client session: disconnect
2015-11-24 17:10:31.691 ThaliTest[1567:1204353] client session: stateChange:2->0 Apple-IpadAir2-1_PT7208.gEcfnw==
,2015-11-24 17:10:31.694 ThaliTest[1567:1204353] jxcore: disconnect: success
2015-11-24T16:10:31.695Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7208.gEcfnw==
---- round done--------
device[3]: Apple-Iphone5-1_PT7498.,cV5UxA==
2015-11-24T16:10:31.697Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24T16:10:31.698Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24T16:10:31.698Z SendDataConnector.js: do connect now
2015-11-24 17:10:31.698 ThaliTest[1567:1204353] jxcore: connect Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:31.699 ThaliTest[1567:1204353] client session: connect
2015-11-24 17:10:31.699 ThaliTest[1567:1204353] client session: stateChange:0->1 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:33.978 ThaliTest[1567:1204903] client session: connected
2015-11-24 17:10:33.979 ThaliTest[1567:1204903] client session: stateChange:1->2 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:33.988 ThaliTest[1567:1204903] client session: fireConnectCallback: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:33.989 ThaliTest[1567:1204903] jxcore: connect: success
2015-11-24T16:10:33.990Z SendDataConnector.js: CLIENT connected to 61296, error: null
2015-11-24T16:10:33.990Z SendDataConnector.js: CLIENT starting client 
,2015-11-24 17:10:33.993 ThaliTest[1567:1204218] client: relay established
2015-11-24 17:10:33.994 ThaliTest[1567:1204218] client: new accepted socket: 0x1c308570
,2015-11-24T16:10:34.006Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-24T16:10:34.392Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-24T16:10:34.562Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-24T16:10:34.576Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-24T16:10:34.916Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-24T16:10:35.125Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-24T16:10:35.126Z SendDataConnector.js: got all data for this round
,2015-11-24T16:10:35.127Z SendDataConnector.js: CLIENT Stop now
2015-11-24T16:10:35.128Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:35.128 ThaliTest[1567:1204353] jxcore: disconnect
2015-11-24 17:10:35.129 ThaliTest[1567:1204353] client session: disconnectFromPeer: Apple-Iphone5-1_PT7498.cV5UxA==
2015-11-24 17:10:35.130 ThaliTest[1567:1204353] client session: disconn,ect
2015-11-24 17:10:35.130 ThaliTest[1567:1204353] client session: stateChange:2->0 Apple-Iphone5-1_PT7498.cV5UxA==
,2015-11-24 17:10:35.133 ThaliTest[1567:1204353] jxcore: disconnect: success
2015-11-24T16:10:35.137Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7498.cV5UxA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT1630","time":11515,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT8445.HcGyQA==","time":2803,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7208.gEcfnw==","time":4431,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT7498.cV5UxA==","time":3428,"result":"OK","connections":1}]}
sendList : 100% : 4431 ms, 99% : 4431 ms, 95 : 4431 ms, 90% : 4431 ms.
,Result count 3, range 2803 ms to  4431 ms.
sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-11-24T16:10:35.150Z SendDataConnector.js: CLIENT Stop now
,2015-11-24T16:10:35.150Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-24 17:10:38.600 ThaliTest[1567:1204904] server session: not connected Apple-IpadAir2-1_PT7208
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-24 17:10:40.306 ThaliTest[1567:1204353] jxcore: stopBroadcasting
,2015-11-24 17:10:40.307 ThaliTest[1567:1204353] THEMultipeerSession stopping peer
,2015-11-24 17:10:40.308 ThaliTest[1567:1204353] multipeer session: stop timer
2015-11-24 17:10:40.309 ThaliTest[1567:1204353] server session: disconnect
2015-11-24 17:10:40.309 ThaliTest[1567:1204353] server session: stateChange:2->0 Apple-Iphone5-1_PT74,98
2015-11-24 17:10:40.316 ThaliTest[1567:1204353] server session: disconnect
2015-11-24 17:10:40.317 ThaliTest[1567:1204353] server session: stateChange:2->0 Apple-Iphone5s-1_PT8445
,2015-11-24 17:10:40.321 ThaliTest[1567:1204353] server session: disconnect
2015-11-24 17:10:40.322 ThaliTest[1567:1204353] server session: stateChange:2->0 Apple-IpadAir2-1_PT7208
,2015-11-24 17:10:40.388 ThaliTest[1567:1204353] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-24T16:10:40.406Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.408Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.410Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-24T16:10:40.410Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":2803,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":3428,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":4431,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT1630.4rgQ,cA==\",\"time\":2721,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":2803,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":2871,\"result\":\"OK\",\"connections\":1},{\",name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":2935,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT8445.HcGyQA==\",\"time\":3022,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT1630.4rgQcA==\",\"time\":3397,\"re,sult\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":3428,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":4431,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1,_PT8445.HcGyQA==\",\"time\":5210,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":5907,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT7498.cV5UxA==\",\"time\":7047,\"result\":\"OK\",\"connecti,ons\":1},{\"name\":\"Apple-IpadAir2-1_PT7208.gEcfnw==\",\"time\":9136,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coo
```
