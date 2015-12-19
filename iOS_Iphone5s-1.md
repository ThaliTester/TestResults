#### Test 5065027869d93ea_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D60BF423-D77B-4F6C-8A6D-C32FF23B5448/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D60BF423-D77B-4F6C-8A6D-C32FF23B5448/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E8B84E97-FAA0-48D6-BC6F-7D2FD62F4338/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60511"
,(lldb)     command script import "/tmp/D60BF423-D77B-4F6C-8A6D-C32FF23B5448/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-19 01:21:48.544 ThaliTest[514:410536] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA437597-F5AB-4219-BC82-314852E98665/Library/Cookies/Cookies.binarycookies
,2015-12-19 01:21:48.933 ThaliTest[514:410536] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 01:21:48.935 ThaliTest[514:410536] Multi-tasking -> Device: YES, App: YES
,2015-12-19 01:21:48.944 ThaliTest[514:410536] Unlimited access to network resources
,2015-12-19 01:21:48.957 ThaliTest[514:410536] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 01:21:57.965 ThaliTest[514:410536] Resetting plugins due to page load.
,2015-12-19 01:22:01.776 ThaliTest[514:410536] Finished load of: file:///var/mobile/Containers/Bundle/Application/E8B84E97-FAA0-48D6-BC6F-7D2FD62F4338/ThaliTest.app/www/index.html
,2015-12-19 01:22:01.963 ThaliTest[514:410536] JXcore Cordova plugin initializing
2015-12-19 01:22:01.964 ThaliTest[514:410898] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-19 01:22:03.283 ThaliTest[514:410536] THREAD WARNING: ['JXcore'] took '89.947021' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52122
,2015-12-19 01:26:56.312 ThaliTest[514:410898] jxcore: startBroadcasting
,2015-12-19 01:26:56.333 ThaliTest[514:410898] server: starting Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:26:56.335 ThaliTest[514:410898] multipeer session: start timer: 0x18471840
,2015-12-19 01:26:56.336 ThaliTest[514:410898] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7601
,2015-12-19 01:26:56.337 ThaliTest[514:410898] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-19T00:26:56.342Z SendDataTCPServer.js: TCP/IP server is bound to port: 52122
,2015-12-19 01:26:57.389 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:26:57.391 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:26:57.394 ThaliTest[514:410536] client: fou,nd peer: Apple-Iphone6-1_PT3810.9x5b9w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT7806.,b8v14g==
2015-12-19T00:26:57.400Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19T00:26:57.401Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19T00:26:57.402Z SendDataConnector.js: do connect now
,2015-12-19 01:26:57.403 ThaliTest[514:410898] jxcore: connect Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:26:57.404 ThaliTest[514:410898] client session: connect
2015-12-19 01:26:57.405 ThaliTest[514:410898] client session: stateChange:0->1 Apple-Iphone5-1_PT7806.b8v14g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6779.RtEaKg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3810.9x5b9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 01:27:00.523 ThaliTest[514:411430] client session: connected
2015-12-19 01:27:00.523 ThaliTest[514:411430] client session: stateChange:1->2 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:00.533 ThaliTest[514:411431] client session: fireConnectCallback: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:27:00.534 ThaliTest[514:411431] jxcore: connect: success
2015-12-19T00:27:00.536Z SendDataConnector.js: CLIENT connected to 5,2125, error: null
2015-12-19T00:27:00.536Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:00.543 ThaliTest[514:410536] client: relay established
2015-12-19 01:27:00.543 ThaliTest[514:410536] client: new accepted socket: 0x18478840
,2015-12-19T00:27:00.560Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:01.001Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T00:27:01.014Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:01.027Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:01.028Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T00:27:01.030Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:01.030Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:01.032 ThaliTest[514:410898] jxcore: disconnect
,2015-12-19 01:27:01.032 ThaliTest[514:410898] client session: disconnectFromPeer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:01.033 ThaliTest[514:410898] client session: disconnect
,2015-12-19 01:27:01.033 ThaliTest[514:410898] client session: stateChange:2->0 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:01.050 ThaliTest[514:410536] multipeer session: reset timer
2015-12-19 01:27:01.050 ThaliTest[514:410536] multipeer session: stop timer
2015-12-19 01:27:01.050 ThaliTest[514:410536] multipeer session: start timer: 0x18471840
2015-12-19 ,01:27:01.050 ThaliTest[514:410536] server session: connect
2015-12-19 01:27:01.050 ThaliTest[514:410536] server session: stateChange:0->1 Apple-Iphone6-1_PT3810
2015-12-19 01:27:01.054 ThaliTest[514:410536] server: accepting invitation Apple-Iphone6-1_PT3810
,2015-12-19 01:27:01.104 ThaliTest[514:410898] jxcore: disconnect: success
,2015-12-19T00:27:01.106Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7806.b8v14g==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:27:01.108Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:27:01.108Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:27:01.109Z SendDataConnector.js: do connect now
,2015-12-19 01:27:01.110 ThaliTest[514:410898] jxcore: connect Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:01.111 ThaliTest[514:410898] client session: connect
,2015-12-19 01:27:01.112 ThaliTest[514:410898] client session: stateChange:0->1 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:01.375 ThaliTest[514:410536] multipeer session: reset timer
2015-12-19 01:27:01.375 ThaliTest[514:410536] multipeer session: stop timer
2015-12-19 01:27:01.375 ThaliTest[514:410536] multipeer session: start timer: 0x18471840
,2015-12-19 01:27:01.375 ThaliTest[514:410536] server session: connect
2015-12-19 01:27:01.375 ThaliTest[514:410536] server session: stateChange:0->1 Apple-Iphone5-1_PT7806
,2015-12-19 01:27:01.382 ThaliTest[514:410536] server: accepting invitation Apple-Iphone5-1_PT7806
,2015-12-19 01:27:03.630 ThaliTest[514:411451] server session: connected
2015-12-19 01:27:03.630 ThaliTest[514:411451] server session: stateChange:1->2 Apple-Iphone6-1_PT3810
,2015-12-19 01:27:03.663 ThaliTest[514:410536] server relay: connected (to port: 52122)
2015-12-19T00:27:03.668Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:03.942Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-19T00:27:03.958Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-19T00:27:03.976Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-19 01:27:03.989 ThaliTest[514:411432] client session: connected
2015-12-19 01:27:03.990 ThaliTest[514:411432] client session: stateChange:1->2 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:27:03.993Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-19T00:27:04.009Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-19T00:27:04.028Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-19 01:27:04.041 ThaliTest[514:411450] server session: connected
,2015-12-19 01:27:04.042 ThaliTest[514:411450] server session: stateChange:1->2 Apple-Iphone5-1_PT7806
,2015-12-19T00:27:04.043Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:04.051 ThaliTest[514:411432] client session: fireConnectCallback: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:04.051 ThaliTest[514:411432] jxcore: connect: success
,2015-12-19 01:27:04.055 ThaliTest[514:410536] server relay: connected (to port: 52122)
,2015-12-19T00:27:04.057Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:04.060Z SendDataConnector.js: CLIENT connected to 52129, error: null
,2015-12-19T00:27:04.061Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:04.064 ThaliTest[514:410536] client: relay established
,2015-12-19 01:27:04.064 ThaliTest[514:410536] client: new accepted socket: 0x18485b10
,2015-12-19T00:27:04.077Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 01:27:04.131 ThaliTest[514:411431] server session: not connected Apple-Iphone6-1_PT3810
,2015-12-19T00:27:04.449Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T00:27:04.498Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-19T00:27:04.548Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:04.549Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:04.549Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:04.549Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:04.550 ThaliTest[514:410898] jxcore: disconnect
,2015-12-19 01:27:04.550 ThaliTest[514:410898] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:04.551 ThaliTest[514:410898] client session: disconnect
,2015-12-19 01:27:04.551 ThaliTest[514:410898] client session: stateChange:2->0 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:04.618 ThaliTest[514:410898] jxcore: disconnect: success
,2015-12-19T00:27:04.619Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6779.RtEaKg==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.620Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.620Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.620Z SendDataConnector.js: do connect now
,2015-12-19 01:27:04.621 ThaliTest[514:410898] jxcore: connect Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:04.622 ThaliTest[514:410898] client session: connect
,2015-12-19 01:27:04.622 ThaliTest[514:410898] client session: stateChange:0->1 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:04.646 ThaliTest[514:410536] multipeer session: reset timer
2015-12-19 01:27:04.646 ThaliTest[514:410536] multipeer session: stop timer
2015-12-19 01:27:04.646 ThaliTest[514:410536] multipeer session: start timer: 0x18471840
,2015-12-19 01:27:04.646 ThaliTest[514:410536] server session: connect
,2015-12-19 01:27:04.647 ThaliTest[514:410536] server session: stateChange:0->1 Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:04.653 ThaliTest[514:410536] server: accepting invitation Apple-IpadAir2-1_PT6779
,2015-12-19T00:27:04.727Z SendDataTCPServer.js: TCP/IP server has received 54324 bytes of data
,2015-12-19T00:27:04.748Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-19T00:27:04.787Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-19T00:27:04.972Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:04.984 ThaliTest[514:411432] server session: not connected Apple-Iphone5-1_PT7806
,2015-12-19 01:27:07.322 ThaliTest[514:411450] server session: connected
2015-12-19 01:27:07.322 ThaliTest[514:411450] server session: stateChange:1->2 Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:07.361 ThaliTest[514:410536] server relay: connected (to port: 52122)
,2015-12-19T00:27:07.370Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 01:27:07.530 ThaliTest[514:411450] client session: connected
2015-12-19 01:27:07.531 ThaliTest[514:411450] client session: stateChange:1->2 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:07.536 ThaliTest[514:411450] client session: fireConnectCallback: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:07.536 ThaliTest[514:411450] jxcore: connect: success
2015-12-19T00:27:07.538Z SendDataConnector.js: CLIENT connected to 52134, error: null
2015-12-19T00:27:07.539Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:07.543 ThaliTest[514:410536] client: relay established
2015-12-19 01:27:07.544 ThaliTest[514:410536] client: new accepted socket: 0x182df070
,2015-12-19T00:27:07.555Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:07.897Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19T00:27:08.007Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-19T00:27:08.020Z SendDataConnector.js: CLIENT is data received : 30000
2015-12-19 01:27:08.021 ThaliTest[514:411432] server session: not connected Apple-IpadAir2-1_PT6779
,2015-12-19T00:27:08.046Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-19T00:27:08.059Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-19T00:27:08.071Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:08.071Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:08.071Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:08.071Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:08.072 ThaliTest[514:410898] jxcore: disconnect
2015-12-19 01:27:08.072 ThaliTest[514:410898] client session: disconnectFromPeer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:27:08.072 ThaliTest[514:410898] client session: disconnect
2015-12-19 01:27:08.073 ThaliTest[514:410898] client session: stateChange:2->0 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:08.077 ThaliTest[514:410898] jxcore: disconnect: success
2015-12-19T00:27:08.079Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3810.9x5b9w==
---- round done--------
startWithNextDevice
,2015-12-19 01:27:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:27:34.719 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:27:34.720 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:34.734 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:28:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:28:04.709 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:28:04.713 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:28:04.714 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:28:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:28:34.706 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:28:34.706 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:28:34.708 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:29:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:29:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:29:34.701 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:29:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:29:34.704 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:30:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:30:04.705 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:30:04.705 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:30:04.706 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:30:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:30:34.703 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:30:34.704 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:30:34.716 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:31:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:31:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:31:34.686 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:31:34.690 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:31:34.691 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:32:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:32:05.491 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:32:06.265 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:32:06.266 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:32:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:32:34.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:32:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:32:34.702 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:33:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:33:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:33:34.699 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:33:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:33:34.705 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:34:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:34:04.707 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:34:04.707 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:34:04.715 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:34:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:35:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:35:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:35:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:35:04.703 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:35:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:36:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:36:04.693 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:36:04.697 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:36:04.704 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:36:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:36:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:36:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:36:34.714 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:37:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:37:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:37:04.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:37:04.704 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:37:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:37:34.702 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:37:34.709 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:37:34.712 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:38:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:38:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:38:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:38:04.704 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:38:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:38:34.704 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:38:34.704 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:38:34.705 ThaliTest[514:410536] client: fou,nd peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:39:04.648 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:39:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:39:04.701 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:39:04.702 ThaliTest[514:410536] client: fou,nd peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:39:34.648 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:40:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:40:04.698 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:04.698 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:40:04.709 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:40:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:40:34.704 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:34.706 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:40:34.707 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:41:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:41:04.707 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:41:04.708 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:41:04.711 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:41:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:41:34.698 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:41:34.707 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:41:34.708 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:42:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:42:04.699 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:42:04.700 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:42:04.702 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:42:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:42:34.707 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:42:34.708 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:42:34.710 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:43:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:43:04.702 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:43:04.707 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:43:04.711 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:43:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:43:34.705 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:43:34.706 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:43:34.707 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T00:43:36.355Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 01:44:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:44:04.705 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:44:04.706 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:44:04.708 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:44:34.648 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:45:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:45:04.704 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:45:04.705 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:45:04.706 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:45:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:46:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:46:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:46:04.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:04.702 ThaliTest[514:410536] client: foun,d peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:46:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:47:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:47:04.697 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:47:04.698 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:47:04.701 ThaliTest[514:410536] client: fou,nd peer: Apple-Iphone5-1_PT7806.jHAIjw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6779.Eyppcg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
peerAvailabilityChanged [{"peerId,entifier":"Apple-Iphone5-1_PT7806.jHAIjw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 01:47:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:48:04.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:48:04.701 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:48:04.701 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:48:04.702 ThaliTest[514:410536] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:48:34.647 ThaliTest[514:410536] multipeer session: restart
,2015-12-19 01:48:34.705 ThaliTest[514:410536] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:48:34.705 ThaliTest[514:410536] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:48:34.706 ThaliTest[514:410536] client: fou,nd peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:49:04.647 ThaliTest[514:410536] multipeer session: restart

```
