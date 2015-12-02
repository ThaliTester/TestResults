#### Test 52445159d291820_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0AD43ABD-483C-4C63-AC25-F6B35EBAFAE2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0AD43ABD-483C-4C63-AC25-F6B35EBAFAE2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52445159d291820/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A981E433-CD14-478B-8B24-28D2449C9672/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59947"
,(lldb)     command script import "/tmp/0AD43ABD-483C-4C63-AC25-F6B35EBAFAE2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 21:05:18.383 ThaliTest[1833:2866765] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/829732AA-AFDC-4EC4-8124-12B19CD7F254/Library/Cookies/Cookies.binarycookies
,2015-12-02 21:05:18.677 ThaliTest[1833:2866765] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 21:05:18.678 ThaliTest[1833:2866765] Multi-tasking -> Device: YES, App: YES
,2015-12-02 21:05:18.684 ThaliTest[1833:2866765] Unlimited access to network resources
,2015-12-02 21:05:18.689 ThaliTest[1833:2866765] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 21:05:22.838 ThaliTest[1833:2866765] Resetting plugins due to page load.
,2015-12-02 21:05:24.160 ThaliTest[1833:2866765] Finished load of: file:///var/mobile/Containers/Bundle/Application/A981E433-CD14-478B-8B24-28D2449C9672/ThaliTest.app/www/index.html
,2015-12-02 21:05:24.308 ThaliTest[1833:2866765] JXcore Cordova plugin initializing
2015-12-02 21:05:24.309 ThaliTest[1833:2866973] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT369
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 49562
,2015-12-02 21:12:27.038 ThaliTest[1833:2866973] jxcore: startBroadcasting
,2015-12-02 21:12:27.044 ThaliTest[1833:2866973] server: starting Apple-IpadAir2-1_PT369.LHPK5g==
,2015-12-02 21:12:27.044 ThaliTest[1833:2866973] multipeer session: start timer: 0x186c7020
2015-12-02 21:12:27.045 ThaliTest[1833:2866973] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT369
,2015-12-02 21:12:27.045 ThaliTest[1833:2866973] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-02T20:12:27.047Z SendDataTCPServer.js: TCP/IP server is bound to port: 49562
,2015-12-02 21:12:28.796 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:12:28.796 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:12:28.796 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-12-02 21:12:28.796 ThaliTest[1833:2866765] server session: connect
2015-12-02 21:12:28.796 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5-1_PT3314
,2015-12-02 21:12:28.798 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5-1_PT3314
,2015-12-02 21:12:29.235 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3314.VcnsbA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02T20:12:29.237Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02T20:12:29.238Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02T20:12:29.238Z SendDataConnector.js: do connect now
2015-12-02 21:12:29.238 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:29.238 ThaliTest[1833:2866973] client session: connect
,2015-12-02 21:12:29.239 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:29.767 ThaliTest[1833:2866765] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3258.XmE3ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:30.709 ThaliTest[1833:2866765] multipeer session: reset timer
,2015-12-02 21:12:30.709 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:12:30.710 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-12-02 21:12:30.710 ThaliTest[1833:2866765] server session: connect
,2015-12-02 21:12:30.710 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone6-1_PT3258
,2015-12-02 21:12:30.712 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone6-1_PT3258
,2015-12-02 21:12:30.896 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 21:12:31.373 ThaliTest[1833:2867694] server session: connected
2015-12-02 21:12:31.373 ThaliTest[1833:2867694] server session: stateChange:1->2 Apple-Iphone5-1_PT3314
,2015-12-02 21:12:31.376 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:12:31.378Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 21:12:31.742 ThaliTest[1833:2867684] client session: connected
2015-12-02 21:12:31.742 ThaliTest[1833:2867684] client session: stateChange:1->2 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:31.744 ThaliTest[1833:2867694] client session: fireConnectCallback: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:31.744 ThaliTest[1833:2867694] jxcore: connect: success
,2015-12-02T20:12:31.745Z SendDataConnector.js: CLIENT connected to 49566, error: null
2015-12-02T20:12:31.745Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:31.746 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:12:31.746 ThaliTest[1833:2866765] client: new accepted socket: 0x198ad7f0
,2015-12-02T20:12:31.759Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:31.971Z SendDataTCPServer.js: TCP/IP server has received 49600 bytes of data
,2015-12-02T20:12:32.272Z SendDataTCPServer.js: TCP/IP server has received 50592 bytes of data
,2015-12-02T20:12:32.335Z SendDataTCPServer.js: TCP/IP server has received 65472 bytes of data
,2015-12-02T20:12:32.348Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-12-02T20:12:32.387Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T20:12:32.388Z SendDataTCPServer.js: TCP/IP server has received 80352 bytes of data
,2015-12-02T20:12:32.399Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T20:12:32.400Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:32.401Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:32.401Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:32.402 ThaliTest[1833:2866973] jxcore: disconnect
,2015-12-02 21:12:32.402 ThaliTest[1833:2866973] client session: disconnectFromPeer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:12:32.402 ThaliTest[1833:2866973] client session: disconnect
,2015-12-02 21:12:32.402 ThaliTest[1833:2866973] client session: stateChange:2->0 Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:12:32.467 ThaliTest[1833:2866973] jxcore: disconnect: success
2015-12-02T20:12:32.467Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3314.VcnsbA==
,---- round done--------
,device[2]: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:12:32.469Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02T20:12:32.469Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:32.469Z SendDataConnector.js: do connect now
,2015-12-02 21:12:32.470 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:32.470 ThaliTest[1833:2866973] client session: connect
2015-12-02 21:12:32.470 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02T20:12:32.473Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:32.507 ThaliTest[1833:2867692] server session: not connected Apple-Iphone5-1_PT3314
,2015-12-02 21:12:32.979 ThaliTest[1833:2867692] server session: connected
2015-12-02 21:12:32.979 ThaliTest[1833:2867692] server session: stateChange:1->2 Apple-Iphone6-1_PT3258
,2015-12-02 21:12:32.982 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:12:32.990Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:33.303Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T20:12:33.317Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-02T20:12:33.331Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-02T20:12:33.381Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-02T20:12:33.606Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 21:12:33.861 ThaliTest[1833:2867694] server session: not connected Apple-Iphone6-1_PT3258
,2015-12-02 21:12:35.515 ThaliTest[1833:2867694] client session: connected
2015-12-02 21:12:35.515 ThaliTest[1833:2867694] client session: stateChange:1->2 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:35.520 ThaliTest[1833:2867685] client session: fireConnectCallback: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:35.520 ThaliTest[1833:2867685] jxcore: connect: success
2015-12-02T20:12:35.521Z SendDataConnector.js: CLIENT connected to 49571, error: null
2015-12-02T20:12:35.521Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:35.522 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:12:35.522 ThaliTest[1833:2866765] client: new accepted socket: 0x186e45f0
,2015-12-02T20:12:35.535Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:36.051Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:12:36.075Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T20:12:36.075Z SendDataConnector.js: got all data for this round
,2015-12-02T20:12:36.076Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:12:36.076Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:12:36.077 ThaliTest[1833:2866973] jxcore: disconnect
,2015-12-02 21:12:36.077 ThaliTest[1833:2866973] client session: disconnectFromPeer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:12:36.077 ThaliTest[1833:2866973] client session: disconnect
2015-12-02 21:12:36.077 ThaliTest[1833:2866973] client session: stateChange:2->0 Apple-Iphone6-1_PT3258.XmE3ag==
,2015-12-02 21:12:36.149 ThaliTest[1833:2866973] jxcore: disconnect: success
2015-12-02T20:12:36.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3258.XmE3ag==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:36.151Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:36.151Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:12:36.151Z SendDataConnector.js: do connect now
,2015-12-02 21:12:36.152 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:36.152 ThaliTest[1833:2866973] client session: connect
2015-12-02 21:12:36.152 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:38.036 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:12:38.036 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:12:38.036 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-,12-02 21:12:38.036 ThaliTest[1833:2866765] server session: connect
2015-12-02 21:12:38.036 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:38.039 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:39.268 ThaliTest[1833:2867694] client session: connected
2015-12-02 21:12:39.268 ThaliTest[1833:2867694] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:39.317 ThaliTest[1833:2867740] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:39.317 ThaliTest[1833:2867740] jxcore: connect: success
,2015-12-02T20:12:39.318Z SendDataConnector.js: CLIENT connected to 49575, error: null
,2015-12-02T20:12:39.318Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:12:39.320 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:12:39.320 ThaliTest[1833:2866765] client: new accepted socket: 0x198a30f0
,2015-12-02T20:12:39.333Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T20:12:39.745Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T20:12:39.768Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T20:12:39.801Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02 21:12:40.353 ThaliTest[1833:2867740] server session: connected
2015-12-02 21:12:40.353 ThaliTest[1833:2867740] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:12:40.362 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:12:40.367Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:12:40.650Z SendDataTCPServer.js: TCP/IP server has received 25712 bytes of data
,2015-12-02T20:12:40.664Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-02T20:12:40.675Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-02T20:12:40.688Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02T20:12:49.802Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:12:49.802Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:49.803Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:12:49.803Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:12:49.803Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:12:49.804 ThaliTest[1833:2866765] client: socket closed
2015-12-02 21:12:49.804 ThaliTest[1833:2866765] client relay: socket disconnected
2015-12-02 21:12:49.804 ThaliTest[1833:2866765] client relay: 0x198a30f0 disconnected with error Error,ge:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:12:49.804 ThaliTest[1833:2866765] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:49.805 ThaliTest[1833:2866765] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:49.805 ThaliTest[1833:2866765] client session: disconnect
2015-12-02 21:12:49.805 ThaliTest[1833:2866765] client session: stateChan,2015-12-02 21:12:49.807 ThaliTest[1833:2866765] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:50.711 ThaliTest[1833:2867692] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02T20:12:54.808Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:54.809Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:12:59.810 ThaliTest[1833:2866973] jxcore: disconnect
,2015-12-02 21:12:59.810 ThaliTest[1833:2866973] jxcore: disconnect: fail
,2015-12-02T20:12:59.810Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:12:59.811Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
,2015-12-02T20:12:59.811Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:12:59.811Z SendDataConnector.js: do connect now
,2015-12-02 21:12:59.812 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:12:59.812 ThaliTest[1833:2866973] client session: connect
2015-12-02 21:12:59.812 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:00.786 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:13:00.786 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:13:00.786 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-,12-02 21:13:00.786 ThaliTest[1833:2866765] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4399)
2015-12-02 21:13:00.786 ThaliTest[1833:2866765] server session: disconnect
2015-12-02 21:13:00.786 ThaliTest[1833:2866765] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02T20:13:00.799Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:13:00.840 ThaliTest[1833:2866765] server session: connect
2015-12-02 21:13:00.841 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:00.843 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:02.592 ThaliTest[1833:2867827] client session: connected
2015-12-02 21:13:02.592 ThaliTest[1833:2867827] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:02.602 ThaliTest[1833:2867820] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:02.602 ThaliTest[1833:2867820] jxcore: connect: success
,2015-12-02T20:13:02.603Z SendDataConnector.js: CLIENT connected to 49580, error: null
,2015-12-02T20:13:02.603Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:02.604 ThaliTest[1833:2866765] client: relay established
,2015-12-02 21:13:02.604 ThaliTest[1833:2866765] client: new accepted socket: 0x18202740
,2015-12-02T20:13:02.617Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:13:03.051 ThaliTest[1833:2867827] server session: connected
2015-12-02 21:13:03.051 ThaliTest[1833:2867827] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:03.058 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:13:03.060Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:13:03.183Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T20:13:03.196Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02T20:13:12.641Z SendDataConnector.js: Receiving data timeout now
2015-12-02T20:13:12.641Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:12.642Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:12.642Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:12.642Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client: socket closed
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client relay: socket disconnected
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client relay: 0x18202740 disconnected with error Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client session: disconnect
2015-12-02 21:13:12.643 ThaliTest[1833:2866765] client session: stateChan,ge:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:12.646 ThaliTest[1833:2866765] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:13.174 ThaliTest[1833:2867850] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02T20:13:17.650Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:13:17.650Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:22.652 ThaliTest[1833:2866973] jxcore: disconnect
2015-12-02 21:13:22.652 ThaliTest[1833:2866973] jxcore: disconnect: fail
2015-12-02T20:13:22.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7,LQ==
2015-12-02T20:13:22.653Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
2015-12-02T20:13:22.653Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:13:22.653Z SendDataConnector.js: do connect now
2015-12-02 21:13:22.653 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:22.653 ThaliTest[1833:2866973] client session: connect
2015-12-02 21:13:22.653 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:23.630 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:13:23.630 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:13:23.630 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-12-02 21:13:23.630 ThaliTest[1833:2866765] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4399)
2015-12-02 21:13:23.631 ThaliTest[1833:2866765] server session: disconnect
2015-12-02 21:13:23.631 ThaliTest[1833:2866765] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:23.632 ThaliTest[1833:2866765] server session: connect
2015-12-02 21:13:23.632 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:23.636 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02T20:13:23.643Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:13:25.919 ThaliTest[1833:2867877] server session: connected
2015-12-02 21:13:25.919 ThaliTest[1833:2867877] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:25.928 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:13:25.936Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 21:13:25.987 ThaliTest[1833:2867877] client session: connected
,2015-12-02 21:13:25.987 ThaliTest[1833:2867877] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:25.995 ThaliTest[1833:2867877] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:25.996 ThaliTest[1833:2867877] jxcore: connect: success
2015-12-02T20:13:25.996Z SendDataConnector.js: CLIENT connected to 49587, error: null
2015-12-02T20:13:25.996Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:25.997 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:13:25.997 ThaliTest[1833:2866765] client: new accepted socket: 0x186ca460
,2015-12-02T20:13:26.010Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:13:26.056Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02T20:13:36.039Z SendDataConnector.js: Receiving data timeout now
2015-12-02T20:13:36.039Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:36.039Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:36.040Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:36.040Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:36.041 ThaliTest[1833:2866765] client: socket closed
,2015-12-02 21:13:36.041 ThaliTest[1833:2866765] client relay: socket disconnected
,2015-12-02 21:13:36.041 ThaliTest[1833:2866765] client relay: 0x186ca460 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:,36.041 ThaliTest[1833:2866765] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:36.041 ThaliTest[1833:2866765] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:36.041 ThaliTest[1833:2866765] client session: disconnect
2015-12-02 21:13:36.042 ThaliTest[1833:2866765] client session: sta,teChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:36.044 ThaliTest[1833:2866765] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:36.206 ThaliTest[1833:2867874] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02T20:13:41.046Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:13:41.047Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:46.049 ThaliTest[1833:2866973] jxcore: disconnect
2015-12-02 21:13:46.049 ThaliTest[1833:2866973] jxcore: disconnect: fail
2015-12-02T20:13:46.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02T20:13:46.050Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
2015-12-02T20:13:46.050Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:13:46.050Z SendDataConnector.js: do connect now
2015-12-02 21:13:46.050 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:46.050 ThaliTest[1833:2866973] client session: connect
,2015-12-02 21:13:46.051 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:46.692 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:13:46.693 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:13:46.693 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-12-02 21:13:46.693 ThaliTest[1833:2866765] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4399)
2015-12-02 21:13:46.693 ThaliTest[1833:2866765] server session: disconnect
2015-12-02 21:13:46.693 ThaliTest[1833:2866765] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:46.695 ThaliTest[1833:2866765] server session: connect
,2015-12-02 21:13:46.695 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:46.699 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02T20:13:46.704Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:13:49.376 ThaliTest[1833:2867951] server session: connected
2015-12-02 21:13:49.376 ThaliTest[1833:2867951] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:13:49.386 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:13:49.399Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02 21:13:49.451 ThaliTest[1833:2867951] client session: connected
2015-12-02 21:13:49.451 ThaliTest[1833:2867951] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:49.505 ThaliTest[1833:2867951] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:49.505 ThaliTest[1833:2867951] jxcore: connect: success
,2015-12-02T20:13:49.506Z SendDataTCPServer.js: TCP/IP server has received 8618 bytes of data
,2015-12-02T20:13:49.507Z SendDataConnector.js: CLIENT connected to 49592, error: null
,2015-12-02T20:13:49.507Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:13:49.508 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:13:49.508 ThaliTest[1833:2866765] client: new accepted socket: 0x198a30f0
,2015-12-02T20:13:49.522Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02T20:13:49.523Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02T20:13:59.548Z SendDataConnector.js: Receiving data timeout now
2015-12-02T20:13:59.549Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:59.549Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:13:59.549Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-02T20:13:59.550Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:13:59.550 ThaliTest[1833:2866765] client: socket closed
2015-12-02 21:13:59.551 ThaliTest[1833:2866765] client relay: socket disconnected
,2015-12-02 21:13:59.551 ThaliTest[1833:2866765] client relay: 0x198a30f0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2015-12-02 21:13:,59.551 ThaliTest[1833:2866765] client session: socket closed: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:59.551 ThaliTest[1833:2866765] client session: onLinkFailure: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:13:59.551 ThaliTest[1833:2866765] client session: disconnect
2015-12-02 21:13:59.551 ThaliTest[1833:2866765] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:59.553 ThaliTest[1833:2866765] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:13:59.793 ThaliTest[1833:2867955] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02T20:14:04.550Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:04.550Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:09.552 ThaliTest[1833:2866973] jxcore: disconnect
2015-12-02 21:14:09.553 ThaliTest[1833:2866973] jxcore: disconnect: fail
2015-12-02T20:14:09.553Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:09.553Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4399.Q1E7LQ== with availability status: true
2015-12-02T20:14:09.553Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02T20:14:09.553Z SendDataConnector.js: do connect now
2015-12-02 21:14:09.553 ThaliTest[1833:2866973] jxcore: connect Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:09.554 ThaliTest[1833:2866973] client session: connect
2015-12-02 21:14:09.554 ThaliTest[1833:2866973] client session: stateChange:0->1 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:09.781 ThaliTest[1833:2866765] multipeer session: reset timer
2015-12-02 21:14:09.781 ThaliTest[1833:2866765] multipeer session: stop timer
2015-12-02 21:14:09.782 ThaliTest[1833:2866765] multipeer session: start timer: 0x186c7020
2015-12-02 21:14:09.782 ThaliTest[1833:2866765] server: disconnecting to refresh session (Apple-Iphone5s-1_PT4399)
2015-12-02 21:14:09.782 ThaliTest[1833:2866765] server session: disconnect
2015-12-02 21:14:09.782 ThaliTest[1833:2866765] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02 21:14:09.783 ThaliTest[1833:2866765] server session: connect
2015-12-02 21:14:09.783 ThaliTest[1833:2866765] server session: stateChange:0->1 Apple-Iphone5s-1_PT4399
,2015-12-02T20:14:09.786Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02 21:14:09.787 ThaliTest[1833:2866765] server: accepting invitation Apple-Iphone5s-1_PT4399
,2015-12-02 21:14:12.915 ThaliTest[1833:2868018] server session: connected
2015-12-02 21:14:12.915 ThaliTest[1833:2868018] server session: stateChange:1->2 Apple-Iphone5s-1_PT4399
,2015-12-02 21:14:12.922 ThaliTest[1833:2866765] server relay: connected (to port: 49562)
,2015-12-02T20:14:12.926Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T20:14:13.038Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-02 21:14:13.124 ThaliTest[1833:2868012] client session: connected
2015-12-02 21:14:13.124 ThaliTest[1833:2868012] client session: stateChange:1->2 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:13.129 ThaliTest[1833:2868018] client session: fireConnectCallback: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:13.129 ThaliTest[1833:2868018] jxcore: connect: success
2015-12-02T20:14:13.130Z SendDataConnector.js: CLIENT connected to 49597, error: null
,2015-12-02T20:14:13.130Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 21:14:13.132 ThaliTest[1833:2866765] client: relay established
2015-12-02 21:14:13.132 ThaliTest[1833:2866765] client: new accepted socket: 0x18680a50
,2015-12-02T20:14:13.144Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
,2015-12-02 21:14:23.034 ThaliTest[1833:2868012] server session: not connected Apple-Iphone5s-1_PT4399
,2015-12-02T20:14:23.168Z SendDataConnector.js: Receiving data timeout now
,2015-12-02T20:14:23.168Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:14:23.168Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02T20:14:23.169Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:14:23.169Z SendDataConnector.js: Stop data retrieving timer
,2015-12-02T20:14:23.170Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 21:14:23.170 ThaliTest[1833:2866973] jxcore: disconnect
2015-12-02 21:14:23.170 ThaliTest[1833:2866973] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
2015-12-02 21:14:23.170 ThaliTest[1833:2866973] client session: discon,nect
2015-12-02 21:14:23.170 ThaliTest[1833:2866973] client session: stateChange:2->0 Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:14:23.172 ThaliTest[1833:2866973] jxcore: disconnect: success
2015-12-02T20:14:23.172Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4399.Q1E7LQ==
---- round done--------
weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT369","time":116141,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT3314.VcnsbA==","time":3163,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3258.XmE3ag==","time":3606,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT4399.Q1E7LQ==","time":107017,"result":"DATA-TIMEOUT","connections":5,"doneRounds":1,"dataAmount":100000,"dataRe,ceived":90000}]}
sendList : 100% : 3606 ms, 99% : 3606 ms, 95 : 3606 ms, 90% : 3606 ms.
Result count 2, range 3163 ms to  3606 ms.
,sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone5s-1_PT4399.Q1E7LQ==, Tried : 5
sendList never tried peers count : 0 [0 %]
2015-12-02T20:14:23.177Z SendDataConnector.js: CLIENT Stop now
2015-12-02T20:14:23.177Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-02T20:14:23.178Z SendDataConnector.js: ----------------- closeClientSocket
,2015-12-02 21:14:39.783 ThaliTest[1833:2866765] multipeer session: restart
,2015-12-02 21:15:09.783 ThaliTest[1833:2866765] multipeer session: restart
,2015-12-02 21:15:09.793 ThaliTest[1833:2866765] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
2015-12-02 21:15:09.793 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
,2015-12-02 21:15:09.794 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:39.783 ThaliTest[1833:2866765] multipeer session: restart
,2015-12-02 21:15:39.793 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5-1_PT3314.VcnsbA==
2015-12-02 21:15:39.793 ThaliTest[1833:2866765] client: found peer: Apple-Iphone5s-1_PT4399.Q1E7LQ==
,2015-12-02 21:15:40.584 ThaliTest[1833:2866765] client: found peer: Apple-Iphone6-1_PT3258.XmE3ag==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
2015-12-02 21:16:04.352 ThaliTest[1833:2866973] jxcore: stopBroadcasting
2015-12-02 21:16:04.353 ThaliTest[1833:2866973] THEMultipeerSession stopping peer
2015-12-02 21:16:04.353 ThaliTest[1833:2866973] multipeer session: stop timer
2015-12-02 21:16:04.353 ThaliTest[1833:2866973] server session: disconnect
2015-12-02 21:16:04.353 ThaliTest[1833:2866973] server session: stateChange:2->0 Apple-Iphone5-1_PT3314
,2015-12-02 21:16:04.414 ThaliTest[1833:2866973] server session: disconnect
2015-12-02 21:16:04.415 ThaliTest[1833:2866973] server session: stateChange:2->0 Apple-Iphone6-1_PT3258
,2015-12-02 21:16:04.472 ThaliTest[1833:2866973] server session: disconnect
2015-12-02 21:16:04.472 ThaliTest[1833:2866973] server session: stateChange:2->0 Apple-Iphone5s-1_PT4399
,2015-12-02 21:16:04.474 ThaliTest[1833:2866973] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-02T20:16:04.489Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:04.490Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:04.490Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T20:16:04.491Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT3314.VcnsbA==\",\"time\":3163,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dat,aAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone6-1_PT3258.XmE3ag==\",\"time\":3606,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone5s-1_PT4399.Q1E7LQ==\",\"time\":107017,\"result\":\"DATA-TIMEOUT\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":90000}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
