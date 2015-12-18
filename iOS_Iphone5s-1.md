#### Test 539786633aa3ea0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/643D764B-902A-4D8D-8F9B-A3B04F7B0294/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/643D764B-902A-4D8D-8F9B-A3B04F7B0294/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786633aa3ea0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/84FDAA9E-4F09-48A5-B337-EA544762E32F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60065"
,(lldb)     command script import "/tmp/643D764B-902A-4D8D-8F9B-A3B04F7B0294/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 14:26:38.065 ThaliTest[443:344857] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA49321E-3DF9-4073-9C65-4D0E6DE39A7C/Library/Cookies/Cookies.binarycookies
,2015-12-18 14:26:38.436 ThaliTest[443:344857] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 14:26:38.437 ThaliTest[443:344857] Multi-tasking -> Device: YES, App: YES
,2015-12-18 14:26:38.446 ThaliTest[443:344857] Unlimited access to network resources
,2015-12-18 14:26:38.459 ThaliTest[443:344857] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 14:26:47.296 ThaliTest[443:344857] Resetting plugins due to page load.
,2015-12-18 14:26:51.167 ThaliTest[443:344857] Finished load of: file:///var/mobile/Containers/Bundle/Application/84FDAA9E-4F09-48A5-B337-EA544762E32F/ThaliTest.app/www/index.html
,2015-12-18 14:26:51.388 ThaliTest[443:344857] JXcore Cordova plugin initializing
,2015-12-18 14:26:51.389 ThaliTest[443:345040] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT4569
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
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51090
,2015-12-18 14:39:33.082 ThaliTest[443:345040] jxcore: startBroadcasting
,2015-12-18 14:39:33.109 ThaliTest[443:345040] server: starting Apple-Iphone5s-1_PT4569.cwXFvg==
,2015-12-18 14:39:33.115 ThaliTest[443:345040] multipeer session: start timer: 0x17544c30
,2015-12-18 14:39:33.125 ThaliTest[443:345040] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4569
,2015-12-18 14:39:33.126 ThaliTest[443:345040] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18T13:39:33.129Z SendDataTCPServer.js: TCP/IP server is bound to port: 51090
,2015-12-18 14:39:33.840 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6006.TYpyOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,device[1]: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:33.848Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18T13:39:33.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18T13:39:33.851Z SendDataConnector.js: do connect now
,2015-12-18 14:39:33.853 ThaliTest[443:345040] jxcore: connect Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:33.854 ThaliTest[443:345040] client session: connect
2015-12-18 14:39:33.854 ThaliTest[443:345040] client session: stateChange:0->1 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:33.927 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:35.044 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5907.ktOSYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 14:39:38.531 ThaliTest[443:346120] client session: connected
2015-12-18 14:39:38.531 ThaliTest[443:346120] client session: stateChange:1->2 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:38.593 ThaliTest[443:346162] client session: fireConnectCallback: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:39:38.593 ThaliTest[443:346162] jxcore: connect: success
,2015-12-18T13:39:38.595Z SendDataConnector.js: CLIENT connected to 51093, error: null
,2015-12-18T13:39:38.596Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:38.600 ThaliTest[443:344857] client: relay established
2015-12-18 14:39:38.601 ThaliTest[443:344857] client: new accepted socket: 0x18eee5e0
,2015-12-18T13:39:38.617Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:39.056Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T13:39:39.082Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T13:39:39.108Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:39.108Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:39.110Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T13:39:39.110Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:39.111 ThaliTest[443:345040] jxcore: disconnect
,2015-12-18 14:39:39.112 ThaliTest[443:345040] client session: disconnectFromPeer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:39.113 ThaliTest[443:345040] client session: disconnect
,2015-12-18 14:39:39.113 ThaliTest[443:345040] client session: stateChange:2->0 Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:39:39.186 ThaliTest[443:345040] jxcore: disconnect: success
,2015-12-18T13:39:39.187Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6006.TYpyOQ==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:39:39.190Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:39:39.190Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18T13:39:39.190Z SendDataConnector.js: do connect now
,2015-12-18 14:39:39.191 ThaliTest[443:345040] jxcore: connect Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:39.192 ThaliTest[443:345040] client session: connect
,2015-12-18 14:39:39.192 ThaliTest[443:345040] client session: stateChange:0->1 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:40.802 ThaliTest[443:344857] multipeer session: reset timer
,2015-12-18 14:39:40.802 ThaliTest[443:344857] multipeer session: stop timer
2015-12-18 14:39:40.803 ThaliTest[443:344857] multipeer session: start timer: 0x17544c30
,2015-12-18 14:39:40.805 ThaliTest[443:344857] server session: connect
2015-12-18 14:39:40.805 ThaliTest[443:344857] server session: stateChange:0->1 Apple-Iphone6-1_PT5907
,2015-12-18 14:39:40.818 ThaliTest[443:344857] server: accepting invitation Apple-Iphone6-1_PT5907
,2015-12-18 14:39:40.827 ThaliTest[443:344857] multipeer session: reset timer
2015-12-18 14:39:40.827 ThaliTest[443:344857] multipeer session: stop timer
,2015-12-18 14:39:40.827 ThaliTest[443:344857] multipeer session: start timer: 0x17544c30
,2015-12-18 14:39:40.836 ThaliTest[443:344857] server session: connect
,2015-12-18 14:39:40.838 ThaliTest[443:344857] server session: stateChange:0->1 Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:40.848 ThaliTest[443:344857] server: accepting invitation Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:42.881 ThaliTest[443:346162] client session: connected
2015-12-18 14:39:42.882 ThaliTest[443:346162] client session: stateChange:1->2 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:42.915 ThaliTest[443:346121] client session: fireConnectCallback: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:39:42.916 ThaliTest[443:346121] jxcore: connect: success
,2015-12-18T13:39:42.918Z SendDataConnector.js: CLIENT connected to 51096, error: null
,2015-12-18T13:39:42.919Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:42.923 ThaliTest[443:344857] client: relay established
,2015-12-18 14:39:42.925 ThaliTest[443:344857] client: new accepted socket: 0x18d6f700
,2015-12-18T13:39:42.937Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:43.285Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T13:39:43.299Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T13:39:43.311Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18 14:39:43.435 ThaliTest[443:346121] server session: connected
2015-12-18 14:39:43.435 ThaliTest[443:346121] server session: stateChange:1->2 Apple-Iphone6-1_PT5907
,2015-12-18 14:39:43.443 ThaliTest[443:344857] server relay: connected (to port: 51090)
,2015-12-18T13:39:43.446Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:39:43.472Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T13:39:43.473Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:43.474Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:43.474Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:43.474 ThaliTest[443:345040] jxcore: disconnect
2015-12-18 14:39:43.475 ThaliTest[443:345040] client session: disconnectFromPeer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:39:43.475 ThaliTest[443:345040] client session: disconnect
,2015-12-18 14:39:43.475 ThaliTest[443:345040] client session: stateChange:2->0 Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:39:43.480 ThaliTest[443:345040] jxcore: disconnect: success
2015-12-18T13:39:43.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT4577.+7TbDw==
---- round done--------
device[3]: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18T13:39:43.483Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18T13:39:43.483Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18T13:39:43.483Z SendDataConne,ctor.js: do connect now
2015-12-18 14:39:43.483 ThaliTest[443:345040] jxcore: connect Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:43.484 ThaliTest[443:345040] client session: connect
2015-12-18 14:39:43.485 ThaliTest[443:345040] client session: stateChange:0->1 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18T13:39:43.723Z SendDataTCPServer.js: TCP/IP server has received 12998 bytes of data
,2015-12-18T13:39:43.736Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T13:39:43.762Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-18T13:39:43.780Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-12-18 14:39:43.792 ThaliTest[443:346121] server session: connected
2015-12-18 14:39:43.792 ThaliTest[443:346121] server session: stateChange:1->2 Apple-IpadAir2-1_PT4577
,2015-12-18T13:39:43.796Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:43.816 ThaliTest[443:344857] server relay: connected (to port: 51090)
,2015-12-18T13:39:43.824Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 14:39:43.878 ThaliTest[443:346122] server session: not connected Apple-Iphone6-1_PT5907
,2015-12-18T13:39:44.226Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T13:39:44.244Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-18T13:39:44.263Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-18T13:39:44.278Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-18T13:39:44.293Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:39:44.387 ThaliTest[443:346120] server session: not connected Apple-IpadAir2-1_PT4577
,2015-12-18 14:39:46.380 ThaliTest[443:346120] client session: connected
2015-12-18 14:39:46.381 ThaliTest[443:346120] client session: stateChange:1->2 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:46.393 ThaliTest[443:346120] client session: fireConnectCallback: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:46.393 ThaliTest[443:346120] jxcore: connect: success
,2015-12-18T13:39:46.395Z SendDataConnector.js: CLIENT connected to 51101, error: null
,2015-12-18T13:39:46.396Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 14:39:46.400 ThaliTest[443:344857] client: relay established
2015-12-18 14:39:46.400 ThaliTest[443:344857] client: new accepted socket: 0x1893f030
,2015-12-18T13:39:46.413Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T13:39:46.868Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T13:39:46.881Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T13:39:46.894Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T13:39:46.918Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18T13:39:46.932Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T13:39:46.945Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T13:39:46.946Z SendDataConnector.js: got all data for this round
,2015-12-18T13:39:46.947Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:46.947Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:39:46.947 ThaliTest[443:345040] jxcore: disconnect
2015-12-18 14:39:46.947 ThaliTest[443:345040] client session: disconnectFromPeer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:39:46.947 ThaliTest[443:345040] client session: disconnect
2015-12-18 14:39:46.948 ThaliTest[443:345040] client session: stateChange:2->0 Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:39:46.955 ThaliTest[443:345040] jxcore: disconnect: success
2015-12-18T13:39:46.956Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5907.ktOSYA==
---- round done--------
,weAreDoneNow , resultArray.length: 3
done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT4569","time":13895,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT6006.TYpyOQ==","time":526,0,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT4577.+7TbDw==","time":4283,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-,1_PT5907.ktOSYA==","time":3463,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 5260 ms, 99% : 5260 ms, 95 : 5260 ms, 90% : 5260 ms.
Result count 3, range 3463 ms to  5260 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
,2015-12-18T13:39:46.963Z SendDataConnector.js: CLIENT Stop now
2015-12-18T13:39:46.963Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 14:40:10.838 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:40:10.901 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:40:10.902 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:40:10.902 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:40:37.481 ThaliTest[443:344857] multipeer session: reset timer
2015-12-18 14:40:37.481 ThaliTest[443:344857] multipeer session: stop timer
2015-12-18 14:40:37.482 ThaliTest[443:344857] multipeer session: start timer: 0x17544c30
2015-12-18 ,14:40:37.482 ThaliTest[443:344857] server session: connect
2015-12-18 14:40:37.482 ThaliTest[443:344857] server session: stateChange:0->1 Apple-Iphone5-1_PT6006
,2015-12-18 14:40:37.495 ThaliTest[443:344857] server: accepting invitation Apple-Iphone5-1_PT6006
,2015-12-18 14:40:40.796 ThaliTest[443:346354] server session: connected
,2015-12-18 14:40:40.796 ThaliTest[443:346354] server session: stateChange:1->2 Apple-Iphone5-1_PT6006
,2015-12-18 14:40:40.822 ThaliTest[443:344857] server relay: connected (to port: 51090)
,2015-12-18T13:40:40.826Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T13:40:41.329Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T13:40:41.349Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T13:40:41.368Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T13:40:41.391Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-18T13:40:41.410Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-18T13:40:41.425Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 14:40:41.668 ThaliTest[443:346354] server session: not connected Apple-Iphone5-1_PT6006
,2015-12-18 14:41:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:41:07.555 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:41:07.558 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:41:07.558 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:41:09.376 ThaliTest[443:344857] client: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:41:09.376 ThaliTest[443:344857] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:41:21.087 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:41:37.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:41:37.552 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:41:37.566 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:41:37.569 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:42:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:42:07.543 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
,2015-12-18 14:42:07.548 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:42:07.548 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:42:14.058 ThaliTest[443:344857] client: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:42:14.059 ThaliTest[443:344857] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:42:20.992 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-18 14:42:37.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:42:38.416 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:42:38.417 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:42:38.418 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:42:50.335 ThaliTest[443:344857] client: lost peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:42:50.335 ThaliTest[443:344857] client session: onPeerLost: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":false}]
,2015-12-18 14:42:54.665 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT4577.+7TbDw==","peerName":"(null)","peerAvailable":true}]
,2015-12-18 14:43:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:43:07.565 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:43:07.567 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:43:07.576 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:43:37.483 ThaliTest[443:344857] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
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
,2015-12-18 14:44:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:44:07.544 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:44:07.553 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:44:07.554 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
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
,2015-12-18 14:44:37.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:44:37.535 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:44:37.535 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:44:37.535 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:45:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:45:07.530 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
,2015-12-18 14:45:07.534 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:45:07.534 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,2015-12-18 14:45:37.483 ThaliTest[443:344857] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:46:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:46:07.536 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:46:07.537 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:46:07.538 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,2015-12-18 14:46:37.483 ThaliTest[443:344857] multipeer session: restart
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:47:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:47:07.538 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:47:07.538 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:47:07.539 ThaliTest[443:344857] client: fou,nd peer: Apple-Iphone6-1_PT5907.ktOSYA==
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
,2015-12-18 14:47:37.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:47:37.548 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:47:37.548 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:47:37.549 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:48:07.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:48:07.545 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:48:07.546 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
,2015-12-18 14:48:07.546 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
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
,2015-12-18 14:48:37.482 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:48:37.539 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:48:37.544 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:48:37.545 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:49:07.482 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:49:07.547 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:49:07.548 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:49:07.548 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
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
,2015-12-18 14:49:37.483 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:49:37.541 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:49:37.542 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:49:37.545 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:50:07.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:50:07.517 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:50:07.517 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:50:07.518 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,2015-12-18 14:50:37.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:50:37.517 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:50:37.518 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:50:37.518 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:51:07.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:51:07.512 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:51:07.512 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:51:07.513 ThaliTest[443:344857] client: foun,d peer: Apple-IpadAir2-1_PT4577.+7TbDw==
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
,2015-12-18 14:51:37.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:51:37.509 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
2015-12-18 14:51:37.510 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:51:37.512 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:52:07.454 ThaliTest[443:344857] multipeer session: restart
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
,2015-12-18 14:52:37.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:52:37.508 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:52:37.509 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:52:37.511 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
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
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-18 14:53:07.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:53:07.513 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:53:07.514 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:53:07.518 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
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
,2015-12-18 14:53:37.454 ThaliTest[443:344857] multipeer session: restart
,2015-12-18 14:53:37.509 ThaliTest[443:344857] client: found peer: Apple-IpadAir2-1_PT4577.+7TbDw==
2015-12-18 14:53:37.510 ThaliTest[443:344857] client: found peer: Apple-Iphone6-1_PT5907.ktOSYA==
2015-12-18 14:53:37.512 ThaliTest[443:344857] client: found peer: Apple-Iphone5-1_PT6006.TYpyOQ==
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

```
