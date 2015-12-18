#### Test 50650278d76d9c3_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9F8499F6-5BA8-472D-ABD8-083F5354865E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9F8499F6-5BA8-472D-ABD8-083F5354865E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A692D404-A7BC-48DD-8AD6-49ED081B2BEE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60362"
,(lldb)     command script import "/tmp/9F8499F6-5BA8-472D-ABD8-083F5354865E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 19:32:48.438 ThaliTest[466:381189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C2213C26-AD9D-44B9-B83A-E615DA20795A/Library/Cookies/Cookies.binarycookies
,2015-12-18 19:32:48.773 ThaliTest[466:381189] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 19:32:48.774 ThaliTest[466:381189] Multi-tasking -> Device: YES, App: YES
,2015-12-18 19:32:48.783 ThaliTest[466:381189] Unlimited access to network resources
,2015-12-18 19:32:48.792 ThaliTest[466:381189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 19:32:57.712 ThaliTest[466:381189] Resetting plugins due to page load.
,2015-12-18 19:33:00.646 ThaliTest[466:381189] Finished load of: file:///var/mobile/Containers/Bundle/Application/A692D404-A7BC-48DD-8AD6-49ED081B2BEE/ThaliTest.app/www/index.html
,2015-12-18 19:33:00.812 ThaliTest[466:381189] JXcore Cordova plugin initializing
,2015-12-18 19:33:00.813 ThaliTest[466:381504] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-18 19:33:01.889 ThaliTest[466:381189] THREAD WARNING: ['JXcore'] took '77.848389' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 53052
,2015-12-18 19:38:08.889 ThaliTest[466:381504] jxcore: startBroadcasting
,2015-12-18 19:38:08.907 ThaliTest[466:381504] server: starting Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:08.908 ThaliTest[466:381504] multipeer session: start timer: 0x183dd190
2015-12-18 19:38:08.909 ThaliTest[466:381504] THEMultipeerSession initialized peer Apple-Iphone6-1_PT6353
2015-12-18 19:38:08.910 ThaliTest[466:381504] jxcore: start,Broadcasting: success
,StartBroadcasting started ok
,null
,2015-12-18T18:38:08.922Z SendDataTCPServer.js: TCP/IP server is bound to port: 53052
,2015-12-18 19:38:09.967 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:09.973Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:09.974Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-,1_PT3434.MiytEA==
2015-12-18T18:38:09.975Z SendDataConnector.js: do connect now
2015-12-18 19:38:09.975 ThaliTest[466:381504] jxcore: connect Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:09.976 ThaliTest[466:381504] client session: connect
2015-12-,18 19:38:09.976 ThaliTest[466:381504] client session: stateChange:0->1 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:10.100 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 19:38:10.188 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 19:38:10.241 ThaliTest[466:381189] multipeer session: reset timer
2015-12-18 19:38:10.241 ThaliTest[466:381189] multipeer session: stop timer
2015-12-18 19:38:10.241 ThaliTest[466:381189] multipeer session: start timer: 0x183dd190
2015-12-18 ,19:38:10.242 ThaliTest[466:381189] server session: connect
2015-12-18 19:38:10.242 ThaliTest[466:381189] server session: stateChange:0->1 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:10.252 ThaliTest[466:381189] server: accepting invitation Apple-Iphone5-1_PT3434
,2015-12-18 19:38:12.991 ThaliTest[466:381988] server session: connected
2015-12-18 19:38:12.992 ThaliTest[466:381988] server session: stateChange:1->2 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:13.012 ThaliTest[466:381189] server relay: connected (to port: 53052)
,2015-12-18T18:38:13.022Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 19:38:13.060 ThaliTest[466:381988] client session: connected
,2015-12-18 19:38:13.061 ThaliTest[466:381988] client session: stateChange:1->2 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:13.067 ThaliTest[466:381988] client session: fireConnectCallback: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:13.068 ThaliTest[466:381988] jxcore: connect: success
,2015-12-18T18:38:13.071Z SendDataConnector.js: CLIENT connected to 53056, error: null
2015-12-18T18:38:13.071Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:13.075 ThaliTest[466:381189] client: relay established
2015-12-18 19:38:13.075 ThaliTest[466:381189] client: new accepted socket: 0x183e3cc0
,2015-12-18T18:38:13.091Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:13.590Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T18:38:13.709Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:13.710Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:13.713Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:13.713Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:13.714 ThaliTest[466:381504] jxcore: disconnect
2015-12-18 19:38:13.715 ThaliTest[466:381504] client session: disconnectFromPeer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:13.715 ThaliTest[466:381504] client session: disconnect
,2015-12-18 19:38:13.716 ThaliTest[466:381504] client session: stateChange:2->0 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:13.784 ThaliTest[466:381504] jxcore: disconnect: success
,2015-12-18T18:38:13.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3434.MiytEA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18T18:38:13.786Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18T18:38:13.787Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18T18:38:13.787Z SendDataConnector.js: do connect now
,2015-12-18 19:38:13.788 ThaliTest[466:381504] jxcore: connect Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:13.788 ThaliTest[466:381504] client session: connect
,2015-12-18 19:38:13.789 ThaliTest[466:381504] client session: stateChange:0->1 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18T18:38:13.798Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T18:38:13.836Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:13.885 ThaliTest[466:381988] server session: not connected Apple-Iphone5-1_PT3434
,2015-12-18 19:38:15.144 ThaliTest[466:381189] multipeer session: reset timer
2015-12-18 19:38:15.144 ThaliTest[466:381189] multipeer session: stop timer
2015-12-18 19:38:15.144 ThaliTest[466:381189] multipeer session: start timer: 0x183dd190
2015-12-18 ,19:38:15.145 ThaliTest[466:381189] server session: connect
2015-12-18 19:38:15.145 ThaliTest[466:381189] server session: stateChange:0->1 Apple-IpadAir2-1_PT9191
2015-12-18 19:38:15.153 ThaliTest[466:381189] server: accepting invitation Apple-IpadAir2-1_,PT9191
,2015-12-18 19:38:15.806 ThaliTest[466:381189] multipeer session: reset timer
2015-12-18 19:38:15.806 ThaliTest[466:381189] multipeer session: stop timer
2015-12-18 19:38:15.807 ThaliTest[466:381189] multipeer session: start timer: 0x183dd190
,2015-12-18 19:38:15.807 ThaliTest[466:381189] server session: connect
2015-12-18 19:38:15.809 ThaliTest[466:381189] server session: stateChange:0->1 Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:15.818 ThaliTest[466:381189] server: accepting invitation Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:16.460 ThaliTest[466:382037] client session: connected
2015-12-18 19:38:16.461 ThaliTest[466:382037] client session: stateChange:1->2 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:16.488 ThaliTest[466:381988] client session: fireConnectCallback: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:16.488 ThaliTest[466:381988] jxcore: connect: success
2015-12-18T18:38:16.490Z SendDataConnector.js: CLIENT connected to ,53059, error: null
2015-12-18T18:38:16.490Z SendDataConnector.js: CLIENT starting client 
2015-12-18 19:38:16.494 ThaliTest[466:381189] client: relay established
2015-12-18 19:38:16.494 ThaliTest[466:381189] client: new accepted socket: 0x1845c650
,2015-12-18T18:38:16.506Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:16.826Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T18:38:16.850Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T18:38:16.850Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T18:38:16.850Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:16.851Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:16.851 ThaliTest[466:381504] jxcore: disconnect
2015-12-18 19:38:16.851 ThaliTest[466:381504] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:16.851 ThaliTest[466:381504] client session: disconnect
2015-12-18 19:38:16.851 ThaliTest[466:381504] client session: stateChange:2->0 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:16.915 ThaliTest[466:381504] jxcore: disconnect: success
2015-12-18T18:38:16.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18T18:38:16.916Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:16.916Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:16.917Z SendDataConnector.js: do connect now
,2015-12-18 19:38:16.917 ThaliTest[466:381504] jxcore: connect Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:16.917 ThaliTest[466:381504] client session: connect
2015-12-18 19:38:16.917 ThaliTest[466:381504] client session: stateChange:0->1 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:17.868 ThaliTest[466:381989] server session: connected
,2015-12-18 19:38:17.869 ThaliTest[466:381989] server session: stateChange:1->2 Apple-IpadAir2-1_PT9191
,2015-12-18T18:38:17.906Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 19:38:17.907 ThaliTest[466:381189] server relay: connected (to port: 53052)
,2015-12-18T18:38:18.303Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-18T18:38:18.321Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-18T18:38:18.338Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
2015-12-18T18:38:18.353Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T18:38:18.369Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:18.415 ThaliTest[466:381989] server session: not connected Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:18.915 ThaliTest[466:381989] server session: connected
2015-12-18 19:38:18.915 ThaliTest[466:381989] server session: stateChange:1->2 Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:18.921 ThaliTest[466:381189] server relay: connected (to port: 53052)
,2015-12-18T18:38:18.930Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:19.350Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-18T18:38:19.366Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-18T18:38:19.382Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-18T18:38:19.413Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-18T18:38:19.427Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:19.542 ThaliTest[466:381989] server session: not connected Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:19.898 ThaliTest[466:381989] client session: connected
2015-12-18 19:38:19.898 ThaliTest[466:381989] client session: stateChange:1->2 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:19.913 ThaliTest[466:381990] client session: fireConnectCallback: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:19.914 ThaliTest[466:381990] jxcore: connect: success
2015-12-18T18:38:19.915Z SendDataConnector.js: CLIENT connected to ,53064, error: null
2015-12-18T18:38:19.915Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:19.918 ThaliTest[466:381189] client: relay established
2015-12-18 19:38:19.919 ThaliTest[466:381189] client: new accepted socket: 0x183e5010
,2015-12-18T18:38:19.932Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:20.516Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:20.516Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:20.517Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:20.518Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:20.518 ThaliTest[466:381504] jxcore: disconnect
,2015-12-18 19:38:20.519 ThaliTest[466:381504] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:20.519 ThaliTest[466:381504] client session: disconnect
,2015-12-18 19:38:20.520 ThaliTest[466:381504] client session: stateChange:2->0 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:20.589 ThaliTest[466:381504] jxcore: disconnect: success
,2015-12-18T18:38:20.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9213.s950ig==
,---- round done--------
,startWithNextDevice
,2015-12-18 19:38:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:39:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:39:15.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:39:15.852 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:39:15.852 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:39:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:39:45.848 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:39:45.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:39:45.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:40:15.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:40:15.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:15.848 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:40:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:40:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:40:45.849 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:40:45.850 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:41:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:41:15.847 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:41:15.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:41:15.850 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:41:45.808 ThaliTest[466:381189] multipeer session: restart
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2015-12-18 19:42:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:42:15.841 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:42:15.841 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:42:15.842 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:42:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:42:45.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:42:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:42:45.849 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,appEnteringBackground wasn't registered
,2015-12-18 19:43:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:43:15.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:43:15.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:43:15.849 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,Connected to the server!
,2015-12-18 19:43:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:43:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:43:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:43:45.849 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:44:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:44:15.849 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:44:15.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:44:15.850 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:44:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:44:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:44:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:44:45.851 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:45:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:45:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:45:45.843 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:45:45.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:45:45.846 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:46:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:46:15.843 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:46:15.848 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:46:15.848 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:46:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:47:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:47:15.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:47:15.850 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:47:15.851 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:47:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:47:45.846 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:47:45.850 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:47:45.852 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:48:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:48:15.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:48:15.850 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:48:15.851 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:48:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:48:45.847 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:48:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:48:45.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:15.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:49:15.846 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:49:15.848 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:49:15.849 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:49:45.808 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:49:45.845 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:49:45.846 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:45.851 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:50:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:50:15.794 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:50:15.800 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:50:15.801 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:50:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:50:45.797 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:50:45.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:50:45.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:51:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:51:15.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:51:15.801 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:51:15.801 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:51:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:51:45.797 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:51:45.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:51:45.798 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:52:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:52:15.794 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:52:15.795 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:52:15.796 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:52:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:53:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:53:15.794 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:53:15.795 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:53:15.797 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:53:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:53:45.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:53:45.802 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:53:45.803 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:54:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:54:15.796 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:54:15.797 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:54:15.798 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:54:45.757 ThaliTest[466:381189] multipeer session: restart
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:54:48.878Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:55:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:55:15.796 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:55:15.796 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:55:15.798 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:55:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:55:45.795 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:55:45.800 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:55:45.801 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:56:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:56:15.797 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:56:15.797 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:56:15.805 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:56:45.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:56:45.795 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:56:45.799 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:56:45.799 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:57:15.757 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:57:15.796 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:57:15.798 ThaliTest[466:381189] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:57:15.800 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:57:45.757 ThaliTest[466:381189] multipeer session: restart
,teardown
,testSendData stopped
,2015-12-18 19:58:10.110 ThaliTest[466:381504] jxcore: stopBroadcasting
2015-12-18 19:58:10.110 ThaliTest[466:381504] THEMultipeerSession stopping peer
2015-12-18 19:58:10.111 ThaliTest[466:381504] multipeer session: stop timer
2015-12-18 19:58:10.111 Th,aliTest[466:381504] server session: disconnect
2015-12-18 19:58:10.111 ThaliTest[466:381504] server session: stateChange:2->0 Apple-IpadAir2-1_PT9191
2015-12-18 19:58:10.117 ThaliTest[466:381504] server session: disconnect
2015-12-18 19:58:10.118 ThaliTest[466:381504] server session: stateChange:2->0 Apple-Iphone5s-1_PT9213
,2015-12-18 19:58:10.133 ThaliTest[466:381504] server session: disconnect
2015-12-18 19:58:10.133 ThaliTest[466:381504] server session: stateChange:2->0 Apple-Iphone5-1_PT3434
,2015-12-18 19:58:10.153 ThaliTest[466:381504] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T18:58:10.174Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-18T18:58:10.175Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:10.179Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:10.181Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 19:58:10.228 ThaliTest[466:381504] jxcore: startBroadcasting
,2015-12-18 19:58:10.240 ThaliTest[466:381504] server: starting Apple-Iphone6-1_PT6353.kxqUHA==
,2015-12-18 19:58:10.242 ThaliTest[466:381504] multipeer session: start timer: 0x1843d500
,2015-12-18 19:58:10.246 ThaliTest[466:381504] THEMultipeerSession initialized peer Apple-Iphone6-1_PT6353
,2015-12-18 19:58:10.249 ThaliTest[466:381504] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 19:58:10.584 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:58:10.586 ThaliTest[466:381189] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:58:10.587 ThaliTest[466:381189] client: fou,nd peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1_PT9213.s950ig==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-18 19:58:11.253 ThaliTest[466:381189] client: lost peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:58:11.253 ThaliTest[466:381189] client session: onPeerLost: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:58:11.620 ThaliTest[466:381189] client: lost peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:58:11.620 ThaliTest[466:381189] client session: onPeerLost: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:58:11.621 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:58:40.247 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:58:40.265 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:58:40.267 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:59:10.247 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:59:10.260 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:59:10.260 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:59:40.247 ThaliTest[466:381189] multipeer session: restart
,2015-12-18 19:59:40.265 ThaliTest[466:381189] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:59:40.267 ThaliTest[466:381189] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 20:00:10.247 ThaliTest[466:381189] multipeer session: restart

```
