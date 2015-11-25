#### Test 513350283842813_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CBD13FCB-EA9C-4956-A4C2-2E30D86824A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CBD13FCB-EA9C-4956-A4C2-2E30D86824A4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350283842813/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6870EFC3-B28D-449D-BD7B-EA8E79C36DDA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55196"
,(lldb)     command script import "/tmp/CBD13FCB-EA9C-4956-A4C2-2E30D86824A4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 10:18:48.832 ThaliTest[1638:1283124] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4682E1A3-76C9-4DF4-AE25-7DE42B8DDD21/Library/Cookies/Cookies.binarycookies
,2015-11-25 10:18:49.204 ThaliTest[1638:1283124] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-25 10:18:49.205 ThaliTest[1638:1283124] Multi-tasking -> Device: YES, App: YES
,2015-11-25 10:18:49.213 ThaliTest[1638:1283124] Unlimited access to network resources
,2015-11-25 10:18:49.218 ThaliTest[1638:1283124] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 10:18:52.683 ThaliTest[1638:1283124] Resetting plugins due to page load.
,2015-11-25 10:18:53.040 ThaliTest[1638:1283124] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/6870EFC3-B28D-449D-BD7B-EA8E79C36DDA/ThaliTest.app/www/index.html
,2015-11-25 10:18:53.165 ThaliTest[1638:1283124] JXcore Cordova plugin initializing
2015-11-25 10:18:53.166 ThaliTest[1638:1283257] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT8682
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":3,"addressList":[],}
,Start now : testSendData.js
,stop tests now !
,testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 0
,check server
,serverPort is 61528
,2015-11-25 10:26:49.310 ThaliTest[1638:1283257] jxcore: startBroadcasting
,2015-11-25 10:26:49.322 ThaliTest[1638:1283257] server: starting Apple-Iphone6-1_PT8682.g043PA==
,2015-11-25 10:26:49.324 ThaliTest[1638:1283257] multipeer session: start timer: 0x1b5a1770
2015-11-25 10:26:49.324 ThaliTest[1638:1283257] THEMultipeerSession initialized peer Apple-Iphone6-1_PT8682
2015-11-25 10:26:49.325 ThaliTest[1638:1283257] jxcore:, startBroadcasting: success
StartBroadcasting started ok
2015-11-25T09:26:49.327Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
,2015-11-25 10:26:49.603 ThaliTest[1638:1283124] client: found peer: Apple-Iphone5s-1_PT1341.lrEeog==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1341.lrEeog==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:49.606Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:49.606Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25T09:26:49.606Z SendDataConnector.js: do connect now
,2015-11-25 10:26:49.606 ThaliTest[1638:1283257] jxcore: connect Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:49.606 ThaliTest[1638:1283257] client session: connect
2015-11-25 10:26:49.607 ThaliTest[1638:1283257] client session: stateChange:0->1 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:49.953 ThaliTest[1638:1283124] multipeer session: reset timer
2015-11-25 10:26:49.953 ThaliTest[1638:1283124] multipeer session: stop timer
2015-11-25 10:26:49.954 ThaliTest[1638:1283124] multipeer session: start timer: 0x1b5a1770
2015-,11-25 10:26:49.954 ThaliTest[1638:1283124] server session: connect
2015-11-25 10:26:49.955 ThaliTest[1638:1283124] server session: stateChange:0->1 Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:49.966 ThaliTest[1638:1283124] server: accepting invitation Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:50.128 ThaliTest[1638:1283124] multipeer session: reset timer
2015-11-25 10:26:50.128 ThaliTest[1638:1283124] multipeer session: stop timer
2015-11-25 10:26:50.128 ThaliTest[1638:1283124] multipeer session: start timer: 0x1b5a1770
2015-,11-25 10:26:50.128 ThaliTest[1638:1283124] server session: connect
2015-11-25 10:26:50.129 ThaliTest[1638:1283124] server session: stateChange:0->1 Apple-Iphone5-1_PT138
,2015-11-25 10:26:50.131 ThaliTest[1638:1283124] server: accepting invitation Apple-Iphone5-1_PT138
,2015-11-25 10:26:50.773 ThaliTest[1638:1283124] client: found peer: Apple-IpadAir2-1_PT7460.CVEGJA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7460.CVEGJA==","peerName":"(null)","peerAvailable":true}]
2015-11-25 10:26:50.776 ThaliTes,t[1638:1283124] client: found peer: Apple-Iphone5-1_PT138.uokMhA==
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT138.uokMhA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 10:26:52.251 ThaliTest[1638:1283952] server session: connected
2015-11-25 10:26:52.252 ThaliTest[1638:1283952] server session: stateChange:1->2 Apple-Iphone5s-1_PT1341
,2015-11-25 10:26:52.262 ThaliTest[1638:1283124] server relay: connected (to port: 61528)
,2015-11-25T09:26:52.269Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25 10:26:52.285 ThaliTest[1638:1283962] server session: connected
2015-11-25 10:26:52.286 ThaliTest[1638:1283962] server session: stateChange:1->2 Apple-Iphone5-1_PT138
,2015-11-25 10:26:52.296 ThaliTest[1638:1283124] server relay: connected (to port: 61528)
,2015-11-25T09:26:52.307Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:26:52.370Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T09:26:52.382Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-11-25T09:26:52.400Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-11-25T09:26:52.418Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-11-25T09:26:52.434Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:26:52.441 ThaliTest[1638:1283957] server session: not connected Apple-Iphone5s-1_PT1341
,2015-11-25T09:26:52.449Z SendDataTCPServer.js: TCP/IP server has received 2976 bytes of data
,2015-11-25T09:26:52.488Z SendDataTCPServer.js: TCP/IP server has received 5952 bytes of data
,2015-11-25T09:26:52.503Z SendDataTCPServer.js: TCP/IP server has received 25792 bytes of data
,2015-11-25T09:26:52.518Z SendDataTCPServer.js: TCP/IP server has received 43648 bytes of data
,2015-11-25T09:26:52.531Z SendDataTCPServer.js: TCP/IP server has received 57536 bytes of data
,2015-11-25T09:26:52.545Z SendDataTCPServer.js: TCP/IP server has received 71424 bytes of data
,2015-11-25T09:26:52.558Z SendDataTCPServer.js: TCP/IP server has received 84320 bytes of data
,2015-11-25T09:26:52.574Z SendDataTCPServer.js: TCP/IP server has received 95232 bytes of data
,2015-11-25T09:26:52.587Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:26:52.607 ThaliTest[1638:1283962] server session: not connected Apple-Iphone5-1_PT138
,2015-11-25 10:26:53.119 ThaliTest[1638:1283957] client session: connected
2015-11-25 10:26:53.119 ThaliTest[1638:1283957] client session: stateChange:1->2 Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:53.131 ThaliTest[1638:1283977] client session: fireConnectCallback: Apple-Iphone5s-1_PT1341.lrEeog==
,2015-11-25 10:26:53.134 ThaliTest[1638:1283977] jxcore: connect: success
,2015-11-25T09:26:53.135Z SendDataConnector.js: CLIENT connected to 61533, error: null
,2015-11-25T09:26:53.136Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:53.139 ThaliTest[1638:1283124] client: relay established
2015-11-25 10:26:53.140 ThaliTest[1638:1283124] client: new accepted socket: 0x1b203bd0
,2015-11-25T09:26:53.152Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:53.265Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T09:26:53.278Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T09:26:53.291Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T09:26:53.301Z SendDataConnector.js: CLIENT is data received : 60000
,2015-11-25T09:26:53.327Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:26:53.340Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T09:26:53.340Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:53.341Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:53.341Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 10:26:53.342 ThaliTest[1638:1283257] jxcore: disconnect
2015-11-25 10:26:53.342 ThaliTest[1638:1283257] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:53.342 ThaliTest[1638:1283257] client session: disconnect
2015-11-25 10:26:53.342 ThaliTest[1638:1283257] client session: stateChange:2->0 Apple-Iphone5s-1_PT1341.lrEeog==
2015-11-25 10:26:53.343 ThaliTest[1638:1283257] jxcore: disconnect: success
2015-11-25T09:26:53.344Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1341.lrEeog==
---- round done--------
device[2]: Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25T09:26:53.345Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:26:53.346Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25T09:26:53.346Z SendDataConnector.js: do connect now
,2015-11-25 10:26:53.346 ThaliTest[1638:1283257] jxcore: connect Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:53.347 ThaliTest[1638:1283257] client session: connect
2015-11-25 10:26:53.347 ThaliTest[1638:1283257] client session: stateChange:0->1 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:56.800 ThaliTest[1638:1283124] multipeer session: reset timer
2015-11-25 10:26:56.800 ThaliTest[1638:1283124] multipeer session: stop timer
2015-11-25 10:26:56.801 ThaliTest[1638:1283124] multipeer session: start timer: 0x1b5a1770
2015-,11-25 10:26:56.802 ThaliTest[1638:1283124] server session: connect
2015-11-25 10:26:56.802 ThaliTest[1638:1283124] server session: stateChange:0->1 Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:56.808 ThaliTest[1638:1283124] server: accepting invitation Apple-IpadAir2-1_PT7460
,2015-11-25 10:26:58.907 ThaliTest[1638:1283961] client session: connected
2015-11-25 10:26:58.907 ThaliTest[1638:1283961] client session: stateChange:1->2 Apple-IpadAir2-1_PT7460.CVEGJA==
,2015-11-25 10:26:58.925 ThaliTest[1638:1283961] client session: fireConnectCallback: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:58.925 ThaliTest[1638:1283961] jxcore: connect: success
2015-11-25T09:26:58.926Z SendDataConnector.js: CLIENT connected to 61536, error: null
2015-11-25T09:26:58.927Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:26:58.930 ThaliTest[1638:1283124] client: relay established
2015-11-25 10:26:58.930 ThaliTest[1638:1283124] client: new accepted socket: 0x1b2fa360
,2015-11-25T09:26:58.941Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:26:59.458Z SendDataConnector.js: CLIENT is data received : 70000
,2015-11-25T09:26:59.522Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T09:26:59.523Z SendDataConnector.js: got all data for this round
,2015-11-25T09:26:59.525Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:26:59.525Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 10:26:59.526 ThaliTest[1638:1283257] jxcore: disconnect
,2015-11-25 10:26:59.527 ThaliTest[1638:1283257] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:59.528 ThaliTest[1638:1283257] client session: disconnect
2015-11-25 10:26:59.528 ThaliTest[1638:1283257] client session,: stateChange:2->0 Apple-IpadAir2-1_PT7460.CVEGJA==
2015-11-25 10:26:59.530 ThaliTest[1638:1283257] jxcore: disconnect: success
2015-11-25T09:26:59.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7460.CVEGJA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25T09:26:59.536Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25T09:26:59.537Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25T09:26:59.537Z SendDataConnector.js: do connect now
,2015-11-25 10:26:59.538 ThaliTest[1638:1283257] jxcore: connect Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:26:59.539 ThaliTest[1638:1283257] client session: connect
2015-11-25 10:26:59.540 ThaliTest[1638:1283257] client session: stateChange:0->1 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:00.014 ThaliTest[1638:1283957] server session: connected
2015-11-25 10:27:00.015 ThaliTest[1638:1283957] server session: stateChange:1->2 Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:00.040 ThaliTest[1638:1283124] server relay: connected (to port: 61528)
,2015-11-25T09:27:00.050Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T09:27:00.273Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T09:27:00.289Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-11-25T09:27:00.307Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-11-25T09:27:00.324Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-11-25T09:27:00.339Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 10:27:00.530 ThaliTest[1638:1283957] server session: not connected Apple-IpadAir2-1_PT7460
,2015-11-25 10:27:01.854 ThaliTest[1638:1283977] client session: connected
2015-11-25 10:27:01.855 ThaliTest[1638:1283977] client session: stateChange:1->2 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:01.889 ThaliTest[1638:1283957] client session: fireConnectCallback: Apple-Iphone5-1_PT138.uokMhA==
2015-11-25 10:27:01.890 ThaliTest[1638:1283957] jxcore: connect: success
2015-11-25T09:27:01.891Z SendDataConnector.js: CLIENT connected t,o 61540, error: null
2015-11-25T09:27:01.892Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 10:27:01.895 ThaliTest[1638:1283124] client: relay established
2015-11-25 10:27:01.896 ThaliTest[1638:1283124] client: new accepted socket: 0x1b611f60
,2015-11-25T09:27:01.908Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T09:27:02.001Z SendDataConnector.js: CLIENT is data received : 10000
,2015-11-25T09:27:02.036Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T09:27:02.137Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T09:27:02.150Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T09:27:02.150Z SendDataConnector.js: got all data for this round
,2015-11-25T09:27:02.151Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:02.151Z SendDataConnector.js: CLIENT closeClientSocket
2015-11-25 10:27:02.151 ThaliTest[1638:1283257] jxcore: disconnect
2015-11-25 10:27:02.151 ThaliTest[1638:1283257] client session: disconnectFromPeer: Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:02.152 ThaliTest[1638:1283257] client session: disconnect
2015-11-25 10:27:02.152 ThaliTest[1638:1283257] client session: stateChange:2->0 Apple-Iphone5-1_PT138.uokMhA==
,2015-11-25 10:27:02.153 ThaliTest[1638:1283257] jxcore: disconnect: success
2015-11-25T09:27:02.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT138.uokMhA==
---- round done--------
weAreDoneNow , resultArray.length: 3,
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT8682","time":12861,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT1341.lrEeog==","time":3735,"result":"OK","connections":1},{"name":"Apple-IpadAir2-1_PT7460.CVEGJA==","time":6177,"result":"OK","connections",:1},{"name":"Apple-Iphone5-1_PT138.uokMhA==","time":2613,"result":"OK","connections":1}]}
sendList : 100% : 6177 ms, 99% : 6177 ms, 95 : 6177 ms, 90% : 6177 ms.
Result count 3, range 2613 ms to  6177 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T09:27:02.158Z SendDataConnector.js: CLIENT Stop now
2015-11-25T09:27:02.158Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-11-25 10:27:05.429 ThaliTest[1638:1283257] jxcore: stopBroadcasting
,2015-11-25 10:27:05.430 ThaliTest[1638:1283257] THEMultipeerSession stopping peer
,2015-11-25 10:27:05.431 ThaliTest[1638:1283257] multipeer session: stop timer
2015-11-25 10:27:05.432 ThaliTest[1638:1283257] server session: disconnect
2015-11-25 10:27:05.433 ThaliTest[1638:1283257] server session: stateChange:2->0 Apple-IpadAir2-1_PT7,460
,2015-11-25 10:27:05.439 ThaliTest[1638:1283257] server session: disconnect
,2015-11-25 10:27:05.440 ThaliTest[1638:1283257] server session: stateChange:2->0 Apple-Iphone5s-1_PT1341
,2015-11-25 10:27:05.443 ThaliTest[1638:1283257] server session: disconnect
2015-11-25 10:27:05.444 ThaliTest[1638:1283257] server session: stateChange:2->0 Apple-Iphone5-1_PT138
,2015-11-25 10:27:05.453 ThaliTest[1638:1283257] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-25T09:27:05.475Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.477Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.478Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T09:27:05.480Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":2613,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":3735,\"r,esult\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6177,\"result\":\"OK\",\"connections\":1}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}},\"combined\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT138.uokMhA,==\",\"time\":2613,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2752,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":2854,\"result\":\"OK\",\"connections\":1},{\"nam,e\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":3651,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":3735,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":3861,\"resul,t\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1341.lrEeog==\",\"time\":4218,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5-1_PT138.uokMhA==\",\"time\":4473,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone5s-1_PT1,341.lrEeog==\",\"time\":5315,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6177,\"result\":\"OK\",\"connections\":1},{\"name\":\"Apple-Iphone6-1_PT8682.g043PA==\",\"time\":6202,\"result\":\"OK\",\"connections\,":1},{\"name\":\"Apple-IpadAir2-1_PT7460.CVEGJA==\",\"time\":6632,\"result\":\"OK\",\"connections\":1}]}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !
end, event received
Coordin
```
