#### Test 5227736558f1fb0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1982AA4F-F8C5-4433-AD05-C358AE9DD3CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/1982AA4F-F8C5-4433-AD05-C358AE9DD3CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5227736558f1fb0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A084EF1F-3810-40F2-AF47-7B0D7901EC4D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59548"
,(lldb)     command script import "/tmp/1982AA4F-F8C5-4433-AD05-C358AE9DD3CE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:05:10.626 ThaliTest[1791:2840347] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/23943C19-4DD1-4690-BD06-41A1712157C8/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:05:10.890 ThaliTest[1791:2840347] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 18:05:10.891 ThaliTest[1791:2840347] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:05:10.897 ThaliTest[1791:2840347] Unlimited access to network resources
,2015-12-02 18:05:10.904 ThaliTest[1791:2840347] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:05:14.888 ThaliTest[1791:2840347] Resetting plugins due to page load.
,2015-12-02 18:05:16.295 ThaliTest[1791:2840347] Finished load of: file:///var/mobile/Containers/Bundle/Application/A084EF1F-3810-40F2-AF47-7B0D7901EC4D/ThaliTest.app/www/index.html
,2015-12-02 18:05:16.435 ThaliTest[1791:2840347] JXcore Cordova plugin initializing
,2015-12-02 18:05:16.436 ThaliTest[1791:2840549] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
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
,my name is : Apple-IpadAir2-1_PT2754
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
,DBG, CoordinatorConnector connect called
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 65238
,2015-12-02 18:12:38.861 ThaliTest[1791:2840549] jxcore: startBroadcasting
,2015-12-02 18:12:38.867 ThaliTest[1791:2840549] server: starting Apple-IpadAir2-1_PT2754.fr+caQ==
2015-12-02 18:12:38.868 ThaliTest[1791:2840549] multipeer session: start timer: 0x1986d1c0
2015-12-02 18:12:38.868 ThaliTest[1791:2840549] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2754
2015-12-02 18:12:38.868 ThaliTest[1791:2840549] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-02T17:12:38.870Z SendDataTCPServer.js: TCP/IP server is bound to port: 65238
,2015-12-02 18:12:39.177 ThaliTest[1791:2840347] client: found peer: Apple-Iphone6-1_PT5992.nsQaaA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT5992.nsQaaA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02T17:12:39.179Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02T17:12:39.180Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02T17:12:39.180Z SendDataConnector.js: do connect now
,2015-12-02 18:12:39.182 ThaliTest[1791:2840549] jxcore: connect Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02 18:12:39.182 ThaliTest[1791:2840549] client session: connect
2015-12-02 18:12:39.182 ThaliTest[1791:2840549] client session: stateChange:0->1 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:40.025 ThaliTest[1791:2840347] client: found peer: Apple-Iphone5-1_PT9787.rFc5Bg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9787.rFc5Bg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-02 18:12:42.058 ThaliTest[1791:2840347] client: found peer: Apple-Iphone5s-1_PT367.AiGtHw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT367.AiGtHw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-02 18:12:42.184 ThaliTest[1791:2841393] client session: connected
2015-12-02 18:12:42.184 ThaliTest[1791:2841393] client session: stateChange:1->2 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:42.194 ThaliTest[1791:2841397] client session: fireConnectCallback: Apple-Iphone6-1_PT5992.nsQaaA==
2015-12-02 18:12:42.194 ThaliTest[1791:2841397] jxcore: connect: success
,2015-12-02T17:12:42.195Z SendDataConnector.js: CLIENT connected to 65241, error: null
,2015-12-02T17:12:42.195Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:42.196 ThaliTest[1791:2840347] client: relay established
2015-12-02 18:12:42.196 ThaliTest[1791:2840347] client: new accepted socket: 0x19871e00
,2015-12-02T17:12:42.209Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:42.681Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T17:12:42.682Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:42.683Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T17:12:42.683Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:42.684 ThaliTest[1791:2840549] jxcore: disconnect
,2015-12-02 18:12:42.685 ThaliTest[1791:2840549] client session: disconnectFromPeer: Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:42.686 ThaliTest[1791:2840549] client session: disconnect
,2015-12-02 18:12:42.686 ThaliTest[1791:2840549] client session: stateChange:2->0 Apple-Iphone6-1_PT5992.nsQaaA==
,2015-12-02 18:12:42.754 ThaliTest[1791:2840549] jxcore: disconnect: success
,2015-12-02T17:12:42.754Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT5992.nsQaaA==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:42.757Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:42.757Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:42.757Z SendDataConnector.js: do connect now
,2015-12-02 18:12:42.757 ThaliTest[1791:2840549] jxcore: connect Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:42.758 ThaliTest[1791:2840549] client session: connect
,2015-12-02 18:12:42.758 ThaliTest[1791:2840549] client session: stateChange:0->1 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:43.081 ThaliTest[1791:2840347] multipeer session: reset timer
2015-12-02 18:12:43.081 ThaliTest[1791:2840347] multipeer session: stop timer
2015-12-02 18:12:43.081 ThaliTest[1791:2840347] multipeer session: start timer: 0x1986d1c0
2015-12-02 18:12:43.081 ThaliTest[1791:2840347] server session: connect
2015-12-02 18:12:43.082 ThaliTest[1791:2840347] server session: stateChange:0->1 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:43.084 ThaliTest[1791:2840347] server: accepting invitation Apple-Iphone5s-1_PT367
,2015-12-02 18:12:43.690 ThaliTest[1791:2840347] multipeer session: reset timer
2015-12-02 18:12:43.690 ThaliTest[1791:2840347] multipeer session: stop timer
2015-12-02 18:12:43.690 ThaliTest[1791:2840347] multipeer session: start timer: 0x1986d1c0
,2015-12-02 18:12:43.690 ThaliTest[1791:2840347] server session: connect
2015-12-02 18:12:43.690 ThaliTest[1791:2840347] server session: stateChange:0->1 Apple-Iphone5-1_PT9787
2015-12-02 18:12:43.692 ThaliTest[1791:2840347] server: accepting invitation Apple-Iphone5-1_PT9787
,2015-12-02 18:12:44.228 ThaliTest[1791:2840347] multipeer session: reset timer
2015-12-02 18:12:44.228 ThaliTest[1791:2840347] multipeer session: stop timer
2015-12-02 18:12:44.228 ThaliTest[1791:2840347] multipeer session: start timer: 0x1986d1c0
2015-12-02 18:12:44.228 ThaliTest[1791:2840347] server session: connect
2015-12-02 18:12:44.228 ThaliTest[1791:2840347] server session: stateChange:0->1 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:44.232 ThaliTest[1791:2840347] server: accepting invitation Apple-Iphone6-1_PT5992
,2015-12-02 18:12:45.744 ThaliTest[1791:2841391] server session: connected
2015-12-02 18:12:45.744 ThaliTest[1791:2841391] server session: stateChange:1->2 Apple-Iphone5s-1_PT367
,2015-12-02 18:12:45.771 ThaliTest[1791:2840347] server relay: connected (to port: 65238)
,2015-12-02T17:12:45.777Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:46.181Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-02T17:12:46.196Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-02T17:12:46.233Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:46.251 ThaliTest[1791:2841393] server session: connected
2015-12-02 18:12:46.251 ThaliTest[1791:2841393] server session: stateChange:1->2 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:46.263 ThaliTest[1791:2841391] server session: not connected Apple-Iphone5s-1_PT367
,2015-12-02 18:12:46.298 ThaliTest[1791:2840347] server relay: connected (to port: 65238)
,2015-12-02T17:12:46.309Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:46.773Z SendDataTCPServer.js: TCP/IP server has received 14880 bytes of data
,2015-12-02 18:12:46.778 ThaliTest[1791:2841403] server session: connected
2015-12-02 18:12:46.778 ThaliTest[1791:2841403] server session: stateChange:1->2 Apple-Iphone6-1_PT5992
,2015-12-02T17:12:46.787Z SendDataTCPServer.js: TCP/IP server has received 26784 bytes of data
,2015-12-02 18:12:46.830 ThaliTest[1791:2840347] server relay: connected (to port: 65238)
,2015-12-02T17:12:46.838Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T17:12:46.851Z SendDataTCPServer.js: TCP/IP server has received 66464 bytes of data
,2015-12-02T17:12:46.865Z SendDataTCPServer.js: TCP/IP server has received 69440 bytes of data
,2015-12-02T17:12:46.913Z SendDataTCPServer.js: TCP/IP server has received 89280 bytes of data
,2015-12-02T17:12:47.234Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-02T17:12:47.249Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-02T17:12:47.268Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-02T17:12:47.291Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-02T17:12:47.304Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:47.337 ThaliTest[1791:2841397] server session: not connected Apple-Iphone6-1_PT5992
,2015-12-02 18:12:47.375 ThaliTest[1791:2841393] client session: connected
2015-12-02 18:12:47.375 ThaliTest[1791:2841393] client session: stateChange:1->2 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02T17:12:47.377Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 18:12:47.382 ThaliTest[1791:2841403] client session: fireConnectCallback: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:47.383 ThaliTest[1791:2841403] jxcore: connect: success
2015-12-02T17:12:47.383Z SendDataConnector.js: CLIENT connected to 65247, error: null
2015-12-02T17:12:47.383Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:47.385 ThaliTest[1791:2840347] client: relay established
2015-12-02 18:12:47.385 ThaliTest[1791:2840347] client: new accepted socket: 0x1988df30
,2015-12-02T17:12:47.397Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02 18:12:47.403 ThaliTest[1791:2841403] server session: not connected Apple-Iphone5-1_PT9787
,2015-12-02T17:12:47.769Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:47.782Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T17:12:47.792Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T17:12:47.805Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T17:12:47.806Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:47.806Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:47.806Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:47.807 ThaliTest[1791:2840549] jxcore: disconnect
,2015-12-02 18:12:47.807 ThaliTest[1791:2840549] client session: disconnectFromPeer: Apple-Iphone5-1_PT9787.rFc5Bg==
2015-12-02 18:12:47.807 ThaliTest[1791:2840549] client session: disconnect
2015-12-02 18:12:47.807 ThaliTest[1791:2840549] client session: stateChange:2->0 Apple-Iphone5-1_PT9787.rFc5Bg==
,2015-12-02 18:12:47.869 ThaliTest[1791:2840549] jxcore: disconnect: success
2015-12-02T17:12:47.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9787.rFc5Bg==
---- round done--------
,device[3]: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:47.870Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:47.870Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02T17:12:47.870Z SendDataConnector.js: do connect now
,2015-12-02 18:12:47.871 ThaliTest[1791:2840549] jxcore: connect Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:47.871 ThaliTest[1791:2840549] client session: connect
2015-12-02 18:12:47.871 ThaliTest[1791:2840549] client session: stateChange:0->1 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:50.969 ThaliTest[1791:2841397] client session: connected
,2015-12-02 18:12:50.969 ThaliTest[1791:2841397] client session: stateChange:1->2 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:50.977 ThaliTest[1791:2841393] client session: fireConnectCallback: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:50.977 ThaliTest[1791:2841393] jxcore: connect: success
2015-12-02T17:12:50.977Z SendDataConnector.js: CLIENT connected to 65251, error: null
,2015-12-02T17:12:50.977Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 18:12:50.979 ThaliTest[1791:2840347] client: relay established
,2015-12-02 18:12:50.979 ThaliTest[1791:2840347] client: new accepted socket: 0x167f37b0
,2015-12-02T17:12:50.996Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T17:12:51.442Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T17:12:51.478Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T17:12:51.491Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T17:12:51.504Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T17:12:51.504Z SendDataConnector.js: got all data for this round
,2015-12-02T17:12:51.505Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:51.505Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 18:12:51.507 ThaliTest[1791:2840549] jxcore: disconnect
2015-12-02 18:12:51.507 ThaliTest[1791:2840549] client session: disconnectFromPeer: Apple-Iphone5s-1_PT367.AiGtHw==
2015-12-02 18:12:51.507 ThaliTest[1791:2840549] client session: disconnect
2015-12-02 18:12:51.507 ThaliTest[1791:2840549] client session: stateChange:2->0 Apple-Iphone5s-1_PT367.AiGtHw==
,2015-12-02 18:12:51.513 ThaliTest[1791:2840549] jxcore: disconnect: success
2015-12-02T17:12:51.513Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT367.AiGtHw==
---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT2754","time":12660,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT5992.nsQaaA==","time":3503,"result":"OK","connections":1,"doneR,ounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9787.rFc5Bg==","time":5049,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT367.AiGtHw==","time":3634,"result",:"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
sendList : 100% : 5049 ms, 99% : 5049 ms, 95 : 5049 ms, 90% : 5049 ms.
,Result count 3, range 3503 ms to  5049 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-02T17:12:51.523Z SendDataConnector.js: CLIENT Stop now
2015-12-02T17:12:51.523Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-02 18:12:59.281 ThaliTest[1791:2840549] jxcore: stopBroadcasting
2015-12-02 18:12:59.281 ThaliTest[1791:2840549] THEMultipeerSession stopping peer
,2015-12-02 18:12:59.281 ThaliTest[1791:2840549] multipeer session: stop timer
2015-12-02 18:12:59.281 ThaliTest[1791:2840549] server session: disconnect
2015-12-02 18:12:59.281 ThaliTest[1791:2840549] server session: stateChange:2->0 Apple-Iphone5s-1_PT3,67
,2015-12-02 18:12:59.344 ThaliTest[1791:2840549] server session: disconnect
2015-12-02 18:12:59.344 ThaliTest[1791:2840549] server session: stateChange:2->0 Apple-Iphone5-1_PT9787
,2015-12-02 18:12:59.346 ThaliTest[1791:2840549] server session: disconnect
2015-12-02 18:12:59.346 ThaliTest[1791:2840549] server session: stateChange:2->0 Apple-Iphone6-1_PT5992
,2015-12-02 18:12:59.402 ThaliTest[1791:2840549] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-02T17:12:59.417Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:59.417Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:59.418Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T17:12:59.418Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT5992.nsQaaA==\",\"time\":3503,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT367.AiGtHw==\",\"time\":3634,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT9787.rFc5Bg==\",\"time\":5049,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
