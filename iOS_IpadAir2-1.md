#### Test 513350283842813_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2FE8737E-4843-48BD-A31B-1F72445AB6E5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2FE8737E-4843-48BD-A31B-1F72445AB6E5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4A161927-5DE4-45D8-BAE2-11E589824BEA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55172"
,(lldb)     command script import "/tmp/2FE8737E-4843-48BD-A31B-1F72445AB6E5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 10:18:00.890 ThaliTest[1273:1704173] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B202FBA-A54C-4DE9-A858-CE257F434D7C/Library/Cookies/Cookies.binarycookies
,2015-11-25 10:18:01.182 ThaliTest[1273:1704173] Apache Cordova native platform version 3.9.2 is starting.
2015-11-25 10:18:01.183 ThaliTest[1273:1704173] Multi-tasking -> Device: YES, App: YES
,2015-11-25 10:18:01.189 ThaliTest[1273:1704173] Unlimited access to network resources
,2015-11-25 10:18:01.195 ThaliTest[1273:1704173] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 10:18:05.429 ThaliTest[1273:1704173] Resetting plugins due to page load.
,2015-11-25 10:18:06.870 ThaliTest[1273:1704173] Finished load of: file:///var/mobile/Containers/Bundle/Application/4A161927-5DE4-45D8-BAE2-11E589824BEA/ThaliTest.app/www/index.html
,2015-11-25 10:18:07.015 ThaliTest[1273:1704173] JXcore Cordova plugin initializing
,2015-11-25 10:18:07.018 ThaliTest[1273:1704357] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT7460
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
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[]}
Start now : testSendData.js
stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
serverPort is 61261
,2015-11-25 10:26:49.803 ThaliTest[1273:1704357] jxcore: startBroadcasting
,2015-11-25 10:26:49.809 ThaliTest[1273:1704357] server: starting Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:49.810 ThaliTest[1273:1704357] multipeer session: start timer: 0x190a8d60
2015-11-25 10:26:49.810 ThaliTest[1273:1704357] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7460
2015-11-25 10:26:49.811 ThaliTest[1273:1704357] jxcore,: startBroadcasting: success
StartBroadcasting started ok
2015-11-25T09:26:49.812Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 10:26:50.561 ThaliTest[1273:1704173] client: found peer: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:50.562 ThaliTest[1273:1704173] client: found peer: Apple-Iphone6-1_PT8682.g043PA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1341.lrEeog==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:50.564Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:50.564Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:50.564Z SendDataConnector.js: do connect now
,2015-11-25 10:26:50.564 ThaliTest[1273:1704357] jxcore: connect Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:50.565 ThaliTest[1273:1704357] client session: connect
2015-11-25 10:26:50.565 ThaliTest[1273:1704357] client session: stateChange:0->1 Apple-Iphone5s-1_PT1341.lrEeog==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8682.g043PA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 10:26:52.666 ThaliTest[1273:1704173] client: found peer: Apple-Iphone5-1_PT138.uokMhA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT138.uokMhA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-11-25 10:26:53.192 ThaliTest[1273:1704173] multipeer session: reset timer
2015-11-25 10:26:53.192 ThaliTest[1273:1704173] multipeer session: stop timer
,2015-11-25 10:26:53.193 ThaliTest[1273:1704173] multipeer session: start timer: 0x190a8d60
2015-11-25 10:26:53.193 ThaliTest[1273:1704173] server session: connect
2015-11-25 10:26:53.193 ThaliTest[1273:1704173] server session: stateChange:0->1 Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:53.195 ThaliTest[1273:1704173] server: accepting invitation Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:54.196 ThaliTest[1273:1705948] client session: connected
2015-11-25 10:26:54.196 ThaliTest[1273:1705948] client session: stateChange:1->2 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:54.204 ThaliTest[1273:1705957] client session: fireConnectCallback: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:54.204 ThaliTest[1273:1705957] jxcore: connect: success
,2015-11-25T09:26:54.205Z SendDataConnector.js: CLIENT connected to 61264, error: null
2015-11-25T09:26:54.206Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:54.207 ThaliTest[1273:1704173] client: relay established
2015-11-25 10:26:54.207 ThaliTest[1273:1704173] client: new accepted socket: 0x17e61c50
,2015-11-25T09:26:54.220Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:54.287Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T09:26:54.705Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T09:26:54.731Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T09:26:54.768Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:26:54.781Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:26:54.781Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:54.782Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:54.782Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:26:54.783 ThaliTest[1273:1704357] jxcore: disconnect
2015-11-25 10:26:54.784 ThaliTest[1273:1704357] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:54.784 ThaliTest[1273:1704357] client session: disconnect
2015-11-25 10:26:54.784 ThaliTest[1273:1704357] client session: stateChange:2->0 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:54.790 ThaliTest[1273:1704357] jxcore: disconnect: success
2015-11-25T09:26:54.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1341.lrEeog==
---- round done--------
device[2]: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:54.791Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:54.791Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8682.g043PA==
2015-11-25T09:26:54.791Z SendDataConnector.js: do connect now
,2015-11-25 10:26:54.792 ThaliTest[1273:1704357] jxcore: connect Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:26:54.792 ThaliTest[1273:1704357] client session: connect
2015-11-25 10:26:54.792 ThaliTest[1273:1704357] client session: stateChange:0->1 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:55.821 ThaliTest[1273:1705948] server session: connected
2015-11-25 10:26:55.821 ThaliTest[1273:1705948] server session: stateChange:1->2 Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:55.840 ThaliTest[1273:1704173] server relay: connected (to port: 61261)
,2015-11-25T09:26:55.852Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 10:26:56.157 ThaliTest[1273:1704173] multipeer session: reset timer
2015-11-25 10:26:56.157 ThaliTest[1273:1704173] multipeer session: stop timer
2015-11-25 10:26:56.157 ThaliTest[1273:1704173] multipeer session: start timer: 0x190a8d60
2015-11-25 10:26:56.157 ThaliTest[1273:1704173] server session: connect
2015-11-25 10:26:56.157 ThaliTest[1273:1704173] server session: stateChange:0->1 Apple-Iphone6-1_PT8682
,2015-11-25 10:26:56.159 ThaliTest[1273:1704173] server: accepting invitation Apple-Iphone6-1_PT8682
,2015-11-25T09:26:56.280Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-11-25T09:26:56.294Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-11-25T09:26:56.308Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-25T09:26:56.345Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:26:58.412 ThaliTest[1273:1705953] server session: not connected Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:59.438 ThaliTest[1273:1705946] server session: connected
2015-11-25 10:26:59.438 ThaliTest[1273:1705946] server session: stateChange:1->2 Apple-Iphone6-1_PT8682
,2015-11-25 10:26:59.440 ThaliTest[1273:1704173] server relay: connected (to port: 61261)
,2015-11-25T09:26:59.445Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:26:59.948Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-11-25T09:26:59.960Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-11-25T09:27:00.022Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:27:00.266 ThaliTest[1273:1705948] server session: not connected Apple-Iphone6-1_PT8682
,2015-11-25 10:27:00.512 ThaliTest[1273:1704173] multipeer session: reset timer
2015-11-25 10:27:00.512 ThaliTest[1273:1704173] multipeer session: stop timer
2015-11-25 10:27:00.512 ThaliTest[1273:1704173] multipeer session: start timer: 0x190a8d60
,2015-11-25 10:27:00.513 ThaliTest[1273:1704173] server session: connect
2015-11-25 10:27:00.513 ThaliTest[1273:1704173] server session: stateChange:0->1 Apple-Iphone5-1_PT138
,2015-11-25 10:27:00.518 ThaliTest[1273:1704173] server: accepting invitation Apple-Iphone5-1_PT138
,2015-11-25 10:27:00.538 ThaliTest[1273:1705953] client session: connected
2015-11-25 10:27:00.540 ThaliTest[1273:1705953] client session: stateChange:1->2 Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:27:00.542 ThaliTest[1273:1705953] client session: fir,eConnectCallback: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:27:00.542 ThaliTest[1273:1705953] jxcore: connect: success
2015-11-25T09:27:00.543Z SendDataConnector.js: CLIENT connected to 61270, error: null
2015-11-25T09:27:00.543Z SendDataConnector.js: CLIENT starting client 
2015-11-25 10:27:00.544 ThaliTest[1273:1704173] client: relay established
2015-11-25 10:27:00.544 ThaliTest[1273:1704173] client: new accepted socket: 0x190c5470
,2015-11-25T09:27:00.557Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:27:00.993Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:27:00.993Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:00.994Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:00.994Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:27:00.995 ThaliTest[1273:1704357] jxcore: disconnect
2015-11-25 10:27:00.995 ThaliTest[1273:1704357] client session: disconnectFromPeer: Apple-Iphone6-1_PT8682.g043PA==
2015-11-25 10:27:00.995 ThaliTest[1273:1704357] client session: disconnect
2015-11-25 10:27:00.995 ThaliTest[1273:1704357] client session: stateChange:2->0 Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:27:01.004 ThaliTest[1273:1704357] jxcore: disconnect: success
2015-11-25T09:27:01.005Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8682.g043PA==
---- round done--------
device[3]: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25T09:27:01.007Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT138.uokMhA==
2015-11-25T09:27:01.007Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT138.uokMhA==
2015-11-25T09:27:01.007Z SendDataConnect,or.js: do connect now
2015-11-25 10:27:01.007 ThaliTest[1273:1704357] jxcore: connect Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:01.008 ThaliTest[1273:1704357] client session: connect
2015-11-25 10:27:01.008 ThaliTest[1273:1704357] client session: stateChange:0->1 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:03.620 ThaliTest[1273:1706002] server session: connected
2015-11-25 10:27:03.620 ThaliTest[1273:1706002] server session: stateChange:1->2 Apple-Iphone5-1_PT138
,2015-11-25 10:27:03.631 ThaliTest[1273:1704173] server relay: connected (to port: 61261)
,2015-11-25T09:27:03.635Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 10:27:03.689 ThaliTest[1273:1705946] client session: connected
2015-11-25 10:27:03.689 ThaliTest[1273:1705946] client session: stateChange:1->2 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:03.695 ThaliTest[1273:1706002] client session: fireConnectCallback: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:03.695 ThaliTest[1273:1706002] jxcore: connect: success
,2015-11-25T09:27:03.696Z SendDataConnector.js: CLIENT connected to 61274, error: null
2015-11-25T09:27:03.696Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:27:03.697 ThaliTest[1273:1704173] client: relay established
2015-11-25 10:27:03.697 ThaliTest[1273:1704173] client: new accepted socket: 0x17e63f30
,2015-11-25T09:27:03.710Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:27:04.134Z SendDataTCPServer.js: TCP/IP server has received 7936 bytes of data
,2015-11-25T09:27:04.148Z SendDataTCPServer.js: TCP/IP server has received 53568 bytes of data
,2015-11-25T09:27:04.149Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T09:27:04.162Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-25T09:27:04.658Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:27:04.658Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:04.658Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:04.659Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 10:27:04.659 ThaliTest[1273:1704357] jxcore: disconnect
2015-11-25 10:27:04.659 ThaliTest[1273:1704357] client session: disconnectFromPeer: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:04.659 ThaliTest[1273:1704357] client session: disconne,ct
2015-11-25 10:27:04.659 ThaliTest[1273:1704357] client session: stateChange:2->0 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:04.664 ThaliTest[1273:1704357] jxcore: disconnect: success
2015-11-25T09:27:04.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT138.uokMhA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7460","time":14868,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT1341.lrEeog==","time":4218,"result":"OK","connections":1},{"name":"Apple-Iphone6-1_PT8682.g043PA==","time":6202,"result":"OK","connections":1},{"name":"Apple-Iphone5-1_PT138.uokMhA==","time":3651,"result":"OK","connections":1}]}
sendList : 100% : 6202 ms, 99% : 6202 ms, 95 : 6202 ms, 90% : 6202 ms.
Result count 3, ,range 3651 ms to  6202 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T09:27:04.669Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:04.669Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25T09:27:04.968Z SendDataTCPServer.js: TCP/IP server has received 65472 bytes of data
,2015-11-25T09:27:04.981Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-11-25T09:27:04.995Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
,2015-11-25T09:27:05.056Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-11-25T09:27:05.069Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:27:05.180 ThaliTest[1273:1705948] server session: not connected Apple-Iphone5-1_PT138
,DBG, CoordinatorConnector command called
command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 10:27:05.520 ThaliTest[1273:1704357] jxcore: stopBroadcasting
2015-11-25 10:27:05.521 ThaliTest[1273:1704357] THEMultipeerSession stopping peer
2015-11-25 10:27:05.521 ThaliTest[1273:1704357] multipeer session: stop timer
2015-11-25 10:27:05.521 ThaliTest[1273:1704357] server session: disconnect
2015-11-25 10:27:05.521 ThaliTest[1273:1704357] server session: stateChange:2->0 Apple-Iphone5-1_PT138
,2015-11-25 10:27:05.524 ThaliTest[1273:1704357] server session: disconnect
2015-11-25 10:27:05.524 ThaliTest[1273:1704357] server session: stateChange:2->0 Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:05.528 ThaliTest[1273:1704357] server session: disconnect
2015-11-25 10:27:05.529 ThaliTest[1273:1704357] server session: stateChange:2->0 Apple-Iphone6-1_PT8682
,2015-11-25 10:27:05.533 ThaliTest[1273:1704357] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-25T09:27:05.549Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.549Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.550Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.550Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":3651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":4218,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":6202,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT138.uokMhA=,=\",\"time\":2613,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2752,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2854,\"result\":\"OK\",\"connections\":1},{\"name,\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":3651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":3735,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":3861,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":4218,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":4473,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT13,41.lrEeog==\",\"time\":5315,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6177,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":6202,\"result\":\"OK\",\"connections\",:1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6632,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
