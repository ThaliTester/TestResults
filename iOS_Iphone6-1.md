#### Test 519863408c638e9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1FD8FF65-AF8D-445E-B465-F772EF7C0BBD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1FD8FF65-AF8D-445E-B465-F772EF7C0BBD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BC5B003A-36A6-465D-BAF3-CBD05197755D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58423"
,(lldb)     command script import "/tmp/1FD8FF65-AF8D-445E-B465-F772EF7C0BBD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 11:47:31.252 ThaliTest[2243:1951148] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0E207915-AAB0-43CA-B85A-257C746DCD7B/Library/Cookies/Cookies.binarycookies
,2015-12-01 11:47:31.648 ThaliTest[2243:1951148] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 11:47:31.649 ThaliTest[2243:1951148] Multi-tasking -> Device: YES, App: YES
,2015-12-01 11:47:31.657 ThaliTest[2243:1951148] Unlimited access to network resources
,2015-12-01 11:47:31.663 ThaliTest[2243:1951148] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 11:47:35.258 ThaliTest[2243:1951148] Resetting plugins due to page load.
,2015-12-01 11:47:35.591 ThaliTest[2243:1951148] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/BC5B003A-36A6-465D-BAF3-CBD05197755D/ThaliTest.app/www/index.html
,2015-12-01 11:47:35.713 ThaliTest[2243:1951148] JXcore Cordova plugin initializing
,2015-12-01 11:47:35.714 ThaliTest[2243:1951308] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT127
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 63801
,2015-12-01 11:54:33.985 ThaliTest[2243:1951308] jxcore: startBroadcasting
,2015-12-01 11:54:33.998 ThaliTest[2243:1951308] server: starting Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:34.001 ThaliTest[2243:1951308] multipeer session: start timer: 0x18a43480
,2015-12-01 11:54:34.004 ThaliTest[2243:1951308] THEMultipeerSession initialized peer Apple-Iphone6-1_PT127
,2015-12-01 11:54:34.005 ThaliTest[2243:1951308] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-01T10:54:34.007Z SendDataTCPServer.js: TCP/IP server is bound to port: 63801
,2015-12-01 11:54:34.231 ThaliTest[2243:1951148] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9146.afM/PQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,device[1]: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:34.234Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:34.234 ThaliTest[2243:1951148] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-,12-01T10:54:34.234Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01T10:54:34.234Z SendDataConnector.js: do connect now
,2015-12-01 11:54:34.235 ThaliTest[2243:1951308] jxcore: connect Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:34.235 ThaliTest[2243:1951308] client session: connect
2015-12-01 11:54:34.235 ThaliTest[2243:1951308] client session: stateChange:0->1 Appl,e-Iphone5s-1_PT9146.afM/PQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:34.321 ThaliTest[2243:1951148] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9531.MSI13Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:36.664 ThaliTest[2243:1952044] client session: connected
2015-12-01 11:54:36.665 ThaliTest[2243:1952044] client session: stateChange:1->2 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:36.670 ThaliTest[2243:1952044] client session: fireConnectCallback: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:36.671 ThaliTest[2243:1952044] jxcore: connect: success
,2015-12-01T10:54:36.673Z SendDataConnector.js: CLIENT connected to 63804, error: null
,2015-12-01T10:54:36.674Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:36.679 ThaliTest[2243:1951148] client: relay established
2015-12-01 11:54:36.679 ThaliTest[2243:1951148] client: new accepted socket: 0x14698c40
,2015-12-01T10:54:36.696Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:37.237Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-01T10:54:37.250Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T10:54:37.263Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T10:54:37.276Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T10:54:37.302Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T10:54:37.302Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:37.304Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:54:37.304Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 11:54:37.305 ThaliTest[2243:1951308] jxcore: disconnect
2015-12-01 11:54:37.305 ThaliTest[2243:1951308] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:54:37.305 ThaliTest[2243:1951308] client session: disconnect
2015-12-01 11:54:37.305 ThaliTest[2243:1951308] client session: stateChange:2->0 Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:37.308 ThaliTest[2243:1951308] jxcore: disconnect: success
,2015-12-01T10:54:37.310Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9146.afM/PQ==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:54:37.312Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:37.312Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01T10:54:37.313Z SendDataConnector.js: do connect now
,2015-12-01 11:54:37.313 ThaliTest[2243:1951308] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:37.313 ThaliTest[2243:1951308] client session: connect
2015-12-01 11:54:37.314 ThaliTest[2243:1951308] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.032 ThaliTest[2243:1952036] client session: connected
2015-12-01 11:54:40.033 ThaliTest[2243:1952036] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.037 ThaliTest[2243:1952033] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:40.038 ThaliTest[2243:1952033] jxcore: connect: success
2015-12-01T10:54:40.040Z SendDataConnector.js: CLIENT connected, to 63807, error: null
2015-12-01T10:54:40.041Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:40.044 ThaliTest[2243:1951148] client: relay established
2015-12-01 11:54:40.045 ThaliTest[2243:1951148] client: new accepted socket: 0x18d5e6d0
,2015-12-01T10:54:40.057Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:40.365Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T10:54:40.378Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T10:54:40.378Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:40.379Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:54:40.379Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 11:54:40.379 ThaliTest[2243:1951308] jxcore: disconnect
2015-12-01 11:54:40.380 ThaliTest[2243:1951308] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:40.380 ThaliTest[2243:1951308] client session: disconnect
2015-12-01 11:54:40.380 ThaliTest[2243:1951308] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.382 ThaliTest[2243:1951308] jxcore: disconnect: success
2015-12-01T10:54:40.382Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
---- round done--------
device[3]: Apple-Iphone5-1_PT9531.,MSI13Q==
2015-12-01T10:54:40.383Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:54:40.383Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01T10:54:40.383Z SendDataConnector.js: do connect now
2015-12-01 11:54:40.383 ThaliTest[2243:1951308] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:40.384 ThaliTest[2243:1951308] client session: connect
,2015-12-01 11:54:40.384 ThaliTest[2243:1951308] client session: stateChange:0->1 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:40.965 ThaliTest[2243:1951148] multipeer session: reset timer
2015-12-01 11:54:40.965 ThaliTest[2243:1951148] multipeer session: stop timer
2015-12-01 11:54:40.966 ThaliTest[2243:1951148] multipeer session: start timer: 0x18a43480
2015-,12-01 11:54:40.967 ThaliTest[2243:1951148] server session: connect
2015-12-01 11:54:40.967 ThaliTest[2243:1951148] server session: stateChange:0->1 Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:40.977 ThaliTest[2243:1951148] server: accepting invitation Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:43.105 ThaliTest[2243:1952033] server session: connected
2015-12-01 11:54:43.106 ThaliTest[2243:1952033] server session: stateChange:1->2 Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:43.112 ThaliTest[2243:1951148] server relay: connected (to port: 63801)
,2015-12-01T10:54:43.122Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:43.426Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-01T10:54:43.440Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-01T10:54:43.457Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-01T10:54:43.473Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-01T10:54:43.486Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 11:54:43.493 ThaliTest[2243:1952036] client session: connected
,2015-12-01 11:54:43.495 ThaliTest[2243:1952036] client session: stateChange:1->2 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:43.499 ThaliTest[2243:1952036] client session: fireConnectCallback: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:43.500 ThaliTest[2243:1952036] jxcore: connect: success
,2015-12-01T10:54:43.502Z SendDataConnector.js: CLIENT connected to 63811, error: null
,2015-12-01T10:54:43.503Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:43.506 ThaliTest[2243:1951148] client: relay established
2015-12-01 11:54:43.506 ThaliTest[2243:1951148] client: new accepted socket: 0x1898a740
,2015-12-01 11:54:43.518 ThaliTest[2243:1952059] server session: not connected Apple-Iphone5s-1_PT9146
,2015-12-01T10:54:43.519Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:43.971Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T10:54:43.984Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T10:54:43.997Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T10:54:43.997Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:43.998Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:54:43.998Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:54:43.998 ThaliTest[2243:1951308] jxcore: disconnect
2015-12-01 11:54:43.999 ThaliTest[2243:1951308] client session: disconnectFromPeer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:44.000 ThaliTest[2243:1951308] client session: disconnect
,2015-12-01 11:54:44.000 ThaliTest[2243:1951308] client session: stateChange:2->0 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:44.058 ThaliTest[2243:1951308] jxcore: disconnect: success
,2015-12-01T10:54:44.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,0}]}
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT127","time":10094,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT9146.afM/PQ==","time":3069,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7493.hpeH+A==","time":3066,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9531.MSI13Q==","time":3614,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":10000,sendList : 100% : 3614 ms, 99% : 3614 ms, 95 : 3614 ms, 90% : 3614 ms.
,Result count 3, range 3066 ms to  3614 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-01T10:54:44.065Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T10:54:44.065Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:55:10.968 ThaliTest[2243:1951148] multipeer session: restart
,2015-12-01 11:55:10.988 ThaliTest[2243:1951148] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:55:10.989 ThaliTest[2243:1951148] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
2015-12-01 11:55:10.990 ThaliTest[2243:1951148] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:40.559 ThaliTest[2243:1951148] client: found peer: Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:55:40.968 ThaliTest[2243:1951148] multipeer session: restart
2015-12-01 11:55:40.974 ThaliTest[2243:1951148] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** First throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x3e5e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 2243 stopped
* thread #1: tid = 0x1dc5ac, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x1dc5ac, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x35e93cc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x35db0908 libsystem_c.dylib`abort + 76
    frame #3: 0x350a79c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x350c1670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x35798f24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x350bede2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x350be8ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x35798dd2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x26d3f29c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x26d3f012 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x2e7ca200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2a50ba08 UIKit`UIApplicationMain + 1440
    frame #13: 0x0003e5e2 ThaliTest`main + 50

```
