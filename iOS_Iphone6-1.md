#### Test 52445159d291820_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/FDBC801B-1670-4E7F-8247-62DF1737E4E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FDBC801B-1670-4E7F-8247-62DF1737E4E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/06C89604-672E-40C7-B593-6E21381E0958/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59949"
,(lldb)     command script import "/tmp/FDBC801B-1670-4E7F-8247-62DF1737E4E9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 21:06:05.594 ThaliTest[2501:2120210] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1CF50C34-EDB6-48C7-BB70-6CAB0E22C5D7/Library/Cookies/Cookies.binarycookies
,2015-12-02 21:06:05.992 ThaliTest[2501:2120210] Apache Cordova native platform version 3.9.2 is starting.
2015-12-02 21:06:05.993 ThaliTest[2501:2120210] Multi-tasking -> Device: YES, App: YES
,2015-12-02 21:06:06.000 ThaliTest[2501:2120210] Unlimited access to network resources
,2015-12-02 21:06:06.006 ThaliTest[2501:2120210] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 21:06:09.581 ThaliTest[2501:2120210] Resetting plugins due to page load.
,2015-12-02 21:06:09.962 ThaliTest[2501:2120210] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/06C89604-672E-40C7-B593-6E21381E0958/ThaliTest.app/www/index.html
,2015-12-02 21:06:10.084 ThaliTest[2501:2120210] JXcore Cordova plugin initializing
,2015-12-02 21:06:10.085 ThaliTest[2501:2120339] JXcore instance initializing
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
,my name is : Apple-Iphone6-1_PT3258
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 49454
,2015-12-02 21:12:27.842 ThaliTest[2501:2120339] jxcore: startBroadcasting
,2015-12-02 21:12:27.854 ThaliTest[2501:2120339] server: starting Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:27.854 ThaliTest[2501:2120339] multipeer session: start timer: 0x195580c0
2015-12-02 21:12:27.854 ThaliTest[2501:2120339] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3258
,2015-12-02 21:12:27.855 ThaliTest[2501:2120339] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-02T20:12:27.856Z SendDataTCPServer.js: TCP/IP server is bound to port: 49454
,2015-12-02 21:12:28.033 ThaliTest[2501:2120210] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT369.LHPK5g==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:12:28.035Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:12:28.035Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02T20:12:28.036Z SendDataConnector.js: do connect now
2015-12-02 21:12:28.036 ThaliTest[2501:2120339] jxcore: connect Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:28.036 ThaliTest[2501:2120339] client session: connect
2015-12-02 21:12:28.036 ThaliTest[2501:2120339] client session: stateChange:0->1 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:28.059 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3314.VcnsbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:28.961 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:31.555 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:12:31.555 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:12:31.556 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:12:31.556 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:12:31.557 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:12:31.567 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:12:31.646 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:12:31.646 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:12:31.647 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:12:31.647 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:12:31.647 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-IpadAir2-1_PT369
,2015-12-02 21:12:31.649 ThaliTest[2501:2120210] server: accepting invitation Apple-IpadAir2-1_PT369
,2015-12-02 21:12:31.697 ThaliTest[2501:2120887] client session: connected
2015-12-02 21:12:31.697 ThaliTest[2501:2120887] client session: stateChange:1->2 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:31.709 ThaliTest[2501:2120877] client session: fireConnectCallback: Apple-IpadAir2-1_PT369.LHPK5g==
2015-12-02 21:12:31.710 ThaliTest[2501:2120877] jxcore: connect: success
2015-12-02T20:12:31.711Z SendDataConnector.js: CLIENT connected to 49457, error: null
,2015-12-02T20:12:31.711Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:31.713 ThaliTest[2501:2120210] client: relay established
2015-12-02 21:12:31.713 ThaliTest[2501:2120210] client: new accepted socket: 0x19251d40
,2015-12-02T20:12:31.728Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:32.096Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T20:12:32.354Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T20:12:32.354Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:32.358Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:32.359Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:32.360 ThaliTest[2501:2120339] jxcore: disconnect
,2015-12-02 21:12:32.362 ThaliTest[2501:2120339] client session: disconnectFromPeer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:32.362 ThaliTest[2501:2120339] client session: disconnect
2015-12-02 21:12:32.363 ThaliTest[2501:2120339] client session: stateChange:2->0 Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:32.368 ThaliTest[2501:2120339] jxcore: disconnect: success
,2015-12-02T20:12:32.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT369.LHPK5g==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02T20:12:32.378Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02T20:12:32.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02T20:12:32.380Z SendDataConnector.js: do connect now
,2015-12-02 21:12:32.381 ThaliTest[2501:2120339] jxcore: connect Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:32.383 ThaliTest[2501:2120339] client session: connect
,2015-12-02 21:12:32.384 ThaliTest[2501:2120339] client session: stateChange:0->1 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:33.173 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:12:33.173 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:12:33.174 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:12:33.174 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:12:33.175 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:33.185 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:33.733 ThaliTest[2501:2120887] server session: connected
2015-12-02 21:12:33.733 ThaliTest[2501:2120887] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:12:33.739 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
,2015-12-02T20:12:33.744Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:34.234Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-12-02 21:12:34.237 ThaliTest[2501:2120908] server session: connected
2015-12-02 21:12:34.239 ThaliTest[2501:2120908] server session: stateChange:1->2 Apple-IpadAir2-1_PT369
,2015-12-02T20:12:34.248Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-02 21:12:34.254 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
,2015-12-02T20:12:34.264Z SendDataTCPServer.js: TCP/IP server has received 21824 bytes of data
2015-12-02T20:12:34.268Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:34.282Z SendDataTCPServer.js: TCP/IP server has received 28768 bytes of data
,2015-12-02T20:12:34.295Z SendDataTCPServer.js: TCP/IP server has received 43648 bytes of data
,2015-12-02T20:12:34.313Z SendDataTCPServer.js: TCP/IP server has received 64480 bytes of data
,2015-12-02T20:12:34.328Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-12-02T20:12:34.341Z SendDataTCPServer.js: TCP/IP server has received 91264 bytes of data
,2015-12-02T20:12:34.352Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T20:12:34.749Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-02T20:12:34.765Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-02T20:12:34.782Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:34.814 ThaliTest[2501:2120908] server session: not connected Apple-IpadAir2-1_PT369
,2015-12-02 21:12:34.865 ThaliTest[2501:2120877] client session: connected
,2015-12-02 21:12:34.866 ThaliTest[2501:2120877] client session: stateChange:1->2 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:34.871 ThaliTest[2501:2120877] client session: fireConnectCallback: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:34.872 ThaliTest[2501:2120877] jxcore: connect: success
,2015-12-02T20:12:34.873Z SendDataConnector.js: CLIENT connected to 49462, error: null
,2015-12-02T20:12:34.874Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:34.878 ThaliTest[2501:2120210] client: relay established
2015-12-02 21:12:34.879 ThaliTest[2501:2120210] client: new accepted socket: 0x1923dcb0
,2015-12-02T20:12:34.891Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:35.298Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T20:12:35.312Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T20:12:35.335Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T20:12:35.335Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:35.336Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:35.336Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:35.336 ThaliTest[2501:2120339] jxcore: disconnect
2015-12-02 21:12:35.337 ThaliTest[2501:2120339] client session: disconnectFromPeer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:35.337 ThaliTest[2501:2120339] client session: disconn,ect
2015-12-02 21:12:35.337 ThaliTest[2501:2120339] client session: stateChange:2->0 Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:35.338 ThaliTest[2501:2120339] jxcore: disconnect: success
2015-12-02T20:12:35.339Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3314.VcnsbA==
---- round done--------
device[3]: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:35.340Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:35.340,Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:35.340Z SendDataConnector.js: do connect now
2015-12-02 21:12:35.340 ThaliTest[2501:2120339] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:35.340 ThaliTest[2501:2120339] client session: connect
,2015-12-02 21:12:35.341 ThaliTest[2501:2120339] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:35.361 ThaliTest[2501:2120904] server session: connected
2015-12-02 21:12:35.362 ThaliTest[2501:2120904] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:35.409 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
,2015-12-02T20:12:35.421Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:35.805Z SendDataTCPServer.js: TCP/IP server has received 4096 bytes of data
,2015-12-02T20:12:35.817Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-02T20:12:35.831Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-02T20:12:35.845Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:35.866 ThaliTest[2501:2120888] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:38.937 ThaliTest[2501:2120888] client session: connected
2015-12-02 21:12:38.937 ThaliTest[2501:2120888] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:38.948 ThaliTest[2501:2120877] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:38.948 ThaliTest[2501:2120877] jxcore: connect: success
2015-12-02T20:12:38.949Z SendDataConnector.js: CLIENT connected, to 49467, error: null
2015-12-02T20:12:38.950Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:38.954 ThaliTest[2501:2120210] client: relay established
2015-12-02 21:12:38.955 ThaliTest[2501:2120210] client: new accepted socket: 0x19548790
,2015-12-02T20:12:38.967Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:39.410Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T20:12:39.448Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:12:39.460Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T20:12:39.460Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:39.461Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:39.461Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:39.461 ThaliTest[2501:2120339] jxcore: disconnect
,2015-12-02 21:12:39.462 ThaliTest[2501:2120339] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:39.462 ThaliTest[2501:2120339] client session: disconnect
2015-12-02 21:12:39.462 ThaliTest[2501:2120339] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:39.463 ThaliTest[2501:2120339] jxcore: disconnect: success
2015-12-02T20:12:39.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
---- round done--------
,weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT3258","time":11638,"result":"OK","sendList":[{"name":"Apple-IpadAir2-1_PT369.LHPK5g==","time":4321,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_P,T3314.VcnsbA==","time":2956,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","time":4120,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4321 ms, 99% : 4321 ms, 95 : 4321 ms, 90% : 4321 ms.
,Result count 3, range 2956 ms to  4321 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-02T20:12:39.470Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T20:12:39.470Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:44.614 ThaliTest[2501:2120877] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:12:54.740 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:12:54.741 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:12:54.741 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:12:54.742 ThaliTest[2501:2120210] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:12:54.742 ThaliTest[2501:2120210] server session: disconnect
2015-12-02 21:12:54.743 ThaliTest[2501:2120210] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:12:54.746 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:12:54.746 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
2015-12-02T20:12:54.752Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-02 21:12:54.763 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:12:57.217 ThaliTest[2501:2120961] server session: connected
2015-12-02 21:12:57.218 ThaliTest[2501:2120961] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:12:57.223 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
2015-12-02T20:12:57.225Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:57.383Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-12-02T20:12:57.398Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:13:07.673 ThaliTest[2501:2120877] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:13:18.211 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:13:18.212 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:13:18.213 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:13:18.213 ThaliTest[2501:2120210] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:13:18.214 ThaliTest[2501:2120210] server session: disconnect
2015-12-02 21:13:18.214 ThaliTest[2501:2120210] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
2015-12-02 21:13:18.217 ThaliTest[2501:2120210] server session: connect
2015-12-02T20:13:18.220Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02 21:13:18.218 ThaliTest[2501:2120210] server session: stateChange:0,->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:13:18.236 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:13:20.407 ThaliTest[2501:2120877] server session: connected
2015-12-02 21:13:20.408 ThaliTest[2501:2120877] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:13:20.413 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
2015-12-02T20:13:20.416Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:20.578Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-02T20:13:20.593Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:13:31.470 ThaliTest[2501:2121002] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:13:40.864 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:13:40.864 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:13:40.865 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:13:40.865 ThaliTest[2501:2120210] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:13:40.865 ThaliTest[2501:2120210] server session: disconnect
2015-12-02 21:13:40.865 ThaliTest[2501:2120210] server session: stateChange:2->0 Apple-Iphone5-1_PT3314
,2015-12-02 21:13:40.867 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:13:40.867 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:13:40.869 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02T20:13:40.875Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:13:43.018 ThaliTest[2501:2121052] server session: connected
,2015-12-02 21:13:43.019 ThaliTest[2501:2121052] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:13:43.024 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
2015-12-02T20:13:43.029Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:43.327Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:13:53.289 ThaliTest[2501:2121043] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:14:03.260 ThaliTest[2501:2120210] multipeer session: reset timer
2015-12-02 21:14:03.261 ThaliTest[2501:2120210] multipeer session: stop timer
2015-12-02 21:14:03.262 ThaliTest[2501:2120210] multipeer session: start timer: 0x195580c0
2015-,12-02 21:14:03.262 ThaliTest[2501:2120210] server: disconnecting to refresh session (Apple-Iphone5-1_PT3314)
2015-12-02 21:14:03.263 ThaliTest[2501:2120210] server session: disconnect
2015-12-02 21:14:03.263 ThaliTest[2501:2120210] server session: stateC,hange:2->0 Apple-Iphone5-1_PT3314
,2015-12-02T20:14:03.273Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:14:03.326 ThaliTest[2501:2120210] server session: connect
2015-12-02 21:14:03.326 ThaliTest[2501:2120210] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:14:03.332 ThaliTest[2501:2120210] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:14:05.497 ThaliTest[2501:2121082] server session: connected
2015-12-02 21:14:05.498 ThaliTest[2501:2121082] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:14:05.504 ThaliTest[2501:2120210] server relay: connected (to port: 49454)
2015-12-02T20:14:05.510Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:14:05.582Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-12-02T20:14:05.596Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:14:15.825 ThaliTest[2501:2121052] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:14:33.263 ThaliTest[2501:2120210] multipeer session: restart
,2015-12-02 21:14:33.281 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:33.284 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:14:33.286 ThaliTest[2501:2120210] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:15:03.263 ThaliTest[2501:2120210] multipeer session: restart
,2015-12-02 21:15:03.279 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:15:03.280 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:03.282 ThaliTest[2501:2120210] client: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:15:33.263 ThaliTest[2501:2120210] multipeer session: restart
,2015-12-02 21:15:33.281 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:15:33.283 ThaliTest[2501:2120210] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:15:33.284 ThaliTest[2501:2120210] clien,t: found peer: Apple-IpadAir2-1_PT369.LHPK5g==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,2015-12-02 21:16:03.263 ThaliTest[2501:2120210] multipeer session: restart
2015-12-02 21:16:03.269 ThaliTest[2501:2120210] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x26e2efef 0x35798c8b 0x26d4aaa3 0x28e09d85 0x26932607 0x26931e81 0x268ab3d3 0x26df4faf 0x26df43bf 0x26df2a25 0x26d3f201 0x26d3f013 0x2e7ca201 0x2a50ba09 0x2f5e3 0x35d4aaaf)
libc++abi.dylib: terminating with uncaught exception of type NSException
,Process 2501 stopped
* thread #1: tid = 0x205a12, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x35e14df0 <+8>:  blo    0x35e14e08                ; <+32>
    0x35e14df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x35e14df8 <+16>: ldr    r12, [pc, r12]
    0x35e14dfc <+20>: b      0x35e14e04                ; <+28>
,* thread #1: tid = 0x205a12, 0x35e14df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
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
    frame #13: 0x0002f5e2 ThaliTest`main + 50

```
