#### Test 51335028c93db41_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D41114F6-F139-405D-90B6-D79C5D0333E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D41114F6-F139-405D-90B6-D79C5D0333E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/08FCACF1-5F11-4FC7-B72B-CDEB8BFF2090/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55488"
,(lldb)     command script import "/tmp/D41114F6-F139-405D-90B6-D79C5D0333E9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 13:45:04.967 ThaliTest[1668:1301589] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77E82A9E-B2A8-46EA-9EFF-2D1C7B87A8FF/Library/Cookies/Cookies.binarycookies
,2015-11-25 13:45:05.360 ThaliTest[1668:1301589] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 13:45:05.361 ThaliTest[1668:1301589] Multi-tasking -> Device: YES, App: YES
,2015-11-25 13:45:05.370 ThaliTest[1668:1301589] Unlimited access to network resources
,2015-11-25 13:45:05.376 ThaliTest[1668:1301589] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 13:45:09.071 ThaliTest[1668:1301589] Resetting plugins due to page load.
,2015-11-25 13:45:09.438 ThaliTest[1668:1301589] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/08FCACF1-5F11-4FC7-B72B-CDEB8BFF2090/ThaliTest.app/www/index.html
,2015-11-25 13:45:09.559 ThaliTest[1668:1301589] JXcore Cordova plugin initializing
2015-11-25 13:45:09.561 ThaliTest[1668:1301737] JXcore instance initializing
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
Radios toggled
,my name is : Apple-Iphone6-1_PT8750
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
,serverPort is 61790
,2015-11-25 13:53:10.465 ThaliTest[1668:1301737] jxcore: startBroadcasting
,2015-11-25 13:53:10.476 ThaliTest[1668:1301737] server: starting Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:10.478 ThaliTest[1668:1301737] multipeer session: start timer: 0x1a65df30
2015-11-25 13:53:10.478 ThaliTest[1668:1301737] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8750
2015-11-25 13:53:10.479 ThaliTest[1668:1301737] jxcore:, startBroadcasting: success
StartBroadcasting started ok
2015-11-25T12:53:10.483Z SendDataTCPServer.js: TCP/IP server is bound to port: 61790
,2015-11-25 13:53:10.965 ThaliTest[1668:1301589] multipeer session: reset timer
2015-11-25 13:53:10.965 ThaliTest[1668:1301589] multipeer session: stop timer
2015-11-25 13:53:10.966 ThaliTest[1668:1301589] multipeer session: start timer: 0x1a65df30
2015-,11-25 13:53:10.966 ThaliTest[1668:1301589] server session: connect
2015-11-25 13:53:10.967 ThaliTest[1668:1301589] server session: stateChange:0->1 Apple-Iphone5-1_PT9701
,2015-11-25 13:53:10.972 ThaliTest[1668:1301589] server: accepting invitation Apple-Iphone5-1_PT9701
,2015-11-25 13:53:11.109 ThaliTest[1668:1301589] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5807.1C0pWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,device[1]: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:11.116Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:11.117Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==,
2015-11-25T12:53:11.117Z SendDataConnector.js: do connect now
,2015-11-25 13:53:11.118 ThaliTest[1668:1301737] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:11.119 ThaliTest[1668:1301737] client session: connect
2015-11-25 13:53:11.120 ThaliTest[1668:1301737] client session: stateChange:0->1 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:11.223 ThaliTest[1668:1301589] multipeer session: reset timer
2015-11-25 13:53:11.223 ThaliTest[1668:1301589] multipeer session: stop timer
2015-11-25 13:53:11.223 ThaliTest[1668:1301589] multipeer session: start timer: 0x1a65df30
2015-11-25 13:53:11.223 ThaliTest[1668:1301589] server session: connect
2015-11-25 13:53:11.224 ThaliTest[1668:1301589] server session: stateChange:0->1 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:11.227 ThaliTest[1668:1301589] server: accepting invitation Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:11.456 ThaliTest[1668:1301589] client: found peer: Apple-IpadAir2-1_PT7357.1lZx3Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7357.1lZx3Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-25 13:53:11.656 ThaliTest[1668:1301589] multipeer session: reset timer
2015-11-25 13:53:11.657 ThaliTest[1668:1301589] multipeer session: stop timer
2015-11-25 13:53:11.658 ThaliTest[1668:1301589] multipeer session: start timer: 0x1a65df30
2015-,11-25 13:53:11.658 ThaliTest[1668:1301589] server session: connect
2015-11-25 13:53:11.659 ThaliTest[1668:1301589] server session: stateChange:0->1 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:11.669 ThaliTest[1668:1301589] server: accepting invitation Apple-IpadAir2-1_PT7357
2015-11-25 13:53:11.682 ThaliTest[1668:1301589] client: found peer: Apple-Iphone5-1_PT9701.GagVHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one5-1_PT9701.GagVHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:13.107 ThaliTest[1668:1302393] server session: connected
2015-11-25 13:53:13.108 ThaliTest[1668:1302393] server session: stateChange:1->2 Apple-Iphone5-1_PT9701
,2015-11-25 13:53:13.116 ThaliTest[1668:1301589] server relay: connected (to port: 61790)
,2015-11-25T12:53:13.124Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:13.260Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-11-25T12:53:13.275Z SendDataTCPServer.js: TCP/IP server has received 19840 bytes of data
,2015-11-25T12:53:13.293Z SendDataTCPServer.js: TCP/IP server has received 34720 bytes of data
,2015-11-25T12:53:13.309Z SendDataTCPServer.js: TCP/IP server has received 53568 bytes of data
,2015-11-25T12:53:13.321Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-11-25T12:53:13.337Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-11-25T12:53:13.352Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-25T12:53:13.366Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:13.381 ThaliTest[1668:1302395] server session: not connected Apple-Iphone5-1_PT9701
,2015-11-25 13:53:13.425 ThaliTest[1668:1302393] server session: connected
2015-11-25 13:53:13.426 ThaliTest[1668:1302393] server session: stateChange:1->2 Apple-Iphone5s-1_PT5807
2015-11-25 13:53:13.431 ThaliTest[1668:1301589] server relay: connected (to port: 61790)
,2015-11-25T12:53:13.441Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:13.723Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-25T12:53:13.742Z SendDataTCPServer.js: TCP/IP server has received 34898 bytes of data
,2015-11-25T12:53:13.759Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-11-25T12:53:13.775Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-11-25T12:53:13.790Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:13.793 ThaliTest[1668:1302368] server session: not connected Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:13.873 ThaliTest[1668:1302368] client session: connected
2015-11-25 13:53:13.874 ThaliTest[1668:1302368] client session: stateChange:1->2 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:13.878 ThaliTest[1668:1302368] client session: fireConnectCallback: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 13:53:13.879 ThaliTest[1668:1302368] jxcore: connect: success
,2015-11-25T12:53:13.881Z SendDataConnector.js: CLIENT connected to 61795, error: null
2015-11-25T12:53:13.882Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:13.885 ThaliTest[1668:1301589] client: relay established
2015-11-25 13:53:13.886 ThaliTest[1668:1301589] client: new accepted socket: 0x1a5db5e0
,2015-11-25T12:53:13.898Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:14.038Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T12:53:14.039Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:14.040Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:14.040Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 13:53:14.040 ThaliTest[1668:1301737] jxcore: disconnect
2015-11-25 13:53:14.041 ThaliTest[1668:1301737] cli,ent session: disconnectFromPeer: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 13:53:14.041 ThaliTest[1668:1301737] client session: disconnect
2015-11-25 13:53:14.041 ThaliTest[1668:1301737] client session: stateChange:2->0 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:14.042 ThaliTest[1668:1301737] jxcore: disconnect: success
2015-11-25T12:53:14.042Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5807.1C0pWw==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:14.044Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:14.044Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25T12:53:14.044Z SendDataConnector.js: do connect now
2015-11-25 13:53:14.044 ThaliTest[1668:1301737] jxcore: connect Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:14.044 ThaliTest[1668:1301737] client session: connect
2015-11-25 13:53:14.045 ThaliTest[1668:1301737] client session: stateChange:0->1 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:14.800 ThaliTest[1668:1302393] server session: connected
2015-11-25 13:53:14.800 ThaliTest[1668:1302393] server session: stateChange:1->2 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:14.806 ThaliTest[1668:1301589] server relay: connected (to port: 61790)
,2015-11-25T12:53:14.812Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:14.865Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-11-25T12:53:14.880Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-11-25T12:53:14.896Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-25T12:53:14.911Z SendDataTCPServer.js: TCP/IP server has received 78556 bytes of data
,2015-11-25T12:53:14.928Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:14.954 ThaliTest[1668:1302368] server session: not connected Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:16.505 ThaliTest[1668:1302368] client session: connected
2015-11-25 13:53:16.506 ThaliTest[1668:1302368] client session: stateChange:1->2 Apple-IpadAir2-1_PT7357.1lZx3Q==
,2015-11-25 13:53:16.510 ThaliTest[1668:1302368] client session: fireConnectCallback: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:16.511 ThaliTest[1668:1302368] jxcore: connect: success
2015-11-25T12:53:16.512Z SendDataConnector.js: CLIENT connected, to 61799, error: null
2015-11-25T12:53:16.512Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:16.516 ThaliTest[1668:1301589] client: relay established
2015-11-25 13:53:16.517 ThaliTest[1668:1301589] client: new accepted socket: 0x1a5cae90
,2015-11-25T12:53:16.529Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:16.966Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:16.967Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:16.969Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:16.969Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:16.970 ThaliTest[1668:1301737] jxcore: disconnect
2015-11-25 13:53:16.971 ThaliTest[1668:1301737] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:16.971 ThaliTest[1668:1301737] client session: discon,nect
2015-11-25 13:53:16.972 ThaliTest[1668:1301737] client session: stateChange:2->0 Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:16.974 ThaliTest[1668:1301737] jxcore: disconnect: success
2015-11-25T12:53:16.975Z SendDataConnector.js: Mobile.Disc,onnect() callback with peer Apple-IpadAir2-1_PT7357.1lZx3Q==
---- round done--------
,device[3]: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:16.977Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:16.979Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25T12:53:16.980Z SendDataConnector.js: do connect now
,2015-11-25 13:53:16.985 ThaliTest[1668:1301737] jxcore: connect Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:16.988 ThaliTest[1668:1301737] client session: connect
,2015-11-25 13:53:16.990 ThaliTest[1668:1301737] client session: stateChange:0->1 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:20.079 ThaliTest[1668:1302395] client session: connected
2015-11-25 13:53:20.081 ThaliTest[1668:1302395] client session: stateChange:1->2 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:20.085 ThaliTest[1668:1302395] client session: fireConnectCallback: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:20.087 ThaliTest[1668:1302395] jxcore: connect: success
2015-11-25T12:53:20.088Z SendDataConnector.js: CLIENT connected to 61802, error: null
2015-11-25T12:53:20.089Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:20.092 ThaliTest[1668:1301589] client: relay established
2015-11-25 13:53:20.093 ThaliTest[1668:1301589] client: new accepted socket: 0x1a5dad60
,2015-11-25T12:53:20.105Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:20.240Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T12:53:20.253Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:20.253Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:20.254Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:20.254Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:20.255 ThaliTest[1668:1301737] jxcore: disconnect
2015-11-25 13:53:20.255 ThaliTest[1668:1301737] client session: disconnectFromPeer: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:20.256 ThaliTest[1668:1301737] client session: disconn,ect
2015-11-25 13:53:20.256 ThaliTest[1668:1301737] client session: stateChange:2->0 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:20.257 ThaliTest[1668:1301737] jxcore: disconnect: success
2015-11-25T12:53:20.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9701.GagVHA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8750","time":9811,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT5807.1C0pWw==","time":2922,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_,PT7357.1lZx3Q==","time":2924,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9701.GagVHA==","time":3276,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":10000,0}]}
sendList : 100% : 3276 ms, 99% : 3276 ms, 95 : 3276 ms, 90% : 3276 ms.
Result count 3, range 2922 ms to  3276 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T12:53:20.262Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:20.263Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 13:53:24.289 ThaliTest[1668:1301737] jxcore: stopBroadcasting
2015-11-25 13:53:24.289 ThaliTest[1668:1301737] THEMultipeerSession stopping peer
2015-11-25 13:53:24.290 ThaliTest[1668:1301737] multipeer session: stop timer
2015-11-25 13:53:24.,290 ThaliTest[1668:1301737] server session: disconnect
2015-11-25 13:53:24.291 ThaliTest[1668:1301737] server session: stateChange:2->0 Apple-Iphone5-1_PT9701
2015-11-25 13:53:24.297 ThaliTest[1668:1301737] server session: disconnect
2015-11-25 13:53:24,.298 ThaliTest[1668:1301737] server session: stateChange:2->0 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:24.303 ThaliTest[1668:1301737] server session: disconnect
,2015-11-25 13:53:24.303 ThaliTest[1668:1301737] server session: stateChange:2->0 Apple-IpadAir2-1_PT7357
,2015-11-25 13:53:24.310 ThaliTest[1668:1301737] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-25T12:53:24.330Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.332Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.333Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:24.334Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5s-1_PT5807.1C0pWw==\",\"time\":2922,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT7357.1lZx3Q==\",\"time\":2924,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT9701.GagVHA==\",\"time\":3276,\"result\":\"OK\",\"connections\":,1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received

```
