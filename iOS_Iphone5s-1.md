#### Test 513350283842813_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A117F5C9-7218-4F46-BD43-DDF22822D1BE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A117F5C9-7218-4F46-BD43-DDF22822D1BE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3285462A-E8A3-4B39-9583-8E10407D5035/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55199"
,(lldb)     command script import "/tmp/A117F5C9-7218-4F46-BD43-DDF22822D1BE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 10:18:51.749 ThaliTest[1582:1351734] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D03FD99-8D67-4169-B07C-0A8C8E1B1889/Library/Cookies/Cookies.binarycookies
,2015-11-25 10:18:52.148 ThaliTest[1582:1351734] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 10:18:52.149 ThaliTest[1582:1351734] Multi-tasking -> Device: YES, App: YES
,2015-11-25 10:18:52.158 ThaliTest[1582:1351734] Unlimited access to network resources
,2015-11-25 10:18:52.167 ThaliTest[1582:1351734] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 10:18:55.812 ThaliTest[1582:1351734] Resetting plugins due to page load.
,2015-11-25 10:18:56.259 ThaliTest[1582:1351734] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/3285462A-E8A3-4B39-9583-8E10407D5035/ThaliTest.app/www/index.html
,2015-11-25 10:18:56.414 ThaliTest[1582:1351734] JXcore Cordova plugin initializing
2015-11-25 10:18:56.415 ThaliTest[1582:1351861] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT1341
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 61720
,2015-11-25 10:26:49.347 ThaliTest[1582:1351861] jxcore: startBroadcasting
,2015-11-25 10:26:49.360 ThaliTest[1582:1351861] server: starting Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:49.361 ThaliTest[1582:1351861] multipeer session: start timer: 0x196e6770
,2015-11-25 10:26:49.362 ThaliTest[1582:1351861] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1341
2015-11-25 10:26:49.363 ThaliTest[1582:1351861] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T09:26:49.366Z SendDat,aTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 10:26:49.673 ThaliTest[1582:1351734] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8682.g043PA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,device[1]: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:49.680Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:49.681Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:49.681Z SendDataConnector.js: do connect now
2015-11-25 10:26:49.682 ThaliTest[1582:1351861] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:49.683 ThaliTest[1582:1351861] client session: connect
2015-11-25 10:26:49.684 ThaliTest[1582:1351861] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:50.804 ThaliTest[1582:1351734] multipeer session: reset timer
2015-11-25 10:26:50.805 ThaliTest[1582:1351734] multipeer session: stop timer
2015-11-25 10:26:50.806 ThaliTest[1582:1351734] multipeer session: start timer: 0x196e6770
2015-,11-25 10:26:50.807 ThaliTest[1582:1351734] server session: connect
2015-11-25 10:26:50.807 ThaliTest[1582:1351734] server session: stateChange:0->1 Apple-Iphone6-1_PT8682
,2015-11-25 10:26:50.820 ThaliTest[1582:1351734] server: accepting invitation Apple-Iphone6-1_PT8682
,2015-11-25 10:26:51.110 ThaliTest[1582:1351734] multipeer session: reset timer
2015-11-25 10:26:51.111 ThaliTest[1582:1351734] multipeer session: stop timer
2015-11-25 10:26:51.112 ThaliTest[1582:1351734] multipeer session: start timer: 0x196e6770
2015-,11-25 10:26:51.112 ThaliTest[1582:1351734] server session: connect
2015-11-25 10:26:51.113 ThaliTest[1582:1351734] server session: stateChange:0->1 Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:51.126 ThaliTest[1582:1351734] server: accepting invitation Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:51.154 ThaliTest[1582:1351734] client: found peer: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:51.155 ThaliTest[1582:1351734] client: found peer: Apple-Iphone5-1_PT138.uokMhA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipad,Air2-1_PT7460.CVEGJA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT138.uokMhA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 10:26:52.255 ThaliTest[1582:1352535] client session: connected
2015-11-25 10:26:52.255 ThaliTest[1582:1352535] client session: stateChange:1->2 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:52.262 ThaliTest[1582:1352541] client session: fireConnectCallback: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:26:52.263 ThaliTest[1582:1352541] jxcore: connect: success
,2015-11-25T09:26:52.264Z SendDataConnector.js: CLIENT connected to 61723, error: null
,2015-11-25T09:26:52.265Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:52.269 ThaliTest[1582:1351734] client: relay established
2015-11-25 10:26:52.270 ThaliTest[1582:1351734] client: new accepted socket: 0x196f03b0
,2015-11-25T09:26:52.282Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:52.394Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T09:26:52.418Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T09:26:52.431Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:26:52.431Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:52.432Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:52.432Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:26:52.433 ThaliTest[1582:1351861] jxcore: disconnect
,2015-11-25 10:26:52.434 ThaliTest[1582:1351861] client session: disconnectFromPeer: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:26:52.434 ThaliTest[1582:1351861] client session: disconnect
2015-11-25 10:26:52.434 ThaliTest[1582:1351861] client session: stateChange:2->0 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:52.436 ThaliTest[1582:1351861] jxcore: disconnect: success
,2015-11-25T09:26:52.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043PA==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:26:52.440Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25T09:26:52.440Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25T09:26:52.440Z SendDataConnector.js: do connect now
,2015-11-25 10:26:52.441 ThaliTest[1582:1351861] jxcore: connect Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:52.441 ThaliTest[1582:1351861] client session: connect
2015-11-25 10:26:52.441 ThaliTest[1582:1351861] client session: stateChange:0->1 Appl,e-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:52.752 ThaliTest[1582:1351734] multipeer session: reset timer
2015-11-25 10:26:52.753 ThaliTest[1582:1351734] multipeer session: stop timer
2015-11-25 10:26:52.753 ThaliTest[1582:1351734] multipeer session: start timer: 0x196e6770
2015-11-25 10:26:52.753 ThaliTest[1582:1351734] server session: connect
2015-11-25 10:26:52.753 ThaliTest[1582:1351734] server session: stateChange:0->1 Apple-Iphone5-1_PT138
,2015-11-25 10:26:52.758 ThaliTest[1582:1351734] server: accepting invitation Apple-Iphone5-1_PT138
,2015-11-25 10:26:53.125 ThaliTest[1582:1352541] server session: connected
2015-11-25 10:26:53.125 ThaliTest[1582:1352541] server session: stateChange:1->2 Apple-Iphone6-1_PT8682
,2015-11-25 10:26:53.142 ThaliTest[1582:1351734] server relay: connected (to port: 61720)
2015-11-25T09:26:53.144Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:26:53.235Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-25T09:26:53.255Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-11-25T09:26:53.276Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-11-25T09:26:53.293Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-25T09:26:53.310Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-25T09:26:53.332Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:26:53.348 ThaliTest[1582:1352537] server session: not connected Apple-Iphone6-1_PT8682
,2015-11-25 10:26:53.678 ThaliTest[1582:1352537] server session: connected
2015-11-25 10:26:53.679 ThaliTest[1582:1352537] server session: stateChange:1->2 Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:53.688 ThaliTest[1582:1351734] server relay: connected (to port: 61720)
2015-11-25T09:26:53.695Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:26:53.759Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-11-25T09:26:53.775Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-11-25T09:26:53.792Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-11-25T09:26:53.807Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-11-25T09:26:53.822Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:26:54.684 ThaliTest[1582:1352541] server session: not connected Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:55.275 ThaliTest[1582:1352529] server session: connected
2015-11-25 10:26:55.277 ThaliTest[1582:1352529] server session: stateChange:1->2 Apple-Iphone5-1_PT138
,2015-11-25 10:26:55.288 ThaliTest[1582:1351734] server relay: connected (to port: 61720)
2015-11-25T09:26:55.291Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 10:26:55.303 ThaliTest[1582:1352541] client session: connected
,2015-11-25 10:26:55.303 ThaliTest[1582:1352541] client session: stateChange:1->2 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:55.324 ThaliTest[1582:1352541] client session: fireConnectCallback: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:55.325 ThaliTest[1582:1352541] jxcore: connect: success
2015-11-25T09:26:55.326Z SendDataConnector.js: CLIENT connected, to 61729, error: null
2015-11-25T09:26:55.327Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:55.330 ThaliTest[1582:1351734] client: relay established
,2015-11-25 10:26:55.330 ThaliTest[1582:1351734] client: new accepted socket: 0x15d97740
,2015-11-25T09:26:55.342Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:55.435Z SendDataTCPServer.js: TCP/IP server has received 1984 bytes of data
,2015-11-25T09:26:55.451Z SendDataTCPServer.js: TCP/IP server has received 24864 bytes of data
,2015-11-25T09:26:55.471Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-25T09:26:55.848Z SendDataTCPServer.js: TCP/IP server has received 65472 bytes of data
,2015-11-25T09:26:55.861Z SendDataTCPServer.js: TCP/IP server has received 83328 bytes of data
,2015-11-25T09:26:55.875Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25T09:26:56.285Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T09:26:56.300Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:26:56.300Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:56.302Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:56.303Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 10:26:56.304 ThaliTest[1582:1351861] jxcore: disconnect
,2015-11-25 10:26:56.305 ThaliTest[1582:1351861] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:56.306 ThaliTest[1582:1351861] client session: disconnect
2015-11-25 10:26:56.307 ThaliTest[1582:1351861] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:56.310 ThaliTest[1582:1351861] jxcore: disconnect: success
2015-11-25T09:26:56.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7460.CVEGJA==
---- round done--------
device[3]: Apple-Iphone5-1_PT138.u,okMhA==
2015-11-25T09:26:56.316Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25T09:26:56.316Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT138.uokMhA==
2015-11-25T09:26:56.317Z SendDataConnector.js: do connect now
,2015-11-25 10:26:56.318 ThaliTest[1582:1351861] jxcore: connect Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:26:56.318 ThaliTest[1582:1351861] client session: connect
2015-11-25 10:26:56.319 ThaliTest[1582:1351861] client session: stateChange:0->1 Apple-,Iphone5-1_PT138.uokMhA==
,2015-11-25 10:26:57.935 ThaliTest[1582:1352535] server session: not connected Apple-Iphone5-1_PT138
,2015-11-25 10:27:00.613 ThaliTest[1582:1352535] client session: connected
2015-11-25 10:27:00.614 ThaliTest[1582:1352535] client session: stateChange:1->2 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:00.639 ThaliTest[1582:1352535] client session: fireConnectCallback: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:00.639 ThaliTest[1582:1352535] jxcore: connect: success
2015-11-25T09:27:00.641Z SendDataConnector.js: CLIENT connected t,o 61732, error: null
2015-11-25T09:27:00.641Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:27:00.645 ThaliTest[1582:1351734] client: relay established
,2015-11-25 10:27:00.646 ThaliTest[1582:1351734] client: new accepted socket: 0x196ec9c0
,2015-11-25T09:27:00.657Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:27:00.766Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T09:27:00.777Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T09:27:00.789Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:27:00.789Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:00.790Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:00.790Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 10:27:00.790 ThaliTest[1582:1351861] jxcore: disconnect
2015-11-25 10:27:00.791 ThaliTest[1582:1351861] client session: disconnectFromPeer: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:00.791 ThaliTest[1582:1351861] client session: disconnect
2015-11-25 10:27:00.791 ThaliTest[1582:1351861] client session: stateChange:2->0 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:00.793 ThaliTest[1582:1351861] jxcore: disconnect: success
,2015-11-25T09:27:00.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT138.uokMhA==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT1341","time":11465,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8682.g043PA==","time":2752,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7460.CVEGJA==","time":3861,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT138.uokMhA==","time":4473,"result":"OK","connections":1}]}
,sendList : 100% : 4473 ms, 99% : 4473 ms, 95 : 4473 ms, 90% : 4473 ms.
,Result count 3, range 2752 ms to  4473 ms.
,sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-11-25T09:27:00.799Z SendDataConnector.js: CLIENT Stop now
,2015-11-25T09:27:00.799Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 10:27:05.004 ThaliTest[1582:1351861] jxcore: stopBroadcasting
,2015-11-25 10:27:05.005 ThaliTest[1582:1351861] THEMultipeerSession stopping peer
,2015-11-25 10:27:05.006 ThaliTest[1582:1351861] multipeer session: stop timer
2015-11-25 10:27:05.007 ThaliTest[1582:1351861] server session: disconnect
2015-11-25 10:27:05.008 ThaliTest[1582:1351861] server session: stateChange:2->0 Apple-IpadAir2-1_PT7,460
,2015-11-25 10:27:05.018 ThaliTest[1582:1351861] server session: disconnect
2015-11-25 10:27:05.020 ThaliTest[1582:1351861] server session: stateChange:2->0 Apple-Iphone5-1_PT138
,2015-11-25 10:27:05.032 ThaliTest[1582:1351861] server session: disconnect
2015-11-25 10:27:05.033 ThaliTest[1582:1351861] server session: stateChange:2->0 Apple-Iphone6-1_PT8682
,2015-11-25 10:27:05.040 ThaliTest[1582:1351861] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-11-25T09:27:05.064Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.065Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.067Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.068Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2752,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Ipa,dAir2-1_PT7460.CVEGJA==\",\"time\":3861,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":4473,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":,[{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":2613,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2752,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2854,\",result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":3651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":3735,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-,1_PT7460.CVEGJA==\",\"time\":3861,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":4218,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":4473,\"result\":\"OK\",\"connecti,ons\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":5315,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6177,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"tim,e\":6202,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6632,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
