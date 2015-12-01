#### Test 519863408c638e9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/981EF7C7-EE4F-492E-AB94-4EDFDFDBD8AD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/981EF7C7-EE4F-492E-AB94-4EDFDFDBD8AD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/519863408c638e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/52F74FB7-9E26-4A02-A5C3-093C94C14F62/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58425"
,(lldb)     command script import "/tmp/981EF7C7-EE4F-492E-AB94-4EDFDFDBD8AD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 11:47:33.962 ThaliTest[2169:2047002] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/352C2C78-20C2-4B19-938B-DBB0776787A2/Library/Cookies/Cookies.binarycookies
,2015-12-01 11:47:34.382 ThaliTest[2169:2047002] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 11:47:34.384 ThaliTest[2169:2047002] Multi-tasking -> Device: YES, App: YES
,2015-12-01 11:47:34.393 ThaliTest[2169:2047002] Unlimited access to network resources
,2015-12-01 11:47:34.400 ThaliTest[2169:2047002] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 11:47:37.978 ThaliTest[2169:2047002] Resetting plugins due to page load.
,2015-12-01 11:47:38.303 ThaliTest[2169:2047002] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/52F74FB7-9E26-4A02-A5C3-093C94C14F62/ThaliTest.app/www/index.html
,2015-12-01 11:47:38.463 ThaliTest[2169:2047002] JXcore Cordova plugin initializing
2015-12-01 11:47:38.464 ThaliTest[2169:2047127] JXcore instance initializing
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
,my name is : Apple-Iphone5s-1_PT9146
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 64256
,2015-12-01 11:54:31.951 ThaliTest[2169:2047127] jxcore: startBroadcasting
,2015-12-01 11:54:31.966 ThaliTest[2169:2047127] server: starting Apple-Iphone5s-1_PT9146.afM/PQ==
,2015-12-01 11:54:31.969 ThaliTest[2169:2047127] multipeer session: start timer: 0x1a5e2220
,2015-12-01 11:54:31.985 ThaliTest[2169:2047127] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9146
,2015-12-01 11:54:31.987 ThaliTest[2169:2047127] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-01T10:54:31.991Z SendDataTCPServer.js: TCP/IP server is bound to port: 64256
,2015-12-01 11:54:32.554 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:54:32.555 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:54:32.555 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:54:32.556 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:54:32.557 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-Iphone5-1_PT9531
,2015-12-01 11:54:32.571 ThaliTest[2169:2047002] server: accepting invitation Apple-Iphone5-1_PT9531
,2015-12-01 11:54:33.016 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:54:33.017 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:54:33.017 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:54:33.018 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:54:33.019 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01 11:54:33.032 ThaliTest[2169:2047002] server: accepting invitation Apple-IpadAir2-1_PT7493
,2015-12-01 11:54:33.158 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:54:33.160 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one5-1_PT9531.MSI13Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:54:33.170Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:54:33.172Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01T10:54:33.172Z SendDataConnector.js: do connect now
,2015-12-01 11:54:33.174 ThaliTest[2169:2047127] jxcore: connect Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:54:33.174 ThaliTest[2169:2047127] client session: connect
2015-12-01 11:54:33.175 ThaliTest[2169:2047127] client session: stateChange:0->1 Apple-Iphone5-1_PT9531.MSI13Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7493.hpeH+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:34.191 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 11:54:34.450 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:54:34.451 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:54:34.451 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:54:34.452 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:54:34.453 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-Iphone6-1_PT127
,2015-12-01 11:54:34.461 ThaliTest[2169:2047002] server: accepting invitation Apple-Iphone6-1_PT127
,2015-12-01 11:54:35.105 ThaliTest[2169:2047754] server session: connected
2015-12-01 11:54:35.106 ThaliTest[2169:2047754] server session: stateChange:1->2 Apple-Iphone5-1_PT9531
,2015-12-01 11:54:35.115 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
,2015-12-01T10:54:35.124Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 11:54:35.614 ThaliTest[2169:2047782] server session: connected
2015-12-01 11:54:35.616 ThaliTest[2169:2047782] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
,2015-12-01 11:54:35.630 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
2015-12-01T10:54:35.639Z SendDataTCPServer.js: TCP/IP server connected
2015-12-01T10:54:35.642Z SendDataTCPServer.js: TCP/IP server has received 6944 bytes of data
,2015-12-01T10:54:35.659Z SendDataTCPServer.js: TCP/IP server has received 11968 bytes of data
,2015-12-01T10:54:35.679Z SendDataTCPServer.js: TCP/IP server has received 23808 bytes of data
,2015-12-01T10:54:35.695Z SendDataTCPServer.js: TCP/IP server has received 37696 bytes of data
,2015-12-01T10:54:35.717Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
,2015-12-01T10:54:35.732Z SendDataTCPServer.js: TCP/IP server has received 57536 bytes of data
,2015-12-01 11:54:35.737 ThaliTest[2169:2047754] client session: connected
,2015-12-01 11:54:35.737 ThaliTest[2169:2047754] client session: stateChange:1->2 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:35.742 ThaliTest[2169:2047754] client session: fireConnectCallback: Apple-Iphone5-1_PT9531.MSI13Q==
2015-12-01 11:54:35.743 ThaliTest[2169:2047754] jxcore: connect: success
,2015-12-01T10:54:35.746Z SendDataTCPServer.js: TCP/IP server has received 63488 bytes of data
,2015-12-01T10:54:35.747Z SendDataConnector.js: CLIENT connected to 64261, error: null
,2015-12-01T10:54:35.748Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:35.750 ThaliTest[2169:2047002] client: relay established
2015-12-01 11:54:35.750 ThaliTest[2169:2047002] client: new accepted socket: 0x1a5f81e0
,2015-12-01T10:54:35.766Z SendDataTCPServer.js: TCP/IP server has received 78368 bytes of data
,2015-12-01T10:54:35.771Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:36.097Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T10:54:36.099Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-01T10:54:36.152Z SendDataTCPServer.js: TCP/IP server has received 98408 bytes of data
,2015-12-01T10:54:36.164Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T10:54:36.189Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T10:54:36.200Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T10:54:36.212Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T10:54:36.226Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01 11:54:36.227 ThaliTest[2169:2047756] server session: not connected Apple-Iphone5-1_PT9531
,2015-12-01T10:54:36.227Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:36.229Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T10:54:36.229Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:54:36.230 ThaliTest[2169:2047127] jxcore: disconnect
,2015-12-01 11:54:36.231 ThaliTest[2169:2047127] client session: disconnectFromPeer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:36.232 ThaliTest[2169:2047127] client session: disconnect
,2015-12-01 11:54:36.233 ThaliTest[2169:2047127] client session: stateChange:2->0 Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:54:36.292 ThaliTest[2169:2047127] jxcore: disconnect: success
2015-12-01T10:54:36.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9531.MSI13Q==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:36.294Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:36.294Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01T10:54:36.294Z SendDataConnector.js: do connect now
,2015-12-01 11:54:36.294 ThaliTest[2169:2047127] jxcore: connect Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:36.295 ThaliTest[2169:2047127] client session: connect
2015-12-01 11:54:36.295 ThaliTest[2169:2047127] client session: stateChange:0->1 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:36.663 ThaliTest[2169:2047782] server session: connected
2015-12-01 11:54:36.663 ThaliTest[2169:2047782] server session: stateChange:1->2 Apple-Iphone6-1_PT127
,2015-12-01 11:54:36.675 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
,2015-12-01T10:54:36.685Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:54:37.222Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-01T10:54:37.239Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-01T10:54:37.253Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-01T10:54:37.268Z SendDataTCPServer.js: TCP/IP server has received 75798 bytes of data
,2015-12-01T10:54:37.284Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 11:54:37.313 ThaliTest[2169:2047756] server session: not connected Apple-Iphone6-1_PT127
,2015-12-01 11:54:40.024 ThaliTest[2169:2047754] client session: connected
2015-12-01 11:54:40.025 ThaliTest[2169:2047754] client session: stateChange:1->2 Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:54:40.030 ThaliTest[2169:2047744] client session: fireConnectCallback: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:40.032 ThaliTest[2169:2047744] jxcore: connect: success
2015-12-01T10:54:40.034Z SendDataConnector.js: CLIENT connected, to 64265, error: null
,2015-12-01T10:54:40.035Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:40.039 ThaliTest[2169:2047002] client: relay established
2015-12-01 11:54:40.040 ThaliTest[2169:2047002] client: new accepted socket: 0x1a560390
,2015-12-01T10:54:40.052Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:40.384Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-01T10:54:40.397Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-01T10:54:40.422Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-01T10:54:40.434Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T10:54:40.435Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:40.435Z SendDataConnector.js: CLIENT Stop now
2015-12-01T10:54:40.435Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 11:54:40.436 ThaliTest[2169:2047127] jxcore: disconnect
,2015-12-01 11:54:40.436 ThaliTest[2169:2047127] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:40.436 ThaliTest[2169:2047127] client session: disconnect
,2015-12-01 11:54:40.436 ThaliTest[2169:2047127] client session: stateChange:2->0 Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:54:40.438 ThaliTest[2169:2047127] jxcore: disconnect: success
2015-12-01T10:54:40.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7493.hpeH+A==
---- round done--------
,device[3]: Apple-Iphone6-1_PT127.797wqw==
2015-12-01T10:54:40.439Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT127.797wqw==
2015-12-01T10:54:40.439Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT127.797wqw==
2015-12-01T10:54:40.439Z SendDataConnector.js: do connect now
2015-12-01 11:54:40.439 ThaliTest[2169:2047127] jxcore: connect Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:40.440 ThaliTest[2169:2047127] client session: connect
2015-12-01 11:54:40.440 ThaliTest[2169:2047127] client session: stateChange:0->1 Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:43.092 ThaliTest[2169:2047756] client session: connected
2015-12-01 11:54:43.092 ThaliTest[2169:2047756] client session: stateChange:1->2 Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:43.114 ThaliTest[2169:2047782] client session: fireConnectCallback: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:54:43.114 ThaliTest[2169:2047782] jxcore: connect: success
2015-12-01T10:54:43.115Z SendDataConnector.js: CLIENT connected to 64269, error: null
2015-12-01T10:54:43.116Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 11:54:43.121 ThaliTest[2169:2047002] client: relay established
2015-12-01 11:54:43.121 ThaliTest[2169:2047002] client: new accepted socket: 0x1a025fd0
,2015-12-01T10:54:43.131Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T10:54:43.451Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T10:54:43.476Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T10:54:43.502Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T10:54:43.502Z SendDataConnector.js: got all data for this round
,2015-12-01T10:54:43.503Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T10:54:43.503Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:54:43.504 ThaliTest[2169:2047127] jxcore: disconnect
,2015-12-01 11:54:43.505 ThaliTest[2169:2047127] client session: disconnectFromPeer: Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:43.506 ThaliTest[2169:2047127] client session: disconnect
,2015-12-01 11:54:43.507 ThaliTest[2169:2047127] client session: stateChange:2->0 Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:54:43.564 ThaliTest[2169:2047127] jxcore: disconnect: success
,2015-12-01T10:54:43.565Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT127.797wqw==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT9146","time":11631,"result":"OK","sendList":[{"name":"Apple-Iphone5-1_PT9531.MSI13Q==","time":3057,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7493.hpeH+A==","time":4141,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT127.797wqw==","time":3063,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4141 ms, 99% : 4141 ms, 95 : 4141 ms, 90% : 4141 ms.
,Result count 3, range 3057 ms to  4141 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-01T10:54:43.574Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T10:54:43.574Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 11:55:04.452 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:55:04.568 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:04.569 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:55:04.570 ThaliTest[2169:2047002] client,: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:55:15.922 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
,2015-12-01 11:55:20.031 ThaliTest[2169:2047002] client: lost peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:20.032 ThaliTest[2169:2047002] client session: onPeerLost: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:55:20.116 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 11:55:26.404 ThaliTest[2169:2047814] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 11:55:34.452 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:55:34.476 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:34.477 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:55:34.478 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:55:41.620 ThaliTest[2169:2047002] client: lost peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:41.621 ThaliTest[2169:2047002] client session: onPeerLost: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:55:41.701 ThaliTest[2169:2047002] client: found peer: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 11:55:44.225 ThaliTest[2169:2047002] client: lost peer: Apple-Iphone6-1_PT127.797wqw==
2015-12-01 11:55:44.226 ThaliTest[2169:2047002] client session: onPeerLost: Apple-Iphone6-1_PT127.797wqw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone6-1_PT127.797wqw==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 11:55:46.991 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:55:46.992 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:55:46.992 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:55:46.993 ThaliTest[2169:2047002] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7493)
2015-12-01 11:55:46.993 ThaliTest[2169:2047002] server session: disconnect
2015-12-01 11:55:46.994 ThaliTest[2169:2047002] server session: stateChange:2->0 Apple-IpadAir2-1_PT7493
,2015-12-01 11:55:46.999 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:55:47.000 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01 11:55:47.009 ThaliTest[2169:2047002] server: accepting invitation Apple-IpadAir2-1_PT7493
2015-12-01T10:55:47.009Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 11:55:49.674 ThaliTest[2169:2047905] server session: connected
,2015-12-01 11:55:49.676 ThaliTest[2169:2047905] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
,2015-12-01 11:55:49.680 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
,2015-12-01T10:55:49.685Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:55:49.738Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 11:56:16.994 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:56:17.020 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:56:17.022 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:56:39.800 ThaliTest[2169:2047949] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 11:56:46.994 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:56:47.015 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:56:47.018 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:56:51.591 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:56:51.591 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:56:51.592 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:56:51.593 ThaliTest[2169:2047002] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7493)
2015-12-01 11:56:51.593 ThaliTest[2169:2047002] server session: disconnect
2015-12-01 11:56:51.594 ThaliTest[2169:2047002] server session: state,Change:2->0 Apple-IpadAir2-1_PT7493
,2015-12-01 11:56:51.598 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:56:51.598 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01T10:56:51.603Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 11:56:51.609 ThaliTest[2169:2047002] server: accepting invitation Apple-IpadAir2-1_PT7493
,2015-12-01 11:56:54.004 ThaliTest[2169:2047999] server session: connected
,2015-12-01 11:56:54.006 ThaliTest[2169:2047999] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
,2015-12-01 11:56:54.010 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
,2015-12-01T10:56:54.019Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T10:56:54.220Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 11:56:56.103 ThaliTest[2169:2047998] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 11:57:21.594 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:57:21.618 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:57:21.619 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:57:51.592 ThaliTest[2169:2047002] multipeer session: restart
2015-12-01 11:57:51.613 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:57:51.615 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:57:58.442 ThaliTest[2169:2047002] multipeer session: reset timer
2015-12-01 11:57:58.443 ThaliTest[2169:2047002] multipeer session: stop timer
2015-12-01 11:57:58.444 ThaliTest[2169:2047002] multipeer session: start timer: 0x1a5e2220
2015-,12-01 11:57:58.445 ThaliTest[2169:2047002] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7493)
2015-12-01 11:57:58.446 ThaliTest[2169:2047002] server session: disconnect
2015-12-01 11:57:58.446 ThaliTest[2169:2047002] server session: state,Change:2->0 Apple-IpadAir2-1_PT7493
2015-12-01 11:57:58.451 ThaliTest[2169:2047002] server session: connect
2015-12-01 11:57:58.452 ThaliTest[2169:2047002] server session: stateChange:0->1 Apple-IpadAir2-1_PT7493
,2015-12-01T10:57:58.467Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01 11:57:58.474 ThaliTest[2169:2047002] server: accepting invitation Apple-IpadAir2-1_PT7493
,2015-12-01 11:58:01.160 ThaliTest[2169:2048125] server session: connected
2015-12-01 11:58:01.161 ThaliTest[2169:2048125] server session: stateChange:1->2 Apple-IpadAir2-1_PT7493
2015-12-01T10:58:01.165Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 11:58:01.169 ThaliTest[2169:2047002] server relay: connected (to port: 64256)
,2015-12-01T10:58:01.227Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 11:58:28.446 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:58:28.470 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:58:28.471 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:58:31.421 ThaliTest[2169:2048128] server session: not connected Apple-IpadAir2-1_PT7493
,2015-12-01 11:58:58.446 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:58:58.467 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 11:58:58.469 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:28.446 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:59:28.465 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:59:28.468 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 11:59:58.445 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 11:59:58.465 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 11:59:58.466 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:28.446 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:00:28.464 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:00:28.466 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:58.444 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:00:58.471 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:00:58.862 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:01:28.444 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:01:28.467 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:01:28.753 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:01:58.444 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:01:58.581 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:01:58.582 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:02:28.444 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:02:28.467 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:02:28.824 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-01 12:02:58.444 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:02:58.464 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:02:59.220 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 12:03:28.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:03:28.467 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:03:28.468 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:03:58.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:03:58.466 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:03:58.467 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:04:28.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:04:28.461 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:04:28.464 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:04:58.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:04:58.463 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:04:58.784 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:05:28.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:05:28.465 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:05:28.467 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:05:58.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:05:59.151 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:05:59.531 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:06:28.443 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:06:28.466 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:06:28.890 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
,2015-12-01 12:06:58.442 ThaliTest[2169:2047002] multipeer session: restart
,2015-12-01 12:06:58.468 ThaliTest[2169:2047002] client: found peer: Apple-IpadAir2-1_PT7493.hpeH+A==
2015-12-01 12:06:58.469 ThaliTest[2169:2047002] client: found peer: Apple-Iphone5-1_PT9531.MSI13Q==
,2015-12-01 12:07:28.443 ThaliTest[2169:2047002] multipeer session: restart
2015-12-01 12:07:28.450 ThaliTest[2169:2047002] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0xdd5e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,* thread #1: tid = 0x1f3c1a, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000dd5e2 ThaliTest`main + 50

```
