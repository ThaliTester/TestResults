#### Test 50650278bcecc5c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DBE68695-DBDD-47B0-9F34-A14D9BBB9A00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DBE68695-DBDD-47B0-9F34-A14D9BBB9A00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38A7C3A1-2E13-4423-A21A-385D78899495/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60245"
,(lldb)     command script import "/tmp/DBE68695-DBDD-47B0-9F34-A14D9BBB9A00/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 18:51:12.173 ThaliTest[471:370593] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5E031281-2E81-4275-B61A-6156C6B8C9DE/Library/Cookies/Cookies.binarycookies
,2015-12-18 18:51:12.559 ThaliTest[471:370593] Apache Cordova native platform version 3.9.2 is starting.
2015-12-18 18:51:12.560 ThaliTest[471:370593] Multi-tasking -> Device: YES, App: YES
,2015-12-18 18:51:12.571 ThaliTest[471:370593] Unlimited access to network resources
,2015-12-18 18:51:12.583 ThaliTest[471:370593] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 18:51:20.561 ThaliTest[471:370593] Resetting plugins due to page load.
,2015-12-18 18:51:23.462 ThaliTest[471:370593] Finished load of: file:///var/mobile/Containers/Bundle/Application/38A7C3A1-2E13-4423-A21A-385D78899495/ThaliTest.app/www/index.html
,2015-12-18 18:51:23.662 ThaliTest[471:370593] JXcore Cordova plugin initializing
2015-12-18 18:51:23.665 ThaliTest[471:370881] JXcore instance initializing
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
,2015-12-18 18:51:24.989 ThaliTest[471:370593] THREAD WARNING: ['JXcore'] took '90.036865' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51373
,2015-12-18 18:56:26.617 ThaliTest[471:370881] jxcore: startBroadcasting
,2015-12-18 18:56:26.637 ThaliTest[471:370881] server: starting Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:26.639 ThaliTest[471:370881] multipeer session: start timer: 0x193a63e0
2015-12-18 18:56:26.640 ThaliTest[471:370881] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT7811
2015-12-18 18:56:26.640 ThaliTest[471:370881] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-18T17:56:26.645Z SendDataTCPServer.js: TCP/IP server is bound to port: 51373
,2015-12-18 18:56:27.393 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.401Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.404Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.404Z SendDataConnector.js: do connect now
,2015-12-18 18:56:27.406 ThaliTest[471:370881] jxcore: connect Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:27.407 ThaliTest[471:370881] client session: connect
2015-12-18 18:56:27.407 ThaliTest[471:370881] client session: stateChange:0->1 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:27.431 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:27.529 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:27.986 ThaliTest[471:370593] multipeer session: reset timer
2015-12-18 18:56:27.987 ThaliTest[471:370593] multipeer session: stop timer
2015-12-18 18:56:27.987 ThaliTest[471:370593] multipeer session: start timer: 0x193a63e0
2015-12-18 ,18:56:27.988 ThaliTest[471:370593] server session: connect
,2015-12-18 18:56:27.988 ThaliTest[471:370593] server session: stateChange:0->1 Apple-Iphone6-1_PT892
,2015-12-18 18:56:28.001 ThaliTest[471:370593] server: accepting invitation Apple-Iphone6-1_PT892
,2015-12-18 18:56:30.897 ThaliTest[471:371654] server session: connected
2015-12-18 18:56:30.897 ThaliTest[471:371654] server session: stateChange:1->2 Apple-Iphone6-1_PT892
,2015-12-18 18:56:30.959 ThaliTest[471:370593] server relay: connected (to port: 51373)
,2015-12-18T17:56:30.969Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:31.399Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T17:56:31.417Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T17:56:31.437Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-18T17:56:31.456Z SendDataTCPServer.js: TCP/IP server has received 67748 bytes of data
,2015-12-18T17:56:31.481Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T17:56:31.502Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:31.565 ThaliTest[471:371665] server session: not connected Apple-Iphone6-1_PT892
,2015-12-18 18:56:32.126 ThaliTest[471:370593] multipeer session: reset timer
2015-12-18 18:56:32.126 ThaliTest[471:370593] multipeer session: stop timer
2015-12-18 18:56:32.126 ThaliTest[471:370593] multipeer session: start timer: 0x193a63e0
2015-12-18 ,18:56:32.127 ThaliTest[471:370593] server session: connect
2015-12-18 18:56:32.127 ThaliTest[471:370593] server session: stateChange:0->1 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:32.138 ThaliTest[471:370593] server: accepting invitation Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:33.501 ThaliTest[471:371655] client session: connected
2015-12-18 18:56:33.502 ThaliTest[471:371655] client session: stateChange:1->2 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:33.520 ThaliTest[471:371659] client session: fireConnectCallback: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:33.521 ThaliTest[471:371659] jxcore: connect: success
,2015-12-18T17:56:33.523Z SendDataConnector.js: CLIENT connected to 51377, error: null
2015-12-18T17:56:33.524Z SendDataConnector.js: CLIENT starting client 
2015-12-18 18:56:33.528 ThaliTest[471:370593] client: relay established
,2015-12-18 18:56:33.530 ThaliTest[471:370593] client: new accepted socket: 0x193c0ca0
,2015-12-18T17:56:33.543Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:34.102Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:34.103Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:34.104Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:34.104Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:34.105 ThaliTest[471:370881] jxcore: disconnect
2015-12-18 18:56:34.106 ThaliTest[471:370881] client session: disconnectFromPeer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:34.106 ThaliTest[471:370881] client session: disconnect
2015-12-18 18:56:34.106 ThaliTest[471:370881] client session: stateChange:2->0 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:34.111 ThaliTest[471:370881] jxcore: disconnect: success
2015-12-18T17:56:34.113Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT892.v2mOqA==
---- round done--------
startWithNextDevice
device[2]: Apple-,Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:34.114Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:34.114Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:34,.114Z SendDataConnector.js: do connect now
,2015-12-18 18:56:34.114 ThaliTest[471:370881] jxcore: connect Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:56:34.116 ThaliTest[471:370881] client session: connect
2015-12-18 18:56:34.116 ThaliTest[471:370881] client session: stateChange:0->1 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:34.783 ThaliTest[471:371654] server session: connected
2015-12-18 18:56:34.783 ThaliTest[471:371654] server session: stateChange:1->2 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:34.970 ThaliTest[471:370593] server relay: connected (to port: 51373)
2015-12-18T17:56:34.972Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:35.248Z SendDataTCPServer.js: TCP/IP server has received 23806 bytes of data
,2015-12-18T17:56:35.265Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-18T17:56:35.283Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-18T17:56:35.301Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-18T17:56:35.320Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:35.452 ThaliTest[471:371665] server session: not connected Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:36.835 ThaliTest[471:370593] multipeer session: reset timer
2015-12-18 18:56:36.836 ThaliTest[471:370593] multipeer session: stop timer
2015-12-18 18:56:36.836 ThaliTest[471:370593] multipeer session: start timer: 0x193a63e0
,2015-12-18 18:56:36.836 ThaliTest[471:370593] server session: connect
,2015-12-18 18:56:36.838 ThaliTest[471:370593] server session: stateChange:0->1 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:36.849 ThaliTest[471:370593] server: accepting invitation Apple-Iphone5-1_PT4784
,2015-12-18 18:56:37.044 ThaliTest[471:371654] client session: connected
,2015-12-18 18:56:37.045 ThaliTest[471:371654] client session: stateChange:1->2 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:37.079 ThaliTest[471:371655] client session: fireConnectCallback: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:37.080 ThaliTest[471:371655] jxcore: connect: success
,2015-12-18T17:56:37.081Z SendDataConnector.js: CLIENT connected to 51381, error: null
,2015-12-18T17:56:37.081Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:37.083 ThaliTest[471:370593] client: relay established
2015-12-18 18:56:37.083 ThaliTest[471:370593] client: new accepted socket: 0x193c00c0
,2015-12-18T17:56:37.096Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:37.365Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T17:56:37.379Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T17:56:37.490Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:37.492Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-18T17:56:37.492Z SendDataConnector.js: CLIENT Stop now
2015-12-18T17:56:37.492Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:37.494 ThaliTest[471:370881] jxcore: disconnect
,2015-12-18 18:56:37.495 ThaliTest[471:370881] client session: disconnectFromPeer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:37.496 ThaliTest[471:370881] client session: disconnect
,2015-12-18 18:56:37.496 ThaliTest[471:370881] client session: stateChange:2->0 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:37.565 ThaliTest[471:370881] jxcore: disconnect: success
,2015-12-18T17:56:37.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4784.tBG+yQ==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:37.567Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:37.567Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:37.568Z SendDataConnector.js: do connect now
,2015-12-18 18:56:37.568 ThaliTest[471:370881] jxcore: connect Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:37.569 ThaliTest[471:370881] client session: connect
,2015-12-18 18:56:37.569 ThaliTest[471:370881] client session: stateChange:0->1 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:39.725 ThaliTest[471:371654] server session: connected
,2015-12-18 18:56:39.725 ThaliTest[471:371654] server session: stateChange:1->2 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:39.754 ThaliTest[471:370593] server relay: connected (to port: 51373)
,2015-12-18T17:56:39.761Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:40.320Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T17:56:40.340Z SendDataTCPServer.js: TCP/IP server has received 51484 bytes of data
,2015-12-18T17:56:40.359Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-18T17:56:40.376Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T17:56:40.388Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:40.452 ThaliTest[471:371713] client session: connected
2015-12-18 18:56:40.453 ThaliTest[471:371713] client session: stateChange:1->2 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:40.460 ThaliTest[471:371665] server session: not connected Apple-Iphone5-1_PT4784
,2015-12-18 18:56:40.510 ThaliTest[471:371665] client session: fireConnectCallback: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:40.511 ThaliTest[471:371665] jxcore: connect: success
2015-12-18T17:56:40.512Z SendDataConnector.js: CLIENT connected to ,51385, error: null
2015-12-18T17:56:40.513Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:40.516 ThaliTest[471:370593] client: relay established
2015-12-18 18:56:40.517 ThaliTest[471:370593] client: new accepted socket: 0x19443560
,2015-12-18T17:56:40.529Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:40.831Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T17:56:40.881Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:40.881Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:40.882Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:40.882Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:40.883 ThaliTest[471:370881] jxcore: disconnect
,2015-12-18 18:56:40.883 ThaliTest[471:370881] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:40.884 ThaliTest[471:370881] client session: disconnect
,2015-12-18 18:56:40.884 ThaliTest[471:370881] client session: stateChange:2->0 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:40.952 ThaliTest[471:370881] jxcore: disconnect: success
,2015-12-18T17:56:40.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9737.0QrSBA==
,---- round done--------
,startWithNextDevice
,2015-12-18 18:57:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:57:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:57:36.893 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:57:36.893 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:57:36.894 ThaliTest[471:370593] client: foun,d peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:58:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:58:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:58:36.884 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:58:37.663 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:58:37.663 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:59:06.838 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:59:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 18:59:37.707 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:59:37.707 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:59:37.708 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:00:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:00:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:00:36.890 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:00:36.891 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:00:36.892 ThaliTest[471:370593] client: foun,d peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:01:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:01:06.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:01:07.768 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:01:07.768 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:01:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:01:36.893 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:01:37.712 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:01:37.712 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:02:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:02:06.886 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:02:07.528 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:02:07.528 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:02:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:03:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:03:06.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:03:07.504 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:07.505 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:03:28.941 ThaliTest[471:370593] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:03:28.942 ThaliTest[471:370593] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:03:28.943 ThaliTest[471:370593] clien,t: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:28.943 ThaliTest[471:370593] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","pe,erAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:03:32.810 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:03:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:03:36.880 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:03:37.879 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:03:56.292 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 19:04:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:04:06.888 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:04:07.687 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:04:07.687 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:04:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:04:36.890 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:04:37.703 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:04:37.704 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:05:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:05:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:05:36.892 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:05:37.845 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:05:37.845 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:06:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:06:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:06:36.890 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:06:37.598 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:06:37.598 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:07:06.838 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:07:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:07:36.887 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:07:36.888 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:07:36.888 ThaliTest[471:370593] client: foun,d peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:08:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:08:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:08:36.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:08:37.695 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:08:37.695 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:09:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:09:06.888 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:09:07.503 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:09:07.504 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:09:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:09:36.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:09:37.448 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:09:37.449 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:10:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:10:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:10:36.886 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:10:37.661 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:10:37.662 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:11:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:11:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:11:36.886 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:11:37.484 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:11:37.485 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:12:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:12:07.410 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:12:07.507 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:12:07.507 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:12:36.837 ThaliTest[471:370593] multipeer session: restart
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:13:06.655Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:13:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:13:06.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:13:07.571 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:13:07.571 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:13:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:13:36.886 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:13:37.542 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:13:37.543 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:14:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:14:06.897 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:14:06.901 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:14:06.905 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:14:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:15:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:15:06.889 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:15:07.666 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:15:07.666 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:15:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:16:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:16:06.890 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:16:07.508 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:07.508 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:16:28.396 ThaliTest[471:370593] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:28.397 ThaliTest[471:370593] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:28.398 ThaliTest[471:370593] clien,t: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:16:28.399 ThaliTest[471:370593] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","pe,erAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:16:28.435 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
2015-12-18 19:16:28.436 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir,2-1_PT9737.STphng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.B3pdeg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
startWithNextDevice
,2015-12-18 19:16:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:16:36.891 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:16:36.891 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:16:36.893 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:17:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:17:06.890 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:17:06.891 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:17:06.900 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:17:36.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:18:06.837 ThaliTest[471:370593] multipeer session: restart
,2015-12-18 19:18:06.887 ThaliTest[471:370593] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:18:06.888 ThaliTest[471:370593] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:18:06.890 ThaliTest[471:370593] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:18:36.837 ThaliTest[471:370593] multipeer session: restart

```
